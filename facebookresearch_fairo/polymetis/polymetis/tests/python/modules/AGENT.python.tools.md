# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/polymetis/polymetis/tests/python/modules/test_feedback.py

Prompts

```
['test the LinearFeedback controller by computing output from current and desired state tensors', 'test the JointSpacePD controller with Kp and Kd gains on joint position and velocity tensors', 'test the CartesianSpacePD controller with 6x6 Kp and Kd gains on end-effector pose and twist', 'review the LinearFeedback class and its usage with gain matrix K for state feedback control', 'review the JointSpacePD class and its proportional-derivative control in joint space', 'test the InverseDynamics feedforward module with a robot model and desired joint accelerations', 'test the Coriolis feedforward module with a robot model and current joint states', 'review the test_inverse_dynamics function to understand parametrized gravity ignore test cases', 'review the test_coriolis function to understand Coriolis force feedforward computation tests', 'summarize the feedforward module test suite covering InverseDynamics and Coriolis modules', 'generate joint space min jerk waypoints between a start and goal joint configuration over time', 'generate cartesian space min jerk waypoints between a start and goal pose with rotation and translation', 'generate position min jerk waypoints between a start and goal 3D position over time', 'generate joint waypoints from a start joint position to a goal end-effector pose using a robot model', 'test the polymetis planning module functions for joint, cartesian, and position min jerk trajectory generation']
```

Usage

```
{'test_linear_feedback': 'test the LinearFeedback controller by computing output from current and desired state tensors', 'test_joint_pd': 'test the JointSpacePD controller with Kp and Kd gains on joint position and velocity tensors', 'test_cartesian_pd': 'test the CartesianSpacePD controller with 6x6 Kp and Kd gains on end-effector pose and twist', 'review_linear_feedback': 'review the LinearFeedback class and its usage with gain matrix K for state feedback control', 'review_joint_space_pd': 'review the JointSpacePD class and its proportional-derivative control in joint space'}
```

## File: facebookresearch_fairo/polymetis/polymetis/tests/python/modules/test_feedforward.py

Prompts

```
['test the LinearFeedback controller by computing output from current and desired state tensors', 'test the JointSpacePD controller with Kp and Kd gains on joint position and velocity tensors', 'test the CartesianSpacePD controller with 6x6 Kp and Kd gains on end-effector pose and twist', 'review the LinearFeedback class and its usage with gain matrix K for state feedback control', 'review the JointSpacePD class and its proportional-derivative control in joint space', 'test the InverseDynamics feedforward module with a robot model and desired joint accelerations', 'test the Coriolis feedforward module with a robot model and current joint states', 'review the test_inverse_dynamics function to understand parametrized gravity ignore test cases', 'review the test_coriolis function to understand Coriolis force feedforward computation tests', 'summarize the feedforward module test suite covering InverseDynamics and Coriolis modules', 'generate joint space min jerk waypoints between a start and goal joint configuration over time', 'generate cartesian space min jerk waypoints between a start and goal pose with rotation and translation', 'generate position min jerk waypoints between a start and goal 3D position over time', 'generate joint waypoints from a start joint position to a goal end-effector pose using a robot model', 'test the polymetis planning module functions for joint, cartesian, and position min jerk trajectory generation']
```

Usage

```
{'test_inverse_dynamics': 'test the InverseDynamics feedforward module with a robot model and desired joint accelerations', 'test_coriolis': 'test the Coriolis feedforward module with a robot model and current joint states', 'review_test_inverse_dynamics': 'review the test_inverse_dynamics function to understand parametrized gravity ignore test cases', 'review_test_coriolis': 'review the test_coriolis function to understand Coriolis force feedforward computation tests', 'summarize_feedforward_tests': 'summarize the feedforward module test suite covering InverseDynamics and Coriolis modules'}
```

## File: facebookresearch_fairo/polymetis/polymetis/tests/python/modules/test_planning.py

Prompts

```
['test the LinearFeedback controller by computing output from current and desired state tensors', 'test the JointSpacePD controller with Kp and Kd gains on joint position and velocity tensors', 'test the CartesianSpacePD controller with 6x6 Kp and Kd gains on end-effector pose and twist', 'review the LinearFeedback class and its usage with gain matrix K for state feedback control', 'review the JointSpacePD class and its proportional-derivative control in joint space', 'test the InverseDynamics feedforward module with a robot model and desired joint accelerations', 'test the Coriolis feedforward module with a robot model and current joint states', 'review the test_inverse_dynamics function to understand parametrized gravity ignore test cases', 'review the test_coriolis function to understand Coriolis force feedforward computation tests', 'summarize the feedforward module test suite covering InverseDynamics and Coriolis modules', 'generate joint space min jerk waypoints between a start and goal joint configuration over time', 'generate cartesian space min jerk waypoints between a start and goal pose with rotation and translation', 'generate position min jerk waypoints between a start and goal 3D position over time', 'generate joint waypoints from a start joint position to a goal end-effector pose using a robot model', 'test the polymetis planning module functions for joint, cartesian, and position min jerk trajectory generation']
```

Usage

```
{'generate_joint_space_min_jerk': 'generate joint space min jerk waypoints between a start and goal joint configuration over time', 'generate_cartesian_space_min_jerk': 'generate cartesian space min jerk waypoints between a start and goal pose with rotation and translation', 'generate_position_min_jerk': 'generate position min jerk waypoints between a start and goal 3D position over time', 'generate_cartesian_target_joint_min_jerk': 'generate joint waypoints from a start joint position to a goal end-effector pose using a robot model', 'test_planning_module': 'test the polymetis planning module functions for joint, cartesian, and position min jerk trajectory generation'}
```

