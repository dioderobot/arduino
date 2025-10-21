# Future Technology Devices International Ltd FT232R USB UART IC Datasheet 

The FT232R is a USB to serial UART interface with the following advanced features:

- Single chip USB to asynchronous serial data transfer interface.
- Entire USB protocol handled on the chip. No USB specific firmware programming required.
- Fully integrated 1024 bit EEPROM storing device descriptors and CBUS I/O configuration.
- Fully integrated USB termination resistors.
- Fully integrated clock generation with no external crystal required plus optional clock output selection enabling a glue-less interface to external MCU or FPGA.
- Data transfer rates from 300 baud to 3 Mbaud (RS422, RS485, RS232) at TTL levels.
- 128 byte receive buffer and 256 byte transmit buffer utilising buffer smoothing technology to allow for high data throughput.
- FTDI's royalty-free Virtual Com Port (VCP) and Direct (D2XX) drivers eliminate the requirement for USB driver development in most cases.
- Unique USB FTDIChip-ID ${ }^{\text {TM }}$ feature.
- Configurable CBUS I/O pins.
- Transmit and receive LED drive signals.
- UART interface support for 7 or 8 data bits, 1 or 2 stop bits and odd / even / mark / space / no parity
![img-0.jpeg](img-0.jpeg)
- FIFO receives and transmits buffers for high data throughput.
- Synchronous and asynchronous bit bang interface options with RD\# and WR\# strobes.
- Device supplied pre-programmed with unique USB serial number.
- Supports bus powered, self-powered and highpower bus powered USB configurations.
- Integrated +3.3 V level converter for USB I/O.
- Integrated level converter on UART and CBUS for interfacing to between +1.8 V and +5 V logic.
- True 5V/3.3V/2.8V/1.8V CMOS drive output and TTL input.
- Configurable I/O pin output drive strength.
- Integrated power-on-reset circuit.
- Fully integrated AVCC supply filtering - no external filtering required.
- UART signal inversion option.
- +3.3 V (using external oscillator) to +5.25 V (internal oscillator) Single Supply Operation.
- Low operating and USB suspend current.
- Low USB bandwidth consumption.
- UHCI/OHCI/EHCI host controller compatible.
- USB 2.0 Full Speed compatible.
- $-40^{\circ} \mathrm{C}$ to $85^{\circ} \mathrm{C}$ extended operating temperature range.
- Available in compact Pb -free 28 Pin SSOP and QFN-32 packages (both RoHS compliant).

[^0]
[^0]:    Neither the whole nor any part of the information contained in, or the product described in this manual, may be adapted or reproduced in any material or electronic form without the prior written consent of the copyright holder. This product and its documentation are supplied on an as-is basis and no warranty as to their suitability for any particular purpose is either made or implied. Future Technology Devices International Ltd will not accept any claim for damages howsoever arising as a result of use or failure of this product. Your statutory rights are not affected. This product or any variant of it is not intended for use in any medical appliance, device or system in which the failure of the product might reasonably be expected to result in personal injury. This document provides preliminary information that may be subject to change without notice. No freedom to use patents or other intellectual property rights is implied by the publication of this document. Future Technology Devices International Ltd, Unit 1, 2 Seaward Place, Centurion Business Park, Glasgow G41 1HH United Kingdom. Scotland Registered Company Number: SC136640# 1 Typical Applications 

- USB to RS232/RS422/RS485 Converters
- Upgrading Legacy Peripherals to USB
- Cellular and Cordless Phone USB data transfer cables and interfaces
- Interfacing MCU/PLD/FPGA based designs to USB
- USB Audio and Low Bandwidth Video data transfer
- PDA to USB data transfer
- USB Smart Card Readers
- USB Instrumentation


### 1.1 Driver Support

## Royalty free VIRTUAL COM PORT (VCP) DRIVERS for...

- Windows 10 32,64-bit
- Windows 8/8.1 32,64-bit
- Windows 7 32,64-bit
- Windows Vista and Vista 64-bit
- Windows XP and XP 64-bit
- Windows 98, 98SE, ME, 2000, Server 2003, XP, Server 2008 and server 2012 R2
- Windows XP Embedded
- Windows CE 4.2, 5.0 and 6.0
- Mac OS 8/9, OS-X
- Linux 2.4 and greater
- USB Industrial Control
- USB MP3 Player Interface
- USB FLASH Card Reader and Writers
- Set Top Box PC - USB interface
- USB Digital Camera Interface
- USB Hardware Modems
- USB Wireless Modems
- USB Bar Code Readers
- USB Software and Hardware Encryption Dongles


## Royalty free D2XX Direct Drivers (USB Drivers + DLL S/W Interface)

- Windows 10 32,64-bit
- Windows 8/8.1 32,64-bit
- Windows 7 32,64-bit
- Windows Vista and Vista 64-bit
- Windows XP and XP 64-bit
- Windows 98, 98SE, ME, 2000, Server 2003, XP, Server 2008 and server 2012 R2
- Windows XP Embedded
- Windows CE 4.2, 5.0 and 6.0
- Linux 2.4 and greater
- Android(J2xx)

The drivers listed above are all available to download for free from FTDI website (www.ftdichip.com). Various 3rd party drivers are also available for other operating systems - see FTDI website (www.ftdichip.com) for details.

For driver installation, please refer to http://www.ftdichip.com/Documents/InstallGuides.htm# 1.2 Part Numbers 

| Part Number | Package |
| :-- | :-- |
| FT232RQ-xxxx | 32 Pin QFN |
| FT232RL-xxxx | 28 Pin SSOP |

Note: Packing codes for xxxx is:

- Reel: Taped and Reel, (SSOP is 2,000pcs per reel, QFN is 6,000pcs per reel).
- Tube: Tube packing, 47pcs per tube (SSOP only)
- Tray: Tray packing, 490pcs per tray (QFN only)

For example: FT232RQ-Reel is 6,000pcs taped and reel packing

### 1.3 USB Compliant

The FT232R is fully compliant with the USB 2.0 specification and has been given the USB-IF Test-ID (TID) 40680004 (Rev B) and 40770018 (Rev C).
![img-1.jpeg](img-1.jpeg)# 2 FT232R Block Diagram 

![img-2.jpeg](img-2.jpeg)

Figure 2.1 FT232R Block Diagram
For a description of each function please refer to Section 4.# Table of Contents 

1 Typical Applications ..... 2
1.1 Driver Support ..... 2
1.2 Part Numbers ..... 3
1.3 USB Compliant ..... 3
2 FT232R Block Diagram ..... 4
3 Device Pin Out and Signal Description ..... 7
3.1 28-LD SSOP Package ..... 7
3.2 SSOP Package Pin Out Description ..... 7
3.3 QFN-32 Package ..... 9
3.4 QFN-32 Package Signal Description ..... 9
3.5 CBUS Signal Options ..... 11
4 Function Description ..... 12
4.1 Key Features ..... 12
4.2 Functional Block Descriptions ..... 13
5 Devices Characteristics and Ratings ..... 15
5.1 Absolute Maximum Ratings ..... 15
5.2 DC Characteristics ..... 15
5.3 EEPROM Reliability Characteristics ..... 17
5.4 Internal Clock Characteristics ..... 17
5.5 Thermal Characteristics ..... 18
6 USB Power Configurations ..... 19
6.1 USB Bus Powered Configuration ..... 19
6.2 Self Powered Configuration ..... 20
6.3 USB Bus Powered with Power Switching Configuration ..... 21
6.4 USB Bus Powered with Selectable External Logic Supply ..... 22
7 Application Examples ..... 24
7.1 USB to RS232 Converter ..... 24
7.2 USB to RS485 Converter ..... 25
7.3 USB to RS422 Converter ..... 26
7.4 USB to MCU UART Interface ..... 277.5 LED Interface ..... 28
7.6 Using the External Oscillator ..... 29
8 Internal EEPROM Configuration ..... 30
9 Package Parameters ..... 31
9.1 SSOP-28 Package Dimensions ..... 31
9.2 QFN-32 Package Dimensions ..... 32
9.3 Solder Reflow Profile ..... 33
10 Alternative Parts ..... 34
11 Contact Information ..... 35
Appendix A - References ..... 36
Document References ..... 36
Acronyms and Abbreviations ..... 36
Appendix B - List of Figures and Tables ..... 37
List of Figures ..... 37
List of Tables ..... 37
Appendix C - Revision History ..... 39# 3 Device Pin Out and Signal Description 

### 3.1 28-LD SSOP Package

![img-3.jpeg](img-3.jpeg)

Figure 3.1 SSOP Package Pin Out and Schematic Symbol

### 3.2 SSOP Package Pin Out Description

Note: The convention used throughout this document for active low signals is the signal name followed by\#

| Pin No. | Name | Type | Description |
| :--: | :--: | :--: | :--: |
| 15 | USBDP | I/O | USB Data Signal Plus, incorporating internal series resistor and $1.5 \mathrm{k} \Omega$ pull up resistor to 3.3 V . |
| 16 | USBDM | I/O | USB Data Signal Minus, incorporating internal series resistor. |

Table 3.1 USB Interface Group

| Pin No. | Name | Type | Description |
| :--: | :--: | :--: | :--: |
| 4 | VCCIO | PWR | +1.8 V to +5.25 V supply to the UART Interface and CBUS group pins $(1 \ldots 3,5,6,9 \ldots 14,22,23)$. In USB bus powered designs connect this pin to 3V3OUT pin to drive out at +3.3 V levels, or connect to VCC to drive out at 5 V CMOS level. This pin can also be supplied with an external +1.8 V to +2.8 V supply in order to drive outputs at lower levels. It should be noted that in this case this supply should originate from the same source as the supply to VCC. This means that in bus powered designs a regulator which is supplied by the +5 V on the USB bus should be used. |
| $\begin{aligned} & 7,18 \\ & 21 \end{aligned}$ | GND | PWR | Device ground supply pins |
| 17 | 3V3OUT | Output | +3.3 V output from integrated LDO regulator. This pin should be decoupled to ground using a 100 nF capacitor. The main use of this pin is to provide the internal +3.3 V supply to the USB transceiver cell and the internal $1.5 \mathrm{k} \Omega$ pull up resistor on USBDP. Up to 50 mA can be drawn from || Pin No. | Name | Type | Description |
| :--: | :--: | :--: | :--: |
|  |  |  | this pin to power external logic if required. This pin can also be used to supply the VCCIO pin. |
| 20 | VCC | PWR | +3.3 V to +5.25 V supply to the device core. (see Note 1) |
| 25 | AGND | PWR | Device analogue ground supply for internal clock multiplier |

