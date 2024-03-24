# Car_Model2

This package contains the design for my car.

## Installation

To install this package, follow these steps:

```bash
# Create a ROS 2 workspace
mkdir -p ros2_ws/src

# Navigate to the src directory
cd ros2_ws/src

# Clone the repository
git clone https://github.com/Z-U-k0rkmaz/car_model2.git

# Navigate back to the ROS 2 workspace
cd ros2_ws

# Build the workspace
colcon build --symlink-install
```

## simulation
```bash
# Before launching the simulation, ensure that ROS 2 environment is properly sourced:
source /opt/ros/foxy/setup.bash
source ~/ros2_ws/install/setup.bash

# Gazebo launch file
launch car_model2 launch_sim.launch.py

# teleop twist keyboard
ros2 run teleop_twist_keyboard teleop_twist_keyboard
```

