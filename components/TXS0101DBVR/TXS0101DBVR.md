# TXS0101 1-Bit Bidirectional Level-Shifting, Voltage-Level Translator With Auto-Direction-Sensing for Open-Drain and Push-Pull Applications 

## 1 Features

- Latch-up performance exceeds 100 mA per JESD 78, class II
- ESD protection exceeds JESD 22:
- A Port:
- 2500V Human-Body Model (A114-B)
- 200V Machine Model (A115-A)
- 1500V Charged-Device Model (C101)
- B port:
- 8kV Human-Body Model (A114-B)
- 200V Machine Model (A115-A)
- 1500V Charged-Device Model (C101)
- No direction-control signal needed
- Maximum data rates:
- 24 Mbps (push pull)
- 2Mbps (open drain)
- Available in the Texas Instruments NanoFree ${ }^{\text {TM }}$ package
- 1.65 V to 3.6 V on A port and 2.3 V to 5.5 V on B port $\left(V_{C C A} \leq V_{C C B}\right)$
- $\mathrm{V}_{\mathrm{CC}}$ isolation feature - if either $\mathrm{V}_{\mathrm{CC}}$ input is at GND, both ports are in the high-impedance state
- No power-supply sequencing required - either $\mathrm{V}_{\mathrm{CCA}}$ or $\mathrm{V}_{\mathrm{CCB}}$ can be ramped first
- $\mathrm{I}_{\text {off }}$ supports partial-power-down mode operation


## 2 Applications

- Handsets
- Smartphones
- Tablets
- Desktop PCs


## 3 Description

This one-bit non-inverting translator uses two separate configurable power-supply rails. The A port is designed to track $\mathrm{V}_{\mathrm{CCA}} . \mathrm{V}_{\mathrm{CCA}}$ accepts any supply voltage from 1.65 V to $3.6 \mathrm{~V} . \mathrm{V}_{\mathrm{CCA}}$ must be less than or equal to $\mathrm{V}_{\mathrm{CCB}}$. The B port is designed to track $\mathrm{V}_{\mathrm{CCB}}$. $\mathrm{V}_{\mathrm{CCB}}$ accepts any supply voltage from 2.3 V to 5.5 V . This allows for low voltage bidirectional translation between any of the $1.8 \mathrm{~V}, 2.5 \mathrm{~V}, 3.3 \mathrm{~V}$, and 5 V voltage nodes.

When the output-enable (OE) input is low, all outputs are placed in the high-impedance state.

To put the device in the high-impedance state during power up or power down, tie OE to GND through a pull-down resistor; the current-sourcing capability of the driver determines the minimum value of the resistor.

Package Information

| PART NUMBER | PACKAGE ${ }^{(1)}$ | PACKAGE SIZE ${ }^{(2)}$ |
| :-- | :-- | :-- |
|  | DBV (SOT-23, 6) | $2.9 \mathrm{~mm} \times 2.8 \mathrm{~mm}$ |
| TXS0101 | DCK (SC70, 6) | $2 \mathrm{~mm} \times 2.1 \mathrm{~mm}$ |
|  | DRL (SOT-5X3, 6) | $1.6 \mathrm{~mm} \times 1.6 \mathrm{~mm}$ |
|  | DRY (SON, 6) | $1.45 \mathrm{~mm} \times 1 \mathrm{~mm}$ |

(1) For more information, see Section 11.
(2) The package size (length $\times$ width) is a nominal value and includes pins, where applicable.
![img-0.jpeg](img-0.jpeg)

Typical Operating Circuit# Table of Contents 

1 Features ..... 1
2 Applications ..... 1
3 Description ..... 1
4 Pin Configuration and Functions ..... 3
5 Specifications ..... 4
5.1 Absolute Maximum Ratings ..... 4
5.2 ESD Ratings ..... 4
5.3 Recommended Operating Conditions ..... 4
5.4 Thermal Information ..... 5
5.5 Electrical Characteristics ..... 5
5.6 Switching Characteristics, $\mathrm{V}_{\mathrm{CCA}}=1.8 \pm 0.15 \mathrm{~V}$ ..... 6
5.7 Switching Characteristics, $\mathrm{V}_{\mathrm{CCA}}=2.5 \pm 0.2 \mathrm{~V}$ ..... 6
5.8 Switching Characteristics, $\mathrm{V}_{\mathrm{CCA}}=3.3 \pm 0.3 \mathrm{~V}$ ..... 7
5.9 Switching Characteristics: $\mathrm{T}_{\text {sk }}, \mathrm{T}_{\text {MAX }}$ ..... 8
5.10 Typical Characteristics ..... 9
6 Parameter Measurement Information ..... 10
6.1 Load Circuits ..... 10
6.2 Voltage Waveforms ..... 11
7 Detailed Description ..... 12
7.1 Overview ..... 12
7.2 Functional Block Diagram ..... 12
7.3 Feature Description ..... 13
7.4 Device Functional Modes ..... 13
8 Application and Implementation ..... 14
8.1 Application Information ..... 14
8.2 Typical Application ..... 14
8.3 Power Supply Recommendations ..... 15
8.4 Layout ..... 16
9 Device and Documentation Support ..... 17
9.1 Device Support ..... 17
9.2 Receiving Notification of Documentation Updates ..... 17
9.3 Support Resources ..... 17
9.4 Trademarks ..... 17
9.5 Electrostatic Discharge Caution ..... 17
9.6 Glossary ..... 17
10 Revision History ..... 17
11 Mechanical, Packaging, and Orderable Information ..... 18# 4 Pin Configuration and Functions 

![img-1.jpeg](img-1.jpeg)

Figure 4-1. DRY Package
![img-2.jpeg](img-2.jpeg)

Figure 4-2. DBV, DCK, and DRL Package
Table 4-1. Pin Functions

| PIN |  | TYPE $^{(1)}$ | DESCRIPTION |
| :--: | :--: | :--: | :--: |
| NAME | DBV, DCK, DRL, DRY |  |  |
| A | 3 | I/O | Input/output A. Referenced to $\mathrm{V}_{\mathrm{CCA}}$ |
| B | 4 | I/O | Input/output B. Referenced to $\mathrm{V}_{\mathrm{CCB}}$ |
| GND | 2 | G | Ground |
| OE | 5 | I | Output enable. Pull OE low to place all outputs in 3-state mode. Referenced to $\mathrm{V}_{\mathrm{CCA}}$. |
| $\mathrm{V}_{\text {CCA }}$ | 1 | I | A-port supply voltage. $1.65 \mathrm{~V} \leq \mathrm{V}_{\mathrm{CCA}} \leq 3.6 \mathrm{~V}$ and $\mathrm{V}_{\mathrm{CCA}} \leq \mathrm{V}_{\mathrm{CCB}}$ |
| $\mathrm{V}_{\text {CCB }}$ | 6 | I | B-port supply voltage. $2.3 \mathrm{~V} \leq \mathrm{V}_{\mathrm{CCB}} \leq 5.5 \mathrm{~V}$ |

(1) $\mathrm{I}=$ input, $\mathrm{O}=$ output, $\mathrm{G}=$ ground# 5 Specifications 

### 5.1 Absolute Maximum Ratings

over operating free-air temperature range (unless otherwise noted) ${ }^{(1)}$

