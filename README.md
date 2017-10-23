# Unscented Kalman Filter Project 
By Pablo Sauras Perez

## Submission code location
The submited code can be found in the **src** directory. In particular, the following files have been modified:
- ukf.cpp
- tools.cpp

## Important Depencencies
As stated in the project description, these are the important dependencies.
- cmake >= 3.5
- make >= 4.1 (Linux, Mac), 3.81 (Windows)
- gcc/g++ >= 5.4

## Basic Build Instructions
As stated in th project description, from the project top directory:
- ```mkdir build && cd build```
- ```cmake .. && make```
-   ```./UnscentedKF```

## Results
As it can be seen in the next figures, ```px, py, vx, vy``` output coordinates have an **RMSE <= [.09, .10, 0.40, 0.30]** when using the file: _obj_pose-laser-radar-synthetic-input.txt_ which is the same data file the simulator uses for Dataset 1.

![Alt text](/UKF_RMSE.jpg?raw=true "RMSE for Dataset 1")


As it can be seen, the RMSE result meets specifications.
