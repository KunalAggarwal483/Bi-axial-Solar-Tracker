# Bi-axial-Solar-Tracker
It is an automation project using Arduino UNO microcontroller board.

Description __

Components :
1. Arduino UNO
2. Servo motors(MG996R) - 2x
3. Light Dependent Resistors(LDR) - 4x
4. 3rd printed fittings(for servo and sensors)
5. Wooden board
6. Breadboard
7. Resistors(10k ohm) - 4x

Construction: 

The servo motors are connected through 6 pins(ports) to arduino , 3 pins each for Supply, control and Ground.
The photoresistors are connected to arduino uno through 4 analog read pins.
Arduino is connected to 5v power supply. 
Breadboard is used for providing Supply , ground and intermediate connections to servos and sensors.

Working:

The servo motors controls the x and y axis of movement of the sensor fitted module.
The sensor fitted module tries to align itself in the direction of light ray falling on it, in vertical , horizontal as well as diagonal directions.
The sensors on module reads the intensity value of light rays falling on them through change in resistance and the code calibrates the change in resistance of senosrs to   an analog range of (0 - 1023).
Using the analog values of each sensor , the sensor with maximum intensity is determined and the servos are set to rotate in the position of that sensor.
In this way at every milisecond the sensors values are read continously and the position of movement gets updated and servos are directed.

THE CODE FOR ABOVE FUNCTIONALITY IS PROVIDED IN THE REPOSITORY.

Below are provided the video and images link related to working and architecture of the SOLAR TRACKER and its connection diagram.

VIDEO link - https://drive.google.com/file/d/1GIctOU1s9jiB_2PHreuJ33SlZo8JXeXg/view?usp=sharing
             
             https://drive.google.com/file/d/1G5xJ3WYHlBzw9-BqBQq_J1yXSBSutSWF/view?usp=sharing
             
DIAGRAM - https://drive.google.com/file/d/1GWy83ggsBVwqF6hXEYpf9ui-234oCHp_/view?usp=sharing             
             