Table 3.2 Power and Ground Group

| Pin No. | Name | Type | Description |
| :--: | :--: | :--: | :-- |
| 8,24 | NC | NC | No internal connection |
| 19 | RESET\# | Input | Active low reset pin. This can be used by an external device to reset the FT232R. If not required can be left unconnected, or pulled up to VCC. |
| 26 | TEST | Input | Puts the device into IC test mode. Must be tied to GND for normal operation, otherwise the device will appear to fail. |
| 27 | OSCI | Input | Input 12MHz Oscillator Cell. Optional - Can be left unconnected for normal operation. (see Note 2) |
| 28 | OSCO | Output | Output from 12MHZ Oscillator Cell. Optional - Can be left unconnected for normal operation if internal Oscillator is used. (see Note 2) |

Table 3.3 Miscellaneous Signal Group

| Pin No. | Name | Type | Description |
| :--: | :--: | :--: | :-- |
| 1 | TXD | Output | Transmit Asynchronous Data Output. |
| 2 | DTR\# | Output | Data Terminal Ready Control Output / Handshake Signal. |
| 3 | RTS\# | Output | Request to Send Control Output / Handshake Signal. |
| 5 | RXD | Input | Receiving Asynchronous Data Input. |
| 6 | RI\# | Input | Ring Indicator Control Input. When remote wake up is enabled in the internal EEPROM taking RI\# low (20ms active low pulse) can be used to resume the PC USB host controller from suspend. |
| 9 | DSR\# | Input | Data Set Ready Control Input / Handshake Signal. |
| 10 | DCD\# | Input | Data Carrier Detect Control Input. |
| 11 | CTS\# | Input | Clear To Send Control Input / Handshake Signal. |
| 12 | CBUS4 | I/O | Configurable CBUS output only Pin. Function of this pin is configured in the device internal EEPROM. Factory default configuration is SLEEP\#. See CBUS Signal Options, Table 3.9. |
| 13 | CBUS2 | I/O | Configurable CBUS I/O Pin. Function of this pin is configured in the device internal EEPROM. Factory default configuration is TXDEN. See CBUS Signal Options, Table 3.9. |
| 14 | CBUS3 | I/O | Configurable CBUS I/O Pin. Function of this pin is configured in the device internal EEPROM. Factory default configuration is PWREN\#. See CBUS Signal Options, Table 3.9. PWREN\# should be used with a $10 \mathrm{k} \Omega$ resistor pull up. |
| 22 | CBUS1 | I/O | Configurable CBUS I/O Pin. Function of this pin is configured in the device internal EEPROM. Factory default configuration is RXLED\#. See CBUS Signal Options, Table 3.9. |
| 23 | CBUS0 | I/O | Configurable CBUS I/O Pin. Function of this pin is configured in the device internal EEPROM. Factory default configuration is TXLED\#. See CBUS Signal Options, Table 3.9. |

# Notes: 

