# Useful Information

## General
- It will be best to use the Arduino IDE for your development.
- To connect the Bluetooth module, you will need to solder the header pins to the Motor Driver Board, you will need to solder the analogue, 5V and GND pins.
- It will be best to use softwareSerial to connect the Bluetooth module, you can use pins A0 and A1.
- Be careful when powering the ESP32.
- The ESP32 Camera is the AI Thinker ESP32-CAM.
- Python and pygame could be useful for developing your teleoperator program (or you could do it all web-based or via a phone).
- Each Bluetooth module has been renamed to your Kit Number.


## Drivers
- Search for AI Thinker ESP32-CAM to set up the ESP within the Arduino IDE.
- The board will come with some simple sketches to set up a video web server.
- Servo library is included as default in the Arduino IDE.
- You will need to google how to set up the Bluetooth module (hint: Bluetooth TX -> Arduino RX, Bluetooth RX -> Arduino TX)
- Bluetooth modules work on 9600 baud with their password as 1234
- Each Bluetooth module has the same name as your team number.

[Click here for a tutorial for a good video stream from your camera](https://randomnerdtutorials.com/esp32-cam-access-point-ap-web-server/#:~:text=To%20connect%20to%20the%20access,4.1%20in%20your%20browser)
