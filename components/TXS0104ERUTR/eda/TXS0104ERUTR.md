# TXS0104E 4-Bit Bidirectional Voltage-Level Translator for Open-Drain and Push-Pull Applications 

## 1 Features

- No direction-control signal needed
- Maximum data rates:
- 24 Mbps (push pull)
- 2Mbps (open drain)
- Available in the Texas Instruments NanoFree ${ }^{\text {TM }}$ package
- 1.65 V to 3.6 V on A port and 2.3 V to 5.5 V on B port $\left(\mathrm{V}_{\mathrm{CCA}} \leq \mathrm{V}_{\mathrm{CCB}}\right)$
- No power-supply sequencing required $-\mathrm{V}_{\mathrm{CCA}}$ or $\mathrm{V}_{\mathrm{CCB}}$ can be ramped first
- Latch-up performance exceeds 100 mA per JESD 78, class II
- ESD protection exceeds JESD 22:
- A port:
- 2000-V Human-Body Model (A114-B)
- 200-V Machine Model (A115-A)
- 1000-V Charged-Device Model (C101)
- B port:
- 15-kV Human-Body Model (A114-B)
- 200-V Machine Model (A115-A)
- 1000-V Charged-Device Model (C101)
- IEC 61000-4-2 ESD (B port):
- $\pm 8-\mathrm{kV}$ contact discharge
- $\pm 10-\mathrm{kV}$ air-gap discharge


## 2 Applications

- Handset
- Smartphone
- Tablet
- Desktop PC


## 3 Description

This 4-bit non-inverting translator uses two separate configurable power-supply rails. The A port is designed to track $\mathrm{V}_{\mathrm{CCA}} . \mathrm{V}_{\mathrm{CCA}}$ accepts any supply voltage from 1.65 V to 3.6 V . $\mathrm{V}_{\mathrm{CCA}}$ must be less than or equal to $\mathrm{V}_{\mathrm{CCB}}$. The B port is designed to track $\mathrm{V}_{\mathrm{CCB}} . \mathrm{V}_{\mathrm{CCB}}$ accepts any supply voltage from 2.3 V to 5.5 V . This allows for low-voltage bidirectional translation between any of the $1.8-\mathrm{V}, 2.5-\mathrm{V}, 3.3-\mathrm{V}$, and $5-\mathrm{V}$ voltage nodes.

When the output-enable (OE) input is low, all outputs are placed in the high-impedance state.

The TXS0104E is designed so that the OE input circuit is supplied by $\mathrm{V}_{\mathrm{CCA}}$.

For the high-impedance state during power up or power down, tie OE to GND through a pulldown resistor; the minimum value of the resistor is determined by the current-sourcing capability of the driver.

Package Information

| PART NUMBER | PACKAGE $^{(1)}$ | PACKAGE SIZE ${ }^{(2)}$ |
| :-- | :-- | :-- |
|  | D (SOIC, 14) | $8.65 \mathrm{~mm} \times 6 \mathrm{~mm}$ |
|  | PW (TSSOP, 14) | $5 \mathrm{~mm} \times 6.4 \mathrm{~mm}$ |
|  | ZXU (BGA, 12) | $2 \mathrm{~mm} \times 2.5 \mathrm{~mm}$ |
|  | RGY (VQFN, 14) | $3.5 \mathrm{~mm} \times 3.5 \mathrm{~mm}$ |
| TXS0104E | YZT (DSBGA, 12) | $2.25 \mathrm{~mm} \times 1.75 \mathrm{~mm}$ |
|  | NMN (nFBGA, 12) | $2 \mathrm{~mm} \times 2.5 \mathrm{~mm}$ |
|  | BQA (WQFN, 12) | $3 \mathrm{~mm} \times 2.5 \mathrm{~mm}$ |
|  | RUT (UQFN, 12) | $2.00 \mathrm{~mm} \times 1.70 \mathrm{~mm}$ |

(1) For all available packages, see the orderable addendum at the end of the data sheet.
(2) The package size (length $\times$ width) is a nominal value and includes pins, where applicable
![img-0.jpeg](img-0.jpeg)

Transfer Characteristics of an N-Channel Transistor# Table of Contents 

