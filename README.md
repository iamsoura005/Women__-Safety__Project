# Women__-Safety__Project
An arduino based project for women and child safety project. Which will be activated by two way- 1. by pressing a button. 2. Shouting "Help" 2 times. And when it will be activated it will send live location to selected 10 contacts and nearby police station. and it will make call to the contacts selected according to the nearby located contacts.

#Components:
1.Arduino Uno or Nano (~$5-20)
2.NEO-6M GPS module (~$10)
3.SIM800L or SIM900A GSM module (~$10-15)
4.KY-038 sound sensor module (~$2-5)
5.Push button (~$0.50)
6.Buzzer (~$1)
7.3.7V Li-Po battery (1000mAh or higher) with TP4056 charging module (~$5)
8.Jumper wires, breadboard, and soldering kit
9.Optional: 0.96” OLED display (I2C, ~$5) for debugging/status
10.USB cable (for Arduino programming)
11. SIM card with SMS/call capability (non-VoLTE for SIM800L/SIM900A)

#Tools
1.Computer with internet access
2.Screwdriver, wire stripper, soldering iron (for final assembly)
3.Multimeter (for troubleshooting)

#Install Required Libraries:
Open Arduino IDE, go to Sketch > Include Library > Manage Libraries.
Search and install:
TinyGPS++: For parsing GPS data from the NEO-6M module.
SoftwareSerial: For serial communication with GPS and GSM modules.
Optional: Adafruit_SSD1306 and Adafruit_GFX for OLED display.
Alternatively, download libraries from GitHub and add them via Sketch > Include Library > Add .ZIP Library.