|  |  |  |  | MIN | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{V}_{\mathrm{CCA}}$ | Supply voltage A |  |  | $-0.5$ | 4.6 | V |
| $\mathrm{V}_{\mathrm{CCB}}$ | Supply voltage B |  |  | $-0.5$ | 6.5 | V |
| $\mathrm{V}_{\mathrm{t}}$ | Input Voltage ${ }^{(2)}$ |  | I/O Ports (A Port) | $-0.5$ | 4.6 | V |
| $V_{t}$ | Input Voltage ${ }^{(2)}$ |  | I/O Ports (B Port), OE | $-0.5$ | 6.5 |  |
| $V_{O}$ | Voltage applied to any output in the high-impedance or power-off state ${ }^{(2)}$ |  | A Port | $-0.5$ | 4.6 | V |
|  |  |  | B Port | $-0.5$ | 6.5 |  |
| $V_{O}$ | Voltage applied to any output in the high or low state ${ }^{(2)(3)}$ |  | A Port | $-0.5$ | $\mathrm{V}_{\mathrm{CCA}} * 0.5$ | V |
|  |  |  | B Port | $-0.5$ | $\mathrm{V}_{\mathrm{CCB}} * 0.5$ |  |
| $I_{t K}$ | Input clamp current |  | $V_{t}<0$ |  | $-50$ | mA |
| $\mathrm{I}_{\mathrm{OK}}$ | Output clamp current |  | $V_{O}<0$ |  | $-50$ | mA |
| $\mathrm{I}_{\mathrm{O}}$ | Continuous output current |  |  |  | $\pm 50$ | mA |
|  | Continuous current through $\mathrm{V}_{\mathrm{CC}}$ or GND |  |  |  | $\pm 100$ | mA |
| $T_{j}$ | Junction Temperature |  |  |  | 150 | ${ }^{\circ} \mathrm{C}$ |
| $T_{\text {sig }}$ | Storage temperature |  |  | $-65$ | 150 | ${ }^{\circ} \mathrm{C}$ |

(1) Stresses beyond those listed under Section 5.1 may cause permanent damage to the device. These are stress ratings only, which do not imply functional operation of the device at these or any other conditions beyond those indicated under Section 5.3 Exposure beyond the limits listed in Section 5.3 may affect device reliability.
(2) The input voltage and output negative-voltage ratings may be exceeded if the input and output current ratings are observed.
(3) The output positive-voltage rating may be exceeded up to 6.5 V maximum if the output current rating is observed.

### 5.2 ESD Ratings

|  |  |  |  | VALUE | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{V}_{\text {(ESD) }}$ | Electrostatic discharge | Human body model (HBM), per ANSI/ESDA/JEDEC JS-001 ${ }^{(1)}$ | A Port | $\pm 2500$ | V |
|  |  |  | B Port | $\pm 8000$ |  |
|  |  | Charged device model (CDM), per ANSI/ESDA/JEDEC JS-002 ${ }^{(2)}$ | B Port | $\pm 1500$ |  |
|  |  |  | A Port | $\pm 200$ |  |

(1) JEDEC document JEP155 states that 500 V HBM allows safe manufacturing with a standard ESD control process.
(2) JEDEC document JEP157 states that 250 V CDM allows safe manufacturing with a standard ESD control process.

### 5.3 Recommended Operating Conditions

over operating free-air temperature range (unless otherwise noted) ${ }^{(1)}$ (2) (3)

|  |  |  | $\mathrm{V}_{\mathrm{CCA}}$ | $\mathrm{V}_{\mathrm{CCB}}$ | MIN | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{V}_{\mathrm{CCA}}$ | Supply voltage A |  |  |  | 1.65 | 3.6 | V |
| $\mathrm{V}_{\mathrm{CCB}}$ | Supply voltage B |  |  |  | 2.3 | 5.5 | V |
| $V_{t H}$ | High-level input voltage | A-port I/O's | 1.65V to 1.95 V | 2.3 V to 5.5 V | $\mathrm{V}_{\mathrm{CCI}}-0.2$ | $\mathrm{V}_{\mathrm{CCI}}$ | V |
|  |  |  | 2.3 V to 3.6 V |  | $\mathrm{V}_{\mathrm{CCI}}-0.4$ | $\mathrm{V}_{\mathrm{CCI}}$ |  |
|  |  | B-port I/O's | 1.65 V to 3.6 V |  | $\mathrm{V}_{\mathrm{CCI}}-0.4$ | $\mathrm{V}_{\mathrm{CCI}}$ | V |
|  |  | OE Input |  | 2.3 V to 5.5 V | $\mathrm{V}_{\mathrm{CCA}} \times 0.65$ | 5.5 |  |
| $V_{t L}$ | Low-level input voltage | A-port I/O's | 1.65 V to 3.6 V | 2.3 V to 5.5 V | 0 | 0.15 | V |
|  |  | B-port I/O's |  |  | 0 | 0.15 | V |
|  |  | OE Input |  |  | 0 | $\mathrm{V}_{\mathrm{CCA}} \times 0.35$ |  |
| $\Delta t / \Delta v$ | Input transition rise and fall time | A//B Port I/Os, Push-Pull Driving | 1.65 V to 3.6 V | 2.3 V to 5.5 V |  | 10 | $\mathrm{ns} / \mathrm{V}$ |
| $T_{A}$ | Operating free-air temperature |  |  |  | $-40$ | 85 | ${ }^{\circ} \mathrm{C}$ |

(1) $\mathrm{V}_{\mathrm{CCI}}$ is the $\mathrm{V}_{\mathrm{CC}}$ associated with the input port.
(2) $\mathrm{V}_{\mathrm{CCO}}$ is the $\mathrm{V}_{\mathrm{CC}}$ associated with the output port.(3) All control inputs and data I/Os of this device have weak pulldowns to ensure the line is not floating when undefined external to the device. The input leakage from these weak pulldowns is defined by the $I_{I}$ specification indicated under Section 5.5.

# 5.4 Thermal Information 

| THERMAL METRIC ${ }^{(1)}$ |  | TXS0101 |  |  |  | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | DCK | DRY | DRL | DBV |  |
|  |  | 6 PINS | 6 PINS | 6 PINS | 6 PINS |  |
| $R_{B, i A}$ | Junction-to-ambient thermal resistance | 222.9 | 277.6 | 207.5 | 195.3 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $R_{B, i C(b i p)}$ | Junction-to-case (top) thermal resistance | 157.0 | 163.1 | 108.9 | 114.5 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $R_{B, i B}$ | Junction-to-board thermal resistance | 77.4 | 158.9 | 88.5 | 76.0 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $\mathrm{Y}_{\mathrm{JT}}$ | Junction-to-top characterization parameter | 58.6 | 29.3 | 6.3 | 51.7 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $\mathrm{Y}_{\mathrm{JB}}$ | Junction-to-board characterization parameter | 77.1 | 158.2 | 88.1 | 75.7 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $R_{B, i C(b o t t o m)}$ | Junction-to-case (bottom) thermal resistance | N/A | N/A | N/A | N/A | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |

(1) For more information about traditional and new thermal metrics, see the Semiconductor and IC Package Thermal Metrics application note.

### 5.5 Electrical Characteristics

over operating free-air temperature range (unless otherwise noted) ${ }^{(1)(2)}$

