View this project on [CADLAB.io](https://cadlab.io/project/27556). 

# xDuinoRail-Decoder

## Features
An easy decoder development plattfrom for Arduino (UNO R3) formfactor MCU boards:

| CPU | MCU | Vendor | Product Name & Page |
|--- | --- | --- | --- | --- |
| ? Atmega ? | Atmega328 | Arduino & Clones|
|--- | Atmega32u4 | Arduino & Clones |
|--- | AtmegaMEGA | Arduino & Clones |
| ARM M0 | SAMD21 | Adafruit | [Metro M0 Express](https://www.adafruit.com/product/3505) | 
| ARM M0 | SAMD21 | SparkFun |
| ARM M4 | SAMD51 | Adafruit | [Metro M4 Express](https://www.adafruit.com/product/4000) | 
| Dual ARM M0+ | RP2040 | Adafruit | [Metro RP2040](https://www.adafruit.com/product/5786) | 


Power:
- It extracts power from the rails.

Data
- It extracts DCC raw signals  from the rails.
- It provides raw (RailCom) feedback to the rails.

The data pins are X (input) and Y (output) per default (no soldering needed, but can be reassigned to any other GPIO-Pins.

## Excluded by purpose
- It doesn't include any power IO
- It doesn't include any MCU
