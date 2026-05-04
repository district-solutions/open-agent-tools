# Agent Python Tools

- repo: google-deepmind/dmrobotics
- repo_uri: https://github.com/google-deepmind/dm_robotics

## File: google-deepmind_dmrobotics/py/moma/models/robots/robot_arms/robot_arm.py

Prompts

```
['create a subclass of RobotArm that implements _build, joints, actuators, and mjcf_model', 'implement set_joint_angles in a RobotArm subclass to configure joint positions from a numpy array', 'access the joints property on a RobotArm subclass to get the list of MuJoCo joint elements', 'access the actuators property on a RobotArm subclass to get the list of MuJoCo actuator elements', 'use the attachment_site property on a RobotArm subclass to get the wrist site for attaching elements', 'build a Sawyer robot arm MJCF model with integrated velocity actuators and collision geometries', 'set the Sawyer robot arm joints to a given configuration using physics and joint angles', 'initialize a simulation episode for the Sawyer robot arm with gravity compensation applied', 'add collision geometries to the Sawyer robot arm MJCF model for physics simulation', 'get the list of actuator elements belonging to the Sawyer robot arm for control', 'compute the tcp pose from a given pinch pose numpy array using tcp_pose_from_pinch_pose', 'check the sawyer robot arm joint limits using the JOINT_LIMITS constant dictionary', 'check the sawyer robot arm velocity limits using the VELOCITY_LIMITS constant dictionary', 'check the sawyer robot arm effort limits in Nm using the EFFORT_LIMITS constant dictionary', 'get the sawyer robot arm joint names tuple using the JOINT_NAMES constant', 'test the Sawyer robot class by creating an instance and stepping its MuJoCo physics simulation', 'test the Sawyer robot initialize_episode method with a physics object and random state seed', 'test the Sawyer robot set_joint_angles method by setting joint positions and verifying physics state', 'test the Sawyer robot after_substep method to verify actuator values are clipped to joint limits', 'test the Sawyer robot joints, actuators, wrist_site, and joint_torque_sensors properties for correct types and counts']
```

Usage

```
{'implement_RobotArm_subclass': 'create a subclass of RobotArm that implements _build, joints, actuators, and mjcf_model', 'implement_set_joint_angles': 'implement set_joint_angles in a RobotArm subclass to configure joint positions from a numpy array', 'access_joints_property': 'access the joints property on a RobotArm subclass to get the list of MuJoCo joint elements', 'access_actuators_property': 'access the actuators property on a RobotArm subclass to get the list of MuJoCo actuator elements', 'use_attachment_site': 'use the attachment_site property on a RobotArm subclass to get the wrist site for attaching elements'}
```

## File: google-deepmind_dmrobotics/py/moma/models/robots/robot_arms/sawyer.py

Prompts

```
['create a subclass of RobotArm that implements _build, joints, actuators, and mjcf_model', 'implement set_joint_angles in a RobotArm subclass to configure joint positions from a numpy array', 'access the joints property on a RobotArm subclass to get the list of MuJoCo joint elements', 'access the actuators property on a RobotArm subclass to get the list of MuJoCo actuator elements', 'use the attachment_site property on a RobotArm subclass to get the wrist site for attaching elements', 'build a Sawyer robot arm MJCF model with integrated velocity actuators and collision geometries', 'set the Sawyer robot arm joints to a given configuration using physics and joint angles', 'initialize a simulation episode for the Sawyer robot arm with gravity compensation applied', 'add collision geometries to the Sawyer robot arm MJCF model for physics simulation', 'get the list of actuator elements belonging to the Sawyer robot arm for control', 'compute the tcp pose from a given pinch pose numpy array using tcp_pose_from_pinch_pose', 'check the sawyer robot arm joint limits using the JOINT_LIMITS constant dictionary', 'check the sawyer robot arm velocity limits using the VELOCITY_LIMITS constant dictionary', 'check the sawyer robot arm effort limits in Nm using the EFFORT_LIMITS constant dictionary', 'get the sawyer robot arm joint names tuple using the JOINT_NAMES constant', 'test the Sawyer robot class by creating an instance and stepping its MuJoCo physics simulation', 'test the Sawyer robot initialize_episode method with a physics object and random state seed', 'test the Sawyer robot set_joint_angles method by setting joint positions and verifying physics state', 'test the Sawyer robot after_substep method to verify actuator values are clipped to joint limits', 'test the Sawyer robot joints, actuators, wrist_site, and joint_torque_sensors properties for correct types and counts']
```

Usage

```
{'build_sawyer_robot_arm': 'build a Sawyer robot arm MJCF model with integrated velocity actuators and collision geometries', 'set_joint_angles_sawyer': 'set the Sawyer robot arm joints to a given configuration using physics and joint angles', 'initialize_episode_sawyer': 'initialize a simulation episode for the Sawyer robot arm with gravity compensation applied', 'add_collision_geoms_sawyer': 'add collision geometries to the Sawyer robot arm MJCF model for physics simulation', 'get_actuators_sawyer': 'get the list of actuator elements belonging to the Sawyer robot arm for control'}
```

