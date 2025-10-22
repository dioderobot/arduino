# LMR514x0, 36-V, 4-A/5-A Synchronous Step-Down DC/DC Converter With Low I ${ }_{\mathrm{Q}}$ 

## 1 Features

- Functional Safety-Capable
- Documentation available to aid functional safety system design
- Configured for rugged industrial applications
- Wide Input voltage range: 4 V to 36 V
- 4-A or 5-A continuous output current
- $\pm 1.0 \%$ tolerance voltage reference at room temperature
- Minimum switching-on time: 75 ns (typical)
- Low Quiescent current: $25 \mu \mathrm{~A}$
- Adjustable Frequency: 200 kHz to 1.1 MHz
- Frequency spread spectrum (PFM variant)
- Protection features
- Precision enable input
- Open-drain PGOOD
- $\mathrm{V}_{\mathrm{IN}}$ undervoltage lockout (UVLO)
- Cycle-by-cycle current limiting
- Short-circuit protection with hiccup mode
- Thermal shutdown
- Low dropout mode operation
- Junction temperature range: $-40^{\circ} \mathrm{C}$ to $150^{\circ} \mathrm{C}$
- Small solution size and ease of use
- Integrated synchronous rectification
- Internal compensation for ease of use
- WSON-12 package
- Various options in pin-to-pin compatible package
- PFM and forced PWM (FPWM) options
- Create a custom design using the LMR5144x0 with the WEBENCH ${ }^{\circledR}$ Power Designer


## 2 Applications

- Major appliances
- PLC, DCS, and PAC
- Test and measurement instrumentation
- Power delivery
![img-0.jpeg](img-0.jpeg)

Simplified Schematic

## 3 Description

The LMR514x0 is a wide- $\mathrm{V}_{\mathrm{IN}}$, easy-to-use synchronous buck converter capable of driving up to 4-A or 5-A load current. With a wide input range of 4 V to 36 V , the device is suitable for a wide range of industrial applications for power conditioning from an unregulated source.

The LMR514x0 features adjustable switching frequency from 200 kHz to 1.1 MHz with an external resistor, which provides the flexibility to optimize either efficiency or external component size. The device has PFM version to realize high efficiency at light load and FPWM version to achieve constant frequency, and small output voltage ripple over the full load range. Soft-start and compensation circuits are implemented internally which allows the device to be used with minimum external components.

The device has built-in protection features, such as cycle-by-cycle current limit, hiccup mode short-circuit protection, and thermal shutdown in case of excessive power dissipation. The LMR514x0 is available in WSON-12 package.

Device Information

| PART NUMBER | Current $^{(1)}$ | PACKAGE ${ }^{(2)}$ | BODY SIZE <br> (NOM) |
| :--: | :--: | :--: | :--: |
| LMR51440 | 4 A | DRR <br> (WSON, 12) | $\begin{gathered} 3.00 \mathrm{~mm} \times 3.00 \\ \mathrm{~mm} \end{gathered}$ |

(1) See the Device Comparison Table.
(2) For all available packages, see the orderable addendum at the end of the data sheet.
![img-1.jpeg](img-1.jpeg)

Efficiency vs Output Current $\mathrm{V}_{\text {OUT }}=\mathbf{5} \mathrm{V}, \mathbf{5 0 0} \mathbf{~ k H z}$# Table of Contents 

1 Features ..... 1
2 Applications ..... 1
3 Description ..... 1
4 Revision History ..... 2
5 Device Comparison Table ..... 3
6 Pin Configuration and Functions ..... 3
7 Specifications ..... 4
7.1 Absolute Maximum Ratings ..... 4
ESD Ratings ..... 4
7.2 Recommended Operating Conditions ..... 4
7.3 Thermal Information ..... 5
7.4 Electrical Characteristics ..... 5
7.5 System Characteristics ..... 7
7.6 Typical Characteristics ..... 8
8 Detailed Description ..... 11
8.1 Overview ..... 11
8.2 Functional Block Diagram ..... 11
8.3 Feature Description ..... 12
8.4 Device Functional Modes ..... 18
9 Application and Implementation ..... 19
9.1 Application Information ..... 19
9.2 Typical Application ..... 20
9.3 Best Design Practices ..... 26
9.4 Power Supply Recommendations ..... 26
9.5 Layout ..... 26
10 Device and Documentation Support ..... 29
10.1 Device Support ..... 29
10.2 Documentation Support ..... 29
10.3 Receiving Notification of Documentation Updates ..... 29
10.4 Support Resources ..... 29
10.5 Trademarks ..... 29
10.6 Electrostatic Discharge Caution ..... 29
10.7 Glossary ..... 29
11 Mechanical, Packaging, and Orderable Information ..... 30

## 4 Revision History

NOTE: Page numbers for previous revisions may differ from page numbers in the current version.

| DATE | REVISION | NOTES |
| :--: | :--: | :--: |
| December 2022 | * | Initial release |# 5 Device Comparison Table 

| ORDERABLE PART NUMBER | Current | PFM OR FPWM | Spread Spectrum |
| :--: | :--: | :--: | :--: |
| LMR51440SDRRR | 4 A | PFM | Yes |
| LMR51450SDRRR | 5 A | PFM | Yes |
| LMR51450FNDRRR | 5 A | FPWM | No |

## 6 Pin Configuration and Functions

![img-2.jpeg](img-2.jpeg)

Figure 6-1. 12-Pin WSON DRR Package (Top View)
Table 6-1. Pin Functions

| PIN |  | TYPE ${ }^{(1)}$ | DESCRIPTION |
| :--: | :--: | :--: | :--: |
| NAME | NO |  |  |
| SW | $1,2,3$ | $P$ | Switching output of the converter. Internally connected to source of the high-side FET and drain of the low-side FET. Connect to power inductor. |
| BOOT | 4 | $P$ | Bootstrap capacitor connection for high-side FET driver. Connect a high quality 100-nF capacitor from this pin to the SW pin. |
| PG | 5 | A | Open-drain power-good monitor output that asserts low if the FB voltage is not within the specified window thresholds. A $10-\mathrm{k} \Omega$ to $100-\mathrm{k} \Omega$ pullup resistor to a suitable voltage is required. If not used, PG can be left open or connected to GND. |
| RT | 6 | A | Frequency setting pin used to set the switching frequency between 200 kHz and 1.1 MHz by placing an external resistor from RT to AGND. RT open defaults to 500 kHz and RT short to ground defaults to 1 MHz . |
| FB | 7 | A | Feedback input to the converter. Connect a resistor divider to set the output voltage. Never short this terminal to ground during operation. |
| AGND | 8 | G | Analog ground. Zero-voltage reference for internal references and logic. All electrical parameters are measured with respect to this pin. These pins must be connected to PGND using a small net-tie. |
| EN | 9 | A | Precision enable input pin. High = on, Low = off. Can be connected to VIN. Precision enable allows the pin to be used as an adjustable input voltage UVLO. Connect an external resistor divider between this pin, VIN and AGND to create an external UVLO. Do not float. |
| VIN | $10,11,12$ | $P$ | Input supply voltage. Connect the input supply to these pins. Connect input capacitors CIN between these pins and PGND in close proximity to the device. |
| PGND | 13 | G | Power ground terminals, connected to the source of low-side FET internally. Connect to system ground, ground side of CIN and COUT. Path to CIN must be as short as possible. |

(1) $\mathrm{A}=$ Analog, $\mathrm{P}=$ Power, $\mathrm{G}=$ Ground.# 7 Specifications 

### 7.1 Absolute Maximum Ratings

Over junction temperature range of $-40^{\circ} \mathrm{C}$ to $150^{\circ} \mathrm{C}$ (unless otherwise noted) ${ }^{(1)}$

|  |  | MIN | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: |
| Input voltage | VIN to PGND | $-0.3$ | 38 | V |
|  | EN to PGND | $-0.3$ | $\mathrm{V}_{\text {IN }}+0.3$ | V |
|  | FB to PGND | $-0.3$ | 5.5 | V |
|  | RT to PGND | $-0.3$ | 5.5 | V |
| Output voltage | BOOT to SW | $-0.3$ | 5.5 | V |
|  | SW to PGND | $-0.3$ | 38 | V |
|  | SW to PGND less than 10-ns transients | $-4$ | 40 | V |
|  | PG to PGND | $-0.3$ | 20 | V |
| Junction Temperature $\mathrm{T}_{\mathrm{J}}$ |  | $-40$ | 150 | ${ }^{\circ} \mathrm{C}$ |
| Storage temperature, $\mathrm{T}_{\text {stg }}$ |  | $-65$ | 150 | ${ }^{\circ} \mathrm{C}$ |

(1) Operation outside the Absolute Maximum Ratings may cause permanent device damage. Absolute Maximum Ratings do not imply functional operation of the device at these or any other conditions beyond those listed under Recommended Operating Conditions. If used outside the Recommended Operating Conditions but within the Absolute Maximum Ratings, the device may not be fully functional, and this may affect device reliability, functionality, performance, and shorten the device lifetime.

## ESD Ratings

|  |  |  | MIN | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{V}_{\text {(ESD) }}$ | Electrostatic discharge | Human body model (HBM), per ANSI/ESDA/JEDEC JS-001 ${ }^{(1)}$ | $-2000$ | 2000 | V |
|  |  | Charged device model (CDM), per ANSI/ESDA/JEDEC JS-002 ${ }^{(2)}$ | $-500$ | 500 |  |

(1) JEDEC document JEP155 states that 500-V HBM allows safe manufacturing with a standard ESD control process.
(2) JEDEC document JEP157 states that 250-V CDM allows safe manufacturing with a standard ESD control process.

### 7.2 Recommended Operating Conditions

Over the recommended operating junction temperature range of $-40^{\circ} \mathrm{C}$ to $150^{\circ} \mathrm{C}$ (unless otherwise noted) ${ }^{(1)}$