1 Features ..... 1
2 Applications ..... 1
3 Description ..... 1
4 Revision History ..... 2
5 Pin Configuration and Functions ..... 4
6 Specifications ..... 8
6.1 Absolute Maximum Ratings ..... 8
6.2 ESD Ratings ..... 8
6.3 Recommended Operating Conditions ..... 9
6.4 Thermal Information: ZXU, YZT, and NMN ..... 9
6.5 Thermal Information: D, PW, and RGY ..... 10
6.6 Electrical Characteristics ..... 10
6.7 Timing Requirements: $\mathrm{V}_{\mathrm{CCA}}=1.8 \mathrm{~V} \pm 0.15 \mathrm{~V}$ ..... 11
6.8 Timing Requirements: $\mathrm{V}_{\mathrm{CCA}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ ..... 11
6.9 Timing Requirements: $\mathrm{V}_{\mathrm{CCA}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ ..... 11
6.10 Switching Characteristics: $\mathrm{V}_{\mathrm{CCA}}=1.8 \mathrm{~V} \pm 0.15 \mathrm{~V}$ ..... 12
6.11 Switching Characteristics: $\mathrm{V}_{\mathrm{CCA}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ ..... 13
6.12 Switching Characteristics: $\mathrm{V}_{\mathrm{CCA}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ ..... 15
6.13 Typical Characteristics ..... 16
7 Parameter Measurement Information ..... 17
7.1 Load Circuits ..... 17
7.2 Voltage Waveforms ..... 18
8 Detailed Description ..... 19
8.1 Overview ..... 19
8.2 Functional Block Diagram ..... 19
8.3 Feature Description ..... 20
8.4 Device Functional Modes ..... 20
9 Application and Implementation ..... 21
9.1 Application Information ..... 21
9.2 Typical Application ..... 21
9.3 Power Supply Recommendations ..... 23
9.4 Layout ..... 23
10 Device and Documentation Support ..... 24
10.1 Documentation Support ..... 24
10.2 Receiving Notification of Documentation Updates ..... 24
10.3 Support Resources ..... 24
10.4 Trademarks ..... 24
10.5 Electrostatic Discharge Caution ..... 24
10.6 Glossary ..... 24
11 Mechanical, Packaging, and Orderable Information ..... 24

## 4 Revision History

NOTE: Page numbers for previous revisions may differ from page numbers in the current version.
Changes from Revision J (August 2023) to Revision K (October 2023) Page

- Added the RUT package ..... 1
Changes from Revision I (October 2020) to Revision J (August 2023) Page
- Updated the Package Information table to include package lead size ..... 1
- Added the $B Q A$ package ..... 1
Changes from Revision H (May 2018) to Revision I (October 2020) Page
- Updated the numbering format for tables, figures, and cross-references throughout the document ..... 1
- Added NMN Package, 12-Pin nFBGA ..... 4
Changes from Revision G (September 2017) to Revision H (May 2018) Page
- Changed maximum values for maximum data rate within Switching Characteristics: $V_{C C A}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ table ..... 15
Changes from Revision F (December 2014) to Revision G (September 2017) Page
- Changed Device Information table ..... 1
- Deleted GXU references throughout ..... 4
- Added Junction temperature in the Absolute Maximum Ratings ..... 8
- Reformatted Electrical Characteristics ..... 10
- Added Receiving Notification of Documentation Updates and Community Resources ..... 24
- Added Basics of Voltage Translation to Related Documentation ..... 24
Changes from Revision E (August 2013) to Revision F (December 2014) Page
- Added Pin Configuration and Functions section, Handling Rating table, Feature Description section, Device Functional Modes, Application and Implementation section, Power Supply Recommendations section, Layoutsection, Device and Documentation Support section, and Mechanical, Packaging, and Orderable Information section ..... 1

- Deleted the Package thermal impedance information from the Absolute max ratings table into the Thermal Information table. Moved the $\mathrm{T}_{\text {stg }}$ row into the new Handling Ratings table. ..... 8
- Changed the last 2 rows of MIN MAX (24 MAX and 2 MAX) to the MIN columns, in the first switching characteristics table ..... 12
Changes from Revision D (May 2008) to Revision E (August 2013) Page
- Deleted the ordering table ..... 1# 5 Pin Configuration and Functions 

![img-1.jpeg](img-1.jpeg)

Figure 5-1. ZXU Package, 12-Pin MICROSTAR JUNIOR (Top View)

| PIN |  | TYPE $^{(1)}$ | DESCRIPTION |
| :--: | :--: | :--: | :--: |
| NO. | NAME |  |  |
| A1 | A1 | I/O | Input/output A1. Referenced to $\mathrm{V}_{\mathrm{CCA}}$. |
| A2 | A2 | I/O | Input/output A2. Referenced to $\mathrm{V}_{\mathrm{CCA}}$. |
| A3 | A3 | I/O | Input/output A3. Referenced to $\mathrm{V}_{\mathrm{CCA}}$. |
| A4 | A4 | I/O | Input/output A4. Referenced to $\mathrm{V}_{\mathrm{CCA}}$. |
| C1 | B1 | I/O | Input/output B1. Referenced to $\mathrm{V}_{\mathrm{CCB}}$. |
| C2 | B2 | I/O | Input/output B2. Referenced to $\mathrm{V}_{\mathrm{CCB}}$. |
| C3 | B3 | I/O | Input/output B3. Referenced to $\mathrm{V}_{\mathrm{CCB}}$. |
| C4 | B4 | I/O | Input/output B4. Referenced to $\mathrm{V}_{\mathrm{CCB}}$. |
| B4 | GND | — | Ground |
| B3 | OE | I | 3-state output-mode enable. Pull OE low to place all outputs in 3-state mode. Referenced to $\mathrm{V}_{\mathrm{CCA}}$. |
| B2 | $\mathrm{V}_{\text {CCA }}$ | — | A-port supply voltage. $1.65 \mathrm{~V} \leq \mathrm{V}_{\mathrm{CCA}} \leq 3.6 \mathrm{~V}$ and $\mathrm{V}_{\mathrm{CCA}} \leq \mathrm{V}_{\mathrm{CCB}}$. |
| B1 | $\mathrm{V}_{\text {CCB }}$ | — | B-port supply voltage. $2.3 \mathrm{~V} \leq \mathrm{V}_{\mathrm{CCB}} \leq 5.5 \mathrm{~V}$. |

(1) $\mathrm{I}=$ input, $\mathrm{O}=$ output![img-2.jpeg](img-2.jpeg)

Figure 5-3. YZT Package, 12-Pin DSBGA (Top View)
Table 5-2. Pin Functions: DSBGA

| PIN |  | TYPE $^{(1)}$ | DESCRIPTION |
| :--: | :--: | :--: | :--: |
| NO. | NAME |  |  |
| A3 | A1 | I/O | Input/output A1. Referenced to $\mathrm{V}_{\mathrm{CCA}}$. |
| B3 | A2 | I/O | Input/output A2. Referenced to $\mathrm{V}_{\mathrm{CCA}}$. |
| C3 | A3 | I/O | Input/output A3. Referenced to $\mathrm{V}_{\mathrm{CCA}}$. |
| D3 | A4 | I/O | Input/output A4. Referenced to $\mathrm{V}_{\mathrm{CCA}}$. |
| A1 | B1 | I/O | Input/output B1. Referenced to $\mathrm{V}_{\mathrm{CCB}}$. |
| B1 | B2 | I/O | Input/output B2. Referenced to $\mathrm{V}_{\mathrm{CCB}}$. |
| C1 | B3 | I/O | Input/output B3. Referenced to $\mathrm{V}_{\mathrm{CCB}}$. |
| D1 | B4 | I/O | Input/output B4. Referenced to $\mathrm{V}_{\mathrm{CCB}}$. |
| D2 | GND | — | Ground |
| C2 | OE | I | 3-state output-mode enable. Pull OE low to place all outputs in 3-state mode. Referenced to $\mathrm{V}_{\mathrm{CCA}}$. |
| B2 | $\mathrm{V}_{\text {CCA }}$ | — | A-port supply voltage. $1.65 \mathrm{~V} \leq \mathrm{V}_{\mathrm{CCA}} \leq 3.6 \mathrm{~V}$ and $\mathrm{V}_{\mathrm{CCA}} \leq \mathrm{V}_{\mathrm{CCB}}$. |
| A2 | $\mathrm{V}_{\text {CCB }}$ | — | B-port supply voltage. $2.3 \mathrm{~V} \leq \mathrm{V}_{\mathrm{CCB}} \leq 5.5 \mathrm{~V}$. |

(1) $\mathrm{I}=$ input, $\mathrm{O}=$ output![img-3.jpeg](img-3.jpeg)
![img-4.jpeg](img-4.jpeg)

NC - No internal connection
Figure 5-5. RGY Package, 14-Pin VQFN (Top View)

NC - No internal connection
Figure 5-4. BQA Package, 14-Pin WQFN (Top View)
![img-5.jpeg](img-5.jpeg)

NC - No internal connection
Figure 5-6. D and PW Package, 14-Pin SOIC and TSSOP (Top View)
Table 5-3. Pin Functions: D, PW, or RGY

| PIN |  | TYPE $^{(1)}$ | DESCRIPTION |
| :--: | :--: | :--: | :--: |
| NAME | NO. |  |  |
| A1 | 2 | I/O | Input/output A1. Referenced to $\mathrm{V}_{\mathrm{CCA}}$. |
| A2 | 3 | I/O | Input/output A2. Referenced to $\mathrm{V}_{\mathrm{CCA}}$. |
| A3 | 4 | I/O | Input/output A3. Referenced to $\mathrm{V}_{\mathrm{CCA}}$. |
| A4 | 5 | I/O | Input/output A4. Referenced to $\mathrm{V}_{\mathrm{CCA}}$. |
| B1 | 13 | I/O | Input/output B1. Referenced to $\mathrm{V}_{\mathrm{CCB}}$. |
| B2 | 12 | I/O | Input/output B2. Referenced to $\mathrm{V}_{\mathrm{CCB}}$. |
| B3 | 11 | I/O | Input/output B3. Referenced to $\mathrm{V}_{\mathrm{CCB}}$. |
| B4 | 10 | I/O | Input/output B4. Referenced to $\mathrm{V}_{\mathrm{CCB}}$. |
| GND | 7 | — | Ground |
| OE | 8 | I | 3-state output-mode enable. Pull OE low to place all outputs in 3-state mode. Referenced to $\mathrm{V}_{\mathrm{CCA}}$. |
| $\mathrm{V}_{\text {CCA }}$ | 1 | — | A-port supply voltage. $1.65 \mathrm{~V} \leq \mathrm{V}_{\mathrm{CCA}} \leq 3.6 \mathrm{~V}$ and $\mathrm{V}_{\mathrm{CCA}} \leq \mathrm{V}_{\mathrm{CCB}}$. |
| $\mathrm{V}_{\text {CCB }}$ | 14 | — | B-port supply voltage. $2.3 \mathrm{~V} \leq \mathrm{V}_{\mathrm{CCB}} \leq 5.5 \mathrm{~V}$. |
| Thermal Pad |  | — | For the RGY package, the exposed center thermal pad must be connected to ground |![img-6.jpeg](img-6.jpeg)

Figure 5-7. RUT Package, 12-Pin UQFN (Transparent Top View)
Table 5-4. Pin Functions: RUT

| PIN |  | TYPE $^{(1)}$ | DESCRIPTION |
| :--: | :--: | :--: | :--: |
| NAME | NO. |  |  |
| A1 | 2 | I/O | Input/output A1. Referenced to $\mathrm{V}_{\text {CCA }}$. |
| A2 | 3 | I/O | Input/output A2. Referenced to $\mathrm{V}_{\text {CCA }}$. |
| A3 | 4 | I/O | Input/output A3. Referenced to $\mathrm{V}_{\text {CCA }}$. |
| A4 | 5 | I/O | Input/output A4. Referenced to $\mathrm{V}_{\text {CCA }}$. |
| B1 | 10 | I/O | Input/output B1. Referenced to $\mathrm{V}_{\text {CCB }}$. |
| B2 | 9 | I/O | Input/output B2. Referenced to $\mathrm{V}_{\text {CCB }}$. |
| B3 | 8 | I/O | Input/output B3. Referenced to $\mathrm{V}_{\text {CCB }}$. |
| B4 | 7 | I/O | Input/output B4. Referenced to $\mathrm{V}_{\text {CCB }}$. |
| GND | 6 | — | Ground |
| OE | 12 | I | 3-state output-mode enable. Pull OE low to place all outputs in 3-state mode. Referenced to $\mathrm{V}_{\text {CCA }}$. |
| $\mathrm{V}_{\text {CCA }}$ | 1 | — | A-port supply voltage. $1.65 \mathrm{~V} \leq \mathrm{V}_{\text {CCA }} \leq 3.6 \mathrm{~V}$ and $\mathrm{V}_{\text {CCA }} \leq \mathrm{V}_{\text {CCB }}$. |
| $\mathrm{V}_{\text {CCB }}$ | 11 | — | A-port supply voltage. $1.65 \mathrm{~V} \leq \mathrm{V}_{\text {CCA }} \leq 3.6 \mathrm{~V}$ and $\mathrm{V}_{\text {CCA }} \leq \mathrm{V}_{\text {CCB }}$. |

(1) $\mathrm{I}=$ input, $\mathrm{O}=$ output# 6 Specifications 

### 6.1 Absolute Maximum Ratings

over operating free-air temperature range (unless otherwise noted) ${ }^{(1)}$

|  |  |  | MIN | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: |
| Supply voltage, $\mathrm{V}_{\mathrm{CCA}}$ |  |  | $-0.5$ | 4.6 | V |
| Supply voltage, $\mathrm{V}_{\mathrm{CCB}}$ |  |  | $-0.5$ | 6.5 | V |
| Input voltage, $\mathrm{V}_{\mathrm{I}}{ }^{(2)}$ |  | A port | $-0.5$ | 4.6 | V |
|  |  | B port | $-0.5$ | 6.5 |  |
| Voltage range applied to any output in the high-impedance or power-off state, $\mathrm{V}_{\mathrm{O}}{ }^{(2)}$ |  | A port | $-0.5$ | 4.6 | V |
|  |  | B port | $-0.5$ | 6.5 |  |
| Voltage range applied to any output in the high or low state, $\mathrm{V}_{\mathrm{O}}{ }^{(2)(3)}$ |  | A port | $-0.5$ | $\mathrm{V}_{\mathrm{CCA}}+0.5$ | V |
|  |  | B port | $-0.5$ | $\mathrm{V}_{\mathrm{CCB}}+0.5$ |  |
| Input clamp current, $\mathrm{I}_{\mathrm{IK}}$ |  | $\mathrm{V}_{\mathrm{I}}<0$ |  | $-50$ | mA |
| Output clamp current, $\mathrm{I}_{\mathrm{OK}}$ |  | $\mathrm{V}_{\mathrm{O}}<0$ |  | $-50$ | mA |
| Continuous output current, $\mathrm{I}_{\mathrm{O}}$ |  |  | $-50$ | 50 | mA |
| Continuous current through each $\mathrm{V}_{\mathrm{CCA}}, \mathrm{V}_{\mathrm{CCB}}$, or GND |  |  | $-100$ | 100 | mA |
| Operating junction temperature, $\mathrm{T}_{\mathrm{J}}$ |  |  |  | 150 | ${ }^{\circ} \mathrm{C}$ |
| Storage temperature, $\mathrm{T}_{\text {STG }}$ |  |  | $-65$ | 150 | ${ }^{\circ} \mathrm{C}$ |

(1) Stresses beyond those listed under Absolute Maximum Ratings may cause permanent damage to the device. These are stress ratings only, and functional operation of the device at these or any other conditions beyond those indicated under Recommended Operating Conditions is not implied. Exposure to absolute-maximum-rated conditions for extended periods may affect device reliability.
(2) The input and output negative-voltage ratings may be exceeded if the input and output current ratings are observed.
(3) The value of $\mathrm{V}_{\mathrm{CCA}}$ and $\mathrm{V}_{\mathrm{CCB}}$ are provided in the recommended operating conditions table.

### 6.2 ESD Ratings

|  |  |  | VALUE | UNIT |
| :--: | :--: | :--: | :--: | :--: |
| $\mathrm{V}_{\text {(ESD) }}$ | Electrostatic discharge | Human body model (HBM), per ANSI/ESDA/JEDEC JS-001, all pins ${ }^{(1)}$ | A Port | $\pm 2000$ | V |
|  |  |  | B Port | $\pm 15$ | kV |
|  |  | Charged device model (CDM), per JEDEC specification JESD22-C101, all pins ${ }^{(2)}$ | A Port | $\pm 1000$ | V |
|  |  |  | B Port | $\pm 1000$ |  |
|  |  | Machine model (MM) | A Port | $\pm 200$ | V |
|  |  |  | B Port | $\pm 200$ |  |

(1) JEDEC document JEP155 states that $500-\mathrm{V}$ HBM allows safe manufacturing with a standard ESD control process.
(2) JEDEC document JEP157 states that $250-\mathrm{V}$ CDM allows safe manufacturing with a standard ESD control process.# 6.3 Recommended Operating Conditions 

over operating free-air temperature range (unless otherwise noted) ${ }^{(1)(2)}$

|  |  |  | $\mathrm{V}_{\text {CCA }}$ | $\mathrm{V}_{\text {CCB }}$ | MIN | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{V}_{\text {CCA }}$ | Supply voltage ${ }^{(3)}$ |  |  |  | 1.65 | 3.6 | V |
| $\mathrm{V}_{\text {CCB }}$ | Supply voltage ${ }^{(3)}$ |  |  |  | 2.3 | 5.5 | V |
| $\mathrm{V}_{\text {IH }}$ | High-level input voltage | A-port I/Os | 1.65 V to 1.95 V | 2.3 V to 5.5 V | $\mathrm{V}_{\mathrm{CCI}}-0.2$ | $\mathrm{V}_{\mathrm{CCI}}$ | V |
|  |  |  | 2.3 V to 3.6 V | 2.3 V to 5.5 V | $\mathrm{V}_{\mathrm{CCI}}-0.4$ | $\mathrm{V}_{\mathrm{CCI}}$ |  |
|  |  | B-port I/Os | 1.65 V to 3.6 V | 2.3 V to 5.5 V | $\mathrm{V}_{\mathrm{CCI}}-0.4$ | $\mathrm{V}_{\mathrm{CCI}}$ |  |
|  |  | OE input | 1.65 V to 3.6 V | 2.3 V to 5.5 V | $\mathrm{V}_{\mathrm{CCA}} \times 0.65$ | 5.5 |  |
| $\mathrm{V}_{\text {IL }}$ | Low-level input voltage | A-port I/Os | 1.65 V to 3.6 V | 2.3 V to 5.5 V | 0 | 0.15 | V |
|  |  | B-port I/Os | 1.65 V to 3.6 V | 2.3 V to 5.5 V | 0 | 0.15 |  |
|  |  | OE input | 1.65 V to 3.6 V | 2.3 V to 5.5 V | 0 | $\mathrm{V}_{\mathrm{CCA}} \times 0.35$ |  |
| $\Delta t / \Delta v$ | Input transition rise or fall rate | A-port I/Os push-pull driving | 1.65 V to 3.6 V | 2.3 V to 5.5 V |  | 10 | $\mathrm{ns} / \mathrm{V}$ |
|  |  | B-port I/Os push-pull driving | 1.65 V to 3.6 V | 2.3 V to 5.5 V |  | 10 |  |
|  |  | Control input | 1.65 V to 3.6 V | 2.3 V to 5.5 V |  | 10 |  |
| $T_{A}$ | Operating free-air temperature |  |  |  | $-40$ | 85 | ${ }^{\circ} \mathrm{C}$ |

(1) $\mathrm{V}_{\mathrm{CCI}}$ is the supply voltage associated with the input port.
(2) $\mathrm{V}_{\mathrm{CCO}}$ is the supply voltage associated with the output port.
(3) $\mathrm{V}_{\mathrm{CCA}}$ must be less than or equal to $\mathrm{V}_{\mathrm{CCB}}$, and $\mathrm{V}_{\mathrm{CCA}}$ must not exceed 3.6 V .

### 6.4 Thermal Information: ZXU, YZT, and NMN

| THERMAL METRIC ${ }^{(1)}$ |  | TXS0104E |  |  | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | ZXU <br> (BGA MICROSTAR JUNIOR) ${ }^{(2)}$ | YZT <br> (DSBGA) | NMN <br> (NFGBA) |  |
|  |  | 12 PINS | 12 PINS | 12 PINS |  |
| $R_{B, I A}$ | Junction-to-ambient thermal resistance | 132.0 | 89.2 | 134.3 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $R_{B, I C(I n p)}$ | Junction-to-case (top) thermal resistance | 98.4 | 0.9 | 90.7 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $R_{B, I B}$ | Junction-to-board thermal resistance | 68.7 | 14.4 | 88.4 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $\psi_{J T}$ | Junction-to-top characterization parameter | 3.1 | 3.0 | 4.3 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $\psi_{J B}$ | Junction-to-board characterization parameter | 68.2 | 14.4 | 89.3 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |

(1) For more information about traditional and new thermal metrics, see the Semiconductor and IC Package Thermal Metrics application report.# 6.5 Thermal Information: D, PW, and RGY 

| THERMAL METRIC ${ }^{(1)}$ |  | TXS0104E |  |  | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | D <br> (SOIC) ${ }^{(1)}$ | PW <br> (TSSOP) ${ }^{(2)}$ | RGY <br> (VQFN) ${ }^{(3)}$ |  |
|  |  | 14 PINS | 14 PINS | 14 PINS |  |
| $R_{B, U A}$ | Junction-to-ambient thermal resistance | 90.4 | 120.1 | 56.1 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $R_{B, \text { (COn) }}$ | Junction-to-case (top) thermal resistance | 50.1 | 49.4 | 68.8 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $R_{B, B B}$ | Junction-to-board thermal resistance | 45.0 | 61.8 | 32.1 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $\psi_{J T}$ | Junction-to-top characterization parameter | 14.4 | 6.2 | 3.1 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $\psi_{J B}$ | Junction-to-board characterization parameter | 44.7 | 61.2 | 32.3 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $R_{B, \text { (COn) }}$ | Junction-to-case (bottom) thermal resistance | - | - | 12.8 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |

(1) For more information about traditional and new thermal metrics, see the Semiconductor and IC Package Thermal Metrics application report.
(2) The package thermal impedance is calculated in accordance with JESD 51-7.
(3) The package thermal impedance is calculated in accordance with JESD 51-5.

### 6.6 Electrical Characteristics

over recommended operating free-air temperature range (unless otherwise noted) ${ }^{(1)}$ (2) (3)

| PARAMETER |  | TEST CONDITIONS | $\mathrm{V}_{\text {CCA }}$ | $\mathrm{V}_{\text {CCB }}$ | MIN | TYP | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V_{\text {OHA }}$ | Port A output high voltage | $\begin{aligned} & \mathrm{I}_{\mathrm{OH}}=-20 \mu \mathrm{~A}, \\ & \mathrm{~V}_{\mathrm{IB}} \geq \mathrm{V}_{\mathrm{CCB}}-0.4 \mathrm{~V} \\ & \mathrm{~T}_{\mathrm{A}}=-40^{\circ} \mathrm{C} \text { to } 85^{\circ} \mathrm{C} \end{aligned}$ | 1.65 V to 3.6 V | 2.3 V to 5.5 V | $\mathrm{V}_{\text {CCA }} \times 0.8$ |  |  | V |
| $V_{\text {OLA }}$ | Port A output low voltage | $\begin{aligned} & \mathrm{I}_{\mathrm{OL}}=1 \mathrm{~mA}, \\ & \mathrm{~V}_{\mathrm{IB}} \leq 0.15 \mathrm{~V} \\ & \mathrm{~T}_{\mathrm{A}}=-40^{\circ} \mathrm{C} \text { to } 85^{\circ} \mathrm{C} \end{aligned}$ | 1.65 V to 3.6 V | 2.3 V to 5.5 V |  |  | 0.4 | V |
| $V_{\text {OHB }}$ | Port B output high voltage | $\begin{aligned} & \mathrm{I}_{\mathrm{OH}}=-20 \mu \mathrm{~A}, \\ & \mathrm{~V}_{\mathrm{IA}} \geq \mathrm{V}_{\mathrm{CCA}}-0.2 \mathrm{~V} \\ & \mathrm{~T}_{\mathrm{A}}=-40^{\circ} \mathrm{C} \text { to } 85^{\circ} \mathrm{C} \end{aligned}$ | 1.65 V to 3.6 V | 2.3 V to 5.5 V | $\mathrm{V}_{\text {CCB }} \times 0.8$ |  |  | V |
| $V_{\text {OLB }}$ | Port B output low voltage | $\begin{aligned} & \mathrm{I}_{\mathrm{OL}}=1 \mathrm{~mA}, \\ & \mathrm{~V}_{\mathrm{IA}} \leq 0.15 \mathrm{~V} \\ & \mathrm{~T}_{\mathrm{A}}=-40^{\circ} \mathrm{C} \text { to } 85^{\circ} \mathrm{C} \end{aligned}$ | 1.65 V to 3.6 V | 2.3 V to 5.5 V |  |  | 0.4 | V |
| $I_{t}$ | Input leakage current | $\begin{aligned} & \mathrm{OE}: \\ & \mathrm{V}_{\mathrm{I}}=\mathrm{V}_{\mathrm{CCI}} \text { or GND } \\ & \mathrm{T}_{\mathrm{A}}=25^{\circ} \mathrm{C} \end{aligned}$ | 1.65 V to 3.6 V | 2.3 V to 5.5 V | $-1$ |  | 1 | $\mu \mathrm{A}$ |
|  |  | $\begin{aligned} & \mathrm{V}_{\mathrm{I}}=\mathrm{V}_{\mathrm{CCI}} \text { or GND } \\ & \mathrm{T}_{\mathrm{A}}=-40^{\circ} \mathrm{C} \text { to } 85^{\circ} \mathrm{C} \end{aligned}$ | 1.65 V to 3.6 V | 2.3 V to 5.5 V | $-2$ |  | 2 |  |
| $\mathrm{I}_{\mathrm{OZ}}$ | High-impedance state output current | A or B port: <br> $\mathrm{OE}=\mathrm{V}_{\mathrm{IL}}$ <br> $\mathrm{T}_{\mathrm{A}}=25^{\circ} \mathrm{C}$ | 1.65 V to 3.6 V | 2.3 V to 5.5 V | $-1$ |  | 1 | $\mu \mathrm{A}$ |
|  |  | A or B port: <br> $\mathrm{OE}=\mathrm{V}_{\mathrm{IL}}$ <br> $\mathrm{T}_{\mathrm{A}}=-40^{\circ} \mathrm{C}$ to $85^{\circ} \mathrm{C}$ | 1.65 V to 3.6 V | 2.3 V to 5.5 V | $-2$ |  | 2 |  |
| $\mathrm{I}_{\text {CCA }}$ | $V_{\text {CCA }}$ supply current | $\begin{aligned} & \mathrm{V}_{\mathrm{I}}=\mathrm{V}_{\mathrm{O}}=\text { Open, } \\ & \mathrm{I}_{\mathrm{O}}=0 \\ & \mathrm{~T}_{\mathrm{A}}=-40^{\circ} \mathrm{C} \text { to } 85^{\circ} \mathrm{C} \end{aligned}$ | 1.65 V to $\mathrm{V}_{\text {CCB }}$ | 2.3 V to 5.5 V |  |  | 2.4 | $\mu \mathrm{A}$ |
|  |  |  | 3.6 V | 0 |  |  | 2.2 |  |
|  |  |  | 0 | 5.5 V |  |  | $-1$ |  |
| $\mathrm{I}_{\text {CCB }}$ | $V_{\text {CCB }}$ supply current | $\begin{aligned} & \mathrm{V}_{\mathrm{I}}=\mathrm{V}_{\mathrm{O}}=\text { Open, } \\ & \mathrm{I}_{\mathrm{O}}=0 \\ & \mathrm{~T}_{\mathrm{A}}=-40^{\circ} \mathrm{C} \text { to } 85^{\circ} \mathrm{C} \end{aligned}$ | 1.65 V to $\mathrm{V}_{\text {CCB }}$ | 2.3 V to 5.5 V |  |  | 12 | $\mu \mathrm{A}$ |
|  |  |  | 3.6 V | 0 |  |  | $-1$ |  |
|  |  |  | 0 | 5.5 V |  |  | 1 |  |
| $\mathrm{I}_{\text {CCA }}+$ ICCB | Combined supply current | $\begin{aligned} & \mathrm{V}_{\mathrm{I}}=\mathrm{V}_{\mathrm{O}}=\text { Open, } \\ & \mathrm{I}_{\mathrm{O}}=0 \\ & \mathrm{~T}_{\mathrm{A}}=-40^{\circ} \mathrm{C} \text { to } 85^{\circ} \mathrm{C} \end{aligned}$ | 1.65 V to $\mathrm{V}_{\text {CCB }}$ | 2.3 V to 5.5 V |  |  | 14.4 | $\mu \mathrm{A}$ |
| $C_{t}$ | Input capacitance | $\begin{aligned} & \mathrm{OE}: \\ & \mathrm{T}_{\mathrm{A}}=25^{\circ} \mathrm{C} \end{aligned}$ | 3.3 V | 3.3 V |  | 2.5 |  | pF |
|  |  | $\begin{aligned} & \mathrm{OE}: \\ & \mathrm{T}_{\mathrm{A}}=-40^{\circ} \mathrm{C} \text { to } 85^{\circ} \mathrm{C} \end{aligned}$ | 3.3 V | 3.3 V |  |  | 3.5 |  |# 6.6 Electrical Characteristics (continued) 

over recommended operating free-air temperature range (unless otherwise noted) ${ }^{(1)(2)(3)}$

| PARAMETER |  | TEST CONDITIONS | $\mathrm{V}_{\mathrm{CCA}}$ | $\mathrm{V}_{\mathrm{CCB}}$ | MIN | TYP | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{C}_{\text {to }}$ | Input-to-output <br> internal capacitance | A port: $\mathrm{T}_{\mathrm{A}}=25^{\circ} \mathrm{C}$ | 3.3 V | 3.3 V |  | 5 |  | pF |
|  |  |  | 3.3 V | 3.3 V |  |  | 6.5 |  |
|  |  | B port: $\mathrm{T}_{\mathrm{A}}=-40^{\circ} \mathrm{C}$ to $85^{\circ} \mathrm{C}$ | 3.3 V | 3.3 V |  | 12 |  |  |
|  |  |  | 3.3 V | 3.3 V |  |  | 16.5 |  |

(1) $\mathrm{V}_{\mathrm{CCI}}$ is the supply voltage associated with the input port.
(2) $\mathrm{V}_{\mathrm{CCO}}$ is the supply voltage associated with the output port.
(3) $\mathrm{V}_{\mathrm{CCA}}$ must be less than or equal to $\mathrm{V}_{\mathrm{CCB}}$, and $\mathrm{V}_{\mathrm{CCA}}$ must not exceed 3.6 V .

### 6.7 Timing Requirements: $\mathrm{V}_{\mathrm{CCA}}=1.8 \mathrm{~V} \pm 0.15 \mathrm{~V}$

over recommended operating free-air temperature range, $\mathrm{V}_{\mathrm{CCA}}=1.8 \mathrm{~V} \pm 0.15 \mathrm{~V}$ (unless otherwise noted)

|  |  |  |  | MIN | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Data rate | Push-pull driving |  | $\begin{aligned} & \mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V} \\ & \mathrm{~V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V} \\ & \mathrm{~V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V} \end{aligned}$ | 24 | Mbps |
|  | Open-drain driving |  | $\begin{aligned} & \mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V} \\ & \mathrm{~V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V} \\ & \mathrm{~V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V} \end{aligned}$ | 2 |  |
| $t_{w}$ Pulse duration | Push-pull driving | Data inputs | $\begin{aligned} & \mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V} \\ & \mathrm{~V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V} \\ & \mathrm{~V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V} \end{aligned}$ | 41 |  | ns |
|  | Open-drain driving | Data inputs | $\begin{aligned} & \mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V} \\ & \mathrm{~V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V} \\ & \mathrm{~V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V} \end{aligned}$ | 500 |  |

