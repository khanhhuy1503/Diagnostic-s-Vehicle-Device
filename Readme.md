# Diagnostic-s-Vehicle-Device
A diagnostic's vehicle device using CAN &amp; SPI protocol based on Rasppery Pi 

/*********************************************************************************************************

	Enable SPI interface: sudo raspi-config
	Compile dts-overlay: dtc spidev_disabler.dts -O dtb >spidev_disabler.dtbo
	Load file dts: sudo dtoverlay -d . spidev_disabler
**********************************************************************************************************/
