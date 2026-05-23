# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/articulated_agents/robots/fetch_robot.py

Prompts

```
['create a FetchRobot instance with agent config and simulator for mobile manipulation tasks', 'create a FetchRobotNoWheels instance without wheel joints for fixed-base manipulation tasks', 'review the FetchRobot update method that fixes head and back joint positions', 'review the FetchRobot base_transformation property that returns the robot base pose with rotation', 'refactor the FetchRobot _get_fetch_params method to customize arm, gripper, and camera parameters', 'create a SpotRobot instance with agent_cfg and sim objects for Habitat simulation', 'review the SpotRobot base_transformation property that returns the robot transformation with added rotation', 'summarize the SpotRobot _get_spot_params method that returns MobileManipulatorParams with joint and camera configs', 'refactor the SpotRobot camera configuration to add or modify ArticulatedAgentCameraParams entries', 'test the SpotRobot constructor with agent_cfg, sim, limit_robo_joints, and fixed_base parameters', 'create a StretchRobot instance with agent config and simulator for mobile manipulation tasks', 'configure MobileManipulatorParams with arm joints, gripper joints, wheel joints, and camera settings for the Stretch robot', 'get the base transformation matrix of the StretchRobot with an added rotation around the X axis', 'create a StretchRobotNoWheels instance that inherits StretchRobot configuration without wheel mobility', 'review the StretchRobot camera configuration including head and third-person ArticulatedAgentCameraParams']
```

Usage

```
{'create_FetchRobot': 'create a FetchRobot instance with agent config and simulator for mobile manipulation tasks', 'create_FetchRobotNoWheels': 'create a FetchRobotNoWheels instance without wheel joints for fixed-base manipulation tasks', 'review_FetchRobot_update': 'review the FetchRobot update method that fixes head and back joint positions', 'review_FetchRobot_base_transformation': 'review the FetchRobot base_transformation property that returns the robot base pose with rotation', 'refactor_FetchRobot_params': 'refactor the FetchRobot _get_fetch_params method to customize arm, gripper, and camera parameters'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/articulated_agents/robots/spot_robot.py

Prompts

```
['create a FetchRobot instance with agent config and simulator for mobile manipulation tasks', 'create a FetchRobotNoWheels instance without wheel joints for fixed-base manipulation tasks', 'review the FetchRobot update method that fixes head and back joint positions', 'review the FetchRobot base_transformation property that returns the robot base pose with rotation', 'refactor the FetchRobot _get_fetch_params method to customize arm, gripper, and camera parameters', 'create a SpotRobot instance with agent_cfg and sim objects for Habitat simulation', 'review the SpotRobot base_transformation property that returns the robot transformation with added rotation', 'summarize the SpotRobot _get_spot_params method that returns MobileManipulatorParams with joint and camera configs', 'refactor the SpotRobot camera configuration to add or modify ArticulatedAgentCameraParams entries', 'test the SpotRobot constructor with agent_cfg, sim, limit_robo_joints, and fixed_base parameters', 'create a StretchRobot instance with agent config and simulator for mobile manipulation tasks', 'configure MobileManipulatorParams with arm joints, gripper joints, wheel joints, and camera settings for the Stretch robot', 'get the base transformation matrix of the StretchRobot with an added rotation around the X axis', 'create a StretchRobotNoWheels instance that inherits StretchRobot configuration without wheel mobility', 'review the StretchRobot camera configuration including head and third-person ArticulatedAgentCameraParams']
```

Usage

```
{'instantiate_SpotRobot': 'create a SpotRobot instance with agent_cfg and sim objects for Habitat simulation', 'review_SpotRobot_base_transformation': 'review the SpotRobot base_transformation property that returns the robot transformation with added rotation', 'summarize_SpotRobot_get_spot_params': 'summarize the SpotRobot _get_spot_params method that returns MobileManipulatorParams with joint and camera configs', 'refactor_SpotRobot_camera_config': 'refactor the SpotRobot camera configuration to add or modify ArticulatedAgentCameraParams entries', 'test_SpotRobot_init': 'test the SpotRobot constructor with agent_cfg, sim, limit_robo_joints, and fixed_base parameters'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/articulated_agents/robots/stretch_robot.py

Prompts

```
['create a FetchRobot instance with agent config and simulator for mobile manipulation tasks', 'create a FetchRobotNoWheels instance without wheel joints for fixed-base manipulation tasks', 'review the FetchRobot update method that fixes head and back joint positions', 'review the FetchRobot base_transformation property that returns the robot base pose with rotation', 'refactor the FetchRobot _get_fetch_params method to customize arm, gripper, and camera parameters', 'create a SpotRobot instance with agent_cfg and sim objects for Habitat simulation', 'review the SpotRobot base_transformation property that returns the robot transformation with added rotation', 'summarize the SpotRobot _get_spot_params method that returns MobileManipulatorParams with joint and camera configs', 'refactor the SpotRobot camera configuration to add or modify ArticulatedAgentCameraParams entries', 'test the SpotRobot constructor with agent_cfg, sim, limit_robo_joints, and fixed_base parameters', 'create a StretchRobot instance with agent config and simulator for mobile manipulation tasks', 'configure MobileManipulatorParams with arm joints, gripper joints, wheel joints, and camera settings for the Stretch robot', 'get the base transformation matrix of the StretchRobot with an added rotation around the X axis', 'create a StretchRobotNoWheels instance that inherits StretchRobot configuration without wheel mobility', 'review the StretchRobot camera configuration including head and third-person ArticulatedAgentCameraParams']
```

Usage

```
{'create_StretchRobot': 'create a StretchRobot instance with agent config and simulator for mobile manipulation tasks', 'configure_get_fetch_params': 'configure MobileManipulatorParams with arm joints, gripper joints, wheel joints, and camera settings for the Stretch robot', 'get_base_transformation': 'get the base transformation matrix of the StretchRobot with an added rotation around the X axis', 'create_StretchRobotNoWheels': 'create a StretchRobotNoWheels instance that inherits StretchRobot configuration without wheel mobility', 'review_StretchRobot_cameras': 'review the StretchRobot camera configuration including head and third-person ArticulatedAgentCameraParams'}
```

