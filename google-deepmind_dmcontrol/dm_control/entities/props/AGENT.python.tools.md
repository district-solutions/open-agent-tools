# Agent Python Tools

- repo: google-deepmind/dmcontrol
- repo_uri: https://github.com/google-deepmind/dm_control

## File: google-deepmind_dmcontrol/dm_control/entities/props/position_detector.py

Prompts

```
['build a PositionDetector with a center position and half-length size for an axis-aligned box region', 'register entities with a PositionDetector so their geoms are monitored for presence in the active region', 'resize a PositionDetector by updating its center position and half-length size at runtime', 'set the runtime position of a PositionDetector using physics and a new position array', 'check if a PositionDetector is activated by reading its activated property after simulation steps', 'test the PositionDetector class for 3D entity detection with configurable position and size parameters', 'test the PositionDetector class for 2D entity detection ignoring the z-axis coordinate', 'test the PositionDetector inverted mode to flip detection logic for registered entities', 'create a PositionDetector with a given position array, size array, and optional inverted flag', 'run the PositionDetector test suite to verify 3D and 2D detection with inverted modes', 'build a Primitive entity with a sphere geom type and specified radius for MuJoCo simulation', 'build a Primitive entity with a box geom type and x, y, z half lengths for simulation', "get the position sensor data from a Primitive entity's framepos sensor in the simulation", 'get the linear and angular velocity sensor data from a Primitive entity in the simulation', 'create PrimitiveObservables to expose position, orientation, linear velocity, and angular velocity as observable features', 'test creating Primitive props with sphere, capsule, cylinder, box, and ellipsoid geom types', 'test setting and observing the position of a Primitive prop via set_pose and observables', 'test setting and observing the orientation quaternion of a Primitive prop via set_pose', 'test setting and observing the linear velocity of a Primitive prop via set_velocity', 'test setting and observing the angular velocity of a Primitive prop via set_velocity']
```

Usage

```
{'build_PositionDetector': 'build a PositionDetector with a center position and half-length size for an axis-aligned box region', 'register_entities_PositionDetector': 'register entities with a PositionDetector so their geoms are monitored for presence in the active region', 'resize_PositionDetector': 'resize a PositionDetector by updating its center position and half-length size at runtime', 'set_position_PositionDetector': 'set the runtime position of a PositionDetector using physics and a new position array', 'check_activated_PositionDetector': 'check if a PositionDetector is activated by reading its activated property after simulation steps'}
```

## File: google-deepmind_dmcontrol/dm_control/entities/props/position_detector_test.py

Prompts

```
['build a PositionDetector with a center position and half-length size for an axis-aligned box region', 'register entities with a PositionDetector so their geoms are monitored for presence in the active region', 'resize a PositionDetector by updating its center position and half-length size at runtime', 'set the runtime position of a PositionDetector using physics and a new position array', 'check if a PositionDetector is activated by reading its activated property after simulation steps', 'test the PositionDetector class for 3D entity detection with configurable position and size parameters', 'test the PositionDetector class for 2D entity detection ignoring the z-axis coordinate', 'test the PositionDetector inverted mode to flip detection logic for registered entities', 'create a PositionDetector with a given position array, size array, and optional inverted flag', 'run the PositionDetector test suite to verify 3D and 2D detection with inverted modes', 'build a Primitive entity with a sphere geom type and specified radius for MuJoCo simulation', 'build a Primitive entity with a box geom type and x, y, z half lengths for simulation', "get the position sensor data from a Primitive entity's framepos sensor in the simulation", 'get the linear and angular velocity sensor data from a Primitive entity in the simulation', 'create PrimitiveObservables to expose position, orientation, linear velocity, and angular velocity as observable features', 'test creating Primitive props with sphere, capsule, cylinder, box, and ellipsoid geom types', 'test setting and observing the position of a Primitive prop via set_pose and observables', 'test setting and observing the orientation quaternion of a Primitive prop via set_pose', 'test setting and observing the linear velocity of a Primitive prop via set_velocity', 'test setting and observing the angular velocity of a Primitive prop via set_velocity']
```

Usage

```
{'test_PositionDetector_3D': 'test the PositionDetector class for 3D entity detection with configurable position and size parameters', 'test_PositionDetector_2D': 'test the PositionDetector class for 2D entity detection ignoring the z-axis coordinate', 'test_PositionDetector_inverted': 'test the PositionDetector inverted mode to flip detection logic for registered entities', 'create_PositionDetector': 'create a PositionDetector with a given position array, size array, and optional inverted flag', 'run_PositionDetector_test': 'run the PositionDetector test suite to verify 3D and 2D detection with inverted modes'}
```

