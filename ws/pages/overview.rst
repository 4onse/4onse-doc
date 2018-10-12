.. _overview:

Overview
---------

The weather station is based on the Arduino Mega 2560 board to collect data
coming from a set of sensors to monitor the environment.
A data logging system is available to minimize the possibility of data loss.
The SIM800 GPRS module allows to send data to the
`istSOS <http://www.istsos.org>`_ open platform  on the web.

The following parameters are available:

* External Temperature (**DS18B20**)
* Internal Temperature (**DHT11**)
* Humidity (**BME280**)
* Barometric Pressure (**BME280**)
* Quantity of rain (**Davis AeroCone collector**)
* Wind speed and direction (**SEN-08942**)
* Soil moisture (**YL-69**)
