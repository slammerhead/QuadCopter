QuadCopter
==========

Contains the code necessary to run my quadcopter on a Raspberry PI. Will probably build on most linux distros, but will only run on Raspberry PI

### rpi
Contains macros and functions used to interact with the GPIO registers (Mostly stolen from http://www.pieter-jan.com/node/15)

### mpu6050
Stolen from the same place, has the code needed to to interact with my accelerometer / gyroscope

### esc
Sends signals to ESC's to control motor speeds

### main
For testing the mpu6050 code

### proximity
Hacked together to try and get data from the proximity sensor (sonar)
