# Sharp GP2Y1010AU0F Optical Dust Sensor Hook-Up Guide

The Sharp GP2Y1010AU0F optical dust sensor is a small (46.0 × 30.0 × 17.6 mm) lightweight
(~15g) air quality sensor containing an infra-red LED and a phototransistor capable of
detecting air-borne dust and smoke. The sensor is available from SparkFun and their
distributors (Product ID: COM-09689) and has a sensitivity of 0.5V/0.1mg/m^3.

Sharp have produced a [detailed datasheet](http://sharp-world.com/products/device/lineup/data/pdf/datasheet/gp2y1010au_e.pdf) for the sensor,
together with a rather useful [application note](http://sharp-world.com/products/device/lineup/data/pdf/datasheet/gp2y1010au_appl_e.pdf).

You will need:
- Arduino Uno or equivalent (e.g. the SparkFun RedBoard – product ID: DEV-12757)
- Sharp GP2Y1010AU0F optical dust sensor (SparkFun ID: COM-09689)
- 6-Way JST ZHR-6 connector housing (SparkFun ID: PRT-09690)
- 6x JST SZH-002T-P0.5 crimp pins (SparkFun ID: PRT-09728)
- 150R Resistor
- 220µF Electrolytic Capacitor
- (Hobby Components offer the sensor, pre-crimped connector, resistor and capacitor as a (complete kit)[http://hobbycomponents.com/sensors/818-gp2y1010au0f-compact-optical-dustsmoke-sensor])
- Small Breadboard or Veroboard
- Hook-up wires

Start by reading the [hook-up instructions](https://github.com/PaulZC/GP2Y1010AU0F_Dust_Sensor/blob/master/Sharp_GP2Y1010AU0F_Optical_Dust_Sensor_Hook-Up_Guide.pdf)

Then download the [Dust_Sensor sketch](https://github.com/PaulZC/GP2Y1010AU0F_Dust_Sensor/tree/master/Dust_Sensor)

Don't forget to install the [Timer1 library](https://code.google.com/p/arduino-timerone/downloads/list)

Make sure you are using a 5V Arduino board. If you try to use a 3V3 board like the Zero, you may damage it.

This project is distributed under a Creative Commons Attribution + Share-alike (BY-SA) licence.
Please refer to section 5 of the licence for the “Disclaimer of Warranties and Limitation of Liability”.

Enjoy!

### _Paul_
