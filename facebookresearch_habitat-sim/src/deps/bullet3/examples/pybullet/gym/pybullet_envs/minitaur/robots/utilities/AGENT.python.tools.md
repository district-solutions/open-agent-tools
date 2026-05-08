# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/robots/utilities/action_filter.py

Prompts

```
['create an ActionFilter instance with custom a and b coefficients for lowpass filtering robot joint actions', 'create an ActionFilterButter instance to apply a Butterworth lowpass or bandpass filter on robot policy outputs', 'create an ActionFilterExp instance to apply exponential smoothing with a configurable alpha to robot actions', 'call the filter method on an ActionFilter to return filtered action values for robot joints', 'call the reset method on an ActionFilter to clear the x and y history buffers to zero', 'compute joint angles for a quadruped robot link using inverse kinematics in pybullet', 'get the world frame position of a robot link using pybullet getLinkState', 'get the local base frame position of a robot link by inverting the base transform', 'compute the 3xN Jacobian matrix for a robot link given its current joint states', 'review the inverse kinematics utility functions for pybullet quadruped robot simulation', 'calculate joint angles from link positions using PyBullet inverse kinematics for a loaded URDF robot', 'get the world frame position of a robot link given its URDF id and link id', "get the local position of a robot link relative to the robot's base frame", 'compute the 3xN Jacobian matrix for a given link and joint configuration in PyBullet', 'rotate a world frame vector into the robot base coordinate system using PyBullet transforms', 'get the pybullet integer link id for a named URDF link using link_name_to_id', 'set the collision filter group and mask for all links of a loaded URDF robot', 'list all link names in a URDF by iterating joints via getJointInfo and LINK_NAME_INDEX', 'resolve the base link id by passing BASE_LINK constant to link_name_to_id', 'configure collision group and mask across all links including the base link of a robot']
```

Usage

