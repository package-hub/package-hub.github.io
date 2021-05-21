---
title: ZigUP
categories: ['javascript']
---
## [ZigUP](https://github.com/formtapez/ZigUP)

### CC2530 based multi-purpose ZigBee Relais, Switch, Sensor and Router


* [Small enough to fit under a normal lightswitch](https://raw.githubusercontent.com/formtapez/ZigUP/master/Pictures/size.jpg) in an european flush-mounted box ("Unterputzdose" - That´s the UP in ZigUP)
* integrated optional ZigBee Router functionality (extends the range of all your other devices)
* Powerful bistable relais for up to 10 amps load
* 2 Inputs for switches/buttons:
	* Input "KEY" directly toggles the relais and outputs a ZigBee message
	* Input "DIG" only outputs a ZigBee message - So your coordinator can decide if the relais has to be toggled or not.
* Input for 16 digital temperature (DS18B20) and 1 humidity sensors (DHT22/AM2302) (Measurements will be reported via ZigBee)
* Input for S0-Bus impulses from power-, water- or gas-meters. Count-Value will be reported via ZigBee)
* Output for one normal LED or up to 10 WS2812B/Neopixel RGB-LEDs (controllable via ZigBee)
* Analog input to measure voltages of up to 32 Volt. (Voltage will be reported via ZigBee)
* Fully equipped debug-port to allow CC Debugger flashing and packet sniffing
