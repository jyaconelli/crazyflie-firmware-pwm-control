# Crazyflie 2.0 Firmware with PWM Control

Takes pwm values to control crazyflie instead of roll, pitch, yaw, and thrust. Send a single int32 containing the two most significant bits of each pwm value in this order:
```
0xDDCCBBAA
AA = motor 1
BB = motor 2
CC = motor 3
DD = motor 4
```

Intended for use in conjunction with https://github.com/josephyaconelli/crazyflie_ros-pwm-control
