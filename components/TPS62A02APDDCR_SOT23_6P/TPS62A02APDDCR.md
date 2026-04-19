# TPS62A0x, TPS62A0xA, and TPS62A02Nx 1A, 2A, High-Efficiency, Synchronous Buck Converters in a SOT-563 and a SOT-23 Package 

## 1 Features

- 2.5 V to 5.5 V input voltage range
- 0.6 V to $\mathrm{V}_{\text {IN }}$ adjustable output voltage range
- $180 \mathrm{~m} \Omega / 120 \mathrm{~m} \Omega$ low $R_{\text {DSON }}$ switches (1A DRL)
- $100 \mathrm{~m} \Omega / 67 \mathrm{~m} \Omega$ low $R_{\text {DSON }}$ switches (1A DDC, 2A)
- $<23 \mu \mathrm{~A}$ quiescent current
- $1 \%$ feedback accuracy $\left(0^{\circ} \mathrm{C}\right.$ to $\left.125^{\circ} \mathrm{C}\right)$
- $100 \%$ mode operation
- 2.4 MHz switching frequency
- Power save mode or PWM option available
- Power-good output pin (optional)
- Short-circuit protection (HICCUP)
- Internal soft start-up
- Active output discharge
- Thermal shutdown protection
- Pin-to-pin compatible with the TLV62585 (DRL)
- Pin-to-pin compatible with the TLV62569 (DDC)


## 2 Applications

- Set top box, TV applications
- IP network camera, Multi-function printer
- Wireless router, solid state drive
- Battery-powered applications
- General purpose point-of-load supply
![img-0.jpeg](img-0.jpeg)

Typical Application
![img-1.jpeg](img-1.jpeg)

Efficiency vs Output Current at $5 \mathrm{~V}_{\text {IN }}$ (TPS62A02x)

## 3 Description

The TPS62A0x family of devices are synchronous step-down buck DC/DC converters optimized for high efficiency and compact design size. The devices integrate switches capable of delivering an output current up to 2 A . At medium to heavy loads, the devices operate in pulse width modulation (PWM) mode with 2.4 MHz switching frequency. At light load, the devices automatically enter power save mode (PSM) to maintain high efficiency over the entire load current range. In shutdown, the current consumption is minimal as well. The TPS62A0xA variants of this device family operate in forced PWM across the whole load current range.

The TPS62A0x devices provide an adjustable output voltage through an external resistor divider. An internal soft-start circuit limits the inrush current during start-up. Other features like overcurrent protection, thermal shutdown protection, and power good (optional) are built-in. The devices are available in a SOT563 and SOT23-6 package.

Package Information

| PART NUMBER | PACKAGE $^{(1)}$ | PACKAGE SIZE ${ }^{(2)}$ |  |
| :-- | :-- | :--: | :--: |
| TPS62A01x | DRL (SOT-563, 6) | $1.60 \mathrm{~mm} \times 1.60 \mathrm{~mm}$ |  |
|  | DDC (SOT-23, 6) | $2.90 \mathrm{~mm} \times 2.80 \mathrm{~mm}$ |  |
| TPS62A02x | DRL (SOT-563, 6) | $1.60 \mathrm{~mm} \times 1.60 \mathrm{~mm}$ |  |
|  | DDC (SOT-23, 6) | $2.90 \mathrm{~mm} \times 2.80 \mathrm{~mm}$ |  |
| TPS62A02Nx | DRL (SOT-563, 6) | $1.60 \mathrm{~mm} \times 1.60 \mathrm{~mm}$ |  |

(1) For more information, see Section 11.
(2) The package size (length $\times$ width) is a nominal value and includes pins, where applicable.

Device Information

| PART NUMBER $^{(1)}$ | OPERATION <br> MODE | OUTPUT <br> CURRENT | PIN 6 |
| :-- | :-- | :--: | :--: |
| TPS62A01 | PSM, PWM | 1A |  |
| TPS62A01A | FPWM |  |  |
| TPS62A02 | PSM, PWM | 2A | PG |
| TPS62A02A | FPWM |  |  |
| TPS62A02N | PSM, PWM |  |  |
| TPS62A02NA | FPWM |  |  |

(1) See the Device Comparison Table.# Table of Contents 

1 Features ..... 1
2 Applications ..... 1
3 Description ..... 1
4 Device Comparison Table ..... 3
5 Pin Configuration and Functions ..... 3
6 Specifications ..... 4
6.1 Absolute Maximum Ratings ..... 4
6.2 ESD Ratings ..... 4
6.3 Recommended Operating Conditions ..... 4
6.4 Thermal Information ..... 4
6.5 Electrical Characteristics ..... 5
6.6 Typical Characteristics ..... 7
7 Detailed Description ..... 8
7.1 Overview ..... 8
7.2 Functional Block Diagram ..... 8
7.3 Feature Description ..... 8
7.4 Device Functional Modes ..... 9
8 Application and Implementation ..... 11
8.1 Application Information ..... 11
8.2 Typical Application ..... 11
8.3 Power Supply Recommendations ..... 17
8.4 Layout ..... 17
9 Device and Documentation Support ..... 19
9.1 Device Support ..... 19
9.2 Receiving Notification of Documentation Updates ..... 19
9.3 Support Resources ..... 19
9.4 Trademarks ..... 19
9.5 Electrostatic Discharge Caution ..... 19
9.6 Glossary ..... 19
10 Revision History ..... 20
11 Mechanical, Packaging, and Orderable Information ..... 20# 4 Device Comparison Table 

| Device Number | Output Current | Package | Operation Mode | Pin 6 |
| :--: | :--: | :--: | :--: | :--: |
| TPS62A01DRLR | 1 A | SOT-563, 6 | PSM, PWM | PG |
| TPS62A01ADRLR |  |  | FPWM |  |
| TPS62A02DRLR | 2 A |  | PSM, PWM |  |
| TPS62A02ADRLR |  |  | FPWM |  |
| TPS62A02NDRLR |  |  | PSM, PWM | OUT |
| TPS62A02NADRLR |  |  | FPWM |  |
| TPS62A01PDDCR | 1 A | SOT-23, 6 | PSM, PWM | PG |
| TPS62A01APDDCR |  |  | FPWM |  |
| TPS62A02PDDCR | 2 A |  | PSM, PWM |  |
| TPS62A02APDDCR |  |  | FPWM |  |

## 5 Pin Configuration and Functions

![img-2.jpeg](img-2.jpeg)

