# Solar-Tracker
The Automatic Solar Tracking System is designed to enhance the efficiency of solar panels by ensuring they continuously face the sun as it moves across the sky. This system uses Light Dependent Resistors (LDRs) to detect the direction of maximum sunlight. An Arduino microcontroller processes the light intensity data and controls a motor to adjust the panel's position accordingly. By following the sun's path throughout the day, the system maximizes solar energy absorption, making it ideal for renewable energy applications.

# Components 
1 Arduino Uno or Nano ,

2 4 × LDRs ,

3 Servo motor or dual-axis motor setup ,

4 Solar panel (small or demo-sized) ,

5 Resistors (10kΩ) ,

6 Power supply or battery

# How it is works:

Four LDRs are placed around the panel to detect sunlight intensity from north, south, east, and west.

The Arduino reads analog values from the LDRs.

It calculates which direction has the most light.

A motor rotates the panel in that direction.

The system continuously adjusts the panel’s position throughout the day.



