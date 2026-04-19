# TOSHIBA 

## 1. General

The DF2B7ASL is a TVS diode (ESD protection diode) protects semiconductor devices used in mobile device interfaces and other applications to protect against static electricity and noise.
Utilizing snapback characteristics, the DF2B7ASL provides low dynamic resistance and superior protective performance.
Furthermore, the DF2B7ASL is housed in an ultra-compact package $(0.62 \mathrm{~mm} \times 0.32 \mathrm{~mm})$ to meet applications that require a small footprint.

## 2. Applications

Mobile Equipment

- Smartphones
- Tablets
- Notebook PCs

Desktop PCs

Note: This product is designed for protection against electrostatic discharge (ESD) and is not intended for any other purpose, including, but not limited to, voltage regulation.

## 3. Features

(1) Suitable for use with a 5 V signal line. $\left(\mathrm{V}_{\mathrm{RWM}} \leq 5.5 \mathrm{~V}\right)$
(2) Protects devices with its high ESD performance.
$\left(\mathrm{V}_{\mathrm{ESD}}= \pm 30 \mathrm{kV}\right.$ (Contact / Air) @IEC61000-4-2)
(3) Low dynamic resistance protects semiconductor devices from static electricity and noise. $\left(\mathrm{R}_{\mathrm{DYN}}=0.2 \Omega\right.$ (typ.))
(4) Snapback characteristics realizing low clamping voltage protects semiconductor devices. $\left(\mathrm{V}_{\mathrm{C}}=11 \mathrm{~V} @ \mathrm{I}_{\mathrm{PP}}=4 \mathrm{~A}\right.$ (typ.))
(5) Compact package is suitable for use in high density board layouts such as in mobile devices. $(0.62 \mathrm{~mm} \times 0.32 \mathrm{~mm}$ size (Nickname: SL2))

## 4. Packaging

![img-0.jpeg](img-0.jpeg)# 5. Example of Circuit Diagram 

![img-1.jpeg](img-1.jpeg)

ESD protection diode

## 6. Quick Reference Data

| Characteristics | Symbol | Note | Test Condition | Min | Typ. | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Working peak reverse voltage | $V_{\text {RWM }}$ | (Note 1) | - | - | - | 5.5 | V |
| Total capacitance | $C_{t}$ |  | $V_{R}=0 \mathrm{~V}, \mathrm{f}=1 \mathrm{MHz}$ | - | 8.5 | 10 | pF |
| Dynamic resistance | $R_{D Y N}$ | (Note 2) | - | - | 0.2 | - | $\Omega$ |
| Electrostatic discharge voltage (IEC61000-4-2) (Contact) | $V_{\text {ESD }}$ | (Note 3) | - | - | - | 30 | kV |

Note 1: Recommended operating condition.
Note 2: TLP parameters: $Z 0=50 \Omega, t p=100 \mathrm{~ns}, \mathrm{tr}=300 \mathrm{ps}$, averaging window: $\mathrm{t} 1=30 \mathrm{~ns}$ to $\mathrm{t} 2=60 \mathrm{~ns}$, extraction of dynamic resistance using least squares fit of TLP characteristics between $\mathrm{I}_{\mathrm{PP} 1}=8 \mathrm{~A}$ and $\mathrm{I}_{\mathrm{PP} 2}=16 \mathrm{~A}$.
Note 3: Criterion: No damage to devices.

### 6.1. ESD Clamp Waveform (Note)

![img-2.jpeg](img-2.jpeg)

Pulse time tp (ns)
Fig. 6.1.1 +8 kV
![img-3.jpeg](img-3.jpeg)

Pulse time tp (ns)
Fig. 6.1.2 -8 kV
![img-4.jpeg](img-4.jpeg)

Fig. 6.1.3 IEC61000-4-2 (Contact)
Note: The above characteristics curves are presented for reference only and not guaranteed by production test, unless otherwise noted.# 6.2. TLP Characteristics (Note) 

![img-5.jpeg](img-5.jpeg)

Note: The above characteristics curves are presented for reference only and not guaranteed by production test, unless otherwise noted.

