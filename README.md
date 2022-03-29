# ROS-Imu-Callibration
Repo contains guide on how to callibrate TF transform of imu correctly in ROS. Callibration is done on example of Phigets IMU

## Usage


1. Clone repo to ros workspace
2. Build using `catkin_make`
3. Connect imu to laptop/robot
4. Run test

```
roslaunch imu_calibration imu_test.launch
```

5. Check if arrow coresponds to robot movement, if not change transform [here](imu_calibration/launch/phidgets_imu.launch)
