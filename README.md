# VIO_with_Kalman_filtering_KITTI_Dataset

In this project, the egomotion of the vehicle is estimated from a sequence of stereo images using Visual Odometry (VO). Since Visual Odometry is used to calculate the movement of the camera through continuously adding new poses, any inaccuracies in each successive frame-to-frame motion will build up over time. As a result, the estimated trajectory gradually deviates from the actual path, creating drift. With the goal of reducing the error drift, implemented an Kalman Filter (KF) to get better state estimates. The algorithm’s effectiveness is showcased through experiments on KITTI Vission Benchmark Suite. These experiments provide sufficient evidence of the algorithm’s capabilities, and demonstrate its ability to achieve results on a range of tasks.

Feature Detection Comparision (500 features) | Feature Matching Comparison (100 features matching)
--- | ---
![](https://github.com/RenuReddyK/VIO_with_Kalman_filtering_KITTI_dataset/assets/68454938/8b53dd47-2e91-4cf1-8053-a470215161ae") | ![](https://github.com/RenuReddyK/VIO_with_Kalman_filtering_KITTI_dataset/assets/68454938/1805f35e-33e9-4d53-b79b-61ea13bd8ad9)

Visual Odometry Vs Filtered Path | VO path Error Vs Filtered path Error with respect to ground truth
--- | --- 
![](https://github.com/RenuReddyK/VIO_with_Kalman_filtering_KITTI_dataset/assets/68454938/64f20059-5db6-419b-b6bb-2210e084250b") | ![](https://github.com/RenuReddyK/VIO_with_Kalman_filtering_KITTI_dataset/assets/68454938/092e3e10-3053-4a04-958f-1c05c11702e3)

Translation along x direction | Translation along y direction
--- | --- 
![](https://github.com/RenuReddyK/VIO_with_Kalman_filtering_KITTI_dataset/assets/68454938/ca92ae5e-b9dc-4849-9f4c-fccefbcbca00") | ![](https://github.com/RenuReddyK/VIO_with_Kalman_filtering_KITTI_dataset/assets/68454938/d619b753-6567-464c-b017-22ffb2ceb2de)

