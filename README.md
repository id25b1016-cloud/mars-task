# mars-task
The Automatic Night Lamp is a simple Arduino-based project that automatically turns ON the light in darkness and turns it OFF in daylight. It uses a light sensor to detect ambient light levels and control the lamp accordingly.

 Features
 Automatically turns ON in low light (night)

 Turns OFF in bright light (day)

Energy efficient system

 Simple and low-cost components

 Components Used
Arduino (Uno/Nano)

photoresistor

Resistor (10kΩ recommended)

LED / Lamp

Breadboard

Connecting wires

Circuit Description
The photoresistor senses the light intensity.

It is connected in a voltage divider circuit with a resistor.

The Arduino reads the analog value from the LDR.

Based on the light level, the Arduino controls the LED.

 Working Principle
In bright light, photoresistor resistance is low → LED OFF

In darkness, photoresistor resistance is high → LED ON