| PARAMETER |  | TEST CONDITIONS | $\mathrm{V}_{\text {CCA }}$ | $\mathrm{V}_{\text {CCB }}$ | Operating free-air temperature $\left(T_{A}\right)$ |  | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  |  |  | $-40^{\circ} \mathrm{C}$ to $85^{\circ} \mathrm{C}$ |  |  |
|  |  |  |  |  | MIN TYP MAX |  |  |
| $V_{\text {OHA }}$ | Port A output high voltage ${ }^{(3)}$ | $\mathrm{I}_{\mathrm{OH}}=-20 \mathrm{uA}, \mathrm{V}_{\mathrm{IB}} \geq \mathrm{V}_{\mathrm{CCB}}-0.4 \mathrm{~V}$ | 1.65 V to 3.6 V | 2.3 V to 5.5 V | $\begin{aligned} & \mathrm{V}_{\mathrm{CCA}} \times \\ & 0.67 \end{aligned}$ |  | V |
| $V_{\text {OLA }}$ | Port A output low voltage ${ }^{(4)}$ | $\mathrm{I}_{\mathrm{OL}}=1 \mathrm{~mA}, \mathrm{~V}_{\mathrm{IB}} \leq 0.15 \mathrm{~V}$ | 1.65 V to 3.6 V | 2.3 V to 5.5 V | 0.4 |  | V |
| $V_{\text {OHB }}$ | Port B output high voltage | $\mathrm{I}_{\mathrm{OH}}=-20 \mathrm{uA}, \mathrm{V}_{\mathrm{IA}} \geq \mathrm{V}_{\mathrm{CCA}}-0.2 \mathrm{~V}$ | 1.65 V to 3.6 V | 2.3 V to 5.5 V | $\begin{aligned} & \mathrm{V}_{\mathrm{CCB}} \times \\ & 0.67 \end{aligned}$ |  | V |
| $V_{\text {OLB }}$ | Port B output low voltage ${ }^{(4)}$ | $\mathrm{I}_{\mathrm{OL}}=1 \mathrm{~mA}, \mathrm{~V}_{\mathrm{IA}} \leq 0.15 \mathrm{~V}$ | 1.65 V to 3.6 V | 1.65 V to 5.5 V | 0.4 |  | V |
| $I_{I}$ | Input leakage current | $\begin{aligned} & \mathrm{OE} \\ & \mathrm{~V}_{\mathrm{I}}=\mathrm{V}_{\mathrm{CC}} \text { or GND, } \mathrm{T}_{\mathrm{A}}=25^{\circ} \mathrm{C} \end{aligned}$ | 1.65 V to 3.6 V | 1.65 V to 5.5 V | $-1$ | 1 | $\mu \mathrm{A}$ |
| $I_{I}$ | Input leakage current | $\begin{aligned} & \mathrm{OE} \\ & \mathrm{~V}_{\mathrm{I}}=\mathrm{V}_{\mathrm{CC}} \text { or GND, }-40^{\circ} \mathrm{C}-85^{\circ} \mathrm{C} \end{aligned}$ | 1.65 V to 3.6 V | 1.65 V to 5.5 V | $-2$ | 2 | $\mu \mathrm{A}$ |
| $I_{\text {off }}$ | Partial power down current | A port | 0 V | 0 V to 5.5 V | $-2$ | 2 | $\mu \mathrm{A}$ |
|  |  | B port | 0 V to 3.6 V | 0 V | $-2$ | 2 | $\mu \mathrm{A}$ |
| $I_{O Z}$ | Tri-state output current | A or B Port: <br> $\mathrm{V}_{\mathrm{I}}=\mathrm{V}_{\mathrm{CCI}}$ or GND <br> $\mathrm{V}_{\mathrm{O}}=\mathrm{V}_{\mathrm{CCO}}$ or GND <br> OE = GND | 1.65 V to 3.6 V | 2.3 V to 5.5 V | $-2$ | 2 | $\mu \mathrm{A}$ |
| $I_{\text {CCA }}$ | $V_{\text {CCA }}$ supply current | $\begin{aligned} & \mathrm{V}_{\mathrm{I}}=\mathrm{V}_{\mathrm{CCI}} \text { or GND } \\ & \mathrm{I}_{\mathrm{O}}=0 \end{aligned}$ | 1.65 V to $\mathrm{V}_{\text {CCB }}$ | 2.3 V to 5.5 V | 2.4 |  | $\mu \mathrm{A}$ |
|  |  |  | 3.6 V | 0 V | 2.2 |  |  |
|  |  |  | 0 V | 5.5 V | $-1$ |  |  |
| $I_{\text {CCB }}$ | $V_{\text {CCB }}$ supply current | $\begin{aligned} & \mathrm{V}_{\mathrm{I}}=\mathrm{V}_{\mathrm{CCI}} \text { or GND } \\ & \mathrm{I}_{\mathrm{O}}=0 \end{aligned}$ | 1.65 V to $\mathrm{V}_{\text {CCB }}$ | 2.3 V to 5.5 V | 12 |  | $\mu \mathrm{A}$ |
|  |  |  | 3.6 V | 0 V | $-1$ |  |  |
|  |  |  | 0 V | 5.5 V | 1 |  |  |
| $\mathrm{I}_{\text {CCA }}+$ ICCB | Combined supply current | $\begin{aligned} & \mathrm{V}_{\mathrm{I}}=\mathrm{V}_{\mathrm{CCI}} \text { or GND } \\ & \mathrm{I}_{\mathrm{O}}=0 \end{aligned}$ | 1.65 V to $\mathrm{V}_{\text {CCB }}$ | 2.3 V to 5.5 V | 14.4 |  | $\mu \mathrm{A}$ |
| $\mathrm{C}_{\mathrm{i}}$ | Input Capacitance | OE | 3.3 V | 3.3 V | 3.5 |  | pF |
| $\mathrm{C}_{\text {lo }}$ | A port | $\begin{aligned} & \mathrm{T}_{\mathrm{A}}=25^{\circ} \mathrm{C} \\ & -40^{\circ} \mathrm{C}-85^{\circ} \mathrm{C} \end{aligned}$ | 3.3 V | 3.3 V | 5 |  | pF |over operating free-air temperature range (unless otherwise noted) ${ }^{(1)(2)}$

| PARAMETER |  | TEST CONDITIONS | $\mathrm{V}_{\mathrm{CCA}}$ | $\mathrm{V}_{\text {CCB }}$ | Operating free-air temperature $\left(T_{A}\right)$ |  |  |  | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  |  |  | $-40^{\circ} \mathrm{C}$ to $85^{\circ} \mathrm{C}$ |  |  |  |  |
|  |  |  |  |  |  |  | MIN | TYP | MAX |
| $\mathrm{C}_{\text {io }}$ | B port | $\begin{aligned} & \mathrm{T}_{\mathrm{A}}=25^{\circ} \mathrm{C} \\ & -40^{\circ} \mathrm{C}-85^{\circ} \mathrm{C} \end{aligned}$ | 3.3 V | 3.3 V |  | 6 |  |  | pF |
|  |  |  |  |  |  | 7.5 |  |  |  |

(1) $\mathrm{V}_{\mathrm{CCI}}$ is the $\mathrm{V}_{\mathrm{CC}}$ associated with the input port
(2) $\mathrm{V}_{\mathrm{CCO}}$ is the $\mathrm{V}_{\mathrm{CC}}$ associated with the output port
(3) Tested at $\mathrm{V}_{\mathrm{I}}=\mathrm{V}_{\mathrm{T}+(\mathrm{MAX})}$
(4) Tested at $\mathrm{V}_{\mathrm{I}}=\mathrm{V}_{\mathrm{T}-(\mathrm{MIN})}$

# 5.6 Switching Characteristics, $\mathrm{V}_{\mathrm{CCA}}=1.8 \pm 0.15 \mathrm{~V}$ 

