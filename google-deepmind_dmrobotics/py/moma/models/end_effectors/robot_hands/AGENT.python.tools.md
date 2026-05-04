# Agent Python Tools

- repo: google-deepmind/dmrobotics
- repo_uri: https://github.com/google-deepmind/dm_robotics

## File: google-deepmind_dmrobotics/py/moma/models/end_effectors/robot_hands/robot_hand.py

Prompts

```
['build a subclass of RobotHand that implements _build, joints, actuators, mjcf_model, name, and tool_center_point', 'review the RobotHand abstract base class and its required abstract methods and properties', 'implement the joints property in a RobotHand subclass to return a sequence of MjcfElement joint elements', 'implement the actuators property in a RobotHand subclass to return a sequence of MjcfElement actuator elements', 'use the AnyRobotHand type alias to accept either MOMA or dm_control RobotHand instances', 'create a Robotiq2F85Mjcf gripper instance with custom gainprm and biasprm actuator parameters', 'build a Robotiq2F85 gripper with a custom TCP orientation quaternion for robot compatibility', 'initialize a simulation episode by applying gravity compensation to all gripper body elements', 'convert a raw joint position value to the gripper sensor output range of 0 to 255', 'check the grasp sensor to detect inward grasp, outward grasp, or no grasp state', 'test the Robotiq2F85 gripper physics step by creating an MJCF model and stepping simulation', 'test the Robotiq2F85 gripper actuator control range is between -255.0 and 255.0', 'test the Robotiq2F85 gripper action spec minimum and maximum values in a composer environment', 'test the Robotiq2F85 gripper fully opens to position 0 and fully closes to position 255', 'test the Robotiq2F85 gripper actuator state clipping when actuation exceeds control range bounds']
```

Usage

```
{'build_robot_hand_subclass': 'build a subclass of RobotHand that implements _build, joints, actuators, mjcf_model, name, and tool_center_point', 'review_robot_hand_abstract_class': 'review the RobotHand abstract base class and its required abstract methods and properties', 'implement_robot_hand_joints_property': 'implement the joints property in a RobotHand subclass to return a sequence of MjcfElement joint elements', 'implement_robot_hand_actuators_property': 'implement the actuators property in a RobotHand subclass to return a sequence of MjcfElement actuator elements', 'use_anyrobot_hand_type_alias': 'use the AnyRobotHand type alias to accept either MOMA or dm_control RobotHand instances'}
```

## File: google-deepmind_dmrobotics/py/moma/models/end_effectors/robot_hands/robotiq_2f85.py

Prompts

```
['build a subclass of RobotHand that implements _build, joints, actuators, mjcf_model, name, and tool_center_point', 'review the RobotHand abstract base class and its required abstract methods and properties', 'implement the joints property in a RobotHand subclass to return a sequence of MjcfElement joint elements', 'implement the actuators property in a RobotHand subclass to return a sequence of MjcfElement actuator elements', 'use the AnyRobotHand type alias to accept either MOMA or dm_control RobotHand instances', 'create a Robotiq2F85Mjcf gripper instance with custom gainprm and biasprm actuator parameters', 'build a Robotiq2F85 gripper with a custom TCP orientation quaternion for robot compatibility', 'initialize a simulation episode by applying gravity compensation to all gripper body elements', 'convert a raw joint position value to the gripper sensor output range of 0 to 255', 'check the grasp sensor to detect inward grasp, outward grasp, or no grasp state', 'test the Robotiq2F85 gripper physics step by creating an MJCF model and stepping simulation', 'test the Robotiq2F85 gripper actuator control range is between -255.0 and 255.0', 'test the Robotiq2F85 gripper action spec minimum and maximum values in a composer environment', 'test the Robotiq2F85 gripper fully opens to position 0 and fully closes to position 255', 'test the Robotiq2F85 gripper actuator state clipping when actuation exceeds control range bounds']
```

Usage

```
{'create_robotiq_2f85_gripper': 'create a Robotiq2F85Mjcf gripper instance with custom gainprm and biasprm actuator parameters', 'build_gripper_with_tcp_orientation': 'build a Robotiq2F85 gripper with a custom TCP orientation quaternion for robot compatibility', 'initialize_episode_gravity_compensation': 'initialize a simulation episode by applying gravity compensation to all gripper body elements', 'convert_joint_position_to_sensor': 'convert a raw joint position value to the gripper sensor output range of 0 to 255', 'check_grasp_sensor_state': 'check the grasp sensor to detect inward grasp, outward grasp, or no grasp state'}
```

## File: google-deepmind_dmrobotics/py/moma/models/end_effectors/robot_hands/robotiq_2f85_test.py

Prompts

```
['build a subclass of RobotHand that implements _build, joints, actuators, mjcf_model, name, and tool_center_point', 'review the RobotHand abstract base class and its required abstract methods and properties', 'implement the joints property in a RobotHand subclass to return a sequence of MjcfElement joint elements', 'implement the actuators property in a RobotHand subclass to return a sequence of MjcfElement actuator elements', 'use the AnyRobotHand type alias to accept either MOMA or dm_control RobotHand instances', 'create a Robotiq2F85Mjcf gripper instance with custom gainprm and biasprm actuator parameters', 'build a Robotiq2F85 gripper with a custom TCP orientation quaternion for robot compatibility', 'initialize a simulation episode by applying gravity compensation to all gripper body elements', 'convert a raw joint position value to the gripper sensor output range of 0 to 255', 'check the grasp sensor to detect inward grasp, outward grasp, or no grasp state', 'test the Robotiq2F85 gripper physics step by creating an MJCF model and stepping simulation', 'test the Robotiq2F85 gripper actuator control range is between -255.0 and 255.0', 'test the Robotiq2F85 gripper action spec minimum and maximum values in a composer environment', 'test the Robotiq2F85 gripper fully opens to position 0 and fully closes to position 255', 'test the Robotiq2F85 gripper actuator state clipping when actuation exceeds control range bounds']
```

Usage

```
{'test_robotiq_2f85_physics_step': 'test the Robotiq2F85 gripper physics step by creating an MJCF model and stepping simulation', 'test_robotiq_2f85_ctrlrange': 'test the Robotiq2F85 gripper actuator control range is between -255.0 and 255.0', 'test_robotiq_2f85_action_spec': 'test the Robotiq2F85 gripper action spec minimum and maximum values in a composer environment', 'test_robotiq_2f85_grasp_open_close': 'test the Robotiq2F85 gripper fully opens to position 0 and fully closes to position 255', 'test_robotiq_2f85_actuation_clipping': 'test the Robotiq2F85 gripper actuator state clipping when actuation exceeds control range bounds'}
```

