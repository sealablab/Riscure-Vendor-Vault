# Riscure-PXI-Index
This file decodes new/old riscure product identifiers. 

## PXI/
## Core components
* [[PXI/Riscure-DS1050A Next-Gen PXI test-bench]] Next-Generation Embedded Security Testbench
	* DS10NNN Next-Generation embedded controller (included in DS1050A)
* [[PXI/Riscure-DS1060A Pattern Based Trigger Generator]] Pattern Based Trigger Generator (next-gen PXI icWaves)
* **DS1070** Glitch Pattern Generator (next-gen PXI Spider) [[Riscure-DS1070]]
* DS1071A  Glitch Pattern Generator **also**(`?`) next-gen PXI Spider [[]]
### PXI Modules (Misc)
This is a partial list of __non-riscure__ branded components that integrate nicely into SCAS/FI settups

* M9601A PXI based `Source Measurement Unit` for Failure Analysis (pairs with LS2 laser and 1300nm laser)
* M5201A PXI based `Down Converter` (2-16GHz)

# Non-PXI stuff

### Misc
* DS1010A Precision XYZ Stage
* DS1180A Glitch Pattern Generator (previously `Spider`) (migrating to PXI [[DS1070]])
* DS1001A (Transceiver) (migrating to PXI [[DSNNNN]])
* DS1002A (icWaves) (migrating to  PXI [[DS1060]])
* DS1150A Clock-Glitcher (old) (migrating to PXI)
* DS1221A Notch Filter and Demodulator (previously `Cleanwave`)
* DS1150A Clock Glitcher (old) 
* DS1160A Clock Gitcher (new)
* DS1170A Automotive test tool (aka `Huracan`) 

### Glitch amps
* DS1140A 1.5A Glitch Amplifier (vertical standing) ( #FI)
* DS114XX 10A Glitch Amplifier  ( #FI)
* DS1141A 30A Glitch Amplifier (deprecated)  ( #FI)
* DS114NN **PMIC-enabled** Glitch Amplifier (latest/bestest) ( #FI)
### Probes - Current
* DS1201A Passive Current Probe (original) ( #SCA)
*  DS1202A Active Current Probe (new) ( #SCA)
### Probes - EM
*   DS1120A Uni-directional EMFI probe (original) ( #FI)
 *  DS1121A Bidirectional Fault Injection Probe (new) ( #SCA **and**  #FI)
#### Probe-tips 

> [!TIP] These items should probably be thought of as `Consumables`

* DS12XXX High-Precision-Electromagnetic-Probe __Tips__ ( #SCA)
* DS1320A Body Bias Injection Probe __Needles__ ( #FI)
* DS1321A HP-EM FI probe __Tips__ ( #FI)
* DS1322A Glitch Amplifier __Needles__( #FI)
### targets
* DS1030A-Software Crypto Target (`Pinata`)
* DS1031A Hardware Crypto Training Target (also `Pinata`?)
* DS1232A-Advanced-Training-Target (`Riscure-Berry`)

## Unnamed products?
* DSQQQ - This is what i would have previously referred to as the 'Low noise amp' (with optional external gain). 
* 
---




