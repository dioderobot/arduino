# ATmega328Px Microcontroller

8-bit AVR microcontroller with 32KB Flash, 16MHz crystal, and Arduino bootloader compatibility.

## Usage

```starlark
ATmega328Px = Module("//reference/ATmega328Px/ATmega328Px.zen")

ATmega328Px(
    name = "mcu",
    VCC = Power("VCC"),           # 1.8V to 5.5V power supply
    GND = Ground("GND"),          # Ground
    UART = uart_interface,        # UART for serial communication
    SPI = spi_interface,          # SPI interface (CLK, MISO, MOSI, CS)
    I2C = i2c_interface,          # I2C interface (SDA, SCL)
    # Digital pins (optional)
    D2 = gpio_pin,
    D3 = pwm_pin,                 # PWM capable
    # ... D4 through D13
    # Analog pins (optional)
    A0 = adc_pin0,
    A1 = adc_pin1,
    # ... A2 through A7
)
```

## Features

- **ATmega328P-AU**: TQFP-32 package, 32KB Flash, 2KB SRAM, 1KB EEPROM
- **Clock**: 16MHz crystal with 22pF load capacitors
- **GPIO**: 23 programmable I/O pins
- **PWM**: 6 channels (D3, D5, D6, D9, D10, D11)
- **ADC**: 8 channels, 10-bit resolution
- **Interfaces**: UART, SPI, I2C
- **Power**: Complete decoupling with 100nF capacitors
- **Reset**: 10kΩ pull-up resistor, optional reset button

## Notes

- Crystal oscillator uses 22pF load capacitors for 18pF crystal
- AREF pin available as optional IO (can connect to external voltage reference)
- Reset pin pulled high through 10kΩ resistor
- Arduino bootloader compatible
- Operating voltage: 4.5-5.5V @ 16MHz (per datasheet)
- All power pins properly decoupled
