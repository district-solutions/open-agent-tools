# Agent Python Tools

- repo: facebookresearch/pyrobot
- repo_uri: https://github.com/facebookresearch/pyrobot

## File: facebookresearch_pyrobot/robots/LoCoBot/locobot_control/scripts/locobot_control/active_camera.py

Prompts

```
['create an ActiveCamera instance to subscribe to ROS camera, depth, and joint state topics', 'set the camera pan and tilt angles using set_pan and set_tilt methods with range constraints', 'get the current camera image or depth data using get_image and get_depth methods', 'compute a 3D point in the base frame from a 2D pixel coordinate using get_3D', 'get the camera intrinsic projection matrix using the get_intrinsics method', 'calculate inverse kinematics for a 5DOF robot arm given position and quaternion orientation', 'compute the intersection points of two circles given their centers and radii', 'solve inverse kinematics for a target position and wrist angle using current arm configuration', 'convert a quaternion to Euler angles and solve inverse kinematics for robot arm joint angles', 'get joint angle solutions from Cartesian position and quaternion orientation with initial joint seed', 'create a Gripper instance that publishes to ROS topics for open and close commands', 'open the robot gripper fully with an optional blocking wait of 4 seconds', 'close the robot gripper fully with an optional blocking wait of 4 seconds', 'reset a stuck gripper by opening, closing, and opening it again sequentially', 'subscribe to the gripper state callback to track open, close, or faulty status', 'run the RobotTeleoperationServer to accept keyboard teleoperation commands for a LoCoBot robot', 'run the KeyboardTeleoperationClient to send keyboard commands to the teleoperation server', 'review the RobotTeleoperationServer class and its arm, base, gripper, and camera control methods', 'refactor the RobotTeleoperationServer move_arm method to support additional end-effector movement constraints', 'test the RobotTeleoperationServer check_safety method for collision avoidance heuristics']
```

Usage

```
{'create_active_camera_instance': 'create an ActiveCamera instance to subscribe to ROS camera, depth, and joint state topics', 'set_camera_pan_tilt': 'set the camera pan and tilt angles using set_pan and set_tilt methods with range constraints', 'get_camera_image_depth': 'get the current camera image or depth data using get_image and get_depth methods', 'compute_3d_point_from_pixel': 'compute a 3D point in the base frame from a 2D pixel coordinate using get_3D', 'get_camera_intrinsics': 'get the camera intrinsic projection matrix using the get_intrinsics method'}
```

## File: facebookresearch_pyrobot/robots/LoCoBot/locobot_control/scripts/locobot_control/analytic_ik.py

Prompts

```
['create an ActiveCamera instance to subscribe to ROS camera, depth, and joint state topics', 'set the camera pan and tilt angles using set_pan and set_tilt methods with range constraints', 'get the current camera image or depth data using get_image and get_depth methods', 'compute a 3D point in the base frame from a 2D pixel coordinate using get_3D', 'get the camera intrinsic projection matrix using the get_intrinsics method', 'calculate inverse kinematics for a 5DOF robot arm given position and quaternion orientation', 'compute the intersection points of two circles given their centers and radii', 'solve inverse kinematics for a target position and wrist angle using current arm configuration', 'convert a quaternion to Euler angles and solve inverse kinematics for robot arm joint angles', 'get joint angle solutions from Cartesian position and quaternion orientation with initial joint seed', 'create a Gripper instance that publishes to ROS topics for open and close commands', 'open the robot gripper fully with an optional blocking wait of 4 seconds', 'close the robot gripper fully with an optional blocking wait of 4 seconds', 'reset a stuck gripper by opening, closing, and opening it again sequentially', 'subscribe to the gripper state callback to track open, close, or faulty status', 'run the RobotTeleoperationServer to accept keyboard teleoperation commands for a LoCoBot robot', 'run the KeyboardTeleoperationClient to send keyboard commands to the teleoperation server', 'review the RobotTeleoperationServer class and its arm, base, gripper, and camera control methods', 'refactor the RobotTeleoperationServer move_arm method to support additional end-effector movement constraints', 'test the RobotTeleoperationServer check_safety method for collision avoidance heuristics']
```

Usage

```
{'calculate_inverse_kinematics_with_quaternion': 'calculate inverse kinematics for a 5DOF robot arm given position and quaternion orientation', 'compute_circle_intersection': 'compute the intersection points of two circles given their centers and radii', 'solve_ik_for_position_and_alpha': 'solve inverse kinematics for a target position and wrist angle using current arm configuration', 'convert_quaternion_to_euler_for_ik': 'convert a quaternion to Euler angles and solve inverse kinematics for robot arm joint angles', 'get_ik_joint_angles': 'get joint angle solutions from Cartesian position and quaternion orientation with initial joint seed'}
```

