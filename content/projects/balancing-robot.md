# Overview
Created a simple balancing robot model in Gazebo, with rectangular prism and wheels.

# Gazebo Simulation - PID

![Failed PID Parameters](./assets/img/balancing_bot/gazebo3.gif)

Model with Failed PID Parameters


![Successful PID](./assets/img/balancing_bot/gazebo4.gif)

Successful Balancing PID Program


# RL Controls
See ML projects for CartPole (Basic RL controls)
![CartPole](./assets/img/machine_learning/CartPole.gif)


What's next: 
- Cascading PID Control. Angle PID inner loop, velocity PID outer loop
- Reinforcement learning controls in Gazebo (or Nvidia Isaac or MuJoCo)
- Properly tuning PID using classical control theory. 

# Physical Model
In progress, will use Arduino, Stepper Motors, MPU6050 IMU
![Balancing Robot Altium](./assets/img/balancing_bot/balanceAltium.png)