|  |  | MIN | NOM | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: |
| Input voltage | Input voltage range | 4.0 |  | 36 | V |
| Input voltage | EN to PGND |  |  | $V_{\text {IN }}$ | V |
| Input voltage | RT to PGND |  |  | 5 | V |
| Input voltage | PGOOD to PGND |  |  | 20 | V |
| Output voltage | SW to PGND |  |  | 36 | V |
| Output voltage | Output voltage range ${ }^{(2)}$ | 0.8 |  | 28 | V |
| Frequency | Frequency range | 200 |  | 1100 | kHz |
| Load current | Output DC current range, 5 A Version ${ }^{(3)}$ | 0 |  | 5 | A |
| Load current | Output DC current rang, 4 A Version ${ }^{(3)}$ | 0 |  | 4 | A |
| Temperature | Operating junction temperature $\mathrm{T}_{\mathrm{J}}$ range ${ }^{(4)}$ | $-40$ |  | 150 | ${ }^{\circ} \mathrm{C}$ |

(1) Recommended operating conditions indicate conditions for which the device is intended to be functional, but do not ensure specific performance limits. For ensured specifications, see Electrical Characteristics table.
(2) Under no conditions should the output voltage be allowed to fall below zero volts.
(3) Maximum continuous DC current may be derated when operating with high switching frequency and/or high ambient temperature. See Application section for details.
(4) High junction temperatures degrade operating lifetimes. Operating lifetime is de-rated for junction temperatures greater than $150^{\circ} \mathrm{C}$.# 7.3 Thermal Information 

| THERMAL METRIC ${ }^{(1)}$ |  | LMR514x0 |  |
| :--: | :--: | :--: | :--: |
|  |  | DRR (WSON) | UNIT |
|  |  | 12 PINS |  |
| $R_{B, i A}$ | Junction-to-ambient thermal resistance | 47.4 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $R_{B, i A(E f f e n t i v e)}$ | Junction-to-ambient thermal resistance with TI EVM board | 23 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $R_{B, i C(t i s s)}$ | Junction-to-case (top) thermal resistance | 44.6 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $R_{B, i B}$ | Junction-to-board thermal resistance | 20.7 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $\psi_{J T}$ | Junction-to-top characterization parameter | 0.7 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $\psi_{J B}$ | Junction-to-board characterization parameter | 20.7 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $R_{B, i C(t i s s)}$ | Junction-to-case (bottom) thermal resistance | 6.3 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |

(1) For more information about traditional and new thermal metrics, see the Semiconductor and IC Package Thermal Metrics application report.

### 7.4 Electrical Characteristics

Limits apply over operating junction temperature $\left(T_{J}\right)$ range of $-40^{\circ} \mathrm{C}$ to $+150^{\circ} \mathrm{C}$, unless otherwise stated. Minimum and Maximum limits ${ }^{(1)}$ are specified through test, design or statistical correlation. Typical values represent the most likely parametric norm at $T_{J}=25^{\circ} \mathrm{C}$, and are provided for reference purposes only. Unless otherwise stated, the following conditions apply: $\mathrm{V}_{\mathrm{IN}}=4 \mathrm{~V}$ to 36 V .

| PARAMETER |  | TEST CONDITIONS | MIN | TYP | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| SUPPLY VOLTAGE AND CURRENT |  |  |  |  |  |  |
| $\mathrm{I}_{\text {Q-nonSW }}$ | Operating quiescent current (nonswitching) | $\mathrm{V}_{\mathrm{EN}}=3.3 \mathrm{~V}$ (PFM variant only) | 25 |  |  | $\mu \mathrm{A}$ |
| $\mathrm{I}_{\text {SD }}$ | Shutdown quiescent current; measured at VIN pin | $\mathrm{V}_{\mathrm{EN}}=0 \mathrm{~V}, \mathrm{~V}_{\mathrm{IN}}=24 \mathrm{~V}$ | 3 |  | 6 | $\mu \mathrm{A}$ |
| $\mathrm{V}_{\text {IN_OPERATE }}$ | VIN UVLO threshold | $\mathrm{V}_{\text {IN }}$ rising, Needed to start up |  |  | 3.9 | V |
|  |  | $\mathrm{V}_{\text {IN }}$ falling, Once operating | 3.4 |  |  | V |
| ENABLE |  |  |  |  |  |  |
| $\mathrm{V}_{\mathrm{EN}-\mathrm{H}}$ | Enable input high level | EN rising, Enable switching | 1.1 | 1.25 | 1.4 | V |
| $\mathrm{V}_{\text {EN-L }}$ | Enable input low level | EN falling, Disable switching | 0.8 | 1 | 1.12 | V |
| $\mathrm{I}_{\text {LKG-EN }}$ | Enable input leakage current | $\mathrm{V}_{\mathrm{EN}}=3.3 \mathrm{~V}$ | 0.1 |  |  | $\mu \mathrm{A}$ |
| VOLTAGE REFERENCE (FB PIN) |  |  |  |  |  |  |
| $\mathrm{V}_{\mathrm{FB}}$ | Feedback voltage | $T_{J}=25^{\circ} \mathrm{C}$ | 0.792 | 0.8 | 0.808 | V |
| $\mathrm{I}_{\text {LKG-FB }}$ | Feedback leakage current | FB $=1 \mathrm{~V}$ |  |  | 100 | nA |
| CURRENT LIMITS AND HICCUP |  |  |  |  |  |  |
| $\mathrm{I}_{\text {SC }}$ | High-side current limit ${ }^{(3)}$ | 5 A Version | 6.4 | 8 | 9.6 | A |
| $\mathrm{I}_{\text {LS-LIMIT }}$ | Low-side current limit ${ }^{(3)}$ | 5 A Version |  | 5 |  | A |
| $\mathrm{I}_{\text {SC }}$ | High-side current limit ${ }^{(3)}$ | 4 A Version | 5.5 | 6.5 | 7.5 | A |
| $\mathrm{I}_{\text {LS-LIMIT }}$ | Low-side current limit ${ }^{(3)}$ | 4 A Version |  | 4 |  | A |
| $\mathrm{I}_{\text {L-ZC }}$ | Zero cross detector threshold | PFM variants only |  | $-0.1$ |  | A |
| $\mathrm{I}_{\text {PEAK-MIN }}$ | Minimum inductor peak current ${ }^{(3)}$ | 5 A Version, PFM variants only |  | 1 |  | A |
| $\mathrm{I}_{\text {PEAK-MIN }}$ | Minimum inductor peak current ${ }^{(3)}$ | 4 A Version, PFM variants only |  | 0.8 |  | A |
| $\mathrm{I}_{\text {L-NEG }}$ | Negative current limit ${ }^{(3)}$ | 5 A Version, FPWM variant only |  | $-2.5$ |  | A |
| $\mathrm{I}_{\text {L-NEG }}$ | Negative current limit ${ }^{(3)}$ | 4 A Version, FPWM variant only |  | $-1.7$ |  | A |
| $\mathrm{V}_{\text {HICCUP }}$ | Ratio of FB voltage to in-regulation FB voltage |  |  | 40 |  | $\%$ |Limits apply over operating junction temperature $\left(T_{J}\right)$ range of $-40^{\circ} \mathrm{C}$ to $+150^{\circ} \mathrm{C}$, unless otherwise stated. Minimum and Maximum limits ${ }^{(1)}$ are specified through test, design or statistical correlation. Typical values represent the most likely parametric norm at $T_{J}=25^{\circ} \mathrm{C}$, and are provided for reference purposes only. Unless otherwise stated, the following conditions apply: $\mathrm{V}_{\mathrm{IN}}=4 \mathrm{~V}$ to 36 V .

| PARAMETER |  | TEST CONDITIONS | MIN | TYP | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| POWER GOOD |  |  |  |  |  |  |
| $\mathrm{V}_{\text {PG-HIGH-UP }}$ | Power-Good upper threshold - rising | \% of FB voltage | 110 | 112 | 115 | \% |
| $\mathrm{V}_{\text {PG-LOW-DN }}$ | Power-Good lower threshold - falling | \% of FB voltage | 88 | 90 | 92 | \% |
| $\mathrm{V}_{\text {PG-HYS }}$ | Power-Good hysteresis (rising \& falling) | \% of FB voltage |  | 2.0 |  | \% |
| $\mathrm{V}_{\text {PG-VALID }}$ | Minimum input voltage for proper Power-Good function |  |  |  | 1.5 | V |
| $R_{P G}$ | Power-Good on-resistance | $\mathrm{V}_{\mathrm{EN}}=3.3 \mathrm{~V}$ |  | 84 |  | $\Omega$ |
| MOSFETS |  |  |  |  |  |  |
| $R_{\text {DS-ON-HS }}$ | High-side MOSFET ON-resistance |  |  | 78 |  | $\mathrm{m} \Omega$ |
| $R_{\text {DS-ON-LS }}$ | Low-side MOSFET ON-resistance |  |  | 45 |  | $\mathrm{m} \Omega$ |
| $\mathrm{V}_{\text {BOOT-SW- }}$ UVLO(R) | BOOT-SW UVLO rising threshold | $\mathrm{V}_{\text {BOOT-SW }}$ rising |  | 2.2 |  | V |
| SWITCHING CHARACTERISTICS |  |  |  |  |  |  |
| $\mathrm{F}_{\text {SW (CCM) }}$ | Switching frequency | $R_{T}=31.6 \mathrm{k} \Omega$ | 425 | 495 | 560 | kHz |
| $\mathrm{F}_{\text {SW (CCM) }}$ | Switching frequency | $R_{T}=$ Open or pull-up to voltage $>1.0 \mathrm{~V}$ | 450 | 500 | 550 | kHz |
| $\mathrm{F}_{\text {SW (CCM) }}$ | Switching frequency | $R_{T}=14.3 \mathrm{k} \Omega$ |  | 1000 |  | kHz |
| $\mathrm{F}_{\text {SW (CCM) }}$ | Switching frequency | $R_{T}=$ Short to GND |  | 1000 |  | kHz |
| $\mathrm{F}_{\text {SPREAD }}$ | Spread of internal oscillator with Spread Spectrum Enabled |  |  | $\pm 10$ |  | \% |
| TIMING REQUIREMENT |  |  |  |  |  |  |
| $t_{\text {ON-MIN }}$ | Minimum switch on-time ${ }^{(2)}$ | $\mathrm{V}_{\text {IN }}=24 \mathrm{~V}$, Iout $=1 \mathrm{~A}$ |  | 75 |  | ns |
| $t_{\text {OFF-MIN }}$ | Minimum switch off-time |  |  | 135 |  | ns |
| $t_{\text {ON-MAX }}$ | Maximum switch on-time |  |  | 5 |  | $\mu \mathrm{s}$ |
| $t_{S S}$ | Internal soft-start time |  | 3.2 | 5 | 7.2 | ms |
| $t_{w}$ | Short circuit wait time ("Hiccup" time) |  |  | 96 |  | ms |
| THERMAL SHUTDOWN |  |  |  |  |  |  |
| $\mathrm{T}_{\text {SD-Rising }}{ }^{(2)}$ | Thermal shutdown | Shutdown threshold |  | 160 |  | ${ }^{\circ} \mathrm{C}$ |
| $\mathrm{T}_{\text {SD-Falling }}{ }^{(2)}$ | Thermal shutdown | Recovery threshold |  | 140 |  | ${ }^{\circ} \mathrm{C}$ |

