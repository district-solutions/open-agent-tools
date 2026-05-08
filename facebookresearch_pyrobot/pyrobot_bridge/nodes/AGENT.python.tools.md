# Agent Python Tools

- repo: facebookresearch/pyrobot
- repo_uri: https://github.com/facebookresearch/pyrobot

## File: facebookresearch_pyrobot/pyrobot_bridge/nodes/kinematics.py

Prompts

```
['run the ROS kinematics node that exposes inverse and forward kinematics services', 'create a TRAC-IK solver to compute joint positions from a target pose and tolerance', 'build a forward kinematics solver that computes end-effector pose from joint angles', 'convert a 3x3 rotation matrix into a quaternion using tf.transformations', 'convert a numpy array of joint values into a PyKDL JntArray for KDL solvers', 'run the MoveitInterface ROS node to interface moveit tools with pyrobot', 'create a MoveitInterface instance that initializes the pyrobot moveit ROS action server', 'compute a motion plan to achieve desired target joint angles using _compute_plan', 'set robot joint positions by computing and executing a MoveIt trajectory plan', 'move the robot end effector along XYZ waypoints using cartesian path planning']
```

Usage

```
{'run_kinematics_server': 'run the ROS kinematics node that exposes inverse and forward kinematics services', 'create_ik_solver': 'create a TRAC-IK solver to compute joint positions from a target pose and tolerance', 'build_fk_solver': 'build a forward kinematics solver that computes end-effector pose from joint angles', 'convert_rotation_matrix_to_quaternion': 'convert a 3x3 rotation matrix into a quaternion using tf.transformations', 'convert_joints_to_kdl': 'convert a numpy array of joint values into a PyKDL JntArray for KDL solvers'}
```

## File: facebookresearch_pyrobot/pyrobot_bridge/nodes/moveit_bridge.py

Prompts

```
['run the ROS kinematics node that exposes inverse and forward kinematics services', 'create a TRAC-IK solver to compute joint positions from a target pose and tolerance', 'build a forward kinematics solver that computes end-effector pose from joint angles', 'convert a 3x3 rotation matrix into a quaternion using tf.transformations', 'convert a numpy array of joint values into a PyKDL JntArray for KDL solvers', 'run the MoveitInterface ROS node to interface moveit tools with pyrobot', 'create a MoveitInterface instance that initializes the pyrobot moveit ROS action server', 'compute a motion plan to achieve desired target joint angles using _compute_plan', 'set robot joint positions by computing and executing a MoveIt trajectory plan', 'move the robot end effector along XYZ waypoints using cartesian path planning']
```

Usage

```
{'run_moveit_bridge_node': 'run the MoveitInterface ROS node to interface moveit tools with pyrobot', 'create_moveit_interface': 'create a MoveitInterface instance that initializes the pyrobot moveit ROS action server', 'compute_motion_plan': 'compute a motion plan to achieve desired target joint angles using _compute_plan', 'set_joint_positions': 'set robot joint positions by computing and executing a MoveIt trajectory plan', 'move_ee_xyz': 'move the robot end effector along XYZ waypoints using cartesian path planning'}
```

