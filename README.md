# Gyro Robot

A two-wheeled balancing robot that uses an IMU 6050 to balance by applying the principle of the inverted pendulum control system. The project demonstrates the application of stepper motors for position control with a set point fed to a PID controller, and a feedback loop based on the yaw, pitch,roll values from an IMU 6050. The device is powered using a 1600 mAh LiPo 4s1p cell and controlled using an Arduino with an Adafruit Motor Control Shield V2.

## Getting Started

Uploading to Arduino using [PlatformIO](https://platformio.org/)
```
git clone https://github.com/serant/GyroBot
platformio run
```

### BOM
* Chassis, I designed and 3D printed mine, available [here]()
* NEMA 17 Stepper Motor
* MPU 6050 Accelerometer and Gyro
* 4s1p lipo cell 1600 mAh
* Arduino Uno R3
* Adafruit Motor Control Shield V2
* Everything can be assembled using M5 screws and hot glue

## Built With
* [Arduino](https://arduino.cc/)
* [MPU 6050](https://playground.arduino.cc/Main/MPU-6050)
* [Stepper Motor](https://www.sparkfun.com/tutorials/400)
* [PID Control](https://playground.arduino.cc/Code/PIDLibrary)
* [PlatformIO](https://platformio.org/)

## Authors

* **Seran Thirugnanam**
