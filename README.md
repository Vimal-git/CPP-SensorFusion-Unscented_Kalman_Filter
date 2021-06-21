# CPP-SensorFusion-Unscented_Kalman_Filter
* This project is a modified version of [this repo](https://github.com/udacity/SFND_Unscented_Kalman_Filter) shared as part of Udacity's Sensor Fusion Nano Degree Program.
* This project has the `ukf.h` and `ukf.cpp` files from `src` folder edited to enable simulation of sensor fusion using Unscented Kalman Filter to fuse measurements from Lidar and Radar.
## Important Dependencies
* cmake >= 3.5
  * All OSes: [click here for installation instructions](https://cmake.org/install/)
* make >= 4.1 (Linux, Mac), 3.81 (Windows)
  * Linux: make is installed by default on most Linux distros
  * Mac: [install Xcode command line tools to get make](https://developer.apple.com/xcode/features/)
  * Windows: [Click here for installation instructions](http://gnuwin32.sourceforge.net/packages/make.htm)
* gcc/g++ >= 5.4
  * Linux: gcc / g++ is installed by default on most Linux distros
  * Mac: same deal as make - [install Xcode command line tools](https://developer.apple.com/xcode/features/)
  * Windows: recommend using [MinGW](http://www.mingw.org/)
 * PCL 1.2

## Basic Build Instructions

1. Clone this repo.
2. Make a build directory: `mkdir build && cd build`
3. Compile: `cmake .. && make`
4. Run it: `./ukf_highway`

**Note: Additional details can be obtained from the file** `Instructions from Udacity.md`