| PARAMETER |  | FROM | TO | Test Conditions | B-Port Supply Voltage ( $\mathrm{V}_{\text {CCB }}$ ) |  |  |  |  |  | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  |  |  | $2.5 \pm 0.2 \mathrm{~V}$ |  | $3.3 \pm 0.3 \mathrm{~V}$ |  | $5.0 \pm 0.5 \mathrm{~V}$ |  |  |
|  |  |  |  |  | MIN TYP | MAX | MIN | TYP | MAX | MIN TYP | MAX |
| $t_{\text {PHL }}$ | Propagation Delay (Hight-to-Low) | A | B | Push-Pull |  | 5.3 |  | 5.4 |  | 6.8 | ns |
|  |  |  |  | Open-Drain | 2.3 | 8.8 | 2.4 | 9.6 | 2.6 | 10 |  |
| $t_{\text {PLH }}$ | Propagation Delay (Low-to-High) | A | B | Push-Pull |  | 6.8 |  | 7.1 |  | 7.5 | ns |
|  |  |  |  | Open-Drain | 45 | 260 | 36 | 208 | 27 | 198 |  |
| $t_{\text {PHL }}$ | Propagation Delay (Hight-to-Low) | B | A | Push-Pull |  | 4.4 |  | 4.5 |  | 4.7 | ns |
|  |  |  |  | Open-Drain | 1.9 | 5.3 | 1.1 | 4.4 | 1.2 | 4 |  |
| $t_{\text {PLH }}$ | Propagation Delay (Low-to-High) | B | A | Push-Pull |  | 5.3 |  | 4.5 |  | 0.5 | ns |
|  |  |  |  | Open-Drain | 45 | 175 | 36 | 140 | 27 | 102 |  |
| $t_{e n}$ | Enable Time | OE | A or B | Push-Pull |  | 200 |  | 200 |  | 200 | ns |
| $t_{\text {dis }}$ | Disable Time |  |  |  | 200 |  | 200 |  | 200 |  |  |
| $t_{1 A}$ | Ouput Rise Time | B | A | Push-Pull | 3.2 | 9.5 | 2.3 | 9.3 | 2 | 7.6 | ns |
|  |  |  |  | Open-Drain | 38 | 165 | 30 | 132 | 22 | 95 |  |
| $t_{1 B}$ | Ouput Rise Time | A | B | Push-Pull | 1.1 | 10.8 | 1 | 9.1 | 1 | 7.6 | ns |
|  |  |  |  | Open-Drain | 34 | 145 | 23 | 106 | 10 | 76 |  |
| $t_{1 A}$ | Output Fall Time | B | A | Push-Pull | 1.9 | 5.9 | 1.9 | 6 | 1.4 | 13.3 | ns |
|  |  |  |  | Open-Drain | 4.4 | 6.9 | 4.3 | 6.4 | 4.2 | 6.1 |  |
| $t_{1 B}$ | Output Fall Time | A | B | Push-Pull | 2.2 | 13.8 | 2.2 | 16.2 | 2.6 | 16.2 | ns |
|  |  |  |  | Open-Drain | 6.9 | 13.8 | 7.5 | 16.2 | 7 | 16.2 |  |

5.7 Switching Characteristics, $\mathrm{V}_{\mathrm{CCA}}=2.5 \pm 0.2 \mathrm{~V}$

| PARAMETER |  | FROM | TO | Test Conditions | B-Port Supply Voltage ( $\mathrm{V}_{\text {CCB }}$ ) |  |  |  |  |  | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  |  |  | $2.5 \pm 0.2 \mathrm{~V}$ |  | $3.3 \pm 0.3 \mathrm{~V}$ |  | $5.0 \pm 0.5 \mathrm{~V}$ |  |  |
|  |  |  |  |  | MIN TYP | MAX | MIN | TYP | MAX | MIN TYP | MAX |
| $t_{\text {PHL }}$ | Propagation Delay (Hight-to-Low) | A | B | Push-Pull |  | 3.2 |  | 3.7 |  | 3.8 | ns |
|  |  |  |  | Open-Drain | 1.7 | 6.3 | 2 | 6 | 2.1 | 5.8 |  |
| $t_{\text {PLH }}$ | Propagation Delay (Low-to-High) | A | B | Push-Pull |  | 3.5 |  | 4.1 |  | 4.4 | ns |
|  |  |  |  | Open-Drain | 43 | 250 | 36 | 206 | 27 | 190 |  |
| $t_{\text {PHL }}$ | Propagation Delay (Hight-to-Low) | B | A | Push-Pull |  | 3 |  | 3.6 |  | 4.3 | ns |
|  |  |  |  | Open-Drain | 1.8 | 4.7 | 1.6 | 4.2 | 1.2 | 4 |  |
| $t_{\text {PLH }}$ | Propagation Delay (Low-to-High) | B | A | Push-Pull |  | 2.5 |  | 1.6 |  | 1 | ns |
|  |  |  |  | Open-Drain | 44 | 170 | 37 | 140 | 27 | 103 |  |
| $t_{e n}$ | Enable Time | OE | A or B | Push-Pull |  | 200 |  | 200 |  | 200 | ns |
| $t_{\text {dis }}$ | Disable Time |  |  |  | 200 |  | 200 |  | 200 |  |  |
| $t_{1 A}$ | Ouput Rise Time | B | A | Push-Pull | 2.8 | 7.4 | 2.1 | 6.6 | 0.9 | 5.6 | ns |
|  |  |  |  | Open-Drain | 34 | 149 | 28 | 121 | 24 | 89 |  |![img-3.jpeg](img-3.jpeg)

|  | PARAMETER | FROM | TO | Test Conditions | B-Port Supply Voltage ( $\mathrm{V}_{\text {CCB }}$ ) |  |  |  |  |  | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  |  |  | $2.5 \pm 0.2 \mathrm{~V}$ |  | $3.3 \pm 0.3 \mathrm{~V}$ |  | $5.0 \pm 0.5 \mathrm{~V}$ |  |  |
|  |  |  |  |  | MIN | TYP | MAX | MIN | TYP | MAX |  |  |  |
| $t_{r B}$ | Ouput Rise Time | A | B | Push-Pull | 1.3 | 8.3 | 0.9 |  | 7.2 | 0.4 |  | 6.1 | ns |
|  |  |  |  | Open-Drain | 35 | 151 | 24 |  | 112 | 12 |  | 81 |  |
| $t_{t A}$ | Output Fall Time | B | A | Push-Pull | 1.9 | 5.7 | 1.4 |  | 5.5 | 0.8 |  | 5.3 | ns |
|  |  |  |  | Open-Drain | 4.4 | 6.9 | 4.3 |  | 6.2 | 4.2 |  | 5.8 |  |
| $t_{t B}$ | Output Fall Time | A | B | Push-Pull | 2.2 | 7.8 | 2.4 |  | 6.7 | 2.6 |  | 6.6 | ns |
|  |  |  |  | Open-Drain | 5.1 | 8.8 | 5.4 |  | 9.4 | 5.4 |  | 10.4 |  |

# 5.8 Switching Characteristics, $\mathrm{V}_{\mathrm{CCA}}=3.3 \pm 0.3 \mathrm{~V}$ 

| PARAMETER |  | FROM | TO | Test Conditions | B-Port Supply Voltage ( $\mathrm{V}_{\text {CCB }}$ ) |  |  |  |  |  | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  |  |  | $3.3 \pm 0.3 \mathrm{~V}$ |  |  | $5.0 \pm 0.5 \mathrm{~V}$ |  |  |  |
|  |  |  |  |  | MIN | TYP | MAX | MIN | TYP | MAX |  |
| $t_{\text {PHL }}$ | Propagation Delay (Hight-to-Low) | A | B | Push-Pull |  |  | 2.4 |  |  | 3.1 | ns |
|  |  |  |  | Open-Drain | 1.3 |  | 4.2 | 1.4 |  | 4.6 |  |
| $t_{\text {PLH }}$ | Propagation Delay (Low-to-High) | A | B | Push-Pull |  |  | 4.2 |  |  | 4.4 | ns |
|  |  |  |  | Open-Drain | 36 |  | 204 | 28 |  | 165 |  |
| $t_{\text {PHL }}$ | Propagation Delay (Hight-to-Low) | B | A | Push-Pull |  |  | 2.5 |  |  | 3.3 | ns |
|  |  |  |  | Open-Drain | 1 |  | 124 | 1 |  | 97 |  |
| $t_{\text {PLH }}$ | Propagation Delay (Low-to-High) | B | A | Push-Pull |  |  | 2.5 |  |  | 2.6 | ns |
|  |  |  |  | Open-Drain | 3 |  | 139 | 3 |  | 105 |  |
| $t_{\text {en }}$ | Enable Time | OE | A or B | Push-Pull |  |  | 200 |  |  | 200 | ns |
| $t_{\text {dis }}$ | Disable Time |  |  |  |  |  | 200 |  |  | 200 |  |
| $t_{r A}$ | Ouput Rise Time | B | A | Push-Pull | 2.3 |  | 5.6 | 1.9 |  | 4.8 | ns |
|  |  |  |  | Open-Drain | 25 |  | 116 | 19 |  | 85 |  |
| $t_{r B}$ | Ouput Rise Time | A | B | Push-Pull | 1.6 |  | 6.4 | 0.6 |  | 7.4 | ns |
|  |  |  |  | Open-Drain | 26 |  | 116 | 14 |  | 72 |  |
| $t_{t A}$ | Output Fall Time | B | A | Push-Pull | 1.4 |  | 5.4 | 1 |  | 5 | ns |
|  |  |  |  | Open-Drain | 4.3 |  | 6.1 | 4.2 |  | 5.7 |  |
| $t_{t B}$ | Output Fall Time | A | B | Push-Pull | 2.3 |  | 7.4 | 2.4 |  | 7.6 | ns |
|  |  |  |  | Open-Drain | 5 |  | 7.6 | 4.8 |  | 8.3 |  |# 5.9 Switching Characteristics: $\mathrm{T}_{\mathrm{sk}}, \mathrm{T}_{\text {MAX }}$ 

