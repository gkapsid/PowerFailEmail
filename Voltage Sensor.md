#Voltage Sensor

The voltage sensor consist of only a SPST 5V relay. 
A 5V cell phone charger is connected to the coil of the relay. The common pin (or one of the two pins) is connected to Arduino ground.
The other is connected to the digital input pin used to notify for the power failure.

An image of the above described circuit is given below:

https://cloud.githubusercontent.com/assets/9993080/12874989/da32173e-cde8-11e5-8904-98cbed985112.png

(Look at the issues page)

A diode can be added between +5 (cathode) and ground (anode) that is reverse polarized.

