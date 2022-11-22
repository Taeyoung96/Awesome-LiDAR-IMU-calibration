# Awesome-LiDAR-IMU-calibration [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)    

:sunglasses: A current list of LiDAR-IMU calibration method

## Introduction  

LiDAR and IMU are among the widely used sensors in the field of self-driving cars and robotics. To fuse both sensors and use them for algorithms (such as LiDAR-inertial SLAM), it is essential to obtain the exact extrinsic parameter.  

Inspired by [Deephome/Awesome-LiDAR-Camera-Calibration](https://github.com/Deephome/Awesome-LiDAR-Camera-Calibration), this repository summarizes the LiDAR-IMU calibration methods currently being studied in research fields and related toolboxes.  

<p align="center"><img src="figure.png" width = "500" ></p>  
The figure above is one of the figures in the paper "Target-free Extrinsic Calibration of a 3D-Lidar and an IMU".

## Related papers  
Target means calibration target.  
**"S"** means spatial information (Transformation matrix) and **"T"** means temporal information (time offset).  

|Paper|Published|Target|Key words|Code|  
| --- | --- | --- | --- | --- |
|3D Lidar-IMU Calibration Based on Upsampled Preintegrated Measurements for Motion Distortion Correction|[ICRA 2018](https://ieeexplore.ieee.org/document/8460179)|S+T|IMU Preintegration, Plane association|X|  
|Error modeling and extrinsic–intrinsic calibration for LiDAR-IMU system based on cone-cylinder features|[RAS 2019](https://www.sciencedirect.com/science/article/pii/S092188901730636X)|S| Cone-cylinder features, IMU intrinsic parameter, EKF based  |X|  
|Targetless Calibration of LiDAR-IMU System Based on Continuous-time Batch Estimation|[IROS 2020](https://ieeexplore.ieee.org/abstract/document/9341405)|S|Continous time trajectory, Surfel map|[LI-Calib](https://github.com/APRIL-ZJU/lidar_IMU_calib)| 
|A Novel Multifeature Based On-Site Calibration Method for LiDAR-IMU System|[TIE 2020](https://ieeexplore.ieee.org/abstract/document/8924904)|S|Multi-type geometric features, Cone-cylinder features(RAS 2019) extended version  |X|  
|Motion-based Calibration between Multiple LiDARs and INS with Rigid Body Constraint on Vehicle Platform|[IV 2020](https://ieeexplore.ieee.org/abstract/document/9304532)|S|Graph structure-based optimization, Multiple LiDAR |X|  
|Efficient Multi-sensor Aided Inertial Navigation with Online Calibration|[ICRA 2021](https://ieeexplore.ieee.org/abstract/document/9561254)|S+T|MSCKF based, Multi-sensor INS,  |X|  
|Target-free Extrinsic Calibration of a 3D-Lidar and an IMU|[MFI 2021](https://ieeexplore.ieee.org/abstract/document/9591180)|S|EKF based|[imu_lidar_calibration](https://github.com/unmannedlab/imu_lidar_calibration)|  
|3D LiDAR/IMU Calibration Based on Continuous-Time Trajectory Estimation in Structured Environments|[IEEE Access 2021](https://ieeexplore.ieee.org/abstract/document/9543701)|S|Continuous-Time Trajectory, Gaussian process(GP) regression|X|  
|Observability-Aware Intrinsic and Extrinsic Calibration of LiDAR-IMU Systems|[TRO 2022](https://ieeexplore.ieee.org/abstract/document/9787062)|S+T|LI-Calib(IROS 2020) extension version|[OA-LICalib](https://github.com/APRIL-ZJU/OA-LICalib)|  
|Robust Real-time LiDAR-inertial Initialization|[IROS 2022](https://arxiv.org/abs/2202.11006)|S+T|IESKF based, FAST-LIO initialization|[LI-Init](https://github.com/hku-mars/LiDAR_IMU_Init)|  
|An Extrinsic Calibration Method of a 3D-LiDAR and a Pose Sensor for Autonomous Driving|[Arxiv 2022](https://arxiv.org/pdf/2209.07694.pdf)|S|LiDAR-INS calibration part of OpenCalib|[LiDAR2INS](https://github.com/OpenCalib/LiDAR2INS)|  

## Other toolboxes  

|ToolBox|Keywords|
| --- | --- |
|[OpenCalib(SensorsCalibration)](https://github.com/PJLab-ADG/SensorsCalibration)|Calibration Toolbox for Autonomous Driving|  
|[chennuo0125-HIT/lidar_imu_calib](https://github.com/chennuo0125-HIT/lidar_imu_calib)|Only calculate extrinsic rotation parameter|
|[ethz-asl/lidar_align](https://github.com/ethz-asl/lidar_align)|Accurate results require highly non-planar motions|  

## Contacts  

If you have any question, feel free to leave an issue or send an email. :smile:

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  
