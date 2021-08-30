# STM32F4x1-N40-EVAL
STM32Fx1CxU6 MCU's evaluation board in Arduino Nano format with 40 pin (instead of 30).
This project will work with F411 and F401 MCU's in UFQFPN-48 package.

**Board features:**
* 4-layers, 1-1.2 mm thickness
* USB-C connector with connector ic (TUSB320)
* Debug via 10-pin Cortex-ARM conector (PLLD-10)
* PLS pins replaced with [Long PBS](https://www.google.com/search?q=long+female+header)
* 1 user button and led
* 4-way switch for enable: DFU, BOOT0, BOOT1, Debug

**DFU enable feature:**
While enabled, it allow to enter DFU via holding reset button about 2-3 seconds. Uses external transistor and RC circuit.

**Debug enable feature:**
Enable debug connector with external mosfet.
