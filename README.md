# VitalSigns Using IWR6843ISK
# What is IWR6843isk
WR6843ISK is an easy-to-use 60 GHz mmWave sensor evaluation kit based on IWR6843 device with long-range antenna. The IWR6843ISK may be used to evaluate the IWR6843 and IWR6443 devices. This board enables access to point-cloud data and power over USB interface.

# How it works.
Python program to read and plot the data in real time from the IWR6843 mmWave radar boards (Texas Instruments). The program has been tested with Windows and Raspberry Pi and is based on the Matlab demo from Texas Instruments.

First, the program configures the Serial ports and sends the CLI commands defined in the configuration file to the radar. Next, the data coming from the radar is parsed to extract the chest movements. The collected data is then transferred to pytqgraph file where it will be translated