1. The minimum operating voltage VCC must be +4.0 V (could use VBUS $=+5 \mathrm{~V}$ ) when using the internal clock generator. Operation at +3.3 V is possible using an external crystal oscillator.
2. For details on how to use an external crystal, ceramic resonator, or oscillator with the FT232R, please refer Section 7.6
3. When used in Input Mode, the input pins are pulled to VCCIO via internal $200 \mathrm{k} \Omega$ resistors. These pins can be programmed to gently pull low during USB suspend (PWREN\# = "1") by setting an option in the internal EEPROM.# 3.3 QFN-32 Package 

![img-4.jpeg](img-4.jpeg)

Figure 3.2 QFN-32 Package Pin Out and schematic symbol

### 3.4 QFN-32 Package Signal Description

| Pin No. | Name | Type | Description |
| :--: | :--: | :--: | :--: |
| 14 | USBDP | I/O | USB Data Signal Plus, incorporating internal series resistor and $1.5 \mathrm{k} \Omega$ pull up resistor to +3.3 V . |
| 15 | USBDM | I/O | USB Data Signal Minus, incorporating internal series resistor. |

Table 3.5 USB Interface Group

| Pin No. | Name | Type | Description |
| :--: | :--: | :--: | :--: |
| 1 | VCCIO | PWR | +1.8 V to +5.25 V supply for the UART Interface and CBUS group pins (2,3, $6,7,8,9,10,11,21,22,30,31,32)$. In USB bus powered designs connect this pin to 3V3OUT to drive out at +3.3 V levels, or connect to VCC to drive out at +5 V CMOS level. This pin can also be supplied with an external +1.8 V to +2.8 V supply in order to drive out at lower levels. It should be noted that in this case this supply should originate from the same source as the supply to VCC. This means that in bus powered designs a regulator which is supplied by the +5 V on the USB bus should be used. |
| $\begin{aligned} & \hline 4,17, \\ & 20 \end{aligned}$ | GND | PWR | Device ground supply pins. |
| 16 | 3V3OUT | Output | +3.3 V output from integrated LDO regulator. This pin should be decoupled || Pin No. | Name | Type | Description |
| :-- | :-- | :-- | :-- |
|  |  |  | to ground using a 100 nF capacitor. The purpose of this output is to provide <br> the internal +3.3 V supply to the USB transceiver cell and the internal <br> $1.5 \mathrm{k} \Omega$ pull up resistor on USBDP. Up to 50 mA can be drawn from this pin <br> to power external logic if required. This pin can also be used to supply the <br> VCCIO pin. |
| 19 | VCC | PWR | +3.3 V to +5.25 V supply to the device core. (See Note 1). |
| 24 | AGND | PWR | Device analogue ground supply for internal clock multiplier. |

Table 3.6 Power and Ground Group

| Pin No. | Name | Type | Description |
| :--: | :--: | :--: | :--: |
| $\begin{aligned} & 5,12, \\ & 13,23, \\ & 25,29 \end{aligned}$ | NC | NC | No internal connection. Do not connect. |
| 18 | RESET\# | Input | Active low reset. Can be used by an external device to reset the FT232R. If not required can be left unconnected, or pulled up to VCC. |
| 26 | TEST | Input | Puts the device into IC test mode. Must be tied to GND for normal operation, otherwise the device will appear to fail. |
| 27 | OSCI | Input | Input 12 MHz Oscillator Cell. Optional - Can be left unconnected for normal operation. (See Note 2). |
| 28 | OSCO | Output | Output from 12MHZ Oscillator Cell. Optional - Can be left unconnected for normal operation if internal Oscillator is used. (See Note 2). |

Table 3.7 Miscellaneous Signal Group

| Pin No. | Name | Type | Description |
| :--: | :--: | :--: | :--: |
| 30 | TXD | Output | Transmit Asynchronous Data Output. |
| 31 | DTR\# | Output | Data Terminal Ready Control Output / Handshake Signal. |
| 32 | RTS\# | Output | Request to Send Control Output / Handshake Signal. |
| 2 | RXD | Input | Receiving Asynchronous Data Input. |
| 3 | RI\# | Input | Ring Indicator Control Input. When remote wake up is enabled in the internal EEPROM taking RI\# low (20ms active low pulse) can be used to resume the PC USB host controller from suspend. |
| 6 | DSR\# | Input | Data Set Ready Control Input / Handshake Signal. |
| 7 | DCD\# | Input | Data Carrier Detect Control Input. |
| 8 | CTS\# | Input | Clear To Send Control Input / Handshake Signal. |
| 9 | CBUS4 | I/O | Configurable CBUS output only Pin. Function of this pin is configured in the device internal EEPROM. Factory default configuration is SLEEP\#. See CBUS Signal Options, Table 3.9. |
| 10 | CBUS2 | I/O | Configurable CBUS I/O Pin. Function of this pin is configured in the device internal EEPROM. Factory default configuration is TXDEN. See CBUS Signal Options, Table 3.9. |
| 11 | CBUS3 | I/O | Configurable CBUS I/O Pin. Function of this pin is configured in the device internal EEPROM. Factory default configuration is PWREN\#. See CBUS Signal Options, Table 3.9. PWREN\# should be used with a $10 \mathrm{k} \Omega$ resistor pull up. |
| 21 | CBUS1 | I/O | Configurable CBUS I/O Pin. Function of this pin is configured in the device internal EEPROM. Factory default configuration is RXLED\#. See CBUS Signal Options, Table 3.9. |
| 22 | CBUS0 | I/O | Configurable CBUS I/O Pin. Function of this pin is configured in the device internal EEPROM. Factory default configuration is TXLED\#. See CBUS Signal Options, Table 3.9. |

# Notes: 

1. The minimum operating voltage VCC must be +4.0 V (could use VBUS $=+5 \mathrm{~V}$ ) when using the internal clock generator. Operation at +3.3 V is possible using an external crystal oscillator.
2. For details on how to use an external crystal, ceramic resonator, or oscillator with the FT232R, please refer to Section 7.6.3. When used in Input Mode, the input pins are pulled to VCCIO via internal $200 \mathrm{k} \Omega$ resistors. These pins can be programmed to gently pull low during USB suspend (PWREN\# = "1") by setting an option in the internal EEPROM.

# 3.5 CBUS Signal Options 

The following options can be configured on the CBUS I/O pins. CBUS signal options are common to both package versions of the FT232R. These options can be configured in the internal EEPROM using the software utility FT_PROG, which can be downloaded from the FTDI Utilities (www.ftdichip.com). The default configuration is described in Section 8.

| CBUS Signal <br> Option | Available On CBUS Pin | Description |
| :--: | :--: | :--: |
| TXDEN | CBUS0, CBUS1, CBUS2, <br> CBUS3, CBUS4 | Enable transmit data for RS485 |
| PWREN\# | CBUS0, CBUS1, CBUS2, <br> CBUS3, CBUS4 | Output is low after the device has been configured <br> by USB, then high during USB suspending mode. <br> This output can be used to control power to <br> external logic P-Channel logic level MOSFET switch. <br> Enable the interface pull-down option when using <br> the PWREN\# in this way.* |
| TXLED\# | CBUS0, CBUS1, CBUS2, <br> CBUS3, CBUS4 | Transmit data LED drive: Data from USB Host to <br> FT232R. Pulses low when transmitting data via USB. <br> See Section 7.5 for more details. |
| RXLED\# | CBUS0, CBUS1, CBUS2, <br> CBUS3, CBUS4 | Receive data LED drive: Data from FT232R to USB <br> Host. Pulses low when receiving data via USB. See <br> Section 7.5 for more details. |
| TX\&RXLED\# | CBUS0, CBUS1, CBUS2, <br> CBUS3, CBUS4 | LED drive - pulses low when transmitting or <br> receiving data via USB. See Section 7.5 for more <br> details. |
| SLEEP\# | CBUS0, CBUS1, CBUS2, <br> CBUS3, CBUS4 | Goes low during USB suspend mode. Typically used <br> to power down an external TTL to RS232 level <br> converter IC in USB to RS232 converter designs. |
| CLK48 | CBUS0, CBUS1, CBUS2, <br> CBUS3, CBUS4 | $48 \mathrm{MHz} \pm 0.7 \%$ Clock output. ** |
| CLK24 | CBUS0, CBUS1, CBUS2, <br> CBUS3, CBUS4 | 24 MHz Clock output. ** |
| CLK12 | CBUS0, CBUS1, CBUS2, <br> CBUS3, CBUS4 | 12 MHz Clock output. ** |
| CLK6 | CBUS0, CBUS1, CBUS2, <br> CBUS3, CBUS4 | $6 \mathrm{MHz} \pm 0.7 \%$ Clock output. ** |
| CBitBangI/O | CBUS0, CBUS1, CBUS2, <br> CBUS3 | CBUS bit bang mode option. Allows up to 4 of the <br> CBUS pins to be used as general purpose I/O. <br> Configured individually for CBUS0, CBUS1, CBUS2 <br> and CBUS3 in the internal EEPROM. A separate <br> application note, AN232R-01, available from FTDI <br> website (www.ftdichip.com) describes in more detail <br> how to use CBUS bit bang mode. |
| BitBangWRn | CBUS0, CBUS1 | Synchronous and asynchronous bit bang mode WR\# <br> strobe output. |
| BitBangRDn | CBUS0, CBUS1, CBUS2, <br> CBUS3 | Synchronous and asynchronous bit bang mode RD\# <br> strobe output. |

Table 3.9 CBUS Configuration Control

* PWREN\# must be used with a $10 \mathrm{k} \Omega$ resistor pull up.
**When in USB suspend mode the outputs clocks are also suspended.# 4 Function Description 

The FT232R is a USB to serial UART interface device which simplifies USB to serial designs and reduces external component count by fully integrating an external EEPROM, USB termination resistors and an integrated clock circuit which requires no external crystal, into the device. It has been designed to operate efficiently with a USB host controller by using as little as possible of the total USB bandwidth available.

### 4.1 Key Features

Functional Integration. Fully integrated EEPROM, USB termination resistors, clock generation, AVCC filtering, POR and LDO regulator.

Configurable CBUS I/O Pin Options. The fully integrated EEPROM allows configuration of the Control Bus (CBUS) functionality, signal inversion and drive strength selection. There are 5 configurable CBUS I/O pins. These configurable options are -

1. TXDEN - transmit enable for RS485 designs.
2. PWREN\# - Power control for high power, bus powered designs.
3. TXLED\# - for pulsing an LED upon transmission of data.
4. RXLED\# - for pulsing an LED upon receiving data.
5. TX\&RXLED\# - which will pulse an LED upon transmission OR reception of data.
6. SLEEP\# - indicates that the device going into USB suspend mode.
7. CLK48 / CLK24 / CLK12 / CLK6 - $48 \mathrm{MHz}, 24 \mathrm{MHz}, 12 \mathrm{MHz}$, and 6 MHz clock output signal options.
8. BitBangWRn / BitBangRDn - Synchronous and asynchronous bit bang mode WR\# / RD\# strobe outputs

The CBUS pins can also be individually configured as GPIO pins, similar to asynchronous bit bang mode. It is possible to use this mode while the UART interface is being used, thus providing up to 4 general purpose I/O pins which are available during normal operation. An application note, AN232R-01, available from FTDI website (www.ftdichip.com) describes this feature.

The CBUS lines can be configured with any one of these output options by setting bits in the internal EEPROM. The device is supplied with the most commonly used pin definitions pre-programmed - see Section 8 for details.

Asynchronous Bit Bang Mode with RD\# and WR\# Strobes. The FT232R supports FTDI's previous chip generation bit-bang mode. In bit-bang mode, the eight UART lines can be switched from the regular interface mode to an 8 -bit general purpose I/O port. Data packets can be sent to the device and they will be sequentially sent to the interface at a rate controlled by an internal timer (equivalent to the baud rate pre-scaler). With the FT232R device this mode has been enhanced by outputting the internal RD\# and WR\# strobes signals which can be used to allow external logic to be clocked by accesses to the bit-bang I/O bus. This option will be described more fully in a separate application note available from FTDI website (www.ftdichip.com).

Synchronous Bit Bang Mode. The FT232R supports synchronous bit bang mode. This mode differs from asynchronous bit bang mode in that the interface pins are only read when the device is written to. This makes it easier for the controlling program to measure the response to an output stimulus as the data returned is synchronous to the output data. An application note, AN232R-01, available from FTDI website (www.ftdichip.com) describes this feature.

FTDIChip-ID ${ }^{\text {TM }}$. The FT232R also includes the new FTDIChip-ID ${ }^{\text {TM }}$ security dongle feature. This FTDIChip-ID ${ }^{\text {TM }}$ feature allows a unique number to be burnt into each device during manufacture. This number cannot be reprogrammed. This number is only readable over USB and forms a basis of a security dongle which can be used to protect any customer application software being copied. This allows the possibility of using the FT232R in a dongle for software licensing. Further to this, a renewable license scheme can be implemented based on the FTDIChip-ID ${ }^{\text {TM }}$ number when encrypted with other information. This encrypted number can be stored in the user area of the FT232R internal EEPROM, and can be decrypted, then compared with the protected FTDIChip-ID ${ }^{\text {TM }}$ to verify that a license is valid. Web basedapplications can be used to maintain product licensing this way. An application note, AN232R-02, available from FTDI website (www.ftdichip.com) describes this feature.

The FT232R is capable of operating at a voltage supply between +3.3 V and +5 V with a nominal operational mode current of 15 mA and a nominal USB suspend mode current of $70 \mu \mathrm{~A}$. This allows greater margin for peripheral designs to meet the USB suspend mode current limit of 2.5 mA . An integrated level converter within the UART interface allows the FT232R to interface to UART logic running at $+1.8 \mathrm{~V}, 2.5 \mathrm{~V}$, +3.3 V or +5 V .

# 4.2 Functional Block Descriptions 

The following paragraphs detail each function within the FT232R. Please refer to the block diagram shown in Figure 2.1.

Internal EEPROM. The internal EEPROM in the FT232R is used to store USB Vendor ID (VID), Product ID (PID), device serial number, product description string and various other USB configuration descriptors. The internal EEPROM is also used to configure the CBUS pin functions. The FT232R is supplied with the internal EEPROM pre-programmed as described in Section 8. A user area of the internal EEPROM is available to system designers to allow storing additional data. The internal EEPROM descriptors can be programmed in circuit, over USB without any additional voltage requirement. It can be programmed using the FTDI utility software called FT_PROG, which can be downloaded from FTDI Utilities on the FTDI website (www.ftdichip.com).
+3.3V LDO Regulator. The +3.3 V LDO regulator generates the +3.3 V reference voltage for driving the USB transceiver cell output buffers. It requires an external decoupling capacitor to be attached to the 3V3OUT regulator output pin. It also provides +3.3 V power to the $1.5 \mathrm{k} \Omega$ internal pull up resistor on USBDP. The main function of the LDO is to power the USB Transceiver and the Reset Generator Cells rather than to power external logic. However, it can be used to supply external circuitry requiring a +3.3 V nominal supply with a maximum current of 50 mA .

USB Transceiver. The USB Transceiver Cell provides the USB 1.1 / USB 2.0 full-speed physical interface to the USB cable. The output drivers provide +3.3 V level slew rate control signalling, whilst a differential input receiver and two single ended input receivers provide USB data in, Single-Ended-0 (SE0) and USB reset detection conditions respectfully. This function also incorporates the internal USB series termination resistors on the USB data lines and a $1.5 \mathrm{k} \Omega$ pull up resistor on USBDP.

USB DPLL. The USB DPLL cell locks on to the incoming NRZI USB data and generates recovered clock and data signals for the Serial Interface Engine (SIE) block.

Internal 12MHz Oscillator - The Internal 12MHz Oscillator cell generates a 12 MHz reference clock. This provides an input to the $x 4$ Clock Multiplier function. The 12 MHz Oscillator is also used as the reference clock for the SIE, USB Protocol Engine and UART FIFO controller blocks.

Clock Multiplier / Divider. The Clock Multiplier / Divider takes the 12 MHz input from the Internal Oscillator function and generates the $48 \mathrm{MHz}, 24 \mathrm{MHz}, 12 \mathrm{MHz}$ and 6 MHz reference clock signals. The 48 Mz clock reference is used by the USB DPLL and the Baud Rate Generator blocks.

Serial Interface Engine (SIE). The Serial Interface Engine (SIE) block performs the parallel to serial and serial to parallel conversion of the USB data. In accordance with the USB 2.0 specification, it performs bit stuffing/un-stuffing and CRC5/CRC16 generation. It also checks the CRC on the USB data stream.

USB Protocol Engine. The USB Protocol Engine manages the data stream from the device USB control endpoint. It handles the low level USB protocol requests generated by the USB host controller and the commands for controlling the functional parameters of the UART in accordance with the USB 2.0 specification chapter 9 .

FIFO RX Buffer (128 bytes). Data sent from the USB host controller to the UART via the USB data OUT endpoint is stored in the FIFO RX (receive) buffer. Data is removed from the buffer to the UART transmit register under control of the UART FIFO controller. (Rx relative to the USB interface).FIFO TX Buffer (256 bytes). Data from the UART receive register is stored in the TX buffer. The USB host controller removes data from the FIFO TX Buffer by sending a USB request for data from the device data IN endpoint. (Tx relative to the USB interface).

UART FIFO Controller. The UART FIFO controller handles the transfer of data between the FIFO RX and TX buffers and the UART transmit and receive registers.

UART Controller with Programmable Signal Inversion and High Drive. Together with the UART FIFO Controller the UART Controller handles the transfer of data between the FIFO RX and FIFO TX buffers and the UART transmit and receive registers. It performs asynchronous 7 or 8 bit parallel to serial and serial to parallel conversion of the data on the RS232 (or RS422 or RS485) interface.

Control signals supported by UART mode include RTS, CTS, DSR, DTR, DCD and RI. The UART Controller also provides a transmitter enable control signal pin option (TXDEN) to assist with interfacing to RS485 transceivers. RTS/CTS, DSR/DTR and XON / XOFF handshaking options are also supported. Handshaking is handled in hardware to ensure fast response times. The UART interface also supports the RS232 BREAK setting and detection conditions.

Additionally, the UART signals can each be individually inverted and have a configurable high drive strength capability. Both these features are configurable in the EEPROM.

Baud Rate Generator - The Baud Rate Generator provides a 16x clock input to the UART Controller from the 48 MHz reference clock. It consists of a 14 bit pre-scaler and 3 register bits which provide fine tuning of the baud rate (used to divide by a number plus a fraction or "sub-integer"). This determines the baud rate of the UART, which is programmable from 183 baud to 3 Mbaud.

The FT232R supports all standard baud rates and non-standard baud rates from 183 Baud up to 3 Mbaud. Achievable non-standard baud rates are calculated as follows -

Baud Rate $=3000000 /(n+x)$
Where ' $n$ ' can be any integer between 2 and $16,384\left(=2^{14}\right)$ and ' $x$ ' can be a sub-integer of the value 0 , $0.125,0.25,0.375,0.5,0.625,0.75$, or 0.875 . When $n=1, x=0$, i.e. baud rate divisors with values between 1 and 2 are not possible.

This gives achievable baud rates in the range 183.1 baud to $3,000,000$ baud. When a non-standard baud rate is required simply pass the required baud rate value to the driver as normal, and the FTDI driver will calculate the required divisor, and set the baud rate. See FTDI application note AN232B-05 on the FTDI website (www.ftdichip.com) for more details.

RESET Generator - The integrated Reset Generator Cell provides a reliable power-on reset to the device internal circuitry at power up. The RESET\# input pin allows an external device to reset the FT232R. RESET\# can be tied to VCC or left unconnected if not being used.# 5 Devices Characteristics and Ratings

### 5.1 Absolute Maximum Ratings

The absolute maximum ratings for the FT232R devices are as follows. These are in accordance with the Absolute Maximum Rating System (IEC 60134). Exceeding these may cause permanent damage to the device.

|  Parameter | Value | Units  |
| --- | --- | --- |
|  Storage Temperature | -65 to 150 | ${ }^{\circ} \mathrm{C}$  |
|  Floor Life (Out of Bag) At Factory Ambient ( $30^{\circ} \mathrm{C} / 60 \%$ Relative Humidity) | 168
(IPC/JEDEC J-STD-033A
MSL Level 3 Compliant)* | Hours  |
|  Ambient Temperature (Power Applied) | -40 to 85 | ${ }^{\circ} \mathrm{C}$  |
|  MTTF FT232RL | 11162037 | hours  |
|  MTTF FT232RQ | 4464815 | hours  |
|  VCC Supply Voltage | -0.5 to +6.00 | V  |
|  DC Input Voltage - USBDP and USBDM | -0.5 to +3.8 | V  |
|  DC Input Voltage - High Impedance Bidirectional | -0.5 to + (VCC +0.5) | V  |
|  DC Input Voltage - All Other Inputs | -0.5 to + (VCC +0.5) | V  |
|  DC Output Current - Outputs | 24 | mA  |
|  DC Output Current - Low Impedance Bidirectional | 24 | mA  |
|  Power Dissipation (VCC = 5.25V) | 500 | mW  |

Table 5.1 Absolute Maximum Ratings

- If devices are stored out of the packaging beyond this time limit the devices should be baked before use. The devices should be ramped up to a temperature of $+125^{\circ} \mathrm{C}$ and baked for up to 17 hours.

### 5.2 DC Characteristics

DC Characteristics (Ambient Temperature $=-40^{\circ} \mathrm{C}$ to $+85^{\circ} \mathrm{C}$ )

|  Parameter | Description | Minimum | Typical | Maximum | Units | Conditions  |
| --- | --- | --- | --- | --- | --- | --- |
|  VCC1 | VCC Operating Supply
Voltage | 4.0 | --- | 5.25 | V | Using Internal
Oscillator  |
|  VCC1 | VCC Operating Supply
Voltage | 3.3 | --- | 5.25 | V | Using External
Crystal  |
|  VCC2 | VCCIO Operating Supply
Voltage | 1.8 | --- | 5.25 | V |   |
|  Icc1 | Operating Supply Current | --- | 15 | --- | mA | Normal Operation  |
|  Icc2 | Operating Supply Current | 50 | 70 | 100 | $\mu \mathrm{A}$ | USB Suspend  |
|  3V3 | 3.3 v regulator output | 3.0 | 3.3 | 3.6 | V |   |

Table 5.2 Operating Voltage and Current

|  Parameter | Description | Minimum | Typical | Maximum | Units | Conditions  |
| --- | --- | --- | --- | --- | --- | --- |
|  Voh | Output Voltage High | 3.2 | 4.1 | 4.9 | V | I source $=2 \mathrm{~mA}$  |
|  Vol | Output Voltage Low | 0.3 | 0.4 | 0.6 | V | I sink $=2 \mathrm{~mA}$  |
|  Vin | Input Switching
Threshold | 1.0 | 1.2 | 1.5 | V | **  |
|  VHys | Input Switching
Hysteresis | 20 | 25 | 30 | mV | **  |

Table 5.3 UART and CBUS I/O Pin Characteristics (VCCIO = +5.0V, Standard Drive Level)| Parameter | Description | Minimum | Typical | Maximum | Units | Conditions |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Voh | Output Voltage High | 2.2 | 2.7 | 3.2 | V | I source $=1 \mathrm{~mA}$ |
| Vol | Output Voltage Low | 0.3 | 0.4 | 0.5 | V | I sink $=2 \mathrm{~mA}$ |
| Vin | Input Switching Threshold | 1.0 | 1.2 | 1.5 | V | ** |
| VHys | Input Switching Hysteresis | 20 | 25 | 30 | mV | ** |

Table 5.4 UART and CBUS I/O Pin Characteristics (VCCIO $=+3.3 \mathrm{~V}$, Standard Drive Level)

| Parameter | Description | Minimum | Typical | Maximum | Units | Conditions |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Voh | Output Voltage High | 2.1 | 2.6 | 2.8 | V | I source $=1 \mathrm{~mA}$ |
| Vol | Output Voltage Low | 0.3 | 0.4 | 0.5 | V | I sink $=2 \mathrm{~mA}$ |
| Vin | Input Switching Threshold | 1.0 | 1.2 | 1.5 | V | ** |
| VHys | Input Switching Hysteresis | 20 | 25 | 30 | mV | ** |

Table 5.5 UART and CBUS I/O Pin Characteristics (VCCIO $=+2.8 \mathrm{~V}$, Standard Drive Level)

| Parameter | Description | Minimum | Typical | Maximum | Units | Conditions |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Voh | Output Voltage High | 1.32 | 1.62 | 1.8 | V | I source $=0.2 \mathrm{~mA}$ |
| Vol | Output Voltage Low | 0.06 | 0.1 | 0.18 | V | I sink $=0.5 \mathrm{~mA}$ |
| Vin | Input Switching Threshold | 1.0 | 1.2 | 1.5 | V | ** |
| VHys | Input Switching Hysteresis | 20 | 25 | 30 | mV | ** |

Table 5.6 UART and CBUS I/O Pin Characteristics (VCCIO $=+1.8 \mathrm{~V}$, Standard Drive Level)

| Parameter | Description | Minimum | Typical | Maximum | Units | Conditions |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Voh | Output Voltage High | 3.2 | 4.1 | 4.9 | V | I source $=6 \mathrm{~mA}$ |
| Vol | Output Voltage Low | 0.3 | 0.4 | 0.6 | V | I sink $=6 \mathrm{~mA}$ |
| Vin | Input Switching Threshold | 1.0 | 1.2 | 1.5 | V | ** |
| VHys | Input Switching Hysteresis | 20 | 25 | 30 | mV | ** |

Table 5.7 UART and CBUS I/O Pin Characteristics (VCCIO $=+5.0 \mathrm{~V}$, High Drive Level)

| Parameter | Description | Minimum | Typical | Maximum | Units | Conditions |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Voh | Output Voltage High | 2.2 | 2.8 | 3.2 | V | I source $=3 \mathrm{~mA}$ |
| Vol | Output Voltage Low | 0.3 | 0.4 | 0.6 | V | I sink $=8 \mathrm{~mA}$ |
| Vin | Input Switching Threshold | 1.0 | 1.2 | 1.5 | V | ** |
| VHys | Input Switching Hysteresis | 20 | 25 | 30 | mV | ** |

Table 5.8 UART and CBUS I/O Pin Characteristics (VCCIO $=+3.3 \mathrm{~V}$, High Drive Level)

| Parameter | Description | Minimum | Typical | Maximum | Units | Conditions |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Voh | Output Voltage High | 2.1 | 2.6 | 2.8 | V | I source $=3 \mathrm{~mA}$ |
| Vol | Output Voltage Low | 0.3 | 0.4 | 0.6 | V | I sink $=8 \mathrm{~mA}$ |
| Vin | Input Switching Threshold | 1.0 | 1.2 | 1.5 | V | ** |
| VHys | Input Switching Hysteresis | 20 | 25 | 30 | mV | ** |

Table 5.9 UART and CBUS I/O Pin Characteristics (VCCIO $=+2.8 \mathrm{~V}$, High Drive Level)| Parameter | Description | Minimum | Typical | Maximum | Units | Conditions |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Voh | Output Voltage High | 1.35 | 1.67 | 1.8 | V | I source $=0.4 \mathrm{~mA}$ |
| Vol | Output Voltage Low | 0.12 | 0.18 | 0.35 | V | I sink $=3 \mathrm{~mA}$ |
| Vin | Input Switching Threshold | 1.0 | 1.2 | 1.5 | V | ** |
| VHys | Input Switching Hysteresis | 20 | 25 | 30 | mV | ** |

Table 5.10 UART and CBUS I/O Pin Characteristics (VCCIO $=+1.8 \mathrm{~V}$, High Drive Level)
** Only input pins have an internal $200 \mathrm{~K} \Omega$ pull-up resistor to VCCIO

| Parameter | Description | Minimum | Typical | Maximum | Units | Conditions |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Vin | Input Switching Threshold | 1.3 | 1.6 | 1.9 | V |  |
| VHys | Input Switching Hysteresis | 50 | 55 | 60 | mV |  |

Table 5.11 RESET\# and TEST Pin Characteristics

| Parameter | Description | Minimum | Typical | Maximum | Units | Conditions |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| UVoh | I/O Pins Static Output (High) | 2.8 |  | 3.6 | V | $\begin{gathered} \text { RI }=1.5 \mathrm{k} \Omega \text { to } \\ 3 \mathrm{~V} 3 \mathrm{OUT}(\mathrm{D}+) \mathrm{RI}= \\ 15 \mathrm{k} \Omega \text { to GND }(\mathrm{D}-) \end{gathered}$ |
| UVol | I/O Pins Static Output (Low) | 0 |  | 0.3 | V | $\begin{gathered} \text { RI }=1.5 \mathrm{k} \Omega \text { to } \\ 3 \mathrm{~V} 3 \mathrm{OUT}(\mathrm{D}+) \mathrm{RI}= \\ 15 \mathrm{k} \Omega \text { to GND }(\mathrm{D}-) \end{gathered}$ |
| UVse | Single Ended Rx Threshold | 0.8 |  | 2.0 | V |  |
| UCom | Differential Common Mode | 0.8 |  | 2.5 | V |  |
| UVDif | Differential Input Sensitivity | 0.2 |  |  | V |  |
| UDrvZ | Driver Output Impedance | 26 | 29 | 44 | Ohms | See Note 1 |

Table 5.12 USB I/O Pin (USBDP, USBDM) Characteristics

# 5.3 EEPROM Reliability Characteristics 

The internal 1024 Bit EEPROM has the following reliability characteristics:

| Parameter | Value | Units |
| :--: | :--: | :--: |
| Data Retention | 10 | Years |
| Write | 10,000 | Cycles |
| Read | Unlimited | Cycles |

Table 5.13 EEPROM Characteristics

### 5.4 Internal Clock Characteristics

The internal Clock Oscillator has the following characteristics:

| Parameter | Value |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: |
|  | Minimum | Typical | Maximum |  |
| Frequency of Operation (see Note 1) | 11.98 | 12.00 | 12.02 | MHz |
| Clock Period | 83.19 | 83.33 | 83.47 | ns |
| Duty Cycle | 45 | 50 | 55 | $\%$ |

Table 5.14 Internal Clock CharacteristicsNote: Equivalent to $+/-1667$ ppm

| Parameter | Description | Minimum | Typical | Maximum | Units | Conditions |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Voh | Output Voltage High | 2.1 | 2.8 | 3.2 | V | I source $=3 \mathrm{~mA}$ |
| Vol | Output Voltage Low | 0.3 | 0.4 | 0.6 | V | I sink $=8 \mathrm{~mA}$ |
| Vin | Input Switching <br> Threshold | 1.0 | 1.2 | 1.5 | V |  |

Table 5.15 OSCI, OSCO Pin Characteristics - see Note 1
Note: When supplied, the FT232R is configured to use its internal clock oscillator. These characteristics only apply when an external oscillator or crystal is used.

# 5.5 Thermal Characteristics 

The FT232RL package has the following thermal characteristics:

| Parameter | Value | Units | Conditions |
| :-- | :--: | :--: | :-- |
| Theta JA $\left(\theta_{\text {JA }}\right)$ | 55.82 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |  |
| Theta JC $\left(\theta_{\text {JC }}\right)$ | 24.04 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |  |

Table 5.16 FT232RL Thermal Characteristics
The FT232RQ package has the following thermal characteristics:

| Parameter | Value | Units | Conditions |
| :-- | :--: | :--: | :-- |
| Theta JA $\left(\theta_{\text {JA }}\right)$ | 31.49 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ | Still air, center pad soldered to PCB, 9 vias to another plane |
| Theta JA $\left(\theta_{\text {JA }}\right)$ | 62.31 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ | Still air, center pad unsoldered |
| Theta JC $\left(\theta_{\text {JC }}\right)$ |  | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |  |

Table 5.17 FT232RQ Thermal Characteristics# 6 USB Power Configurations 

The following sections illustrate possible USB power configurations for the FT232R. The illustrations have omitted pin numbers for ease of understanding since the pins differ between the FT232RL and FT232RQ package options.

All USB power configurations illustrated apply to both package options for the FT232R device. Please refer to Section 3 for the package option pin-out and signal descriptions.

### 6.1 USB Bus Powered Configuration

![img-5.jpeg](img-5.jpeg)

Figure 6.1 Bus Powered Configuration
Figure 6.1 Illustrates the FT232R in a typical USB bus powered design configuration. A USB bus powered device gets its power from the USB bus. Basic rules for USB bus power devices are as follows -
i) On plug-in to USB, the device should draw no more current than 100 mA .
ii) In USB Suspend mode the device should draw no more than 2.5 mA .
iii) A bus powered high power USB device (one that draws more than 100 mA ) should use one of the CBUS pins configured as PWREN\# and use it to keep the current below 100 mA on plug-in and 2.5 mA on USB suspend.
iv) A device that consumes more than 100 mA cannot be plugged into a USB bus powered hub.
v) No device can draw more than 500 mA from the USB bus.