over operating free-air temperature range (unless otherwise noted)

| PARAMETER | TEST CONDITIONS |  | $\mathrm{V}_{\text {CCA }}$ | $V_{\text {CCB }}$ | Operating free-air temperature $\left(T_{A}\right)$ |  | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  |  |  | $-40^{\circ} \mathrm{C}$ to $125^{\circ} \mathrm{C}$ |  |  |
|  |  |  |  |  | MIN | TYP | MAX |
| $\mathrm{T}_{\text {MAX }}$ - Maximum Data Rate | 50\% Duty Cycle Input One channel switching | Push-Pull Driving | $1.8 \pm 0.15 \mathrm{~V}$ | $2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 21 |  | Mbps |
|  |  |  |  | $3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 22 |  |
|  |  |  |  | $5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 24 |  |
|  |  |  | $2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | $2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 20 |  |
|  |  |  |  | $3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 22 |  |
|  |  |  |  | $5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 24 |  |
|  |  |  | $3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | $3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 23 |  |
|  |  |  |  | $5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 24 |  |
|  |  | Open-Drain Driving | $1.8 \pm 0.15 \mathrm{~V}$ | $2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 2 |  |
|  |  |  |  | $3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 2 |  |
|  |  |  |  | $5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 2 |  |
|  |  |  | $2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | $2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 2 |  |
|  |  |  |  | $3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 2 |  |
|  |  |  |  | $5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 1 |  |
|  |  |  | $3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | $3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 2 |  |
|  |  |  |  | $5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 2 |  |
| $t_{w}$ | Pulse Duration, Data Inputs | Push-Pull Driving | $\begin{aligned} & 1.8 \mathrm{~V} \pm 0.15 \mathrm{~V} \\ & \text { to } \\ & 3.3 \mathrm{~V} \pm 0.3 \mathrm{~V} \end{aligned}$ | $\begin{aligned} & 2.5 \mathrm{~V} \pm 0.2 \mathrm{~V} \\ & \text { to } \\ & 5.5 \mathrm{~V} \pm 0.5 \mathrm{~V} \end{aligned}$ | 41 | ns |
|  |  | Open-Drain Driving | $\begin{aligned} & 1.8 \mathrm{~V} \pm 0.15 \mathrm{~V} \\ & \text { to } \\ & 3.3 \mathrm{~V} \pm 0.3 \mathrm{~V} \end{aligned}$ | $\begin{aligned} & 2.5 \mathrm{~V} \pm 0.2 \mathrm{~V} \\ & \text { to } \\ & 5.5 \mathrm{~V} \pm 0.5 \mathrm{~V} \end{aligned}$ | 500 |  |# 5.10 Typical Characteristics 

![img-4.jpeg](img-4.jpeg)

Figure 5-1. Low-Level Output Voltage ( $\mathrm{V}_{\mathrm{OL}(\mathrm{Bx})}$ ) vs Low-Level Current ( $\left.\mathrm{I}_{\mathrm{OL}(\mathrm{Bx})}\right)$
![img-5.jpeg](img-5.jpeg)

Figure 5-2. Low-Level Output Voltage ( $\mathrm{V}_{\mathrm{OL}(\mathrm{Bx})}$ ) vs Low-Level Current ( $\left.\mathrm{I}_{\mathrm{OL}(\mathrm{Bx})}\right)$
![img-6.jpeg](img-6.jpeg)

Figure 5-3. Low-Level Output Voltage ( $\mathrm{V}_{\mathrm{OL}(\mathrm{Bx})}$ ) vs Low-Level Current ( $\left.\mathrm{I}_{\mathrm{OL}(\mathrm{Bx})}\right)$# 6 Parameter Measurement Information 

### 6.1 Load Circuits

Figure 6-1 shows the push-pull driver circuit used for measuring data rate, pulse duration, propagation delay, output rise-time and fall-time. Figure 6-2 shows the open-drain driver circuit used for measuring data rate, pulse duration, propagation delay, output rise-time and fall-time.
![img-7.jpeg](img-7.jpeg)

Figure 6-1. Data Rate, Pulse Duration, Propagation Delay, Output Rise-Time and Fall-Time Measurement Using a Push-Pull Driver
![img-8.jpeg](img-8.jpeg)

Figure 6-2. Data Rate, Pulse Duration, Propagation Delay, Output Rise-Time and Fall-Time Measurement Using an Open-Drain Driver
![img-9.jpeg](img-9.jpeg)

Figure 6-3. Load Circuit for Enable-Time and Disable-Time Measurement

| TEST | S1 |
| :--: | :--: |
| $\begin{aligned} & \mathrm{t}_{\mathrm{PZL}} / \mathrm{t}_{\mathrm{PLZ}} \\ & \left(\mathrm{t}_{\mathrm{dis}}\right) \end{aligned}$ | $2 \times \mathrm{V}_{\mathrm{CCO}}$ |
| $\begin{aligned} & \mathrm{t}_{\mathrm{PHZ}} / \mathrm{t}_{\mathrm{PZH}} \\ & \left(\mathrm{t}_{\mathrm{en}}\right) \end{aligned}$ | Open |

1. $t_{P L Z}$ and $t_{P H Z}$ are the same as $t_{d i s}$.
2. $t_{P Z L}$ and $t_{P Z H}$ are the same as $t_{e n}$.
3. $\mathrm{V}_{\mathrm{CCI}}$ is the $\mathrm{V}_{\mathrm{CC}}$ associated with the input port.
4. $\mathrm{V}_{\mathrm{CCO}}$ is the $\mathrm{V}_{\mathrm{CC}}$ associated with the output port.# 6.2 Voltage Waveforms 

![img-10.jpeg](img-10.jpeg)

Figure 6-4. Pulse Duration (Push-Pull)
![img-11.jpeg](img-11.jpeg)

Figure 6-5. Propagation Delay Times
![img-12.jpeg](img-12.jpeg)

- $C_{L}$ includes probe and jig capacitance.
- Waveform 1 in Figure 6-6 is for an output with internal such that the output is high, except when OE is high (see Figure 6-3). Waveform 2 in Figure 6-6 is for an output with conditions such that the output is low, except when OE is high.
- All input pulses are supplied by generators having the following characteristics: PRR $\leq 10 \mathrm{MHz}, \mathrm{Z}_{\mathrm{O}}=50 \Omega$, dv/dt $\geq 1 \mathrm{~V} / \mathrm{ns}$.
- The outputs are measured one at a time, with one transition per measurement.
- $t_{P L Z}$ and $t_{P H Z}$ are the same as $t_{d i s}$.
- $t_{P Z L}$ and $t_{P Z H}$ are the same as $t_{e n}$.
- $t_{P L H}$ and $t_{P H L}$ are the same as $t_{p d}$.
- $\mathrm{V}_{\mathrm{CCI}}$ is the $\mathrm{V}_{\mathrm{CC}}$ associated with the input port.
- $\mathrm{V}_{\mathrm{CCO}}$ is the $\mathrm{V}_{\mathrm{CC}}$ associated with the output port.

Figure 6-6. Enable and Disable Times# 7 Detailed Description 

### 7.1 Overview