(1) MIN and MAX limits are $100 \%$ production tested at $25^{\circ} \mathrm{C}$. Limits over the operating temperature range verified through correlation using Statistical Quality Control (SQC) methods. Limits are used to calculate Average Outgoing Quality Level (AOQL).
(2) Not production tested. Specified by correlation by design.
(3) The current limit values in this table are tested, open loop, in production. They may differ from those found in a closed loop application.# 7.5 System Characteristics 

The following specifications apply to a typical application circuit with nominal component values. Specifications in the typical (TYP) column apply to $\mathrm{T}_{\mathrm{J}}=25^{\circ} \mathrm{C}$ only. Specifications in the minimum (MIN) and maximum (MAX) columns apply to the case of typical components over the temperature range of $\mathrm{T}_{\mathrm{J}}=-40^{\circ} \mathrm{C}$ to $150^{\circ} \mathrm{C}$. These specifications are not ensured by production testing.

| PARAMETER |  | TEST CONDITIONS | MIN | TYP | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{V}_{\text {IN }}$ | Operating input voltage range |  | 4 |  | 36 | V |
| $\mathrm{V}_{\text {OUT }}$ | Adjustable output voltage regulation ${ }^{(1)}$ | PFM operation | $1.5 \%$ |  |  |  |
| $\mathrm{I}_{\text {SUPPLY }}$ | Input supply current when in regulation | $\begin{aligned} & \mathrm{V}_{\text {IN }}=24 \mathrm{~V}, \mathrm{~V}_{\text {OUT }}=3.3 \mathrm{~V}, \mathrm{I}_{\text {OUT }}=0 \mathrm{~A}, \\ & \mathrm{R}_{\text {FBT }}=1 \mathrm{M} \Omega, \text { PFM variant } \end{aligned}$ | 35 |  |  | $\mu \mathrm{A}$ |
| $D_{\text {MAX }}$ | Maximum switch duty cycle ${ }^{(2)}$ |  | $97 \%$ |  |  |  |
| $\mathrm{V}_{\text {HC }}$ | FB pin voltage required to trip short-circuit hiccup mode |  | 0.32 |  |  | V |
| $\mathrm{T}_{\text {SO }}$ | Thermal shutdown temperature | Shutdown temperature | 160 |  |  | ${ }^{\circ} \mathrm{C}$ |
| $\mathrm{T}_{\text {SO }}$ | Thermal shutdown temperature | Recovery temperature | 140 |  |  | ${ }^{\circ} \mathrm{C}$ |

(1) Deviation in $\mathrm{V}_{\text {OUT }}$ from nominal output voltage value at $\mathrm{V}_{\text {IN }}=24 \mathrm{~V}, \mathrm{I}_{\text {OUT }}=0 \mathrm{~A}$ to full load
(2) In dropout the switching frequency drops to increase the effective duty cycle. The lowest frequency is clamped at approximately: $\mathrm{F}_{\text {MIN }}$ $=1 /\left(\mathrm{I}_{\mathrm{ON}-\text { MAX }}+\mathrm{I}_{\text {OFF-MIN }}\right) . \mathrm{D}_{\text {MAX }}=\mathrm{I}_{\mathrm{ON}-\text { MAX }} /\left(\mathrm{I}_{\mathrm{ON}-\text { MAX }}+\mathrm{I}_{\text {OFF-MIN }}\right)$.# 7.6 Typical Characteristics 

$V_{\text {IN }}=12 \mathrm{~V}, f_{\mathrm{SW}}=500 \mathrm{kHz}, \mathrm{T}_{\mathrm{A}}=25^{\circ} \mathrm{C}$, unless otherwise specified.
![img-3.jpeg](img-3.jpeg)

Figure 7-1. 5-V Efficiency versus Load Current
![img-4.jpeg](img-4.jpeg)

Figure 7-3. 3.3-V Efficiency versus Load Current
![img-5.jpeg](img-5.jpeg)

Figure 7-5. 3.3-V Load Regulation
![img-6.jpeg](img-6.jpeg)

Figure 7-2. 5-V Efficiency versus Load Current
![img-7.jpeg](img-7.jpeg)

Figure 7-4. 3.3-V Efficiency versus Load Current
![img-8.jpeg](img-8.jpeg)![img-9.jpeg](img-9.jpeg)

Figure 7-7. 5-V Dropout
![img-10.jpeg](img-10.jpeg)

Figure 7-9. Non-Switching Input Supply Current
![img-11.jpeg](img-11.jpeg)

Figure 7-11. Reference Voltage
![img-12.jpeg](img-12.jpeg)

Figure 7-8. 3.3-V Dropout
![img-13.jpeg](img-13.jpeg)

Figure 7-12. High Side and Low Side Switches $\mathrm{R}_{\text {DS_ON }}$![img-14.jpeg](img-14.jpeg)

Figure 7-13. LMR51450 High Side and Low Side Current Limits
![img-15.jpeg](img-15.jpeg)

Figure 7-14. LMR51440 High Side and Low Side Current Limits# 8 Detailed Description 

### 8.1 Overview

The LMR514x0 converter is an easy-to-use synchronous step-down DC-DC converter operating from a 4-V to $36-\mathrm{V}$ supply voltage. The device is capable of delivering up to $4-\mathrm{A}$ or $5-\mathrm{A}$ DC load current in a very small solution size. The family has multiple versions applicable to various applications. See Device Comparison Table for detailed information.

The LMR514x0 employs fixed-frequency peak-current mode control. The PFM version enters PFM Mode at light load to achieve high efficiency. A FPWM version is provided to achieve low output voltage ripple, tight output voltage regulation, and constant switching frequency at light load. The device is internally compensated, which reduces design time and requires few external components.

Additional features such as precision enable and internal soft start provide a flexible and easy-to-use solution for a wide range of applications. Protection features include thermal shutdown, $\mathrm{V}_{\mathrm{IN}}$ undervoltage lockout, cycle-by-cycle current limit, and hiccup mode short-circuit protection.

This family of devices requires very few external components and has a pin-out designed for simple, optimum PCB layout.

### 8.2 Functional Block Diagram

![img-16.jpeg](img-16.jpeg)# 8.3 Feature Description 

### 8.3.1 Fixed Frequency Peak Current Mode Control

The following operating description of the LMR514x0 refers to Functional Block Diagram and to the waveforms in Figure 8-1. The LMR514x0 is a step-down synchronous buck converter with integrated high-side (HS) and low-side (LS) switches (synchronous rectifier). The LMR514x0 supplies a regulated output voltage by turning on the high-side and low-side NMOS switches with controlled duty cycle. During high-side switch ON time, the SW pin voltage swings up to approximately $\mathrm{V}_{\mathrm{IN}}$, and the inductor current, $\mathrm{i}_{\mathrm{L}}$, increases with linear slope ( $\mathrm{V}_{\mathrm{IN}}$ $\left.V_{\text {OUT }}\right) / L$. When the high-side switch is turned off by the control logic, the low-side switch is turned on after an anti-shoot-through dead time. Inductor current discharges through the low-side switch with a slope of $-V_{\text {OUT }} / \mathrm{L}$. The control parameter of a buck converter is defined as Duty Cycle $D=t_{O N} / T_{S W}$, where $t_{O N}$ is the high-side switch ON time and $\mathrm{T}_{\mathrm{SW}}$ is the switching period. The converter control loop maintains a constant output voltage by adjusting the duty cycle D. In an ideal buck converter, where losses are ignored, D is proportional to the output voltage and inversely proportional to the input voltage: $D=V_{\text {OUT }} / V_{\text {IN }}$.
![img-17.jpeg](img-17.jpeg)

Figure 8-1. SW Node and Inductor Current Waveforms in Continuous Conduction Mode (CCM)
The LMR514x0 employs fixed-frequency peak-current mode control. A voltage feedback loop is used to get accurate DC voltage regulation by adjusting the peak-current command based on voltage offset. The peak inductor current is sensed from the high-side switch and compared to the peak current threshold to control the ON time of the high-side switch. The voltage feedback loop is internally-compensated, which allows for fewer external components, making designing easy, and providing stable operation when using a variety of output capacitors. The converter operates with fixed switching frequency at normal load conditions. During light-load condition, the LMR514x0 operates in PFM mode to maintain high efficiency (PFM version) or in FPWM mode for low output voltage ripple, tight output voltage regulation, and constant switching frequency (FPWM version).# 8.3.2 Adjustable Output Voltage 

A precision $0.8-\mathrm{V}$ reference voltage $\left(\mathrm{V}_{\text {REF }}\right)$ is used to maintain a tightly regulated output voltage over the entire operating temperature range. The output voltage is set by a resistor divider from $\mathrm{V}_{\text {OUT }}$ to the FB pin. TI recommends to use $1 \%$ tolerance resistors with a low temperature coefficient for the FB divider. Select the bottom-side resistor $\mathrm{R}_{\text {FBB }}$ for the desired divider current and use Equation 1 to calculate top-side resistor $\mathrm{R}_{\text {FBT }}$. The recommend range for $R_{F B T}$ is $10 \mathrm{k} \Omega$ to $100 \mathrm{k} \Omega$. A lower $R_{F B T}$ value can be used if pre-loading is desired to reduce $\mathrm{V}_{\text {OUT }}$ offset in PFM operation. Lower $\mathrm{R}_{\text {FBT }}$ reduces efficiency at very light load. Less static current goes through a larger $\mathrm{R}_{\text {FBT }}$ and can be more desirable when light-load efficiency is critical. However, TI does not recommend $R_{F B T}$ larger than $1 \mathrm{M} \Omega$ because it makes the feedback path more susceptible to noise. Larger $R_{F B T}$ values require more carefully designed feedback path trace from the feedback resistors to the feedback pin of the device. The tolerance and temperature variation of the resistor divider network affect the output voltage regulation.
![img-18.jpeg](img-18.jpeg)

