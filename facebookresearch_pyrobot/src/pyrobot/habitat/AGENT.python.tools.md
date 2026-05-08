# Agent Python Tools

- repo: facebookresearch/pyrobot
- repo_uri: https://github.com/facebookresearch/pyrobot

## File: facebookresearch_pyrobot/src/pyrobot/habitat/base.py

Prompts

```
['create a LoCoBotBase instance with configs and simulator to initialize robot state in Habitat-Sim', 'execute a turn_left, turn_right, or move_forward action on the robot and check for collisions', 'get the robot current odometry state as x, y, yaw tuple relative to initial pose', 'move the robot to a relative x, y, yaw goal position from its initial pose', 'move the robot to an absolute x, y, yaw goal position in the world frame', 'get the RGB and depth images from the Habitat simulator camera observations', 'get the 3x3 camera intrinsic matrix with focal length and principal point values', 'convert pixel row and column indices to 3D points with RGB colors in camera or base frame', 'set the camera pan and tilt joint angles and update the sensor position and rotation', 'get the current point cloud with 3D coordinates and RGB colors from the depth and RGB images', 'build a Habitat-Sim simulator configuration with scene, physics, and sensor settings using make_cfg', 'create sensor specifications with uuid, type, resolution, and position from SIM config', 'create an agent action space with move_forward, turn_left, and turn_right actions', 'review the make_cfg function that builds SimulatorConfiguration with sensors and agent specs', 'refactor make_cfg to move hardcoded agent actions and gpu2gpu_transfer into the SIM config', 'create a HabitatSim instance with configs, scene_path, physics_config, and seed arguments', 'get the list of agent objects from the HabitatSim simulator using get_agents', 'get the dictionary of sensor IDs and sensors from the HabitatSim simulator using get_sensors', 'reset the Habitat simulator to its initial state using the reset method', 'set the random seed for the Habitat simulator using the set_seed method']
```

Usage

```
{'create_locobotbase_init': 'create a LoCoBotBase instance with configs and simulator to initialize robot state in Habitat-Sim', 'execute_action_turn_move': 'execute a turn_left, turn_right, or move_forward action on the robot and check for collisions', 'get_state_odom': 'get the robot current odometry state as x, y, yaw tuple relative to initial pose', 'go_to_relative_pose': 'move the robot to a relative x, y, yaw goal position from its initial pose', 'go_to_absolute_pose': 'move the robot to an absolute x, y, yaw goal position in the world frame'}
```

## File: facebookresearch_pyrobot/src/pyrobot/habitat/camera.py

Prompts

```
['create a LoCoBotBase instance with configs and simulator to initialize robot state in Habitat-Sim', 'execute a turn_left, turn_right, or move_forward action on the robot and check for collisions', 'get the robot current odometry state as x, y, yaw tuple relative to initial pose', 'move the robot to a relative x, y, yaw goal position from its initial pose', 'move the robot to an absolute x, y, yaw goal position in the world frame', 'get the RGB and depth images from the Habitat simulator camera observations', 'get the 3x3 camera intrinsic matrix with focal length and principal point values', 'convert pixel row and column indices to 3D points with RGB colors in camera or base frame', 'set the camera pan and tilt joint angles and update the sensor position and rotation', 'get the current point cloud with 3D coordinates and RGB colors from the depth and RGB images', 'build a Habitat-Sim simulator configuration with scene, physics, and sensor settings using make_cfg', 'create sensor specifications with uuid, type, resolution, and position from SIM config', 'create an agent action space with move_forward, turn_left, and turn_right actions', 'review the make_cfg function that builds SimulatorConfiguration with sensors and agent specs', 'refactor make_cfg to move hardcoded agent actions and gpu2gpu_transfer into the SIM config', 'create a HabitatSim instance with configs, scene_path, physics_config, and seed arguments', 'get the list of agent objects from the HabitatSim simulator using get_agents', 'get the dictionary of sensor IDs and sensors from the HabitatSim simulator using get_sensors', 'reset the Habitat simulator to its initial state using the reset method', 'set the random seed for the Habitat simulator using the set_seed method']
```

Usage

```
{'get_rgb_depth': 'get the RGB and depth images from the Habitat simulator camera observations', 'get_intrinsics': 'get the 3x3 camera intrinsic matrix with focal length and principal point values', 'pix_to_3dpt': 'convert pixel row and column indices to 3D points with RGB colors in camera or base frame', 'set_pan_tilt': 'set the camera pan and tilt joint angles and update the sensor position and rotation', 'get_current_pcd': 'get the current point cloud with 3D coordinates and RGB colors from the depth and RGB images'}
```

