# mockturtlebot2

ROS2 from scratch, learning by doing

A simple ros2 differential drive robot.

Hardware components
===================
- Intel NUC 
- Arduino NANO + Servoboard
- LiFePO Accu 3S 11.2V 3200mAh
- Step-Up/Step-Down converters for NUC and controllers
- RC car servocontroller
- DC motors
- Intel R200 / Kinect V1 / USB CAM
- Sonar HC-SR04
- 3DoF Razor like IMU

Software components
===================
- Ubuntu 18.04 LTS Server
- ROS2 Eloquent 
- PyMata-AIO
- py-trees

Requirements
============
apt install python3
apt install python3-pip
pip3 install pymata-aio

Arduino IDE
===========
flash firmataplus from pymata-aio to arduino hardware


Sources:
========
Servoboard
https://www.amazon.de/IZOKEE-Erweiterungs-Sensor-Shield-Arduino/dp/B07KCDLBMG/ref=pd_sbs_147_1?_encoding=UTF8&pd_rd_i=B07KCDLBMG&pd_rd_r=b32c4b1f-1985-11e9-b411-653be4f1f91d&pd_rd_w=6LGBe&pd_rd_wg=pVDeB&pf_rd_p=51bcaa00-4765-4e8f-a690-5db3c9ed1b31&pf_rd_r=8TMPCJJ44FKY80Z49SD7&psc=1&refRID=8TMPCJJ44FKY80Z49SD7#HLCXComparisonWidget_feature_div

Pymata-IO
https://github.com/MrYsLab/pymata-aio

All samples are pure python3 programs

Stay tuned
