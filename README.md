# Sheep Counter

This is a tinkercad simulation of a device that can help count a flock of sheep that enters a fenced grassland.
An Arduino Uno R3 microcontroller, 2 PIR sensor, a breadboard and small led's are used for this device.

The first PIR sensor is placed just before the gate, the second sensor is placed on the grassland side of the gate. When a sheep passes through the gate, the count will only increase if the sheep passes through first PIR sensor first and then the second PIR sensor (i.e, confirming it has entered the grassland). Similarly, the count decreases when the sheep passes through second PIR sensor first and then the first PIR sensor. Led lights and console messages have been provided to confirm visually the working of the system.