The TXS0101 device is a directionless voltage-level translator specifically designed for translating logic voltage levels. The A port can accept I/O voltages ranging from 1.65 V to 3.6 V , while the B port can accept I/O voltages from 2.3 V to 5.5 V . The device is a pass gate architecture with edge rate accelerators (one shots) to improve the overall data rate. $10 \mathrm{k} \Omega$ pullup resistors, commonly used in open drain applications, have been conveniently integrated so that an external resistor is not needed. While this device is designed for open drain applications, the device can also translate push-pull CMOS logic outputs.

### 7.2 Functional Block Diagram

![img-13.jpeg](img-13.jpeg)# 7.3 Feature Description 

### 7.3.1 Architecture

As shown in Figure 7-1, the TXS0101 architecture does not require a direction-control signal to control the direction of data flow from $A$ to $B$ or from $B$ to $A$.
![img-14.jpeg](img-14.jpeg)

Figure 7-1. Architecture of a TXS01xx Cell
Each A-port I/O has an internal $10 \mathrm{k} \Omega$ pullup resistor to $\mathrm{V}_{\mathrm{CCA}}$, and each B-port I/O has an internal $10 \mathrm{k} \Omega$ pullup resistor to $\mathrm{V}_{\mathrm{CCB}}$. The output one-shots detect rising edges on the A or B ports. During a rising edge, the one-shot turns on the PMOS transistors (T1 and T2) for a short duration, which speeds up the low-to-high transition.

### 7.3.2 Input Driver Requirements

The fall time ( $t_{f A}$ and $t_{f B}$ ) of a signal depends on the output impedance of the external device driving the data I/Os of the TXS0101. Similarly, the $\mathrm{t}_{\mathrm{PHL}}$ and maximum data rates also depend on the output impedance of the external driver. The values for $t_{f A}, t_{f B}, t_{P H L}$, and maximum data rates in the data sheet assume that the output impedance of the external driver is less than $50 \Omega$.

### 7.3.3 Power Up

During operation, ensure that $\mathrm{V}_{\mathrm{CCA}} \leq \mathrm{V}_{\mathrm{CCB}}$ at all times. During power-up sequencing, $\mathrm{V}_{\mathrm{CCA}} \geq \mathrm{V}_{\mathrm{CCB}}$ does not damage the device, so any power supply can be ramped up first.

### 7.3.4 Enable and Disable

The TXS0101 has an OE input that is used to disable the device by setting OE low, which places all I/Os in the Hi-Z state. The disable time ( $\mathrm{t}_{\text {dis }}$ ) indicates the delay between the time when OE goes low and when the outputs actually get disabled (Hi-Z). The enable time ( $t_{\text {en }}$ ) indicates the amount of time the user must allow for the one-shot circuitry to become operational after OE is taken high.

### 7.3.5 Pullup or Pulldown Resistors on I/O Lines

Each A-port I/O has an internal $10 \mathrm{k} \Omega$ pullup resistor to $\mathrm{V}_{\mathrm{CCA}}$, and each B-port I/O has an internal $10 \mathrm{k} \Omega$ pullup resistor to $\mathrm{V}_{\mathrm{CCB}}$. If a smaller value of pullup resistor is required, an external resistor must be added from the I/O to $\mathrm{V}_{\mathrm{CCA}}$ or $\mathrm{V}_{\mathrm{CCB}}$ (in parallel with the internal $10 \mathrm{k} \Omega$ resistors).

### 7.4 Device Functional Modes

The TXS0101 device has two functional modes, enabled and disabled. To disable the device set the OE input low, which places all I/Os in a high impedance state. Setting the OE input high will enable the device.# 8 Application and Implementation 

## Note

Information in the following applications sections is not part of the TI component specification, and TI does not warrant its accuracy or completeness. TI's customers are responsible for determining suitability of components for their purposes, as well as validating and testing their design implementation to confirm system functionality.

### 8.1 Application Information

The TXS0101 can be used in level-translation applications for interfacing devices or systems operating at different interface voltages with one another. The TXS0101 is an excellent choice for use in applications where an open-drain driver is connected to the data I/Os. The TXS0101 can also be used in applications where a push-pull driver is connected to the data I/Os, but the TXB0102 might be a better option for such push-pull applications.

### 8.2 Typical Application

![img-15.jpeg](img-15.jpeg)

Figure 8-1. Typical Application Schematic

### 8.2.1 Design Requirements

For this design example, use the parameters listed in Table 8-1.
Table 8-1. Design Parameters

| DESIGN PARAMETER | EXAMPLE VALUE |
| :--: | :--: |
| Input voltage range | 1.65 to 3.6 V |
| Output voltage range | 2.3 to 5.5 V |

### 8.2.2 Detailed Design Procedure

To begin the design process, determine the following:

- Input voltage range:
- Use the supply voltage of the device that is driving the TXS0101 device to determine the input voltage range. For a valid logic high the value must exceed the $\mathrm{V}_{\mathrm{IN}}$ of the input port. For a valid logic low the value must be less than the $\mathrm{V}_{\mathrm{IL}}$ of the input port.
- Output voltage range:
- Use the supply voltage of the device that the TXS0101 device is driving to determine the output voltage range.
- The TXS0101 device has $10 \mathrm{k} \Omega$ internal pullup resistors. External pullup resistors can be added to reduce the total RC of a signal trace if necessary.- An external pull down resistor decreases the output $\mathrm{V}_{\mathrm{OH}}$ and $\mathrm{V}_{\mathrm{OL}}$. Use Equation 1 to calculate the $\mathrm{V}_{\mathrm{OH}}$ as a result of an external pull down resistor.

$$
V_{O H}=V_{C C x} \times R_{P D} /\left(R_{P D}+10 k \Omega\right)
$$

where

- $\mathrm{V}_{\mathrm{CCx}}$ is the supply voltage on either $\mathrm{V}_{\mathrm{CCA}}$ or $\mathrm{V}_{\mathrm{CCB}}$
- $R_{P D}$ is the value of the external pull down resistor


# 8.2.3 Application Curve 

![img-16.jpeg](img-16.jpeg)

Figure 8-2. Level-Translation of a 2.5 MHz Signal

### 8.3 Power Supply Recommendations

The TXS0101 device uses two separate configurable power-supply rails, $\mathrm{V}_{\mathrm{CCA}}$ and $\mathrm{V}_{\mathrm{CCB}}$. $\mathrm{V}_{\mathrm{CCB}}$ accepts any supply voltage from 2.3 V to 5.5 V and $\mathrm{V}_{\mathrm{CCA}}$ accepts any supply voltage from 1.65 V to 3.6 V . The A port and B port are designed to track $\mathrm{V}_{\mathrm{CCA}}$ and $\mathrm{V}_{\mathrm{CCB}}$ respectively allowing for low voltage bidirectional translation between any of the $1.8 \mathrm{~V}, 2.5 \mathrm{~V}, 3.3 \mathrm{~V}$, and 5 V voltage nodes.

The TXS0101 device does not require power sequencing between $\mathrm{V}_{\mathrm{CCA}}$ and $\mathrm{V}_{\mathrm{CCB}}$ during power-up so the powersupply rails can be ramped in any order. A $\mathrm{V}_{\mathrm{CCA}}$ value greater than or equal to $\mathrm{V}_{\mathrm{CCB}}\left(\mathrm{V}_{\mathrm{CCA}} \geq \mathrm{V}_{\mathrm{CCB}}\right)$ does not damage the device, but during operation, $\mathrm{V}_{\mathrm{CCA}}$ must be less than or equal to $\mathrm{V}_{\mathrm{CCB}}\left(\mathrm{V}_{\mathrm{CCA}} \leq \mathrm{V}_{\mathrm{CCB}}\right)$ at all times.

