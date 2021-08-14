# esp-aq-sensor


## BOM
| Sensor  | Purpose       | Ali link                                          | Docs                                              |
|---------|---------------|---------------------------------------------------|---------------------------------------------------|
| PMS5003 | PM Sensor     | https://aliexpress.com/item/1005001793669306.html | https://esphome.io/components/sensor/pmsx003.html |
| MH-Z19  | CO2 Sensor    | https://aliexpress.com/item/4000212024923.html    | https://esphome.io/components/sensor/mhz19.html   |
| BME280  | Temp/Humidity | https://aliexpress.com/item/4000943231922.html    | https://esphome.io/components/sensor/bme280.html  |
| SGP30   | TVOC          | https://nl.aliexpress.com/item/4000080488619.html | https://esphome.io/components/sensor/sgp30.html   |

## Wiring
For NodeMCU-32S 

### PMS5003
- VCC to VIN (5v)
- GND to GND
- TXD to 26
- SET to 27

### BME280
- VIN to 3.3V
- GND to GND
- SCL to 22
- SDA to 23

### BH1750
- VCC to 3.3V
- GND to GND
- SCL to 22
- SDA to 23


### MH-Z19
 - VIN to VIN (5V)
 - GND to GND
 - TX to pin 18
 - RX to pin 19
 
 
