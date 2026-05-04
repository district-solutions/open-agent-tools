# Agent Python Tools

- repo: google-deepmind/dmrobotics
- repo_uri: https://github.com/google-deepmind/dm_robotics

## File: google-deepmind_dmrobotics/py/moma/models/end_effectors/wrist_sensors/robotiq_fts300.py

Prompts

```
['build a RobotiqFTS300 force torque sensor entity from an MJCF XML model file', 'initialize a simulation episode and apply gravity compensation to all sensor bodies', 'get the force and torque noise standard deviations and max absolute range parameters', 'access the force sensor and torque sensor MJCF elements from the RobotiqFTS300 entity', 'get the list of collision geometry full identifiers for the sensor base mount', 'test that RobotiqFTS300 can be instantiated and physics step executes without error', 'test that the F/T sensor reads zero force on Z axis when gravity is disabled', 'run the RobotiqFTS300Test test suite using absltest to validate sensor instantiation and readings', 'review the RobotiqFTS300Test class and its parameterized test methods for sensor validation', 'summarize the test_load_sensor and test_zero_gravity_readings methods in RobotiqFTS300Test']
```

Usage

```
{'build_robotiq_fts300_sensor': 'build a RobotiqFTS300 force torque sensor entity from an MJCF XML model file', 'initialize_episode_gravity_compensation': 'initialize a simulation episode and apply gravity compensation to all sensor bodies', 'get_sensor_params': 'get the force and torque noise standard deviations and max absolute range parameters', 'access_force_torque_sensors': 'access the force sensor and torque sensor MJCF elements from the RobotiqFTS300 entity', 'get_collision_geom_group': 'get the list of collision geometry full identifiers for the sensor base mount'}
```

## File: google-deepmind_dmrobotics/py/moma/models/end_effectors/wrist_sensors/robotiq_fts300_test.py

Prompts

```
['build a RobotiqFTS300 force torque sensor entity from an MJCF XML model file', 'initialize a simulation episode and apply gravity compensation to all sensor bodies', 'get the force and torque noise standard deviations and max absolute range parameters', 'access the force sensor and torque sensor MJCF elements from the RobotiqFTS300 entity', 'get the list of collision geometry full identifiers for the sensor base mount', 'test that RobotiqFTS300 can be instantiated and physics step executes without error', 'test that the F/T sensor reads zero force on Z axis when gravity is disabled', 'run the RobotiqFTS300Test test suite using absltest to validate sensor instantiation and readings', 'review the RobotiqFTS300Test class and its parameterized test methods for sensor validation', 'summarize the test_load_sensor and test_zero_gravity_readings methods in RobotiqFTS300Test']
```

Usage

```
{'test_RobotiqFTS300_sensor_load': 'test that RobotiqFTS300 can be instantiated and physics step executes without error', 'test_RobotiqFTS300_zero_gravity': 'test that the F/T sensor reads zero force on Z axis when gravity is disabled', 'run_RobotiqFTS300Test': 'run the RobotiqFTS300Test test suite using absltest to validate sensor instantiation and readings', 'review_RobotiqFTS300Test_class': 'review the RobotiqFTS300Test class and its parameterized test methods for sensor validation', 'summarize_RobotiqFTS300_test_methods': 'summarize the test_load_sensor and test_zero_gravity_readings methods in RobotiqFTS300Test'}
```