The power descriptors in the internal EEPROM of the FT232R should be programmed to match the current drawn by the device.

A ferrite bead is connected in series with the USB power supply to reduce EMI noise from the FT232R and associated circuitry being radiated down the USB cable to the USB host. The value of the Ferrite Bead depends on the total current drawn by the application. A suitable range of Ferrite Beads is available from Steward (www.steward.com), for example Steward Part \# MI0805K400R-10.

Note: If using PWREN\# (available using the CBUS) the pin should be pulled to VCCIO using a $10 \mathrm{k} \Omega$ resistor.# 6.2 Self Powered Configuration 

![img-6.jpeg](img-6.jpeg)

Figure 6.2 Self-Powered Configuration
Figure 6.2 illustrates the FT232R in a typical USB self-powered configuration. A USB self-powered device gets its power from its own power supply, VCC, and does not draw current from the USB bus. The basic rules for USB self-powered devices are as follows -
i) A self-powered device should not force current down the USB bus when the USB host or hub controller is powered down.
ii) A self-powered device can use as much current as it needs during normal operation and USB suspend as it has its own power supply.
iii) A self-powered device can be used with any USB host, a bus powered USB hub or a selfpowered USB hub.

The power descriptor in the internal EEPROM of the FT232R should be programmed to a value of zero (self-powered).
n order to comply with the first requirement above, the USB bus power (pin 1) is used to control the RESET\# pin of the FT232R device. When the USB host or hub is powered up an internal $1.5 \mathrm{k} \Omega$ resistor on USBDP is pulled up to +3.3 V (generated using the 4 K 7 and 10 k resistor network), thus identifying the device as a full speed device to the USB host or hub. When the USB host or hub is powered off, RESET\# will be low and the FT232R is held in reset. Since RESET\# is low, the internal $1.5 \mathrm{k} \Omega$ resistor is not pulled up to any power supply (hub or host is powered down), so no current flows down USBDP via the $1.5 \mathrm{k} \Omega$ pull-up resistor. Failure to do this may cause some USB host or hub controllers to power up erratically.

