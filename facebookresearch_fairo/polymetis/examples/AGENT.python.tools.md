# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/polymetis/examples/3_custom_controller.py

Prompts

```
['run a custom sine trajectory policy on joint 6 of a robot using RobotInterface', 'create a MySinePolicy instance with PD gains, magnitude, and period for joint space control', 'review the MySinePolicy forward method that computes sine trajectory and executes PD control', 'test sending a torch policy to a robot via RobotInterface.send_torch_policy', 'refactor the MySinePolicy class to target a different joint or trajectory pattern', 'create a custom PD control policy module that inherits from toco.PolicyModule for robot joint control', 'run a RobotInterface connection to localhost and send a torch policy for robot control', 'update the current robot policy parameters at 50hz to execute a sine trajectory on a joint', 'review the MyPDPolicy forward method that computes joint torques using JointSpacePD feedback control', 'terminate the current robot policy and retrieve the state log from the robot interface']
```

Usage

```
{'run_custom_sine_policy': 'run a custom sine trajectory policy on joint 6 of a robot using RobotInterface', 'create_MySinePolicy': 'create a MySinePolicy instance with PD gains, magnitude, and period for joint space control', 'review_MySinePolicy_forward': 'review the MySinePolicy forward method that computes sine trajectory and executes PD control', 'test_RobotInterface_send_torch_policy': 'test sending a torch policy to a robot via RobotInterface.send_torch_policy', 'refactor_MySinePolicy': 'refactor the MySinePolicy class to target a different joint or trajectory pattern'}
```

## File: facebookresearch_fairo/polymetis/examples/4_custom_updatable_controller.py

Prompts

```
['run a custom sine trajectory policy on joint 6 of a robot using RobotInterface', 'create a MySinePolicy instance with PD gains, magnitude, and period for joint space control', 'review the MySinePolicy forward method that computes sine trajectory and executes PD control', 'test sending a torch policy to a robot via RobotInterface.send_torch_policy', 'refactor the MySinePolicy class to target a different joint or trajectory pattern', 'create a custom PD control policy module that inherits from toco.PolicyModule for robot joint control', 'run a RobotInterface connection to localhost and send a torch policy for robot control', 'update the current robot policy parameters at 50hz to execute a sine trajectory on a joint', 'review the MyPDPolicy forward method that computes joint torques using JointSpacePD feedback control', 'terminate the current robot policy and retrieve the state log from the robot interface']
```

Usage

```
{'create_custom_pd_policy': 'create a custom PD control policy module that inherits from toco.PolicyModule for robot joint control', 'run_robot_interface': 'run a RobotInterface connection to localhost and send a torch policy for robot control', 'update_policy_parameters': 'update the current robot policy parameters at 50hz to execute a sine trajectory on a joint', 'review_MyPDPolicy_forward': 'review the MyPDPolicy forward method that computes joint torques using JointSpacePD feedback control', 'terminate_robot_policy': 'terminate the current robot policy and retrieve the state log from the robot interface'}
```

