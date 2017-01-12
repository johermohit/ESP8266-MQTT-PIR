# ESP8266-MQTT-PIR
Arduino sketch for ESP8266 that sends PIR motion events to MQTT broker.

This code is designed to read input from a PIR sensor and send a message to a MQTT broker. It will automatically connect and reconnect to your Wi-Fi and MQTT broker. It's built based on a NodeMCU but will work on any ESP8266 variant with basic changes to pin numbers. If you have any awesome improvements please share!

You will need to install these Arduino libraries:

ESP8266wifi

Adafruit_MQTT
