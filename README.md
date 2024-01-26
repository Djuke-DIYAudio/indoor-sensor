# Indoor sensor
This project contains the open source design files of an affordable indoor air sensor that can accurately measure CO2 level, Temperature, Humidity and Pressure. It contains a ESP8266 wi-fi module making it easy to integrate with your home automation system. 

Possible use cases:
* Monitoring sensor values over time
* Switching of air ventilation based on CO2 or humidity level
* Regulating room temperature (airco or heater)

# Design

## Considerations
At the moment the design considerations are:

* MH-Z19 sensor for measuring CO2 ppm
* BME280 sensor for measuring temperature, humidity and pressure sensor
* ESP8266 module to easily integrate with WIFI in the smart home
* red/green dual LED for level indication
  - Green, PPM < 800
  - Yellow/Orange, 800 < PPM < 1400
  - Red, PPM > 1400
* Connectors for optional 0.91 inch or 0.96 inch SSD1306 display
* Sales price around 25 euros

