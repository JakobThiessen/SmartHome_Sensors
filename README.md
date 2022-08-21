# SmartHome_Sensors
Verschiedene Sensoren mit Tasmota

# Sensoren die UNterstütz werden
| Name    | Beschreibung        | Getestet|
|---------|---------------------|---------|
| SCD40   | CO2 sensor          |    X    |
| TSL2591 | Lichtsensor         |    X    |
| BME280  | Environment Sensor  |    X    |
| BME680  | CO2                 |    X    |
| HDC1080 | T/RH                |    X    |

# Tasmota precompiled

tasmota-sensors.bin


# Verdrahtung



## Pinoutt of ESP 8266 WEMOS-D1

| Label | IO    | Beschreibung      |
|-------|-------|-------------------|
| D1	  | GPIO5 | used as SCL (I2C) |
| D2	  | GPIO4 | used as SDA (I2C) |

https://randomnerdtutorials.com/esp8266-pinout-reference-gpios/

![ESP8266](https://i0.wp.com/randomnerdtutorials.com/wp-content/uploads/2019/05/ESP8266-ESP-12E-chip-pinout-gpio-pin.png?quality=100&strip=all&ssl=1)

![ESP8266](https://i0.wp.com/randomnerdtutorials.com/wp-content/uploads/2019/05/ESP8266-WeMos-D1-Mini-pinout-gpio-pin.png?quality=100&strip=all&ssl=1)
