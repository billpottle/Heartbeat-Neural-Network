This repository contains explanation and related files from work on biological signals.
=======================================
In 2002 we built and trained a Neural Network to detect heartbeat type (ie, Normal, AFIB, VFIB, PVC, etc) similar to what current technologies such as AliveCor Kardia achieve. 

The network took a one second ECG recording sampled at 300 Hz. This gave 300 input nodes, and the QRS peak was set at node 100. 

We trained the data on sets of heartbeats identified by cardiologists. 

The **Neural Network for EVG Classification** and **Neural Network Paper** file have the details of this work. 

The **EMG Design and Construction** file reconts a generalized recorder for electrical signals. We used this device to record electrical activity from various exercises. 
The **Data Compression for Heart and Muscle** file contains the details of how we achieved a 46x compression ratio, without siginificant loss of classification ability. 
The .wav files are the raw data recorded from our muscles. 

======================================
![heartbeat](https://github.com/billpottle/Heartbeat-Neural-Network/blob/master/Image2.jpg)
![heartbeat](https://github.com/billpottle/Heartbeat-Neural-Network/blob/master/Image1.jpg)
