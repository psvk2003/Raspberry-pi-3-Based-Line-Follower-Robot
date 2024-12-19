# Raspberry pi 3 Based Line Follower Robot

### Requirements

* Python
* Colab
* HTML

### Explanation
The Line Follower Robot using Raspberry Pi 3 and L298N motor is a project aimed at developing an autonomous robot capable of following a line on a track. The Raspberry Pi 3 serves as the main controller, while the L298N motor driver is used to control the motors for precise movement. The objective of this project is to demonstrate the integration of hardware and software components to create an efficient line-following robot.

### Components Used
* Raspberry Pi 3
* IR Sensor (2)
* DC Gear Motor (2)
* JUMPER WIRES
* L298n Motor Driver
* Chaises (robot body)

### Working Principle
* Line Follower Robot is able to track a line with the help of an IR sensor. This sensor has a IR Transmitter and IR receiver.
* The IR transmitter (IR LED) transmits the light and the Receiver (Photodiode) waits for the transmitted light to return back.
* An IR light will return back only if it is reflect by a surface. Whereas, all surfaces do not reflect an IR light, only white the colour surface can completely reflect them and black colour surface will completely absorb them.
* These two IR sensors will be placed one on either side of the line. If none of the sensors are detecting a black line them they PI instructs the motors to move forward.
* If left sensor comes on black line then the PI instructs the robot to turn left by rotating the right wheel alone.
* If right sensor comes on black line then the PI instructs the robot to turn right by rotating the left wheel alone.
* If both sensors comes on black line, robot stops as shown in the next slide.

![lmao](https://github.com/Harish-Balaji-B/Raspberry-pi-3-Based-Line-Follower-Robot/blob/main/demo/exp.png)<br>


### Example Results
<strong>Example Video Link</strong><br>
https://drive.google.com/file/d/1ejr4K5gGsT-U2nuUzQ-vaD0seedmmj32/view?usp=drive_link

<strong>Sample Photo</strong><br>
![lmao](https://github.com/Harish-Balaji-B/Raspberry-pi-3-Based-Line-Follower-Robot/blob/main/demo/work.png)<br>