### 6.8 Timing Requirements: $\mathrm{V}_{\mathrm{CCA}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$

over recommended operating free-air temperature range, $\mathrm{V}_{\mathrm{CCA}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ (unless otherwise noted)

|  |  |  |  | MIN | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Data rate | Push-pull driving |  | $\begin{aligned} & \mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V} \\ & \mathrm{CCB}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V} \\ & \mathrm{CCB}=5 \mathrm{~V} \pm 0.5 \mathrm{~V} \end{aligned}$ | 24 | Mbps |
|  | Open-drain driving |  | $\begin{aligned} & \mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V} \\ & \mathrm{CCB}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V} \\ & \mathrm{CCB}=5 \mathrm{~V} \pm 0.5 \mathrm{~V} \end{aligned}$ | 2 |  |
| $t_{w}$ Pulse duration | Push-pull driving | Data inputs | $\begin{aligned} & \mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V} \\ & \mathrm{CCB}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V} \\ & \mathrm{CCB}=5 \mathrm{~V} \pm 0.5 \mathrm{~V} \end{aligned}$ | 41 |  | ns |
|  | Open-drain driving | Data inputs | $\begin{aligned} & \mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V} \\ & \mathrm{CCB}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V} \\ & \mathrm{CCB}=5 \mathrm{~V} \pm 0.5 \mathrm{~V} \end{aligned}$ | 500 |  |

