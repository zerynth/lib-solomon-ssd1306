***************
SOLOMON SSD1306
***************

The SSD1306 is a CMOS OLED/PLED driver with controller for light emitting diode dot-matrix graphic display system. It consists of 128 segments and 64 commons. This IC is designed for Common Cathode type OLED panel.

The SSD1306 embeds with contrast control, display RAM and oscillator, which reduces the number of
external components and power consumption. It has 256-step brightness control. Data/Commands are
sent from general MCU through the hardware selectable 6800/8000 series compatible SPI Interface.

More information at `Solomon dedicated page <http://www.solomon-systech.com/en/product/display-ic/oled-driver-controller/ssd1306/>`_

=================
Technical Details
=================

* Supply Voltage (Vdd): from 1.65 V to 3.3 V
* Operation Temperature (Top): from -40 °C to 85 °C
* Resolution: 128 x 64 dot matrix panel
* Segment maximum source current: 100uA 
* Common maximum sink current: 15mA
* 256 step brightness current control
* SPI interface

Here below, the Zerynth driver for the SOLOMON SSD1306.

.. include:: __toc.rst
