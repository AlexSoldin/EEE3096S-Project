# Environmental Logger

The speciﬁcation provided explains that the system should output a voltage to be directly monitored by external recording equipment. The value of this voltage is calculated according to sensor characteristics.

If this voltage is below 0.65V or above 2.65V , an alarm LED will be illuminated indicating the alarm being triggered.

All the recorded information should be easily accessible using Blynk. Blynk is a popular Internet of Things (IoT) platform that connects devices to the cloud, allows for easy app design and management of deployed products. This allows the user to access the conditions in the greenhouse using remote monitoring.

Interfacing with the Raspberry Pi required the use of multiple libraries. The WiringPi library was used to streamline the use of the Pi’s on-board I2C interface. The mcp3004 library was used to interface with the MCP3008 ADC chip using a serial SPI connection.

<p align="center">
<img alt="" height="300" src="https://i.imgur.com/narxFsp.png" width="300">
</p>