### 6.9 Timing Requirements: $\mathrm{V}_{\mathrm{CCA}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$

over recommended operating free-air temperature range, $\mathrm{V}_{\mathrm{CCA}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ (unless otherwise noted)

|  |  |  |  | MIN | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Data rate | Push-pull driving |  | $\begin{aligned} & \mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V} \\ & \mathrm{~V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V} \end{aligned}$ | 24 | Mbps |
|  | Open-drain driving |  | $\begin{aligned} & \mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V} \\ & \mathrm{~V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V} \end{aligned}$ | 2 |  |
| $t_{w}$ Pulse duration | Push-pull driving | Data inputs | $\begin{aligned} & \mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V} \\ & \mathrm{~V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V} \end{aligned}$ | 41 |  | ns |
|  | Open-drain driving | Data inputs | $\begin{aligned} & \mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V} \\ & \mathrm{~V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V} \end{aligned}$ | 500 |  |# 6.10 Switching Characteristics: $\mathrm{V}_{\mathrm{CCA}}=1.8 \mathrm{~V} \pm 0.15 \mathrm{~V}$ 

over recommended operating free-air temperature range, $\mathrm{V}_{\mathrm{CCA}}=1.8 \mathrm{~V} \pm 0.15 \mathrm{~V}$ (unless otherwise noted)

| PARAMETER |  | TEST CONDITIONS |  |  | MIN | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{\text {PHL }}$ | Propagation <br> delay time <br> (high-to-low output) | A-to-B | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ |  | 4.6 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 4.7 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 5.8 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 2.9 | 8.8 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 2.9 | 9.6 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 3 | 10 |  |
| $t_{\text {PLH }}$ | Propagation <br> delay time <br> (low-to-high output) |  | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ |  | 6.8 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 6.8 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 7 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 45 | 260 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 36 | 208 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 27 | 198 |  |
| $t_{\text {PHL }}$ | Propagation <br> delay time <br> (high-to-low output) | B-to-A | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ |  | 4.4 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 4.5 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 4.7 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 1.9 | 5.3 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 1.1 | 4.4 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 1.2 | 4 |  |
| $t_{\text {PLH }}$ | Propagation <br> delay time <br> (low-to-high output) |  | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ |  | 5.3 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 4.5 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 0.5 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 45 | 175 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 36 | 140 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 27 | 102 |  |
| $t_{\text {en }}$ | Enable time | OE-to-A or B |  | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ |  | 200 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 200 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 200 |  |
| $t_{\text {dis }}$ | Disable time | OE-to-A or B |  | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ |  | 50 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 40 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 35 |  |
| $t_{r A}$ | Input rise time | A-port rise time | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 3.2 | 9.5 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 2.3 | 9.3 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 2 | 7.6 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 38 | 165 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 30 | 132 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 22 | 95 |  |
| $t_{r B}$ | Input rise time | B-port rise time | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 4 | 10.8 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 2.7 | 9.1 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 2.7 | 7.6 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 34 | 145 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 23 | 106 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 10 | 58 |  |# 6.10 Switching Characteristics: $\mathrm{V}_{\mathrm{CCA}}=1.8 \mathrm{~V} \pm 0.15 \mathrm{~V}$ (continued) 

