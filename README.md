contains files pertaining to the power supply powering the dell miniPC from the comma body platform.

i used the convenient "arm" USB-C port to implement the miniPC power supply in concert with the main power button.

first I drop its 12v to 5v to power an adafruit trinket.

the trinket does 2 things: 1 it spoofs dell's silly 1-Wire-based supply identification protocol, once this spoof is ready, it turns on the power to the miniPC