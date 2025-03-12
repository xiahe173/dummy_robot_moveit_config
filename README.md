# Dummy Robot MoveIt Configuration Package

## Installation

1. Install [Dummy Robot Description Package](https://github.com/aod321/dummy_robot_description), build and source `setup.bash` \(or `setup.zsh`\).
2. Clone this repository into your ROS2 workspace.
```bash
cd ~/ros2_ws/src
git clone https://github.com/xiahe173/dummy_robot_moveit_config
```

## Build 
```bash
cd ~/ros2_ws
colcon build
source install/setup.bash  # Use setup.zsh if using zsh
```

## Usage

### Demo
```bash
ros2 launch dummy_robot_moveit_config demo.launch.py
```

