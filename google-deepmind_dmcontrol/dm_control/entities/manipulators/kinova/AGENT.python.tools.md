# Agent Python Tools

- repo: google-deepmind/dmcontrol
- repo_uri: https://github.com/google-deepmind/dm_control

## File: google-deepmind_dmcontrol/dm_control/entities/manipulators/kinova/jaco_arm.py

Prompts

```
['build a JacoArm composer entity to initialize a 6-DOF Kinova Jaco robot arm model', 'create a velocity actuator for a joint with torque and velocity limits based on joint size', 'add a torque sensor to a joint parent body and return the MJCF sensor element', 'get the joints_pos observable that returns sine and cosine pairs of joint angles', 'get the joints_torque observable that projects 3-axis torque sensor data onto joint axes', 'build a JacoHand composer entity with a custom name and pinch site as the tool center point', 'set the Jaco hand finger positions using close factors from 0 open to 1 closed', 'add a velocity actuator to an MJCF joint with configured gain force and control ranges', 'get the pinch site position and rotation matrix observables from a JacoHandObservables instance', 'review the JacoHand class properties including joints actuators hand geoms finger geoms grip site and pinch site', 'test the JacoArm class by compiling the MJCF model and stepping the physics simulation', 'test attaching a JacoHand to a JacoArm and verify the combined physics model compiles', 'test JacoArm velocity actuation by applying control inputs and measuring joint velocities', 'test JacoArm backdriving torque by applying incremental torque and measuring joint acceleration thresholds', 'test JacoHand grip force by closing fingers on a sphere and measuring touch sensor data']
```

Usage

```
{'build_jaco_arm_entity': 'build a JacoArm composer entity to initialize a 6-DOF Kinova Jaco robot arm model', 'create_velocity_actuator': 'create a velocity actuator for a joint with torque and velocity limits based on joint size', 'add_torque_sensor': 'add a torque sensor to a joint parent body and return the MJCF sensor element', 'get_joints_pos_observable': 'get the joints_pos observable that returns sine and cosine pairs of joint angles', 'get_joints_torque_observable': 'get the joints_torque observable that projects 3-axis torque sensor data onto joint axes'}
```

## File: google-deepmind_dmcontrol/dm_control/entities/manipulators/kinova/jaco_hand.py

Prompts

```
['build a JacoArm composer entity to initialize a 6-DOF Kinova Jaco robot arm model', 'create a velocity actuator for a joint with torque and velocity limits based on joint size', 'add a torque sensor to a joint parent body and return the MJCF sensor element', 'get the joints_pos observable that returns sine and cosine pairs of joint angles', 'get the joints_torque observable that projects 3-axis torque sensor data onto joint axes', 'build a JacoHand composer entity with a custom name and pinch site as the tool center point', 'set the Jaco hand finger positions using close factors from 0 open to 1 closed', 'add a velocity actuator to an MJCF joint with configured gain force and control ranges', 'get the pinch site position and rotation matrix observables from a JacoHandObservables instance', 'review the JacoHand class properties including joints actuators hand geoms finger geoms grip site and pinch site', 'test the JacoArm class by compiling the MJCF model and stepping the physics simulation', 'test attaching a JacoHand to a JacoArm and verify the combined physics model compiles', 'test JacoArm velocity actuation by applying control inputs and measuring joint velocities', 'test JacoArm backdriving torque by applying incremental torque and measuring joint acceleration thresholds', 'test JacoHand grip force by closing fingers on a sphere and measuring touch sensor data']
```

Usage

```
{'build_jaco_hand_entity': 'build a JacoHand composer entity with a custom name and pinch site as the tool center point', 'set_grasp_finger_positions': 'set the Jaco hand finger positions using close factors from 0 open to 1 closed', 'add_velocity_actuator_to_joint': 'add a velocity actuator to an MJCF joint with configured gain force and control ranges', 'get_jaco_hand_observables': 'get the pinch site position and rotation matrix observables from a JacoHandObservables instance', 'review_jaco_hand_class': 'review the JacoHand class properties including joints actuators hand geoms finger geoms grip site and pinch site'}
```

## File: google-deepmind_dmcontrol/dm_control/entities/manipulators/kinova/kinova_test.py

Prompts

```
['build a JacoArm composer entity to initialize a 6-DOF Kinova Jaco robot arm model', 'create a velocity actuator for a joint with torque and velocity limits based on joint size', 'add a torque sensor to a joint parent body and return the MJCF sensor element', 'get the joints_pos observable that returns sine and cosine pairs of joint angles', 'get the joints_torque observable that projects 3-axis torque sensor data onto joint axes', 'build a JacoHand composer entity with a custom name and pinch site as the tool center point', 'set the Jaco hand finger positions using close factors from 0 open to 1 closed', 'add a velocity actuator to an MJCF joint with configured gain force and control ranges', 'get the pinch site position and rotation matrix observables from a JacoHandObservables instance', 'review the JacoHand class properties including joints actuators hand geoms finger geoms grip site and pinch site', 'test the JacoArm class by compiling the MJCF model and stepping the physics simulation', 'test attaching a JacoHand to a JacoArm and verify the combined physics model compiles', 'test JacoArm velocity actuation by applying control inputs and measuring joint velocities', 'test JacoArm backdriving torque by applying incremental torque and measuring joint acceleration thresholds', 'test JacoHand grip force by closing fingers on a sphere and measuring touch sensor data']
```

Usage

```
{'test_jaco_arm_compile_and_step': 'test the JacoArm class by compiling the MJCF model and stepping the physics simulation', 'test_jaco_arm_attach_hand': 'test attaching a JacoHand to a JacoArm and verify the combined physics model compiles', 'test_jaco_arm_velocity_actuation': 'test JacoArm velocity actuation by applying control inputs and measuring joint velocities', 'test_jaco_arm_backdriving_torque': 'test JacoArm backdriving torque by applying incremental torque and measuring joint acceleration thresholds', 'test_jaco_hand_grip_force': 'test JacoHand grip force by closing fingers on a sphere and measuring touch sensor data'}
```