```
{'create_action_filter': 'create an ActionFilter instance with custom a and b coefficients for lowpass filtering robot joint actions', 'create_butterworth_filter': 'create an ActionFilterButter instance to apply a Butterworth lowpass or bandpass filter on robot policy outputs', 'create_exponential_filter': 'create an ActionFilterExp instance to apply exponential smoothing with a configurable alpha to robot actions', 'filter_robot_actions': 'call the filter method on an ActionFilter to return filtered action values for robot joints', 'reset_filter_history': 'call the reset method on an ActionFilter to clear the x and y history buffers to zero'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/robots/utilities/kinematics.py

Prompts

```
['create an ActionFilter instance with custom a and b coefficients for lowpass filtering robot joint actions', 'create an ActionFilterButter instance to apply a Butterworth lowpass or bandpass filter on robot policy outputs', 'create an ActionFilterExp instance to apply exponential smoothing with a configurable alpha to robot actions', 'call the filter method on an ActionFilter to return filtered action values for robot joints', 'call the reset method on an ActionFilter to clear the x and y history buffers to zero', 'compute joint angles for a quadruped robot link using inverse kinematics in pybullet', 'get the world frame position of a robot link using pybullet getLinkState', 'get the local base frame position of a robot link by inverting the base transform', 'compute the 3xN Jacobian matrix for a robot link given its current joint states', 'review the inverse kinematics utility functions for pybullet quadruped robot simulation', 'calculate joint angles from link positions using PyBullet inverse kinematics for a loaded URDF robot', 'get the world frame position of a robot link given its URDF id and link id', "get the local position of a robot link relative to the robot's base frame", 'compute the 3xN Jacobian matrix for a given link and joint configuration in PyBullet', 'rotate a world frame vector into the robot base coordinate system using PyBullet transforms', 'get the pybullet integer link id for a named URDF link using link_name_to_id', 'set the collision filter group and mask for all links of a loaded URDF robot', 'list all link names in a URDF by iterating joints via getJointInfo and LINK_NAME_INDEX', 'resolve the base link id by passing BASE_LINK constant to link_name_to_id', 'configure collision group and mask across all links including the base link of a robot']
```

Usage

```
{'compute_joint_angles_from_link_position': 'compute joint angles for a quadruped robot link using inverse kinematics in pybullet', 'get_link_position_in_world_frame': 'get the world frame position of a robot link using pybullet getLinkState', 'get_link_position_in_base_frame': 'get the local base frame position of a robot link by inverting the base transform', 'compute_jacobian_for_link': 'compute the 3xN Jacobian matrix for a robot link given its current joint states', 'review_kinematics_utilities': 'review the inverse kinematics utility functions for pybullet quadruped robot simulation'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/robots/utilities/kinematics_utils.py

Prompts

```
['create an ActionFilter instance with custom a and b coefficients for lowpass filtering robot joint actions', 'create an ActionFilterButter instance to apply a Butterworth lowpass or bandpass filter on robot policy outputs', 'create an ActionFilterExp instance to apply exponential smoothing with a configurable alpha to robot actions', 'call the filter method on an ActionFilter to return filtered action values for robot joints', 'call the reset method on an ActionFilter to clear the x and y history buffers to zero', 'compute joint angles for a quadruped robot link using inverse kinematics in pybullet', 'get the world frame position of a robot link using pybullet getLinkState', 'get the local base frame position of a robot link by inverting the base transform', 'compute the 3xN Jacobian matrix for a robot link given its current joint states', 'review the inverse kinematics utility functions for pybullet quadruped robot simulation', 'calculate joint angles from link positions using PyBullet inverse kinematics for a loaded URDF robot', 'get the world frame position of a robot link given its URDF id and link id', "get the local position of a robot link relative to the robot's base frame", 'compute the 3xN Jacobian matrix for a given link and joint configuration in PyBullet', 'rotate a world frame vector into the robot base coordinate system using PyBullet transforms', 'get the pybullet integer link id for a named URDF link using link_name_to_id', 'set the collision filter group and mask for all links of a loaded URDF robot', 'list all link names in a URDF by iterating joints via getJointInfo and LINK_NAME_INDEX', 'resolve the base link id by passing BASE_LINK constant to link_name_to_id', 'configure collision group and mask across all links including the base link of a robot']
```

Usage

```
{'calculate_inverse_kinematics': 'calculate joint angles from link positions using PyBullet inverse kinematics for a loaded URDF robot', 'get_link_world_position': 'get the world frame position of a robot link given its URDF id and link id', 'get_link_base_position': "get the local position of a robot link relative to the robot's base frame", 'compute_jacobian_matrix': 'compute the 3xN Jacobian matrix for a given link and joint configuration in PyBullet', 'rotate_vector_to_base_frame': 'rotate a world frame vector into the robot base coordinate system using PyBullet transforms'}
```

## File: facebookresearch_habitat-sim/src/deps/bullet3/examples/pybullet/gym/pybullet_envs/minitaur/robots/utilities/urdf_utils.py

Prompts

```
['create an ActionFilter instance with custom a and b coefficients for lowpass filtering robot joint actions', 'create an ActionFilterButter instance to apply a Butterworth lowpass or bandpass filter on robot policy outputs', 'create an ActionFilterExp instance to apply exponential smoothing with a configurable alpha to robot actions', 'call the filter method on an ActionFilter to return filtered action values for robot joints', 'call the reset method on an ActionFilter to clear the x and y history buffers to zero', 'compute joint angles for a quadruped robot link using inverse kinematics in pybullet', 'get the world frame position of a robot link using pybullet getLinkState', 'get the local base frame position of a robot link by inverting the base transform', 'compute the 3xN Jacobian matrix for a robot link given its current joint states', 'review the inverse kinematics utility functions for pybullet quadruped robot simulation', 'calculate joint angles from link positions using PyBullet inverse kinematics for a loaded URDF robot', 'get the world frame position of a robot link given its URDF id and link id', "get the local position of a robot link relative to the robot's base frame", 'compute the 3xN Jacobian matrix for a given link and joint configuration in PyBullet', 'rotate a world frame vector into the robot base coordinate system using PyBullet transforms', 'get the pybullet integer link id for a named URDF link using link_name_to_id', 'set the collision filter group and mask for all links of a loaded URDF robot', 'list all link names in a URDF by iterating joints via getJointInfo and LINK_NAME_INDEX', 'resolve the base link id by passing BASE_LINK constant to link_name_to_id', 'configure collision group and mask across all links including the base link of a robot']
```

Usage

```
{'get_link_id_by_name': 'get the pybullet integer link id for a named URDF link using link_name_to_id', 'set_collision_filter': 'set the collision filter group and mask for all links of a loaded URDF robot', 'list_urdf_links': 'list all link names in a URDF by iterating joints via getJointInfo and LINK_NAME_INDEX', 'resolve_base_link': 'resolve the base link id by passing BASE_LINK constant to link_name_to_id', 'configure_robot_collisions': 'configure collision group and mask across all links including the base link of a robot'}
```