### 6.3. Clamp Voltage - Peak Pulse Current ( $\mathrm{V}_{\mathrm{C}}$ - IPP) (Note)

![img-6.jpeg](img-6.jpeg)

Fig. 6.3.1 $\mathrm{V}_{\mathrm{C}}-\mathrm{Ipp}$
![img-7.jpeg](img-7.jpeg)

Fig. 6.3.2 Based on IEC61000-4-5 8/20 $\mu$ s pulse.

Note: The above characteristics curves are presented for reference only and not guaranteed by production test, unless otherwise noted.# 7. Absolute Maximum Ratings (Note) (Unless otherwise specified, $\mathrm{T}_{\mathrm{a}}=25^{\circ} \mathrm{C}$ ) 

| Characteristics | Symbol | Note | Rating | Unit |
| :-- | :--: | :--: | :--: | :--: |
| Electrostatic discharge voltage (IEC61000-4-2) (Contact) | $\mathrm{V}_{\text {ESD }}$ | (Note 1) | $\pm 30$ | kV |
| Electrostatic discharge voltage (IEC61000-4-2) (Air) |  |  | $\pm 30$ |  |
| Peak pulse power ( $\mathrm{tp}=8 / 20 \mu \mathrm{~s}$ ) | $\mathrm{P}_{\mathrm{PK}}$ |  | 80 | W |
| Peak pulse current ( $\mathrm{tp}=8 / 20 \mu \mathrm{~s}$ ) | $\mathrm{I}_{\mathrm{PP}}$ | (Note 2) | 4 | A |
| Junction temperature | $\mathrm{T}_{\mathrm{j}}$ |  | 150 | ${ }^{\circ} \mathrm{C}$ |
| Storage temperature | $\mathrm{T}_{\text {stg }}$ |  | -55 to 150 | ${ }^{\circ} \mathrm{C}$ |

Note: Using continuously under heavy loads (e.g. the application of high temperature/current/voltage and the significant change in temperature, etc.) may cause this product to decrease in the reliability significantly even if the operating conditions (i.e. operating temperature/current/voltage, etc.) are within the absolute maximum ratings.
Please design the appropriate reliability upon reviewing the Toshiba Semiconductor Reliability Handbook ("Handling Precautions"/"Derating Concept and Methods") and individual reliability data (i.e. reliability test report and estimated failure rate, etc).
Note 1: According to IEC61000-4-2.
Note 2: According to IEC61000-4-5.

## 8. Electrical Characteristics (Unless otherwise specified, $\mathrm{T}_{\mathrm{a}}=25^{\circ} \mathrm{C}$ )

$V_{\text {RWM: }}$ Working peak reverse voltage
$V_{B R}$ : Reverse breakdown voltage
$\mathrm{I}_{\mathrm{BR}}$ : Reverse breakdown current
$\mathrm{I}_{\mathrm{R}}$ : Reverse current
$V_{C}$ : Clamp voltage
$\mathrm{I}_{\mathrm{PP}}$ : Peak pulse current
$R_{D Y N}$ : Dynamic resistance
![img-8.jpeg](img-8.jpeg)

Fig. 8.1 Definitions of Electrical Characteristics

| Characteristics | Symbol | Note | Test Condition | Min | Typ. | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Working peak reverse voltage | $V_{R W M}$ | (Note 1) | — | — | — | 5.5 | V |
| Total capacitance | $C_{t}$ |  | $\mathrm{V}_{\mathrm{R}}=0 \mathrm{~V}, \mathrm{f}=1 \mathrm{MHz}$ | — | 8.5 | 10 | pF |
| Dynamic resistance | $R_{D Y N}$ | (Note 2) | - | — | 0.2 | — | $\Omega$ |
| Reverse breakdown voltage | $V_{B R}$ |  | $\mathrm{I}_{\mathrm{BR}}=1 \mathrm{~mA}$ | 5.8 | 6.8 | 7.8 | V |
| Reverse current | $\mathrm{I}_{\mathrm{R}}$ |  | $\mathrm{V}_{\text {RWM }}=5.5 \mathrm{~V}$ | — | — | 100 | nA |
| Clamp voltage | $V_{C}$ | (Note 3) | $\mathrm{I}_{\mathrm{PP}}=1 \mathrm{~A}$ | — | 8 | — | V |
|  |  |  | $\mathrm{I}_{\mathrm{PP}}=4 \mathrm{~A}$ | — | 11 | 20 |  |
|  |  | (Note 2) | $\mathrm{I}_{\mathrm{TLP}}=16 \mathrm{~A}$ | — | 12 | — | V |
|  |  |  | $\mathrm{I}_{\mathrm{TLP}}=30 \mathrm{~A}$ | — | 15 | — |  |

