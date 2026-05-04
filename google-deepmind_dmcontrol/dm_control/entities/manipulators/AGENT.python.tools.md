# Agent Python Tools

- repo: google-deepmind/dmcontrol
- repo_uri: https://github.com/google-deepmind/dm_control

## File: google-deepmind_dmcontrol/dm_control/entities/manipulators/base.py

Prompts

```
['use inverse kinematics to move a robot arm site to a target Cartesian position and orientation', 'randomize the joint positions of a robot arm within valid sampling bounds from the MJCF model', 'get the lower and upper position bounds for all arm joints from the physics model', 'set the finger grasp positions of a robot hand using close factors from 0 open to 1 closed', 'build observable features for robot arm joint positions and velocities using MJCFFeature']
```

Usage

```
{'set_site_to_xpos': 'use inverse kinematics to move a robot arm site to a target Cartesian position and orientation', 'randomize_arm_joints': 'randomize the joint positions of a robot arm within valid sampling bounds from the MJCF model', 'get_joint_pos_sampling_bounds': 'get the lower and upper position bounds for all arm joints from the physics model', 'set_grasp': 'set the finger grasp positions of a robot hand using close factors from 0 open to 1 closed', 'build_joints_observables': 'build observable features for robot arm joint positions and velocities using MJCFFeature'}
```

