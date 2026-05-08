# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/lowlevel/pyro_utils.py

Prompts

```
['call a Pyro4 remote method safely with automatic ConnectionClosedError handling and traceback printing', 'wrap a Pyro4 remote call to catch ConnectionClosedError and re-raise as RuntimeError with method name', 'invoke a Pyro4 remote method and print the Pyro traceback when a generic exception occurs', 'review the safe_call function that wraps Pyro4 calls with connection error handling and traceback output', 'refactor the safe_call function to use a logger instead of print for Pyro traceback output', 'convert a canonical XYT coordinate to pyrobot coordinates using base_canonical_coords_to_pyrobot_coords', 'convert 3D pyrobot coordinates to canonical coordinates using xyz_pyrobot_to_canonical_coords', 'convert 3D canonical coordinates to pyrobot coordinates using xyz_canonical_coords_to_pyrobot_coords', 'inspect the pyrobot_to_canonical_frame 3x3 numpy transformation matrix for coordinate transforms', 'review the robot_coordinate_utils module and its coordinate transformation functions', 'review the MoverInterface abstract base class and its eight abstract methods for robot movement and sensor inputs', 'implement a concrete subclass of MoverInterface that provides logic for the bot_step method', 'implement the get_base_pos_in_canonical_coords, get_rgb_depth, get_pan, and get_tilt sensor input methods in a MoverInterface subclass', 'implement the move_relative, move_absolute, turn, and look_at movement methods in a MoverInterface subclass', 'refactor a MoverInterface subclass to add type hints and docstrings to each abstract method', 'compute yaw and pitch angles for a camera looking at a target 3D point from its current position', 'transform a point cloud into the geocentric frame using the camera position and yaw rotation', 'calculate a robot base move target position and yaw to approach a 3D point within an epsilon distance', 'generate a circular trajectory of waypoints around a target point starting from the robot nearest position', 'create a TrajectoryDataSaver instance to save RGB images, depth maps, segmentation masks, and robot poses to disk']
```

Usage

```
{'safe_call_pyro_remote_method': 'call a Pyro4 remote method safely with automatic ConnectionClosedError handling and traceback printing', 'handle_pyro_connection_errors': 'wrap a Pyro4 remote call to catch ConnectionClosedError and re-raise as RuntimeError with method name', 'get_pyro_traceback_on_error': 'invoke a Pyro4 remote method and print the Pyro traceback when a generic exception occurs', 'review_safe_call_function': 'review the safe_call function that wraps Pyro4 calls with connection error handling and traceback output', 'refactor_safe_call_for_logging': 'refactor the safe_call function to use a logger instead of print for Pyro traceback output'}
```

## File: facebookresearch_fairo/droidlet/lowlevel/robot_coordinate_utils.py

Prompts

```
['call a Pyro4 remote method safely with automatic ConnectionClosedError handling and traceback printing', 'wrap a Pyro4 remote call to catch ConnectionClosedError and re-raise as RuntimeError with method name', 'invoke a Pyro4 remote method and print the Pyro traceback when a generic exception occurs', 'review the safe_call function that wraps Pyro4 calls with connection error handling and traceback output', 'refactor the safe_call function to use a logger instead of print for Pyro traceback output', 'convert a canonical XYT coordinate to pyrobot coordinates using base_canonical_coords_to_pyrobot_coords', 'convert 3D pyrobot coordinates to canonical coordinates using xyz_pyrobot_to_canonical_coords', 'convert 3D canonical coordinates to pyrobot coordinates using xyz_canonical_coords_to_pyrobot_coords', 'inspect the pyrobot_to_canonical_frame 3x3 numpy transformation matrix for coordinate transforms', 'review the robot_coordinate_utils module and its coordinate transformation functions', 'review the MoverInterface abstract base class and its eight abstract methods for robot movement and sensor inputs', 'implement a concrete subclass of MoverInterface that provides logic for the bot_step method', 'implement the get_base_pos_in_canonical_coords, get_rgb_depth, get_pan, and get_tilt sensor input methods in a MoverInterface subclass', 'implement the move_relative, move_absolute, turn, and look_at movement methods in a MoverInterface subclass', 'refactor a MoverInterface subclass to add type hints and docstrings to each abstract method', 'compute yaw and pitch angles for a camera looking at a target 3D point from its current position', 'transform a point cloud into the geocentric frame using the camera position and yaw rotation', 'calculate a robot base move target position and yaw to approach a 3D point within an epsilon distance', 'generate a circular trajectory of waypoints around a target point starting from the robot nearest position', 'create a TrajectoryDataSaver instance to save RGB images, depth maps, segmentation masks, and robot poses to disk']
```

Usage

```
{'convert_base_canonical_to_pyrobot': 'convert a canonical XYT coordinate to pyrobot coordinates using base_canonical_coords_to_pyrobot_coords', 'convert_pyrobot_xyz_to_canonical': 'convert 3D pyrobot coordinates to canonical coordinates using xyz_pyrobot_to_canonical_coords', 'convert_canonical_xyz_to_pyrobot': 'convert 3D canonical coordinates to pyrobot coordinates using xyz_canonical_coords_to_pyrobot_coords', 'inspect_pyrobot_to_canonical_frame': 'inspect the pyrobot_to_canonical_frame 3x3 numpy transformation matrix for coordinate transforms', 'review_coordinate_transform_utils': 'review the robot_coordinate_utils module and its coordinate transformation functions'}
```

