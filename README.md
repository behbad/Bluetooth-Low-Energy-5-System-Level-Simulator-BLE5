# BLE5
## System-level simulator of Bluetooth Low Energy version 5

This simulator is written in C++ and developed to work in [MiXiM framework](http://mixim.sourceforge.net/) of the [OMNeT++ engine](https://omnetpp.org/). This simulation ,which simulates the PHY and MAC layer of BLE 5, is veleoped on top of [BLE 4.2 simulator](http://cc.oulu.fi/~kmikhayl/BLE.html). The following features of BLE5 have been developed:

* New PHY layers including, **LE Coded S2**, **LE Coded S8**, **LE 2M PHY** in addition to **LE 1M PHY**.
* Chanell Selection Algorithm 2\#.
In addition to the above mentioned features, a dedicated decider for BLE in PHY layer, flow control in MAC layer and new auxillary advertising packets are developed. It is worth mentioning that this simulator is developed and tested with **OMNeT++ version 4.4.1 and MiXiM version 2.3**. The higher versions of OMNeT++ may or may not work with the tool. 


 