Figure 8-2. Output Voltage Setting

$$
\mathrm{R}_{\mathrm{FBT}}=\frac{\left(\mathrm{V}_{\mathrm{OUT}}-\mathrm{V}_{\mathrm{REF}}\right)}{\mathrm{V}_{\mathrm{REF}}} \times \mathrm{R}_{\mathrm{FBB}}
$$

### 8.3.3 Enable

The voltage on the EN pin controls the ON and OFF operation of the LMR514x0. A voltage of less than 0.8 V shuts down the device, while a voltage of greater than 1.4 V is required to start the converter. The EN pin is an input and cannot be left open or floating. The simplest way to enable the operation of the LMR514x0 is to connect the EN to VIN. This connection allows self-start-up of the LMR514x0 when $\mathrm{V}_{\mathrm{IN}}$ is within the operating range.

Many applications benefit from the employment of an enable divider $R_{E N T}$ and $R_{E N B}$ (Figure 8-3) to establish a precision system UVLO level for the converter. System UVLO can be used for supplies operating from utility power as well as battery power. System UVLO can be used for sequencing, ensuring reliable operation, or supplying protection, such as a battery discharge level. An external logic signal can also be used to drive EN input for system sequencing and protection. Note, the EN pin voltage must not to be greater than $\mathrm{V}_{\mathrm{IN}}+0.3 \mathrm{~V}$. TI does not recommend to apply EN voltage when $\mathrm{V}_{\mathrm{IN}}$ is 0 V .
![img-19.jpeg](img-19.jpeg)

Figure 8-3. System UVLO by Enable Divider# 8.3.4 Switching Frequency 

The switching frequency of the LMR514x0 can be programmed by the resistor RT from the RT pin and GND pin. To determine the timing resistance for a given switching frequency, use Equation 2 or the curve in Figure 8-4. Table 8-1 gives typical $R_{T}$ values for a given $f_{S W}$.

$$
\mathrm{R}_{\mathrm{T}}(\mathrm{k} \Omega)=30542 \times \mathrm{f}_{\mathrm{SW}}(\mathrm{kHz})^{-1.108}
$$

![img-20.jpeg](img-20.jpeg)

Figure 8-4. $\mathbf{R}_{\mathbf{T}}$ Versus Frequency Curve
Table 8-1. Typical Frequency Setting $\mathbf{R}_{\mathbf{T}}$ Resistance

| $\mathbf{f}_{\mathbf{S W}}(\mathbf{k H z})$ | $\mathbf{R}_{\mathbf{T}}(\mathbf{k} \boldsymbol{)})$ |
| :--: | :--: |
| 200 | 84.5 |
| 400 | 39.2 |
| 495 | 31.6 |
| 500 | Open or pull-up to voltage $>1.0 \mathrm{~V}$ |
| 800 | 18.2 |
| 1000 | 14.3 |
| 1000 | Short to GND |

### 8.3.5 Power-Good Flag Output

The power-good flag function (PG output pin) of the LMR514x0 can be used to reset a system microprocessor whenever the output voltage is out of regulation. This open-drain output goes low under fault conditions, such as current limit and thermal shutdown, as well as during normal start-up. A glitch filter prevents false flag operation for short excursions of the output voltage, such as during line and load transients. Output voltage excursions lasting less than $\mathbf{t}_{\text {dg }} 35 \mu \mathrm{~s}$ (typical) do not trip the power-good flag. After the FB voltage has returned to the regulation value and after a delay of $\mathbf{t}_{\text {pg-delay }} 3.1 \mathrm{~ms}$ (typical), the power-good flag goes high.
The power-good output consists of an open-drain NMOS, requiring an external pullup resistor to a suitable logic supply. It can be pulled up to power supply below 20 V through a $10-\mathrm{k} \Omega$ to $100-\mathrm{k} \Omega$ resistor, as desired. If this function is not needed, the PG pin must be left floating. When EN is pulled low, the flag output is also forced low. With EN low, power good remains valid as long as the input voltage is greater than or equal to 1.5 V (typical). Limit the current into the power-good flag pin to less than 5-mA D.C.![img-21.jpeg](img-21.jpeg)

Figure 8-5. Static Power-Good Operation
![img-22.jpeg](img-22.jpeg)

Figure 8-6. Power-Good Timing Behavior (OV Events Not Included)

# 8.3.6 Minimum ON-Time, Minimum OFF-Time, and Frequency Foldback 

Minimum ON-time ( $\mathrm{T}_{\mathrm{ON} \text { MIN }}$ ) is the shortest duration of time that the high-side switch can be turned on. $\mathrm{T}_{\mathrm{ON} \text { MIN }}$ is typically 75 ns for the LMR514x0. Minimum OFF-time ( $\mathrm{T}_{\text {OFF_MIN }}$ ) is the shortest duration of time that thehigh-side switch can be off. $\mathrm{T}_{\text {OFF_MIN }}$ is typically 135 ns . In CCM operation, $\mathrm{T}_{\text {ON_MIN }}$ and $\mathrm{T}_{\text {OFF_MIN }}$ limit the voltage conversion range without switching frequency foldback.
The minimum duty cycle without frequency foldback allowed is:

$$
\mathrm{D}_{\mathrm{MIN}}=\mathrm{T}_{\mathrm{ON} \_\mathrm{MIN}} \times \mathrm{f}_{\mathrm{SW}}
$$

The maximum duty cycle without frequency foldback allowed is:

$$
\mathrm{D}_{\mathrm{MAX}}=1-\mathrm{T}_{\mathrm{OFF} \_\mathrm{MIN}} \times \mathrm{f}_{\mathrm{SW}}
$$

Given a required output voltage, the maximum $\mathrm{V}_{\mathrm{IN}}$ without frequency foldback can be found by:

$$
\mathrm{V}_{\mathrm{IN} \_\mathrm{MAX}}=\frac{\mathrm{V}_{\mathrm{OUT}}}{\mathrm{f}_{\mathrm{SW}} \times \mathrm{T}_{\mathrm{ON} \_\mathrm{MIN}}}
$$

The minimum $\mathrm{V}_{\mathrm{IN}}$ without frequency foldback can be calculated by:

$$
\mathrm{V}_{\mathrm{IN} \_\mathrm{MIN}}=\frac{\mathrm{V}_{\mathrm{OUT}}}{1-\mathrm{f}_{\mathrm{SW}} \times \mathrm{T}_{\mathrm{OFF} \_\mathrm{MIN}}}
$$

In the LMR514x0, a frequency foldback scheme is employed after the $\mathrm{T}_{\mathrm{ON} \_\mathrm{MIN}}$ or $\mathrm{T}_{\mathrm{OFF} \_\mathrm{MIN}}$ is triggered, which can extend the maximum duty cycle or lower the minimum duty cycle.
The on-time decreases while $\mathrm{V}_{\mathrm{IN}}$ voltage increases. After the on-time decreases to $\mathrm{T}_{\mathrm{ON} \_\mathrm{MIN}}$, the switching frequency starts to decrease while $\mathrm{V}_{\mathrm{IN}}$ continues to go up, which lowers the duty cycle further to keep $\mathrm{V}_{\mathrm{OUT}}$ in regulation according to Equation 5.
The frequency foldback scheme also works after larger duty cycle is needed under low $\mathrm{V}_{\mathrm{IN}}$ condition. The frequency decreases after the device hits its $\mathrm{T}_{\text {OFF_MIN }}$, which extends the maximum duty cycle according to Equation 6. In such condition, the frequency can be as low as approximately 200 kHz . Wide range of frequency foldback allows for the LMR514x0 output voltage to stay in regulation with a much lower supply voltage $\mathrm{V}_{\mathrm{IN}}$, which leads to a lower effective dropout.
With frequency foldback while maintaining a regulated output voltage, $\mathrm{V}_{\mathrm{IN} \_\mathrm{MAX}}$ is raised, and $\mathrm{V}_{\mathrm{IN} \_\mathrm{MIN}}$ is lowered by decreased $\mathrm{f}_{\mathrm{SW}}$.

# 8.3.7 Bootstrap Voltage 

The LMR514x0 provides an integrated bootstrap voltage converter. A small capacitor between the CB and SW pins provides the gate drive voltage for the high-side MOSFET. The bootstrap capacitor is refreshed when the high-side MOSFET is off and the low-side switch is on. The recommended value of the bootstrap capacitor is $0.1 \mu \mathrm{~F}$. TI recommends a ceramic capacitor with an X7R or X5R grade dielectric with a voltage rating of 16 V or higher for stable performance over temperature and voltage.

### 8.3.8 Overcurrent and Short-Circuit Protection

The LMR514x0 incorporates both peak and valley inductor current limit to provide protection to the device from overloads and short circuits and limit the maximum output current. Valley current limit prevents inductor current runaway during short circuits on the output, while both peak and valley limits work together to limit the maximum output current of the converter. Cycle-by-cycle current limit is used for overloads, while hiccup mode is used for sustained short circuits.

High-side MOSFET overcurrent protection is implemented by the nature of the peak current mode control. The high-side switch current is sensed when the high-side is turned on after a set blanking time. The high-side switch current is compared to the output of the Error Amplifier (EA) minus slope compensation every switching cycle. See Functional Block Diagram for more details. The peak current of high-side switch is limited by a clamped maximum peak current threshold $\mathrm{I}_{\mathrm{sc}}$ which is constant.
The current going through low-side MOSFET is also sensed and monitored. When the low-side switch turns on, the inductor current begins to ramp down. The low-side switch is not turned OFF at the end of a switching cycleif its current is above the low-side current limit $\mathrm{I}_{\mathrm{LS} \_}$LIMIT . The low-side switch is kept ON so that inductor current keeps ramping down, until the inductor current ramps below the $\mathrm{I}_{\mathrm{LS} \_}$LIMIT. Then the low-side switch is turned OFF and the high-side switch is turned on after a dead time. After $\mathrm{I}_{\mathrm{LS} \_}$LIMIT is achieved, peak and valley current limit controls the maximum current deliver and can be calculated using Equation 7.

