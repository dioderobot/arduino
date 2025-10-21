# SKRKAHE020x Tactile Switch

Low-profile SMD tactile switch for reset buttons and user input.

## Usage

```starlark
SKRKAHE020x = Module("//reference/SKRKAHE020x/SKRKAHE020x.zen")

SKRKAHE020x(
    name = "SW_RESET",
    P1 = signal_net,              # Connect to signal (e.g., RESET)
    P2 = Ground("GND"),           # Connect to ground
)
```

## Features

- **SKRKAHE020**: ALPS Electric tactile switch
- **Package**: 4.2mm x 3.5mm x 2.0mm SMD
- **Force**: 260gf operating force
- **Rating**: 50mA @ 12V DC
- **Type**: SPST-NO (normally open)
- **Life**: 100,000 cycles minimum
- **Travel**: 0.2mm
- **Compact**: Low-profile design for space-constrained boards

## Notes

- Typically used for reset buttons on microcontroller boards
- Connect one pin to signal, other pin to ground
- When pressed, connects P1 to P2
- No additional components required
- Can be used with internal or external pull-up resistors

