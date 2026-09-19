# car-stereo
I am VERY unhappy with how much insight my hybrid gives the driver with regards to what the power train is doing. I want to see charge/discharge current and allowed rates. MG1, MG2 and engine RPMs and power battery temperature, internal resistance of cells, cell delta etc...

This project contains hardware files for the primary control board of a car stereo that can access the CANBus of a vehicle and pull hybrid system information and display it.

It is based off of an STM32MP153DAE microprocessor.

Peripheral support:
* Power Amplifiers for in-cab speakers
* GNSS module support
* 2x USB Host
* Ethernet
* 1x USB C Power Delivery 2.0 65W
* CAN 2.0B


