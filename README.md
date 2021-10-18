# STM32F4x1-N40-EVAL
STM32Fx1CxU6 MCU's evaluation board in Arduino Nano format with 40 pin (instead of 30).
This project will work with F411 and F401 MCU's in UFQFPN-48 package.

**Board features:**
* 4-layers, 1.6 mm thickness
* USB-C connector with controller ic (TUSB320)
* Debug via 10-pin Cortex-ARM conector (PLLD-10)
* PLS pins replaced with [Long PBS](https://www.google.com/search?q=long+female+header)
* 1 user button and led
* 4-way switch for enable: DFU, BOOT0, BOOT1, Debug
* Advanced I2C perepheiral with 2 interrupt channels: 
  * Temperature sensor
  * Magnetometer sensor (3-axis)
  * Accelerometer sensor (3-axis)
  * EEPROM 2Kx8 size
  * USB-C controller

**DFU enable feature:**
While enabled, it allow to enter DFU via holding reset button about 2-3 seconds. Uses external transistor and RC circuit.

Board renders:

![image](https://user-images.githubusercontent.com/24395607/136925343-b0255ce0-a965-4216-8746-86d07a956da2.png)
![image](https://user-images.githubusercontent.com/24395607/136926016-af36a900-3bb7-4a81-8f79-7a0a27de7d08.png)
![image](https://user-images.githubusercontent.com/24395607/136926116-23091c77-1ccb-4925-9e58-6ce16e92d7f8.png)
![image](https://user-images.githubusercontent.com/24395607/136926402-a3d0fded-169b-4d9e-9712-97baa5761bf4.png)