$$
\mathrm{I}_{\text {OUT_MAX }}=\frac{\mathrm{I}_{\mathrm{LS} \_ \text {LIMIT }}+\mathrm{I}_{\mathrm{SC}}}{2}
$$

If the feedback voltage is lower than $40 \%$ of the $\mathrm{V}_{\text {REF }}$, the current of the low-side switch triggers $\mathrm{I}_{\mathrm{LS} \_}$LIMIT for 128 consecutive cycles and hiccup current protection mode is activated. In hiccup mode, the converter shuts down and keeps off for a period of hiccup, $\mathrm{T}_{\text {HICCUP }}$ ( $96-\mathrm{ms}$ typical) before the LMR514x0 tries to start again. If overcurrent or short-circuit fault condition still exist, hiccup repeats until the fault condition is removed. Hiccup mode reduces power dissipation under severe overcurrent conditions, prevents over-heating and potential damage to the device.

For FPWM version, the inductor current is allowed to go negative. When this current exceed the low-side negative current limit $\mathrm{I}_{\mathrm{LS} \_ \text {NEG }}$, the low-side switch is turned off and high-side switch is turned on immediately. This is used to protect the low-side switch from excessive negative current.

# 8.3.9 Soft Start 

The integrated soft-start circuit prevents input inrush current impacting the LMR514x0 and the input power supply. Soft start is achieved by slowly ramping up the internal reference voltage when the device is first enabled or powered up. The typical soft-start time is 5 ms .

### 8.3.10 Thermal Shutdown

The LMR514x0 provides an internal thermal shutdown to protect the device when the junction temperature exceeds $160^{\circ} \mathrm{C}$. Both high-side and low-side FETs stop switching in thermal shutdown. After the die temperature falls below $140^{\circ} \mathrm{C}$, the device reinitiates the power-up sequence controlled by the internal soft-start circuitry.# 8.4 Device Functional Modes 

### 8.4.1 Shutdown Mode

The EN pin provides electrical ON and OFF control for the LMR514x0. When $\mathrm{V}_{\mathrm{EN}}$ is below 0.8 V , the device is in shutdown mode. The LMR514x0 also employs $\mathrm{V}_{\mathrm{IN}}$ undervoltage lockout protection (UVLO). If $\mathrm{V}_{\mathrm{IN}}$ voltage is below its UVLO threshold 3.4 V , the converter is turned off.

### 8.4.2 Active Mode

The LMR514x0 is in active mode when both $\mathrm{V}_{\mathrm{EN}}$ and $\mathrm{V}_{\mathrm{IN}}$ are above their respective operating threshold. The simplest way to enable the LMR514x0 is to connect the EN pin to VIN pin. This allows self-start-up when the input voltage is in the operating range of 4 V to 36 V . See Enable for details on setting these operating levels.
In active mode, depending on the load current, the LMR514x0 is in one of four modes:

1. Continuous conduction mode (CCM) with fixed switching frequency when load current is greater than half of the peak-to-peak inductor current ripple (for both PFM and FPWM versions)
2. Discontinuous conduction mode (DCM) with fixed switching frequency when load current is less than half of the peak-to-peak inductor current ripple(only for PFM version)
3. Pulse frequency modulation mode (PFM) when switching frequency is decreased at very light load (only for PFM version)
4. Forced pulse width modulation mode (FPWM) with fixed switching frequency even at light load (only for FPWM version).

### 8.4.3 CCM Mode

Continuous Conduction Mode (CCM) operation is employed in the LMR514x0 when the load current is greater than half of the peak-to-peak inductor current. In CCM operation, the frequency of operation is fixed, output voltage ripple is at a minimum in this mode and the maximum output current of 4 A or 5 A can be supplied by the LMR514x0.

### 8.4.4 Light-Load Operation (PFM Version)

For PFM version, when the load current is lower than half of the peak-to-peak inductor current in CCM, the LMR514x0 operates in Discontinuous Conduction Mode (DCM), also known as Diode Emulation Mode (DEM). In DCM operation, the low-side switch is turned off when the inductor current drops to $\mathrm{I}_{\mathrm{LS}, \mathrm{ZC}}$ (100-mA typical) to improve efficiency. Both switching losses and conduction losses are reduced in DCM, compared to forced PWM operation at light load.

During light load operation, Pulse Frequency Modulation (PFM) mode is activated to maintain high efficiency operation. When either the minimum high-side switch ON time $\mathrm{t}_{\mathrm{ON}, \text { MIN }}$ or the minimum peak inductor current $\mathrm{I}_{\text {PEAK, MIN }}$ (1-A typical for LMR51450 and 0.8-A typical for LMR51440) is reached, the switching frequency decreases to maintain regulation. In PFM mode, switching frequency is decreased by the control loop to maintain output voltage regulation when load current reduces. Switching loss is further reduced in PFM operation due to a significant drop in effective switching frequency.

### 8.4.5 Light-Load Operation (FPWM Version)

For FPWM version, LMR514x0 is locked in PWM mode at full load range. This operation is maintained, even in no-load condition, by allowing the inductor current to reverse its normal direction. This mode trades off reduced light load efficiency for low output voltage ripple, tight output voltage regulation, and constant switching frequency.# 9 Application and Implementation 

## Note

Information in the following applications sections is not part of the TI component specification, and TI does not warrant its accuracy or completeness. TI's customers are responsible for determining suitability of components for their purposes, as well as validating and testing their design implementation to confirm system functionality.

### 9.1 Application Information

The LMR514x0 is a step-down DC-to-DC converter. The device is typically used to convert a higher input voltage to a lower output DC voltage with a maximum output current of 4 A or 5 A . The following design procedure can be used to select components for the LMR514x0 . Alternately, the WEBENCH ${ }^{\circledR}$ software can be used to generate complete designs. When generating a design, the WEBENCH® software uses iterative design procedure and accesses comprehensive databases of components. Go to ti.com for more details.

## Note

All of the capacitance values given in the following application information refer to effective values unless otherwise stated. The effective value is defined as the actual capacitance under DC bias and temperature, not the rated or nameplate values. Use high-quality, low-ESR, ceramic capacitors with an X7R or better dielectric throughout. All high value ceramic capacitors have a large voltage coefficient in addition to normal tolerances and temperature effects. Under DC bias the capacitance drops considerably. Large case sizes and higher voltage ratings are better in this regard. To help mitigate these effects, multiple capacitors can be used in parallel to bring the minimum effective capacitance up to the required value. This can also ease the RMS current requirements on a single capacitor. A careful study of bias and temperature variation of any capacitor bank must be made to ensure that the minimum value of effective capacitance is provided.# 9.2 Typical Application 

The LMR514x0 only requires a few external components to convert from a wide voltage range supply to a fixed output voltage. Figure 9-1 shows a basic schematic.
![img-23.jpeg](img-23.jpeg)

Figure 9-1. Application Circuit
The external components have to fulfill the needs of the application and the stability criteria of the control loop of the device. Use Table 9-1 and Table 9-2 to simplify the output filter component selection.

Table 9-1. L and $\mathrm{C}_{\text {OUT }}$ Typical Values for LMR51440

| $\mathbf{f}_{\text {SW }}(\mathbf{k H z})$ | $\mathbf{V}_{\text {OUT }}(\mathbf{V})$ | $\mathbf{L}(\mu \mathrm{H})$ | $\mathbf{C}_{\text {OUT }}(\mu \mathrm{F})^{(1)}$ | $\mathbf{R}_{\text {FBT }}(\mathbf{k} \boldsymbol{\Omega})$ | $\mathbf{R}_{\text {FBB }}(\mathbf{k} \boldsymbol{)})$ | $\mathbf{C}_{\text {FF }}(\mathbf{p F})$ | $\mathbf{R}_{\text {FF }}(\mathbf{k} \boldsymbol{)})$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 500 | 3.3 | 4.7 | $2 \times 47$ | 100 | 31.6 | 33 | 1 |
|  | 5 | 5.6 | $2 \times 33$ | 100 | 19.1 | 33 | 1 |
|  | 12 | 8.2 | $2 \times 10$ | 100 | 7.15 | 33 | 1 |
| 1000 | 3.3 | 2.2 | 47 | 100 | 31.6 | 22 | 1 |
|  | 5 | 3.3 | 33 | 100 | 19.1 | 22 | 1 |

(1) A ceramic capacitor is used in this table. All the $\mathrm{C}_{\text {OUT }}$ values are after derating.
Table 9-2. L and $\mathrm{C}_{\text {OUT }}$ Typical Values for LMR51450

| $\mathbf{f}_{\text {SW }}(\mathbf{k H z})$ | $\mathbf{V}_{\text {OUT }}(\mathbf{V})$ | $\mathbf{L}(\mu \mathbf{H})$ | $\mathbf{C}_{\text {OUT }}(\mu \mathbf{F})^{(1)}$ | $\mathbf{R}_{\text {FBT }}(\mathbf{k} \boldsymbol{)})$ | $\mathbf{R}_{\text {FBB }}(\mathbf{k} \boldsymbol{)})$ | $\mathbf{C}_{\text {FF }}(\mathbf{p F})$ | $\mathbf{R}_{\text {FF }}(\mathbf{k} \boldsymbol{)})$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 500 | 3.3 | 3.3 | $2 \times 47$ | 100 | 31.6 | 33 | 1 |
|  | 5 | 4.7 | $2 \times 33$ | 100 | 19.1 | 33 | 1 |
|  | 12 | 6.8 | $2 \times 10$ | 100 | 7.15 | 33 | 1 |

(1) A ceramic capacitor is used in this table. All the $\mathrm{C}_{\text {OUT }}$ values are after derating.# 9.2.1 Design Requirements 

The detailed design procedure is described based on a design example. For this design example, use the parameters listed in Table 9-3 as the input parameters.