over recommended operating free-air temperature range, $\mathrm{V}_{\mathrm{CCA}}=1.8 \mathrm{~V} \pm 0.15 \mathrm{~V}$ (unless otherwise noted)

| PARAMETER |  | TEST CONDITIONS |  |  | MIN | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{R A}$ | Input fall time | A-port fall time | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 2 | 5.9 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 1.9 | 6 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 1.7 | 13.3 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 4.4 | 6.9 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 4.3 | 6.4 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 4.2 | 6.1 |  |
| $t_{R B}$ | Input fall time | B-port fall time | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 2.9 | 7.6 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 2.8 | 7.5 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 2.8 | 8.8 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 6.9 | 13.8 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 7.5 | 16.2 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 7 | 16.2 |  |
| $\mathrm{t}_{\mathrm{SK(0)}}$ | Skew (time), output | Channel-to-channel skew |  | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ |  | 1 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 1 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 1 |  |
| Maximum data rate |  |  | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 24 | Mbps |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 24 |  |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 24 |  |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 2 |  |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 2 |  |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 2 |  |  |

### 6.11 Switching Characteristics: $\mathrm{V}_{\mathrm{CCA}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$

over recommended operating free-air temperature range, $\mathrm{V}_{\mathrm{CCA}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ (unless otherwise noted)

| PARAMETER |  | TEST CONDITIONS |  |  | MIN | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{P H L}$ | Propagation delay time (high-to-low output) | A-to-B | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ |  | 3.2 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 3.3 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 3.4 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 1.7 | 6.3 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 2 | 6 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 2.1 | 5.8 |  |
| $t_{P L H}$ | Propagation delay time (low-to-high output) | A-to-B | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ |  | 3.5 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 4.1 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 4.4 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 43 | 250 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 36 | 206 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 27 | 190 |  |
| $t_{P H L}$ | Propagation delay time (high-to-low output) | B-to-A | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ |  | 3 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 3.6 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 4.3 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 1.8 | 4.7 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 2.6 | 4.2 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 1.2 | 4 |  |# 6.11 Switching Characteristics: $\mathrm{V}_{\mathrm{CCA}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ (continued) 

over recommended operating free-air temperature range, $\mathrm{V}_{\mathrm{CCA}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ (unless otherwise noted)

| PARAMETER |  | TEST CONDITIONS |  |  | MIN | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{\text {PLH }}$ | Propagation <br> delay time <br> (low-to-high output) | B-to-A | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ |  | 2.5 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 1.6 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 0.7 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 44 | 170 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 37 | 140 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 27 | 103 |  |
| $t_{\text {en }}$ | Enable time | OE-to-A or B |  | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ |  | 200 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 200 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 200 |  |
| $t_{\text {dis }}$ | Disable time | OE-to-A or B |  | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ |  | 50 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 40 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 35 |  |
| $t_{r A}$ | Input rise time | A-port rise time | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 2.8 | 7.4 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 2.6 | 6.6 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 1.8 | 5.6 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 34 | 149 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 28 | 121 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 24 | 89 |  |
| $t_{r B}$ | Input rise time | B-port rise time | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 3.2 | 8.3 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 2.9 | 7.2 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 2.4 | 6.1 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 35 | 151 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 24 | 112 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 12 | 64 |  |
| $t_{f A}$ | Input fall time | A-port fall time | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 1.9 | 5.7 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 1.9 | 5.5 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 1.8 | 5.3 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 4.4 | 6.9 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 4.3 | 6.2 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 4.2 | 5.8 |  |
| $t_{f B}$ | Input fall time | B-port fall time | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 2.2 | 7.8 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 2.4 | 6.7 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 2.6 | 6.6 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ | 5.1 | 8.8 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 5.4 | 9.4 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 5.4 | 10.4 |  |
| $t_{S K(O)}$ | Skew (time), output | Channel-to-channel skew |  | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ |  | 1 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 1 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 1 |  |# 6.11 Switching Characteristics: $\mathrm{V}_{\mathrm{CCA}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ (continued) 

over recommended operating free-air temperature range, $\mathrm{V}_{\mathrm{CCA}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ (unless otherwise noted)

| PARAMETER |  | TEST CONDITIONS |  |  | MIN | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Maximum data rate |  | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ |  | 24 |  | Mbps |
|  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 24 |  |
|  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 24 |  |
|  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=2.5 \mathrm{~V} \pm 0.2 \mathrm{~V}$ |  | 2 |  |
|  |  |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 2 |  |
|  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 2 |  |

### 6.12 Switching Characteristics: $\mathrm{V}_{\mathrm{CCA}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$

over recommended operating free-air temperature range, $\mathrm{V}_{\mathrm{CCA}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ (unless otherwise noted)

| PARAMETER |  | TEST CONDITIONS |  |  | MIN | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{\text {PHL }}$ | Propagation <br> delay time <br> (high-to-low output) | A-to-B | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 2.4 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 3.1 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 1.3 | 4.2 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 1.4 | 4.6 |  |
| $t_{\text {PLH }}$ | Propagation <br> delay time <br> (low-to-high output) |  | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 4.2 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 4.4 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 36 | 204 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 28 | 165 |  |
| $t_{\text {PHL }}$ | Propagation <br> delay time <br> (high-to-low output) | B-to-A | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 2.5 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 3.3 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 1 | 124 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 1 | 97 |  |
| $t_{\text {PLH }}$ | Propagation <br> delay time <br> (low-to-high output) |  | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 2.5 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 2.6 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 3 | 139 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 3 | 105 |  |
| $t_{\text {en }}$ | Enable time | OE-to-A or B |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 200 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 200 |  |
| $t_{\text {dis }}$ | Disable time | OE-to-A or B |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 40 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 35 |  |
| $t_{r A}$ | Input rise time | A-port rise time | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 2.3 | 5.6 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 1.9 | 4.8 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 25 | 116 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 19 | 85 |  |
| $t_{r B}$ | Input rise time | B-port rise time | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 2.5 | 6.4 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 2.1 | 7.4 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 26 | 116 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 26 | 116 |  |
| $t_{f A}$ | Input fall time | A-port fall time | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 2 | 5.4 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 1.9 | 5 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 4.3 | 6.1 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 4.2 | 5.7 |  |# 6.12 Switching Characteristics: $\mathrm{V}_{\mathrm{CCA}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ (continued) 

over recommended operating free-air temperature range, $\mathrm{V}_{\mathrm{CCA}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ (unless otherwise noted)

| PARAMETER |  | TEST CONDITIONS |  |  | MIN | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{R B}$ | Input fall time | B-port fall time | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 2.3 | 7.4 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 2.4 | 7.6 |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 5 | 7.6 |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 4.8 | 8.3 |  |
| $t_{\text {SK(O) }}$ | Skew (time), output | Channel-to-channel skew |  | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ |  | 1 | ns |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ |  | 1 |  |
| Maximum data rate |  |  | Push-pull driving | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 24 |  | Mbps |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 24 |  |  |
|  |  |  | Open-drain driving | $\mathrm{V}_{\mathrm{CCB}}=3.3 \mathrm{~V} \pm 0.3 \mathrm{~V}$ | 2 |  |  |
|  |  |  |  | $\mathrm{V}_{\mathrm{CCB}}=5 \mathrm{~V} \pm 0.5 \mathrm{~V}$ | 2 |  |  |

### 6.13 Typical Characteristics

![img-7.jpeg](img-7.jpeg)

Figure 6-1. Low-Level Output Voltage $\left(\mathrm{V}_{\mathrm{OL}(\mathrm{Ax})}\right)$ vs Low-Level Current $\left(\mathrm{I}_{\mathrm{OL}(\mathrm{Ax})}\right)$
![img-8.jpeg](img-8.jpeg)

Figure 6-2. Low-Level Output Voltage ( $\mathrm{V}_{\mathrm{OL}(\mathrm{Ax})}$ ) vs Low-Level Current ( $\mathrm{I}_{\mathrm{OL}(\mathrm{Ax})}$ )
![img-9.jpeg](img-9.jpeg)

Figure 6-3. Low-Level Output Voltage ( $\mathrm{V}_{\mathrm{OL}(\mathrm{Ax})}$ ) vs Low-Level Current ( $\mathrm{I}_{\mathrm{OL}(\mathrm{Ax})}$ )# 7 Parameter Measurement Information 

### 7.1 Load Circuits

![img-10.jpeg](img-10.jpeg)

Figure 7-1. Data Rate, Pulse Duration, Propagation Delay, Output Rise-Time and Fall-Time Measurement Using a Push-Pull Driver
![img-11.jpeg](img-11.jpeg)

Figure 7-2. Data Rate, Pulse Duration, Propagation Delay, Output Rise-Time and Fall-Time Measurement Using an Open-Drain Driver
![img-12.jpeg](img-12.jpeg)

Figure 7-3. Load Circuit for Enable-Time and Disable-Time Measurement

1. $t_{P L Z}$ and $t_{P H Z}$ are the same as $t_{d i s}$.
2. $t_{P Z L}$ and $t_{P Z H}$ are the same as $t_{e n}$.
3. $\mathrm{V}_{\mathrm{CCI}}$ is the $\mathrm{V}_{\mathrm{CC}}$ associated with the input port.
4. $\mathrm{V}_{\mathrm{CCO}}$ is the $\mathrm{V}_{\mathrm{CC}}$ associated with the output port.# 7.2 Voltage Waveforms 

The outputs are measured one at a time, with one transition per measurement. All input pulses are supplied by generators that have the following characteristics:

- PRR $\leq 10 \mathrm{MHz}$
- $Z_{O}=50 \Omega$
- $\mathrm{dv} / \mathrm{dt} \geq 1 \mathrm{~V} / \mathrm{ns}$
![img-13.jpeg](img-13.jpeg)

Figure 7-4. Pulse Duration
![img-14.jpeg](img-14.jpeg)

Figure 7-5. Propagation Delay Times
![img-15.jpeg](img-15.jpeg)
A. Waveform 1 is for an output with internal such that the output is high, except when OE is high (see Figure 7-3).
B. Waveform 2 is for an output with conditions such that the output is low, except when OE is high.

Figure 7-6. Enable and Disable Times# 8 Detailed Description 

### 8.1 Overview

The TXS0104E device is a directionless voltage-level translator specifically designed for translating logic voltage levels. The A port is able to accept I/O voltages ranging from 1.65 V to 3.6 V , while the B port can accept I/O voltages from 2.3 V to 5.5 V . The device is a pass gate architecture with edge rate accelerators (one shots) to improve the overall data rate. $10-\mathrm{k} \Omega$ pullup resistors, commonly used in open drain applications, have been conveniently integrated so that an external resistor is not needed. While this device is designed for open drain applications, the device can also translate push-pull CMOS logic outputs.

### 8.2 Functional Block Diagram

![img-16.jpeg](img-16.jpeg)# 8.3 Feature Description 

### 8.3.1 Architecture

The TXS0104E architecture (see Figure 8-1) does not require a direction-control signal in order to control the direction of data flow from $A$ to $B$ or from $B$ to $A$.
![img-17.jpeg](img-17.jpeg)

Figure 8-1. Architecture of a TXS01xx Cell
Each A-port I/O has an internal $10-\mathrm{k} \Omega$ pullup resistor to $\mathrm{V}_{\mathrm{CCA}}$, and each B-port I/O has an internal $10-\mathrm{k} \Omega$ pullup resistor to $\mathrm{V}_{\mathrm{CCB}}$. The output one-shots detect rising edges on the A or B ports. During a rising edge, the one-shot turns on the PMOS transistors (T1, T2) for a short duration which speeds up the low-to-high transition.

### 8.3.2 Input Driver Requirements

The fall time $\left(t_{f A}, t_{f B}\right)$ of a signal depends on the output impedance of the external device driving the data I/Os of the TXS0104E device. Similarly, the $t_{\text {PHL }}$ and maximum data rates also depend on the output impedance of the external driver. The values for $t_{f A}, t_{f B}, t_{P H L}$, and maximum data rates in the data sheet assume that the output impedance of the external driver is less than $50 \Omega$.

### 8.3.3 Power Up

During operation, ensure that $\mathrm{V}_{\mathrm{CCA}} \leq \mathrm{V}_{\mathrm{CCB}}$ at all times. During power-up sequencing, $\mathrm{V}_{\mathrm{CCA}} \geq \mathrm{V}_{\mathrm{CCB}}$ does not damage the device, so any power supply can be ramped up first.

### 8.3.4 Enable and Disable

The TXS0104E device has an OE input that disables the device by setting OE low, which places all I/Os in the high-impedance state. The disable time ( $\mathrm{t}_{\text {dis }}$ ) indicates the delay between the time when the OE pin goes low and when the outputs actually enter the high-impedance state. The enable time ( $t_{\text {en }}$ ) indicates the amount of time the user must allow for the one-shot circuitry to become operational after the OE pin is taken high.

### 8.3.5 Pullup and Pulldown Resistors on I/O Lines

Each A-port I/O has an internal $10-\mathrm{k} \Omega$ pullup resistor to $\mathrm{V}_{\mathrm{CCA}}$, and each B-port I/O has an internal $10-\mathrm{k} \Omega$ pullup resistor to $\mathrm{V}_{\mathrm{CCB}}$. If a smaller value of pullup resistor is required, an external resistor must be added from the I/O to $\mathrm{V}_{\mathrm{CCA}}$ or $\mathrm{V}_{\mathrm{CCB}}$ (in parallel with the internal $10-\mathrm{k} \Omega$ resistors).

### 8.4 Device Functional Modes

The TXS0104E device has two functional modes, enabled and disabled. To disable the device set the OE input low, which places all I/Os in a high impedance state. Setting the OE input high will enable the device.# 9 Application and Implementation 

## Note

Information in the following applications sections is not part of the TI component specification, and TI does not warrant its accuracy or completeness. TI's customers are responsible for determining suitability of components for their purposes, as well as validating and testing their design implementation to confirm system functionality.

### 9.1 Application Information

The TXS0104E device can be used in level-translation applications for interfacing devices or systems operating at different interface voltages with one another. The TXS0104E device is an excellent choice for applications where an open-drain driver is connected to the data I/Os. The TXS0104E device can also be used in applications where a push-pull driver is connected to the data I/Os, but the TXB0104 device might be a better option for such push-pull applications.

### 9.2 Typical Application

![img-18.jpeg](img-18.jpeg)

Figure 9-1. Application Schematic

### 9.2.1 Design Requirements

For this design example, use the parameters listed in Table 9-1.
Table 9-1. Design Parameters

| DESIGN PARAMETER | EXAMPLE VALUE |
| :--: | :--: |
| Input voltage range | 1.65 to 3.6 V |
| Output voltage range | 2.3 to 5.5 V |# 9.2.2 Detailed Design Procedure 

To begin the design process, determine the following:

- Input voltage range
- Use the supply voltage of the device that is driving the TXS0104E device to determine the input voltage range. For a valid logic high the value must exceed the $\mathrm{V}_{\mathrm{IH}}$ of the input port. For a valid logic low the value must be less than the $\mathrm{V}_{\mathrm{IL}}$ of the input port.
- Output voltage range
- Use the supply voltage of the device that the TXS0104E device is driving to determine the output voltage range.
- The TXS0104E device has 10-k $\Omega$ internal pullup resistors. External pullup resistors can be added to reduce the total RC of a signal trace if necessary.
- An external pull down resistor decreases the output $\mathrm{V}_{\mathrm{OH}}$ and $\mathrm{V}_{\mathrm{OL}}$. Use Equation 1 to calculate the $\mathrm{V}_{\mathrm{OH}}$ as a result of an external pull down resistor.

$$
V_{O H}=V_{C C x} \times R_{P D} /\left(R_{P D}+10 k \Omega\right)
$$

where
$\mathrm{V}_{\mathrm{CCx}}$ is the supply voltage on either $\mathrm{V}_{\mathrm{CCA}}$ or $\mathrm{V}_{\mathrm{CCB}}$
$R_{P D}$ is the value of the external pull down resistor

### 9.2.3 Application Curve

![img-19.jpeg](img-19.jpeg)

Figure 9-2. Level-Translation of a 2.5-MHz Signal# 9.3 Power Supply Recommendations 

The TXS0104E device uses two separate configurable power-supply rails, $\mathrm{V}_{\mathrm{CCA}}$ and $\mathrm{V}_{\mathrm{CCB}} . \mathrm{V}_{\mathrm{CCB}}$ accepts any supply voltage from 2.3 V to 5.5 V and $\mathrm{V}_{\mathrm{CCA}}$ accepts any supply voltage from 1.65 V to 3.6 V as long as Vs is less than or equal to $\mathrm{V}_{\mathrm{CCB}}$. The A port and B port are designed to track $\mathrm{V}_{\mathrm{CCA}}$ and $\mathrm{V}_{\mathrm{CCB}}$ respectively allowing for low-voltage bidirectional translation between any of the $1.8-\mathrm{V}, 2.5-\mathrm{V}, 3.3-\mathrm{V}$, and $5-\mathrm{V}$ voltage nodes.
The TXS0104E device does not require power sequencing between $\mathrm{V}_{\mathrm{CCA}}$ and $\mathrm{V}_{\mathrm{CCB}}$ during power-up so the power-supply rails can be ramped in any order. A $\mathrm{V}_{\mathrm{CCA}}$ value greater than or equal to $\mathrm{V}_{\mathrm{CCB}}\left(\mathrm{V}_{\mathrm{CCA}} \geq \mathrm{V}_{\mathrm{CCB}}\right)$ does not damage the device, but during operation, $\mathrm{V}_{\mathrm{CCA}}$ must be less than or equal to $\mathrm{V}_{\mathrm{CCB}}\left(\mathrm{V}_{\mathrm{CCA}} \leq \mathrm{V}_{\mathrm{CCB}}\right)$ at all times.

The output-enable (OE) input circuit is designed so that it is supplied by $\mathrm{V}_{\mathrm{CCA}}$ and when the (OE) input is low, all outputs are placed in the high-impedance state. For the high-impedance state of the outputs during power up or power down, the OE input pin must be tied to GND through a pulldown resistor and must not be enabled until $\mathrm{V}_{\mathrm{CCA}}$ and $\mathrm{V}_{\mathrm{CCB}}$ are fully ramped and stable. The minimum value of the pulldown resistor to ground is determined by the current-sourcing capability of the driver.

### 9.4 Layout

### 9.4.1 Layout Guidelines

For device reliability, following common printed-circuit board layout guidelines is recommended.

- Bypass capacitors should be used on power supplies.
- Short trace lengths should be used to avoid excessive loading.
- PCB signal trace-lengths must be kept short enough so that the round-trip delay of any reflection is less than the one shot duration, approximately 30 ns , and encounters low impedance at the source driver.
- Placing pads on the signal paths for loading capacitors or pullup resistors to help adjust rise and fall times of signals depending on the system requirements


### 9.4.2 Layout Example

![img-20.jpeg](img-20.jpeg)

Figure 9-3. TXS0104E Layout Example# 10 Device and Documentation Support 

### 10.1 Documentation Support

### 10.1.1 Related Documentation

For related documentation, see the following:

- Texas Instruments, Effects of External Pullup and Pulldown Resistors on TXS and TXB Devices application report
- Texas Instruments, Basics of Voltage Translation application report
- Texas Instruments, A Guide to Voltage Translation With TXS-Type Translators application report


### 10.2 Receiving Notification of Documentation Updates

To receive notification of documentation updates, navigate to the device product folder on ti.com. Click on Subscribe to updates to register and receive a weekly digest of any product information that has changed. For change details, review the revision history included in any revised document.

### 10.3 Support Resources

TI E2E ${ }^{\text {TM }}$ support forums are an engineer's go-to source for fast, verified answers and design help - straight from the experts. Search existing answers or ask your own question to get the quick design help you need.
Linked content is provided "AS IS" by the respective contributors. They do not constitute TI specifications and do not necessarily reflect TI's views; see TI's Terms of Use.

### 10.4 Trademarks

NanoFree ${ }^{\text {TM }}$ and TI E2E ${ }^{\text {TM }}$ are trademarks of Texas Instruments.
All trademarks are the property of their respective owners.

### 10.5 Electrostatic Discharge Caution

This integrated circuit can be damaged by ESD. Texas Instruments recommends that all integrated circuits be handled with appropriate precautions. Failure to observe proper handling and installation procedures can cause damage.
ESD damage can range from subtle performance degradation to complete device failure. Precision integrated circuits may be more susceptible to damage because very small parametric changes could cause the device not to meet its published specifications.

### 10.6 Glossary

TI Glossary This glossary lists and explains terms, acronyms, and definitions.

## 11 Mechanical, Packaging, and Orderable Information

The following pages include mechanical, packaging, and orderable information. This information is the most current data available for the designated devices. This data is subject to change without notice and revision of this document. For browser-based versions of this data sheet, refer to the left-hand navigation.# PACKAGE OPTION ADDENDUM

|  Orderable part number | Status
(1) | Material type
(2) | Package | Pins | Package qty | Carrier | RoHS
(3) | Lead finish/ Ball material
(4) | MSL rating/ Peak reflow
(5) | Op temp ( ${ }^{\circ} \mathrm{C}$ ) | Part marking
(6)  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  TXS0104EBQAR | Active | Production | WQFN (BQA) | 14 | 3000 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 125 | YF04E  |
|  TXS0104EBQAR.A | Active | Production | WQFN (BQA) | 14 | 3000 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 125 | YF04E  |
|  TXS0104ED | Active | Production | SOIC (D) | 14 | 50 | TUBE | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 85 | TXS0104E  |
|  TXS0104ED.B | Active | Production | SOIC (D) | 14 | 50 | TUBE | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 85 | TXS0104E  |
|  TXS0104EDG4 | Active | Production | SOIC (D) | 14 | 50 | TUBE | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 85 | TXS0104E  |
|  TXS0104EDR | Active | Production | SOIC (D) | 14 | 2500 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 85 | TXS0104E  |
|  TXS0104EDR.A | Active | Production | SOIC (D) | 14 | 2500 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 85 | TXS0104E  |
|  TXS0104EDR.B | Active | Production | SOIC (D) | 14 | 2500 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 85 | TXS0104E  |
|  TXS0104EDRG4 | Active | Production | SOIC (D) | 14 | 2500 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 125 | TXS0104E  |
|  TXS0104EDRG4.A | Active | Production | SOIC (D) | 14 | 2500 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 125 | TXS0104E  |
|  TXS0104EDRG4.B | Active | Production | SOIC (D) | 14 | 2500 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 125 | TXS0104E  |
|  TXS0104ENMNR | Active | Production | NFBGA (NMN) | 12 | 2500 | LARGE T\&R | Yes | SNAGCU | Level-2-260C-1 YEAR | $-40$ to 85 | 29XW  |
|  TXS0104ENMNR.B | Active | Production | NFBGA (NMN) | 12 | 2500 | LARGE T\&R | Yes | SNAGCU | Level-2-260C-1 YEAR | $-40$ to 85 | 29XW  |
|  TXS0104EPWR | Active | Production | TSSOP (PW) | 14 | 2000 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 85 | YF04E  |
|  TXS0104EPWR.A | Active | Production | TSSOP (PW) | 14 | 2000 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 85 | YF04E  |
|  TXS0104EPWR.B | Active | Production | TSSOP (PW) | 14 | 2000 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 85 | YF04E  |
|  TXS0104EPWRG4 | Active | Production | TSSOP (PW) | 14 | 2000 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 85 | YF04E  |
|  TXS0104ERGYR | Active | Production | VQFN (RGY) | 14 | 3000 | LARGE T\&R | Yes | NIPDAU | Level-2-260C-1 YEAR | $-40$ to 85 | YF04E  |
|  TXS0104ERGYR.A | Active | Production | VQFN (RGY) | 14 | 3000 | LARGE T\&R | Yes | NIPDAU | Level-2-260C-1 YEAR | $-40$ to 85 | YF04E  |
|  TXS0104ERGYR.B | Active | Production | VQFN (RGY) | 14 | 3000 | LARGE T\&R | Yes | NIPDAU | Level-2-260C-1 YEAR | $-40$ to 85 | YF04E  |
|  TXS0104ERGYRG4 | Active | Production | VQFN (RGY) | 14 | 3000 | LARGE T\&R | Yes | NIPDAU | Level-2-260C-1 YEAR | $-40$ to 85 | YF04E  |
|  TXS0104ERUTR | Active | Production | UQFN (RUT) | 12 | 3000 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 125 | 1RP  |
|  TXS0104ERUTR.A | Active | Production | UQFN (RUT) | 12 | 3000 | LARGE T\&R | Yes | NIPDAU | Level-1-260C-UNLIM | $-40$ to 125 | 1RP  |
|  TXS0104EYZTR | Active | Production | DSBGA (YZT) | 12 | 3000 | LARGE T\&R | Yes | SNAGCU | Level-1-260C-UNLIM | $-40$ to 85 | 2N  |
|  TXS0104EYZTR.B | Active | Production | DSBGA (YZT) | 12 | 3000 | LARGE T\&R | Yes | SNAGCU | Level-1-260C-UNLIM | $-40$ to 85 | 2N  |

${ }^{(1)}$ Status: For more details on status, see our product life cycle.# PACKAGE OPTION ADDENDUM 

(2) Material type: When designated, preproduction parts are prototypes/experimental devices, and are not yet approved or released for full production. Testing and final process, including without limitation quality assurance, reliability performance testing, and/or process qualification, may not yet be complete, and this item is subject to further changes or possible discontinuation. If available for ordering, purchases will be subject to an additional waiver at checkout, and are intended for early internal evaluation purposes only. These items are sold without warranties of any kind.
${ }^{(3)}$ RoHS values: Yes, No, RoHS Exempt. See the TI RoHS Statement for additional information and value definition.
${ }^{(4)}$ Lead finish/Ball material: Parts may have multiple material finish options. Finish options are separated by a vertical ruled line. Lead finish/Ball material values may wrap to two lines if the finish value exceeds the maximum column width.
${ }^{(5)}$ MSL rating/Peak reflow: The moisture sensitivity level ratings and peak solder (reflow) temperatures. In the event that a part has multiple moisture sensitivity ratings, only the lowest level per JEDEC standards is shown. Refer to the shipping label for the actual reflow temperature that will be used to mount the part to the printed circuit board.
${ }^{(6)}$ Part marking: There may be an additional marking, which relates to the logo, the lot trace code information, or the environmental category of the part.

Multiple part markings will be inside parentheses. Only one part marking contained in parentheses and separated by a "-" will appear on a part. If a line is indented then it is a continuation of the previous line and the two combined represent the entire part marking for that device.

Important Information and Disclaimer:The information provided on this page represents TI's knowledge and belief as of the date that it is provided. TI bases its knowledge and belief on information provided by third parties, and makes no representation or warranty as to the accuracy of such information. Efforts are underway to better integrate information from third parties. TI has taken and continues to take reasonable steps to provide representative and accurate information but may not have conducted destructive testing or chemical analysis on incoming materials and chemicals. TI and TI suppliers consider certain information to be proprietary, and thus CAS numbers and other limited information may not be available for release.

In no event shall TI's liability arising out of such information exceed the total purchase price of the TI part(s) at issue in this document sold by TI to Customer on an annual basis.

## OTHER QUALIFIED VERSIONS OF TX50104E :

- Automotive : TX50104E-Q1

NOTE: Qualified Version Definitions:

- Automotive - Q100 devices qualified for high-reliability automotive applications targeting zero defects# TAPE AND REEL INFORMATION 

![img-21.jpeg](img-21.jpeg)

TAPE DIMENSIONS
![img-22.jpeg](img-22.jpeg)

| A0 | Dimension designed to accommodate the component width |
| :-- | :-- |
| B0 | Dimension designed to accommodate the component length |
| K0 | Dimension designed to accommodate the component thickness |
| W | Overall width of the carrier tape |
| P1 | Pitch between successive cavity centers |

QUADRANT ASSIGNMENTS FOR PIN 1 ORIENTATION IN TAPE
![img-23.jpeg](img-23.jpeg)
*All dimensions are nominal

| Device | Package <br> Type | Package <br> Drawing | Pins | SPQ | Reel <br> Diameter <br> (mm) | Reel <br> Width <br> W1 (mm) | A0 <br> (mm) | B0 <br> (mm) | K0 <br> (mm) | P1 <br> (mm) | W <br> (mm) | Pin1 <br> Quadrant |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| TXS0104EBQAR | WQFN | BQA | 14 | 3000 | 180.0 | 12.4 | 2.8 | 3.3 | 1.1 | 4.0 | 12.0 | Q1 |
| TXS0104EDR | SOIC | D | 14 | 2500 | 330.0 | 12.4 | 3.75 | 3.75 | 1.15 | 8.0 | 12.0 | Q1 |
| TXS0104EDRG4 | SOIC | D | 14 | 2500 | 330.0 | 12.4 | 3.75 | 3.75 | 1.15 | 8.0 | 12.0 | Q1 |
| TXS0104ENMNR | NFBGA | NMN | 12 | 2500 | 180.0 | 8.4 | 2.3 | 2.8 | 1.15 | 4.0 | 8.0 | Q2 |
| TXS0104EPWR | TSSOP | PW | 14 | 2000 | 330.0 | 12.4 | 6.9 | 5.6 | 1.6 | 8.0 | 12.0 | Q1 |
| TXS0104ERGYR | VQFN | RGY | 14 | 3000 | 330.0 | 12.4 | 3.75 | 3.75 | 1.15 | 8.0 | 12.0 | Q1 |
| TXS0104ERGYR | VQFN | RGY | 14 | 3000 | 330.0 | 12.4 | 3.75 | 3.75 | 1.15 | 8.0 | 12.0 | Q1 |
| TXS0104ERUTR | UQFN | RUT | 12 | 3000 | 180.0 | 8.4 | 2.0 | 2.3 | 0.75 | 4.0 | 8.0 | Q1 |
| TXS0104EYZTR | DSBGA | YZT | 12 | 3000 | 180.0 | 8.4 | 1.49 | 1.99 | 0.75 | 4.0 | 8.0 | Q2 |# PACKAGE MATERIALS INFORMATION

## TAPE AND REEL BOX DIMENSIONS

![img-24.jpeg](img-24.jpeg)

*All dimensions are nominal

|  Device | Package Type | Package Drawing | Pins | SPQ | Length (mm) | Width (mm) | Height (mm)  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  TXS0104EBQAR | WQFN | BQA | 14 | 3000 | 210.0 | 185.0 | 35.0  |
|  TXS0104EDR | SOIC | D | 14 | 2500 | 353.0 | 353.0 | 32.0  |
|  TXS0104EDRG4 | SOIC | D | 14 | 2500 | 353.0 | 353.0 | 32.0  |
|  TXS0104ENMNR | NFBGA | NMN | 12 | 2500 | 210.0 | 185.0 | 35.0  |
|  TXS0104EPWR | TSSOP | PW | 14 | 2000 | 353.0 | 353.0 | 32.0  |
|  TXS0104ERGYR | VQFN | RGY | 14 | 3000 | 353.0 | 353.0 | 32.0  |
|  TXS0104ERGYR | VQFN | RGY | 14 | 3000 | 360.0 | 360.0 | 36.0  |
|  TXS0104ERUTR | UQFN | RUT | 12 | 3000 | 210.0 | 185.0 | 35.0  |
|  TXS0104EYZTR | DSBGA | YZT | 12 | 3000 | 182.0 | 182.0 | 20.0  |# PACKAGE MATERIALS INFORMATION

www.ti.com 25-Jul-2025

## TUBE

![img-25.jpeg](img-25.jpeg)

|  *All dimensions are nominal |  |  |  |  |  |  |  |   |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|  Device | Package Name | Package Type | Pins | SPQ | L (mm) | W (mm) | T (μm) | B (mm)  |
|  TXS0104ED | D | SOIC | 14 | 50 | 506.6 | 8 | 3940 | 4.32  |
|  TXS0104ED.B | D | SOIC | 14 | 50 | 506.6 | 8 | 3940 | 4.32  |
|  TXS0104EDG4 | D | SOIC | 14 | 50 | 506.6 | 8 | 3940 | 4.32  |

Pack Materials-Page 3# GENERIC PACKAGE VIEW 

## RGY 14

$3.5 \times 3.5,0.5 \mathrm{~mm}$ pitch

VQFN - 1 mm max height
PLASTIC QUAD FLATPACK - NO LEAD

This image is a representation of the package family, actual package may vary.
Refer to the product data sheet for package details.
![img-26.jpeg](img-26.jpeg)![img-27.jpeg](img-27.jpeg)

# PACKAGE OUTLINE 

RGY0014A
VQFN - 1 mm max height
PLASTIC QUAD FLATPACK - NO LEAD
![img-28.jpeg](img-28.jpeg)

NOTES:

1. All linear dimensions are in millimeters. Any dimensions in parenthesis are for reference only. Dimensioning and tolerancing per ASME Y14.5M.
2. This drawing is subject to change without notice.
3. The package thermal pad must be soldered to the printed circuit board for thermal and mechanical performance.![img-29.jpeg](img-29.jpeg)

NOTES: (continued)
4. This package is designed to be soldered to a thermal pad on the board. For more information, see Texas Instruments literature number SLUA271 (www.ti.com/lit/slua271).# EXAMPLE STENCIL DESIGN 

RGY0014A
VQFN - 1 mm max height
PLASTIC QUAD FLATPACK - NO LEAD
![img-30.jpeg](img-30.jpeg)

NOTES: (continued)
5. Laser cutting apertures with trapezoidal walls and rounded corners may offer better paste release. IPC-7525 may have alternate design recommendations.YZT (R-XBGA-N12)
(CUSTOM) DIE-SIZE BALL GRID ARRAY
![img-31.jpeg](img-31.jpeg)

NOTES: A. All linear dimensions are in millimeters. Dimensioning and tolerancing per ASME Y14.5M-1994.
B. This drawing is subject to change without notice.
C. NanoFree ${ }^{\text {TM }}$ package configuration.![img-32.jpeg](img-32.jpeg)

NOTES:

1. All linear dimensions are in millimeters. Dimensions in parenthesis are for reference only. Dimensioning and tolerancing per ASME Y14.5M.
2. This drawing is subject to change without notice.
3. This dimension does not include mold flash, protrusions, or gate burrs. Mold flash, protrusions, or gate burrs shall not exceed 0.15 mm , per side.
4. This dimension does not include interlead flash. Interlead flash shall not exceed 0.43 mm , per side.
5. Reference JEDEC registration MS-012, variation AB.![img-33.jpeg](img-33.jpeg)

NOTES: (continued)
6. Publication IPC-7351 may have alternate designs.
7. Solder mask tolerances between and around signal pads can vary based on board fabrication site.![img-34.jpeg](img-34.jpeg)

NOTES: (continued)
8. Laser cutting apertures with trapezoidal walls and rounded corners may offer better paste release. IPC-7525 may have alternate design recommendations.
9. Board assembly site may have different recommendations for stencil design.# GENERIC PACKAGE VIEW 

## BQA 14

$2.5 \times 3,0.5 \mathrm{~mm}$ pitch

## WQFN - 0.8 mm max height

PLASTIC QUAD FLATPACK - NO LEAD

This image is a representation of the package family, actual package may vary.
Refer to the product data sheet for package details.
![img-35.jpeg](img-35.jpeg)![img-36.jpeg](img-36.jpeg)

NOTES:

1. All linear dimensions are in millimeters. Any dimensions in parenthesis are for reference only. Dimensioning and tolerancing per ASME Y14.5M.
2. This drawing is subject to change without notice.
3. The package thermal pad must be soldered to the printed circuit board for optimal thermal and mechanical performance.![img-37.jpeg](img-37.jpeg)

NOTES: (continued)
4. This package is designed to be soldered to a thermal pad on the board. For more information, see Texas Instruments literature number SLUA271 (www.ti.com/lit/slua271).
5. Vias are optional depending on application, refer to device data sheet. If any vias are implemented, refer to their locations shown on this view. It is recommended that vias under paste be filled, plugged or tented.![img-38.jpeg](img-38.jpeg)

SOLDER PASTE EXAMPLE
BASED ON 0.125 mm THICK STENCIL
EXPOSED PAD
88\% PRINTED COVERAGE BY AREA
SCALE: 20X

NOTES: (continued)
6. Laser cutting apertures with trapezoidal walls and rounded corners may offer better paste release. IPC-7525 may have alternate design recommendations.![img-39.jpeg](img-39.jpeg)

PLASTIC QUAD FLATPACK - NO LEAD
![img-40.jpeg](img-40.jpeg)

NOTES:

1. All linear dimensions are in millimeters. Any dimensions in parenthesis are for reference only. Dimensioning and tolerancing per ASME Y14.5M.
2. This drawing is subject to change without notice.![img-41.jpeg](img-41.jpeg)

NOTES: (continued)
3. For more information, see Texas Instruments literature number SLUA271 (www.ti.com/lit/slua271).![img-42.jpeg](img-42.jpeg)

NOTES: (continued)
4. Laser cutting apertures with trapezoidal walls and rounded corners may offer better paste release. IPC-7525 may have alternate design recommendations.![img-43.jpeg](img-43.jpeg)
![img-44.jpeg](img-44.jpeg)

NOTES:
NanoFree is a trademark of Texas Instruments.

1. All linear dimensions are in millimeters. Any dimensions in parenthesis are for reference only. Dimensioning and tolerancing per ASME Y14.5M.
2. This drawing is subject to change without notice.![img-45.jpeg](img-45.jpeg)

NOTES: (continued)
3. Final dimensions may vary due to manufacturing tolerance considerations and also routing constraints. Refer to Texas Instruments Literature number SNVA009 (www.ti.com/lit/snva009).![img-46.jpeg](img-46.jpeg)

NOTES: (continued)
4. Laser cutting apertures with trapezoidal walls and rounded corners may offer better paste release.![img-47.jpeg](img-47.jpeg)

NOTES:

1. All linear dimensions are in millimeters. Any dimensions in parenthesis are for reference only. Dimensioning and tolerancing per ASME Y14.5M.
2. This drawing is subject to change without notice.
3. This dimension does not include mold flash, protrusions, or gate burrs. Mold flash, protrusions, or gate burrs shall not exceed 0.15 mm per side.
4. This dimension does not include interlead flash. Interlead flash shall not exceed 0.25 mm per side.
5. Reference JEDEC registration MO-153.![img-48.jpeg](img-48.jpeg)

NOTES: (continued)
6. Publication IPC-7351 may have alternate designs.
7. Solder mask tolerances between and around signal pads can vary based on board fabrication site.![img-49.jpeg](img-49.jpeg)

NOTES: (continued)
8. Laser cutting apertures with trapezoidal walls and rounded corners may offer better paste release. IPC-7525 may have alternate design recommendations.
9. Board assembly site may have different recommendations for stencil design.# IMPORTANT NOTICE AND DISCLAIMER 

TI PROVIDES TECHNICAL AND RELIABILITY DATA (INCLUDING DATA SHEETS), DESIGN RESOURCES (INCLUDING REFERENCE DESIGNS), APPLICATION OR OTHER DESIGN ADVICE, WEB TOOLS, SAFETY INFORMATION, AND OTHER RESOURCES "AS IS" AND WITH ALL FAULTS, AND DISCLAIMS ALL WARRANTIES, EXPRESS AND IMPLIED, INCLUDING WITHOUT LIMITATION ANY IMPLIED WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE OR NON-INFRINGEMENT OF THIRD PARTY INTELLECTUAL PROPERTY RIGHTS.
These resources are intended for skilled developers designing with TI products. You are solely responsible for (1) selecting the appropriate TI products for your application, (2) designing, validating and testing your application, and (3) ensuring your application meets applicable standards, and any other safety, security, regulatory or other requirements.
These resources are subject to change without notice. TI grants you permission to use these resources only for development of an application that uses the TI products described in the resource. Other reproduction and display of these resources is prohibited. No license is granted to any other TI intellectual property right or to any third party intellectual property right. TI disclaims responsibility for, and you will fully indemnify TI and its representatives against, any claims, damages, costs, losses, and liabilities arising out of your use of these resources.
TI's products are provided subject to TI's Terms of Sale or other applicable terms available either on ti.com or provided in conjunction with such TI products. TI's provision of these resources does not expand or otherwise alter TI's applicable warranties or warranty disclaimers for TI products.
TI objects to and rejects any additional or different terms you may have proposed.
Mailing Address: Texas Instruments, Post Office Box 655303, Dallas, Texas 75265
Copyright © 2025, Texas Instruments Incorporated