Figure 6.2 illustrates a self-powered design which has a +4 V to +5.25 V supply.

## Note:

1. When the FT232R is in reset, the UART interface I/O pins are tri-stated. Input pins have internal $200 \mathrm{k} \Omega$ pull-up resistors to VCCIO, so they will gently pull high unless driven by some external logic.
2. When using internal FT232R oscillator the VCC supply voltage range must be +4.0 V to 5.25 V .
3. When using external oscillator the VCC supply voltage range must be +3.3 V to 5.25 V

Any design which interfaces to +3.3 V or +1.8 V would be having a +3.3 V or +1.8 V supply to VCCIO.# 6.3 USB Bus Powered with Power Switching Configuration 

![img-7.jpeg](img-7.jpeg)

Figure 6.3 Bus Powered with Power Switching Configuration
A requirement of USB bus powered applications, is when in USB suspend mode, the application draws a total current of less than 2.5 mA . This requirement includes external logic. Some external logic has the ability to power itself down into a low current state by monitoring the PWREN\# signal. For external logic that cannot power itself down in this way, the FT232R provides a simple but effective method of turning off power during the USB suspend mode.

Figure 6.3 shows an example of using a discrete P-Channel MOSFET to control the power to external logic. A suitable device to do this is an International Rectifier (www.irf.com) IRLML6402, or equivalent. It is recommended that a "soft start" circuit consisting of a $1 \mathrm{k} \Omega$ series resistor and a $0.1 \mu \mathrm{~F}$ capacitor is used to limit the current surge when the MOSFET turns on. Without the soft start circuit it is possible that the transient power surge, caused when the MOSFET switches on, will reset the FT232R or the USB host/hub controller. The soft start circuit example shown in Figure 6.3 powers up with a slew rate of approximately $12.5 \mathrm{~V} / \mathrm{ms}$. Thus supply voltage to external logic transitions from GND to +5 V in approximately 400 microseconds.

As an alternative to the MOSFET, a dedicated power switch IC with inbuilt "soft-start" can be used. A suitable power switch IC for such an application is the Micrel (www.micrel.com) MIC2025-2BM or equivalent.

With power switching controlled designs the following should be noted:
i) The external logic to which the power is being switched should have its own reset circuitry to automatically reset the logic when power is re-applied when moving out of suspend mode.
ii) Set the Pull-down on Suspend option in the internal FT232R EEPROM.
iii) One of the CBUS Pins should be configured as PWREN\# in the internal FT232R EEPROM, and used to switch the power supply to the external circuitry. This should be pulled high through a $10 \mathrm{k} \Omega$ resistor.![img-8.jpeg](img-8.jpeg)

# 6.4 USB Bus Powered with Selectable External Logic Supply 

![img-9.jpeg](img-9.jpeg)

Figure 6.4 USB Bus Powered with +3.3 V or +5 V External Logic Power Supply
Figure 6.4 illustrates a USB bus power application with selectable external logic supply. The external logic can be selected between +3.3 V and +5 V using the jumper switch. This jumper is used to allow the FT232R to be interfaced with a +3.3 V or +5 V logic devices. The VCCIO pin is either supplied with +5 V from the USB bus (jumper pins1 and 2 connected), or from the +3.3 V output from the FT232R 3V3OUT pin (jumper pins 2 and 3 connected). The supply to VCCIO is also used to supply external logic.

With bus powered applications, the following should be noted:
i) To comply with the 2.5 mA current supply limit during USB suspend mode, PWREN\# or SLEEP\# signals should be used to power down external logic in this mode. If this is not possible, use the configuration shown in Section 6.3.
ii) The maximum current sourced from the USB bus during normal operation should not exceed 100 mA , otherwise a bus powered design with power switching (Section 6.3) should be used.