Table 9-3. Design Example Parameters

| PARAMETER | VALUE |
| :-- | :--: |
| Input voltage, $\mathrm{V}_{\text {IN }}$ | $12-\mathrm{V}$ typical, range from 6 V to 36 V |
| Output voltage, $\mathrm{V}_{\text {OUT }}$ | $5 \mathrm{~V} \pm 3 \%$ |
| Maximum output current, $\mathrm{I}_{\text {OUT_MAX }}$ | 5 A |
| Output overshoot/ undershoot 1.5 A to 4 A | $5 \%$ |
| Output voltage ripple | $0.5 \%$ |
| Operating frequency | 500 kHz |

### 9.2.2 Detailed Design Procedure

### 9.2.2.1 Output Voltage Set-Point

The output voltage of the LMR514x0 device is externally adjustable using a resistor divider network. The divider network is comprised of top feedback resistor $\mathrm{R}_{\text {FBT }}$ and bottom feedback resistor $\mathrm{R}_{\text {FBB. Equation } 8}$ is used to determine the output voltage of the converter:

$$
\mathrm{R}_{\mathrm{FBT}}=\frac{\left(\mathrm{V}_{\mathrm{OUT}}-\mathrm{V}_{\mathrm{REF}}\right)}{\mathrm{V}_{\mathrm{REF}}} \times \mathrm{R}_{\mathrm{FBB}}
$$

Choose the value of $R_{F B B}$ to be $19.1 \mathrm{k} \Omega$. With the desired output voltage set to 5 V and the $\mathrm{V}_{\mathrm{REF}}=0.8 \mathrm{~V}$, the $\mathrm{R}_{\text {FBT }}$ value can then be calculated using Equation 8. The formula yields to a value $100.28 \mathrm{k} \Omega$, a standard value of $100 \mathrm{k} \Omega$ is selected.

### 9.2.2.2 Switching Frequency

The higher switching frequency allows for lower value inductors and smaller output capacitors, which results in smaller solution size and lower component cost. However, higher switching frequency brings more switching loss, making the solution less efficient and produce more heat. The switching frequency is also limited by the minimum on-time of the integrated power switch, the input voltage, the output voltage, and the frequency shift limitation as mentioned in Minimum ON-Time, Minimum OFF-Time, and Frequency Foldback.

For this example, a switching frequency of 500 kHz is selected. RT open defaults to 500 kHz .

### 9.2.2.3 Inductor Selection

The most critical parameters for the inductor are the inductance, saturation current, and the RMS current. The inductance is based on the desired peak-to-peak ripple current $\Delta \mathrm{i}_{\mathrm{L}}$. Because the ripple current increases with the input voltage, the maximum input voltage is always used to calculate the minimum inductance $\mathrm{L}_{\text {MIN }}$. Use Equation 10 to calculate the minimum value of the output inductor. $\mathrm{K}_{\text {IND }}$ is a coefficient that represents the amount of inductor ripple current relative to the maximum output current of the device. A reasonable value of $\mathrm{K}_{\text {IND }}$ must be $20 \%$ to $60 \%$ of maximum $\mathrm{I}_{\text {OUT }}$ supported by converter. During an instantaneous overcurrent operation event, the RMS and peak inductor current can be high. The inductor saturation current must be higher than peak current limit level.

$$
\begin{aligned}
& \Delta \mathrm{i}_{\mathrm{L}}=\frac{\mathrm{V}_{\mathrm{OUT}} \times\left(\mathrm{V}_{\mathrm{IN} \_\mathrm{MAX}}-\mathrm{V}_{\mathrm{OUT}}\right)}{\mathrm{V}_{\mathrm{IN} \_\mathrm{MAX}} \times \mathrm{L} \times \mathrm{f}_{\mathrm{SW}}} \\
& \mathrm{~L}_{\mathrm{MIN}}=\frac{\mathrm{V}_{\mathrm{IN} \_\mathrm{MAX}}-\mathrm{V}_{\mathrm{OUT}}}{\mathrm{I}_{\mathrm{OUT}} \times \mathrm{K}_{\mathrm{IND}}} \times \frac{\mathrm{V}_{\mathrm{OUT}}}{\mathrm{~V}_{\mathrm{IN} \_\mathrm{MAX}} \times \mathrm{f}_{\mathrm{SW}}}
\end{aligned}
$$

In general, choosing lower inductance in switching power supplies is preferable because it usually corresponds to faster transient response, smaller DCR, and reduced size for more compact designs. Too low of an inductance can generate too large of an inductor current ripple such that overcurrent protection at the full load can be falselytriggered. It also generates more inductor core loss because the current ripple is larger. Larger inductor current ripple also implies larger output voltage ripple with the same output capacitors. With peak current mode control, TI recommends to have adequate amount of inductor ripple current. A larger inductor ripple current improves the comparator signal-to-noise ratio.

For this design example, choose $K_{\text {IND }}=0.4$. The minimum inductor value is calculated to be $4.31 \mu \mathrm{H}$. Choose the nearest standard $4.7 \mu \mathrm{H}$ power inductor with a capability of 6 -A RMS current and 10 -A saturation current.

# 9.2.2.4 Output Capacitor Selection 

The device is designed to be used with a wide variety of LC filters. Minimize the output capacitance to keep cost and size down. The output capacitor or capacitors, $\mathrm{C}_{\text {OUT }}$, must be chosen with care because it directly affects the steady state output voltage ripple, loop stability, and output voltage overshoot and undershoot during load current transient. The output voltage ripple is essentially composed of two parts. One part is caused by the inductor ripple current flowing through the Equivalent Series Resistance (ESR) of the output capacitors:

$$
\Delta \mathrm{V}_{\text {OUT_ESR }}=\Delta \mathrm{i}_{\mathrm{L}} \times \mathrm{ESR}=\mathrm{K}_{\mathrm{IND}} \times \mathrm{I}_{\text {OUT }} \times \mathrm{ESR}
$$

The other part is caused by the inductor current ripple charging and discharging the output capacitors:

$$
\Delta \mathrm{V}_{\mathrm{OUT}_{-} \mathrm{C}}=\frac{\Delta \mathrm{i}_{\mathrm{L}}}{\mathrm{~B} \times \mathrm{I}_{\mathrm{SW}} \times \mathrm{C}_{\mathrm{OUT}}}=\frac{\mathrm{K}_{\mathrm{IND}} \times \mathrm{I}_{\mathrm{OUT}}}{\mathrm{~B} \times \mathrm{I}_{\mathrm{SW}} \times \mathrm{C}_{\mathrm{OUT}}}
$$

The two components of the voltage ripple are not in-phase, therefore, the actual peak-to-peak ripple is less than the sum of the two peaks.

Output capacitance is usually limited by transient performance specifications if the system requires tight voltage regulation with presence of large current steps and fast slew rates. When a large load step occurs, output capacitors provide the required charge before the inductor current can slew to an appropriate level. The control loop of the converter usually requires eight or more clock cycles to regulate the inductor current equal to the new load level during this time. The output capacitance must be large enough to supply the current difference for 6 clock cycles to maintain the output voltage within the specified range. Equation 13 shows the minimum output capacitance needed for a specified $\mathrm{V}_{\text {OUT }}$ overshoot and undershoot.

$$
\mathrm{C}_{\text {OUT }}>\frac{1}{2} \times \frac{6 \times\left(\mathrm{I}_{\mathrm{OH}}-\mathrm{I}_{\mathrm{OL}}\right)}{\mathrm{I}_{\mathrm{SW}} \times \Delta \mathrm{~V}_{\text {OUT_SHOOT }}}
$$

where

- $\mathrm{K}_{\text {IND }}=$ Ripple ratio of the inductor current $\left(\Delta \mathrm{i}_{\mathrm{L}} / \mathrm{I}_{\text {OUT }}\right)$
- $\mathrm{I}_{\mathrm{OL}}=$ Low level output current during load transient
- $\mathrm{I}_{\mathrm{OH}}=$ High level output current during load transient
- $\mathrm{V}_{\text {OUT_SHOOT }}=$ Target output voltage overshoot or undershoot

For this design example, the target output ripple is 25 mV . Assuming $\Delta \mathrm{V}_{\text {OUT_ESR }}=\Delta \mathrm{V}_{\text {OUT_C }}=25 \mathrm{mV}$, choose $\mathrm{K}_{\text {IND }}=0.4$. Equation 11 yields ESR no larger than $12.5 \mathrm{~m} \Omega$ and Equation 12 yields $\mathrm{C}_{\text {OUT }}$ no smaller than 20 $\mu \mathrm{F}$. For the target overshoot and undershoot limitation of this design, $\Delta \mathrm{V}_{\text {OUT_SHOOT }}=5 \% \times \mathrm{V}_{\text {OUT }}=250 \mathrm{mV}$. The $\mathrm{C}_{\text {OUT }}$ can be calculated to be no less than $60 \mu \mathrm{~F}$ by Equation 13. In summary, the most stringent criteria for the output capacitor is $60 \mu \mathrm{~F}$. Considering derating, two $33-\mu \mathrm{F}, 16-\mathrm{V}, \mathrm{X} 7 \mathrm{R}$ ceramic capacitor with $5-\mathrm{m} \Omega$ ESR is used.

### 9.2.2.5 Input Capacitor Selection

The LMR514x0 device requires a high frequency input decoupling capacitor or capacitor. The typical recommended value for the high frequency decoupling capacitor is $10 \mu \mathrm{~F}$ or higher. TI recommends a highquality ceramic type X5R or X7R with sufficiency voltage rating. The voltage rating must be greater than the maximum input voltage. To compensate the derating of ceramic capacitors, TI recommends a voltage rating of twice the maximum input voltage. For this design, two $4.7-\mu \mathrm{F}, \mathrm{X} 7 \mathrm{R}$ dielectric capacitor rated for 50 V is used for the input decoupling capacitor. The equivalent series resistance (ESR) is approximately $10 \mathrm{~m} \Omega$. Include a capacitor with a value of $0.1 \mu \mathrm{~F}$ for high-frequency filtering and place it as close as possible to the device pins.# 9.2.2.6 Bootstrap Capacitor 

