# AMS1117x Linear Voltage Regulator

1A Low Dropout Linear Regulator with fixed 5.0V output for Arduino power supply.

## Usage

```starlark
AMS1117x = Module("//reference/AMS1117x/AMS1117x.zen")

AMS1117x(
    name = "REG_5V",
    add_led_indicator = True,     # Optional power LED
    VIN = Power("VIN"),           # 7-12V input (6.5-15V absolute max)
    VOUT = Power("5V"),           # Regulated 5V output
    GND = Ground("GND"),
)
```

## Features

- **AMS1117-5.0**: Fixed 5.0V output, 1A maximum current
- **Dropout**: 1.3V @ 1A load
- **Input Range**: 6.5V to 15V (7-12V recommended for Arduino)
- **Package**: SOT-223 with thermal tab
- **Protection**: Thermal shutdown, current limiting
- **Capacitors**: 10µF input + 22µF output for stability
- **Optional**: Power indicator LED

## Notes

- Minimum input voltage: 6.3V (5V + 1.3V dropout)
- Recommended input: 7-12V for proper thermal margin
- Output capacitor must be low-ESR (ceramic preferred)
- Tab pin must be soldered to ground plane for heat dissipation
- Maximum power dissipation: P = (VIN - VOUT) × IOUT
  - Example: (12V - 5V) × 1A = 7W (requires heatsinking!)
- For currents >500mA, ensure adequate copper area for cooling
- Input bypass capacitors should be placed close to VIN pin
- Optional LED draws ~3mA @ 5V
