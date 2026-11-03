# BLE5
## System-level simulator of Bluetooth Low Energy version 5

This simulator is written in C++ and developed to work in [MiXiM framework](http://mixim.sourceforge.net/) of the [OMNeT++ engine](https://omnetpp.org/). 
The simulator implements key PHY and MAC layer features of Bluetooth 5 and is intended for system-level evaluation of BLE networks.

#Publication
This simulator was used in the following publication:
B. Badihi, F. Ghavimi, and R. Jäntti,
"On the System-level Performance Evaluation of Bluetooth 5 in IoT: Open Office Case Study,"
2019 16th International Symposium on Wireless Communication Systems (ISWCS), Oulu, Finland, 2019, pp. 485–489.
DOI: 10.1109/ISWCS.2019.8877223


****PHY Layer
The following Bluetooth 5 PHY modes are supported:

- LE 1M PHY
- LE 2M PHY
- LE Coded PHY with S=2
- LE Coded PHY with S=8
A dedicated BLE PHY decider has also been implemented to support reception and PHY-level processing of Bluetooth Low Energy packets.
#MAC Layer
The MAC layer includes:

- Channel Selection Algorithm #2
- Flow control mechanisms
- Support for auxiliary advertising packets
These extensions enable simulation of Bluetooth 5 communication behavior at both the PHY and MAC layers.




 It is worth mentioning that this simulator is developed and tested with **OMNeT++ version 4.4.1 and MiXiM version 2.3**. The higher versions of OMNeT++ may or may not work with the tool. 

In order to use this tool, the user must accept the **GNU v3 license** by confirming that she/he has read, understood and agree with the conditions of this licence. 
**In order to use this tool, the user need the password for openning the zip file. The password is "I hereby accept the license terms" without all spaces.** After unzipping the file, the is a tarball that can be directly imported by OMNet++.


 

