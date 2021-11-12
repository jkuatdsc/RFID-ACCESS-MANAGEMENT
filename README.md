# RFID-ACCESS-MANAGEMENT
IOT example for RFID for access control and management

## WIRING
### LCD
| LCD | NODEMCU (ESP8266) |
| --- | ----------------- |
| GND | GND |
| VCC | VIN |
| SDA | D2 |
| SCL | D1 |

### RFID RECEIVER
| NODEMCU | MFRC522 |
| ------- | ------- |
| D4 | SDA |
| D5 | SCK |
| D7 | MOSI |
| D6 | MISO |
| GND | GND|
| D3 | RST |
| 3v | 3.3V|