The output-enable (OE) input circuit is designed so that it is supplied by $\mathrm{V}_{\mathrm{CCA}}$ and when the (OE) input is low, all outputs are placed in the high-impedance state. To put the outputs in the high-impedance state during power up or power down, the OE input pin must be tied to GND through a pulldown resistor and must not be enabled until $\mathrm{V}_{\mathrm{CCA}}$ and $\mathrm{V}_{\mathrm{CCB}}$ are fully ramped and stable. The current-sourcing capability of the driver determines the minimum value of the pulldown resistor to ground.# 8.4 Layout 

### 8.4.1 Layout Guidelines

For device reliability, TI recommends following common printed-circuit board layout guidelines such as follows:

- Bypass capacitors should be used on power supplies.
- Short trace lengths should be used to avoid excessive loading.
- PCB signal trace-lengths must be kept short enough so that the round-trip delay of any reflection is less than the one shot duration, approximately 30 ns , causing any reflection to encounter low impedance at the source driver.
- Placing pads on the signal paths for loading capacitors or pullup resistors to help adjust rise and fall times of signals depending on the system requirements


### 8.4.2 Layout Example

![img-17.jpeg](img-17.jpeg)
![img-18.jpeg](img-18.jpeg)

Figure 8-3. Typical Layout of TXS0101# 9 Device and Documentation Support 

### 9.1 Device Support

### 9.1.1 Related Documentation

For related documentation, see the following:

- Texas Instruments, A Guide to Voltage Translation With TXS-Type Translators
- Texas Instruments, Introduction to Logic


### 9.2 Receiving Notification of Documentation Updates

To receive notification of documentation updates, navigate to the device product folder on ti.com. Click on Notifications to register and receive a weekly digest of any product information that has changed. For change details, review the revision history included in any revised document.

### 9.3 Support Resources

TI E2E ${ }^{\text {TM }}$ support forums are an engineer's go-to source for fast, verified answers and design help - straight from the experts. Search existing answers or ask your own question to get the quick design help you need.
Linked content is provided "AS IS" by the respective contributors. They do not constitute TI specifications and do not necessarily reflect TI's views; see TI's Terms of Use.

### 9.4 Trademarks

NanoFree ${ }^{\text {TM }}$ and TI E2E ${ }^{\text {TM }}$ are trademarks of Texas Instruments.
All trademarks are the property of their respective owners.

### 9.5 Electrostatic Discharge Caution

This integrated circuit can be damaged by ESD. Texas Instruments recommends that all integrated circuits be handled with appropriate precautions. Failure to observe proper handling and installation procedures can cause damage.
ESD damage can range from subtle performance degradation to complete device failure. Precision integrated circuits may be more susceptible to damage because very small parametric changes could cause the device not to meet its published specifications.

### 9.6 Glossary

TI Glossary This glossary lists and explains terms, acronyms, and definitions.

## 10 Revision History

NOTE: Page numbers for previous revisions may differ from page numbers in the current version.
Changes from Revision E (October 2024) to Revision F (Sep 2025)
Page

- Updated disable times (max conditions)................................................................................................................ 6
- Updated disable times (max conditions)................................................................................................................ 6
- Updated disable times (max conditions)................................................................................................................ 7

Changes from Revision D (June 2017) to Revision E (October 2024)
Page

- Added DRY pinout diagram............................................................................................................................... 3

Changes from Revision C (December 2015) to Revision D (June 2017)
Page

- Changed YZP package pinout diagram with new image and added YZP pin assignments in Pin Functions table............................................................................................................................................................................ 3# 11 Mechanical, Packaging, and Orderable Information 

The following pages include mechanical, packaging, and orderable information. This information is the most current data available for the designated devices. This data is subject to change without notice and revision of this document. For browser-based versions of this data sheet, refer to the left-hand navigation.# PACKAGE OPTION ADDENDUM

|  PACKAGE OPTION ADDENDUM |  |  |  |  |  |  |  |  |   |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |   |   |   |   |   |   |   |   |   |
|  |# PACKAGE OPTION ADDENDUM 

(2) Material type: When designated, preproduction parts are prototypes/experimental devices, and are not yet approved or released for full production. Testing and final process, including without limitation quality assurance, reliability performance testing, and/or process qualification, may not yet be complete, and this item is subject to further changes or possible discontinuation. If available for ordering, purchases will be subject to an additional waiver at checkout, and are intended for early internal evaluation purposes only. These items are sold without warranties of any kind.
${ }^{(3)}$ RoHS values: Yes, No, RoHS Exempt. See the TI RoHS Statement for additional information and value definition.
${ }^{(4)}$ Lead finish/Ball material: Parts may have multiple material finish options. Finish options are separated by a vertical ruled line. Lead finish/Ball material values may wrap to two lines if the finish value exceeds the maximum column width.
${ }^{(5)}$ MSL rating/Peak reflow: The moisture sensitivity level ratings and peak solder (reflow) temperatures. In the event that a part has multiple moisture sensitivity ratings, only the lowest level per JEDEC standards is shown. Refer to the shipping label for the actual reflow temperature that will be used to mount the part to the printed circuit board.
${ }^{(6)}$ Part marking: There may be an additional marking, which relates to the logo, the lot trace code information, or the environmental category of the part.

Multiple part markings will be inside parentheses. Only one part marking contained in parentheses and separated by a "-" will appear on a part. If a line is indented then it is a continuation of the previous line and the two combined represent the entire part marking for that device.

Important Information and Disclaimer:The information provided on this page represents TI's knowledge and belief as of the date that it is provided. TI bases its knowledge and belief on information provided by third parties, and makes no representation or warranty as to the accuracy of such information. Efforts are underway to better integrate information from third parties. TI has taken and continues to take reasonable steps to provide representative and accurate information but may not have conducted destructive testing or chemical analysis on incoming materials and chemicals. TI and TI suppliers consider certain information to be proprietary, and thus CAS numbers and other limited information may not be available for release.

In no event shall TI's liability arising out of such information exceed the total purchase price of the TI part(s) at issue in this document sold by TI to Customer on an annual basis.

## OTHER QUALIFIED VERSIONS OF TX50101 :

- Automotive : TX50101-Q1

NOTE: Qualified Version Definitions:

- Automotive - Q100 devices qualified for high-reliability automotive applications targeting zero defects# TAPE AND REEL INFORMATION 

![img-19.jpeg](img-19.jpeg)

TAPE DIMENSIONS
![img-20.jpeg](img-20.jpeg)

| A0 | Dimension designed to accommodate the component width |
| :-- | :-- |
| B0 | Dimension designed to accommodate the component length |
| K0 | Dimension designed to accommodate the component thickness |
| W | Overall width of the carrier tape |
| P1 | Pitch between successive cavity centers |

QUADRANT ASSIGNMENTS FOR PIN 1 ORIENTATION IN TAPE
![img-21.jpeg](img-21.jpeg)
*All dimensions are nominal

| Device | Package <br> Type | Package <br> Drawing | Pins | SPQ | Reel <br> Diameter <br> (mm) | Reel <br> Width <br> W1 (mm) | A0 <br> (mm) | B0 <br> (mm) | K0 <br> (mm) | P1 <br> (mm) | W <br> (mm) | Pin1 <br> Quadrant |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| TXS0101DBVR | SOT-23 | DBV | 6 | 3000 | 180.0 | 8.4 | 3.2 | 3.2 | 1.4 | 4.0 | 8.0 | Q3 |
| TXS0101DBVR | SOT-23 | DBV | 6 | 3000 | 180.0 | 8.4 | 3.23 | 3.17 | 1.37 | 4.0 | 8.0 | Q3 |
| TXS0101DBVT | SOT-23 | DBV | 6 | 250 | 180.0 | 8.4 | 3.23 | 3.17 | 1.37 | 4.0 | 8.0 | Q3 |
| TXS0101DBVTG4 | SOT-23 | DBV | 6 | 250 | 180.0 | 8.4 | 3.23 | 3.17 | 1.37 | 4.0 | 8.0 | Q3 |
| TXS0101DCKR | SC70 | DCK | 6 | 3000 | 180.0 | 8.4 | 2.3 | 2.5 | 1.2 | 4.0 | 8.0 | Q3 |
| TXS0101DCKR | SC70 | DCK | 6 | 3000 | 179.0 | 8.4 | 2.2 | 2.5 | 1.2 | 4.0 | 8.0 | Q3 |
| TXS0101DCKT | SC70 | DCK | 6 | 250 | 179.0 | 8.4 | 2.2 | 2.5 | 1.2 | 4.0 | 8.0 | Q3 |
| TXS0101DRLR | SOT-5X3 | DRL | 6 | 4000 | 180.0 | 8.4 | 1.98 | 1.78 | 0.69 | 4.0 | 8.0 | Q3 |
| TXS0101DRYR | SON | DRY | 6 | 5000 | 180.0 | 8.4 | 1.2 | 1.65 | 0.63 | 4.0 | 8.0 | Q1 |
| TXS0101YZPR | DSBGA | YZP | 6 | 3000 | 178.0 | 9.2 | 1.02 | 1.52 | 0.63 | 4.0 | 8.0 | Q1 |# PACKAGE MATERIALS INFORMATION

