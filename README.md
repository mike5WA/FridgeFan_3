# FridgeFan_3
Via arduino Uno code to control fan speed dependant upon temperature
Used in campervan where fridge is in an enclosed cavity which is ventilated with 2 * 12v fans
Routine adjusts fan speed dependant upon cavity temperasture by pwm on npn transistor controlling power to fans
Displays temperature and a bar graph of fan speed in % on a 2.2" TFT LCD display via software SPI
To dim display at night a light sensor is monitored and via pwm reduces tft display as lux levels fall.
