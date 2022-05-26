# Witmotion WT901C TTL ROS
This is a Python code for Witmotion's WT901CTTL IMU sensor (Acceleromenter, Gyroscope, and Magnetometer)

## License and Origin Code
* MIT License
* github address of Origin Code : https://github.com/6Harmony9/Witmotion-WT901CTTL-Python

## Descriptiong of Code
* For using WIT-Motion's WT901CTTL with ROS(noetic) -> developing
* It will be tested on Ubuntu 20.04 + ROS noetic ASAP

## HARDWARE
* WIT-Motion's WT901CTTL
* USB-TTL Converter

## Dependancy
* If you get some error like this : [Python] AttributeError: module 'serial' has no attribute 'Serial'
* Use this commands for fixing error

```
pip install pyserial # Use Python 2.x

pip3 install pyserial # Use Python 3.x
```

## Usage

```
sudo chmod 666 /dev/ttyUSB0 # port
rosrun wt901cttl_ros WT901.py
```