Figure 5-1. 6-Pin DRL SOT-563 Package (Top View), 6-Pin DDC SOT-23 Package (Top View)
Table 5-1. Pin Functions

| Pin Number |  |  | Type $^{(1)}$ | Description |
| :--: | :--: | :--: | :--: | :--: |
| Name | SOT563-6 | SOT23-6 |  |  |
| EN | 4 | 1 | I | Device enable logic input. Logic high enables the device. Logic low disables the device and turns the device into shutdown. Do not leave the pin floating. |
| FB | 5 | 6 | I | Feedback pin for the internal control loop. Connect this pin to an external feedback divider. |
| GND | 1 | 2 | G | Ground pin. |
| PG | 6 | 5 | 0 | Power-good open-drain output pin. The pullup resistor cannot be connected to any voltage higher than 5.5 V . If unused, leave the pin open or connect to GND. |
| OUT ${ }^{(2)}$ |  | / | I | Output voltage sense pin. |
| SW | 2 | 3 | 0 | Switch pin connected to the internal FET switches and inductor terminal. Connect the inductor of the output filter to this pin. |
| VIN | 3 | 4 | I | Input voltage pin. Connect the input capacitor as close as possible between $\mathrm{V}_{\text {IN }}$ and GND. |

(1) $\mathrm{I}=$ Input, $\mathrm{O}=$ Output, $\mathrm{G}=$ Ground.
(2) Only for TPS62A0xN versions.# 6 Specifications 

### 6.1 Absolute Maximum Ratings

Over operating free-air temperature range (unless otherwise noted) ${ }^{(1)}$

|  |  | MIN | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: |
| Pin voltage ${ }^{(2)}$ | VIN, EN, PG | $-0.3$ | 6.5 | V |
|  | SW, DC | $-0.3$ | $V_{R 1}+0.3$ | V |
|  | SW, transient < 10 ns | $-3.0$ | 10 | V |
|  | FB | $-0.3$ | 3 | V |
| $T_{J}$ | Operating junction temperature | $-40$ | 150 | ${ }^{\circ} \mathrm{C}$ |
| $T_{\text {sig }}$ | Storage temperature | $-55$ | 150 | ${ }^{\circ} \mathrm{C}$ |

(1) Operation outside the Absolute Maximum Ratings may cause permanent device damage. Absolute Maximum Ratings do not imply functional operation of the device at these or any other conditions beyond those listed under Recommended Operating Conditions. If used outside the Recommended Operating Conditions but within the Absolute Maximum Ratings, the device may not be fully functional, and this may affect device reliability, functionality, performance, and shorten the device lifetime.
(2) All voltage values are with respect to the network ground terminal.

### 6.2 ESD Ratings

|  |  |  | VALUE | UNIT |
| :-- | :-- | :-- | :--: | :--: |
| $V_{(\text {ESD) }}$ | Electrostatic discharge | Human-body model (HBM), per ANSI/ESDA/JEDEC JS-001 ${ }^{(1)}$ | $\pm 2000$ | V |
|  |  | Charged-device model (CDM), per ANSI/ESDA/JEDEC JS-002 ${ }^{(2)}$ | $\pm 500$ |  |

(1) JEDEC document JEP155 states that 500-V HBM allows safe manufacturing with a standard ESD control process.
(2) JEDEC document JEP157 states that 250-V CDM allows safe manufacturing with a standard ESD control process.

### 6.3 Recommended Operating Conditions

Over operating junction temperature range (unless otherwise noted)

|  |  |  | MIN | NOM | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V_{R 1}$ | Input supply voltage range |  | 2.5 |  | 5.5 | V |
| $V_{\text {OUT }}$ | Output voltage range |  | 0.6 |  | $V_{R 1}$ | V |
| $I_{\text {OUT }}$ | Output current range | TPS62A01 | 0 |  | 1 | A |
| $I_{\text {OUT }}$ | Output current range ${ }^{(1)}$ | TPS62A02 | 0 |  | 2 | A |
| L | Effective inductance |  |  | 1.0 |  | $\mu \mathrm{H}$ |
| $\mathrm{C}_{\text {OUT }}$ | Output capacitance | $V_{\text {OUT }}<1.2 \mathrm{~V}$ |  | 44 |  | $\mu \mathrm{F}$ |
| $\mathrm{C}_{\text {OUT }}$ | Output capacitance | $1.2 \mathrm{~V} \leq V_{\text {OUT }}<1.8 \mathrm{~V}$ |  | 22 |  | $\mu \mathrm{F}$ |
| $\mathrm{C}_{\text {OUT }}$ | Output capacitance | $V_{\text {OUT }} \geq 1.8 \mathrm{~V}$ |  | 10 |  | $\mu \mathrm{F}$ |
| $I_{P G}$ | Power Good input current capability |  | 0 |  | 1 | mA |
| $T_{J}$ | Operating junction temperature |  | $-40$ |  | 125 | ${ }^{\circ} \mathrm{C}$ |

(1) Operating continuously at 2-A with input voltages $<3.3 \mathrm{~V}$ or at ambient temperatures $>85^{\circ} \mathrm{C}$ might result in thermal shutdown, per EVM measurements.

### 6.4 Thermal Information

| THERMAL METRIC ${ }^{(1)}$ |  | TPS62A0x | TPS62A0x | UNIT |
| :--: | :--: | :--: | :--: | :--: |
|  |  | DRL | DDC |  |
|  |  | 6 PINS | 6 PINS |  |
| $R_{\text {6JA }}$ | Junction-to-ambient thermal resistance | 157.3 | 132.1 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $R_{\text {6JC(top) }}$ | Junction-to-case (top) thermal resistance | 92.2 | 74.9 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $R_{\text {6JB }}$ | Junction-to-board thermal resistance | 45.6 | 45.5 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
| $\psi_{\text {JT }}$ | Junction-to-top characterization parameter | 4.0 | 25.5 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |# 6.4 Thermal Information (continued)

|  THERMAL METRIC ${ }^{(1)}$ |  | TPS62A0x | TPS62A0x | UNIT  |
| --- | --- | --- | --- | --- |
|   |  | DRL | DDC |   |
|   |  | 6 PINS | 6 PINS |   |
|  $\psi_{J B}$ | Junction-to-board characterization parameter | 45.0 | 45.1 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$  |

(1) For more information about traditional and new thermal metrics, see the Semiconductor and IC Package Thermal Metrics report.

### 6.5 Electrical Characteristics

