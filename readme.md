# raspberry-utility

## This Windows 10 IoT class library features helpers and tool to code with a Raspberry PI.

### PCF5891

This class can be used to connect to the I2C bus on your Raspberry GPIO extension.
With an AD/DA converter, such as the PCF8591 component, this class will read the data from the I2C bus and convert digital value to an analog one, using the following syntax:
```
PCF8591 ADConverter = await PCF8591.Create();
double value = ADConverter.ReadI2CAnalog_AsDouble(PCF8591_AnalogPin.A0);
```
more details here : (http://phoebecoeus.net/dev/read-analog-data-on-your-raspberry-with-windows-iot)

