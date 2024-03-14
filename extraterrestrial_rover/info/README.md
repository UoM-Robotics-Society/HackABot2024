# Useful Information

## General
- It will be best to use the Arduino IDE for your development.
- To connect the bluetooth module, you will need to solder on header pins to the Motor Driver Board, you will need to solder the analog, 5V and GND pins.
- It will be best to use softwareSerial for connection of the Bluetooth module, you can use pins A0 and A1.
- Be careful when powering the ESP32, it requires 3.3V.
- The ESP32 Camera is the AI Thinker ESP32-CAM.
- Python and pygame could be useful for developing your teleoperator program (or you could do it all web-based or via a phone).
- Each Bluetooth module has been renamed to your Kit Number.


## Drivers
- Search for AI Thinkwe ESP32-CAM to set up the ESP within the Arduino IDE.
- The board will come with some simple sketches to set up a video web server.
- Servo library is included as default in the Arduino IDE.
- You will need to google how to set up the Bluetooth module (hint: TX -> RX, RX -> TX)