Another possible configuration could use a discrete low dropout (LDO) regulator which is supplied by the 5 V on the USB bus to supply between +1.8 V and +2.8 V to the VCCIO pin and to the external logic. In this case VCC would be supplied with the +5 V from the USB bus and the VCCIO would be supplied from the output of the LDO regulator. This results in the FT232R I/O pins driving out at between +1.8 V and +2.8 V logic levels.

For a USB bus powered application, it is important to consider the following when selecting the regulator:i) The regulator must be capable of sustaining its output voltage with an input voltage of +4.35 V . A Low Drop Out (LDO) regulator should be selected.
ii) The quiescent current of the regulator must be low enough to meet the total current requirement of $<=2.5 \mathrm{~mA}$ during USB suspend mode.

A suitable series of LDO regulators that meets these requirements is the MicroChip/Telecom (www.microchip.com) TC55 series of devices. These devices can supply up to 250 mA current and have a quiescent current of under $1 \mu \mathrm{~A}$.# 7 Application Examples 

The following sections illustrate possible applications of the FT232R. The illustrations have omitted pin numbers for ease of understanding since the pins differ between the FT232RL and FT232RQ package options.

### 7.1 USB to RS232 Converter

![img-10.jpeg](img-10.jpeg)

Figure 7.1 Application Example showing USB to RS232 Converter
An example of using the FT232R as a USB to RS232 converter is illustrated in Figure 7.1. In this application, a TTL to RS232 Level Converter IC is used on the serial UART interface of the FT232R to convert the TTL levels of the FT232R to RS232 levels. This level shift can be done using the popular "213" series of TTL to RS232 level converters. These "213" devices typically have 4 transmitters and 5 receivers in a 28-LD SSOP package and feature an in-built voltage converter to convert the +5 V (nominal) VCC to the $+/-9$ volts required by RS232. A useful feature of these devices is the SHDN\# pin which can be used to power down the device to a low quiescent current during USB suspend mode.

A suitable level shifting device is the Sipex SP213EHCA which is capable of RS232 communication at up to 500 k baud. If a lower baud rate is acceptable, then several pin compatible alternatives are available such as the Sipex SP213ECA, the Maxim MAX213CAI and the Analogue Devices ADM213E, which are all suitable for communication at up to 115.2 k baud. If a higher baud rate is required, the Maxim MAX3245CAI device is capable of RS232 communication rates up to 1 Mbaud. Note that the MAX3245 is not pin compatible with the 213 series devices and that the SHDN pin on the MAX device is active high and should be connect to PWREN\# pin instead of SLEEP\# pin.

In example shown, the CBUS0 and CBUS1 have been configured as TXLED\# and RXLED\# and are being used to drive two LEDs.# 7.2 USB to RS485 Converter 

![img-11.jpeg](img-11.jpeg)

Figure 7.2 Application Example Showing USB to RS485 Converter
An example of using the FT232R as a USB to RS485 converter is shown in Figure 7.2. In this application, a TTL to RS485 level converter IC is used on the serial UART interface of the FT232R to convert the TTL levels of the FT232R to RS485 levels.

This example uses the Sipex SP481 device. Equivalent devices are available from Maxim and Analogue Devices. The SP481 is a RS485 device in a compact 8 pin SOP package. It has separate enables on both the transmitter and receiver. With RS485, the transmitter is only enabled when a character is being transmitted from the UART. The TXDEN signal CBUS pin option on the FT232R is provided for exactly this purpose and so the transmitter enable is wired to CBUS2 which has been configured as TXDEN. Similarly, CBUS3 has been configured as PWREN\#. This signal is used to control the SP481's receiver enable. The receiver enable is active low, so it is wired to the PWREN\# pin to disable the receiver when in USB suspend mode. CBUS2 = TXDEN and CBUS3 = PWREN\# are the default device configurations of the FT232R pins.

RS485 is a multi-drop network; so many devices can communicate with each other over a two wire cable interface. The RS485 cable requires to be terminated at each end of the cable. A link (which provides the $120 \Omega$ termination) allows the cable to be terminated if the SP481 is physically positioned at either end of the cable.

In this example the data transmitted by the FT232R is also present on the receive path of the SP481.This is a common feature of RS485 and requires the application software to remove the transmitted data from the received data stream. With the FT232R it is possible to do this entirely in hardware by modifying the example shown in Figure 7.2 by logically OR'ing the FT232R TXDEN and the SP481 receiver output and connecting the output of the OR gate to the RXD of the FT232R.

Note that the TXDEN is activated 1 bit period before the start bit. TXDEN is deactivated at the same time as the stop bit. This is not configurable.# 7.3 USB to RS422 Converter 

![img-12.jpeg](img-12.jpeg)

Figure 7.3 USB to RS422 Converter Configuration
An example of using the FT232R as a USB to RS422 converter is shown in Figure 7.3. In this application, two TTL to RS422 Level Converter ICs are used on the serial UART interface of the FT232R to convert the TTL levels of the FT232R to RS422 levels. There are many suitable level converter devices available. This example uses Sipex SP491 devices which have enables on both the transmitter and receiver. Since the SP491 transmitter enable is active high, it is connected to a CBUS pin in SLEEP\# configuration. The SP491 receiver enable is active low and is therefore connected to a CBUS pin PWREN\# configuration. This ensures that when both the SP491 transmitters and receivers are enabled then the device is active, and when the device is in USB suspend mode, the SP491 transmitters and receivers are disabled. If a similar application is used, but the design is USB BUS powered, it may be necessary to use a P-Channel logic level MOSFET (controlled by PWREN\#) in the VCC line of the SP491 devices to ensure that the USB standby current of 2.5 mA is met.

The SP491 is specified to transmit and receive data at a rate of up to 5 Mbaud. In this example the maximum data rate is limited to 3 Mbaud by the FT232R.# 7.4 USB to MCU UART Interface 

![img-13.jpeg](img-13.jpeg)

Figure 7.4 USB to MCU UART Interface
An example of using the FT232R as a USB to Microcontroller (MCU) UART interface is shown in Figure 7.4. In this application the FT232R uses TXD and RXD for transmission and reception of data, and RTS\# / CTS\# signals for hardware handshaking. Also in this example CBUS0 has been configured as a 12 MHz output to clock the MCU.

Optionally, RI\# could be connected to another I/O pin on the MCU and used to wake up the USB host controller from suspend mode. If the MCU is handling power management functions, then a CBUS pin can be configured as PWREN\# and would also be connected to an I/O pin of the MCU.# 7.5 LED Interface 

Any of the CBUS I/O pins can be configured to drive an LED. The FT232R has 3 configuration options for driving LEDs from the CBUS. These are TXLED\#, RXLED\#, and TX\&RXLED\#. Refer to Section 3.5 for configuration options.
![img-14.jpeg](img-14.jpeg)

