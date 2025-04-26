# Project Mizuki Circuit Blocks - "Canned Circuits"
## Introduction
There are the circuit modules used in Project Mizuki. Some of them has been physically verified (with the “Confirmed==True” attribute) and works fine. Some of the circuit modules used libraries provided by public component libraries such as _Component Search Engine_ or _Ultra Librarian_, and the source of the symbols or packages are indicated in the circuit diagrams.

## Modules
### 1.`Mizuki_Analog`
| Name | Description | Verified? |
|---|---|---|
| `AMP_Headphone_1622` | Differential input mono headphone amplifier with OPA1622 | Yes |
| `AMP_Speaker_NJU8759A` | Mono speaker amplifier with NJU8759A class-D amplifier and NJU72344 electronic volume controller | No |
| `AMP_Speaker_SSM2315_vol` | Mono speaker amplifier with SSM2315A Hi-Fi class-D amplifier and NJU72344 electronic volume controller | Yes |
| `PREAMP_Microphone_1` | Condenser microphone preamplifier, 0~20dB | Yes |

### 2. `Mizuki_CODEC`
| Name | Description | Verified? |
|---|---|---|
| `CODEC_ES9290Q` | ESS ES9290Q circuit | No |

### 3. `Mizuki_Digital`
| Name | Description | Verified? |
|---|---|---|
| `FLASH_QSPI_W25Q128` | W25Q128 QSPI flash | Yes |
| `FLASH_OSPI_IS25xX` | IS25(W/L)* OSPI flash | No |
| `OSC_24576_Audio_Clock` | 24.576MHz clock with YXC OT3225 series oscillator | Yes |
| `RAM_OSPI_S27KL064` | Infineon S27KL064 PSRAM | No |
| `RAM_HB_W958D8` | W958D8 HyperBus PSRAM | No |
| `RST_STM32` | STM32 reset | Yes |
| `SDCard_4bit` | SDCard 4-bit mode, 3.3V only (DH/HS only) | No |
| `SDCard_4bit_Protected` | SDCard 4-bit mode, 3.3V only (DH/HS only) w/ ESD protected | No |
| `SPILCD_with_TOUCH` | ILI9341 SPI LCD with resistive touch | No | 
| `DBG_STDC14` | STDC14 interface | Yes, but needs to be updated |
| `DBG_STDC14_Protected` | STDC-14 ST-Link debug interface w/ ESD protected, updated version of `DBG_STDC14` | No |
| `XTAL_8MHZ` | 8MHz crystal circuit | Yes, but needs to be updated |
| `XTAL_8MHZ_with_adjustment` | XTAL circuit w/ external additional feedback and current limit resistor, updated version of `XTAL_8MHZ` | No |

### 3. `Mizuki_Power`
| Name | Description | Verified? |
|---|---|---|
| `BAT_Protect_Gauge` | Li-ion(3.7V) battery protection and BQ27441 fuel gauge | No |
| `CHG_MP2722` | MP2722 NVDC charger circuit | Yes |
| `PWR_Analog_1` | Cost-optimized +/-5V analog supply circuit #1 | Yes |
| `PWR_Analog_2` | Cost-optimized +/-5V analog supply circuit #2 | No |
| `PWR_ES9290Q_3V3` | Dual 3.3V analog supply for ES9290Q | Yes |
| `PWR_TPS82130_3V3` | 3.3V digital supply | Yes |
| `USB_Interface` | USB interface with switch to switch between BC identify(MP2722) and data transfer(MCU) | Yes |

## License
Lincened under BSD 3-Clause Clear License.