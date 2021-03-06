# PSU
Software-controlled variable-voltage power supply with current and power monitoring.

Features:
- Digital Potentiometer for software-controlled adjustment
- Common voltages preset through web interface
- Voltage adjustment via Rotary Encoder
- TFT LCD to display output voltage and current
- Software-controlled fuse

## Hardware
Display hardware as [WifiWeatherGuy](https://cadlab.io/project/1280/master/files):
- [Wemos D1 Mini](https://wiki.wemos.cc/products:d1:d1_mini)
- PCB-mounted push switch
- 1.8" TFT LCD display
- v3 PCB (with pin headers)

PSU hardware:
- [LM317](https://en.wikipedia.org/wiki/LM317) variable voltage regulator
- [INA219](https://www.adafruit.com/product/904) voltage and current sensor
- [X9C103S](https://www.renesas.com/us/en/products/data-converters/digital-potentiometers/dcp/device/X9C103.html) digital potentiometer
- [Rotary Encoder](https://en.wikipedia.org/wiki/Rotary_encoder)
- Old laptop transformer (19v)

## Software
- [Arduino](https://www.arduino.cc/en/main/software) v1.8.x
- [Arduino/ESP8266](https://github.com/esp8266/Arduino) v2.5.0
- [TFT_eSPI](https://github.com/Bodmer/TFT_eSPI) v1.1.3
- [Adafruit_INA219](https://github.com/adafruit/Adafruit_INA219) v1.0.4
- [Arduino-X9C](https://github.com/philbowles/Arduino-X9C) v0.9.0
- [SimpleTimer](https://github.com/schinken/SimpleTimer)