$T_{J}=-40^{\circ} \mathrm{C}$ to $+125^{\circ} \mathrm{C}, V_{I N}=2.5 \mathrm{~V}$ to 5.5 V . Typical values are at $T_{J}=25^{\circ} \mathrm{C}$ and $V_{I N}=5 \mathrm{~V}$ (unless otherwise noted)

|  PARAMETER |  | TEST CONDITIONS | MIN | TYP | MAX | UNIT  |
| --- | --- | --- | --- | --- | --- | --- |
|  SUPPLY |  |  |  |  |  |   |
|  $\mathrm{I}_{\text {Q(VIN) }}$ | VIN quiescent current | Non-switching; $\mathrm{V}*{\mathrm{EN}}=\mathrm{High} ; \mathrm{V}*{\mathrm{FB}}=610$ $\mathrm{mV} ;$ TPS62A01xDRL | 20 |  |  | $\mu \mathrm{A}$  |
|  $\mathrm{I}_{\text {Q(VIN) }}$ | VIN quiescent current | Non-switching; $\mathrm{V}*{\mathrm{EN}}=\mathrm{High} ; \mathrm{V}*{\mathrm{FB}}=610 \mathrm{mV} ;$ TPS62A01xDDC; TPS62A02 | 23 |  |  | $\mu \mathrm{A}$  |
|  $\mathrm{I}_{\text {S(IVIN) }}$ | VIN shutdown supply current | $\mathrm{V}_{\mathrm{EN}}=$ Low | 0.01 | 2 |  | $\mu \mathrm{A}$  |
|  UVLO |  |  |  |  |  |   |
|  $\mathrm{V}_{\text {UVLO(R) }}$ | VIN UVLO rising threshold | $\mathrm{V}_{\text {IN }}$ rising | 2.3 | 2.4 | 2.5 | V  |
|  $\mathrm{V}_{\text {UVLO(F) }}$ | VIN UVLO falling threshold | $\mathrm{V}_{\text {IN }}$ falling | 2.2 | 2.3 | 2.4 | V  |
|  ENABLE |  |  |  |  |  |   |
|  $\mathrm{V}_{\text {EN(R) }}$ | EN voltage rising threshold | EN rising; enable switching | 1.2 |  |  | V  |
|  $\mathrm{V}_{\text {EN(F) }}$ | EN voltage falling threshold | EN falling, disable switching |  |  | 0.4 | V  |
|  $\mathrm{V}_{\text {EN(LKG) }}$ | EN Input leakage current | $\mathrm{V}_{\mathrm{EN}}=5 \mathrm{~V}$ |  |  | 100 | nA  |
|  REFERENCE VOLTAGE |  |  |  |  |  |   |
|  $\mathrm{V}_{\mathrm{FB}}$ | FB voltage | $T_{J}=0^{\circ} \mathrm{C}$ to $125^{\circ} \mathrm{C}$, PWM mode | 594 | 600 | 606 | mV  |
|  $\mathrm{V}_{\mathrm{FB}}$ | FB voltage | PWM mode | 591 | 600 | 609 | mV  |
|  $\mathrm{I}_{\text {FBLKG) }}$ | FB input leakage current | $\mathrm{V}_{\mathrm{FB}}=0.6 \mathrm{~V}$ |  |  | 100 | nA  |
|  SWITCHING FREQUENCY |  |  |  |  |  |   |
|  $\mathrm{f}_{\text {SW(FCCM) }}$ | Switching frequency, FPWM operation | $\mathrm{V}_{\mathrm{IN}}=5 \mathrm{~V} ; \mathrm{V}_{\text {OUT }}=1.8 \mathrm{~V}$ | 2400 |  |  | kHz  |
|  STARTUP |  |  |  |  |  |   |
|   | Internal fixed soft-start time | From EN = High to $\mathrm{V}_{\mathrm{FB}}=0.56 \mathrm{~V}$ | 1 |  |  | ms  |
|  POWER STAGE |  |  |  |  |  |   |
|  $\mathrm{R}_{\text {DSON(HS) }}$ | High-side MOSFET on-resistance | TPS62A01xDRL; $\mathrm{V}_{\mathrm{IN}}=5 \mathrm{~V}$ | 180 |  |  | $\mathrm{m} \Omega$  |
|  $\mathrm{R}_{\text {DSON(LS) }}$ | Low-side MOSFET on-resistance | TPS62A01xDRL; $\mathrm{V}_{\mathrm{IN}}=5 \mathrm{~V}$ | 120 |  |  | $\mathrm{m} \Omega$  |
|  $\mathrm{R}_{\text {DSON(HS) }}$ | High-side MOSFET on-resistance | $\mathrm{V}_{\mathrm{IN}}=5 \mathrm{~V}$; TPS62A01xDDC; TPS62A02 | 100 |  |  | $\mathrm{m} \Omega$  |
|  $\mathrm{R}_{\text {DSON(LS) }}$ | Low-side MOSFET on-resistance | $\mathrm{V}_{\mathrm{IN}}=5 \mathrm{~V}$; TPS62A01xDDC; TPS62A02 | 67 |  |  | $\mathrm{m} \Omega$  |
|  OVERCURRENT PROTECTION |  |  |  |  |  |   |
|  $\mathrm{I}_{\text {HS(OC) }}$ | High-side peak current limit | TPS62A01 | 1.3 | 1.8 |  | A  |
|  $\mathrm{I}_{\text {LS(OC) }}$ | Low-side valley current limit | TPS62A01 |  | 1.8 |  | A  |
|  $\mathrm{I}_{\text {HS(OC) }}$ | High-side peak current limit | TPS62A02 | 2.7 | 3.4 |  | A  |
|  $\mathrm{I}_{\text {LS(OC) }}$ | Low-side valley current limit | TPS62A02xDRL |  | 4.2 |  | A  |
|  $\mathrm{I}_{\text {LS(OC) }}$ | Low-side valley current limit | TPS62A02xDDC |  | 3.15 |  | A  |
|  POWER GOOD |  |  |  |  |  |   |
|  $\mathrm{V}_{\text {PGTH }}$ | Power Good threshold | PG low, FB falling | 93.5 |  |  | \%  |
|  $\mathrm{V}_{\text {PGTH }}$ | Power Good threshold | PG high, FB rising | 96 |  |  | \%  |
|   | PG delay falling |  | 35 |  |  | $\mu \mathrm{s}$  |
|   | PG delay rising |  | 10 |  |  | $\mu \mathrm{s}$  |
|  $\mathrm{I}_{\text {PG(LKG) }}$ | PG pin Leakage current when open drain output is high | $\mathrm{V}_{\mathrm{PG}}=5 \mathrm{~V}$ |  |  | 100 | nA  |
|   | PG pin output low-level voltage | $\mathrm{I}_{\mathrm{PG}}=1 \mathrm{~mA}$ |  |  | 400 | mV  |
|  OUTPUT DISCHARGE |  |  |  |  |  |   |# 6.5 Electrical Characteristics (continued) 

