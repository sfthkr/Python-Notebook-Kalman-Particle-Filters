# UKF - Sensor Fusion

Python notebook written for sensor fusion application using unscented Kalman filter. 

There are two sensors:
  - Radar
  - Lidar

Sensor measurements are read from *.txt* file which is adapted from Udacity Self Driving Car Course's sensor fusion project. Each line in *.txt* file is a sensor measurement either captured from Lidar or Radar with a timestamp value. Each line's first character is either 'L' or 'R' which indicates Lidar or Radar measurements respectively. 

The state and measurement equations and matrices are described in the notebook. Constant Turn Rate and Velocity (CTRV) is used for the state update. Since the process noise couldn't be expressed as an seperate matrix, the augmented state UKF should be used. 

More information could be found in:
https://github.com/udacity/CarND-Unscented-Kalman-Filter-Project


