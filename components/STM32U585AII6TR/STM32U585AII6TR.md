# STM32U585xx 

Ultra-low-power Arm ${ }^{\circledR}$ Cortex ${ }^{\circledR}$-M33 32-bit MCU+TrustZone ${ }^{\circledR}+$ FPU, 240 DMIPS, up to 2 MB Flash memory, 786 KB SRAM, crypto

Datasheet - production data

## Features

## Includes ST state-of-the-art patented technology

## Ultra-low-power with FlexPowerControl

- 1.71 V to 3.6 V power supply
- $-40^{\circ} \mathrm{C}$ to $+85 / 125^{\circ} \mathrm{C}$ temperature range
- Low-power background autonomous mode (LPBAM): autonomous peripherals with DMA, functional down to Stop 2 mode
- $\mathrm{V}_{\text {BAT }}$ mode: supply for RTC, $32 \times 32$-bit backup registers and 2-Kbyte backup SRAM
- 160 nA Shutdown mode (24 wake-up pins)
- 210 nA Standby mode (24 wake-up pins)
- 530 nA Standby mode with RTC
- $1.9 \mu \mathrm{~A}$ Stop 3 mode with 16-Kbyte SRAM
- $4.3 \mu \mathrm{~A}$ Stop 3 mode with full SRAM
- $4.0 \mu \mathrm{~A}$ Stop 2 mode with 16-Kbyte SRAM
- $8.95 \mu \mathrm{~A}$ Stop 2 mode with full SRAM
- $19.5 \mu \mathrm{~A} / \mathrm{MHz}$ Run mode @ 3.3 V


## Core

- Arm ${ }^{\circledR} 32$-bit Cortex ${ }^{\circledR}$-M33 CPU with TrustZone ${ }^{\circledR}$, MPU, DSP, and FPU


## ART Accelerator

- 8-Kbyte instruction cache allowing 0 -wait-state execution from flash and external memories: up to $160 \mathrm{MHz}, 240 \mathrm{DMIPS}$
- 4-Kbyte data cache for external memories


## Power management

- Embedded regulator (LDO) and SMPS step-down converter supporting switch on-the-fly and voltage scaling


## Benchmarks

- 1.5 DMIPS/MHz (Drystone 2.1)
![img-0.jpeg](img-0.jpeg)
- 651 CoreMark ${ }^{\circledR}(4.07$ CoreMark ${ }^{\circledR} / \mathrm{MHz})$
- 450 ULPMark ${ }^{\text {TM }}$-CP
- 109 ULPMark ${ }^{\text {TM }}$-PP
- 51.5 ULPMark ${ }^{\text {TM }}$-CM
- 133000 SecureMark ${ }^{\text {TM }}$-TLS


## Memories

- 2-Mbyte flash memory with ECC, 2 banks read-while-write, including 512 Kbytes with 100 kcycles
- 786-Kbyte SRAM with ECC OFF or 722-Kbyte SRAM including up to 322-Kbyte SRAM with ECC ON
- External memory interface supporting SRAM, PSRAM, NOR, NAND, and FRAM memories
- 2 Octo-SPI memory interfaces


## Security and cryptography

- SESIP3 and PSA Level 3 Certified Assurance Target
- Arm ${ }^{\circledR}$ TrustZone ${ }^{\circledR}$ and securable I/Os, memories, and peripherals
- Flexible life cycle scheme with RDP and password protected debug
- Root of trust thanks to unique boot entry and secure hide protection area (HDP)
![img-1.jpeg](img-1.jpeg)- Secure firmware installation (SFI) thanks to embedded root secure services (RSS)
- Secure data storage with hardware unique key (HUK)
- Secure firmware upgrade support with TF-M
- 2 AES coprocessors including one with DPA resistance
- Public key accelerator, DPA resistant
- On-the-fly decryption of Octo-SPI external memories
- HASH hardware accelerator
- True random number generator, NIST SP800-90B compliant
- 96-bit unique ID
- 512-byte OTP (one-time programmable)
- Active tampers


## Clock management

- 4 to 50 MHz crystal oscillator
- 32 kHz crystal oscillator for RTC (LSE)
- Internal 16 MHz factory-trimmed RC ( $\pm 1 \%$ )
- Internal low-power $32 \mathrm{kHz} \mathrm{RC}( \pm 5 \%)$
- 2 internal multispeed 100 kHz to 48 MHz oscillators, including one autotrimmed by LSE (better than $\pm 0.25 \%$ accuracy)
- Internal 48 MHz with clock recovery
- 3 PLLs for system clock, USB, audio, ADC


## General-purpose input/outputs

- Up to 136 fast I/Os with interrupt capability most 5V-tolerant and up to 14 I/Os with independent supply down to 1.08 V


## Up to 17 timers and 2 watchdogs

- 2 16-bit advanced motor-control, 4 32-bit, 5 16-bit, 4 low-power 16-bit (available in Stop mode), 2 SysTick timers and 2 watchdogs
- RTC with hardware calendar and calibration


## Up to 22 communication peripherals

- 1 USB Type- ${ }^{\circledR} /$ USB power delivery controller
- 1 USB OTG 2.0 full-speed controller
- 2 SAls (serial audio interface)
- 4 I2C FM+(1 Mbit/s), SMBus/PMBus ${ }^{\circledR}$
- 6 U(S)ART (SPI, ISO 7816, LIN, IrDA, modem)
- 3 SPI (+2 with OCTOSPI +3 with USART)
- 1 CAN FD controller
- 2 SDMMC interfaces
- 1 multifunction digital filter (6 filters) + 1 audio digital filter with sound-activity detection
- Parallel synchronous slave interface


## 16- and 4-channel DMA controllers, functional in Stop mode

## Graphic features

- Chrom-ART Accelerator (DMA2D) for enhanced graphic content creation
- 1 digital camera interface


## Mathematical coprocessor

- CORDIC for trigonometric functions acceleration
- Filter mathematical accelerator (FMAC)


## Up to 22 capacitive sensing channels

- Support touch key, linear, and rotary touch sensors


## Rich analog peripherals (independent supply)

- 14-bit ADC 2.5-Msps with hardware oversampling
- 12-bit ADC 2.5-Msps, with hardware oversampling, autonomous in Stop 2 mode
- 2 12-bit DAC, low-power sample and hold
- 2 operational amplifiers with built-in PGA
- 2 ultra-low-power comparators


## CRC calculation unit

## Debug

- Development support: serial-wire debug (SWD), JTAG, Embedded Trace Macrocell ${ }^{\text {TM }}$ (ETM)
ECOPACK2 compliant packages
Table 1. Device summary

| Reference | Part numbers |
| :--: | :--: |
| STM32U585xx | STM32U585AI, STM32U585CI, STM32U585OI, STM32U585QI, STM32U585RI, STM32U585VI, STM32U585ZI |# Contents 

1 Introduction ..... 16
2 Description ..... 17
3 Functional overview ..... 22
3.1 Arm Cortex-M33 core with TrustZone and FPU ..... 22
3.2 ART Accelerator (ICACHE and DCACHE) ..... 22
3.2.1 Instruction cache (ICACHE) ..... 22
3.2.2 Data cache (DCACHE) ..... 23
3.3 Memory protection unit ..... 24
3.4 Embedded flash memory ..... 24
3.4.1 Flash memory protection ..... 25
3.4.2 Additional flash memory protections when TrustZone activated ..... 27
3.4.3 FLASH privilege protection ..... 28
3.5 Embedded SRAMs ..... 28
3.5.1 SRAMs TrustZone security ..... 28
3.5.2 SRAMs privilege protection ..... 28
3.6 TrustZone security architecture ..... 29
3.6.1 TrustZone peripheral classification ..... 30
3.6.2 Default TrustZone security state ..... 30
3.7 Boot modes ..... 30
3.8 Global TrustZone controller (GTZC) ..... 33
3.9 Power supply management ..... 33
3.9.1 Power supply schemes ..... 34
3.9.2 Power supply supervisor ..... 38
3.9.3 Low-power modes ..... 39
3.9.4 Reset mode ..... 47
3.9.5 VBAT operation ..... 47
3.9.6 PWR TrustZone security ..... 47
3.10 Peripheral interconnect matrix ..... 48
3.11 Reset and clock controller (RCC) ..... 48
3.11.1 RCC TrustZone security ..... 51
3.12 Clock recovery system (CRS) ..... 513.13 General-purpose inputs/outputs (GPIOs) ..... 51
3.13.1 GPIOs TrustZone security ..... 51
3.14 Low-power general-purpose inputs/outputs (LPGPIO) ..... 51
3.14.1 LPGPIO TrustZone security ..... 52
3.15 Multi-AHB bus matrix ..... 52
3.16 System configuration controller (SYSCFG) ..... 52
3.17 General purpose direct memory access controller (GPDMA) ..... 52
3.18 Low-power direct memory access controller (LPDMA) ..... 54
3.19 Chrom-ART Accelerator controller (DMA2D) ..... 56
3.20 Interrupts and events ..... 57
3.20.1 Nested vectored interrupt controller (NVIC) ..... 57
3.20.2 Extended interrupt/event controller (EXTI) ..... 57
3.21 Cyclic redundancy check calculation unit (CRC) ..... 58
3.22 CORDIC coprocessor (CORDIC) ..... 58
3.23 Filter math accelerator (FMAC) ..... 58
3.24 Flexible static memory controller (FSMC) ..... 59
3.24.1 LCD parallel interface ..... 59
3.24.2 FSMC TrustZone security ..... 60
3.25 Octo-SPI interface (OCTOSPI) ..... 60
3.25.1 OCTOSPI TrustZone security ..... 61
3.26 OCTOSPI I/O manager (OCTOSPIM) ..... 61
3.27 Delay block (DLYB) ..... 61
3.28 Analog-to-digital converter (ADC1 and ADC4) ..... 61
3.28.1 Analog-to-digital converter 1 (ADC1) ..... 62
3.28.2 Analog-to-digital converter 4 (ADC4) ..... 64
3.28.3 Temperature sensor ..... 65
3.28.4 Internal voltage reference (VREFINT) ..... 66
3.28.5 VBAT battery voltage monitoring ..... 66
3.29 Digital-to-analog converter (DAC) ..... 66
3.30 Voltage reference buffer (VREFBUF) ..... 67
3.31 Comparators (COMP) ..... 67
3.32 Operational amplifiers (OPAMP) ..... 68
3.33 Multifunction digital filter (MDF) and audio digital filter (ADF) ..... 68
3.33.1 Multifunction digital filter (MDF) ..... 68
3.33.2 Audio digital filter (ADF) ..... 703.34 Digital camera interface (DCMI) ..... 72
3.35 Parallel synchronous slave interface (PSSI) ..... 72
3.36 Touch sensing controller (TSC) ..... 72
3.37 True random number generator (RNG) ..... 73
3.38 Secure advanced encryption standard hardware accelerator (SAES)
and encryption standard hardware accelerator (AES) ..... 74
3.39 HASH hardware accelerator (HASH) ..... 76
3.40 On-the-fly decryption engine (OTFDEC) ..... 77
3.41 Public key accelerator (PKA) ..... 78
3.42 Timers and watchdogs ..... 78
3.42.1 Advanced-control timers (TIM1, TIM8) ..... 79
3.42.2 General-purpose timers (TIM2, TIM3, TIM4, TIM5, TIM15,
TIM16, TIM17) ..... 79
3.42.3 Basic timers (TIM6 and TIM7) ..... 80
3.42.4 Low-power timers (LPTIM1, LPTIM2, LPTIM3, LPTIM4) ..... 80
3.42.5 Infrared interface (IRTIM) ..... 81
3.42.6 Independent watchdog (IWDG) ..... 81
3.42.7 Window watchdog (WWDG) ..... 81
3.42.8 SysTick timer ..... 81
3.43 Real-time clock (RTC), tamper and backup registers ..... 81
3.43.1 Real-time clock (RTC) ..... 81
3.43.2 Tamper and backup registers (TAMP) ..... 82
3.44 Inter-integrated circuit interface ( ${ }^{2} \mathrm{C}$ ) ..... 84
3.45 Universal synchronous/asynchronous receiver transmitter (USART/UART)
and low-power universal asynchronous receiver transmitter (LPUART) ..... 85
3.45.1 Universal synchronous/asynchronous receiver transmitter (USART/UART) ..... 85
3.45.2 Low-power universal asynchronous receiver transmitter (LPUART) ..... 87
3.46 Serial peripheral interface (SPI) ..... 88
3.47 Serial audio interfaces (SAI) ..... 89
3.48 Secure digital input/output and MultiMediaCards interface (SDMMC) ..... 90
3.49 Controller area network (FDCAN) ..... 92
3.50 USB on-the-go full-speed (OTG_FS) ..... 92
3.51 USB Type-C /USB Power Delivery controller (UCPD) ..... 94
3.52 Development support ..... 94
3.52.1 Serial-wire/JTAG debug port (SWJ-DP) ..... 943.52.2 Embedded Trace Macrocell ..... 94
4 Pinout, pin description and alternate functions ..... 95
4.1 Pinout/ballout schematics ..... 95
4.2 Pin description ..... 107
4.3 Alternate functions ..... 135
5 Electrical characteristics ..... 154
5.1 Parameter conditions ..... 154
5.1.1 Minimum and maximum values ..... 154
5.1.2 Typical values ..... 154
5.1.3 Typical curves ..... 154
5.1.4 Loading capacitor ..... 154
5.1.5 Pin input voltage ..... 154
5.1.6 Power supply scheme ..... 154
5.1.7 Current consumption measurement ..... 157
5.2 Absolute maximum ratings ..... 157
5.3 Operating conditions ..... 160
5.3.1 General operating conditions ..... 160
5.3.2 Operating conditions at power-up/power-down ..... 162
5.3.3 Embedded reset and power control block characteristics ..... 163
5.3.4 SMPS characteristics ..... 164
5.3.5 Embedded voltage reference ..... 165
5.3.6 Supply current characteristics ..... 166
5.3.7 Wake-up time from low-power modes and voltage scaling transition times ..... 210
5.3.8 External clock timing characteristics ..... 214
5.3.9 Internal clock timing characteristics ..... 220
5.3.10 PLL characteristics ..... 226
5.3.11 Flash memory characteristics ..... 228
5.3.12 EMC characteristics ..... 229
5.3.13 Electrical sensitivity characteristics ..... 230
5.3.14 I/O current injection characteristics ..... 231
5.3.15 I/O port characteristics ..... 232
5.3.16 NRST pin characteristics ..... 242
5.3.17 Extended interrupt and event controller input (EXTI) characteristics ..... 243
5.3.18 Analog switches booster ..... 2435.3.19 14-bit analog-to-digital converter (ADC1) characteristics ..... 244
5.3.20 12-bit analog-to-digital converter (ADC4) characteristics ..... 250
5.3.21 Temperature sensor characteristics ..... 255
5.3.22 $\mathrm{V}_{\text {CORE }}$ monitoring characteristics ..... 255
5.3.23 $\mathrm{V}_{\text {BAT }}$ monitoring characteristics ..... 255
5.3.24 Digital-to-analog converter characteristics ..... 256
5.3.25 Voltage reference buffer characteristics ..... 260
5.3.26 Comparator characteristics ..... 263
5.3.27 Operational amplifiers characteristics ..... 264
5.3.28 Temperature and backup domain supply thresholds monitoring ..... 267
5.3.29 ADF/MDF characteristics ..... 268
5.3.30 DCMI characteristics ..... 271
5.3.31 PSSI characteristics ..... 272
5.3.32 Timer characteristics ..... 274
5.3.33 FSMC characteristics ..... 275
5.3.34 OCTOSPI characteristics ..... 290
5.3.35 SD/SDIO/e-MMC card host interfaces (SDMMC) characteristics ..... 296
5.3.36 Delay block characteristics ..... 298
5.3.37 I2C interface characteristics ..... 298
5.3.38 USART (SPI mode) characteristics ..... 299
5.3.39 SPI characteristics ..... 301
5.3.40 SAI characteristics ..... 305
5.3.41 OTG_FS characteristics ..... 307
5.3.42 UCPD characteristics ..... 308
5.3.43 JTAG/SWD interface characteristics ..... 308
6 Package information ..... 310
6.1 UFQFPN48 package information (A0B9) ..... 311
6.2 LQFP48 package information (5B) ..... 314
6.3 LQFP64 package information (5W) ..... 318
6.4 WLCSP90 package information (B01C) ..... 322
6.5 LQFP100 package information (1L) ..... 325
6.6 UFBGA132 package information (A0G8) ..... 329
6.7 LQFP144 package information (1A) ..... 332
6.8 UFBGA169 package information (A0YV) ..... 337
6.9 Package thermal characteristics ..... 3406.9.1 Reference documents ..... 341
7 Ordering information ..... 342
8 Important security notice ..... 343
9 Revision history ..... 344# List of tables 

Table 1. Device summary ..... 2
Table 2. STM32U585xx features and peripheral counts ..... 18
Table 3. Access status versus protection level and execution modes when TZEN $=0$ ..... 25
Table 4. Access status versus protection level and execution modes when TZEN $=1$ ..... 26
Table 5. Example of memory map security attribution versus SAU configuration regions ..... 29
Table 6. Boot modes when TrustZone is disabled (TZEN = 0) ..... 31
Table 7. Boot modes when TrustZone is enabled (TZEN = 1) ..... 32
Table 8. Boot space versus RDP protection ..... 32
Table 9. STM32U585xx mode overview ..... 39
Table 10. Functionalities depending on the working mode ..... 44
Table 11. GPDMA1 channels implementation and usage ..... 54
Table 12. GPDMA1 autonomous mode and wake-up in low-power modes ..... 54
Table 13. LPDMA1 channels implementation and usage ..... 55
Table 14. LPDMA1 autonomous mode and wake-up in low-power modes ..... 56
Table 15. ADC features ..... 61
Table 16. Temperature sensor calibration values ..... 65
Table 17. Internal voltage reference calibration values ..... 66
Table 18. MDF features ..... 68
Table 19. AES/SAES features ..... 76
Table 20. Timer feature comparison ..... 78
Table 21. I2C implementation ..... 84
Table 22. USART, UART, and LPUART features ..... 85
Table 23. SPI features ..... 89
Table 24. SAI implementation ..... 90
Table 25. SDMMC features ..... 91
Table 26. Legend/abbreviations used in the pinout table ..... 107
Table 27. STM32U585xx pin definitions ..... 108
Table 28. Alternate function AF0 to AF7 ..... 136
Table 29. Alternate function AF8 to AF15 ..... 145
Table 30. Voltage characteristics ..... 158
Table 31. Current characteristics ..... 158
Table 32. Thermal characteristics ..... 159
Table 33. General operating conditions ..... 160
Table 34. Operating conditions at power-up/power-down ..... 162
Table 35. Embedded reset and power control block characteristics. ..... 163
Table 36. SMPS characteristics ..... 164
Table 37. Embedded internal voltage reference ..... 165
Table 38. Current consumption in Run mode on LDO, code with data processing running from Flash memory, ICACHE ON (1-way), prefetch ON ..... 167
Table 39. Current consumption in Run mode on SMPS, code with data processing running from Flash memory, ICACHE ON (1-way), prefetch ON ..... 168
Table 40. Current consumption in Run mode on SMPS, code with data processing running from Flash memory, ICACHE ON (1-way), prefetch ON, $\mathrm{V}_{\mathrm{DD}}=3.0 \mathrm{~V}$ ..... 169
Table 41. Typical current consumption in Run mode on LDO, with different codes running from Flash memory in low-power mode, ICACHE ON (1-way), prefetch ON ..... 170
Table 42. Typical current consumption in Run mode on LDO, with different codes running from Flash memory, ICACHE ON (1-way), prefetch ON ..... 170
Table 43. Typical current consumption in Run mode on SMPS, with different codesrunning from Flash memory in low-power mode, ICACHE ON (1-way), prefetch ON ..... 172
Table 44. Typical current consumption in Run mode on SMPS, with different codes running from Flash memory, ICACHE ON (1-way), prefetch ON ..... 172
Table 45. Current consumption in Sleep mode on LDO, Flash memory in power down ..... 174
Table 46. Current consumption in Sleep mode on SMPS, Flash memory in power down ..... 175
Table 47. Current consumption in Sleep mode on SMPS, Flash memory in power down, $\mathrm{V}_{\mathrm{DD}}=3.0 \mathrm{~V}$ ..... 176
Table 48. SRAM1/SRAM3 current consumption in Run/Sleep mode with LDO and SMPS ..... 177
Table 49. Static power consumption of Flash banks, when supplied by LDO/SMPS ..... 178
Table 50. Current consumption in Stop 0 mode on LDO ..... 179
Table 51. Current consumption in Stop 0 mode on SMPS ..... 180
Table 52. Current consumption in Stop 1 mode on LDO ..... 180
Table 53. Current consumption during wake-up from Stop 1 mode on LDO ..... 182
Table 54. Current consumption in Stop 1 mode on SMPS ..... 182
Table 55. Current consumption during wake-up from Stop 1 mode on SMPS ..... 184
Table 56. Current consumption in Stop 2 mode on LDO ..... 184
Table 57. SRAM static power consumption in Stop 2 when supplied by LDO ..... 186
Table 58. Current consumption during wake-up from Stop 2 mode on LDO ..... 187
Table 59. Current consumption in Stop 2 mode on SMPS ..... 187
Table 60. SRAM static power consumption in Stop 2 when supplied by SMPS ..... 189
Table 61. Current consumption during wake-up from Stop 2 mode on SMPS ..... 190
Table 62. Current consumption in Stop 3 mode on LDO ..... 190
Table 63. SRAM static power consumption in Stop 3 when supplied by LDO ..... 192
Table 64. Current consumption during wake-up from Stop 3 mode on LDO ..... 193
Table 65. Current consumption in Stop 3 mode on SMPS ..... 193
Table 66. SRAM static power consumption in Stop 3 when supplied by SMPS ..... 195
Table 67. Current consumption during wake-up from Stop 3 mode on SMPS ..... 196
Table 68. Current consumption in Standby mode ..... 197
Table 69. Current consumption during wake-up from Standby mode. ..... 200
Table 70. Current consumption in Shutdown mode ..... 201
Table 71. Current consumption during wake-up from Shutdown mode ..... 201
Table 72. Current consumption in $\mathrm{V}_{\mathrm{BAT}}$ mode ..... 202
Table 73. Typical dynamic current consumption of peripherals ..... 205
Table 74. Low-power mode wake-up timings on LDO ..... 210
Table 75. Low-power mode wake-up timings on SMPS ..... 212
Table 76. Regulator mode transition times ..... 213
Table 77. Wake-up time using USART/LPUART ..... 214
Table 78. High-speed external user clock characteristics. ..... 214
Table 79. Low-speed external user clock characteristics ..... 216
Table 80. HSE oscillator characteristics ..... 217
Table 81. LSE oscillator characteristics ( $\mathrm{f}_{\mathrm{LSE}}=32.768 \mathrm{kHz}$ ) ..... 219
Table 82. HSI16 oscillator characteristics ..... 220
Table 83. MSI oscillator characteristics ..... 221
Table 84. HSI48 oscillator characteristics ..... 224
Table 85. SHSI oscillator characteristics ..... 226
Table 86. LSI oscillator characteristics ..... 226
Table 87. PLL characteristics ..... 226
Table 88. Flash memory characteristics ..... 228
Table 89. Flash memory endurance and data retention ..... 228
Table 90. EMS characteristics ..... 229
Table 91. EMI characteristics for $\mathrm{f}_{\mathrm{HSE}}=8 \mathrm{MHz}$ and $\mathrm{f}_{\mathrm{HCLK}}=160 \mathrm{MHz}$. ..... 230
Table 92. ESD absolute maximum ratings ..... 230Table 93. Electrical sensitivities ..... 231
Table 94. I/O current injection susceptibility ..... 231
Table 95. I/O static characteristics ..... 232
Table 96. Output voltage characteristics (all I/Os except FT_t I/Os in VBAT mode, and FT_o I/Os) ..... 236
Table 97. Output voltage characteristics for FT_t I/Os in $\mathrm{V}_{\mathrm{BAT}}$ mode, and for FT_o I/Os ..... 236
Table 98. Output AC characteristics, HSLV OFF (all I/Os except FT_c, FT_t in VBAT mode and FT_o I/Os) ..... 237
Table 99. Output AC characteristics, HSLV ON (all I/Os except FT_c) ..... 239
Table 100. Output AC characteristics for FT_c I/Os ..... 241
Table 101. Output AC characteristics for FT_t I/Os in $\mathrm{V}_{\mathrm{BAT}}$ mode, and for FT_o I/Os ..... 241
Table 102. NRST pin characteristics ..... 242
Table 103. EXTI input characteristics ..... 243
Table 104. Analog switches booster characteristics ..... 243
Table 105. 14-bit ADC1 characteristics ..... 244
Table 106. Maximum RAIN for 14-bit ADC1 ..... 246
Table 107. 14-bit ADC1 accuracy ..... 248
Table 108. 12-bit ADC4 characteristics ..... 250
Table 109. Maximum RAIN for 12-bit ADC4 ..... 252
Table 110. 12-bit ADC4 accuracy ..... 254
Table 111. Temperature sensor characteristics ..... 255
Table 112. $\mathrm{V}_{\text {CORE }}$ monitoring characteristics ..... 255
Table 113. $\mathrm{V}_{\mathrm{BAT}}$ monitoring characteristics ..... 255
Table 114. $\mathrm{V}_{\mathrm{BAT}}$ charging characteristics ..... 256
Table 115. DAC characteristics ..... 256
Table 116. DAC accuracy ..... 258
Table 117. VREFBUF characteristics ..... 260
Table 118. COMP characteristics ..... 263
Table 119. OPAMP characteristics ..... 264
Table 120. ADF characteristics ..... 268
Table 121. MDF characteristics ..... 269
Table 122. DCMI characteristics ..... 271
Table 123. PSSI transmit characteristics ..... 272
Table 124. PSSI receive characteristics ..... 273
Table 125. TIMx characteristics ..... 274
Table 126. IWDG min/max timeout period at 32 kHz (LSI) ..... 275
Table 127. WWDG min/max timeout value at 160 MHz (PCLK) ..... 275
Table 128. Asynchronous non-multiplexed SRAM/PSRAM/NOR read timings ..... 277
Table 129. Asynchronous non-multiplexed SRAM/PSRAM/NOR read-NWAIT timings ..... 277
Table 130. Asynchronous non-multiplexed SRAM/PSRAM/NOR write timings ..... 278
Table 131. Asynchronous non-multiplexed SRAM/PSRAM/NOR write-NWAIT timings ..... 279
Table 132. Asynchronous multiplexed PSRAM/NOR read timings ..... 280
Table 133. Asynchronous multiplexed PSRAM/NOR read-NWAIT timings ..... 280
Table 134. Asynchronous multiplexed PSRAM/NOR write timings ..... 281
Table 135. Asynchronous multiplexed PSRAM/NOR write-NWAIT timings ..... 282
Table 136. Synchronous multiplexed NOR/PSRAM read timings ..... 283
Table 137. Synchronous multiplexed PSRAM write timings ..... 284
Table 138. Synchronous non-multiplexed NOR/PSRAM read timings ..... 286
Table 139. Synchronous non-multiplexed PSRAM write timings ..... 287
Table 140. Switching characteristics for NAND Flash read cycles ..... 289
Table 141. Switching characteristics for NAND Flash write cycles ..... 290
Table 142. OCTOSPI characteristics in SDR mode ..... 290Table 143. OCTOSPI characteristics in DTR mode (no DQS) ..... 291
Table 144. OCTOSPI characteristics in DTR mode (with DQS)/HyperBus ..... 292
Table 145. SD/e $\cdot$ MMC characteristics ( $\mathrm{V}_{\mathrm{DD}}=2.7 \mathrm{~V}$ to 3.6 V ) ..... 296
Table 146. e $\cdot$ MMC characteristics ( $\mathrm{V}_{\mathrm{DD}}=1.71 \mathrm{~V}$ to 1.9 V ) ..... 297
Table 147. Delay block characteristics ..... 298
Table 148. I2C analog filter characteristics ..... 299
Table 149. USART (SPI mode) characteristics ..... 299
Table 150. SPI characteristics ..... 302
Table 151. SAI characteristics ..... 306
Table 152. OTG_FS characteristics ..... 307
Table 153. UCPD characteristics ..... 308
Table 154. JTAG characteristics ..... 308
Table 155. SWD characteristics ..... 309
Table 156. UFQFPN48 - Mechanical data ..... 312
Table 157. LQFP48 - Mechanical data ..... 315
Table 158. LQFP64 - Mechanical data ..... 319
Table 159. WLCSP90 - Mechanical data ..... 322
Table 160. WLCSP90 - Recommended PCB design rules ..... 323
Table 161. LQFP100 - Mechanical data ..... 326
Table 162. UFBGA132 - Mechanical data ..... 329
Table 163. UFBGA132 - Example of PCB design rules ( 0.5 mm pitch BGA) ..... 330
Table 164. LQFP144 - Mechanical data ..... 333
Table 165. UFBGA169 - Mechanical data ..... 337
Table 166. UFBGA169 - Example of PCB design rules ( 0.5 mm pitch BGA) ..... 338
Table 167. Package thermal characteristics ..... 341
Table 168. Document revision history ..... 344# List of figures 

Figure 1. STM32U585xx block diagram ..... 21
Figure 2. STM32U585xQ power supply overview (with SMPS) ..... 36
Figure 3. STM32U585xx power supply overview (without SMPS) ..... 37
Figure 4. Power-up /down sequence ..... 38
Figure 5. Clock tree ..... 50
Figure 6. VREFBUF block diagram ..... 67
Figure 7. LQFP48_SMPS pinout ..... 95
Figure 8. LQFP48 pinout ..... 95
Figure 9. UFQFPN48_SMPS pinout ..... 96
Figure 10. UFQFPN48 pinout ..... 96
Figure 11. LQFP64_SMPS pinout ..... 97
Figure 12. LQFP64 pinout ..... 97
Figure 13. WLCSP90_SMPS ballout ..... 98
Figure 14. LQFP100_SMPS pinout ..... 99
Figure 15. LQFP100 pinout ..... 100
Figure 16. UFBGA132_SMPS ballout ..... 101
Figure 17. UFBGA132 ballout ..... 102
Figure 18. LQFP144_SMPS pinout ..... 103
Figure 19. LQFP144 pinout ..... 104
Figure 20. UFBGA169_SMPS ballout ..... 105
Figure 21. UFBGA169 ballout ..... 106
Figure 22. Pin loading conditions ..... 154
Figure 23. Pin input voltage ..... 154
Figure 24. STM32U585xx power supply scheme (without SMPS) ..... 155
Figure 25. STM32U585xQ power supply scheme (with SMPS) ..... 156
Figure 26. Current consumption measurement ..... 157
Figure 27. VREFINT versus temperature ..... 166
Figure 28. AC timing diagram for high-speed external clock source (digital mode) ..... 215
Figure 29. AC timing diagram for high-speed external clock source (analog mode) ..... 216
Figure 30. AC timing diagram for low-speed external square clock source ..... 216
Figure 31. AC timing diagram for low-speed external sinusoidal clock source ..... 217
Figure 32. Typical application with a 8 MHz crystal ..... 218
Figure 33. Typical application with a 32.768 kHz crystal ..... 219
Figure 34. HSI16 frequency versus temperature and $\mathrm{V}_{\mathrm{DD}}$ ..... 220
Figure 35. HSI48 frequency versus temperature ..... 225
Figure 36. I/O input characteristics (all I/Os except BOOT0 and FT_c). ..... 235
Figure 37. Output AC characteristics definition ..... 242
Figure 38. Recommended NRST pin protection ..... 243
Figure 39. ADC accuracy characteristics ..... 249
Figure 40. Typical connection diagram when using the ADC with FT/TT pins featuring analog switch function ..... 249
Figure 41. 12-bit buffered/non-buffered DAC ..... 258
Figure 42. $\mathrm{V}_{\text {REFBUF_OUT }}$ versus temperature (VRS $=000$ ) ..... 261
Figure 43. $\mathrm{V}_{\text {REFBUF_OUT }}$ versus temperature (VRS $=001$ ) ..... 262
Figure 44. $\mathrm{V}_{\text {REFBUF_OUT }}$ versus temperature (VRS $=010$ ) ..... 262
Figure 45. $\mathrm{V}_{\text {REFBUF_OUT }}$ versus temperature (VRS $=011$ ) ..... 262
Figure 46. OPAMP voltage noise density, normal mode, $R_{\text {LOAD }}=3.9 \mathrm{k} \Omega$ ..... 267
Figure 47. OPAMP voltage noise density, low-power mode, $R_{\text {LOAD }}=20 \mathrm{k} \Omega$ ..... 267Figure 48. ADF timing diagram ..... 269
Figure 49. MDF timing diagram ..... 270
Figure 50. DCMI timing diagram ..... 271
Figure 51. PSSI transmit timing diagram ..... 273
Figure 52. PSSI receive timing diagram ..... 274
Figure 53. Asynchronous non-multiplexed SRAM/PSRAM/NOR read waveforms ..... 276
Figure 54. Asynchronous non-multiplexed SRAM/PSRAM/NOR write waveforms ..... 278
Figure 55. Asynchronous multiplexed PSRAM/NOR read waveforms. ..... 279
Figure 56. Asynchronous multiplexed PSRAM/NOR write waveforms ..... 281
Figure 57. Synchronous multiplexed NOR/PSRAM read timings ..... 283
Figure 58. Synchronous multiplexed PSRAM write timings ..... 284
Figure 59. Synchronous non-multiplexed NOR/PSRAM read timings ..... 285
Figure 60. Synchronous non-multiplexed PSRAM write timings ..... 286
Figure 61. NAND controller waveforms for read access ..... 288
Figure 62. NAND controller waveforms for write access ..... 288
Figure 63. NAND controller waveforms for common memory read access ..... 289
Figure 64. NAND controller waveforms for common memory write access ..... 289
Figure 65. OCTOSPI timing diagram - SDR mode ..... 294
Figure 66. OCTOSPI timing diagram - DDR mode ..... 294
Figure 67. OCTOSPI HyperBus clock ..... 294
Figure 68. OCTOSPI HyperBus read ..... 295
Figure 69. OCTOSPI HyperBus read with double latency ..... 295
Figure 70. OCTOSPI HyperBus write ..... 295
Figure 71. SD high-speed mode ..... 297
Figure 72. SD default mode ..... 297
Figure 73. SDMMC DDR mode ..... 298
Figure 74. USART timing diagram in SPI master mode ..... 300
Figure 75. USART timing diagram in SPI slave mode ..... 301
Figure 76. SPI timing diagram - slave mode and CPHA $=0$ ..... 304
Figure 77. SPI timing diagram - slave mode and CPHA $=1$ ..... 304
Figure 78. SPI timing diagram - master mode ..... 305
Figure 79. SAI master timing diagram ..... 307
Figure 80. SAI slave timing diagram ..... 307
Figure 81. JTAG timing diagram ..... 309
Figure 82. SWD timing diagram ..... 309
Figure 83. UFQFPN48 - Outline ..... 311
Figure 84. UFQFPN48 - Footprint example ..... 312
Figure 85. UFQFPN48 marking example (package top view) ..... 313
Figure 86. LQFP48 - Outline ${ }^{(15)}$ ..... 314
Figure 87. LQFP48 - Footprint example ..... 316
Figure 88. LQFP48 marking example (package top view) ..... 317
Figure 89. LQFP64 - Outline ${ }^{(15)}$ ..... 318
Figure 90. LQFP64 - Footprint example ..... 320
Figure 91. LQFP64 marking example (package top view) ..... 321
Figure 92. WLCSP90 - Outline ..... 322
Figure 93. WLCSP90 - Recommended footprint ..... 323
Figure 94. WLCSP90 marking example (package top view) ..... 324
Figure 95. LQFP100 - Outline ${ }^{(15)}$ ..... 325
Figure 96. LQFP100 - Footprint example ..... 327
Figure 97. LQFP100 marking example (package top view) ..... 328
Figure 98. UFBGA132 - Outline ..... 329
Figure 99. UFBGA132 - Footprint example ..... 330Figure 100. UFBGA132 marking example (package top view) ..... 331
Figure 101. LQFP144 - Outline ${ }^{(15)}$ ..... 332
Figure 102. LQFP144 - Footprint example ..... 335
Figure 103. LQFP144 marking example (package top view) ..... 336
Figure 104. UFBGA169 - Outline ..... 337
Figure 105. UFBGA169 - Footprint example ..... 338
Figure 106. UFBGA169 marking example (package top view) ..... 339# 1 Introduction 

This document provides the ordering information and mechanical device characteristics of the STM32U585xx microcontrollers.
For information on the Arm ${ }^{\circledR(\mathrm{a})}$ Cortex ${ }^{\circledR}$-M33 core, refer to the Cortex ${ }^{\circledR}$-M33 Technical reference manual, available from the www.arm.com website.

For information on the device errata with respect to the datasheet and reference manual, refer to the STM32U575xx and STM32U585xx errata sheet (ES0499).
![img-2.jpeg](img-2.jpeg)
arm
a. Arm is a registered trademark of Arm Limited (or its subsidiaries) in the US and/or elsewhere.# 2 Description 

The STM32U585xx devices belong to an ultra-low-power microcontrollers family (STM32U5 series) based on the high-performance Arm ${ }^{\circledR}$ Cortex ${ }^{\circledR}$-M33 32-bit RISC core. They operate at a frequency of up to 160 MHz .
The Cortex ${ }^{\circledR}$-M33 core features a single-precision FPU (floating-point unit), that supports all the Arm ${ }^{\circledR}$ single-precision data-processing instructions and all the data types.
The Cortex ${ }^{\circledR}$-M33 core also implements a full set of DSP (digital signal processing) instructions and a MPU (memory protection unit) that enhances the application security.
The devices embed high-speed memories ( 2 Mbytes of flash memory and 786 Kbytes of SRAM), an FSMC (flexible external memory controller) for static memories (for devices with packages of 90 pins and more), two Octo-SPI flash memory interfaces (at least one Quad-SPI available on all packages) and an extensive range of enhanced I/Os and peripherals connected to three APB buses, three AHB buses and a 32-bit multi-AHB bus matrix.

The devices offer security foundation compliant with the TBSA (trusted-based security architecture) requirements from $\mathrm{Arm}^{\circledR}$. It embeds the necessary security features to implement a secure boot, secure data storage and secure firmware update. Besides these capabilities, the devices incorporate a secure firmware installation feature that allows the customer to secure the provisioning of the code during its production. A flexible lifecycle is managed thanks to multiple levels of readout protection and debug unlock with password. Firmware hardware isolation is supported thanks to securable peripherals, memories and I/Os, and privilege configuration of peripherals and memories.

The devices feature several protection mechanisms for embedded flash memory and SRAM: readout protection, write protection, secure, and hide protection areas.

The devices embed several peripherals reinforcing security: a fast AES coprocessor, a secure AES coprocessor with DPA resistance and hardware unique key that can be shared by hardware with fast AES, a PKA (public key accelerator) with DPA resistance, an on-the-fly decryption engine for Octo-SPI external memories, a HASH hardware accelerator, and a true random number generator.

The devices offer active tamper detection and protection against transient and environmental perturbation attacks, thanks to several internal monitoring generating secret data erase in case of attack. This helps to fit the PCI requirements for point of sales applications.

The devices offer one fast 14-bit ADC ( 2.5 Msps ), one 12-bit ADC ( 2.5 Msps ), two comparators, two operational amplifiers, two DAC channels, an internal voltage reference buffer, a low-power RTC, four 32-bit general-purpose timers, two 16-bit PWM timers dedicated to motor control, three 16-bit general-purpose timers, two 16-bit basic timers and four 16-bit low-power timers.

The devices support an MDF (multifunction digital filter) with six filters dedicated to the connection of external sigma-delta modulators. Another low-power digital filter dedicated to audio signals is embedded (ADF), with one filter supporting sound-activity detection. The devices embed also a Chrom-ART Accelerator dedicated to graphic applications, and mathematical accelerators (a trigonometric functions accelerator plus a filter mathematical accelerator). In addition, up to 22 capacitive sensing channels are available.The devices also feature standard and advanced communication interfaces such as: four $I^{2} \mathrm{Cs}$, three SPIs, three USARTs, two UARTs, one low-power UART, two SAIs, one digital camera interface (DCMI), two SDMMCs, one FDCAN, one USB OTG full-speed, one USB Type-C /USB Power Delivery controller, and one generic synchronous 8-/16-bit PSSI (parallel data input/output slave interface).
The devices operate in the -40 to $+85^{\circ} \mathrm{C}\left(+105^{\circ} \mathrm{C}\right.$ junction) and -40 to $+125^{\circ} \mathrm{C}$ ( $+130^{\circ} \mathrm{C}$ junction) temperature ranges from a 1.71 to 3.6 V power supply.
A comprehensive set of power-saving modes allow the design of low-power applications. Many peripherals (including communication, analog, timers, and audio peripherals) can be functional and autonomous down to Stop mode with direct memory access, thanks to LPBAM support (low-power background autonomous mode).
Some independent power supplies are supported like an analog independent supply input for ADC, DACs, OPAMPs and comparators, a 3.3 V dedicated supply input for USB and up to $14 \mathrm{I} /$ Os that can be supplied independently down to 1.08 V . A VBAT input is available for connecting a backup battery in order to preserve the RTC functionality and to backup 32 32-bit registers and 2-Kbyte SRAM.
The devices offer eight packages from 48 to 169 pins.
Table 2. STM32U585xx features and peripheral counts

| Peripherals |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Flash memory (Mbytes) |  |  |  | 2 |  |  |
| SRAM | System (Kbytes) |  |  | $784(192+64+512+16)$ |  |  |
|  | Backup (bytes) | 2048 |  | backup SRAM + 128 backup registers |  |  |
| External memory controller for static memories (FSMC) |  | No | Yes ${ }^{(1)}$ | Yes ${ }^{(2)}$ |  |  |
| OCTOSPI |  | $2^{(3)}$ |  |  | 2 |  |
| Timers | Advanced control | 2 (16 bits) |  |  |  |  |
|  | General purpose | 4 (32 bits) and 3 (16 bits) |  |  |  |  |
|  | Basic | 2 (16 bits) |  |  |  |  |
|  | Low power | 4 (16 bits) |  |  |  |  |
|  | SysTick timer | 2 |  |  |  |  |
|  | Watchdog timers (independent, window) | 2 |  |  |  |  |Table 2. STM32U585xx features and peripheral counts (continued)
![img-3.jpeg](img-3.jpeg)Table 2. STM32U585xx features and peripheral counts (continued)

| Peripherals |  |  |  |  |  |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Capacitive sensing <br> Number of channels (without SMPS <br> / with SMPS) |  | $5 / 4$ | $10 / 9$ | 11 | $19 / 18$ | $22 / 22$ | $22 / 21$ |
| ADC | 12-bit ADC | 1 |  |  |  |  |  |
|  | 14-bit ADC | 1 |  |  |  |  |  |
|  | Nbr of channels (without SMPS / with SMPS) | $11 / 10$ | $17 / 15$ | 16 | $20 / 18$ | $24 / 24$ | $24 / 22$ |
| DAC | Number of 12-bit D-to-A converters | 2 |  |  |  |  |  |
| Internal voltage reference buffer |  | No |  | Yes |  |  |  |
| Analog comparator |  | 2 |  |  |  |  |  |
| Operational amplifiers |  | 2 |  |  |  |  |  |
| Maximum CPU frequency |  | 160 MHz |  |  |  |  |  |
| Operating voltage |  | 1.71 to 3.6 V |  |  |  |  |  |
| Operating temperature |  | Ambient operating temperature: -40 to $+85^{\circ} \mathrm{C} /-40$ to $+125^{\circ} \mathrm{C}$ Junction temperature: -40 to $+105^{\circ} \mathrm{C} /-40$ to $+130^{\circ} \mathrm{C}$ |  |  |  |  |  |
| Package |  | $\begin{aligned} & \text { LQFP48, } \\ & \text { UFQFPN } \\ & 48 \end{aligned}$ | LQFP64 | WLCSP <br> 90 | $\begin{aligned} & \text { LQFP } \\ & 100 \end{aligned}$ | $\begin{aligned} & \text { UFBGA } \\ & 132 \end{aligned}$ | LQFP144 | $\begin{aligned} & \text { UFBGA } \\ & 169 \end{aligned}$ |

1. For the WLCSP90 package, FSMC can only support 8-bit LCD interface.
2. For the LQFP100 package, only FSMC Bank1 is available. Bank1 can only support a multiplexed NOR/PSRAM memory using the NE1 chip select.
3. Two OCTOSPIs are available only in Muxed mode.
4. When both are used simultaneously, one supports only SDIO interface.
5. Available on packages without SMPS, not available on packages with SMPS.
6. Active tampers in output sharing mode (one output shared by all inputs).Figure 1. STM32U585xx block diagram
![img-4.jpeg](img-4.jpeg)# 3 Functional overview 

### 3.1 Arm Cortex-M33 core with TrustZone and FPU

The Cortex-M33 with TrustZone and FPU is a highly energy-efficient processor designed for microcontrollers and deeply embedded applications, especially those requiring efficient security.

The Cortex-M33 processor delivers a high computational performance with low-power consumption and an advanced response to interrupts. It features:

- Arm TrustZone technology, using the Armv8-M main extension supporting secure and nonsecure states
- MPUs (memory protection units), supporting up to 16 regions for secure and nonsecure applications
- Configurable SAU (secure attribute unit) supporting up to eight memory regions as secure or nonsecure
- Floating-point arithmetic functionality with support for single precision arithmetic

The processor supports a set of DSP instructions that allows an efficient signal processing and a complex algorithm execution.

The Cortex-M33 processor supports the following bus interfaces:

- System AHB bus:

The S-AHB (system AHB) bus interface is used for any instruction fetch and data access to the memory-mapped SRAM, peripheral, external RAM and external device, or Vendor_SYS regions of the Armv8-M memory map.

- Code AHB bus:

The C-AHB (code AHB) bus interface is used for any instruction fetch and data access to the code region of the Armv8-M memory map.

Figure 1 shows the general block diagram of the STM32U585xx devices.

### 3.2 ART Accelerator (ICACHE and DCACHE)

### 3.2.1 Instruction cache (ICACHE)

The ICACHE is introduced on C-AHB code bus of Cortex-M33 processor to improve performance when fetching instruction (or data) from both internal and external memories.

ICACHE offers the following features:

- Multibus interface:
- Slave port receiving the memory requests from the Cortex-M33 C-AHB code execution port
- Master1 port performing refill requests to internal memories (Flash memory and SRAMs)
- Master2 port performing refill requests to external memories (external flash memory and RAMs through Octo-SPI and FMC interfaces)
- Second slave port dedicated to ICACHE registers access- Close to zero wait-states instructions/data access performance:
- 0 wait-state on cache hit
- Hit-under-miss capability, allowing to serve new processor requests while a line refill (due to a previous cache miss) is still ongoing
- Critical-word-first refill policy, minimizing processor stalls on cache miss
- Hit ratio improved by two-ways set-associative architecture and pLRU-t replacement policy (pseudo-least-recently-used, based on binary tree), algorithm with best complexity/performance balance
- Dual master ports allowing to decouple internal and external memory traffics, on fast and slow buses, respectively; also minimizing impact on interrupt latency
- Optimal cache line refill thanks to AHB burst transactions (of the cache line size)
- Performance monitoring by means of a hit counter and a miss counter
- Extension of cacheable region beyond the code memory space, by means of address remapping logic that allows four cacheable external regions to be defined
- Power consumption reduced intrinsically (more accesses to cache memory rather to bigger main memories); even improved by configuring ICACHE as direct mapped (rather than the default two-ways set-associative mode)
- TrustZone security support
- Maintenance operation for software management of cache coherency
- Error management: detection of unexpected cacheable write access, with optional interrupt raising


# 3.2.2 Data cache (DCACHE) 

The DCACHE is introduced on S-AHB system bus of Cortex-M33 processor to improve the performance of data traffic to/from external memories.

DCACHE offers the following features:

- Multibus interface:
- Slave port receiving the memory requests from the Cortex-M33 S-AHB system port
- Master port performing refill requests to external memories (external flash memory and RAMs through Octo-SPI and FMC interfaces)
- Second slave port dedicated to DCACHE registers access
- Close to zero wait-states external data access performance:
- Zero wait-states on cache hit
- Hit-under-miss capability, allowing to serve new processor requests to cached data, while a line refill (due to a previous cache miss) is still ongoing
- Critical-word-first refill policy for read transactions, minimizing processor stalls on cache miss
- Hit ratio improved by two-ways set-associative architecture and pLRU-t replacement policy (pseudo-least-recently-used, based on binary tree), algorithm with best complexity/performance balance
- Optimal cache line refill thanks to AHB burst transactions (of the cache line size)
- Performance monitoring by means of two hit counters (for read and write) and two miss counters (for read and write)- Supported cache accesses:
- Both write-back and write-through policies supported (selectable with AHB bufferable attribute)
- Read and write-back always allocated
- Write-through always nonallocated (write-around)
- Byte, half-word, and word writes supported
- TrustZone security support
- Maintenance operations for software management of cache coherency:
- Full cache invalidation (noninterruptible)
- Address range clean and/or invalidate operations (background task, interruptible)
- Error management: detection of error for master port request initiated by DCACHE (line eviction or clean operation), with optional interrupt raising


# 3.3 Memory protection unit 

The MPU (memory protection unit) is used to manage the CPU accesses to the memory and to prevent one task to accidentally corrupt the memory or the resources used by any other active task. This memory area is organized into up to 16 protected areas.
The MPU regions and registers are banked across secure and nonsecure states.
The MPU is especially helpful for applications where some critical or certified code must be protected against the misbehavior of other tasks. It is usually managed by an RTOS (real-time operating system).

If a program accesses a memory location that is prohibited by the MPU, the RTOS can detect it and take action. In an RTOS environment, the kernel can dynamically update the MPU area setting based on the process to be executed.

The MPU is optional and can be bypassed for applications that do not need it.

### 3.4 Embedded flash memory

The devices feature 2 Mbytes of embedded flash memory that is available for storing programs and data. The flash memory supports 10000 cycles and up to 100000 cycles on 512 Kbytes.

A 128-bit instruction prefetch is implemented and can optionally be enabled.
The flash memory interface features:

- Dual-bank operating modes
- Read-while-write (RWW)

This allows a read operation to be performed from one bank while an erase or program operation is performed to the other bank. The dual-bank boot is also supported. Each bank contains 128 pages of 8 Kbytes . The flash memory also embeds 512-byte OTP (one-time programmable) for user data.

The whole nonvolatile memory embeds the ECC (error correction code) feature supporting:

- single-error detection and correction
- double-error detection
- ECC fail address report# 3.4.1 Flash memory protection 

The option bytes allow the configuration of flexible protections:

- write protection (WRP) to protect areas against erasing and programming. Two areas per bank can be selected with 8 -Kbyte granularity.
- RDP (readout protection) to protect the whole memory, has four levels of protection available (see Table 3 and Table 4):
- Level 0: no readout protection
- Level 0.5: available only when TrustZone is enabled

All read/write operations (if no write protection is set) from/to the nonsecure flash memory are possible. The debug access to secure area is prohibited.
Debug access to nonsecure area remains possible.

- Level 1: memory readout protection

The flash memory cannot be read from or written to if either the debug features are connected or the boot in RAM or bootloader are selected. If TrustZone is enabled, the nonsecure debug is possible and the boot in SRAM is not possible. Regressions from Level 1 to lower levels can be protected by password authentication.

- Level 2: chip readout protection

The debug features, the boot in RAM and the bootloader selection are disabled. A secure secret key can be configured in the secure options to allow the regression capability from level 2 to level 1. By default (key not configured), this level 2 selection is irreversible and JTAG/SWD interfaces are disabled. If the secret key was previously configured in lower RDP levels, the device enables the RDP regression from level 2 to level 1 after password authentication through JTAG/SWD interface.

Note: In order to reach the best protection level, it is recommended to activate TrustZone and to set the RDP Level 2 with password authentication regression enabled.

Table 3. Access status versus protection level and execution modes when TZEN $=0$

| Area | RDP <br> level | User execution <br> (boot from Flash memory) |  |  | Debug/boot from RAM/ bootloader ${ }^{(1)}$ |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | Read | Write | Erase | Read | Write | Erase |
| Flash main memory | 1 | Yes | Yes | Yes | No | No | No ${ }^{(4)}$ |
|  | 2 | Yes | Yes | Yes | N/A | N/A | N/A |
| System memory ${ }^{(2)}$ | 1 | Yes | No | No | Yes | No | No |
|  | 2 | Yes | No | No | N/A | N/A | N/A |
| Option bytes ${ }^{(3)}$ | 1 | Yes | Yes ${ }^{(4)}$ | N/A | Yes | Yes ${ }^{(4)}$ | N/A |
|  | 2 | Yes | No ${ }^{(5)}$ | N/A | N/A | N/A | N/A |
| OTP | 1 | Yes | Yes ${ }^{(6)}$ | N/A | Yes | Yes ${ }^{(6)}$ | N/A |
|  | 2 | Yes | Yes ${ }^{(6)}$ | N/A | N/A | N/A | N/A |Table 3. Access status versus protection level and execution modes when TZEN $=0$ (continued)

| Area | RDP <br> level | User execution <br> (boot from Flash memory) |  |  | Debug/boot from RAM/ bootloader ${ }^{(1)}$ |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | Read | Write | Erase | Read | Write | Erase |
| Backup registers | 1 | Yes | Yes | N/A | No | No | $\mathrm{N} / \mathrm{A}^{(7)}$ |
|  | 2 | Yes | Yes | N/A | N/A | N/A | N/A |
| SRAM2/backup <br> RAM | 1 | Yes | Yes | N/A | No | No | $\mathrm{N} / \mathrm{A}^{(8)}$ |
|  | 2 | Yes | Yes | N/A | N/A | N/A | N/A |
| OTFDEC regions <br> (Octo-SPI) | 1 | Yes | Yes | Yes | $\mathrm{No}^{(9)}$ | Yes | Yes |
|  | 2 | Yes | Yes | Yes | N/A | N/A | N/A |

1. When the protection level 2 is active, the debug port, the boot from RAM and the boot from system memory are disabled.
2. The system memory is only read-accessible, whatever the protection level ( 0,1 or 2 ) and execution mode.
3. Option bytes are only accessible through the flash memory registers and OPSTRT bit.
4. The flash main memory is erased when the RDP option byte changes from level 1 to level 0 .
5. SWAP_BANK option bit can be modified.
6. OTP can only be written once.
7. The backup registers are erased when RDP changes from level 1 to level 0 .
8. All SRAMs are erased when RDP changes from level 1 to level 0 .
9. The OTFDEC keys are erased when the RDP option byte changes from level 1 to level 0 .

Table 4. Access status versus protection level and execution modes when TZEN $=1$

| Area | RDP <br> level | User execution <br> (boot from flash memory) |  |  | Debug/ bootloader ${ }^{(1)}$ |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | Read | Write | Erase | Read | Write | Erase |
| Flash main memory | 0.5 | Yes | Yes | Yes | $\operatorname{Yes}^{(2)}$ | $\operatorname{Yes}^{(2)}$ | $\operatorname{Yes}^{(2)}$ |
|  | 1 | Yes | Yes | Yes | No | No | $\mathrm{No}^{(5)}$ |
|  | 2 | Yes | Yes | Yes | N/A | N/A | N/A |
| System memory ${ }^{(3)}$ | 0.5 | Yes | No | No | Yes | No | No |
|  | 1 | Yes | No | No | Yes | No | No |
|  | 2 | Yes | No | No | N/A | N/A | N/A |
| Option bytes ${ }^{(4)}$ | 0.5 | Yes | $\operatorname{Yes}^{(5)}$ | N/A | Yes | $\operatorname{Yes}^{(5)}$ | N/A |
|  | 1 | Yes | $\operatorname{Yes}^{(5)}$ | N/A | Yes | $\operatorname{Yes}^{(5)}$ | N/A |
|  | 2 | Yes | $\mathrm{No}^{(6)}$ | N/A | N/A | N/A | N/A |Table 4. Access status versus protection level and execution modes when TZEN $=1$ (continued)

| Area | RDP <br> level | User execution (boot from flash memory) |  |  | Debug/ bootloader ${ }^{(1)}$ |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | Read | Write | Erase | Read | Write | Erase |
| OTP | 0.5 | Yes | Yes ${ }^{(7)}$ | N/A | Yes | Yes ${ }^{(7)}$ | N/A |
|  | 1 | Yes | Yes ${ }^{(7)}$ | N/A | Yes | Yes ${ }^{(7)}$ | N/A |
|  | 2 | Yes | Yes ${ }^{(7)}$ | N/A | N/A | N/A | N/A |
| Backup registers | 0.5 | Yes | Yes | N/A | Yes ${ }^{(2)}$ | Yes ${ }^{(2)}$ | N/A ${ }^{(8)}$ |
|  | 1 | Yes | Yes | N/A | No | No | N/A ${ }^{(8)}$ |
|  | 2 | Yes | Yes | N/A | N/A | N/A | N/A |
| SRAM2/backup <br> RAM | 0.5 | Yes | Yes | N/A | Yes ${ }^{(2)}$ | Yes ${ }^{(2)}$ | N/A ${ }^{(9)}$ |
|  | 1 | Yes | Yes | N/A | No | No | N/A ${ }^{(9)}$ |
|  | 2 | Yes | Yes | N/A | N/A | N/A | N/A |
| OTFDEC regions (Octo-SPI) | 0.5 | Yes | Yes | Yes | No ${ }^{(10)}$ | Yes | Yes |
|  | 1 | Yes | Yes | Yes | No ${ }^{(10)}$ | Yes | Yes |
|  | 2 | Yes | Yes | Yes | N/A | N/A | N/A |

1. When the protection level 2 is active, the debug port and the bootloader mode are disabled.
2. Depends on TrustZone security access rights.
3. The system memory is only read-accessible, whatever the protection level ( 0,1 or 2 ) and execution mode.
4. Option bytes are only accessible through the flash memory registers and OPSTRT bit.
5. The flash main memory is erased when the RDP option byte regresses from level 1 to level 0 .
6. SWAP_BANK option bit can be modified.
7. OTP can only be written once.
8. The backup registers are erased when RDP changes from level 1 to level 0 .
9. All SRAMs are erased when RDP changes from level 1 to level 0 .
10. The OTFDEC keys are erased when the RDP option byte changes from level 1 to level 0 .

# 3.4.2 Additional flash memory protections when TrustZone activated 

When the TrustZone security is enabled through option bytes, the whole flash memory is secure after reset, and the following protections are available:

- nonvolatile watermark-based secure flash memory area

The secure area can be accessed only in secure mode. One area per bank can be selected with a page granularity.

- secure HDP (hide protection area)

It is part of the flash memory secure area and can be protected to deny an access to this area by any data read, write and instruction fetch. For example, a software code in the secure flash memory hide protection area can be executed only once and deny anyfurther access to this area until next system reset. One area per bank can be selected at the beginning of the secure area.

- volatile block-based secure flash memory area

Each page can be programmed on-the-fly as secure or nonsecure.

# 3.4.3 FLASH privilege protection 

Each flash memory page can be programmed on-the-fly as privileged or unprivileged.

### 3.5 Embedded SRAMs

Five SRAMs are embedded in the STM32U585xx devices, each with specific features. SRAM1, SRAM2, and SRAM3 are the main SRAMs. SRAM4 is in the SRAM used for peripherals LPBAM (low-power background autonomous mode) in Stop 2 mode.

These SRAMs are made of several blocks that can be powered down in Stop mode to reduce consumption:

- SRAM1: three 64-Kbyte blocks (total 192 Kbytes)
- SRAM2: 8-Kbyte + 56-Kbyte blocks (total 64 Kbytes) with optional ECC. In addition, SRAM2 blocks can be retained in Standby mode.
- SRAM3: eight 64-Kbyte blocks (total 512 Kbytes) with optional ECC. When ECC is enabled, 256 Kbytes support ECC and 192 Kbytes of SRAM3 can be accessed without ECC.
- SRAM4: 16 Kbytes
- BKPSRAM (backup SRAM): 2 Kbytes with optional ECC. The BKPSRAM can be retained in all low-power modes and when $\mathrm{V}_{\mathrm{DD}}$ is off in $\mathrm{V}_{\mathrm{BAT}}$ mode, but not in Shutdown mode.


### 3.5.1 SRAMs TrustZone security

When the TrustZone security is enabled, all SRAMs are secure after reset.
The SRAM1, SRAM2, SRAM3, SRAM4 can be programmed as secure or nonsecure by blocks, using the MPCBB (block-based memory protection controller).

The granularity of SRAM secure block based is a page of 512 bytes. Backup SRAM regions can be programmed as secure or nonsecure with watermark, using the TZSC (TrustZone security controller) in the GTZC (global TrustZone controller).

### 3.5.2 SRAMs privilege protection

The SRAM1, SRAM2, SRAM3, SRAM4 can be programmed as privileged or unprivileged by blocks, using the MPCBB. The granularity of SRAM privilege block based is a page of 512 bytes. Backup SRAM regions can be programmed as privileged or unprivileged with watermark, using the TZSC (TrustZone security controller) in the GTZC (global TrustZone controller).# 3.6 TrustZone security architecture 

The security architecture is based on Arm TrustZone with the Armv8-M main extension.
The TrustZone security is activated by the TZEN option bit in the FLASH_OPTR register.
When the TrustZone is enabled, the SAU (security attribution unit) and IDAU (implementation defined attribution unit) define the access permissions based on secure and nonsecure state.

- SAU: up to eight SAU configurable regions are available for security attribution.
- IDAU: It provides a first memory partition as nonsecure or nonsecure callable attributes. It is then combined with the results from the SAU security attribution and the higher security state is selected.

Based on IDAU security attribution, the flash memory, system SRAM, and peripheral memory space is aliased twice for secure and nonsecure states. However, the external memory space is not aliased.

The table below shows an example of typical SAU region configuration based on IDAU regions. The user can split and choose the secure, nonsecure, or NSC regions for external memories as needed.

Table 5. Example of memory map security attribution versus SAU configuration regions

| Region description | Address range | IDAU security attribution | SAU security attribution typical configuration | Final security attribution |
| :--: | :--: | :--: | :--: | :--: |
| Code - external memories | $\begin{aligned} & 0 \times 00000000 \\ & 0 \times 07 F F F F F F \end{aligned}$ | Nonsecure | Secure or nonsecure or NSC ${ }^{(1)}$ | Secure or nonsecure or NSC |
| Code - Flash and SRAM | $\begin{aligned} & 0 \times 08000000 \\ & 0 \times 0 B F F F F F F \end{aligned}$ | Nonsecure | Nonsecure | Nonsecure |
|  | $\begin{aligned} & 0 \times 0 \mathrm{C} 000000 \\ & 0 \times 0 \mathrm{FFF} \text { FFFF } \end{aligned}$ | NSC | Secure or NSC | Secure or NSC |
| Code - external memories | $\begin{aligned} & 0 \times 10000000 \\ & 0 \times 17 F F F F F F \end{aligned}$ | Nonsecure | Nonsecure |  |
|  | $\begin{aligned} & 0 \times 18000000 \\ & 0 \times 1 F F F F F F F \end{aligned}$ |  |  |  |
| SRAM | $\begin{aligned} & 0 \times 20000000 \\ & 0 \times 2 F F F F F F F \end{aligned}$ | Nonsecure |  |  |
|  | $\begin{aligned} & 0 \times 30000000 \\ & 0 \times 3 F F F F F F F \end{aligned}$ | NSC | Secure or NSC | Secure or NSC |
| Peripherals | $\begin{aligned} & 0 \times 40000000 \\ & 0 \times 4 F F F F F F F \end{aligned}$ | Nonsecure | Nonsecure | Nonsecure |
|  | $\begin{aligned} & 0 \times 50000000 \\ & 0 \times 5 F F F F F F F \end{aligned}$ | NSC | Secure or NSC | Secure or NSC |
| External memories | $\begin{aligned} & 0 \times 60000000 \\ & 0 \times D F F F F F F F \end{aligned}$ | Nonsecure | Secure or nonsecure or NSC | Secure or nonsecure or NSC |

1. $\mathrm{NSC}=$ nonsecure callable.# 3.6.1 TrustZone peripheral classification 

When the TrustZone security is active, a peripheral can be either securable or TrustZone-aware type as follows:

- securable: peripheral protected by an AHB/APB firewall gate that is controlled from TZSC to define security properties
- TrustZone-aware: peripheral connected directly to AHB or APB bus and implementing a specific TrustZone behavior such as a subset of registers being secure


### 3.6.2 Default TrustZone security state

The default system security state is detailed below:

- CPU:
- Cortex-M33 is in secure state after reset. The boot address must be in secure address.
- Memory map:
- SAU is fully secure after reset. Consequently, all memory map is fully secure. Up to eight SAU configurable regions are available for security attribution.
- Flash memory:
- Flash memory security area is defined by watermark user options.
- Flash memory block based area is nonsecure after reset.
- SRAMs:
- All SRAMs are secure after reset. MPCBB (memory protection block based controller) is secure.
- External memories:
- FSMC, OCTOSPI banks are secure after reset. MPCWMx (memory protection watermark based controller) is secure.
- Peripherals
- Securable peripherals are nonsecure after reset.
- TrustZone-aware peripherals are nonsecure after reset. Their secure configuration registers are secure.
- All GPIOs are secure after reset.
- Interrupts:
- NVIC: All interrupts are secure after reset. NVIC is banked for secure and nonsecure state.
- TZIC: All illegal access interrupts are disabled after reset.


### 3.7 Boot modes

At startup, a BOOT0 pin, nBOOT0, NSBOOTADDx[24:0] $(x=0,1)$ and SECBOOTADD0[24:0] option bytes are used to select the boot memory address that includes:

- Boot from any address in user flash memory.
- Boot from system memory bootloader.
- Boot from any address in embedded SRAM.
- Boot from RSS (root security services).The BOOT0 value comes from the PH3-BOOT0 pin or from an option bit depending on the value of a user option bit to free the GPIO pad if needed.
The bootloader is located in the system memory, programmed by ST during production. The bootloader is used to reprogram the flash memory by using USART, I2C, SPI, FDCAN, or USB FS in device mode through the DFU (device firmware upgrade).
The bootloader is available on all devices. Refer to the application note STM32 microcontroller system memory boot mode (AN2606) for more details.
The RSS are embedded in a flash memory area named secure information block, programmed during ST production.
For example, the RSS enable the SFI (secure firmware installation), thanks to the RSSe SFI (RSS extension firmware).
This feature allows customer to produce the confidentiality of the firmware to be provisioned into the STM32, when production is subcontracted to untrusted third party.
The RSS are available on all devices, after enabling the TrustZone through the TZEN option bit. Refer to the application note Overview secure firmware install (SFI) (AN4992) for more details.
Refer to Table 6 and Table 7 for boot modes when TrustZone is disabled and enabled respectively.

Table 6. Boot modes when TrustZone is disabled (TZEN = 0)

| nBOOT0 <br> FLASH_ <br> OPTR[27] | BOOT0 <br> pin PH3 | nSWBOOT0 <br> FLASH_ <br> OPTR[26] | Boot address <br> option-byte <br> selection | Boot area | ST programmed <br> default value |
| :--: | :--: | :--: | :--: | :--: | :--: |
| - | 0 | 1 | NSBOOTADD0[24:0] | Boot address defined by <br> user option bytes <br> NSBOOTADD0[24:0] | Flash: 0x0800 0000 |
| - | 1 | 1 | NSBOOTADD1[24:0] | Boot address defined by <br> user option bytes <br> NSBOOTADD1[24:0] | Bootloader: <br> 0x0BF9 0000 |
| 1 | - | 0 | NSBOOTADD0[24:0] | Boot address defined by <br> user option bytes <br> NSBOOTADD0[24:0] | Flash: 0x0800 0000 |
| 0 | - | 0 | NSBOOTADD1[24:0] | Boot address defined by <br> user option bytes <br> NSBOOTADD1[24:0] | Bootloader: <br> 0x0BF9 0000 |

When TrustZone is enabled by setting the TZEN option bit, the boot space must be in the secure area. The SECBOOTADD0[24:0] option bytes are used to select the boot secure memory address.
A unique boot entry option can be selected by setting the BOOT_LOCK option bit, allowing to boot always at the address selected by SECBOOTADD0[24:0] option bytes. All other boot options are ignored.Table 7. Boot modes when TrustZone is enabled (TZEN = 1)

| $\begin{aligned} & \text { BOOT_ } \\ & \text { LOCK } \end{aligned}$ | nBOOT0 <br> FLASH_ OPTR[27] | $\begin{gathered} \text { BOOT0 } \\ \text { pin } \\ \text { PH3 } \end{gathered}$ | nSWBOOT0 <br> FLASH_ OPTR[26] | RSS <br> com- <br> mand | Boot address option-bytes selection | Boot area | ST programmed default value |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 0 | - | 0 | 1 | 0 | SECBOOTADDO [24:0] | Secure boot address defined by user option bytes SECBOOTADDO[24:0] | Flash: <br> 0x0C00 0000 |
|  | - | 1 | 1 | 0 | N/A | RSS | RSS: <br> 0x0FF8 0000 |
|  | 1 | - | 0 | 0 | SECBOOTADDO [24:0] | Secure boot address defined by user option bytes SECBOOTADDO[24:0] | Flash: <br> 0x0C00 0000 |
|  | 0 | - | 0 | 0 | N/A | RSS | RSS: <br> 0x0FF8 0000 |
|  | - | - | - | $\neq 0$ | N/A | RSS | RSS: <br> 0x0FF8 0000 |
| 1 | - | - | - | - | SECBOOTADDO [24:0] | Secure boot address defined by user option bytes SECBOOTADDO[24:0] | Flash: <br> 0x0C00 0000 |

The boot address option bytes allow any boot memory address to be programmed. However, the allowed address space depends on the flash memory RDP level.

If the programmed boot memory address is out of the allowed memory mapped area when RDP level is 0.5 or more, the default boot address is forced either in secure flash memory or nonsecure flash memory, depending on TrustZone security option as described in the table below.

Table 8. Boot space versus RDP protection

| RDP | TZEN $=1$ | TZEN $=0$ |
| :--: | :--: | :--: |
| 0 | Any boot address | Any boot address |
| 0.5 | Boot address only in RSS or secure Flash memory: 0x0C00 0000 - 0x0C1F FFFF Otherwise, forced boot address is 0x0FF8 0000. | N/A |
| 2 |  | Any boot address |
|  |  | Boot address only in Flash memory 0x0800 0000 - 0x081F FFFF Otherwise, forced boot address is 0x0800 0000. |# 3.8 Global TrustZone controller (GTZC) 

GTZC is used to configure TrustZone and privileged attributes within the full system.
The GTZC includes three different subblocks:

- TZSC: TrustZone security controller

This subblock defines the secure/privilege state of slave/master peripherals. It also controls the nonsecure area size for the watermark memory peripheral controller (MPCWM). The TZSC block informs some peripherals (such as RCC or GPIOs) about the secure status of each securable peripheral, by sharing with RCC and I/O logic.

- TZIC: TrustZone illegal access controller

This subblock gathers all security illegal access events in the system and generates a secure interrupt towards NVIC.

- MPCBB: MPCBB: block-based memory protection controller

This subblock controls secure states of all memory blocks (512-byte pages) of the associated SRAM. This peripheral aims at configuring the internal RAM in a TrustZone system product having segmented SRAM with programmable-security and privileged attributes.

The GTZC main features are:

- Three independent 32-bit AHB interfaces for TZSC, TZIC, and MPCBB
- Secure and nonsecure access supported for privileged/unprivileged part of TZSC
- Set of registers to define product security settings:
- Secure/privilege regions for external memories
- Secure/privilege access mode for securable peripherals
- Secure/privilege access mode for securable legacy masters


### 3.9 Power supply management

The PWR (power controller) main features are:

- Power supplies and supply domains
- Core domain ( $\mathrm{V}_{\mathrm{CORE}}$ )
- $\mathrm{V}_{\mathrm{DD}}$ domain
- Backup domain ( $\mathrm{V}_{\mathrm{BAT}}$ )
- Analog domain ( $\mathrm{V}_{\mathrm{DDA}}$ )
- SMPS power stage ( $\mathrm{V}_{\text {DDSMPS }}$, available only on SMPS packages)
- $\mathrm{V}_{\text {DDIO2 }}$ domain
- $\mathrm{V}_{\text {DDUSB }}$ for USB transceiver
- System supply voltage regulation
- SMPS step-down converter
- Voltage regulator (LDO)
- Power supply supervision
- BOR monitor
- PVD monitor
- PVM monitor ( $\mathrm{V}_{\mathrm{DDA}}, \mathrm{V}_{\mathrm{DDUSB}}, \mathrm{V}_{\mathrm{DDIO2}}$ )- Power management
- Operating modes
- Voltage scaling control
- Low-power modes
- $\mathrm{V}_{\mathrm{BAT}}$ battery charging
- TrustZone security and privileged protection


# 3.9.1 Power supply schemes 

The devices require a 1.71 V to $3.6 \mathrm{~V} \mathrm{~V}_{\mathrm{DD}}$ operating voltage supply. Several independent supplies can be provided for specific peripherals:

- $\mathrm{V}_{\mathrm{DD}}=1.71 \mathrm{~V}$ to 3.6 V (functionality guaranteed down to $\mathrm{V}_{\mathrm{BOR} \mathrm{x}}$ min value)
$\mathrm{V}_{\mathrm{DD}}$ is the external power supply for the I/Os, the internal regulator and the system analog such as reset, power management and internal clocks. It is provided externally through the VDD pins.
- $\mathrm{V}_{\mathrm{DDA}}=1.58 \mathrm{~V}$ (COMPs) / 1.6 V (DACs, OPAMPs) / 1.62 V (ADCs) / 1.8 V (VREFBUF) to 3.6 V
$\mathrm{V}_{\mathrm{DDA}}$ is the external analog power supply for ADCs, DACs, voltage reference buffer, operational amplifiers, and comparators. The $\mathrm{V}_{\mathrm{DDA}}$ voltage level is independent from the $\mathrm{V}_{\mathrm{DD}}$ voltage and must be connected to VDD or VSS pin (preferably to VDD) when these peripherals are not used.
- $\quad \mathrm{V}_{\text {DDSMPS }}=1.71 \mathrm{~V}$ to 3.6 V
$\mathrm{V}_{\text {DDSMPS }}$ is the external power supply for the SMPS step-down converter. It is provided externally through VDDSMPS supply pin. It must be connected to the same supply VDD pin when the SMPS is used in the application. When the SMPS is not used, it is recommended to connect both $\mathrm{V}_{\text {DDSMPS }}$ and $\mathrm{V}_{\text {LXSMPS }}$ to GND.
- $\quad \mathrm{V}_{\text {LXSMPS }}$ is the switched SMPS step-down converter output.

Note: The SMPS power supply pins are available only on a specific package with SMPS step-down converter option.

- $\quad \mathrm{V}_{\mathrm{DDUSB}}=3.0 \mathrm{~V}$ to 3.6 V
$\mathrm{V}_{\text {DDUSB }}$ is the external independent power supply for USB transceivers. $\mathrm{V}_{\text {DDUSB }}$ voltage level is independent from the $\mathrm{V}_{\mathrm{DD}}$ voltage and must be connected to VDD or VSS pin (preferably to VDD) when the USB is not used.
- $\quad \mathrm{V}_{\mathrm{DDIO} 2}=1.08 \mathrm{~V}$ to 3.6 V
$\mathrm{V}_{\mathrm{DDIO} 2}$ is the external power supply for $14 \mathrm{I} / \mathrm{Os}$ (port G[15:2]). The $\mathrm{V}_{\mathrm{DDIO} 2}$ voltage level is independent from the $\mathrm{V}_{\mathrm{DD}}$ voltage and must be connected to VDD or VSS pin (preferably to VDD) when PG[15:2] are not used.
- $\quad \mathrm{V}_{\mathrm{BAT}}=1.65 \mathrm{~V}$ to 3.6 V (functionality guaranteed down to $\mathrm{V}_{\mathrm{BOR}} \_$VBAT min value)
$\mathrm{V}_{\mathrm{BAT}}$ is the power supply for RTC, TAMP, external and internal clocks 32 kHz oscillators, and backup registers (through power switch) when $\mathrm{V}_{\mathrm{DD}}$ is not present.
- VREF-, VREF+
$\mathrm{V}_{\mathrm{REF}+}$ is the input reference voltage for ADCs and DACs. It is also the output of the internal voltage reference buffer when enabled.
$\mathrm{V}_{\mathrm{REF}+}$ can be grounded when ADC and DAC are not active.
The internal voltage reference buffer supports four outputs:
- $\mathrm{V}_{\mathrm{REF}+}$ around 1.5 V . This requires $\mathrm{V}_{\mathrm{DDA}} \geq 1.8 \mathrm{~V}$.- $\mathrm{V}_{\text {REF+ }}$ around 1.8 V . This requires $\mathrm{V}_{\mathrm{DDA}} \geq 2.1 \mathrm{~V}$.
- $\quad \mathrm{V}_{\text {REF+ }}$ around 2.048 V . This requires $\mathrm{V}_{\mathrm{DDA}} \geq 2.4 \mathrm{~V}$.
- $\quad \mathrm{V}_{\text {REF+ }}$ around 2.5 V . This requires $\mathrm{V}_{\mathrm{DDA}} \geq 2.8 \mathrm{~V}$.

VREF- and VREF+ pins are not available on all packages. When not available, they are bonded to VSSA and VDDA, respectively.
When the VREF+ is double-bonded with VDDA in a package, the internal voltage reference buffer is not available and must be kept disabled.
$\mathrm{V}_{\text {REF }}$, must always be equal to $\mathrm{V}_{\mathrm{SSA}}$.
The STM32U585xx devices embed two regulators: one LDO and one SMPS in parallel to provide the $\mathrm{V}_{\text {CORE }}$ supply for digital peripherals, SRAM1, SRAM2, SRAM3, and SRAM4 and embedded flash memory. The SMPS generates this voltage on VDD11 (two pins), with a total external capacitor of $4.7 \mu \mathrm{~F}$ typical. SMPS requires an external coil of $2.2 \mu \mathrm{H}$ typical. The LDO generates this voltage on VCAP pin connected to an external capacitor of $4.7 \mu \mathrm{~F}$ typical.
Both regulators can provide four different voltages (voltage scaling) and can operate in Stop modes.

It is possible to switch from SMPS to LDO and from LDO to SMPS on-the-fly.Figure 2. STM32U585xQ power supply overview (with SMPS)
![img-5.jpeg](img-5.jpeg)Figure 3. STM32U585xx power supply overview (without SMPS)
![img-6.jpeg](img-6.jpeg)

In this document, $\mathrm{V}_{\text {DDIOx }}$ refers to the I/O power supply. $\mathrm{V}_{\text {DDIOx }}$ can be $\mathrm{V}_{\text {DDIO1 }}$ (which is supplied by $\mathrm{V}_{\mathrm{DD}}$ ), $\mathrm{V}_{\text {DDIO2 }}$ (independent power supply for PG[15:2]), or $\mathrm{V}_{\mathrm{SW}}$ (supplying PC13, PC14, PC15, and all FT_t I/Os in VBAT mode).
$\mathrm{V}_{\mathrm{SW}}=\mathrm{V}_{\mathrm{DD}}$ when $\mathrm{V}_{\mathrm{DD}}$ is above $\mathrm{V}_{\mathrm{BOR} 0}$, and $\mathrm{V}_{\mathrm{SW}}=\mathrm{V}_{\mathrm{BAT}}$ when $\mathrm{V}_{\mathrm{DD}}$ is below $\mathrm{V}_{\mathrm{BOR} 0}$.
During power-up and power-down phases, the following power sequence requirements must be respected:

- When $\mathrm{V}_{\mathrm{DD}}$ is below 1 V , other power supplies $\left(\mathrm{V}_{\mathrm{DDA}}, \mathrm{V}_{\mathrm{DDIO2}}, \mathrm{V}_{\mathrm{DDUSB}}\right)$ must remain below $\mathrm{V}_{\mathrm{DD}}+300 \mathrm{mV}$.
- When $\mathrm{V}_{\mathrm{DD}}$ is above 1 V , all power supplies are independent.
- During the power-down phase, $\mathrm{V}_{\mathrm{DD}}$ can temporarily become lower than other supplies only if the energy provided to the MCU remains below 1 mJ . This allows external decoupling capacitors to be discharged with different time constants during the power-down transient phase.Figure 4. Power-up /down sequence
![img-7.jpeg](img-7.jpeg)

1. $\mathrm{V}_{\mathrm{DDX}}$ refers to any power supply among $\mathrm{V}_{\mathrm{DDA}}, \mathrm{V}_{\mathrm{DDUSB}}$, and $\mathrm{V}_{\mathrm{DDIO} 2}$.

# 3.9.2 Power supply supervisor 

The devices have an integrated ultra-low-power BOR (Brownout reset) active in all modes (except for Shutdown mode). The BOR ensures proper operation of the device after poweron and during power-down. The device remains in reset mode when the monitored supply voltage $\mathrm{V}_{\mathrm{DD}}$ is below a specified threshold, without the need for an external reset circuit.
The lowest BOR level is 1.71 V at power-on, and other higher thresholds can be selected through option bytes. The devices feature an embedded PVD (programmable voltage detector) that monitors the $\mathrm{V}_{\mathrm{DD}}$ power supply and compares it to the $\mathrm{V}_{\mathrm{PVD}}$ threshold.
An interrupt can be generated when $\mathrm{V}_{\mathrm{DD}}$ drops below and/or rises above the $\mathrm{V}_{\mathrm{PVD}}$ threshold. The interrupt service routine can then generate a warning message and/or put the MCU into a safe state. The PVD is enabled by software.
In addition, the devices embed a peripheral voltage monitor that compares the independent supply voltages $\mathrm{V}_{\mathrm{DDA}}, \mathrm{V}_{\mathrm{DDUSB}}$, and $\mathrm{V}_{\mathrm{DDIO} 2}$ to ensure that the peripheral is in its functional supply range.
The devices support dynamic voltage scaling to optimize its power consumption in Run mode. The voltage from the main regulator that supplies the logic ( $\mathrm{V}_{\mathrm{CORE}}$ ) can be adjusted according to the system's maximum operating frequency.
The main regulator operates in the following ranges:

- Range $1\left(V_{\text {CORE }}=1.2 \mathrm{~V}\right)$ with CPU and peripherals running at up to 160 MHz
- Range $2\left(V_{\text {CORE }}=1.1 \mathrm{~V}\right)$ with CPU and peripherals running at up to 110 MHz
- Range $3\left(V_{\text {CORE }}=1.0 \mathrm{~V}\right)$ with CPU and peripherals running at up to 55 MHz
- Range $4\left(V_{\text {CORE }}=0.9 \mathrm{~V}\right)$ with CPU and peripherals running at up to 25 MHz# 3.9.3 Low-power modes 

The ultra-low-power STM32U585xx devices support seven low-power modes to achieve the best compromise between low-power consumption, short startup time, available peripherals and available wake-up sources.
The table below details the related low-power modes.
Table 9. STM32U585xx mode overview

| Mode | Regulator ${ }^{(1)}$ | CPU | Flash | SRAM | Clocks | DMA and peripherals ${ }^{(2)}$ | Wake-up source |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Run | Range 1 | Yes | $\mathrm{ON}^{(3)}$ | ON | Any | All | N/A |
|  | Range 2 |  |  |  |  |  |  |
|  | Range 3 |  |  |  |  | All except OTG_FS and UCPD |  |
| Sleep | Range 1 | No | ON | $\mathrm{ON}^{(4)}$ | Any | All | Any interrupt or event |
|  | Range 2 |  |  |  |  |  |  |
|  | Range 3 |  |  |  |  |  |  |
|  | Range 4 |  |  |  |  | All except OTG_FS, and UCPD |  |
| Stop 0 | Range 1 | No | OFF | $\mathrm{ON}^{(5)}$ | $\begin{aligned} & \text { LSE } \\ & \text { LSI } \\ & \text { (6) } \end{aligned}$ | BOR, PVD, PVM, <br> RTC, TAMP, IWDG, <br> TEMP (temp. sensor), <br> VREFBUF, <br> ADC4 ${ }^{(7)}$, <br> DAC1 (2 channels) ${ }^{(8)}$, <br> COMPx ( $x=1,2$ ), <br> OPAMPx ( $x=1,2$ ), <br> USARTx ( $x=1 \ldots 5$ ) ${ }^{(9)}$, <br> LPUART1, <br> SPIx $(x=1 \ldots 3)^{(10)}$, <br> I2Cx $(x=1 \ldots 4)^{(11)}$, <br> LPTIMx $(x=1 \ldots 4)^{(12)}$, <br> MDF1 ${ }^{(13)}$, ADF1, <br> GPIO, LPGPIO, <br> GPDMA1 ${ }^{(14)}$, LPDMA1 <br> All other peripherals are frozen. | Reset pin, all I/Os, <br> BOR, PVD, PVM, <br> RTC, TAMP, IWDG, <br> TEMP, <br> ADC4, <br> DAC1 (2 channels), <br> COMPx ( $x=1,2$ ), <br> USARTx ( $x=1 \ldots 5$ ), <br> LPUART1, <br> SPIx ( $x=1 \ldots 3$ ), <br> I2Cx ( $x=1 \ldots 4$ ), <br> LPTIMx ( $x=1 \ldots 4$ ), <br> MDF1, ADF1, <br> GPDMA1, <br> LPDMA1, <br> OTG_FS, UCPD |Table 9. STM32U585xx mode overview (continued)

| Mode | Regulator ${ }^{(1)}$ | CPU | Flash | SRAM | Clocks | DMA and peripherals ${ }^{(2)}$ | Wake-up source |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Stop 2 | LPR | No | OFF | $\mathrm{ON}^{(5)}$ | $\begin{aligned} & \text { LSE } \\ & \text { LSI } \end{aligned}$ | BOR, PVD, PVM, <br> RTC, TAMP, IWDG, <br> TEMP, VREFBUF, <br> ADC4, <br> DAC1 (2 channels), <br> COMPx ( $x=1,2$ ), <br> OPAMPx ( $x=1,2$ ), <br> LPUART1, <br> SPI3, <br> I2C3, <br> LPTIMx ( $x=1,3,4$ ), <br> ADF1, <br> LPGPIO, <br> LPDMA1 <br> All other peripherals are frozen. | Reset pin, all I/Os, BOR, PVD, PVM, RTC, TAMP, IWDG, TEMP, ADC4, COMPx ( $x=1,2$ ), LPUART1, SPI3, I2C3, LPTIMx ( $x=1,3,4$ ), ADF1, LPDMA1 |
| Stop 3 | LPR | No | OFF | $\mathrm{ON}^{(5)}$ | $\begin{aligned} & \text { LSE } \\ & \text { LSI } \end{aligned}$ | BOR, <br> RTC, TAMP, IWDG, <br> DAC1 (2 static channels), <br> OPAMPx ( $x=1,2$ ) <br> All other peripherals are frozen. <br> I/O configuration can be floating, pull-up or pull-down. | Reset pin, 24 I/Os (WKUPx), BOR, RTC, TAMP, IWDG |
| Standby | LPR | Powered off | OFF | $\begin{aligned} & \text { 64-, 56- or 8-Kbyle SRAM2 } \\ & \text { 2-Kbyle BKPSRAM } \end{aligned}$ | LSE <br> LSI | BOR, RTC, TAMP, IWDG <br> All other peripherals are powered off. <br> I/O configuration can be floating, pull-up or pull-down. | Reset pin, 24 I/Os (WKUPx), BOR, RTC, TAMP, IWDG |
|  | OFF |  |  |  |  |  |  |
| Shutdown | OFF | Powered off | OFF | $\begin{aligned} & \text { Powered } \\ & \text { off } \end{aligned}$ | LSE | RTC, TAMP <br> All other peripherals are powered off. <br> I/O configuration can be floating, pull-up or pull-down ${ }^{(15)}$. | Reset pin, 24 I/Os (WKUPx), RTC, TAMP |1. LPR means that the main regulator is OFF and the low-power regulator is ON.
2. All peripherals can be active or clock gated to save power consumption.
3. The flash memory can be put in power-down and its clock can be gated off when executing from SRAM. One bank can also be put in power-down mode.
4. The SRAM1, SRAM2, SRAM3, SRAM4, and BKPSRAM clocks can be gated on or off independently.
5. The SRAM can be individually powered off to save power consumption.
6. MSI and HSI16 can be temporary enabled upon peripheral request, for autonomous functions with DMA or wake-up from Stop event detections.
7. The ADC4 conversion is functional and autonomous with DMA in Stop mode, and can generate a wake-up interrupt on conversion events.
8. DAC1 is the digital-to-analog (D/A) converter controller instance name. This instance controls two D/A converters also called "two channels". The DAC conversions are functional and autonomous with DMA in Stop mode.
9. U(S)ART and LPUART transmission and reception is functional and autonomous with DMA in Stop mode, and can generate a wake-up interrupt on transfer events.
10. SPI transmission and reception is functional and autonomous with DMA in Stop mode, and can generate a wake-up interrupt on transfer events.
11. I2C transmission and reception is functional and autonomous with DMA in Stop mode, and can generate a wake-up interrupt on transfer events.
12. LPTIM is functional and autonomous with DMA in Stop mode, and can generate a wake-up interrupt on all events.
13. MDF and ADF are functional and autonomous with DMA in Stop mode, and can generate a wake-up interrupt on events.
14. GPDMA and LPDMA are functional and autonomous in Stop mode, and can generate a wake-up interrupt on events.
15. I/Os can be configured with internal pull-up, pull-down, or floating in Shutdown mode but the configuration is lost when exiting the Shutdown mode.

By default, the microcontroller is in Run mode after a system or a power reset. It is up to the user to select one of the low-power modes described below:

- Sleep mode

In Sleep mode, only the CPU is stopped. All peripherals continue to operate and can wake up the CPU when an interrupt/event occurs.

- Stop 0, Stop 1, Stop 2, and Stop 3 modes

Stop mode achieves the lowest power consumption while retaining the content of SRAM and registers. The SRAMs can be totally or partially switched off to further reduce consumption. All clocks in the $\mathrm{V}_{\text {CORE }}$ domain are stopped, the PLL, the MSI, the HSI16, the HSI48, and the HSE crystal oscillators are disabled. The LSE or LSI is still running.
The RTC can remain active (Stop mode with RTC, Stop mode without RTC).
Some peripherals are autonomous and can operate in Stop mode by requesting their kernel clock and their bus (APB or AHB) when needed, in order to transfer data with DMA (GPDMA1 in Stop 0 and Stop 1 modes, LPDMA1 in Stop 0, Stop 1 and Stop 2 modes). Refer to Low-power background autonomous mode (LPBAM) for more details. LPBAM is not supported in Stop 3 mode.
In Stop 2 and Stop 3 modes, most of the $\mathrm{V}_{\text {CORE }}$ domain is put in a lower leakage mode. Stop 0 and Stop 1 modes offer the largest number of active peripherals and wake-up sources, a smaller wake-up time but a higher consumption than Stop 2 mode.
In Stop 0 mode, the main regulator remains ON, allowing a very fast wake-up time but with much higher consumption.
Stop 3 is the lowest power mode with full retention, but the functional peripherals and sources of wake-up are reduced to the same ones than in Standby mode.
The system clock when exiting from Stop 0, Stop 1 or Stop 2 mode can be either MSI up to 24 MHz or HSI16, depending on software configuration.- Standby mode

The Standby mode is used to achieve the lowest power consumption with BOR. The internal regulator is switched off so that the $\mathrm{V}_{\text {CORE }}$ domain is powered off. The PLL, the MSI, the HSI16, the HSI48, and the HSE crystal oscillators are also switched off.
The RTC can remain active (Standby mode with RTC, Standby mode without RTC).
The BOR always remains active in Standby mode.
The state of each I/O during Standby mode can be selected by software: I/O with internal pull-up, internal pull-down or floating.
After entering Standby mode, SRAMs and register contents are lost except for registers and backup SRAM in the backup domain and Standby circuitry. Optionally, the full SRAM2 or 8 Kbytes or 56 Kbytes can be retained in Standby mode, supplied by the low-power regulator (Standby with SRAM2 retention mode).
The BOR can be configured in ultra-low-power mode to further reduce power consumption during Standby mode.
The device exits Standby mode when an external reset (NRST pin), an IWDG reset, WKUP pin event (configurable rising or falling edge), an RTC event occurs (alarm, periodic wake-up, timestamp), or a tamper detection. The tamper detection can be raised either due to external pins or due to an internal failure detection.
The system clock after wake-up is MSI up to 4 MHz .

- Shutdown mode

The lowest power consumption is achieved in Shutdown mode. The internal regulator is switched off so that the $\mathrm{V}_{\text {CORE }}$ domain is powered off. The PLL, the HSI16, the HSI48, the MSI, the LSI, and the HSE oscillators are also switched off.
The RTC can remain active (Shutdown mode with RTC, Shutdown mode without RTC). The BOR is not available in Shutdown mode. No power voltage monitoring is possible in this mode, therefore the switch to backup domain is not supported ( $\mathrm{V}_{\mathrm{BAT}}$ mode is not supported).
SRAMs and register contents are lost except for registers in the backup domain as long as VDD is present.
The device exits Shutdown mode when an external reset (NRST pin), a WKUP pin event (configurable rising or falling edge), or an RTC event occurs (alarm, periodic wake-up, timestamp), or a tamper detection.
The system clock after wake-up is MSI at 4 MHz .

# Low-power background autonomous mode (LPBAM) 

The ultra-low-power STM32U585xx devices support LPBAM (low-power background autonomous mode) that allows peripherals to be functional and autonomous in Stop mode (Stop 0, Stop 1 and Stop 2 modes), so without any software running.
In Stop 0 and Stop 1 modes, the autonomous peripherals are the following: ADC4, DAC1, LPTIMx ( $x=1$ to 4 ), USARTx ( $x=1$ to 5 ), LPUART1, SPIx ( $x=1$ to 3 ), I2Cx ( $x=1$ to 4 ), MDF1, ADF1, GPDMA1, and LPDMA1. In these modes, SRAM1, SRAM2, SRAM3 and SRAM4 can be accessed by the GPDMA1, and SRAM4 can be accessed by the LPDMA1.
In Stop 2 mode, the autonomous peripherals are the following: ADC4, DAC1, LPTIM1, LPTIM3, LPTIM4, LPUART1, SPI3, I2C3, ADF1, and LPDMA1. In this mode, the SRAM4 can be accessed by the LPDMA1.Those peripherals support the features detailed below:

- Functionality in Stop mode thanks to its own independent clock (named kernel clock) request capability: the peripheral kernel clock is automatically switched on when requested by a peripheral, and automatically switched off when no peripheral requests it.
- DMA transfers supported in Stop mode thanks to system clock request capability: the system clock (MSI or HSI16) automatically switched on when requested by a peripheral, and automatically switched off when no peripheral requests it. When the system clock is requested by an autonomous peripheral, the system clock is woken up and distributed to all peripherals enabled in the RCC. This allows the DMA to access the enabled SRAM, and any enabled peripheral register (for instance GPIO or LPGPIO registers).
- Automatic start of the peripheral thanks to hardware synchronous or asynchronous triggers (such as I/Os edge detection and low-power timer event).
- Wake-up from Stop mode with peripheral interrupt.

The GPDMA and LPDMA are fully functional and the linked-list is updated in Stop mode, allowing the different DMA transfers to be linked without any CPU wake-up. This can be used to chain different peripherals transfers, or to write peripherals registers in order to change their configuration while remaining in Stop mode.

The DMA transfers from memory to memory can be started by hardware synchronous or asynchronous triggers, and the DMA transfers between peripherals and memories can also be gated by those triggers.
Here below some use-cases that can be done while remaining in Stop mode:

- A/D or D/A conversion triggered by a low-power timer (or any other trigger)
- wake-up from Stop mode on analog watchdog if the A/D conversion result is out of programmed thresholds
- wake-up from Stop mode on DMA buffer event
- Audio digital filter data transfer into SRAM
- wake-up from Stop on sound-activity detection
- $I^{2} \mathrm{C}$ slave reception or transmission, SPI reception, UART/LPUART reception
- wake-up at the end of peripheral transfer or on DMA buffer event
- $I^{2} \mathrm{C}$ master transfer, SPI transmission, UART/LPUART transmission, triggered by a low-power timer (or any other trigger):
- example: sensor periodic read
- wake-up at the end of peripheral transfer or on DMA buffer event
- Bridges between peripherals
- example: ADC converted data transferred by communication peripherals
- Data transfer from/to GPIO/LPGPIO to/from SRAM for:
- controlling external components
- implementing data transmission and reception protocolsTable 10. Functionalities depending on the working mode ${ }^{(1)}$

| Peripheral | Run | Sleep | Stop 0/1 |  | Stop 2 |  | Stop 3 |  | Standby |  | Shutdown |  | $\mathrm{V}_{\text {BAT }}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | - |  | - |  | - |  | - |  | - |  |  |
| CPU | Y | - | - | - | - | - | - | - | - | - | - | - | - |
| Flash memory (2 Mbytes) | $0^{(2)}$ | $0^{(2)}$ | - | - | - | - | - | - | - | - | - | - | - |
| SRAM1 (192 Kbytes) | $Y^{(3)(4)}$ | $Y^{(3)(4)}$ | $0^{(7)}$ | - | $0^{(7)}$ | - | $0^{(7)}$ | - | - | - | - | - | - |
| SRAM2 (64 Kbytes) | $Y^{(3)(4)}$ | $Y^{(3)(4)}$ | $0^{(7)}$ | $0^{(5)}$ | $0^{(7)}$ | - | $0^{(7)}$ | - | $0^{(6)}$ | - | - | - | - |
| SRAM3 (512 Kbytes) | $Y^{(3)(4)}$ | $Y^{(3)(4)}$ | $0^{(7)}$ | $0^{(5)}$ | $0^{(7)}$ | - | $0^{(7)}$ | - | - | - | - | - | - |
| SRAM4 (16 Kbytes) | $Y^{(3)(4)}$ | $Y^{(3)(4)}$ | $0^{(7)}$ | - | $0^{(7)}$ | - | $0^{(7)}$ | - | - | - | - | - | - |
| BKPSRAM | $0^{(4)}$ | $0^{(4)}$ | 0 | $0^{(5)}$ | 0 |  | 0 |  | 0 |  | - |  | 0 |
| FSMC | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| OCTOSPIx ( $x=1,2$ ) | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| Backup registers | Y | Y | Y | - | Y | - | Y | - | Y | - | Y | - | Y |
| BOR (Brownout reset) | Y | Y | Y | Y | Y | Y | Y | Y | Y | Y | - | - | - |
| PVD (programmable voltage detector) | 0 | 0 | 0 | 0 | 0 | 0 | - | - | - | - | - | - | - |
| Peripheral voltage monitor | 0 | 0 | 0 | 0 | 0 | 0 | - | - | - | - | - | - | - |
| GPDMA1 | 0 | 0 | 0 | $0^{(8)}$ | - | - | - | - | - | - | - | - | - |
| LPDMA1 | 0 | 0 | 0 | $0^{(9)}$ | 0 | $0^{(9)}$ | - | - | - | - | - | - | - |
| DMA2D | 0 | 0 |  |  |  |  |  |  |  |  |  |  |  |
| HSI16 (high-speed internal) | 0 | 0 | ${ }^{(10)}$ | - | ${ }^{(10)}$ | - | - | - | - | - | - | - | - |
| HSI48 oscillator | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| HSE (high-speed external) | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| LSI (low-speed internal) | 0 | 0 | 0 | - | 0 | - | 0 | - | 0 | - | - | - | 0 |
| LSE (low-speed external) | 0 | 0 | 0 | - | 0 | - | 0 | - | 0 | - | 0 | - | 0 |
| MSIS and MSIK (multi-speed internal) | 0 | 0 | ${ }^{(10)}$ | - | ${ }^{(10)}$ | - | - | - | - | - | - | - | - |
| CSS (clock security system) | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| Clock security system on LSE | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |Table 10. Functionalities depending on the working mode ${ }^{(1)}$ (continued)

| Peripheral | Run | Sleep | Stop 0/1 |  | Stop 2 |  | Stop 3 |  | Standby |  | Shutdown |  | $\mathrm{V}_{\text {BAT }}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | $\begin{aligned} & \text { Wake-up } \\ & \text { capab } \end{aligned}$ |  | Wake-up capab |  | Wake-up capab |  | Wake-up capab |  | Wake-up capab |  |  |
| Backup domain voltage and temperature monitoring | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | - |  | 0 |
| RTC/TAMP | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 | 0 |
| Number of RTC tamper pins | 8 | 8 | 8 | 0 | 8 | 0 | 8 | 0 | 8 | 0 | 8 | 0 | 8 |
| OTG_FS, UCPD | $0^{(11)}$ | $0^{(11)}$ | - | 0 | - | - | - | - | - | - | - | - | - |
| USARTx $(x=1,2,3,4,5)$ | 0 | 0 | $0^{(12)}$ | $0^{(12)}$ | - | - | - | - | - | - | - | - | - |
| Low-power UART (LPUART1) | 0 | 0 | $0^{(12)}$ | $0^{(12)}$ | $0^{(12)}$ | $0^{(12)}$ | - | - | - | - | - | - | - |
| I2Cx ( $x=1,2,4)$ | 0 | 0 | $0^{(13)}$ | $0^{(13)}$ | - | - | - | - | - | - | - | - | - |
| I2C3 | 0 | 0 | $0^{(13)}$ | $0^{(13)}$ | $0^{(13)}$ | $0^{(13)}$ | - | - | - | - | - | - | - |
| SPIx ( $x=1,2)$ | 0 | 0 | $0^{(14)}$ | $0^{(14)}$ | - | - | - | - | - | - | - | - | - |
| SPI3 | 0 | 0 | $0^{(14)}$ | $0^{(14)}$ | $0^{(14)}$ | $0^{(14)}$ |  |  |  |  |  |  |  |
| FDCAN1 | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| SDMMCx ( $x=1,2)$ | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| SAIx ( $x=1,2)$ | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| ADC1 | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| ADC4 | 0 | 0 | $0^{(15)}$ | $0^{(15)}$ | $0^{(15)}$ | $0^{(15)}$ | - | - | - | - | - | - | - |
| DAC1 (2 converters) | 0 | 0 | 0 | - | 0 | - | - | - | - | - | - | - | - |
| VREFBUF | 0 | 0 | 0 | - | 0 | - | - | - | - | - | - | - | - |
| OPAMPx ( $x=1,2)$ | 0 | 0 | 0 | - | 0 | - | - | - | - | - | - | - | - |
| COMPx ( $x=1,2)$ | 0 | 0 | 0 | 0 | 0 | 0 | - | - | - | - | - | - | - |
| Temperature sensor | 0 | 0 | 0 | - | 0 | - | - | - | - | - | - | - | - |
| Timers (TIMx) | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| LPTIMx ( $x=1,3,4)$ | 0 | 0 | $0^{(16)}$ | $0^{(16)}$ | $0^{(16)}$ | $0^{(16)}$ | - | - | - | - | - | - | - |
| LPTIM2 | 0 | 0 | $0^{(16)}$ | $0^{(16)}$ | - | - | - | - | - | - | - | - | - |
| IWDG (independent watchdog) | 0 | 0 | 0 | 0 | 0 | 0 | 0 | $\begin{gathered} 0 \\ (17) \end{gathered}$ | 0 | $\begin{gathered} 0 \\ (17) \end{gathered}$ | - | - | - |
| WWDG (window watchdog) | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |Table 10. Functionalities depending on the working mode ${ }^{(1)}$ (continued)

| Peripheral | Run | Sleep | Stop 0/1 |  | Stop 2 |  | Stop 3 |  | Standby |  | Shutdown |  | $\mathrm{V}_{\text {BAT }}$ |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  | - | - | - | - | - | - | - | - | - | - |  |
| SysTick timer | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| MDF1 (multi-function digital filter) | 0 | 0 | $0^{(18)}$ | $0^{(18)}$ | - | - | - | - | - | - | - | - | - |
| ADF1 (audio digital filter) | 0 | 0 | $0^{(18)}$ | $0^{(18)}$ | $0^{(18)}$ | $0^{(18)}$ | - | - | - | - | - | - | - |
| DCMI (digital camera interface) | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| PSSI (paral. synch. <br> slave interface) | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| CORDIC coprocessor | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| FMAC (filter mathematical accelerator) | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| TSC (touch sensing controller) | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| RNG (true random number generator) | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| AES and secure AES | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| PKA (public key accelerator) | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| OTFDEC (on-the-fly decryption) | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| HASH accelerator | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| CRC calculation unit | 0 | 0 | - | - | - | - | - | - | - | - | - | - | - |
| GPIOs | 0 | 0 | 0 | 0 | 0 | 0 | $\begin{gathered} - \\ (19) \end{gathered}$ | $\begin{gathered} 24 \\ \text { pins } \end{gathered}$ | $\begin{gathered} - \\ (19) \end{gathered}$ | $\begin{gathered} 24 \\ \text { pins } \end{gathered}$ | $\begin{gathered} - \\ (20) \end{gathered}$ | $\begin{gathered} 24 \\ \text { pins } \end{gathered}$ | - |

1. $Y=$ yes (enabled). $O=$ optional (disabled by default, can be enabled by software). - = not available. Gray cells highlight the wake-up capability in each mode.
2. The flash memory can be configured in power-down mode. By default, it is not in power-down mode.
3. The SRAMs can be powered on or off independently.
4. The SRAM clock can be gated on or off independently.
5. ECC error interrupt or NMI wake-up from Stop mode.
6. 8-Kbyte, 56-Kbyte or full SRAM2 content can be preserved.
7. Subblocks or full SRAM1 and SRAM3, full SRAM2, and SRAM4 can be powered-off to save power consumption. SRAM1, SRAM2, SRAM3 and SRAM4 can be accessed by GPDMA1 in Stop 0 and Stop 1 modes. SRAM4 can be accessed by LPDMA1 in Stop 0, Stop 1 and Stop 2 modes.
8. GPDMA transfers are functional and autonomous in Stop mode, and generates a wake-up interrupt on transfer events.
9. LPDMA transfers are functional and autonomous in Stop mode, and generates a wake-up interrupt on transfer events.10. Some peripherals with autonomous mode and wake-up from Stop capability can request HSI16, MSIS, or MSIK to be enabled. In this case, the oscillator is woken up by the peripheral, and is automatically put off when no peripheral needs it.
11. OTG_FS is functional in voltage scaling range 1, 2, and 3.
12. USART and LPUART reception and transmission are functional and autonomous in Stop mode in asynchronous and in SPI master modes, and generate a wake-up interrupt on transfer events.
13. I²C reception and transmission are functional and autonomous in Stop mode, and generate a wake-up interrupt on transfer events.
14. SPI reception and transmission are functional and autonomous in Stop mode, and generate a wake-up interrupt on transfer events.
15. A/D conversion is functional and autonomous in Stop mode, and generates a wake-up interrupt on conversion events.
16. LPTIM is functional and autonomous in Stop mode, and generates a wake-up interrupt on events.
17. Only IWDG reset can exit the device from Stop 3 and Standby modes. Wake-up with IWDG interrupt is not supported.
18. MDF and ADF are functional and autonomous in Stop mode, and generate a wake-up interrupt on events.
19. I/Os can be configured with internal pull-up, pull-down, or floating in Stop 3 and Standby modes.
20. I/Os can be configured with internal pull-up, pull-down, or floating in Shutdown mode but the configuration is lost when exiting the Shutdown mode.

# 3.9.4 Reset mode 

In order to improve the consumption under reset, the I/O state under and after reset is "analog state" (the I/O Schmitt trigger is disabled). In addition, the internal reset pull-up is deactivated when the reset source is internal.

### 3.9.5 VBAT operation

The VBAT pin allows the device $\mathrm{V}_{\mathrm{BAT}}$ domain to be powered from an external battery or an external supercapacitor.

The VBAT pin supplies the RTC with LSE, antitamper detection (TAMP), backup registers, and 2-Kbyte backup SRAM. Eight antitamper detection pins are available in $\mathrm{V}_{\mathrm{BAT}}$ mode.

The VBAT operation is automatically activated when $\mathrm{V}_{\mathrm{DD}}$ is not present. An internal $\mathrm{V}_{\mathrm{BAT}}$ battery charging circuit is embedded and can be activated when $\mathrm{V}_{\mathrm{DD}}$ is present.
Note: When the microcontroller is supplied from $V_{B A T}$, neither external interrupts nor RTC/TAMP alarm/events exit the microcontroller from the $V_{B A T}$ operation.

### 3.9.6 PWR TrustZone security

When the TrustZone security is activated by the TZEN option bit, the PWR is switched in TrustZone security mode.

The PWR TrustZone security secures the following configuration:

- low-power mode
- WKUP (wake-up) pins
- voltage detection and monitoring
- $\mathrm{V}_{\mathrm{BAT}}$ mode

Some of the PWR configuration bits security is defined by the security of other peripherals:

- The VOS (voltage scaling) configuration is secure when the system clock selection is secure in RCC.
- The I/O pull-up/pull-down in Standby mode configuration is secure when the corresponding GPIO is secure.# 3.10 Peripheral interconnect matrix 

Several peripherals have direct connections between them, that allow autonomous communication between them and support the saving of CPU resources (thus power supply consumption). In addition, these hardware connections allow fast and predictable latency.

Depending on the peripherals, these interconnections can operate in Run, Sleep, Stop 0, Stop 1, and Stop 2 modes.

### 3.11 Reset and clock controller (RCC)

The RCC (reset and clock control) manages the different reset types, and generates all clocks for the bus and peripherals.

The RCC distributes the clocks coming from the different oscillators to the core and to the peripherals. It also manages the clock gating for low-power modes and ensures the clock robustness. It features:

- Clock prescaler: in order to get the best trade-off between speed and current consumption, the clock frequency to the CPU and peripherals can be adjusted by a programmable prescaler.
- Clock security system: clock sources can be changed safely on-the-fly in Run mode through a configuration register.
- Clock management: in order to reduce the power consumption, the clock controller can stop the clock to the core, individual peripherals or memory.
- System clock source: four different clock sources can be used to drive the master clock SYSCLK:
- HSE (4 to 50 MHz high-speed external crystal or ceramic resonator) that can supply a PLL. The HSE can also be configured in bypass mode for an external clock.
- HSI16 (16 MHz high-speed internal RC oscillator) trimmable by software that can supply a PLL.
- MSI (multispeed internal RC oscillator) trimmable by software that can generate 16 frequencies from 100 kHz to 48 MHz . When a 32.768 kHz clock source is available in the system (LSE), the MSI frequency can be automatically trimmed by hardware to reach better than $\pm 0.25 \%$ accuracy. In this mode the MSI can feed the USB device, saving the need of an external high-speed crystal (HSE). The MSI can supply a PLL.
- System PLL that can be fed by HSE, HSI16, or MSI, with a maximum frequency at 160 MHz .
- HSI48 (RC48 with clock recovery system) internal 48 MHz clock source that can be used to drive the USB, the SDMMC, or the RNG peripherals. This clock can be output on the MCO.
- UCPD kernel clock, derived from HSI16 clock. The HSI16 RC oscillator must be enabled prior to the UCPD kernel clock use.- Auxiliary clock source: two ultra-low-power clock sources that can be used to drive the real-time clock:
- LSE ( 32.768 kHz low-speed external crystal), supporting three drive capability modes. The LSE can also be configured in bypass mode for an external clock.
- LSI ( 32 kHz low-speed internal RC), also used to drive the independent watchdog. The LSI clock accuracy is $\pm 5 \%$ accuracy. The LSI clock can be divided by 128 to output a 250 Hz as source clock.
- Peripheral clock sources: several peripherals have their own independent clock whatever the system clock. Three PLLs, each having three independent outputs allowing the highest flexibility, can generate independent clocks for the ADC, USB, SDMMC, RNG, MDF, ADF, FDCAN1, OCTOSPIs, and SAIs.
- Startup clock: after reset, the microcontroller restarts by default with MSI. The prescaler ratio and clock source can be changed by the application program as soon as the code execution starts.
- CSS (clock security system): this feature can be enabled by software. If an HSE clock failure occurs, the master clock automatically switches to HSI16 and a software interrupt is generated if enabled. LSE failure can also be detected and generates an interrupt.
- Clock-out capability:
- MCO (microcontroller clock output): it outputs one of the internal clocks for external use by the application.
- LSCO (low-speed clock output): it outputs LSI or LSE in all low-power modes (except $\mathrm{V}_{\mathrm{BAT}}$ mode).
Several prescalers allow AHB and APB frequencies configuration. The maximum frequency of the AHB and the APB clock domains is 160 MHz .Figure 5. Clock tree
![img-8.jpeg](img-8.jpeg)# 3.11.1 RCC TrustZone security 

When the TrustZone security is activated by the TZEN option bit, the RCC is switched in TrustZone security mode.

The RCC TrustZone security secures some RCC system configuration and peripheral configuration clock from being read or modified by nonsecure accesses: when a peripheral is secure, the related peripheral clock, reset, clock source selection and clock enable during low-power modes control bits are secure.

A peripheral is in secure state:

- when its corresponding SEC security bit is set in the TZSC (TrustZone security controller), for securable peripherals.
- when a security feature of this peripheral is enabled through its dedicated bits, for TrustZone-aware peripherals.


### 3.12 Clock recovery system (CRS)

The devices embed a special block that allows automatic trimming of the internal 48 MHz oscillator to guarantee its optimal accuracy over the whole device operational range. This automatic trimming is based on the external synchronization signal that is either derived from USB SOF signalization, from LSE oscillator, from an external signal on CRS_SYNC pin or generated by user software. For faster lock-in during startup, automatic trimming and manual trimming action can be combined.

### 3.13 General-purpose inputs/outputs (GPIOs)

Each of the GPIO pins can be configured by software as output (push-pull or open-drain), as input (with or without pull-up or pull-down) or as peripheral alternate function. Most of the GPIO pins are shared with digital or analog alternate functions.

After reset, all GPIOs are in analog mode to reduce power consumption.
The I/Os alternate function configuration can be locked if needed following a specific sequence in order to avoid spurious writing to the I/Os registers.

### 3.13.1 GPIOs TrustZone security

Each I/O pin of GPIO port can be individually configured as secure. When the selected I/O pin is configured as secure, its corresponding configuration bits for alternate function, mode selection, I/O data are secure against a nonsecure access. The associated registers bit access is restricted to a secure software only. After reset, all GPIO ports are secure.

### 3.14 Low-power general-purpose inputs/outputs (LPGPIO)

The LPGPIO allows dynamic I/O control in Stop 2 mode thanks to LPDMA1. Up to 16 I/Os can be configured and controlled as input or output (open-drain or push-pull depending on GPIO configuration).# 3.14.1 LPGPIO TrustZone security 

Each I/O pin registers bit of the LPGPIO is configured as secure if the corresponding I/O is configured as secure in the GPIO.

### 3.15 Multi-AHB bus matrix

A 32-bit multi-AHB bus matrix interconnects all master (CPU, DMA2D, GPDMA1, SDMMC1, SDMMC2) and slave (Flash memory, RAM, FMC, OCTOSPIs, SRAMs, AHB, and APB) peripherals. It also ensures a seamless and efficient operation even when several highspeed peripherals work simultaneously.

Another multi-AHB bus matrix interconnects two masters (previous AHB bus matrix slave port and LPDMA1) and all slaves that are functional in Stop 2 modes (SRAM4 and AHB/APB peripherals functional in Stop 2 mode).

### 3.16 System configuration controller (SYSCFG)

The STM32U585xx devices feature a set of configuration registers. The main purposes of the system configuration controller are the following:

- Managing robustness feature
- Configuring FPU interrupts
- Enabling/disabling the FMP high-drive mode of some I/Os and voltage booster for I/Os analog switches
- Managing the I/O compensation cell
- Configuring register security access


### 3.17 General purpose direct memory access controller (GPDMA)

The general purpose direct memory access (GPDMA) controller is a bus master and system peripheral.

The GPDMA is used to perform programmable data transfers between memory-mapped peripherals and/or memories via linked-lists, upon the control of an off-loaded CPU.
The GPDMA main features are:

- Dual bidirectional AHB master
- Memory-mapped data transfers from a source to a destination:
- Peripheral-to-memory
- Memory-to-peripheral
- Memory-to-memory
- Peripheral-to-peripheral
- Autonomous data transfers during Sleep and Stop modes
- Transfers arbitration based on a four-grade programmed priority at a channel level:
- One high-priority traffic class, for time-sensitive channels (queue 3)
- Three low-priority traffic classes, with a weighted round-robin allocation for non time-sensitive channels (queues $0,1,2$ )- Per channel event generation, on any of the following events: transfer complete or half transfer complete or data transfer error or user setting error, and/or update linked-list item error or completed suspension
- Per channel interrupt generation, with separately programmed interrupt enable per event
- 16 concurrent DMA channels:
- Per channel FIFO for queuing source and destination transfers
- Intrachannel DMA transfers chaining via programmable linked-list into memory, supporting two execution modes: run-to-completion and link step mode
- Intrachannel and interchannel DMA transfers chaining via programmable DMA input triggers connection to DMA task completion events
- Per linked-list item within a channel:
- Separately programmed source and destination transfers
- Programmable data handling between source and destination: byte-based reordering, packing or unpacking, padding or truncation, sign extension and left/right realignment
- Programmable number of data bytes to be transferred from the source, defining the block level
- 12 channels with linear source and destination addressing: either fixed or contiguously incremented addressing, programmed at a block level, between successive single transfers
- Four channels with 2D source and destination addressing: programmable signed address offsets between successive burst transfers (noncontiguous addressing within a block, combined with programmable signed address offsets between successive blocks, at a second 2D/repeated block level)
- Support for scatter-gather (multibuffer transfers), data interleaving and deinterleaving via 2D addressing
- Programmable DMA request and trigger selection
- Programmable DMA half-transfer and transfer complete events generation
- Pointer to the next linked-list item and its data structure in memory, with automatic update of the DMA linked-list control registers
- Debug:
- Channel suspend and resume support
- Channel status reporting including FIFO level and event flags
- TrustZone support:
- Support for secure and nonsecure DMA transfers, independently at a first channel level, and independently at a source/destination and link sublevels
- Secure and nonsecure interrupts reporting, resulting from any of the respectively secure and nonsecure channels
- TrustZone-aware AHB slave port, protecting any DMA secure resource (register, register field) from a nonsecure access
- Privileged/unprivileged support:
- Support for privileged and unprivileged DMA transfers, independently at channel level
- Privileged-aware AHB slave portTable 11. GPDMA1 channels implementation and usage

| Channel <br> $\mathbf{x}$ | Hardware parameters |  | Features |
| :--: | :--: | :--: | :--: |
|  | dma_fifo_ <br> size[x] | dma_ <br> addressing[x] |  |
| $x=0$ to 11 | 2 | 0 | Channel $x(x=0$ to 11) is implemented with: <br> - a FIFO of 8 bytes, 2 words <br> - fixed/contiguously incremented addressing <br> These channels may be also used for GPDMA transfers, between an APB <br> or AHB peripheral and SRAM. |
| $x=12$ to <br> 15 | 4 | 1 | Channel $x(x=12$ to 15) is implemented with: <br> - a FIFO of 32 bytes, 8 words <br> - 2D addressing <br> These channels may be also used for GPDMA transfers, between <br> a demanding AHB peripheral and SRAM, or for transfers from/to external <br> memories. |

Table 12. GPDMA1 autonomous mode and wake-up in low-power modes

| Feature | Low-power modes |
| :-- | :-- |
| Autonomous mode and wake-up | GPDMA1 in Sleep, Stop 0 and Stop 1 modes |

# 3.18 Low-power direct memory access controller (LPDMA) 

The LPDMA controller is a bus master and system peripheral. The LPDMA is used to perform programmable data transfers between memory-mapped peripherals and/or memories via linked-lists, upon the control of an off-loaded CPU.

The LPDMA main features are:

- Single bidirectional AHB master
- Memory-mapped data transfers from a source to a destination:
- Peripheral-to-memory
- Memory-to-peripheral
- Memory-to-memory
- Peripheral-to-peripheral
- Autonomous data transfers during Sleep and Stop modes
- Transfers arbitration based on a 4-grade programmed priority at channel level:
- One high-priority traffic class, for time-sensitive channels (queue 3)
- Three low-priority traffic classes, with a weighted round-robin allocation for non time-sensitive channels (queues $0,1,2$ )
- Per channel event generation, on any of the following events: transfer complete, or half-transfer complete, or data transfer error, or user setting error, and/or update linked-list item error, or completed suspension
- Per channel interrupt generation, with separately programmed interrupt enable per event- Four concurrent DMA channels:
- Intrachannel DMA transfers chaining via programmable linked-list into memory, supporting two execution modes: run-to-completion and link step mode
- Intrachannel and interchannel DMA transfers chaining via programmable DMA input triggers connection to DMA task completion events
- Per linked-list item within a channel:
- Separately programmed source and destination transfers
- Programmable data handling between source and destination: byte-based padding or truncation, sign extension and left/right realignment
- Programmable number of data bytes to be transferred from the source, defining the block level
- Linear source and destination addressing: either fixed or contiguously incremented addressing, programmed at a block level, between successive single transfers
- Programmable DMA request and trigger selection
- Programmable DMA half-transfer and transfer complete events generation
- Pointer to the next linked-list item and its data structure in memory, with automatic update of the DMA linked-list control registers
- Debug:
- Channel suspend and resume support
- Channel status reporting and event flags
- TrustZone support
- Support for secure and nonsecure DMA transfers, independently at a first channel level, and independently at a source/destination and link sublevels
- Secure and nonsecure interrupts reporting, resulting from any of the respectively secure and nonsecure channels
- TrustZone-aware AHB slave port, protecting any DMA secure resource (register, register field) from a nonsecure access
- Privileged/unprivileged support:
- Support for privileged and unprivileged DMA transfers, independently at channel level
- Privileged-aware AHB slave port

Table 13. LPDMA1 channels implementation and usage

| Channel <br> $\mathbf{x}$ | Hardware parameters |  | Features |
| :--: | :--: | :--: | :--: |
|  | dma_fifo_ <br> size $[\mathrm{x}]$ | dma_ <br> addressing $[\mathrm{x}]$ |  |
| $x=0$ to 3 | 0 | 0 | Channel $x(x=0$ to 3$)$ is implemented with: <br> - no FIFO. Only a single source transfer cell is internally registered. <br> - fixed/contiguously incremented addressing |Table 14. LPDMA1 autonomous mode and wake-up in low-power modes

| Feature | Low-power modes |
| :-- | :-- |
| Autonomous mode and wake-up | LPDMA1 in Sleep, Stop 0, Stop 1 and Stop 2 modes |

# 3.19 Chrom-ART Accelerator controller (DMA2D) 

The Chrom-ART Accelerator (DMA2D) is a specialized DMA dedicated to image manipulation. It can perform the following operations:

- Filling a part or the whole of a destination image with a specific color
- Copying a part or the whole of a source image into a part or the whole of a destination image
- Copying a part or the whole of a source image into a part or the whole of a destination image with a pixel format conversion
- Blending a part and/or two complete source images with different pixel format and copy the result into a part or the whole of a destination image with a different color format.
All the classical color coding schemes are supported from 4-bit up to 32-bit per pixel with indexed or direct color mode. The DMA2D has its own dedicated memories for CLUTs (color look-up tables).

The main DMA2D features are:

- Single AHB master bus architecture
- AHB slave programming interface supporting 8/16/32-bit accesses (except for CLUT accesses that are 32-bit)
- User programmable working area size
- User programmable offset for sources and destination areas expressed in pixels or bytes expressed in pixels or bytes
- User programmable sources and destination addresses on the whole memory space
- Up to two sources with blending operation
- Alpha value can be modified (source value, fixed value, or modulated value)
- User programmable source and destination color format
- Up to 11 color formats supported from 4-bit up to 32-bit per pixel with indirect or direct color coding
- Two internal memories for CLUT storage in indirect color mode
- Automatic CLUT loading or CLUT programming via the CPU
- User programmable CLUT size
- Internal timer to control AHB bandwidth
- Six operating modes: register-to-memory, memory-to-memory, memory-to-memory with pixel format conversion, memory-to-memory with pixel format conversion and blending, memory-to memory with pixel format conversion, blending and fixed color foreground, and memory-to memory with pixel format conversion, blending and fixed color background
- Area filling with a fixed color
- Copy from an area to another
- Copy with pixel format conversion between source and destination images
- Copy from two sources with independent color format and blending- Output buffer byte swapping to support refresh of displays through parallel interface
- Abort and suspend of DMA2D operations
- Watermark interrupt on a user programmable destination line
- Interrupt generation on bus error or access conflict
- Interrupt generation on process completion


# 3.20 Interrupts and events 

### 3.20.1 Nested vectored interrupt controller (NVIC)

The devices embed an NVIC that is able to manage 16 priority levels and to handle up to 125 maskable interrupt channels plus the 16 interrupt lines of the Cortex-M33.

The NVIC benefits are the following:

- closely coupled NVIC giving low-latency interrupt processing
- interrupt entry vector table address passed directly to the core
- early processing of interrupts
- processing of late arriving higher priority interrupts
- support for tail chaining
- processor state automatically saved
- interrupt entry restored on interrupt exit with no instruction overhead
- TrustZone support: NVIC registers banked across secure and nonsecure states

The NVIC hardware block provides flexible interrupt management features with minimal interrupt latency.

### 3.20.2 Extended interrupt/event controller (EXTI)

The EXTI manages the individual CPU and system wake-up through configurable event inputs. It provides wake-up requests to the power control, and generates an interrupt request to the CPU NVIC and events to the CPU event input. For the CPU, an additional event generation block (EVG) is needed to generate the CPU event signal.

The EXTI wake-up requests allow the system to be woken up from Stop modes.
The interrupt request and event request generation can also be used in Run modes. The EXTI also includes the EXTI multiplexer I/O port selection.

The EXTI main features are the following:

- All event inputs allowed to wake up the system
- Configurable events (signals from I/Os or peripherals able to generate a pulse)
- Selectable active trigger edge
- Interrupt pending status register bit independent for the rising and falling edge
- Individual interrupt and event generation mask, used for conditioning the CPU wake-up, interrupt, and event generation
- Software trigger possibility- TrustZone secure events
- The access to control and configuration bits of secure input events can be made secure
- EXTI I/O port selection


# 3.21 Cyclic redundancy check calculation unit (CRC) 

The CRC is used to get a CRC code using a configurable generator with polynomial value and size.

Among other applications, the CRC-based techniques are used to verify data transmission or storage integrity. In the scope of the EN/IEC 60335-1 standard, they offer a mean to verify the flash memory integrity.

The CRC calculation unit helps to compute a signature of the software during runtime that can be ulteriorly compared with a reference signature generated at link-time and that can be stored at a given memory location.

### 3.22 CORDIC coprocessor (CORDIC)

The CORDIC coprocessor provides hardware acceleration of certain mathematical functions, notably trigonometric, commonly used in motor control, metering, signal processing and many other applications. It speeds up the calculation of these functions compared to a software implementation, allowing a lower operating frequency, or freeing up processor cycles in order to perform other tasks.

The CORDIC main features are:

- 24-bit CORDIC rotation engine
- Circular and hyperbolic modes
- Rotation and vectoring modes
- Functions: sine, cosine, sinh, cosh, atan, atan2, atanh, modulus, square root, natural logarithm
- Programmable precision
- Low-latency AHB slave interface
- Results can be read as soon as ready without polling or interrupt
- DMA read and write channels
- Multiple register read/write by DMA


### 3.23 Filter math accelerator (FMAC)

The FMAC performs arithmetic operations on vectors. It comprises a MAC (multiplier/accumulator) unit, together with address generation logic that allows it to index vector elements held in local memory.

The unit includes support for circular buffers on input and output that allows digital filters to be implemented. Both finite and infinite impulse response filters can be done.The unit allows frequent or lengthy filtering operations to be offloaded from the CPU, freeing up the processor for other tasks. In many cases it can accelerate such calculations compared to a software implementation, resulting in a speed-up of time critical tasks.

The FMAC main features are:

- $16 \times 16$-bit multiplier
- $24+2$-bit accumulator with addition and subtraction
- 16-bit input and output data
- $256 \times 16$-bit local memory
- Up to three areas can be defined in memory for data buffers (two inputs, one output), defined by programmable base address pointers and associated size registers
- Input and output buffers can be circular
- Filter functions: FIR, IIR (direct form 1)
- Vector functions: dot product, convolution, correlation
- AHB slave interface
- DMA read and write data channels


# 3.24 Flexible static memory controller (FSMC) 

The FSMC includes two memory controllers:

- NOR/PSRAM memory controller
- NAND/memory controller

The FSMC is also named flexible memory controller (FMC).
The main features of the FSMC are the following:

- Interface with static-memory mapped devices including:
- Static random access memory (SRAM)
- NOR flash memory/OneNAND flash memory
- PSRAM (four memory banks)
- NAND flash memory with ECC hardware to check up to 8 Kbytes of data
- Ferroelectric RAM (FRAM)
- 8-,16-bit data bus width
- Independent chip select control for each memory bank
- Independent configuration for each memory bank
- Write FIFO


### 3.24.1 LCD parallel interface

The FSMC can be configured to interface seamlessly with most graphic LCD controllers. It supports the Intel ${ }^{\circledR} 8080$ and Motorola ${ }^{\circledR} 6800$ modes, and is flexible enough to adapt to specific LCD interfaces.

This LCD parallel interface capability makes it easy to build cost effective graphic applications using LCD modules with embedded controllers or high-performance solutions using external controllers with dedicated acceleration.# 3.24.2 FSMC TrustZone security 

When the TrustZone security is enabled, the whole FSMC banks are secure after reset. Nonsecure area can be configured using the TZSC MPCWMx controller:

- FSMC NOR/PSRAM bank:
- Up to two nonsecure areas can be configured thought the TZSC MPCWM2 controller with a 64 -Kbyte granularity
- FSMC NAND bank:
- Can be either configured as fully secure or fully nonsecure using the TZSC MPCWM3 controller

The FSMC registers can be configured as secure through the TZSC controller.

### 3.25 Octo-SPI interface (OCTOSPI)

The devices embed two OCTOSPIs. The OCTOSPI supports most external serial memories such as serial PSRAMs, serial NAND and serial NOR flash memories, HyperRAMs ${ }^{\text {TM }}$ and HyperFlash ${ }^{\text {TM }}$ memories, with the following functional modes:

- Indirect mode: all the operations are performed using the OCTOSPI registers.
- Status-polling mode: the external memory status register is periodically read and an interrupt can be generated in case of flag setting.
- Memory-mapped mode: the external memory is memory mapped and is seen by the system as if it were an internal memory supporting read and write operation.
The OCTOSPI supports the following protocols with associated frame formats:
- the standard frame format with the command, address, alternate byte, dummy cycles, and data phase
- the HyperBus ${ }^{\text {TM }}$ frame format

The OCTOSPI offers the following features:

- Three functional modes: Indirect, Status-polling, and Memory-mapped
- Read and write support in Memory-mapped mode
- Supports for single, dual, quad, and octal communication
- Dual-quad mode, where eight bits can be sent/received simultaneously by accessing two quad memories in parallel.
- SDR (single-data rate) and DTR (double-transfer rate) support
- Data strobe support
- Fully programmable opcode
- Fully programmable frame format
- HyperBus support
- Integrated FIFO for reception and transmission
- 8-, 16-, and 32-bit data accesses allowed
- DMA channel for Indirect mode operations
- Interrupt generation on FIFO threshold, timeout, operation complete, and access error# 3.25.1 OCTOSPI TrustZone security 

When the TrustZone security is enabled, the whole OCTOSPI bank is secure after reset.
Up to two nonsecure areas can be configured thought the TZSC MPCWM1 and MPCWM5 controllers with a granularity of 64 Kbytes.

The OCTOSPI registers can be configured as secure through the TZSC controller.

### 3.26 OCTOSPI I/O manager (OCTOSPIM)

The OCTOSPI I/O manager is a low-level interface enabling:

- efficient OCTOSPI pin assignment with a full I/O matrix (before alternate function map)
- multiplex of Single-, Dual-, Quad-, Octal-SPI interfaces over the same bus and hence support memories embedded in a multichip package
The OCTOSPIM main features are:
- Supports up to two single-, dual-, quad-, octal-SPI interfaces
- Supports up to two ports for pin assignment
- Fully programmable I/O matrix for pin assignment by function (data/control/clock)


### 3.27 Delay block (DLYB)

The delay block (DLYB) is used to generate an output clock that is dephased from the input clock. The phase of the output clock must be programmed by the user application. The output clock is then used to clock the data received by another peripheral such as a SDMMC or Octo-SPI interface. The delay is voltage and temperature dependent, that may require the application to reconfigure and recenter the output clock phase with the received data.

The delay block main features are:

- Input clock frequency ranging from 25 to 160 MHz
- Up to 12 oversampling phases


### 3.28 Analog-to-digital converter (ADC1 and ADC4)

The devices embed two successive approximation analog-to-digital converters.
Table 15. ADC features

| ADC modes/features ${ }^{(1)}$ | ADC1 | ADC4 |
| :-- | :--: | :--: |
| Resolution | 14 bits | 12 bits |
| Maximum sampling speed for maximum resolution | 2.5 Msps | 2.5 Msps |
| Hardware offset calibration | X | X |
| Hardware linearity calibration | X | - |
| Single-ended inputs | X | X |
| Differential inputs | X | - |Table 15. ADC features (continued)

| ADC modes/features ${ }^{(1)}$ | ADC1 | ADC4 |
| :-- | :--: | :--: |
| Injected channel conversion | X | - |
| Oversampling | up to x1024 | up to x256 |
| Data register | 32 bits | 16 bits |
| DMA support | X | X |
| Parallel data output to MDF | X | - |
| Autonomous mode | - | X |
| Offset compensation | X | - |
| Gain compensation | X | - |
| Number of analog watchdogs | 3 | 3 |
| Wake-up from Stop mode | - | $X^{(2)}$ |

1. $X=$ supported.
2. Wake-up supported from Stop 0, Stop 1 and Stop 2 modes.

# 3.28.1 Analog-to-digital converter 1 (ADC1) 

The ADC1 is a 14-bit ADC successive approximation analog-to-digital converter.
This ADC has up to 20 multiplexed channels. A/D conversion of the various channels can be performed in Single, Continuous, Scan or Discontinuous mode. The result of the ADC is stored in a left-aligned or right-aligned 32-bit data register.

This ADC is mapped on the AHB bus to allow fast data handling. The analog watchdog features allow the application to detect if the input voltage goes outside the user-defined high or low thresholds.

A built-in hardware over sampler allows analog performances to be improved while off-loading the related computational burden from the CPU.

An efficient low-power mode is implemented to allow very low consumption at low frequency.
The ADC1 main features are:

- High-performance features
- 14-, 12-, 10-, or 8-bit configurable resolution
- A/D conversion time independent from the AHB bus clock frequency
- Faster conversion time by lowering resolution
- Management of single-ended or differential inputs (programmable per channels)
- Fast data handling thanks to the AHB slave bus interface
- Self-calibration (both offset and linearity)
- Channel-wise programmable sampling time
- Flexible sampling time control
- Up to four injected channels (analog inputs assignment to regular or injected channels is fully configurable)
- Fast context switching thanks to the hardware assistant that prepares the context of the injected channels- Data alignment with in-built data coherency
- Data can be managed by GPDMA for regular channel conversions with FIFO
- Data can be routed to MDF for post processing
- Four dedicated data registers for the injected channels
- Oversampler
- 32-bit data register
- Oversampling ratio adjustable from 2 to 1024
- Programmable data right and left shift
- Data preconditioning
- Gain compensation
- Offset compensation
- Low-power features
- Speed adaptive low-power mode to reduce ADC consumption when operating at low frequency
- Slow bus frequency application while keeping optimum ADC performance
- Automatic control to avoid ADC overrun in low AHB bus clock frequency application (autodelayed mode)
- ADC features an external analog input channel:
- Up to 17 channels from dedicated GPIO pads
- Three additional internal dedicated channels:
- One channel for internal reference voltage (VREFINT)
- One channel for internal temperature sensor (VSENSE)
- One channel for VBAT monitoring channel (VBAT/4)
- Start-of-conversion can be initiated:
- by software for both regular and injected conversions
- by hardware triggers with configurable polarity (internal timers events or GPIO input events) for both regular and injected conversions
- Conversion modes
- Single mode: the ADC converts a single channel. The conversion is triggered by a special event.
- Scan mode: the ADC scans and converts a sequence of channels.
- Continuous mode: the ADC converts continuously selected inputs.
- Discontinuous mode: the ADC converts a subset of the conversion sequence.
- Interrupt generation when the ADC is ready, at end of sampling, end of conversion (regular or injected), end of sequence conversion (regular or injected), analog watchdog 1, 2 or 3 or when an overrun event occurs
- Three analog watchdogs
- Filtering to ignore out-of-range data
- ADC input range: $\mathrm{V}_{\mathrm{SSA}}<\mathrm{VIN}<\mathrm{VREF}+$

Note: The ADC1 analog block clock frequency must be between 5 MHz and 55 MHz .# 3.28.2 Analog-to-digital converter 4 (ADC4) 

The 12-bit ADC4 is a successive approximation analog-to-digital converter. It has up to 25 multiplexed channels allowing it to measure signals from 19 external and six internal sources. A/D conversion of the various channels can be performed in Single, Continuous, Scan or Discontinuous mode. The result of the ADC is stored in a left-aligned or right-aligned 16-bit data register.

The analog watchdog feature allows the application to detect if the input voltage goes outside the user-defined higher or lower thresholds.

An efficient low-power mode is implemented to allow very low consumption at low frequency. The ADC4 is autonomous in low-power modes down to Stop 2 mode.

A built-in hardware oversampler allows analog performances to be improved while off-loading the related computational burden from the CPU.

The ADC4 main features are:

- High performance
- 12-, 10-, 8- or, 6-bit configurable resolution
- A/D conversion time: $0.4 \mu \mathrm{~s}$ for 12-bit resolution ( 2.5 MHz ), faster conversion times obtained by lowering resolution
- Self-calibration
- Programmable sampling time
- Data alignment with built-in data coherency
- DMA support
- Low-power
- HCLK frequency reduced for low-power operation while still keeping optimum ADC performance
- Wait mode: ADC overrun prevented in applications with low frequency HCLK
- Auto-off mode: ADC automatically powered off except during the active conversion phase, dramatically reducing the ADC power consumption
- Autonomous mode: In low-power modes down to Stop 2 mode, the ADC4 is automatically switched on when a trigger occurs to start conversion, and it is automatically switched off after conversion. Data are transferred in SRAM with DMA.
- ADC4 interrupts wake up the device from Stop 0, Stop 1, and Stop 2 modes.
- Analog input channels
- Up to 19 external analog inputs
- One channel for the internal temperature sensor ( $\mathrm{V}_{\text {SENSE }}$ )
- One channel for the internal reference voltage ( $\mathrm{V}_{\text {REFINT }}$ )
- One channel for the internal digital core voltage ( $\mathrm{V}_{\text {CORE }}$ )
- One channel for monitoring the external VBAT power supply pin
- Connection to two DAC internal channels
- Start-of-conversion can be initiated:
- By software
- By hardware triggers with configurable polarity (timer events or GPIO input events)- Conversion modes
- Conversion of a single channel or scan of a sequence of channels
- Selected inputs converted once per trigger in Single mode
- Selected inputs converted continuously in Continuous mode
- Discontinuous mode
- Interrupt generation at the end of sampling, end of conversion, end of sequence conversion, and in case of analog watchdog or overrun events, with wake-up from Stop capability
- Analog watchdog
- Oversampler
- 16-bit data register
- Oversampling ratio adjustable from 2 to 256
- Programmable data shift up to 8 bits
- ADC supply requirements: 1.62 to 3.6 V
- ADC input range: $\mathrm{V}_{\mathrm{SSA}}<\mathrm{V}_{\mathrm{IN}}<\mathrm{V}_{\mathrm{REF}+}$

Note: The ADC4 analog block clock frequency must be between 140 kHz and 55 MHz .

# 3.28.3 Temperature sensor 

The temperature sensor generates a voltage $\mathrm{V}_{\text {SENSE }}$ that varies linearly with temperature. The temperature sensor is internally connected to ADC1 and ADC4 input channel that is used to convert the sensor output voltage into a digital value.

The sensor provides good linearity but it must be calibrated to obtain a good accuracy of the temperature measurement. As the offset of the temperature sensor varies from chip to chip due to process variation, the uncalibrated internal temperature sensor is suitable for applications that detect temperature changes only.

To improve the accuracy of the temperature sensor measurement, each device is individually factory-calibrated by ST. The temperature sensor factory calibration data are stored by STMicroelectronics in the system memory area, accessible in read-only mode.

Table 16. Temperature sensor calibration values

| Calibration <br> value name | Description | Memory address |
| :--: | :-- | :-- |
| TS_CAL1 | Temperature sensor 14-bit raw data acquired by ADC1 <br> at $30^{\circ} \mathrm{C}\left( \pm 5^{\circ} \mathrm{C}\right), \mathrm{V}_{\mathrm{DDA}}=\mathrm{V}_{\mathrm{REF}+}=3.0 \mathrm{~V}( \pm 10 \mathrm{mV})$ | 0x0BFA 0710 - 0x0BFA 0711 |
| TS_CAL2 | Temperature sensor 14-bit raw data acquired by ADC1 <br> at $130^{\circ} \mathrm{C}\left( \pm 5^{\circ} \mathrm{C}\right), \mathrm{V}_{\mathrm{DDA}}=\mathrm{V}_{\mathrm{REF}+}=3.0 \mathrm{~V}( \pm 10 \mathrm{mV})$ | 0x0BFA 0742 - 0x0BFA 0743 |# 3.28.4 Internal voltage reference (VREFINT) 

The VREFINT provides a stable (bandgap) voltage output for the ADC and the comparators. The VREFINT is internally connected to ADC1 and ADC4 input channels.

The precise voltage of VREFINT is individually measured for each part by STMicroelectronics during production test and stored in the system memory area. It is accessible in read-only mode.

Table 17. Internal voltage reference calibration values

| Calibration value name | Description | Memory address |
| :--: | :-- | :-- |
| VREFINT_CAL | 14-bit raw data acquired by ADC1 <br> at $30^{\circ} \mathrm{C}\left( \pm 5^{\circ} \mathrm{C}\right), \mathrm{V}_{\mathrm{DDA}}=\mathrm{V}_{\mathrm{REF}+}=3.0 \mathrm{~V}( \pm 10 \mathrm{mV})$ | 0x0BFA 07A5 - 0x0BFA 07A6 |

### 3.28.5 $\quad \mathrm{V}_{\mathrm{BAT}}$ battery voltage monitoring

This embedded hardware enables the application to measure the $\mathrm{V}_{\mathrm{BAT}}$ battery voltage using ADC1 or ADC4 input channel. As the $\mathrm{V}_{\mathrm{BAT}}$ voltage may be higher than the $\mathrm{V}_{\mathrm{DDA}}$, and thus outside the ADC input range, the VBAT pin is internally connected to a bridge divider by four. As a consequence, the converted digital value is a quarter of the $\mathrm{V}_{\mathrm{BAT}}$ voltage.

### 3.29 Digital-to-analog converter (DAC)

The DAC module is a 12-bit, voltage output digital-to-analog converter. The DAC can be configured in 8- or 12-bit mode and may be used with the DMA controller. In 12-bit mode, the data may be left- or right-aligned.

The DAC features two output channels, each with its own converter. In dual DAC channel mode, conversions can be done independently or simultaneously when both channels are grouped together for synchronous update operations. An input reference pin, VREF+ (shared with others analog peripherals) is available for better resolution. An internal reference can also be set on the same input.

The DAC_OUTx pin can be used as general-purpose input/output (GPIO) when the DAC output is disconnected from output pad and connected to on chip peripheral. The DAC output buffer can be optionally enabled to allow a high drive output current. An individual calibration can be applied on each DAC output channel. The DAC output channels support a low-power mode, the sample and hold mode.

The digital interface supports the following features:

- One DAC interface, maximum two output channels
- Left or right data alignment in 12-bit mode
- Synchronized update capability
- Noise-wave and triangular-wave generation
- Sawtooth wave generation
- Dual DAC channel for independent or simultaneous conversions
- DMA capability for each channel including DMA underrun error detection
- Double data DMA capability to reduce the bus activity
- External triggers for conversion
- DAC output channel buffered/unbuffered modes- Buffer offset calibration
- Each DAC output can be disconnected from the DAC_OUTx output pin
- DAC output connection to on chip peripherals
- Sample and hold mode for low-power operation in Stop mode. The DAC voltage can be changed autonomously with the DMA while the device is in Stop mode.
- Autonomous mode to reduce the power consumption for the system
- Voltage reference input


# 3.30 Voltage reference buffer (VREFBUF) 

The devices embed a voltage reference buffer that can be used as voltage reference for ADCs, DACs and also as voltage reference for external components through the VREF + pin.

Figure 6. VREFBUF block diagram
![img-9.jpeg](img-9.jpeg)

The internal voltage reference buffer supports four voltages: $1.5 \mathrm{~V}, 1.8 \mathrm{~V}, 2.048 \mathrm{~V}$, and 2.5 V .
An external voltage reference can be provided through the VREF + pin when the internal voltage reference buffer is off.

The VREF + pin is double-bonded with VDDA on some packages. In these packages, the internal voltage reference buffer is not available.

### 3.31 Comparators (COMP)

The devices embed two rail-to-rail comparators with programmable reference voltage (internal or external), hysteresis and speed (low speed for low power) and with selectable output polarity.

The reference voltage can be one of the following:

- External I/O
- DAC output channels
- Internal reference voltage or submultiple (1/4, 1/2, 3/4)All comparators can wake up from Stop 0, Stop 1 and Stop 2 modes, generate interrupts and breaks for the timers and can also be combined into a window comparator.

# 3.32 Operational amplifiers (OPAMP) 

The devices embed two operational amplifiers with external or internal follower routing and PGA capability.
The operational amplifier features:

- Low-input bias current
- Low-offset voltage
- Low-power mode
- Rail-to-rail input


### 3.33 Multifunction digital filter (MDF) and audio digital filter (ADF)

The table below lists the set of features implemented into the MDF and the ADF.
Table 18. MDF features

| MDF modes/features $\left.{ }^{(1}\right)$ | ADF1 | MDF1 |
| :-- | :--: | :--: |
| Number of filters (DFLTx) and serial interfaces (SITFx) | 1 | 6 |
| ADF_CKI0 / MDF_CKly connected to pins | - | X |
| Sound activity detection (SAD) | X | - |
| RXFIFO depth (number of 24-bit words) | 4 | 4 |
| ADC connected to ADCITF1 | - | ADC1 |
| ADC connected to ADCITF2 | - | - |
| Motor dedicated features (SCD, OLD, OEC, INT, snapshot, break) | - | X |
| Main path with CIC4, CIC5 | X | X |
| Main path with CIC1,2, 3 or FastSinc | - | X |
| RSFLT, HPF, SAT, SCALE, DLY, Discard functions | X | X |
| Autonomous in Stop mode | $X^{(2)}$ | $X^{(3)}$ |

1. $X=$ supported.
2. Stop 0 , Stop 1 and Stop 2 modes only.
3. Stop 0 and Stop 1 modes only.

### 3.33.1 Multifunction digital filter (MDF)

The MDF is a high-performance module dedicated to the connection of external sigma-delta $(\Sigma \Delta)$ modulators. It is mainly targeted for the following applications:

- audio capture signals
- motor control
- metering

The MDF features six digital serial interfaces (SITFx) and digital filters (DFLTx) with flexible digital processing options to offer up to 24-bit final resolution.

The DFLTx of the MDF also include the filters of the ADF (audio digital filter).The MDF can receive, via its serial interfaces, streams coming from various digital sensors.
The MDF supports the following standards allowing the connection of various $\Sigma \Delta$ modulator sensors:

- SPI interface
- Manchester coded 1-wire interface
- PDM interface

A flexible BSMX (bitstream matrix) allows the connection of any incoming bitstream to any filter.

The MDF converts an input data stream into clean decimated digital data words. This conversion is done thanks to low-pass digital filters and decimation blocks. In addition it is possible to insert a high-pass filter or DC offset correction block.

The conversion speed and resolution are adjustable according to configurable parameters for digital processing: filter type, filter order, decimation ratio, integrator length. The maximum output data resolution is up to 24 bits. There are two conversion modes: single conversion and continuous modes. The data can be automatically stored in a system RAM buffer through DMA, thus reducing the software overhead.

A flexible trigger interface can be used to control the conversion start. This timing control can trigger simultaneous conversions or insert a programmable delay between conversions.
The MDF features an OLD (out-off limit detectors) function. There is one OLD for each digital filter chain. Independent programmable thresholds are available for each OLD, making it very suitable for overcurrent detection.

An SCD (short circuit detector) is also available for every selected bitstream. The SCD is able to detect a short-circuit condition with a very short latency. Independent programmable thresholds are offered in order to define the short circuit condition.

All the digital processing is performed using only the kernel clock. The MDF requests the bus interface clock (AHB clock) only when data must be transferred or when a specific event requests the attention of the system processor.

The MDF main features are:

- AHB interface
- Six serial digital inputs:
- configurable SPI interface to connect various digital sensors
- configurable Manchester coded interface support
- compatible with PDM interface to support digital microphones
- Two common clock input/output for $\Sigma \Delta$ modulators
- Flexible BSMX for connection between filters and digital inputs
- Two inputs to connect the internal ADCs
- Six flexible digital filter paths, including:
- A configurable CIC filter:
- Can be split into two CIC filters: high-resolution filter and out-off limit detector
- Can be configured in Sinc ${ }^{4}$ filter
- Can be configured in Sinc ${ }^{5}$ filter
- Adjustable decimation ratio
- A reshape filter to improve the out-off band rejection and in-band ripple- A high-pass filter to cancel the DC offset
- An offset error cancellation
- Gain control
- Saturation blocks
- An out-off limit detector
- Short-circuit detector
- Clock absence detector
- 16- or 24-bit signed output data resolution
- Continuous or single conversion
- Possibility to delay independently each bitstream
- Various trigger possibilities
- Break generation on out-of limit or short-circuit detector events
- Autonomous functionality in Stop modes
- DMA can be used to read the conversion data
- Interrupts services


# 3.33.2 Audio digital filter (ADF) 

The ADF is a high-performance module dedicated to the connection of external $\Sigma \Delta$ modulators. It is mainly targeted for the following applications:

- audio capture signals
- metering

The ADF features one digital serial interface (SITFO) and one digital filter (DFLTO) with flexible digital processing options to offer up to 24-bit final resolution.
The DLFTO of the ADF is a subset of the digital filters included into the MDF.
The ADF serial interface supports several standards allowing the connection of various $\Sigma \Delta$ modulator sensors:

- SPI interface
- Manchester coded 1-wire interface
- PDM interface

A flexible BSMX allows the connection of any incoming bitstream to any filter.
The ADF converts an input data stream into clean decimated digital data words. This conversion is done thanks to low-pass digital filters and decimation blocks. In addition it is possible to insert a high-pass filter or a DC offset correction block.

The conversion speed and resolution are adjustable according to configurable parameters for digital processing: filter type, filter order, decimation ratio. The maximum output data resolution is up to 24 bits. There are two conversion modes: single conversion and continuous modes. The data can be automatically stored in a system RAM buffer through DMA, thus reducing the software overhead.

A SAD (sound activity detector) is available for the detection of "speech-like" signals. The SAD is connected at the output of DFLTO. Several parameters can be programmed to adjust properly the SAD to the sound environment. The SAD can strongly reduce the power consumption by preventing the storage of samples into the system memory as long as the observed signal does not match the programmed criteria.A flexible trigger interface can be used to control the start of conversion of the ADF.
All the digital processing is performed using only the kernel clock. The ADF requests the bus interface clock (AHB clock) only when data must be transferred or when a specific event requests the attention of the system processor.
The ADF main features are:

- AHB interface
- One serial digital input:
- Configurable SPI interface to connect various digital sensors
- Configurable Manchester coded interface support
- Compatible with PDM interface to support digital microphones
- Two common clocks input/output for $\Sigma \Delta$ modulators
- Flexible BSMX for connection between filters and digital inputs
- One flexible digital filter path, including:
- A configurable CIC filter:
- Can be configured in Sinc ${ }^{4}$ filter
- Can be configured in Sinc ${ }^{5}$ filter
- Adjustable decimation ratio
- A reshape filter to improve the out-off band rejection and in-band ripple
- A high-pass filter to cancel the DC offset
- Gain control
- Saturation blocks
- Clock absence detector
- Sound activity detector
- 16- or 24-bit signed output data resolution
- Continuous or single conversion
- Possibility to delay independently each bitstream
- Various trigger possibilities
- Autonomous mode in Stop 0, Stop 1 and Stop 2 modes
- Wake-up from Stop with all interrupts
- DMA can be used to read the conversion data
- Interrupts services# 3.34 Digital camera interface (DCMI) 

The DCMI is a synchronous parallel interface able to receive a high-speed data flow from an external 8-, 10-, 12-, or 14-bit CMOS camera module. It supports different data formats: YCbCr4:2:2/RGB565 progressive video and compressed data (JPEG).
This interface is for use with black and white cameras, X24 and X5 cameras, and it is assumed that all preprocessing such as resizing is performed in the camera module.
The DCMI features are:

- 8-, 10-, 12-, or 14-bit parallel interface
- Embedded/external line and frame synchronization
- Continuous or snapshot mode
- Crop feature
- Supports the following data formats:
- 8/10/12/14-bit progressive video: either monochrome or raw Bayer
- YCbCr 4:2:2 progressive video
- RGB 565 progressive video
- Compressed data: JPEG


### 3.35 Parallel synchronous slave interface (PSSI)

The PSSI and the DCMI use the same circuitry. As a result, these two peripherals cannot be used at the same time: when using the PSSI, the DCMI registers cannot be accessed, and vice versa. In addition, the PSSI and the DCMI share the same alternate functions and the same interrupt vector.

The PSSI is a generic synchronous 8-/16-bit parallel data input/output slave interface. It enables the transmitter to send a data valid signal that indicates when the data is valid, and the receiver to output a flow control signal that indicates when it is ready to sample the data.

The PSSI peripheral main features are the following:

- Slave mode operation
- 8-bit or 16-bit parallel data input or output
- 4-word (16-byte) FIFO
- Data enable (PSSI_DE) alternate function input and ready (PSSI_RDY) alternate function output

When selected, these inputs can either enable the transmitter to indicate when the data is valid, or allow the receiver to indicate when it is ready to sample the data, or both.

### 3.36 Touch sensing controller (TSC)

The TSC provides a simple solution to add capacitive sensing functionality to any application. A capacitive sensing technology is able to detect finger presence near an electrode that is protected from direct touch by a dielectric (such as glass or plastic). The capacitive variation introduced by the finger (or any conductive object) is measured using a proven implementation based on a surface charge transfer acquisition principle.The TSC is fully supported by the STMTouch touch sensing firmware library that is free to use and allows touch sensing functionality to be implemented reliably in the end application.
The TSC main features are the following:

- Proven and robust surface charge transfer acquisition principle
- Supports up to 22 capacitive sensing channels
- Up to eight capacitive sensing channels can be acquired in parallel offering a very good response time
- Spread spectrum feature to improve system robustness in noisy environments
- Full hardware management of the charge transfer acquisition sequence
- Programmable charge transfer frequency
- Programmable sampling capacitor I/O pin
- Programmable channel I/O pin
- Programmable max count value to avoid long acquisition when a channel is faulty
- Dedicated end of acquisition and max count error flags with interrupt capability
- One sampling capacitor for up to three capacitive sensing channels to reduce the system components
- Compatible with proximity, touchkey, linear and rotary touch sensor implementation
- Designed to operate with STMTouch touch sensing firmware library

Note: The number of capacitive sensing channels is dependent on the size of the packages and subject to I/O availability.

# 3.37 True random number generator (RNG) 

The RNG is a true random number generator that provides full entropy outputs to the application as 32-bit samples. It is composed of a live entropy source (analog) and an internal conditioning component.
The RNG is a NIST SP 800-90B compliant entropy source that can be used to construct a nondeterministic random bit generator (NDRBG).
The true random generator:

- delivers 32-bit true random numbers, produced by an analog entropy source conditioned by a NIST SP800-90B approved conditioning stage
- can be used as entropy source to construct a nondeterministic random bit generator (NDRBG)
- produces four 32-bit random samples every 412 AHB clock cycles if $\mathrm{f}_{\text {AHB }}<77 \mathrm{MHz}$ (256 RNG clock cycles otherwise)
- embeds startup and NIST SP800-90B approved continuous health tests (repetition count and adaptive proportion tests), associated with specific error management
- can be disabled to reduce power consumption, or enabled with an automatic low-power mode (default configuration)
- has an AMBA AHB slave peripheral, accessible through 32-bit word single accesses only (else an AHB bus error is generated, and the write accesses are ignored)# 3.38 Secure advanced encryption standard hardware accelerator (SAES) <br> and encryption standard hardware accelerator (AES) 

The devices embed two AES accelerators: SAES and AES. The SAES with hardware unique key embeds protection against differential power analysis (DPA) and related side channel attacks. The SAES can share its current key register information with the faster AES using a dedicated hardware bus.

The SAES and the AES can be used to both encrypt and decrypt data using the AES algorithm. It is a fully compliant implementation of the advanced encryption standard (AES) as defined by Federal Information Processing Standards Publication (FIPS PUB 197, Nov 2001).

Multiple chaining modes are supported for key sizes of 128 or 256 bits. ECB and CBC chaining is supported by both SAES and AES, while CTR, CCM, GCM and GMAC chaining is only supported by the AES.

SAES and AES support DMA single transfers for incoming and outgoing data (two DMA channels required).

The SAES supports the selection of all the following key sources, while the AES support only the first:

- 256-bit software key, written by the application in the key registers (write only)
- 256-bit derived hardware unique key (DHUK), computed inside the SAES engine from a nonvolatile OTP based root hardware unique key (RHUK)
- 256-bit boot hardware key (BHK), stored in tamper-resistant secure backup registers, written by a secure code during boot. Once written, this key cannot be read or write by any application until the next product reset.
- XOR of DHUK (provisioned chip secret) and BHK (software secret)

DHUK, BHK, and their XOR are not visible by any software (even secure).
Note: 128-bit key size can also be selected.
BHK key is cleared in case of tamper or RDP regression.
When the SAES is secure (respectively nonsecure), DHUK secure (respectively nonsecure) is used.

The SAES peripheral is connected by hardware to the true random number generator RNG (for side-channel resistance).
The SAES and AES peripherals support:

- Compliant implementation of standard NIST Special Publication 197, Advanced Encryption Standard (AES) and Special Publication 800-38A, Recommendation for Block Cipher Modes of Operation
- 128-bit data block processing
- Support for cipher keys length of 128-bit and 256-bit
- Encryption and decryption with multiple chaining modes:
- Electronic codebook (ECB) mode
- Cipher block chaining (CBC) mode- Additional chaining modes supported by AES only:
- Counter (CTR) mode
- Galois counter mode (GCM)
- Galois message authentication code (GMAC) mode
- Counter with CBC-MAC (CCM) mode
- 528 or 743 clock cycle latency in ECB encryption mode for SAES processing one 128-bit block of data with, respectively, 128-bit or 256-bit key
- 51 or 75 clock cycle latency in ECB encryption mode for AES processing one 128-bit block of data with, respectively, 128-bit or 256-bit key
- Integrated round key scheduler to compute the last round key for AES ECB/CBC decryption
- 256-bit register for storing the cryptographic key (four 32-bit registers), with key atomicity enforcement
- 128-bit registers for storing initialization vectors (four 32-bit registers)
- One 32-bit input buffer and one 32-bit output buffer
- Automatic data flow control with support of single-transfer direct memory access (DMA) using two channels (one for incoming data, one for processed data)
- Data swapping logic to support 1-, 8-, 16-, or 32-bit data
- Possibility for software to suspend a message if the SAES/AES needs to process another message with a higher priority (suspend/resume operation)
- SAES additional features:
- Security context enforcement for keys
- Hardware secret key encryption/decryption (wrapped key mode) and sharing with faster AES peripheral (Shared key mode)
- Protection against differential power analysis (DPA) and related side-channel attacks
- Optional hardware loading of two hardware secret keys (BHK, DHUK) that can be XORed together

On top of standard AES encryption and decryption with a key loaded by software, SAES peripheral allows the following advanced use cases:

- Allow or deny the sharing of a key between a secure and a nonsecure application, enforced by hardware
- Encrypt once a key using side-channel resistant AES, then share it to a faster AES engine by decrypting it (Shared key mode)
- On-chip encrypted storage using chip-unique secret DHUK
- Transport key generation by encrypting the device public unique ID with the application secret BHK
- Binding of device secure storage keys, using the silicon unique secret key (DHUK) XORed with the boot secret key (BHK). If BHK is lost, the whole device secure storage is lost.

Note: Encrypted storage or derived keys that are using DHUK or BHK, cannot be used anymore when a security breach is detected.Table 19. AES/SAES features

| AES/SAES modes/features ${ }^{(1)}$ | AES | SAES |
| :-- | :--: | :--: |
| ECB, CBC chaining | X | X |
| CTR, CCM, GCM chaining | X | - |
| AES 128-bit ECB encryption in cycles | 51 | 528 |
| DHUK and BHK key selection | - | X |
| Side-channel attacks resistance | - | X |
| Shared key between SAES and AES | X |  |

1. $X=$ supported.

# 3.39 HASH hardware accelerator (HASH) 

The HASH is a fully compliant implementation of the secure hash algorithm (SHA-1, SHA-224, SHA-256), the MD5 (message-digest algorithm 5) hash algorithm and the HMAC (keyed-hash message authentication code) algorithm. HMAC is suitable for applications requiring message authentication.
The HASH computes FIPS (Federal information processing standards) approved digests of length of 160, 224, 256 bits, for messages of up to $\left(2^{64}-1\right)$ bits. It also computes 128 bits digests for the MD5 algorithm.
The HASH main features are:

- Suitable for data authentication applications, compliant with:
- Federal Information Processing Standards Publication FIPS PUB 180-4, Secure Hash Standard (SHA-1 and SHA-2 family)
- Federal Information Processing Standards Publication FIPS PUB 186-4, Digital Signature Standard (DSS)
- Internet Engineering Task Force (IETF) Request For Comments RFC 1321, MD5 Message-Digest Algorithm
- Internet Engineering Task Force (IETF) Request For Comments RFC 2104, HMAC: Keyed-Hashing for Message Authentication and Federal Information Processing Standards Publication FIPS PUB 198-1, The Keyed-Hash Message Authentication Code (HMAC)
- Fast computation of SHA-1, SHA-224, SHA-256, and MD5
- 82 (respectively 66) clock cycles for processing one 512-bit block of data using SHA-1 (respectively SHA-256) algorithm
- 66 clock cycles for processing one 512-bit block of data using MD5 algorithm
- Corresponding 32-bit words of the digest from consecutive message blocks are added to each other to form the digest of the whole message:
- Automatic 32-bit words swapping to comply with the internal little-endian representation of the input bit string
- Word swapping supported: bits, bytes, half-words, and 32-bit words
- Automatic padding to complete the input bit string to fit digest minimum block size of 512 bits ( $16 \times 32$ bits)- Single 32-bit input register associated to an internal input FIFO of sixteen 32-bit words, corresponding to one block size
- AHB slave peripheral, accessible through 32-bit word accesses only (else an AHB error is generated)
- $8 \times 32$-bit words ( H 0 to H 7 ) for output message digest
- Automatic data flow control with support of direct memory access (DMA) using one channel. Single or fixed burst of 4 supported.
- Interruptible message digest computation, on a per-32-bit word basis
- Reloadable digest registers
- Hashing computation suspend/resume mechanism, including using DMA


# 3.40 On-the-fly decryption engine (OTFDEC) 

The OTFDEC allows the decryption of the on-the-fly AHB traffic based on the read request address information, for example execute-in-place of a code stored encrypted. Four independent and nonoverlapping encrypted regions can be defined in OTFDEC.

OTFDEC uses AES-128 in counter mode to achieve the lowest possible latency. As consequence, each time the content of one encrypted region is changed the entire region must be reencrypted with a different cryptographic context (key or initialization vector). This constraint makes OTFDEC suitable to decrypt read-only data or code, stored in external NOR Flash.

Note: When OTFDEC is used with OCTOSPI, it is mandatory to access the flash memory using the Memory-mapped mode of the flash memory controller.

When security is enabled in the product, OTFDEC can be programmed only by a secure host.

The OTFDEC main features are the following:

- On-the-fly 128-bit decryption during OCTOSPI memory-mapped read operations (single or multiple)
- Use of AES in counter (CTR) mode, with two 128-bit key stream buffers
- Support for any read size
- Physical address of the reads is used for the encryption/decryption
- Up to 4 independent encrypted regions
- Granularity of the region definition: 4096 bytes
- Region configuration write locking mechanism
- Each region has its own 128-bit key, two bytes firmware version, and eight bytes application-defined nonce. At least one of those must be changed each time an encryption is performed by the application.
- Encryption keys confidentiality and integrity protection
- Write-only registers, with software locking mechanism
- Availability of 8-bit CRC as public key information
- Support for OCTOSPI prefetching mechanism
- Possibility to select an enhanced encryption mode to add a proprietary layer of protection on top of AES stream cipher (execute only)- AMBA ${ }^{\circledR}$ AHB slave peripheral, accessible through 32-bit word single accesses only (otherwise an AHB bus error is generated, and write accesses are ignored)
- Secure only programming if TrustZone security is enabled
- Encryption mode


# 3.41 Public key accelerator (PKA) 

The PKA is intended for the computation of cryptographic public key primitives, specifically those related to RSA, Diffie-Hellmann, or ECC (elliptic curve cryptography) over GF(p) (Galois fields). To achieve high performance at a reasonable cost, these operations are executed in the Montgomery domain.

All needed computations are performed within the accelerator, so no further hardware/software elaboration is needed to process the inputs or the outputs.

The PKA main features are:

- Acceleration of RSA, DH, and ECC over GF(p) operations, based on the Montgomery method for fast modular multiplications. More specifically:
- RSA modular exponentiation, RSA Chinese remainder theorem (CRT) exponentiation
- ECC scalar multiplication, point on curve check, complete addition, double base ladder, projective to affine
- ECDSA signature generation and verification
- Capability to handle operands up to 4160 bits for RSA/DH and 640 bits for ECC
- Arithmetic and modular operations such as addition, subtraction, multiplication, modular reduction, modular inversion, comparison, and Montgomery multiplication
- Built-in Montgomery domain inward and outward transformations
- Protection against differential power analysis (DPA) and related side-channel attacks.


### 3.42 Timers and watchdogs

The devices include two advanced control timers, up to seven general-purpose timers, two basic timers, four low-power timers, two watchdog timers and two SysTick timers.

The table below compares the features of the advanced control, general-purpose and basic timers.

Table 20. Timer feature comparison

| Timer type | Timer | Counter <br> resolution | Counter <br> type | Prescaler <br> factor | DMA <br> request <br> generation | Capture/ <br> compare <br> channels | Complementary <br> outputs |
| :-- | :-- | :--: | :--: | :--: | :--: | :--: | :--: |
| Advanced <br> control | TIM1, TIM8 | 16 bits | Up, down, <br> Up/down | Any integer <br> between 1 and <br> 65536 | Yes | 4 | 3 |
| General- <br> purpose | TIM2, TIM3, <br> TIM4, TIM5 | 32 bits | Up, down, <br> Up/down | Any integer <br> between 1 and <br> 65536 | Yes | 4 | No |Table 20. Timer feature comparison (continued)

| Timer type | Timer | Counter <br> resolution | Counter <br> type | Prescaler <br> factor | DMA <br> request <br> generation | Capture/ <br> compare <br> channels | Complementary <br> outputs |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| General- <br> purpose | TIM15 | 16 bits | Up | Any integer <br> between 1 and <br> 65536 | Yes | 2 | 1 |
| General- <br> purpose | TIM16, <br> TIM17 | 16 bits | Up | Any integer <br> between 1 and <br> 65536 | Yes | 1 | 1 |
| Basic | TIM6, TIM7 | 16 bits | Up | Any integer <br> between 1 and <br> 65536 | Yes | 0 | No |

# 3.42.1 Advanced-control timers (TIM1, TIM8) 

The advanced-control timers can each be seen as a three-phase PWM multiplexed on six channels. They have complementary PWM outputs with programmable inserted dead-times. They can also be seen as complete general-purpose timers.

The four independent channels can be used for:

- Input capture
- Output compare
- PWM generation (edge or center-aligned modes) with full modulation capability ( $0-100 \%)$
- One-pulse mode output

In Debug mode, the advanced-control timer counter can be frozen and the PWM outputs disabled in order to turn off any power switches driven by these outputs.

Many features are shared with the general-purpose TIMx timers (described in the next section) using the same architecture, so the advanced-control timers can work together with the TIMx timers via the Timer Link feature for synchronization or event chaining.

### 3.42.2 General-purpose timers (TIM2, TIM3, TIM4, TIM5, TIM15, TIM16, TIM17)

There are up to seven synchronizable general-purpose timers embedded in the STM32U585xx devices (see Table 20 for differences). Each general-purpose timer can be used to generate PWM outputs, or act as a simple time base.

- TIM2, TIM3, TIM4, and TIM5

They are full-featured general-purpose timers with 32-bit autoreload up/downcounter and 16-bit prescaler.
These timers feature four independent channels for input capture/output compare, PWM, or one-pulse mode output. They can work together, or with the other general-purpose timers via the Timer Link feature for synchronization or event chaining.
The counters can be frozen in Debug mode.
All have independent DMA request generation and support quadrature encoders.- TIM15, 16 and 17

They are general-purpose timers with mid-range features.
They have 16-bit autoreload upcounters and 16-bit prescalers.

- TIM15 has two channels and one complementary channel
- TIM16 and TIM17 have one channel and one complementary channel

All channels can be used for input capture/output compare, PWM, or one-pulse mode output.
The timers can work together via the Timer Link feature for synchronization or event chaining. The timers have independent DMA request generation.
The counters can be frozen in Debug mode.

# 3.42.3 Basic timers (TIM6 and TIM7) 

The basic timers are mainly used for DAC trigger generation. They can also be used as generic 16-bit timebase.

### 3.42.4 Low-power timers (LPTIM1, LPTIM2, LPTIM3, LPTIM4)

The devices embed four low-power timers. These timers have an independent clock and are running in Stop mode if they are clocked by HSI16, MSI, LSE, LSI, or an external clock. They are able to wake up the system from Stop mode.

LPTIM1, LPTIM3, and LPTIM4 are active in Stop 0, Stop 1 and Stop 2 modes.
LPTIM2 is active in Stop 0 and Stop 1 mode.
The low-power timer supports the following features:

- 16-bit up counter with 16-bit autoreload register
- 3-bit prescaler with eight possible dividing factors ( $1,2,4,8,16,32,64,128$ )
- Selectable clock
- Internal clock sources: LSE, LSI, HSI16, MSIK (LPTIM1, LPTIM3, LPTIM4 only) or APB clock (LPTIM2 only)
- External clock source over LPTIM input (working with no LP oscillator running, used by Pulse Counter application)
- 16-bit ARR autoreload register
- 16-bit capture/compare register
- Continuous/One-shot mode
- Selectable software/hardware input trigger
- Programmable digital glitch filter
- Configurable output: pulse, PWM
- Configurable I/O polarity
- Encoder mode
- Repetition counter
- Up to 2 independent channels for:
- Input capture
- PWM generation (edge-aligned mode)
- One-pulse mode output
- Interrupt generation on 10 events- DMA request generation on the following events:
- Update event
- Input capture


# 3.42.5 Infrared interface (IRTIM) 

An infrared interface (IRTIM) for remote control is available on the device. It can be used with an infrared LED to perform remote control functions. It uses internal connections with TIM16 and TIM17.

### 3.42.6 Independent watchdog (IWDG)

The independent watchdog is based on a 12-bit downcounter and an 8-bit prescaler. It is clocked from an independent 32 kHz internal RC (LSI) and, as it operates independently from the main clock, it can operate in Stop and Standby modes. It can be used either as a watchdog to reset the device when a problem occurs, or as a free running timer for application timeout management. It is hardware or software configurable through the option bytes. The counter can be frozen in Debug mode.

### 3.42.7 Window watchdog (WWDG)

The window watchdog is based on a 7-bit downcounter that can be set as free running. It can be used as a watchdog to reset the device when a problem occurs. It is clocked from the main clock. It has an early warning interrupt capability and the counter can be frozen in Debug mode.

### 3.42.8 SysTick timer

The Cortex-M33 with TrustZone embeds two SysTick timers.
When TrustZone is activated, two SysTick timers are available:

- SysTick, secure instance
- SysTick, nonsecure instance

When TrustZone is disabled, only one SysTick timer is available. This timer (secure or nonsecure) is dedicated to real-time operating systems, but can also be used as a standard down counter. It features:

- A 24-bit down counter
- Autoreload capability
- Maskable system interrupt generation when the counter reaches 0
- Programmable clock source


### 3.43 Real-time clock (RTC), tamper and backup registers

### 3.43.1 Real-time clock (RTC)

The RTC supports the following features:

- Calendar with subsecond, seconds, minutes, hours (12 or 24 format), weekday, date, month, year, in BCD (binary-coded decimal) format
- Binary mode with 32-bit free-running counter- Automatic correction for 28, 29 (leap year), 30, and 31 days of the month
- Two programmable alarms
- On-the-fly correction from 1 to 32767 RTC clock pulses. This can be used to synchronize it with a master clock
- Reference clock detection: a more precise second source clock ( 50 or 60 Hz ) can be used to enhance the calendar precision
- Digital calibration circuit with 0.95 ppm resolution, to compensate for quartz crystal inaccuracy
- Timestamp feature that can be used to save the calendar content. This function can be triggered by an event on the timestamp pin, or by a tamper event, or by a switch to $\mathrm{V}_{\text {BAT }}$ mode
- 17-bit autoreload wake-up timer (WUT) for periodic events with programmable resolution and period
- TrustZone support:
- RTC fully securable
- Alarm A, alarm B, wake-up timer and timestamp individual secure or nonsecure configuration
- Alarm A, alarm B, wake-up timer and timestamp individual privileged protection

The RTC is supplied through a switch that takes power either from the $\mathrm{V}_{\mathrm{DD}}$ supply when present or from the VBAT pin.
The RTC clock sources can be one of the following:

- 32.768 kHz external crystal (LSE)
- external resonator or oscillator (LSE)
- internal low-power RC oscillator (LSI, with typical frequency of 32 kHz )
- high-speed external clock (HSE), divided by a prescaler in the RCC.

The RTC is functional in $\mathrm{V}_{\mathrm{BAT}}$ mode and in all low-power modes when it is clocked by the LSE. When clocked by the LSI, the RTC is not functional in $\mathrm{V}_{\mathrm{BAT}}$ mode, but is functional in all low-power modes except Shutdown mode.

All RTC events (alarm, wake-up timer, timestamp) can generate an interrupt and wake-up the device from the low-power modes.

# 3.43.2 Tamper and backup registers (TAMP) 

The antitamper detection circuit is used to protect sensitive data from external attacks. 32 32-bit backup registers are retained in all low-power modes and also in $\mathrm{V}_{\mathrm{BAT}}$ mode. The backup registers, as well as other secrets in the device, are protected by this antitamper detection circuit with eight tamper pins and eleven internal tampers. The external tamper pins can be configured for edge detection, or level detection with or without filtering, or active tamper that increases the security level by auto checking that the tamper pins are not externally opened or shorted.
TAMP main features:

- A tamper detection can erase the backup registers, backup SRAM, SRAM2, caches, and cryptographic peripherals.
- 32 32-bit backup registers:
- The backup registers (TAMP_BKPxR) are implemented in the backup domain that remains powered-on by $\mathrm{V}_{\mathrm{BAT}}$ when the $\mathrm{V}_{\mathrm{DD}}$ power is switched off.- Up to 8 tamper pins for 8 external tamper detection events:
- Active tamper mode: continuous comparison between tamper output and input to protect from physical open-short attacks
- Flexible active tamper I/O management: from 4 meshes (each input associated to its own exclusive output) to 7 meshes (single output shared for up to 7 tamper inputs)
- Passive tampers: ultra-low-power edge or level detection with internal pull-up hardware management
- Configurable digital filter
- 11 internal tamper events to protect against transient or environmental perturbation attacks:
- Backup domain voltage monitoring
- Temperature monitoring
- LSE monitoring
- RTC calendar overflow
- JTAG/SWD access if RDP different from 0
- Monotonic counter overflow
- Cryptographic peripherals fault (RNG, SAES, AES, PKA)
- Independent watchdog reset when tamper flag is already set
- 3 ADC4 watchdogs
- Each tamper can be configured in two modes:
- Hardware mode: immediate erase of secrets on tamper detection, including backup registers erase
- Software mode: erase of secrets following a tamper detection launched by software
- Any tamper detection can generate an RTC time stamp event.
- TrustZone support:
- Tamper secure or nonsecure configuration
- Backup registers configuration in 3 configurable-size areas:
- 1 read/write secure area
- 1 write secure/read nonsecure area
- 1 read/write nonsecure area
- Boot secret key (BHK) only usable by secure AES peripheral, stored in backup registers, protected against read and write access
- Tamper configuration and backup registers privilege protection
- Monotonic counter# 3.44 Inter-integrated circuit interface (I2C) 

The device embeds four I2C. Refer to Table 21 for the features implementation.
The $I^{2} \mathrm{C}$ bus interface handles communications between the microcontroller and the serial $I^{2} \mathrm{C}$ bus. It controls all $I^{2} \mathrm{C}$ bus-specific sequencing, protocol, arbitration, and timing.
The I2C peripheral supports:

- $\quad{ }^{2} \mathrm{C}$-bus specification and user manual rev. 5 compatibility:
- Slave and Master modes, multimaster capability
- Standard-mode (Sm), with a bit rate up to $100 \mathrm{Kbit} / \mathrm{s}$
- Fast-mode (Fm), with a bit rate up to $400 \mathrm{Kbit} / \mathrm{s}$
- Fast-mode Plus (Fm+), with a bit rate up to $1 \mathrm{Mbit} / \mathrm{s}$ and 20 mA output drive I/Os
- 7-bit and 10-bit addressing mode, multiple 7-bit slave addresses
- Programmable setup and hold times
- Optional clock stretching
- System management bus (SMBus) specification rev 3.0 compatibility:
- Hardware PEC (packet error checking) generation and verification with ACK control
- Address resolution protocol (ARP) support
- SMBus alert
- Power system management protocol (PMBus) specification rev 1.3 compatibility
- Independent clock: a choice of independent clock sources allowing the $I^{2} \mathrm{C}$ communication speed to be independent from the PCLK reprogramming
- Autonomous functionality in Stop modes with wake-up from Stop capability
- Programmable analog and digital noise filters
- 1-byte buffer with DMA capability

Table 21. I2C implementation

| I2C features ${ }^{(1)}$ | I2C1 | I2C2 | I2C3 | I2C4 |
| :-- | :--: | :--: | :--: | :--: |
| Standard-mode (up to $100 \mathrm{Kbit} / \mathrm{s}$ ) | X | X | X | X |
| Fast-mode (up to $400 \mathrm{Kbit} / \mathrm{s}$ ) | X | X | X | X |
| Fast-mode Plus with 20 mA output drive I/Os (up to $1 \mathrm{Mbit} / \mathrm{s}$ ) | X | X | X | X |
| Programmable analog and digital noise filters | X | X | X | X |
| SMBus/PMBus hardware support | X | X | X | X |
| Independent clock | X | X | X | X |
| Autonomous in Stop 0, Stop 1 mode with wake-up capability | X | X | X | X |
| Autonomous in Stop 2 mode with wake-up capability | - | - | X | - |

1. $X$ : supported# 3.45 Universal synchronous/asynchronous receiver transmitter (USART/UART) and low-power universal asynchronous receiver transmitter (LPUART) 

The devices embed three universal synchronous receiver transmitters (USART1, USART2, and USART3), two universal asynchronous receiver transmitters (UART4, UART5) and one low-power universal asynchronous receiver transmitter (LPUART1).

Table 22. USART, UART, and LPUART features

| USART modes/features ${ }^{(1)}$ | USART1/2/3 | UART4/5 | LPUART1 |
| :-- | :--: | :--: | :--: |
| Hardware flow control for modem | X | X | X |
| Continuous communication using DMA | X | X | X |
| Multiprocessor communication | X | X | X |
| Synchronous SPI mode (master/slave) | X | - | - |
| Smartcard mode | X | - | - |
| Single-wire half-duplex communication | X | X | X |
| IrDA SIR ENDEC block | X | X | - |
| LIN mode | X | X | - |
| Dual-clock domain and wake-up from Stop mode | $X^{(2)}$ | $X^{(2)}$ | $X^{(3)}$ |
| Receiver timeout interrupt | X | X | - |
| Modbus communication | X | X | - |
| Auto-baud rate detection | X | X | - |
| Driver enable | X | X | X |
| USART data length | 7,8 and 9 bits |  |  |
| Tx/Rx FIFO | X | X | X |
| Tx/Rx FIFO size | 8 bytes |  |  |
| Autonomous mode | X | X | X |

1. $X=$ supported.
2. Wake-up supported from Stop 0 and Stop 1 modes.
3. Wake-up supported from Stop 0, Stop 1 and Stop 2 modes.

### 3.45.1 Universal synchronous/asynchronous receiver transmitter (USART/UART)

The USART offers a flexible means to perform full-duplex data exchange with external equipment requiring an industry standard NRZ asynchronous serial data format. A very wide range of baud rates can be achieved through a fractional baud rate generator.

The USART supports both synchronous one-way and half-duplex single-wire communications, as well as LIN (local interconnection network), Smartcard protocol, IrDA (infrared data association) SIR ENDEC specifications, and modem operations (CTS/RTS). Multiprocessor communications are also supported.High-speed data communications up to 20 Mbauds are possible by using the DMA (direct memory access) for multibuffer configuration.
The USART main features are:

- Full-duplex asynchronous communication
- NRZ standard format (mark/space)
- Configurable oversampling method by 16 or 8 to achieve the best compromise between speed and clock tolerance
- Baud rate generator systems
- Two internal FIFOs for transmit and receive data

Each FIFO can be enabled/disabled by software and come with a status flag.

- A common programmable transmit and receive baud rate
- Dual-clock domain with dedicated kernel clock for peripherals independent from PCLK
- Auto baud rate detection
- Programmable data word length (7, 8 or 9 bits)
- Programmable data order with MSB-first or LSB-first shifting
- Configurable stop bits (1 or 2 stop bits)
- Synchronous SPI Master/Slave mode and clock output/input for synchronous communications
- SPI slave transmission underrun error flag
- Single-wire half-duplex communications
- Continuous communications using DMA
- Received/transmitted bytes are buffered in reserved SRAM using centralized DMA
- Separate enable bits for transmitter and receiver
- Separate signal polarity control for transmission and reception
- Swappable Tx/Rx pin configuration
- Hardware flow control for modem and RS-485 transceiver
- Communication control/error detection flags
- Parity control:
- Transmits parity bit
- Checks parity of received data byte
- Interrupt sources with flags
- Multiprocessor communications: wake-up from Mute mode by idle line detection or address mark detection
- Autonomous functionality in Stop mode with wake-up from stop capability
- LIN master synchronous break send capability and LIN slave break detection capability
- 13-bit break generation and 10/11-bit break detection when USART is hardware configured for LIN
- IrDA SIR encoder decoder supporting 3/16-bit duration for Normal mode
- Smartcard mode
- Supports the $T=0$ and $T=1$ asynchronous protocols for smartcards as defined in the ISO/IEC 7816-3 standard
- 0.5 and 1.5 stop bits for Smartcard operation- Support for Modbus communication
- Timeout feature
- CR/LF character recognition


# 3.45.2 Low-power universal asynchronous receiver transmitter (LPUART) 

The LPUART supports bidirectional asynchronous serial communication with minimum power consumption. It also supports half-duplex single-wire communication and modem operations (CTS/RTS). It allows multiprocessor communication.
Only a 32.768 kHz clock (LSE) is needed to allow LPUART communication up to 9600 baud. Therefore, even in Stop mode, the LPUART can wait for an incoming frame while having an extremely low energy consumption. Higher-speed clock can be used to reach higher baud rates.

The LPUART interface can be served by the DMA controller.
The LPUART main features are:

- Full-duplex asynchronous communications
- NRZ standard format (mark/space)
- Programmable baud rate
- From 300 baud/s to 9600 baud/s using a 32.768 kHz clock source
- Higher baud rates can be achieved by using a higher frequency clock source
- Two internal FIFOs to transmit and receive data

Each FIFO can be enabled/disabled by software and come with status flags for FIFO states.

- Dual-clock domain with dedicated kernel clock for peripherals independent from PCLK
- Programmable data word length (7 or 8 or 9 bits)
- Programmable data order with MSB-first or LSB-first shifting
- Configurable stop bits (1 or 2 stop bits)
- Single-wire half-duplex communications
- Continuous communications using DMA
- Received/transmitted bytes are buffered in reserved SRAM using centralized DMA
- Separate enable bits for transmitter and receiver
- Separate signal polarity control for transmission and reception
- Swappable Tx/Rx pin configuration
- Hardware flow control for modem and RS-485 transceiver
- Transfer detection flags:
- Receive buffer full
- Transmit buffer empty
- Busy and end of transmission flags
- Parity control:
- Transmits parity bit
- Checks parity of received data byte- Four error detection flags:
- Overrun error
- Noise detection
- Frame error
- Parity error
- Interrupt sources with flags
- Multiprocessor communications: wake-up from Mute mode by idle line detection or address mark detection
- Autonomous functionality in Stop mode with wake-up from Stop capability


# 3.46 Serial peripheral interface (SPI) 

The devices embed three serial peripheral interfaces (SPI) that can be used to communicate with external devices while using the specific synchronous protocol. The SPI protocol supports half-duplex, full-duplex, and simplex synchronous, serial communication with external devices.

The interface can be configured as master or slave and can operate in multislave or multimaster configurations. The device configured as master provides communication clock (SCK) to the slave device. The slave select (SS) and ready (RDY) signals can be applied optionally just to setup communication with concrete slave and to assure it handles the data flow properly. The Motorola ${ }^{\circledR}$ data format is used by default, but some other specific modes are supported as well.
The SPI main features are:

- Full-duplex synchronous transfers on three lines
- Half-duplex synchronous transfer on two lines (with bidirectional data line)
- Simplex synchronous transfers on two lines (with unidirectional data line)
- 4-bit to 32-bit data size selection or fixed to 8-bit and 16-bit only
- Multimaster or multislave mode capability
- Dual-clock domain, separated clock for the peripheral kernel that can be independent of PCLK
- Baud rate prescaler up to kernel frequency/2 or bypass from RCC in Master mode
- Protection of configuration and setting
- Hardware or software management of SS for both master and slave
- Adjustable minimum delays between data and between SS and data flow
- Configurable SS signal polarity and timing, MISO x MOSI swap capability
- Programmable clock polarity and phase
- Programmable data order with MSB-first or LSB-first shifting
- Programmable number of data within a transaction to control SS and CRC
- Dedicated transmission and reception flags with interrupt capability
- SPI Motorola ${ }^{\circledR}$ and Texas Instruments ${ }^{\circledR}$ formats support
- Hardware CRC feature can secure communication at the end of transaction by:
- Adding CRC value in Tx mode
- Automatic CRC error checking for Rx mode- Error detection with interrupt capability in case of data overrun, CRC error, data underrun at slave, mode fault at master
- Two 16x or 8x 8-bit embedded Rx and TxFIFOs with DMA capability
- Programmable number of data in transaction
- Configurable FIFO thresholds (data packing)
- Configurable behavior at slave underrun condition (support of cascaded circular buffers)
- Autonomous functionality in Stop modes (handling of the transaction flow and required clock distribution) with wake-up from stop capability
- Optional status pin RDY signalizing the slave device ready to handle the data flow.

Table 23. SPI features

| SPI feature | SPI1, SPI2 <br> (full feature set instances) | SPI3 <br> (limited feature set instance) |
| :-- | :--: | :--: |
| Data size | Configurable from 4 to 32-bit | $8 / 16$-bit |
| CRC computation | CRC polynomial length <br> configurable from 5 to 33-bit | CRC polynomial length <br> configurable from 9 to 17-bit |
| Size of FIFOs | $16 \times 8$-bit | $8 \times 8$-bit |
| Number of transfered data | Unlimited, expandable | Up to 1024, no data counter |
| Autonomous in Stop 0, Stop 1 mode <br> with wake-up capability | Yes | Yes |
| Autonomous in Stop 2 mode with <br> wake-up capability | No | Yes |

# 3.47 Serial audio interfaces (SAI) 

The devices embed two SAIs. Refer to Table 24: SAI implementation for the features implementation. The SAI bus interface handles communications between the microcontroller and the serial audio protocol.

The SAI peripheral supports:

- Two independent audio subblocks that can be transmitters or receivers with their respective FIFO
- 8-word integrated FIFOs for each audio subblock
- Synchronous or asynchronous mode between the audio subblocks
- Master or slave configuration independent for both audio subblocks
- Clock generator for each audio block to target independent audio frequency sampling when both audio subblocks are configured in master mode
- Data size configurable: 8-, 10-, 16-, 20-, 24-, 32-bit
- Peripheral with large configurability and flexibility allowing to target as example the following audio protocol: I2S, LSB or MSB-justified, PCM/DSP, TDM, AC'97 and SPDIF out
- Up to 16 slots available with configurable size and with the possibility to select which ones are active in the audio frame
- Number of bits by frame may be configurable- Frame synchronization active level configurable (offset, bit length, level)
- First active bit position in the slot is configurable
- LSB first or MSB first for data transfer
- Mute mode
- Stereo/mono audio frame capability
- Communication clock strobing edge configurable (SCK)
- Error flags with associated interrupts if enabled respectively
- Overrun and underrun detection
- Anticipated frame synchronization signal detection in Slave mode
- Late frame synchronization signal detection in Slave mode
- Codec not ready for the AC'97 mode in reception
- Interruption sources when enabled:
- Errors
- FIFO requests
- DMA interface with two dedicated channels to handle access to the dedicated integrated FIFO of each SAI audio subblock.

Table 24. SAI implementation

| SAI features ${ }^{(1)}$ | SAI1 | SAI2 |
| :-- | :--: | :--: |
| I2S, LSB or MSB-justified, PCM/DSP, TDM, AC'97 | X | X |
| Mute mode | X | X |
| Stereo/mono audio frame capability. | X | X |
| 16 slots | X | X |
| Data size configurable: 8-, 10-, 16-, 20-, 24-, 32-bit | X | X |
| FIFO size | $X$ (8 words) | $X$ (8 words) |
| SPDIF | X | X |
| PDM | X | - |

1. $X$ : supported

# 3.48 Secure digital input/output and MultiMediaCards interface (SDMMC) 

The SDMMC (SD/SDIO embedded MultiMediaCard e $\cdot$ MMC $^{\text {TM }}$ host interface) provides an interface between the AHB bus and SD memory cards, SDIO cards and e $\cdot$ MMC devices.

The MultiMediaCard system specifications are available through the MultiMediaCard association website at www.mmca.org, published by the MMCA technical committee.

SD memory card and SD I/O card system specifications are available through the SD card Association website at www.sdcard.org.The SDMMC features include the following:

- Compliance with Embedded MultiMediaCard System Specification Version 5.1 Card support for three different databus modes: 1-bit (default), 4-bit and 8-bit (HS200 SDMMC_CK speed limited to maximum allowed I/O speed) (HS400 is not supported).
- Full compatibility with previous versions of MultiMediaCards (backward compatibility).
- Full compliance with SD memory card specifications version 6.0
(SDR104 SDMMC_CK speed limited to maximum allowed I/O speed, SPI mode and UHS-II mode not supported).
- Full compliance with SDIO card specification version 4.0

Card support for two different databus modes: 1-bit (default) and 4-bit
(SDR104 SDMMC_CK speed limited to maximum allowed I/O speed, SPI mode and UHS-II mode not supported).

- Data transfer up to 208 Mbyte/s for the 8-bit mode (Depending maximum allowed I/O speed).
- Data and command output enable signals to control external bidirectional drivers
- IDMA linked list support

The MultiMediaCard/SD bus connects cards to the host.
The current version of the SDMMC supports only one SD/SDIO/e $\cdot$ MMC card at any one time and a stack of e $\bullet$ MMC.

Table 25. SDMMC features

| SDMMC modes/features ${ }^{(1)}$ | SDMMC1 | SDMMC2 |
| :--: | :--: | :--: |
| Variable delay (SDR104, HS200) | X | X |
| SDMMC_CKIN | X | - |
| SDMMC_CDIR, SDMMC_D0DIR | X | - |
| SDMMC_D123DIR | X | - |

1. $X=$ supported.

When SDMMC peripherals are used simultaneously:

- Only one can be used in e $\bullet$ MMC with 8-bit bus width.
- The SDMMC1 SDIO voltage switch use is mutually exclusive with SDMMC2 interfacing $e \bullet M M C$ with 8 -bit bus width, as follows:
- If SDMMC1 has to support SDIO UHS-I modes (SDR12, SDR25, SDR50, SDR104, or DDR50), SDMMC2 cannot support e $\bullet$ MMC with 8-bit bus width.
- if SDMMC2 has to support e $\bullet$ MMC with 8-bit bus width, SDMMC1 supports only SDIO default mode and high-speed mode.# 3.49 Controller area network (FDCAN) 

The controller area network (CAN) subsystem consists of one CAN module, a shared message RAM memory and a configuration block.

The modules (FDCAN) are compliant with ISO 11898-1: 2015 (CAN protocol specification version 2.0 part A, B) and CAN FD protocol specification version 1.0.

A 0.8 -Kbyte message RAM implements filters, receives FIFOs, transmits event FIFOs and transmits FIFOs.

The FDCAN main features are:

- Conform with CAN protocol version 2.0 part A, B, and ISO 11898-1: 2015, -4
- CAN FD with maximum 64 data bytes supported
- CAN error logging
- AUTOSAR and J1939 support
- Improved acceptance filtering
- 2 receive FIFOs of three payloads each (up to 64 bytes per payload)
- Separate signaling on reception of high priority messages
- Configurable transmit FIFO / queue of three payloads (up to 64 bytes per payload)
- Configurable transmit Event FIFO
- Programmable loop-back test mode
- Maskable module interrupts
- Two clock domains: APB bus interface and CAN core kernel clock
- Power-down support


### 3.50 USB on-the-go full-speed (OTG_FS)

The devices embed a USB OTG full-speed device/host/OTG peripheral with integrated transceivers. The USB OTG_FS peripheral is compliant with the USB 2.0 specification and with the OTG 2.0 specification. It has software-configurable endpoint setting and supports suspend/resume.

This interface requires a precise 48 MHz clock that can be generated from the internal main PLL (the clock source must use a HSE crystal oscillator) or by the internal 48 MHz oscillator (HSI48) in automatic-trimming mode. The synchronization for this oscillator can be taken from the USB data stream itself (SOF signalization) that allows crystal less operation.

The OTG_FS features are:

- USB-IF certified to the Universal Serial Bus Specification Rev 2.0
- On-chip full-speed PHY
- Full support (PHY) for the optional OTG (on-the-go) protocol detailed in the OTG Supplement Rev 2.0 specification
- Integrated support for A-B device identification (ID line)
- Integrated support for host negotiation protocol (HNP) and session request protocol (SRP)
- Allows host to turn $\mathrm{V}_{\text {BUS }}$ off to conserve battery power in OTG applications
- Supports OTG monitoring of $\mathrm{V}_{\text {BUS }}$ levels with internal comparators
- Supports dynamic host-peripheral switch of role- Software-configurable to operate as:
- SRP capable USB FS peripheral (B-device)
- SRP capable USB FS/LS host (A-device)
- USB On-The-Go Full-Speed dual role device
- Supports FS SOF and LS keep-alives with
- SOF pulse PAD connectivity
- SOF pulse internal connection to timer (TIMx)
- Configurable framing period
- Configurable end of frame interrupt
- USB 2.0 link power management (LPM) support
- Includes power saving features such as system stop during USB suspend, switch-off of clock domains internal to the digital core, PHY, and DFIFO power management.
- Dedicated RAM of 1.25 Kbytes with advanced FIFO control:
- Configurable partitioning of RAM space into different FIFOs for flexible and efficient use of RAM
- Each FIFO able to hold multiple packets
- Dynamic memory allocation
- Configurable FIFO sizes that are not powers of two to allow the use of contiguous memory locations
- Max guaranteed USB bandwidth for up to one frame ( 1 ms ) without system intervention
- Support of charging port detection as described in Battery Charging Specification revision 1.2 on the FS PHY transceiver only.
Host-mode features:
- External charge pump for VBUS voltage generation.
- Up to 12 host channels (pipes): each channel is dynamically reconfigurable to allocate any type of USB transfer.
- Built-in hardware scheduler holding:
- Up to 12 interrupt plus isochronous transfer requests in the periodic hardware queue
- Up to 12 control plus bulk transfer requests in the nonperiodic hardware queue
- Management of a shared Rx FIFO, a periodic Tx FIFO and a nonperiodic Tx FIFO for efficient usage of the USB data RAM
Peripheral-mode features:
- 1 bidirectional control endpoint0
- 5 IN endpoints (EPs) configurable to support bulk, interrupt, or isochronous transfers
- 5 OUT endpoints configurable to support bulk, interrupt, or isochronous transfers
- Management of a shared Rx FIFO and a Tx-OUT FIFO for efficient usage of the USB data RAM
- Management of up to 6 dedicated Tx-IN FIFOs (one for each active IN EP) to put less load on the application
- Support for the soft disconnect feature# 3.51 USB Type-C /USB Power Delivery controller (UCPD) 

The device embeds one controller (UCPD) compliant with USB Type-C Cable and Connector Specification release 2.0 and USB Power Delivery Rev. 3.0 specifications.

The controller uses specific I/Os supporting the USB Type-C and USB power delivery requirements, featuring:

- USB Type-C pull-up (Rp, all values) and pull-down (Rd) resistors
- "Dead battery" support
- USB power delivery message transmission and reception
- FRS (fast role swap) support

The digital controller handles notably:

- USB Type-C level detection with debounce, generating interrupts
- FRS detection, generating an interrupt
- Byte-level interface for USB power delivery payload, generating interrupts (DMA compatible)
- USB power delivery timing dividers (including a clock prescaler)
- CRC generation/checking
- 4b5b encode/decode
- Ordered sets (with a programmable ordered set mask at receive)
- Frequency recovery in receiver during preamble

The interface offers low-power operation compatible with Stop mode, maintaining the capacity to detect incoming USB power delivery messages and FRS signaling.

### 3.52 Development support

### 3.52.1 Serial-wire/JTAG debug port (SWJ-DP)

The Arm SWJ-DP interface is embedded and is a combined JTAG and serial-wire debug port that enables either a serial wire debug or a JTAG probe to be connected to the target.

Debug is performed using two pins only instead of five required by the JTAG (JTAG pins can be reused as GPIO with alternate function): the JTAG TMS and TCK pins are shared with SWDIO and SWCLK, respectively, and a specific sequence on the TMS pin is used to switch between JTAG-DP and SW-DP.

### 3.52.2 Embedded Trace Macrocell

The Arm Embedded Trace Macrocell (ETM) provides a greater visibility of the instruction and data flow inside the CPU core by streaming compressed data at a very high rate from the devices through a small number of ETM pins to an external hardware trace port analyzer (TPA) device.

Real-time instruction and data flow activity be recorded and then formatted for display on the host computer that runs the debugger software. TPA hardware is commercially available from common development tool vendors.

The ETM operates with third party debugger software tools.# 4 Pinout, pin description and alternate functions 

### 4.1 Pinout/ballout schematics

Figure 7. LQFP48_SMPS pinout
![img-10.jpeg](img-10.jpeg)

1. The above figure shows the package top view.

Figure 8. LQFP48 pinout
![img-11.jpeg](img-11.jpeg)

1. The above figure shows the package top view.Figure 9. UFQFPN48_SMPS pinout
![img-12.jpeg](img-12.jpeg)

1. The above figure shows the package top view.

Figure 10. UFQFPN48 pinout
![img-13.jpeg](img-13.jpeg)

1. The above figure shows the package top view.Figure 11. LQFP64_SMPS pinout
![img-14.jpeg](img-14.jpeg)

1. The above figure shows the package top view.

Figure 12. LQFP64 pinout
![img-15.jpeg](img-15.jpeg)

1. The above figure shows the package top view.Figure 13. WLCSP90_SMPS ballout
![img-16.jpeg](img-16.jpeg)

1. The above figure shows the package top view.Figure 14. LQFP100_SMPS pinout
![img-17.jpeg](img-17.jpeg)

1. The above figure shows the package top view.Figure 15. LQFP100 pinout
![img-18.jpeg](img-18.jpeg)

1. The above figure shows the package top view.Figure 16. UFBGA132_SMPS ballout
![img-19.jpeg](img-19.jpeg)

1. The above figure shows the package top view.Figure 17. UFBGA132 ballout
![img-20.jpeg](img-20.jpeg)

1. The above figure shows the package top view.Figure 18. LQFP144_SMPS pinout
![img-21.jpeg](img-21.jpeg)

1. The above figure shows the package top view.Figure 19. LQFP144 pinout
![img-22.jpeg](img-22.jpeg)

1. The above figure shows the package top view.Figure 20. UFBGA169 SMPS ballout
![img-23.jpeg](img-23.jpeg)

1. The above figure shows the package top view.Figure 21. UFBGA169 ballout
![img-24.jpeg](img-24.jpeg)

1. The above figure shows the package top view.# 4.2 Pin description 

Table 26. Legend/abbreviations used in the pinout table

| Name | Abbreviation | Definition |
| :--: | :--: | :--: |
| Pin name | Unless otherwise specified in brackets below the pin name, the pin function during and after reset is the same as the actual pin name |  |
| Pin type | S | Supply pin |
|  | I | Input only pin |
|  | I/O | Input/output pin |
| I/O structure | FT | 5V-tolerant I/O |
|  | TT | 3.6V-tolerant I/O |
|  | RST | Bidirectional reset pin with embedded weak pull-up resistor |
|  | Option for TT or FT I/Os ${ }^{(1)}$ |  |
|  | _a | I/O, with analog switch function supplied by $\mathrm{V}_{\text {DDA }}$ |
|  | _c | I/O with USB Type-C power delivery function |
|  | _d | I/O with USB Type-C power delivery dead battery function |
|  | _f | I/O, Fm+ capable |
|  | _h | I/O with high-speed low-voltage mode |
|  | _o | I/O with OSC32_IN/OSC32_OUT capability |
|  | _s | I/O supplied only by $\mathrm{V}_{\text {DDIO2 }}$ |
|  | _t | I/O with a function supplied by $\mathrm{V}_{\mathrm{SW}}$ |
|  | _u | I/O, with USB function supplied by $\mathrm{V}_{\text {DDUSB }}$ |
|  | _v | I/O very high-speed capable |
| Notes |  | Unless otherwise specified by a note, all I/Os are set as analog inputs during and after reset. |
| Pin functions | Alternate functions | Functions selected through GPIOx_AFR registers |
|  | Additional functions | Functions directly selected/enabled through peripheral registers |

1. The related I/O structures in the table below are a concatenation of various options. Examples: FT_hat, FT_fs, FT_u, TT_a.Table 27. STM32U585xx pin definitions ${ }^{(1)}$

|  | Pin number |  |  |  |  |  |  |  |  |  |  | Pin name (function after reset) | Pin type | I/O structure | Notes | Alternate functions |  | Additional functions |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | LOFP48 SMPS UFQFPN48 SMPS LOFP64 SMPS | WLCSP00 SMPS | LQFP100 SMPS | LQFP144 SMPS | UFBGA169 SMPS | LQFP48 UFQFPN48 | LQFP64 | LQFP100 | UFBGA132 | LQFP144 | UFBGA169 |  |  |  |  |  |  |  |
|  | - | - | - | 1 | B3 | 1 | A1 | - | - | 1 | B3 | 1 | A1 | PE2 | I/O | FT_ha | - | TRACECLK, TIM3_ETR, SAI1_CK1, TSC_G7_IO1, LPGPIO1_P14, FMC_A23, SAI1_MCLK_A, EVENTOUT | - |
|  | - | - | C15 | 2 | A2 | 2 | D3 | - | - | 2 | A2 | 2 | D3 | PE3 | I/O | $\begin{aligned} & \text { FT_ } \\ & \text { hat } \end{aligned}$ | - | TRACED0, TIM3_CH1, OCTOSPIM_P1_DQS, TSC_G7_IO2, LPGPIO1_P15, FMC_A19, SAI1_SD_B, EVENTOUT | TAMP_IN6/ TAMP_ OUT3 |
|  | - | - | D14 | 3 | B2 | 3 | C2 | - | - | 3 | B2 | 3 | C2 | PE4 | I/O | $\begin{aligned} & \text { FT_ } \\ & \text { hat } \end{aligned}$ | - | TRACED1, TIM3_CH2, SAI1_D2, MDF1_SDI3, TSC_G7_IO3, DCMI_D4/PSSI_D4, FMC_A20, SAI1_FS_A, EVENTOUT | WKUP1, TAMP_IN7/ TAMP_ OUT8 |
|  | - | - | E13 | 4 | A1 | 4 | D2 | - | - | 4 | A1 | 4 | D2 | PE5 | I/O | $\begin{aligned} & \text { FT_ } \\ & \text { hat } \end{aligned}$ | - | TRACED2, TIM3_CH3, SAI1_CK2, MDF1_CKI3, TSC_G7_IO4, DCMI_D6/PSSI_D6, FMC_A21, SAI1_SCK_A, EVENTOUT | WKUP2, TAMP_IN8/ TAMP_ OUT7 |
|  | - | - | D16 | 5 | C2 | 5 | E4 | - | - | 5 | C2 | 5 | E4 | PE6 | I/O | FT_ht | - | TRACED3, TIM3_CH4, SAI1_D1, DCMI_D7/PSSI_D7, FMC_A22, SAI1_SD_A, EVENTOUT | WKUP3, TAMP_IN3/ TAMP_ OUT6 |
|  | 1 | 1 | C17 | 6 | B1 | 6 | C1 | 1 | 1 | 6 | B1 | 6 | C1 | VBAT | S | - | - | - | - |
|  | - | - | - | - | - | - | F2 | - | - | - | - | - | F2 | VSS | S | - | - | - | - |Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)
![img-25.jpeg](img-25.jpeg)Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)

|  | Pin number |  |  |  |  |  |  |  |  |  |  | Pin name (function after reset) | Pin type | I/O structure | Notes | Alternate functions |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | LQFP48 SMPS UFQFPN48 SMPS |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | LQFP64 SMPS |  | WLCSP90 SMPS | LQFP100 SMPS | UFBGA132 SMPS | LQFP144 SMPS | UFBGA169 SMPS | LQFP64 | LQFP100 | UFBGA132 | LQFP144 | UFBGA169 |  |  |  |  |  |  |
|  | - | - | - | - | F2 | 15 | G4 | - | - | - | F2 | 15 | G4 | PF5 | I/O | FT_hv | - | LPTIM3_CH1, OCTOSPIM_P2_NCLK_FMC_A5, EVENTOUT |
|  | - | - | - | 10 | F6 | 16 | H2 | - | - | 10 | F6 | 16 | H2 | VSS | S | - | - | - |
|  | - | - | - | 11 | F7 | 17 | G1 | - | - | 11 | F7 | 17 | G1 | VDD | S | - | - | - |
|  | - | - | - | - | - | 18 | H6 | - | - | - | - | 18 | H6 | PF6 | I/O | FT_h | - | TIM5_ETR, TIM5_CH1, DCMI_D12/PSSI_D12, OCTOSPIM_P2_NCS, OCTOSPIM_P1_IO3, SAI1_SD_B, EVENTOUT |
|  | - | - | - | - | - | 19 | G2 | - | - | - | - | 19 | G2 | PF7 | I/O | FT_h | - | TIM5_CH2, FDCAN1_RX, OCTOSPIM_P1_IO2, SAI1_MCLK_B, EVENTOUT |
|  | - | - | - | - | - | 20 | F1 | - | - | - | - | 20 | F1 | PF8 | I/O | FT_h | - | TIM5_CH3, PSSI_D14, FDCAN1_TX, OCTOSPIM_P1_IO0, SAI1_SCK_B, EVENTOUT |
|  | - | - | - | - | - | 21 | G3 | - | - | - | - | 21 | G3 | PF9 | I/O | FT_h | - | TIM5_CH4, PSSI_D15, OCTOSPIM_P1_IO1, SAI1_FS_B, TIM15_CH1, EVENTOUT |
|  | - | - | - | - | - | 22 | H4 | - | - | - | - | 22 | H4 | PF10 | I/O | FT_hv | - | OCTOSPIM_P1_CLK, PSSI_D15, MDF1_CCK1, DCMI_D11/PSSI_D11, SAI1_D3, TIM15_CH2, EVENTOUT |Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)
![img-26.jpeg](img-26.jpeg)Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)
![img-27.jpeg](img-27.jpeg)Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)
![img-28.jpeg](img-28.jpeg)Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)
![img-29.jpeg](img-29.jpeg)Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)
![img-30.jpeg](img-30.jpeg)Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)

|  | Pin number |  |  |  |  |  |  |  |  |  |  | Pin name (function after reset) | Pin type |  |  |  | Alternate functions |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | - | - | - | - | L6 | 52 | N6 | - | - | - | L6 | 55 | N6 | PF15 | I/O | $\begin{aligned} & \text { FT } \\ & \text { fha } \end{aligned}$ | - | I2C4_SDA, TSC_G8_IO2, FMC_A9, EVENTOUT | ADC4_IN6 |
| - | - | - | - | M6 | 53 | J6 | - | - | - | M6 | 56 | J6 | PG0 | I/O | FT_ha | - | OCTOSPIM_P2_IO4, TSC_G8_IO3, FMC_A10, EVENTOUT | ADC4_IN7 |
| - | - | - | - | K6 | 54 | H7 | - | - | - | K6 | 57 | H7 | PG1 | I/O | FT_ha | - | OCTOSPIM_P2_IO5, TSC_G8_IO4, FMC_A11, EVENTOUT | ADC4_IN8 |
| - | - | H8 | 35 | K7 | 55 | L7 | - | - | 38 | K7 | 58 | L7 | PE7 | I/O | FT_h | - | TIM1_ETR, MDF1_SDI2, FMC_D4/FMC_AD4, SAI1_SD_B, EVENTOUT | WKUP6 |
| - | - | J9 | 36 | J6 | 56 | K7 | - | - | 39 | J6 | 59 | K7 | PE8 | I/O | FT_h | - | TIM1_CH1N, MDF1_CKI2, FMC_D5/FMC_AD5, SAI1_SCK_B, EVENTOUT | WKUP7 |
| - | - | K8 | 37 | M7 | 57 | J7 | - | - | 40 | M7 | 60 | J7 | PE9 | I/O | FT_hv | - | TIM1_CH1, ADF1_CCK0, MDF1_CCK0, OCTOSPIM_P1_NCLK, FMC_D6/FMC_AD6, SAI1_FS_B, EVENTOUT | - |
| - | - | - | - | - | 58 | - | - | - | - | - | 61 | - | VSS | S | - | - | - | - |
| - | - | - | - | J4 | 59 | - | - | - | - | J4 | 62 | - | VDD | S | - | - | - | - |
| - | - | J7 | 38 | J7 | 60 | H8 | - | - | 41 | J7 | 63 | H8 | PE10 | I/O | $\begin{aligned} & \text { FT } \\ & \text { hav } \end{aligned}$ | - | TIM1_CH2N, ADF1_SDI0, MDF1_SDI4, TSC_G5_IO1, OCTOSPIM_P1_CLK, FMC_D7/FMC_AD7, SAI1_MCLK_B, EVENTOUT | - |Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)
![img-31.jpeg](img-31.jpeg)Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)

|  | Pin number |  |  |  |  |  |  |  |  |  |  | Pin name (function after reset) | Pin type |  |  |  | Alternate functions |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | LOFP48 SMPS |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | UFQFPN48 SMPS |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | LOFP64 SMPS |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | WLCSP90 SMPS |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | LOFP100 SMPS |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | UFBGA132 SMPS |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | UFBGA169 SMPS |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | LOFP46 UFQFPN48 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | LQFP64 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | LQFP100 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | UFBGA132 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | LQFP144 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | 27 | H6 | 44 | K9 | 66 | K9 | 21 | 29 | 47 | K9 | 69 | K9 | PB10 | I/O | $\begin{aligned} & \text { FT } \\ & \text { fhv } \end{aligned}$ | - | TIM2_CH3, LPTIM3_CH1, I2C4_SCL, I2C2_SCL(boot), SPI2_SCK, USART3_TX, LPUART1_RX, TSC_SYNC, OCTOSPIM_P1_CLK, LPGPIO1_P4, COMP1_OUT, SAI1_SCK_A, EVENTOUT | WKUP8 |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | - | - | - | 45 | L9 | 67 | L9 | - | - | - | L9 | - | L9 | PB11 | I/O | FT_fh | - | TIM2_CH4, I2C4_SDA, I2C2_SDA(boot), SPI2_RDY, USART3_RX, LPUART1_TX, OCTOSPIM_P1_NCS, COMP2_OUT, EVENTOUT | - |
|  | 20 | 28 | K6 | 46 | M10 | 68 | N9 | - | - | - | - | - | - | VLXSMPS | S | - | - | - | - |
|  | 21 | 29 | K4 | 47 | M9 | 69 | N10 | - | - | - | - | - | - | VDDSMPS | S | - | - | - | - |
|  | 22 | 30 | J5 | 48 | L10 | 70 | M10 | - | - | - | - | - | - | VSSSMPS | S | - | - | - | - |
|  | - | - | - | - | - | - | - | 22 | 30 | 48 | L10 | 70 | N11 | VCAP | S | - | - | - | - |
|  | 23 | 31 | K2 | 49 | M11 | 71 | N11 | - | - | - | - | - | - | VDD11 | S | - | - | - | - |
|  | 24 | 32 | J3 | 50 | E9 | 72 | M11 | 23 | 31 | 49 | E9 | 71 | M11 | VSS | S | - | - | - | - |
|  | 25 | 33 | J1 | 51 | D4 | 73 | N12 | 24 | 32 | 50 | D4 | 72 | N12 | VDD | S | - | - | - | - |Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)
![img-32.jpeg](img-32.jpeg)Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)

|  | Pin number |  |  |  |  |  |  |  |  |  |  | Pin name (function after reset) | Pin type | I/O structure | Notes | Alternate functions |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | - | - | - | 55 | L12 | 77 | L12 | - | - | 55 | L12 | 77 | L12 | PD8 | I/O | FT_h | - $\begin{aligned} & \text { USART3_TX, } \\ & \text { DCMI_HSYNC/PSSI_DE, } \\ & \text { FMC_D13/FMC_AD13, } \\ & \text { EVENTOUT } \end{aligned}$ |
|  | - | - | - | 56 | J10 | 78 | L13 | - | - | 56 | J10 | 78 | L13 | PD9 | I/O | FT_h | - $\begin{aligned} & \text { LPTIM2_IN2, USART3_RX, } \\ & \text { DCMI_PIXCLK/PSSI_PDCK, } \\ & \text { FMC_D14/FMC_AD14, } \\ & \text { SAI2_MCLK_A, LPTIM3_IN1, } \\ & \text { EVENTOUT } \end{aligned}$ | - |
|  | - | - | - | 57 | M12 | 79 | K11 | - | - | 57 | M12 | 79 | K11 | PD10 | I/O | FT_ha | - $\begin{aligned} & \text { LPTIM2_CH2, USART3_CK, } \\ & \text { TSC_G6_IO1, } \\ & \text { FMC_D15/FMC_AD15, } \\ & \text { SAI2_SCK_A, LPTIM3_ETR, } \\ & \text { EVENTOUT } \end{aligned}$ | - |
|  | - | - | - | 58 | J11 | 80 | M13 | - | - | 58 | J11 | 80 | M13 | PD11 | I/O | FT_ha | - $\begin{aligned} & \text { I2C4_SMBA, USART3_CTS, } \\ & \text { TSC_G6_IO2, } \\ & \text { FMC_CLE/FMC_A16, } \\ & \text { SAI2_SD_A, LPTIM2_ETR, } \\ & \text { EVENTOUT } \end{aligned}$ | ADC4_IN15 |
|  | - | - | - | 59 | J12 | 81 | K10 | - | - | 59 | J12 | 81 | K10 | PD12 | I/O | $\begin{aligned} & \text { FT- } \\ & \text { fha } \end{aligned}$ | - $\begin{aligned} & \text { TIM4_CH1, I2C4_SCL, } \\ & \text { USART3_RTS/USART3_DE, } \\ & \text { TSC_G6_IO3, } \\ & \text { FMC_ALE/FMC_A17, } \\ & \text { SAI2_FS_A, LPTIM2_IN1, } \\ & \text { EVENTOUT } \end{aligned}$ | ADC4_IN16 |Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)
![img-33.jpeg](img-33.jpeg)Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)
![img-34.jpeg](img-34.jpeg)Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)
![img-35.jpeg](img-35.jpeg)Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)

| Pin number |  |  |  |  |  |  |  |  |  |  |  | Pin name (function after reset) | Pin type | I/O structure | Notes | Alternate functions |  | Additional functions |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
| 32 | 44 | E3 | 70 | C12 | 103 | G13 | 32 | 44 | 70 | C12 | 103 | G13 | PA11 | I/O | FT_u | - | TIM1_CH4, TIM1_BKIN2, SPI1_MISO, USART1_CTS, FDCAN1_RX, EVENTOUT | OTG_FS_ DM(boot) |
| 33 | 45 | D2 | 71 | B12 | 104 | F13 | 33 | 45 | 71 | B12 | 104 | F13 | PA12 | I/O | FT_u | - | TIM1_ETR, SPI1_MOSI, OCTOSPIM_P2_NCS, USART1_RTS/USART1_DE, FDCAN1_TX, EVENTOUT | OTG_FS_ DP(boot) |
| 34 | 46 | D4 | 72 | C10 | 105 | F12 | 34 | 46 | 72 | C10 | 105 | F12 | PA13 (JTMS/ SWDIO) | I/O | FT | (5) | JTMS/SWDIO, IR_OUT, OTG_FS_NOE, SAI1_SD_B, EVENTOUT | - |
| - | 47 | - | - | - | - | - | - | 47 | - | - | - | - | VSS | S | - | - | - | - |
| - | 48 | C1 | 73 | A12 | 106 | E13 | - | 48 | 73 | A12 | 106 | E13 | VDDUSB | S | - | - | - | - |
| 35 | - | B2 | 74 | H4 | 107 | E12 | 35 | - | 74 | H4 | 107 | E12 | VSS | S | - | - | - | - |
| 36 | - | A1 | 75 | D9 | 108 | D13 | 36 | - | 75 | D9 | 108 | D13 | VDD | S | - | - | - | - |
| 37 | 49 | C3 | 76 | C11 | 109 | C10 | 37 | 49 | 76 | C11 | 109 | C10 | PA14 (JTCK/ SWCLK) | I/O | FT | (5) | JTCK/SWCLK, LPTIM1_CH1, I2C1_SMBA, I2C4_SMBA, OTG_FS_SOF, SAI1_FS_B, EVENTOUT | - |
| 38 | 50 | E5 | 77 | A11 | 110 | A10 | 38 | 50 | 77 | A11 | 110 | A10 | PA15 (JTDI) | I/O | FT_c | (4) <br> (5) | JTDI, TIM2_CH1, TIM2_ETR, USART2_RX, SPI1_NSS, SPI3_NSS, USART3_RTS/USART3_DE, UART4_RTS/UART4_DE, SAI2_FS_B, EVENTOUT | UCPD1_ CC1 |Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)
![img-36.jpeg](img-36.jpeg)Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)

|  | Pin number |  |  |  |  |  |  |  |  |  |  | Pin name (function after reset) | Pin type | I/O structure | Notes | Alternate functions |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | LQFP48 SMPS UFQFPN48 SMPS |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | LQFP64 SMPS |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | WLCSP90 SMPS |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | LQFP100 SMPS |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | LQFP144 SMPS |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | UFBGA132 |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | LQFP144 SMPS |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | 54 | A5 | 83 | A9 | 116 | F7 | - | 54 | 83 | A9 | 116 | F7 | PD2 | I/O | FT | - | TRACED2, TIM3_ETR, USART3_RTS/USART3_DE, UART5_RX, TSC_SYNC, DCMI_D11/PSSI_D11, LPGPIO1_P7, SDMMC1_CMD, LPTIM4_ETR, EVENTOUT | - |
|  | - | - | 84 | C8 | 117 | D8 | - | - | 84 | C8 | 117 | D8 | PD3 | I/O | FT_hv | - | SPI2_SCK, DCMI_D5/PSSI_D5, SPI2_MISO, MDF1_SDI0, USART2_CTS, OCTOSPIM_P2_NCS, FMC_CLK, EVENTOUT | - |
|  | - | - | D8 | 85 | B8 | 118 | C8 | - | - | 85 | B8 | 118 | C8 | PD4 | I/O | FT_h | - | SPI2_MOSI, MDF1_CKI0, USART2_RTS/USART2_DE, OCTOSPIM_P1_IO4, FMC_NOE, EVENTOUT | - |
|  | - | - | B6 | 86 | A8 | 119 | E7 | - | - | 86 | A8 | 119 | E7 | PD5 | I/O | FT_h | - | SPI2_RDY, USART2_TX, OCTOSPIM_P1_IO5, FMC_NWE, EVENTOUT | - |
|  | - | - | - | - | - | 120 | B8 | - | - | - | - | 120 | B8 | VSS | S | - | - | - | - |
|  | - | - | - | - | - | 121 | A8 | - | - | - | - | 121 | A8 | VDD | S | - | - | - | - |
|  | - | - | - | 87 | A7 | 122 | B7 | - | - | 87 | A7 | 122 | B7 | PD6 | I/O | FT_hv | - | SAI1_D1, DCMI_D10/PSSI_D10, SPI3_MOSI, MDF1_SDI1, USART2_RX, OCTOSPIM_P1_IO6, SDMMC2_CK, FMC_NWAIT, SAI1_SD_A, EVENTOUT | - |Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)
![img-37.jpeg](img-37.jpeg)Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)
![img-38.jpeg](img-38.jpeg)Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)
![img-39.jpeg](img-39.jpeg)Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)

|  | Pin number |  |  |  |  |  |  |  |  |  |  | Pin name (function after reset) | Pin type | I/O structure | Notes | Alternate functions |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | 43 | 59 | B12 | 93 | D5 | 136 | F5 | 43 | 59 | 93 | D5 | 137 | F5 | PB7 | I/O | FT_ <br> fhav | - | LPTIM1_IN2, TIM4_CH2, TIM8_BKIN, I2C1_SDA(boot), I2C4_SDA, MDF1_CKI5, USART1_RX, UART4_CTS, TSC_G2_IO4, DCMI_VSYNC/PSSI_RDY, FMC_NL, TIM17_CH1N, EVENTOUT  |
|  | 44 | 60 | C13 | 94 | B5 | 137 | C5 | 44 | 60 | 94 | B5 | 138 | C5 | PH3-BOOT0 | I/O | FT | - | EVENTOUT  |
|  | 45 | 61 | B14 | 95 | C5 | 138 | E5 | 45 | 61 | 95 | C5 | 139 | E5 | PB8 | I/O | FT_f | - | TIM4_CH3, SAI1_CK1, I2C1_SCL, MDF1_CCK0, SPI3_RDY, SDMMC1_CKIN, FDCAN1_RX(boot), DCMI_D6/PSSI_D6, SDMMC2_D4, SDMMC1_D4, SAI1_MCLK_A, TIM16_CH1, EVENTOUT  |
|  | - | - | A15 | 96 | A4 | 139 | D5 | 46 | 62 | 96 | A4 | 140 | D5 | PB9 | I/O | FT_f | - | IR_OUT, TIM4_CH4, SAI1_D2, I2C1_SDA, SPI2_NSS, SDMMC1_CDIR, FDCAN1_TX(boot), DCMI_D7/PSSI_D7, SDMMC2_D5, SDMMC1_D5, SAI1_FS_A, TIM17_CH1, EVENTOUT  |
|  | - | - | - | 97 | C4 | 140 | D4 | - | - | 97 | C4 | 141 | D4 | PE0 | I/O | FT_h | - | TIM4_ETR, DCMI_D2/PSSI_D2, LPGPIO1_P13, FMC_NBL0, TIM16_CH1, EVENTOUT  |Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)
![img-40.jpeg](img-40.jpeg)Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)

|  | Pin number |  |  |  |  |  |  |  |  |  | Pin name (function after reset) | Pin type | I/O structure | Notes | Alternate functions |  | Additional functions |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | - | - | - | - | - | E9 | - | - | - | - | - E9 | PH9 | I/O | FT_h | - | I2C3_SMBA, OCTOSPIM_P2_IO4, DCMI_DO/PSSI_DO, EVENTOUT | - |
|  | - | - | - | - | - | C13 | - | - | - | - | - C13 | PH10 | I/O | FT_h | - | TIM5_CH1, OCTOSPIM_P2_IO5, DCMI_D1/PSSI_D1, EVENTOUT | - |
|  | - | - | - | - | - | D9 | - | - | - | - | - D9 | PH11 | I/O | FT_h | - | TIM5_CH2, OCTOSPIM_P2_IO6, DCMI_D2/PSSI_D2, EVENTOUT | - |
|  | - | - | - | - | - | B13 | - | - | - | - | - B13 | PH12 | I/O | FT_h | - | TIM5_CH3, TIM8_CH4N, OCTOSPIM_P2_IO7, DCMI_D3/PSSI_D3, EVENTOUT | - |
|  | - | - | - | - | - | C12 | - | - | - | - | - C12 | PH13 | I/O | FT | - | TIM8_CH1N, FDCAN1_TX, EVENTOUT | - |
|  | - | - | - | - | - | C11 | - | - | - | - | - C11 | PH14 | I/O | FT | - | TIM8_CH2N, FDCAN1_RX, DCMI_D4/PSSI_D4, EVENTOUT | - |
|  | - | - | - | - | - | A13 | - | - | - | - | - A13 | PH15 | I/O | FT_h | - | TIM8_CH3N, OCTOSPIM_P2_IO6, DCMI_D11/PSSI_D11, EVENTOUT | - |
|  | - | - | - | - | - | A11 | - | - | - | - | - A11 | VDD | S | - | - | - | - |
|  | - | - | - | - | - | B12 | - | - | - | - | - B12 | PIO | I/O | FT_h | - | TIM5_CH4, OCTOSPIM_P1_IO5, SPI2_NSS, DCMI_D13/PSSI_D13, EVENTOUT | - |
|  | - | - | - | - | - | A12 | - | - | - | - | - A12 | PI1 | I/O | FT_h | - | SPI2_SCK, OCTOSPIM_P2_IO2, DCMI_D8/PSSI_D8, EVENTOUT | - |Table 27. STM32U585xx pin definitions ${ }^{(1)}$ (continued)
![img-41.jpeg](img-41.jpeg)

1. Function availability depends on the chosen device.
2. PC13, PC14 and PC15 are supplied through the power switch (by $\mathrm{V}_{\mathrm{SW}}$ ). Since the switch only sinks a limited amount of current ( 3 mA ), the use of PC13 to PC15 GPIOs in output mode is limited:

- PC13 speed must not exceed 2 MHz with a maximum load of 30 pF . Refer to FT_o electrical characteristics for PC14, PC15.
- These GPIOs must not be used as current sources (for example to drive a LED).3. After a backup domain power-up, PC13, PC14 and PC15 operate as GPIOs. Their function depends then on the content of the RTC registers that are not reset by the system reset. For details on how to manage these GPIOs, refer to the backup domain and RTC register descriptions in the product reference manual.
4. After reset, a pull-down resistor ( $\mathrm{Rd}=5.1 \mathrm{k} \Omega$ from UCPD peripheral) can be activated on PA15 and PB15 (UCPD1_CC1, UCPD1_CC2). The pull-down on PA15 (UCPD1_CC1) is activated by high level on PB5 (UCPD1_DBCC1). The pull-down on PB15 (UCPD1_CC2) is activated by high level on PB14 (UCPD1_DBCC2). This pull-down control (dead battery support on UCPD) can be disabled by setting UCPD_DBDIS $=1$ in the PWR_UCPDR register.
5. After reset, this pin is configured as JTAG/SWD alternate functions. The internal pull-up on PA15, PA13, PB4 pins and the internal pull-down on PA14 pin are activated.4.3 Alternate functionsTable 28. Alternate function AF0 to AF7 ${ }^{(1)}$

|  Port | AF0 | AF1 | AF2 | AF3 | AF4 | AF5 | AF6 | AF7  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   | CRS/LPTIM1/ SYS_AF | LPTIM1/ TIM1/2/5/8 | LPTIM1/2/3/ TIM1/2/3/4/5 | ADF1/I2C4/ OCTOSPIM_P1/ OTG_FS/SAI1/ SPI2/TIM1/8/ USART2 | DCMI/ I2C1/2/3/4/ LPTIM3 | DCMI/I2C4/MDF1/ OCTOSPIM_P1/2/ SPI1/2/3 | I2C3/MDF1/ OCTOSPIM_P2/ SPI3 | USART1/2/3  |
|  PA0 | - | TIM2_CH1 | TIM5_CH1 | TIM8_ETR | - | - | SPI3_RDY | USART2_CTS  |
|  PA1 | LPTIM1_CH2 | TIM2_CH2 | TIM5_CH2 | - | I2C1_SMBA | SPI1_SCK | - | USART2_ RTS/USART2_ DE  |
|  PA2 | - | TIM2_CH3 | TIM5_CH3 | - | - | SPI1_RDY | - | USART2_TX  |
|  PA3 | - | TIM2_CH4 | TIM5_CH4 | SAI1_CK1 | - | - | - | USART2_RX  |
|  PA4 | - | - | - | OCTOSPIM_P1 _NCS | - | SPI1_NSS | SPI3_NSS | USART2_CK  |
|  PA5 | CSLEEP | TIM2_CH1 | TIM2_ETR | TIM8_CH1N | PSSI_D14 | SPI1_SCK | - | USART3_RX  |
|  PA6 | CDSTOP | TIM1_BKIN | TIM3_CH1 | TIM8_BKIN | DCMI_PIXCL K/PSSI_ PDCK | SPI1_MISO | - | USART3_CTS  |
|  PA7 | SRDSTOP | TIM1_CH1N | TIM3_CH2 | TIM8_CH1N | I2C3_SCL | SPI1_MOSI | - | USART3_TX  |
|  PA8 | MCO | TIM1_CH1 | - | SAI1_CK2 | - | SPI1_RDY | - | USART1_CK  |
|  PA9 | - | TIM1_CH2 | - | SPI2_SCK | - | DCMI_D0/PSSI_D0 | - | USART1_TX  |
|  PA10 | CRS_SYNC | TIM1_CH3 | LPTIM2_IN2 | SAI1_D1 | - | DCMI_D1/PSSI_D1 | - | USART1_RX  |
|  PA11 | - | TIM1_CH4 | TIM1_BKIN2 | - | - | SPI1_MISO | - | USART1_CTS  |
|  PA12 | - | TIM1_ETR | - | - | - | SPI1_MOSI | OCTOSPIM_ P2_NCS | USART1_ RTS/USART1_ DE  |
|  PA13 | JTMS/SWDIO | IR_OUT | - | - | - | - | - | -  |
|  PA14 | JTCK/SWCLK | LPTIM1_CH1 | - | - | I2C1_SMBA | I2C4_SMBA | - | -  |
|  PA15 | JTDI | TIM2_CH1 | TIM2_ETR | USART2_RX | - | SPI1_NSS | SPI3_NSS | USART3_ RTS/USART3_ DE  |Table 28. Alternate function AF0 to AF7 ${ }^{(1)}$ (continued)

|  Port | AF0 | AF1 | AF2 | AF3 | AF4 | AF5 | AF6 | AF7  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   | CRS/LPTIM1/ SYS_AF | LPTIM1/ TIM1/2/5/8 | LPTIM1/2/3/ TIM1/2/3/4/5 | ADF1/I2C4/ OCTOSPIM_P1/ OTG_FS/SAI1/ SPI2/TIM1/8/ USART2 | DCMI/ I2C1/2/3/4/ LPTIM3 | DCMI/I2C4/MDF1/ OCTOSPIM_P1/2/ SPI1/2/3 | I2C3/MDF1/ OCTOSPIM_P2/ SPI3 | USART1/2/3  |
|  PB0 | - | TIM1_CH2N | TIM3_CH3 | TIM8_CH2N | LPTIM3_CH1 | SPI1_NSS | - | USART3_CK  |
|  PB1 | - | TIM1_CH3N | TIM3_CH4 | TIM8_CH3N | LPTIM3_CH2 | - | MDF1_SDI0 | USART3_ RTS/USART3_ DE  |
|  PB2 | - | LPTIM1_CH1 | - | TIM8_CH4N | I2C3_SMBA | SPI1_RDY | MDF1_CKI0 | -  |
|  PB3 | JTDO/ TRACESWO | TIM2_CH2 | LPTIM1_CH1 | ADF1_CCK0 | I2C1_SDA | SPI1_SCK | SPI3_SCK | USART1_ RTS/USART1_ DE  |
|  PB4 | NJTRST | LPTIM1_CH2 | TIM3_CH1 | ADF1_SDI0 | I2C3_SDA | SPI1_MISO | SPI3_MISO | USART1_CTS  |
|  PB5 | - | LPTIM1_IN1 | TIM3_CH2 | OCTOSPIM_ P1_NCLK | I2C1_SMBA | SPI1_MOSI | SPI3_MOSI | USART1_CK  |
|  PB6 | - | LPTIM1_ETR | TIM4_CH1 | TIM8_BKIN2 | I2C1_SCL | I2C4_SCL | MDF1_SDI5 | USART1_TX  |
|  PB7 | - | LPTIM1_IN2 | TIM4_CH2 | TIM8_BKIN | I2C1_SDA | I2C4_SDA | MDF1_CKI5 | USART1_RX  |
|  PB8 | - | - | TIM4_CH3 | SAI1_CK1 | I2C1_SCL | MDF1_CCK0 | SPI3_RDY | -  |
|  PB9 | - | IR_OUT | TIM4_CH4 | SAI1_D2 | I2C1_SDA | SPI2_NSS | - | -  |
|  PB10 | - | TIM2_CH3 | LPTIM3_CH1 | I2C4_SCL | I2C2_SCL | SPI2_SCK | - | USART3_TX  |
|  PB11 | - | TIM2_CH4 | - | I2C4_SDA | I2C2_SDA | SPI2_RDY | - | USART3_RX  |
|  PB12 | - | TIM1_BKIN | - | - | I2C2_SMBA | SPI2_NSS | MDF1_SDI1 | USART3_CK  |
|  PB13 | - | TIM1_CH1N | LPTIM3_IN1 | - | I2C2_SCL | SPI2_SCK | MDF1_CKI1 | USART3_CTS  |
|  PB14 | - | TIM1_CH2N | LPTIM3_ETR | TIM8_CH2N | I2C2_SDA | SPI2_MISO | MDF1_SDI2 | USART3_ RTS/USART3_ DE  |
|  PB15 | RTC_REFIN | TIM1_CH3N | LPTIM2_IN2 | TIM8_CH3N | - | SPI2_MOSI | MDF1_CKI2 | -  |Table 28. Alternate function AF0 to AF7 ${ }^{(1)}$ (continued)

|  Port | AF0 | AF1 | AF2 | AF3 | AF4 | AF5 | AF6 | AF7  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   | CRS/LPTIM1/
SYS_AF | LPTIM1/
TIM1/2/5/8 | LPTIM1/2/3/
TIM1/2/3/4/5 | ADF1/I2C4/
OCTOSPIM_P1/
OTG_FS/SAI1/
SPI2/TIM1/8/
USART2 | DCMI/
I2C1/2/3/4/
LPTIM3 | DCMI/I2C4/MDF1/
OCTOSPIM_P1/2/
SPI1/2/3 | I2C3/MDF1/
OCTOSPIM_P2/
SPI3 | USART1/2/3  |
|  PC0 | - | LPTIM1_IN1 | - | OCTOSPIM_
P1_ID7 | I2C3_SCL | SPI2_RDY | MDF1_SDI4 | -  |
|  PC1 | TRACED0 | LPTIM1_CH1 | - | SPI2_MOSI | I2C3_SDA | - | MDF1_CKI4 | -  |
|  PC2 | - | LPTIM1_IN2 | - | - | - | SPI2_MISO | MDF1_CCK1 | -  |
|  PC3 | - | LPTIM1_ETR | LPTIM3_CH1 | SAI1_D1 | - | SPI2_MOSI | - | -  |
|  PC4 | - | - | - | - | - | - | - | USART3_TX  |
|  PC5 | - | TIM1_CH4N | - | SAI1_D3 | PSSI_D15 | - | - | USART3_RX  |
|  PC6 | CSLEEP | - | TIM3_CH1 | TIM8_CH1 | - | - | MDF1_CKI3 | -  |
|  PC7 | CDSTOP | - | TIM3_CH2 | TIM8_CH2 | - | - | MDF1_SDI3 | -  |
|  PC8 | SRDSTOP | - | TIM3_CH3 | TIM8_CH3 | - | - | - | -  |
|  PC9 | TRACED0 | TIM8_BKIN2 | TIM3_CH4 | TIM8_CH4 | DCMI_D3/
PSSI_D3 | - | - | -  |
|  PC10 | TRACED1 | - | LPTIM3_ETR | ADF1_CCK1 | - | - | SPI3_SCK | USART3_TX  |
|  PC11 | - | - | LPTIM3_IN1 | ADF1_SDI0 | DCMI_D2/
PSSI_D2 | OCTOSPIM_
P1_NCS | SPI3_MISO | USART3_RX  |
|  PC12 | TRACED3 | - | - | - | - | - | SPI3_MOSI | USART3_CK  |
|  PC13 | - | - | - | - | - | - | - | -  |
|  PC14 | - | - | - | - | - | - | - | -  |
|  PC15 | - | - | - | - | - | - | - | -  |Table 28. Alternate function AF0 to AF7 ${ }^{(1)}$ (continued)

|  Port | AF0 | AF1 | AF2 | AF3 | AF4 | AF5 | AF6 | AF7  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   | CRS/LPTIM1/ SYS_AF | LPTIM1/ TIM1/2/5/8 | LPTIM1/2/3/ TIM1/2/3/4/5 | ADF1/I2C4/ OCTOSPIM_P1/ OTG_FS/SAI1/ SPI2/TIM1/8/ USART2 | DCMI/ I2C1/2/3/4/ LPTIM3 | DCMI/I2C4/MDF1/ OCTOSPIM_P1/2/ SPI1/2/3 | I2C3/MDF1/ OCTOSPIM_P2/ SPI3 | USART1/2/3  |
|  PD0 | - | - | - | TIM8_CH4N | - | SPI2_NSS | - | -  |
|  PD1 | - | - | - | - | - | SPI2_SCK | - | -  |
|  PD2 | TRACED2 | - | TIM3_ETR | - | - | - | - | USART3_ RTS/USART3_ DE  |
|  PD3 | - | - | - | SPI2_SCK | DCMI_D5/ PSSI_D5 | SPI2_MISO | MDF1_SDI0 | USART2_CTS  |
|  PD4 | - | - | - | - | - | SPI2_MOSI | MDF1_CKI0 | USART2_ RTS/USART2_ DE  |
|  PD5 | - | - | - | - | - | SPI2_RDY | - | USART2_TX  |
|  PD6 | - | - | - | SAI1_D1 | DCMI_D10/ PSSI_D10 | SPI3_MOSI | MDF1_SDI1 | USART2_RX  |
|  PD7 | - | - | - | - | - | - | MDF1_CKI1 | USART2_CK  |
|  PD8 | - | - | - | - | - | - | - | USART3_TX  |
|  PD9 | - | - | LPTIM2_IN2 | - | - | - | - | USART3_RX  |
|  PD10 | - | - | LPTIM2_CH2 | - | - | - | - | USART3_CK  |
|  PD11 | - | - | - | - | I2C4_SMBA | - | - | USART3_CTS  |
|  PD12 | - | - | TIM4_CH1 | - | I2C4_SCL | - | - | USART3_ RTS/USART3_ DE  |
|  PD13 | - | - | TIM4_CH2 | - | I2C4_SDA | - | - | -  |
|  PD14 | - | - | TIM4_CH3 | - | - | - | - | -  |
|  PD15 | - | - | TIM4_CH4 | - | - | - | - | -  |Table 28. Alternate function AF0 to AF7 ${ }^{(1)}$ (continued)

|  Port | AF0 | AF1 | AF2 | AF3 | AF4 | AF5 | AF6 | AF7  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   | CRS/LPTIM1/
SYS_AF | LPTIM1/
TIM1/2/5/8 | LPTIM1/2/3/
TIM1/2/3/4/5 | ADF1/I2C4/
OCTOSPIM_P1/
OTG_FS/SAI1/
SPI2/TIM1/8/
USART2 | DCMI/
I2C1/2/3/4/
LPTIM3 | DCMI/I2C4/MDF1/
OCTOSPIM_P1/2/
SPI1/2/3 | I2C3/MDF1/
OCTOSPIM_P2/
SPI3 | USART1/2/3  |
|  PE0 | - | - | TIM4_ETR | - | - | - | - | -  |
|  PE1 | - | - | - | - | - | - | - | -  |
|  PE2 | TRACECLK | - | TIM3_ETR | SAI1_CK1 | - | - | - | -  |
|  PE3 | TRACED0 | - | TIM3_CH1 | OCTOSPIM_
P1_DQS | - | - | - | -  |
|  PE4 | TRACED1 | - | TIM3_CH2 | SAI1_D2 | - | - | MDF1_SDI3 | -  |
|  PE5 | TRACED2 | - | TIM3_CH3 | SAI1_CK2 | - | - | MDF1_CKI3 | -  |
|  PE6 | TRACED3 | - | TIM3_CH4 | SAI1_D1 | - | - | - | -  |
|  PE7 | - | TIM1_ETR | - | - | - | - | MDF1_SDI2 | -  |
|  PE8 | - | TIM1_CH1N | - | - | - | - | MDF1_CKI2 | -  |
|  PE9 | - | TIM1_CH1 | - | ADF1_CCK0 | - | - | MDF1_CCK0 | -  |
|  PE10 | - | TIM1_CH2N | - | ADF1_SDI0 | - | - | MDF1_SDI4 | -  |
|  PE11 | - | TIM1_CH2 | - | - | - | SPI1_RDY | MDF1_CKI4 | -  |
|  PE12 | - | TIM1_CH3N | - | - | - | SPI1_NSS | MDF1_SDI5 | -  |
|  PE13 | - | TIM1_CH3 | - | - | - | SPI1_SCK | MDF1_CKI5 | -  |
|  PE14 | - | TIM1_CH4 | TIM1_BKIN2 | - | - | SPI1_MISO | - | -  |
|  PE15 | - | TIM1_BKIN | - | TIM1_CH4N | - | SPI1_MOSI | - | -  |Table 28. Alternate function AF0 to AF7 ${ }^{(1)}$ (continued)

|  Port | AF0 | AF1 | AF2 | AF3 | AF4 | AF5 | AF6 | AF7  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   | CRS/LPTIM1/ SYS_AF | LPTIM1/ TIM1/2/5/8 | LPTIM1/2/3/ TIM1/2/3/4/5 | ADF1/I2C4/ OCTOSPIM_P1/ OTG_FS/SAI1/ SPI2/TIM1/8/ USART2 | DCMI/ I2C1/2/3/4/ LPTIM3 | DCMI/I2C4/MDF1/ OCTOSPIM_P1/2/ SPI1/2/3 | I2C3/MDF1/ OCTOSPIM_P2/ SPI3 | USART1/2/3  |
|  PF0 | - | - | - | - | I2C2_SDA | OCTOSPIM_P2_IO0 | - | -  |
|  PF1 | - | - | - | - | I2C2_SCL | OCTOSPIM_P2_IO1 | - | -  |
|  PF2 | - | - | LPTIM3_CH2 | - | I2C2_SMBA | OCTOSPIM_P2_IO2 | - | -  |
|  PF3 | - | - | LPTIM3_IN1 | - | - | OCTOSPIM_P2_IO3 | - | -  |
|  PF4 | - | - | LPTIM3_ETR | - | - | OCTOSPIM_ P2_CLK | - | -  |
|  PF5 | - | - | LPTIM3_CH1 | - | - | OCTOSPIM_ P2_NCLK | - | -  |
|  PF6 | - | TIM5_ETR | TIM5_CH1 | - | DCMI_D12/P SSI_D12 | OCTOSPIM_ P2_NCS | - | -  |
|  PF7 | - | - | TIM5_CH2 | - | - | - | - | -  |
|  PF8 | - | - | TIM5_CH3 | - | PSSI_D14 | - | - | -  |
|  PF9 | - | - | TIM5_CH4 | - | PSSI_D15 | - | - | -  |
|  PF10 | - | - | - | OCTOSPIM_ P1_CLK | PSSI_D15 | - | MDF1_CCK1 | -  |
|  PF11 | - | - | - | OCTOSPIM_ P1_NCLK | - | - | - | -  |
|  PF12 | - | - | - | - | - | OCTOSPIM_ P2_DQS | - | -  |
|  PF13 | - | - | - | - | I2C4_SMBA | - | - | -  |
|  PF14 | - | - | - | - | I2C4_SCL | - | - | -  |
|  PF15 | - | - | - | - | I2C4_SDA | - | - | -  |Table 28. Alternate function AF0 to AF7 ${ }^{(1)}$ (continued)

|  Port | AF0 | AF1 | AF2 | AF3 | AF4 | AF5 | AF6 | AF7  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   | CRS/LPTIM1/ SYS_AF | LPTIM1/ TIM1/2/5/8 | LPTIM1/2/3/ TIM1/2/3/4/5 | ADF1/I2C4/ OCTOSPIM_P1/ OTG_FS/SAI1/ SPI2/TIM1/8/ USART2 | DCMI/ I2C1/2/3/4/ LPTIM3 | DCMI/I2C4/MDF1/ OCTOSPIM_P1/2/ SPI1/2/3 | I2C3/MDF1/ OCTOSPIM_P2/ SPI3 | USART1/2/3  |
|  PG0 | - | - | - | - | - | OCTOSPIM_P2_IO4 | - | -  |
|  PG1 | - | - | - | - | - | OCTOSPIM_P2_IO5 | - | -  |
|  PG2 | - | - | - | - | - | SPI1_SCK | - | -  |
|  PG3 | - | - | - | - | - | SPI1_MISO | - | -  |
|  PG4 | - | - | - | - | - | SPI1_MOSI | - | -  |
|  PG5 | - | - | - | - | - | SPI1_NSS | - | -  |
|  PG6 | - | - | - | OCTOSPIM_ P1_DQS | I2C3_SMBA | SPI1_RDY | - | -  |
|  PG7 | - | - | - | SAI1_CK1 | I2C3_SCL | OCTOSPIM_ P2_DQS | MDF1_CCK0 | -  |
|  PG8 | - | - | - | - | I2C3_SDA | - | - | -  |
|  PG9 | - | - | - | - | - | OCTOSPIM_P2_IO6 | SPI3_SCK | USART1_TX  |
|  PG10 | - | LPTIM1_IN1 | - | - | - | OCTOSPIM_P2_IO7 | SPI3_MISO | USART1_RX  |
|  PG11 | - | LPTIM1_IN2 | - | OCTOSPIM_ P1_IO5 | - | - | SPI3_MOSI | USART1_CTS  |
|  PG12 | - | LPTIM1_ETR | - | - | - | OCTOSPIM_ P2_NCS | SPI3_NSS | USART1_ RTS/USART1_ DE  |
|  PG13 | - | - | - | - | I2C1_SDA | - | SPI3_RDY | USART1_CK  |
|  PG14 | - | LPTIM1_CH2 | - | - | I2C1_SCL | - | - | -  |
|  PG15 | - | LPTIM1_CH1 | - | - | I2C1_SMBA | OCTOSPIM_ P2_DQS | - | -  |Table 28. Alternate function AF0 to AF7 ${ }^{(1)}$ (continued)

|  Port | AF0 | AF1 | AF2 | AF3 | AF4 | AF5 | AF6 | AF7  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   | CRS/LPTIM1/ SYS_AF | LPTIM1/ TIM1/2/5/8 | LPTIM1/2/3/ TIM1/2/3/4/5 | ADF1/I2C4/ OCTOSPIM_P1/ OTG_FS/SAI1/ SPI2/TIM1/8/ USART2 | DCMI/ I2C1/2/3/4/ LPTIM3 | DCMI/I2C4/MDF1/ OCTOSPIM_P1/2/ SPI1/2/3 | I2C3/MDF1/ OCTOSPIM_P2/ SPI3 | USART1/2/3  |
|  PH0 | - | - | - | - | - | - | - | -  |
|  PH1 | - | - | - | - | - | - | - | -  |
|  PH2 | - | - | - | OCTOSPIM_ P1_IO4 | - | - | - | -  |
|  PH3 | - | - | - | - | - | - | - | -  |
|  PH4 | - | - | - | - | I2C2_SCL | OCTOSPIM_ P2_DQS | - | -  |
|  PH5 | - | - | - | - | I2C2_SDA | - | - | -  |
|  PH6 | - | - | - | - | I2C2_SMBA | OCTOSPIM_ P2_CLK | - | -  |
|  PH7 | - | - | - | - | I2C3_SCL | OCTOSPIM_ P2_NCLK | - | -  |
|  PH8 | - | - | - | - | I2C3_SDA | OCTOSPIM_P2_IO3 | - | -  |
|  PH9 | - | - | - | - | I2C3_SMBA | OCTOSPIM_P2_IO4 | - | -  |
|  PH10 | - | - | TIM5_CH1 | - | - | OCTOSPIM_P2_IO5 | - | -  |
|  PH11 | - | - | TIM5_CH2 | - | - | OCTOSPIM_P2_IO6 | - | -  |
|  PH12 | - | - | TIM5_CH3 | TIM8_CH4N | - | OCTOSPIM_P2_IO7 | - | -  |
|  PH13 | - | - | - | TIM8_CH1N | - | - | - | -  |
|  PH14 | - | - | - | TIM8_CH2N | - | - | - | -  |
|  PH15 | - | - | - | TIM8_CH3N | - | OCTOSPIM_P2_IO6 | - | -  |Table 28. Alternate function AF0 to AF7 ${ }^{(1)}$ (continued)

|  Port | AF0 | AF1 | AF2 | AF3 | AF4 | AF5 | AF6 | AF7  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   | CRS/LPTIM1/
SYS_AF | LPTIM1/
TIM1/2/5/8 | LPTIM1/2/3/
TIM1/2/3/4/5 | ADF1/I2C4/
OCTOSPIM_P1/
OTG_FS/SAI1/
SPI2/TIM1/8/
USART2 | DCMI/
I2C1/2/3/4/
LPTIM3 | DCMI/I2C4/MDF1/
OCTOSPIM_P1/2/
SPI1/2/3 | I2C3/MDF1/
OCTOSPIM_P2/
SPI3 | USART1/2/3  |
|  PI0 | - | - | TIM5_CH4 | OCTOSPIM_
P1_IO5 | - | SPI2_NSS | - | -  |
|  PI1 | - | - | - | - | - | SPI2_SCK | OCTOSPIM_
P2_IO2 | -  |
|  PI2 | - | - | - | TIM8_CH4 | - | SPI2_MISO | OCTOSPIM_
P2_IO1 | -  |
|  PI3 | - | - | - | TIM8_ETR | - | SPI2_MOSI | OCTOSPIM_
P2_IO0 | -  |
|  PI4 | - | - | - | TIM8_BKIN | - | SPI2_RDY | - | -  |
|  PI5 | - | - | - | TIM8_CH1 | - | OCTOSPIM_
P2_NCS | - | -  |
|  PI6 | - | - | - | TIM8_CH2 | - | OCTOSPIM_
P2_CLK | - | -  |
|  PI7 | - | - | - | TIM8_CH3 | - | OCTOSPIM_
P2_NCLK | - | -  |

1. Refer to the next table for AF8 to AF15.Table 29. Alternate function AF8 to AF15 ${ }^{(1)}$

|  Port | AF8 | AF9 | AF10 | AF11 | AF12 | AF13 | AF14 | AF15  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   | LPUART1/
SDMMC1/
UART4/5 | CAN1/TSC | CRS/DCMI/
OCTOSPIM_P1/2/
OTG_FS | LPGPIO1/
SDMMC2/
UCPD1/FMC | COMP1/2/FMC/
SDMMC1/2 | LPTIM2/4/
SAI1/2 | LPTIM2/3/
TIM2/15/16/17 | EVENTOUT  |
|  PA0 | UART4_TX | - | OCTOSPIM_
P2_NCS | - | SDMMC2_CMD | AUDIOCLK | TIM2_ETR | EVENTOUT  |
|  PA1 | UART4_RX | - | OCTOSPIM_
P1_DQS | LPGPIO1_P0 | - | - | TIM15_CH1N | EVENTOUT  |
|  PA2 | LPUART1_TX | - | OCTOSPIM_
P1_NCS | UCPD1_
FRSTX1 | - | - | TIM15_CH1 | EVENTOUT  |
|  PA3 | LPUART1_RX | - | OCTOSPIM_P1_CLK | LPGPIO1_P1 | - | SAI1_MCLK_A | TIM15_CH2 | EVENTOUT  |
|  PA4 | - | - | DCMI_HSYNC/
PSSI_DE | - | - | SAI1_FS_B | LPTIM2_CH1 | EVENTOUT  |
|  PA5 | - | - | - | - | - | - | LPTIM2_ETR | EVENTOUT  |
|  PA6 | LPUART1_CTS | - | OCTOSPIM_P1_IO3 | LPGPIO1_P2 | - | - | TIM16_CH1 | EVENTOUT  |
|  PA7 | - | - | OCTOSPIM_P1_IO2 | - | - | LPTIM2_CH2 | TIM17_CH1 | EVENTOUT  |
|  PA8 | - | - | OTG_FS_SOF | - | TRACECLK | SAI1_SCK_A | LPTIM2_CH1 | EVENTOUT  |
|  PA9 | - | - | - | - | - | SAI1_FS_A | TIM15_BKIN | EVENTOUT  |
|  PA10 | - | - | OTG_FS_ID | - | - | SAI1_SD_A | TIM17_BKIN | EVENTOUT  |
|  PA11 | - | FDCAN1_RX | - | - | - | - | - | EVENTOUT  |
|  PA12 | - | FDCAN1_TX | - | - | - | - | - | EVENTOUT  |
|  PA13 | - | - | OTG_FS_NOE | - | - | SAI1_SD_B | - | EVENTOUT  |
|  PA14 | - | - | OTG_FS_SOF | - | - | SAI1_FS_B | - | EVENTOUT  |
|  PA15 | UART4_RTS/
UART4_DE | - | - | - | - | SAI2_FS_B | - | EVENTOUT  |Table 29. Alternate function AF8 to AF15 ${ }^{(1)}$ (continued)

|  Port | AF8 | AF9 | AF10 | AF11 | AF12 | AF13 | AF14 | AF15  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   | LPUART1/
SDMMC1/
UART4/5 | CAN1/TSC | CRS/DCMI/
OCTOSPIM_P1/2/
OTG_FS | LPGPIO1/
SDMMC2/
UCPD1/FMC | COMP1/2/FMC/
SDMMC1/2 | LPTIM2/4/
SAI1/2 | LPTIM2/3/
TIM2/15/16/17 | EVENTOUT  |
|  PB0 | - | - | OCTOSPIM_P1_IO1 | LPGPIO1_P9 | COMP1_OUT | AUDIOCLK | - | EVENTOUT  |
|  PB1 | LPUART1_
RTS/LPUART1_
DE | - | OCTOSPIM_P1_IO0 | LPGPIO1_P3 | - | - | LPTIM2_IN1 | EVENTOUT  |
|  PB2 | - | - | OCTOSPIM_
P1_DQS | UCPD1_
FRSTX1 | - | - | - | EVENTOUT  |
|  PB3 | - | - | CRS_SYNC | LPGPIO1_P11 | SDMMC2_D2 | SAI1_SCK_B | - | EVENTOUT  |
|  PB4 | UART5_RTS/
UART5_DE | TSC_G2_IO1 | DCMI_D12/
PSSI_D12 | LPGPIO1_P12 | SDMMC2_D3 | SAI1_MCLK_B | TIM17_BKIN | EVENTOUT  |
|  PB5 | UART5_CTS | TSC_G2_IO2 | DCMI_D10/
PSSI_D10 | - | COMP2_OUT | SAI1_SD_B | TIM16_BKIN | EVENTOUT  |
|  PB6 | - | TSC_G2_IO3 | DCMI_D5/PSSI_D5 | - | - | SAI1_FS_B | TIM16_CH1N | EVENTOUT  |
|  PB7 | UART4_CTS | TSC_G2_IO4 | DCMI_VSYNC/
PSSI_RDY | - | FMC_NL | - | TIM17_CH1N | EVENTOUT  |
|  PB8 | SDMMC1_CKIN | FDCAN1_RX | DCMI_D6/PSSI_D6 | SDMMC2_D4 | SDMMC1_D4 | SAI1_MCLK_A | TIM16_CH1 | EVENTOUT  |
|  PB9 | SDMMC1_CDIR | FDCAN1_TX | DCMI_D7/PSSI_D7 | SDMMC2_D5 | SDMMC1_D5 | SAI1_FS_A | TIM17_CH1 | EVENTOUT  |
|  PB10 | LPUART1_RX | TSC_SYNC | OCTOSPIM_P1_CLK | LPGPIO1_P4 | COMP1_OUT | SAI1_SCK_A | - | EVENTOUT  |
|  PB11 | LPUART1_TX | - | OCTOSPIM_
P1_NCS | - | COMP2_OUT | - | - | EVENTOUT  |
|  PB12 | LPUART1_RTS/
LPUART1_DE | TSC_G1_IO1 | OCTOSPIM_
P1_NCLK | - | - | SAI2_FS_A | TIM15_BKIN | EVENTOUT  |
|  PB13 | LPUART1_CTS | TSC_G1_IO2 | - | - | - | SAI2_SCK_A | TIM15_CH1N | EVENTOUT  |
|  PB14 | - | TSC_G1_IO3 | - | - | SDMMC2_D0 | SAI2_MCLK_A | TIM15_CH1 | EVENTOUT  |
|  PB15 | - | - | - | FMC_NBL1 | SDMMC2_D1 | SAI2_SD_A | TIM15_CH2 | EVENTOUT  |Table 29. Alternate function AF8 to AF15 ${ }^{(1)}$ (continued)

|  Port | AF8 | AF9 | AF10 | AF11 | AF12 | AF13 | AF14 | AF15  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   | LPUART1/
SDMMC1/
UART4/5 | CAN1/TSC | CRS/DCMI/
OCTOSPIM_P1/2/
OTG_FS | LPGPIO1/
SDMMC2/
UCPD1/FMC | COMP1/2/FMC/
SDMMC1/2 | LPTIM2/4/
SAI1/2 | LPTIM2/3/
TIM2/15/16/17 | EVENTOUT  |
|  PC0 | LPUART1_RX | - | - | - | SDMMC1_D5 | SAI2_FS_A | LPTIM2_IN1 | EVENTOUT  |
|  PC1 | LPUART1_TX | - | OCTOSPIM_P1_IO4 | - | SDMMC2_CK | SAI1_SD_A | - | EVENTOUT  |
|  PC2 | - | - | OCTOSPIM_P1_IO5 | LPGPIO1_P5 | - | - | - | EVENTOUT  |
|  PC3 | - | - | OCTOSPIM_P1_IO6 | - | - | SAI1_SD_A | LPTIM2_ETR | EVENTOUT  |
|  PC4 | - | - | OCTOSPIM_P1_IO7 | - | - | - | - | EVENTOUT  |
|  PC5 | - | - | - | - | - | - | - | EVENTOUT  |
|  PC6 | SDMMC1_
D0DIR | TSC_G4_IO1 | DCMI_D0/PSSI_D0 | SDMMC2_D6 | SDMMC1_D6 | SAI2_MCLK_A | - | EVENTOUT  |
|  PC7 | SDMMC1_
D123DIR | TSC_G4_IO2 | DCMI_D1/PSSI_D1 | SDMMC2_D7 | SDMMC1_D7 | SAI2_MCLK_B | LPTIM2_CH2 | EVENTOUT  |
|  PC8 | - | TSC_G4_IO3 | DCMI_D2/PSSI_D2 | - | SDMMC1_D0 | - | LPTIM3_CH1 | EVENTOUT  |
|  PC9 | - | TSC_G4_IO4 | OTG_FS_NOE | - | SDMMC1_D1 | - | LPTIM3_CH2 | EVENTOUT  |
|  PC10 | UART4_TX | TSC_G3_IO2 | DCMI_D8/PSSI_D8 | LPGPIO1_P8 | SDMMC1_D2 | SAI2_SCK_B | - | EVENTOUT  |
|  PC11 | UART4_RX | TSC_G3_IO3 | DCMI_D4/PSSI_D4 | UCPD1_
FRSTX2 | SDMMC1_D3 | SAI2_MCLK_B | - | EVENTOUT  |
|  PC12 | UART5_TX | TSC_G3_IO4 | DCMI_D9/PSSI_D9 | LPGPIO1_P10 | SDMMC1_CK | SAI2_SD_B | - | EVENTOUT  |
|  PC13 | - | - | - | - | - | - | - | EVENTOUT  |
|  PC14 | - | - | - | - | - | - | - | EVENTOUT  |
|  PC15 | - | - | - | - | - | - | - | EVENTOUT  |Table 29. Alternate function AF8 to AF15 ${ }^{(1)}$ (continued)

|  Port | AF8 | AF9 | AF10 | AF11 | AF12 | AF13 | AF14 | AF15  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   | LPUART1/ SDMMC1/ UART4/5 | CAN1/TSC | CRS/DCMI/ OCTOSPIM_P1/2/ OTG_FS | LPGPIO1/ SDMMC2/ UCPD1/FMC | COMP1/2/FMC/ SDMMC1/2 | LPTIM2/4/ SAI1/2 | LPTIM2/3/ TIM2/15/16/17 | EVENTOUT  |
|  PD0 | - | FDCAN1_RX | - | - | FMC_D2/FMC_ AD2 | - | - | EVENTOUT  |
|  PD1 | - | FDCAN1_TX | - | - | FMC_D3/FMC_ AD3 | - | - | EVENTOUT  |
|  PD2 | UART5_RX | TSC_SYNC | DCMI_D11/ PSSI_D11 | LPGPIO1_P7 | SDMMC1_CMD | LPTIM4_ETR | - | EVENTOUT  |
|  PD3 | - | - | OCTOSPIM_ P2_NCS | - | FMC_CLK | - | - | EVENTOUT  |
|  PD4 | - | - | OCTOSPIM_P1_IO4 | - | FMC_NOE | - | - | EVENTOUT  |
|  PD5 | - | - | OCTOSPIM_P1_IO5 | - | FMC_NWE | - | - | EVENTOUT  |
|  PD6 | - | - | OCTOSPIM_P1_IO6 | SDMMC2_CK | FMC_NWAIT | SAI1_SD_A | - | EVENTOUT  |
|  PD7 | - | - | OCTOSPIM_P1_IO7 | SDMMC2_CMD | FMC_NCE/ FMC_NE1 | LPTIM4_OUT | - | EVENTOUT  |
|  PD8 | - | - | DCMI_HSYNC/ PSSI_DE | - | FMC_D13/FMC _AD13 | - | - | EVENTOUT  |
|  PD9 | - | - | DCMI_PIXCLK/ PSSI_PDCK | - | FMC_D14/FMC _AD14 | SAI2_MCLK_A | LPTIM3_IN1 | EVENTOUT  |
|  PD10 | - | TSC_G6_IO1 | - | - | FMC_D15/FMC _AD15 | SAI2_SCK_A | LPTIM3_ETR | EVENTOUT  |
|  PD11 | - | TSC_G6_IO2 | - | - | FMC_CLE/ FMC_A16 | SAI2_SD_A | LPTIM2_ETR | EVENTOUT  |
|  PD12 | - | TSC_G6_IO3 | - | - | FMC_ALE/ FMC_A17 | SAI2_FS_A | LPTIM2_IN1 | EVENTOUT  |
|  PD13 | - | TSC_G6_IO4 | - | LPGPIO1_P6 | FMC_A18 | LPTIM4_IN1 | LPTIM2_CH1 | EVENTOUT  |
|  PD14 | - | - | - | - | FMC_D0/FMC_ AD0 | - | LPTIM3_CH1 | EVENTOUT  |
|  PD15 | - | - | - | - | FMC_D1/FMC_ AD1 | - | LPTIM3_CH2 | EVENTOUT  |Table 29. Alternate function AF8 to AF15 ${ }^{(1)}$ (continued)

|  Port | AF8 | AF9 | AF10 | AF11 | AF12 | AF13 | AF14 | AF15  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   | LPUART1/ SDMMC1/ UART4/5 | CAN1/TSC | CRS/DCMI/ OCTOSPIM_P1/2/ OTG_FS | LPGPIO1/ SDMMC2/ UCPD1/FMC | COMP1/2/FMC/ SDMMC1/2 | LPTIM2/4/ SAI1/2 | LPTIM2/3/ TIM2/15/16/17 | EVENTOUT  |
|  PE0 | - | - | DCMI_D2/PSSI_D2 | LPGPIO1_P13 | FMC_NBL0 | - | TIM16_CH1 | EVENTOUT  |
|  PE1 | - | - | DCMI_D3/PSSI_D3 | - | FMC_NBL1 | - | TIM17_CH1 | EVENTOUT  |
|  PE2 | - | TSC_G7_IO1 | - | LPGPIO1_P14 | FMC_A23 | SAI1_MCLK_A | - | EVENTOUT  |
|  PE3 | - | TSC_G7_IO2 | - | LPGPIO1_P15 | FMC_A19 | SAI1_SD_B | - | EVENTOUT  |
|  PE4 | - | TSC_G7_IO3 | DCMI_D4/PSSI_D4 | - | FMC_A20 | SAI1_FS_A | - | EVENTOUT  |
|  PE5 | - | TSC_G7_IO4 | DCMI_D6/PSSI_D6 | - | FMC_A21 | SAI1_SCK_A | - | EVENTOUT  |
|  PE6 | - | - | DCMI_D7/PSSI_D7 | - | FMC_A22 | SAI1_SD_A | - | EVENTOUT  |
|  PE7 | - | - | - | - | FMC_D4/FMC_ AD4 | SAI1_SD_B | - | EVENTOUT  |
|  PE8 | - | - | - | - | FMC_D5/FMC_ AD5 | SAI1_SCK_B | - | EVENTOUT  |
|  PE9 | - | - | OCTOSPIM_P1_NC LK | - | FMC_D6/FMC_ AD6 | SAI1_FS_B | - | EVENTOUT  |
|  PE10 | - | TSC_G5_IO1 | OCTOSPIM_P1_CLK | - | FMC_D7/FMC_ AD7 | SAI1_MCLK_B | - | EVENTOUT  |
|  PE11 | - | TSC_G5_IO2 | OCTOSPIM_ P1_NCS | - | FMC_D8/FMC_ AD8 | - | - | EVENTOUT  |
|  PE12 | - | TSC_G5_IO3 | OCTOSPIM_P1_IO0 | - | FMC_D9/FMC_ AD9 | - | - | EVENTOUT  |
|  PE13 | - | TSC_G5_IO4 | OCTOSPIM_P1_IO1 | - | FMC_D10/FMC _AD10 | - | - | EVENTOUT  |
|  PE14 | - | - | OCTOSPIM_P1_IO2 | - | FMC_D11/FMC _AD11 | - | - | EVENTOUT  |
|  PE15 | - | - | OCTOSPIM_P1_IO3 | - | FMC_D12/FMC _AD12 | - | - | EVENTOUT  |Table 29. Alternate function AF8 to AF15 ${ }^{(1)}$ (continued)

|  Port | AF8 | AF9 | AF10 | AF11 | AF12 | AF13 | AF14 | AF15  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   | LPUART1/
SDMMC1/
UART4/5 | CAN1/TSC | CRS/DCMI/
OCTOSPIM_P1/2/
OTG_FS | LPGPIO1/
SDMMC2/
UCPD1/FMC | COMP1/2/FMC/
SDMMC1/2 | LPTIM2/4/
SAI1/2 | LPTIM2/3/
TIM2/15/16/17 | EVENTOUT  |
|  PF0 | - | - | - | - | FMC_A0 | - | - | EVENTOUT  |
|  PF1 | - | - | - | - | FMC_A1 | - | - | EVENTOUT  |
|  PF2 | - | - | - | - | FMC_A2 | - | - | EVENTOUT  |
|  PF3 | - | - | - | - | FMC_A3 | - | - | EVENTOUT  |
|  PF4 | - | - | - | - | FMC_A4 | - | - | EVENTOUT  |
|  PF5 | - | - | - | - | FMC_A5 | - | - | EVENTOUT  |
|  PF6 | - | - | OCTOSPIM_P1_IO3 | - | - | SAI1_SD_B | - | EVENTOUT  |
|  PF7 | - | FDCAN1_RX | OCTOSPIM_P1_IO2 | - | - | SAI1_MCLK_B | - | EVENTOUT  |
|  PF8 | - | FDCAN1_TX | OCTOSPIM_P1_IO0 | - | - | SAI1_SCK_B | - | EVENTOUT  |
|  PF9 | - | - | OCTOSPIM_P1_IO1 | - | - | SAI1_FS_B | TIM15_CH1 | EVENTOUT  |
|  PF10 | - | - | DCMI_D11/
PSSI_D11 | - | - | SAI1_D3 | TIM15_CH2 | EVENTOUT  |
|  PF11 | - | - | DCMI_D12/
PSSI_D12 | - | - | LPTIM4_IN1 | - | EVENTOUT  |
|  PF12 | - | - | - | - | FMC_A6 | LPTIM4_ETR | - | EVENTOUT  |
|  PF13 | - | - | - | UCPD1,
FRSTX2 | FMC_A7 | LPTIM4_OUT | - | EVENTOUT  |
|  PF14 | - | TSC_G8_IO1 | - | - | FMC_A8 | - | - | EVENTOUT  |
|  PF15 | - | TSC_G8_IO2 | - | - | FMC_A9 | - | - | EVENTOUT  |Table 29. Alternate function AF8 to AF15 ${ }^{(1)}$ (continued)

|  Port |  | AF8 | AF9 | AF10 | AF11 | AF12 | AF13 | AF14 | AF15  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  | LPUART1/
SDMMC1/
UART4/5 | CAN1/TSC | CRS/DCMI/
OCTOSPIM_P1/2/
OTG_FS | LPGPIO1/
SDMMC2/
UCPD1/FMC | COMP1/2/FMC/
SDMMC1/2 | LPTIM2/4/
SAI1/2 | LPTIM2/3/
TIM2/15/16/17 | EVENTOUT  |
|   | PG0 | - | TSC_G8_IO3 | - | - | FMC_A10 | - | - | EVENTOUT  |
|   | PG1 | - | TSC_G8_IO4 | - | - | FMC_A11 | - | - | EVENTOUT  |
|   | PG2 | - | - | - | - | FMC_A12 | SAI2_SCK_B | - | EVENTOUT  |
|   | PG3 | - | - | - | - | FMC_A13 | SAI2_FS_B | - | EVENTOUT  |
|   | PG4 | - | - | - | - | FMC_A14 | SAI2_MCLK_B | - | EVENTOUT  |
|   | PG5 | LPUART1_CTS | - | - | - | FMC_A15 | SAI2_SD_B | - | EVENTOUT  |
|   | PG6 | LPUART1_RTS/
LPUART1_DE | - | - | UCPD1_
FRSTX1 | - | - | - | EVENTOUT  |
|   | PG7 | LPUART1_TX | - | - | UCPD1_
FRSTX2 | FMC_INT | SAI1_MCLK_A | - | EVENTOUT  |
|   | PG8 | LPUART1_RX | - | - | - | - | - | - | EVENTOUT  |
|   | PG9 | - | - | - | - | FMC_NCE/
FMC_NE2 | SAI2_SCK_A | TIM15_CH1N | EVENTOUT  |
|   | PG10 | - | - | - | - | FMC_NE3 | SAI2_FS_A | TIM15_CH1 | EVENTOUT  |
|   | PG11 | - | - | - | - | - | SAI2_MCLK_A | TIM15_CH2 | EVENTOUT  |
|   | PG12 | - | - | - | - | FMC_NE4 | SAI2_SD_A | - | EVENTOUT  |
|   | PG13 | - | - | - | - | FMC_A24 | - | - | EVENTOUT  |
|   | PG14 | - | - | - | - | FMC_A25 | - | - | EVENTOUT  |
|   | PG15 | - | - | DCMI_D13/
PSSI_D13 | - | - | - | - | EVENTOUT  |Table 29. Alternate function AF8 to AF15 ${ }^{(1)}$ (continued)

|  Part | AF8 | AF9 | AF10 | AF11 | AF12 | AF13 | AF14 | AF15  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   | LPUART1/
SDMMC1/
UART4/5 | CAN1/TSC | CRS/DCMI/
OCTOSPIM_P1/2/
OTG_FS | LPGPIO1/
SDMMC2/
UCPD1/FMC | COMP1/2/FMC/
SDMMC1/2 | LPTIM2/4/
SAI1/2 | LPTIM2/3/
TIM2/15/16/17 | EVENTOUT  |
|  PH0 | - | - | - | - | - | - | - | EVENTOUT  |
|  PH1 | - | - | - | - | - | - | - | EVENTOUT  |
|  PH2 | - | - | - | - | - | - | - | EVENTOUT  |
|  PH3 | - | - | - | - | - | - | - | EVENTOUT  |
|  PH4 | - | - | PSSI_D14 | - | - | - | - | EVENTOUT  |
|  PH5 | - | - | DCMI_PIXCLK/
PSSI_PDCK | - | - | - | - | EVENTOUT  |
|  PH6 | - | - | DCMI_D8/PSSI_D8 | - | - | - | - | EVENTOUT  |
|  PH7 | - | - | DCMI_D9/PSSI_D9 | - | - | - | - | EVENTOUT  |
|  PH8 | - | - | DCMI_HSYNC/
PSSI_DE | - | - | - | - | EVENTOUT  |
|  PH9 | - | - | DCMI_D0/PSSI_D0 | - | - | - | - | EVENTOUT  |
|  PH10 | - | - | DCMI_D1/PSSI_D1 | - | - | - | - | EVENTOUT  |
|  PH11 | - | - | DCMI_D2/PSSI_D2 | - | - | - | - | EVENTOUT  |
|  PH12 | - | - | DCMI_D3/PSSI_D3 | - | - | - | - | EVENTOUT  |
|  PH13 | - | FDCAN1_TX | - | - | - | - | - | EVENTOUT  |
|  PH14 | - | FDCAN1_RX | DCMI_D4/PSSI_D4 | - | - | - | - | EVENTOUT  |
|  PH15 | - | - | DCMI_D11/
PSSI_D11 | - | - | - | - | EVENTOUT  |Table 29. Alternate function AF8 to AF15 ${ }^{(1)}$ (continued)

|  Port | AF8 | AF9 | AF10 | AF11 | AF12 | AF13 | AF14 | AF15  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   | LPUART1/
SDMMC1/
UART4/5 | CAN1/TSC | CRS/DCMI/
OCTOSPIM_P1/2/
OTG_FS | LPGPIO1/
SDMMC2/
UCPD1/FMC | COMP1/2/FMC/
SDMMC1/2 | LPTIM2/4/
SAI1/2 | LPTIM2/3/
TIM2/15/16/17 | EVENTOUT  |
|  PI0 | - | - | DCMI_D13/
PSSI_D13 | - | - | - | - | EVENTOUT  |
|  PI1 | - | - | DCMI_D8/PSSI_D8 | - | - | - | - | EVENTOUT  |
|  PI2 | - | - | DCMI_D9/PSSI_D9 | - | - | - | - | EVENTOUT  |
|  PI3 | - | - | DCMI_D10/
PSSI_D10 | - | - | - | - | EVENTOUT  |
|  PI4 | - | - | DCMI_D5/PSSI_D5 | - | - | - | - | EVENTOUT  |
|  PI5 | - | - | DCMI_VSYNC/
PSSI_RDY | - | - | - | - | EVENTOUT  |
|  PI6 | - | - | DCMI_D6/PSSI_D6 | - | - | - | - | EVENTOUT  |
|  PI7 | - | - | DCMI_D7/PSSI_D7 | - | - | - | - | EVENTOUT  |

1. For AF0 to AF7 refer to the previous table.# 5 Electrical characteristics 

### 5.1 Parameter conditions

Unless otherwise specified, all voltages are referenced to $\mathrm{V}_{\mathrm{SS}}$.

### 5.1.1 Minimum and maximum values

Unless otherwise specified, the minimum and maximum values are guaranteed in the worst conditions of ambient temperature, supply voltage and frequencies by tests in production on $100 \%$ of the devices with an ambient temperature at $T_{A}=25^{\circ} \mathrm{C}$ and $T_{A}=T_{A} \max$ (given by the selected temperature range).

Data based on characterization results, design simulation and/or technology characteristics are indicated in the table footnotes, and are not tested in production. Based on characterization, the minimum and maximum values refer to sample tests and represent the mean value plus or minus three times the standard deviation (mean $\pm 3 \sigma$ ).

### 5.1.2 Typical values

Unless otherwise specified, typical data are based on $T_{A}=25^{\circ} \mathrm{C}, V_{D D}=V_{D D A}=3 \mathrm{~V}$. They are given only as design guidelines and are not tested.

Typical ADC accuracy values are determined by characterization of a batch of samples from a standard diffusion lot over the full temperature range and supply voltage range, where $95 \%$ of the devices have an error less than or equal to the value indicated (mean $\pm 2 \sigma$ ).

### 5.1.3 Typical curves

Unless otherwise specified, all typical curves are given only as design guidelines and are not tested.

### 5.1.4 Loading capacitor

The loading conditions used for pin parameter measurement are shown in Figure 22.

### 5.1.5 Pin input voltage

The input voltage measurement on a pin of the device is described in Figure 23.
![img-42.jpeg](img-42.jpeg)

### 5.1.6 Power supply scheme

Each power supply pair (such as $\mathrm{V}_{\mathrm{DD}} / \mathrm{V}_{\mathrm{SS}}$ or $\mathrm{V}_{\mathrm{DDA}} / \mathrm{V}_{\mathrm{SSA}}$ ) must be decoupled with filtering ceramic capacitors as shown in Figure 24 and Figure 25. These capacitors must be placedas close as possible to, or below, the appropriate pins on the underside of the PCB to ensure the proper functionality of the device.

Figure 24. STM32U585xx power supply scheme (without SMPS)
![img-43.jpeg](img-43.jpeg)

Caution: If there are two VCAP pins (UFBGA169 package), each pin must be connected to a $2.2 \mu \mathrm{~F}$ (typical) capacitor.

The external capacitor on VCAP pin requires the following characteristics:

- $\mathrm{C}_{\text {OUT }}=4.7 \mu \mathrm{~F}$ or $2 \times 2.2 \mu \mathrm{~F} \pm 20 \%$
- $\mathrm{C}_{\text {OUT }}$ ESR $<20 \mathrm{~m} \Omega$ at 3 MHz
- $\mathrm{C}_{\text {OUT }}$ rated voltage $\geq 10 \mathrm{~V}$Figure 25. STM32U585xQ power supply scheme (with SMPS)
![img-44.jpeg](img-44.jpeg)

Note: SMPS and LDO regulators provide, in a concurrent way, the $V_{\text {CORE }}$ supply depending on application requirements. However, only one of them is active at the same time. When SMPS is active, it feeds the $V_{\text {CORE }}$ on the two VDD11 pins supplied by the filtered SMPS VLXSMPS output pin. When LDO is active, it supplies the $V_{\text {CORE }}$ and regulates it using the same capacitors on VDD11 pins. It is recommended to add a decoupling capacitor of 100 nF near each VDD11 pin/ball, but it is not mandatory.The external capacitors on VDD11 pins require the following characteristics:

- $\mathrm{C}_{\text {OUT }}=2 \times 2.2 \mu \mathrm{~F} \pm 20 \%$
- $\mathrm{C}_{\text {OUT }} \mathrm{ESR}<20 \mathrm{~m} \Omega$ at 3 MHz
- $\mathrm{C}_{\text {OUT }}$ rated voltage $\geq 10 \mathrm{~V}$

The external capacitor on VDDSMPS pin requires the following characteristics:

- $\mathrm{C}_{\mathrm{IN}}=10 \mu \mathrm{~F} \pm 20 \%$
- $\mathrm{C}_{\mathrm{IN}} \mathrm{ESR}<10 \mathrm{~m} \Omega$ at 3 MHz
- $\mathrm{C}_{\mathrm{IN}}$ rated voltage $\geq 10 \mathrm{~V}$

The external inductance between VLXSMPS and VDD11 requires the following characteristics:

- $\mathrm{L}=2.2 \mu \mathrm{H} \pm 20 \%$
- $\mathrm{LI}_{\mathrm{SAT}}>0.5 \mathrm{~A}$
- $\mathrm{LDCR}<200 \mathrm{~m} \Omega$


# 5.1.7 Current consumption measurement 

The $\mathrm{I}_{\mathrm{DD}}$ parameters given in various tables in the next sections, represent the total MCU consumption including the current supplying $\mathrm{V}_{\mathrm{DD}}, \mathrm{V}_{\mathrm{DDIO2}}, \mathrm{V}_{\mathrm{DDA}}, \mathrm{V}_{\mathrm{DDUSB}}, \mathrm{V}_{\mathrm{BAT}}$ and $\mathrm{V}_{\text {DDSMPS }}$ (if the device embeds the SMPS).

Figure 26. Current consumption measurement
![img-45.jpeg](img-45.jpeg)

### 5.2 Absolute maximum ratings

Stresses above the absolute maximum ratings listed in Table 30, Table 31 and Table 32 may cause permanent damage to the device. These are stress ratings only and the functional operation of the device at these conditions is not implied. Exposure to maximum rating conditions for extended periods may affect device reliability. Device mission profile (application conditions) is compliant with JEDEC JESD47 qualification standard, extended mission profiles are available on demand.Table 30. Voltage characteristics ${ }^{(1)(2)}$

| Symbol | Ratings | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $\mathrm{V}_{\mathrm{DDX}}-\mathrm{V}_{\mathrm{SS}}$ | External main supply voltage (including $\mathrm{V}_{\text {DDSMPS }}, \mathrm{V}_{\mathrm{DDA}}, \mathrm{V}_{\mathrm{DDUSB}}, \mathrm{V}_{\mathrm{BAT}}, \mathrm{V}_{\mathrm{REF}+}$ ) | $-0.3$ | 4.0 | V |
| $\mathrm{V}_{\mathrm{DDIOx}}{ }^{(3)}-\mathrm{V}_{\mathrm{SS}}$ | I/O supply when HSLV $=0$ | $-0.3$ | 4.0 |  |
|  | I/O supply when HSLV $=1$ | $-0.3$ | 2.75 |  |
| $\mathrm{V}_{\mathrm{IN}}{ }^{(4)}$ | Input voltage on FT_xx pins except FT_c pins | $\mathrm{V}_{\mathrm{SS}}-0.3$ | $\begin{gathered} \operatorname{Min}\left(\min \left(\mathrm{V}_{\mathrm{DD}}, \mathrm{V}_{\mathrm{DDA}}, \mathrm{V}_{\mathrm{DDUSB}}, \mathrm{V}_{\mathrm{DDIO} 2}\right)\right. \\ +4.0,6.0)^{(5)(6)} \end{gathered}$ |  |
|  | Input voltage on FT_t pins in $\mathrm{V}_{\text {BAT }}$ mode | $\mathrm{V}_{\mathrm{SS}}-0.3$ | $\begin{gathered} \operatorname{Min}\left(\min \left(\mathrm{V}_{\mathrm{BAT}}, \mathrm{V}_{\mathrm{DDA}}, \mathrm{V}_{\mathrm{DDUSB}}\right.\right. \\ \left.\left.\mathrm{V}_{\mathrm{DDIO2}}\right)+4.0,6.0\right)^{(5)(6)} \end{gathered}$ |  |
| $\mathrm{V}_{\mathrm{IN}}{ }^{(4)}$ | Input voltage on FT_c pins | $\mathrm{V}_{\mathrm{SS}}-0.3$ | 5.5 | V |
|  | Input voltage on any other pins | $\mathrm{V}_{\mathrm{SS}}-0.3$ | 4.0 |  |
| $\mathrm{V}_{\text {REF+ }}-\mathrm{V}_{\text {DDA }}$ | Allowed voltage difference for $\mathrm{V}_{\text {REF+ }}>\mathrm{V}_{\text {DDA }}$ | - | 0.4 |  |
| $\left\|\Delta \mathrm{V}_{\mathrm{DDx}}\right\|$ | Variations between different VDDx power pins of the same domain | - | 50.0 | mV |
| $\left\|\mathrm{V}_{\mathrm{SSx}}-\mathrm{V}_{\mathrm{SS}}\right\|$ | Variations between all the different ground pins ${ }^{(7)}$ | - | 50.0 |  |

1. All main power (VDD, VDDSMPS, VDDA, VDDUSB, VDDIO2, VBAT) and ground (VSS, VSSA, VSSSMPS) pins must always be connected to the external power supply, in the permitted range.
2. The I/O structure options listed in this table can be a concatenation of options including the option explicitly listed. For instance TT_a refers to any TT I/O with _a option. TT_xx refers to any TT I/O and FT_xx refers to any FT I/O.
3. $\mathrm{V}_{\text {DDIO1 }}$ or $\mathrm{V}_{\text {DDIO2 }}$ or $\mathrm{V}_{\mathrm{SW}}, \mathrm{V}_{\text {DDIO1 }}=\mathrm{V}_{\mathrm{DD}}$.
4. $\mathrm{V}_{\text {IN }}$ maximum must always be respected. Refer to Table 31 for the maximum allowed injected current values.
5. To sustain a voltage higher than 4 V , the internal pull-up/pull-down resistors must be disabled.
6. This formula has to be applied only on the power supplies related to the I/O structure described in the pin definition table.
7. Including VREF- pin.

Table 31. Current characteristics

| Symbol | Ratings | Max | Unit |
| :--: | :--: | :--: | :--: |
| $\sum \mathrm{IV}_{\mathrm{DD}}$ | Total current into sum of all $\mathrm{V}_{\mathrm{DD}}$ power lines (source) ${ }^{(1)}$ | 200 | mA |
| $\sum \mathrm{IV}_{\mathrm{SS}}$ | Total current out of sum of all $\mathrm{V}_{\mathrm{SS}}$ ground lines (sink) ${ }^{(1)}$ | 200 |  |
| $\mathrm{IV}_{\mathrm{DD}}$ | Maximum current into each VDD power pin (source) ${ }^{(1)}$ | 100 |  |
| $\mathrm{IV}_{\mathrm{SS}}$ | Maximum current out of each VSS ground pin (sink) ${ }^{(1)}$ | 100 |  |
| $\mathrm{I}_{\mathrm{IO}}$ | Output current sunk by any I/O and control pin | 20 |  |
|  | Output current sourced by any I/O and control pin | 20 |  |
| $\sum \mathrm{I}_{(\text {PIN) }}$ | Total output current sunk by sum of all I/Os and control pins ${ }^{(2)}$ | 120 |  |
|  | Total output current sourced by sum of all I/Os and control pins ${ }^{(2)}$ | 120 |  |
| $\mathrm{I}_{\text {INJ(PIN) }}{ }^{(3)(4)}$ | Injected current on FT_xx, TT_xx, RST pins | $-5 /+0$ |  |
| $\sum \mid_{\text {INJ(PIN) }} \mid$ | Total injected current (sum of all I/Os and control pins) ${ }^{(5)}$ | $\pm 25$ |  |

1. All main power (VDD, VDDSMPS, VDDA, VDDUSB, VDDIO2, VBAT) and ground (VSS, VSSA, VSSSMPS) pins must always be connected to the external power supplies, in the permitted range.2. This current consumption must be correctly distributed over all I/Os and control pins. The total output current must not be sunk/sourced between two consecutive power supply pins, referring to high pin count QFP packages.
3. Positive injection (when $V_{I N}>V_{D D I O x}$ ) is not possible on these I/Os and does not occur for input voltages lower than the specified maximum value.
4. A negative injection is induced by $V_{I N}<V_{S S} \cdot I_{I N J(P I N)}$ must never be exceeded. Refer also to Table 30 for the minimum allowed input voltage values.
5. When several inputs are submitted to a current injection, the maximum $\left.\sum I_{I N J(P I N}\right)$ is the absolute sum of the negative injected currents (instantaneous values).

Table 32. Thermal characteristics

| Symbol | Ratings | Value | Unit |
| :--: | :-- | :--: | :--: |
| $\mathrm{T}_{\text {STG }}$ | Storage temperature range | -65 to +150 | ${ }^{\circ} \mathrm{C}$ |
| $\mathrm{T}_{\mathrm{J}}$ | Maximum junction temperature | 140 |  |# 5.3 Operating conditions 

### 5.3.1 General operating conditions

Table 33. General operating conditions

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V_{D D}$ | Standard operating voltage | IO_VDD_HSLV ${ }^{(1)}=0$ | $1.71^{(2)}$ | - | 3.6 | V |
|  |  | IO_VDD_HSLV = 1 | $1.71^{(2)}$ | - | 2.7 |  |
| $V_{\text {DDSMPS }}$ | Supply voltage for the internal SMPS step-down converter | - | $V_{D D}$ |  |  |  |
| $V_{\text {DDIO2 }}$ | Supply voltage for PG[15:2] I/Os | At least one I/O in PG[15:2] used, IO_VDDIO2_HSLV = 0 | 1.08 | - | 3.6 |  |
|  |  | At least one I/O in PG[15:2] used, IO_VDDIO2_HSLV = 1 | 1.08 | - | 2.7 |  |
|  |  | PG[15:2] I/Os not used | 0 | - | 3.6 |  |
| $V_{\text {DDUSB }}$ | USB supply voltage | USB used | 3.0 | - | 3.6 |  |
|  |  | USB not used | 0 | - | 3.6 |  |
| $V_{\text {DDA }}$ | Analog supply voltage | COMP used | 1.58 | - | 3.6 |  |
|  |  | DAC or OPAMP used | 1.60 |  | 3.6 |  |
|  |  | ADC used | 1.62 | - | 3.6 |  |
|  |  | VREFBUF used (normal mode) | 1.8 | - | 3.6 |  |
|  |  | ADC, DAC, COMP, OPAMP, and VREFBUF not used | 0 | - | 3.6 |  |
| $V_{\text {BAT }}$ | Backup domain supply voltage | - | $1.65^{(3)}$ | - | 3.6 |  |
| $V_{\text {IN }}$ | I/O input voltage | All I/Os except FT_c and TT_xx pins | $-0.3$ | - | $\begin{gathered} \operatorname{Min}\left(\min \left(V_{D D}, V_{D D A}, V_{D D U S B}\right.\right. \\ \left.\left.V_{D D I O 2}\right)+3.6,5.5\right)^{(4)(5)} \end{gathered}$ | V |
|  |  | Input voltage on FT_t pins in $\mathrm{V}_{\text {BAT }}$ mode | $-0.3$ | - | $\begin{gathered} \operatorname{Min}\left(\min \left(V_{B A T}, V_{D D A}\right.\right. \\ \left.\left.V_{D D U S B}, V_{D D I O 2}\right)+3.6\right. \\ \left.5.5\right)^{(4)(5)} \end{gathered}$ |  |
|  |  | FT_c I/Os | $-0.3$ | - | 5.0 |  |
|  |  | TT_xx I/Os | $-0.3$ | - | $V_{D D I O x}+0.3$ |  |
| $I_{\text {IO_SW }}$ | Sum of output current sourced by all I/Os powered by $\mathrm{V}_{\mathrm{SW}}{ }^{(6)}$ | - | - | - | 3 | mA |Table 33. General operating conditions (continued)

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V_{\text {CORE }}$ | Internal regulator ON | Range 1 | 1.15 | 1.21 | 1.27 | V |
|  |  | Range 2 | 1.05 | 1.1 | 1.15 |  |
|  |  | Range 3 | 0.95 | 1.0 | 1.05 |  |
|  |  | Range 4 | 0.81 | 0.9 | 0.99 |  |
| $f_{\text {HCLK }}$ | AHB clock frequency | Range 1 | - | - | 160 | MHz |
|  |  | Range 2 | - | - | 110 |  |
|  |  | Range 3 | - | - | 55 |  |
|  |  | Range 4 | - | - | 25 |  |
| $\begin{aligned} & \mathrm{f}_{\text {PCLKx }} \\ & (\mathrm{x}=1,2,3) \end{aligned}$ | APB1, APB2, APB3 clock frequency | Range 1 | - | - | 160 |  |
|  |  | Range 2 | - | - | 110 |  |
|  |  | Range 3 | - | - | 55 |  |
|  |  | Range 4 | - | - | 25 |  |
| $P_{D}$ | Power dissipation at $\mathrm{T}_{\mathrm{A}}=85^{\circ} \mathrm{C}$ for suffix $6^{(7)}$ | LQFP48 | See Section 6.9: Package thermal characteristics for application appropriate thermal resistance and package. The power dissipation is then calculated according to ambient temperature $\left(T_{A}\right)$ and maximum junction temperature $\left(T_{J}\right)$ and selected thermal resistance. |  |  |  |
|  |  | UFQFPN48 |  |  |  |  |
|  |  | LQFP64 |  |  |  |  |
|  |  | WLCSP90 |  |  |  |  |
|  |  | LQFP100 |  |  |  |  |
|  |  | UFBGA132 |  |  |  |  |
|  |  | LQFP144 |  |  |  |  |
|  |  | UFBGA169 |  |  |  | mW |
| $P_{D}$ | Power dissipation at $\mathrm{T}_{\mathrm{A}}=125^{\circ} \mathrm{C}$ for suffix $3^{(7)}$ | LQFP48 | See Section 6.9: Package thermal characteristics for application appropriate thermal resistance and package. The power dissipation is then calculated according ambient temperature $\left(T_{A}\right)$ and maximum junction temperature $\left(T_{J}\right)$ and selected thermal resistance. |  |  |  |
|  |  | UFQFPN48 |  |  |  |  |
|  |  | LQFP64 |  |  |  |  |
|  |  | WLCSP90 |  |  |  |  |
|  |  | LQFP100 |  |  |  |  |
|  |  | UFBGA132 |  |  |  |  |
|  |  | LQFP144 |  |  |  |  |
|  |  | UFBGA169 |  |  |  |  |Table 33. General operating conditions (continued)

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | Ambient temperature for suffix 6 | Maximum power dissipation | $-40$ | - | 85 | ${ }^{\circ} \mathrm{C}$ |
| TA |  | Low-power dissipation ${ }^{(8)}$ | $-40$ | - | 105 |  |
|  | Ambient temperature for suffix 3 | Maximum power dissipation | $-40$ | - | 125 |  |
|  |  | Low-power dissipation ${ }^{(8)}$ | $-40$ | - | 130 |  |
| TJ | Junction temperature range | Suffix 6 version | $-40$ | - | 105 |  |
|  |  | Suffix 3 version | $-40$ | - | 130 |  |

1. HSLV means high-speed low-voltage mode (refer to the product reference manual).
2. When RESET is released, the functionality is guaranteed down to $\mathrm{V}_{\mathrm{BORx}}$ min.
3. In $\mathrm{V}_{\mathrm{BAT}}$ mode, the functionality is guaranteed down to $\mathrm{V}_{\mathrm{BOR}} \mathrm{V}_{\mathrm{BAT}}$ min.
4. This formula has to be applied only on the power supplies related to the I/O structure described by the pin definition table. The maximum I/O input voltage is the smallest value between $\operatorname{Min}\left(\mathrm{V}_{\mathrm{DD}}, \mathrm{V}_{\mathrm{DDA}}, \mathrm{V}_{\mathrm{DDUSB}}, \mathrm{V}_{\mathrm{DDIO2}}\right)+3.6 \mathrm{~V}$, and 5.5 V .
5. For operation with voltage higher than $\operatorname{Min}\left(\mathrm{V}_{\mathrm{DD}}, \mathrm{V}_{\mathrm{DDA}}, \mathrm{V}_{\mathrm{DDUSB}}, \mathrm{V}_{\mathrm{DDIO2}}\right)+0.3 \mathrm{~V}$, the internal pull-up and pull-down resistors must be disabled.
6. The I/Os powered by $\mathrm{V}_{\mathrm{SW}}$ are:

- PC13, PC14, PC15 when $\mathrm{V}_{\mathrm{DD}}$ is present,
- PC13, PC14, PC15, and all FT_t I/Os in $\mathrm{V}_{\mathrm{BAT}}$ mode.

7. If $T_{A}$ is lower, higher $P_{D}$ values are allowed as long as $T_{J}$ does not exceed $T_{J}$ max (see Section 6.9: Package thermal characteristics).
8. In low-power dissipation state, $\mathrm{T}_{\mathrm{A}}$ can be extended to this range as long as $\mathrm{T}_{\mathrm{J}}$ does not exceed $\mathrm{T}_{\mathrm{J}}$ max (see Section 6.9: Package thermal characteristics).

# 5.3.2 Operating conditions at power-up/power-down 

The parameters given in the table below are derived from tests performed under the ambient temperature condition summarized in Table 33.

Table 34. Operating conditions at power-up/power-down

| Symbol | Parameter | Conditions | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  | $\mathrm{V}_{\mathrm{DD}}$ rise-time rate | - | 0 | $=$ | $\mu \mathrm{s} / \mathrm{V}$ |
| $t_{\text {VDD }}$ |  | $\mathrm{ULPMEN}=0$ (default value) | 20 | $=$ |  |
|  |  | Standby mode, BOR level 0 selected with ULPMEN $=1$ | 250 | $=$ | $\mathrm{ms} / \mathrm{V}$ |# 5.3.3 Embedded reset and power control block characteristics 

The parameters given in the table below are derived from tests performed under the ambient temperature conditions summarized in Table 33.

Table 35. Embedded reset and power control block characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{t}_{\text {RSTTEMPO }}{ }^{(2)}$ | Reset temporization after BOR0 is detected | $\mathrm{V}_{\mathrm{DD}}$ rising | - | - | 900 | $\mu \mathrm{s}$ |
| $\mathrm{V}_{\text {BOR0 }}$ | Brownout reset threshold 0 | Rising edge | 1.6 | 1.66 | 1.71 | V |
|  |  | Falling edge, range 1, 2, 3 | 1.58 | 1.64 | 1.69 |  |
|  |  | Falling edge, range 4 and low-power modes | 1.58 | 1.64 | 1.69 |  |
| $\mathrm{V}_{\text {BOR1 }}$ | Brownout reset threshold 1 | Rising edge | 1.98 | 2.08 | 2.17 |  |
|  |  | Falling edge | 1.9 | 2.00 | 2.1 |  |
| $\mathrm{V}_{\text {BOR2 }}$ | Brownout reset threshold 2 | Rising edge | 2.18 | 2.29 | 2.39 |  |
|  |  | Falling edge | 2.08 | 2.18 | 2.25 |  |
| $\mathrm{V}_{\text {BOR3 }}$ | Brownout reset threshold 3 | Rising edge | 2.48 | 2.59 | 2.7 |  |
|  |  | Falling edge | 2.39 | 2.5 | 2.61 |  |
| $\mathrm{V}_{\text {BOR4 }}$ | Brownout reset threshold 4 | Rising edge | 2.76 | 2.88 | 3.0 |  |
|  |  | Falling edge | 2.67 | 2.79 | 2.9 |  |
| $\mathrm{V}_{\text {PVD0 }}$ | Programmable voltage detector threshold 0 | Rising edge | 2.03 | 2.13 | 2.23 |  |
|  |  | Falling edge | 1.93 | 2.03 | 2.12 |  |
| $\mathrm{V}_{\text {PVD1 }}$ | PVD threshold 1 | Rising edge | 2.18 | 2.29 | 2.39 |  |
|  |  | Falling edge | 2.08 | 2.18 | 2.28 |  |
| $\mathrm{V}_{\text {PVD2 }}$ | PVD threshold 2 | Rising edge | 2.33 | 2.44 | 2.55 |  |
|  |  | Falling edge | 2.23 | 2.34 | 2.44 |  |
| $\mathrm{V}_{\text {PVD3 }}$ | PVD threshold 3 | Rising edge | 2.47 | 2.59 | 2.7 |  |
|  |  | Falling edge | 2.39 | 2.50 | 2.61 |  |
| $\mathrm{V}_{\text {PVD4 }}$ | PVD threshold 4 | Rising edge | 2.6 | 2.72 | 2.83 |  |
|  |  | Falling edge | 2.5 | 2.62 | 2.73 |  |
| $\mathrm{V}_{\text {PVD5 }}$ | PVD threshold 5 | Rising edge | 2.76 | 2.88 | 3.0 |  |
|  |  | Falling edge | 2.66 | 2.78 | 2.9 |  |
| $\mathrm{V}_{\text {PVD6 }}$ | PVD threshold 6 | Rising edge | 2.83 | 2.96 | 3.08 |  |
|  |  | Falling edge | 2.76 | 2.88 | 3.0 |  |
| $\mathrm{V}_{\text {hyst_BOR0 }}$ | Hysteresis voltage of BOR0 | - | - | 20 | - | mV |
| $\mathrm{V}_{\text {hyst_BOR_PVD }}$ | Hysteresis voltage of BOR (except BOR0) and PVD | - | - | 80 | - |  |
| $\mathrm{t}_{\text {BORO }}$ sampling | BOR0 sampling period | ULPMEN $=1$ | - | 30 | 55 | ms |Table 35. Embedded reset and power control block characteristics ${ }^{(1)}$ (continued)

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| ${ }^{I_{D D} \text { _BOR0 }}{ }^{(2)}$ | Additional BOR0 consumption if ULPMEN $=0$ versus ULPMEN $=1$ | Standby mode | - | 60 | - | nA |
| ${ }^{I_{D D} \text { _BOR_PVD }}{ }^{(2)}$ | $\mathrm{BOR}^{(3)}$ (except BOR0) and PVD consumption from $\mathrm{V}_{\mathrm{DD}}{ }^{(4)}$ | - | - | 1 | 1.5 | $\mu \mathrm{A}$ |
| $\mathrm{V}_{\text {BOR_VBAT }}$ | $\mathrm{V}_{\text {BAT }}$ brownout reset threshold | - | 1.58 | - | 1.65 | V |
| ${ }^{\text {I }_{\text {VBAT_BOR }}}$ <br> _sampling | $\mathrm{V}_{\text {BAT }}$ BOR sampling period in $\mathrm{V}_{\text {BAT }}$ mode | MONEN $=0^{(5)}$ | - | 0.5 | 2.5 | s |
| $\mathrm{V}_{\text {AVM1 }}$ | $\mathrm{V}_{\text {DDA }}$ voltage monitor 1 threshold | Rising edge | 1.61 | 1.68 | 1.75 | V |
|  |  | Falling edge | 1.58 | 1.65 | 1.71 |  |
| $\mathrm{V}_{\text {AVM2 }}$ | $\mathrm{V}_{\text {DDA }}$ voltage monitor 2 threshold | Rising edge | 1.77 | 1.86 | 1.95 |  |
|  |  | Falling edge | 1.73 | 1.82 | 1.9 |  |
| $\mathrm{V}_{\text {IO2VM }}$ | $\mathrm{V}_{\text {DDIO2 }}$ voltage monitor threshold | - | 0.96 | 1.01 | 1.05 |  |
| $\mathrm{V}_{\text {UVM }}$ | $\mathrm{V}_{\text {DDUSB }}$ voltage monitor threshold | - | 1.15 | 1.22 | 1.28 |  |
| $\mathrm{V}_{\text {hysI_AVM }}$ | Hysteresis of $\mathrm{V}_{\text {DDA }}$ voltage monitor | - | - | 40 | - | mV |
| ${ }^{\mathrm{I}} \mathrm{DD}_{-} \mathrm{VM}^{(2)}$ | Voltage monitor consumption from $\mathrm{V}_{\mathrm{DD}}$ (AVM1, AVM2, IO2VM or UVM single instance) | - | - | 0.4 | 0.6 | $\mu \mathrm{A}$ |
| ${ }^{\mathrm{I}} \mathrm{DD}_{-} \mathrm{AVM}_{-} \mathrm{A}^{(2)}$ | $\mathrm{V}_{\text {DDA }}$ voltage monitor consumption from $\mathrm{V}_{\text {DDA }}$ (resistor bridge) | - | - | 1.25 | 1.85 |  |

1. Evaluated by characterization and not tested in production, unless otherwise specified.
2. Specified by design. Not tested in production
3. BOR0 is enabled in all modes (except Shutdown), and its consumption is therefore included in the supply current characteristics tables.
4. This is also the consumption saved in Standby mode when ULPMEN $=1$.
5. $\mathrm{V}_{\text {BAT }}$ brownout reset monitoring is discontinuous when MONEN $=0$ in PWR_BDCR1, and is continuous when MONEN $=1$.

# 5.3.4 SMPS characteristics 

Table 36. SMPS characteristics

| Symbol | Parameter | Conditions | Typ | Unit |
| :--: | :--: | :--: | :--: | :--: |
| Freq | Switching frequency (range 1, 2, 3) ${ }^{(1)}$ | $\mathrm{V}_{\mathrm{DD}}>1.9 \mathrm{~V}$ | 3 | MHz |
|  |  | $\mathrm{V}_{\mathrm{DD}}<1.9 \mathrm{~V}$ | 1.5 |  |

1. The SMPS is asynchronous in range 4 and low-power modes.# 5.3.5 Embedded voltage reference 

The parameters given in the table below are derived from tests performed under the ambient temperature and supply voltage conditions summarized in Table 33.

Table 37. Embedded internal voltage reference

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V_{\text {REFINT }}{ }^{(1)}$ | Internal reference voltage | Range 1, 2, 3 | 1.175 | 1.215 | 1.255 | V |
|  |  | Range 4 and low-power modes | 1.170 | 1.215 | 1.260 |  |
| $\mathrm{t}_{\mathrm{S} \text { _vrefint }}{ }^{(2)(3)}$ | ADC sampling time when reading the internal reference voltage | - | 12.65 | - | - | $\mu \mathrm{s}$ |
| $t_{\text {start_vrefint }}{ }^{(3)}$ | Start time of reference voltage buffer when the ADC is enabled | - | - | 4 | 6 |  |
| $\begin{gathered} \mathrm{I}_{\text {DD(VREFINTBUF) }} \\ (3) \end{gathered}$ | $\mathrm{V}_{\text {REFINT }}$ buffer consumption from $\mathrm{V}_{\mathrm{DD}}$ when converted by the ADC | - | - | 1.5 | 2.1 | $\mu \mathrm{A}$ |
| $\Delta \mathrm{V}_{\text {REFINT }}{ }^{(4)}$ | Internal reference voltage spread over the temperature range | $\mathrm{V}_{\mathrm{DD}}=3 \mathrm{~V}$ | - | 6 | 11.5 | mV |
| $\mathrm{T}_{\text {Coeff }}{ }^{(4)}$ | Average temperature coefficient | $-40^{\circ} \mathrm{C}<\mathrm{T}_{\mathrm{J}}<+130^{\circ} \mathrm{C}$ | - | 40 | 125 | $\mathrm{ppm} /{ }^{\circ} \mathrm{C}$ |
| $\mathrm{A}_{\text {Coeff }}{ }^{(3)}$ | Long term stability | 1000 hours, $\mathrm{T}_{\mathrm{J}}=25^{\circ} \mathrm{C}$ | - | 400 | 1000 | ppm |
| $V_{\text {DDCoeff }}{ }^{(4)}$ | Average voltage coefficient | $3.0 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | - | 500 | 2900 | $\mathrm{ppm} / \mathrm{V}$ |
| $\mathrm{V}_{\text {REFINT_DIV1 }}{ }^{(3)}$ | $1 / 4$ reference voltage | - | 24 | 25 | 26 | $\%$ |
| $\mathrm{V}_{\text {REFINT_DIV2 }}{ }^{(3)}$ | $1 / 2$ reference voltage | - | 49 | 50 | 51 | $V_{\text {REFINT }}$ |
| $V_{\text {REFINT_DIV3 }}{ }^{(3)}$ | $3 / 4$ reference voltage | - | 74 | 75 | 76 |  |

1. $\mathrm{V}_{\text {REFINT }}$ does not take into account package and soldering effects.
2. The shortest sampling time for the application can be determined by multiple iterations.
3. Specified by design. Not tested in production.
4. Evaluated by characterization. Not tested in production.Figure 27. $\mathrm{V}_{\text {REFINT }}$ versus temperature
![img-46.jpeg](img-46.jpeg)

# 5.3.6 Supply current characteristics 

The current consumption is a function of several parameters and factors such as the operating voltage, ambient temperature, I/O pin loading, device software configuration, operating frequencies, I/O pin switching rate, program location in memory and executed binary code.
The current consumption is measured as described in Section 5.1.7: Current consumption measurement.

## Typical and maximum current consumption

The MCU is placed under the following conditions:

- All I/O pins are in analog input mode.
- All peripherals are disabled except when explicitly mentioned.
- The Flash memory access time is adjusted with the minimum wait-state number, depending on the $f_{\text {HCLK }}$ frequency (refer to the tables "Number of wait states according to CPU clock (HCLK) frequency" available in the product reference manual).
- When the peripherals are enabled, $f_{\text {PCLK }}=f_{\text {HCLK }}$.
- The voltage scaling range is adjusted to $f_{\text {HCLK }}$ frequency as follows:
- Voltage range 1 for $110 \mathrm{MHz}<f_{\mathrm{HCLK}} \leq 160 \mathrm{MHz}$
- Voltage range 2 for $55 \mathrm{MHz}<f_{\mathrm{HCLK}} \leq 110 \mathrm{MHz}$
- Voltage range 3 for $25 \mathrm{MHz}<f_{\mathrm{HCLK}} \leq 55 \mathrm{MHz}$
- Voltage range 4 for $f_{\mathrm{HCLK}} \leq 25 \mathrm{MHz}$

The parameters given in the tables below are derived from tests performed under ambient temperature and supply voltage conditions summarized in Table 33.Table 38. Current consumption in Run mode on LDO, code with data processing running from Flash memory, ICACHE ON (1-way), prefetch $\mathrm{ON}^{(1)}$

|  $\begin{aligned} & \text { ㅈ } \\ & \text { ㅇ } \end{aligned}$ | Parameter | Conditions |  |  | Typ |  |  |  |  | $\operatorname{Max}^{(2)}$ |  |  |  | Unit  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  | - | Voltage scaling | $\begin{aligned} & \mathrm{f}_{\mathrm{HCLK}} \ & (\mathrm{MHz}) \end{aligned}$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$  |
|   | Supply current in Run mode | $f_{\text {HCLK }}=f_{\text {MSI }}$, all peripherals and AHB/APB disabled, Flash bank 2 in power down, all SRAMs enabled | Range 4 | 24 | 1.75 | 2.10 | 3.10 | 4.65 | 7.70 | 2.60 | 3.40 | 6.40 | 12.00 | 21.00  |
|   |  |  |  | 16 | 1.30 | 1.65 | 2.65 | 4.20 | 7.25 | 2.10 | 2.90 | 5.90 | 11.00 | 20.00  |
|   |  |  |  | 12 | 1.05 | 1.40 | 2.40 | 3.95 | 7.00 | 1.80 | 2.70 | 5.60 | 11.00 | 20.00  |
|   |  |  |  | 4 | 0.49 | 0.82 | 1.85 | 3.40 | 6.40 | 1.20 | 2.00 | 5.00 | 9.80 | 19.00  |
|   |  |  |  | 2 | 0.37 | 0.70 | 1.70 | 3.25 | 6.30 | 1.10 | 1.90 | 4.90 | 9.60 | 19.00  |
|   |  |  |  | 1 | 0.30 | 0.63 | 1.65 | 3.20 | 6.20 | 0.94 | 1.80 | 4.80 | 9.60 | 19.00  |
|   |  |  |  | 0.4 | 0.26 | 0.59 | 1.60 | 3.15 | 6.15 | 0.89 | 1.80 | 4.80 | 9.50 | 19.00  |
|   |  |  |  | 0.1 | 0.24 | 0.57 | 1.55 | 3.15 | 6.15 | 0.87 | 1.80 | 4.70 | 9.50 | 19.00  |
|   |  | $f_{\text {HCLK }}=$ PLL on HSE 16 MHz in bypass mode, all peripherals and AHB/APB disabled, Flash bank 2 in power down, all SRAMs enabled | Range 1 | 160 | 13.50 | 14.50 | 16.00 | 18.50 | 23.50 | 17.00 | 19.00 | 26.00 | 37.00 | 57.00  |
|   |  |  |  | 140 | 12.00 | 12.50 | 14.50 | 17.00 | 21.50 | 15.00 | 17.00 | 24.00 | 35.00 | 55.00  |
|   |  |  |  | 120 | 10.50 | 11.00 | 13.00 | 15.50 | 20.00 | 14.00 | 15.00 | 23.00 | 33.00 | 53.00  |
|   |  |  |  | 110 | 8.80 | 9.35 | 10.50 | 13.00 | 16.50 | 11.00 | 13.00 | 18.00 | 26.00 | 41.00  |
|   |  |  |  | 72 | 6.00 | 6.50 | 10.00 | 10.00 | 14.00 | 7.80 | 9.30 | 15.00 | 23.00 | 38.00  |
|   |  |  |  | 64 | 5.40 | 5.95 | 9.50 | 9.50 | 13.50 | 7.10 | 8.70 | 14.00 | 22.00 | 38.00  |
|   |  | $f_{\text {HCLK }}=f_{\text {HSE }}$ bypass mode, all peripherals and AHB/APB disabled, Flash bank 2 in power down, all SRAMs enabled | Range 3 | 55 | 4.25 | 4.65 | 5.90 | 7.75 | 11.50 | 5.60 | 6.70 | 11.00 | 17.00 | 29.00  |
|   |  |  |  | 32 | 2.70 | 3.10 | 4.30 | 6.10 | 9.60 | 3.80 | 5.00 | 8.80 | 15.00 | 27.00  |

1. The current consumption from SRAM is similar.
2. Evaluated by characterization. Not tested in production.Table 39. Current consumption in Run mode on SMPS, code with data processing running from Flash memory, ICACHE ON (1-way), prefetch $\mathrm{ON}^{(1)}$

| $\begin{aligned} & \text { Symbol } \\ & \text { (i) } \end{aligned}$ | Parameter | Conditions |  |  |  | Typ at $\mathrm{V}_{\mathrm{DD}}=1.8 \mathrm{~V}$ |  |  |  | Max at $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}^{(2)(3)}$ |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | - | Voltage scaling | $\begin{aligned} & \mathrm{f}_{\mathrm{HCLK}} \\ & (\mathrm{MHz}) \end{aligned}$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |
| $\begin{aligned} & \mathrm{I}_{\mathrm{DD}} \\ & \text { (Run) } \end{aligned}$ | Supply current in Run mode | $\mathrm{f}_{\text {HCLK }}=\mathrm{f}_{\text {MSI }}$, <br> all peripherals and AHB/APB <br> disabled, <br> Flash bank 2 in power down, <br> all SRAMs enabled | Range 4 | 24 | 1.15 | 1.35 | 2.05 | 3.10 | 5.20 | 2.30 | 2.40 | 4.50 | 7.80 | 15.00 |
|  |  |  |  | 16 | 0.88 | 1.10 | 1.75 | 2.80 | 4.90 | 1.60 | 2.00 | 4.20 | 7.50 | 15.00 |
|  |  |  |  | 12 | 0.62 | 0.97 | 1.60 | 2.65 | 4.70 | 1.30 | 1.80 | 4.00 | 7.30 | 14.00 |
|  |  |  |  | 4 | 0.34 | 0.56 | 1.20 | 2.20 | 4.40 | 0.77 | 1.40 | 3.50 | 6.80 | 14.00 |
|  |  |  |  | 2 | 0.22 | 0.46 | 1.15 | 2.20 | 4.25 | 0.64 | 1.30 | 3.50 | 6.80 | 14.00 |
|  |  |  |  | 1 | 0.18 | 0.40 | 1.10 | 2.15 | 4.20 | 0.60 | 1.20 | 3.40 | 6.70 | 14.00 |
|  |  |  |  | 0.4 | 0.16 | 0.36 | 1.05 | 2.10 | 4.20 | 0.57 | 1.10 | 3.40 | 6.70 | 14.00 |
|  |  |  |  | 0.1 | 0.15 | 0.34 | 1.05 | 2.10 | 4.20 | 0.55 | 1.10 | 3.40 | 6.70 | 14.00 |
|  |  | $\mathrm{f}_{\text {HCLK }}=$ PLL on HSE 16 MHz in bypass mode, all peripherals and AHB/APB disabled, <br> Flash bank 2 in power down, all SRAMs enabled | Range 1 | 160 | 10.50 | 11.00 | 12.50 | 14.50 | 18.00 | 14.00 | 15.00 | 21.00 | 28.00 | 44.00 | mA |
|  |  |  |  | 140 | 9.30 | 9.85 | 11.00 | 13.00 | 16.50 | 13.00 | 14.00 | 19.00 | 27.00 | 42.00 |
|  |  |  |  | 120 | 8.50 | 9.05 | 10.50 | 12.50 | 16.50 | 11.00 | 13.00 | 18.00 | 26.00 | 42.00 |
|  |  |  |  | 110 | 6.95 | 7.40 | 8.55 | 10.00 | 13.00 | 8.90 | 9.90 | 14.00 | 20.00 | 32.00 |
|  |  |  |  | 72 | 4.35 | 4.70 | 5.65 | 7.10 | 9.80 | 6.00 | 6.80 | 11.00 | 17.00 | 28.00 |
|  |  |  |  | 64 | 3.95 | 4.30 | 5.25 | 6.65 | 9.40 | 5.40 | 6.30 | 11.00 | 16.00 | 27.00 |
|  |  | $\mathrm{f}_{\text {HCLK }}=\mathrm{f}_{\text {HSE }}$ bypass mode, all peripherals and AHB/APB disabled, <br> Flash bank 2 in power down, all SRAMs enabled | Range 3 | 55 | 3.05 | 3.40 | 4.25 | 5.60 | 7.95 | 4.10 | 4.90 | 7.90 | 13.00 | 21.00 |
|  |  |  |  | 32 | 1.85 | 2.10 | 2.85 | 3.95 | 6.15 | 2.70 | 3.40 | 6.20 | 11.00 | 19.00 |

1. The current consumption from SRAM is similar.
2. Evaluated by characterization. Not tested in production.
3. The maximum value is at $\mathrm{V}_{\mathrm{DD}}=1.71 \mathrm{~V}$ in Run mode on SMPS.Table 40. Current consumption in Run mode on SMPS, code with data processing running from Flash memory, ICACHE ON (1-way), prefetch $\mathrm{ON}, \mathrm{V}_{\mathrm{DD}}=3.0 \mathrm{~V}^{(1)}$

| $\begin{aligned} & \text { Symbol } \\ & \text { (i) } \end{aligned}$ | Parameter | Conditions |  |  |  | Typ at $\mathrm{V}_{\mathrm{DD}}=3.0 \mathrm{~V}$ |  |  |  |  | Max at $\mathrm{V}_{\mathrm{DD}}=3.0 \mathrm{~V}^{(2)}$ |  |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | - | Voltage scaling | $\begin{aligned} & \mathrm{f}_{\mathrm{HCLK}} \\ & (\mathrm{MHz}) \end{aligned}$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |  |  |
| $\begin{aligned} & \mathrm{I}_{\mathrm{DD}} \\ & \text { (Run) } \end{aligned}$ | Supply current in Run mode | $\mathrm{f}_{\text {HCLK }}=\mathrm{f}_{\text {MSI }}$, <br> all peripherals and AHB/APB <br> disabled, <br> Flash bank 2 in power down, <br> all SRAMs enabled | Range 4 | 24 | 0.73 | 0.91 | 1.30 | 2.00 | 3.45 | 2.30 | 2.40 | 3.10 | 4.80 | 9.10 | mA |
|  |  |  |  | 16 | 0.60 | 0.71 | 1.15 | 1.80 | 3.25 | 1.60 | 1.90 | 2.70 | 4.60 | 8.80 |  |
|  |  |  |  | 12 | 0.45 | 0.65 | 1.05 | 1.70 | 3.15 | 1.30 | 1.60 | 2.60 | 4.50 | 8.70 |  |
|  |  |  |  | 4 | 0.23 | 0.38 | 0.82 | 1.50 | 2.80 | 0.60 | 0.97 | 2.30 | 4.30 | 8.40 |  |
|  |  |  |  | 2 | 0.17 | 0.31 | 0.74 | 1.40 | 2.85 | 0.49 | 0.84 | 2.20 | 4.20 | 8.40 |  |
|  |  |  |  | 1 | 0.15 | 0.29 | 0.73 | 1.40 | 2.80 | 0.46 | 0.81 | 2.20 | 4.20 | 8.40 |  |
|  |  |  |  | 0.4 | 0.13 | 0.27 | 0.72 | 1.40 | 2.75 | 0.44 | 0.79 | 2.20 | 4.20 | 8.30 |  |
|  |  |  |  | 0.1 | 0.12 | 0.26 | 0.72 | 1.35 | 2.75 | 0.44 | 0.78 | 2.20 | 4.10 | 8.30 |  |
|  |  | $\mathrm{f}_{\text {HCLK }}=$ PLL on HSE 16 MHz in bypass mode, <br> all peripherals and AHB/APB <br> disabled, <br> Flash bank 2 in power down, all SRAMs enabled | Range 1 | 160 | 7.15 | 7.55 | 8.55 | 9.90 | 12.50 | 14.00 | 15.00 | 16.00 | 19.00 | 28.00 |  | mA |
|  |  |  |  | 140 | 6.35 | 6.75 | 7.70 | 9.05 | 11.50 | 13.00 | 13.00 | 15.00 | 17.00 | 27.00 |  |
|  |  |  |  | 120 | 5.80 | 6.20 | 7.20 | 8.60 | 11.00 | 11.00 | 12.00 | 13.00 | 17.00 | 26.00 |  |
|  |  |  |  | 110 | 4.40 | 4.70 | 5.40 | 6.35 | 8.20 | 8.90 | 9.20 | 11.00 | 13.00 | 19.00 |  |
|  |  |  |  | 72 | 3.05 | 3.35 | 4.05 | 5.10 | 7.00 | 6.00 | 6.20 | 7.40 | 11.00 | 18.00 |  |
|  |  |  |  | 64 | 2.80 | 3.10 | 3.80 | 4.80 | 6.70 | 5.40 | 5.70 | 6.90 | 11.00 | 18.00 |  |
|  |  | $\mathrm{f}_{\text {HCLK }}=\mathrm{f}_{\text {HSE }}$ bypass mode, all peripherals and AHB/APB disabled, <br> Flash bank 2 in power down, all SRAMs enabled | Range 3 | 55 | 2.20 | 2.45 | 3.05 | 3.95 | 5.55 | 4.00 | 4.40 | 5.40 | 7.90 | 14.00 |  |
|  |  |  |  | 32 | 1.40 | 1.60 | 2.15 | 2.95 | 4.50 | 2.60 | 3.00 | 4.30 | 6.80 | 13.00 |  |

1. The current consumption from SRAM is similar.
2. Evaluated by characterization. Not tested in production.Table 41. Typical current consumption in Run mode on LDO, with different codes running from Flash memory in low-power mode, ICACHE ON (1-way), prefetch ON

| Symbol | Parameter | Conditions |  |  | Typ |  |  | Unit | Typ |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | - | Voltage scaling | Code | 1.8 V | 3 V | 3.3 V |  | 1.8 V | 3 V | 3.3 V |  |
| $\mathrm{I}_{\text {DD }}$ <br> (Run) | Supply current in Run mode | $\mathrm{f}_{\text {HCLK }}=\mathrm{f}_{\text {MSI }}=24 \mathrm{MHz}$, all peripherals disabled, Flash bank 2 in power down, SRAM2 enabled, SRAM1, SRAM3, SRAM4 in power down | Range 4 | Reduced Code | 1.65 | 1.65 | 1.65 | mA | 68.8 | 68.8 | 68.8 | $\mu \mathrm{A} /$ <br> MHz |
|  |  |  |  | CoreMark | 1.55 | 1.60 | 1.60 |  | 64.6 | 66.7 | 66.7 |  |
|  |  |  |  | SecureMark | 1.80 | 1.80 | 1.80 |  | 75.0 | 75.0 | 75.0 |  |
|  |  |  |  | Dhrystone 2.1 | 1.65 | 1.65 | 1.65 |  | 68.8 | 68.8 | 68.8 |  |
|  |  |  |  | Fibonacci | 1.30 | 1.30 | 1.30 |  | 54.2 | 54.2 | 54.2 |  |
|  |  |  |  | while(1) | 1.20 | 1.20 | 1.20 |  | 50.0 | 50.0 | 50.0 |  |

Table 42. Typical current consumption in Run mode on LDO, with different codes running from Flash memory, ICACHE ON (1-way), prefetch ON ${ }^{(1)}$

| Symbol | Parameter | Conditions |  |  | Typ |  |  | Unit | Typ |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | - | Voltage scaling | Code | 1.8 V | 3 V | 3.3 V |  | 1.8 V | 3 V | 3.3 V |  |
| $\mathrm{I}_{\text {DD }}$ <br> (Run) | Supply current in Run mode | $\mathrm{f}_{\text {HCLK }}=\mathrm{f}_{\text {MSI }}=24 \mathrm{MHz}$, all peripherals disabled, Flash bank 2 in power down, all SRAMs enabled | Range 4 | Reduced Code | 1.75 | 1.75 | 1.75 | mA | 72.9 | 72.9 | 72.9 | $\mu \mathrm{A} /$ <br> MHz |
|  |  |  |  | CoreMark | 1.65 | 1.65 | 1.65 |  | 68.8 | 68.8 | 68.8 |  |
|  |  |  |  | SecureMark | 1.85 | 1.85 | 1.90 |  | 77.1 | 77.1 | 79.2 |  |
|  |  |  |  | Dhrystone 2.1 | 1.75 | 1.75 | 1.75 |  | 72.9 | 72.9 | 72.9 |  |
|  |  |  |  | Fibonacci | 1.40 | 1.40 | 1.40 |  | 58.3 | 58.3 | 58.3 |  |
|  |  |  |  | While(1) | 1.30 | 1.30 | 1.30 |  | 54.2 | 54.2 | 54.2 |  |Table 42. Typical current consumption in Run mode on LDO, with different codes running from Flash memory, ICACHE ON (1-way), prefetch $\mathrm{ON}^{(1)}$ (continued)

| Symbol | Parameter | Conditions |  |  | Typ |  |  | Unit | Typ |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | - | Voltage scaling | Code | 1.8 V | 3 V | 3.3 V |  | 1.8 V | 3 V | 3.3 V |  |
| $\begin{aligned} & \mathrm{I}_{\text {DD }} \\ & \text { (Run) } \end{aligned}$ | Supply current in Run mode | $f_{\text {HCLK }}=f_{\text {PLL }}=160 \mathrm{MHz}$, PLL on HSE 16 MHz in bypass mode, all peripherals disabled, Flash bank 2 in power down, all SRAMs enabled | Range 1 | Reduced Code | 13.50 | 13.50 | 13.50 | mA | 84.4 | 84.4 | 84.4 | $\mu \mathrm{A} /$ <br> MHz |
|  |  |  |  | CoreMark | 13.50 | 13.50 | 13.50 |  | 84.4 | 84.4 | 84.4 |
|  |  |  |  | SecureMark | 15.00 | 15.00 | 15.00 |  | 93.8 | 93.8 | 93.8 |
|  |  |  |  | Dhrystone 2.1 | 14.00 | 14.00 | 14.00 |  | 87.5 | 87.5 | 87.5 |
|  |  |  |  | Fibonacci | 10.50 | 10.50 | 10.50 |  | 65.6 | 65.6 | 65.6 |
|  |  |  |  | While(1) | 10.00 | 10.00 | 10.00 |  | 62.5 | 62.5 | 62.5 |
|  |  | $f_{\text {HCLK }}=f_{\text {PLL }}=110 \mathrm{MHz}$, <br> PLL on HSE 16 MHz in bypass mode, <br> all peripherals disabled, <br> Flash bank 2 in power down, <br> all SRAMs enabled | Range 2 | Reduced Code | 8.80 | 8.80 | 8.85 |  | 80.0 | 80.0 | 80.5 |  |
|  |  |  |  | CoreMark | 8.60 | 8.65 | 8.65 |  | 78.2 | 78.6 | 78.6 |
|  |  |  |  | SecureMark | 9.65 | 9.70 | 9.70 |  | 87.7 | 88.2 | 88.2 |
|  |  |  |  | Dhrystone 2.1 | 9.05 | 9.05 | 9.10 |  | 82.3 | 82.3 | 82.7 |
|  |  |  |  | Fibonacci | 6.80 | 6.80 | 6.80 |  | 61.8 | 61.8 | 61.8 |
|  |  |  |  | While(1) | 6.55 | 6.55 | 6.60 |  | 59.5 | 59.5 | 60.0 |
|  |  | $f_{\text {HCLK }}=f_{\text {HSE }}=55 \mathrm{MHz}$, <br> all peripherals disable, <br> Flash bank 2 in power down, <br> all SRAMs enabled | Range 3 | Reduced Code | 4.15 | 4.25 | 4.25 |  | 75.5 | 77.3 | 77.3 |  |
|  |  |  |  | CoreMark | 4.15 | 4.20 | 4.25 |  | 75.5 | 76.4 | 77.3 |
|  |  |  |  | SecureMark | 4.65 | 4.70 | 4.75 |  | 84.5 | 85.5 | 86.4 |
|  |  |  |  | Dhrystone 2.1 | 4.35 | 4.40 | 4.40 |  | 79.1 | 80.0 | 80.0 |
|  |  |  |  | Fibonacci | 3.25 | 3.30 | 3.35 |  | 59.1 | 60.0 | 60.9 |
|  |  |  |  | While(1) | 3.05 | 3.10 | 3.15 |  | 55.5 | 56.4 | 57.3 |

1. The current consumption from SRAM is similar.Table 43. Typical current consumption in Run mode on SMPS, with different codes running from Flash memory in low-power mode, ICACHE ON (1-way), prefetch ON

| Symbol | Parameter | Conditions |  |  | Typ |  |  | Unit | Typ |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | - | Voltage scaling | Code | 1.8 V | 3 V | 3.3 V |  | 1.8 V | 3 V | 3.3 V |  |
| $\begin{aligned} & \mathrm{f}_{\mathrm{DD}} \\ & \text { (Run) } \end{aligned}$ | Supply current in Run mode | $\mathrm{f}_{\text {HCLK }}=\mathrm{f}_{\text {MSI }}=24 \mathrm{MHz}$, all peripherals disabled, Flash bank 2 in power down, SRAM2 enabled, SRAM1, SRAM3, SRAM4 in power down | Range 4 | Reduced Code | 1.10 | 0.69 | 0.64 | mA | 45.8 | 28.5 | 26.5 | $\mu \mathrm{A} /$ MHz |
|  |  |  |  | CoreMark | 1.05 | 0.68 | 0.61 |  | 43.8 | 28.3 | 25.4 |  |
|  |  |  |  | SecureMark | 1.20 | 0.79 | 0.72 |  | 50.0 | 32.9 | 30.0 |  |
|  |  |  |  | Dhrystone 2.1 | 1.10 | 0.69 | 0.64 |  | 45.8 | 28.5 | 26.7 |  |
|  |  |  |  | Fibonacci | 0.89 | 0.59 | 0.51 |  | 37.1 | 24.4 | 21.3 |  |
|  |  |  |  | while(1) | 0.77 | 0.54 | 0.47 |  | 32.1 | 22.3 | 19.5 |  |

Table 44. Typical current consumption in Run mode on SMPS, with different codes running from Flash memory, ICACHE ON (1-way), prefetch ON ${ }^{(1)}$

| Symbol | Parameter | Conditions |  |  | Typ |  |  | Unit | Typ |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | - | Voltage scaling | Code | 1.8 V | 3 V | 3.3 V |  | 1.8 V | 3 V | 3.3 V |  |
| $\begin{aligned} & \mathrm{f}_{\mathrm{DD}} \\ & \text { (Run) } \end{aligned}$ | Supply current in Run mode | $\mathrm{f}_{\text {HCLK }}=\mathrm{f}_{\text {MSI }}=24 \mathrm{MHz}$, all peripherals disabled, Flash bank 2 in power down, all SRAMs enabled | Range 4 | Reduced Code | 1.15 | 0.73 | 0.68 | mA | 47.9 | 30.2 | 28.3 | $\mu \mathrm{A} /$ MHz |
|  |  |  |  | CoreMark | 1.10 | 0.72 | 0.66 |  | 45.8 | 30.0 | 27.5 |  |
|  |  |  |  | SecureMark | 1.25 | 0.85 | 0.77 |  | 52.1 | 35.2 | 32.1 |  |
|  |  |  |  | Dhrystone 2.1 | 1.15 | 0.75 | 0.69 |  | 47.9 | 31.0 | 28.8 |  |
|  |  |  |  | Fibonacci | 0.97 | 0.65 | 0.58 |  | 40.4 | 26.9 | 24.2 |  |
|  |  |  |  | while(1) | 0.89 | 0.61 | 0.55 |  | 36.9 | 25.2 | 22.7 |  |Table 44. Typical current consumption in Run mode on SMPS, with different codes running from Flash memory, ICACHE ON (1-way), prefetch $\mathrm{ON}^{[1]}$ (continued)

| Symbol | Parameter | Conditions |  |  | Typ |  |  | Unit | Typ |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | - | Voltage scaling | Code | 1.8 V | 3 V | 3.3 V |  | 1.8 V | 3 V | 3.3 V |  |
| $\begin{aligned} & \mathrm{I}_{\mathrm{DD}} \\ & \text { (Run) } \end{aligned}$ | Supply current in Run mode | $f_{\text {HCLK }}=f_{\text {PLL }}=160 \mathrm{MHz}$, PLL on HSE 16 MHz in bypass mode, all peripherals disabled, Flash bank 2 in power down, all SRAMs enabled | Range 1 | Reduced Code | 10.50 | 7.15 | 6.70 | mA | 65.6 | 44.7 | 41.9 | $\mu \mathrm{A} /$ MHz |
|  |  |  |  | CoreMark | 10.50 | 7.05 | 6.55 |  | 65.6 | 44.1 | 40.9 |
|  |  |  |  | SecureMark | 11.50 | 7.85 | 7.35 |  | 71.9 | 49.1 | 45.9 |
|  |  |  |  | Dhrystone 2.1 | 11.00 | 7.40 | 6.90 |  | 68.8 | 46.3 | 43.1 |
|  |  |  |  | Fibonacci | 8.25 | 5.65 | 5.30 |  | 51.6 | 35.3 | 33.1 |
|  |  |  |  | while(1) | 7.90 | 5.45 | 5.10 |  | 49.4 | 34.1 | 31.9 |
|  |  | $f_{\text {HCLK }}=f_{\text {PLL }}=110 \mathrm{MHz}$, PLL on HSE 16 MHz in bypass mode, all peripherals disabled, Flash bank 2 in power down, all SRAMs enabled | Range 2 | Reduced Code | 6.40 | 4.40 | 4.15 |  | 58.2 | 40.0 | 37.7 |  |
|  |  |  |  | CoreMark | 6.25 | 4.30 | 4.05 |  | 56.8 | 39.1 | 36.8 |
|  |  |  |  | SecureMark | 7.00 | 4.80 | 4.50 |  | 63.6 | 43.6 | 40.9 |
|  |  |  |  | Dhrystone 2.1 | 6.55 | 4.50 | 4.25 |  | 59.5 | 40.9 | 38.6 |
|  |  |  |  | Fibonacci | 5.00 | 3.50 | 3.30 |  | 45.5 | 31.8 | 30.0 |
|  |  |  |  | while(1) | 4.80 | 3.35 | 3.20 |  | 43.6 | 30.5 | 29.1 |
|  |  | $f_{\text {HCLK }}=f_{\text {HSE }}=55 \mathrm{MHz}$, all peripherals disabled, Flash bank 2 in power down, all SRAMs enabled | Range 3 | Reduced Code | 3.05 | 2.20 | 2.15 |  | 55.5 | 40.0 | 39.1 |  |
|  |  |  |  | CoreMark | 3.05 | 2.20 | 2.10 |  | 55.5 | 40.0 | 38.2 |  |
|  |  |  |  | SecureMark | 3.40 | 2.45 | 2.30 |  | 61.8 | 44.5 | 41.8 |  |
|  |  |  |  | Dhrystone 2.1 | 3.20 | 2.30 | 2.20 |  | 58.2 | 41.8 | 40.0 |  |
|  |  |  |  | Fibonacci | 2.40 | 1.80 | 1.75 |  | 43.6 | 32.7 | 31.8 |  |
|  |  |  |  | while(1) | 2.30 | 1.70 | 1.65 |  | 41.8 | 30.9 | 30.0 |  |

1. The current consumption from SRAM is similar.Table 45. Current consumption in Sleep mode on LDO, Flash memory in power down

| Symbol | Parameter | Conditions |  |  | Typ |  |  |  | $\operatorname{Max}^{(1)}$ |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | - | Voltage scaling | $\mathrm{f}_{\text {HCLK }}$ <br> (MHz) | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |
| $\mathrm{I}_{\text {DD }}$ <br> (Sleep) | Supply current in Sleep mode | $\mathrm{f}_{\text {HCLK }}=\mathrm{f}_{\text {MSI }}$, all peripherals disabled | Range 4 | 24 | 0.61 | 0.94 | 1.95 | 3.50 | 6.50 | 1.20 | 2.10 | 5.00 | 9.70 | 19.00 |
|  |  |  |  | 16 | 0.49 | 0.81 | 1.80 | 3.35 | 6.40 | 1.10 | 1.90 | 4.90 | 9.50 | 19.00 |
|  |  |  |  | 12 | 0.43 | 0.75 | 1.75 | 3.30 | 6.30 | 0.95 | 1.90 | 4.80 | 9.50 | 19.00 |
|  |  |  |  | 4 | 0.25 | 0.58 | 1.55 | 3.10 | 6.15 | 0.76 | 1.70 | 4.60 | 9.30 | 19.00 |
|  |  |  |  | 2 | 0.22 | 0.55 | 1.55 | 3.10 | 6.10 | 0.72 | 1.60 | 4.60 | 9.30 | 19.00 |
|  |  |  |  | 1 | 0.21 | 0.53 | 1.55 | 3.05 | 6.10 | 0.71 | 1.60 | 4.60 | 9.20 | 19.00 |
|  |  |  |  | 0.4 | 0.19 | 0.52 | 1.50 | 3.05 | 6.05 | 0.69 | 1.60 | 4.50 | 9.20 | 19.00 |
|  |  |  |  | 0.1 | 0.19 | 0.52 | 1.50 | 3.05 | 6.10 | 0.69 | 1.60 | 4.50 | 9.20 | 19.00 |
|  | $\mathrm{f}_{\text {DD }}$ <br> (Sleep) |  |  | Range 1 | 160 | 4.35 | 4.95 | 6.65 | 9.10 | 13.50 | 6.10 | 8.10 | 15.00 | 26.00 | 46.00 |
|  |  |  |  | 140 | 3.90 | 4.50 | 6.15 | 8.65 | 13.50 | 5.60 | 7.60 | 15.00 | 25.00 | 46.00 |
|  |  |  |  | 120 | 3.45 | 4.05 | 5.75 | 8.20 | 13.00 | 5.10 | 7.10 | 14.00 | 25.00 | 46.00 |
|  |  |  |  | Range 2 | 110 | 3.25 | 3.75 | 5.20 | 7.35 | 11.50 | 4.50 | 6.00 | 12.00 | 20.00 | 35.00 |
|  |  |  |  | 72 | 2.15 | 2.65 | 4.05 | 6.15 | 10.00 | 3.30 | 4.80 | 9.90 | 18.00 | 34.00 |
|  |  |  |  | 64 | 2.00 | 2.50 | 3.90 | 6.00 | 9.95 | 3.20 | 4.70 | 9.80 | 18.00 | 33.00 |
|  |  | $\mathrm{f}_{\text {HCLK }}=\mathrm{f}_{\text {HSE }}$ bypass mode, all peripherals disabled | Range 3 | 55 | 1.45 | 1.85 | 3.05 | 4.85 | 8.40 | 2.30 | 3.40 | 7.30 | 14.00 | 26.00 |
|  |  |  |  | 32 | 1.00 | 1.40 | 2.60 | 4.40 | 7.85 | 1.80 | 2.90 | 6.80 | 13.00 | 25.00 |

1. Evaluated by characterization. Not tested in production.Table 46. Current consumption in Sleep mode on SMPS, Flash memory in power down

| Symbol | Parameter | Conditions |  |  |  | Typ at $\mathrm{V}_{\mathrm{DD}}=1.8 \mathrm{~V}$ |  |  |  | Max at $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}^{(1)(2)}$ |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | - | Voltage scaling | $\mathrm{f}_{\text {HCLK }}$ (MHz) | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |
| $\begin{aligned} & \mathrm{f}_{\mathrm{DD}} \\ & \text { (Sleep) } \end{aligned}$ | Supply current in Sleep mode | $\mathrm{f}_{\text {HCLK }}=\mathrm{f}_{\text {MSI }}$, all peripherals disabled | Range 4 | 24 | 0.41 | 0.63 | 1.25 | 2.25 | 4.40 | 0.73 | 1.40 | 3.60 | 6.80 | 14.00 |
|  |  |  |  | 16 | 0.27 | 0.53 | 1.20 | 2.20 | 4.30 | 0.57 | 1.30 | 3.50 | 6.70 | 14.00 |
|  |  |  |  | 12 | 0.24 | 0.48 | 1.15 | 2.20 | 4.25 | 0.53 | 1.20 | 3.50 | 6.70 | 14.00 |
|  |  |  |  | 4 | 0.14 | 0.34 | 1.05 | 2.05 | 4.10 | 0.42 | 1.10 | 3.40 | 6.50 | 13.00 |
|  |  |  |  | 2 | 0.12 | 0.34 | 1.05 | 2.05 | 4.10 | 0.39 | 1.00 | 3.40 | 6.50 | 13.00 |
|  |  |  |  | 1 | 0.11 | 0.33 | 1.05 | 2.05 | 4.10 | 0.38 | 0.99 | 3.40 | 6.50 | 13.00 |
|  |  |  |  | 0.4 | 0.10 | 0.31 | 1.05 | 2.05 | 4.10 | 0.38 | 0.97 | 3.40 | 6.50 | 13.00 |
|  |  |  |  | 0.1 | 0.10 | 0.31 | 1.05 | 2.05 | 4.10 | 0.37 | 0.97 | 3.40 | 6.50 | 13.00 |
|  |  | $\mathrm{f}_{\text {HCLK }}=$ PLL on HSE 16 MHz in bypass mode, all peripherals disabled | Range 1 | 160 | 3.50 | 3.95 | 5.20 | 7.00 | 10.50 | 4.80 | 6.20 | 12.00 | 19.00 | 34.00 |
|  |  |  |  | 140 | 3.10 | 3.60 | 4.80 | 6.60 | 10.00 | 4.30 | 5.80 | 12.00 | 19.00 | 34.00 |
|  |  |  |  | 120 | 2.80 | 3.25 | 4.50 | 6.30 | 9.70 | 4.00 | 5.40 | 11.00 | 19.00 | 33.00 |
|  |  |  | Range 2 | 110 | 2.60 | 3.00 | 4.10 | 5.75 | 8.65 | 3.50 | 4.70 | 8.80 | 15.00 | 26.00 |
|  |  |  |  | 72 | 1.65 | 2.00 | 2.90 | 4.30 | 7.00 | 2.40 | 3.50 | 7.40 | 13.00 | 24.00 |
|  |  |  |  | 64 | 1.55 | 1.90 | 2.80 | 4.20 | 6.90 | 2.30 | 3.40 | 7.30 | 13.00 | 24.00 |
|  |  | $\mathrm{f}_{\text {HCLK }}=\mathrm{f}_{\text {HSE }}$ bypass mode, all peripherals disabled | Range 3 | 55 | 1.10 | 1.40 | 2.25 | 3.55 | 5.90 | 1.70 | 2.50 | 5.60 | 9.80 | 19.00 |
|  |  |  |  | 32 | 0.85 | 1.10 | 1.90 | 3.15 | 5.60 | 1.40 | 2.20 | 5.10 | 9.40 | 18.00 |

1. Evaluated by characterization. Not tested in production.
2. The maximum value is at $\mathrm{V}_{\mathrm{DD}}=1.71 \mathrm{~V}$ in Sleep mode on SMPS.Table 47. Current consumption in Sleep mode on SMPS, Flash memory in power down, $\mathrm{V}_{\mathrm{DD}}=3.0 \mathrm{~V}$

| Symbol | Parameter | Conditions |  |  |  | Typ at $\mathrm{V}_{\mathrm{DD}}=3.0 \mathrm{~V}$ |  |  |  |  | Max at $\mathrm{V}_{\mathrm{DD}}=3.0 \mathrm{~V}^{(1)}$ |  |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | - | Voltage scaling | $\begin{aligned} & \mathrm{f}_{\mathrm{HCLK}} \\ & (\mathrm{MHz}) \end{aligned}$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |  |  |
| $\mathrm{I}_{\text {DD }}$ <br> (Sleep) | Supply current in Sleep mode | $\mathrm{f}_{\text {HCLK }}=\mathrm{f}_{\text {MSI }}$, all peripherals disabled | Range 4 | 24 | 0.26 | 0.40 | 0.83 | 1.50 | 2.80 | 0.66 | 1.20 | 2.20 | 4.20 | 8.20 | mA |
|  |  |  |  | 16 | 0.20 | 0.33 | 0.77 | 1.40 | 2.80 | 0.54 | 0.99 | 2.10 | 4.10 | 8.20 |  |
|  |  |  |  | 12 | 0.17 | 0.31 | 0.75 | 1.40 | 2.75 | 0.49 | 0.92 | 2.10 | 4.10 | 8.10 |  |
|  |  |  |  | 4 | 0.10 | 0.24 | 0.66 | 1.30 | 2.70 | 0.30 | 0.71 | 2.00 | 3.90 | 8.10 |  |
|  |  |  |  | 2 | 0.08 | 0.22 | 0.66 | 1.30 | 2.65 | 0.27 | 0.68 | 2.00 | 3.90 | 8.00 |  |
|  |  |  |  | 1 | 0.08 | 0.22 | 0.66 | 1.30 | 2.65 | 0.26 | 0.67 | 2.00 | 3.90 | 8.00 |  |
|  |  |  |  | 0.4 | 0.07 | 0.21 | 0.65 | 1.30 | 2.65 | 0.26 | 0.64 | 2.00 | 3.90 | 8.00 |  |
|  |  |  |  | 0.1 | 0.07 | 0.21 | 0.65 | 1.30 | 2.65 | 0.26 | 0.65 | 2.00 | 3.90 | 8.00 |  |
|  |  | $\mathrm{f}_{\text {HCLK }}=$ PLL on HSE 16 MHz in bypass mode, all peripherals disabled | Range 1 | 160 | 2.50 | 2.85 | 3.75 | 5.05 | 7.40 | 4.50 | 5.00 | 7.40 | 13.00 | 22.00 |  |
|  |  |  |  | 140 | 2.25 | 2.60 | 3.50 | 4.75 | 7.15 | 4.00 | 4.60 | 7.20 | 12.00 | 22.00 |  |
|  |  |  |  | 120 | 2.05 | 2.40 | 3.25 | 4.55 | 6.90 | 3.60 | 4.20 | 6.90 | 12.00 | 21.00 |  |
|  |  |  | Range 2 | 110 | 1.95 | 2.25 | 3.00 | 4.10 | 6.05 | 3.20 | 3.60 | 5.70 | 9.30 | 17.00 |  |
|  |  |  |  | 72 | 1.30 | 1.55 | 2.20 | 3.20 | 5.10 | 2.20 | 2.60 | 4.80 | 8.30 | 16.00 |  |
|  |  |  |  | 64 | 1.20 | 1.45 | 2.15 | 3.15 | 5.00 | 2.00 | 2.50 | 4.70 | 8.20 | 16.00 |  |
|  |  | $\mathrm{f}_{\text {HCLK }}=\mathrm{f}_{\text {HSE }}$ bypass mode, all peripherals disabled | Range 3 | 55 | 0.92 | 1.10 | 1.70 | 2.55 | 4.15 | 1.40 | 1.90 | 3.60 | 6.30 | 12.00 |  |
|  |  |  |  | 32 | 0.70 | 0.89 | 1.45 | 2.30 | 3.95 | 1.10 | 1.60 | 3.30 | 6.00 | 12.00 |  |

1. Evaluated by characterization. Not tested in production.Table 48. SRAM1/SRAM3 current consumption in Run/Sleep mode with LDO and SMPS

| Symbol | Parameter | Conditions |  |  |  | Typ |  |  |  |  | Max |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | - | Voltage scaling | $\mathrm{f}_{\text {HCLK }}$ $(\mathrm{MHz})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |  |
| $\mathrm{I}_{\text {DD }}$ <br> (SRAM1) | LDO | SRAM1 supply current in Run/Sleep mode (SRAM1PD = 1 versus SRAM1PD = 0) | Range 4 | 24 | 0.02 | 0.05 | 0.16 | 0.33 | 0.68 | 0.06 | 0.15 | 0.48 | 1.00 | 2.05 | mA |
|  |  |  | Range 1 | 160 | 0.04 | 0.10 | 0.28 | 0.55 | 1.07 | 0.15 | 0.30 | 0.83 | 1.65 | 3.20 |  |
|  |  |  | Range 2 | 110 | 0.03 | 0.08 | 0.23 | 0.47 | 0.94 | 0.11 | 0.24 | 0.70 | 1.41 | 2.82 |  |
|  |  |  | Range 3 | 55 | 0.02 | 0.06 | 0.19 | 0.40 | 0.81 | 0.08 | 0.19 | 0.58 | 1.20 | 2.43 |  |
| $\mathrm{I}_{\text {DD }}$ <br> (SRAM3) |  | SRAM3 supply current in Run/Sleep mode (SRAM3PD = 1 versus SRAM3PD = 0) | Range 4 | 24 | 0.04 | 0.13 | 0.41 | 0.87 | 1.78 | 0.15 | 0.39 | 1.24 | 2.62 | 5.34 |  |
|  |  |  | Range 1 | 160 | 0.11 | 0.26 | 0.73 | 1.44 | 2.80 | 0.39 | 0.79 | 2.18 | 4.31 | 8.40 |  |
|  |  |  | Range 2 | 110 | 0.08 | 0.21 | 0.60 | 1.22 | 2.44 | 0.28 | 0.62 | 1.81 | 3.67 | 7.32 |  |
|  |  |  | Range 3 | 55 | 0.06 | 0.16 | 0.50 | 1.04 | 2.09 | 0.20 | 0.49 | 1.50 | 3.11 | 6.28 |  |
| $\mathrm{I}_{\text {DD }}$ <br> (SRAM1) | SMPS, $V_{D D}=3.0 \mathrm{~V}$ | SRAM1 supply current in Run/Sleep mode (SRAM1PD = 1 versus SRAM1PD = 0) | Range 4 | 24 | 0.01 | 0.02 | 0.06 | 0.10 | 0.26 | 0.02 | 0.06 | 0.19 | 0.31 | 0.78 |  |
|  |  |  | Range 1 | 160 | 0.02 | 0.05 | 0.14 | 0.28 | 0.55 | 0.07 | 0.15 | 0.43 | 0.84 | 1.64 |  |
|  |  |  | Range 2 | 110 | 0.01 | 0.04 | 0.12 | 0.23 | 0.46 | 0.05 | 0.12 | 0.36 | 0.70 | 1.37 |  |
|  |  |  | Range 3 | 55 | 0.01 | 0.03 | 0.09 | 0.18 | 0.36 | 0.04 | 0.09 | 0.27 | 0.55 | 1.09 |  |
| $\mathrm{I}_{\text {DD }}$ <br> (SRAM3) |  | SRAM3 supply current in Run/Sleep mode (SRAM3PD = 1 versus SRAM3PD = 0) | Range 4 | 24 | 0.02 | 0.05 | 0.17 | 0.32 | 0.69 | 0.06 | 0.16 | 0.51 | 0.95 | 2.07 |  |
|  |  |  | Range 1 | 160 | 0.06 | 0.13 | 0.37 | 0.73 | 1.43 | 0.20 | 0.40 | 1.12 | 2.20 | 4.28 |  |
|  |  |  | Range 2 | 100 | 0.04 | 0.10 | 0.30 | 0.61 | 1.19 | 0.14 | 0.31 | 0.91 | 1.84 | 3.57 |  |
|  |  |  | Range 3 | 55 | 0.03 | 0.08 | 0.23 | 0.48 | 0.95 | 0.09 | 0.23 | 0.70 | 1.45 | 2.86 |  |Table 48. SRAM1/SRAM3 current consumption in Run/Sleep mode with LDO and SMPS (continued)

| Symbol | Parameter | Conditions |  |  |  | Typ |  |  |  |  | Max |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | - | Voltage scaling | $\mathrm{f}_{\mathrm{HCLK}}$ <br> (MHz) | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |  |
| $\mathrm{I}_{\text {DD }}$ <br> (SRAM1) | SMPS $^{(1)}$ | SRAM1 supply current in Run/Sleep mode (SRAM1PD $=1$ versus SRAM1PD $=0$ ) | Range 4 | 24 | 0.01 | 0.03 | 0.11 | 0.17 | 0.43 | 0.04 | 0.11 | 0.34 | 0.55 | 1.37 | mA |
|  |  |  | Range 1 | 160 | 0.03 | 0.09 | 0.24 | 0.47 | 0.91 | 0.13 | 0.27 | 0.75 | 1.47 | 2.88 |  |
|  |  |  | Range 2 | 110 | 0.02 | 0.07 | 0.20 | 0.39 | 0.76 | 0.09 | 0.21 | 0.63 | 1.23 | 2.41 |  |
|  |  |  | Range 3 | 55 | 0.02 | 0.05 | 0.15 | 0.31 | 0.60 | 0.06 | 0.16 | 0.48 | 0.97 | 1.91 |  |
| $\mathrm{I}_{\text {DD }}$ <br> (SRAM3) |  | SRAM3 supply current in Run/Sleep mode (SRAM3PD $=1$ versus SRAM3PD $=0$ ) | Range 4 | 24 | 0.03 | 0.09 | 0.28 | 0.53 | 1.15 | 0.11 | 0.28 | 0.89 | 1.66 | 3.62 |  |
|  |  |  | Range 1 | 160 | 0.09 | 0.22 | 0.62 | 1.22 | 2.38 | 0.35 | 0.71 | 1.96 | 3.87 | 7.52 |  |
|  |  |  | Range 2 | 100 | 0.06 | 0.17 | 0.51 | 1.02 | 1.98 | 0.24 | 0.54 | 1.60 | 3.22 | 6.26 |  |
|  |  |  | Range 3 | 55 | 0.04 | 0.13 | 0.39 | 0.80 | 1.59 | 0.16 | 0.40 | 1.24 | 2.54 | 5.01 |  |

1. The typical value is measured at $\mathrm{V}_{\mathrm{DD}}=1.8 \mathrm{~V}$. The maximum value is for $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ and is at $\mathrm{V}_{\mathrm{DD}}=1.71 \mathrm{~V}$ in Run/Sleep mode on SMPS.

Table 49. Static power consumption of Flash banks, when supplied by LDO/SMPS

| Symbol | Parameter | Typ |  |  |  |  | Max |  |  |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |  |  |
| $\begin{gathered} \mathrm{I}_{\text {DD }} \\ \text { (Flash_Bank1) } \end{gathered}$ | Flash bank 1 static consumption in normal mode (PD1 $=1$ versus PD1 $=0$ ) | 45.0 | 50.0 | 50.0 | 50.0 | 100.0 | 100.0 | 100.0 | 100.0 | 100.0 | 100.0 | 150.0 | $\mu \mathrm{A}$ |
| $\begin{gathered} \mathrm{I}_{\text {DD }} \\ \text { (Flash_Bank2) } \end{gathered}$ | Flash bank 2 static consumption in normal mode (PD2 $=1$ versus PD2 $=0$ ) | 45.0 | 50.0 | 50.0 | 50.0 | 100.0 | 100.0 | 100.0 | 100.0 | 100.0 | 100.0 | 150.0 |  |
| $\begin{gathered} \mathrm{I}_{\text {DD }} \\ \text { (Flash_Bank_LPM) } \end{gathered}$ | One Flash bank additional static consumption in normal mode versus low-power mode (LPM $=0$ versus LPM $=1$ ) | 25.0 | 25.0 | 25.0 | 25.0 | 50.0 | 40.0 | 40.0 | 40.0 | 40.0 | 40.0 | 70.0 |  |

1. When one bank is in power down, this consumption is saved. When Flash memory is in power down in Sleep mode (SLEEP_PD =1), Bank 1 and Bank 2 are in power down.
2. If no bank is in power-down, the Flash memory additional static consumption in normal mode versus low-power mode is $2 \times \mathrm{I}_{\text {DD(Fash_Bank_LPM) }}$.Table 50. Current consumption in Stop 0 mode on LDO

|  Symbol | Parameter | Conditions | Typ |  |  |  |  | Max $^{(1)}$ |  |  |  |  | Unit  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |   |
|  ${ }^{1}$ DD(Stop 0) | Supply current in Stop 0 mode, regulator in Range 4, RTC disabled, 8 -Kbyte SRAM2 + ICACHE retained | 1.8 | 110 | 280 | 770 | 1500 | 3000 | 400 | 840 | 2400 | 4500 | 9000 | $\mu \mathrm{A}$  |
|   |  | 2.4 | 115 | 290 | 805 | 1600 | 3050 | 420 | 870 | 2500 | 4800 | 9200 |   |
|   |  | 3.0 | 115 | 295 | 820 | 1600 | 3150 | 420 | 890 | 2500 | 4800 | 9500 |   |
|   |  | 3.3 | 115 | 295 | 820 | 1600 | 3150 | 420 | 890 | 2500 | 4800 | 9500 |   |
|   |  | 3.6 | 115 | 295 | 825 | 1600 | 3150 | 420 | 890 | 2500 | 4800 | 9500 |   |
|   | Supply current in Stop 0 mode, regulator in Range 4, RTC disabled, All SRAMs retained | 1.8 | 125 | 305 | 840 | 1650 | 3300 | 460 | 920 | 2600 | 5000 | 9900 |   |
|   |  | 2.4 | 125 | 315 | 875 | 1750 | 3400 | 460 | 950 | 2700 | 5300 | 11000 |   |
|   |  | 3.0 | 125 | 320 | 895 | 1800 | 3500 | 460 | 960 | 2700 | 5400 | 11000 |   |
|   |  | 3.3 | 130 | 320 | 890 | 1750 | 3500 | 470 | 960 | 2700 | 5300 | 11000 |   |
|   |  | 3.6 | 130 | 320 | 895 | 1800 | 3500 | 470 | 960 | 2700 | 5400 | 11000 |   |

1. Evaluated by characterization. Not tested in production.Table 51. Current consumption in Stop 0 mode on SMPS

|  Symbol | Parameter | Conditions | Typ |  |  |  |  | Max $^{(1)}$ |  |  |  |  | Unit  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |   |
|  $\mathrm{I}_{\text {DD(Stop 0) }}$ | Supply current in Stop 0 mode, regulator in Range 4, RTC disabled, 8 -Kbyte SRAM2 + ICACHE retained | 1.8 | 54.5 | 160 | 535 | 1050 | 2100 | 200 | 480 | 1700 | 3200 | 6300 | $\mu \mathrm{A}$  |
|   |  | 2.4 | 38.5 | 115 | 360 | 890 | 1650 | 140 | 350 | 1100 | 2700 | 5000 |   |
|   |  | 3.0 | 39.5 | 115 | 340 | 685 | 1400 | 150 | 350 | 1100 | 2100 | 4200 |   |
|   |  | 3.3 | 37.0 | 105 | 315 | 640 | 1300 | 140 | 320 | 950 | 2000 | 3900 |   |
|   |  | 3.6 | 35.5 | 100 | 295 | 605 | 1200 | 130 | 300 | 890 | 1900 | 3600 |   |
|   | Supply current in Stop 0 mode, regulator in Range 4, RTC disabled, All SRAM retained | 1.8 | 61.5 | 175 | 515 | 1200 | 2350 | 230 | 530 | 1600 | 3600 | 7100 |   |
|   |  | 2.4 | 43.5 | 125 | 400 | 930 | 1850 | 160 | 380 | 1200 | 2800 | 5600 |   |
|   |  | 3.0 | 44.5 | 125 | 370 | 770 | 1550 | 170 | 380 | 1200 | 2400 | 4700 |   |
|   |  | 3.3 | 41.5 | 115 | 345 | 705 | 1400 | 150 | 350 | 1100 | 2200 | 4200 |   |
|   |  | 3.6 | 40.0 | 110 | 325 | 665 | 1350 | 150 | 330 | 980 | 2000 | 4100 |   |

1. Evaluated by characterization. Not tested in production.

Table 52. Current consumption in Stop 1 mode on LDO

|  Symbol | Parameter | Conditions | Typ |  |  |  |  | Max $^{(1)}$ |  |  |  |  | Unit  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |   |
|  $\mathrm{I}_{\text {DD (Stop 1) }}$ | Supply current in Stop 1 mode, RTC disabled, 8 -Kbyte SRAM2 + ICACHE retained | 1.8 | 82.0 | 250 | 755 | 1500 | 3000 | 300 | 750 | 2300 | 4500 | 9000 | $\mu \mathrm{A}$  |
|   |  | 2.4 | 83.5 | 250 | 750 | 1500 | 3050 | 310 | 750 | 2300 | 4500 | 9200 |   |
|   |  | 3.0 | 87.5 | 255 | 755 | 1550 | 3050 | 320 | 770 | 2300 | 4700 | 9200 |   |
|   |  | 3.3 | 84.0 | 250 | 755 | 1550 | 3050 | 310 | 750 | 2300 | 4700 | 9200 |   |
|   |  | 3.6 | 95.5 | 255 | 760 | 1550 | 3050 | 350 | 770 | 2300 | 4700 | 9200 |   |Table 52. Current consumption in Stop 1 mode on LDO (continued)

|  Symbol | Parameter | Conditions | Typ |  |  |  |  | Max ${ }^{(1)}$ |  |  |  |  | Unit  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |   |
|  $\mathrm{I}_{\text {DD (Stop 1) }}$ | Supply current in Stop 1 mode, RTC disabled, All SRAMs retained | 1.8 | 89.0 | 255 | 760 | 1550 | 3100 | 330 | 770 | 2300 | 4700 | 9300 | $\mu \mathrm{A}$  |
|   |  | 2.4 | 94.0 | 265 | 795 | 1600 | 3200 | 340 | 800 | 2400 | 4800 | 9600 |   |
|   |  | 3.0 | 100.0 | 270 | 815 | 1650 | 3300 | 370 | 810 | 2500 | 5000 | 9900 |   |
|   |  | 3.3 | 100.0 | 275 | 815 | 1650 | 3300 | 370 | 830 | 2500 | 5000 | 9900 |   |
|   |  | 3.6 | 110.0 | 275 | 825 | 1650 | 3300 | 400 | 830 | 2500 | 5000 | 9900 |   |
|  $\begin{aligned} & \mathrm{I}_{\text {DD(Stop 1 }} \ & \text { with RTC) } \end{aligned}$ | Supply current in Stop 1 mode, $\mathrm{RTC}^{(2)}$ clocked by LSI 32 kHz , 8 -Kbyte SRAM2 + ICACHE retained | 1.8 | 85.0 | 250 | 755 | 1500 | 3000 | - | - | - | - | - |   |
|   |  | 2.4 | 88.5 | 250 | 750 | 1500 | 3050 | - | - | - | - | - |   |
|   |  | 3.0 | 93.0 | 255 | 755 | 1550 | 3050 | - | - | - | - | - |   |
|   |  | 3.3 | 89.0 | 250 | 755 | 1550 | 3050 | - | - | - | - | - |   |
|   |  | 3.6 | 98.0 | 255 | 760 | 1550 | 3050 | - | - | - | - | - |   |
|   | Supply current in Stop 1 mode, $\mathrm{RTC}^{(2)}$ clocked by LSE bypassed at 32768 Hz , 8 -Kbyte SRAM2 + ICACHE retained | 1.8 | 82.5 | 250 | 755 | 1500 | 3000 | - | - | - | - | - |   |
|   |  | 2.4 | 84.0 | 250 | 750 | 1500 | 3050 | - | - | - | - | - |   |
|   |  | 3.0 | 90.5 | 255 | 755 | 1550 | 3050 | - | - | - | - | - |   |
|   |  | 3.3 | 84.5 | 250 | 755 | 1550 | 3050 | - | - | - | - | - |   |
|   |  | 3.6 | 96.0 | 255 | 760 | 1550 | 3050 | - | - | - | - | - |   |
|   | Supply current in Stop 1 mode, $\mathrm{RTC}^{(2)}$ clocked by LSE quartz in low-drive mode, LSESYSEN $=0$ in RCC_BDCR, 8 -Kbyte SRAM2 + ICACHE retained | 1.8 | 83.5 | 250 | 755 | 1500 | 3000 | - | - | - | - | - |   |
|   |  | 2.4 | 84.0 | 250 | 750 | 1500 | 3050 | - | - | - | - | - |   |
|   |  | 3.0 | 88.0 | 255 | 755 | 1550 | 3050 | - | - | - | - | - |   |
|   |  | 3.3 | 84.5 | 250 | 755 | 1550 | 3050 | - | - | - | - | - |   |
|   |  | 3.6 | 96.0 | 255 | 760 | 1550 | 3050 | - | - | - | - | - |   |

1. Evaluated by characterization. Not tested in production.
2. RTC with default configuration but LPCAL $=1$ in RTC_CALR.Table 53. Current consumption during wake-up from Stop 1 mode on LDO

|  Symbol | Parameter | Conditions |  |  |  |  |  |  |  |  | Unit  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  |  |  | - |  |  | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ |  | $25^{\circ} \mathrm{C}$ |  |   |
|  $\mathrm{Q}_{\text {DD(wake-up from Stop 1) }}$ | Electrical charge consumed during wake-up from Stop 1 mode |  |  | Wake-up clock is MSI 24 MHz |  |  |  |  | 40 |  | nAs  |
|   |  |  |  | Wake-up clock is HSI 16 MHz |  |  | 3.0 |  | 40 |  |   |
|   |  |  |  | Wake-up clock is MSI 1 MHz |  |  |  |  | 70 |  |   |

Table 54. Current consumption in Stop 1 mode on SMPS

|  Symbol | Parameter | Conditions | Typ |  |  |  |  | Max $^{(1)}$ |  |  |  |  | Unit  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |   |
|  $\mathrm{I}_{\text {DD(10000) }}$ | Supply current in Stop 1 mode, RTC disabled, 8-Kipple SRAM2 + ICACHE retained | 1.8 | 54.5 | 160 | 535 | 1050 | 2100 | 200 | 480 | 1700 | 3200 | 6300 | $\mu \mathrm{A}$  |
|   |  | 2.4 | 38.5 | 115 | 350 | 890 | 1650 | 140 | 350 | 1100 | 2700 | 5000 |   |
|   |  | 3.0 | 39.5 | 115 | 340 | 685 | 1400 | 150 | 350 | 1100 | 2100 | 4200 |   |
|   |  | 3.3 | 37.0 | 105 | 315 | 640 | 1300 | 140 | 320 | 950 | 2000 | 3900 |   |
|   |  | 3.6 | 35.5 | 100 | 295 | 600 | 1200 | 130 | 300 | 890 | 1800 | 3600 |   |
|   | Supply current in Stop 1 mode, RTC disabled, All SRAMs retained | 1.8 | 61.5 | 175 | 515 | 1200 | 2350 | 230 | 530 | 1600 | 3600 | 7100 |   |
|   |  | 2.4 | 43.5 | 125 | 390 | 930 | 1850 | 160 | 380 | 1200 | 2800 | 5600 |   |
|   |  | 3.0 | 44.0 | 125 | 370 | 770 | 1550 | 160 | 380 | 1200 | 2400 | 4700 |   |
|   |  | 3.3 | 41.5 | 115 | 345 | 705 | 1400 | 150 | 350 | 1100 | 2200 | 4200 |   |
|   |  | 3.6 | 39.5 | 110 | 325 | 665 | 1350 | 150 | 330 | 980 | 2000 | 4100 |   |Table 54. Current consumption in Stop 1 mode on SMPS (continued)

| Symbol | Parameter | Conditions | Typ |  |  |  |  | $\operatorname{Max}^{(1)}$ |  |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |  |
| $\begin{aligned} & \text { tDD(Stop } \\ & \text { with RTC) } \end{aligned}$ | Supply current in Stop 1 mode, RTC ${ }^{(2)}$ clocked by LSI 32 kHz , 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 54.5 | 160 | 535 | 1050 | 2100 | - | - | - | - | - | $\mu \mathrm{A}$ |
|  |  | 2.4 | 39.0 | 115 | 350 | 890 | 1650 | - | - | - | - | - |  |
|  |  | 3.0 | 40.0 | 115 | 340 | 685 | 1400 | - | - | - | - | - |  |
|  |  | 3.3 | 37.5 | 110 | 315 | 640 | 1300 | - | - | - | - | - |  |
|  |  | 3.6 | 36.0 | 100 | 295 | 600 | 1200 | - | - | - | - | - |  |
|  | Supply current in Stop 1 mode, RTC ${ }^{(2)}$ clocked by LSE bypassed at 32768 Hz , 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 65.0 | 180 | 535 | 890 | 2100 | - | - | - | - | - |  |
|  |  | 2.4 | 50.0 | 140 | 415 | 850 | 1700 | - | - | - | - | - |  |
|  |  | 3.0 | 42.0 | 120 | 345 | 705 | 1300 | - | - | - | - | - |  |
|  |  | 3.3 | 39.0 | 110 | 320 | 655 | 1250 | - | - | - | - | - |  |
|  |  | 3.6 | 38.0 | 105 | 300 | 620 | 1200 | - | - | - | - | - |  |
|  | Supply current in Stop 1 mode, RTC ${ }^{(2)}$ clocked by LSE quartz in low-drive mode, LSESYSEN $=0$ in RCC_BDCR, 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 55.0 | 160 | 610 | 1050 | 2100 | - | - | - | - | - |  |
|  |  | 2.4 | 39.5 | 150 | 490 | 890 | 1650 | - | - | - | - | - |  |
|  |  | 3.0 | 39.5 | 115 | 340 | 685 | 1400 | - | - | - | - | - |  |
|  |  | 3.3 | 37.0 | 105 | 315 | 640 | 1300 | - | - | - | - | - |  |
|  |  | 3.6 | 35.5 | 100 | 295 | 600 | 1200 | - | - | - | - | - |  |

1. Evaluated by characterization. Not tested in production.
2. RTC with default configuration but LPCAL $=1$ in RTC_CALR.Table 55. Current consumption during wake-up from Stop 1 mode on SMPS

|  Symbol | Parameter | Conditions |  |  |  |  |  |  |  |  | Unit  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  |  |  | - |  | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ |  | $25^{\circ} \mathrm{C}$ |  |  |   |
|  $\mathrm{Q}_{\text {DD(wake-up from Stop 1) }}$ | Electrical charge consumed during wake-up from Stop 1 mode |  |  | Wake-up clock is MSI 24 MHz |  |  |  |  | 40 |  | nAs  |
|   |  |  |  | Wake-up clock is HSI 16 MHz |  |  |  |  | 40 |  |   |
|   |  |  |  | Wake-up clock is MSI 1 MHz |  |  |  |  | 70 |  |   |

Table 56. Current consumption in Stop 2 mode on LDO

|  Symbol | Parameter | Conditions | Typ |  |  |  |  | $\operatorname{Max}^{(1)}$ |  |  |  |  | Unit  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |   |
|  $\begin{aligned} & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \Table 56. Current consumption in Stop 2 mode on LDO (continued)

| Symbol | Parameter | Conditions | Typ |  |  |  |  | Max ${ }^{(1)}$ |  |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |  |
| $\begin{aligned} & \text { DD(Stop } 2 \\ & \text { with RTC) } \end{aligned}$ | Supply current in Stop 2 mode, $\mathrm{RTC}^{(2)}$ clocked by LSI 32 kHz , 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 9.45 | 24.0 | 71.5 | 150 | 315 | 35.0 | 72.0 | 220.0 | 450.0 | 950.0 | $\mu \mathrm{A}$ |
|  |  | 2.4 | 9.50 | 24.0 | 71.5 | 150 | 315 | 35.0 | 72.0 | 220.0 | 450.0 | 950.0 |  |
|  |  | 3.0 | 9.60 | 24.5 | 73.0 | 150 | 320 | 35.0 | 74.0 | 220.0 | 450.0 | 960.0 |  |
|  |  | 3.3 | 9.30 | 25.0 | 74.0 | 155 | 325 | 34.0 | 75.0 | 230.0 | 470.0 | 980.0 |  |
|  |  | 3.6 | 11.00 | 26.5 | 77.0 | 160 | 335 | 40.0 | 80.0 | 240.0 | 480.0 | 1100.0 |  |
|  | Supply current in Stop 2 mode, $\mathrm{RTC}^{(2)}$ clocked by LSI 250 Hz , 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 9.15 | 23.5 | 70.0 | 145 | 305 | 33.0 | 71.0 | 210.0 | 440.0 | 920.0 |  |
|  |  | 2.4 | 9.20 | 23.5 | 70.5 | 145 | 310 | 34.0 | 71.0 | 220.0 | 440.0 | 930.0 |  |
|  |  | 3.0 | 9.20 | 24.0 | 71.5 | 150 | 315 | 34.0 | 72.0 | 220.0 | 450.0 | 950.0 |  |
|  |  | 3.3 | 9.50 | 24.5 | 73.0 | 150 | 320 | 35.0 | 74.0 | 220.0 | 450.0 | 960.0 |  |
|  |  | 3.6 | 10.50 | 26.0 | 76.0 | 155 | 325 | 38.0 | 78.0 | 230.0 | 470.0 | 980.0 |  |
|  | Supply current in Stop 2 mode, $\mathrm{RTC}^{(2)}$ clocked by LSE bypassed at 32768 Hz , 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 9.15 | 24.0 | 71.5 | 150 | 315 | 33.0 | 72.0 | 220.0 | 450.0 | 950.0 |  |
|  |  | 2.4 | 9.20 | 24.0 | 71.5 | 150 | 315 | 34.0 | 72.0 | 220.0 | 450.0 | 950.0 |  |
|  |  | 3.0 | 9.50 | 24.0 | 72.5 | 150 | 320 | 35.0 | 72.0 | 220.0 | 450.0 | 960.0 |  |
|  |  | 3.3 | 9.50 | 25.0 | 74.0 | 155 | 325 | 35.0 | 75.0 | 230.0 | 470.0 | 980.0 |  |
|  |  | 3.6 | 10.50 | 26.5 | 76.5 | 160 | 335 | 38.0 | 80.0 | 230.0 | 480.0 | 1100.0 |  |
|  | Supply current in Stop 2 mode, $\mathrm{RTC}^{(2)}$ clocked by LSE quartz in low-drive mode, 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 9.45 | 23.5 | 70.5 | 145 | 305 | - | - | - | - | - |  |
|  |  | 2.4 | 9.50 | 24.0 | 71.0 | 150 | 310 | - | - | - | - | - |  |
|  |  | 3.0 | 9.35 | 24.0 | 72.0 | 150 | 315 | - | - | - | - | - |  |
|  |  | 3.3 | 9.75 | 25.0 | 73.5 | 150 | 320 | - | - | - | - | - |  |
|  |  | 3.6 | 10.60 | 26.5 | 76.0 | 155 | 325 | - | - | - | - | - |  |

1. Evaluated by characterization. Not tested in production.
2. RTC with default configuration but LPCAL $=1$ in RTC_CALR.Table 57. SRAM static power consumption in Stop 2 when supplied by LDO

| Symbol | Parameter | Typ | | | | | Max ${ }^{(1)}$ | | | | | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |  |
| ${ }^{1}$ DD(SRAM1_64kB) ${ }^{(2)}$ | SRAM1 64-Kbyte page $x$ static consumption (SRAM1PDSx $=1$ versus SRAM1PDSx $=0$ ) | 0.8 | 2.0 | 6.0 | 13.2 | 28.6 | 3.0 | 6.0 | 18.0 | 40.0 | 86.0 | $\mu \mathrm{A}$ |
| ${ }^{1}$ DD(SRAM2_8KB) ${ }^{(3)}$ | SRAM2 8-Kbyte page 1 static consumption (SRAM2PDS1 $=1$ versus SRAM2PDS1 $=0$ ) | 0.2 | 0.4 | 1.4 | 3.1 | 6.5 | 0.7 | 1.4 | 4.4 | 10.0 | 20.0 |  |
| ${ }^{1}$ DD(SRAM2_56KB) ${ }^{(3)}$ | SRAM2 56-Kbyte page 2 static consumption (SRAM2PDS2 $=1$ versus SRAM2PDS2 $=0$ ) | 1.0 | 2.6 | 8.0 | 17.6 | 37.9 | 3.6 | 7.7 | 25.0 | 53.0 | 120.0 |  |
| ${ }^{1}$ DD(SRAM3_64kB) ${ }^{(4)}$ | SRAM3 64-Kbyte page $x$ static consumption (SRAM3PDSx $=1$ versus SRAM3PDSx $=0$ ) | 0.8 | 1.9 | 5.7 | 12.6 | 27.5 | 3.0 | 5.8 | 18.0 | 38.0 | 83.0 |  |
| ${ }^{1}$ DD(SRAM4) | SRAM4 static consumption (SRAM4PDS $=1$ versus SRAM4PDS $=0$ ) | 0.3 | 0.6 | 1.8 | 3.9 | 8.2 | 1.0 | 1.8 | 5.4 | 12.0 | 25.0 |  |
| ${ }^{1}$ DD(ICRAM) | ICACHE SRAM static consumption (ICRAMPDS $=1$ versus ICRAMPDS $=0$ ) | 0.1 | 0.4 | 1.3 | 2.9 | 5.7 | 0.5 | 1.3 | 4.0 | 8.6 | 18.0 |  |
| ${ }^{1}$ DD(DC1RAM) | DCACHE1 SRAM static consumption (DC1RAMPDS $=1$ versus DC1RAMPDS $=0$ ) | 0.1 | 0.2 | 0.7 | 1.5 | 3.0 | 0.3 | 0.7 | 2.3 | 4.6 | 9.1 |  |
| ${ }^{1}$ DD(DMA2DRAM) | DMA2D SRAM static consumption (DMA2DRAMPDS $=1$ versus DMA2DRAMPDS $=0$ ) | 0.0 | 0.1 | 0.3 | 0.5 | 0.7 | 0.2 | 0.3 | 1.0 | 1.6 | 2.0 |  |
| ${ }^{1}$ DD(PRAM) | FMAC, FDCAN and USB SRAM static consumption (PRAMPDS $=1$ versus PRAMPDS $=0$ ) | 0.0 | 0.1 | 0.4 | 0.7 | 1.1 | 0.2 | 0.4 | 1.3 | 2.3 | 3.2 |  |
| ${ }^{1}$ DD(PKARAM) | PKA SRAM static consumption (PKARAMPDS $=1$ versus PKARAMPDS $=0$ ) | 0.1 | 0.2 | 0.6 | 1.2 | 2.1 | 0.3 | 0.5 | 1.9 | 3.6 | 6.3 |  |

1. Evaluated by characterization. Not tested in production.
2. SRAM1 total consumption is $3 \times 1_{\text {DD(SRAM1_64KB) }}$.
3. SRAM2 total consumption is $1_{\text {DD(SRAM2_8KB) }}+1_{\text {DD(SRAM2_56KB) }}$.
4. SRAM3 total consumption is $8 \times 1_{\text {DD(SRAM3_64KB) }}$.Table 58. Current consumption during wake-up from Stop 2 mode on LDO

|  Symbol | Parameter | Conditions |  |  |  |  |  |  |  |  |  | Unit  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  |  |  | - |  |  |  | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ |  | $25^{\circ} \mathrm{C}$ |  |   |
|  $\mathrm{Q}_{\text {DD(wake-up from Stop 2) }}$ | Electrical charge consumed during wake-up from Stop 2 mode |  |  | Wake-up clock is MSI 24 MHz |  |  |  | 3.0 |  | 30 |  | nAs  |
|   |  |  |  | Wake-up clock is HSI 16 MHz |  |  |  |  |  | 30 |  |   |
|   |  |  |  | Wake-up clock is MSI 1 MHz |  |  |  |  |  | 70 |  |   |

Table 59. Current consumption in Stop 2 mode on SMPS

|  Symbol | Parameter | Conditions | Typ |  |  |  |  | $\operatorname{Max}^{(1)}$ |  |  |  |  | Unit  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |   |
|  $\begin{aligned} & \text { DD } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D } \ & \text { D }Table 59. Current consumption in Stop 2 mode on SMPS (continued)

| Symbol | Parameter | Conditions | Typ |  |  |  |  | Max ${ }^{(1)}$ |  |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |  |
| $\begin{aligned} & \text { DD(Stop } 2 \\ & \text { with RTC) } \end{aligned}$ | Supply current in Stop 2 mode, $\mathrm{RTC}^{(2)}$ clocked by LSI 32 kHz , 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 5.60 | 14.0 | 42.0 | 89.0 | 195 | 20.0 | 42.0 | 130.0 | 270.0 | 580.0 | $\mu \mathrm{A}$ |
|  |  | 2.4 | 3.85 | 10.0 | 30.0 | 63.5 | 140 | 14.0 | 30.0 | 89.0 | 190.0 | 410.0 |  |
|  |  | 3.0 | 4.35 | 10.5 | 32.0 | 68.5 | 150 | 16.0 | 31.0 | 94.0 | 200.0 | 440.0 |  |
|  |  | 3.3 | 4.40 | 10.5 | 31.0 | 66.0 | 145 | 16.0 | 31.0 | 91.0 | 200.0 | 420.0 |  |
|  |  | 3.6 | 5.15 | 11.5 | 31.5 | 66.0 | 145 | 18.0 | 33.0 | 91.0 | 190.0 | 420.0 |  |
|  | Supply current in Stop 2 mode, $\mathrm{RTC}^{(2)}$ clocked by LSI 250 Hz , 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 5.40 | 14.0 | 42.0 | 89.0 | 195 | 20.0 | 42.0 | 130.0 | 270.0 | 580.0 |  |
|  |  | 2.4 | 3.60 | 9.8 | 30.0 | 63.5 | 140 | 13.0 | 29.0 | 89.0 | 190.0 | 410.0 |  |
|  |  | 3.0 | 4.00 | 10.5 | 31.5 | 68.0 | 150 | 15.0 | 31.0 | 93.0 | 200.0 | 440.0 |  |
|  |  | 3.3 | 4.05 | 10.5 | 31.0 | 65.5 | 145 | 15.0 | 31.0 | 91.0 | 190.0 | 420.0 |  |
|  |  | 3.6 | 4.75 | 11.0 | 31.5 | 65.5 | 145 | 17.0 | 32.0 | 91.0 | 190.0 | 420.0 |  |
|  | Supply current in Stop 2 mode, $\mathrm{RTC}^{(2)}$ clocked by LSE bypassed at 32768 Hz , 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 5.50 | 14.0 | 42.0 | 89.0 | 195 | 20.0 | 42.0 | 130.0 | 270.0 | 580.0 |  |
|  |  | 2.4 | 3.70 | 9.9 | 30.0 | 63.5 | 140 | 14.0 | 30.0 | 89.0 | 190.0 | 410.0 |  |
|  |  | 3.0 | 4.15 | 10.5 | 32.0 | 68.0 | 150 | 15.0 | 31.0 | 94.0 | 200.0 | 440.0 |  |
|  |  | 3.3 | 4.20 | 10.5 | 31.0 | 66.0 | 145 | 15.0 | 31.0 | 91.0 | 200.0 | 420.0 |  |
|  |  | 3.6 | 4.90 | 11.0 | 31.5 | 65.5 | 145 | 17.0 | 32.0 | 91.0 | 190.0 | 420.0 |  |
|  | Supply current in Stop 2 mode, $\mathrm{RTC}^{(2)}$ clocked by LSE quartz in low-drive mode, 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 5.60 | 14.0 | 42.0 | 88.5 | 195 | - | - | - | - | - |  |
|  |  | 2.4 | 3.90 | 9.9 | 30.0 | 63.5 | 140 | - | - | - | - | - |  |
|  |  | 3.0 | 4.25 | 10.5 | 31.5 | 68.0 | 150 | - | - | - | - | - |  |
|  |  | 3.3 | 4.30 | 10.5 | 31.0 | 65.5 | 145 | - | - | - | - | - |  |
|  |  | 3.6 | 4.95 | 11.0 | 31.5 | 65.0 | 145 | - | - | - | - | - |  |

1. Evaluated by characterization. Not tested in production.
2. RTC with default configuration but LPCAL $=1$ in RTC_CALR.Table 60. SRAM static power consumption in Stop 2 when supplied by SMPS

| Symbol | Parameter | Typ |  |  |  |  | Max ${ }^{(1)}$ |  |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |  |
| ${ }^{1}$ DD(SRAM1_64kB) ${ }^{(2)}$ | SRAM1 64-Kbyte page $x$ static consumption (SRAM1PDSx $=1$ versus SRAM1PDSx $=0$ ) | 0.4 | 0.9 | 2.6 | 5.5 | 12.7 | 1.5 | 2.7 | 7.7 | 17.0 | 39.0 | $\mu \mathrm{A}$ |
| ${ }^{1}$ DD(SRAM2_8KB) ${ }^{(3)}$ | SRAM2 8-Kbyte page 1 static consumption (SRAM2PDS1 $=1$ versus SRAM2PDS1 $=0$ ) | 0.1 | 0.2 | 0.6 | 1.2 | 2.9 | 0.3 | 0.6 | 2.0 | 3.7 | 10.0 |  |
| ${ }^{1}$ DD(SRAM2_56KB) ${ }^{(3)}$ | SRAM2 56-Kbyte page 2 static consumption (SRAM2PDS2 $=1$ versus SRAM2PDS2 $=0$ ) | 0.5 | 1.1 | 3.4 | 7.5 | 16.7 | 1.7 | 3.4 | 11.0 | 23.0 | 50.0 |  |
| ${ }^{1}$ DD(SRAM3_64kB) ${ }^{(4)}$ | SRAM3 64-Kbyte page $x$ static consumption (SRAM3PDSx $=1$ versus SRAM3PDSx $=0$ ) | 0.4 | 0.8 | 2.4 | 5.3 | 12.2 | 1.4 | 2.5 | 7.3 | 16.0 | 37.0 |  |
| ${ }^{1}$ DD(SRAM4) | SRAM4 static consumption (SRAM4PDS $=1$ versus SRAM4PDS $=0$ ) | 0.1 | 0.3 | 0.7 | 1.5 | 3.7 | 0.4 | 0.8 | 2.2 | 4.6 | 12.0 |  |
| ${ }^{1}$ DD(ICRAM) | ICACHE SRAM static consumption (ICRAMPDS $=1$ versus ICRAMPDS $=0$ ) | 0.1 | 0.2 | 0.5 | 1.0 | 2.6 | 0.3 | 0.5 | 2.0 | 3.1 | 7.9 |  |
| ${ }^{1}$ DD(DC1RAM) | DCACHE1 SRAM static consumption (DC1RAMPDS $=1$ versus DC1RAMPDS $=0$ ) | 0.0 | 0.1 | 0.3 | 0.4 | 1.3 | 0.2 | 0.3 | 1.0 | 1.4 | 4.0 |  |
| ${ }^{1}$ DD(DMA2DRAM) | DMA2D SRAM static consumption (DMA2DRAMPDS $=1$ versus DMA2DRAMPDS $=0$ ) | 0.0 | 0.0 | 0.1 | 0.2 | 0.4 | 0.1 | 0.1 | 0.2 | 0.6 | 1.1 |  |
| ${ }^{1}$ DD(PRAM) | FMAC, FDCAN and USB SRAM static consumption (PRAMPDS $=1$ versus PRAMPDS $=0$ ) | 0.0 | 0.0 | 0.1 | 0.2 | 0.6 | 0.1 | 0.1 | 0.3 | 0.6 | 1.8 |  |
| ${ }^{1}$ DD(PKARAM) | PKA SRAM static consumption (PKARAMPDS $=1$ versus PKARAMPDS $=0$ ) | 0.0 | 0.1 | 0.2 | 0.3 | 1.0 | 0.1 | 0.2 | 0.6 | 0.9 | 2.9 |  |

1. Evaluated by characterization. Not tested in production.
2. SRAM1 total consumption is $3 \times 1_{\text {DD(SRAM1_64KB) }}$.
3. SRAM2 total consumption is $1_{\text {DD(SRAM2_8KB) }}+1_{\text {DD(SRAM2_56KB) }}$.
4. SRAM3 total consumption is $8 \times 1_{\text {DD(SRAM3_64KB) }}$.Table 61. Current consumption during wake-up from Stop 2 mode on SMPS

|  Symbol | Parameter | Conditions |  |  |  |  |  |  |  |  | Unit  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  |  |  | - |  |  | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ |  | $25^{\circ} \mathrm{C}$ |  |   |
|  $\mathrm{Q}_{\text {DD(wake-up from Stop 2) }}$ | Electrical charge consumed during wake-up from Stop 2 mode |  |  | Wake-up clock is MSI 24 MHz |  |  |  | 3.0 | 30 |  | nAs  |
|   |  |  |  | Wake-up clock is HSI 16 MHz |  |  |  |  | 30 |  |   |
|   |  |  |  | Wake-up clock is MSI 1 MHz |  |  |  |  | 70 |  |   |

Table 62. Current consumption in Stop 3 mode on LDO

|  Symbol | Parameter | Conditions | Typ |  |  |  |  | Max $^{(1)}$ |  |  |  |  | Unit  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |   |
|  $\mathrm{I}_{\text {DD(Stop 3) }}$ | Supply current in Stop 3 mode, RTC disabled, 8 -Kbyte SRAM2 + ICACHE retained | 1.8 | 5.15 | 14.5 | 49.0 | 110 | 240 | 19.0 | 44.0 | 150.0 | 330.0 | 710.0 | $\mu \mathrm{A}$  |
|   |  | 2.4 | 5.15 | 15.0 | 49.5 | 110 | 240 | 19.0 | 45.0 | 150.0 | 330.0 | 710.0 |   |
|   |  | 3.0 | 5.60 | 15.0 | 50.5 | 110 | 245 | 20.0 | 45.0 | 150.0 | 330.0 | 720.0 |   |
|   |  | 3.3 | 5.30 | 15.5 | 51.5 | 115 | 250 | 19.0 | 46.0 | 160.0 | 340.0 | 740.0 |   |
|   |  | 3.6 | 6.80 | 17.0 | 54.0 | 115 | 255 | 24.0 | 50.0 | 160.0 | 340.0 | 750.0 |   |
|   | Supply current in Stop 3 mode, RTC disabled, all SRAMs retained | 1.8 | 12.00 | 35.5 | 125.0 | 290 | 665 | 44.0 | 110.0 | 380.0 | 870.0 | 2000.0 |   |
|   |  | 2.4 | 12.00 | 36.0 | 125.0 | 295 | 670 | 44.0 | 110.0 | 380.0 | 890.0 | 2000.0 |   |
|   |  | 3.0 | 13.00 | 36.5 | 130.0 | 300 | 675 | 47.0 | 110.0 | 390.0 | 900.0 | 2100.0 |   |
|   |  | 3.3 | 14.50 | 37.0 | 130.0 | 300 | 685 | 52.0 | 120.0 | 390.0 | 900.0 | 2100.0 |   |
|   |  | 3.6 | 14.50 | 39.0 | 135.0 | 305 | 695 | 52.0 | 120.0 | 410.0 | 910.0 | 2100.0 |   |Table 62. Current consumption in Stop 3 mode on LDO (continued)

| Symbol | Parameter | Conditions | Typ |  |  |  |  | Max ${ }^{(1)}$ |  |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |  |
| $\begin{aligned} & \text { D } \\ & \text { with } \mathrm{RTC} \end{aligned}$ | Supply current in Stop 3 mode, $\mathrm{RTC}^{(2)}$ clocked by LSI 32 kHz , 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 5.45 | 15.0 | 49.5 | 110 | 240 | 20.0 | 45.0 | 150.0 | 330.0 | 710.0 | $\mu \mathrm{A}$ |
|  |  | 2.4 | 5.55 | 15.0 | 50.0 | 110 | 240 | 20.0 | 45.0 | 150.0 | 330.0 | 710.0 |  |
|  |  | 3.0 | 6.05 | 15.5 | 51.0 | 110 | 245 | 22.0 | 46.0 | 160.0 | 330.0 | 720.0 |  |
|  |  | 3.3 | 5.80 | 16.0 | 52.0 | 115 | 250 | 21.0 | 48.0 | 160.0 | 340.0 | 740.0 |  |
|  |  | 3.6 | 7.35 | 18.0 | 54.5 | 120 | 255 | 26.0 | 53.0 | 160.0 | 360.0 | 750.0 |  |
|  | Supply current in Stop 3 mode, $\mathrm{RTC}^{(2)}$ clocked by LSI 250 Hz , 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 5.25 | 15.0 | 49.5 | 110 | 240 | 19.0 | 45.0 | 150.0 | 330.0 | 710.0 |  |
|  |  | 2.4 | 5.30 | 15.0 | 49.5 | 110 | 240 | 19.0 | 45.0 | 150.0 | 330.0 | 710.0 |  |
|  |  | 3.0 | 5.75 | 15.0 | 50.5 | 110 | 245 | 21.0 | 45.0 | 150.0 | 330.0 | 720.0 |  |
|  |  | 3.3 | 5.40 | 16.0 | 52.0 | 115 | 250 | 19.0 | 48.0 | 160.0 | 340.0 | 740.0 |  |
|  |  | 3.6 | 6.95 | 17.5 | 54.5 | 115 | 255 | 25.0 | 51.0 | 160.0 | 340.0 | 750.0 |  |
|  | Supply current in Stop 3 mode, $\mathrm{RTC}^{(2)}$ clocked by LSE bypassed at 32768 Hz , 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 5.35 | 15.0 | 49.5 | 110 | 240 | 20.0 | 45.0 | 150.0 | 330.0 | 710.0 |  |
|  |  | 2.4 | 5.40 | 15.0 | 49.5 | 110 | 240 | 20.0 | 45.0 | 150.0 | 330.0 | 710.0 |  |
|  |  | 3.0 | 5.90 | 15.5 | 50.5 | 110 | 245 | 21.0 | 46.0 | 150.0 | 330.0 | 720.0 |  |
|  |  | 3.3 | 5.55 | 16.0 | 52.0 | 115 | 250 | 20.0 | 48.0 | 160.0 | 340.0 | 740.0 |  |
|  |  | 3.6 | 7.20 | 17.5 | 54.5 | 115 | 255 | 25.0 | 51.0 | 160.0 | 340.0 | 750.0 |  |
|  | Supply current in Stop 3 mode, $\mathrm{RTC}^{(2)}$ clocked by LSE quartz in low-drive mode, 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 5.45 | 15.0 | 49.0 | 110 | 240 | - | - | - | - | - |  |
|  |  | 2.4 | 5.55 | 15.0 | 49.5 | 110 | 240 | - | - | - | - | - |  |
|  |  | 3.0 | 6.05 | 15.5 | 50.5 | 110 | 245 | - | - | - | - | - |  |
|  |  | 3.3 | 6.65 | 16.0 | 51.5 | 115 | 250 | - | - | - | - | - |  |
|  |  | 3.6 | 7.30 | 17.5 | 54.0 | 115 | 255 | - | - | - | - | - |  |

1. Evaluated by characterization. Not tested in production.
2. RTC with default configuration but LPCAL $=1$ in RTC_CALR.Table 63. SRAM static power consumption in Stop 3 when supplied by LDO

| Symbol | Parameter | Typ |  |  |  |  | Max ${ }^{(1)}$ |  |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |  |
| ${ }^{1}$ DD(SRAM1_64kB) ${ }^{(2)}$ | SRAM1 64-Kbyte page $x$ static consumption (SRAM1PDSx $=1$ versus SRAM1PDSx $=0$ ) | 0.7 | 1.8 | 6.4 | 15.3 | 35.6 | 2.7 | 5.3 | 20.0 | 46.0 | 110.0 | $\mu \mathrm{A}$ |
| ${ }^{1}$ DD(SRAM2_8KB) ${ }^{(3)}$ | SRAM2 8-Kbyte page 1 static consumption (SRAM2PDS1 $=1$ versus SRAM2PDS1 $=0$ ) | 0.2 | 0.7 | 2.4 | 5.8 | 12.8 | 1.0 | 2.1 | 7.1 | 18.0 | 39.0 |  |
| ${ }^{1}$ DD(SRAM2_56KB) ${ }^{(3)}$ | SRAM2 56-Kbyte page 2 static consumption (SRAM2PDS2 $=1$ versus SRAM2PDS2 $=0$ ) | 0.9 | 2.2 | 7.8 | 18.5 | 41.7 | 3.2 | 6.5 | 24.0 | 56.0 | 130.0 |  |
| ${ }^{1}$ DD(SRAM3_64kB) ${ }^{(4)}$ | SRAM3 64-Kbyte page $x$ static consumption (SRAM3PDSx $=1$ versus SRAM3PDSx $=0$ ) | 0.7 | 1.7 | 6.1 | 14.8 | 34.2 | 2.6 | 5.2 | 19.0 | 45.0 | 110.0 |  |
| ${ }^{1}$ DD(SRAM4) | SRAM4 static consumption (SRAM4PDS $=1$ versus SRAM4PDS $=0$ ) | 0.2 | 0.5 | 1.7 | 4.0 | 8.9 | 0.8 | 1.5 | 5.1 | 12.0 | 27.0 |  |
| ${ }^{1}$ DD(ICRAM) | ICACHE SRAM static consumption (ICRAMPDS $=1$ versus ICRAMPDS $=0$ ) | 0.0 | 0.3 | 1.3 | 2.9 | 6.3 | 0.0 | 1.1 | 3.9 | 8.9 | 19.0 |  |
| ${ }^{1}$ DD(DC1RAM) | DCACHE1 SRAM static consumption (DC1RAMPDS $=1$ versus DC1RAMPDS $=0$ ) | 0.0 | 0.0 | 0.0 | 0.3 | 1.2 | 0.0 | 0.0 | 0.0 | 1.0 | 3.7 |  |
| ${ }^{1}$ DD(DMA2DRAM) | DMA2D SRAM static consumption (DMA2DRAMPDS $=1$ versus DMA2DRAMPDS $=0$ ) | 0.0 | 0.1 | 0.3 | 0.6 | 1.1 | 0.2 | 0.2 | 1.0 | 1.9 | 3.4 |  |
| ${ }^{1}$ DD(PRAM) | FMAC, FDCAN and USB SRAM static consumption (PRAMPDS $=1$ versus PRAMPDS $=0$ ) | 0.1 | 0.1 | 0.4 | 0.8 | 1.5 | 0.2 | 0.3 | 1.3 | 2.3 | 4.6 |  |
| ${ }^{1}$ DD(PKARAM) | PKA SRAM static consumption (PKARAMPDS $=1$ versus PKARAMPDS $=0$ ) | 0.1 | 0.2 | 0.6 | 1.3 | 2.8 | 0.3 | 0.5 | 1.9 | 4.0 | 8.4 |  |

1. Evaluated by characterization. Not tested in production.
2. SRAM1 total consumption is $3 \times 1_{\text {DD(SRAM1_64KB) }}$.
3. SRAM2 total consumption is $1_{\text {DD(SRAM2_8KB) }}+1_{\text {DD(SRAM2_56KB) }}$.
4. SRAM3 total consumption is $8 \times 1_{\text {DD(SRAM3_64KB) }}$.Table 64. Current consumption during wake-up from Stop 3 mode on LDO

|  Symbol | Parameter | Conditions |  |  |  |  |  |  |  |  | $\begin{gathered} \text { Typ }^{(1)} \ 25^{\circ} \mathrm{C} \end{gathered}$ | Unit  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  | - |  |  |  |  |  |  | $V_{D D}(V)$ | $25^{\circ} \mathrm{C}$ |  |   |
|  $\mathrm{Q}_{\text {DD(wake-up from Stop 3) }}$ | Electrical charge consumed during wake-up from Stop 3 mode | Wake-up clock is MSI 24 MHz |  |  |  |  |  |  |  |  |  | nAs  |
|   |  | Wake-up clock is HSI 16 MHz |  |  |  |  |  |  |  |  |  |   |
|   |  | Wake-up clock is MSI 1 MHz |  |  |  |  |  |  |  |  |  |   |

1. Evaluated by characterization in worse case condition ( $\mathrm{V}_{\mathrm{CAP}}=0.7 \mathrm{~V}$ before wake-up).

Table 65. Current consumption in Stop 3 mode on SMPS

|  Symbol | Parameter | Conditions | Typ |  |  |  |  | $\operatorname{Max}^{(1)}$ |  |  |  |  | Unit  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  | $\mathrm{V}_{\text {DD }}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |   |
|  $\mathrm{I}_{\text {DD(Stop 3) }}$ | Supply current in Stop 3 mode, RTC disabled, 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 2.10 | 6.55 | 22.5 | 50.5 | 115.0 | 7.4 | 20.0 | 66.0 | 150.0 | 340.0 | $\mu \mathrm{A}$  |
|   |  | 2.4 | 1.85 | 5.95 | 20.5 | 46.5 | 110.0 | 6.5 | 18.0 | 60.0 | 140.0 | 320.0 |   |
|   |  | 3.0 | 1.70 | 5.30 | 18.5 | 42.0 | 98.5 | 5.9 | 16.0 | 54.0 | 130.0 | 280.0 |   |
|   |  | 3.3 | 1.80 | 5.55 | 18.5 | 41.5 | 97.0 | 6.1 | 16.0 | 53.0 | 120.0 | 280.0 |   |
|   |  | 3.6 | 2.65 | 6.55 | 19.5 | 42.5 | 98.0 | 8.6 | 19.0 | 55.0 | 120.0 | 280.0 |   |
|   | Supply current in Stop 3 mode, RTC disabled, all SRAMs retained | 1.8 | 5.20 | 15.50 | 55.0 | 130.0 | 355.0 | 19.0 | 47.0 | 170.0 | 390.0 | 1100.0 |   |
|   |  | 2.4 | 4.55 | 14.00 | 50.0 | 115.0 | 275.0 | 17.0 | 42.0 | 150.0 | 350.0 | 820.0 |   |
|   |  | 3.0 | 3.90 | 12.00 | 42.5 | 100.0 | 235.0 | 14.0 | 36.0 | 130.0 | 300.0 | 690.0 |   |
|   |  | 3.3 | 3.65 | 11.50 | 40.5 | 95.0 | 225.0 | 13.0 | 34.0 | 120.0 | 280.0 | 660.0 |   |
|   |  | 3.6 | 4.50 | 12.00 | 40.5 | 92.5 | 215.0 | 16.0 | 35.0 | 120.0 | 270.0 | 630.0 |   |Table 65. Current consumption in Stop 3 mode on SMPS (continued)

| Symbol | Parameter | Conditions | Typ |  |  |  |  | $\operatorname{Max}^{(1)}$ |  |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |  |
| $\begin{aligned} & 1_{\text {DD(Stop } 3} \\ & \text { with RTC) }} \end{aligned}$ | Supply current in Stop 3 mode, $\mathrm{RTC}^{(2)}$ clocked by LSI 32 kHz , 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 2.40 | 6.85 | 22.5 | 51.0 | 120.0 | 8.5 | 21.0 | 66.0 | 150.0 | 350.0 | $\mu \mathrm{A}$ |
|  |  | 2.4 | 2.25 | 6.30 | 21.0 | 47.0 | 110.0 | 8.0 | 19.0 | 62.0 | 140.0 | 320.0 |  |
|  |  | 3.0 | 2.15 | 5.80 | 19.0 | 42.5 | 99.0 | 7.5 | 17.0 | 55.0 | 130.0 | 290.0 |  |
|  |  | 3.3 | 2.30 | 6.05 | 19.0 | 42.0 | 97.5 | 7.9 | 18.0 | 55.0 | 120.0 | 280.0 |  |
|  |  | 3.6 | 3.20 | 7.10 | 20.0 | 43.0 | 98.5 | 11.0 | 20.0 | 56.0 | 130.0 | 280.0 |  |
|  | Supply current in Stop 3 mode, $\mathrm{RTC}^{(2)}$ clocked by LSI 250 Hz , 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 2.20 | 6.70 | 22.5 | 50.5 | 115.0 | 7.8 | 20.0 | 66.0 | 150.0 | 340.0 |  |
|  |  | 2.4 | 2.00 | 6.10 | 20.5 | 47.0 | 110.0 | 7.1 | 18.0 | 60.0 | 140.0 | 320.0 |  |
|  |  | 3.0 | 1.85 | 5.45 | 18.5 | 42.0 | 98.5 | 6.5 | 16.0 | 54.0 | 130.0 | 280.0 |  |
|  |  | 3.3 | 1.90 | 5.70 | 18.5 | 41.5 | 97.0 | 6.4 | 17.0 | 53.0 | 120.0 | 280.0 |  |
|  |  | 3.6 | 2.80 | 6.70 | 20.0 | 42.5 | 98.0 | 9.2 | 19.0 | 56.0 | 120.0 | 280.0 |  |
|  | Supply current in Stop 3 mode, $\mathrm{RTC}^{(2)}$ clocked by LSE bypassed at 32768 Hz , 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 2.30 | 6.80 | 22.5 | 51.0 | 120.0 | 8.2 | 21.0 | 66.0 | 150.0 | 350.0 |  |
|  |  | 2.4 | 2.10 | 6.20 | 21.0 | 47.0 | 110.0 | 7.4 | 19.0 | 62.0 | 140.0 | 320.0 |  |
|  |  | 3.0 | 2.00 | 5.60 | 18.5 | 42.0 | 99.0 | 7.0 | 17.0 | 54.0 | 130.0 | 290.0 |  |
|  |  | 3.3 | 2.05 | 5.85 | 18.5 | 42.0 | 97.5 | 7.0 | 17.0 | 53.0 | 120.0 | 280.0 |  |
|  |  | 3.6 | 3.00 | 6.90 | 20.0 | 43.0 | 98.5 | 9.9 | 20.0 | 56.0 | 130.0 | 280.0 |  |
|  | Supply current in Stop 3 mode, $\mathrm{RTC}^{(2)}$ clocked by LSE quartz in low-drive mode, 8-Kbyte SRAM2 + ICACHE retained | 1.8 | 2.45 | 6.90 | 22.5 | 50.5 | 115.0 | - | - | - | - | - |  |
|  |  | 2.4 | 2.25 | 6.35 | 21.0 | 46.5 | 110.0 | - | - | - | - | - |  |
|  |  | 3.0 | 2.15 | 5.80 | 18.5 | 42.0 | 98.5 | - | - | - | - | - |  |
|  |  | 3.3 | 2.35 | 6.05 | 18.5 | 41.5 | 97.0 | - | - | - | - | - |  |
|  |  | 3.6 | 3.15 | 7.05 | 20.0 | 42.5 | 98.0 | - | - | - | - | - |  |

1. Evaluated by characterization. Not tested in production.
2. RTC with default configuration but LPCAL $=1$ in RTC_CALR.Table 66. SRAM static power consumption in Stop 3 when supplied by SMPS

| Symbol | Parameter | Typ |  |  |  |  | $\operatorname{Max}^{(1)}$ |  |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |  |
| ${ }^{1}$ DD(SRAM1_64kB) ${ }^{(2)}$ | SRAM1 64-Kbyte page $x$ static consumption (SRAM1PDSx $=1$ versus SRAM1PDSx $=0$ ) | 0.2 | 0.6 | 2.2 | 5.4 | 12.6 | 0.7 | 2.0 | 8.0 | 17.0 | 38.0 | $\mu \mathrm{A}$ |
| ${ }^{1}$ DD(SRAM2_8KB) ${ }^{(3)}$ | SRAM2 8-Kbyte page 1 static consumption (SRAM2PDS1 $=1$ versus SRAM2PDS1 $=0$ ) | 0.1 | 0.2 | 0.8 | 2.0 | 4.6 | 0.2 | 1.0 | 2.5 | 5.9 | 14.0 |  |
| ${ }^{1}$ DD(SRAM2_56KB) ${ }^{(3)}$ | SRAM2 56-Kbyte page 2 static consumption (SRAM2PDS2 $=1$ versus SRAM2PDS2 $=0$ ) | 0.2 | 0.7 | 2.7 | 6.4 | 14.8 | 1.0 | 3.0 | 8.0 | 20.0 | 45.0 |  |
| ${ }^{1}$ DD(SRAM3_64kB) ${ }^{(4)}$ | SRAM3 64-Kbyte page $x$ static consumption (SRAM3PDSx $=1$ versus SRAM3PDSx $=0$ ) | 0.2 | 0.6 | 2.1 | 5.0 | 12.0 | 1.0 | 2.0 | 6.3 | 16.0 | 36.0 |  |
| ${ }^{1}$ DD(SRAM4) | SRAM4 static consumption (SRAM4PDS $=1$ versus SRAM4PDS $=0$ ) | 0.0 | 0.1 | 0.6 | 1.4 | 3.0 | 0.5 | 1.0 | 2.0 | 4.1 | 8.9 |  |
| ${ }^{1}$ DD(ICRAM) | ICACHE SRAM static consumption (ICRAMPDS $=1$ versus ICRAMPDS $=0$ ) | 0.0 | 0.1 | 0.4 | 1.0 | 2.0 | 0.1 | 1.0 | 2.0 | 3.0 | 6.1 |  |
| ${ }^{1}$ DD(DC1RAM) | DCACHE1 SRAM static consumption (DC1RAMPDS $=1$ versus DC1RAMPDS $=0$ ) | 0.0 | 0.1 | 0.2 | 0.5 | 0.9 | 1.2 | 1.0 | 1.0 | 1.5 | 2.6 |  |
| ${ }^{1}$ DD(DMA2DRAM) | DMA2D SRAM static consumption (DMA2DRAMPDS $=1$ versus DMA2DRAMPDS $=0$ ) | 0.0 | 0.0 | 0.0 | 0.1 | 0.1 | 0.4 | 0.1 | 0.1 | 0.4 | 0.4 |  |
| ${ }^{1}$ DD(PRAM) | FMAC, FDCAN and USB SRAM static consumption (PRAMPDS $=1$ versus PRAMPDS $=0$ ) | 0.0 | 0.0 | 0.1 | 0.2 | 0.3 | 0.0 | 0.1 | 1.0 | 0.7 | 0.8 |  |
| ${ }^{1}$ DD(PKARAM) | PKA SRAM static consumption (PKARAMPDS $=1$ versus PKARAMPDS $=0$ ) | 0.0 | 0.1 | 0.2 | 0.4 | 0.7 | 0.0 | 1.0 | 1.0 | 1.3 | 2.1 |  |

1. Evaluated by characterization. Not tested in production.
2. SRAM1 total consumption is $3 \times 1_{\text {DD(SRAM1_64KB) }}$.
3. SRAM2 total consumption is $1_{\text {DD(SRAM2_8KB) }}+1_{\text {DD(SRAM2_56KB) }}$.
4. SRAM3 total consumption is $8 \times 1_{\text {DD(SRAM3_64KB) }}$.Table 67. Current consumption during wake-up from Stop 3 mode on SMPS

|  Symbol | Parameter | Conditions |  | Typ ${ }^{(1)}$ | Unit  |
| --- | --- | --- | --- | --- | --- |
|   |  | - | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ |   |
|  $\mathrm{Q}_{\text {DD(wake-up from Stop 3) }}$ | Electrical charge consumed during wake-up from Stop 3 mode | Wake-up clock is MSI 24 MHz | 3.0 | 160 | nAs  |
|   |  | Wake-up clock is HSI 16 MHz |  | 150 |   |
|   |  | Wake-up clock is MSI 1 MHz |  | 250 |   |

1. Evaluated by characterization in worse case condition $\left(\mathrm{V}*{\mathrm{DD} 11}=0.7 \mathrm{~V}\right.$ before wake-up).Table 68. Current consumption in Standby mode

| Symbol | Parameter | Conditions |  | Typ |  |  |  | $\operatorname{Max}^{(1)}$ |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | - | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |
| $\begin{aligned} & \mathrm{I}_{\text {DD(Standby) }} \\ & \mathrm{I}_{\text {DD(Standby) }} \end{aligned}$ | Supply current in Standby mode (backup registers retained), RTC disabled | No IWDG <br> ULPMEN $=1$ | 1.8 | 0.21 | 0.71 | 3.30 | 9.10 | 28.40 | 0.55 | 1.70 | 7.40 | 20.00 | 58.00 | $\mu \mathrm{A}$ |
|  |  |  | 2.4 | 0.21 | 0.74 | 3.47 | 9.54 | 29.70 | 0.58 | 1.80 | 7.90 | 22.00 | 61.00 |
|  |  |  | 3.0 | 0.36 | 1.08 | 4.41 | 11.50 | 34.20 | 1.10 | 2.70 | 11.00 | 27.00 | 73.00 |
|  |  |  | 3.3 | 0.64 | 1.69 | 5.68 | 13.70 | 38.40 | 2.00 | 4.20 | 14.00 | 32.00 | 83.00 |
|  |  |  | 3.6 | 1.51 | 3.04 | 8.07 | 17.40 | 44.20 | 4.80 | 7.70 | 20.00 | 41.00 | 98.00 |
|  |  | No IWDG <br> ULPMEN $=0$ | 1.8 | 0.28 | 0.76 | 3.28 | 8.95 | 27.70 | 0.63 | 1.70 | 7.40 | 20.00 | 57.00 |
|  |  |  | 2.4 | 0.29 | 0.83 | 3.52 | 9.46 | 29.10 | 0.67 | 1.90 | 7.90 | 22.00 | 61.00 |
|  |  |  | 3.0 | 0.43 | 1.16 | 4.43 | 11.40 | 33.40 | 1.10 | 2.80 | 11.00 | 27.00 | 72.00 |
|  |  |  | 3.3 | 0.75 | 1.75 | 5.68 | 13.60 | 37.40 | 2.20 | 4.30 | 14.00 | 32.00 | 82.00 |
|  |  |  | 3.6 | 1.58 | 3.10 | 8.07 | 17.20 | 43.30 | 4.90 | 7.70 | 20.00 | 41.00 | 97.00 |
|  | with IWDG <br> clocked by <br> LSI 32 kHz <br> ULPMEN $=0$ | 1.8 | 0.52 | 1.03 | 3.55 | 9.04 | 26.57 | 0.79 | 1.90 | 7.20 | 19.00 | 57.00 |  |
|  |  |  | 2.4 | 0.64 | 1.18 | 3.81 | 9.51 | 27.47 | 0.93 | 2.10 | 7.80 | 20.00 | 61.00 |
|  |  |  | 3.0 | 0.87 | 1.62 | 4.81 | 11.48 | 31.63 | 1.50 | 3.10 | 11.00 | 25.00 | 72.00 |
|  |  |  | 3.3 | 1.23 | 2.26 | 6.12 | 13.68 | 35.58 | 2.60 | 4.60 | 14.00 | 30.00 | 83.00 |
|  |  |  | 3.6 | 2.13 | 3.67 | 8.55 | 17.34 | 41.46 | 5.30 | 8.10 | 20.00 | 39.00 | 97.00 |
|  |  | with IWDG <br> clocked by <br> LSI 250 Hz <br> ULPMEN $=0$ | 1.8 | 0.38 | 0.88 | 3.44 | 9.15 | 28.00 | 0.77 | 1.90 | 7.60 | 21.00 | 57.00 |
|  |  |  | 2.4 | 0.40 | 0.94 | 3.63 | 9.58 | 29.20 | 0.79 | 2.00 | 8.00 | 22.00 | 61.00 |
|  |  |  | 3.0 | 0.55 | 1.28 | 4.55 | 11.50 | 33.50 | 1.30 | 2.90 | 11.00 | 27.00 | 72.00 |
|  |  |  | 3.3 | 0.87 | 1.90 | 5.83 | 13.70 | 37.50 | 2.30 | 4.40 | 14.00 | 32.00 | 82.00 |
|  |  |  | 3.6 | 1.71 | 3.26 | 8.22 | 17.30 | 43.30 | 5.10 | 7.90 | 20.00 | 41.00 | 97.00 |Table 68. Current consumption in Standby mode (continued)

|  Symbol | Parameter | Conditions |  | Typ |  |  |  | $\operatorname{Max}^{(1)}$ |  |  |  | Unit  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  | - | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$  |
|  $\begin{aligned} & \text { DD(Standby with } \ & \text { RTC) } \end{aligned}$ | Supply current in Standby mode (backup registers retained), RTC enabled |  | 1.8 | 0.56 | 1.05 | 3.60 | 9.29 | 28.10 | 0.81 | 1.90 | 7.50 | 20.00  |
|   |  |  | 2.4 | 0.64 | 1.18 | 3.88 | 9.82 | 29.40 | 0.93 | 2.20 | 8.20 | 22.00  |
|   |  |  | 3.0 | 0.88 | 1.61 | 4.88 | 11.80 | 33.80 | 1.50 | 3.20 | 11.00 | 27.00  |
|   |  |  | 3.3 | 1.25 | 2.26 | 6.19 | 14.10 | 37.80 | 2.60 | 4.70 | 14.00 | 33.00  |
|   |  |  | 3.6 | 2.13 | 3.67 | 8.63 | 17.70 | 43.70 | 5.30 | 8.20 | 20.00 | 42.00  |
|   |  | RTC ${ }^{(2)}$ clocked by LSI 250 Hz , no IWDG | 1.8 | 0.39 | 0.88 | 3.44 | 9.14 | 28.00 | 0.77 | 1.90 | 7.60 | 21.00  |
|   |  |  | 2.4 | 0.40 | 0.94 | 3.63 | 9.58 | 29.20 | 0.79 | 2.00 | 8.00 | 22.00  |
|   |  |  | 3.0 | 0.56 | 1.29 | 4.56 | 11.50 | 33.40 | 1.30 | 2.90 | 11.00 | 27.00  |
|   |  |  | 3.3 | 0.89 | 1.90 | 5.83 | 13.70 | 37.50 | 2.30 | 4.40 | 14.00 | 32.00  |
|   |  |  | 3.6 | 1.73 | 3.27 | 8.23 | 17.30 | 43.30 | 5.10 | 7.90 | 20.00 | 41.00  |
|   |  | RTC ${ }^{(2)}$ clocked by LSE bypassed at 32768 Hz | 1.8 | 0.47 | 0.96 | 3.51 | 9.22 | 28.10 | 0.95 | 2.10 | 7.70 | 21.00  |
|   |  |  | 2.4 | 0.50 | 1.04 | 3.75 | 9.72 | 29.40 | 1.10 | 2.30 | 8.30 | 22.00  |
|   |  |  | 3.0 | 0.69 | 1.42 | 4.71 | 11.70 | 33.80 | 1.60 | 3.30 | 11.00 | 27.00  |
|   |  |  | 3.3 | 1.04 | 2.06 | 6.00 | 13.90 | 37.80 | 2.70 | 4.80 | 15.00 | 33.00  |
|   |  |  | 3.6 | 1.91 | 3.46 | 8.43 | 17.60 | 43.70 | 5.50 | 8.30 | 21.00 | 42.00  |
|   |  | RTC ${ }^{(2)}$ clocked by LSE quartz in low-drive mode | 1.8 | 0.56 | 1.07 | 3.61 | 9.25 | 27.30 | - | - | - | -  |
|   |  |  | 2.4 | 0.59 | 1.15 | 3.83 | 9.70 | 28.30 | - | - | - | -  |
|   |  |  | 3.0 | 0.75 | 1.50 | 4.77 | 11.60 | 32.60 | - | - | - | -  |
|   |  |  | 3.3 | 1.07 | 2.11 | 6.04 | 13.80 | 36.60 | - | - | - | -  |
|   |  |  | 3.6 | 1.91 | 3.47 | 8.43 | 17.50 | 42.40 | - | - | - | -  |Table 68. Current consumption in Standby mode (continued)

| Symbol | Parameter | Conditions |  | Typ |  |  |  | $\operatorname{Max}^{(1)}$ |  |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | - | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |
| $\begin{aligned} & \text { I } \\ & \text { RTC) } \end{aligned}$ | Supply current in Standby mode (backup registers retained), RTC enabled | $\mathrm{RTC}^{(2)}$ clocked by LSE quartz in low-drive mode <br> ULPMEN $=1$ | 1.8 | 0.53 | 1.07 | 3.65 | 9.55 | 29.30 | - | - | - | - | - | $\mu \mathrm{A}$ |
|  |  |  | 2.4 | 0.56 | 1.13 | 3.90 | 10.10 | 30.10 | - | - | - | - | - |
|  |  |  | 3.0 | 0.71 | 1.47 | 4.85 | 12.45 | 35.30 | - | - | - | - | - |
|  |  |  | 3.3 | 1.07 | 2.06 | 6.10 | 14.55 | 39.00 | - | - | - | - | - |
|  |  |  | 3.6 | 1.86 | 3.50 | 8.60 | 17.90 | 45.50 | - | - | - | - | - |
| $\begin{aligned} & \text { I } \\ & \text { I } \\ & \text { I } \end{aligned}$ | Supply current to be added in Standby mode when backup SRAM is retained | - | 1.8 | 0.13 | 0.22 | 0.53 | 1.15 | 2.50 | 0.47 | 0.66 | 1.60 | 3.50 | 7.50 |
|  |  |  | 2.4 | 0.12 | 0.19 | 0.47 | 1.04 | 2.30 | 0.45 | 0.56 | 1.50 | 3.20 | 6.90 |
|  |  |  | 3.0 | 0.13 | 0.19 | 0.47 | 1.00 | 2.30 | 0.47 | 0.58 | 1.50 | 3.00 | 7.00 |
|  |  |  | 3.3 | 0.09 | 0.20 | 0.48 | 1.00 | 2.40 | 0.31 | 0.60 | 1.50 | 3.00 | 7.20 |
|  |  |  | 3.6 | 0.10 | 0.20 | 0.48 | 1.00 | 2.20 | 0.37 | 0.60 | 1.50 | 3.00 | 6.70 |
|  | Supply current to be added in Standby mode when full SRAM2 and BKPSRAM are retained | LDO | 1.8 | 1.62 | 4.09 | 11.92 | 25.75 | 55.60 | 5.90 | 13.00 | 36.00 | 78.00 | 170.00 |
|  |  |  | 2.4 | 1.62 | 4.05 | 11.88 | 25.74 | 55.60 | 5.90 | 13.00 | 36.00 | 78.00 | 170.00 |
|  |  |  | 3.0 | 1.64 | 4.02 | 11.87 | 25.80 | 55.70 | 6.00 | 13.00 | 36.00 | 78.00 | 170.00 |
|  |  |  | 3.3 | 1.65 | 4.02 | 11.82 | 25.70 | 55.70 | 6.00 | 13.00 | 36.00 | 78.00 | 170.00 |
|  |  |  | 3.6 | 1.68 | 3.99 | 11.73 | 25.50 | 55.20 | 6.10 | 12.00 | 36.00 | 77.00 | 170.00 |
|  | Supply current to be added in Standby mode when SRAM2 8-Kbyte page 1 and BKPSRAM are retained |  | 1.8 | 0.58 | 1.41 | 4.02 | 8.55 | 18.20 | 2.10 | 4.30 | 13.00 | 26.00 | 55.00 |
|  |  |  | 2.4 | 0.63 | 1.37 | 3.95 | 8.44 | 17.90 | 2.30 | 4.10 | 12.00 | 26.00 | 54.00 |
|  |  |  | 3.0 | 0.63 | 1.36 | 3.93 | 8.40 | 17.90 | 2.30 | 4.10 | 12.00 | 26.00 | 54.00 |
|  |  |  | 3.3 | 0.60 | 1.35 | 3.90 | 8.30 | 17.80 | 2.20 | 4.10 | 12.00 | 25.00 | 54.00 |
|  |  |  | 3.6 | 0.69 | 1.35 | 3.73 | 8.10 | 17.30 | 2.50 | 4.10 | 12.00 | 25.00 | 52.00 |Table 68. Current consumption in Standby mode (continued)

|  Symbol | Parameter | Conditions |  | Typ |  |  |  | $\operatorname{Max}^{(1)}$ |  |  |  | Unit  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  | - | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$  |
|  $\mathrm{I}_{\text {DD(SRAM2) }}$ | Supply current to be added in Standby mode when full SRAM2 and BKPSRAM are retained | SMPS | 1.8 | 0.97 | 2.23 | 6.55 | 14.25 | 31.40 | 3.50 | 6.70 | 20.00 | 43.00  |
|   |  |  | 2.4 | 0.63 | 1.48 | 4.40 | 9.44 | 19.50 | 2.30 | 4.50 | 14.00 | 29.00  |
|   |  |  | 3.0 | 0.67 | 1.51 | 4.50 | 9.90 | 21.60 | 2.50 | 4.60 | 14.00 | 30.00  |
|   |  |  | 3.3 | 0.56 | 1.35 | 4.05 | 8.90 | 19.60 | 2.10 | 4.10 | 13.00 | 27.00  |
|   |  |  | 3.6 | 0.55 | 1.19 | 3.53 | 7.80 | 17.40 | 2.00 | 3.60 | 11.00 | 24.00  |
|  $\mathrm{I}_{\text {DD(SRAM2_BK) }}$ | Supply current to be added in Standby mode when SRAM2 8-Kbyte page 1 and BKPSRAM are retained |  | 1.8 | 0.34 | 0.78 | 2.21 | 4.75 | 10.40 | 1.30 | 2.40 | 6.70 | 15.00  |
|   |  |  | 2.4 | 0.24 | 0.52 | 1.45 | 3.04 | 6.80 | 0.85 | 1.60 | 4.40 | 9.20  |
|   |  |  | 3.0 | 0.25 | 0.50 | 1.45 | 3.10 | 6.80 | 0.89 | 1.50 | 4.40 | 9.30  |
|   |  |  | 3.3 | 0.17 | 0.42 | 1.23 | 2.70 | 6.00 | 0.63 | 1.30 | 3.70 | 8.10  |
|   |  |  | 3.6 | 0.18 | 0.33 | 0.86 | 2.10 | 4.80 | 0.65 | 0.99 | 2.60 | 6.30  |

1. Evaluated by characterization. Not tested in production.
2. RTC with default configuration but LPCAL $=1$ in RTC_CALR.
3. Current consumption with IWDG enabled is similar.

Table 69. Current consumption during wake-up from Standby mode

|  Symbol | Parameter | Conditions |  | Typ ${ }^{(1)}$ | Unit  |
| --- | --- | --- | --- | --- | --- |
|   |  | - | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ |   |
|  $\mathrm{Q}_{\text {DD(wake-up from Standby) }}$ | Electrical charge consumed during wake-up from Standby mode | Wake-up clock is MSI 4 MHz | 3.0 | 3.2 | $\mu \mathrm{As}$  |
|   |  | Wake-up clock is MSI 1 MHz |  | 3.2 |   |

1. Evaluated by characterization in worse case condition $\left(\mathrm{V}*{\mathrm{DD} 11} / \mathrm{V}*{\mathrm{CAP}}=0 \mathrm{~V}\right.$ before wake-up).Table 70. Current consumption in Shutdown mode

| Symbol | Parameter | Conditions |  |  | Typ |  |  |  | Max ${ }^{(1)}$ |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | - | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |
| $\mathrm{I}_{\text {DD(Shutdown) }}$ | Supply current in Shutdown mode (backup registers retained), RTC disabled | - | 1.8 | 0.16 | 0.62 | 2.65 | 7.05 | 18.50 | 0.49 | 1.60 | 6.70 | 18.00 | 47.00 |
|  |  |  | 2.4 | 0.17 | 0.68 | 2.85 | 7.65 | 20.00 | 0.53 | 1.70 | 7.20 | 20.00 | 50.00 |
|  |  |  | 3.0 | 0.31 | 1.05 | 3.85 | 9.75 | 25.00 | 0.95 | 2.70 | 9.70 | 25.00 | 63.00 |
|  |  |  | 3.3 | 0.64 | 1.65 | 5.15 | 12.00 | 29.00 | 2.00 | 4.20 | 13.00 | 30.00 | 73.00 |
|  |  |  | 3.6 | 1.55 | 3.05 | 7.60 | 15.50 | 35.00 | 4.90 | 7.70 | 19.00 | 39.00 | 88.00 |
| $\begin{aligned} & \text { I } \\ & \text { IDD(Shutdown } \\ & \text { with RTC) } \end{aligned}$ | Supply current in Shutdown mode (backup registers retained), RTC enabled | RTC ${ }^{(2)}$ clocked by LSE bypassed at 32768 Hz | 1.8 | 0.33 | 0.80 | 2.85 | 7.25 | 19.00 | 0.67 | 1.80 | 6.90 | 18.00 | 47.00 |
|  |  |  | 2.4 | 0.37 | 0.88 | 3.10 | 7.85 | 20.50 | 0.75 | 2.00 | 7.40 | 20.00 | 51.00 |
|  |  |  | 3.0 | 0.57 | 1.30 | 4.15 | 10.00 | 25.50 | 1.30 | 2.90 | 10.00 | 25.00 | 64.00 |
|  |  |  | 3.3 | 0.94 | 2.00 | 5.50 | 12.50 | 29.50 | 2.40 | 4.60 | 14.00 | 31.00 | 74.00 |
|  |  |  | 3.6 | 1.90 | 3.45 | 8.00 | 16.00 | 35.50 | 5.20 | 8.10 | 20.00 | 40.00 | 89.00 |
|  |  | RTC ${ }^{(2)}$ clocked by LSE quartz in low-drive mode | 1.8 | 0.48 | 0.97 | 3.10 | 7.70 | 20.00 | - | - | - | - | - |
|  |  |  | 2.4 | 0.52 | 1.03 | 3.30 | 8.15 | 21.00 | - | - | - | - | - |
|  |  |  | 3.0 | 0.66 | 1.35 | 4.20 | 10.05 | 25.50 | - | - | - | - | - |
|  |  |  | 3.3 | 0.98 | 2.00 | 5.50 | 12.10 | 29.50 | - | - | - | - | - |
|  |  |  | 3.6 | 1.84 | 3.35 | 7.90 | 16.10 | 35.50 | - | - | - | - | - |

1. Evaluated by characterization. Not tested in production.
2. RTC with default configuration but LPCAL $=1$ in RTC_CALR.

Table 71. Current consumption during wake-up from Shutdown mode

| Symbol | Parameter | Conditions |  | Typ $^{(1)}$ | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | - | $\mathrm{V}_{\mathrm{DD}}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ |  |
| $\mathrm{Q}_{\text {DD(wake-up from }}$ <br> Shutdown) | Electrical charge consumed during wake-up from Shutdown mode | Wake-up clock is MSI 4 MHz | 3.0 | 3.4 | $\mu \mathrm{As}$ |

1. Evaluated by characterization in worse case condition $\left(\mathrm{V}_{\mathrm{DD} 11} / \mathrm{V}_{\mathrm{CAP}}=0 \mathrm{~V}\right.$ before wake-up).Table 72. Current consumption in $\mathrm{V}_{\mathrm{BAT}}$ mode

|  Symbol | Parameter | Conditions |  |  | Typ |  |  |  | $\operatorname{Max}^{(1)}$ |  |  |  |  | Unit  |
| --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- | --- |
|   |  | - | $\mathrm{V}_{\text {BAT }}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |   |
|  $\mathrm{I}_{\text {DD(VBAT) }}$ | Supply current in $\mathrm{V}_{\text {BAT }}$ mode (backup registers retained), RTC disabled | - | 1.8 | 0.12 | 0.27 | 1.00 | 2.60 | 7.70 | 0.36 | 0.67 | 2.50 | 6.50 | 20.00 | $\mu \mathrm{A}$  |
|   |  |  | 2.4 | 0.13 | 0.29 | 1.05 | 2.70 | 8.10 | 0.39 | 0.72 | 2.70 | 6.80 | 21.00 |   |
|   |  |  | 3.0 | 0.16 | 0.37 | 1.30 | 3.20 | 9.10 | 0.50 | 0.93 | 3.30 | 8.00 | 23.00 |   |
|   |  |  | 3.3 | 0.25 | 0.56 | 1.80 | 4.25 | 11.50 | 0.78 | 1.40 | 4.50 | 11.00 | 29.00 |   |
|   |  |  | 3.6 | 0.46 | 0.89 | 2.35 | 5.00 | 13.00 | 1.50 | 2.30 | 5.90 | 13.00 | 33.00 |   |
|  $\mathrm{I}_{\text {DD(VBAT with }}$ RTC) | Supply current in $\mathrm{V}_{\text {BAT }}$ mode (backup registers retained), RTC enabled | RTC ${ }^{(2)}$ clocked by LSE bypassed at 32768 Hz | 1.8 | 0.40 | 0.56 | 1.30 | 2.80 | 7.65 | 0.68 | 0.99 | 2.90 | 6.80 | 20.00 |   |
|   |  |  | 2.4 | 0.48 | 0.65 | 1.45 | 3.05 | 8.30 | 0.78 | 1.20 | 3.10 | 7.20 | 21.00 |   |
|   |  |  | 3.0 | 0.62 | 0.85 | 1.80 | 3.75 | 9.65 | 1.10 | 1.50 | 3.80 | 8.70 | 24.00 |   |
|   |  |  | 3.3 | 0.78 | 1.10 | 2.35 | 4.90 | 12.50 | 1.40 | 2.00 | 5.20 | 12.00 | 30.00 |   |
|   |  |  | 3.6 | 1.10 | 1.55 | 3.00 | 5.80 | 13.50 | 2.20 | 3.00 | 6.60 | 14.00 | 34.00 |   |
|   |  |  | 1.8 | 0.31 | 0.47 | 1.20 | 2.70 | 7.55 | 0.89 | 1.30 | 3.10 | 6.90 | 20.00 |   |
|   |  |  | 2.4 | 0.36 | 0.53 | 1.30 | 2.95 | 8.15 | 1.10 | 1.40 | 3.40 | 7.50 | 21.00 |   |
|   |  |  | 3.0 | 0.46 | 0.69 | 1.65 | 3.55 | 9.50 | 1.40 | 1.90 | 4.20 | 9.00 | 24.00 |   |
|   |  |  | 3.3 | 0.60 | 0.93 | 2.20 | 4.70 | 12.00 | 1.80 | 2.40 | 5.60 | 12.00 | 31.00 |   |
|   |  |  | 3.6 | 0.87 | 1.35 | 2.80 | 5.60 | 13.50 | 2.60 | 3.50 | 7.10 | 15.00 | 34.00 |   |
|   |  |  | 1.8 | 0.54 | 0.71 | 1.45 | 3.05 | 8.35 | - | - | - | - | - |   |
|   |  |  | 2.4 | 0.60 | 0.77 | 1.55 | 3.25 | 8.70 | - | - | - | - | - |   |
|   |  |  | 3.0 | 0.69 | 0.91 | 1.85 | 3.75 | 9.70 | - | - | - | - | - |   |
|   |  |  | 3.3 | 0.80 | 1.10 | 2.35 | 4.90 | 12.60 | - | - | - | - | - |   |
|   |  |  | 3.6 | 1.05 | 1.50 | 2.95 | 5.70 | 13.60 | - | - | - | - | - |   |Table 72. Current consumption in $\mathrm{V}_{\text {BAT }}$ mode (continued)

| Symbol | Parameter | Conditions |  | Typ |  |  |  | $\operatorname{Max}^{(1)}$ |  |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | - | $\mathrm{V}_{\text {BAT }}(\mathrm{V})$ | $25^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ | $30^{\circ} \mathrm{C}$ | $55^{\circ} \mathrm{C}$ | $85^{\circ} \mathrm{C}$ | $105^{\circ} \mathrm{C}$ | $125^{\circ} \mathrm{C}$ |
| $\begin{aligned} & \mathrm{I}_{\text {DD(VBAT with }} \\ & \text { RTC) } \end{aligned}$ | Supply current in $\mathrm{V}_{\text {BAT }}$ mode (backup registers retained), RTC enabled | RTC ${ }^{(2)}$ clocked by LSE quartz in low-drive mode, LPCAL $=1$ in RTC_CALR | 1.8 | 0.46 | 0.62 | 1.35 | 3.00 | 8.25 | - | - | - | - | - | $\mu \mathrm{A}$ |
|  |  |  | 2.4 | 0.48 | 0.66 | 1.45 | 3.10 | 8.55 | - | - | - | - | - |
|  |  |  | 3.0 | 0.53 | 0.76 | 1.70 | 3.60 | 9.55 | - | - | - | - | - |
|  |  |  | 3.3 | 0.63 | 0.95 | 2.20 | 4.70 | 12.10 | - | - | - | - | - |
|  |  |  | 3.6 | 0.85 | 1.30 | 2.75 | 5.50 | 13.60 | - | - | - | - | - |
| $\mathrm{I}_{\text {DD(BKPSRAM) }}$ | Supply current to be added in $\mathrm{V}_{\text {BAT }}$ mode when backup SRAM is retained | - | 1.8 | 0.12 | 0.19 | 0.41 | 0.85 | 1.75 | 0.26 | 0.44 | 1.10 | 2.50 | 5.20 |  |
|  |  |  | 2.4 | 0.12 | 0.19 | 0.45 | 0.95 | 1.90 | 0.26 | 0.45 | 1.30 | 2.80 | 5.60 |
|  |  |  | 3.0 | 0.12 | 0.20 | 0.50 | 1.05 | 2.40 | 0.28 | 0.49 | 1.40 | 3.10 | 7.10 |
|  |  |  | 3.3 | 0.13 | 0.22 | 0.50 | 1.10 | 2.50 | 0.31 | 0.54 | 1.40 | 3.20 | 7.40 |
|  |  |  | 3.6 | 0.14 | 0.22 | 0.50 | 1.20 | 2.50 | 0.36 | 0.55 | 1.40 | 3.50 | 7.40 |

1. Evaluated by characterization. Not tested in production.
2. RTC with default configuration except otherwise specified# I/O system current consumption 

The current consumption of the I/O system has two components: static and dynamic.

## I/O static current consumption

All the I/Os used as inputs with pull-up or pull-down generate current consumption when the pin is externally held to the opposite level. The value of this current consumption can be simply computed by using the pull-up/pull-down resistors values given in Section 5.3.15: I/O port characteristics.

For the output pins, any internal or external pull-up or pull-down or external load must also be considered to estimate the current consumption.

Additional I/O current consumption is due to I/Os configured as inputs if an intermediate voltage level is externally applied. This current consumption is caused by the input Schmitt trigger circuits used to discriminate the input value. Unless this specific configuration is required by the application, this supply current consumption can be avoided by configuring these I/Os in analog mode. This is notably the case of the ADC input pins, that must be configured as analog inputs.

Caution: Any floating input pin can also settle to an intermediate voltage level or switch inadvertently, as a result of external electromagnetic noise. To avoid current consumption related to floating pins, they must either be configured in analog mode, or forced internally to a definite digital value. This can be done either by using pull-up/down resistors or by configuring the pins in output mode.

## I/O dynamic current consumption

In addition to the on-chip peripheral current consumption (see Table 73 for peripheral current consumption in Run mode), the I/Os used by an application also contribute to the current consumption. When an I/O pin switches, it uses the current from the I/O supply voltage to supply the I/O pin circuitry and to charge/discharge the capacitive load (internal and external) connected to the pin:

$$
\mathrm{I}_{\mathrm{SW}}=\mathrm{V}_{\mathrm{DDIOx}} \times \mathrm{f}_{\mathrm{SW}} \times \mathrm{C}
$$

where:

- $\quad I_{S W}$ is the current sunk by a switching I/O to charge/discharge the capacitive load.
- $\quad \mathrm{V}_{\text {DDIOx }}$ is the I/O supply voltage.
- $\quad \mathrm{f}_{\mathrm{SW}}$ is the I/O switching frequency.
- $\quad C$ is the total capacitance seen by the I/O pin: $C=C_{\text {INT }}+C_{\text {EXT }}+C_{S}$.
- $\quad C_{S}$ is the PCB board capacitance including the pad pin.

The test pin is configured in push-pull output mode and is toggled by software at a fixed frequency.# On-chip peripheral current consumption 

The current consumption of the on-chip peripherals is given in the table below. The MCU is placed under the following conditions:

- All I/O pins are in analog mode.
- The given value is calculated by measuring the difference of the current consumptions:
- when the peripheral is clocked on
- when the peripheral is clocked off
- The ambient operating temperature and supply voltage conditions are summarized in Table 33.
- The power consumption of the digital part of the on-chip peripherals is given in the table below. The power consumption of the analog part of the peripherals (where applicable) is indicated in each related section of the datasheet.

Table 73. Typical dynamic current consumption of peripherals

| Bus | Peripheral | LDO |  |  |  |  | SMPS |  |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | AHB1 | 1.81 | 1.64 | 1.48 | 1.34 | - | 0.87 | 0.74 | 0.61 | 0.48 | - | $\mu \mathrm{A} /$ <br> $\mathrm{MHz}$ |
|  | BKPSRAM | 0.90 | 0.80 | 0.74 | 0.67 | - | 0.44 | 0.37 | 0.31 | 0.24 | - |  |
|  | CORDIC | 0.56 | 0.51 | 0.45 | 0.41 | - | 0.27 | 0.23 | 0.19 | 0.15 | - |  |
|  | CRC | 0.34 | 0.30 | 0.27 | 0.25 | - | 0.17 | 0.14 | 0.12 | 0.09 | - |  |
|  | DCACHE1 | 0.74 | 0.65 | 0.60 | 0.56 | - | 0.36 | 0.31 | 0.25 | 0.19 | - |  |
|  | DMA2D | 1.95 | 1.76 | 1.60 | 1.46 | - | 0.94 | 0.80 | 0.67 | 0.52 | - |  |
|  | FLASH | 2.21 | 2.01 | 1.82 | 1.65 | - | 1.07 | 0.91 | 0.76 | 0.59 | - |  |
|  | FMAC | 2.24 | 2.03 | 1.84 | 1.68 | - | 1.08 | 0.92 | 0.77 | 0.59 | - |  |
|  | GPDMA1 | 3.71 | 3.38 | 3.05 | 2.75 | - | 1.80 | 1.52 | 1.27 | 0.98 | - |  |
|  | GTZC1 | 0.39 | 0.34 | 0.31 | 0.30 | - | 0.18 | 0.16 | 0.13 | 0.10 | - |  |
|  | ICACHE | 0.76 | 0.68 | 0.63 | 0.57 | - | 0.37 | 0.32 | 0.26 | 0.20 | - |  |
|  | MDF1 | 7.65 | 6.95 | 6.27 | 5.67 | - | 3.69 | 3.12 | 2.61 | 2.01 | - |  |
|  | MDF1 indep ${ }^{(1)}$ | 0.84 | 0.76 | 0.68 | 0.63 | - | 0.4 | 0.34 | 0.29 | 0.22 | - |  |
|  | RAMCFG | 1.26 | 1.14 | 1.03 | 0.96 | - | 0.61 | 0.52 | 0.43 | 0.33 | - |  |
|  | SRAM1 | 0.82 | 0.73 | 0.67 | 0.62 | - | 0.40 | 0.34 | 0.28 | 0.22 | - |  |
|  | TSC | 1.11 | 1.00 | 0.91 | 0.83 | - | 0.54 | 0.46 | 0.38 | 0.29 | - |  |
|  | AHB2-1 | 2.08 | 1.88 | 1.71 | 1.54 | - | 1.00 | 0.85 | 0.71 | 0.55 | - |  |
|  | ADC1 | 2.01 | 1.84 | 1.65 | 1.52 | - | 0.97 | 0.82 | 0.69 | 0.53 | - |  |
|  | ADC1 indep ${ }^{(1)}$ | 1.43 | 1.30 | 1.17 | 1.06 | - | 0.69 | 0.58 | 0.48 | 0.37 | - |  |
|  | AES | 2.36 | 2.17 | 1.94 | 1.75 | - | 1.14 | 0.97 | 0.81 | 0.62 | - |  |Table 73. Typical dynamic current consumption of peripherals (continued)

| Bus | Peripheral | LDO |  |  |  |  | SMPS |  |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | DCMI | 4.68 | 4.28 | 3.87 | 3.50 | - | 2.26 | 1.92 | 1.61 | 1.24 | - | $\mu \mathrm{A} /$ <br> MHz |
|  | GPIOA | 0.08 | 0.07 | 0.07 | 0.05 | - | 0.04 | 0.03 | 0.03 | 0.02 | - |  |
|  | GPIOB | 0.06 | 0.05 | 0.04 | 0.04 | - | 0.03 | 0.02 | 0.02 | 0.01 | - |  |
|  | GPIOC | 0.11 | 0.11 | 0.08 | 0.08 | - | 0.05 | 0.05 | 0.04 | 0.03 | - |  |
|  | GPIOD | 0.07 | 0.07 | 0.06 | 0.06 | - | 0.04 | 0.03 | 0.03 | 0.02 | - |  |
|  | GPIOE | 0.04 | 0.05 | 0.03 | 0.03 | - | 0.02 | 0.02 | 0.01 | 0.01 | - |  |
|  | GPIOF | 0.07 | 0.08 | 0.06 | 0.05 | - | 0.04 | 0.03 | 0.03 | 0.02 | - |  |
|  | GPIOG | 0.22 | 0.21 | 0.17 | 0.16 | - | 0.11 | 0.09 | 0.07 | 0.05 | - |  |
|  | GPIOH | 0.22 | 0.21 | 0.17 | 0.17 | - | 0.11 | 0.09 | 0.07 | 0.06 | - |  |
|  | GPIOI | 0.12 | 0.13 | 0.10 | 0.09 | - | 0.06 | 0.05 | 0.04 | 0.03 | - |  |
|  | HASH | 1.18 | 1.10 | 0.98 | 0.88 | - | 0.57 | 0.49 | 0.41 | 0.31 | - |  |
|  | OCTOSPIM | 0.25 | 0.23 | 0.20 | 0.18 | - | 0.09 | 0.07 | 0.06 | 0.05 | - |  |
|  | OTFDEC1 | 1.86 | 1.72 | 1.52 | 1.38 | - | 0.90 | 0.76 | 0.64 | 0.49 | - |  |
|  | OTFDEC2 | 2.05 | 1.89 | 1.68 | 1.52 | - | 0.99 | 0.84 | 0.70 | 0.54 | - |  |
|  | PKA | 7.93 | 7.24 | 6.54 | 5.91 | - | 3.83 | 3.24 | 2.72 | 2.09 | - |  |
|  | RNG | 0.82 | 0.76 | 0.67 | 0.60 | - | 0.39 | 0.33 | 0.28 | 0.21 | - |  |
|  | RNG indep ${ }^{(1)}$ | 0.10 | 0.06 | 0.06 | 0.06 | - | 0.06 | 0.02 | 0.02 | 0.02 | - |  |
|  | SAES | 2.80 | 2.57 | 2.30 | 2.08 | - | 1.35 | 1.14 | 0.96 | 0.74 | - |  |
|  | SDMMC1 | 12.26 | 11.18 | 10.11 | 9.15 | - | 5.92 | 5.01 | 4.20 | 3.24 | - |  |
|  | SDMMC1 indep ${ }^{(1)}$ | 1.47 | 1.34 | 1.22 | 1.09 | - | 0.71 | 0.60 | 0.50 | 0.40 | - |  |
|  | SDMMC2 | 12.48 | 11.39 | 10.29 | 9.31 | - | 6.02 | 5.10 | 4.28 | 3.30 | - |  |
|  | SDMMC2 indep ${ }^{(1)}$ | 1.59 | 1.44 | 1.31 | 1.18 | - | 0.76 | 0.65 | 0.54 | 0.44 | - |  |
|  | SRAM2 | 1.18 | 1.10 | 0.97 | 0.88 | - | 0.57 | 0.48 | 0.40 | 0.32 | - |  |
|  | SRAM3 | 1.31 | 1.22 | 1.07 | 0.97 | - | 0.63 | 0.54 | 0.45 | 0.35 | - |  |
|  | USB_OTG_FS | 10.47 | 9.58 | 8.67 | 7.83 | - | 5.05 | 4.30 | 3.61 | 2.77 | - |  |
|  | AHB2-2 | 0.79 | 0.74 | 0.64 | 0.58 | - | 0.38 | 0.32 | 0.26 | 0.20 | - |  |
|  | FMC | 5.34 | 4.87 | 4.42 | 3.99 | - | 2.58 | 2.19 | 1.84 | 1.42 | - |  |
|  | OCTOSPI1 | 0.79 | 0.72 | 0.65 | 0.58 | - | 0.39 | 0.32 | 0.28 | 0.21 | - |  |
|  | OCTOSPI1 indep ${ }^{(1)}$ | 1.11 | 1.01 | 0.91 | 0.83 | - | 0.54 | 0.45 | 0.38 | 0.29 | - |  |
|  | OCTOSPI2 | 0.79 | 0.72 | 0.65 | 0.58 | - | 0.39 | 0.32 | 0.28 | 0.21 | - |  |
|  | OCTOSPI2 indep ${ }^{(1)}$ | 0.91 | 0.83 | 0.75 | 0.68 | - | 0.44 | 0.37 | 0.31 | 0.24 | - |  |Table 73. Typical dynamic current consumption of peripherals (continued)

| Bus | Peripheral | LDO |  |  |  |  | SMPS |  |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | ADC4 | 0.96 | 0.87 | 0.79 | 0.72 | 0.98 | 0.46 | 0.39 | 0.33 | 0.26 | 0.35 | $\mu \mathrm{A} /$ <br> MHz |
|  | ADC4 indep ${ }^{(1)}$ | 2.52 | 2.28 | 2.06 | 1.85 | 1.86 | 1.21 | 1.03 | 0.86 | 0.66 | 0.66 |  |
|  | ADF1 | 0.97 | 0.87 | 0.79 | 0.72 | 0.97 | 0.47 | 0.39 | 0.33 | 0.25 | 0.34 |  |
|  | ADF1 indep ${ }^{(1)}$ | 0.35 | 0.31 | 0.28 | 0.26 | 0.21 | 0.17 | 0.14 | 0.12 | 0.09 | 0.07 |  |
|  | AHB3 | 0.34 | 0.34 | 0.28 | 0.24 | - | 0.17 | 0.14 | 0.11 | 0.09 | - |  |
|  | DAC1 | 1.88 | 1.70 | 1.55 | 1.39 | 1.66 | 0.91 | 0.76 | 0.64 | 0.50 | 0.59 |  |
|  | DAC1 indep ${ }^{(1)}$ | 1.30 | 1.17 | 1.06 | 0.96 | 0.92 | 0.63 | 0.52 | 0.44 | 0.34 | 0.33 |  |
|  | GTZC2 | 0.34 | 0.32 | 0.30 | 0.29 | - | 0.16 | 0.14 | 0.12 | 0.11 | - |  |
|  | LPDMA1 | 0.43 | 0.39 | 0.36 | 0.32 | 0.58 | 0.21 | 0.17 | 0.14 | 0.11 | 0.20 |  |
|  | LPGPIO1 | 0.10 | 0.09 | 0.09 | 0.08 | 0.26 | 0.05 | 0.04 | 0.03 | 0.03 | 0.09 |  |
|  | PWR | 0.13 | 0.12 | 0.10 | 0.09 | - | 0.06 | 0.05 | 0.04 | 0.03 | - |  |
|  | SRAM4 | 0.45 | 0.40 | 0.37 | 0.34 | 0.26 | 0.21 | 0.18 | 0.15 | 0.12 | 0.09 |  |
|  | APB1 | 1.50 | 1.39 | 1.23 | 1.10 | - | 0.73 | 0.61 | 0.51 | 0.40 | - |  |
|  | CRS | 0.30 | 0.27 | 0.25 | 0.22 | - | 0.15 | 0.12 | 0.10 | 0.08 | - |  |
|  | FDCAN1 | 5.09 | 4.64 | 4.21 | 3.79 | - | 2.46 | 2.08 | 1.75 | 1.35 | - |  |
|  | FDCAN1 indep ${ }^{(1)}$ | 2.70 | 2.41 | 2.20 | 1.99 | - | 1.30 | 1.10 | 0.93 | 0.71 | - |  |
|  | I2C1 | 0.98 | 0.90 | 0.81 | 0.72 | - | 0.48 | 0.40 | 0.34 | 0.26 | - |  |
|  | I2C1 indep ${ }^{(1)}$ | 2.26 | 2.06 | 1.86 | 1.69 | - | 1.09 | 0.92 | 0.78 | 0.59 | - |  |
|  | I2C2 | 3.24 | 2.95 | 2.67 | 2.40 | - | 1.57 | 1.33 | 1.11 | 0.86 | - |  |
|  | I2C2 indep ${ }^{(1)}$ | 2.30 | 2.09 | 1.90 | 1.72 | - | 1.11 | 0.94 | 0.79 | 0.61 | - |  |
|  | I2C4 | 1.26 | 1.15 | 1.04 | 0.92 | - | 0.61 | 0.52 | 0.43 | 0.33 | - |  |
|  | I2C4 indep ${ }^{(1)}$ | 2.43 | 2.21 | 2.00 | 1.81 | - | 1.17 | 0.99 | 0.84 | 0.64 | - |  |Table 73. Typical dynamic current consumption of peripherals (continued)

| Bus | Peripheral | LDO |  |  |  |  | SMPS |  |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |
|  | LPTIM2 | 1.71 | 1.56 | 1.42 | 1.26 | - | 0.83 | 0.70 | 0.59 | 0.46 | - | $\mu \mathrm{A} /$ <br> $\mathrm{MH}_{2}$ |
|  | LPTIM2 indep ${ }^{(1)}$ | 4.20 | 3.83 | 3.48 | 3.15 | - | 2.03 | 1.72 | 4.95 | 1.11 | - |  |
|  | SPI2 | 1.90 | 1.73 | 1.57 | 1.40 | - | 0.92 | 0.77 | 0.66 | 0.51 | - |  |
|  | SPI2 indep ${ }^{(1)}$ | 0.81 | 0.75 | 0.68 | 0.62 | - | 0.40 | 0.33 | 0.28 | 0.21 | - |  |
|  | TIM2 | 4.01 | 3.64 | 3.31 | 2.99 | - | 1.93 | 1.64 | 1.37 | 1.06 | - |  |
|  | TIM3 | 4.51 | 4.10 | 3.72 | 3.35 | - | 2.18 | 1.84 | 1.55 | 1.19 | - |  |
|  | TIM4 | 4.27 | 3.88 | 3.52 | 3.16 | - | 2.06 | 1.74 | 1.46 | 1.12 | - |  |
|  | TIM5 | 3.95 | 3.60 | 3.27 | 2.93 | - | 1.91 | 1.62 | 1.36 | 1.04 | - |  |
|  | TIM6 | 0.95 | 0.86 | 0.78 | 0.69 | - | 0.46 | 0.39 | 0.33 | 0.25 | - |  |
|  | TIM7 | 0.90 | 0.82 | 0.75 | 0.65 | - | 0.44 | 0.37 | 0.31 | 0.24 | - |  |
|  | UART4 | 1.86 | 1.70 | 1.54 | 1.39 | - | 0.90 | 0.76 | 0.64 | 0.50 | - |  |
|  | UART4 indep ${ }^{(1)}$ | 3.47 | 3.17 | 2.87 | 2.60 | - | 1.68 | 1.42 | 1.19 | 0.93 | - |  |
|  | UART5 | 1.93 | 1.76 | 1.60 | 1.44 | - | 0.94 | 0.79 | 0.66 | 0.51 | - |  |
|  | UART5 indep ${ }^{(1)}$ | 3.57 | 3.25 | 2.95 | 2.67 | - | 1.72 | 1.46 | 1.23 | 0.95 | - |  |
|  | UCPD1 | 1.60 | 1.46 | 1.33 | 1.17 | - | 0.78 | 0.66 | 0.55 | 0.43 | - |  |
|  | USART2 | 5.53 | 5.04 | 4.57 | 4.12 | - | 2.67 | 2.26 | 1.91 | 1.46 | - |  |
|  | USART2 indep ${ }^{(1)}$ | 3.57 | 3.24 | 2.95 | 2.65 | - | 1.72 | 1.46 | 1.22 | 0.94 | - |  |
|  | USART3 | 2.10 | 1.91 | 1.73 | 1.57 | - | 1.02 | 0.86 | 0.72 | 0.56 | - |  |
|  | USART3 indep ${ }^{(1)}$ | 4.24 | 3.86 | 3.5 | 3.17 | - | 2.05 | 1.73 | 1.45 | 1.12 | - |  |
|  | WWDG | 0.37 | 0.34 | 0.31 | 0.25 | - | 0.18 | 0.15 | 0.13 | 0.10 | - |  |
|  | APB2 | 0.60 | 0.58 | 0.50 | 0.42 | - | 0.29 | 0.25 | 0.20 | 0.16 | - |  |
|  | SAI1 | 2.10 | 1.90 | 1.73 | 1.55 | - | 1.01 | 0.86 | 0.72 | 0.55 | - |  |
|  | SAI1 indep ${ }^{(1)}$ | 1.36 | 1.23 | 1.11 | 0.95 | - | 0.66 | 0.55 | 0.46 | 0.34 | - |  |
|  | SAI2 | 1.98 | 1.80 | 1.64 | 1.48 | - | 0.96 | 0.81 | 0.68 | 0.53 | - |  |
|  | SAI2 indep ${ }^{(1)}$ | 1.25 | 1.14 | 1.02 | 0.92 | - | 0.60 | 0.51 | 0.43 | 0.40 | - |  |
|  | SPI1 | 2.17 | 1.97 | 1.79 | 1.63 | - | 1.05 | 0.89 | 0.75 | 0.57 | - |  |Table 73. Typical dynamic current consumption of peripherals (continued)

| Bus | Peripheral | LDO |  |  |  |  | SMPS |  |  |  |  | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  |  |  |  |  |  |  |  |  |  |  |  |
|  |  |  |  |  |  |  |  |  |  |  |  |  |
| $\begin{aligned} & \text { A } \\ & \text { A } \\ & \text { A } \\ & \text { A } \end{aligned}$ | SPI1 indep ${ }^{(1)}$ | 0.97 | 0.88 | 0.79 | 0.72 | - | 0.47 | 0.39 | 0.33 | 0.25 | - | $\mu \mathrm{A} /$ <br> $\mathrm{MH}_{2}$ |
|  | TIM1 | 6.14 | 5.59 | 5.08 | 4.60 | - | 2.96 | 2.52 | 2.11 | 1.63 | - |  |
|  | TIM15 | 3.37 | 3.06 | 2.79 | 2.51 | - | 1.63 | 1.38 | 1.16 | 0.89 | - |  |
|  | TIM16 | 2.60 | 2.36 | 2.15 | 1.94 | - | 1.25 | 1.06 | 0.90 | 0.69 | - |  |
|  | TIM17 | 2.40 | 2.18 | 1.99 | 1.79 | - | 1.16 | 0.98 | 0.82 | 0.63 | - |  |
|  | TIM8 | 6.24 | 5.69 | 5.16 | 4.66 | - | 3.01 | 2.55 | 2.15 | 1.65 | - |  |
|  | USART1 | 2.38 | 2.16 | 1.96 | 1.76 | - | 1.14 | 0.97 | 0.81 | 0.62 | - |  |
|  | USART1 indep ${ }^{(1)}$ | 4.48 | 4.09 | 3.71 | 3.35 | - | 2.17 | 1.84 | 1.54 | 1.19 | - |  |
|  | APB3 | 0.49 | 0.48 | 0.40 | 0.36 | - | 0.24 | 0.20 | 0.16 | 0.13 | - |  |
|  | COMP | 0.20 | 0.18 | 0.16 | 0.14 | 0.15 | 0.10 | 0.08 | 0.06 | 0.05 | 0.05 |  |
|  | I2C3 | 0.79 | 0.71 | 0.65 | 0.58 | 0.59 | 0.38 | 0.32 | 0.27 | 0.20 | 0.21 |  |
|  | I2C3 indep ${ }^{(1)}$ | 1.84 | 1.66 | 1.50 | 1.36 | 1.36 | 0.89 | 0.75 | 0.63 | 0.48 | 0.48 |  |
|  | LPTIM1 | 0.98 | 0.89 | 0.81 | 0.72 | 0.73 | 0.48 | 0.40 | 0.33 | 0.25 | 0.26 |  |
|  | LPTIM1 indep ${ }^{(1)}$ | 3.08 | 2.81 | 2.49 | 2.29 | 2.33 | 1.46 | 1.24 | 1.04 | 0.81 | 0.83 |  |
|  | LPTIM3 | 1.07 | 0.98 | 0.89 | 0.80 | 0.80 | 0.52 | 0.44 | 0.37 | 0.28 | 0.28 |  |
|  | LPTIM3 indep ${ }^{(1)}$ | 2.85 | 2.61 | 2.36 | 2.15 | 2.19 | 1.43 | 1.22 | 0.98 | 0.77 | 0.78 |  |
|  | LPTIM4 | 0.58 | 0.52 | 0.48 | 0.42 | 0.43 | 0.28 | 0.24 | 0.20 | 0.15 | 0.15 |  |
|  | LPTIM4 indep ${ }^{(1)}$ | 1.67 | 1.50 | 1.38 | 1.26 | 1.30 | 0.8 | 0.70 | 0.57 | 0.44 | 0.46 |  |
|  | LPUART1 | 1.18 | 1.07 | 0.97 | 0.87 | 0.88 | 0.57 | 0.48 | 0.41 | 0.31 | 0.31 |  |
|  | LPUART1 indep ${ }^{(1)}$ | 1.96 | 1.78 | 1.62 | 1.45 | 1.46 | 0.95 | 0.80 | 0.67 | 0.52 | 0.52 |  |
|  | OPAMP | 0.19 | 0.17 | 0.16 | 0.12 | 0.14 | 0.09 | 0.07 | 0.07 | 0.04 | 0.05 |  |
|  | RTC | 2.33 | 2.12 | 1.92 | 1.73 | 1.63 | 1.12 | 0.95 | 0.80 | 0.61 | 0.58 |  |
|  | SPI3 | 1.48 | 1.34 | 1.22 | 1.10 | 1.10 | 0.71 | 0.61 | 0.51 | 0.38 | 0.39 |  |
|  | SPI3 indep ${ }^{(1)}$ | 0.57 | 0.52 | 0.47 | 0.42 | 0.42 | 0.28 | 0.24 | 0.20 | 0.15 | 0.15 |  |
|  | SYSCFG | 0.29 | 0.27 | 0.24 | 0.22 | - | 0.14 | 0.12 | 0.10 | 0.08 | - |  |
|  | VREFBUF | 0.13 | 0.11 | 0.10 | 0.08 | 0.09 | 0.06 | 0.05 | 0.04 | 0.03 | 0.03 |  |

1. indep $=$ independent clock domain.# 5.3.7 Wake-up time from low-power modes and voltage scaling transition times 

The wake-up times given in the table below are the latency between the event and the execution of the first user instruction (FSTEN $=1$ in PWR_CR3 if not mentioned).
The device goes in low-power mode after the WFE (wait for event) instruction.
Table 74. Low-power mode wake-up timings on $\mathrm{LDO}^{(1)}$

| Mode | Parameter | Conditions |  | Typ$\left(3 \mathrm{~V}, 25^{\circ} \mathrm{C}\right)$ | Max <br> (3 V) | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{t}_{\text {wu(Sleep) }}$ | Wake-up time from Sleep to Run mode | SLEEP_PD $=0$ |  | 14 | 17 | Nb of CPU cycles |
|  |  | SLEEP_PD $=1$ with MSI $=24 \mathrm{MHz}$ |  | 8.1 | 8.8 | $\mu \mathrm{s}$ |
| $\mathrm{t}_{\text {wu(Stop 0) }}$ | Wake-up time from Stop 0 to Run mode All SRAMs retained | Wake-up in FLASH, range 4, FLASHFWU $=1$ and SRAM4FWU $=1$ in PWR_CR2, ICACHE OFF | MSI 24 MHz | 2.35 | 2.5 |  |
|  |  | Wake-up in FLASH, range 4, FLASHFWU $=0$ and SRAM4FWU $=0$ in PWR_CR2, ICACHE OFF | MSI 24 MHz | 11.0 | 12.0 |  |
|  |  |  | HSI 16 MHz | 11.0 | 12.0 |  |
|  |  |  | MSI 1 MHz | 37.0 | 39.0 |  |
|  |  | Wake-up in SRAM2, range 4, FLASHFWU $=0$ and SRAM4FWU $=0$ in PWR_CR2 | MSI 24 MHz | 4.75 | 5.00 |  |
|  |  |  | HSI 16 MHz | 6.75 | 7.4 |  |
|  |  |  | MSI 1 MHz | 34.00 | 36.0 |  |
| $\mathrm{t}_{\text {wu(Stop 1) }}$ | Wake-up time from Stop 1 to Run mode All SRAMs retained | Wake-up in FLASH, FLASHFWU $=1$ and SRAM4FWU $=1$ in PWR_CR2, ICACHE OFF | MSI 24 MHz | 13.0 | 15.0 |  |
|  |  | Wake-up in FLASH, FLASHFWU $=0$ and SRAM4FWU $=0$ in PWR_CR2, ICACHE OFF | MSI 24 MHz | 22.0 | 24.0 |  |
|  |  |  | HSI 16 MHz | 21.5 | 24.0 |  |
|  |  |  | MSI 1 MHz | 48.0 | 51.0 |  |
|  |  | Wake-up in SRAM2, range 4, FLASHFWU $=0$ and SRAM4FWU $=0$ in PWR_CR2 | MSI 24 MHz | 15.5 | 18.0 |  |
|  |  |  | HSI 16 MHz | 17.5 | 20.0 |  |
|  |  |  | MSI 1 MHz | 45.0 | 48.0 |  |Table 74. Low-power mode wake-up timings on $\mathrm{LDO}^{(1)}$ (continued)

| Mode | Parameter | Conditions |  | Typ $\left(3 \mathrm{~V}, 25^{\circ} \mathrm{C}\right)$ | $\begin{gathered} \text { Max } \\ (3 \mathrm{~V}) \end{gathered}$ | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{t}_{\text {wu(Stop 2) }}$ | Wake-up time from Stop 2 to Run mode All SRAMs retained | Wake-up in FLASH, SRAM4FWU $=1$ in PWR_CR2, ICACHE OFF | MSI 24 MHz | 20.0 | 23.0 | $\mu \mathrm{s}$ |
|  |  | Wake-up in FLASH, SRAM4FWU $=0$ in PWR_CR2, ICACHE OFF | MSI 24 MHz | 23.0 | $25.0^{(2)}$ |  |
|  |  |  | HSI 16 MHz | 22.5 | 25.0 |  |
|  |  |  | MSI 1 MHz | 57.0 | 60.0 |  |
|  |  | Wake-up in SRAM2, range 4, SRAM4FWU $=0$ in PWR_CR2 | MSI 24 MHz | 16.5 | 19.0 |  |
|  |  |  | HSI 16 MHz | 18.5 | 21.0 |  |
|  |  |  | MSI 1 MHz | 54.0 | 57.0 |  |
| $\mathrm{t}_{\text {wu(Stop 3) }}$ | Wake-up time from Stop 3 to Run mode All SRAMs retained | Wake-up in FLASH, FSTEN $=0$ in PWR_CR3, ICACHE OFF | MSI 24 MHz | 68.0 | 130 |  |
|  |  | Wake-up in FLASH, FSTEN $=1$ in PWR_CR3, ICACHE OFF | MSI 24 MHz | 28.50 | 37.0 |  |
|  |  |  | HSI 16 MHz | 28.0 | 36.0 |  |
|  |  |  | MSI 1 MHz | 68.50 | 91.0 |  |
|  |  | Wake-up in SRAM2, range 4, FLASHFWU $=0$ and SRAM4FWU $=0$ in PWR_CR2 | MSI 24 MHz | 22.50 | 31.0 |  |
|  |  |  | HSI 16 MHz | 24.0 | 32.0 |  |
|  |  |  | MSI 1 MHz | 64.5 | 85.0 |  |
| $\mathrm{t}_{\text {wu(Standby }}$ with SRAM2) | Wake-up time from Standby with SRAM2 to Run mode | Wake-up in FLASH, FSTEN $=0$ in PWR_CR3 | MSI 4 MHz | 64.5 | 110 |  |
|  |  | Wake-up in FLASH, FSTEN $=1$ in PWR_CR3 | MSI 4 MHz | 64.5 | 83.0 |  |
|  |  |  | MSI 1 MHz | 155 | 240 |  |
| $\mathrm{t}_{\text {wu(Standby) }}$ | Wake-up time from Standby to Run mode | Wake-up in FLASH, FSTEN $=0$ in PWR_CR3 | MSI 4 MHz | 340 | 420 |  |
|  |  | Wake-up in FLASH, FSTEN $=1$ in PWR_CR3 | MSI 4 MHz | 100 | 130 |  |
|  |  |  | MSI 1 MHz | 210 | 290 |  |
| $\mathrm{t}_{\text {wu(Shutdown) }}$ | Wake-up time from Shutdown to Run mode | - | MSI 4 MHz | 610 | 710 |  |

1. Evaluated by characterization and not tested in production, unless otherwise specified.
2. Tested in production at $130^{\circ} \mathrm{C}$.Table 75. Low-power mode wake-up timings on SMPS ${ }^{(1)}$

| Mode | Parameter | Conditions |  | $\begin{aligned} & \text { Typ } \\ & \text { (3 V, } \\ & 25^{\circ} \mathrm{C} \text { ) } \end{aligned}$ | $\begin{aligned} & \text { Max } \\ & (3 \mathrm{~V}) \end{aligned}$ | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{t}_{\text {wu(Sleep) }}$ | Wake-up time from Sleep to Run mode | SLEEP_PD $=0$ |  | 14 | 17 | Nb of <br> CPU <br> cycles |
|  |  | SLEEP_PD $=1$ with MSI $=24 \mathrm{MHz}$ |  | 8.1 | 8.8 |  |
| $\mathrm{t}_{\text {wu(Stop 0) }}$ | Wake-up time from Stop 0 to Run mode All SRAMs retained | Wake-up in FLASH, range 4, FLASHFWU $=1$ and SRAM4FWU $=1$ in PWR_CR2 | MSI 24 MHz | 2.35 | 2.5 |  |
|  |  | Wake-up in FLASH, range 4, FLASHFWU $=0$ and SRAM4FWU $=0$ in PWR_CR2 | MSI 24 MHz | 11.0 | 12.0 |  |
|  |  |  | HSI 16 MHz | 11.0 | 12.0 |  |
|  |  |  | MSI 1 MHz | 37.0 | 39.0 |  |
|  |  | Wake-up in SRAM2, range 4, FLASHFWU $=0$ and SRAM4FWU $=0$ in PWR_CR2 | MSI 24 MHz | 4.75 | 5.0 |  |
|  |  |  | HSI 16 MHz | 6.75 | 7.4 |  |
|  |  |  | MSI 1 MHz | 34.0 | 36.0 |  |
| $\mathrm{t}_{\text {wu(Stop 1) }}$ | Wake-up time from Stop 1 to Run mode All SRAMs retained | Wake-up in FLASH, FLASHFWU $=1$ and SRAM4FWU $=1$ in PWR_CR2 | MSI 24 MHz | 7.7 | 8.3 | $\mu \mathrm{s}$ |
|  |  | Wake-up in FLASH <br> FLASHFWU $=0$ and <br> SRAM4FWU $=0$ in <br> PWR_CR2 | MSI 24 MHz | 16.5 | 18.0 |  |
|  |  |  | HSI 16 MHz | 16.0 | 18.0 |  |
|  |  |  | MSI 1 MHz | 42.5 | 45.0 |  |
|  |  | Wake-up in SRAM2, range 4, FLASHFWU $=0$ and SRAM4FWU $=0$ in PWR_CR2 | MSI 24 MHz | 10.0 | 11.0 |  |
|  |  |  | HSI 16 MHz | 12.0 | 13.0 |  |
|  |  |  | MSI 1 MHz | 39.5 | 42.0 |  |
| $\mathrm{t}_{\text {wu(Stop 2) }}$ | Wake-up time from Stop 2 to Run mode All SRAMs retained | Wake-up in FLASH <br> SRAM4FWU $=1$ in PWR_CR2 | MSI 24 MHz | 17.5 | 19.0 |  |
|  |  | Wake-up in FLASH <br> SRAM4FWU $=0$ in PWR_CR2 | MSI 24 MHz | 20.5 | 22.0 |  |
|  |  |  | HSI 16 MHz | 20.0 | 22.0 |  |
|  |  |  | MSI 1 MHz | 54.0 | 70.0 |  |
|  |  | Wake-up in SRAM2, range 4, SRAM4FWU $=0$ in PWR_CR2 | MSI 24 MHz | 14.0 | 16.0 |  |
|  |  |  | HSI 16 MHz | 16.0 | 18.0 |  |
|  |  |  | MSI 1 MHz | 51.5 | 74.0 |  |Table 75. Low-power mode wake-up timings on SMPS ${ }^{(1)}$ (continued)

| Mode | Parameter | Conditions |  | $\begin{aligned} & \text { Typ } \\ & \left(3 \mathrm{~V}, \quad \text { Max }\right. \\ & 25^{\circ} \mathrm{C} \text { ) } \end{aligned}$ | Unit |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{\text {wu(Stop 3) }}$ | Wake-up time from Stop 3 to Run mode All SRAMs retained | Wake-up in FLASH, FSTEN $=0$ in PWR_CR3 | MSI 24 MHz | 130 | 160 | $\mu \mathrm{s}$ |
|  |  | Wake-up in FLASH, FSTEN $=1$ in PWR_CR3 | MSI 24 MHz | 32.5 | 37.0 |  |
|  |  |  | HSI 16 MHz | 32.0 | 36.0 |  |
|  |  |  | MSI 1 MHz | 72.5 | 94.0 |  |
|  |  | Wake-up in SRAM2, range 4 | MSI 24 MHz | 26.5 | 31.0 |  |
|  |  |  | HSI 16 MHz | 28.0 | 32.0 |  |
|  |  |  | MSI 1 MHz | 68.5 | 89.0 |  |
| $\begin{aligned} & t_{\text {wu(Standby }} \\ & \text { with SRAM2) } \end{aligned}$ | Wake-up time from Standby with SRAM2 to Run mode | Wake-up in FLASH, FSTEN $=0$ in PWR_CR3 | MSI 4 MHz | 61.5 | 80.0 |  |
|  |  | Wake-up in FLASH, FSTEN $=1$ in PWR_CR3 | MSI 4 MHz | 61.5 | 80.0 |  |
|  |  |  | MSI 1 MHz | 150 | 240 |  |
| $t_{\text {wu(Standby) }}$ | Wake-up time from Standby to Run mode | Wake-up in FLASH, FSTEN $=0$ in PWR_CR3 | MSI 4 MHz | 340 | 420 |  |
|  |  | Wake-up in FLASH, FSTEN $=1$ in PWR_CR3 | MSI 4 MHz | 100 | 130 |  |
|  |  |  | MSI 1 MHz | 210 | 290 |  |
| $t_{\text {wu(Shutdown) }}$ | Wake-up time from Shutdown to Run mode | - | MSI 4 MHz | 610 | 710 |  |

1. Evaluated by characterization. Not tested in production.

Table 76. Regulator mode transition times ${ }^{(1)}$

| Symbol | Parameter | Conditions | Typ (3 V, $25^{\circ} \mathrm{C}$ ) | Max (3 V) | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{\text {LDO }}{ }^{(2)}$ | SMPS to LDO transition time | Range 4 | 16.0 | $20.0^{(3)}$ | $\mu \mathrm{s}$ |
|  |  | Range 3 | 15.0 | 17.0 |  |
|  |  | Range 2 | 14.0 | 18.0 |  |
|  |  | Range 1 | 14.0 | 16.0 |  |
| $t_{\text {SMPS }}{ }^{(2)}$ | LDO to SMPS transition time | Range 4 | 14.0 | $16.0^{(3)}$ |  |
|  |  | Range 3 | 17.0 | 20.0 |  |
|  |  | Range 2 | 16.0 | 19.0 |  |
|  |  | Range 1 | 16.0 | 19.0 |  |Table 76. Regulator mode transition times ${ }^{(1)}$ (continued)

| Symbol | Parameter | Conditions | Typ $\left(3 \mathrm{~V}, 25^{\circ} \mathrm{C}\right)$ | Max (3 V) | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{t}_{\text {VOSY }}{ }^{(4)}$ | Range 4 to range 3 | LDO | 19.0 | 21.0 | $\mu \mathrm{s}$ |
|  |  | SMPS | 25.0 | 38.0 |  |
|  | Range 3 to range 2 | LDO | 13.0 | 15.0 |  |
|  |  | SMPS | 13.0 | 23.0 |  |
|  | Range 2 to range 1 | LDO | 12.0 | 14.0 |  |
|  |  | SMPS | 12.0 | 17.0 |  |
|  | Range 4 to range 1 | LDO | 42.0 | 47.0 |  |
|  |  | SMPS | 48.0 | 76.0 |  |

1. Evaluated by characterization and not tested in production, unless otherwise specified.
2. Time to REGS change in PWR_SVMSR.
3. Tested in production at $30^{\circ} \mathrm{C}$.
4. Time to VOSRDY $=1$ in PWR_VOSR.

Table 77. Wake-up time using USART/LPUART ${ }^{(1)}$

| Symbol | Parameter | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $\mathrm{t}_{\text {WUUSART }}$ | Wake-up time needed to calculate the maximum USART/LPUART baud rate that is needed to wake up from Stop mode when the USART/LPUART kernel clock source is HSI16/MSI. | - | $(2)$ | $\mu \mathrm{s}$ |

1. Specified by design. Not tested in production.
2. This wake-up time is the HSI16 (see Table 82) or the MSI (see Table 83) oscillator maximum startup time.

# 5.3.8 External clock timing characteristics 

## High-speed external user clock generated from an external source

In bypass mode, the HSE oscillator is switched off and the input pin is a standard GPIO.
The external clock signal has to respect the I/O characteristics in Section 5.3.15: I/O port characteristics. However, the recommended clock input waveform is shown in the figure below.

Table 78. High-speed external user clock characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions |  | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{t}_{\text {HSE_ext }}$ | User external clock source frequency | Digital mode (HSEBYP = 1, HSEEXT = 1) | Voltage scaling range 1, 2, 3 | - | - | 55 | MHz |
|  |  | Analog mode (HSEBYP = 1, HSEEXT = 0) |  | $4^{(2)}$ | - | 50 |  |
|  |  | - | Voltage scaling range 4 | $4^{(2)}$ | - | 25 |  |Table 78. High-speed external user clock characteristics ${ }^{(1)}$ (continued)

| Symbol | Parameter | Conditions |  | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{V}_{\text {HSEH }}$ | OSC_IN input pin high-level voltage | Digital mode (HSEBYP = 1, HSEEXT $=1$ ) | - | $0.7 \times V_{D D}$ | - | $\mathrm{V}_{\mathrm{DD}}$ | V |
| $\mathrm{V}_{\text {HSEL }}$ | OSC_IN input pin low-level voltage |  | - | $\mathrm{V}_{\mathrm{SS}}$ | - | $0.3 \times \mathrm{V}_{\mathrm{DD}}$ |  |
| $\begin{aligned} & \mathrm{t}_{\mathrm{w}(\text { HSEH })} \\ & \mathrm{t}_{\mathrm{w}(\text { HSEL })} \end{aligned}$ | OSC_IN high or low time |  | Voltage scaling range $1,2,3$ | 7 | - | - | ns |
|  |  |  | Voltage scaling range 4 | 18 | - | - |  |
| $\mathrm{DuCy}_{\text {HSE }}$ | OSC_IN duty cycle |  | - | 45 | - | 55 | \% |
| $\begin{gathered} \mathrm{V}_{\text {HSE_ext. }} \\ \text { PP } \end{gathered}$ | OSC_IN peak-to-peak amplitude | Analog mode (HSEBYP = 1, HSEEXT $=0$ ) | - | 0.2 | - | $2 / 3 \mathrm{~V}_{\mathrm{DD}}$ | V |
| $\mathrm{V}_{\text {HSE_ext }}$ | OSC_IN input range |  | - | 0 | - | $\mathrm{V}_{\mathrm{DD}}$ |  |
| $\begin{gathered} \mathrm{t}_{\mathrm{f}(\text { HSE })} \\ \mathrm{t}_{\mathrm{f}}(\mathrm{HSE}) \end{gathered}$ | OSC_IN rise and fall time |  | - | $\begin{gathered} 0.05 / \\ \mathrm{t}_{\text {HSE_ext }} \end{gathered}$ | - | $\begin{gathered} 0.3 / \\ \mathrm{t}_{\text {HSE_ext }} \end{gathered}$ | ns |

1. Specified by design. Not tested in production.
2. Only for Analog mode. No minimum value in digital mode.

Figure 28. AC timing diagram for high-speed external clock source (digital mode)
![img-47.jpeg](img-47.jpeg)Figure 29. AC timing diagram for high-speed external clock source (analog mode)
![img-48.jpeg](img-48.jpeg)

# Low-speed external user clock generated from an external source 

In bypass mode, the LSE oscillator is switched off and the input pin is a standard GPIO.
The external clock signal has to respect the I/O characteristics in Section 5.3.15: I/O port characteristics. However, the recommended clock input waveform is shown in Figure 30 and Figure 31.

Table 79. Low-speed external user clock characteristics ${ }^{(1)}$

| Symbol | Parameter | Min | Typ | Max | Unit |
| :--: | :-- | :--: | :--: | :--: | :--: |
| $\mathrm{f}_{\text {LSE_ext }}$ | User external clock source frequency | 5 | 32.768 | 40 | kHz |
| $\mathrm{V}_{\text {LSE_ext PP }}$ | OSC32_IN peak-to-peak amplitude | 0.3 | - | $\mathrm{V}_{\mathrm{SW}}$ | V |
| $\mathrm{V}_{\text {LSE_ext }}$ | OSC32_IN input range | 0 | - | $\mathrm{V}_{\mathrm{SW}}{ }^{(2)}$ |  |
| $\mathrm{t}_{\mathrm{w}(\text { LSEH })}$ | OSC32_IN high or low time for square signal input | 10 | - | - | $\mu \mathrm{s}$ |

1. Specified by design. Not tested in production.
2. In case VBAT mode is used, $\mathrm{V}_{\mathrm{LSE} \text { _ext }}$ must be lower than $\mathrm{V}_{\text {BOR0 }}$ in order to respect this requirement when the switch to VBAT occurs.

Figure 30. AC timing diagram for low-speed external square clock source
![img-49.jpeg](img-49.jpeg)Figure 31. AC timing diagram for low-speed external sinusoidal clock source
![img-50.jpeg](img-50.jpeg)

# High-speed external clock generated from a crystal/ceramic resonator 

The high-speed external (HSE) clock can be supplied with a 4 to 48 MHz crystal/ceramic resonator oscillator. All the information given in this paragraph are based on design simulation results obtained with typical external components specified in the table below.

In the application, the resonator and the load capacitors have to be placed as close as possible to the oscillator pins, in order to minimize the output distortion and startup stabilization time. Refer to the crystal resonator manufacturer for more details on the resonator characteristics (frequency, package, accuracy).

Table 80. HSE oscillator characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions ${ }^{(2)}$ | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{\text {OSC_IN }}$ | Oscillator frequency | - | 4 | - | 50 | MHz |
| $R_{F}$ | Feedback resistor | - | - | 200 | - | $\mathrm{k} \Omega$ |
| $\mathrm{I}_{\mathrm{DD}(\mathrm{HSE})}$ | HSE current consumption | Rev. $X$ | During startup ${ }^{(3)}$ | - | - | 8 | mA |
|  |  |  | $\mathrm{V}_{\mathrm{DD}}=3 \mathrm{~V}, \mathrm{Rm}=30 \Omega, \mathrm{C}_{\mathrm{L}}=10 \mathrm{pF} @ 4 \mathrm{MHz}$ | - | 670 | - | $\mu \mathrm{A}$ |
|  |  |  | $\mathrm{V}_{\mathrm{DD}}=3 \mathrm{~V}, \mathrm{Rm}=30 \Omega, \mathrm{C}_{\mathrm{L}}=10 \mathrm{pF} @ 8 \mathrm{MHz}$ | - | 530 | - |
|  |  |  | $\mathrm{V}_{\mathrm{DD}}=3 \mathrm{~V}, \mathrm{Rm}=45 \Omega, \mathrm{C}_{\mathrm{L}}=10 \mathrm{pF} @ 8 \mathrm{MHz}$ | - | 580 | - |
|  |  |  | $\mathrm{V}_{\mathrm{DD}}=3 \mathrm{~V}, \mathrm{Rm}=30 \Omega, \mathrm{C}_{\mathrm{L}}=5 \mathrm{pF} @ 48 \mathrm{MHz}$ | - | 980 | - |
|  |  |  | $\mathrm{V}_{\mathrm{DD}}=3 \mathrm{~V}, \mathrm{Rm}=30 \Omega, \mathrm{C}_{\mathrm{L}}=10 \mathrm{pF} @ 48 \mathrm{MHz}$ | - | 1700 | - |
|  |  |  | $\mathrm{V}_{\mathrm{DD}}=3 \mathrm{~V}, \mathrm{Rm}=30 \Omega, \mathrm{C}_{\mathrm{L}}=20 \mathrm{pF} @ 48 \mathrm{MHz}$ | - | 2700 | - |Table 80. HSE oscillator characteristics ${ }^{(1)}$ (continued)

| Symbol | Parameter | Conditions ${ }^{(2)}$ |  | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{I}_{\text {DD(HSE) }}$ | HSE current consumption | Other revisions | During startup ${ }^{(3)}$ | - | - | 8 | mA |
|  |  |  | $\mathrm{V}_{\mathrm{DD}}=3 \mathrm{~V}, \mathrm{Rm}=30 \Omega, \mathrm{C}_{\mathrm{L}}=10 \mathrm{pF} @ 4 \mathrm{MHz}$ | - | 790 | - | $\mu \mathrm{A}$ |
|  |  |  | $\mathrm{V}_{\mathrm{DD}}=3 \mathrm{~V}, \mathrm{Rm}=30 \Omega, \mathrm{C}_{\mathrm{L}}=10 \mathrm{pF} @ 8 \mathrm{MHz}$ | - | 910 | - |  |
|  |  |  | $\mathrm{V}_{\mathrm{DD}}=3 \mathrm{~V}, \mathrm{Rm}=45 \Omega, \mathrm{C}_{\mathrm{L}}=10 \mathrm{pF} @ 8 \mathrm{MHz}$ | - | 930 | - |  |
|  |  |  | $\mathrm{V}_{\mathrm{DD}}=3 \mathrm{~V}, \mathrm{Rm}=30 \Omega, \mathrm{C}_{\mathrm{L}}=5 \mathrm{pF} @ 48 \mathrm{MHz}$ | - | 1430 | - |  |
|  |  |  | $\mathrm{V}_{\mathrm{DD}}=3 \mathrm{~V}, \mathrm{Rm}=30 \Omega, \mathrm{C}_{\mathrm{L}}=10 \mathrm{pF} @ 48 \mathrm{MHz}$ | - | 1960 | - |  |
|  |  |  | $\mathrm{V}_{\mathrm{DD}}=3 \mathrm{~V}, \mathrm{Rm}=30 \Omega, \mathrm{C}_{\mathrm{L}}=20 \mathrm{pF} @ 48 \mathrm{MHz}$ | - | 3000 | - |  |
| $\mathrm{Gm}_{\text {critmax }}$ | Maximum critical crystal transconductance $\mathrm{G}_{\mathrm{m}}$ | Startup |  | - | - | 1.5 | $\mathrm{mA} / \mathrm{V}$ |
| $\mathrm{t}_{\mathrm{SU}(\mathrm{HSE})}$ <br> (4) | Startup time | $\mathrm{V}_{\mathrm{DD}}$ stabilized |  | - | 2 | - | ms |

1. Specified by design. Not tested in production.
2. Resonator characteristics given by the crystal/ceramic resonator manufacturer.
3. This consumption level occurs during the first $2 / 3$ of the $\mathrm{t}_{\mathrm{SU}(\mathrm{HSE})}$ startup time.
4. $\mathrm{t}_{\mathrm{SU}(\mathrm{HSE})}$ is the startup time measured from the moment it is enabled (by software) to a stabilized 8 MHz oscillation is reached. This value is measured for a standard crystal resonator and it can vary significantly with the crystal manufacturer.

Note: $\quad$ For information on selecting the crystal, refer to the application note 'Oscillator design guide for STM8AF/AL/S, STM32 MCUs and MPUs' (AN2867).

Figure 32. Typical application with a 8 MHz crystal
![img-51.jpeg](img-51.jpeg)

1. $R_{E X T}$ value depends on the crystal characteristics.

# Low-speed external clock generated from a crystal resonator 

The low-speed external (LSE) clock can be supplied with a 32.768 kHz crystal resonator oscillator. All the information given in this paragraph are based on design simulation results obtained with typical external components specified in the table below. In the application, the resonator and the load capacitors have to be placed as close as possible to theoscillator pins in order to minimize output distortion and startup stabilization time. Refer to the crystal resonator manufacturer for more details on the resonator characteristics (frequency, package, accuracy).

Table 81. LSE oscillator characteristics $\left(f_{\text {LSE }}=32.768 \mathrm{kHz}\right)^{(1)}$

| Symbol | Parameter | Conditions ${ }^{(2)}$ |  | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{\text {DD(LSE) }}$ | LSE current consumption | Rev. $X$ | LSEDRV[1:0] $=01$, medium low-drive capability | - | 350 | - | nA |
|  |  |  | LSEDRV[1:0] $=10$, medium high-drive capability | - | 450 | - |  |
|  |  |  | LSEDRV[1:0] $=11$, high-drive capability | - | 600 | - |  |
|  |  | Other revisions | LSEDRV[1:0] $=00$, low-drive capability | - | 410 | - |  |
|  |  |  | LSEDRV[1:0] $=01$, medium low-drive capability |  | 450 |  |  |
|  |  |  | LSEDRV[1:0] $=10$, medium high-drive capability | - | 590 | - |  |
|  |  |  | LSEDRV[1:0] $=11$, high-drive capability | - | 700 | - |  |
| $\mathrm{Gm}_{\text {critmax }}$ | Maximum critical crystal Gm | LSEDRV[1:0] $=00$, low-drive capability |  | - | - | 0.5 | $\mu \mathrm{AV}$ |
|  |  | LSEDRV[1:0] $=01$, medium low-drive capability |  | - | - | 0.75 |  |
|  |  | LSEDRV[1:0] $=10$, medium high-drive capability |  | - | - | 1.7 |  |
|  |  | LSEDRV[1:0] $=11$, high-drive capability |  | - | - | 2.7 |  |
| $\mathrm{C}_{\text {S_PARA }}$ | Internal stray parasitic capacitance ${ }^{(3)}$ | Rev. $X$ | - |  | 5 | - | pF |
|  |  | Other revisions | - | - | 3 | - |  |
| $t_{\text {SU(LSE }}{ }^{(4)}$ | Startup time | $\mathrm{V}_{\mathrm{DD}}$ is stabilized |  | - | 2 | - | s |

1. Specified by design. Not tested in production.
2. Refer to the note below this table.
3. $\mathrm{C}_{\mathrm{S} \text { PARA }}$ is the equivalent capacitance seen by the crystal due to OSC32_IN and OSC32_OUT internal parasitic capacitances.
4. $\mathrm{t}_{\text {SU(LSE) }}$ is the startup time measured from the moment it is enabled (by software) to a stabilized 32.768 kHz oscillation is reached. This value is measured for a standard crystal and it can vary significantly with the crystal manufacturer

Note: $\quad$ For information on selecting the crystal, refer to the application note 'Oscillator design guide for STM8AF/AL/S, STM32 MCUs and MPUs' (AN2867).

Figure 33. Typical application with a 32.768 kHz crystal
![img-52.jpeg](img-52.jpeg)

Note: An external resistor is not required between OSC32_IN and OSC32_OUT and it is forbidden to add one.# 5.3.9 Internal clock timing characteristics 

The parameters given in the table below are derived from tests performed under ambient temperature and supply voltage conditions summarized in Table 33. The provided curves are characterization results, not tested in production.

High-speed internal (HSI16) RC oscillator
Table 82. HSI16 oscillator characteristics

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $f_{\text {HSI16 }}$ | HSI16 frequency after factory calibration | $\mathrm{V}_{\mathrm{DD}}=3.0 \mathrm{~V}, \mathrm{~T}_{\mathrm{J}}=30^{\circ} \mathrm{C}$ | 15.92 | 16 | 16.08 | MHz |
| $f_{\text {HSI16 }}{ }^{(1)}$ |  | $\begin{aligned} & \mathrm{T}_{\mathrm{J}}=-10^{\circ} \mathrm{C} \text { to } 100^{\circ} \mathrm{C} \\ & 1.58 \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V} \end{aligned}$ | 15.84 | - | 16.16 |  |
|  |  | $\begin{aligned} & \mathrm{T}_{\mathrm{J}}=-40^{\circ} \mathrm{C} \text { to } 130^{\circ} \mathrm{C} \\ & 1.58 \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V} \end{aligned}$ | 15.65 | - | 16.25 |  |
| TRIM $_{\text {HSI16 }}{ }^{(2)}$ | HSI16 user trimming step | - | 18 | 29 | 40 | kHz |
| $\operatorname{DuCy}_{\text {HSI16 }}{ }^{(2)}$ | Duty cycle | - | 45 | - | 55 | \% |
| $t_{\text {su(HSI16) }}{ }^{(2)}$ | HSI16 oscillator startup time | - | - | 2.5 | 3.6 | $\mu \mathrm{s}$ |
| $t_{\text {stab(HSI16) }}{ }^{(2)}$ | HSI16 oscillator stabilization time | At 1\% of target frequency | - | 4 | 6 |  |
| $I_{D D(H S I 16)^{(2)}}$ | HSI16 oscillator power consumption | - | - | 150 | 210 | $\mu \mathrm{A}$ |

1. Evaluated by characterization. Not tested in production. It does not take into account package and soldering effects.
2. Specified by design. Not tested in production.

Figure 34. HSI16 frequency versus temperature and $\mathrm{V}_{\mathrm{DD}}$
![img-53.jpeg](img-53.jpeg)# Multi-speed internal (MSI) RC oscillator 

Table 83. MSI oscillator characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions |  | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  |  | $\mathrm{V}_{\mathrm{DD}}=3 \mathrm{~V}$ <br> $\mathrm{T}_{\mathrm{J}}=30^{\circ} \mathrm{C}$ | MSI mode | MSI range 0 <br> (MSIRC0) | 47.74 | 48 | 48.70 | MHz |
|  |  |  |  | MSI range 1 | 23.87 | 24 | 24.35 |
|  |  |  |  | MSI range 2 | 15.91 | 16 | 16.23 |
|  |  |  |  | MSI range 3 | 11.93 | 12 | 12.17 |
|  |  |  |  | MSI range 4 <br> (MSIRC1) | 3.98 | 4 | 4.06 |
|  |  |  |  | MSI range 5 | 1.99 | 2 | 2.03 |
|  |  |  |  | MSI range 6 | 1.33 | 1.33 | 1.35 |
|  |  |  |  | MSI range 7 | 0.99 | 1 | 1.01 |
|  |  |  |  | MSI range 8 <br> (MSIRC2) | 3.05 | 3.08 | 3.12 |
|  |  |  |  | MSI range 9 | 1.53 | 1.54 | 1.56 |
|  |  |  |  | MSI range 10 | 1.02 | 1.03 | 1.04 |
|  |  |  |  | MSI range 11 | 0.76 | 0.77 | 0.78 |
|  |  |  |  | MSI range 12 <br> (MSIRC3) | 397.68 | 400 | 405.71 | kHz |
| $\mathrm{f}_{\text {MSI }}$ | MSI frequency <br> after factory <br> calibration |  |  | MSI range 13 | 198.84 | 200 | 202.86 |
|  |  |  |  | MSI range 14 | 132.56 | 133 | 135.24 |
|  |  |  |  | MSI range 15 | 99.42 | 100 | 101.43 |
|  |  |  | $\begin{aligned} & \text { PLL } \\ & \text { mode }^{(2)} \\ & \text { XTAL = } \\ & 32.768 \mathrm{kHz} \end{aligned}$ | MSI range 0 <br> (MSIRC0) | - | 48.005 | - | MHz |
|  |  |  |  | MSI range 1 | - | 24.003 | - |
|  |  |  |  | MSI range 2 | - | 16.002 | - |
|  |  |  |  | MSI range 3 | - | 12.001 | - |
|  |  |  |  | MSI range 4 <br> (MSIRC1) | - | 3.998 | - |
|  |  |  |  | MSI range 5 | - | 1.999 | - |
|  |  |  |  | MSI range 6 | - | 1.333 | - |
|  |  |  |  | MSI range 7 | - | 0.999 | - |
|  |  |  |  | MSI range 8 <br> (MSIRC2) | - | 3.08 | - |
|  |  |  |  | MSI range 9 | - | 1.54 | - |
|  |  |  |  | MSI range 10 | - | 1.027 | - |
|  |  |  |  | MSI range 11 | - | 0.77 | - |Table 83. MSI oscillator characteristics ${ }^{(1)}$ (continued)

| Symbol | Parameter | Conditions |  |  | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\begin{aligned} & t_{\text {MSI (cont'd) }} \end{aligned}$ | MSI frequency after factory calibration | $\begin{aligned} & \mathrm{V}_{\mathrm{DD}}=3 \mathrm{~V} \\ & \mathrm{~T}_{\mathrm{J}}=30^{\circ} \mathrm{C} \end{aligned}$ | PLL mode <br> XTAL $=$ <br> 32.768 kHz | MSI range 12 <br> (MSIRC3) | - | 393 | - | kHz |
|  |  |  |  | MSI range 13 | - | 196.6 | - |
|  |  |  |  | MSI range 14 | - | 131 | - |
|  |  |  |  | MSI range 15 | - | 98.3 | - |
| $\mathrm{DuCy}_{\text {MSI }}{ }^{(3)}$ | Duty cycle | MSI range 0, 4, 8, or 12 |  |  | 38 | - | 62 | \% |
|  |  | MSI range 2, 6, 10, or 14 |  |  | 31 | - | 69 |  |
|  |  | Other MSI ranges |  |  | 48 | - | 52 |  |
| TRIM $_{\text {MSI }}$ | User trimming step | - |  |  | - | 0.4 | - |  |
| $\Delta_{\text {TEMP(MSI) }}{ }^{(4)}$ | MSI oscillator frequency drift over temperature (reference is $30^{\circ} \mathrm{C}$ ) | MSI mode | $T_{J}=-40$ to $130^{\circ} \mathrm{C}$ |  | $-4$ | - | 2 |  |
| $\Delta_{\text {VDD(MSI) }}{ }^{(4)}$ | MSI oscillator frequency drift over $\mathrm{V}_{\mathrm{DD}}$ (reference is 3 V ) | MSI mode | MSI range <br> 0 to 3 | $1.58 \leq V_{D D} \leq 3.6 \mathrm{~V}$ | $-4$ | - | 1 | \% |
|  |  |  |  | $2.4 \leq V_{D D} \leq 3.6 \mathrm{~V}$ | $-1$ | - | 1 |
|  |  |  | MSI range <br> 4 to 7 | $1.58 \leq V_{D D} \leq 3.6 \mathrm{~V}$ | $-3$ | - | 1 |
|  |  |  |  | $2.4 \leq V_{D D} \leq 3.6 \mathrm{~V}$ | $-1$ | - | 1 |
|  |  |  | MSI range <br> 8 to 11 | $1.58 \leq V_{D D} \leq 3.6 \mathrm{~V}$ | $-3$ | - | 1 |
|  |  |  |  | $2.4 \leq V_{D D} \leq 3.6 \mathrm{~V}$ | $-1$ | - | 1 |
|  |  |  | MSI range <br> 12 to 15 | $1.58 \leq V_{D D} \leq 3.6 \mathrm{~V}$ | $-3$ | - | 1 |  |
|  |  |  |  | $2.4 \leq V_{D D} \leq 3.6 \mathrm{~V}$ | $-1$ | - | 1 |  |
| $\begin{gathered} \Delta_{\text {FSAMPLING }} \\ \text { (MSI) } \end{gathered}$ | MSI frequency variation in sampling mode (MSIBIAS $=1$ ) | MSI mode | $T_{J}=-40$ to $130^{\circ} \mathrm{C}$ |  | - | - | 0.2 |  |
| $\begin{gathered} \text { CC } \\ \text { jitter(MSI) }^{(3)} \end{gathered}$ | RMS <br> cycle-to-cycle jitter | PLL mode | MSI range 0 |  | - | 60 | - | ps |
|  |  |  | MSI range 4 |  | - | 160 | - |
|  |  |  | MSI range 8 |  | - | 200 | - |
|  |  |  | MSI range 12 |  | - | 1100 | - |
| P jitter(MSI) ${ }^{(3)}$ | RMS period jitter | PLL mode | MSI range 0 |  | - | 40 | - |  |
|  |  |  | MSI range 4 |  | - | 130 | - |
|  |  |  | MSI range 8 |  | - | 170 | - |
|  |  |  | MSI range 12 |  | - | 800 | - |Table 83. MSI oscillator characteristics ${ }^{(1)}$ (continued)

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{t}_{\text {su( }(\mathrm{MSI})^{(3)}}$ | MSI oscillator startup time ${ }^{(5)}$ | MSI range 0 to 3 | - | - | 13 <br> MSIRC0 cycles + <br> 11 MSI cycles |  |
|  |  | MSI range 4 to 7 | - | - | 4 <br> MSIRC1 <br> cycles + <br> 11 MSI <br> cycles |  |
|  |  | MSI range 8 to 11 | - | - | 4 <br> MSIRC2 <br> cycles + <br> 11 MSI <br> cycles |  |
|  |  | MSI range 12 to 15 | - | - | 4 <br> MSIRC3 <br> cycles + <br> 11 MSI <br> cycles |  |
| $\mathrm{t}_{\text {switch( }(\mathrm{MSI})^{(3)}}$ | MSI oscillator transition time ${ }^{(6)}$ | - | - | - | 3 <br> destination MSI cycles |  |
| $\mathrm{t}_{\text {stab( }(\mathrm{MSI})^{(3)}}$ | MSI oscillator stabilization time | Normal mode | Continuous mode ${ }^{(7)}$ | Final frequency | - | - | 10 | $\mu \mathrm{s}$ |
|  |  |  | Sampling mode ${ }^{(8)}$ |  | - | - | 200 |  |
|  |  | PLL mode, MSIPLL FAST $=0$ | All MSI ranges | $1 \%$ of final frequency | - | - | 0.8 | ms |
|  |  | PLL mode, MSIPLL FAST $=1$ | All MSI ranges |  | 2 |  |  | $\frac{\text { ㅇ }}{\text { ㅇ }}$ |
| $\mathrm{t}_{\text {DD( }(\mathrm{MSI} \text { OEF }}$ <br> _PLLFAST) ${ }^{(3)}$ | MSI PLL-mode oscillator power consumption when MSI is disabled with PLL accuracy retention | MSIPLL <br> EN $=1$ and <br> MSIPLL <br> FAST $=1$ | LDO | MSI range 0 to 3 | - | 6.6 | - | $\mu \mathrm{A}$ |
|  |  |  |  | MSI range 4 to 7 | - | 1.6 | - |
|  |  |  |  | MSI range 8 to 11 | - | 1.4 | - |
|  |  |  |  | MSI range 12 to 15 | - | 0.8 | - |
|  |  |  | SMPS | MSI range 0 to 3 | - | 4.7 | - |
|  |  |  |  | MSI range 4 to 7 | - | 1.4 | - |
|  |  |  |  | MSI range 8 to 11 | - | 1.3 | - |
|  |  |  |  | MSI range 12 to 15 | - | 0.8 | - |Table 83. MSI oscillator characteristics ${ }^{(1)}$ (continued)

| Symbol | Parameter | Conditions |  |  | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{I}_{\mathrm{DD}(\mathrm{MSI})}{ }^{(3)}$ | MSI oscillator power consumption | Continuous mode ${ }^{(7)}$ | LDO | MSI range 0 to 3 | - | $\begin{aligned} & 21+2.5 \\ & \mu \mathrm{~A} / \mathrm{MHz} \end{aligned}$ | - | $\mu \mathrm{A}$ |
|  |  |  |  | MSI range 4 to 15 | - | $\begin{aligned} & 19+2.5 \\ & \mu \mathrm{~A} / \mathrm{MHz} \end{aligned}$ | - |  |
|  |  |  | SMPS ${ }^{(9)}$ | MSI range 0 to 3 | - | $\begin{aligned} & 21+1,3 \\ & \mu \mathrm{~A} / \mathrm{MHz} \end{aligned}$ | - |  |
|  |  |  |  | MSI range 4 to 15 | - | $\begin{aligned} & 19+1,3 \\ & \mu \mathrm{~A} / \mathrm{MHz} \end{aligned}$ | - |  |
|  |  | Sampling mode ${ }^{(8)}$ | LDO | Range 0 to 3 | - | $\begin{aligned} & 3+2.5 \\ & \mu \mathrm{~A} / \mathrm{MHz} \end{aligned}$ | - |  |
|  |  |  |  | Range 4 to 15 | - | $\begin{gathered} 1+ \\ 2.5 \mu \mathrm{~A} / \\ \mathrm{MHz} \end{gathered}$ | - |  |
|  |  |  | SMPS | Range 0 to 3 | - | $\begin{aligned} & 3+1 \\ & \mu \mathrm{~A} / \mathrm{MHz} \end{aligned}$ | - |  |
|  |  |  |  | Range 4 to 15 | - | $\begin{gathered} 1+1 \\ \mu \mathrm{~A} / \mathrm{MHz} \end{gathered}$ | - |  |

1. Evaluated by characterization and not tested in production, unless otherwise specified.
2. In PLL mode, the MSI accuracy is the LSE crystal accuracy.
3. Specified by design. Not tested in production.
4. This is a deviation for an individual part once the initial frequency has been measured.
5. The MSI startup time is the time when the four MSIRCs are in power down.
6. This delay is the time to switch from one MSIRC to another one. In case the destination MSIRC is in power down, the total delay is $t_{\text {tost(MSI) }} \cdot t_{\text {twelst(MSI) }}$
7. The MSI is in continuous mode when the internal regulator is in voltage range 1,2 or 3 .
8. The MSI is in sampling mode when MSIBIAS $=1$ in RCC_ICSCR1, and the regulator is in voltage range 4 , or when the device is in Stop 1 or Stop 2 mode.
9. SMPS efficiency in range 1, based on $\mathrm{V}_{\text {CORE }}$ current $=19.4 \mathrm{~mA}$.

# High-speed internal 48 MHz (HSI48) RC oscillator 

Table 84. HSI48 oscillator characteristics

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{f}_{\text {HSI48 }}$ | HSI48 frequency after factory calibration | $\mathrm{V}_{\mathrm{DD}}=3.0 \mathrm{~V}, \mathrm{~T}_{\mathrm{J}}=30^{\circ} \mathrm{C}$ | 47.5 | 48 | 48.5 | MHz |Table 84. HSI48 oscillator characteristics (continued)

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| TRIM $_{\text {HSI48 }}{ }^{(1)}$ | User trimming step | - | - | 0.12 | 0.18 | \% |
| USER TRIM <br> COVERAGE ${ }^{(2)}$ | User trimming coverage | $\pm 63$ steps | $\pm 4.5$ | $\pm 7.56$ | - |  |
| $\mathrm{DuCy}_{\text {HSI48 }}{ }^{(1)}$ | Duty cycle | - | 45 | - | 55 |  |
| $\begin{gathered} \mathrm{ACC}_{\text {HSI48_REL }} \\ (2) \end{gathered}$ | Accuracy of the HSI48 oscillator over temperature (factory calibrated) Reference is 3 V and $30^{\circ} \mathrm{C}^{(3)}$. | $\begin{aligned} & 1.58 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}, \\ & \mathrm{~T}_{\mathrm{J}}=-40 \text { to } 125^{\circ} \mathrm{C} \end{aligned}$ | $-3$ | - | 2 |  |
| $\Delta_{\text {VDD(HSI48) }}{ }^{(1)}$ | HSI48 frequency drift with $\mathrm{V}_{\mathrm{DD}}{ }^{(4)}$ | $3.0 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | - | 0.025 | 0.05 |  |
|  |  | $1.58 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | - | 0.05 | 0.1 |  |
| $\mathrm{N}_{\mathrm{T}}$ jitter $^{(1)}$ | Next transition jitter Accumulated jitter on 28 cycles $^{(5)}$ | - | - | $\pm 0.15$ | - | ns |
| $P_{T}$ jitter $^{(1)}$ | Paired transition jitter Accumulated jitter on 56 cycles $^{(5)}$ | - | - | $\pm 0.25$ | - |  |
| $I_{\text {su(HSI48) }}{ }^{(1)}$ | HSI48 oscillator startup time | - | - | 2.5 | 6 | $\mu \mathrm{s}$ |
| $I_{D D(H S I 48)^{(1)}}$ | HSI48 oscillator power consumption | - | - | 350 | 400 | $\mu \mathrm{A}$ |

1. Specified by design. Not tested in production.
2. Evaluated by characterization. Not tested in production.
3. $\Delta \mathrm{f}_{\mathrm{HSI}}=\mathrm{ACC}_{\text {HSI48_REL }}+\Delta \mathrm{V}_{\mathrm{DD}}$.
4. These values are obtained with one of the following formula: (Freq(3.6 V) - Freq(3.0 V)) / Freq(3.0 V) or (Freq(3.6 V) - Freq(1.58 V)) / Freq(1.58 V).
5. Jitter measurements are performed without clock source activated in parallel.

Figure 35. HSI48 frequency versus temperature
![img-54.jpeg](img-54.jpeg)# Secure high-speed internal (SHSI) RC oscillator 

Table 85. SHSI oscillator characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $f_{\text {SHSI }}$ | SHSI frequency | - | - | 48 | - | MHz |
| $\mathrm{t}_{\mathrm{SU}(\mathrm{SHSI})}$ | SHSI oscillator startup time | - | - | 2.5 | 6 | $\mu \mathrm{s}$ |
| $\mathrm{I}_{\mathrm{DD}(\mathrm{SHSI})}$ | SHSI oscillator power consumption | - | - | 350 | 400 | $\mu \mathrm{A}$ |

1. Specified by design. Not tested in production.

## Low-speed internal (LSI) RC oscillator

Table 86. LSI oscillator characteristics

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $f_{\text {LSI }}$ | LSI frequency | $\begin{aligned} & \mathrm{V}_{\mathrm{DD}}=3.0 \mathrm{~V}, \mathrm{~T}_{\mathrm{J}}=30^{\circ} \mathrm{C}, \text { LSIPREDIV }=0 \\ & \mathrm{~V}_{\mathrm{DD}}=3.0 \mathrm{~V}, \mathrm{~T}_{\mathrm{J}}=30^{\circ} \mathrm{C}, \text { LSIPREDIV }=1 \\ & 1.58 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}, \mathrm{~T}_{\mathrm{J}}=-40 \text { to } 125^{\circ} \mathrm{C} \end{aligned}$ | $\begin{aligned} & 31.4 \\ & 0.245 \\ & 30.4^{(1)} \end{aligned}$ | - | $\begin{aligned} & 32.6 \\ & 0.255 \\ & 33.6^{(1)} \end{aligned}$ | kHz |
| $\mathrm{DuCy}_{\text {LSI }}$ | LSI duty cycle | LSIPREDIV $=1$ | - | 50 | - | \% |
| $\mathrm{t}_{\mathrm{SU}(\mathrm{LSI})}{ }^{(2)}$ | LSI oscillator startup time | - | - | 230 | 260 | $\mu \mathrm{s}$ |
| $\mathrm{t}_{\text {STAB(LSI) }}{ }^{(2)}$ | LSI oscillator stabilization time | 5\% of final frequency | - | 230 | 260 |  |
| $\mathrm{I}_{\mathrm{DD}(\mathrm{LSI})^{(2)}}$ | LSI oscillator power consumption | LSIPREDIV $=0$ | - | 140 | 255 | nA |
|  |  | LSIPREDIV $=1$ | - | 130 | 240 |  |

1. Evaluated by characterization. Not tested in production.
2. Specified by design. Not tested in production.

### 5.3.10 PLL characteristics

The parameters given in the table below are derived from tests performed under temperature and $\mathrm{V}_{\mathrm{DD}}$ supply voltage conditions summarized in Table 33.

Table 87. PLL characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $f_{\text {PLL_IN }}$ | PLL input clock | - | 4 | - | 16 | MHz |
|  | PLL input clock duty cycle | - | 10 | - | 90 | \% |
| $f_{\text {PLL_OUT }}$ | PLL P, Q, R output clock | Voltage scaling range 1 | 1 | - | $160^{(2)}$ | MHz |
|  |  | Voltage scaling range 2 | 1 | - | 110 |  |
|  |  | Voltage scaling range 3 | 1 | - | 55 |  |
| $f_{\text {VCO_OUT }}$ | PLL VCO output | Voltage scaling range 1, 2 | 128 | - | 544 |  |
|  |  | Voltage scaling range 3 | 128 | - | 330 |  |
|  |  | Duty cycle with division 1 | 40 | - | 60 | \% |Table 87. PLL characteristics ${ }^{(1)}$ (continued)

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{I}_{\text {LOCK }}{ }^{(3)(4)}$ | PLL lock time | Integer mode | - | 25 | 50 | $\mu \mathrm{s}$ |
|  |  | Fractional mode | - | 40 | 65 |  |
| Jitter | RMS cycle-tocycle jitter | Integer mode, $\mathrm{VCO}=544 \mathrm{MHz}$ | - | 20 | - | $\pm \mathrm{ps}$ |
|  |  | Fractional mode, $\mathrm{VCO}=544 \mathrm{MHz}$ | - | 70 | - |  |
|  | RMS period jitter | Integer mode, $\mathrm{VCO}=544 \mathrm{MHz}$ | - | 35 | - |  |
|  |  | Fractional mode, $\mathrm{VCO}=544 \mathrm{MHz}$ | - | 45 | - |  |
|  | Long-term jitter ${ }^{(5)}$, $\mathrm{f}_{\text {PLL_IN }}=8 \mathrm{MHz}$ | Integer mode, $\mathrm{VCO}=544 \mathrm{MHz}$ | - | 160 | - |  |
|  |  | Fractional mode, $\mathrm{VCO}=544 \mathrm{MHz}$ | - | 170 | - |  |
| $\mathrm{I}_{\text {DD(PLL) }}$ | PLL power consumption on $\mathrm{V}_{\mathrm{DD}}$ with LDO | VCO freq $=160 \mathrm{MHz}$, 1 clock output | Range 1 | - | 370 | - | $\mu \mathrm{A}$ |
|  |  | VCO freq $=160 \mathrm{MHz}$, 3 clock outputs | Range 1 | - | 390 | - |
|  |  | VCO freq $=200 \mathrm{MHz}$, 1 clock output | Range 1 | - | 460 | - |
|  |  |  | Range 2 | - | 435 | - |
|  |  |  | Range 3 | - | 410 | - |
|  |  | VCO freq $=336 \mathrm{MHz}$, 1 clock output | Range 1 | - | 710 | - |
|  |  | VCO freq $=544 \mathrm{MHz}$, 1 clock output | Range 1 | - | 1100 | - |
| $\mathrm{I}_{\text {DD(PLL) }}$ | PLL power consumption on $\mathrm{V}_{\mathrm{DD}}$ with SMPS | VCO freq $=160 \mathrm{MHz}$, 1 clock output | Range 1, $\mathrm{I}_{\text {VCORE }}{ }^{(6)}=19.4 \mathrm{~mA}$ | - | 260 | - |
|  |  | VCO freq $=160 \mathrm{MHz}$, 3 clock outputs | Range 1, $\mathrm{I}_{\text {VCORE }}{ }^{(6)}=19.4 \mathrm{~mA}$ | - | 270 | - |
|  |  | VCO freq $=200 \mathrm{MHz}$, 1 clock output | Range 1, $\mathrm{I}_{\text {VCORE }}{ }^{(6)}=19.4 \mathrm{~mA}$ | - | 320 | - |
|  |  |  | Range 2, $\mathrm{I}_{\text {VCORE }}{ }^{(6)}=11.7 \mathrm{~mA}$ | - | 300 | - |
|  |  |  | Range 3, $\mathrm{I}_{\text {VCORE }}{ }^{(6)}=5.74 \mathrm{~mA}$ | - | 290 | - |
|  |  | VCO freq $=336 \mathrm{MHz}$, 1 clock output | Range 1, $\mathrm{I}_{\text {VCORE }}{ }^{(6)}=19.4 \mathrm{~mA}$ | - | 470 | - |
|  |  | VCO freq $=544 \mathrm{MHz}$, 1 clock output | Range 1, $\mathrm{I}_{\text {VCORE }}{ }^{(6)}=19.4 \mathrm{~mA}$ | - | 730 | - |

1. Specified by design and not tested in production, unless otherwise specified.
2. PLL1 output $Q$ and PLL2 output $Q$ can be up to 200 MHz only when selected as OCTOSPI clock.
3. Evaluated by characterization. Not tested in production.
4. Lock time is the duration until PLLxRDY flag ( $2 \%$ of final frequency).
5. Measured on 5000 cycles.
6. SMPS efficiency based on CoreMark RUN current on $\mathrm{V}_{\text {CORE }}$ at max frequency of each voltage range.# 5.3.11 Flash memory characteristics 

Table 88. Flash memory characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions | Typ | Max ${ }^{(2)}$ | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{\text {prog }}$ | 128-bit programming time | Normal mode | 118 | 118 | $\mu \mathrm{s}$ |
|  |  | Burst mode | 48 | 48 |  |
| $t_{\text {prog_page }}$ | One 8-Kbyte page programming time | $f_{\text {AHB }}=160 \mathrm{MHz}$, normal mode | 60.2 | - | ms |
|  |  | $f_{\text {AHB }}=160 \mathrm{MHz}$, burst mode | 24.5 | - |  |
| $t_{\text {prog_bank }}$ | One 1-Mbyte bank programming time | $f_{\text {AHB }}=160 \mathrm{MHz}$, normal mode | 7710 | - |  |
|  |  | $f_{\text {AHB }}=160 \mathrm{MHz}$, burst mode | 3140 | - |  |
| $t_{\text {ERASE }}$ | One 8-Kbyte page erase time | 10 k endurance cycles | 1.5 | 2.4 |  |
|  |  | 100 k endurance cycles | 1.7 | 3.4 |  |
| $t_{\text {ME }}$ | Mass erase time (one bank) | 10 k endurance cycles | 195 | 308 |  |
|  | Mass erase time (two banks) |  | 390 | 616 |  |
| $t_{\text {DD }}{ }^{(3)}$ | Average consumption from $\mathrm{V}_{\mathrm{DD}}$ | Write mode | 2.1 | - | mA |
|  |  | Erase mode | 1.3 | - |  |
|  | Maximum current (peak) | Write mode | 2.6 | - |  |
|  |  | Erase mode | 3.0 | - |  |

1. Specified by design. Not tested in production.
2. Evaluated by characterization after cycling. Not tested in production.
3. Evaluated by characterization. Not tested in production.

Table 89. Flash memory endurance and data retention

| Symbol | Parameter | Conditions |  | Min $^{(1)}$ | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{N}_{\text {END }}$ | Endurance | Whole bank | $T_{A}=-40$ to $125^{\circ} \mathrm{C}$ | 10 | kcycles |
|  |  | Limited to 256 Kbytes per bank |  | 100 |  |
| $t_{\text {RET }}$ | Data retention | Whole bank | $\mathrm{T}_{\mathrm{A}}=85^{\circ} \mathrm{C}$ after $1 \mathrm{kcycle}^{(2)}$ | 30 | Years |
|  |  |  | $\mathrm{T}_{\mathrm{A}}=105^{\circ} \mathrm{C}$ after $1 \mathrm{kcycle}^{(2)}$ | 15 |  |
|  |  |  | $\mathrm{T}_{\mathrm{A}}=125^{\circ} \mathrm{C}$ after $1 \mathrm{kcycle}^{(2)}$ | 10 |  |
|  |  |  | $\mathrm{T}_{\mathrm{A}}=55^{\circ} \mathrm{C}$ after $10 \mathrm{kcycles}^{(2)}$ | 30 |  |
|  |  |  | $\mathrm{T}_{\mathrm{A}}=85^{\circ} \mathrm{C}$ after $10 \mathrm{kcycles}^{(2)}$ | 15 |  |
|  |  |  | $\mathrm{T}_{\mathrm{A}}=105^{\circ} \mathrm{C}$ after $10 \mathrm{kcycles}^{(2)}$ | 10 |  |
|  |  | Limited to 256 Kbytes per bank | $\mathrm{T}_{\mathrm{A}}=55^{\circ} \mathrm{C}$ after $100 \mathrm{kcycles}^{(2)}$ | 30 |  |
|  |  |  | $\mathrm{T}_{\mathrm{A}}=85^{\circ} \mathrm{C}$ after $100 \mathrm{kcycles}^{(2)}$ | 15 |  |
|  |  |  | $\mathrm{T}_{\mathrm{A}}=105^{\circ} \mathrm{C}$ after $100 \mathrm{kcycles}^{(2)}$ | 10 |  |

1. Evaluated by characterization. Not tested in production.
2. Cycling performed over the whole temperature range.# 5.3.12 EMC characteristics 

Susceptibility tests are performed on a sample basis during device characterization.

## Functional EMS (electromagnetic susceptibility)

While a simple application is executed on the device (toggling two LEDs through the I/O ports), the device is stressed by two electromagnetic events until a failure occurs. The failure is indicated by the LEDs as follows:

- Electrostatic discharge (ESD) (positive and negative): applied to all device pins until a functional disturbance occurs. This test is compliant with the IEC 61000-4-2 standard.
- FTB (fast transient voltage burst) (positive and negative): applied to VDD and VSS pins through a 100 pF capacitor, until a functional disturbance occurs. This test is compliant with the IEC 61000-4-4 standard.

A device reset allows normal operations to be resumed.
The test results are given in the table below. They are based on the EMS levels and classes defined in application note EMC design guide for STM8, STM32 and Legacy MCUs (AN1709).

Table 90. EMS characteristics

| Symbol | Parameter | Conditions | Level/ <br> Class |
| :--: | :--: | :--: | :--: |
| $\mathrm{V}_{\text {FESD }}$ | Voltage limits to be applied on any I/O pin to induce a functional disturbance | $\mathrm{V}_{\mathrm{DD}}=3.3 \mathrm{~V}, \mathrm{~T}_{\mathrm{A}}=+25^{\circ} \mathrm{C}, \mathrm{f}_{\mathrm{HCLK}}=160 \mathrm{MHz}$, BGA169 conforming to IEC 61000-4-2 | 3B |
| $\mathrm{V}_{\text {EFTB }}$ | Fast transient voltage burst limits to be applied through 100 pF on $\mathrm{V}_{\mathrm{DD}}$ and $\mathrm{V}_{\mathrm{SS}}$ pins to induce a functional disturbance | $\mathrm{V}_{\mathrm{DD}}=3.3 \mathrm{~V}, \mathrm{~T}_{\mathrm{A}}=+25^{\circ} \mathrm{C}, \mathrm{f}_{\mathrm{HCLK}}=160 \mathrm{MHz}$, BGA169 conforming to IEC 61000-4-4 | 5 A |

## Designing hardened software to avoid noise problems

The EMC characterization and optimization are performed at component level with a typical application environment and simplified MCU software. Note that good EMC performance is highly dependent on the user application and the software in particular.
Therefore it is recommended that the user applies EMC software optimization and prequalification tests in relation with the EMC level requested for the application.

## Software recommendations

The software flowchart must include the management of runaway conditions such as:

- Corrupted program counter
- Unexpected reset
- Critical data corruption (control registers)


## Prequalification trials

Most of the common failures (unexpected reset and program counter corruption) can be reproduced by manually forcing a low state on the NRST pin or the oscillator pins for 1 second.

To complete these trials, ESD stress can be applied directly on the device, over the range of specification values. When unexpected behavior is detected, the software can be hardenedto prevent unrecoverable errors occurring. See application note Software techniques for improving microcontrollers EMC performance (AN1015) for more details.

# Electromagnetic Interference (EMI) 

The electromagnetic field emitted by the device is monitored while a simple application is executed (toggling two LEDs through the I/O ports). This emission test is compliant with IEC 61967-2 standard that specifies the test board and the pin loading.

Table 91. EMI characteristics for $f_{\text {HSE }}=8 \mathrm{MHz}$ and $f_{\text {HCLK }}=160 \mathrm{MHz}$

| Symbol | Parameter | Conditions | Monitored frequency band | Value | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: |
| $S_{\text {EMI }}$ | Peak ${ }^{(1)}$ | $\begin{gathered} V_{D D}=3.6 \mathrm{~V}, T_{A}=25^{\circ} \mathrm{C} \\ \text { BGA169 package compliant } \\ \text { with IEC 61967-2 } \end{gathered}$ | 0.1 MHz to 30 MHz | 5 | $\mathrm{dB} \mu \mathrm{V}$ |
|  |  |  | 30 MHz to 130 MHz | 6 |  |
|  |  |  | 130 MHz to 1 GHz | 6 |  |
|  |  |  | 1 GHz to 2 GHz | 7 |  |
|  | Level ${ }^{(2)}$ |  | 0.1 MHz to 2 GHz | 2 | - |

1. Refer to the EMI radiated test section of the application note EMC design guide for STM8, STM32 and Legacy MCUs (AN1709).
2. Refer to the EMI level classification section of the application note EMC design guide for STM8, STM32 and Legacy MCUs (AN1709).

### 5.3.13 Electrical sensitivity characteristics

Based on three different tests (ESD, latch-up) using specific measurement methods, the device is stressed in order to determine its performance in terms of electrical sensitivity.

## Electrostatic discharge (ESD)

Electrostatic discharges (a positive then a negative pulse separated by 1 second) are applied to the pins of each sample according to each pin combination. The sample size depends on the number of supply pins in the device ( 3 parts $\times(n+1)$ supply pins). This test conforms to the ANSI/JEDEC standard.

Table 92. ESD absolute maximum ratings ${ }^{(1)}$

| Symbol | Ratings | Conditions | Packages | Class | Max <br> value | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{V}_{\text {ESD(HBM) }}$ | Electrostatic discharge voltage (human body model) | $\mathrm{T}_{\mathrm{A}}=25^{\circ} \mathrm{C}$, conforming to ANSI/ESDA/JEDEC JS-001 | All | 2 | 2000 | V |
| $\mathrm{V}_{\text {ESD(CDM) }}$ | Electrostatic discharge voltage (charge device model) | $\mathrm{T}_{\mathrm{A}}=25^{\circ} \mathrm{C}$, conforming to ANSI/ESDA/JEDEC JS-002 | LQFP100 <br> LQFP144 | C1 | 250 |  |
|  |  |  | UFQFPN48 <br> LQFP48 <br> LQFP64 | C2a | 500 |  |
|  |  |  | WLCSP90 <br> UFBGA132 <br> UFBGA169 | C2b | 750 |  |

1. Evaluated by characterization. Not tested in production.# Static latch-up 

The following complementary static tests are required on three parts to assess the latch-up performance:

- A supply overvoltage is applied to each power supply pin.
- A current injection is applied to each input, output and configurable I/O pin.

These tests are compliant with EIA/JESD 78E IC latch-up standard.
Table 93. Electrical sensitivities ${ }^{(1)}$

| Symbol | Parameter | Conditions | Class |
| :--: | :-- | :-- | :--: |
| LU | Static latch-up class | $\mathrm{T}_{\mathrm{J}}=130^{\circ} \mathrm{C}$ conforming to JESD78E | 2 |

1. Evaluated by characterization. Not tested in production.

### 5.3.14 I/O current injection characteristics

As a general rule, the current injection to the I/O pins, due to external voltage below $\mathrm{V}_{\mathrm{SS}}$ or above $\mathrm{V}_{\text {DDIOx }}$ (for standard, 3.3 V -capable I/O pins) must be avoided during normal product operation. However, in order to give an indication of the robustness of the microcontroller if abnormal injection accidentally happens, some susceptibility tests are performed on a sample basis during the device characterization.

## Functional susceptibility to I/O current injection

While a simple application is executed on the device, the device is stressed by injecting current into the I/O pins programmed in floating-input mode. While this current is injected into the I/O pin, one at a time, the device is checked for functional failures.

The failure is indicated by an out-of-range parameter, such as an ADC error above a certain limit (higher than 5 LSB TUE), out of conventional limits of induced leakage current on adjacent pins (out of the $-5 \mu \mathrm{~A} /+0 \mu \mathrm{~A}$ range), or other functional failure (for example reset occurrence or oscillator frequency deviation).
The characterization results are given in the table below. The negative induced leakage current is caused by the negative injection. The positive induced leakage current is caused by the positive injection.

Table 94. I/O current injection susceptibility ${ }^{(1)(2)}$

| Symbol | Description | Functional susceptibility |  | Unit |
| :--: | :--: | :--: | :--: | :--: |
|  |  | Negative injection | Positive injection |  |
| $I_{I N J}$ | Injected current on OPAMP1_VINM, OPAMP2_VINM, PA4, PA5, PB0, PE7, PB15, PC11, and PD0 pins | 0 | 0 | mA |
|  | Injected current on all other pins | 5 | N/A |  |

1. Evaluated by characterization. Not tested in production.
2. The I/O structure options listed in this table can be a concatenation of options including the option explicitly listed. For instance TT_a refers to any TT I/O with _a option. TT_xx refers to any TT I/O and FT_xx refers to any FT I/O.# 5.3.15 I/O port characteristics 

## General input/output characteristics

Unless otherwise specified, the parameters given in the table below are derived from tests performed under the conditions summarized in Table 33. All I/Os are designed as CMOS- and TTL-compliant.

Note: $\quad$ For information on GPIO configuration, refer to the application note 'STM32 GPIO configuration for hardware settings and low-power consumption' (AN4899).

Table 95. I/O static characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{V}_{\mathrm{IL}}{ }^{(2)}$ | I/O input low-level voltage | $1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | - | $0.3 \mathrm{~V}_{\text {DDIOx }}$ | V |
|  |  | All I/Os except FT_c | - | - | $0.38 \mathrm{~V}_{\text {DDIOx }}{ }^{(3)}$ |  |
|  |  | FT_c I/Os | - | - | $0.3 \mathrm{~V}_{\text {DDIOx }}$ |  |
| $\begin{aligned} & V_{\text {IH }} \\ & \text { (2) } \end{aligned}$ | I/O input high-level voltage | $1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | $0.7 \mathrm{~V}_{\text {DDIOx }}$ | - | - |  |
|  |  | All I/Os except FT_c | $\begin{gathered} 0.5 \mathrm{~V}_{\text {DDIOx }} \\ +0.2^{(3)} \end{gathered}$ | - | - |  |
|  |  | FT_c I/Os | $0.7 \mathrm{~V}_{\text {DDIOx }}$ | - | - |  |
| $\begin{aligned} & \mathrm{V}_{\text {hys }} \\ & \text { (3) } \end{aligned}$ | Input hysteresis | TT_xx, FT_xx I/Os | - | 250 | - | mV |Table 95. I/O static characteristics ${ }^{(1)}$ (continued)

| Symbol | Parameter | Conditions |  | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\begin{aligned} & \mathrm{I}_{\mathrm{mg}} \\ & (3)(A) \end{aligned}$ | Input leakage current | All I/Os except FT_u, FT_c, FT_d, FT_o, FT_t, TT_xx | $\begin{aligned} & V_{\text {IN }} \leq \operatorname{Max}\left(V_{D D X X X}\right)^{(5)} \ & \operatorname{Max}\left(V_{D D X X X}\right)<V_{I N} \\ & \leq \operatorname{Max}\left(V_{D D X X X}\right)+1 V^{(6)} \end{aligned}$ | - | - | 150 | nA |
|  |  |  | $\begin{aligned} & \operatorname{Max}\left(V_{D D X X X}\right)+1 \vee<V_{I N} \\ & \leq 5.5 V^{(6)} \end{aligned}$ | - | - | 500 |
|  |  | FT_o I/Os <br> Rev. $X$ | $\begin{aligned} & V_{\text {IN }} \leq \operatorname{Max}\left(V_{D D X X X}\right)^{(5)} \end{aligned}$ | - | - | 150 |  |
|  |  |  | $\begin{aligned} & \operatorname{Max}\left(V_{D D X X X}\right)<V_{I N} \\ & \leq \operatorname{Max}\left(V_{D D X X X}\right)+1 V^{(6)} \end{aligned}$ | - | - | 2000 |  |
|  |  |  | $\begin{aligned} & \operatorname{Max}\left(V_{D D X X X}\right)+1 \vee<V_{I N} \\ & \leq 5.5 V^{(6)} \end{aligned}$ | - | - | 500 |  |
|  |  | FT_o I/Os <br> Other revisions | $\begin{aligned} & V_{\text {IN }} \leq \operatorname{Max}\left(V_{D D X X X}\right)^{(5)} \end{aligned}$ | - | - | 50 |  |
|  |  |  | $\begin{aligned} & \operatorname{Max}\left(V_{D D X X X}\right)<V_{I N} \\ & \leq \operatorname{Max}\left(V_{D D X X X}\right)+1 V^{(6)} \end{aligned}$ | - | - | 500 |  |
|  |  |  | $\begin{aligned} & \operatorname{Max}\left(V_{D D X X X}\right)+1 \vee<V_{I N} \\ & \leq 5.5 V^{(6)} \end{aligned}$ | - | - | 200 |  |
|  |  | FT_u I/Os | $\begin{aligned} & V_{\text {IN }} \leq \operatorname{Max}\left(V_{D D X X X}\right)^{(5)} \end{aligned}$ | - | - | 200 |  |
|  |  |  | $\begin{aligned} & \operatorname{Max}\left(V_{D D X X X}\right)<V_{I N} \\ & \leq \operatorname{Max}\left(V_{D D X X X}\right)+1 V^{(6)} \end{aligned}$ | - | - | 2500 |  |
|  |  |  | $\begin{aligned} & \operatorname{Max}\left(V_{D D X X X}\right)+1 \vee<V_{I N} \\ & \leq 5.5 V^{(6)} \end{aligned}$ | - | - | 500 |  |
|  |  | FT_c I/Os | $\begin{aligned} & V_{\text {IN }} \leq \operatorname{Max}\left(V_{D D X X X}\right) \\ & \operatorname{Max}\left(V_{D D X X X}\right)<V_{I N} \leq 5 V^{(6)} \end{aligned}$ | - | - | 1500 |  |
|  |  |  | $\begin{aligned} & \operatorname{Max}\left(V_{D D X X X}\right)<V_{I N} \leq 5 \vee^{(6)} \end{aligned}$ | - | - | 1500 |  |
|  |  |  | $\begin{aligned} & \operatorname{Max}\left(V_{D D X X X}\right)<V_{I N} \leq 5.5 V^{(6)} \end{aligned}$ | - | - | 5000 |  |
|  |  | FT_t I/Os | $\begin{aligned} & V_{\text {IN }} \leq \operatorname{Max}\left(V_{D D X X X}\right) \\ & \operatorname{Max}\left(V_{D D X X X}\right)<V_{I N} \\ & \leq \operatorname{Max}\left(V_{D D X X X}\right)+1 V^{(6)} \end{aligned}$ | - | - | 300 |  |
|  |  |  | $\begin{aligned} & \operatorname{Max}\left(V_{D D X X X}\right)+1 \vee<V_{I N} \\ & \leq 5.5 V^{(6)} \end{aligned}$ | - | - | 600 |  |Table 95. I/O static characteristics ${ }^{(1)}$ (continued)

| Symbol | Parameter | Conditions |  | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\begin{aligned} & \mathrm{I}_{\mathrm{kg}} \\ & (3)(4) \end{aligned}$ | Input leakage current | TT_xx I/Os except OPAMPx_VINM $(x=1,2)$ | $V_{I N} \leq \operatorname{Max}\left(V_{D D X X X}\right)$ | - | - | 500 | nA |
|  |  | OPAMPx_VINM $(x=1,2)$ dedicated input leakage current |  | - | - | (7) |  |
| $R_{P U}$ | Weak pull-up equivalent | - |  | 30 | 40 | 50 | k 1 |
| $R_{P D}$ | Weak pull-down equivalent | - |  | 30 | 40 | 50 |  |
| $\mathrm{C}_{\mathrm{IO}}$ | I/O pin capacitance | - |  | - | 5 | - | pF |

1. The I/O structure options listed in this table can be a concatenation of options including the option explicitly listed. For instance TT_a refers to any TT I/O with _a option. TT_xx refers to any TT I/O and FT_xx refers to any FT I/O.
2. Refer to Figure 36: I/O input characteristics (all I/Os except BOOT0 and FT_c).
3. Specified by design. Not tested in production.
4. This parameter represents the pad leakage of the I/O itself. The total product pad leakage is provided by the following formula: $\mathrm{I}_{\text {total_ileak_max }} \approx 10 \mu \mathrm{~A}+$ [number of I/Os where $V_{I N}$ is applied on the pad] $+I_{\text {Ikg }}$ max.
5. $\operatorname{Max}\left(V_{\text {DDXXX }}\right)$ is the maximum value of all the I/O supplies. The I/O supplies depend on the I/O structure options, as described in Table 26: Legend/abbreviations used in the pinout table.
6. To sustain a voltage higher than $\operatorname{Min}\left(V_{D D}, V_{D D A}, V_{D D U S B}, V_{D D I O 2}\right)+0.3 \mathrm{~V}$, the internal pull-up and pull-down resistors must be disabled.
7. Refer to $\mathrm{I}_{\text {bias }}$ in the OPAMP characteristics table for the values of the OPAMP dedicated input leakage current.
8. The pull-up and pull-down resistors are designed with a true resistance in series with a switchable PMOS/NMOS. This PMOS/NMOS contribution to the series resistance is minimal ( $\sim 10 \%$ order).All I/Os are CMOS- and TTL-compliant (no software configuration required). Their characteristics cover more than the strict CMOS-technology or TTL parameters. The coverage of these requirements is shown in the figure below.

Figure 36. I/O input characteristics (all I/Os except BOOT0 and FT_c)
![img-55.jpeg](img-55.jpeg)

# Output driving current 

The GPIOs (except PC13, PC14, PC15) can sink or source up to $\pm 8 \mathrm{~mA}$, and sink or source up to $\pm 20 \mathrm{~mA}$ (with a relaxed $\mathrm{V}_{\mathrm{OL}} / \mathrm{V}_{\mathrm{OH}}$ ). PC13, PC14, PC15 are limited in source capability: +3 mA shared between the three I/Os. These GPIOs have the same sink capability than other GPIOs.

In the user application, the number of I/O pins tat can drive current must be limited to respect the absolute maximum rating specified in Section 5.2: Absolute maximum ratings:

- The sum of the currents sourced by all the I/Os on $\mathrm{V}_{\text {DDIOx }}$, plus the maximum consumption of the MCU sourced on $\mathrm{V}_{\mathrm{DD}}$, cannot exceed the absolute maximum rating $\Sigma \mathrm{I}_{\mathrm{VDD}}$ (see Table 31: Current characteristics).
- The sum of the currents sunk by all the I/Os on $\mathrm{V}_{\mathrm{SS}}$, plus the maximum consumption of the MCU sunk on $\mathrm{V}_{\mathrm{SS}}$, cannot exceed the absolute maximum rating $\Sigma \mathrm{I}_{\mathrm{VSS}}$ (see Table 31: Current characteristics).# Output voltage levels 

Unless otherwise specified, the parameters given in the table below are derived from tests performed under the ambient temperature and supply voltage conditions summarized in Table 33. All I/Os are CMOS- and TTL-compliant (FT OR TT unless otherwise specified).

Table 96. Output voltage characteristics (all I/Os except FT_t I/Os in $\mathrm{V}_{\text {BAT }}$ mode, and $\mathrm{FT} \_\mathrm{o} \mathrm{I} / \mathrm{Os}^{(1)})^{(2)(3)}$

| Symbol | Parameter | Conditions | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{V}_{\mathrm{OL}}$ | Output low-level voltage | CMOS port ${ }^{(4)}, \mathrm{I}_{\mathrm{IO}}=8 \mathrm{~mA}$, $2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 0.4 | V |
| $\mathrm{V}_{\mathrm{OH}}$ | Output high-level voltage |  | $\mathrm{V}_{\text {DDIOx }}-0.4$ | - |  |
| $\mathrm{V}_{\mathrm{OL}}{ }^{(5)}$ | Output low-level voltage | TTL port ${ }^{(4)} \mid I_{\mathrm{IO}}=8 \mathrm{~mA}$, $2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 0.4 |  |
| $\mathrm{V}_{\mathrm{OH}}{ }^{(5)}$ | Output high-level voltage |  | 2.4 | - |  |
| $\mathrm{V}_{\mathrm{OL}}{ }^{(5)}$ | Output low-level voltage | All I/Os, $\left|I_{\mathrm{IO}}\right|=20 \mathrm{~mA}$, $2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 1.3 |  |
| $\mathrm{V}_{\mathrm{OH}}{ }^{(5)}$ | Output high-level voltage |  | $\mathrm{V}_{\text {DDIOx }}-1.3$ | - |  |
| $\mathrm{V}_{\mathrm{OL}}{ }^{(5)}$ | Output low-level voltage | $\left\|_{\mathrm{IO}}\right|=4 \mathrm{~mA}$, $1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 0.4 |  |
| $\mathrm{V}_{\mathrm{OH}}{ }^{(5)}$ | Output high-level voltage |  | $\mathrm{V}_{\text {DDIOx }}-0.4$ | - |  |
| $\mathrm{V}_{\mathrm{OL}}{ }^{(5)}$ | Output low-level voltage | $\left\|_{\mathrm{IO}}\right|=1 \mathrm{~mA}$, $1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<3.6 \mathrm{~V}$ | - | 0.4 |  |
| $\mathrm{V}_{\mathrm{OH}}{ }^{(5)}$ | Output high-level voltage |  | $\mathrm{V}_{\text {DDIOx }}-0.4$ | - |  |
| $\mathrm{V}_{\mathrm{OLFM}}{ }^{(5)}$ | Output low-level voltage for a FT_f I/O pin in FM+ mode | $\left\|_{\mathrm{IO}}\right|=20 \mathrm{~mA}$, $2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 0.4 |  |
|  |  | $\left\|_{\mathrm{IO}}\right|=10 \mathrm{~mA}$, $1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 0.4 |  |
|  |  | $\left\|_{\mathrm{IO}}\right|=2 \mathrm{~mA}$, $1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<3.6 \mathrm{~V}$ | - | 0.4 |  |

1. $\mathrm{FT} \_\mathrm{t} \mathrm{I} / \mathrm{O}$ characteristics are degraded only in $\mathrm{V}_{\mathrm{BAT}}$ mode (refer to Table 97). $\mathrm{FT} \_\mathrm{o} \mathrm{I} / \mathrm{O}$ characteristics are provided in this table for revision $X$ devices. FT_o I/O characteristics are provided in Table 97 for all other device revisions.
2. The I/O structure options listed in this table can be a concatenation of options including the option explicitly listed. For instance TT_a refers to any TT I/O with _x option. TT_xx refers to any TT I/O and FT_xx refers to any FT I/O.
3. The $I_{I O}$ current sourced or sunk by the device must always respect the absolute maximum rating specified in Table 31: Current characteristics, and the sum of the currents sourced or sunk by all the I/Os (I/O ports and control pins) must always respect the absolute maximum ratings $\Sigma_{\mathrm{I}}$.
4. TTL and CMOS outputs are compatible with JEDEC standards JESD36 and JESD52.
5. Specified by design. Not tested in production.

Table 97. Output voltage characteristics for FT_t I/Os in $\mathrm{V}_{\text {BAT }}$ mode, and for FT_o I/Os ${ }^{(1)}$ (2)

| Symbol | Parameter | Conditions | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{V}_{\mathrm{OL}}$ | Output low-level voltage | $\left\|_{\mathrm{IO}}\right|=0.5 \mathrm{~mA}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\mathrm{SW}} \leq 3.6 \mathrm{~V}$ | - | 0.4 | V |
| $\mathrm{V}_{\mathrm{OH}}$ | Output high-level voltage |  | $\mathrm{V}_{\mathrm{SW}}-0.4$ | - |  |
| $\mathrm{V}_{\mathrm{OL}}$ | Output low-level voltage | $\left\|_{\mathrm{IO}}\right|=0.25 \mathrm{~mA}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\mathrm{SW}} \leq 3.6 \mathrm{~V}$ | - | 0.4 |  |
| $\mathrm{V}_{\mathrm{OH}}$ | Output high-level voltage |  | $\mathrm{V}_{\mathrm{SW}}-0.4$ | - |  |

1. Specified by design. Not tested in production.
2. $\mathrm{FT} \_\mathrm{o} \mathrm{I} / \mathrm{Os}$ output voltage characteristics are provided in Table 96 for revision $X$ devices.# Output AC characteristics 

The definition and values of output AC characteristics are given in Figure 37: Output AC characteristics definition and in the table below respectively.

Unless otherwise specified, the parameters given are derived from tests performed under the ambient temperature and supply voltage conditions summarized in Table 33.

Table 98. Output AC characteristics, HSLV OFF (all I/Os except FT_c, FT_t in $\mathrm{V}_{\text {BAT }}$ mode and $\mathrm{FT} \_\mathrm{o} \mathrm{I} / \mathrm{Os}^{(1)} \mid^{(2)(3)(4)}$

| Speed | Symbol | Parameter | Conditions | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 00 | Fmax | Maximum frequency all I/Os | $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 12.5 | MHz |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 5 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 1 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 12.5 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 5 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 1 |  |
|  | $t_{r} / t_{f}$ | Output rise and fall time all I/Os | $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 17 | ns |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 33 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 85 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 12.5 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 25 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 50 |  |
| 01 | Fmax | Maximum frequency all I/Os | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 55 | MHz |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 12.5 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 2.5 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 55 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 12.5 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq<1.58 \mathrm{~V}$ | - | 2.5 |  |
|  | $t_{r} / t_{f}$ | Output rise and fall time all I/Os | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 5.8 | ns |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 10 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 18 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 4.2 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 7.5 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 12 |  |Table 98. Output AC characteristics, HSLV OFF (all I/Os except FT_c, FT_t in $\mathrm{V}_{\mathrm{BAT}}$ mode and $\mathrm{FT} \_\mathrm{o} \mathrm{I} / \mathrm{Os}{ }^{(1)})^{(2)(3)(4)}$ (continued)

| Speed | Symbol | Parameter | Conditions | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 10 | Fmax | Maximum frequency all I/Os | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | $100^{(5)}$ | MHz |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $33^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 5 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | $133^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $40^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 5 |  |
|  | $t_{r} / t_{f}$ | Output rise and fall time all I/Os | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | $3.3^{(5)}$ | ns |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $6.0^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 13.3 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | $2^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $4.1^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 9.2 |  |
| 11 | Fmax | Maximum frequency All I/Os except FT_c, FT_v, and TT_v | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | $100^{(5)}$ | MHz |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $33^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 5 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | $133^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $40^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 5 |  |
|  |  | Maximum frequency <br> FT_v and TT_v I/Os | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | $140^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $40^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 5 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | $166^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $50^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 5 |  |
|  | $t_{r} / t_{f}$ | Output rise and fall time All I/Os except FT_c, FT_v, and TT_v | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | $3.3^{(5)}$ | ns |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $6.0^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 13.3 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ |  | $2.0^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ |  | $4.1^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ |  | 9.2 |  |Table 98. Output AC characteristics, HSLV OFF (all I/Os except FT_c, FT_t in $\mathrm{V}_{\mathrm{BAT}}$ mode and $\mathrm{FT} \_\mathrm{o} \mathrm{I} / \mathrm{Os}^{(1)} \mathrm{I}^{(2)(3)(4)}$ (continued)

| Speed | Symbol | Parameter | Conditions | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\begin{gathered} 11 \\ \text { (cont'd) } \end{gathered}$ | $t_{r} / t_{f}$ | Output rise and fall time FT_v and TT_v I/Os | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | $2.5^{(5)}$ | ns |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $5.0^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 11 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | $1.66^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $3.1^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 7 |  |
| Fm+ | Fmax | Maximum frequency | $\mathrm{C}_{\mathrm{L}}=550 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<3.6 \mathrm{~V}$ | - | 1 | MHz |
|  | $t_{f}$ | Output fall time ${ }^{(6)}$ | $\mathrm{C}_{\mathrm{L}}=100 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<3.6 \mathrm{~V}$ | - | 50 | ns |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=100 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 80 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=550 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<3.6 \mathrm{~V}$ | - | 100 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=550 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 220 |  |

1. FT_t I/O characteristics are degraded only in $\mathrm{V}_{\mathrm{BAT}}$ mode (refer to Table 101). FT_o I/O characteristics are provided in this table for revision $X$ devices. FT_o I/O characteristics are provided in Table 101 for all other device revisions.
2. The I/O structure options listed in this table can be a concatenation of options including the option explicitly listed. For instance TT_a refers to any TT I/O with _a option. TT_xx refers to any TT I/O and FT_xx refers to any FT I/O.
3. The I/O speed is configured using the OSPEEDRy[1:0] bits. Refer to the product reference manual for a description of GPIO port configuration register.
4. Specified by design. Not tested in production.
5. Compensation system enabled.
6. The fall time is defined between $70 \%$ and $30 \%$ of the output waveform accordingly to $\mathrm{I}^{2} \mathrm{C}$ specification.

Table 99. Output AC characteristics, HSLV ON (all I/Os except FT_c) ${ }^{(1)(2)(3)(4)}$

| Speed | Symbol | Parameter | Conditions | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 00 | Fmax | Maximum frequency | $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 10 | MHz |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 4 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 15 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 4 |  |
|  | $t_{r} / t_{f}$ | Output rise and fall time | $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 18 | ns |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 32 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 12 |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 21 |  |Table 99. Output AC characteristics, HSLV ON (all I/Os except FT_c) ${ }^{(1)(2)(3)(4)}$ (continued)

| Speed | Symbol | Parameter | Conditions | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 01 | Fmax | Maximum frequency | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 50 | MHz |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 10 |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 67 |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 10 |
|  | $t_{r} / t_{\ell}$ | Output rise and fall time | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 5.3 | ns |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 10.6 |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 3.1 |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 5.6 |
| 10 | Fmax | Maximum frequency | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $75^{(5)}$ | MHz |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 15 |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $100^{(5)}$ |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 15 |
|  | $t_{r} / t_{\ell}$ | Output rise and fall time | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $4.4^{(5)}$ | ns |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 9.6 |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $2.2^{(5)}$ |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 4.7 |
| 11 | Fmax | Maximum frequency <br> All I/Os except FT_c, FT_v, and TT_v | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $75^{(5)}$ | MHz |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 15 |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $100^{(5)}$ |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 15 |
|  |  | Maximum frequency <br> FT_v and TT_v I/Os | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $110^{(5)}$ |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 25 |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $150^{(5)}$ |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 25 |
| 11 | $t_{r} / t_{\ell}$ | Output rise and fall time All I/Os except FT_c, FT_v, and TT_v | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $4.4^{(5)}$ | ns |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 9.6 |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $2.2^{(5)}$ |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 4.7 |
|  |  | Output rise and fall time <br> FT_v and TT_v I/Os | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $3.0^{(5)}$ |  |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 6.6 |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | $1.6^{(5)}$ |
|  |  |  | $\mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}, 1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<1.58 \mathrm{~V}$ | - | 3.4 |

1. The I/O structure options listed in this table can be a concatenation of options including the option explicitly listed. For instance TT_a refers to any TT I/O with _a option. TT_xx refers to any TT I/O and FT_xx refers to any FT I/O.
2. The I/O speed is configured using the OSPEEDRy[1:0] bits. Refer to the product reference manual for a description of GPIO port configuration register.3. Specified by design. Not tested in production.
4. $\mathrm{FT} \_\mathrm{t}$ I/O characteristics are degraded only in $\mathrm{V}_{\mathrm{BAT}}$ mode (refer to Table 101).
5. Compensation system enabled.

Table 100. Output AC characteristics for FT_c I/Os ${ }^{(1)(2)}$

| Speed | Symbol | Parameter | Conditions | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 00 | Fmax | Maximum frequency | All I/Os, $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 10 | MHz |
|  |  |  | All I/Os, $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 5 |  |
|  | $t_{r} / t_{f}$ | Output rise and fall time | All I/Os, $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 33 | ns |
|  |  |  | All I/Os, $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 66 |  |
| 01 | Fmax | Maximum frequency | All I/Os, $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 25 | MHz |
|  |  |  | All I/Os, $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 10 |  |
|  | $t_{r} / t_{f}$ | Output rise and fall time | All I/Os, $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 13 | ns |
|  |  |  | All I/Os, $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 33 |  |
| $1 x$ | Fmax | Maximum frequency | All I/Os, $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 40 | MHz |
|  |  |  | All I/Os, $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 20 |  |
|  | $t_{r} / t_{f}$ | Output rise and fall time | All I/Os, $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }} \leq 3.6 \mathrm{~V}$ | - | 8 | ns |
|  |  |  | All I/Os, $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOx }}<2.7 \mathrm{~V}$ | - | 17 |  |

1. Specified by design. Not tested in production.
2. The I/O speed is configured using the OSPEEDRy[1:0] bits. Refer to the product reference manual for a description of GPIO port configuration register.

Table 101. Output AC characteristics for FT_t I/Os in $\mathrm{V}_{\text {BAT }}$ mode, and for FT_o I/Os ${ }^{(1)(2)}$

| Symbol | Parameter | Conditions | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: |
| Fmax | Maximum frequency | $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\mathrm{SW}} \leq 3.6 \mathrm{~V}$ | - | 0.5 | MHz |
|  |  | $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\mathrm{SW}}<2.7 \mathrm{~V}$ | - | 0.25 |  |
| $t_{r} / t_{f}$ | Output rise and fall time | $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 2.7 \mathrm{~V} \leq \mathrm{V}_{\mathrm{SW}} \leq 3.6 \mathrm{~V}$ | - | 400 | ns |
|  |  | $\mathrm{C}_{\mathrm{L}}=50 \mathrm{pF}, 1.58 \mathrm{~V} \leq \mathrm{V}_{\mathrm{SW}}<2.7 \mathrm{~V}$ | - | 900 |  |

1. Specified by design. Not tested in production.
2. FT_o I/Os output AC characteristics are provided in Table 98 for revision $X$ devices.Figure 37. Output AC characteristics definition
![img-56.jpeg](img-56.jpeg)

Maximum frequency is achieved with a duty cycle at (45 - 55\%) when loaded by the specified capacitance.

# 5.3.16 NRST pin characteristics 

The NRST pin input driver uses the CMOS technology. It is connected to a permanent pull-up resistor, $\mathrm{R}_{\mathrm{PU}}$.

Unless otherwise specified, the parameters given in the table below are derived from tests performed under the ambient temperature and supply voltage conditions summarized in Table 33.

Table 102. NRST pin characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{V}_{\text {IL(NRST) }}$ | NRST input low-level voltage | - | - | - | $0.3 \times \mathrm{V}_{\mathrm{DD}}$ | V |
| $\mathrm{V}_{\text {IH(NRST) }}$ | NRST input high-level voltage | - | $0.7 \times V_{D D}$ | - | - |  |
| $\mathrm{V}_{\text {hys(NRST) }}$ | NRST Schmitt trigger voltage hysteresis | - | - | 200 | - | mV |
| $R_{P U}$ | Weak pull-up equivalent resistor ${ }^{(2)}$ | $\mathrm{V}_{\mathrm{IN}}=\mathrm{V}_{\mathrm{SS}}$ | 30 | 40 | 50 | $\mathrm{k} \Omega$ |
| $\mathrm{I}_{\mathrm{F}(\text { NRST) }}$ | NRST input filtered pulse | - | - | - | 50 | ns |
| $\mathrm{I}_{\mathrm{NF}(\text { NRST) }}$ | NRST input not-filtered pulse | $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | 330 | - | - |  |
|  |  | $1.58 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | 1000 | - | - |  |

1. Specified by design. Not tested in production.
2. The pull-up is designed with a true resistance in series with a switchable PMOS. This PMOS contribution to the series resistance is minimal ( $\sim 10 \%$ order).Figure 38. Recommended NRST pin protection
![img-57.jpeg](img-57.jpeg)

1. The reset network protects the device against parasitic resets.
2. The user must ensure that the level on the NRST pin can go below the $\mathrm{V}_{\mathrm{IL}(\text { NRST) }}$ max level specified in the above table. Otherwise the reset is not taken into account by the device.
3. The external capacitor on NRST must be placed as close as possible to the device.

# 5.3.17 Extended interrupt and event controller input (EXTI) characteristics 

The pulse on the interrupt input must have a minimal length in order to guarantee that it is detected by the event controller.

Table 103. EXTI input characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :-- | :--: | :--: | :--: | :--: | :--: |
| PLEC | Pulse length to event controller | - | 20 | - | - | ns |

1. Specified by design. Not tested in production.

### 5.3.18 Analog switches booster

Table 104. Analog switches booster characteristics ${ }^{(1)}$

| Symbol | Parameter | Min | Typ | Max | Unit |
| :--: | :-- | :--: | :--: | :--: | :--: |
| $\mathrm{V}_{\mathrm{DD}}$ | Supply voltage | 1.6 | 1.8 | 3.6 | V |
| $\mathrm{t}_{\mathrm{SU}(\text { BOOST) }}$ | Booster startup time | - | - | 50 | $\mu \mathrm{s}$ |
| $\mathrm{I}_{\mathrm{DD}(\text { BOOST) }}$ | Booster consumption | - | - | 125 | $\mu \mathrm{A}$ |

1. Specified by design. Not tested in production.# 5.3.19 14-bit analog-to-digital converter (ADC1) characteristics 

Unless otherwise specified, the parameters given in the table below are values derived from tests performed under ambient temperature, $\mathrm{f}_{\mathrm{HCLK}}$ frequency and $\mathrm{V}_{\text {DDA }}$ supply voltage conditions summarized in Table 33.

Note: It is recommended to perform a calibration after each power-up.
Table 105. 14-bit ADC1 characteristics ${ }^{(1)(2)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V_{\text {DDA }}$ | Analog power supply for ADC ON | - | 1.62 | - | 3.6 | V |
| $V_{\text {REF }+}$ | Positive reference voltage | $\mathrm{V}_{\mathrm{DDA}} \geq 2 \mathrm{~V}$ | 2 | - | $V_{\text {DDA }}$ |  |
|  |  | $V_{D D A}<2 \mathrm{~V}$ |  | $V_{\text {DDA }}$ |  |  |
| $V_{\text {REF }}$. | Negative reference voltage | - |  | $V_{\text {SSA }}$ |  |  |
| $f_{\text {ADC }}$ | ADC clock frequency | $1.62 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DDA}} \leq 3.6 \mathrm{~V}$ | $5^{(3)}$ | - | 55 | MHz |
|  | ADC clock ratio | - | 45 | - | 55 | \% |
| $f_{s}$ | Sampling rate | Resolution $=14$ bits | 0.23 | - | 2.5 | Msps |
|  |  | Resolution $=12$ bits | 0.25 | - | 2.75 |  |
|  |  | Resolution $=10$ bits | 0.28 | - | 3.05 |  |
|  |  | Resolution $=8$ bits | 0.31 | - | 3.44 |  |
| $t_{\text {TRIG }}$ | External trigger period | Resolution $=14$ bits | 26 | - | - | $1 / f_{\text {ADC }}$ |
| $V_{\text {AIN }}{ }^{(4)}$ | Conversion voltage range | - | 0 | - | $V_{\text {REF }+}$ | V |
| $V_{\text {CIMV }}$ | Common mode input voltage | - | $V_{\text {REF }+} / 2-10 \%$ | $V_{\text {REF }+} / 2$ | $V_{\text {REF }+} / 2+10 \%$ | V |
| $R_{\text {AIN }}{ }^{(5)}$ | External input impedance | Resolution $=14$ bits $\mathrm{T}_{\mathrm{j}}=130^{\circ} \mathrm{C}$ | - | - | 1000 | $\Omega$ |
|  |  | Resolution $=12$ bits $\mathrm{T}_{\mathrm{j}}=130^{\circ} \mathrm{C}$ | - | - | 1000 |  |
|  |  | Resolution $=10$ bits $\mathrm{T}_{\mathrm{j}}=130^{\circ} \mathrm{C}$ | - | - | 4700 |  |
|  |  | Resolution $=8$ bits $\mathrm{T}_{\mathrm{j}}=130^{\circ} \mathrm{C}$ | - | - | 22000 |  |
| $C_{\text {ADC }}$ | Internal sample and hold capacitor | - | - | 5 | - | pF |
| $\begin{gathered} \mathrm{t}_{\text {ADCVREG }} \\ \text { STUP } \end{gathered}$ | ADC LDO startup time | - | - | - | 17 | $\mu \mathrm{s}$ |
| $t_{\text {STAB }}$ | ADC power-up time | LDO already started | $\left(3 \times 1 / f_{\text {ADC }}\right)+1$ |  |  | Cycle |
| $t_{\text {CAL }}$ | Offset and linearity calibration time | - | 31849 |  |  | $1 / f_{\text {ADC }}$ |
| $t_{\text {OFF_CAL }}$ | Offset calibration time | - | 885 |  |  |  |Table 105. 14-bit ADC1 characteristics ${ }^{(1)(2)}$ (continued)

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{\text {LATR }}$ | Trigger conversion latency for regular and injected channels, without aborting the conversion | PRESC $=0$ | 3 |  |  | $1 / f_{\text {ADC }}$ |
|  |  | PRESC $=1$ | 7 |  |  |  |
|  |  | PRESC $=2$ | 13 |  |  |  |
| $t_{\text {LATRINJ }}$ | Trigger conversion latency Injected channels aborting a regular conversion | PRESC $=0$ | 4 |  |  |  |
|  |  | PRESC $=1$ | 9 |  |  |  |
|  |  | PRESC $=2$ | 17 |  |  |  |
| $t_{\mathrm{s}}$ | Sampling time | - | 5 | - | 814 |  |
| $t_{\text {CONV }}$ | Total conversion time (including sampling time) | Resolution $=\mathrm{N}$ bits | $t_{s}+N+3$ |  |  |  |
| $\mathrm{t}_{\text {DDA_D(ADC) }}$ | ADC consumption on $\mathrm{V}_{\text {DDA }}$ Differential mode | $f_{s}=2.5 \mathrm{Msps}$, resolution $=14$ bits | - | 970 | - | $\mu \mathrm{A}$ |
|  |  | $f_{s}=1 \mathrm{Msps}$, resolution $=14$ bits | - | 550 | - |  |
|  |  | $f_{s}=10 \mathrm{ksps}$, resolution $=14$ bits | - | 130 | - |  |
|  |  | $f_{s}=2.5 \mathrm{Msps}$, resolution $=12$ bits | - | 940 | - |  |
|  |  | $f_{s}=2.5 \mathrm{Msps}$, resolution $=10$ bits | - | 840 | - |  |
|  |  | $f_{s}=2.5 \mathrm{Msps}$, resolution $=8$ bits | - | 730 | - |  |
| $\mathrm{t}_{\text {DDV_D(ADC) }}$ | ADC consumption on $\mathrm{V}_{\text {REF }+}$ Differential mode | $f_{s}=2.5 \mathrm{Msps}$, resolution $=14$ bits | - | 140 | - | $\mu \mathrm{A}$ |
|  |  | $f_{s}=1 \mathrm{Msps}$, resolution $=14$ bits | - | 80 | - |  |
|  |  | $f_{s}=10 \mathrm{ksps}$, resolution $=14$ bits | - | 13 | - |  |
|  |  | $f_{s}=2.5 \mathrm{Msps}$, resolution $=12$ bits | - | 140 | - |  |
|  |  | $f_{s}=2.5 \mathrm{Msps}$, resolution $=10$ bits | - | 140 | - |  |
|  |  | $f_{s}=2.5 \mathrm{Msps}$, resolution $=8$ bits | - | 120 | - |  |Table 105. 14-bit ADC1 characteristics ${ }^{(1)(2)}$ (continued)

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{I}_{\text {DDA_5(ADC) }}$ | ADC consumption on $\mathrm{V}_{\text {DDA }}$ Singe-ended mode | $f_{s}=2.5 \mathrm{Msps}$, <br> resolution $=14$ bits | - | 980 | - | $\mu \mathrm{A}$ |
|  |  | $f_{s}=1 \mathrm{Msps}$, <br> resolution $=14$ bits | - | 550 | - |  |
|  |  | $f_{s}=10 \mathrm{ksps}$, <br> resolution $=14$ bits | - | 130 | - |  |
|  |  | $f_{s}=2.5 \mathrm{Msps}$, <br> resolution $=12$ bits | - | 900 | - |  |
|  |  | $f_{s}=2.5 \mathrm{Msps}$, <br> resolution $=10$ bits | - | 840 | - |  |
|  |  | $f_{s}=2.5 \mathrm{Msps}$, <br> resolution $=$ 8bits | - | 770 | - |  |
| $\mathrm{I}_{\text {DDV_5(ADC) }}$ | ADC consumption on $\mathrm{V}_{\text {REF }}$, Single-ended mode | $f_{s}=2.5 \mathrm{Msps}$, <br> resolution $=14$ bits | - | 160 | - | $\mu \mathrm{A}$ |
|  |  | $f_{s}=1 \mathrm{Msps}$, <br> resolution $=14$ bits | - | 90 | - |  |
|  |  | $f_{s}=10 \mathrm{ksps}$, <br> resolution $=14$ bits | - | 15 | - |  |
|  |  | $f_{s}=2.5 \mathrm{Msps}$, <br> resolution $=12$ bits | - | 150 | - |  |
|  |  | $f_{s}=2.5 \mathrm{Msps}$, <br> resolution $=10$ bits | - | 150 | - |  |
|  |  | $f_{s}=2.5 \mathrm{Msps}$, <br> resolution $=$ 8bits | - | 150 | - |  |

1. Specified by design. Not tested in production.
2. The voltage booster on the ADC switches must be used when $\mathrm{V}_{\text {DDA }}<2.4 \mathrm{~V}$ (embedded I/O switches).
3. Degraded differential linearity error below 10 MHz .
4. Depending on the package, $\mathrm{V}_{\mathrm{REF}}$, can be internally connected to $\mathrm{V}_{\mathrm{DDA}}$ and $\mathrm{V}_{\mathrm{REF}}$, can be internally connected to $\mathrm{V}_{\mathrm{SSA}}$.
5. The maximum value of $R_{\text {alN }}$ is specified to keep leakage induced offset within the specified tolerance. The tolerance is 4 LSBs for 14-bit resolution and 2 LSBs for 12-bit, 10-bit, and 8-bit resolutions.

The maximum value of $R_{\text {AlN }}$ can be found in the table below.
Table 106. Maximum $\mathbf{R}_{\text {AlN }}$ for 14-bit $\mathrm{ADC1}^{(1)(2)}$ (3)

| Resolution $\left({ }^{(4)}\right.$ | $\mathbf{R}_{\text {AlN }} \max (\Omega)^{(5)}$ | Sampling time [ns] | Sampling cycle at 5 MHz | Sampling cycle at 55 MHz |
| :--: | :--: | :--: | :--: | :--: |
| 14 bits | 47 | 142 | 5 | 12 |
|  | 68 | 145 |  |  |
|  | 100 | 170 |  |  |Table 106. Maximum $R_{\text {AIN }}$ for 14-bit $\operatorname{ADC1}{ }^{(1)(2)(3)}$ (continued)

| Resolution ${ }^{(4)}$ | $\mathrm{R}_{\text {AIN }}$ max ( $\Omega$ ) ${ }^{(5)}$ | Sampling time [ns] | Sampling cycle at 5 MHz | Sampling cycle at 55 MHz |
| :--: | :--: | :--: | :--: | :--: |
| 12 bits | 47 | 135 | 5 | 12 |
|  | 68 | 135 |  |  |
|  | 100 | 140 |  |  |
|  | 150 | 145 |  |  |
|  | 220 | 150 |  |  |
|  | 330 | 155 |  |  |
|  | 470 | 180 |  |  |
| 10 bits | 47 | 128 | 5 | 12 |
|  | 68 | 130 |  |  |
|  | 100 | 132 |  |  |
|  | 150 | 134 |  |  |
|  | 220 | 140 |  |  |
|  | 330 | 146 |  |  |
|  | 470 | 160 |  |  |
|  | 680 | 176 |  | 12 |
|  | 1000 | 200 |  |  |
|  | 1500 | 240 |  | 20 |
|  | 2200 | 320 |  |  |
| 8 bits | 47 | 123 | 5 | 12 |
|  | 68 | 124 |  |  |
|  | 100 | 125 |  |  |
|  | 150 | 128 |  |  |
|  | 220 | 130 |  |  |
|  | 330 | 137 |  |  |
|  | 470 | 140 |  |  |
|  | 680 | 157 |  |  |
|  | 1000 | 178 |  |  |
|  | 1500 | 204 |  |  |
|  | 2200 | 250 |  | 20 |
|  | 3300 | 313 |  |  |
|  | 4700 | 400 | 5 | 36 |
|  | 6800 | 546 |  |  |
|  | 10000 | 830 |  | 68 |

1. Specified by design. Not tested in production.
2. BOOSTEN and ANASWVDD configured properly according to $\mathrm{V}_{\mathrm{DD}}$ and $\mathrm{V}_{\mathrm{DDA}}$ values.
3. Values without external capacitor.4. The tolerance is 2 LSBs for 14 bits and 1 LSB for other resolutions.
5. The maximum value of $R_{A / N}$ is obtained in a worst-case scenario: channel conversion in scan mode with channel $i$ connected to $\mathrm{V}_{\text {REF }}$, and channel $i+1$ connected to $\mathrm{V}_{\text {REF } .}$.

Table 107. 14-bit ADC1 accuracy ${ }^{(1)(2)}$

| Symbol | Parameter | Conditions ${ }^{(3)}$ |  | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| ET | Total unadjusted error | Single ended | Rev. $X$ | - | $\pm 25$ | - | LSB |
|  |  | Differential |  | - | $\pm 28$ | - |  |
|  |  | Single ended | Other revision with extended calibration mode | - | $\pm 6$ | $\pm 12$ |  |
|  |  | Differential |  | - | $\pm 3$ | $\pm 6$ |  |
| EO | Offset error | Single ended |  | - | $\pm 6$ | $\pm 12^{(4)}$ |  |
|  |  | Differential |  | - | $\pm 2$ | $\pm 6^{(4)}$ |  |
| EG | Gain error | Single ended | Rev. $X$ | - | $\pm 15$ | - |  |
|  |  | Differential |  | - |  |  |  |
|  |  | Single ended | Other revision with extended calibration mode | - | $\pm 5$ | $\pm 10$ |  |
|  |  | Differential |  | - | $\pm 2.5$ | $\pm 5$ |  |
| ED | Differential linearity error | Single ended | $f_{\text {ADC }} \geq 10 \mathrm{MHz}$ | - | $-0.9 /+1.5$ | $-0.9 /+2.5$ |  |
|  |  | Differential |  | - |  |  |  |
|  |  | Single ended | $f_{\text {ADC }}<10 \mathrm{MHz}$ | - | $-0.9 /+1.5$ | $-1 /+3$ |  |
|  |  | Differential |  | - |  |  |  |
| EL | Integral linearity error | Single ended |  | - | $\pm 3$ | $\pm 7$ |  |
|  |  | Differential |  | - | $\pm 2$ | $\pm 5$ |  |
| ENOB | Effective number of bits | Single ended |  | 11 | 12 | - | bits |
|  |  | Differential |  | 11.8 | 12.8 | - |  |
| SINAD | Signal-to-noise and distortion ratio | Single ended |  | 68 | 74 | - | dB |
|  |  | Differential |  | 73 | 78 | - |  |
| SNR | Signal-to-noise ratio | Single ended |  | 68 | 74 | - |  |
|  |  | Differential |  | 73 | 78 | - |  |
| THD | Total harmonic distortion | Single ended |  | - | $-84$ | $-80$ |  |
|  |  | Differential |  | - | $-95$ | $-89$ |  |

1. Evaluated by characterization for BGA packages. Not tested in production. The values for LQFP packages may differ.
2. ADC DC accuracy values are measured after the internal calibration.
3. The I/O analog switch voltage booster is enable when $\mathrm{V}_{\mathrm{DDA}}<2.4 \mathrm{~V}$ (BOOSTEN $=1$ in SYSCFG_CFGR1 when $\mathrm{V}_{\mathrm{DDA}}<2.4 \mathrm{~V}$ ). The booster is disabled when $\mathrm{V}_{\mathrm{DDA}} \geq 2.4 \mathrm{~V}$. Resolution $=14$ bits, no oversampling.
4. This parameter may degrade in case of digital activity on adjacent I/Os.Figure 39. ADC accuracy characteristics
![img-58.jpeg](img-58.jpeg)

Figure 40. Typical connection diagram when using the ADC with FT/TT pins featuring analog switch function
![img-59.jpeg](img-59.jpeg)

1. Refer to the ADCx characteristic table for the values of $R_{A / N}$ and $C_{A D C}$.
2. $C_{\text {parasitic }}$ represents the capacitance of the PCB (dependent on soldering and PCB layout quality) plus the pad capacitance (refer to Table 95: I/O static characteristics for the value of the pad capacitance). A high $C_{\text {parasitic }}$ value downgrades the conversion accuracy. To remedy this, $f_{\text {ADC }}$ must be reduced.
3. Refer to Table 95: I/O static characteristics for the values of $I_{\text {/kg }}$.
4. Refer to Section 5.1.6: Power supply scheme.

# General PCB design guidelines 

The power-supply decoupling must be performed as shown in the corresponding power-supply scheme. The 100 nF capacitor must be ceramic (good quality) and must be placed as close as possible to the chip.# 5.3.20 12-bit analog-to-digital converter (ADC4) characteristics 

Unless otherwise specified, the parameters given in the table below are values derived from tests performed under ambient temperature, $\mathrm{f}_{\mathrm{HCLK}}$ frequency and $\mathrm{V}_{\mathrm{DDA}}$ supply voltage conditions summarized in Table 33.

Note: It is recommended to perform a calibration after each power-up.
Table 108. 12-bit ADC4 characteristics ${ }^{(1)(2)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V_{D D A}$ | Analog power supply for ADC <br> ON | - | 1.62 | - | 3.6 | V |
| $\mathrm{V}_{\text {REF }+}$ | Positive reference voltage | - | 1 | - | $V_{\text {DDA }}$ |  |
| $V_{\text {REF- }}$ | Negative reference voltage | - | $V_{\text {SSA }}$ |  |  |  |
| $f_{\text {ADC }}$ | ADC clock frequency | $1.62 \mathrm{~V} \leq \mathrm{V}_{\text {DDA }} \leq 3.6 \mathrm{~V}$ | 0.14 | - | 55 | MHz |
|  | ADC clock duty cycle | - | 45 | - | 55 | \% |
| $f_{s}$ | Sampling rate | Resolution $=12$ bits | 0.01 | - | 2.75 | Msps |
|  |  | Resolution $=10$ bits | 0.012 | - | 3.05 |  |
|  |  | Resolution $=8$ bits | 0.014 | - | 3.43 |  |
|  |  | Resolution $=6$ bits | 0.0175 | - | 3.92 |  |
| $t_{\text {TRIG }}$ | External trigger period | Resolution $=12$ bits | 16 | - | - | $1 / f_{\text {ADC }}$ |
| $\mathrm{V}_{\text {AIN }}{ }^{(3)}$ | Conversion voltage range | - | 0 | - | $\mathrm{V}_{\text {REF }+}$ | V |
| $R_{\text {AIN }}{ }^{(4)}$ | External input impedance $T_{i}=130^{\circ} \mathrm{C}$ | Resolution $=12$ bits | - | - | 2.2 | kD |
|  |  | Resolution $=10$ bits | - | - | 6.8 |  |
|  |  | Resolution $=8$ bits | - | - | 33.0 |  |
|  |  | Resolution $=6$ bits | - | - | 47.0 |  |
| $C_{\text {ADC }}$ | Internal sample and hold capacitor | - | - | 5 | - | pF |
| $\begin{gathered} \mathrm{t}_{\text {ADCVREG }} \\ \text { STUP } \end{gathered}$ | ADC LDO startup ready flag time | - | - | - | 25 | $\mu \mathrm{s}$ |
| $t_{\text {STAB }}$ | ADC power-up time | LDO already started | $\left(3 \times 1 / f_{\text {ADC }}\right)+1$ |  |  | Cycle |
| $\mathrm{t}_{\text {OFF_CAL }}$ | Offset calibration time | - | - | 123 | - | $1 / f_{\text {ADC }}$ |
| $t_{\text {LATR }}$ | Trigger conversion latency | WAIT $=0$, AUTOFF $=0$, $\mathrm{DPD}=0, \mathrm{f}_{\mathrm{ADC}}=\mathrm{HCLK}$ | 4 |  |  |  |
|  |  | WAIT $=0$, AUTOFF $=0$, $\mathrm{DPD}=0, \mathrm{f}_{\mathrm{ADC}}=\mathrm{HCLK} / 2$ | 4 |  |  |  |
|  |  | WAIT $=0$, AUTOFF $=0$, $\mathrm{DPD}=0, \mathrm{f}_{\mathrm{ADC}}=\mathrm{HCLK} / 4$ | 3.75 |  |  |  |
| $t_{s}$ | Sampling time | - | 1.5 | - | 814.5 |  |Table 108. 12-bit ADC4 characteristics ${ }^{(1)(2)}$ (continued)

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{\text {CONV }}$ | Total conversion time (including sampling time) | Resolution $=\mathrm{N}$ bits, VREFPROTEN $=0$ | $t_{s}+N+0.5$ |  |  | $1 / f_{A D C}$ |
|  |  | Resolution $=\mathrm{N}$ bits, VREFPROTEN $=1$ VREFSECSMP $=0$ | $t_{s}+N+0.5$ | - | $t_{s}+N+1.5$ |  |
|  |  | Resolution $=\mathrm{N}$ bits, VREFPROTEN $=1$ VREFSECSMP $=1$ | $t_{s}+N+0.5$ | - | $t_{s}+N+2.5$ |  |
| $I_{D D A(A D C)}$ | ADC consumption on $\mathrm{V}_{\text {DDA }}$ | $f_{s}=2.5 \mathrm{Msps}$ | - | 360 | - | $\mu \mathrm{A}$ |
|  |  | $f_{s}=1 \mathrm{Msps}$ | - | 180 | - |  |
|  |  | $f_{s}=10 \mathrm{ksps}$ | - | 10 | - |  |
|  |  | AUTOFF $=1, \mathrm{DPD}=0$, no conversion | - | 9 | - |  |
|  |  | AUTOFF $=1, \mathrm{DPD}=1$, no conversion | - | 0.1 | - |  |
| $I_{D D V(A D C)}$ | ADC consumption on $\mathrm{V}_{\text {REF }}$ | $f_{s}=2.5 \mathrm{Msps}$ | - | 18 | - |  |
|  |  | $f_{s}=1 \mathrm{Msps}$ | - | 10.2 | - |  |
|  |  | $f_{s}=10 \mathrm{ksps}$ | - | 0.12 | - |  |
|  |  | AUTOFF $=1, \mathrm{DPD}=0$, no conversion | - | 0.01 | - |  |
|  |  | AUTOFF $=1, \mathrm{DPD}=1$, no conversion | - | 0.01 | - |  |

1. Specified by design. Not tested in production.
2. The voltage booster on the ADC switches must be used when $\mathrm{V}_{\text {DDA }}<2.4 \mathrm{~V}$ (embedded I/O switches).
3. Depending on the package, $\mathrm{V}_{\text {REF }}$, can be internally connected to $\mathrm{V}_{\text {DDA }}$ and $\mathrm{V}_{\text {REF }}$, can be internally connected to $\mathrm{V}_{\text {SSA }}$.
4. The maximum value of $R_{\text {sin }}$ is specified to keep leakage induced offset within the specified tolerance. The tolerance is 2 LSBs.The maximum value of $R_{\text {AIN }}$ can be found in the table below.
Table 109. Maximum $\mathrm{R}_{\text {AIN }}$ for 12-bit ADC4 ${ }^{(1)(2)(3)}$

| Resolution ${ }^{(4)}$ | $\mathbf{R}_{\text {AIN }} \max (\Omega)^{(5)}$ | Sampling time [ns] | Sampling cycle at 35 MHz | Sampling cycle at 55 MHz |
| :--: | :--: | :--: | :--: | :--: |
| 12 bits | 47 | 276 | 12.5 | 19.5 |
|  | 68 | 288 |  |  |
|  | 100 | 306 |  |  |
|  | 150 | 336 |  |  |
|  | 220 | 377 | 19.5 | 39.5 |
|  | 330 | 442 |  |  |
|  | 470 | 526 |  |  |
|  | 680 | 650 | 39.5 |  |
|  | 1000 | 840 |  | 79.5 |
|  | 1500 | 1134 |  |  |
|  | 2200 | 1643 | 79.5 | 814.5 |
|  | 3300 | 2395 | 814.5 |  |
|  | 4700 | 3342 |  |  |
|  | 6800 | 4754 |  |  |
|  | 10000 | 6840 |  |  |
|  | 15000 | 9967 |  |  |
|  | 22000 | 14068 |  |  |
|  | 33000 | 19933 |  | N/A |
| 10 bits | 47 | 86 | 3.5 | 7.5 |
|  | 68 | 90 |  |  |
|  | 100 | 95 |  |  |
|  | 150 | 108 | 7.5 |  |
|  | 220 | 116 |  |  |
|  | 330 | 136 |  |  |
|  | 470 | 161 |  | 12.5 |
|  | 680 | 212 |  |  |
|  | 1000 | 276 | 12.5 | 19.5 |
|  | 1500 | 376 | 19.5 | 39.5 |
|  | 2200 | 516 |  | 79.5 |
|  | 3300 | 735 | 39.5 |  |
|  | 4700 | 1012 |  |  |
|  | 6800 | 1423 | 79.5 | 814.5 |Table 109. Maximum $\mathrm{R}_{\text {AIN }}$ for 12-bit ADC4 ${ }^{(1)(2)(3)}$ (continued)

| Resolution ${ }^{(4)}$ | $\mathrm{R}_{\text {AIN }}$ max ( $\Omega$ ) ${ }^{(5)}$ | Sampling time [ns] | Sampling cycle at 35 MHz | Sampling cycle at 55 MHz |
| :--: | :--: | :--: | :--: | :--: |
| 10 bits (cont'd) | 10000 | 2040 | 814.5 | 814.5 |
|  | 15000 | 2978 |  |  |
|  | 22000 | 4356 |  |  |
|  | 33000 | 6443 |  |  |
|  | 47000 | 8925 |  |  |
| 8 bits | 47 | 45 | 3.5 | 3.5 |
|  | 68 | 46 |  |  |
|  | 100 | 48 |  |  |
|  | 150 | 53 |  |  |
|  | 220 | 59 |  |  |
|  | 330 | 69 |  | 7.5 |
|  | 470 | 81 |  |  |
|  | 680 | 101 | 7.5 |  |
|  | 1000 | 130 |  |  |
|  | 1500 | 177 |  | 12.5 |
|  | 2200 | 242 | 12.5 | 19.5 |
|  | 3300 | 345 |  |  |
|  | 4700 | 475 | 19.5 | 39.5 |
|  | 6800 | 670 | 39.5 |  |
|  | 10000 | 963 |  | 79.5 |
|  | 15000 | 1417 | 79.5 |  |
|  | 22000 | 2040 |  | 814.5 |
|  | 33000 | 2995 | 814.5 |  |
|  | 47000 | 4158 |  |  |
| 6 bits | 47 | 32 | 1.5 | 3.5 |
|  | 68 | 32 |  |  |
|  | 100 | 33 |  |  |
|  | 150 | 35 |  |  |
|  | 220 | 37 |  |  |
|  | 330 | 41 |  |  |Table 109. Maximum $\mathrm{R}_{\text {AIN }}$ for 12-bit ADC4 ${ }^{(1)(2)(3)}$ (continued)

| Resolution ${ }^{(4)}$ | $\mathbf{R}_{\text {AIN }} \max (\Omega)^{(5)}$ | Sampling time [ns] | Sampling cycle at 35 MHz | Sampling cycle at 55 MHz |
| :--: | :--: | :--: | :--: | :--: |
| 6 bits (cont'd) | 470 | 49 | 3.5 | 3.5 |
|  | 680 | 61 |  |  |
|  | 1000 | 79 |  | 7.5 |
|  | 1500 | 106 | 7.5 |  |
|  | 2200 | 146 |  | 12.5 |
|  | 3300 | 207 |  |  |
|  | 4700 | 286 | 12.5 | 19.5 |
|  | 6800 | 404 | 19.5 | 39.5 |
|  | 10000 | 584 | 39.5 |  |
|  | 22000 | 1250 | 79.5 | 79.5 |
|  | 33000 | 1853 |  | 814.5 |
|  | 47000 | 2607 | 814.5 |  |

1. Specified by design. Not tested in production.
2. BOOSTEN and ANASWVDD configured properly according to $\mathrm{V}_{\mathrm{DD}}$ and $\mathrm{V}_{\mathrm{DDA}}$ values.
3. Values without external capacitor.
4. The tolerance is 1 LSB .
5. The maximum value of $R_{A J N}$ is obtained in a worst-case scenario: channel conversion in scan mode with channel $i$ connected to $\mathrm{V}_{\text {REF }}$, and channel $\mathrm{i}+1$ connected to $\mathrm{V}_{\text {REF }}$ -

Table 110. 12-bit ADC4 accuracy ${ }^{(1)(2)(3)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :-- | :--: | :--: | :--: | :--: | :--: |
| ET | Total unadjusted error | - | - | $\pm 3$ | $\pm 7.5$ | LSB |
| EO | Offset error | - | - | $\pm 2$ | $\pm 5.5$ |  |
| EG | Gain error | - | - | $\pm 2$ | $\pm 6.5$ |  |
| ED | Differential linearity error | - | - | $-0.9 /+1$ | $-0.9 /+1.5$ |  |
| EL | Integral linearity error | - | - | $\pm 2$ | $\pm 3.5$ |  |
| ENOB | Effective number of bits | - | 9.9 | 10.9 | - | bits |
| SINAD | Signal-to-noise and distortion ratio | - | 61.4 | 67.4 | - | dB |
| SNR | Signal-to-noise ratio | - | 61.6 | 67.5 | - |  |
| THD | Total harmonic distortion | - | - | -74 | -70 |  |

1. Evaluated by characterization for BGA packages. Not tested in production. The values for LQFP packages may differ.
2. ADC DC accuracy values are measured after the internal calibration.
3. The I/O analog switch voltage booster is enabled when $\mathrm{V}_{\mathrm{DDA}}<2.4 \mathrm{~V}$ (BOOSTEN $=1$ in SYSCFG_CFGR1 when $\left.\mathrm{V}_{\mathrm{DDA}}<2.4 \mathrm{~V}\right)$. This switch is disabled when $\mathrm{V}_{\mathrm{DDA}} \geq 2.4 \mathrm{~V}$. Resolution $=12$ bits, no oversampling.

See Figure 39: ADC accuracy characteristics, Figure 40: Typical connection diagram when using the ADC with FT/TT pins featuring analog switch function and General PCB design guidelines.# 5.3.21 Temperature sensor characteristics 

Table 111. Temperature sensor characteristics

| Symbol | Parameter | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{T}_{\mathrm{L}}{ }^{(1)}$ | $\mathrm{V}_{\text {SENSE }}$ linearity with temperature | - | - | 1.3 | ${ }^{\circ} \mathrm{C}$ |
| Avg_Slope ${ }^{(1)}$ | Average slope | 2 | 2.5 | 3.0 | $\mathrm{mV} /{ }^{\circ} \mathrm{C}$ |
| $\mathrm{V}_{30}{ }^{(2)}$ | Voltage at $30^{\circ} \mathrm{C}\left( \pm 1^{\circ} \mathrm{C}\right)$ | 700 | 752 | 800 | mV |
| $\begin{gathered} \Lambda\left(\mathrm{V}_{\text {continuous }} \mathrm{V}_{\text {sampling }}\right)^{(3)} \\ \hline \end{gathered}$ | Difference of voltage between continuous and sampling modes ${ }^{(4)}$ | - | - | $-10 /+4$ |  |
| $\begin{gathered} \mathrm{t}_{\text {START }} \\ \text { (TS_BUF) } \\ \hline \end{gathered}$ | Sensor buffer startup time | - | 1 | 10 | $\mu \mathrm{s}$ |
| $\mathrm{t}_{\mathrm{S} \text { _temp }}{ }^{(3)}$ | ADC sampling time when reading the temperature | 13 | - | - |  |
| $\mathrm{I}_{\mathrm{DD}(\mathrm{TS})^{(3)}}$ | Temperature sensor consumption from $\mathrm{V}_{\mathrm{DD}}$, when selected by ADC | - | 14 | 20 | $\mu \mathrm{A}$ |

1. Evaluated by characterization. Not tested in production.
2. Measured at $\mathrm{V}_{\mathrm{REF}+}=$ V $_{\mathrm{DDA}}=3.0 \mathrm{~V} \pm 10 \mathrm{mV}$. The $\mathrm{V}_{30} \mathrm{~A} / \mathrm{D}$ conversion result is stored in the TS_CAL1 byte. Refer to Table 16: Temperature sensor calibration values.
3. Specified by design. Not tested in production.
4. The temperature sensor is in continuous mode when the regulator is in range 1, 2 or 3 . The temperature sensor is in sampling mode when the regulator is in range 4 , or when the device is in Stop 1 or Stop 2 mode.

### 5.3.22 $\mathrm{V}_{\text {CORE }}$ monitoring characteristics

Table 112. $\mathrm{V}_{\text {CORE }}$ monitoring characteristics ${ }^{(1)}$

| Symbol | Parameter | Min | Typ | Max | Unit |
| :--: | :-- | :--: | :--: | :--: | :--: |
| $\mathrm{t}_{\mathrm{S} \text { _VORE }}$ | ADC sampling time when reading the VCORE <br> voltage | 1 | - | - | $\mu \mathrm{s}$ |

1. Specified by design. Not tested in production.

### 5.3.23 $\mathrm{V}_{\text {BAT }}$ monitoring characteristics

Table 113. $\mathrm{V}_{\text {BAT }}$ monitoring characteristics ${ }^{(1)}$

| Symbol | Parameter | Min | Typ | Max | Unit |
| :--: | :-- | :--: | :--: | :--: | :--: |
| R | Resistor bridge for $\mathrm{V}_{\mathrm{BAT}}$ | - | $4 \times 25.6$ | - | $\mathrm{k} \Omega$ |
| Q | Ratio on $\mathrm{V}_{\mathrm{BAT}}$ measurement | - | 4 | - | - |
| $\mathrm{Er}^{(2)}$ | Error on Q | -5 | - | 5 | $\%$ |
| $\mathrm{t}_{\mathrm{S} \text { _VBAT }}{ }^{(2)}$ | ADC sampling time when reading the VBAT | 5 | - | - | $\mu \mathrm{s}$ |

1. $1.58 \mathrm{~V} \leq \mathrm{V}_{\mathrm{BAT}} \leq 3.6 \mathrm{~V}$
2. Specified by design. Not tested in production.Table 114. $\mathrm{V}_{\text {BAT }}$ charging characteristics

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $R_{B C}$ | Battery charging resistor | VBRS $=0$ | - | 5 | - | k 5 |
|  |  | VBRS $=1$ | - | 1.5 | - |  |

# 5.3.24 Digital-to-analog converter characteristics 

Table 115. DAC characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V_{\text {DDA }}$ | Analog supply voltage for DAC ON | - | 1.6 | - | 3.6 | V |
| $V_{\text {REF }+}$ | Positive reference voltage | - | 1.6 | - | $V_{\text {DDA }}$ |  |
| $V_{\text {REF }}$ | Negative reference voltage | - | - | $V_{\text {SSA }}$ | - |  |
| $R_{L}$ | Resistive load | DAC output buffer ON | connected to $\mathrm{V}_{\text {SSA }}$ | 5 | - | - |
|  |  |  | connected to $V_{\text {DDA }}$ | 25 | - | - |
| $R_{O}$ | Output impedance | DAC output buffer OFF | 10 | 13 | 16 | $\mathrm{k} \Omega$ |
| $R_{\text {BON }}$ | Output impedance sample and hold mode, output buffer ON | $\begin{aligned} & V_{D D A}=2.7 \mathrm{~V} \\ & V_{D D A}=2.0 \mathrm{~V} \end{aligned}$ | - | - | 1.5 |  |
|  |  |  | - | - | 2.5 |  |
| $R_{\text {BOFF }}$ | Output impedance sample and hold mode, output buffer OFF | $\begin{aligned} & V_{D D A}=2.7 \mathrm{~V} \\ & V_{D D A}=2.0 \mathrm{~V} \end{aligned}$ | - | - | 16.5 |  |
|  |  |  | - | - | 17.5 |  |
| $\mathrm{C}_{\mathrm{L}}$ | Capacitive load | DAC output buffer OFF | - | - | 50 | pF |
| $\mathrm{C}_{\mathrm{SH}}$ |  | Sample and hold mode | - | 0.1 | 1 | $\mu \mathrm{F}$ |
| $V_{\text {DAC_OUT }}$ | Voltage on DAC_OUT output | DAC output buffer ON | 0.2 | - | $V_{\text {DDA }}-0.2$ | V |
|  |  | DAC output buffer OFF | 0 | - | $V_{\text {REF }+}$ |  |
| tSETTLING | Settling time (full scale: for a 12-bit code transition between the lowest and the highest input codes when DAC_OUT reaches the final value of $\pm 0.5 \mathrm{LSB}$, $\pm 1 \mathrm{LSB}, \pm 2 \mathrm{LSB}, \pm 4 \mathrm{LSB}$, or $\pm 8 \mathrm{LSB}$ ) | Normal mode DAC output buffer ON $\mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}$, $\mathrm{R}_{\mathrm{L}} \geq 5 \mathrm{k} \Omega$ | $\pm 0.5 \mathrm{LSB}$ | - | 2.05 | 3.05 | $\mu \mathrm{s}$ |
|  |  |  | $\pm 1$ LSB | - | 1.90 | 3 |
|  |  |  | $\pm 2$ LSB | - | 1.85 | 2.85 |
|  |  |  | $\pm 4$ LSB | - | 1.80 | 2.8 |
|  |  |  | $\pm 8$ LSB | - | 1.75 | 2.65 |
|  |  | Normal mode DAC output buffer OFF, $\pm 1 \mathrm{LSB}, \mathrm{C}_{\mathrm{L}}=10 \mathrm{pF}$ | - | 1.7 | 3 |  |
| $\begin{aligned} & \mathrm{t}_{\text {WAKEUP }} \\ & \text { (2) } \end{aligned}$ | Wake-up time from off state (setting the ENx bit in the DAC control register) until the final value $\pm 1$ LSB | Normal mode DAC output buffer ON $\mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}, \mathrm{R}_{\mathrm{L}}=5 \mathrm{k} \Omega$ | - | 4.2 | 7.5 | $\mu \mathrm{s}$ |
|  |  | Normal mode DAC output buffer OFF, $\mathrm{C}_{\mathrm{L}} \leq 10 \mathrm{pF}$ | - | 2 | 5 |  |Table 115. DAC characteristics ${ }^{(1)}$ (continued)

| Symbol | Parameter | Conditions |  | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| PSRR | $\mathrm{DC} \mathrm{V}_{\text {DDA }}$ supply rejection ratio | Normal mode DAC output buffer $\begin{aligned} & \text { ON } \\ & \mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}, \mathrm{R}_{\mathrm{L}}=5 \mathrm{k} \Omega \end{aligned}$ |  | - | $-80$ | $-28$ | dB |
| $\mathrm{t}_{\text {SAMP }}$ | Sampling time in sample and hold mode, $\mathrm{C}_{\mathrm{SH}}=100 \mathrm{nF}$ (code transition between the lowest input code and the highest input code when DACOUT reaches the final value $\pm 1$ LSB) | DAC_OUT <br> pin <br> connected | DAC output buffer <br> ON, $\mathrm{C}_{\mathrm{SH}}=100 \mathrm{nF}$ | - | 0.7 | 1.9 | ms |
|  |  |  | DAC output buffer OFF, $\mathrm{C}_{\mathrm{SH}}=$ 100 nF | - | 10.5 | 15 |  |
|  |  | DAC_OUT pin not connected (internal connection only) | DAC output buffer OFF | - | 2 | 8 | $\mu \mathrm{s}$ |
| $\mathrm{I}_{\text {leak }}$ | Output leakage current | - |  | - | - | ${ }^{(3)}$ | nA |
| $\mathrm{Cl}_{\text {int }}$ | Internal sample and hold capacitor | - |  | 7 | 9.2 | 11 | pF |
| $t_{\text {TRIM }}$ | Middle code offset trim time | DAC output buffer ON |  | 50 | - | - | $\mu \mathrm{s}$ |
| $V_{\text {offset }}$ | Middle code offset for 1 trim code step | $\mathrm{V}_{\text {REF+ }}=3.6 \mathrm{~V}$ |  | - | 1520 | - | $\mu \mathrm{V}$ |
|  |  | $\mathrm{V}_{\text {REF+ }}=1.6 \mathrm{~V}$ |  | - | 680 | - |  |
| $\mathrm{I}_{\text {DDA(DAC) }}$ | DAC consumption from $\mathrm{V}_{\text {DDA }}$ | DAC output buffer ON | No load, middle code (0x800) | - | 330 | 510 | $\mu \mathrm{A}$ |
|  |  |  | No load, worst code (0xF1C) | - | 470 | 680 |  |
|  |  | DAC output buffer OFF | No load, middle/worst code (0x800) | - | - | 0.3 |  |
|  |  | Sample and hold mode, $\mathrm{C}_{\mathrm{SH}}=100 \mathrm{nF}$ |  | - | $\begin{gathered} 330 \times \mathrm{T}_{\mathrm{ON}} \\ /\left(\mathrm{T}_{\mathrm{ON}}+\right. \\ \mathrm{T}_{\mathrm{OFF}} \\ \hline \end{gathered}$ | $\begin{gathered} 680 \times \mathrm{T}_{\mathrm{ON}} \\ \text { /(T } \\ \text { (4) } \end{gathered}$ |  |Table 115. DAC characteristics ${ }^{(1)}$ (continued)

| Symbol | Parameter | Conditions |  | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{I}_{\text {DDV(DAC) }}$ | DAC consumption from $\mathrm{V}_{\text {REF }+}$ | DAC output buffer ON | No load, middle code (0x800) | - | 170 | 240 | $\mu \mathrm{A}$ |
|  |  |  | No load, worst code (0x0E4) | - | 300 | 400 |  |
|  |  | DAC output buffer OFF | No load, middle/worst code (0x800) | - | 145 | 180 |  |
|  |  | Sample and hold mode, buffer $\mathrm{ON}, \mathrm{C}_{\mathrm{SH}}=100 \mathrm{nF}$ (worst code) |  | $\begin{aligned} & 170 \times \mathrm{T}_{\mathrm{ON}} \\ & /\left(\mathrm{T}_{\mathrm{ON}}+ \\ & \mathrm{T}_{\mathrm{OFF}}\right) \\ & (4) \end{aligned}$ | $\begin{aligned} & 400 \times \mathrm{T}_{\mathrm{ON}} \\ & /\left(\mathrm{T}_{\mathrm{ON}}+ \\ & \mathrm{T}_{\mathrm{OFF}}\right) \\ & (4) \end{aligned}$ |  |  |
|  |  | Sample and hold mode, buffer OFF, $\mathrm{C}_{\mathrm{SH}}=100 \mathrm{nF}$ (worst code) |  | $\begin{aligned} & 145 \times \mathrm{T}_{\mathrm{ON}} \\ & /\left(\mathrm{T}_{\mathrm{ON}}+ \\ & \mathrm{T}_{\mathrm{OFF}}\right) \\ & (4) \end{aligned}$ | $\begin{aligned} & 180 \times \mathrm{T}_{\mathrm{ON}} \\ & /\left(\mathrm{T}_{\mathrm{ON}}+ \\ & \mathrm{T}_{\mathrm{OFF}}\right) \\ & (4) \end{aligned}$ |  |  |

1. Specified by design. Not tested in production.
2. In buffered mode, the output can overshoot above the final value for low input code (starting from the minimum value).
3. Refer to Table 95: I/O static characteristics.
4. $\mathrm{T}_{\mathrm{ON}}$ is the refresh phase duration. $\mathrm{T}_{\mathrm{OFF}}$ is the hold phase duration (see the product reference manual for more details).

Figure 41. 12-bit buffered/non-buffered DAC
![img-60.jpeg](img-60.jpeg)

Table 116. DAC accuracy ${ }^{(1)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| DNL | Differential non-linearity ${ }^{(2)}$ | DAC output buffer ON | - | - | $\pm 2$ | LSB |
|  |  | DAC output buffer OFF | - | - | $\pm 2$ |  |
| - | Monotonicity | 10 bits | guaranteed |  |  | - |
| INL | Integral non-linearity ${ }^{(3)}$ | DAC output buffer $\mathrm{ON}, \mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}, \mathrm{R}_{\mathrm{L}} \geq 5 \mathrm{k} \Omega$ | - | - | $\pm 4$ | LSB |
|  |  | DAC output buffer OFF, $\mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}$, no $\mathrm{R}_{\mathrm{L}}$ | - | - | $\pm 4$ |  |Table 116. DAC accuracy ${ }^{(1)}$ (continued)

| Symbol | Parameter | Conditions |  | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| Offset | Offset error at code $0 \times 800^{(3)}$ | DAC output buffer OFF, $\mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}$, no $\mathrm{R}_{\mathrm{L}}$ |  | - | - | $\pm 8$ | LSB |
| Offset1 | Offset error at code $0 \times 001^{(4)}$ | DAC output buffer OFF, $\mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}$, no $\mathrm{R}_{\mathrm{L}}$ |  | - | - | $\pm 5$ |  |
| OffsetCal | Offset error at code $0 \times 800^{(3)}$ <br> after calibration | DAC output buffer ON, $\mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}, \mathrm{R}_{\mathrm{L}} \geq 5 \mathrm{k} \Omega$ | $\mathrm{V}_{\text {REF }+}=3.6 \mathrm{~V}$ | - | - | $\pm 5$ |  |
|  |  |  | $\mathrm{V}_{\text {REF }+}=1.6 \mathrm{~V}$ | - | - | $\pm 5$ |  |
| Gain | Gain error ${ }^{(5)}$ | DAC output buffer ON, $\mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}, \mathrm{R}_{\mathrm{L}} \geq 5 \mathrm{k} \Omega$ |  | - | - | $\pm 0.5$ | \% |
|  |  | DAC output buffer OFF, $\mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}$, no $\mathrm{R}_{\mathrm{L}}$ |  | - | - | $\pm 0.5$ |  |
| TUE | Total unadjusted error | DAC output buffer OFF, $\mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}$, no $\mathrm{R}_{\mathrm{L}}$ |  | - | - | $\pm 10$ | LSB |
|  |  | DAC output buffer ON, $\mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}, \mathrm{R}_{\mathrm{L}} \geq 5 \mathrm{k} \Omega$, after calibration |  | - | - | $\pm 14$ |  |
| SNR | Signal-to-noise ratio ${ }^{(6)}$ | DAC output buffer ON, $\mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}, \mathrm{R}_{\mathrm{L}} \geq 5 \mathrm{k} \Omega$, $1 \mathrm{kHz}, \mathrm{BW}=500 \mathrm{kHz}$ |  | - | 70.6 | - | dB |
|  |  | DAC output buffer OFF, $\mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}$, no $\mathrm{R}_{\mathrm{L}}, 1 \mathrm{kHz}$, $\mathrm{BW}=500 \mathrm{kHz}$ |  | - | 72 | - |  |
| THD | Total harmonic distortion ${ }^{(6)}$ | DAC output buffer ON, $\mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}, \mathrm{R}_{\mathrm{L}} \geq 5 \mathrm{k} \Omega, 1 \mathrm{kHz}$ |  | - | $-79$ | - |  |
|  |  | DAC output buffer OFF, $\mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}$, no $\mathrm{R}_{\mathrm{L}}, 1 \mathrm{kHz}$ |  | - | $-81$ | - |  |
| SINAD | Signal-to-noise and distortion ratio ${ }^{(6)}$ | DAC output buffer ON, $\mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}, \mathrm{R}_{\mathrm{L}} \geq 5 \mathrm{k} \Omega, 1 \mathrm{kHz}$ |  | - | 70.1 | - |  |
|  |  | DAC output buffer OFF, $\mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}$, no $\mathrm{R}_{\mathrm{L}}, 1 \mathrm{kHz}$ |  | - | 71.5 | - |  |
| ENOB | Effective number of bits | DAC output buffer ON, $\mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}, \mathrm{R}_{\mathrm{L}} \geq 5 \mathrm{k} \Omega, 1 \mathrm{kHz}$ |  | - | 11.3 | - | bits |
|  |  | DAC output buffer OFF, $\mathrm{C}_{\mathrm{L}} \leq 50 \mathrm{pF}$, no $\mathrm{R}_{\mathrm{L}}, 1 \mathrm{kHz}$ |  | - | 11.6 | - |  |

1. Specified by design. Not tested in production.
2. Difference between two consecutive codes minus 1 LSB .
3. Difference between the value measured at code i and the value measured at code i on a line drawn between code 0 and last code 4095.
4. Difference between the value measured at code $(0 \times 001)$ and the ideal value.
5. Difference between the ideal transfer-function slope and the measured slope computed from code $0 \times 000$ and $0 \times F F F$ when the buffer is OFF, and from code giving 0.2 V and (VREF $+-0.2 \mathrm{~V}$ ) when the buffer is ON.
6. Signal is -0.5 dBFS with Fsampling $=1 \mathrm{MHz}$.# 5.3.25 Voltage reference buffer characteristics 

Table 117. VREFBUF characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions |  | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V_{\text {DDA }}$ | Analog supply voltage | Normal mode | VRS $=000$ | 1.8 | - | 3.6 | V |
|  |  |  | VRS $=001$ | 2.1 | - |  |  |
|  |  |  | VRS $=010$ | 2.4 | - |  |  |
|  |  |  | VRS $=011$ | 2.8 | - |  |  |
|  |  | Degraded mode ${ }^{(2)}$ | VRS $=000$ | 1.62 | - | 1.8 |  |
|  |  |  | VRS $=001$ |  | - | 2.1 |  |
|  |  |  | VRS $=010$ |  | - | 2.4 |  |
|  |  |  | VRS $=011$ |  | - | 2.8 |  |
| $\begin{aligned} & \mathrm{V}_{\text {REFBUF }} \\ & \text { OUT } \\ & \text { (3) } \end{aligned}$ | Voltage reference buffer output | Normal mode at $\mathrm{V}_{\mathrm{DDA}}=3 \mathrm{~V}$, $\mathrm{T}_{\mathrm{J}}=30^{\circ} \mathrm{C}$, $\mathrm{I}_{\text {load }}=10 \mu \mathrm{~A}$ | VRS $=000$ | 1.496 | 1.5 | 1.504 |  |
|  |  |  | VRS $=001$ | 1.795 | 1.8 | 1.805 |  |
|  |  |  | VRS $=010$ | 2.042 | 2.048 | 2.054 |  |
|  |  |  | VRS $=011$ | 2.493 | 2.5 | 2.507 |  |
|  |  | Degraded mode ${ }^{(2)}$ | VRS $=000$ | $\begin{gathered} \operatorname{Min}\left(\mathrm{~V}_{\mathrm{DDA}}-0.15 ; 1.496\right) \end{gathered}$ | - | 1.504 |  |
|  |  |  | VRS $=001$ | $\begin{gathered} \operatorname{Min}\left(\mathrm{~V}_{\mathrm{DDA}}-0.15 ; 1.795\right) \end{gathered}$ | - | 1.805 |  |
|  |  |  | VRS $=010$ | $\begin{gathered} \operatorname{Min}\left(\mathrm{~V}_{\mathrm{DDA}}-0.15 ; 2.042\right) \end{gathered}$ | - | 2.054 |  |
|  |  |  | VRS $=011$ | $\begin{gathered} \operatorname{Min}\left(\mathrm{~V}_{\mathrm{DDA}}-0.15 ; 2.493\right) \end{gathered}$ | - | 2.507 |  |
| TRIM | Trim step | - |  | 0.1 | 0.175 | 0.25 | \% |
| $\mathrm{C}_{\mathrm{L}}$ | Load capacitor ${ }^{(4)}$ | - |  | 0.5 | 1.10 | 1.50 | $\mu \mathrm{F}$ |
| esr | $\mathrm{C}_{\mathrm{L}}$ equivalent serial resistor | - |  | - | - | 2 | $\Omega$ |
| $\mathrm{I}_{\text {load }}$ | Static load current | - |  | - | - | 4 | mA |
| $R_{P D}$ | Pull-down resistance | - |  | - | - | 400 | $\Omega$ |
| $\mathrm{I}_{\text {line_reg }}$ | Line regulation | $\begin{aligned} & \mathrm{V}_{\text {DDAmin }} \leq \mathrm{V}_{\mathrm{DDA}} \leq 3.6 \mathrm{~V}, \\ & \text { Normal mode, } \\ & 500 \mu \mathrm{~A} \leq \mathrm{I}_{\text {load }} \leq 4 \mathrm{~mA} \end{aligned}$ |  | $\pm 0.016$ | $\pm 0.033$ | $\pm 0.053$ | \% |
| $\mathrm{I}_{\text {load_reg }}$ | Load regulation ${ }^{(5)}$ | Normal mode, $500 \mu \mathrm{~A} \leq \mathrm{I}_{\text {load }} \leq 4 \mathrm{~mA}$ |  | - | 50 | 400 | $\begin{gathered} \mathrm{ppm} / \\ \mathrm{mA} \end{gathered}$ |
| $\mathrm{T}_{\text {Coeff }}$ | Temperature coefficient | $-40^{\circ} \mathrm{C}<\mathrm{T}_{\mathrm{J}}<+130^{\circ} \mathrm{C}$ |  | - | - | $\begin{gathered} \mathrm{T}_{\text {coeff_vrefint }} \\ +50 \end{gathered}$ | $\begin{gathered} \mathrm{ppm} / \\ { }^{\circ} \mathrm{C} \end{gathered}$ |
| PSRR | Power supply rejection | DC |  | - | 65 | - | dB |
|  |  | 100 kHz |  | - | 30 | - |  |Table 117. VREFBUF characteristics ${ }^{(1)}$ (continued)

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{\text {START }}$ | Startup time | $\mathrm{C}_{\mathrm{L}}=0.5 \mu \mathrm{~F}$ | - | 110 | 200 | $\mu \mathrm{s}$ |
|  |  | $\mathrm{C}_{\mathrm{L}}=1.1 \mu \mathrm{~F}$ | - | 240 | 350 |  |
|  |  | $\mathrm{C}_{\mathrm{L}}=1.5 \mu \mathrm{~F}$ | - | 320 | 500 |  |
| $t_{\text {INRUSH }}$ | Control of DC current drive on $\mathrm{V}_{\text {REFBUF_ }}$ OUT during startup phase ${ }^{(6)}$ | - | - | 8 | 11 | mA |
| $\begin{aligned} & \mathrm{I}_{\text {DDA }} \\ & \text { (VREFBUF } \\ & \text { ) } \end{aligned}$ | VREFBUF consumption from $\mathrm{V}_{\text {DDA }}$ | $\mathrm{I}_{\text {load }}=0 \mu \mathrm{~A}$ | - | 14 | 18 | $\mu \mathrm{A}$ |
|  |  | $\mathrm{I}_{\text {load }}=500 \mu \mathrm{~A}$ | - | 16 | 20 |  |
|  |  | $\mathrm{I}_{\text {load }}=4 \mathrm{~mA}$ | - | 42 | 50 |  |

1. Specified by design and not tested in production, unless otherwise specified.
2. In degraded mode, the voltage reference buffer can not accurately maintain the output voltage ( $\mathrm{V}_{\text {DDA }}$ - drop voltage).
3. Evaluated by characterization. Not tested in production.
4. The capacitive load must include a 100 nF capacitor in order to cut off the high-frequency noise.
5. The load regulation value only takes into account the die and package resistance. The parasitic resistance on PCB degrades this value.
6. To correctly control the VREFBUF inrush current during startup phase and scaling change, the $\mathrm{V}_{\text {DDA }}$ voltage must be in the range of $[1.8 \mathrm{~V}-3.6 \mathrm{~V}],[2.1 \mathrm{~V}-3.6 \mathrm{~V}],[2.4 \mathrm{~V}-3.6 \mathrm{~V}]$ and $[2.8 \mathrm{~V}-3.6 \mathrm{~V}]$ for VRS $=000,001,010$ and 011 respectively.

Figure 42. $\mathrm{V}_{\text {REFBUF OUT }}$ versus temperature (VRS $=000$ )
![img-61.jpeg](img-61.jpeg)Figure 43. $\mathrm{V}_{\text {REFBUF OUT }}$ versus temperature (VRS = 001)
![img-62.jpeg](img-62.jpeg)

Figure 44. $\mathrm{V}_{\text {REFBUF OUT }}$ versus temperature (VRS = 010)
![img-63.jpeg](img-63.jpeg)

Figure 45. $\mathrm{V}_{\text {REFBUF OUT }}$ versus temperature (VRS = 011)
![img-64.jpeg](img-64.jpeg)# 5.3.26 Comparator characteristics 

Table 118. COMP characteristics ${ }^{(1)(2)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V_{\text {DDA }}$ | Analog supply voltage for COMP ON | - | 1.58 | - | 3.6 | V |
| $V_{\text {IN }}$ | Comparator input voltage range | - | 0 | - | $V_{\text {DDA }}$ |  |
| $V_{\text {REFINT }}{ }^{(3)}$ | Scaler input voltage | - | (3) |  |  |  |
| $V_{S C}$ | Scaler offset voltage | - | - | $\pm 5$ | $\pm 10$ | mV |
| $\mathrm{t}_{\text {DDA(SCALER) }}$ | Scaler static consumption from $V_{\text {DDA }}$ | Scaler bridge disabled ${ }^{(4)}$ | - | 0.20 | 0.25 | $\mu \mathrm{A}$ |
|  |  | Scaler bridge enabled ${ }^{(5)}$ | - | 0.7 | 1 |  |
| $\mathrm{t}_{\text {START_SCALER }}$ | Scaler startup time | - | - | 130 | 220 | $\mu \mathrm{s}$ |
| $t_{\text {START }}$ | Comparator startup time to reach propagation delay specification | High-speed mode | - | - | 5 |  |
|  |  | Medium mode | - | - | 25 |  |
|  |  | Ultra-low-power mode | - | - | 80 |  |
| $\mathrm{t}_{\mathrm{D}}{ }^{(6)}$ | Propagation delay for 200 mV step with 100 mV overdrive | High-speed mode | - | 40 | 100 | ns |
|  |  | Medium mode | - | 0.5 | 1 | $\mu \mathrm{s}$ |
|  |  | Ultra-low-power mode | - | 2 | 7 |  |
| $V_{\text {offset }}$ | Comparator offset error | Full common mode range | - | $\pm 5$ | $\pm 20$ | mV |
| $V_{\text {hys }}$ | Comparator hysteresis | No hysteresis | - | 0 | - |  |
|  |  | Low hysteresis | - | 15 | - |  |
|  |  | Medium hysteresis | - | 30 | - |  |
|  |  | High hysteresis | - | 45 | - |  |
| $t_{\text {bias }}$ | Comparator input bias current | - | (7) |  |  | nA |
| $t_{\text {DDA(COMP) }}$ | Comparator consumption from $V_{\text {DDA }}$ | High-speed mode, static | - | 48 | 90 | $\mu \mathrm{A}$ |
|  |  | High-speed mode, with 50 kHz , $\pm 100 \mathrm{mV}$ overdrive square signal | - | 50 | - |  |
|  |  | Medium mode, static | - | 3 | 6 |  |
|  |  | Medium mode, with $50 \mathrm{kHz}, \pm 100 \mathrm{mV}$ overdrive square signal | - | 3.75 | - |  |
|  |  | Ultra-low-power mode, static | - | 0.3 | 1 |  |
|  |  | Ultra-low-power mode, with 50 kHz , $\pm 100 \mathrm{mV}$ overdrive square signal | - | 0.65 |  |  |

1. Specified by design and not tested in production, unless otherwise specified.
2. The input capacitance is negligible compared to the I/O capacitance.
3. Refer to Table 37: Embedded internal voltage reference.
4. No $V_{\text {REFINT }}$ division, includes only buffer consumption.
5. $\mathrm{V}_{\text {REFINT }}$ division, includes resistor bridge and buffer consumption.6. Evaluated by characterization. Not tested in production.
7. Mostly I/O leakage when used in analog mode. Refer to $\mathrm{I}_{\mathrm{lag}}$ parameter in Table 95: I/O static characteristics.

# 5.3.27 Operational amplifiers characteristics 

Table 119. OPAMP characteristics ${ }^{(1)(2)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $V_{\text {DDA }}$ | Analog supply voltage range for OPAMP ON | - | 1.60 | - | 3.6 | V |
| CMIR | Common mode input range | - | 0 | - | $V_{\text {DDA }}$ |  |
| VI $_{\text {OFFSET }}$ | Input offset voltage | $\mathrm{T}_{\mathrm{J}}=30^{\circ} \mathrm{C}$, no load on output, <br> Normal mode | - | - | $\pm 3$ | mV |
|  |  | $\mathrm{T}_{\mathrm{J}}=30^{\circ} \mathrm{C}$, no load on output, Low-power mode | - | - | $\pm 3$ |  |
|  |  | All voltages and temperature, Normal mode | - | - | $\pm 7$ |  |
|  |  | All voltages and temperature, Low-power mode | - | - | $\pm 11.5$ |  |
| $\Delta \mathrm{VI}_{\text {OFFSET }}$ | Input offset voltage drift over temperature | Normal mode | - | $\pm 7$ | - | $\mu \mathrm{V} /{ }^{\circ} \mathrm{C}$ |
|  |  | Low-power mode | - | $\pm 15$ | - |  |
| TRIMOFFSETP <br> TRIMLPOFFSETP | Offset trim step at low common input voltage $\left(0.1 \times V_{\text {DDA }}\right)$ | - | - | 1.05 | 1.25 | mV |
| TRIMOFFSETN <br> TRIMLPOFFSETN | Offset trim step at high common input voltage $\left(0.9 \times V_{\text {DDA }}\right)$ | - | - | 1.05 | 1.25 |  |
| $\mathrm{I}_{\text {LOAD }}$ | Drive current | Normal mode | - | - | 500 | $\mu \mathrm{A}$ |
|  |  | Low-power mode | - | - | 100 |  |
| $\mathrm{I}_{\text {LOAD_PGA }}$ | Drive current in PGA mode | Normal mode | - | - | 450 |  |
|  |  | Low-power mode | - | - | 50 |  |
| $R_{\text {LOAD }}$ | Resistive load (connected to VSSA or VDDA) | Normal mode | 3.9 | - | - | kD |
|  |  | Low-power mode | 20 | - | - |  |
| $\mathrm{C}_{\text {LOAD }}$ | Capacitive load | - | - | - | 50 | pF |
| CMRR | Common mode rejection ratio | Normal mode | - | 79 | - | dB |
|  |  | Low-power mode | - | 69 | - |  |
| PSRR | Power supply rejection ratio | Normal mode | $\begin{aligned} & \mathrm{C}_{\text {LOAD }} \leq 50 \mathrm{pF}, \\ & \mathrm{R}_{\text {LOAD }} \geq 3.9 \mathrm{k} \Omega^{(3)}, \\ & \mathrm{DC} \end{aligned}$ | 35 | 75 | - | dB |
|  |  | Low-power mode | $\begin{aligned} & \mathrm{C}_{\text {LOAD }} \leq 50 \mathrm{pF}, \\ & \mathrm{R}_{\text {LOAD }} \geq 20 \mathrm{k} \Omega^{(3)}, \\ & \mathrm{DC} \end{aligned}$ | 32 | 69 | - |Table 119. OPAMP characteristics ${ }^{(1)(2)}$ (continued)

| Symbol | Parameter | Conditions |  | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| GBW | Gain bandwidth product | Normal mode |  | 0.4 | 2 | 3.1 | MHz |
|  |  | Low-power mode |  | 0.23 | 0.5 | 0.76 |  |
| $\mathrm{SR}^{(3)}$ | Slew rate (from 10\% and $90 \%$ of output voltage) | Normal mode | Standard speed mode <br> (OPAHSM $=0$ ) | 0.5 | 1 | 3.2 | $\mathrm{V} / \mu \mathrm{s}$ |
|  |  | Low-power mode |  | 0.14 | 0.25 | 0.75 |  |
|  |  | Normal mode | High speed mode (OPAHSM = 1) | 1.4 | 3.2 | 5.6 |  |
|  |  | Low-power mode |  | 0.38 | 0.82 | 1.5 |  |
| AO | Open loop gain | Normal mode |  | 72 | 105 | - | dB |
|  |  | Low-power mode |  | 77 | 106 | - |  |
| $\varphi \mathrm{m}$ | Phase margin | Normal mode |  | 54 | 67 | - | " |
|  |  | Low-power mode |  | 54 | 65 | - |  |
| GM | Gain margin | Normal mode |  | - | 9 | - | dB |
|  |  | Low-power mode |  | - | 17 | - |  |
| $\mathrm{V}_{\text {OHSAT }}{ }^{(3)}$ | High saturation voltage | Normal mode | $\mathrm{I}_{\text {LOAD }}$ max or $\mathrm{R}_{\text {LOAD }}$ min, Input at $\mathrm{V}_{\text {DDA }}$ | $\begin{aligned} & \mathrm{V}_{\text {DDA }} \\ & -100 \end{aligned}$ | - | - | mV |
|  |  | Low-power mode |  | $\begin{aligned} & \mathrm{V}_{\text {DDA }} \\ & -50 \end{aligned}$ | - | - |  |
| $\mathrm{V}_{\text {OLSAT }}{ }^{(3)}$ | Low saturation voltage | Normal mode | $\mathrm{I}_{\text {LOAD }}$ max or $\mathrm{R}_{\text {LOAD }}$ min, Input at 0 V | - | - | 100 |  |
|  |  | Low-power mode |  | - | - | 50 |  |
| IWAKEUP | Wake-up time from OFF state | Normal mode | $\begin{aligned} & \mathrm{C}_{\text {LOAD }} \leq 50 \mathrm{pF}, \\ & \mathrm{R}_{\text {LOAD }} \geq 3.9 \mathrm{k} \Omega \text {, } \end{aligned}$ | - | 4 | 10 | $\mu \mathrm{s}$ |
|  |  | Low-power mode | $\begin{aligned} & \mathrm{C}_{\text {LOAD }} \leq 50 \mathrm{pF}, \\ & \mathrm{R}_{\text {LOAD }} \geq 20 \mathrm{k} \Omega \text {, } \end{aligned}$ follower config. | - | 20 | 40 |  |
| $\mathrm{I}_{\text {bias }}$ | OPAMP input bias current | General purpose input (all packages except UFBGA) |  | - | - | (4) | nA |
|  |  | Dedicated input (UFBGA only) | $\begin{aligned} & \mathrm{T}_{\mathrm{J}} \leq 75^{\circ} \mathrm{C} \\ & \mathrm{~T}_{\mathrm{J}} \leq 85^{\circ} \mathrm{C} \end{aligned}$ | - | - | 7 |  |
|  |  |  |  | - | - | 9 |  |
|  |  |  | $\mathrm{T}_{\mathrm{J}} \leq 105^{\circ} \mathrm{C}$ | - | - | 18 |  |
|  |  |  | $\mathrm{T}_{\mathrm{J}} \leq 125^{\circ} \mathrm{C}$ | - | - | 25 |  |Table 119. OPAMP characteristics ${ }^{(1)(2)}$ (continued)

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| PGA gain ${ }^{(3)}$ | Non-inverting gain value | PGA_GAIN[1:0] = 00 | - | 2 | - | - |
|  |  | PGA_GAIN[1:0] = 01 | - | 4 | - |  |
|  |  | PGA_GAIN[1:0] = 10 | - | 8 | - |  |
|  |  | PGA_GAIN[1:0] = 11 | - | 16 | - |  |
| Rnetwork | R2/R1 internal resistance values in non-inverting PGA mode ${ }^{(5)}$ | PGA gain $=2$ | - | 80/80 | - | $\mathrm{k} \Omega /$ <br> $\mathrm{k} \Omega$ |
|  |  | PGA gain $=4$ | - | 120/40 | - |  |
|  |  | PGA gain $=8$ | - | 140/20 | - |  |
|  |  | PGA gain $=16$ | - | 150/10 | - |  |
| Delta R | Resistance variation (R1 or R2) | - | $-18$ | - | 18 | \% |
| PGA gain error | PGA gain error | - | $-1$ | - | 1 |  |
| PGA BW | PGA bandwidth for different non inverting gain | PGA gain $=2$ | - | GBW/2 | - | MHz |
|  |  | PGA gain $=4$ | - | GBW/4 | - |  |
|  |  | PGA gain $=8$ | - | GBW/8 | - |  |
|  |  | PGA gain $=16$ | - | GBW/16 | - |  |
| en | Voltage noise density | Normal mode | At 1 kHz , output loaded with $3.9 \mathrm{k} \Omega$ | - | 220 | - | $\begin{gathered} \mathrm{nV} \\ / \sqrt{ } \mathrm{Hz} \end{gathered}$ |
|  |  | Low-power mode | At 1 kHz , output loaded with $20 \mathrm{k} \Omega$ | - | 350 | - |
|  |  | Normal mode | At 10 kHz , output loaded with $3.9 \mathrm{k} \Omega$ | - | 190 | - |
|  |  | Low-power mode | at 10 kHz , output loaded with $20 \mathrm{k} \Omega$ | - | 210 | - |
| $\mathrm{I}_{\text {DDA(OPAMP) }}$ | OPAMP consumption from $\mathrm{V}_{\text {DDA }}$ | Normal mode | no load, quiescent mode, standard speed | - | 130 | 190 | $\mu \mathrm{A}$ |
|  |  | Low-power mode |  | - | 40 | 58 |  |
|  |  | Normal mode | no load, quiescent mode, high-speed mode | - | 138 | 205 |  |
|  |  | Low-power mode |  | - | 42 | 60 |  |

1. Specified by design and not tested in production, unless otherwise specified.
2. OPA_RANGE must be set to 1 in OPAMP1_CSR.
3. Evaluated by characterization. Not tested in production.
4. Mostly I/O leakage when used in analog mode. Refer to $\mathrm{I}_{\text {leg }}$ parameter in Table 95: I/O static characteristics.
5. R2 is the internal resistance between the OPAMP output and the OPAMP inverting input. R1 is the internal resistance between the OPAMP inverting input and ground. PGA gain $=1+\mathrm{R} 2 / \mathrm{R} 1$.Figure 46. OPAMP voltage noise density, normal mode, $R_{\text {LOAD }}=3.9 \mathrm{k} \Omega$
![img-65.jpeg](img-65.jpeg)

Figure 47. OPAMP voltage noise density, low-power mode, $R_{\text {LOAD }}=20 \mathrm{k} \Omega$
![img-66.jpeg](img-66.jpeg)

# 5.3.28 Temperature and backup domain supply thresholds monitoring 

The temperature and backup domain supply monitoring characteristics are provided in the technical note STM32U54xxx/STM32U58xxx/STM32U5Axxx/STM32U5Gxxx MCUs for PCI products (TN1333) (NDA required).# 5.3.29 ADF/MDF characteristics 

Unless otherwise specified, the parameters given in the table below are derived from tests performed under the ambient temperature, $\mathrm{f}_{\mathrm{AHB}}$ frequency and $\mathrm{V}_{\mathrm{DD}}$ supply voltage conditions summarized in Table 33, with the following configuration:

- Output speed set to OSPEEDRy[1:0] = 10
- Capacitive load $C_{L}=30 \mathrm{pF}$
- Measurement points done at $0.5 \times V_{D D}$ level
- I/O compensation cell activated
- HSLV activated when $\mathrm{V}_{\mathrm{DD}} \leq 2.7 \mathrm{~V}$
- Voltage scaling range 1

Refer to Section 5.3.15: I/O port characteristics for more details on the input/output alternate function characteristics.

Table 120. ADF characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $f_{C C K I}$ | Input clock frequency via ADF_CCK[1:0] pin, in SLAVE SPI mode | $1.71 \leq V_{D D} \leq 3.6 \mathrm{~V}$ | - | - | 25 | MHz |
| $f_{\text {CCKO }}$ | Output clock frequency in MASTER SPI mode |  | - | - | 25 |  |
| $f_{\text {CCKOLF }}$ | Output clock frequency in LF_MASTER SPI mode |  | - | - | 5 |  |
| $f_{\text {SYMB }}$ | Input symbol rate in Manchester mode |  | - | - | 20 |  |
| $\begin{aligned} & \mathrm{f}_{\text {HCCKI }} \\ & \mathrm{f}_{\text {LCCKI }} \end{aligned}$ | ADF_CCK[1:0] input clock high and low time | In SLAVE SPI mode | $2 \times$ <br> Tadf_proc_ck ${ }^{(2)}$ | - | - | ns |
| $\begin{aligned} & \mathrm{f}_{\text {HCCKO }} \\ & \mathrm{f}_{\text {LCCKO }} \end{aligned}$ | ADF_CCK[1:0] output clock high and low time | In MASTER SPI mode | $2 \times$ <br> Tadf_proc_ck | - | - |  |
| $\begin{aligned} & \mathrm{f}_{\text {HCCKOLF }} \\ & \mathrm{f}_{\text {LCCKOLF }} \end{aligned}$ | ADF_CCK[1:0] output clock high and low time | In LF_MASTER SPI mode | Tadf_proc_ck | - | - |  |
| $t_{\text {SUCCKI }}$ | Data setup time with respect to ADF_CCK[1:0] input | In SLAVE SPI mode: ADF_CCK[1:0] configured in input, measured on rising and falling edge | 4.5 | - | - |  |
| $t_{\text {HDCCKI }}$ | Data hold time with respect to ADF_CCK[1:0] input |  | 1 | - | - |  |
| $t_{\text {SUCCKO }}$ | Data setup time with respect to ADF_CCK[1:0] output | In MASTER SPI mode: ADF_CCK[1:0] configured in output, measured on rising and falling edge | 5.5 | - | - |  |
| $t_{\text {HDCCKO }}$ | Data hold time with respect to ADF_CCK[1:0] output |  | 0 | - | - |  |
| $t_{\text {SUCCKOLF }}$ | Data setup time with respect to ADF_CCK[1:0] output | In LF_MASTER SPI mode: ADF_CCK[1:0] configured in output, measured on rising and falling edge | 19.5 | - | - | ns |
| $t_{\text {HDCCKOLF }}$ | Data hold time with respect to ADF_CCK[1:0] output |  | 0 | - | - |  |

1. Evaluated by characterization. Not tested in production.
2. Tadf_proc_ck is the period of the ADF processing clock.Figure 48. ADF timing diagram
![img-67.jpeg](img-67.jpeg)

Table 121. MDF characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $f_{C K I}$ | Input clock frequency via MDF_CKIx pin, in SLAVE SPI mode | $1.71 \leq V_{D D} \leq 3.6 \mathrm{~V}$ | - | - | 25 | MHz |
| $f_{\text {CCKI }}$ | Input clock frequency via MDF_CCK[1:0] pin, in SLAVE SPI mode |  | - | - | 25 |  |
| $f_{\text {CCKO }}$ | Output clock frequency in MASTER SPI mode |  | - | - | 25 |  |
| $f_{\text {CCKOLF }}$ | Output clock frequency in LF_MASTER SPI mode |  | - | - | 5 |  |
| $f_{\text {SYMB }}$ | Input symbol rate in Manchester mode |  | - | - | 20 |  |
| $t_{\text {HCKI }} t_{\text {LCKI }}$ | MDF_CKIx input clock high and low time | In SLAVE SPI mode | $2 \times$ <br> Tmdf_proc_ck ${ }^{(2)}$ | - | - | ns |
| $t_{\text {HCCKI }}$ <br> $t_{\text {LCCKI }}$ | MDF_CCK[1:0] input clock high and low time | In SLAVE SPI mode | $2 \times$ <br> Tmdf_proc_ck | - | - |  |
| $t_{\text {HCCKO }}$ <br> $t_{\text {LCCKO }}$ | MDF_CCK[1:0] output clock high and low time | In MASTER SPI mode | $2 \times$ <br> Tmdf_proc_ck | - | - |  |
| $t_{\text {HCCKOLF }}$ <br> $t_{\text {LCCKOLF }}$ | MDF_CCK[1:0] output clock high and low time | In LF_MASTER SPI mode | Tmdf_proc_ck | - | - |  |Table 121. MDF characteristics ${ }^{(1)}$ (continued)

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{\text {SUCKI }}$ | Data setup time with respect to MDF_CKIx input | In SLAVE SPI mode, measured on rising and falling edge | 1.5 | - | - | ns |
| $t_{\text {HDCKI }}$ | Data hold time with respect to MDF_CKIx input |  | 0 | - | - |  |
| $t_{\text {SUCCKI }}$ | Data setup time with respect to MDF_CCK[1:0] input | In SLAVE SPI mode: MDF_CCK[1:0] configured in input, measured on rising and falling edge | 1.5 | - | - |  |
| $t_{\text {HDCCKI }}$ | Data hold time with respect to MDF_CCK[1:0] input |  | 0.5 | - | - |  |
| $t_{\text {SUCCKO }}$ | Data setup time with respect to MDF_CCK[1:0] output | In MASTER SPI mode: MDF_CCK[1:0] configured in output, measured on rising and falling edge | 3.5 | - | - |  |
| $t_{\text {HDCCKO }}$ | Data hold time with respect to MDF_CCK[1:0] output |  | 1.5 | - | - |  |
| $t_{\text {SUCCKOLF }}$ | Data setup time with respect to MDF_CCK[1:0] output | In LF_MASTER SPI mode, MDF_CCK[1:0] configured in output, measured on rising and falling edge | 19.5 | - | - |  |
| $t_{\text {HDCCKOLF }}$ | Data hold time with respect to MDF_CCK[1:0] output |  | 0 | - | - |  |

1. Evaluated by characterization. Not tested in production.
2. Tmdf_proc_ck is the period of the MDF processing clock.

Figure 49. MDF timing diagram
![img-68.jpeg](img-68.jpeg)# 5.3.30 DCMI characteristics 

Unless otherwise specified, the parameters given in the table below are derived from tests performed under the ambient temperature, $f_{\text {HCLK }}$ frequency and $V_{D D}$ supply voltage summarized in Table 33, with the following configuration:

- Output speed set to OSPEEDRy[1:0] = 10
- DCMI_PIXCLK polarity: falling
- DCMI_VSYNC and DCMI_HSYNC polarity: high
- Data formats: 14 bits
- Capacitive load $C_{L}=30 \mathrm{pF}$
- Measurement points done at $0.5 \times V_{D D}$ level
- I/O compensation cell activated
- HSLV activated when $V_{D D} \leq 2.7 \mathrm{~V}$
- Voltage scaling range 1

Table 122. DCMI characteristics ${ }^{(1)}$

| Symbol | Parameter | Min | Max | Unit |
| :--: | :-- | :--: | :--: | :--: |
| - | Frequency ratio DCMI_PIXCLK/ | - | 0.4 | - |
| DCMI_PIXCLK | Pixel clock input | - | 64 | MHz |
| $\mathrm{D}_{\text {PIXEL }}$ | Pixel clock input duty cycle | 30 | 70 | $\%$ |
| $\mathrm{t}_{\text {su(DATA) }}$ | Data input setup time | 2 | - | ns |
| $\mathrm{t}_{\text {h(DATA) }}$ | Data hold time | 1 | - |  |
| $\mathrm{t}_{\text {su(HSYNC) }}$ <br> $\mathrm{t}_{\text {su(VSYNC) }}$ | DCMI_HSYNC and DCMI_VSYNC input setup times | 2 | - |  |
| $\mathrm{t}_{\text {h(HSYNC) }}$ <br> $\mathrm{t}_{\text {h(VSYNC) }}$ | DCMI_HSYNC and DCMI_VSYNC input hold times | 1 | - |  |

1. Evaluated by characterization. Not tested in production.

Figure 50. DCMI timing diagram
![img-69.jpeg](img-69.jpeg)# 5.3.31 PSSI characteristics 

Unless otherwise specified, the parameters given in the table below are derived from tests performed under the ambient temperature, $\mathrm{f}_{\mathrm{HCLK}}$ frequency and $\mathrm{V}_{\mathrm{DD}}$ supply voltage summarized in Table 33, with the following configuration:

- Output speed set to OSPEEDRy[1:0] = 10
- PSSI_PDCK polarity: falling
- PSSI_RDY and PSSI_DE polarity: low
- Bus width: 16 lines
- Data width: 32 bits
- Capacitive load $C_{L}=30 \mathrm{pF}$
- Measurement points done at $0.5 \times V_{D D}$ level
- I/O compensation cell activated
- HSLV activated when $\mathrm{V}_{\mathrm{DD}} \leq 2.7 \mathrm{~V}$
- Voltage scaling range 1

Table 123. PSSI transmit characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: |
| - | Frequency ratio DCMI_PDCK/f $_{\text {HCLK }}$ | - | - | 0.4 | - |
| PSSI_PDCK | PSSI clock input | $2.7 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | - | $64^{(2)}$ | MHz |
|  |  | $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | - | $47^{(2)}$ |  |
| $D_{\text {PIXEL }}$ | PSSI clock input duty cycle | - | 30 | 70 | \% |
| $\mathrm{t}_{\text {OV(DATA) }}$ | Data output valid time | $2.7 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | - | 14 | ns |
|  |  | $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | - | 21 |  |
| $\mathrm{t}_{\mathrm{OH} \text { (DATA) }}$ | Data output hold time | $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | 7 | - |  |
| $\mathrm{t}_{\mathrm{OV}(\mathrm{DE})}$ | DE output valid time |  | - | 12.5 |  |
| $\mathrm{t}_{\mathrm{OH}(\mathrm{DE})}$ | DE output hold time |  | 6 | - |  |
| $\mathrm{t}_{\text {SU(RDY) }}$ | RDY input setup time | $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | 0 | - |  |
| $\mathrm{t}_{\mathrm{H}(\mathrm{RDY})}$ | RDY input hold time |  | 0 | - |  |

1. Evaluated by characterization. Not tested in production.
2. This maximal frequency does not consider receiver setup and hold timings.Figure 51. PSSI transmit timing diagram
![img-70.jpeg](img-70.jpeg)

Table 124. PSSI receive characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: |
| - | Frequency ratio DCMI_PDCK/fHCLK | - | - | 0.4 | - |
| PSSI_PDCK | PSSI clock input | $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | - | 64 | MHz |
| $D_{\text {PIXEL }}$ | PSSI clock input duty cycle | - | 30 | 70 | \% |
| $\mathrm{t}_{\text {SU(DATA) }}$ | Data input setup time | $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | 2 | - | ns |
| $\mathrm{t}_{\mathrm{H}(\text { DATA) }}$ | Data input hold time |  | 1.5 | - |  |
| $\mathrm{t}_{\text {SU(DE) }}$ | DE input setup time |  | 0.5 | - |  |
| $t_{H(\text { DE })}$ | DE input hold time |  | 2 | - |  |
| $t_{O V(R D Y)}$ | RDY output valid time |  | - | 12 |  |
| $t_{O H(R D Y)}$ | RDY output hold time |  | 6 | - |  |

1. Evaluated by characterization. Not tested in production.Figure 52. PSSI receive timing diagram
![img-71.jpeg](img-71.jpeg)

# 5.3.32 Timer characteristics 

The parameters given in the following tables are specified by design, not tested in production.
Refer to Section 5.3.15: I/O port characteristics for details on the input/output alternate function characteristics (output compare, input capture, external clock, PWM output).

Table 125. TIMx ${ }^{(1)}$ characteristics

| Symbol | Parameter | Conditions | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{\text {res(TIM) }}$ | Timer resolution time | - | 1 | - | $t_{\text {TIMxCLK }}$ |
|  |  | $t_{\text {TIMxCLK }}=160 \mathrm{MHz}$ | 6.25 | - | ns |
| $f_{\text {EXT }}$ | Timer external clock frequency on CH1 to CH4 | - | 0 | $f_{\text {TIMxCLK }} / 2$ | MHz |
|  |  | $t_{\text {TIMxCLK }}=160 \mathrm{MHz}$ | 0 | 80 |  |
| Res $_{\text {TIM }}$ | Timer resolution | TIMx (except TIM2/3/4/5) | - | 16 | bit |
|  |  | TIM2/3/4/5 | - | 32 |  |
| $t_{\text {COUNTER }}$ | 16-bit counter clock period | - | 1 | 65536 | $t_{\text {TIMxCLK }}$ |
|  |  | $t_{\text {TIMxCLK }}=160 \mathrm{MHz}$ | 0.007 | 409.6 | $\mu \mathrm{s}$ |
| $t_{\text {MAX_COUNT }}$ | Maximum possible count with 32-bit counter | - | - | $65536 \times 65536$ | $t_{\text {TIMxCLK }}$ |
|  |  | $t_{\text {TIMxCLK }}=160 \mathrm{MHz}$ | - | 26.843 | s |

1. TIMx ${ }_{i}$ is used as a general term in which $x$ stands for $1,2,3,4,5,6,7,8,15,16$ or 17 .Table 126. IWDG min/max timeout period at $32 \mathrm{kHz}(\mathrm{LSI})^{(1)}$

| Prescaler divider | PR[2:0] bits | Min timeout RL[11:0] = 0x000 | Max timeout RL[11:0] = 0xFFF | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $1 / 4$ | 0 | 0.125 | 512 | ms |
| $1 / 8$ | 1 | 0.250 | 1024 |  |
| $1 / 16$ | 2 | 0.500 | 2048 |  |
| $1 / 32$ | 3 | 1.0 | 4096 |  |
| $1 / 64$ | 4 | 2.0 | 8192 |  |
| $1 / 128$ | 5 | 4.0 | 16384 |  |
| $1 / 256$ | 6 or 7 | 8.0 | 32768 |  |

1. The exact timings still depend on the phasing of the APB interface clock versus the LSI clock, so that there is always a full RC period of uncertainty.

Table 127. WWDG min/max timeout value at 160 MHz (PCLK)

| Prescaler | WDGTB | Min timeout value | Max timeout value | Unit |
| :--: | :--: | :--: | :--: | :--: |
| 1 | 0 | 0.025 | 1.638 | ms |
| 2 | 1 | 0.051 | 3.276 |  |
| 4 | 2 | 0.102 | 6.553 |  |
| 8 | 3 | 0.204 | 13.107 |  |
| 16 | 4 | 0.409 | 26.214 |  |
| 32 | 5 | 0.819 | 52.428 |  |
| 46 | 6 | 1.177 | 75.366 |  |
| 128 | 7 | 3.276 | 209.715 |  |

# 5.3.33 FSMC characteristics 

Unless otherwise specified, the parameters given in the tables below are derived from tests performed under the ambient temperature, $f_{\text {HCLK }}$ frequency and $V_{D D}$ supply voltage conditions summarized in Table 33, with the following configuration:

- Output speed set to OSPEEDRy[1:0] = 10
- Capacitive load $C_{L}=30 \mathrm{pF}$, unless otherwise specified
- Measurement points done at $0.5 \times V_{D D}$ level
- I/O compensation cell activated
- HSLV activated when $V_{D D} \leq 2.7 \mathrm{~V}$
- Voltage scaling range 1

Refer to Section 5.3.15: I/O port characteristics for more details on the input/output characteristics.# Asynchronous waveforms and timings 

Figure 53 to Figure 56 represent asynchronous waveforms and Table 128 to Table 135 provide the corresponding timings. The results shown in these tables are obtained with the following FMC configuration:

- AddressSetupTime (ADDSET) $=0 \times 1$
- AddressHoldTime (ADDHLD) $=0 \times 1$
- ByteLaneSetup (NBLSET) $=0 \times 1$
- DataSetupTime (DATAST) $=0 \times 1$ (except for asynchronous NWAIT mode, DataSetupTime $=0 \times 5$ )
- DataHoldTime (DATAHLD) $=0 \times 1$ ( $0 \times 0$ for write operation)
- BusTurnAroundDuration $=0 \times 0$
- Capacitive load $C_{L}=30 \mathrm{pF}$

In all timing tables, the $T_{\text {HCLK }}$ is the HCLK clock period.
Figure 53. Asynchronous non-multiplexed SRAM/PSRAM/NOR read waveforms
![img-72.jpeg](img-72.jpeg)Table 128. Asynchronous non-multiplexed SRAM/PSRAM/NOR read timings ${ }^{(1)}$

| Symbol | Parameter | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $t_{w(N E)}$ | FMC_NE low time | $3 \times t_{\text {HCLK }}-1$ | $3 \times t_{\text {HCLK }}+1$ | ns |
| $t_{v(N O E} N E)$ | FMC_NEx low to FMC_NOE low | 0 | 5 |  |
| $t_{w(N O E)}$ | FMC_NOE low time | $2 \times t_{\text {HCLK }}-1$ | $2 \times t_{\text {HCLK }}+1$ |  |
| $t_{h(N E} N O E)$ | FMC_NOE high to FMC_NE high hold time | $T_{\text {HCLK }}$ | - |  |
| $t_{v(A} N E)$ | FMC_NEx low to FMC_A valid | - | 1.5 |  |
| $t_{h(A} N O E)$ | Address hold time after FMC_NOE high | $2 \times t_{\text {HCLK }}-1$ | - |  |
| $t_{\text {su(Data } N E)}$ | Data to FMC_NEx high setup time | $t_{\text {HCLK }}+15$ | - |  |
| $t_{\text {su(Data }}$ NOE) | Data to FMC_NOEx high setup time | 15 | - |  |
| $t_{h(\text { Data }}$ NOE) | Data hold time after FMC_NOE high | 0 | - |  |
| $t_{h(\text { Data } N E)}$ | Data hold time after FMC_NEx high | 0 | - |  |
| $t_{v(\text { NADV }}$ NE) | FMC_NEx low to FMC_NADV low | - | 1.5 |  |
| $t_{w(\text { NADV) }}$ | FMC_NADV low time | - | $T_{\text {HCLK }}+1$ |  |

1. Evaluated by characterization. Not tested in production.

Table 129. Asynchronous non-multiplexed SRAM/PSRAM/NOR read-NWAIT timings ${ }^{(1)}$

| Symbol | Parameter | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $t_{w(N E)}$ | FMC_NE low time | $8 \times t_{\text {HCLK }}-1$ | $8 \times t_{\text {HCLK }}+1$ |  |
| $t_{w(N O E)}$ | FMC_NWE low time | $7 \times t_{\text {HCLK }}-1$ | $7 \times t_{\text {HCLK }}+1$ |  |
| $t_{w(N W A I T)}$ | FMC_NWAIT ${ }^{(2)}$ low time | $t_{\text {HCLK }}$ | - | ns |
| $t_{\text {su }}$ (NWAIT_NE) | FMC_NWAIT valid before FMC_NEx high | $5 \times t_{\text {HCLK }}+9.5$ | - |  |
| $t_{h(N E}$ NWAIT) | FMC_NEx hold time after FMC_NWAIT invalid | $4 \times t_{\text {HCLK }}+10$ | - |  |

1. Evaluated by characterization. Not tested in production.
2. NWAIT pulse is equal to one HCLK cycle.Figure 54. Asynchronous non-multiplexed SRAM/PSRAM/NOR write waveforms
![img-73.jpeg](img-73.jpeg)

Table 130. Asynchronous non-multiplexed SRAM/PSRAM/NOR write timings ${ }^{(1)}$

| Symbol | Parameter | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $t_{w(N E)}$ | FMC_NE low time | $3 \times t_{\text {HCLK }}-1$ | $3 \times t_{\text {HCLK }}+1$ | ns |
| $t_{v(\text { NWE } \_N E)}$ | FMC_NEx low to FMC_NWE low | $t_{\text {HCLK }}-1$ | $t_{\text {HCLK }}+1$ |  |
| $t_{w(\text { NWE }}$ | FMC_NWE low time | $t_{\text {HCLK }}-0.5$ | $t_{\text {HCLK }}+0.5$ |  |
| $t_{h(N E \_N W E)}$ | FMC_NWE high to FMC_NE high hold time | $t_{\text {HCLK }}$ | - |  |
| $t_{v(A \_N E)}$ | FMC_NEx low to FMC_A valid | - | 1 |  |
| $t_{h(A \_N W E)}$ | Address hold time after FMC_NWE high | $t_{\text {HCLK }}-0.5$ | - |  |
| $t_{v(B L \_N E)}$ | FMC_NEx low to FMC_BL valid | - | 0.5 |  |
| $t_{h(B L \_N W E)}$ | FMC_BL hold time after FMC_NWE high | $t_{\text {HCLK }}-0.5$ | - |  |
| $t_{v(\text { Data } \_N E)}$ | FMC_NEx low to Data valid | - | $t_{\text {HCLK }}+2$ |  |
| $t_{h(\text { Data } \_N W E)}$ | Data hold time after FMC_NWE high | $t_{\text {HCLK }}$ | - |  |
| $t_{v(\text { NADV } \_N E)}$ | FMC_NEx low to FMC_NADV low | - | 2 |  |
| $t_{w(\text { NADV) }}$ | FMC_NADV low time | - | $t_{\text {HCLK }}+1$ |  |

1. Evaluated by characterization. Not tested in production.Table 131. Asynchronous non-multiplexed SRAM/PSRAM/NOR write-NWAIT timings ${ }^{(1)}$

| Symbol | Parameter | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $\mathrm{t}_{\mathrm{w}(\mathrm{NE})}$ | FMC_NE low time | $8 \times \mathrm{t}_{\mathrm{HCLK}}-1$ | $8 \times \mathrm{t}_{\mathrm{HCLK}}+1$ | ns |
| $\mathrm{t}_{\mathrm{w}(\mathrm{NWE})}$ | FMC_NWE low time | $6 \times \mathrm{t}_{\mathrm{HCLK}}-1$ | $6 \times \mathrm{t}_{\mathrm{HCLK}}+1$ |  |
| $\mathrm{t}_{\mathrm{su}(\mathrm{NWAIT} \_N E)}$ | FMC_NWAIT ${ }^{(2)}$ valid before FMC_NEx high | $5 \times \mathrm{t}_{\mathrm{HCLK}}+13$ | - |  |
| $\mathrm{t}_{\mathrm{h}(\mathrm{NE} \_N W A I T)}$ | FMC_NEx hold time after FMC_NWAIT invalid | $4 \times \mathrm{t}_{\mathrm{HCLK}}+12$ | - |  |

1. Evaluated by characterization. Not tested in production.
2. NWAIT pulse is equal to one HCLK cycle.

Figure 55. Asynchronous multiplexed PSRAM/NOR read waveforms
![img-74.jpeg](img-74.jpeg)Table 132. Asynchronous multiplexed PSRAM/NOR read timings ${ }^{(1)}$

| Symbol | Parameter | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $t_{w(N E)}$ | FMC_NE low time | $3 \times t_{\text {HCLK }}-1$ | $3 \times t_{\text {HCLK }}+1$ | ns |
| $t_{v(N O E \_N E)}$ | FMC_NEx low to FMC_NOE low | 0 | 5 |  |
| $t_{w(N O E)}$ | FMC_NOE low time | $2 \times t_{\text {HCLK }}-0.5$ | $2 \times t_{\text {HCLK }}+0.5$ |  |
| $t_{h(N E \_N O E)}$ | FMC_NOE high to FMC_NE high hold time | $t_{\text {HCLK }}$ | - |  |
| $t_{v(A \_N E)}$ | FMC_NEx low to FMC_A valid | - | 1.5 |  |
| $t_{v(\text { NADV } \_N E)}$ | FMC_NEx low to FMC_NADV low | 0 | 1.5 |  |
| $t_{w(\text { NADV) }}$ | FMC_NADV low time | $t_{\text {HCLK }}-0.5$ | $t_{\text {HCLK }}+1$ |  |
| $t_{h(A D \_N A D V)}$ | FMC_AD(address) valid hold time after FMC_NADV high) | $t_{\text {HCLK }}-4$ | - |  |
| $t_{h(A \_N O E)}$ | Address hold time after FMC_NOE high | $t_{\text {HCLK }}-1$ | - |  |
| $t_{\text {su(Data } \_N E)}$ | Data to FMC_NEx high setup time | $t_{\text {HCLK }}+15$ | - |  |
| $t_{\text {su(Data } \_N O E)}$ | Data to FMC_NOE high setup time | 15 | - |  |
| $t_{h(\text { Data } \_N E)}$ | Data hold time after FMC_NEx high | 0 | - | ns |
| $t_{h(\text { Data } \_N O E)}$ | Data hold time after FMC_NOE high | 0 | - |  |

1. Evaluated by characterization. Not tested in production.

Table 133. Asynchronous multiplexed PSRAM/NOR read-NWAIT timings ${ }^{(1)}$

| Symbol | Parameter | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $t_{w(N E)}$ | FMC_NE low time | $8 \times t_{\text {HCLK }}-1$ | $8 \times t_{\text {HCLK }}+1$ | ns |
| $t_{w(N O E)}$ | FMC_NOE low time | $7 \times t_{\text {HCLK }}-1$ | $7 \times t_{\text {HCLK }}+1$ |  |
| $t_{\text {su }(\text { NWAIT } \_N E)}$ | FMC_NWAIT ${ }^{(2)}$ valid before FMC_NEx high | $4 \times t_{\text {HCLK }}+9.5$ | - |  |
| $t_{h(N E \_N W A I T)}$ | FMC_NEx hold time after FMC_NWAIT invalid | $3 \times t_{\text {HCLK }}+10$ | - |  |

1. Evaluated by characterization. Not tested in production.
2. NWAIT pulse is equal to one HCLK cycle.Figure 56. Asynchronous multiplexed PSRAM/NOR write waveforms
![img-75.jpeg](img-75.jpeg)

Table 134. Asynchronous multiplexed PSRAM/NOR write timings ${ }^{(1)}$

| Symbol | Parameter | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $t_{w(N E)}$ | FMC_NE low time | $3 \times t_{\text {HCLK }}-1$ | $3 \times t_{\text {HCLK }}+1$ |  |
| $t_{v(\text { NWE } \_N E)}$ | FMC_NEx low to FMC_NWE low | $t_{\text {HCLK }}-1$ | $t_{\text {HCLK }}$ |  |
| $t_{w(N W E)}$ | FMC_NWE low time | $2 \times t_{\text {HCLK }}-0.5$ | $2 \times t_{\text {HCLK }}+1$ |  |
| $t_{h(N E \_N W E)}$ | FMC_NWE high to FMC_NE high hold time | $t_{\text {HCLK }}$ | - |  |
| $t_{v(A \_N E)}$ | FMC_NEx low to FMC_A valid | - | 1 |  |
| $t_{v(\text { NADV } \_N E)}$ | FMC_NEx low to FMC_NADV low | 0 | 2 |  |
| $t_{w(\text { NADV) }}$ | FMC_NADV low time | $t_{\text {HCLK }}-0.5$ | $t_{\text {HCLK }}+1$ | ns |
| $t_{h(A D \_N A D V)}$ | FMC_AD(adress) valid hold time after FMC_NADV high) | $t_{\text {HCLK }}-4.5$ | - |  |
| $t_{h(A \_N W E)}$ | Address hold time after FMC_NWE high | $t_{\text {HCLK }}-0.5$ | - |  |
| $t_{h(B L \_N W E)}$ | FMC_BL hold time after FMC_NWE high | $t_{\text {HCLK }}-0.5$ | - |  |
| $t_{v(B L \_N E)}$ | FMC_NEx low to FMC_BL valid | - | 0.5 |  |
| $t_{v(\text { Data_NADV) }}$ | FMC_NADV high to Data valid | - | $t_{\text {HCLK }}+2$ |  |
| $t_{h(\text { Data_NWE) }}$ | Data hold time after FMC_NWE high | $t_{\text {HCLK }}$ | - |  |

1. Evaluated by characterization. Not tested in production.Table 135. Asynchronous multiplexed PSRAM/NOR write-NWAIT timings ${ }^{(1)}$

| Symbol | Parameter | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $t_{w(N E)}$ | FMC_NE low time | $8 \times t_{\text {HCLK }}-1$ | $8 \times t_{\text {HCLK }}+1$ | ns |
| $t_{w(N W E)}$ | FMC_NWE low time | $6 \times t_{\text {HCLK }}-1$ | $6 \times t_{\text {HCLK }}+1$ |  |
| $t_{\text {su }}$ (NWAIT_NE) | FMC_NWAIT valid before FMC_NEx high | $5 \times t_{\text {HCLK }}+13$ | - |  |
| $t_{h(N E \_N W A I T)}$ | FMC_NEx hold time after FMC_NWAIT invalid | $4 \times t_{\text {HCLK }}+12$ | - |  |

1. Evaluated by characterization. Not tested in production.

# Synchronous waveforms and timings 

Figure 57 to Figure 60 represent synchronous waveforms and Table 136 to Table 139 provide the corresponding timings. The results shown in these tables are obtained with the following FMC configuration:

- BurstAccessMode = FMC_BurstAccessMode_Enable
- MemoryType = FMC_MemoryType_CRAM
- WriteBurst = FMC_WriteBurst_Enable
- CLKDivision = 1
- DataLatency $=1$ for NOR Flash; DataLatency $=0$ for PSRAM

In all timing tables, the $T_{\text {HCLK }}$ is the HCLK clock period.

- Maximum FMC_CLK $=80 \mathrm{MHz}$ for $2.7 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$, with $\mathrm{C}_{\mathrm{L}}=15 \mathrm{pF}$ and with $C_{L}=20 \mathrm{pF}$
- Maximum FMC_CLK $=80 \mathrm{MHz}$ for $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 1.9 \mathrm{~V}$ with $\mathrm{C}_{\mathrm{L}}=15 \mathrm{pF}$ and with $C_{L}=20 \mathrm{pF}$Figure 57. Synchronous multiplexed NOR/PSRAM read timings
![img-76.jpeg](img-76.jpeg)

Table 136. Synchronous multiplexed NOR/PSRAM read timings ${ }^{(1)(2)}$

| Symbol | Parameter | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $t_{w(C L K)}$ | FMC_CLK period | $2 \times t_{\text {HCLK }}-0.5$ | - | ns |
| $t_{d(C L K L-N E x L)}$ | FMC_CLK low to FMC_NEx low $(x=0 . .2)$ | - | 1 |  |
| $t_{d(C L K H \_N E x H)}$ | FMC_CLK high to FMC_NEx high $(x=0 . .2)$ | $t_{\text {HCLK }}-0.5$ | - |  |
| $t_{d(C L K L-N A D V L)}$ | FMC_CLK low to FMC_NADV low | - | 1.5 |  |
| $t_{d(C L K L-N A D V H)}$ | FMC_CLK low to FMC_NADV high | 1 | - |  |
| $t_{d(C L K L-A V)}$ | FMC_CLK low to FMC_Ax valid $(x=16 . .25)$ | - | 2.5 |  |
| $t_{d(C L K H-A I V)}$ | FMC_CLK high to FMC_Ax invalid $(x=16 . .25)$ | $t_{\text {HCLK }}-0.5$ | - |  |
| $t_{d(C L K L-N O E L)}$ | FMC_CLK low to FMC_NOE low | - | 1.5 |  |
| $t_{d(C L K H-N O E H)}$ | FMC_CLK high to FMC_NOE high | $t_{\text {HCLK }}+1$ | - |  |
| $t_{d(C L K L-A D V)}$ | FMC_CLK low to FMC_AD[15:0] valid | - | 2 |  |
| $t_{d(C L K L-A D I V)}$ | FMC_CLK low to FMC_AD[15:0] invalid | 0 | - |  |Table 136. Synchronous multiplexed NOR/PSRAM read timings ${ }^{(1)(2)}$ (continued)

| Symbol | Parameter | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $t_{\text {su(ADV-CLKH) }}$ | FMC_A/D[15:0] valid data before FMC_CLK high | 3 | - | ns |
| $t_{n(\text { CLKH-ADV) }}$ | FMC_A/D[15:0] valid data after FMC_CLK high | 4 | - |  |
| $t_{\text {su(NWAIT-CLKH) }}$ | FMC_NWAIT valid before FMC_CLK high | 1 | - |  |
| $t_{n(\text { CLKH-NWAIT) }}$ | FMC_NWAIT valid after FMC_CLK high | 2.5 | - |  |

1. Evaluated by characterization. Not tested in production.
2. Clock ratio $R=($ HCLK period $/$ FMC_CLK period).

Figure 58. Synchronous multiplexed PSRAM write timings
![img-77.jpeg](img-77.jpeg)

Table 137. Synchronous multiplexed PSRAM write timings ${ }^{(1)}$

| Symbol | Parameter | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $t_{w(C L K)}$ | FMC_CLK period, $2.7 \mathrm{~V} \leq \mathrm{VDD} \leq 3.6 \mathrm{~V}$ | $2 \times t_{\text {HCLK }}-0.5$ | - | ns |
| $t_{d(C L K L-N E x L)}$ | FMC_CLK low to FMC_NEx low $(x=0 . .2)$ | - | 2 |  |
| $t_{d(C L K H-N E x H)}$ | FMC_CLK high to FMC_NEx high $(x=0 . .2)$ | $t_{\text {HCLK }}+1.5$ | - |  |
| $t_{d(C L K L-N A D V L)}$ | FMC_CLK low to FMC_NADV low | - | 2 |  |Table 137. Synchronous multiplexed PSRAM write timings ${ }^{(1)}$ (continued)

| Symbol | Parameter | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $t_{d(C L K L-N A D V H)}$ | FMC_CLK low to FMC_NADV high | 1 | - | ns |
| $t_{d(C L K L-A V)}$ | FMC_CLK low to FMC_Ax valid $(x=16 . .25)$ | - | 3 |  |
| $t_{d(C L K H-A I V)}$ | FMC_CLK high to FMC_Ax invalid $(x=16 . .25)$ | $t_{\text {HCLK }}$ | - |  |
| $t_{d(C L K L-N W E L)}$ | FMC_CLK low to FMC_NWE low | - | 2.5 |  |
| $t_{d(C L K H-N W E H)}$ | FMC_CLK high to FMC_NWE high | $t_{\text {HCLK }}+1$ | - |  |
| $t_{d(C L K L-A D V)}$ | FMC_CLK low to FMC_AD[15:0] valid | - | 2 |  |
| $t_{d(C L K L-A D I V)}$ | FMC_CLK low to FMC_AD[15:0] invalid | 0 | - |  |
| $t_{d(C L K L-D A T A)}$ | FMC_A/D[15:0] valid data after FMC_CLK low | - | 3 |  |
| $t_{d(C L K L-N B L L)}$ | FMC_CLK low to FMC_NBL low | - | 2 |  |
| $t_{d(C L K H-N B L H)}$ | FMC_CLK high to FMC_NBL high | $t_{\text {HCLK }}+0.5$ | - |  |
| $t_{\text {su }}$ (NWAIT-CLKH) | FMC_NWAIT valid before FMC_CLK high | 3 | - |  |
| $t_{h(C L K H-N W A I T)}$ | FMC_NWAIT valid after FMC_CLK high | 2.5 | - |  |

1. Evaluated by characterization. Not tested in production.

Figure 59. Synchronous non-multiplexed NOR/PSRAM read timings
![img-78.jpeg](img-78.jpeg)Table 138. Synchronous non-multiplexed NOR/PSRAM read timings ${ }^{(1)}$

| Symbol | Parameter | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $t_{w(C L K)}$ | FMC_CLK period | $t_{\text {HCLK }}-0.5$ | - | ns |
| $t_{d(C L K-L-N E x L)}$ | FMC_CLK low to FMC_NEx low $(x=0 . .2)$ | - | 1 |  |
| $t_{d(C L K H-N E x H)}$ | FMC_CLK high to FMC_NEx high $(x=0 \ldots 2)$ | $t_{\text {HCLK }}-0.5$ | - |  |
| $t_{d(C L K-L-N A D V L)}$ | FMC_CLK low to FMC_NADV low | - | 1.5 |  |
| $t_{d(C L K-L-N A D V H)}$ | FMC_CLK low to FMC_NADV high | 1 | - |  |
| $t_{d(C L K-L-A V)}$ | FMC_CLK low to FMC_Ax valid $(x=0 \ldots 25)$ | - | 2.5 |  |
| $t_{d(C L K H-A I V)}$ | FMC_CLK high to FMC_Ax invalid $(x=0 \ldots 25)$ | $t_{\text {HCLK }}-0.5$ | - |  |
| $t_{d(C L K-L-N O E L)}$ | FMC_CLK low to FMC_NOE low | - | 1.5 |  |
| $t_{d(C L K H-N O E H)}$ | FMC_CLK high to FMC_NOE high | $t_{\text {HCLK }}+1$ | - |  |
| $t_{\text {su }}$ (DV-CLKH) | FMC_D[15:0] valid data before FMC_CLK high | 3 | - |  |
| $t_{h(C L K H-D V)}$ | FMC_D[15:0] valid data after FMC_CLK high | 4 | - |  |
| $t_{\text {su }}$ (NWAIT-CLKH) | FMC_NWAIT valid before FMC_CLK high | 1 | - |  |
| $t_{h(C L K H-N W A I T)}$ | FMC_NWAIT valid after FMC_CLK high | 2.5 | - |  |

1. Evaluated by characterization. Not tested in production.

Figure 60. Synchronous non-multiplexed PSRAM write timings
![img-79.jpeg](img-79.jpeg)Table 139. Synchronous non-multiplexed PSRAM write timings ${ }^{(1)}$

| Symbol | Parameter | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $t_{w(C L K)}$ | FMC_CLK period | $2 \times t_{\text {HCLK }}-0.5$ | - | ns |
| $t_{d(C L K L-N E x L)}$ | FMC_CLK low to FMC_NEx low $(x=0 . .2)$ | - | 3 |  |
| $t_{d(C L K H-N E x H)}$ | FMC_CLK high to FMC_NEx high $(x=0 . .2)$ | $t_{\text {HCLK }}+1.5$ | - |  |
| $t_{d(C L K L-N A D V L)}$ | FMC_CLK low to FMC_NADV low | - | 2 |  |
| $t_{d(C L K L-N A D V H)}$ | FMC_CLK low to FMC_NADV high | 1 | - |  |
| $t_{d(C L K L-A V)}$ | FMC_CLK low to FMC_Ax valid $(x=16 . .25)$ | - | 3 |  |
| $t_{d(C L K H-A I V)}$ | FMC_CLK high to FMC_Ax invalid $(x=16 . .25)$ | $t_{\text {HCLK }}$ | - |  |
| $t_{d(C L K L-N W E L)}$ | FMC_CLK low to FMC_NWE low | - | 2.5 |  |
| $t_{d(C L K H-N W E H)}$ | FMC_CLK high to FMC_NWE high | $t_{\text {HCLK }}+1$ | - |  |
| $t_{d(C L K L-D a t a)}$ | FMC_D[15:0] valid data after FMC_CLK low | - | 3 |  |
| $t_{d(C L K L-N B L L)}$ | FMC_CLK low to FMC_NBL low | - | 2 |  |
| $t_{d(C L K H-N B L H)}$ | FMC_CLK high to FMC_NBL high | $t_{\text {HCLK }}+0.5$ | - |  |
| $t_{\text {su }}$ (NWAIT-CLKH) | FMC_NWAIT valid before FMC_CLK high | 3 | - |  |
| $t_{h(C L K H-N W A I T)}$ | FMC_NWAIT valid after FMC_CLK high | 2.5 | - |  |

1. Evaluated by characterization. Not tested in production.

# NAND controller waveforms and timings 

Figure 61 to Figure 64 represent synchronous waveforms, and Table 140/Table 141 provide the corresponding timings. The results shown in these tables are obtained with the following FMC configuration:

- COM.FMC_SetupTime $=0 \times 01$
- COM.FMC_WaitSetupTime $=0 \times 03$
- COM.FMC_HoldSetupTime $=0 \times 02$
- COM.FMC_HiZSetupTime $=0 \times 01$
- ATT.FMC_SetupTime $=0 \times 01$
- ATT.FMC_WaitSetupTime $=0 \times 03$
- ATT.FMC_HoldSetupTime $=0 \times 02$
- ATT.FMC_HiZSetupTime $=0 \times 01$
- Bank = FMC_Bank_NAND
- MemoryDataWidth = FMC_MemoryDataWidth_16b
- ECC = FMC_ECC_Enable
- ECCPageSize = FMC_ECCPageSize_512Bytes
- TCLRSetupTime $=0$
- TARSetupTime $=0$

In all timing tables, the $T_{\text {HCLK }}$ is the HCLK clock period.Figure 61. NAND controller waveforms for read access
![img-80.jpeg](img-80.jpeg)

1. $y=7$ or 15 depending on the NAND flash memory interface.

Figure 62. NAND controller waveforms for write access
![img-81.jpeg](img-81.jpeg)

1. $y=7$ or 15 depending on the NAND flash memory interface.Figure 63. NAND controller waveforms for common memory read access
![img-82.jpeg](img-82.jpeg)

Figure 64. NAND controller waveforms for common memory write access
![img-83.jpeg](img-83.jpeg)

Table 140. Switching characteristics for NAND Flash read cycles ${ }^{(1)}$

| Symbol | Parameter | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $t_{w(\text { NOE })}$ | FMC_NOE low width | $4 \times t_{\text {HCLK }}-0.5$ | $4 \times t_{\text {HCLK }}+0.5$ | ns |
| $t_{\text {su(D-NOE) }}$ | FMC_D[15-0] valid data before FMC_NOE high | 10 | - |  |
| $t_{h(\text { NOE-D) }}$ | FMC_D[15-0] valid data after FMC_NOE high | 0 | - |  |
| $t_{d(\text { ALE-NOE })}$ | FMC_ALE valid before FMC_NOE low | - | $3 \times t_{\text {HCLK }}+0.5$ |  |
| $t_{h(\text { NOE-ALE })}$ | FMC_NWE high to FMC_ALE invalid | $4 \times t_{\text {HCLK }}-1$ | - |  |

1. Evaluated by characterization. Not tested in production.Table 141. Switching characteristics for NAND Flash write cycles ${ }^{(1)}$

| Symbol | Parameter | Min | Max | Unit |
| :--: | :-- | :--: | :--: | :--: |
| $\mathrm{t}_{\mathrm{w}(\text { NWE) }}$ | FMC_NWE low width | $4 \times \mathrm{t}_{\text {HCLK }}-0.5$ | $4 \times \mathrm{t}_{\text {HCLK }}+0.5$ | ns |
| $\mathrm{t}_{\mathrm{v}(\text { NWE-D) }}$ | FMC_NWE low to FMC_D[15-0] valid | 0 | - |  |
| $\mathrm{t}_{\mathrm{h}(\text { NWE-D) }}$ | FMC_NWE high to FMC_D[15-0] invalid | $2 \times t_{\text {HCLK }}+1$ | - |  |
| $\mathrm{t}_{\mathrm{d}(\text { D-NWE) }}$ | FMC_D[15-0] valid before FMC_NWE high | $5 \times t_{\text {HCLK }}-5$ | - |  |
| $\mathrm{t}_{\mathrm{d}(\text { ALE_NWE) }}$ | FMC_ALE valid before FMC_NWE low | - | $3 \times t_{\text {HCLK }}+0.5$ |  |
| $\mathrm{t}_{\mathrm{h}(\text { NWE-ALE) }}$ | FMC_NWE high to FMC_ALE invalid | $2 \times t_{\text {HCLK }}-0.5$ | - |  |

1. Evaluated by characterization. Not tested in production.

# 5.3.34 OCTOSPI characteristics 

Unless otherwise specified, the parameters given in Table 142 to Table 144 are derived from tests performed under the ambient temperature, $\mathrm{f}_{\mathrm{AHB}}$ frequency and $\mathrm{V}_{\mathrm{DD}}$ supply voltage conditions summarized in Table 33, with the following configuration:

- Output speed set to OSPEEDRy[1:0] = 10
- Delay block enabled for DTR (with DQS)/HyperBus
- Measurement points done at $0.5 \times V_{D D}$ level
- I/O compensation cell activated
- HSLV activated when $\mathrm{V}_{\mathrm{DD}} \leq 2.7 \mathrm{~V}$
- Voltage scaling range 1 unless otherwise specified

Refer to Section 5.3.15: I/O port characteristics for more details on the input/output alternate function characteristics.

Table 142. OCTOSPI characteristics in SDR mode ${ }^{(1)(2)(3)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $f_{(C L K)}$ | OCTOSPI clock <br> frequency | $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ <br> Voltage range 1 <br> $\mathrm{C}_{\mathrm{L}}=15 \mathrm{pF}$ | - | - | 93 | MHz |
|  |  | $2.7 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ <br> Voltage range1 <br> $\mathrm{C}_{\mathrm{L}}=15 \mathrm{pF}$ | - | - | 100 |  |
|  |  | $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ <br> Voltage range 4 <br> $\mathrm{C}_{\mathrm{L}}=15 \mathrm{pF}$ | - | - | 24 |  |Table 142. OCTOSPI characteristics in SDR mode ${ }^{(1)(2)(3)}$ (continued)

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{t}_{\mathrm{w}(\mathrm{CLKH})}$ | OCTOSPI clock high and low time (even division) | PRESCALER[7:0] = n $(n=0,1,3,5, . .255)$ | $\mathrm{t}_{(\mathrm{CLK})^{\prime} 2}$ - 0.5 | - | $t_{(CL K)^{\prime} 2}$ | ns |
| $\mathrm{t}_{\mathrm{w}(\mathrm{CLKL})}$ |  |  | $t_{(\mathrm{CLK})^{\prime} 2}$ - 0.5 | - | $t_{(\mathrm{CLK})^{\prime} 2}$ |  |
| $\mathrm{t}_{\mathrm{w}(\mathrm{CLKH})}$ | OCTOSPI clock high and low time (odd division) | PRESCALER[7:0] = n $(n=2,4,6, . .254)$ | $\begin{gathered} (\mathrm{n} / 2) \times \mathrm{t}_{(\mathrm{CLK})} \\ /(\mathrm{n}+1)-0.5 \end{gathered}$ | - | $\begin{gathered} (\mathrm{n} / 2) \times \mathrm{t}_{(\mathrm{CLK})} \\ /(\mathrm{n}+1) \end{gathered}$ |  |
| $\mathrm{t}_{\mathrm{w}(\mathrm{CLKL})}$ |  |  | $\begin{gathered} ((\mathrm{n} / 2)+1) \times \mathrm{t}_{(\mathrm{CLK})} \\ /(\mathrm{n}+1)-0.5 \end{gathered}$ | - | $\begin{gathered} ((\mathrm{n} / 2)+1) \times \mathrm{t}_{(\mathrm{CLK})} \\ /(\mathrm{n}+1) \end{gathered}$ |  |
| $t_{s(i N)}$ | Data input setup time | Voltage range 1 | 2.75 | - | - |  |
|  |  | Voltage range 4 | 3 | - | - |  |
| $t_{h(i N)}$ | Data input hold time | Voltage range 1 | 0.5 | - | - |  |
|  |  | Voltage range 4 | 1 | - | - |  |
| $t_{v(\text { OUT })}$ | Data output valid time | Voltage range 1 | - | 0.5 | 1 |  |
|  |  | Voltage range 4 | - | 1.5 | 2.5 |  |
| $t_{h(\text { OUT })}$ | Data output hold time | Voltage range 1 | 0.5 | - | - |  |
|  |  | Voltage range 4 | $-0.25$ | - | - |  |

1. Evaluated by characterization. Not tested in production.
2. Measured values in this table apply to Octo- and Quad-SPI data modes.
3. Delay block bypassed.

Table 143. OCTOSPI characteristics in DTR mode (no DQS) ${ }^{(1)(2)(3)}$

| Sym <br> bol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{(\mathrm{CLK})}$ | OCTOSPI clock frequency | $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ Voltage range $1, \mathrm{C}_{\mathrm{L}}=15 \mathrm{pF}$ | - | - | $93^{(4)}$ | MHz |
|  |  | $2.7 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ <br> Voltage range $1, \mathrm{C}_{\mathrm{L}}=15 \mathrm{pF}$ | - | - | $100^{(4)}$ |  |
|  |  | $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ <br> Voltage range $4, \mathrm{C}_{\mathrm{L}}=15 \mathrm{pF}$ | - | - | $24^{(4)}$ |  |Table 143. OCTOSPI characteristics in DTR mode (no DQS) ${ }^{(1)(2)(3)}$ (continued)

| Sym <br> bol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{t}_{\mathrm{w}(\mathrm{CLKH})}$ | OCTOSPI clock <br> high and low time <br> (even division) | PRESCALER[7:0] = n <br> $(n=0,1,3,5, . .255)$ | $\mathrm{t}_{(\mathrm{CLK})} / 2-0.5$ | - | $\mathrm{t}_{(\mathrm{CLK})} / 2+0.5$ | ns |
| $\mathrm{t}_{\mathrm{w}(\mathrm{CLKL})}$ |  |  | $t_{(\mathrm{CLK})} / 2-0.5$ | - | $t_{(\mathrm{CLK})} / 2+0.5$ |  |
| $\mathrm{t}_{\mathrm{w}(\mathrm{CLKH})}$ | OCTOSPI clock <br> high and low time <br> (odd division) | PRESCALER[7:0] = n <br> $(n=2,4,6, . .254)$ | $\begin{gathered} (n / 2) \times t_{(C L K)} \\ /(n+1)-0.5 \end{gathered}$ | - | $\begin{gathered} (n / 2) \times t_{(C L K)} \\ /(n+1)+0.5 \end{gathered}$ |  |
| $\mathrm{t}_{\mathrm{w}(\mathrm{CLKL})}$ |  |  | $\begin{gathered} \left((n / 2)+1\right) \times t_{(C L K)} \\ /(n+1)-0.5 \end{gathered}$ | - | $\begin{gathered} \left((n / 2)+1\right) \times t_{(C L K)} \\ /(n+1)+0.5 \end{gathered}$ |  |
| $\mathrm{t}_{\mathrm{sr}(\mathrm{IN})}$ <br> $\mathrm{t}_{\mathrm{sf}(\mathrm{IN})}$ | Data input setup time | Voltage range 1 | 3.25 | - | - |  |
|  |  | Voltage range 4 | 3.75 | - | - |  |
| $\mathrm{t}_{\mathrm{hr}(\mathrm{IN})}$ <br> $\mathrm{t}_{\mathrm{hf}(\mathrm{IN})}$ | Data input hold time | Voltage range 1 | 1 | - | - |  |
|  |  | Voltage range 4 | 1.5 | - | - |  |
| $\mathrm{t}_{\mathrm{sr}(\mathrm{OUT})}$ <br> $\mathrm{t}_{\mathrm{hf}(\mathrm{OUT})}$ | Data output valid time, DHQC $=0$ | Voltage range 1 | - | 6 | 9.25 |  |
|  |  | Voltage range 4 | - | 13.25 | 19.75 |  |
|  | Data output valid time, DHQC $=1$ | Voltage range 1 <br> All prescaler values (except 0) | - | $\begin{aligned} & \mathrm{t}_{(\mathrm{CLK})} / 4 \\ & +0.75 \end{aligned}$ | $\mathrm{t}_{(\mathrm{CLK})} / 4+1.5$ |  |
| $\mathrm{t}_{\mathrm{hr}(\mathrm{OUT})}$ <br> $\mathrm{t}_{\mathrm{hf}(\mathrm{OUT})}$ | Data output hold time DHQC $=0$ | Voltage range 1 | 4 | - | - |  |
|  |  | Voltage range 4 | 8 | - | - |  |
|  | Data output hold time DHQC $=1$ | Voltage range 1 <br> All prescaler values (except 0) | $t_{(C L K)} / 4-0.5$ | - | - |  |

1. Evaluated by characterization. Not tested in production.
2. Measured values in this table apply to Octo- and Quad-SPI data modes.
3. Delay block bypassed.
4. Activating DHQC is mandatory to reach this frequency.

Table 144. OCTOSPI characteristics in DTR mode (with DQS)/HyperBus ${ }^{(1)(2)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{t}_{(\mathrm{CLK})}$ | OCTOSPI clock frequency | $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ <br> Voltage range 1 <br> $\mathrm{C}_{\mathrm{L}}=15 \mathrm{pF}$ | - | - | $93^{(3)(4)}$ | MHz |
|  |  | $2.7 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ <br> Voltage range1 <br> $\mathrm{C}_{\mathrm{L}}=15 \mathrm{pF}$ | - | - | $100^{(3)(4)}$ |  |
|  |  | $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ <br> Voltage range 4 <br> $\mathrm{C}_{\mathrm{L}}=15 \mathrm{pF}$ | - | - | $24^{(4)}$ |  |Table 144. OCTOSPI characteristics in DTR mode (with DQS)/HyperBus ${ }^{(1)(2)}$ (continued)

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{t}_{\mathrm{w}(\mathrm{CLKH})}$ | OCTOSPI clock high and low time (even division) | PRESCALER[7:0] $=\mathrm{n}$ $(n=0,1,3,5, . .255)$ | $\mathrm{t}_{(\mathrm{CLK})^{\prime} 2}$ - 0.5 | - | $\mathrm{t}_{(\mathrm{CLK})^{\prime} 2}+0.5$ | ns |
| $\mathrm{t}_{\mathrm{w}(\mathrm{CLKL})}$ |  |  | $\mathrm{t}_{(\mathrm{CLK})^{\prime} 2}$ - 0.5 | - | $\mathrm{t}_{(\mathrm{CLK})^{\prime} 2}+0.5$ |  |
| $\mathrm{t}_{\mathrm{w}(\mathrm{CLKH})}$ | OCTOSPI clock high and low time (odd division) | PRESCALER[7:0] $=\mathrm{n}$ $(n=2,4,6, . .254)$ | $\begin{gathered} (\mathrm{n} / 2) \times \mathrm{t}_{(\mathrm{CLK})} \\ /(\mathrm{n}+1)-0.5 \end{gathered}$ | - | $\begin{gathered} (\mathrm{n} / 2) \times \mathrm{t}_{(\mathrm{CLK})} \\ /(\mathrm{n}+1)+0.5 \end{gathered}$ |  |
| $\mathrm{t}_{\mathrm{w}(\mathrm{CLKL})}$ |  |  | $\begin{gathered} \left((\mathrm{n} / 2)+1\right) \times \mathrm{t}_{(\mathrm{CLK})} \\ /(\mathrm{n}+1)-0.5 \end{gathered}$ | - | $\begin{gathered} \left((\mathrm{n} / 2)+1\right) \times \mathrm{t}_{(\mathrm{CLK})} \\ /(\mathrm{n}+1)+0.5 \end{gathered}$ |  |
| $t_{v(\mathrm{CLK})}$ | Clock valid time | - | - | - | $t_{(\mathrm{CLK})}+2$ |  |
| $t_{h(\mathrm{CLK})}$ | Clock hold time | - | $t_{(\mathrm{CLK})^{\prime} 2}$ - 0.5 | - | - |  |
| $\begin{gathered} \mathrm{V}_{\mathrm{OD}(\mathrm{CLK})} \\ (5) \end{gathered}$ | CLK, NCLK crossing level on CLK rising edge | $\mathrm{V}_{\mathrm{DD}}=1.8 \mathrm{~V}$ | 975 | - | 1120 | mV |
| $\begin{gathered} \mathrm{V}_{\mathrm{OD}(\mathrm{CLK})} \\ (5) \end{gathered}$ | CLK, NCLK crossing level on CLK falling edge | $\mathrm{V}_{\mathrm{DD}}=1.8 \mathrm{~V}$ | 845 | - | 990 |  |
| $t_{w(C S)}$ | Chip select high time | - | $3 \times t_{(\mathrm{CLK})}$ | - | - | ns |
| $t_{v(D Q)}$ | Data input valid time | - | 0 | - | - |  |
| $t_{v(D S)}$ | Data strobe input valid time |  | 0 | - | - |  |
| $t_{h(D S)}$ | Data strobe input hold time | - | 0 | - | - |  |
| $t_{v(R W D S)}$ | Data strobe output valid time | - | - | - | $3 \times t_{(\mathrm{CLK})}$ |  |
| $\begin{aligned} & \mathrm{t}_{\mathrm{sr}(\mathrm{DQ})} \\ & \mathrm{t}_{\mathrm{sf}(\mathrm{DQ})} \end{aligned}$ | Data input setup time | Voltage range 1 | $-0.5$ | - | $\mathrm{t}_{(\mathrm{CLK})^{\prime} 2}$ - $1.5^{(6)}$ |  |
|  |  | Voltage range 4 | $-0.25$ | - | $\mathrm{t}_{(\mathrm{CLK})^{\prime} 2}$ - $1.75^{(6)}$ |  |
| $\begin{aligned} & \mathrm{t}_{\mathrm{hr}(\mathrm{DQ})} \\ & \mathrm{t}_{\mathrm{hf}(\mathrm{DQ})} \end{aligned}$ | Data input hold time | Voltage range 1 | 1.5 | - | - |  |
|  |  | Voltage range 4 | 1.75 | - | - |  |
| $\begin{aligned} & \mathrm{t}_{\mathrm{vr}(\mathrm{OUT})} \\ & \mathrm{t}_{\mathrm{vf}(\mathrm{OUT})} \end{aligned}$ | Data output valid time DHQC $=0$ | Voltage range 1 | - | 6 | 9.5 | ns |
|  |  | Voltage range 4 | - | 13 | 19.5 |  |
|  | Data output valid time DHQC $=1$ | Voltage range 1 All prescaler values (except 0) | - | $t_{(\mathrm{CLK})^{\prime} 4}+0.5$ | $t_{(\mathrm{CLK})^{\prime} 4}+1.25$ |  |
| $\begin{aligned} & \mathrm{t}_{\mathrm{hr}(\mathrm{OUT})} \\ & \mathrm{t}_{\mathrm{hf}(\mathrm{OUT})} \end{aligned}$ | Data output hold time DHQC $=0$ | Voltage range 1 | 4 | - | - |  |
|  |  | Voltage range 4 | 7.75 | - | - |  |
| $t_{h r(O U T)}$ | Data output hold time DHQC $=1$ | Voltage range 1 All prescaler values (except 0) | $t_{(\mathrm{CLK})^{\prime} 4}$ - 0.5 | - | - |  |

1. Evaluated by characterization. Not tested in production.
2. Delay block activated.3. Maximum frequency values are given for a RWDS to DQ skew of maximum $\pm 1.0 \mathrm{~ns}$.
4. Activating DHQC is mandatory to reach this frequency.
5. Crossing results are in line with specification, except for PA3/PB5 CLK that exceed slightly the specification.
6. Data input maximum setup time does not take into account the data level switching duration.

Figure 65. OCTOSPI timing diagram - SDR mode
![img-84.jpeg](img-84.jpeg)

Figure 66. OCTOSPI timing diagram - DDR mode
![img-85.jpeg](img-85.jpeg)

Figure 67. OCTOSPI HyperBus clock
![img-86.jpeg](img-86.jpeg)Figure 68. OCTOSPI HyperBus read
![img-87.jpeg](img-87.jpeg)

Figure 69. OCTOSPI HyperBus read with double latency
![img-88.jpeg](img-88.jpeg)

Figure 70. OCTOSPI HyperBus write
![img-89.jpeg](img-89.jpeg)# 5.3.35 SD/SDIO/e・MMC card host interfaces (SDMMC) characteristics 

Unless otherwise specified, the parameters given in Table 145 and Table 146 are derived from tests performed under the ambient temperature, $\mathrm{f}_{\mathrm{AHB}}$ frequency and $\mathrm{V}_{\mathrm{DD}}$ supply voltage conditions summarized in Table 33, with the following configuration:

- Output speed set to OSPEEDRy[1:0] = 10
- Capacitive load $\mathrm{C}_{\mathrm{L}}=30 \mathrm{pF}$, unless otherwise specified
- Measurement points done at $0.5 \times V_{D D}$ level
- I/O compensation cell activated
- HSLV activated when $\mathrm{V}_{\mathrm{DD}} \leq 2.7 \mathrm{~V}$
- Voltage scaling range 1

Refer to Section 5.3.15: I/O port characteristics for more details on the input/output characteristics.

Table 145. SD/e・MMC characteristics $\left(\mathrm{V}_{\mathrm{DD}}=2.7 \mathrm{~V}\right.$ to $\left.3.6 \mathrm{~V}\right)^{(1)(2)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $f_{P P}$ | Clock frequency in data transfer mode | - | 0 | - | $100^{(3)}$ | MHz |
| $\mathrm{t}_{\mathrm{W}(\mathrm{CKL})}$ | Clock low time | $\mathrm{f}_{\mathrm{PP}}=52 \mathrm{MHz}$ | 8.5 | 9.5 | - | ns |
| $\mathrm{t}_{\mathrm{W}(\mathrm{CKH})}$ | Clock high time | $\mathrm{f}_{\mathrm{PP}}=52 \mathrm{MHz}$ | 8.5 | 9.5 | - |  |
| CMD, D inputs (referenced to CK) in e-MMC legacy/SDR/DDR and SD HS/SDR ${ }^{(4)} / \mathrm{DDR}^{(4)}$ modes |  |  |  |  |  |  |
| $t_{\text {ISU }}$ | Input setup time HS | - | 3.5 | - | - | ns |
| $t_{I H}$ | Input hold time HS | - | 1.5 | - | - |  |
| $t_{I D W}{ }^{(5)}$ | Input valid window (variable window) | - | 4.5 | - | - |  |
| CMD, D outputs (referenced to CK) in e-MMC legacy/SDR/DDR and SD HS/SDR ${ }^{(4)} / \mathrm{DDR}^{(4)}$ modes |  |  |  |  |  |  |
| $t_{O V}$ | Output valid time HS | - | - | 5.5 | 6 | ns |
| $t_{O H}$ | Output hold time HS | - | 4 | - | - |  |
| CMD, D inputs (referenced to CK) in SD default mode |  |  |  |  |  |  |
| $t_{\text {ISU }}$ | Input setup time SD | - | 3.5 | - | - | ns |
| $t_{I H}$ | Input hold time SD | - | 1.5 | - | - |  |
| CMD, D outputs (referenced to CK) in SD default mode |  |  |  |  |  |  |
| $t_{O V}$ | Output valid default time SD | - | - | 0.5 | 2 | ns |
| $t_{O H}$ | Output hold default time SD | - | 0 | - | - |  |

1. Evaluated by characterization. Not tested in production.
2. For SDMMC2 in SD/e.MMC DDR mode, the clock OSPEEDRy[1:0] is set to 01 while data OSPEEDRy[1:0] remains at 10.
3. With capacitive load $C_{L}=20 \mathrm{pF}$.
4. For SD 1.8 V support, an external voltage converter is needed.
5. Minimum window of time where the data needs to be stable for proper sampling in tuning mode.Table 146. e・MMC characteristics $\left(\mathrm{V}_{\mathrm{DD}}=1.71 \mathrm{~V}\right.$ to $\left.1.9 \mathrm{~V}\right)^{(1)(2)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $f_{P P}$ | Clock frequency in data transfer mode | All modes except DDR | - | - | 84 | MHz |
|  |  | DDR mode | - | - | $40^{(3)}$ |  |
| $\mathrm{t}_{\mathrm{W}(\mathrm{CKL})}$ | Clock low time | $\mathrm{f}_{\mathrm{PP}}=52 \mathrm{MHz}$ | 8.5 | 9.5 | - | ns |
| $\mathrm{t}_{\mathrm{W}(\mathrm{CKH})}$ | Clock high time | $\mathrm{f}_{\mathrm{PP}}=52 \mathrm{MHz}$ | 8.5 | 9.5 | - |  |
| CMD, D inputs (referenced to CK) in e・MMC mode |  |  |  |  |  |  |
| $t_{\text {ISU }}$ | Input setup time HS | - | 2.5 | - | - | ns |
| $t_{I H}$ | Input hold time HS | - | 2 | - | - |  |
| $t_{I D W}{ }^{(4)}$ | Input valid window (variable window) | - | 4 | - | - |  |
| CMD, D outputs (referenced to CK) in e・MMC mode |  |  |  |  |  |  |
| $t_{O V}$ | Output valid time HS | - | - | 10.5 | $13 / 15^{(5)}$ | ns |
| $t_{O H}$ | Output hold time HS | - | 7 | - | - |  |

1. Evaluated by characterization. Not tested in production.
2. With capacitive load $\mathrm{C}_{\mathrm{L}}=20 \mathrm{pF}$.
3. For DDR mode, the maximum frequency is 40 MHz and HSLV must be OFF.
4. Minimum window of time where the data needs to be stable for proper sampling in tuning mode.
5. $t_{O V}=13 \mathrm{~ns}$ for SDMMC1 and $t_{O V}=15 \mathrm{~ns}$ for SDMMC2.

Figure 71. SD high-speed mode
![img-90.jpeg](img-90.jpeg)

Figure 72. SD default mode
![img-91.jpeg](img-91.jpeg)Figure 73. SDMMC DDR mode
![img-92.jpeg](img-92.jpeg)

# 5.3.36 Delay block characteristics 

Unless otherwise specified, the parameters given in the table below are derived from tests performed under the ambient temperature, $\mathrm{f}_{\mathrm{HCLK}}$ frequency and $\mathrm{V}_{\mathrm{DD}}$ supply voltage conditions summarized in Table 33.

Table 147. Delay block characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :-- | :--: | :--: | :--: | :--: | :--: |
| $t_{\text {init }}$ | Initial delay | - | 900 | 1300 | 2100 | ps |
| $t_{1}$ | Unit delay | - | 34 | 41 | 51 |  |

1. Evaluated by characterization. Not tested in production.

### 5.3.37 $\mathrm{I}^{2} \mathrm{C}$ interface characteristics

The $I^{2} \mathrm{C}$ interface meets the timings requirements of the $I^{2} \mathrm{C}$-bus specification and user manual rev. 03 for:

- Standard-mode (Sm): with a bitrate up to $100 \mathrm{Kbit} / \mathrm{s}$
- Fast-mode (Fm): with a bitrate up to $400 \mathrm{Kbit} / \mathrm{s}$
- Fast-mode Plus (Fm+): with a bitrate up to $1 \mathrm{Mbit} / \mathrm{s}$

The I2C timings requirements are specified by design, not tested in production, when the I2C peripheral is properly configured (refer to the product reference manual).
The SDA and SCL I/O requirements are met with the following restrictions: the SDA and SCL I/O pins are not "true" open-drain. When configured as open-drain, the PMOS connected between the I/O pin and $\mathrm{V}_{\text {DDIOx }}$ is disabled, but is still present. Only FT_ f I/O pins support Fm+ low-level output-current maximum requirement. Refer to Section 5.3.15: I/O port characteristics for the I2C I/Os characteristics.
All I2C SDA and SCL I/Os embed an analog filter. Refer to the table below for the analog filter characteristics.Table 148. I2C analog filter characteristics ${ }^{(1)}$

| Symbol | Parameter | Min | Max | Unit |
| :--: | :-- | :-- | :--: | :--: |
| $\mathrm{t}_{\mathrm{AF}}$ | Maximum pulse width of spikes that are suppressed by the analog filter | $50^{(2)}$ | $115^{(3)}$ | ns |

1. Specified by design. Not tested in production.
2. Spikes with widths below $\mathrm{t}_{\mathrm{AF}}$ min are filtered.
3. Spikes with width above $\mathrm{t}_{\mathrm{AF}}$ max are not filtered.

# 5.3.38 USART (SPI mode) characteristics 

Unless otherwise specified, the parameters given in the table below are derived from tests performed under the ambient temperature, $\mathrm{f}_{\text {PCLKx }}$ frequency and $\mathrm{V}_{\mathrm{DD}}$ supply voltage conditions summarized in Table 33, with the following configuration:

- Output speed set to OSPEEDRy[1:0] = 10
- Capacitive load $C_{L}=30 \mathrm{pF}$
- Measurement points done at $0.5 \times V_{D D}$ level
- I/O compensation cell activated
- HSLV activated when $\mathrm{V}_{\mathrm{DD}} \leq 2.7 \mathrm{~V}$
- Voltage scaling range 1

Refer to Section 5.3.15: I/O port characteristics for more details on the input/output alternate function characteristics (NSS, CK, TX, RX for USART).

Table 149. USART (SPI mode) characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $f_{C K}$ | USART clock <br> frequency | SPI master mode, $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | - | - | 20 | MH <br> Z |
|  |  | SPI slave receiver, <br> $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | - | - | 53 |  |
|  |  | SPI slave transmitter, <br> $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | - | - | 28.5 |  |
|  |  | SPI slave transmitter, <br> $2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | - | - | 32 |  |Table 149. USART (SPI mode) characteristics ${ }^{(1)}$ (continued)

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{\text {su(NSS) }}$ | NSS setup time | SPI slave mode | $T_{\text {ker }}{ }^{(2)}+2$ | - | - | ns |
| $t_{n(\text { NSS) }}$ | NSS hold time | SPI slave mode | 2 | - | - |  |
| $\begin{aligned} & t_{w(C K H)} \\ & t_{w(C K L)} \end{aligned}$ | CK high and low time | SPI master mode | $1 / f_{C K} / 2-1$ | $1 / f_{C K} / 2$ | $1 / f_{C K} / 2+1$ |  |
| $t_{\text {su(RX) }}$ | Data input setup time | SPI master mode | 14 | - | - |  |
|  |  | SPI slave mode | 1 | - | - |  |
| $t_{n(R X)}$ | Data input hold time | SPI master mode | 4 | - | - |  |
| $t_{n(R X)}$ |  | SPI slave mode | 1 | - | - |  |
| $t_{v(T X)}$ | Data output valid time | SPI slave mode, $2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | - | 11 | 15.5 |  |
|  |  | SPI slave mode, $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | - | 11 | 17.5 |  |
| $t_{v(T X)}$ |  | SPI master mode | - | 2.5 | 6.5 |  |
| $t_{n(T X)}$ | Data output hold time | SPI slave mode | 8.5 | - | - |  |
| $t_{n(T X)}$ |  | SPI master mode | 2 | - | - |  |

1. Evaluated by characterization. Not tested in production.
2. $T_{\text {ker }}$ is the usart_ker_ck_pres clock period.

Figure 74. USART timing diagram in SPI master mode
![img-93.jpeg](img-93.jpeg)Figure 75. USART timing diagram in SPI slave mode
![img-94.jpeg](img-94.jpeg)

# 5.3.39 SPI characteristics 

Unless otherwise specified, the parameters given in the table below are derived from tests performed under the ambient temperature, $\mathrm{f}_{\mathrm{PCLKx}}$ frequency and supply voltage conditions summarized in Table 33.

- Output speed set to OSPEEDRy[1:0] = 10
- Capacitive load $C_{L}=30 \mathrm{pF}$
- Measurement points done at $0.5 \times V_{D D}$ level
- I/O compensation cell activated
- HSLV activated when $\mathrm{V}_{\mathrm{DD}} \leq 2.7 \mathrm{~V}$

Refer to Section 5.3.15: I/O port characteristics for more details on the input/output alternate function characteristics (NSS, SCK, MOSI, MISO for SPI).Table 150. SPI characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\begin{gathered} \mathrm{f}_{\text {SCK }} \\ 1 / \mathrm{t}_{\mathrm{c}(\mathrm{SCK})} \end{gathered}$ | SPI clock frequency | Master mode, $2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$, voltage range 1 | - | - | 80 | MHz |
|  |  | Master mode, $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }}<2.7 \mathrm{~V}$ voltage range 1 | - | - | $\begin{gathered} 75 \\ \text { or } 50^{(2)} \end{gathered}$ |  |
|  |  | Master transmitter mode, $2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$, voltage range 1 | - | - | 80 |  |
|  |  | Master transmitter mode, $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 2.7 \mathrm{~V}$, voltage range 1 | - | - | $\begin{gathered} 75 \\ \text { or } 50^{(2)} \end{gathered}$ |  |
|  |  | Slave receiver mode, $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$, voltage range 1 | - | - | 100 |  |
|  |  | Slave mode transmitter/full duplex ${ }^{(3)}$, $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }}<2.7 \mathrm{~V}$, voltage range 1 | - | - | $\begin{gathered} 41.5 \\ \text { or } 25.5^{(4)} \end{gathered}$ |  |
|  |  | Slave mode transmitter/full duplex ${ }^{(3)}$, $2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$, voltage range 1 | - | - | 38.5 |  |
|  |  | Master or slave mode $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$, voltage range 4 | - | - | 12.5 |  |
|  |  | Master or slave mode $1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIO2 }} \leq 1.32 \mathrm{~V}^{(5)}$ | - | - | 15 |  |
| $\mathrm{t}_{\text {su(NSS) }}$ | NSS setup time | Slave mode | 4 | - | - | ns |
| $t_{h(N S S)}$ | NSS hold time | Slave mode | 3 | - | - |  |
| $\begin{aligned} & \mathrm{t}_{\mathrm{w}(\text { SCKH) }} \\ & \mathrm{t}_{\mathrm{w}(\text { SCKL) }} \end{aligned}$ | SCK high and low time | Master mode | $\mathrm{t}_{\mathrm{SCK}}{ }^{(6)} / 2-1$ | $\mathrm{t}_{\mathrm{SCK}} / 2$ | $\mathrm{t}_{\mathrm{SCK}} / 2+1$ |  |
| $\mathrm{t}_{\mathrm{su}(\mathrm{MI})}$ | Data input setup time | Master mode | 4.5 | - | - |  |
| $t_{\text {su(SI) }}$ |  | Slave mode | 2.5 | - | - |  |
| $t_{h( }_{( })$ | Data input hold time | Master mode | 3 | - | - |  |
| $t_{h(S I)}$ |  | Slave mode | 1 | - | - |  |
| $t_{a(S O)}$ | Data output access time | Slave mode | 9 | - | 34 |  |
| $t_{\text {dis(SO) }}$ | Data output disable time | Slave mode | 9 | - | 16 |  |Table 150. SPI characteristics ${ }^{(1)}$ (continued)

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $t_{v(\text { SO })}$ | Data output valid time | Slave mode, $2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$, voltage range 1 | - | 10 | 13 | ns |
|  |  | Slave mode, $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }}<2.7 \mathrm{~V}$, voltage range 1 | - | 10 | $\begin{gathered} 12 \\ \text { or } 19.5^{(4)} \end{gathered}$ |  |
|  |  | Slave mode, $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$, voltage range 4 | - | 17 | $\begin{gathered} 19.5 \\ \text { or } 27^{(4)} \end{gathered}$ |  |
|  |  | Slave mode, $1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIO2 }} \leq 1.32 \mathrm{~V}^{(5)}$ | - | 21 | 22.5 |  |
| $t_{v(\text { MO })}$ |  | Master mode | - | 1.5 | 2 or $9.5^{(7)}$ <br> or $12.5^{(8)}$ |  |
| $t_{h(\text { SO })}$ | Data output hold time | Slave mode, $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | 7 | - | - |  |
|  |  | Slave mode, $1.08 \mathrm{~V} \leq \mathrm{V}_{\text {DDIO2 }} \leq 1.32 \mathrm{~V}^{(5)}$ | 18 | - | - |  |
| $t_{h(\text { MO })}$ |  | Master mode | 0 | - | - |  |

1. Evaluated by characterization. Not tested in production.
2. When using PA5, PA9, PC10, PB3, PB13.
3. The maximum frequency in slave transmitter mode is determined by the sum of $t_{v(\mathrm{SO})}$ and $t_{h(\mathrm{MI})}$ that has to fit into SCK low or high phase preceding the SCK sampling edge. This value can be achieved when the SPI communicates with a master having $t_{h v(M)}=0$ while Duty(SCK) $=50 \%$.
4. When using PA11, PB4, PB14.
5. The SPI is mapped on port G I/Os, that is supplied by VDDIO2 specified down to 1.08 V . The SPI is tested at this value.
6. $\mathrm{t}_{\mathrm{SCK}}=\mathrm{tspi} \_$ker_ck $\times$ baud rate prescaler.
7. When using PA12.
8. When using PB15.Figure 76. SPI timing diagram - slave mode and CPHA $=0$
![img-95.jpeg](img-95.jpeg)

Figure 77. SPI timing diagram - slave mode and CPHA = 1
![img-96.jpeg](img-96.jpeg)Figure 78. SPI timing diagram - master mode
![img-97.jpeg](img-97.jpeg)

# 5.3.40 SAI characteristics 

Unless otherwise specified, the parameters given in the table below are derived from tests performed under the ambient temperature, $\mathrm{f}_{\mathrm{PCLKx}}$ frequency and $\mathrm{V}_{\mathrm{DD}}$ supply voltage conditions summarized in Table 33, with the following configuration:

- Output speed set to OSPEEDRy[1:0] = 10
- Capacitive load $C_{L}=30 \mathrm{pF}$
- Measurement points done at $0.5 \times V_{D D}$ level
- I/O compensation cell activated
- HSLV activated when $V_{D D} \leq 2.7 \mathrm{~V}$
- Voltage scaling range 1

Refer to Section 5.3.15: I/O port characteristics for more details on the input/output alternate function characteristics (SCK, SD, FS).Table 151. SAI characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions | Min | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: |
| $f_{\text {MCK }}$ | SAI main clock output | - | - | 50 | MHz |
| $f_{\text {SCK }}$ | SAI clock frequency ${ }^{(2)}$ | Master transmitter, $2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | - | 26 |  |
|  |  | Master transmitter, $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | - | 18 |  |
|  |  | Master receiver, $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | - | 21.5 |  |
|  |  | Slave transmitter, $2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | - | 30 |  |
|  |  | Slave transmitter, $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | - | 20.5 |  |
|  |  | Slave receiver, $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | - | 50 |  |
| $t_{v(\text { FS })}$ | FS valid time | Master mode, $2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | - | 16 | ns |
|  |  | Master mode $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | - | 23 |  |
| $t_{h(\text { FS })}$ | FS hold time | Master mode | 7 | - |  |
| $t_{\text {su(FS) }}$ | FS setup time | Slave mode | 2.5 | - |  |
| $t_{h(\text { FS })}$ | FS hold time | Slave mode | 1 | - |  |
| $t_{\text {su(SD_A_MR) }}$ | Data input setup time | Master receiver | 4 | - |  |
| $t_{\text {su(SD_B_SR) }}$ |  | Slave receiver | 3 | - |  |
| $t_{h(S D _ A _ M R)}$ | Data input hold time | Master receiver | 1 | - |  |
| $t_{h(S D _ B _ S R)}$ |  | Slave receiver | 1 | - |  |
| $t_{v(S D _ B _ S T)}$ | Data output valid time | Slave transmitter (after enable edge), $2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | - | 16.5 |  |
|  |  | Slave transmitter (after enable edge), $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | - | 24 |  |
| $t_{h(S D _ B _ S T)}$ | Data output hold time | Slave transmitter (after enable edge) | 8 | - |  |
| $t_{v(S D _ A _ M T)}$ | Data output valid time | Master transmitter (after enable edge), $2.7 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | - | 19 | ns |
|  |  | Master transmitter (after enable edge), $1.71 \mathrm{~V} \leq \mathrm{V}_{\text {DDIOX }} \leq 3.6 \mathrm{~V}$ | - | 27.5 |  |
| $t_{h(S D _ A _ M T)}$ | Data output hold time | Master transmitter (after enable edge) | 8 | - |  |

1. Evaluated by characterization. Not tested in production.
2. APB clock frequency that must be at least twice SAI clock frequency.Figure 79. SAI master timing diagram
![img-98.jpeg](img-98.jpeg)

Figure 80. SAI slave timing diagram
![img-99.jpeg](img-99.jpeg)

# 5.3.41 OTG_FS characteristics 

Table 152. OTG_FS characteristics

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :-- | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{V}_{\text {DDUSB }}$ | USB transceiver operating supply voltage | - | $3.0^{(1)}$ | - | 3.6 | V |Table 152. OTG_FS characteristics (continued)

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :-- | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{R}_{\text {PUI }}$ | Embedded USB_DP pullup value during idle | - | 900 | - | 1575 | $\Omega$ |
| $\mathrm{R}_{\text {PUR }}$ | Embedded USB_DP pullup value during reception | - | 1425 | - | 3090 |  |
| $\mathrm{Z}_{\text {DRV }}$ | Output driver impedance ${ }^{(2)}$ | High and low driver | 28 | 36 | 44 |  |

1. USB functionality is ensured down to 2.7 V , but some USB electrical characteristics are degraded in 2.7 to 3.0 V range.
2. No external termination series resistors are required on USB_DP (D+) and USB_DM (D-). The matching impedance is already included in the embedded driver.

# 5.3.42 UCPD characteristics 

UCPD controller complies with USB Type-C Rev 1.2 and USB Power Delivery Rev 3.0 specifications.

Table 153. UCPD characteristics

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :-- | :-- | :--: | :--: | :--: | :--: |
| $\mathrm{V}_{\mathrm{DD}}$ | UCPD operating supply voltage | Sink mode only | 3.0 | 3.3 | 3.6 | V |
|  |  | Sink and source mode | 3.135 | 3.3 | 3.465 |  |

### 5.3.43 JTAG/SWD interface characteristics

Unless otherwise specified, the parameters given in the tables below are derived from tests performed under the ambient temperature, $f_{\text {HCLKx }}$ frequency and $V_{D D}$ supply voltage conditions summarized in Table 33, with the following configuration:

- Output speed set to OSPEEDRy[1:0] = 10
- Capacitive load $C_{L}=30 \mathrm{pF}$
- Measurement points done at $0.5 \times V_{D D}$ level

Refer to Section 5.3.15: I/O port characteristics for more details on the input/output characteristics.

Table 154. JTAG characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $\mathrm{F}_{\text {TCK }}$ | TCK clock frequency | $2.7 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | - | - | 38 | MHz |
|  |  | $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | - | - | 26 |  |
| $\mathrm{ti}_{\text {su(TMS) }}$ | TMS input setup time | - | 1 | - | - | ns |
| $\mathrm{ti}_{\text {h(TMS) }}$ | TMS input hold time | - | 3 | - | - |  |
| $\mathrm{ti}_{\text {su(TDI) }}$ | TDI input setup time | - | 2 | - | - |  |
| $\mathrm{ti}_{\mathrm{h}(\mathrm{TDI})}$ | TDI input hold time | - | 1 | - | - |  |
| $t_{\text {ov(TDO) }}$ | TDO output valid time | $2.7 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | - | 9 | 13 | ns |
|  |  | $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | - | 9 | 19 |  |
| $t_{\text {oh(TDO) }}$ | TDO output hold time | - | 7 | - | - |  |

1. Evaluated by characterization. Not tested in production.Table 155. SWD characteristics ${ }^{(1)}$

| Symbol | Parameter | Conditions | Min | Typ | Max | Unit |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| $F_{\text {SWCLK }}$ | SWCLK clock frequency | $2.7 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | - | - | 66.5 | MHz |
|  |  | $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | - | - | 43 |  |
| $\mathrm{ti}_{\text {av }}$ (SWDIO) | SWDIO input setup time | - | 1 | - | - | ns |
| $\mathrm{ti}_{\mathrm{h} \text { (SWDIO) }}$ | SWDIO input hold time | - | 2.5 | - | - |  |
| $t_{\text {ov(SWDIO) }}$ | SWDIO output valid time | $2.7 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | - | 10.5 | 15 |  |
|  |  | $1.71 \mathrm{~V} \leq \mathrm{V}_{\mathrm{DD}} \leq 3.6 \mathrm{~V}$ | - | 10.5 | 23 |  |
| $t_{\text {oh(SWDIO) }}$ | SWDIO output hold time | - | 7.5 | - | - |  |

1. Evaluated by characterization. Not tested in production.

Figure 81. JTAG timing diagram
![img-100.jpeg](img-100.jpeg)

Figure 82. SWD timing diagram
![img-101.jpeg](img-101.jpeg)# 6 Package information 

In order to meet environmental requirements, ST offers these devices in different grades of ECOPACK packages, depending on their level of environmental compliance. ECOPACK specifications, grade definitions and product status are available at: www.st.com. ECOPACK is an ST trademark.# 6.1 UFQFPN48 package information (A0B9) 

This UFQFPN is a 48-lead, $7 \times 7 \mathrm{~mm}, 0.5 \mathrm{~mm}$ pitch, ultra thin fine pitch quad flat package.
Figure 83. UFQFPN48 - Outline
![img-102.jpeg](img-102.jpeg)

1. Drawing is not to scale.
2. All leads/pads should also be soldered to the PCB to improve the lead/pad solder joint life.
3. There is an exposed die pad on the underside of the UFQFPN48 package. It is recommended to connect and solder this back-side pad to PCB ground.Table 156. UFQFPN48 - Mechanical data

| Symbol | millimeters |  |  | inches $^{(1)}$ |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | Min | Typ | Max | Min | Typ | Max |
| A | 0.500 | 0.550 | 0.600 | 0.0197 | 0.0217 | 0.0236 |
| A1 | 0.000 | 0.020 | 0.050 | 0.0000 | 0.0008 | 0.0020 |
| A3 | - | 0.152 | - | - | 0.0060 | - |
| b | 0.200 | 0.250 | 0.300 | 0.0079 | 0.0098 | 0.0118 |
| $D^{(2)}$ | 6.900 | 7.000 | 7.100 | 0.2717 | 0.2756 | 0.2795 |
| D1 | 5.400 | 5.500 | 5.600 | 0.2126 | 0.2165 | 0.2205 |
| D2 ${ }^{(3)}$ | 5.500 | 5.600 | 5.700 | 0.2165 | 0.2205 | 0.2244 |
| $E^{(2)}$ | 6.900 | 7.000 | 7.100 | 0.2717 | 0.2756 | 0.2795 |
| E1 | 5.400 | 5.500 | 5.600 | 0.2126 | 0.2165 | 0.2205 |
| E2 ${ }^{(3)}$ | 5.500 | 5.600 | 5.700 | 0.2165 | 0.2205 | 0.2244 |
| e | - | 0.500 | - | - | 0.0197 | - |
| L | 0.300 | 0.400 | 0.500 | 0.0118 | 0.0157 | 0.0197 |
| ddd | - | - | 0.080 | - | - | 0.0031 |

1. Values in inches are converted from mm and rounded to four decimal digits.
2. Dimensions D and E do not include mold protrusion, not exceed 0.15 mm .
3. Dimensions D2 and E2 are not in accordance with JEDEC.

Figure 84. UFQFPN48 - Footprint example
![img-103.jpeg](img-103.jpeg)

1. Dimensions are expressed in millimeters.# Device marking for UFQFPN48 

The following figure gives an example of topside marking versus pin 1 position identifier location.

The printed markings may differ depending on the supply chain.
Other optional marking or inset/upset marks, which depend on supply chain operations, are not indicated below.

Figure 85. UFQFPN48 marking example (package top view)
![img-104.jpeg](img-104.jpeg)

1. Parts marked as "ES", "E" or accompanied by an Engineering Sample notification letter, are not yet qualified and therefore not approved for use in production. ST is not responsible for any consequences resulting from such use. In no event will ST be liable for the customer using any of these engineering samples in production. ST's Quality department must be contacted prior to any decision to use these engineering samples to run a qualification activity.# 6.2 LQFP48 package information (5B) 

This LQFP is a 48 -pin, $7 \times 7 \mathrm{~mm}$ low-profile quad flat package.
Note: $\quad$ See list of notes in the notes section.
Figure 86. LQFP48 - Outline ${ }^{(15)}$
![img-105.jpeg](img-105.jpeg)Table 157. LQFP48 - Mechanical data

| Symbol | millimeters |  |  | inches ${ }^{(14)}$ |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | Min | Typ | Max | Min | Typ | Max |
| A | - | - | 1.60 | - | - | 0.0630 |
| A1 ${ }^{(12)}$ | 0.05 | - | 0.15 | 0.0020 | - | 0.0059 |
| A2 | 1.35 | 1.40 | 1.45 | 0.0531 | 0.0551 | 0.0571 |
| $b^{(9)(11)}$ | 0.17 | 0.22 | 0.27 | 0.0067 | 0.0087 | 0.0106 |
| b1 ${ }^{(11)}$ | 0.17 | 0.20 | 0.23 | 0.0067 | 0.0079 | 0.0090 |
| $c^{(11)}$ | 0.09 | - | 0.20 | 0.0035 | - | 0.0079 |
| c1 ${ }^{(11)}$ | 0.09 | - | 0.16 | 0.0035 | - | 0.0063 |
| $D^{(4)}$ | 9.00 BSC |  |  | 0.3543 BSC |  |  |
| D1 ${ }^{(2)(5)}$ | 7.00 BSC |  |  | 0.2756 BSC |  |  |
| $E^{(4)}$ | 9.00 BSC |  |  | 0.3543 BSC |  |  |
| E1 ${ }^{(2)(5)}$ | 7.00 BSC |  |  | 0.2756 BSC |  |  |
| e | 0.50 BSC |  |  | 0.1970 BSC |  |  |
| L | 0.45 | 0.60 | 0.75 | 0.0177 | 0.0236 | 0.0295 |
| L1 | 1.00 REF |  |  | 0.0394 REF |  |  |
| $N^{(13)}$ | 48 |  |  |  |  |  |
| $\theta$ | $0^{\circ}$ | $3.5^{\circ}$ | $7^{\circ}$ | $0^{\circ}$ | $3.5^{\circ}$ | $7^{\circ}$ |
| $\theta 1$ | $0^{\circ}$ | - | - | $0^{\circ}$ | - | - |
| $\theta 2$ | $10^{\circ}$ | $12^{\circ}$ | $14^{\circ}$ | $10^{\circ}$ | $12^{\circ}$ | $14^{\circ}$ |
| $\theta 3$ | $10^{\circ}$ | $12^{\circ}$ | $14^{\circ}$ | $10^{\circ}$ | $12^{\circ}$ | $14^{\circ}$ |
| R1 | 0.08 | - | - | 0.0031 | - | - |
| R2 | 0.08 | - | 0.20 | 0.0031 | - | 0.0079 |
| S | 0.20 | - | - | 0.0079 | - | - |
| aaa ${ }^{(1)(7)}$ | 0.20 |  |  | 0.0079 |  |  |
| bbb ${ }^{(1)(7)}$ | 0.20 |  |  | 0.0079 |  |  |
| $\operatorname{ccc}^{(1)(7)}$ | 0.08 |  |  | 0.0031 |  |  |
| $\operatorname{ddd}^{(1)(7)}$ | 0.08 |  |  | 0.0031 |  |  |# Notes: 

1. Dimensioning and tolerancing schemes conform to ASME Y14.5M-1994.
2. The Top package body size may be smaller than the bottom package size by as much as 0.15 mm .
3. Datums A-B and D to be determined at datum plane H .
4. To be determined at seating datum plane $C$.
5. Dimensions D1 and E1 do not include mold flash or protrusions. Allowable mold flash or protrusions is " 0.25 mm " per side. D1 and E1 are Maximum plastic body size dimensions including mold mismatch.
6. Details of pin 1 identifier are optional but must be located within the zone indicated.
7. All Dimensions are in millimeters.
8. No intrusion allowed inwards the leads.
9. Dimension "b" does not include dambar protrusion. Allowable dambar protrusion shall not cause the lead width to exceed the maximum "b" dimension by more than 0.08 mm . Dambar cannot be located on the lower radius or the foot. Minimum space between protrusion and an adjacent lead is 0.07 mm for 0.4 mm and 0.5 mm pitch packages.
10. Exact shape of each corner is optional.
11. These dimensions apply to the flat section of the lead between 0.10 mm and 0.25 mm from the lead tip.
12. A1 is defined as the distance from the seating plane to the lowest point on the package body.
13. " N " is the number of terminal positions for the specified body size.
14. Values in inches are converted from mm and rounded to 4 decimal digits.
15. Drawing is not to scale.

Figure 87. LQFP48 - Footprint example
![img-106.jpeg](img-106.jpeg)

1. Dimensions are expressed in millimeters.# Device marking for LQFP48 

The following figure gives an example of topside marking versus pin 1 position identifier location.

The printed markings may differ depending on the supply chain.
Other optional marking or inset/upset marks, which depend on supply chain operations, are not indicated below.

Figure 88. LQFP48 marking example (package top view)
![img-107.jpeg](img-107.jpeg)

1. Parts marked as "ES", "E" or accompanied by an Engineering Sample notification letter, are not yet qualified and therefore not approved for use in production. ST is not responsible for any consequences resulting from such use. In no event will ST be liable for the customer using any of these engineering samples in production. ST's Quality department must be contacted prior to any decision to use these engineering samples to run a qualification activity.# 6.3 LQFP64 package information (5W) 

This LQFP is 64-pin, $10 \times 10 \mathrm{~mm}$ low-profile quad flat package.
Note: $\quad$ See list of notes in the notes section.
Figure 89. LQFP64 - Outline ${ }^{(15)}$
![img-108.jpeg](img-108.jpeg)Table 158. LQFP64 - Mechanical data

| Symbol | millimeters |  |  | inches ${ }^{(14)}$ |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | Min | Typ | Max | Min | Typ | Max |
| A | - | - | 1.60 | - | - | 0.0630 |
| A1 ${ }^{(12)}$ | 0.05 | - | 0.15 | 0.0020 | - | 0.0059 |
| A2 | 1.35 | 1.40 | 1.45 | 0.0531 | 0.0551 | 0.0570 |
| $b^{(9)(11)}$ | 0.17 | 0.22 | 0.27 | 0.0067 | 0.0087 | 0.0106 |
| b1 ${ }^{(11)}$ | 0.17 | 0.20 | 0.23 | 0.0067 | 0.0079 | 0.0091 |
| $c^{(11)}$ | 0.09 | - | 0.20 | 0.0035 | - | 0.0079 |
| c1 ${ }^{(11)}$ | 0.09 | - | 0.16 | 0.0035 | - | 0.0063 |
| $D^{(4)}$ | 12.00 BSC |  |  | 0.4724 BSC |  |  |
| D1 ${ }^{(2)(5)}$ | 10.00 BSC |  |  | 0.3937 BSC |  |  |
| $E^{(4)}$ | 12.00 BSC |  |  | 0.4724 BSC |  |  |
| E1 ${ }^{(2)(5)}$ | 10.00 BSC |  |  | 0.3937 BSC |  |  |
| e | 0.50 BSC |  |  | 0.1970 BSC |  |  |
| L | 0.45 | 0.60 | 0.75 | 0.0177 | 0.0236 | 0.0295 |
| L1 | 1.00 REF |  |  | 0.0394 REF |  |  |
| $\mathrm{N}^{(13)}$ | 64 |  |  |  |  |  |
| $\theta$ | $0^{\circ}$ | $3.5^{\circ}$ | $7^{\circ}$ | $0^{\circ}$ | $3.5^{\circ}$ | $7^{\circ}$ |
| $\theta 1$ | $0^{\circ}$ | - | - | $0^{\circ}$ | - | - |
| $\theta 2$ | $10^{\circ}$ | $12^{\circ}$ | $14^{\circ}$ | $10^{\circ}$ | $12^{\circ}$ | $14^{\circ}$ |
| $\theta 3$ | $10^{\circ}$ | $12^{\circ}$ | $14^{\circ}$ | $10^{\circ}$ | $12^{\circ}$ | $14^{\circ}$ |
| R1 | 0.08 | - | - | 0.0031 | - | - |
| R2 | 0.08 | - | 0.20 | 0.0031 | - | 0.0079 |
| S | 0.20 | - | - | 0.0079 | - | - |
| aaa ${ }^{(1)}$ | 0.20 |  |  | 0.0079 |  |  |
| bbb ${ }^{(1)}$ | 0.20 |  |  | 0.0079 |  |  |
| $\mathrm{ccc}^{(1)}$ | 0.08 |  |  | 0.0031 |  |  |
| $\mathrm{ddd}^{(1)}$ | 0.08 |  |  | 0.0031 |  |  |# Notes: 

1. Dimensioning and tolerancing schemes conform to ASME Y14.5M-1994.
2. The Top package body size may be smaller than the bottom package size by as much as 0.15 mm .
3. Datums A-B and D to be determined at datum plane H .
4. To be determined at seating datum plane $C$.
5. Dimensions D1 and E1 do not include mold flash or protrusions. Allowable mold flash or protrusions is " 0.25 mm " per side. D1 and E1 are Maximum plastic body size dimensions including mold mismatch.
6. Details of pin 1 identifier are optional but must be located within the zone indicated.
7. All Dimensions are in millimeters.
8. No intrusion allowed inwards the leads.
9. Dimension "b" does not include dambar protrusion. Allowable dambar protrusion shall not cause the lead width to exceed the maximum "b" dimension by more than 0.08 mm . Dambar cannot be located on the lower radius or the foot. Minimum space between protrusion and an adjacent lead is 0.07 mm for 0.4 mm and 0.5 mm pitch packages.
10. Exact shape of each corner is optional.
11. These dimensions apply to the flat section of the lead between 0.10 mm and 0.25 mm from the lead tip.
12. A1 is defined as the distance from the seating plane to the lowest point on the package body.
13. " $N$ " is the number of terminal positions for the specified body size.
14. Values in inches are converted from mm and rounded to 4 decimal digits.
15. Drawing is not to scale.

Figure 90. LQFP64 - Footprint example
![img-109.jpeg](img-109.jpeg)

1. Dimensions are expressed in millimeters.# Device marking for LQFP64 

The following figure gives an example of topside marking orientation versus pin 1 identifier location.

The printed markings may differ depending on the supply chain.
Other optional marking or inset/upset marks, which also depend on supply chain operations, are not indicated below.

Figure 91. LQFP64 marking example (package top view)
![img-110.jpeg](img-110.jpeg)

1. Parts marked as ES or E or accompanied by an Engineering Sample notification letter are not yet qualified and therefore not approved for use in production. ST is not responsible for any consequences resulting from such use. In no event will ST be liable for the customer using any of these engineering samples in production. ST's Quality department must be contacted prior to any decision to use these engineering samples to run a qualification activity.# 6.4 WLCSP90 package information (B01C) 

WLCSP is a 90 balls, $4.20 \times 3.95 \mathrm{~mm}, 0.4 \mathrm{~mm}$ pitch, wafer level chip scale package.
Figure 92. WLCSP90 - Outline
![img-111.jpeg](img-111.jpeg)

1. Drawing is not to scale.
2. Dimension is measured at the maximum bump diameter parallel to primary datum $Z$.
3. Primary datum $Z$ and seating plane are defined by the spherical crowns of the bump.
4. Bump position designation per JESD 95-1, SPP-010.

Table 159. WLCSP90 - Mechanical data

| Symbol | millimeters |  |  | inches $\left.{ }^{(1)}\right.$ |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | Min | Typ | Max | Min | Typ | Max |
| $A^{(2)}$ | - | - | 0.59 | - | - | 0.023 |
| A1 | - | 0.18 | - | - | 0.007 | - |
| A2 | - | 0.38 | - | - | 0.015 | - |
| $A 3^{(3)}$ | - | 0.025 | - | - | 0.001 | - |
| b | 0.22 | 0.25 | 0.28 | 0.009 | 0.010 | 0.011 |
| D | 4.19 | 4.20 | 4.21 | 0.165 | 0.165 | 0.166 |
| E | 3.93 | 3.95 | 3.97 | 0.155 | 0.156 | 0.156 |
| e | - | 0.40 | - | - | 0.016 | - |Table 159. WLCSP90 - Mechanical data (continued)

| Symbol | millimeters |  |  | inches $^{(1)}$ |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | Min | Typ | Max | Min | Typ | Max |
| e1 | - | 3.40 | - | - | 0.134 | - |
| e2 | - | 3.12 | - | - | 0.123 | - |
| $F^{(4)}$ | - | 0.400 | - | - | 0.016 | - |
| $G^{(4)}$ | - | 0.416 | - | - | 0.016 | - |
| aaa | - | - | 0.10 | - | - | 0.004 |
| bbb | - | - | 0.10 | - | - | 0.004 |
| ccc | - | - | 0.10 | - | - | 0.004 |
| ddd | - | - | 0.05 | - | - | 0.002 |
| eee | - | - | 0.05 | - | - | 0.002 |

1. Values in inches are converted from mm and rounded to 4 decimal digits.
2. The maximum total package height is calculated by the RSS method (Root Sum Square) using nominal and tolerances values of A1 and A2.
3. Back side coating. Nominal dimension is rounded to the 3rd decimal place resulting from process capability.
4. Calculated dimensions are rounded to the 3rd decimal place

Figure 93. WLCSP90 - Recommended footprint
![img-112.jpeg](img-112.jpeg)

Table 160. WLCSP90 - Recommended PCB design rules

| Dimension | Recommended values |
| :-- | :-- |
| Pitch | 0.4 mm |
| Dpad | 0,225 mm |
| Dsm | 0.290 mm typ. (depends on soldermask registration tolerance) |
| Stencil opening | 0.250 mm |
| Stencil thickness | 0.100 mm |# Device marking for WLCSP90 

The following figure gives an example of topside marking orientation versus pin 1 identifier location.

The printed markings may differ depending on the supply chain.
Other optional marking or inset/upset marks, which also depend on supply chain operations, are not indicated below.

Figure 94. WLCSP90 marking example (package top view)
![img-113.jpeg](img-113.jpeg)

1. Parts marked as ES or E or accompanied by an Engineering Sample notification letter are not yet qualified and therefore not approved for use in production. ST is not responsible for any consequences resulting from such use. In no event will ST be liable for the customer using any of these engineering samples in production. ST's Quality department must be contacted prior to any decision to use these engineering samples to run a qualification activity.# 6.5 LQFP100 package information (1L) 

This LQFP is 100 lead, $14 \times 14 \mathrm{~mm}$ low-profile quad flat package.
Note: $\quad$ See list of notes in the notes section.
Figure 95. LQFP100 - Outline ${ }^{(15)}$
![img-114.jpeg](img-114.jpeg)Table 161. LQFP100 - Mechanical data

| Symbol | millimeters |  |  | inches ${ }^{(14)}$ |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | Min | Typ | Max | Min | Typ | Max |
| A | - | 1.50 | 1.60 | - | 0.0590 | 0.0630 |
| A1 ${ }^{(12)}$ | 0.05 | - | 0.15 | 0.0019 | - | 0.0059 |
| A2 | 1.35 | 1.40 | 1.45 | 0.0531 | 0.0551 | 0.0570 |
| $b^{(9)(11)}$ | 0.17 | 0.22 | 0.27 | 0.0067 | 0.0087 | 0.0106 |
| b1 ${ }^{(11)}$ | 0.17 | 0.20 | 0.23 | 0.0067 | 0.0079 | 0.0090 |
| $c^{(11)}$ | 0.09 | - | 0.20 | 0.0035 | - | 0.0079 |
| c1 ${ }^{(11)}$ | 0.09 | - | 0.16 | 0.0035 | - | 0.0063 |
| $D^{(4)}$ | 16.00 BSC |  |  | 0.6299 BSC |  |  |
| D1 ${ }^{(2)(5)}$ | 14.00 BSC |  |  | 0.5512 BSC |  |  |
| $E^{(4)}$ | 16.00 BSC |  |  | 0.6299 BSC |  |  |
| E1 ${ }^{(2)(5)}$ | 14.00 BSC |  |  | 0.5512 BSC |  |  |
| e | 0.50 BSC |  |  | 0.0197 BSC |  |  |
| L | 0.45 | 0.60 | 0.75 | 0.177 | 0.0236 | 0.0295 |
| L1 ${ }^{(1)(11)}$ | 1.00 |  |  | - | 0.0394 | - |
| $\mathrm{N}^{(13)}$ | 100 |  |  |  |  |  |
| $\theta$ | $0^{\circ}$ | $3.5^{\circ}$ | $7^{\circ}$ | $0^{\circ}$ | $3.5^{\circ}$ | $7^{\circ}$ |
| $\theta 1$ | $0^{\circ}$ | - | - | $0^{\circ}$ | - | - |
| $\theta 2$ | $10^{\circ}$ | $12^{\circ}$ | $14^{\circ}$ | $10^{\circ}$ | $12^{\circ}$ | $14^{\circ}$ |
| $\theta 3$ | $10^{\circ}$ | $12^{\circ}$ | $14^{\circ}$ | $10^{\circ}$ | $12^{\circ}$ | $14^{\circ}$ |
| R1 | 0.08 | - | - | 0.0031 | - | - |
| R2 | 0.08 | - | 0.20 | 0.0031 | - | 0.0079 |
| S | 0.20 | - | - | 0.0079 | - | - |
| aaa ${ }^{(1)}$ | 0.20 |  |  | 0.0079 |  |  |
| bbb $^{(1)}$ | 0.20 |  |  | 0.0079 |  |  |
| $\mathrm{ccc}^{(1)}$ | 0.08 |  |  | 0.0031 |  |  |
| $\mathrm{ddd}^{(1)}$ | 0.08 |  |  | 0.0031 |  |  |# Notes: 

1. Dimensioning and tolerancing schemes conform to ASME Y14.5M-1994.
2. The Top package body size may be smaller than the bottom package size by as much as 0.15 mm .
3. Datums A-B and D to be determined at datum plane H .
4. To be determined at seating datum plane $C$.
5. Dimensions D1 and E1 do not include mold flash or protrusions. Allowable mold flash or protrusions is " 0.25 mm " per side. D1 and E1 are Maximum plastic body size dimensions including mold mismatch.
6. Details of pin 1 identifier are optional but must be located within the zone indicated.
7. All Dimensions are in millimeters.
8. No intrusion allowed inwards the leads.
9. Dimension "b" does not include dambar protrusion. Allowable dambar protrusion shall not cause the lead width to exceed the maximum "b" dimension by more than 0.08 mm . Dambar cannot be located on the lower radius or the foot. Minimum space between protrusion and an adjacent lead is 0.07 mm for 0.4 mm and 0.5 mm pitch packages.
10. Exact shape of each corner is optional.
11. These dimensions apply to the flat section of the lead between 0.10 mm and 0.25 mm from the lead tip.
12. A1 is defined as the distance from the seating plane to the lowest point on the package body.
13. " $N$ " is the number of terminal positions for the specified body size.
14. Values in inches are converted from mm and rounded to 4 decimal digits.
15. Drawing is not to scale.

Figure 96. LQFP100 - Footprint example
![img-115.jpeg](img-115.jpeg)

1. Dimensions are expressed in millimeters.# Device marking for LQFP100 

The following figure gives an example of topside marking orientation versus pin 1 identifier location. The printed markings may differ depending on the supply chain.

Other optional marking or inset/upset marks, which also depend on supply chain operations, are not indicated below.

Figure 97. LQFP100 marking example (package top view)
![img-116.jpeg](img-116.jpeg)

1. Parts marked as ES or E or accompanied by an Engineering Sample notification letter are not yet qualified and therefore not approved for use in production. ST is not responsible for any consequences resulting from such use. In no event will ST be liable for the customer using any of these engineering samples in production. ST's Quality department must be contacted prior to any decision to use these engineering samples to run a qualification activity.# 6.6 UFBGA132 package information (A0G8) 

This UFBGA is a 132-ball, $7 \times 7 \mathrm{~mm}$ ultra thin fine pitch ball grid array package.
Figure 98. UFBGA132 - Outline
![img-117.jpeg](img-117.jpeg)

1. Drawing is not to scale.

Table 162. UFBGA132 - Mechanical data

| Symbol | millimeters |  |  | inches $\left.{ }^{(1)}\right.$ |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | Min | Typ | Max | Min | Typ | Max |
| A | - | - | 0.600 | - | - | 0.0236 |
| A1 | - | - | 0.110 | - | - | 0.0043 |
| A2 | - | 0.450 | - | - | 0.0177 | - |
| A3 | - | 0.130 | - | - | 0.0051 | - |
| A4 | - | 0.320 | - | - | 0.0126 | - |
| b | 0.240 | 0.290 | 0.340 | 0.0094 | 0.0114 | 0.0134 |
| D | 6.850 | 7.000 | 7.150 | 0.2697 | 0.2756 | 0.2815 |
| D1 | - | 5.500 | - | - | 0.2165 | - |
| E | 6.850 | 7.000 | 7.150 | 0.2697 | 0.2756 | 0.2815 |
| E1 | - | 5.500 | - | - | 0.2165 | - |Table 162. UFBGA132 - Mechanical data (continued)

| Symbol | millimeters |  |  | inches $\left.{ }^{(1)}\right.$ |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | Min | Typ | Max | Min | Typ | Max |
| e | - | 0.500 | - | - | 0.0197 | - |
| Z | - | 0.750 | - | - | 0.0295 | - |
| ddd | - | 0.080 | - | - | 0.0031 | - |
| eee | - | 0.150 | - | - | 0.0059 | - |
| fff | - | 0.050 | - | - | 0.0020 | - |

1. Values in inches are converted from mm and rounded to 4 decimal digits.

Figure 99. UFBGA132 - Footprint example
![img-118.jpeg](img-118.jpeg)

Table 163. UFBGA132 - Example of PCB design rules ( 0.5 mm pitch BGA)

| Dimension | Values |
| :-- | :-- |
| Pitch | 0.5 mm |
| Dpad | 0.280 mm |
| Dsm | 0.370 mm typ. (depends on the soldermask <br> registration tolerance) |
| Stencil opening | 0.280 mm |
| Stencil thickness | Between 0.100 mm and 0.125 mm |
| Pad trace width | 0.100 mm |
| Ball diameter | 0.280 mm |# Device marking for UFBGA132 

The following figure gives an example of topside marking orientation versus pin 1 identifier location.

The printed markings may differ depending on the supply chain.
Other optional marking or inset/upset marks, which also depend on supply chain operations, are not indicated below.

Figure 100. UFBGA132 marking example (package top view)
![img-119.jpeg](img-119.jpeg)

1. Parts marked as ES or E or accompanied by an Engineering Sample notification letter are not yet qualified and therefore not approved for use in production. ST is not responsible for any consequences resulting from such use. In no event will ST be liable for the customer using any of these engineering samples in production. ST's Quality department must be contacted prior to any decision to use these engineering samples to run a qualification activity.# 6.7 LQFP144 package information (1A) 

This LQFP is a 144-pin, $20 \times 20 \mathrm{~mm}$ low-profile quad flat package.
Note: $\quad$ See list of notes in the notes section.
Figure 101. LQFP144 - Outline ${ }^{(15)}$
![img-120.jpeg](img-120.jpeg)Table 164. LQFP144 - Mechanical data

| Symbol | millimeters |  |  | inches ${ }^{(14)}$ |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | Min | Typ | Max | Min | Typ | Max |
| A | - | - | 1.60 | - | - | 0.0630 |
| A1 ${ }^{(12)}$ | 0.05 | - | 0.15 | 0.0020 | - | 0.0059 |
| A2 | 1.35 | 1.40 | 1.45 | 0.0531 | 0.0551 | 0.0571 |
| $b^{(9)(11)}$ | 0.17 | 0.22 | 0.27 | 0.0067 | 0.0087 | 0.0106 |
| b1 ${ }^{(11)}$ | 0.17 | 0.20 | 0.23 | 0.0067 | 0.0079 | 0.0090 |
| $c^{(11)}$ | 0.09 | - | 0.20 | 0.0035 | - | 0.0079 |
| c1 ${ }^{(11)}$ | 0.09 | - | 0.16 | 0.0035 | - | 0.0063 |
| $D^{(4)}$ | 22.00 BSC |  |  | 0.8661 BSC |  |  |
| D1 ${ }^{(2)(5)}$ | 20.00 BSC |  |  | 0.7874 BSC |  |  |
| $E^{(4)}$ | 22.00 BSC |  |  | 0.8661 BSC |  |  |
| E1 ${ }^{(2)(5)}$ | 20.00 BSC |  |  | 0.7874 BSC |  |  |
| e | 0.50 BSC |  |  | 0.0197 BSC |  |  |
| L | 0.45 | 0.60 | 0.75 | 0.0177 | 0.0236 | 0.0295 |
| L1 | 1.00 REF |  |  | 0.0394 REF |  |  |
| $\mathrm{N}^{(13)}$ | 144 |  |  |  |  |  |
| $\theta$ | $0^{\circ}$ | $3.5^{\circ}$ | $7^{\circ}$ | $0^{\circ}$ | $3.5^{\circ}$ | $7^{\circ}$ |
| $\theta 1$ | $0^{\circ}$ | - | - | $0^{\circ}$ | - | - |
| $\theta 2$ | $10^{\circ}$ | $12^{\circ}$ | $14^{\circ}$ | $10^{\circ}$ | $12^{\circ}$ | $14^{\circ}$ |
| $\theta 3$ | $10^{\circ}$ | $12^{\circ}$ | $14^{\circ}$ | $10^{\circ}$ | $12^{\circ}$ | $14^{\circ}$ |
| R1 | 0.08 | - | - | 0.0031 | - | - |
| R2 | 0.08 | - | 0.20 | 0.0031 | - | 0.0079 |
| S | 0.20 | - | - | 0.0079 | - | - |
| aaa | 0.20 |  |  | 0.0079 |  |  |
| bbb | 0.20 |  |  | 0.0079 |  |  |
| ccc | 0.08 |  |  | 0.0031 |  |  |
| ddd | 0.08 |  |  | 0.0031 |  |  |# Notes: 

1. Dimensioning and tolerancing schemes conform to ASME Y14.5M-1994.
2. The Top package body size may be smaller than the bottom package size by as much as 0.15 mm .
3. Datums A-B and D to be determined at datum plane H .
4. To be determined at seating datum plane $C$.
5. Dimensions D1 and E1 do not include mold flash or protrusions. Allowable mold flash or protrusions is " 0.25 mm " per side. D1 and E1 are Maximum plastic body size dimensions including mold mismatch.
6. Details of pin 1 identifier are optional but must be located within the zone indicated.
7. All Dimensions are in millimeters.
8. No intrusion allowed inwards the leads.
9. Dimension "b" does not include dambar protrusion. Allowable dambar protrusion shall not cause the lead width to exceed the maximum "b" dimension by more than 0.08 mm . Dambar cannot be located on the lower radius or the foot. Minimum space between protrusion and an adjacent lead is 0.07 mm for 0.4 mm and 0.5 mm pitch packages.
10. Exact shape of each corner is optional.
11. These dimensions apply to the flat section of the lead between 0.10 mm and 0.25 mm from the lead tip.
12. A1 is defined as the distance from the seating plane to the lowest point on the package body.
13. " $N$ " is the number of terminal positions for the specified body size.
14. Values in inches are converted from mm and rounded to 4 decimal digits.
15. Drawing is not to scale.Figure 102. LQFP144 - Footprint example
![img-121.jpeg](img-121.jpeg)

1. Dimensions are expressed in millimeters.# Device marking for LQFP144 

The following figure gives an example of topside marking orientation versus pin 1 identifier location.

The printed markings may differ depending on the supply chain.
Other optional marking or inset/upset marks, which also depend on supply chain operations, are not indicated below.

Figure 103. LQFP144 marking example (package top view)
![img-122.jpeg](img-122.jpeg)

1. Parts marked as ES or E or accompanied by an Engineering Sample notification letter are not yet qualified and therefore not approved for use in production. ST is not responsible for any consequences resulting from such use. In no event will ST be liable for the customer using any of these engineering samples in production. ST's Quality department must be contacted prior to any decision to use these engineering samples to run a qualification activity.# 6.8 UFBGA169 package information (A0YV) 

This UFBGA is a 169-ball, $7 \times 7 \mathrm{~mm}, 0.50 \mathrm{~mm}$ pitch, ultra fine pitch ball grid array package.
Figure 104. UFBGA169 - Outline
![img-123.jpeg](img-123.jpeg)

1. Drawing is not to scale.

Table 165. UFBGA169 - Mechanical data

| Symbol | millimeters |  |  | inches $^{(1)}$ |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | Min. | Typ. | Max. | Min. | Typ. | Max. |
| A | 0.460 | 0.530 | 0.600 | 0.0181 | 0.0209 | 0.0236 |
| A1 | 0.050 | 0.080 | 0.110 | 0.0020 | 0.0031 | 0.0043 |
| A2 | 0.400 | 0.450 | 0.500 | 0.0157 | 0.0177 | 0.0197 |
| A3 | - | 0.130 | - | - | 0.0051 | - |
| A4 | 0.270 | 0.320 | 0.370 | 0.0106 | 0.0126 | 0.0146 |
| b | 0.230 | 0.280 | 0.330 | 0.0091 | 0.0110 | 0.0130 |
| D | 6.950 | 7.000 | 7.050 | 0.2736 | 0.2756 | 0.2776 |
| D1 | 5.950 | 6.000 | 6.050 | 0.2343 | 0.2362 | 0.2382 |
| E | 6.950 | 7.000 | 7.050 | 0.2736 | 0.2756 | 0.2776 |
| E1 | 5.950 | 6.000 | 6.050 | 0.2343 | 0.2362 | 0.2382 |Table 165. UFBGA169 - Mechanical data (continued)

| Symbol | millimeters |  |  | inches $\left({ }^{1}\right)$ |  |  |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: |
|  | Min. | Typ. | Max. | Min. | Typ. | Max. |
| e | - | 0.500 | - | - | 0.0197 | - |
| F | 0.450 | 0.500 | 0.550 | 0.0177 | 0.0197 | 0.0217 |
| ddd | - | - | 0.100 | - | - | 0.0039 |
| eee | - | - | 0.150 | - | - | 0.0059 |
| fff | - | - | 0.050 | - | - | 0.0020 |

1. Values in inches are converted from mm and rounded to 4 decimal digits.

Figure 105. UFBGA169 - Footprint example
![img-124.jpeg](img-124.jpeg)

Table 166. UFBGA169 - Example of PCB design rules ( 0.5 mm pitch BGA)

| Dimension | Values |
| :-- | :-- |
| Pitch | 0.5 mm |
| Dpad | 0.27 mm |
| Dsm | 0.35 mm typ. (depends on the soldermask <br> registration tolerance) |
| Solder paste | 0.27 mm aperture diameter. |

Note: Non-solder mask defined (NSMD) pads are recommended.
Note: 4 to 6 mils solder paste screen printing process.# Device marking for UFBGA169 

The following figure gives an example of topside marking orientation versus pin 1 identifier location.

The printed markings may differ depending on the supply chain.
Other optional marking or inset/upset marks, which also depend on supply chain operations, are not indicated below.

Figure 106. UFBGA169 marking example (package top view)
![img-125.jpeg](img-125.jpeg)

1. Parts marked as ES or E or accompanied by an Engineering Sample notification letter are not yet qualified and therefore not approved for use in production. ST is not responsible for any consequences resulting from such use. In no event will ST be liable for the customer using any of these engineering samples in production. ST's Quality department must be contacted prior to any decision to use these engineering samples to run a qualification activity.# 6.9 Package thermal characteristics 

The maximum chip-junction temperature, $\mathrm{T}_{\mathrm{J}}$ max, in degrees Celsius, can be calculated using the following equation:
$\mathrm{T}_{\mathrm{J}} \max =\mathrm{T}_{\mathrm{A}} \max +\left(\mathrm{P}_{\mathrm{D}} \max \times \Theta_{\mathrm{JA}}\right)$
where:

- $\quad T_{A}$ max is the maximum ambient temperature in ${ }^{\circ} \mathrm{C}$.
- $\quad \Theta_{J A}$ is the package junction-to-ambient thermal resistance in ${ }^{\circ} \mathrm{C} / \mathrm{W}$.
- $\quad P_{D}$ max is the sum of $P_{\text {INT }}$ max and $P_{I / O}$ max ( $P_{D} \max =P_{\text {INT }} \max +P_{I / O} \max$ ).
- $\quad P_{\text {INT }}$ max is the product of $\mathrm{I}_{\mathrm{DD}}$ and $\mathrm{V}_{\mathrm{DD}}$, expressed in Watts. This is the maximum chip internal power.
$\mathrm{P}_{\mathrm{I} / \mathrm{O}}$ max represents the maximum power dissipation on output pins:
$\mathrm{P}_{\mathrm{I} / \mathrm{O}} \max =\sum\left(\mathrm{V}_{\mathrm{OL}} \times \mathrm{I}_{\mathrm{OL}}\right)+\sum\left(\left(\mathrm{V}_{\mathrm{DDIOx}}-\mathrm{V}_{\mathrm{OH}}\right) \times \mathrm{I}_{\mathrm{OH}}\right)$
taking into account the actual $\mathrm{V}_{\mathrm{OL}} / \mathrm{I}_{\mathrm{OL}}$ and $\mathrm{V}_{\mathrm{OH}} / \mathrm{I}_{\mathrm{OH}}$ of the $\mathrm{I} / \mathrm{Os}$ at low and high level in the application.Table 167. Package thermal characteristics

| Symbol | Parameter | Package | Value | Unit |
| :--: | :--: | :--: | :--: | :--: |
| $\Theta_{\text {JA }}$ | Thermal resistance junction-ambient | LQFP48 $7 \times 7 \mathrm{~mm}$ | 45.8 | ${ }^{\circ} \mathrm{C} / \mathrm{W}$ |
|  |  | UFQFPN48 $7 \times 7 \mathrm{~mm}$ | 26.9 |  |
|  |  | LQFP64 $10 \times 10 \mathrm{~mm}$ | 39.6 |  |
|  |  | WLCSP90 $4.2 \times 3.95 \mathrm{~mm}$ | 42.3 |  |
|  |  | LQFP100 - $14 \times 14 \mathrm{~m}$ | 34.4 |  |
|  |  | UFBGA132 $7 \times 7 \mathrm{~mm}$ | 35.2 |  |
|  |  | LQFP144 $20 \times 20 \mathrm{~mm}$ | 35.9 |  |
|  |  | UFBGA169 $7 \times 7 \mathrm{~mm}$ | 33.7 |  |
| $\Theta_{\text {JB }}$ | Thermal resistance junction-board | LQFP48 $7 \times 7 \mathrm{~mm}$ | 23.4 |  |
|  |  | UFQFPN48 $7 \times 7 \mathrm{~mm}$ | 11.2 |  |
|  |  | LQFP64 $10 \times 10 \mathrm{~mm}$ | 22 |  |
|  |  | WLCSP90 $4.2 \times 3.95 \mathrm{~mm}$ | 27.5 |  |
|  |  | LQFP100 - $14 \times 14 \mathrm{~m}$ | 20.3 |  |
|  |  | UFBGA132 $7 \times 7 \mathrm{~mm}$ | 20.7 |  |
|  |  | LQFP144 $20 \times 20 \mathrm{~mm}$ | 24.8 |  |
|  |  | UFBGA169 $7 \times 7 \mathrm{~mm}$ | 19.3 |  |
| $\Theta_{\text {JC }}$ | Thermal resistance junction-top case | LQFP48 $7 \times 7 \mathrm{~mm}$ | 10.7 |  |
|  |  | UFQFPN48 $7 \times 7 \mathrm{~mm}$ | 8 |  |
|  |  | LQFP64 $10 \times 10 \mathrm{~mm}$ | 9.0 |  |
|  |  | WLCSP90 $4.2 \times 3.95 \mathrm{~mm}$ | 1.6 |  |
|  |  | LQFP100 - $14 \times 14 \mathrm{~m}$ | 7.4 |  |
|  |  | UFBGA132 $7 \times 7 \mathrm{~mm}$ | 8.3 |  |
|  |  | LQFP144 $20 \times 20 \mathrm{~mm}$ | 7.6 |  |
|  |  | UFBGA169 $7 \times 7 \mathrm{~mm}$ | 8.3 |  |

# 6.9.1 Reference documents 

- JESD51-2 Integrated Circuits Thermal Test Method Environment Conditions - Natural Convection (Still Air) available on www.jedec.org.
- For information on thermal management, refer to application note "Guidelines for thermal management on STM32 applications" (AN5036) available on www.st.com.# 7 Ordering information 

![img-126.jpeg](img-126.jpeg)

For a list of available options (such as speed or package) or for further information on any aspect of this device, contact the nearest ST sales office.# 8 Important security notice 

The STMicroelectronics group of companies (ST) places a high value on product security, which is why the ST product(s) identified in this documentation may be certified by various security certification bodies and/or may implement our own security measures as set forth herein. However, no level of security certification and/or built-in security measures can guarantee that ST products are resistant to all forms of attacks. As such, it is the responsibility of each of ST's customers to determine if the level of security provided in an ST product meets the customer needs both in relation to the ST product alone, as well as when combined with other components and/or software for the customer end product or application. In particular, take note that:

- ST products may have been certified by one or more security certification bodies, such as Platform Security Architecture (www.psacertified.org) and/or Security Evaluation standard for loT Platforms (www.trustcb.com). For details concerning whether the ST product(s) referenced herein have received security certification along with the level and current status of such certification, either visit the relevant certification standards website or go to the relevant product page on www.st.com for the most up to date information. As the status and/or level of security certification for an ST product can change from time to time, customers should re-check security certification status/level as needed. If an ST product is not shown to be certified under a particular security standard, customers should not assume it is certified.
- Certification bodies have the right to evaluate, grant and revoke security certification in relation to ST products. These certification bodies are therefore independently responsible for granting or revoking security certification for an ST product, and ST does not take any responsibility for mistakes, evaluations, assessments, testing, or other activity carried out by the certification body with respect to any ST product.
- Industry-based cryptographic algorithms (such as AES, DES, or MD5) and other open standard technologies which may be used in conjunction with an ST product are based on standards which were not developed by ST. ST does not take responsibility for any flaws in such cryptographic algorithms or open technologies or for any methods which have been or may be developed to bypass, decrypt or crack such algorithms or technologies.
- While robust security testing may be done, no level of certification can absolutely guarantee protections against all attacks, including, for example, against advanced attacks which have not been tested for, against new or unidentified forms of attack, or against any form of attack when using an ST product outside of its specification or intended use, or in conjunction with other components or software which are used by customer to create their end product or application. ST is not responsible for resistance against such attacks. As such, regardless of the incorporated security features and/or any information or support that may be provided by ST, each customer is solely responsible for determining if the level of attacks tested for meets their needs, both in relation to the ST product alone and when incorporated into a customer end product or application.
- All security features of ST products (inclusive of any hardware, software, documentation, and the like), including but not limited to any enhanced security features added by ST, are provided on an "AS IS" BASIS. AS SUCH, TO THE EXTENT PERMITTED BY APPLICABLE LAW, ST DISCLAIMS ALL WARRANTIES, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE IMPLIED WARRANTIES OF MERCHANTABILITY OR FITNESS FOR A PARTICULAR PURPOSE, unless the applicable written and signed contract terms specifically provide otherwise.# 9 Revision history 

Table 168. Document revision history

| Date | Revision | Changes |
| :--: | :--: | :--: |
| 02-Sep-2021 | 1 | Initial release. |
| 24-Sep-2021 | 2 | Updated: <br> - Figure 24 and Figure 25: STM32U585xQ power supply scheme (with SMPS) <br> - Figure 28: AC timing diagram for high-speed external clock source <br> - Figure 29: AC timing diagram for low-speed external square clock source <br> $-\mathrm{V}_{\text {DDCoeff }}$ values in Table 36: Embedded internal voltage reference <br> $-\mathrm{I}_{\mathrm{DD}(\mathrm{RUN})}$ Range 2 values in Table 37 and Table 38 <br> - New consumption Table 40, Table 42, Table 45, Table 46, Table 50, Table 52, Table 54, Table 56, Table 58, Table 60, Table 66, Table 68 <br> - All values in consumption Table 53, Table 55, Table 57, Table 59, Table 65 <br> - All values in Table 71, Table 72, Table 73 <br> - USER TROM COVERAGE removed in Table 80: MSI oscillator characteristics <br> - Table 84: PLL characteristics |
| 19-Nov-2021 | 3 | Updated: <br> - Security and cryptography <br> - 'legacy' replaced by 'without SMPS' in Table 2: STM32U585xx features and peripheral counts <br> - PSSI in Table 10: Functionalities depending on the working mode <br> - Table 38 and new Table 39: Current consumption in Run mode on SMPS, code with data processing running from Flash memory, ICACHE ON (1-way), prefetch ON, $V_{D D}=3.0 \mathrm{~V}$ <br> - Table 45 and new Table 46: Current consumption in Sleep mode on SMPS, Flash memory in power down, $V_{D D}=3.0 \mathrm{~V}$ <br> - Table 47: SRAM1/SRAM3 current consumption in Run/Sleep mode with LDO and SMPS <br> - $\mathrm{t}_{\text {WU }}$ (Sleep) max in Table 74: Low-power mode wakeup timings on SMPS <br> - Footnote 8 on Table 82: MSI oscillator characteristics <br> $-\mathrm{t}_{\mathrm{SU}(\mathrm{RX})}$ in Table 147: USART characteristics <br> - Section 6.5: LQFP100 package information |
| 13-Dec-2021 | 4 | Updated: <br> - FMC_A16 and FMC_A17 in Table 26: STM32U585xx pin definitions and Table 28: Alternate function AF8 to AF15 <br> - New $\mathrm{I}_{\text {UBAT_BOR_sampling }}$ in Table 34: Embedded reset and power control block characteristics <br> - $\mathrm{C}_{\mathrm{S} \text { _PARA }}$ in Table 79: LSE oscillator characteristics ( $f_{L S E}=32.768 \mathrm{kHz}$ ) <br> - Figure 32: Typical application with a 32.768 kHz crystal |
| 13-Mar-2022 | 5 | Updated: <br> - GPIOs and capacitive sensing in Table 2: STM32U585xx features and peripheral counts <br> - Figure 1: STM32U585xx block diagram <br> $-\mathrm{V}_{\text {BAT }}$ in Section 3.9.1: Power supply schemes |Table 168. Document revision history (continued)

| Date | Revision | Changes |
| :--: | :--: | :--: |
| 13-Mar-2022 | 5 (cont'd) | - Backup domain in Figure 2 and Figure 3: STM32U585xx power supply overview (without SMPS) <br> - IWDG in Table 10: Functionalities depending on the working mode <br> - New sentence beg. of Section 3.25: Octo-SPI interface (OCTOSPI) <br> - Section 3.25.1: OCTOSPI TrustZone security <br> - Figure 9: UFQFPN48_SMPS pinout <br> - PB2 I/O structure in Table 27: STM32U585xx pin definitions <br> - Notes of Table 51: Current consumption in Stop 1 mode on LDO <br> - Table 52: Current consumption during wakeup from Stop 1 mode on LDO <br> - Notes of Table 53: Current consumption in Stop 1 mode on SMPS <br> - Table 54: Current consumption during wakeup from Stop 1 mode on SMPS <br> - Table SRAM static power consumption in Stop 2 when supplied by LDO moved <br> - Notes of Table 55: Current consumption in Stop 2 mode on LDO <br> - Table 57: Current consumption during wakeup from Stop 2 mode on LDO <br> - Table SRAM static power consumption in Stop 2 when supplied by SMPS moved <br> - Table 60: Current consumption during wakeup from Stop 2 mode on SMPS <br> - Notes of Table 58: Current consumption in Stop 2 mode on SMPS <br> - Table SRAM static power consumption in Stop 3 when supplied by LDO moved <br> - Table 63: Current consumption during wakeup from Stop 3 mode on LDO <br> - Table SRAM static power consumption in Stop 3 when supplied by SMPS moved <br> - Notes of Table 64: Current consumption in Stop 3 mode on SMPS <br> - Table 66: Current consumption during wakeup from Stop 3 mode on SMPS <br> - Table 68: Current consumption during wakeup from Standby mode <br> - Notes of Table 69: Current consumption in Shutdown mode <br> - Table 70: Current consumption during wakeup from Shutdown mode <br> - $\operatorname{teu}($ sleep $)$ and notes of Table 73: Low-power mode wakeup timings on LDO <br> - Notes Table 75: Regulator mode transition times <br> - Output driving current <br> - Notes of Table 95: Output voltage characteristics <br> - New Table 96: Output voltage characteristics for FT_t I/Os in Vbat mode <br> - Notes of Table 97: Output AC characteristics, HSLV OFF (all I/Os except FT_c) <br> - Notes of Table 98: Output AC characteristics, HSLV ON (all I/Os except FT_c) <br> - Table 100: Output AC characteristics for FT_t I/Os in Vbat mode <br> - fAHB_CAL removed from Table 104: 14-bit ADC1 characteristics <br> - Table 114: DAC characteristics <br> - RLoad and en in Table 118: OPAMP characteristics <br> - New Figure 44: OPAMP voltage noise density, normal mode, RLOAD $=3.9 \mathrm{k} \Omega$ and Figure 45: OPAMP voltage noise density, low-power mode, RLOAD $=20 \mathrm{k} \Omega$ <br> - tLv(NOE_NE) in Table 131: Asynchronous multiplexed PSRAM/NOR read timings <br> - Section 6.2: LQFP48 package information <br> - Section 6.3: LQFP64 package information <br> - Section 6.5: LQFP100 package information <br> - Section 6.7: LQFP144 package information <br> - Disclaimer |Table 168. Document revision history (continued)

| Date | Revision | Changes |
| :--: | :--: | :--: |
| 2-Jun-2022 | 6 | Added: <br> - Section 8: Important security notice <br> Updated: <br> - Up to 22 capacitive sensing channels <br> - Section 2: Description <br> - Table 2.: STM32U585xx features and peripheral counts <br> - Section 3.36: Touch sensing controller (TSC) <br> - TSC_G3_IO1/TSC_G1_IO4 are removed from PC2/PC3 in Table 27.: STM32U585xx pin definitions and Table 29.: Alternate function AF8 to AF15 <br> - Table 72.: Typical dynamic current consumption of peripherals <br> - Table 90: EMI characteristics for $f_{\text {HSE }}=8 \mathrm{MHz}$ and $f_{\text {HCLK }}=160 \mathrm{MHz}$ <br> - Minimum value added for PSSR in Table 118.: OPAMP characteristics <br> - Disclaimer |
| 27-Mar-2023 | 7 | Updates related to revisions other than X: <br> - Features <br> - Table 26: Legend/abbreviations used in the pinout table <br> - Table 27: STM32U585xx pin definitions <br> - Table 51: Current consumption in Stop 1 mode on LDO <br> - Table 53: Current consumption in Stop 1 mode on SMPS <br> - Table 55: Current consumption in Stop 2 mode on LDO <br> - Table 58: Current consumption in Stop 2 mode on SMPS <br> - Table 61: Current consumption in Stop 3 mode on LDO <br> - Table 64: Current consumption in Stop 3 mode on SMPS <br> - Table 67: Current consumption in Standby mode <br> - Table 69: Current consumption in Shutdown mode <br> - Table 71: Current consumption in $V_{B A T}$ mode <br> - Table 79: HSE oscillator characteristics <br> - Table 80: LSE oscillator characteristics ( $f_{L S E}=32.768 \mathrm{kHz}$ ) <br> - Table 94: I/O static characteristics <br> - Table 95: Output voltage characteristics (all I/Os except FT_t I/Os in VBAT mode, and FT_o I/Os) <br> - Table 96: Output voltage characteristics for FT_t I/Os in $V_{B A T}$ mode, and for FT_o I/Os <br> - Table 97: Output AC characteristics, HSLV OFF (all I/Os except FT_c, FT_t in VBAT mode and FT_o I/Os) <br> - Table 100: Output AC characteristics for FT_t I/Os in $V_{B A T}$ mode, and for FT_o I/Os <br> - Table 106: 14-bit ADC1 accuracy <br> Other updates: <br> - Figure 2: STM32U585xQ power supply overview (with SMPS) <br> - Figure 3: STM32U585xx power supply overview (without SMPS) <br> - Section 3.9.1: Power supply schemes |Table 168. Document revision history (continued)

| Date | Revision | Changes |
| :--: | :--: | :--: |
| 27-Mar-2023 | 7 (cont'd) | - Section 3.9.3: Low-power modes <br> - Table 15: ADC features <br> - Section 5.1.2: Typical values <br> - Table 31: Current characteristics <br> - Table 33: General operating conditions <br> - Table 34: Operating conditions at power-up/power-down <br> - Table 35: Embedded reset and power control block characteristics <br> - Table 36: Embedded internal voltage reference <br> - Table 72: Typical dynamic current consumption of peripherals <br> - Table 73: Low-power mode wake-up timings on LDO <br> - Table 77: High-speed external user clock characteristics <br> - Output driving current <br> - Section 5.3.29: DCMI characteristics <br> - Section 5.3.30: PSSI characteristics <br> - Table 141: OCTOSPI characteristics in SDR mode <br> - Table 142: OCTOSPI characteristics in DTR mode (no DQS) <br> - Table 143: OCTOSPI characteristics in DTR mode (with DQS)/HyperBus <br> - Table 148: USART characteristics <br> - Table 149: SPI characteristics <br> - Table 150: SAI characteristics <br> Typos fix and minor changes in overall document <br> Added: <br> - USB logo in Section 1: Introduction <br> - Figure 29: AC timing diagram for high-speed external clock source (analog mode) <br> - Section 6.9.1: Reference documents |
| 04-Aug-2023 | 8 | Updated: <br> - Replaced PSA level 3 and SESIP level 3 certified by SESIP3 and PSA Level 3 Certified Assurance Target in Security and cryptography <br> - Figure 1: STM32U585xx block diagram <br> - Section 3.9.5: VBAT operation <br> - Section 3.10: Peripheral interconnect matrix <br> - Section 5.1.6: Power supply scheme <br> - Table 38: Current consumption in Run mode on LDO, code with data processing running from Flash memory, ICACHE ON (1-way), prefetch ON <br> - Table 53: Current consumption during wake-up from Stop 1 mode on LDO <br> - Table 55: Current consumption during wake-up from Stop 1 mode on SMPS <br> - Table 58: Current consumption during wake-up from Stop 2 mode on LDO <br> - Table 61: Current consumption during wake-up from Stop 2 mode on SMPS <br> - Table 64: Current consumption during wake-up from Stop 3 mode on LDO <br> - Table 67: Current consumption during wake-up from Stop 3 mode on SMPS <br> - Table 69: Current consumption during wake-up from Standby mode <br> - Table 71: Current consumption during wake-up from Shutdown mode <br> - Table 74: Low-power mode wake-up timings on LDO <br> - Table 75: Low-power mode wake-up timings on SMPS <br> - Table 76: Regulator mode transition times |Table 168. Document revision history (continued)

| Date | Revision | Changes |
| :--: | :--: | :--: |
| 04-Aug-2023 | 8 (cont'd) | - Table 78: High-speed external user clock characteristics <br> - Increased HSE consumption during startup from $8 \mu \mathrm{~A}$ to 8 mA in Table 80: HSE oscillator characteristics <br> - Table 81: LSE oscillator characteristics ( $f_{L S E}=32.768 \mathrm{kHz}$ ) <br> - Table 97: Output voltage characteristics for FT_t I/Os in $V_{B A T}$ mode, and for FT_o I/Os <br> - Table 101: Output AC characteristics for FT_t I/Os in $V_{B A T}$ mode, and for FT_o I/Os <br> - $t_{C A L}$ and $t_{O F F, C A L}$ values in Table 105: 14-bit ADC1 characteristics <br> - $t_{O F F, C A L}$ values in Table 108: 12-bit ADC4 characteristics <br> - Note added in Table 106: Maximum RAIN for 14-bit ADC1 and Table 109: Maximum RAIN for 12-bit ADC4 <br> - Section 5.3.28: Temperature and backup domain supply thresholds monitoring <br> - Figure 74: USART timing diagram in master mode <br> - Figure 75: USART timing diagram in slave mode <br> - Figure 76: SPI timing diagram - slave mode and CPHA $=0$ <br> - Figure 77: SPI timing diagram - slave mode and CPHA $=1$ <br> - Figure 78: SPI timing diagram - master mode <br> - Figure 79: SAI master timing diagram <br> - Figure 80: SAI slave timing diagram <br> - Section 6.1: UFQFPN48 package information (A0B9) <br> - Section 6.2: LQFP48 package information (5B) <br> - Section 6.3: LQFP64 package information (5W) <br> - Section 6.4: WLCSP90 package information (B01C) <br> - Section 6.5: LQFP100 package information (1L) <br> - Section 6.6: UFBGA132 package information (A0G8) <br> - Section 6.7: LQFP144 package information (1A) <br> - Section 6.8: UFBGA169 package information (A0YV) <br> Added: <br> - Table 5.3.4: SMPS characteristics |
| 19-Feb-2024 | 9 | Updated: <br> - Up to 22 communication peripherals in Features <br> - Replaced "o" by "-" for Backup domain voltage and temperature monitoring in Table 10: Functionalities depending on the working mode <br> - Figure 60: NAND controller waveforms for read access <br> - Figure 61: NAND controller waveforms for write access <br> - Figure 73: USART timing diagram in SPI master mode <br> - Figure 74: USART timing diagram in SPI slave mode <br> - Table 79: Low-speed external user clock characteristics <br> - Table 102: NRST pin characteristics <br> Added: <br> - SPI mode in Table 22: USART, UART, and LPUART features, Section 3.45.1: Universal synchronous/asynchronous receiver transmitter (USART/UART), and Section 5.3.38: USART (SPI mode) characteristics |Table 168. Document revision history (continued)

| Date | Revision | Changes |
| :--: | :--: | :--: |
| 05-Jul-2024 | 10 | Updated: <br> - Table 27: STM32U585xx pin definitions <br> - Table 28: Alternate function AF0 to AF7 <br> - Table 29: Alternate function AF8 to AF15 <br> - Table 52: Current consumption in Stop 1 mode on LDO <br> - Table 54: Current consumption in Stop 1 mode on SMPS <br> - Table 59: Current consumption in Stop 2 mode on SMPS <br> - Table 62: Current consumption in Stop 3 mode on LDO <br> - Table 65: Current consumption in Stop 3 mode on SMPS <br> Note: Table 27, Table 28 and Table 29 updates do not require any hardware or firmware change. <br> - Section 3.9.1: Power supply schemes <br> - Notes in Section 5.2: Absolute maximum ratings <br> Added: <br> - Sustainable technology logo in Features <br> - Figure 34: HSI16 frequency versus temperature and $V_{D D}$ |# IMPORTANT NOTICE - READ CAREFULLY 

STMicroelectronics NV and its subsidiaries ("ST") reserve the right to make changes, corrections, enhancements, modifications, and improvements to ST products and/or to this document at any time without notice. Purchasers should obtain the latest relevant information on ST products before placing orders. ST products are sold pursuant to ST's terms and conditions of sale in place at the time of order acknowledgment.

Purchasers are solely responsible for the choice, selection, and use of ST products and ST assumes no liability for application assistance or the design of purchasers' products.

No license, express or implied, to any intellectual property right is granted by ST herein.

Resale of ST products with provisions different from the information set forth herein shall void any warranty granted by ST for such product.

ST and the ST logo are trademarks of ST. For additional information about ST trademarks, refer to www.st.com/trademarks. All other product or service names are the property of their respective owners.

Information in this document supersedes and replaces information previously supplied in any prior versions of this document.
(c) 2024 STMicroelectronics - All rights reserved