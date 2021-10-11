[Stefano Carlo Lambertenghi](https://github.com/steflamb)

[Felix Boelter](https://github.com/felixboelter/)
# Robotics Road Simulation
A controller implementation of lane following, road sign detecting, obstacle avoiding robots.

Report can be found [here](https://github.com/felixboelter/Robotics-Road-Simulation/blob/main/Robotics_Project_2021.pdf).
### Road-sign Detection
![Road Sign Detection](https://github.com/felixboelter/Robotics-Road-Simulation/blob/main/Images/1.gif)
### Crossroad Detection
![Crossroad Detection](https://github.com/felixboelter/Robotics-Road-Simulation/blob/main/Images/2.gif)
### Lane recovery
![Crossroad Detection](https://github.com/felixboelter/Robotics-Road-Simulation/blob/main/Images/3.gif)
### Obstacle avoidance
![Crossroad Detection](https://github.com/felixboelter/Robotics-Road-Simulation/blob/main/Images/5.gif)
## Requirements
* ROS 2
* Gazebo 11.0.0 or higher
* PyTorch 1.8.1 or higher
## Installation
### 1. Add models to "~/.gazebo/models"
Add the contents of the folder "Models" to "~/.gazebo/models"
### 2. Launch the code using the launcher file
In the terminal you can run the following code to launch the environment into Gazebo,
```
roslaunch robotics_project_2021 robotics_project_2021.launch
```
### 3. Seeing what the robot sees
To see what the robot sees and the GUI. Open a new terminal and use the command,
```
rqt
```