## File: facebookresearch_pyrobot/robots/LoCoBot/locobot_control/scripts/locobot_control/gripper.py

Prompts

```
['create an ActiveCamera instance to subscribe to ROS camera, depth, and joint state topics', 'set the camera pan and tilt angles using set_pan and set_tilt methods with range constraints', 'get the current camera image or depth data using get_image and get_depth methods', 'compute a 3D point in the base frame from a 2D pixel coordinate using get_3D', 'get the camera intrinsic projection matrix using the get_intrinsics method', 'calculate inverse kinematics for a 5DOF robot arm given position and quaternion orientation', 'compute the intersection points of two circles given their centers and radii', 'solve inverse kinematics for a target position and wrist angle using current arm configuration', 'convert a quaternion to Euler angles and solve inverse kinematics for robot arm joint angles', 'get joint angle solutions from Cartesian position and quaternion orientation with initial joint seed', 'create a Gripper instance that publishes to ROS topics for open and close commands', 'open the robot gripper fully with an optional blocking wait of 4 seconds', 'close the robot gripper fully with an optional blocking wait of 4 seconds', 'reset a stuck gripper by opening, closing, and opening it again sequentially', 'subscribe to the gripper state callback to track open, close, or faulty status', 'run the RobotTeleoperationServer to accept keyboard teleoperation commands for a LoCoBot robot', 'run the KeyboardTeleoperationClient to send keyboard commands to the teleoperation server', 'review the RobotTeleoperationServer class and its arm, base, gripper, and camera control methods', 'refactor the RobotTeleoperationServer move_arm method to support additional end-effector movement constraints', 'test the RobotTeleoperationServer check_safety method for collision avoidance heuristics']
```

Usage

```
{'create_gripper_instance': 'create a Gripper instance that publishes to ROS topics for open and close commands', 'open_gripper': 'open the robot gripper fully with an optional blocking wait of 4 seconds', 'close_gripper': 'close the robot gripper fully with an optional blocking wait of 4 seconds', 'reset_gripper': 'reset a stuck gripper by opening, closing, and opening it again sequentially', 'subscribe_gripper_state': 'subscribe to the gripper state callback to track open, close, or faulty status'}
```

## File: facebookresearch_pyrobot/robots/LoCoBot/locobot_control/scripts/locobot_control/teleoperation.py

Prompts

```
['create an ActiveCamera instance to subscribe to ROS camera, depth, and joint state topics', 'set the camera pan and tilt angles using set_pan and set_tilt methods with range constraints', 'get the current camera image or depth data using get_image and get_depth methods', 'compute a 3D point in the base frame from a 2D pixel coordinate using get_3D', 'get the camera intrinsic projection matrix using the get_intrinsics method', 'calculate inverse kinematics for a 5DOF robot arm given position and quaternion orientation', 'compute the intersection points of two circles given their centers and radii', 'solve inverse kinematics for a target position and wrist angle using current arm configuration', 'convert a quaternion to Euler angles and solve inverse kinematics for robot arm joint angles', 'get joint angle solutions from Cartesian position and quaternion orientation with initial joint seed', 'create a Gripper instance that publishes to ROS topics for open and close commands', 'open the robot gripper fully with an optional blocking wait of 4 seconds', 'close the robot gripper fully with an optional blocking wait of 4 seconds', 'reset a stuck gripper by opening, closing, and opening it again sequentially', 'subscribe to the gripper state callback to track open, close, or faulty status', 'run the RobotTeleoperationServer to accept keyboard teleoperation commands for a LoCoBot robot', 'run the KeyboardTeleoperationClient to send keyboard commands to the teleoperation server', 'review the RobotTeleoperationServer class and its arm, base, gripper, and camera control methods', 'refactor the RobotTeleoperationServer move_arm method to support additional end-effector movement constraints', 'test the RobotTeleoperationServer check_safety method for collision avoidance heuristics']
```

Usage

```
{'run_robot_teleoperation_server': 'run the RobotTeleoperationServer to accept keyboard teleoperation commands for a LoCoBot robot', 'run_keyboard_teleoperation_client': 'run the KeyboardTeleoperationClient to send keyboard commands to the teleoperation server', 'review_robot_teleoperation_server': 'review the RobotTeleoperationServer class and its arm, base, gripper, and camera control methods', 'refactor_move_arm': 'refactor the RobotTeleoperationServer move_arm method to support additional end-effector movement constraints', 'test_check_safety': 'test the RobotTeleoperationServer check_safety method for collision avoidance heuristics'}
```

