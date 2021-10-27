AI-Assignment2-Webots

Webots is an open source and multi-platform desktop application used to simulate robots. It provides a complete development environment to model, program and simulate robots.

It has been designed for a professional use, and it is widely used in industry, education and research. Cyberbotics Ltd. maintains Webots as its main product continuously since 1998.

Obstacle-Avoidance-Webot

The algorithm is very simple, just only need two condition and three states.

1. If the robot detects obstacle on the front right, then the robot is rotate left in place. We use sensor 0 and sensor 1 to detect an obstacle on the front right. If one of the sensors is active, then there is an obstacle on the front right.

2. If no obstacle on the front right, then the robot detects the obstacle on the front left. If any, then the robot is rotate right in place. We use sensor 7 and sensor 6 to detect the obstacle on the front left. If one of the sensors is active, then there is an obstacle on the front left.

3. If no obstacle in the front right or front left, then the robot is moving forward.
What about if an obstacle is in front of the robot? If there is an obstacle in front of the robot, then the sensor 0 or sensor 1 is active. So the obstacle front right detection condition is true.