Every LMR514x0 design requires a bootstrap capacitor, $\mathrm{C}_{\text {BOOT }}$. The recommended bootstrap capacitor is 0.1 $\mu \mathrm{F}$ and rated at 16 V or higher. The bootstrap capacitor is located between the SW pin and the BOOT pin. The bootstrap capacitor must be a high-quality ceramic type with X7R or X5R grade dielectric for temperature stability.

### 9.2.2.7 Undervoltage Lockout Set-Point

The system undervoltage lockout (UVLO) is adjusted using the external voltage divider network of $R_{E N T}$ and $R_{E N B}$. The UVLO has two thresholds, one for power up when the input voltage is rising and one for power down or brown outs when the input voltage is falling. Equation 14 can be used to determine the $\mathrm{V}_{\text {IN }}$ UVLO level.

$$
\mathrm{V}_{\text {IN_RISING }}=\mathrm{V}_{\mathrm{ENH}} \times \frac{\mathrm{R}_{\mathrm{EBT}}+\mathrm{R}_{\mathrm{ENB}}}{\mathrm{R}_{\mathrm{ENB}}}
$$

The EN rising threshold $\left(\mathrm{V}_{\mathrm{ENH}}\right)$ for LMR514x0 is set to be 1.25 V (typical). Choose a value of $21.5 \mathrm{k} \Omega$ for $\mathrm{R}_{\mathrm{ENB}}$ to minimize input current from the supply. If the desired $\mathrm{V}_{\text {IN }}$ UVLO level is at 6.0 V , then the value of $\mathrm{R}_{\text {ENT }}$ can be calculated using Equation 15:

$$
\mathrm{R}_{\mathrm{EBT}}=\left(\frac{\mathrm{V}_{\mathrm{IN} \text { RISING }}}{\mathrm{V}_{\mathrm{ENH}}}-1\right) \times \mathrm{R}_{\mathrm{ENB}}
$$

The above equation yields a value of $81.7 \mathrm{k} \Omega$, a standard value of $82 \mathrm{k} \Omega$ is selected. The resulting falling UVLO threshold, equals 4.8 V , can be calculated by Equation 16 where EN hysteresis voltage, $\mathrm{V}_{\mathrm{EN}_{-} \text {HYS, }}$ is 0.25 V (typical).

$$
\mathrm{V}_{\text {IN_FALLING }}=\left(\mathrm{V}_{\mathrm{ENH}}-\mathrm{V}_{\mathrm{ENH} \_\mathrm{HYS}}\right) \times \frac{\mathrm{R}_{\mathrm{EBT}}+\mathrm{R}_{\mathrm{ENB}}}{\mathrm{R}_{\mathrm{ENB}}}
$$# 9.2.3 Application Curves 

Unless otherwise specified the following conditions apply: $\mathrm{V}_{\mathrm{IN}}=12 \mathrm{~V}, \mathrm{~V}_{\text {OUT }}=5 \mathrm{~V}, \mathrm{f}_{\mathrm{SW}}=500 \mathrm{kHz}, \mathrm{L}=4.7 \mu \mathrm{H}$, $\mathrm{C}_{\text {OUT }}=66 \mu \mathrm{~F}, \mathrm{~T}=25^{\circ} \mathrm{C}$.
![img-24.jpeg](img-24.jpeg)

Figure 9-2. Ripple at No Load
![img-25.jpeg](img-25.jpeg)

Figure 9-4. Start-Up by $\mathrm{V}_{\text {IN }}$
![img-26.jpeg](img-26.jpeg)

Figure 9-6. Load Transient
![img-27.jpeg](img-27.jpeg)

Figure 9-3. Ripple at Full Load
![img-28.jpeg](img-28.jpeg)

Figure 9-5. Start-Up by EN
![img-29.jpeg](img-29.jpeg)

Figure 9-7. Line Transient![img-30.jpeg](img-30.jpeg)

**Figure 9-8. Short Protection**

![img-31.jpeg](img-31.jpeg)

**Figure 9-9. Short Recovery**# 9.3 Best Design Practices 

- Do not exceed the Absolute Maximum Ratings .
- Do not exceed the Recommended Operating Conditions.
- Do not exceed the ESD Ratings.
- Do not allow the EN input to float.
- Do not allow the output voltage to exceed the input voltage, nor go below ground.
- Follow all the guidelines and suggestions found in this data sheet before committing the design to production. TI application engineers are ready to help critique your design and PCB layout to help make your project a success.


### 9.4 Power Supply Recommendations

The LMR514x0 is designed to operate from an input voltage supply range between 4 V and 36 V . This input supply must be well-regulated and able to withstand maximum input current and maintain a stable voltage. The resistance of the input supply rail must be low enough that an input current transient does not cause a high enough drop at the LMR514x0 supply voltage that can cause a false UVLO fault triggering and system reset. If the input supply is located more than a few inches from the LMR514x0 additional bulk capacitance can be required in addition to the ceramic bypass capacitors. The amount of bulk capacitance is not critical, but a $47-\mu \mathrm{F}$ or $100-\mu \mathrm{F}$ electrolytic capacitor is a typical choice.

### 9.5 Layout

### 9.5.1 Layout Guidelines

Layout is a critical portion of good power supply design. The following guidelines help users design a PCB with the best power conversion performance, thermal performance, and minimized generation of unwanted EMI.

1. The input bypass capacitor $\mathrm{C}_{\mathrm{IN}}$ must be placed as close as possible to the VIN and PGND pins. Grounding for both the input and output capacitors must consist of localized top side planes that connect to the PGND pin.
2. Minimize trace length to the FB pin net. Both feedback resistors, $R_{F B T}$ and $R_{F B B}$, must be located close to the FB pin. If $V_{\text {OUT }}$ accuracy at the load is important, make sure $V_{\text {OUT }}$ sense is made at the load. Route $V_{\text {OUT }}$ sense path away from noisy nodes and preferably through a layer on the other side of a shielded layer.
3. Use ground plane in one of the middle layers as noise shielding and heat dissipation path if possible.
4. Make $\mathrm{V}_{\mathrm{IN}}, \mathrm{V}_{\text {OUT }}$, and ground bus connections as wide as possible. This reduces any voltage drops on the input or output paths of the converter and maximizes efficiency.
5. Provide adequate device heat-sinking. Use an array of heat-sinking vias to connect the top side ground plane to the ground plane on the bottom PCB layer. If the PCB has multiple copper layers, these thermal vias can also be connected to inner layer heat-spreading ground planes. Make sure enough copper area is used for heat-sinking to keep the junction temperature below $150^{\circ} \mathrm{C}$.

### 9.5.1.1 Compact Layout for EMI Reduction

Radiated EMI is generated by the high di/dt components in pulsing currents in switching converters. The larger area covered by the path of a pulsing current, the more EMI is generated. High frequency ceramic bypass capacitors at the input side provide primary path for the high di/dt components of the pulsing current. Placing a ceramic bypass capacitor or capacitors as close as possible to the VIN and PGND pins is the key to EMI reduction.

The SW pin connecting to the inductor must be as short as possible, and just wide enough to carry the load current without excessive heating. Short, thick traces or copper pours (shapes) must be used for high current conduction path to minimize parasitic resistance. The output capacitors must be placed close to the $V_{\text {OUT }}$ end of the inductor and closely grounded to PGND pin.

### 9.5.1.2 Feedback Resistors

To reduce noise sensitivity of the output voltage feedback path, make sure to place the resistor divider close to the FB pin, rather than close to the load. The FB pin is the input to the error amplifier, so it is a high impedance node and very sensitive to noise. Placing the resistor divider closer to the FB pin reduces the trace length ofFB signal and reduces noise coupling. The output node is a low impedance node, so the trace from $\mathrm{V}_{\text {OUT }}$ to the resistor divider can be long if short path is not available.

If voltage accuracy at the load is important, make sure voltage sense is made at the load. Doing so corrects for voltage drops along the traces and provides the best output accuracy. The voltage sense trace from the load to the feedback resistor divider must be routed away from the SW node path and the inductor to avoid contaminating the feedback signal with switch noise, while also minimizing the trace length. This is most important when high value resistors are used to set the output voltage. TI recommends to route the voltage sense trace and place the resistor divider on a different layer than the inductor and SW node path, such that there is a ground plane in between the feedback trace and inductor/SW node polygon. This action provides further shielding for the voltage feedback path from EMI noises.# 9.5.2 Layout Example 

![img-32.jpeg](img-32.jpeg)

Figure 9-10. Layout# 10 Device and Documentation Support 

### 10.1 Device Support

### 10.1.1 Development Support

### 10.1.1.1 Custom Design With WEBENCH® Tools

Click here to create a custom design using the LMR51450 device with the WEBENCH® Power Designer.

1. Start by entering the input voltage $\left(\mathrm{V}_{\mathrm{IN}}\right)$, output voltage $\left(\mathrm{V}_{\mathrm{OUT}}\right)$, and output current $\left(\mathrm{I}_{\mathrm{OUT}}\right)$ requirements.
2. Optimize the design for key parameters such as efficiency, footprint, and cost using the optimizer dial.
3. Compare the generated design with other possible solutions from Texas Instruments.

The WEBENCH Power Designer provides a customized schematic along with a list of materials with real-time pricing and component availability.
In most cases, these actions are available:

- Run electrical simulations to see important waveforms and circuit performance
- Run thermal simulations to understand board thermal performance
- Export customized schematic and layout into popular CAD formats
- Print PDF reports for the design, and share the design with colleagues

Get more information about WEBENCH tools at www.ti.com/WEBENCH.

### 10.2 Documentation Support

### 10.2.1 Related Documentation

For related documentation see the following:

- Texas Instruments, Layout Guidelines for Switching Power Supplies
- Texas Instruments, A Guide to Board Layout for Best Thermal Resistance for Exposed Pad Packages
- Texas Instruments, How to Properly Evaluate Junction Temperature with Thermal Metrics


### 10.3 Receiving Notification of Documentation Updates

To receive notification of documentation updates, navigate to the device product folder on ti.com. Click on Subscribe to updates to register and receive a weekly digest of any product information that has changed. For change details, review the revision history included in any revised document.

### 10.4 Support Resources

