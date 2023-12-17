View this project on [CADLAB.io](https://cadlab.io/project/27556). 

# xDuinoRail-Decoder

The friendly decoder development plattform for model railroad tinkers.

## Target plattforms

### Arduino (UNO R3) formfactor

The primary tinker formfactor is the "Arduino UNO R3":

| CPU | MCU | Vendor | Product Name & Page |
|--- | --- | --- | --- | 
| ? Atmega ? | Atmega328 | Arduino & Clones|
|--- | Atmega32u4 | Arduino & Clones |
|--- | AtmegaMEGA | Arduino & Clones |
| ARM M0 | SAMD21 | Adafruit | [Metro M0 Express](https://www.adafruit.com/product/3505) | 
| ARM M0 | SAMD21 | SparkFun |
| ARM M4 | SAMD51 | Adafruit | [Metro M4 Express](https://www.adafruit.com/product/4000) | 
| Dual ARM M0+ | RP2040 | Adafruit | [Metro RP2040](https://www.adafruit.com/product/5786) | 
| RV32IMAC | RISC-V | SparkFun | [SparkFun RED-V RedBoard](https://www.sparkfun.com/products/15594) 

### Decoder development for XIAO formfactor

The XIAO formfactor may even fit some H0 locomotives, so COMING SOON:

| CPU | MCU | Vendor | Product Name & Page |
|--- | --- | --- | --- | 
| ? Atmega ? | Atmega328 | Arduino & Clones|

## Features
Power:
- It extracts power from the rails.

Data
- It extracts DCC raw signals  from the rails.
- It provides raw (RailCom) feedback to the rails.

The data pins are X (input) and Y (output) per default (no soldering needed, but can be reassigned to any other GPIO-Pins.

## Excluded by purpose
- It doesn't include any power IO
- It doesn't include any MCU