## File: google-deepmind_dmcontrol/dm_control/entities/props/primitive.py

Prompts

```
['build a PositionDetector with a center position and half-length size for an axis-aligned box region', 'register entities with a PositionDetector so their geoms are monitored for presence in the active region', 'resize a PositionDetector by updating its center position and half-length size at runtime', 'set the runtime position of a PositionDetector using physics and a new position array', 'check if a PositionDetector is activated by reading its activated property after simulation steps', 'test the PositionDetector class for 3D entity detection with configurable position and size parameters', 'test the PositionDetector class for 2D entity detection ignoring the z-axis coordinate', 'test the PositionDetector inverted mode to flip detection logic for registered entities', 'create a PositionDetector with a given position array, size array, and optional inverted flag', 'run the PositionDetector test suite to verify 3D and 2D detection with inverted modes', 'build a Primitive entity with a sphere geom type and specified radius for MuJoCo simulation', 'build a Primitive entity with a box geom type and x, y, z half lengths for simulation', "get the position sensor data from a Primitive entity's framepos sensor in the simulation", 'get the linear and angular velocity sensor data from a Primitive entity in the simulation', 'create PrimitiveObservables to expose position, orientation, linear velocity, and angular velocity as observable features', 'test creating Primitive props with sphere, capsule, cylinder, box, and ellipsoid geom types', 'test setting and observing the position of a Primitive prop via set_pose and observables', 'test setting and observing the orientation quaternion of a Primitive prop via set_pose', 'test setting and observing the linear velocity of a Primitive prop via set_velocity', 'test setting and observing the angular velocity of a Primitive prop via set_velocity']
```

Usage

```
{'build_primitive_sphere': 'build a Primitive entity with a sphere geom type and specified radius for MuJoCo simulation', 'build_primitive_box': 'build a Primitive entity with a box geom type and x, y, z half lengths for simulation', 'get_primitive_position': "get the position sensor data from a Primitive entity's framepos sensor in the simulation", 'get_primitive_velocity': 'get the linear and angular velocity sensor data from a Primitive entity in the simulation', 'create_primitive_observables': 'create PrimitiveObservables to expose position, orientation, linear velocity, and angular velocity as observable features'}
```

## File: google-deepmind_dmcontrol/dm_control/entities/props/primitive_test.py

Prompts

```
['build a PositionDetector with a center position and half-length size for an axis-aligned box region', 'register entities with a PositionDetector so their geoms are monitored for presence in the active region', 'resize a PositionDetector by updating its center position and half-length size at runtime', 'set the runtime position of a PositionDetector using physics and a new position array', 'check if a PositionDetector is activated by reading its activated property after simulation steps', 'test the PositionDetector class for 3D entity detection with configurable position and size parameters', 'test the PositionDetector class for 2D entity detection ignoring the z-axis coordinate', 'test the PositionDetector inverted mode to flip detection logic for registered entities', 'create a PositionDetector with a given position array, size array, and optional inverted flag', 'run the PositionDetector test suite to verify 3D and 2D detection with inverted modes', 'build a Primitive entity with a sphere geom type and specified radius for MuJoCo simulation', 'build a Primitive entity with a box geom type and x, y, z half lengths for simulation', "get the position sensor data from a Primitive entity's framepos sensor in the simulation", 'get the linear and angular velocity sensor data from a Primitive entity in the simulation', 'create PrimitiveObservables to expose position, orientation, linear velocity, and angular velocity as observable features', 'test creating Primitive props with sphere, capsule, cylinder, box, and ellipsoid geom types', 'test setting and observing the position of a Primitive prop via set_pose and observables', 'test setting and observing the orientation quaternion of a Primitive prop via set_pose', 'test setting and observing the linear velocity of a Primitive prop via set_velocity', 'test setting and observing the angular velocity of a Primitive prop via set_velocity']
```

Usage

```
{'test_primitive_instantiation': 'test creating Primitive props with sphere, capsule, cylinder, box, and ellipsoid geom types', 'test_primitive_position_observable': 'test setting and observing the position of a Primitive prop via set_pose and observables', 'test_primitive_orientation_observable': 'test setting and observing the orientation quaternion of a Primitive prop via set_pose', 'test_primitive_linear_velocity_observable': 'test setting and observing the linear velocity of a Primitive prop via set_velocity', 'test_primitive_angular_velocity_observable': 'test setting and observing the angular velocity of a Primitive prop via set_velocity'}
```

