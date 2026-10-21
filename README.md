# RobiDuo

Robot model, chassis driver, and arm firmware resources for RobiDuo.

## Robot description

[Download the RobiDuo URDF archive](RobiDuo_ros2.zip).

`RobiDuo_ros2.zip` is the URDF robot-description archive for RobiDuo. The original archive is provided unchanged.

## Chassis driver

[Download the DT chassis driver V1.1.3](chassis_driver/dt_control_ros_V1.1.3.zip).

The original driver archive is provided unchanged. It contains:

- `dt_control`: chassis communication and control node, including the supplier's launch file and documentation.
- `dt_control_msgs`: chassis message definitions and documentation.

This driver uses **ROS 1 / catkin** (`roscpp`), not ROS 2. The supplier documentation identifies the driver as V1.1.3 and the message package as V1.1.1; the package manifests still declare version 1.0.0. Driver compatibility and chassis operation have not been tested here. Extract the archive to access the supplier's integration instructions. Original comments and documentation are retained in their supplied language.

## Arm firmware

[Download arm firmware from Google Drive](https://drive.google.com/drive/folders/1r7pd_gfpbZOjxODhQRNSVo-EK5FLSH62?usp=sharing).

Arm firmware is distributed through the linked folder; firmware files are not stored in this repository.