$\mathrm{T}_{\mathrm{J}}=-40^{\circ} \mathrm{C}$ to $+125^{\circ} \mathrm{C}, \mathrm{V}_{\mathrm{IN}}=2.5 \mathrm{~V}$ to 5.5 V . Typical values are at $\mathrm{T}_{\mathrm{J}}=25^{\circ} \mathrm{C}$ and $\mathrm{V}_{\mathrm{IN}}=5 \mathrm{~V}$ (unless otherwise noted)

| PARAMETER |  | TEST CONDITIONS | MIN | TYP | MAX | UNIT |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | Output discharge current on SW pin | $\mathrm{V}_{\mathrm{IN}}=3 \mathrm{~V}, \mathrm{~V}_{\text {OUT }}=2.0 \mathrm{~V}$; TPS62A01xDRL |  | 60 |  | mA |
|  | Output discharge current on SW pin | $\begin{aligned} & \mathrm{V}_{\mathrm{IN}}=3 \mathrm{~V}, \mathrm{~V}_{\text {OUT }}=2.0 \mathrm{~V} ; \text { TPS62A01xDDC; } \\ & \text { TPS62A02 } \end{aligned}$ |  | 76 |  | mA |
| THERMAL SHUTDOWN |  |  |  |  |  |  |
| $\mathrm{T}_{\mathrm{J(SD)}}$ | Thermal shutdown threshold | Temperature rising |  | 170 |  | ${ }^{\circ} \mathrm{C}$ |
| $\mathrm{T}_{\mathrm{J(HYS)}}$ | Thermal shutdown hysteresis |  |  | 20 |  | ${ }^{\circ} \mathrm{C}$ |# 6.6 Typical Characteristics 

![img-3.jpeg](img-3.jpeg)# 7 Detailed Description 

### 7.1 Overview

The TPS62A0x is a high-efficiency synchronous step-down converter. The device operates with an adaptive off time with a peak current control scheme. The device operates typically at 2.4 MHz frequency pulse width modulation (PWM) at moderate to heavy load currents. Based on the $\mathrm{V}_{\text {IN }} / \mathrm{V}_{\text {OUT }}$ ratio, a simple circuit sets the required off time for the low-side MOSFET, making the switching frequency relatively constant regardless of the variation of the input voltage, output voltage, and load current.

### 7.2 Functional Block Diagram

![img-4.jpeg](img-4.jpeg)

### 7.3 Feature Description

### 7.3.1 Power Save Mode

The device automatically enters power save mode to improve efficiency at light load when the inductor current becomes discontinuous. In power save mode, the converter reduces the switching frequency and minimizes current consumption. In power save mode, the output voltage rises slightly above the nominal output voltage. This effect is minimized by increasing the output capacitor or adding a feedforward capacitor.# 7.3.2 100\% Duty Cycle Low Dropout Operation 

The device offers low input-to-output voltage difference by entering 100\% duty cycle mode. In this mode, the high-side MOSFET switch is constantly turned on and the low-side MOSFET is switched off. The minimum input voltage to maintain output regulation, depending on the load current and output voltage, is calculated as:

$$
\mathrm{V}_{\mathrm{IN}(\mathrm{MIN})}=\mathrm{V}_{\mathrm{OUT}}+\mathrm{I}_{\mathrm{OUT}} \times\left(\mathrm{R}_{\mathrm{DS}(\mathrm{ON})}+\mathrm{R}_{\mathrm{L}}\right)
$$

where

- $\mathrm{R}_{\mathrm{DS}(\mathrm{ON})}=$ High-side FET on-resistance
- $\mathrm{R}_{\mathrm{L}}=$ Inductor ohmic resistance (DCR)


### 7.3.3 Soft Start

After enabling the device, internal soft-start circuitry ramps up the output voltage, which reaches the nominal output voltage during start-up time, avoiding excessive inrush current and creating a smooth voltage rise slope. Internal soft-start circuitry also prevents excessive voltage drops of primary cells and rechargeable batteries with high internal impedance.

The TPS62A0x is able to start into a prebiased output capacitor. The converter starts with the applied bias voltage and ramps the output voltage to the nominal value.

### 7.3.4 Switch Current Limit and Short-Circuit Protection (HICCUP)

The switch current limit prevents the device from high inductor current and drawing excessive current from the battery or input rail. Due to internal propagation delay, the AC peak current can exceed the static current limit during that time. Excessive current can occur with a shorted or saturated inductor, an overload or shorted output circuit condition. If the inductor current reaches the threshold $\mathrm{I}_{\mathrm{LIM}}$, the high-side MOSFET is turned off and the low-side MOSFET is turned on to ramp down the inductor current with an adaptive off time.

When this switch current limit is triggered 32 times, the device stops switching to protect the output. The device then automatically starts a new start-up after a typical delay time of $100 \mu \mathrm{~s}$ has passed. This is named HICCUP short-circuit protection. The device repeats this mode until the high load condition disappears. HICCUP protection is also enabled during the start-up.

### 7.3.5 Undervoltage Lockout

To avoid misoperation of the device at low input voltages, an undervoltage lockout (UVLO) is implemented, which shuts down the device at voltages lower than $\mathrm{V}_{\text {UVLO }}$.

### 7.3.6 Thermal Shutdown

The device goes into thermal shutdown and stops switching when the junction temperature exceeds $T_{J S D}$. When the device temperature falls below the threshold by $20^{\circ} \mathrm{C}$, the device returns to normal operation automatically.

### 7.4 Device Functional Modes

### 7.4.1 Enable and Disable

The device is enabled by setting the EN input to a logic High. Accordingly, a logic Low disables the device. If the device is enabled, the internal power stage starts switching and regulates the output voltage to the set point voltage. The EN input must be terminated and not be left floating.

### 7.4.2 Power Good