## File: google-deepmind_dmrobotics/py/moma/models/robots/robot_arms/sawyer_constants.py

Prompts

```
['create a subclass of RobotArm that implements _build, joints, actuators, and mjcf_model', 'implement set_joint_angles in a RobotArm subclass to configure joint positions from a numpy array', 'access the joints property on a RobotArm subclass to get the list of MuJoCo joint elements', 'access the actuators property on a RobotArm subclass to get the list of MuJoCo actuator elements', 'use the attachment_site property on a RobotArm subclass to get the wrist site for attaching elements', 'build a Sawyer robot arm MJCF model with integrated velocity actuators and collision geometries', 'set the Sawyer robot arm joints to a given configuration using physics and joint angles', 'initialize a simulation episode for the Sawyer robot arm with gravity compensation applied', 'add collision geometries to the Sawyer robot arm MJCF model for physics simulation', 'get the list of actuator elements belonging to the Sawyer robot arm for control', 'compute the tcp pose from a given pinch pose numpy array using tcp_pose_from_pinch_pose', 'check the sawyer robot arm joint limits using the JOINT_LIMITS constant dictionary', 'check the sawyer robot arm velocity limits using the VELOCITY_LIMITS constant dictionary', 'check the sawyer robot arm effort limits in Nm using the EFFORT_LIMITS constant dictionary', 'get the sawyer robot arm joint names tuple using the JOINT_NAMES constant', 'test the Sawyer robot class by creating an instance and stepping its MuJoCo physics simulation', 'test the Sawyer robot initialize_episode method with a physics object and random state seed', 'test the Sawyer robot set_joint_angles method by setting joint positions and verifying physics state', 'test the Sawyer robot after_substep method to verify actuator values are clipped to joint limits', 'test the Sawyer robot joints, actuators, wrist_site, and joint_torque_sensors properties for correct types and counts']
```

Usage

```
{'compute_tcp_pose_from_pinch_pose': 'compute the tcp pose from a given pinch pose numpy array using tcp_pose_from_pinch_pose', 'check_sawyer_joint_limits': 'check the sawyer robot arm joint limits using the JOINT_LIMITS constant dictionary', 'check_sawyer_velocity_limits': 'check the sawyer robot arm velocity limits using the VELOCITY_LIMITS constant dictionary', 'check_sawyer_effort_limits': 'check the sawyer robot arm effort limits in Nm using the EFFORT_LIMITS constant dictionary', 'get_sawyer_joint_names': 'get the sawyer robot arm joint names tuple using the JOINT_NAMES constant'}
```

## File: google-deepmind_dmrobotics/py/moma/models/robots/robot_arms/sawyer_test.py

Prompts

```
['create a subclass of RobotArm that implements _build, joints, actuators, and mjcf_model', 'implement set_joint_angles in a RobotArm subclass to configure joint positions from a numpy array', 'access the joints property on a RobotArm subclass to get the list of MuJoCo joint elements', 'access the actuators property on a RobotArm subclass to get the list of MuJoCo actuator elements', 'use the attachment_site property on a RobotArm subclass to get the wrist site for attaching elements', 'build a Sawyer robot arm MJCF model with integrated velocity actuators and collision geometries', 'set the Sawyer robot arm joints to a given configuration using physics and joint angles', 'initialize a simulation episode for the Sawyer robot arm with gravity compensation applied', 'add collision geometries to the Sawyer robot arm MJCF model for physics simulation', 'get the list of actuator elements belonging to the Sawyer robot arm for control', 'compute the tcp pose from a given pinch pose numpy array using tcp_pose_from_pinch_pose', 'check the sawyer robot arm joint limits using the JOINT_LIMITS constant dictionary', 'check the sawyer robot arm velocity limits using the VELOCITY_LIMITS constant dictionary', 'check the sawyer robot arm effort limits in Nm using the EFFORT_LIMITS constant dictionary', 'get the sawyer robot arm joint names tuple using the JOINT_NAMES constant', 'test the Sawyer robot class by creating an instance and stepping its MuJoCo physics simulation', 'test the Sawyer robot initialize_episode method with a physics object and random state seed', 'test the Sawyer robot set_joint_angles method by setting joint positions and verifying physics state', 'test the Sawyer robot after_substep method to verify actuator values are clipped to joint limits', 'test the Sawyer robot joints, actuators, wrist_site, and joint_torque_sensors properties for correct types and counts']
```

Usage

```
{'test_sawyer_physics_step': 'test the Sawyer robot class by creating an instance and stepping its MuJoCo physics simulation', 'test_sawyer_initialize_episode': 'test the Sawyer robot initialize_episode method with a physics object and random state seed', 'test_sawyer_set_joint_angles': 'test the Sawyer robot set_joint_angles method by setting joint positions and verifying physics state', 'test_sawyer_after_substep_clipping': 'test the Sawyer robot after_substep method to verify actuator values are clipped to joint limits', 'test_sawyer_robot_properties': 'test the Sawyer robot joints, actuators, wrist_site, and joint_torque_sensors properties for correct types and counts'}
```

