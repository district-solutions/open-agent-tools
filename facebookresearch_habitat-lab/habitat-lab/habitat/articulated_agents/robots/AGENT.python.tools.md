# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-lab/habitat/articulated_agents/robots/fetch_robot.py

Prompts

```
['create a FetchRobot instance with agent config and simulator for mobile manipulation tasks', 'configure FetchRobot arm joints, gripper joints, wheel joints, and camera parameters via MobileManipulatorParams', 'reset the FetchRobot to initial state with fixed head and back joint positions', 'update FetchRobot head rotation, head tilt, and back joint positions during simulation steps', 'create a FetchRobotNoWheels variant without wheel control and adjusted joint indices for fixed base', 'create a SpotRobot instance with agent config, simulator, and optional fixed base flag', 'configure SpotRobot camera parameters including arm RGB, depth, panoptic, and head stereo cameras', 'get the SpotRobot base transformation matrix with applied rotation offset from simulation object', 'customize SpotRobot arm, gripper, and leg joint initial parameters and motor gains', 'review the SpotRobot class that extends MobileManipulator with Boston Dynamics Spot robot configuration', 'create a StretchRobot instance with agent config, simulator, and optional joint limits', 'create a StretchRobotNoWheels instance from a URDF path and simulator', 'review the StretchRobot _get_fetch_params method that returns MobileManipulatorParams with arm, gripper, and wheel joint configuration', 'review the StretchRobot base_transformation property that returns the simulation object transformation with added rotation', 'refactor the StretchRobot _get_fetch_params to modify arm joints, gripper joints, camera params, or motor gains']
```

Usage

```
{'create_FetchRobot': 'create a FetchRobot instance with agent config and simulator for mobile manipulation tasks', 'configure_FetchRobot_params': 'configure FetchRobot arm joints, gripper joints, wheel joints, and camera parameters via MobileManipulatorParams', 'reset_FetchRobot': 'reset the FetchRobot to initial state with fixed head and back joint positions', 'update_FetchRobot_joints': 'update FetchRobot head rotation, head tilt, and back joint positions during simulation steps', 'create_FetchRobotNoWheels': 'create a FetchRobotNoWheels variant without wheel control and adjusted joint indices for fixed base'}
```

## File: facebookresearch_habitat-lab/habitat-lab/habitat/articulated_agents/robots/spot_robot.py

Prompts

```
['create a FetchRobot instance with agent config and simulator for mobile manipulation tasks', 'configure FetchRobot arm joints, gripper joints, wheel joints, and camera parameters via MobileManipulatorParams', 'reset the FetchRobot to initial state with fixed head and back joint positions', 'update FetchRobot head rotation, head tilt, and back joint positions during simulation steps', 'create a FetchRobotNoWheels variant without wheel control and adjusted joint indices for fixed base', 'create a SpotRobot instance with agent config, simulator, and optional fixed base flag', 'configure SpotRobot camera parameters including arm RGB, depth, panoptic, and head stereo cameras', 'get the SpotRobot base transformation matrix with applied rotation offset from simulation object', 'customize SpotRobot arm, gripper, and leg joint initial parameters and motor gains', 'review the SpotRobot class that extends MobileManipulator with Boston Dynamics Spot robot configuration', 'create a StretchRobot instance with agent config, simulator, and optional joint limits', 'create a StretchRobotNoWheels instance from a URDF path and simulator', 'review the StretchRobot _get_fetch_params method that returns MobileManipulatorParams with arm, gripper, and wheel joint configuration', 'review the StretchRobot base_transformation property that returns the simulation object transformation with added rotation', 'refactor the StretchRobot _get_fetch_params to modify arm joints, gripper joints, camera params, or motor gains']
```

Usage

```
{'create_SpotRobot_instance': 'create a SpotRobot instance with agent config, simulator, and optional fixed base flag', 'configure_SpotRobot_camera_params': 'configure SpotRobot camera parameters including arm RGB, depth, panoptic, and head stereo cameras', 'get_SpotRobot_base_transformation': 'get the SpotRobot base transformation matrix with applied rotation offset from simulation object', 'customize_SpotRobot_joint_params': 'customize SpotRobot arm, gripper, and leg joint initial parameters and motor gains', 'review_SpotRobot_class': 'review the SpotRobot class that extends MobileManipulator with Boston Dynamics Spot robot configuration'}
```

## File: facebookresearch_habitat-lab/habitat-lab/habitat/articulated_agents/robots/stretch_robot.py

Prompts

```
['create a FetchRobot instance with agent config and simulator for mobile manipulation tasks', 'configure FetchRobot arm joints, gripper joints, wheel joints, and camera parameters via MobileManipulatorParams', 'reset the FetchRobot to initial state with fixed head and back joint positions', 'update FetchRobot head rotation, head tilt, and back joint positions during simulation steps', 'create a FetchRobotNoWheels variant without wheel control and adjusted joint indices for fixed base', 'create a SpotRobot instance with agent config, simulator, and optional fixed base flag', 'configure SpotRobot camera parameters including arm RGB, depth, panoptic, and head stereo cameras', 'get the SpotRobot base transformation matrix with applied rotation offset from simulation object', 'customize SpotRobot arm, gripper, and leg joint initial parameters and motor gains', 'review the SpotRobot class that extends MobileManipulator with Boston Dynamics Spot robot configuration', 'create a StretchRobot instance with agent config, simulator, and optional joint limits', 'create a StretchRobotNoWheels instance from a URDF path and simulator', 'review the StretchRobot _get_fetch_params method that returns MobileManipulatorParams with arm, gripper, and wheel joint configuration', 'review the StretchRobot base_transformation property that returns the simulation object transformation with added rotation', 'refactor the StretchRobot _get_fetch_params to modify arm joints, gripper joints, camera params, or motor gains']
```

Usage

```
{'create_StretchRobot': 'create a StretchRobot instance with agent config, simulator, and optional joint limits', 'create_StretchRobotNoWheels': 'create a StretchRobotNoWheels instance from a URDF path and simulator', 'review_StretchRobot__get_fetch_params': 'review the StretchRobot _get_fetch_params method that returns MobileManipulatorParams with arm, gripper, and wheel joint configuration', 'review_StretchRobot_base_transformation': 'review the StretchRobot base_transformation property that returns the simulation object transformation with added rotation', 'refactor_StretchRobot__get_fetch_params': 'refactor the StretchRobot _get_fetch_params to modify arm joints, gripper joints, camera params, or motor gains'}
```