## TAPE AND REEL BOX DIMENSIONS

![img-22.jpeg](img-22.jpeg)

*All dimensions are nominal

|  Device | Package Type | Package Drawing | Pins | SPQ | Length (mm) | Width (mm) | Height (mm)  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  TXS0101DBVR | SOT-23 | DBV | 6 | 3000 | 210.0 | 185.0 | 35.0  |
|  TXS0101DBVR | SOT-23 | DBV | 6 | 3000 | 202.0 | 201.0 | 28.0  |
|  TXS0101DBVT | SOT-23 | DBV | 6 | 250 | 202.0 | 201.0 | 28.0  |
|  TXS0101DBVTG4 | SOT-23 | DBV | 6 | 250 | 202.0 | 201.0 | 28.0  |
|  TXS0101DCKR | SC70 | DCK | 6 | 3000 | 210.0 | 185.0 | 35.0  |
|  TXS0101DCKR | SC70 | DCK | 6 | 3000 | 200.0 | 183.0 | 25.0  |
|  TXS0101DCKT | SC70 | DCK | 6 | 250 | 200.0 | 183.0 | 25.0  |
|  TXS0101DRLR | SOT-5X3 | DRL | 6 | 4000 | 202.0 | 201.0 | 28.0  |
|  TXS0101DRYR | SON | DRY | 6 | 5000 | 210.0 | 185.0 | 35.0  |
|  TXS0101YZPR | DSBGA | YZP | 6 | 3000 | 220.0 | 220.0 | 35.0  |![img-23.jpeg](img-23.jpeg)

NOTES:

1. All linear dimensions are in millimeters. Any dimensions in parenthesis are for reference only. Dimensioning and tolerancing per ASME Y14.5M.
2. This drawing is subject to change without notice.
3. This dimension does not include mold flash, protrusions, or gate burrs. Mold flash, protrusions, or gate burrs shall not exceed 0.15 mm per side.
4. Reference JEDEC registration MO-293 Variation UAAD![img-24.jpeg](img-24.jpeg)

NOTES: (continued)
5. Publication IPC-7351 may have alternate designs.
6. Solder mask tolerances between and around signal pads can vary based on board fabrication site.
7. Land pattern design aligns to IPC-610, Bottom Termination Component (BTC) solder joint inspection criteria.![img-25.jpeg](img-25.jpeg)

NOTES: (continued)
8. Laser cutting apertures with trapezoidal walls and rounded corners may offer better paste release. IPC-7525 may have alternate design recommendations.
9. Board assembly site may have different recommendations for stencil design.![img-26.jpeg](img-26.jpeg)

NOTES:

1. All linear dimensions are in millimeters. Any dimensions in parenthesis are for reference only. Dimensioning and tolerancing per ASME Y14.5M.
2. This drawing is subject to change without notice.
3. Body dimensions do not include mold flash or protrusion. Mold flash and protrusion shall not exceed 0.25 per side.
4. Leads $1,2,3$ may be wider than leads $4,5,6$ for package orientation.
5. Reference JEDEC MO-178.![img-27.jpeg](img-27.jpeg)

NOTES: (continued)
6. Publication IPC-7351 may have alternate designs.
7. Solder mask tolerances between and around signal pads can vary based on board fabrication site.![img-28.jpeg](img-28.jpeg)

NOTES: (continued)
8. Laser cutting apertures with trapezoidal walls and rounded corners may offer better paste release. IPC-7525 may have alternate design recommendations.
9. Board assembly site may have different recommendations for stencil design.![img-29.jpeg](img-29.jpeg)

NOTES:
NanoFree Is a trademark of Texas Instruments.

1. All linear dimensions are in millimeters. Any dimensions in parenthesis are for reference only. Dimensioning and tolerancing per ASME Y14.5M.
2. This drawing is subject to change without notice.
3. NanoFree ${ }^{\text {TM }}$ package configuration.![img-30.jpeg](img-30.jpeg)

NOTES: (continued)
4. Final dimensions may vary due to manufacturing tolerance considerations and also routing constraints. For more information, see Texas Instruments literature number SBVA017 (www.ti.com/lit/sbva017).![img-31.jpeg](img-31.jpeg)

NOTES: (continued)
5. Laser cutting apertures with trapezoidal walls and rounded corners may offer better paste release.![img-32.jpeg](img-32.jpeg)

NOTES:

1. All linear dimensions are in millimeters. Any dimensions in parenthesis are for reference only. Dimensioning and tolerancing per ASME Y14.5M.
2. This drawing is subject to change without notice.
3. Body dimensions do not include mold flash or protrusion. Mold flash and protrusion shall not exceed 0.15 per side.
4. Falls within JEDEC MO-203 variation $A B$.![img-33.jpeg](img-33.jpeg)

NOTES: (continued)
5. Publication IPC-7351 may have alternate designs.
6. Solder mask tolerances between and around signal pads can vary based on board fabrication site.![img-34.jpeg](img-34.jpeg)

NOTES: (continued)
7. Laser cutting apertures with trapezoidal walls and rounded corners may offer better paste release. IPC-7525 may have alternate design recommendations.
8. Board assembly site may have different recommendations for stencil design.Images above are just a representation of the package family, actual package may vary. Refer to the product data sheet for package details.# IMPORTANT NOTICE AND DISCLAIMER 

TI PROVIDES TECHNICAL AND RELIABILITY DATA (INCLUDING DATA SHEETS), DESIGN RESOURCES (INCLUDING REFERENCE DESIGNS), APPLICATION OR OTHER DESIGN ADVICE, WEB TOOLS, SAFETY INFORMATION, AND OTHER RESOURCES "AS IS" AND WITH ALL FAULTS, AND DISCLAIMS ALL WARRANTIES, EXPRESS AND IMPLIED, INCLUDING WITHOUT LIMITATION ANY IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE OR NON-INFRINGEMENT OF THIRD PARTY INTELLECTUAL PROPERTY RIGHTS.
These resources are intended for skilled developers designing with TI products. You are solely responsible for (1) selecting the appropriate TI products for your application, (2) designing, validating and testing your application, and (3) ensuring your application meets applicable standards, and any other safety, security, regulatory or other requirements.
These resources are subject to change without notice. TI grants you permission to use these resources only for development of an application that uses the TI products described in the resource. Other reproduction and display of these resources is prohibited. No license is granted to any other TI intellectual property right or to any third party intellectual property right. TI disclaims responsibility for, and you will fully indemnify TI and its representatives against, any claims, damages, costs, losses, and liabilities arising out of your use of these resources.
TI's products are provided subject to TI's Terms of Sale or other applicable terms available either on ti.com or provided in conjunction with such TI products. TI's provision of these resources does not expand or otherwise alter TI's applicable warranties or warranty disclaimers for TI products.
TI objects to and rejects any additional or different terms you may have proposed.
Mailing Address: Texas Instruments, Post Office Box 655303, Dallas, Texas 75265
Copyright © 2025, Texas Instruments Incorporated