The TPS62A0x (except devices with 'N' suffix) has a built-in power-good (PG) feature to indicate whether the output voltage has reached the target and the device is ready. The PG signal can be used for start-up sequencing of multiple rails. The PG pin is an open-drain output that requires a pullup resistor to any voltage up to the recommended input voltage level. PG is low when the device is turned off due to EN, UVLO (undervoltage lockout), or thermal shutdown. VIN must remain present for the PG pin to stay low. If not used, the power-goodcan be tie to GND or left open. The PG indicator has a de-glitch to avoid the signal indicating glitches or transient responses from the loop.

Table 7-1. Power-Good indicator Functional Table

| Logic Signals |  |  |  | PG Status |
| :--: | :--: | :--: | :--: | :--: |
| $V_{i}$ | EN Pin | Thermal Shutdown | $V_{O}$ |  |
| $V_{i}>$ UVLO | HIGH | NO | $V_{O}$ on target | High Impedance |
|  |  |  | $V_{O}<$ target | LOW |
|  |  |  | YES | LOW |
|  |  | YES | $x$ | LOW |
|  | LOW | $x$ | $x$ | LOW |
| $V_{i}<1.8 \mathrm{~V}$ | $x$ | $x$ | $x$ | Undefined |# 8 Application and Implementation 

## Note

Information in the following applications sections is not part of the TI component specification, and TI does not warrant its accuracy or completeness. TI's customers are responsible for determining suitability of components for their purposes, as well as validating and testing their design implementation to confirm system functionality.

### 8.1 Application Information

The following section discusses the design of the external components to complete the power supply design for several input and output voltage options by using typical applications as a reference.

### 8.2 Typical Application

![img-5.jpeg](img-5.jpeg)

Figure 8-1. TPS62A01 Typical Application Circuit
![img-6.jpeg](img-6.jpeg)

Figure 8-2. TPS62A02 Typical Application Circuit
![img-7.jpeg](img-7.jpeg)

Figure 8-3. TPS62A02N Typical Application Circuit
*C3 is optional# 8.2.1 Design Requirements 

For this design example, use the parameters listed in Table 8-1 as the input parameters
Table 8-1. Design Parameters

| Design Parameter | Example Value |
| :--: | :--: |
| Input voltage | 2.5 V to 5.5 V |
| Output voltage | 1.8 V |
| Maximum output current | $1.0 \mathrm{~A}, 2.0 \mathrm{~A}$ |

Table 8-2 lists the components used for the example.
Table 8-2. List of Components

| Reference | Description | Manufacturer ${ }^{(1)}$ |
| :--: | :--: | :--: |
| C1 | 4.7 $\mu \mathrm{F}$, Ceramic Capacitor, 10V, X7R, size <br> 0805, GRM21BR71A475KA73L | Murata |
| C2 | 22 $\mu \mathrm{F}$, Ceramic Capacitor, 10V, X7R, size <br> 0805, GRM21BZ71A226KE15L | Murata |
| L1 | $1 \mu \mathrm{H}$, Power Inductor, DFE252012F-1R0M <br> (1A) / XGL3520-102MEC (2A) | Murata / Coilcraft |
| R1, R2 | Chip resistor, 1\%, size 0603 | Std. |
| C3 | Optional, 120pF if needed | Std. |

(1) See the Third-Party Products Disclaimer.

### 8.2.2 Detailed Design Procedure

### 8.2.2.1 Setting the Output Voltage

The output voltage is set by an external resistor divider according to Equation 2.

$$
R 1=R 2 \times\left(\frac{V_{O U T}}{V_{F B}}-1\right)=R 2 \times\left(\frac{V_{O U T}}{0.6 V}-1\right)
$$

R2 must not be higher than $100 \mathrm{k} \Omega$ to provide acceptable noise sensitivity.

### 8.2.2.2 Output Filter Design

The inductor and output capacitor together provide a low-pass filter. To simplify this process, Table 8-3 outlines possible inductor and capacitor value combinations. Checked cells represent combinations that are proven for stability by simulation and lab test. Check further combinations for each individual application.

Table 8-3. Matrix of Output Capacitor and Inductor Combinations for TPS62A01 and TPS62A02

| $\mathbf{V}_{\text {OUT }}[\mathbf{V}]$ | $\mathbf{L}[\mu \mathrm{H}]^{(1)}$ | $\mathbf{C}_{\text {OUT }}[\mu \mathrm{F}]^{(2)}$ |  |  |
| :--: | :--: | :--: | :--: | :--: |
|  |  | 10 | 22 | $2 \times 22$ |
| $0.6 \leq V_{\text {OUT }}<1.2$ | 1 |  | $+$ | $++^{(3)}$ |
| $1.2 \leq V_{\text {OUT }}<1.8$ |  |  | $++^{(3)}$ | $+$ |
| $1.8 \leq V_{\text {OUT }}$ |  | $+(4)$ | $++(3)$ | $+$ |

(1) Inductor tolerance and current de-rating is anticipated. The effective inductance can vary by $+20 \%$ and $-30 \%$.
(2) Capacitance tolerance and bias voltage de-rating is anticipated. The effective capacitance can vary by $+20 \%$ and $-50 \%$.
(3) This LC combination is the standard value and recommended for most applications.
(4) The minimum $\mathrm{C}_{\text {OUT }}$ of $10 \mu \mathrm{~F}$ does not support an additional feedforward capacitor.

A 0.47 uH inductor can also be used with the same recommended output capacitors for the TPS62A02x. In case a lower output ripple is desired, higher output capacitance can help reduce the ripple.

### 8.2.2.3 Input and Output Capacitor Selection

The architecture of the TPS62A0x allows use of tiny ceramic-type output capacitors with low equivalent series resistance (ESR). These capacitors provide low output voltage ripple and are thus recommended. To keepresistance up to high frequencies and to achieve narrow capacitance variation with temperature, TI recommends to use X7R or X5R dielectric.

The input capacitor is the low impedance energy source for the converter that helps provide stable operation. TI recommends a low-ESR multilayer ceramic capacitor for best filtering. For most applications, a $4.7 \mu \mathrm{~F}$ input capacitor is sufficient; a larger value reduces input voltage ripple.

The TPS62A0x is designed to operate with an output capacitor of $10 \mu \mathrm{~F}$ to $47 \mu \mathrm{~F}$, depending on the selected output voltage, as outlined in Table 8-3.

A feedforward capacitor reduces the output ripple in PSM and improves the load transient response. A 120pF capacitor is good for the 1.8 V output typical application.# 8.2.3 Application Curves 