Note 1: Recommended operating condition.
Note 2: TLP parameters: $Z 0=50 \Omega, t p=100 \mathrm{~ns}, \mathrm{tr}=300 \mathrm{ps}$, averaging window: $t 1=30 \mathrm{~ns}$ to $\mathrm{t} 2=60 \mathrm{~ns}$, extraction of dynamic resistance using least squares fit of TLP characteristics between $\mathrm{I}_{\mathrm{PP} 1}=8 \mathrm{~A}$ and $\mathrm{I}_{\mathrm{PP} 2}=16 \mathrm{~A}$.
Note 3: Based on IEC61000-4-5 8/20 $\mu$ s pulse.# 9. Characteristics Curves (Note) 

![img-9.jpeg](img-9.jpeg)

Fig. 9.1 I-V
![img-10.jpeg](img-10.jpeg)

Fig. 9.3 $\mathrm{C}_{\mathrm{f}}-\mathrm{V}_{\mathrm{R}}$
![img-11.jpeg](img-11.jpeg)

Fig. 9.5 S21-f
![img-12.jpeg](img-12.jpeg)

Fig. 9.2 $\mathrm{I}_{\mathrm{R}}-\mathrm{V}_{\mathrm{R}}$
![img-13.jpeg](img-13.jpeg)

Fig. 9.4 $\mathrm{C}_{\mathrm{t}}-\mathrm{f}$
![img-14.jpeg](img-14.jpeg)

Note: The above characteristics curves are presented for reference only and not guaranteed by production test, unless otherwise noted.# 10. Internal Circuit (Note) 

![img-15.jpeg](img-15.jpeg)

Note: Connect Pin 2 to GND when using Pin 1 for I/O.
Connect Pin 1 to GND when using Pin 2 for I/O.

## 11. Marking (Top view)

![img-16.jpeg](img-16.jpeg)
12. Land Pattern Dimensions (for reference only)
![img-17.jpeg](img-17.jpeg)# Package Dimensions

Unit: mm

![img-18.jpeg](img-18.jpeg)

Weight: 0.2 mg (typ.)

Package Name(s)

Nickname: SL2

©2016-2018
Toshiba Electronic Devices & Storage Corporation

7

2018-06-27
Rev.3.0# RESTRICTIONS ON PRODUCT USE 

Toshiba Corporation and its subsidiaries and affiliates are collectively referred to as "TOSHIBA".
Hardware, software and systems described in this document are collectively referred to as "Product".