## File: facebookresearch_pyrobot/src/pyrobot/habitat/sim_utils.py

Prompts

```
['create a LoCoBotBase instance with configs and simulator to initialize robot state in Habitat-Sim', 'execute a turn_left, turn_right, or move_forward action on the robot and check for collisions', 'get the robot current odometry state as x, y, yaw tuple relative to initial pose', 'move the robot to a relative x, y, yaw goal position from its initial pose', 'move the robot to an absolute x, y, yaw goal position in the world frame', 'get the RGB and depth images from the Habitat simulator camera observations', 'get the 3x3 camera intrinsic matrix with focal length and principal point values', 'convert pixel row and column indices to 3D points with RGB colors in camera or base frame', 'set the camera pan and tilt joint angles and update the sensor position and rotation', 'get the current point cloud with 3D coordinates and RGB colors from the depth and RGB images', 'build a Habitat-Sim simulator configuration with scene, physics, and sensor settings using make_cfg', 'create sensor specifications with uuid, type, resolution, and position from SIM config', 'create an agent action space with move_forward, turn_left, and turn_right actions', 'review the make_cfg function that builds SimulatorConfiguration with sensors and agent specs', 'refactor make_cfg to move hardcoded agent actions and gpu2gpu_transfer into the SIM config', 'create a HabitatSim instance with configs, scene_path, physics_config, and seed arguments', 'get the list of agent objects from the HabitatSim simulator using get_agents', 'get the dictionary of sensor IDs and sensors from the HabitatSim simulator using get_sensors', 'reset the Habitat simulator to its initial state using the reset method', 'set the random seed for the Habitat simulator using the set_seed method']
```

Usage

```
{'build_habitat_sim_config': 'build a Habitat-Sim simulator configuration with scene, physics, and sensor settings using make_cfg', 'create_sensor_specs': 'create sensor specifications with uuid, type, resolution, and position from SIM config', 'create_agent_action_space': 'create an agent action space with move_forward, turn_left, and turn_right actions', 'review_make_cfg': 'review the make_cfg function that builds SimulatorConfiguration with sensors and agent specs', 'refactor_make_cfg': 'refactor make_cfg to move hardcoded agent actions and gpu2gpu_transfer into the SIM config'}
```

## File: facebookresearch_pyrobot/src/pyrobot/habitat/simulator.py

Prompts

```
['create a LoCoBotBase instance with configs and simulator to initialize robot state in Habitat-Sim', 'execute a turn_left, turn_right, or move_forward action on the robot and check for collisions', 'get the robot current odometry state as x, y, yaw tuple relative to initial pose', 'move the robot to a relative x, y, yaw goal position from its initial pose', 'move the robot to an absolute x, y, yaw goal position in the world frame', 'get the RGB and depth images from the Habitat simulator camera observations', 'get the 3x3 camera intrinsic matrix with focal length and principal point values', 'convert pixel row and column indices to 3D points with RGB colors in camera or base frame', 'set the camera pan and tilt joint angles and update the sensor position and rotation', 'get the current point cloud with 3D coordinates and RGB colors from the depth and RGB images', 'build a Habitat-Sim simulator configuration with scene, physics, and sensor settings using make_cfg', 'create sensor specifications with uuid, type, resolution, and position from SIM config', 'create an agent action space with move_forward, turn_left, and turn_right actions', 'review the make_cfg function that builds SimulatorConfiguration with sensors and agent specs', 'refactor make_cfg to move hardcoded agent actions and gpu2gpu_transfer into the SIM config', 'create a HabitatSim instance with configs, scene_path, physics_config, and seed arguments', 'get the list of agent objects from the HabitatSim simulator using get_agents', 'get the dictionary of sensor IDs and sensors from the HabitatSim simulator using get_sensors', 'reset the Habitat simulator to its initial state using the reset method', 'set the random seed for the Habitat simulator using the set_seed method']
```

Usage

```
{'create_HabitatSim_instance': 'create a HabitatSim instance with configs, scene_path, physics_config, and seed arguments', 'get_agents_HabitatSim': 'get the list of agent objects from the HabitatSim simulator using get_agents', 'get_sensors_HabitatSim': 'get the dictionary of sensor IDs and sensors from the HabitatSim simulator using get_sensors', 'reset_HabitatSim': 'reset the Habitat simulator to its initial state using the reset method', 'set_seed_HabitatSim': 'set the random seed for the Habitat simulator using the set_seed method'}
```

