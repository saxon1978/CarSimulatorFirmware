
Wheelbase:

v1.0.0.9 
* changed: stop force doesn't depend on overall gain
* fixed: effect wheelcheck with spring 
v1.0.0.8 
* Added: add 2 options: old filter and new filter
* Added: Add correction encoder feature.
* Fixed: turn one direction on Calibration 
* Fixed: set Centering dont save to flash (cause STM32 delay about 3s, may crash if send data to stm32)

v1.0.0.6

* Fixed: Force calculation 
* Fixed: Biquad filter calculation reviewed
* Fixed: Removed unused settings from internal flash
* Fixed: Race condition when saving data in calibration process
* Fixed: An attempt to handle crash in calibration
* Tested PWM/DIR: Working witout error, due to user connections.