TI E2E ${ }^{\text {TM }}$ support forums are an engineer's go-to source for fast, verified answers and design help - straight from the experts. Search existing answers or ask your own question to get the quick design help you need.
Linked content is provided "AS IS" by the respective contributors. They do not constitute TI specifications and do not necessarily reflect TI's views; see TI's Terms of Use.

### 10.5 Trademarks

TI E2E ${ }^{\text {TM }}$ is a trademark of Texas Instruments.
WEBENCH ${ }^{\circledR}$ is a registered trademark of Texas Instruments.
All trademarks are the property of their respective owners.

### 10.6 Electrostatic Discharge Caution

This integrated circuit can be damaged by ESD. Texas Instruments recommends that all integrated circuits be handled with appropriate precautions. Failure to observe proper handling and installation procedures can cause damage.
ESD damage can range from subtle performance degradation to complete device failure. Precision integrated circuits may be more susceptible to damage because very small parametric changes could cause the device not to meet its published specifications.

### 10.7 Glossary

TI Glossary This glossary lists and explains terms, acronyms, and definitions.# 11 Mechanical, Packaging, and Orderable Information 

The following pages include mechanical, packaging, and orderable information. This information is the most current data available for the designated devices. This data is subject to change without notice and revision of this document. For browser-based versions of this data sheet, refer to the left-hand navigation.# PACKAGE OPTION ADDENDUM

|  Orderable part number | Status
(1) | Material type
(2) | Package | Pins | Package qty | Carrier | RoHS
(3) | Lead finish/
Ball material
(4) | MSL rating/
Peak reflow
(5) | Op temp ( ${ }^{\circ} \mathrm{C}$ ) | Part marking
(6)  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  LMR51440SDRRR | Active | Production | WSON (DRR) | 12 | 3000 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 150 | L5144S  |
|  LMR51440SDRRR.A | Active | Production | WSON (DRR) | 12 | 3000 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 150 | L5144S  |
|  LMR51450FNDRRR | Active | Production | WSON (DRR) | 12 | 3000 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 150 | L5145F  |
|  LMR51450FNDRRR.A | Active | Production | WSON (DRR) | 12 | 3000 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 150 | L5145F  |
|  LMR51450SDRRR | Active | Production | WSON (DRR) | 12 | 3000 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 150 | L5145S  |
|  LMR51450SDRRR.A | Active | Production | WSON (DRR) | 12 | 3000 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 150 | L5145S  |

${ }^{(1)}$ Status: For more details on status, see our product life cycle. ${ }^{(2)}$ Material type: When designated, preproduction parts are prototypes/experimental devices, and are not yet approved or released for full production. Testing and final process, including without limitation quality assurance, reliability performance testing, and/or process qualification, may not yet be complete, and this item is subject to further changes or possible discontinuation. If available for ordering, purchases will be subject to an additional waiver at checkout, and are intended for early internal evaluation purposes only. These items are sold without warranties of any kind. ${ }^{(3)}$ RoHS values: Yes, No, RoHS Exempt. See the TI RoHS Statement for additional information and value definition. ${ }^{(4)}$ Lead finish/Ball material: Parts may have multiple material finish options. Finish options are separated by a vertical ruled line. Lead finish/Ball material values may wrap to two lines if the finish value exceeds the maximum column width. ${ }^{(5)}$ MSL rating/Peak reflow: The moisture sensitivity level ratings and peak solder (reflow) temperatures. In the event that a part has multiple moisture sensitivity ratings, only the lowest level per JEDEC standards is shown. Refer to the shipping label for the actual reflow temperature that will be used to mount the part to the printed circuit board. ${ }^{(6)}$ Part marking: There may be an additional marking, which relates to the logo, the lot trace code information, or the environmental category of the part.

Multiple part markings will be inside parentheses. Only one part marking contained in parentheses and separated by a "-" will appear on a part. If a line is indented then it is a continuation of the previous line and the two combined represent the entire part marking for that device.

Important Information and Disclaimer:The information provided on this page represents TI's knowledge and belief as of the date that it is provided. TI bases its knowledge and belief on information provided by third parties, and makes no representation or warranty as to the accuracy of such information. Efforts are underway to better integrate information from third parties. TI has taken and continues to take reasonable steps to provide representative and accurate information but may not have conducted destructive testing or chemical analysis on incoming materials and chemicals. TI and TI suppliers consider certain information to be proprietary, and thus CAS numbers and other limited information may not be available for release.

In no event shall TI's liability arising out of such information exceed the total purchase price of the TI part(s) at issue in this document sold by TI to Customer on an annual basis.OTHER QUALIFIED VERSIONS OF LMR51440, LMR51450 :

- Automotive : LMR51440-Q1, LMR51450-Q1

NOTE: Qualified Version Definitions:

- Automotive - Q100 devices qualified for high-reliability automotive applications targeting zero defects# TAPE AND REEL INFORMATION 

![img-33.jpeg](img-33.jpeg)

TAPE DIMENSIONS
![img-34.jpeg](img-34.jpeg)

| A0 | Dimension designed to accommodate the component width |
| :-- | :-- |
| B0 | Dimension designed to accommodate the component length |
| K0 | Dimension designed to accommodate the component thickness |
| W | Overall width of the carrier tape |
| P1 | Pitch between successive cavity centers |

QUADRANT ASSIGNMENTS FOR PIN 1 ORIENTATION IN TAPE
![img-35.jpeg](img-35.jpeg)

Pocket Quadrants
*All dimensions are nominal

| Device | Package <br> Type | Package <br> Drawing | Pins | SPQ | Reel <br> Diameter <br> (mm) | Reel <br> Width <br> W1 (mm) | A0 <br> (mm) | B0 <br> (mm) | K0 <br> (mm) | P1 <br> (mm) | W <br> (mm) | Pin1 <br> Quadrant |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| LMR51440SDRRR | WSON | DRR | 12 | 3000 | 330.0 | 12.4 | 3.3 | 3.3 | 1.1 | 8.0 | 12.0 | Q2 |
| LMR51450FNDRRR | WSON | DRR | 12 | 3000 | 330.0 | 12.4 | 3.3 | 3.3 | 1.1 | 8.0 | 12.0 | Q2 |
| LMR51450SDRRR | WSON | DRR | 12 | 3000 | 330.0 | 12.4 | 3.3 | 3.3 | 1.1 | 8.0 | 12.0 | Q2 |# PACKAGE MATERIALS INFORMATION

## TAPE AND REEL BOX DIMENSIONS

![img-36.jpeg](img-36.jpeg)

*All dimensions are nominal

|  Device | Package Type | Package Drawing | Pins | SPQ | Length (mm) | Width (mm) | Height (mm)  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  LMR51440SDRRR | WSON | DRR | 12 | 3000 | 367.0 | 367.0 | 35.0  |
|  LMR51450FNDRRR | WSON | DRR | 12 | 3000 | 367.0 | 367.0 | 35.0  |
|  LMR51450SDRRR | WSON | DRR | 12 | 3000 | 367.0 | 367.0 | 35.0  |# GENERIC PACKAGE VIEW 

## DRR 12

## WSON - 0.8 mm max height

$3 \times 3,0.5 \mathrm{~mm}$ pitch

PLASTIC SMALL OUTLINE - NO LEAD

This image is a representation of the package family, actual package may vary.
Refer to the product data sheet for package details.
![img-37.jpeg](img-37.jpeg)![img-38.jpeg](img-38.jpeg)

# PACKAGE OUTLINE 

## DRR0012G

## WSON - 0.8 mm max height

PLASTIC SMALL OUTLINE - NO LEAD
![img-39.jpeg](img-39.jpeg)

## NOTES:

1. All linear dimensions are in millimeters. Any dimensions in parenthesis are for reference only. Dimensioning and tolerancing per ASME Y14.5M.
2. This drawing is subject to change without notice.
3. The package thermal pad must be soldered to the printed circuit board for thermal and mechanical performance.![img-40.jpeg](img-40.jpeg)

NOTES: (continued)
4. This package is designed to be soldered to a thermal pad on the board. For more information, see Texas Instruments literature number SLUA271 (www.ti.com/lit/slua271).
5. Vias are optional depending on application, refer to device data sheet. If any vias are implemented, refer to their locations shown on this view. It is recommended that vias under paste be filled, plugged or tented.![img-41.jpeg](img-41.jpeg)

NOTES: (continued)
6. Laser cutting apertures with trapezoidal walls and rounded corners may offer better paste release. IPC-7525 may have alternate design recommendations.# IMPORTANT NOTICE AND DISCLAIMER 

TI PROVIDES TECHNICAL AND RELIABILITY DATA (INCLUDING DATA SHEETS), DESIGN RESOURCES (INCLUDING REFERENCE DESIGNS), APPLICATION OR OTHER DESIGN ADVICE, WEB TOOLS, SAFETY INFORMATION, AND OTHER RESOURCES "AS IS" AND WITH ALL FAULTS, AND DISCLAIMS ALL WARRANTIES, EXPRESS AND IMPLIED, INCLUDING WITHOUT LIMITATION ANY IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE OR NON-INFRINGEMENT OF THIRD PARTY INTELLECTUAL PROPERTY RIGHTS.
These resources are intended for skilled developers designing with TI products. You are solely responsible for (1) selecting the appropriate TI products for your application, (2) designing, validating and testing your application, and (3) ensuring your application meets applicable standards, and any other safety, security, regulatory or other requirements.
These resources are subject to change without notice. TI grants you permission to use these resources only for development of an application that uses the TI products described in the resource. Other reproduction and display of these resources is prohibited. No license is granted to any other TI intellectual property right or to any third party intellectual property right. TI disclaims responsibility for, and you will fully indemnify TI and its representatives against, any claims, damages, costs, losses, and liabilities arising out of your use of these resources.
TI's products are provided subject to TI's Terms of Sale or other applicable terms available either on ti.com or provided in conjunction with such TI products. TI's provision of these resources does not expand or otherwise alter TI's applicable warranties or warranty disclaimers for TI products.
TI objects to and rejects any additional or different terms you may have proposed.
Mailing Address: Texas Instruments, Post Office Box 655303, Dallas, Texas 75265
Copyright © 2025, Texas Instruments Incorporated