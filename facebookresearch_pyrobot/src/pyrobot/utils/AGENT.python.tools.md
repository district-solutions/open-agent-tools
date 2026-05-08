# Agent Python Tools

- repo: facebookresearch/pyrobot
- repo_uri: https://github.com/facebookresearch/pyrobot

## File: facebookresearch_pyrobot/src/pyrobot/utils/move_group_interface.py

Prompts

```
['create a MoveGroupInterface instance to control a robot arm via ROS MoveIt movegroup services', 'move a robot arm to target joint positions using the moveToJointPosition method with tolerance and wait parameters', 'move a robot arm end-effector to a target PoseStamped using the moveToPose method with position and orientation constraints', 'execute a Cartesian path along a list of waypoints using the followCartesian method with collision avoidance', 'plan a motion to target joint positions without executing, returning trajectory points via motionPlanToJointPosition', 'add a box collision object to the MoveIt planning scene with specified dimensions and pose', 'add a cylinder collision object to the planning scene with given height, radius, and pose', 'add a mesh collision object loaded from a file to the planning scene at a given pose', 'attach a box collision object to a specified robot link in the planning scene', 'remove a named collision object from the MoveIt planning scene by its identifier', 'convert a 6 or 7 element pose list into a ROS geometry_msgs Pose message using list_to_pose', 'lookup the translation and quaternion transform between two ROS TF frames using get_tf_transform', 'convert a quaternion in x,y,z,w format to a 3x3 rotation matrix using quat_to_rot_mat', 'convert yaw, pitch, roll euler angles to a quaternion using euler_to_quat with rzyx axis order', 'add a box type world object to the Moveit planning scene using MoveitObjectHandler add_world_object']
```

Usage

```
{'create_MoveGroupInterface': 'create a MoveGroupInterface instance to control a robot arm via ROS MoveIt movegroup services', 'moveToJointPosition': 'move a robot arm to target joint positions using the moveToJointPosition method with tolerance and wait parameters', 'moveToPose': 'move a robot arm end-effector to a target PoseStamped using the moveToPose method with position and orientation constraints', 'followCartesian': 'execute a Cartesian path along a list of waypoints using the followCartesian method with collision avoidance', 'motionPlanToJointPosition': 'plan a motion to target joint positions without executing, returning trajectory points via motionPlanToJointPosition'}
```

## File: facebookresearch_pyrobot/src/pyrobot/utils/planning_scene_interface.py

Prompts

```
['create a MoveGroupInterface instance to control a robot arm via ROS MoveIt movegroup services', 'move a robot arm to target joint positions using the moveToJointPosition method with tolerance and wait parameters', 'move a robot arm end-effector to a target PoseStamped using the moveToPose method with position and orientation constraints', 'execute a Cartesian path along a list of waypoints using the followCartesian method with collision avoidance', 'plan a motion to target joint positions without executing, returning trajectory points via motionPlanToJointPosition', 'add a box collision object to the MoveIt planning scene with specified dimensions and pose', 'add a cylinder collision object to the planning scene with given height, radius, and pose', 'add a mesh collision object loaded from a file to the planning scene at a given pose', 'attach a box collision object to a specified robot link in the planning scene', 'remove a named collision object from the MoveIt planning scene by its identifier', 'convert a 6 or 7 element pose list into a ROS geometry_msgs Pose message using list_to_pose', 'lookup the translation and quaternion transform between two ROS TF frames using get_tf_transform', 'convert a quaternion in x,y,z,w format to a 3x3 rotation matrix using quat_to_rot_mat', 'convert yaw, pitch, roll euler angles to a quaternion using euler_to_quat with rzyx axis order', 'add a box type world object to the Moveit planning scene using MoveitObjectHandler add_world_object']
```

Usage

```
{'add_box_to_planning_scene': 'add a box collision object to the MoveIt planning scene with specified dimensions and pose', 'add_cylinder_to_planning_scene': 'add a cylinder collision object to the planning scene with given height, radius, and pose', 'add_mesh_to_planning_scene': 'add a mesh collision object loaded from a file to the planning scene at a given pose', 'attach_box_to_robot_link': 'attach a box collision object to a specified robot link in the planning scene', 'remove_collision_object_from_scene': 'remove a named collision object from the MoveIt planning scene by its identifier'}
```

## File: facebookresearch_pyrobot/src/pyrobot/utils/util.py

Prompts

```
['create a MoveGroupInterface instance to control a robot arm via ROS MoveIt movegroup services', 'move a robot arm to target joint positions using the moveToJointPosition method with tolerance and wait parameters', 'move a robot arm end-effector to a target PoseStamped using the moveToPose method with position and orientation constraints', 'execute a Cartesian path along a list of waypoints using the followCartesian method with collision avoidance', 'plan a motion to target joint positions without executing, returning trajectory points via motionPlanToJointPosition', 'add a box collision object to the MoveIt planning scene with specified dimensions and pose', 'add a cylinder collision object to the planning scene with given height, radius, and pose', 'add a mesh collision object loaded from a file to the planning scene at a given pose', 'attach a box collision object to a specified robot link in the planning scene', 'remove a named collision object from the MoveIt planning scene by its identifier', 'convert a 6 or 7 element pose list into a ROS geometry_msgs Pose message using list_to_pose', 'lookup the translation and quaternion transform between two ROS TF frames using get_tf_transform', 'convert a quaternion in x,y,z,w format to a 3x3 rotation matrix using quat_to_rot_mat', 'convert yaw, pitch, roll euler angles to a quaternion using euler_to_quat with rzyx axis order', 'add a box type world object to the Moveit planning scene using MoveitObjectHandler add_world_object']
```

Usage

```
{'convert_pose_list_to_ros_pose': 'convert a 6 or 7 element pose list into a ROS geometry_msgs Pose message using list_to_pose', 'lookup_tf_transform_between_frames': 'lookup the translation and quaternion transform between two ROS TF frames using get_tf_transform', 'convert_quaternion_to_rotation_matrix': 'convert a quaternion in x,y,z,w format to a 3x3 rotation matrix using quat_to_rot_mat', 'convert_euler_angles_to_quaternion': 'convert yaw, pitch, roll euler angles to a quaternion using euler_to_quat with rzyx axis order', 'add_box_object_to_moveit_scene': 'add a box type world object to the Moveit planning scene using MoveitObjectHandler add_world_object'}
```

