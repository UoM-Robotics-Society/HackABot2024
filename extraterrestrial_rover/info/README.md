# Useful Information

## General
- To connect the bluetooth module, you will need to solder male header pins onto the underside of the Uno board and to the 5V and GND headers on the mootor drive board.
- Programs will not upload if you have the bluetooth module connected to the serial port on the arduino.
- It will be best to use the Arduino IDE for your development.
- Be careful when powering the ESP32, it takes 3.3V 

## Drivers
- Search for ESP32-CAM to set up the ESP within the arduino IDE.
- The board will come with some simple sketches to set up a video web server.
- Servo libaray is included as defualt in the Arduino IDE.
- You will need to google how to set up the Bluetooth module (hint: TX -> RX, RX -> TX)
