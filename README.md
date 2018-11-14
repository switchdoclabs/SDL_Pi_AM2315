#
# SDL_Pi_AM2315
#
# AM2315 Pure Python Library
# SwitchDoc Labs November 2019
#
#

#Introduction
This is a pure python AM2315 library to replace the tentacle_pi C based library


#Installation

Requires installation of Adafruit_Python_GPIO

```
sudo apt-get update
sudo apt-get install build-essential python-pip python-dev python-smbus git
git clone https://github.com/adafruit/Adafruit_Python_GPIO.git
cd Adafruit_Python_GPIO
sudo python setup.py install
```


Place files in program directory

# testing

```
import AM2315 
sens = AM2315.AM2315()
print sens.read_temperature()
print sens.read_humidity()
print sens.read_humidity_temperature()
print sens.read_humidity_temperature_crc()
```