- TOSHIBA reserves the right to make changes to the information in this document and related Product without notice.
- This document and any information herein may not be reproduced without prior written permission from TOSHIBA. Even with TOSHIBA's written permission, reproduction is permissible only if reproduction is without alteration/omission.
- Though TOSHIBA works continually to improve Product's quality and reliability, Product can malfunction or fail. Customers are responsible for complying with safety standards and for providing adequate designs and safeguards for their hardware, software and systems which minimize risk and avoid situations in which a malfunction or failure of Product could cause loss of human life, bodily injury or damage to property, including data loss or corruption. Before customers use the Product, create designs including the Product, or incorporate the Product into their own applications, customers must also refer to and comply with (a) the latest versions of all relevant TOSHIBA information, including without limitation, this document, the specifications, the data sheets and application notes for Product and the precautions and conditions set forth in the "TOSHIBA Semiconductor Reliability Handbook" and (b) the instructions for the application with which the Product will be used with or for. Customers are solely responsible for all aspects of their own product design or applications, including but not limited to (a) determining the appropriateness of the use of this Product in such design or applications; (b) evaluating and determining the applicability of any information contained in this document, or in charts, diagrams, programs, algorithms, sample application circuits, or any other referenced documents; and (c) validating all operating parameters for such designs and applications. TOSHIBA ASSUMES NO LIABILITY FOR CUSTOMERS' PRODUCT DESIGN OR APPLICATIONS.
- PRODUCT IS NEITHER INTENDED NOR WARRANTED FOR USE IN EQUIPMENTS OR SYSTEMS THAT REQUIRE EXTRAORDINARILY HIGH LEVELS OF QUALITY AND/OR RELIABILITY, AND/OR A MALFUNCTION OR FAILURE OF WHICH MAY CAUSE LOSS OF HUMAN LIFE, BODILY INJURY, SERIOUS PROPERTY DAMAGE AND/OR SERIOUS PUBLIC IMPACT ("UNINTENDED USE"). Except for specific applications as expressly stated in this document, Unintended Use includes, without limitation, equipment used in nuclear facilities, equipment used in the aerospace industry, medical equipment, equipment used for automobiles, trains, ships and other transportation, traffic signaling equipment, equipment used to control combustions or explosions, safety devices, elevators and escalators, devices related to electric power, and equipment used in finance-related fields. IF YOU USE PRODUCT FOR UNINTENDED USE, TOSHIBA ASSUMES NO LIABILITY FOR PRODUCT. For details, please contact your TOSHIBA sales representative.
- Do not disassemble, analyze, reverse-engineer, alter, modify, translate or copy Product, whether in whole or in part.
- Product shall not be used for or incorporated into any products or systems whose manufacture, use, or sale is prohibited under any applicable laws or regulations.
- The information contained herein is presented only as guidance for Product use. No responsibility is assumed by TOSHIBA for any infringement of patents or any other intellectual property rights of third parties that may result from the use of Product. No license to any intellectual property right is granted by this document, whether express or implied, by estoppel or otherwise.
- ABSENT A WRITTEN SIGNED AGREEMENT, EXCEPT AS PROVIDED IN THE RELEVANT TERMS AND CONDITIONS OF SALE FOR PRODUCT, AND TO THE MAXIMUM EXTENT ALLOWABLE BY LAW, TOSHIBA (1) ASSUMES NO LIABILITY WHATSOEVER, INCLUDING WITHOUT LIMITATION, INDIRECT, CONSEQUENTIAL, SPECIAL, OR INCIDENTAL DAMAGES OR LOSS, INCLUDING WITHOUT LIMITATION, LOSS OF PROFITS, LOSS OF OPPORTUNITIES, BUSINESS INTERRUPTION AND LOSS OF DATA, AND (2) DISCLAIMS ANY AND ALL EXPRESS OR IMPLIED WARRANTIES AND CONDITIONS RELATED TO SALE, USE OF PRODUCT, OR INFORMATION, INCLUDING WARRANTIES OR CONDITIONS OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, ACCURACY OF INFORMATION, OR NONINFRINGEMENT.
- Do not use or otherwise make available Product or related software or technology for any military purposes, including without limitation, for the design, development, use, stockpiling or manufacturing of nuclear, chemical, or biological weapons or missile technology products (mass destruction weapons). Product and related software and technology may be controlled under the applicable export laws and regulations including, without limitation, the Japanese Foreign Exchange and Foreign Trade Law and the U.S. Export Administration Regulations. Export and re-export of Product or related software or technology are strictly prohibited except in compliance with all applicable export laws and regulations.
- Please contact your TOSHIBA sales representative for details as to environmental matters such as the RoHS compatibility of Product. Please use Product in compliance with all applicable laws and regulations that regulate the inclusion or use of controlled substances, including without limitation, the EU RoHS Directive. TOSHIBA ASSUMES NO LIABILITY FOR DAMAGES OR LOSSES OCCURRING AS A RESULT OF NONCOMPLIANCE WITH APPLICABLE LAWS AND REGULATIONS.