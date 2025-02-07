# ros2_control ABB Driver

## Dependencies:

- A robot description and moveit_config package, e.g. from https://github.com/dignakov/abb or ./abb_experimental
- https://github.com/ros-industrial/abb_libegm

## Compiling:
Please follow the directions here https://github.com/ros-controls/ros2_control_demos to set up ros2_control, ros2_controllers, and ros2_control_demos.

For now the directory structure should look something like this to have everything compile:

```
colcon_ws/src
|
├── abb (https://github.com/dignakov/abb)
├── abb_experimental (https://github.com/dignakov/abb_experimental)
├── abb_libegm (https://github.com/ros-industrial/abb_libegm)
└── ros2_control_abb_driver
```

## ABB Driver:

For testing, this needs a real robot or RobotWare compatible with libegm. RobotStudio testing setup instructions can be found [here](robot_studio/README.md).