## File: facebookresearch_fairo/droidlet/lowlevel/robot_mover.py

Prompts

```
['call a Pyro4 remote method safely with automatic ConnectionClosedError handling and traceback printing', 'wrap a Pyro4 remote call to catch ConnectionClosedError and re-raise as RuntimeError with method name', 'invoke a Pyro4 remote method and print the Pyro traceback when a generic exception occurs', 'review the safe_call function that wraps Pyro4 calls with connection error handling and traceback output', 'refactor the safe_call function to use a logger instead of print for Pyro traceback output', 'convert a canonical XYT coordinate to pyrobot coordinates using base_canonical_coords_to_pyrobot_coords', 'convert 3D pyrobot coordinates to canonical coordinates using xyz_pyrobot_to_canonical_coords', 'convert 3D canonical coordinates to pyrobot coordinates using xyz_canonical_coords_to_pyrobot_coords', 'inspect the pyrobot_to_canonical_frame 3x3 numpy transformation matrix for coordinate transforms', 'review the robot_coordinate_utils module and its coordinate transformation functions', 'review the MoverInterface abstract base class and its eight abstract methods for robot movement and sensor inputs', 'implement a concrete subclass of MoverInterface that provides logic for the bot_step method', 'implement the get_base_pos_in_canonical_coords, get_rgb_depth, get_pan, and get_tilt sensor input methods in a MoverInterface subclass', 'implement the move_relative, move_absolute, turn, and look_at movement methods in a MoverInterface subclass', 'refactor a MoverInterface subclass to add type hints and docstrings to each abstract method', 'compute yaw and pitch angles for a camera looking at a target 3D point from its current position', 'transform a point cloud into the geocentric frame using the camera position and yaw rotation', 'calculate a robot base move target position and yaw to approach a 3D point within an epsilon distance', 'generate a circular trajectory of waypoints around a target point starting from the robot nearest position', 'create a TrajectoryDataSaver instance to save RGB images, depth maps, segmentation masks, and robot poses to disk']
```

Usage

```
{'review_MoverInterface': 'review the MoverInterface abstract base class and its eight abstract methods for robot movement and sensor inputs', 'implement_MoverInterface_bot_step': 'implement a concrete subclass of MoverInterface that provides logic for the bot_step method', 'implement_MoverInterface_sensor_inputs': 'implement the get_base_pos_in_canonical_coords, get_rgb_depth, get_pan, and get_tilt sensor input methods in a MoverInterface subclass', 'implement_MoverInterface_movement': 'implement the move_relative, move_absolute, turn, and look_at movement methods in a MoverInterface subclass', 'refactor_MoverInterface': 'refactor a MoverInterface subclass to add type hints and docstrings to each abstract method'}
```

## File: facebookresearch_fairo/droidlet/lowlevel/robot_mover_utils.py

Prompts

```
['call a Pyro4 remote method safely with automatic ConnectionClosedError handling and traceback printing', 'wrap a Pyro4 remote call to catch ConnectionClosedError and re-raise as RuntimeError with method name', 'invoke a Pyro4 remote method and print the Pyro traceback when a generic exception occurs', 'review the safe_call function that wraps Pyro4 calls with connection error handling and traceback output', 'refactor the safe_call function to use a logger instead of print for Pyro traceback output', 'convert a canonical XYT coordinate to pyrobot coordinates using base_canonical_coords_to_pyrobot_coords', 'convert 3D pyrobot coordinates to canonical coordinates using xyz_pyrobot_to_canonical_coords', 'convert 3D canonical coordinates to pyrobot coordinates using xyz_canonical_coords_to_pyrobot_coords', 'inspect the pyrobot_to_canonical_frame 3x3 numpy transformation matrix for coordinate transforms', 'review the robot_coordinate_utils module and its coordinate transformation functions', 'review the MoverInterface abstract base class and its eight abstract methods for robot movement and sensor inputs', 'implement a concrete subclass of MoverInterface that provides logic for the bot_step method', 'implement the get_base_pos_in_canonical_coords, get_rgb_depth, get_pan, and get_tilt sensor input methods in a MoverInterface subclass', 'implement the move_relative, move_absolute, turn, and look_at movement methods in a MoverInterface subclass', 'refactor a MoverInterface subclass to add type hints and docstrings to each abstract method', 'compute yaw and pitch angles for a camera looking at a target 3D point from its current position', 'transform a point cloud into the geocentric frame using the camera position and yaw rotation', 'calculate a robot base move target position and yaw to approach a 3D point within an epsilon distance', 'generate a circular trajectory of waypoints around a target point starting from the robot nearest position', 'create a TrajectoryDataSaver instance to save RGB images, depth maps, segmentation masks, and robot poses to disk']
```

Usage

```
{'get_camera_angles': 'compute yaw and pitch angles for a camera looking at a target 3D point from its current position', 'transform_pose': 'transform a point cloud into the geocentric frame using the camera position and yaw rotation', 'get_move_target_for_point': 'calculate a robot base move target position and yaw to approach a 3D point within an epsilon distance', 'get_circular_path': 'generate a circular trajectory of waypoints around a target point starting from the robot nearest position', 'TrajectoryDataSaver': 'create a TrajectoryDataSaver instance to save RGB images, depth maps, segmentation masks, and robot poses to disk'}
```

