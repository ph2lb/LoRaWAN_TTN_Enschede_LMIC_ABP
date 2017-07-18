# LoRaWAN_TTN_Enschede_LMIC_ABP
BMx280 and Adruino ProMini based enviromental node with LMIC ABP

Description : A low power BMx280 based datalogger for the ThingsNetwork with deepsleep support and variable interval

Revision : 2017 jul-17 1.0 first "beta"

Hardware used : 
  - Arduino Pro-Mini 3.3V 
       Modified with aditional resistors to allow vcc measurment 
       by internal 1.1V reference (so max measurment is 4.4V)
       Mod > GND ---[33K]--- A3 ---[100K]--- VCC
  - RFM95W
  - BMx280 sensor.

Software used : 
  - LMIC https://github.com/matthijskooijman/arduino-lmic
  - BME280 library https://github.com/adafruit/Adafruit_BME280_Library
  - BMP280 library https://github.com/adafruit/Adafruit_BMP280_Library
  - LowPower library https://github.com/rocketscream/Low-Power
  - MiniCore loader  https://forum.arduino.cc/index.php?topic=412070 https://github.com/MCUdude/MiniCore 
    To use a brownout detection of 1.8V.
  
For licenses of the used libraries, check the links above.
