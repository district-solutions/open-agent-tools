# Agent Python Tools

- repo: google-deepmind/dmrobotics
- repo_uri: https://github.com/google-deepmind/dm_robotics

## File: google-deepmind_dmrobotics/cpp/controllers_py/cartesian_6d_to_joint_velocity_mapper_test.py

Prompts

```
['create a Parameters object to configure joint IDs, object type, and collision avoidance settings for the mapper', 'build a Mapper instance from Parameters to compute joint velocities for a MuJoCo humanoid model', 'test compute_joint_velocities to realize a target 6D Cartesian velocity on the right hand geom', 'test nullspace control by computing joint velocities that achieve a target while biasing toward a nullspace vector', 'test collision avoidance by running 5000 integration steps and verifying no left arm to floor contact occurs', 'create a Parameters object to configure joint velocity filtering with model, joint IDs, and timestep', 'build a JointVelocityFilter instance from Parameters to filter robot joint velocities with constraints', 'test the filter_joint_velocities method to compute safe velocities that avoid collisions and respect limits', 'run the helper function to set joint velocities in a MuJoCo physics data object', 'review the Parameters class attributes including collision avoidance, velocity limits, and solver settings']
```

Usage

```
{'create_parameters': 'create a Parameters object to configure joint IDs, object type, and collision avoidance settings for the mapper', 'build_mapper': 'build a Mapper instance from Parameters to compute joint velocities for a MuJoCo humanoid model', 'test_compute_joint_velocities': 'test compute_joint_velocities to realize a target 6D Cartesian velocity on the right hand geom', 'test_nullspace_control': 'test nullspace control by computing joint velocities that achieve a target while biasing toward a nullspace vector', 'test_collision_avoidance': 'test collision avoidance by running 5000 integration steps and verifying no left arm to floor contact occurs'}
```

## File: google-deepmind_dmrobotics/cpp/controllers_py/joint_velocity_filter_test.py

Prompts

```
['create a Parameters object to configure joint IDs, object type, and collision avoidance settings for the mapper', 'build a Mapper instance from Parameters to compute joint velocities for a MuJoCo humanoid model', 'test compute_joint_velocities to realize a target 6D Cartesian velocity on the right hand geom', 'test nullspace control by computing joint velocities that achieve a target while biasing toward a nullspace vector', 'test collision avoidance by running 5000 integration steps and verifying no left arm to floor contact occurs', 'create a Parameters object to configure joint velocity filtering with model, joint IDs, and timestep', 'build a JointVelocityFilter instance from Parameters to filter robot joint velocities with constraints', 'test the filter_joint_velocities method to compute safe velocities that avoid collisions and respect limits', 'run the helper function to set joint velocities in a MuJoCo physics data object', 'review the Parameters class attributes including collision avoidance, velocity limits, and solver settings']
```

Usage

```
{'create_joint_velocity_filter_parameters': 'create a Parameters object to configure joint velocity filtering with model, joint IDs, and timestep', 'build_joint_velocity_filter': 'build a JointVelocityFilter instance from Parameters to filter robot joint velocities with constraints', 'test_filter_joint_velocities': 'test the filter_joint_velocities method to compute safe velocities that avoid collisions and respect limits', 'run_set_joint_velocities': 'run the helper function to set joint velocities in a MuJoCo physics data object', 'review_parameters_attributes': 'review the Parameters class attributes including collision avoidance, velocity limits, and solver settings'}
```