![img-8.jpeg](img-8.jpeg)![img-9.jpeg](img-9.jpeg)

Figure 8-10. 1.8V Output Efficiency
![img-10.jpeg](img-10.jpeg)

Figure 8-12. 0.6V Output Efficiency
![img-11.jpeg](img-11.jpeg)

Figure 8-14. 1.8V Output Efficiency
![img-12.jpeg](img-12.jpeg)

Figure 8-11. 1.8V Output Efficiency
![img-13.jpeg](img-13.jpeg)

Figure 8-13. 1.2V Output Efficiency
![img-14.jpeg](img-14.jpeg)

Figure 8-15. 1.8V Output Efficiency![img-15.jpeg](img-15.jpeg)

Figure 8-16. 0.6V Output Efficiency
![img-16.jpeg](img-16.jpeg)

Figure 8-18. 1.8V Output Efficiency
![img-17.jpeg](img-17.jpeg)

Figure 8-20. PWM Operation
![img-18.jpeg](img-18.jpeg)

Figure 8-17. 1.2V Output Efficiency
![img-19.jpeg](img-19.jpeg)

Figure 8-19. 1.8V Output Efficiency
![img-20.jpeg](img-20.jpeg)

Figure 8-21. Power Save Mode Operation![img-21.jpeg](img-21.jpeg)

# 8.3 Power Supply Recommendations 

The device is designed to operate from an input voltage supply range from 2.5 V to 5.5 V . Make sure that the input power supply has a sufficient current rating for the application.

### 8.4 Layout

### 8.4.1 Layout Guidelines

The printed-circuit-board (PCB) layout is an important step to maintain the high performance of the TPS62A01x and TPS62A02x devices.

- Place the input and output capacitors and the inductor as close as possible to the IC. This action keeps the power traces short. Routing these power traces direct and wide results in low trace resistance and low parasitic inductance.
- Connect the low side of the input and output capacitors properly to the GND pin to avoid a ground potential shift.
- The sense traces connected to FB is a signal trace. Take special care to avoid noise being induced. Keep these traces away from SW nodes.
- Use a common ground. GND layers can be used for shielding.

See Figure 8-24 and Figure 8-25 for the recommended PCB layout.

### 8.4.2 Layout Example

![img-22.jpeg](img-22.jpeg)

Figure 8-24. TPS62A0x (SOT563) PCB Layout Recommendation![img-23.jpeg](img-23.jpeg)

Figure 8-25. TPS62A0x (SOT23-6) PCB Layout Recommendation# 9 Device and Documentation Support 

### 9.1 Device Support

### 9.1.1 Third-Party Products Disclaimer

TI'S PUBLICATION OF INFORMATION REGARDING THIRD-PARTY PRODUCTS OR SERVICES DOES NOT CONSTITUTE AN ENDORSEMENT REGARDING THE SUITABILITY OF SUCH PRODUCTS OR SERVICES OR A WARRANTY, REPRESENTATION OR ENDORSEMENT OF SUCH PRODUCTS OR SERVICES, EITHER ALONE OR IN COMBINATION WITH ANY TI PRODUCT OR SERVICE.

### 9.2 Receiving Notification of Documentation Updates

To receive notification of documentation updates, navigate to the device product folder on ti.com. Click on Notifications to register and receive a weekly digest of any product information that has changed. For change details, review the revision history included in any revised document.

### 9.3 Support Resources

TI E2E ${ }^{\text {TM }}$ support forums are an engineer's go-to source for fast, verified answers and design help - straight from the experts. Search existing answers or ask your own question to get the quick design help you need.
Linked content is provided "AS IS" by the respective contributors. They do not constitute TI specifications and do not necessarily reflect TI's views; see TI's Terms of Use.

### 9.4 Trademarks

TI E2E ${ }^{\text {TM }}$ is a trademark of Texas Instruments.
All trademarks are the property of their respective owners.

### 9.5 Electrostatic Discharge Caution

This integrated circuit can be damaged by ESD. Texas Instruments recommends that all integrated circuits be handled with appropriate precautions. Failure to observe proper handling and installation procedures can cause damage.
ESD damage can range from subtle performance degradation to complete device failure. Precision integrated circuits may be more susceptible to damage because very small parametric changes could cause the device not to meet its published specifications.

### 9.6 Glossary

TI Glossary This glossary lists and explains terms, acronyms, and definitions.# 10 Revision History 

NOTE: Page numbers for previous revisions may differ from page numbers in the current version.
Changes from Revision D (April 2024) to Revision E (June 2024)
Page

- Changed device status of TPS62A02Nx versions and devices in DDC package from preview to production throughout the data sheet. ..... 3
Changes from Revision C (December 2023) to Revision D (April 2024) Page
- Added devices with ' N ' suffix throughout the data sheet ..... 1
- Changed absolute maximum voltage of VIN, EN and PG from 6 V to 6.5 V ..... 4
- Updated block diagram to include devices with ' N ' suffix (OUT instead of PG) ..... 8
Changes from Revision B (July 2022) to Revision C (December 2023) Page
- Added DDC package option throughout the data sheet ..... 3
- Changed ESD Ratings CDM row from showing testing was per JESD22-C101 to show that testing was per JS-002 ..... 4
- Changed block diagram PG circuit by swapping $\mathrm{V}_{\mathrm{PG}}$ and $\mathrm{V}_{\mathrm{FB}}$ ..... 8


