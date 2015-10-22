# ESP8266-OWM-Client

This is a simple OpenWeatherMap client based on the Lua Language
for the ESP8266 chip/board running the NodeMcu firmware.

Note: You must register on OpenWeatherMap to get an API key. It's free to a certain volume.
Replace the key right at the start of the http_client.lua file.

The code calls the OpenWeatherMap API and shows the weather values 
in a 16x2 I2C connected LCD.

Off course if we don't have a I2C LCD whe can simply just print the
values on the serial port.
