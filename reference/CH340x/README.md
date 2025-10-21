# CH340x USB to Serial Converter

USB to UART bridge IC for serial communication and Arduino programming.

## Usage

```starlark
CH340x = Module("//reference/CH340x/CH340x.zen")

CH340x(
    name = "usb_serial",
    add_tx_rx_leds = True,        # Optional TX/RX indicator LEDs
    VCC = Power("VCC"),           # 5V power supply
    USB_VCC = Power("USB_5V"),    # USB VBUS (can be same as VCC)
    GND = Ground("GND"),
    USB = usb_connector,          # USB 2.0 D+/D- differential pair
    UART = mcu_uart,              # UART interface to microcontroller
    DTR = reset_signal,           # DTR output for Arduino auto-reset
    RTS = rts_signal,             # RTS output (optional)
)
```

## Features

- **CH340G**: SOP-16 package USB to UART bridge
- **USB 2.0**: Full speed (12Mbps) with built-in termination
- **UART**: Up to 2Mbps baud rate
- **Clock**: 12MHz crystal oscillator
- **Regulator**: Built-in 3.3V regulator (V3 pin)
- **Signals**: DTR and RTS for Arduino auto-reset programming
- **Power**: 3.3V or 5V operation
- **Optional**: TX/RX indicator LEDs

## Arduino Auto-Reset

Connect DTR through 100nF capacitor to ATmega328P reset pin:

```starlark
# In your board design:
Capacitor(
    name = "C_AUTORESET",
    value = "100nF",
    package = "0402",
    P1 = usb_serial.DTR,
    P2 = mcu.RESET,
)
```

## Notes

- 12MHz crystal with 22pF load capacitors
- Built-in USB pull-up resistors (no external required)
- V3 pin provides 3.3V output for internal use
- R232 pin pulled high through 1kΩ resistor
- Compatible with Arduino IDE and avrdude
- Lower cost alternative to FTDI FT232RL
- Requires CH340 drivers (built into modern OS)
- TX/RX LEDs optional, add ~4mA current draw
- DTR/RTS are active-low signals