## 11 Mechanical, Packaging, and Orderable Information

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
|  TPS62A01ADRLR | Active | Production | SOT-5X3 (DRL) | 6 | 4000 | LARGE T\&R | Yes | Call TI | Sn | Level-1-260C-UNLIM | $-40$ to 125  |
|  TPS62A01ADRLR.A | Active | Production | SOT-5X3 (DRL) | 6 | 4000 | LARGE T\&R | Yes | SN | Level-1-260C-UNLIM | $-40$ to 125 | 1J8  |
|  TPS62A01APDDCR | Active | Production | SOT-23-
THIN (DDC) | 6 | 3000 | LARGE T\&R | Yes | Call TI | Sn | Level-1-260C-UNLIM | $-40$ to 125  |
|  TPS62A01APDDCR.A | Active | Production | SOT-23-
THIN (DDC) | 6 | 3000 | LARGE T\&R | Yes | SN | Level-1-260C-UNLIM | $-40$ to 125 | A01AP  |
|  TPS62A01DRLR | Active | Production | SOT-5X3 (DRL) | 6 | 4000 | LARGE T\&R | Yes | Call TI | Sn | Level-1-260C-UNLIM | $-40$ to 125  |
|  TPS62A01DRLR.A | Active | Production | SOT-5X3 (DRL) | 6 | 4000 | LARGE T\&R | Yes | SN | Level-1-260C-UNLIM | $-40$ to 125 | 1J7  |
|  TPS62A01PDDCR | Active | Production | SOT-23-
THIN (DDC) | 6 | 3000 | LARGE T\&R | Yes | Call TI | Sn | Level-1-260C-UNLIM | $-40$ to 125  |
|  TPS62A01PDDCR.A | Active | Production | SOT-23-
THIN (DDC) | 6 | 3000 | LARGE T\&R | Yes | SN | Level-1-260C-UNLIM | $-40$ to 125 | A01P  |
|  TPS62A02ADRLR | Active | Production | SOT-5X3 (DRL) | 6 | 4000 | LARGE T\&R | Yes | Call TI | Sn | Level-1-260C-UNLIM | $-40$ to 125  |
|  TPS62A02ADRLR.A | Active | Production | SOT-5X3 (DRL) | 6 | 4000 | LARGE T\&R | Yes | SN | Level-1-260C-UNLIM | $-40$ to 125 | 1JM  |
|  TPS62A02APDDCR | Active | Production | SOT-23-
THIN (DDC) | 6 | 3000 | LARGE T\&R | Yes | Call TI | Sn | Level-1-260C-UNLIM | $-40$ to 125  |
|  TPS62A02APDDCR.A | Active | Production | SOT-23-
THIN (DDC) | 6 | 3000 | LARGE T\&R | Yes | SN | Level-1-260C-UNLIM | $-40$ to 125 | A02AP  |
|  TPS62A02DRLR | Active | Production | SOT-5X3 (DRL) | 6 | 4000 | LARGE T\&R | Yes | Call TI | Sn | Level-1-260C-UNLIM | $-40$ to 125  |
|  TPS62A02DRLR.A | Active | Production | SOT-5X3 (DRL) | 6 | 4000 | LARGE T\&R | Yes | SN | Level-1-260C-UNLIM | $-40$ to 125 | 1JL  |
|  TPS62A02NADRLR | Active | Production | SOT-5X3 (DRL) | 6 | 4000 | LARGE T\&R | Yes | Call TI | Sn | Level-1-260C-UNLIM | $-40$ to 125  |
|  TPS62A02NADRLR.A | Active | Production | SOT-5X3 (DRL) | 6 | 4000 | LARGE T\&R | Yes | SN | Level-1-260C-UNLIM | $-40$ to 125 | 1SC  |
|  TPS62A02NDRLR | Active | Production | SOT-5X3 (DRL) | 6 | 4000 | LARGE T\&R | Yes | SN | Level-1-260C-UNLIM | $-40$ to 125 | 1SB  |
|  TPS62A02NDRLR.A | Active | Production | SOT-5X3 (DRL) | 6 | 4000 | LARGE T\&R | Yes | SN | Level-1-260C-UNLIM | $-40$ to 125 | 1SB  |
|  TPS62A02PDDCR | Active | Production | SOT-23-
THIN (DDC) | 6 | 3000 | LARGE T\&R | Yes | Call TI | Sn | Level-1-260C-UNLIM | $-40$ to 125  |
|  TPS62A02PDDCR.A | Active | Production | SOT-23-
THIN (DDC) | 6 | 3000 | LARGE T\&R | Yes | SN | Level-1-260C-UNLIM | $-40$ to 125 | A02P  |

${ }^{(1)}$ Status: For more details on status, see our product life cycle.# PACKAGE OPTION ADDENDUM 

(2) Material type: When designated, preproduction parts are prototypes/experimental devices, and are not yet approved or released for full production. Testing and final process, including without limitation quality assurance, reliability performance testing, and/or process qualification, may not yet be complete, and this item is subject to further changes or possible discontinuation. If available for ordering, purchases will be subject to an additional waiver at checkout, and are intended for early internal evaluation purposes only. These items are sold without warranties of any kind.
${ }^{(3)}$ RoHS values: Yes, No, RoHS Exempt. See the TI RoHS Statement for additional information and value definition.
${ }^{(4)}$ Lead finish/Ball material: Parts may have multiple material finish options. Finish options are separated by a vertical ruled line. Lead finish/Ball material values may wrap to two lines if the finish value exceeds the maximum column width.
${ }^{(5)}$ MSL rating/Peak reflow: The moisture sensitivity level ratings and peak solder (reflow) temperatures. In the event that a part has multiple moisture sensitivity ratings, only the lowest level per JEDEC standards is shown. Refer to the shipping label for the actual reflow temperature that will be used to mount the part to the printed circuit board.
${ }^{(6)}$ Part marking: There may be an additional marking, which relates to the logo, the lot trace code information, or the environmental category of the part.

Multiple part markings will be inside parentheses. Only one part marking contained in parentheses and separated by a "-" will appear on a part. If a line is indented then it is a continuation of the previous line and the two combined represent the entire part marking for that device.

Important Information and Disclaimer:The information provided on this page represents TI's knowledge and belief as of the date that it is provided. TI bases its knowledge and belief on information provided by third parties, and makes no representation or warranty as to the accuracy of such information. Efforts are underway to better integrate information from third parties. TI has taken and continues to take reasonable steps to provide representative and accurate information but may not have conducted destructive testing or chemical analysis on incoming materials and chemicals. TI and TI suppliers consider certain information to be proprietary, and thus CAS numbers and other limited information may not be available for release.

In no event shall TI's liability arising out of such information exceed the total purchase price of the TI part(s) at issue in this document sold by TI to Customer on an annual basis.

## OTHER QUALIFIED VERSIONS OF TPS62A01, TPS62A01A, TPS62A02, TPS62A02A :

- Automotive : TPS62A01-Q1, TPS62A01A-Q1, TPS62A02-Q1, TPS62A02A-Q1

NOTE: Qualified Version Definitions:

- Automotive - Q100 devices qualified for high-reliability automotive applications targeting zero defects# TAPE AND REEL INFORMATION 

![img-24.jpeg](img-24.jpeg)

TAPE DIMENSIONS
![img-25.jpeg](img-25.jpeg)

