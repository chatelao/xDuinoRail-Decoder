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
| ARM M0+ | SAMD21 | Adafruit | [Metro M0 Express](https://www.adafruit.com/product/3505) | 
| ARM M0+ | SAMD21 | SparkFun |
| ARM M4 | SAMD51 | Adafruit | [Metro M4 Express](https://www.adafruit.com/product/4000) | 
| Dual ARM M0+ | RP2040 | Adafruit | [Metro RP2040](https://www.adafruit.com/product/5786) | 
| ARM M4 | nRF52840 | Nordic | [nRF52840 DK](https://www.mouser.ch/ProductDetail/Nordic-Semiconductor/nRF52840-DK?qs=F5EMLAvA7IA76ZLjlwrwMw%3D%3D&gad_source=1&gclid=CjwKCAiA1fqrBhA1EiwAMU5m_9iVmasRrajTl6bT0wZal1_tMu6lTCWF3Ct0FWfQw9FYF_E3vaRdBRoC_tcQAvD_BwE)
| ARM M4 | nRF52840 | Waveshare | [nRF52840 Bluetooth 5.0 Evaluation Kit](https://www.waveshare.com/nrf52840-eval-kit.htm)
| RV32IMAC | SiFive RISC-V | SparkFun | [SparkFun RED-V RedBoard](https://www.sparkfun.com/products/15594) 
| RV32IMAFC | WCH RISC-V | AliExpress | [CH32V307V-EVT-R1 CH32V307 Evaluation Board RISC-V](https://de.aliexpress.com/item/1005004151524708.html)

### Decoder development for XIAO formfactor

The XIAO formfactor may even fit some H0 locomotives, so COMING SOON:

| CPU | MCU | Vendor | Product Name & Page |
|--- | --- | --- | --- | 
| ARM M0+ | SAMD21 | SeeedStudio | [XIAO SAMD21](https://wiki.seeedstudio.com/Seeeduino-XIAO)
| Dual ARM M0+ | RP2040 | SeeedStudio | [XIAO RP2040](https://wiki.seeedstudio.com/XIAO-RP2040/)
| ARM M4 | nRF52840  | SeeedStudio | [XIAO BLE](https://wiki.seeedstudio.com/XIAO_BLE/)
| Xtensa LX7  | ESP32-S3 | SeeedStudio | [ESP32-S3](https://wiki.seeedstudio.com/xiao_esp32s3_getting_started/)
| RV32IMC  | ESP32-C3 | SeeedStudio | [ESP32-C3](https://wiki.seeedstudio.com/XIAO_ESP32C3_Getting_Started/) 
| ARM M0+ | SAMD21 | Adafruit | [QT Py SAMD21](https://www.adafruit.com/product/4600) 
| Dual ARM M0+ | RP2040 | Adafruit | [QT Py RP2040](https://www.adafruit.com/product/4900) 
| RV32IMC | ESP32-C3 | Adafruit | [QT Py ESP32-C3](https://www.adafruit.com/product/5405)
| Xtensa LX7 | Adafruit | [QT Py ESP32-S2](https://www.adafruit.com/product/5325)
| Xtensa LX7  | ESP32-S3 | Adafruit | [QT Py ESP32-S3](https://www.adafruit.com/product/5426)

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
