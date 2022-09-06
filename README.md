# Blinky IVT Tray
The IVT Heat pump web interface API is closed so it is not possible to interface a spot price device directly to this heat pump. However, as with most heat pumps, this heat pump is controlled with a infra-red remote control. As a workaround, the an infra-red remote control can be substituted with an [Blinky-Lite cube](https://github.com/blinky-lite-energy-exchange/blinky-ivt-cube) that is equipped with a an infra-red diode that can send the appropriate bitstream to the heat pump. This tray receives user input and the spot price from the Blinky-Lite application box server and uses the Blinky-Bus interface to communicate serially with the cube.The serial communication in this tray is done over Bluetooth.

<img src="doc/blinkyIvt.png"/><br>
