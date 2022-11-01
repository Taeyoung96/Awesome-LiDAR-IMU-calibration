# Awesome-LiDAR-IMU-calibration [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)    

## Introduction  

LiDAR and IMU are among the widely used sensors in the field of self-driving cars and robotics. To fuse both sensors and use them for algorithms (such as SLAM), it is essential to obtain the exact extrinsic parameter.  

Inspired by [Deephome/Awesome-LiDAR-Camera-Calibration](https://github.com/Deephome/Awesome-LiDAR-Camera-Calibration), this repository summarizes the LiDAR-IMU calibration methods currently being studied in research fields and related toolboxes.  

<p align="center"><img src="figure.png" width = "500" ></p>  
The figure above is one of the figures in the paper "Target-free Extrinsic Calibration of a 3D-Lidar and an IMU".

## Related papers  
Target means calibration target.  
"S" means spatial information (Transformation matrix) and "T" means temporal information (time offset).  

|Paper|Published|Target|Key words|Code|  
| --- | --- | --- | --- | --- |
|3D Lidar-IMU Calibration Based on Upsampled Preintegrated Measurements for Motion Distortion Correction|[ICRA 2018](https://ieeexplore.ieee.org/document/8460179)|S+T|IMU Preintegration, Plane association|X|  

## Other toolboxes  

