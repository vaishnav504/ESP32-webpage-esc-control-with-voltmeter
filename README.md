# ESP32-webpage-esc-control-with-voltmeter
A self-hosted ESP32-based system that allows users to control an ESC and monitor real-time voltage using a web interface. The webpage is served directly from the ESP32 using AP mode, requiring no external Wi-Fi or internet.
Libraries used = WiFi.h  WebServer.h   ESP32Servo.h
components used = ESP32,ESC,30k and 7.5k resistor for voltage divider (max 15 volt input)
esc pin = 12
analog input from voltage divider = 34
