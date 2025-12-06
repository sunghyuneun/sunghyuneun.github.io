# Overview
I created this in 2 weeks, for submission to Hack the North's application. 


# Mechanical
Reused flywheels from old Nerf Zeus gun.


![Assembled Turret](./assets/img/autonomous_turret/turretAssembled.png)
3D Printed Design, with the Flywheels Attached. 

# Software

![Color Detection](./assets/img/autonomous_turret/color-analyzer.png)

USB Webcam, ROS2, Raspberry Pi were used.
Written in Python, OpenCV, ROS2.
Colour masks, Erosion/Dilation, and Contour Detection were used to find centroid.

Writes centroid location through Serial to Arduino, which controls stepper motors.

![Turret Flowchart](./assets/img/autonomous_turret/turretFlowchart.png)

