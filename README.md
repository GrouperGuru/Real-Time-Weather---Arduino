# ☀️ 🌦️ Real Time Weather 🌩️ 🌨️
## Arduino Nano (ESP32) with GME12864 OLED display
This app utilizes the OpenWeather API (Free) to pull down current weather conditions for the City of your choice.
### OpenWeather (API) ⌕
You will need to create a free account to obtain your API key.
https://openweathermap.org/
### Network Settings 🛜
The following will need to be changed:
``` CPP
const char* ssid     = "WIFI NETWORK NAME";
const char* password = "WIFI NETWORK PASSWORD";
const char* apiKey   = "OPENWEATHERMAP API KEY";
const char* city     = "Buffalo";
const char* country  = "US";
```
