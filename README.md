# ROS simulation for Neobotix mobile robots

This simulation package provides a quick and easy way to try out the autonomous mobile robots from Neobotix. It comes with the most commonly used configuration but is open for any kind of modification.

Please find our documentations in https://docs.neobotix.de/

<img src="https://raw.githubusercontent.com/neobotix/neo_simulation/melodic/neo_git.png">

## Source

source gazebo models and worlds:

```shell
echo 'export GAZEBO_MODEL_PATH=$(rospack find neo_simulation)/models:${GAZEBO_MODEL_PATH}' >> ~/.bashrc
```

```shell
echo 'export GAZEBO_RESOURCE_PATH=$(rospack find neo_simulation)/worlds:${GAZEBO_RESOURCE_PATH}' >> ~/.bashrc
```