# NewClock

Adruino Project using NodeMCU 1.0 (ESP8266), DS3231, and MAX7219

# About

It's a digital clock

# Installation

1. Download/Clone repo
2. Install Arduino IDE
3. Install device driver (https://www.silabs.com/products/development-tools/software/usb-to-uart-bridge-vcp-drivers)
4. Install libraries
  - In the Arduino IDE, go to File -> Preferences -> Settings and copy + paste "http://arduino.esp8266.com/stable/package_esp8266com_index.json" in Additional Boards Manager URLs
  - Try to compile/verify the code as is. For each error regarding a library, go to Tools -> Library Manager and search for the matching library.
  - Some libraries are specific, such as: "Rtc by Makuna" for DS3231 (look it up in the libraries manager), and "Time library for Arduino" (https://github.com/PaulStoffregen/Time).
5. Done.