Figure 7.5 Dual LED Configuration
An example of using the FT232R to drive LEDs is shown in Figure 7.5. In this application one of the CBUS pins is used to indicate transmission of data (TXLED\#) and another is used to indicate receiving data (RXLED\#). When data is being transmitted or received the respective pins will drive from tristate to low in order to provide indication on the LEDs of data transfer. A digital one-shot is used so that even a small percentage of data transfer is visible to the end user.
![img-15.jpeg](img-15.jpeg)

Figure 7.6 Single LED Configuration
Another example of using the FT232R to drive LEDs is shown in Figure 7.6. In this example one of the CBUS pins is used to indicate when data is being transmitted or received by the device (TX\&RXLED). In this configuration the FT232R will drive only a single LED.# 7.6 Using the External Oscillator 

The FT232R defaults to operating using its own internal oscillator. This requires that the device is powered with $\mathrm{VCC}(\min )=+4.0 \mathrm{~V}$. This supply voltage can be taken from the USB VBUS. Applications which require using an external oscillator, $\mathrm{VCC}=+3.3 \mathrm{~V}$, must do so in the following order:

1. When device powered for the very first time, it must have $\mathrm{VCC}>+4.0 \mathrm{~V}$. This supply is available from the USB VBUS supply $=+5.0 \mathrm{~V}$.
2. The EEPROM must then be programmed to enable external oscillator. This EEPROM modification cannot be done using the FTDI programming utility, FT_PROG. The EEPROM can only be reconfigured from a custom application. Please refer to the following applications note on how to do this:

## AN_100_Using_The_FT232_245R_With_External_Osc

3. The FT232R can then be powered from $\mathrm{VCC}=+3.3 \mathrm{~V}$ and an external oscillator. This can be done using a link to switch the VCC supply.

The FT232R will fail to operate when the internal oscillator has been disabled, but no external oscillator has been connected.# 8 Internal EEPROM Configuration

Following a power-on reset or a USB reset the FT232R will scan its internal EEPROM and read the USB configuration descriptors stored there. The default factory programmed values of the internal EEPROM are shown in Table 8.1.

|  Parameter | Value | Notes  |
| --- | --- | --- |
|  USB Vendor ID (VID) | 0403 h | FTDI default VID (hex)  |
|  USB Product UD (PID) | 6001 h | FTDI default PID (hex)  |
|  Serial Number Enabled? | Yes |   |
|  Serial Number | See Note | A unique serial number is generated and programmed into the EEPROM during device final test.  |
|  Pull down I/O Pins in USB Suspend | Disabled | Enabling this option will make the device pull down on the UART interface lines when in USB suspend mode (PWREN# is high).  |
|  Manufacturer Name | FTDI |   |
|  Product Description | FT232R USB UART |   |
|  Max Bus Power Current | 90 mA |   |
|  Power Source | Bus Powered |   |
|  Device Type | FT232R |   |
|  USB Version | 0200 | Returns USB 2.0 device description to the host. Note: The device is a USB 2.0 Full Speed device ( $12 \mathrm{Mb} / \mathrm{s}$ ) as opposed to a USB 2.0 High Speed device ( $480 \mathrm{Mb} / \mathrm{s}$ ).  |
|  Remote Wake Up | Enabled | Taking RI# low will wake up the USB host controller from suspend in approximately 20 ms .  |
|  High Current I/Os | Disabled | Enables the high drive level on the UART and CBUS I/O pins.  |
|  Load VCP Driver | Enabled | Makes the device load the VCP driver interface for the device.  |
|  CBUS0 | TXLED# | Default configuration of CBUS0 - Transmit LED drive.  |
|  CBUS1 | RXLED# | Default configuration of CBUS1 - Receive LED drive.  |
|  CBUS2 | TXDEN | Default configuration of CBUS2 - Transmit data enable for RS485.  |
|  CBUS3 | PWREN# | Default configuration of CBUS3 - Power enable. Low after USB enumeration, high during USB suspend mode.  |
|  CBUS4 | SLEEP# | Default configuration of CBUS4 - Low during USB suspend mode.  |
|  Invert TXD | Disabled | Signal on this pin becomes TXD# if enable.  |
|  Invert RXD | Disabled | Signal on this pin becomes RXD# if enable.  |
|  Invert RTS# | Disabled | Signal on this pin becomes RTS if enable.  |
|  Invert CTS# | Disabled | Signal on this pin becomes CTS if enable.  |
|  Invert DTR# | Disabled | Signal on this pin becomes DTR if enable.  |
|  Invert DSR# | Disabled | Signal on this pin becomes DSR if enable.  |
|  Invert DCD# | Disabled | Signal on this pin becomes DCD if enable.  |
|  Invert RI# | Disabled | Signal on this pin becomes RI if enable.  |

Table 8.1 Default Internal EEPROM Configuration The internal EEPROM in the FT232R can be programmed over USB using the FTDI utility program FT_PROG. FT_PROG can be downloaded from FTDI Utilities on the FTDI website (www.ftdichip.com). Version 2.8a or later is required for the FT232R chip. Users who do not have their own USB Vendor ID but who would like to use a unique Product ID in their design can apply to FTDI for a free block of unique PIDs. Contact FTDI support for this service.# 9 Package Parameters 

The FT232R is available in two different packages. The FT232RL is the SSOP-28 option and the FT232RQ is the QFN-32 package option. The solder reflow profile for both packages is described in Section 9.3.

### 9.1 SSOP-28 Package Dimensions

![img-16.jpeg](img-16.jpeg)

| SYMBOLS | MIN. | NOM. | MAX. |
| :--: | :--: | :--: | :--: |
| A | - | - | 2.0 |
| A1 | 0.05 | - | - |
| A2 | 1.65 | 1.75 | 1.85 |
| b | 0.22 | - | 0.38 |
| c | 0.09 | - | 0.25 |
| 0 | 10.05 | 10.20 | 10.50 |
| 1 | 7.65 | 7.80 | 7.90 |
| C1 | 5.00 | 5.30 | 5.60 |
| 8 |  | 0.65 BSC |  |
|  | 0.55 | 0.75 | 0.95 |
| 9 | 0.09 | - | - |
| $8^{\prime}$ | $0^{\prime}$ | $4^{\prime}$ | $8^{\prime}$ |

Figure 9.1 SSOP-28 Package Dimensions
The FT232RL is supplied in a RoHS compliant 28 pin SSOP package. The package is lead (Pb) free and uses a 'green' compound. The package is fully compliant with European Union directive 2002/95/EC.

This package is nominally $5.30 \mathrm{~mm} \times 10.20 \mathrm{~mm}$ body ( $7.80 \mathrm{~mm} \times 10.20 \mathrm{~mm}$ including pins). The pins are on a 0.65 mm pitch. The above mechanical drawing shows the SSOP-28 package.

All dimensions are in millimetres.
The date code format is $\mathbf{Y Y X X}$-A where $X X=2$ digit week number, $Y Y=2$ digit year number, $A=$ single letter corresponding to the revision of the device (e.g. A or B or C).

The code $\mathbf{X X X X X X X X X X X X}$ is the manufacturing LOT code. This only applies to devices manufactured after April 2009.# 9.2 QFN-32 Package Dimensions 

![img-17.jpeg](img-17.jpeg)

Figure 9.2 QFN-32 Package Dimensions
The FT232RQ is supplied in a RoHS compliant leadless QFN-32 package. The package is lead ( Pb ) free, and uses a 'green' compound. The package is fully compliant with European Union directive 2002/95/EC.

This package is nominally $5.00 \mathrm{~mm} \times 5.00 \mathrm{~mm}$. The solder pads are on a 0.50 mm pitch. The above mechanical drawing shows the QFN-32 package. All dimensions are in millimetres.

The centre pad on the base of the FT232RQ is not internally connected, and can be left unconnected, or connected to ground (recommended).

The date code format is $\mathbf{Y Y X X - A}$ where $X X=2$ digit week number, $Y Y=2$ digit year number, $A=$ single letter corresponding to the revision of the device (e.g. A or B or C).

The code $\mathbf{X X X X X X X}$ is the manufacturing LOT code. This only applies to devices manufactured after April 2009.# 9.3 Solder Reflow Profile 

The FT232R is supplied in Pb free 28 LD SSOP and QFN-32 packages. The recommended solder reflow profile for both package options is shown in Figure 9.3.
![img-18.jpeg](img-18.jpeg)

Figure 9.3 FT232R Solder Reflow Profile
The recommended values for the solder reflow profile are detailed in Table 9.1. Values are shown for both a completely Pb free solder process (i.e. the FT232R is used with Pb free solder), and for a non-Pb free solder process (i.e. the FT232R is used with non-Pb free solder).

| Profile Feature | Pb Free Solder <br> Process | Non-Pb Free Solder Process |
| :--: | :--: | :--: |
| Average Ramp Up Rate ( $\mathrm{T}_{\mathrm{s}}$ to $\mathrm{T}_{\mathrm{p}}$ ) | $3^{\circ} \mathrm{C} /$ second Max. | $3^{\circ} \mathrm{C} /$ Second Max. |
| Preheat <br> - Temperature Min ( $\mathrm{T}_{\mathrm{s}}$ Min.) <br> - Temperature Max ( $\mathrm{T}_{\mathrm{s}}$ Max.) <br> - Time ( $\mathrm{t}_{\mathrm{s}}$ Min to $\mathrm{t}_{\mathrm{s}}$ Max) | $\begin{gathered} 150^{\circ} \mathrm{C} \\ 200^{\circ} \mathrm{C} \\ 60 \text { to } 120 \text { seconds } \end{gathered}$ | $\begin{gathered} 100^{\circ} \mathrm{C} \\ 150^{\circ} \mathrm{C} \\ 60 \text { to } 120 \text { seconds } \end{gathered}$ |
| Time Maintained Above Critical Temperature $\mathrm{T}_{\mathrm{L}}$ : <br> - Temperature ( $\mathrm{T}_{\mathrm{L}}$ ) <br> - Time ( $\mathrm{t}_{\mathrm{L}}$ ) | $\begin{gathered} 217^{\circ} \mathrm{C} \\ 60 \text { to } 150 \text { seconds } \end{gathered}$ | $\begin{gathered} 183^{\circ} \mathrm{C} \\ 60 \text { to } 150 \text { seconds } \end{gathered}$ |
| Peak Temperature ( $\mathrm{T}_{\mathrm{p}}$ ) | $260^{\circ} \mathrm{C}$ | $240^{\circ} \mathrm{C}$ |
| Time within $5^{\circ} \mathrm{C}$ of actual Peak Temperature ( $\mathrm{t}_{\mathrm{p}}$ ) | 20 to 40 seconds | 20 to 40 seconds |
| Ramp Down Rate | $6^{\circ} \mathrm{C} /$ second Max. | $6^{\circ} \mathrm{C} /$ second Max. |
| Time for $\mathrm{T}=25^{\circ} \mathrm{C}$ to Peak Temperature, $\mathrm{T}_{\mathrm{p}}$ | 8 minutes Max. | 6 minutes Max. |

Table 9.1 Reflow Profile Parameter Values# 10 Alternative Parts 

The following lists of parts are not all direct drop in replacements but offer similar features as an alternative to the FT232R. The FT-X series is the latest device family offering reduced power and pin count with additional features such as battery charge detection, while the Hi-Speed solution offers faster interfacing.

|  | FT232R | FT234XD | FT230X | FT231X | FT232H |
| :--: | :--: | :--: | :--: | :--: | :--: |
| Description | Single channel USB to UART with full modem control lines | Single channel USB to Basic UART | Single channel USB to Basic UART | Single channel USB to UART with full modem control lines | Single channel USB to UART with full modem control lines |
| USB Speed | USB 2.0 full speed | USB 2.0 full speed | USB 2.0 full speed | USB 2.0 full speed | USB 2.0 hispeed |
| UART Data <br> Rates | 3 MBaud | 3 MBaud | 3 MBaud | 3 MBaud | 12 MBaud |
| CBUS | 5 | 1 | 4 | 4 | 10 |
| MTP for storing descriptors | Internal | Internal | Internal | Internal | External |
| Package options | 32 pin QFN <br> 28 pin SSOP | 12 pin DFN $(3 \mathrm{~mm} \times 3 \mathrm{~mm})$ | 16 pin QFN <br> 16 pin SSOP | 20 pin QFN <br> 20 pin SSOP | 48 pin QFN <br> 48 pin LQFP |
| Datasheet | FT232R | FT234XD | FT230X | FT231X | FT232H |

Table 10.1 FT232R alternative solutions# 11 Contact Information 

## Head Office - Glasgow, UK

Future Technology Devices International Limited Unit 1, 2 Seaward Place
Centurion Business Park
Glasgow, G41 1HH
United Kingdom
Tel: +44 (0) 1414292777
Fax: +44 (0) 1414292758

E-mail (Sales)
sales1@ftdichip.com
E-mail (Support)
support1@ftdichip.com
E-mail (General Enquiries) admin1@ftdichip.com
Web Shop URL
http://www.ftdichip.com

## Branch Office - Taipei, Taiwan

Future Technology Devices International Limited (Taiwan)
2F, No 516, Sec. 1 NeiHu Road
Taipei 114
Taiwan, R.O.C.
Tel: +886 (0) 287971330
Fax: +886 (0) 287519737
E-mail (Sales)
tw.sales1@ftdichip.com
E-mail (Support)
tw.support1@ftdichip.com
E-mail (General Enquiries) tw.admin1@ftdichip.com

## Branch Office - Tigard, Oregon, USA

Future Technology Devices International Limited (USA) 7130 SW Fir Loop
Tigard, OR 97223-8160
USA
Tel: +1 (503) 5470988
Fax: +1 (503) 5470987

E-Mail (Sales)
us.sales@ftdichip.com
E-Mail (Support)
us.support@ftdichip.com
E-Mail (General Enquiries)
us.admin@ftdichip.com

## Branch Office - Shanghai, China

Future Technology Devices International Limited (China)
Room 1103, No. 666 West Huaihai Road, Shanghai, 200052
China
Tel: +86 2162351596
Fax: +86 2162351595
E-Mail (Sales)
En.sales@ftdichip.com
E-Mail (Support)
En.support@ftdichip.com
E-Mail (General Enquiries)
cn.admin1@ftdichip.com

## Web Site

http://www.ftdichip.com

## Distributor and Sales Representatives

Please visit the Sales Network page of the FTDI Web site for the contact details of our distributor(s) and sales representative(s) in your country.

[^0]
[^0]:    System and equipment manufacturers and designers are responsible to ensure that their systems, and any Future Technology Devices International Ltd (FTDI) devices incorporated in their systems, meet all applicable safety, regulatory and system-level performance requirements. All application-related information in this document (including application descriptions, suggested FTDI devices and other materials) is provided for reference only. While FTDI has taken care to assure it is accurate, this information is subject to customer confirmation, and FTDI disclaims all liability for system designs and for any applications assistance provided by FTDI. Use of FTDI devices in life support and/or safety applications is entirely at the user's risk, and the user agrees to defend, indemnify and hold harmless FTDI from any and all damages, claims, suits or expense resulting from such use. This document is subject to change without notice. No freedom to use patents or other intellectual property rights is implied by the publication of this document. Neither the whole nor any part of the information contained in, or the product described in this document, may be adapted or reproduced in any material or electronic form without the prior written consent of the copyright holder. Future Technology Devices International Ltd, Unit 1, 2 Seaward Place, Centurion Business Park, Glasgow G41 1HH, United Kingdom. Scotland Registered Company Number: SC136640# Appendix A - References 

## Document References

AN 232R-01 Bit Bang Mode Available for FT232R and FT245R
AN 107-Advanced Driver Options
AN232R-02 FTDIChip-ID for the FT232R and FT245R
AN 121- Accessing the EEPROM User Area of FTDI Devices
AN 120 Aliasing VCP Baud Rates
AN 100 - Using the FT232R/FT245R with an External Crystal or Oscillator
AN 126 - User Guide for FT232B/R Factory Test Utility
AN232B-05 Configuring FT232R, FT2232 and FT232B Baud Rates
http://www.ftdichip.com/Documents/InstallGuides.htm
FT PROG

## Acronyms and Abbreviations

| Terms | Description |
| :--: | :-- |
| EEPROM | Electrically Erasable Programmable Read-Only Memory |
| FPGA | Field Programmable Gate Array |
| LED | Light Emitting Diode |
| MCU | Micro Controller Unit |
| PLD | Programmable Logic Device |
| QFN | Quad Flat No-leads |
| RoHS | Restriction of Hazardous Substances Directive |
| SIE | Serial Interface Engine |
| UART | Universal Asynchronous Receiver/Transmitter |
| USB | Universal Serial Bus |
| VCP | Virtual Communication Port |# Appendix B - List of Figures and Tables 

## List of Figures

Figure 2.1 FT232R Block Diagram ..... 4
Figure 3.1 SSOP Package Pin Out and Schematic Symbol ..... 7
Figure 3.2 QFN-32 Package Pin Out and schematic symbol ..... 9
Figure 6.1 Bus Powered Configuration ..... 19
Figure 6.2 Self-Powered Configuration ..... 20
Figure 6.3 Bus Powered with Power Switching Configuration ..... 21
Figure 6.4 USB Bus Powered with +3.3 V or +5 V External Logic Power Supply ..... 22
Figure 7.1 Application Example showing USB to RS232 Converter ..... 24
Figure 7.2 Application Example Showing USB to RS485 Converter ..... 25
Figure 7.3 USB to RS422 Converter Configuration ..... 26
Figure 7.4 USB to MCU UART Interface ..... 27
Figure 7.5 Dual LED Configuration ..... 28
Figure 7.6 Single LED Configuration ..... 28
Figure 9.1 SSOP-28 Package Dimensions ..... 31
Figure 9.2 QFN-32 Package Dimensions ..... 32
Figure 9.3 FT232R Solder Reflow Profile ..... 33
List of Tables
Table 3.1 USB Interface Group ..... 7
Table 3.2 Power and Ground Group ..... 8
Table 3.3 Miscellaneous Signal Group ..... 8
Table 3.4 UART Interface and CUSB Group (see note 3) ..... 8
Table 3.5 USB Interface Group ..... 9
Table 3.6 Power and Ground Group ..... 10
Table 3.7 Miscellaneous Signal Group ..... 10
Table 3.8 UART Interface and CBUS Group (see note 3) ..... 10
Table 3.9 CBUS Configuration Control ..... 11
Table 5.1 Absolute Maximum Ratings ..... 15
Table 5.2 Operating Voltage and Current ..... 15
Table 5.3 UART and CBUS I/O Pin Characteristics (VCCIO $=+5.0 \mathrm{~V}$, Standard Drive Level) ..... 15
Table 5.4 UART and CBUS I/O Pin Characteristics (VCCIO $=+3.3 \mathrm{~V}$, Standard Drive Level) ..... 16
Table 5.5 UART and CBUS I/O Pin Characteristics (VCCIO $=+2.8 \mathrm{~V}$, Standard Drive Level) ..... 16
Table 5.6 UART and CBUS I/O Pin Characteristics (VCCIO $=+1.8 \mathrm{~V}$, Standard Drive Level) ..... 16
Table 5.7 UART and CBUS I/O Pin Characteristics (VCCIO $=+5.0 \mathrm{~V}$, High Drive Level) ..... 16
Table 5.8 UART and CBUS I/O Pin Characteristics (VCCIO $=+3.3 \mathrm{~V}$, High Drive Level) ..... 16
Table 5.9 UART and CBUS I/O Pin Characteristics (VCCIO $=+2.8 \mathrm{~V}$, High Drive Level) ..... 16
Table 5.10 UART and CBUS I/O Pin Characteristics (VCCIO $=+1.8 \mathrm{~V}$, High Drive Level) ..... 17# FT232R USB UART IC Datasheet Version 2.16 

Table 5.11 RESET\# and TEST Pin Characteristics ..... 17
Table 5.12 USB I/O Pin (USBDP, USBDM) Characteristics ..... 17
Table 5.13 EEPROM Characteristics ..... 17
Table 5.14 Internal Clock Characteristics ..... 17
Table 5.15 OSCI, OSCO Pin Characteristics - see Note 1 ..... 18
Table 5.16 FT232RL Thermal Characteristics ..... 18
Table 5.17 FT232RQ Thermal Characteristics ..... 18
Table 8.1 Default Internal EEPROM Configuration ..... 30
Table 9.1 Reflow Profile Parameter Values ..... 33
Table 10.1 FT232R alternative solutions ..... 34# Appendix C - Revision History 

Document Title:
Document Reference No.:
Clearance No.:
Product Page:
Document Feedback:

FT232R USB UART IC Datasheet
FT_000053
FTDI\# 38
http://www.ftdichip.com/FTProducts.htm
Send Feedback

| Revision | Changes | Date |
| :--: | :--: | :--: |
| Version 0.90 | Initial Release | August 2005 |
| Version 0.96 | Revised Pre-release datasheet | October 2005 |
| Version 1.00 | Full Datasheet Release | December 2005 |
| Version 1.02 | Minor revisions to datasheet | December 2005 |
| Version 1.03 | Manufacturer ID added to default EEPROM configuration; Buffer sizes added | January 2006 |
| Version 1.04 | QFN-32 Pad layout and solder paste diagrams added | January 2006 |
| Version 2.00 | Reformatted, updated package info, added notes for 3.3V operation; Part numbers, TID; added UART and CBUS characteristics for +1.8 V ; <br> Corrected RESET\#; Added MTTF data; <br> Corrected the input switching threshold and input hysteresis values for VCCIO $=5 \mathrm{~V}$ | June 2008 |
| Version 2.01 | Corrected pin-out number in table3.2 for GND pin18. <br> Improved graphics on some Figures. <br> Add packing details. Changed USB suspend current spec from 500uA to 2.5 mA <br> Corrected Figure 9.2 QFN dimensions. | August 2008 |
| Version 2.02 | Corrected Tape and Reel quantities. <br> Added comment "PWREN\# should be used with a $10 \mathrm{k} \Omega$ resistor pull up". <br> Replaced TXDEN\# with TXDEN since it is active high in various places. <br> Added lot number to the device markings. <br> Added 3V3 regulator output tolerance. <br> Clarified VCC operation and added section headed "Using an external Oscillator" <br> Updated company contact information. | April 2009 |
| Version 2.03 | Corrected the RX/TX buffer definitions to be relative to the USB interface | June 2009 |
| Version 2.04 | Additional dimensions added to QFN solder profile | June 2009 || Revision | Changes | Date |
| :--: | :--: | :--: |
| Version 2.05 | Modified package dimensions to $5.0 \times 5.0+/-0.075 \mathrm{~mm}$ and Solder paste diagram to $2.50 \times 2.50+/-0.0375 \mathrm{~mm}$ <br> Added Windows 7 32, 64 bit driver support <br> Added FT_PROG utility references <br> Added Appendix A-references. Figure 2.1 updated. <br> Updated USB-IF TID for Rev B | December 2009 |
| Version 2.06 | Updated section 6.2, Figure 6.2 and the note, Updated section 5.3, Table 5.13, EEPROM data retention time | May 2010 |
| Version 2.07 | Added USB Certification Logos | July 2010 |
| Version 2.08 | Updated USB-IF TID for Rev C | April 2011 |
| Version 2.09 | Corrected Rev C TID number | April 2011 |
| Version 2.10 | Table 3.9, added clock output frequency within $\pm 0.7 \%$ <br> Edited Table 3.9, TXLED\# and TXLED\# Description <br> Added feedback links | March 2012 |
| Version 2.11 | Added thermal characteristics (Section 5.5) <br> Added section 10 highlighting alternative solutions from FTDI | April 2015 |
| Version 2.12 | Updated the links under section A - References - Useful Application Notes <br> Updated list of OS with supported drivers | August 2015 |
| Version 2.13 | Update Typo error in section heading 7.2 USB to RS485 Converter | $2015-11-18$ |
| Version 2.14 | Changes made to Bit bang WRn CBUS signal availability in Table 3.9. | $2018-06-27$ |
| Version 2.15 | Updated Fig.3.2 QFN-32 Package Pin Out and schematic symbol <br> Updated Fig.9.1 SSOP-28 Package Dimensions <br> Updated Fig.9.2 QFN-32 Package Dimensions <br> Deleted QFN-32 Package Typical Pad Layout and QFN-32 Package Typical Solder Paste Diagram sections | 2019-04-04 |
| Version 2.16 | Added note about revision letter in the package marking pages (Package Parameters section 9) | $2020-05-21$ |