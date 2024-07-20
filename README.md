 ESP32 IR Remote Control Web Server
This project sets up an ESP32 microcontroller as a web server that allows you to control an IR device (e.g., a TV) through a web interface. The ESP32 creates a Wi-Fi access point and provides a web page with buttons for toggling power, increasing/decreasing volume, and muting the device.

Features
Wi-Fi Access Point: The ESP32 sets up a Wi-Fi access point.
Web Server: A web server running on the ESP32 serves an HTML page with control buttons.
IR Remote Control: Control an IR device using buttons on the web page.
Hardware Required
ESP32 development board
IR receiver connected to GPIO 26
IR transmitter connected to GPIO 33
Button (optional) connected to GPIO 14
Libraries Required
IRremote: To send and receive IR signals.
WiFi: For Wi-Fi connectivity.
WebServer: For running the web server.
 
