# FT232RLx USB to Serial Converter

FTDI USB to UART bridge IC with two package options for high-quality serial communication and Arduino programming.

## Usage

```starlark
FT232RLx = Module("//reference/FT232RLx/FT232RLx.zen")

FT232RLx(
    name = "usb_serial",
    package = "FT231XQ",              # "FT231XQ" (4×4mm) or "FT232RL" (10×5mm)
    add_tx_rx_leds = True,            # Optional TX/RX indicator LEDs
    add_ferrite_bead = True,          # Optional EMI filtering on USB power
    VCC = Power("VCC"),               # 5V power supply (4.35-5.25V)
    VCCIO = Power("3V3"),             # I/O voltage (3.3V or 5V)
    USB_VCC = Power("USB_5V"),        # USB VBUS
    GND = Ground("GND"),
    USB = usb_connector,              # USB 2.0 D+/D- differential pair
    UART = mcu_uart,                  # UART interface to microcontroller
    DTR = reset_signal,               # DTR output for Arduino auto-reset
    RTS = rts_signal,                 # RTS output (optional)
    CTS = cts_signal,                 # CTS input (optional)
    CBUS0 = tx_led,                   # CBUS0/TXLED
    CBUS1 = rx_led,                   # CBUS1/RXLED
    # CBUS2-4 available as GPIO
)
```

## Package Options

### FT231XQ - Compact (Default)
- **Package**: QFN-20 (4mm × 4mm)
- **Best for**: Space-constrained designs, Arduino Nano
- **Features**: 4 CBUS pins, all essential Arduino features
- **Cost**: Lower than FT232RL

### FT232RL - Full Featured
- **Package**: SSOP-28 (10mm × 5mm)  
- **Best for**: Designs needing extra GPIO or legacy compatibility
- **Features**: 5 CBUS pins, more configuration options
- **Cost**: Higher than FT231XQ

## Features

- **USB 2.0**: Full speed (12Mbps) with built-in termination
- **UART**: Up to 3Mbps baud rate with hardware flow control
- **Oscillator**: Internal oscillator (no external crystal needed)
- **Regulator**: Built-in 3.3V regulator (50mA max on 3V3OUT pin)
- **VCCIO**: Configurable I/O voltage (3.3V or 5V logic levels)
- **Signals**: DTR, RTS, CTS for Arduino auto-reset and flow control
- **CBUS**: Configurable pins (TXLED, RXLED, GPIO, etc.)
- **EEPROM**: Internal EEPROM for USB descriptors
- **Drivers**: Native support in most operating systems

## Arduino Auto-Reset

Connect DTR through 100nF capacitor to ATmega328P reset pin:

```starlark
Capacitor(
    name = "C_AUTORESET",
    value = "100nF",
    package = "0402",
    P1 = usb_serial.DTR,
    P2 = mcu.RESET,
)
```

## VCCIO Configuration

The VCCIO pin sets the I/O voltage level:
- **5V I/O**: Connect VCCIO to VCC (5V)
- **3.3V I/O**: Connect VCCIO to 3.3V rail

This allows voltage translation between USB (5V) and 3.3V microcontrollers.

## CBUS Pins

CBUS pins can be configured via EEPROM (using FT_PROG utility):
- **CBUS0**: TXLED (default) - Blinks when transmitting
- **CBUS1**: RXLED (default) - Blinks when receiving
- **CBUS2-3**: GPIO, PWM, Clock output, etc.
- **CBUS4**: GPIO (FT232RL only)

## Notes

- **FT231XQ advantages**: Smaller (4×4mm), lower cost, adequate for Arduino
- **FT232RL advantages**: More CBUS pins, easier hand soldering (SSOP vs QFN)
- No external crystal required (internal oscillator)
- USB series resistors (27Ω) for signal integrity
- Optional ferrite bead on USB power for EMI filtering
- 3V3OUT provides max 50mA for external use
- Superior signal quality compared to CH340
- Requires FTDI drivers (usually pre-installed)
- EEPROM can store custom VID/PID and device name
- DTR/RTS are active-low signals