| A0 | Dimension designed to accommodate the component width |
| :-- | :-- |
| B0 | Dimension designed to accommodate the component length |
| K0 | Dimension designed to accommodate the component thickness |
| W | Overall width of the carrier tape |
| P1 | Pitch between successive cavity centers |

QUADRANT ASSIGNMENTS FOR PIN 1 ORIENTATION IN TAPE
![img-26.jpeg](img-26.jpeg)
*All dimensions are nominal

| Device | Package <br> Type | Package <br> Drawing | Pins | SPQ | Reel <br> Diameter <br> (mm) | Reel <br> Width <br> W1 (mm) | A0 <br> (mm) | B0 <br> (mm) | K0 <br> (mm) | P1 <br> (mm) | W <br> (mm) | Pin1 <br> Quadrant |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| TPS62A01ADRLR | SOT-5X3 | DRL | 6 | 4000 | 180.0 | 8.4 | 2.0 | 1.8 | 0.75 | 4.0 | 8.0 | Q3 |
| TPS62A01APDDCR | SOT-23- <br> THIN | DDC | 6 | 3000 | 180.0 | 8.4 | 3.2 | 3.2 | 1.4 | 4.0 | 8.0 | Q3 |
| TPS62A01DRLR | SOT-5X3 | DRL | 6 | 4000 | 180.0 | 8.4 | 2.0 | 1.8 | 0.75 | 4.0 | 8.0 | Q3 |
| TPS62A01PDDCR | SOT-23- <br> THIN | DDC | 6 | 3000 | 180.0 | 8.4 | 3.2 | 3.2 | 1.4 | 4.0 | 8.0 | Q3 |
| TPS62A02ADRLR | SOT-5X3 | DRL | 6 | 4000 | 180.0 | 8.4 | 2.0 | 1.8 | 0.75 | 4.0 | 8.0 | Q3 |
| TPS62A02APDDCR | SOT-23- <br> THIN | DDC | 6 | 3000 | 180.0 | 8.4 | 3.2 | 3.2 | 1.4 | 4.0 | 8.0 | Q3 |
| TPS62A02DRLR | SOT-5X3 | DRL | 6 | 4000 | 180.0 | 8.4 | 1.8 | 1.8 | 0.75 | 4.0 | 8.0 | Q3 |
| TPS62A02DRLR | SOT-5X3 | DRL | 6 | 4000 | 180.0 | 8.4 | 2.0 | 1.8 | 0.75 | 4.0 | 8.0 | Q3 |
| TPS62A02NADRLR | SOT-5X3 | DRL | 6 | 4000 | 180.0 | 8.4 | 2.0 | 1.8 | 0.75 | 4.0 | 8.0 | Q3 |
| TPS62A02NDRLR | SOT-5X3 | DRL | 6 | 4000 | 180.0 | 8.4 | 2.0 | 1.8 | 0.75 | 4.0 | 8.0 | Q3 |
| TPS62A02PDDCR | SOT-23- <br> THIN | DDC | 6 | 3000 | 180.0 | 8.4 | 3.2 | 3.2 | 1.4 | 4.0 | 8.0 | Q3 |# PACKAGE MATERIALS INFORMATION

## TAPE AND REEL BOX DIMENSIONS

![img-27.jpeg](img-27.jpeg)

*All dimensions are nominal

|  Device | Package Type | Package Drawing | Pins | SPQ | Length (mm) | Width (mm) | Height (mm)  |
| --- | --- | --- | --- | --- | --- | --- | --- |
|  TPS62A01ADRLR | SOT-5X3 | DRL | 6 | 4000 | 210.0 | 185.0 | 35.0  |
|  TPS62A01APDDCR | SOT-23-THIN | DDC | 6 | 3000 | 210.0 | 185.0 | 35.0  |
|  TPS62A01DRLR | SOT-5X3 | DRL | 6 | 4000 | 210.0 | 185.0 | 35.0  |
|  TPS62A01PDDCR | SOT-23-THIN | DDC | 6 | 3000 | 210.0 | 185.0 | 35.0  |
|  TPS62A02ADRLR | SOT-5X3 | DRL | 6 | 4000 | 210.0 | 185.0 | 35.0  |
|  TPS62A02APDDCR | SOT-23-THIN | DDC | 6 | 3000 | 210.0 | 185.0 | 35.0  |
|  TPS62A02DRLR | SOT-5X3 | DRL | 6 | 4000 | 210.0 | 185.0 | 35.0  |
|  TPS62A02DRLR | SOT-5X3 | DRL | 6 | 4000 | 210.0 | 185.0 | 35.0  |
|  TPS62A02NADRLR | SOT-5X3 | DRL | 6 | 4000 | 210.0 | 185.0 | 35.0  |
|  TPS62A02NDRLR | SOT-5X3 | DRL | 6 | 4000 | 210.0 | 185.0 | 35.0  |
|  TPS62A02PDDCR | SOT-23-THIN | DDC | 6 | 3000 | 210.0 | 185.0 | 35.0  |![img-28.jpeg](img-28.jpeg)

NOTES:

1. All linear dimensions are in millimeters. Any dimensions in parenthesis are for reference only. Dimensioning and tolerancing per ASME Y14.5M.
2. This drawing is subject to change without notice.
3. Reference JEDEC MO-193.![img-29.jpeg](img-29.jpeg)

NOTES: (continued)
4. Publication IPC-7351 may have alternate designs.
5. Solder mask tolerances between and around signal pads can vary based on board fabrication site.![img-30.jpeg](img-30.jpeg)

NOTES: (continued)
6. Laser cutting apertures with trapezoidal walls and rounded corners may offer better paste release. IPC-7525 may have alternate design recommendations.
7. Board assembly site may have different recommendations for stencil design.![img-31.jpeg](img-31.jpeg)

NOTES:

1. All linear dimensions are in millimeters. Any dimensions in parenthesis are for reference only. Dimensioning and tolerancing per ASME Y14.5M.
2. This drawing is subject to change without notice.
3. This dimension does not include mold flash, protrusions, or gate burrs. Mold flash, protrusions, or gate burrs shall not exceed 0.15 mm per side.
4. Reference JEDEC registration MO-293 Variation UAAD![img-32.jpeg](img-32.jpeg)

NOTES: (continued)
5. Publication IPC-7351 may have alternate designs.
6. Solder mask tolerances between and around signal pads can vary based on board fabrication site.
7. Land pattern design aligns to IPC-610, Bottom Termination Component (BTC) solder joint inspection criteria.![img-33.jpeg](img-33.jpeg)

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