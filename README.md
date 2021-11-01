# ESP8266 and ESP32 OpenWeather client
Modified to handle Geocoding from Geocoder.geo.census.gov a Free US gov site that has a API that doesnt use keys.

Has .getGeo command which pulls the JSON from the Geocoder.

See https://github.com/Bunge32/WiFiWeatherArduino for example in use. 

Arduino client library for https://openweathermap.org/

Collects current weather plus daily forecasts.

Requires the JSON parse library here:
https://github.com/Bodmer/JSON_Decoder

The OpenWeather_Test example sketch sends collected data to the Serial port for API test. It does not not require a TFT screen.

The TFT_eSPI_Weather example works with the ESP8266 and ESP32, it displays the weather data on a TFT screen.  These examples use anti-aliased fonts and newly created icons:

![Weather isons](https://i.imgur.com/luK7Vcj.jpg)

Latest screen grabs:

![TFT screenshot 1](https://i.imgur.com/ORovwNY.png)

