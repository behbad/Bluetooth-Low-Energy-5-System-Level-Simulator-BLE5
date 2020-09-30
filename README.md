# BLE5
## System-level simulator of Bluetooth Low Energy version 5

This simulator is written in C++ and developed to work in [MiXiM framework](http://mixim.sourceforge.net/) of the [OMNeT++ engine](https://omnetpp.org/). This simulation, which simulates the PHY and MAC layer of BLE 5, is developed on top of [BLE 4.2 simulator](http://cc.oulu.fi/~kmikhayl/BLE.html). This simulator has been used for publishing the following article:
*  **B. Badihi**, F. Ghavimi and R. Jäntti, "On the System-level Performance Evaluation of Bluetooth 5 in IoT: Open Office Case Study," 2019 16th International Symposium on Wireless Communication Systems (ISWCS), Oulu, Finland, 2019, pp. 485-489, doi: 10.1109/ISWCS.2019.8877223.

The following features of BLE5 have been developed:

* New PHY layers including, **LE Coded S2**, **LE Coded S8**, **LE 2M PHY** in addition to **LE 1M PHY**.
* Channel Selection Algorithm 2\#.




In addition to the above-mentioned features, a dedicated decider for BLE in PHY layer, flow control in MAC layer and new auxiliary advertising packets are developed. It is worth mentioning that this simulator is developed and tested with **OMNeT++ version 4.4.1 and MiXiM version 2.3**. The higher versions of OMNeT++ may or may not work with the tool. 

In order to use this tool, the user must accept the **GNU v3 license** by confirming that she/he has read, understood and agree with the conditions of this licence. 
**In order to use this tool, the user need the password for openning the zip file. The password is "I hereby accept the license terms" without all spaces.** After unzipping the file, the is a tarball that can be directly imported by OMNet++.


 

