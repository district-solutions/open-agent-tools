# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src_python/habitat_sim/errors.py

Prompts

```
['review the InvalidAttachedObject exception class and its usage as a RuntimeError subclass', 'review the GreedyFollowerError exception class and its usage as a RuntimeError subclass', 'test the assert_obj_valid function with a valid and invalid AbstractFeature3D object', 'create an InvalidAttachedObject exception to handle invalid attached object scenarios in habitat-sim', 'create a GreedyFollowerError exception to handle greedy follower failure scenarios in habitat-sim', 'use the habitat sim logger to log messages at DEBUG, INFO, WARNING, ERROR, or FATAL levels', 'create a function that safely formats a LogRecord message string handling both formatted and plain messages', 'build a custom logging Formatter subclass that prefixes all log messages with the [Sim] tag', 'configure the logger level to ERROR when sim_is_quiet is true or INFO otherwise using LoggingContext', 'review the HabitatSimFormatter format method to understand how it wraps LogRecord messages with the [Sim] prefix', 'register a new movement controller with the Habitat-Sim registry using the decorator syntax', 'register a new sensor noise model with the Habitat-Sim registry using the decorator syntax', 'retrieve a previously registered movement function by its name from the registry', 'retrieve a previously registered sensor noise model by its name from the registry', 'convert a CamelCase string to snake_case using regex-based name transformation', 'create a Simulator instance from a Configuration object with sim_cfg and agent configurations', 'reset the simulator state and return sensor observations for specified agent ids', 'step the simulation forward with an action and return sensor observations with collision info', 'get sensor observations for one or more agents by their agent ids', 'create a new sensor on a SceneNode using a SensorSpec and register it in the simulator']
```

Usage

```
{'review_InvalidAttachedObject': 'review the InvalidAttachedObject exception class and its usage as a RuntimeError subclass', 'review_GreedyFollowerError': 'review the GreedyFollowerError exception class and its usage as a RuntimeError subclass', 'test_assert_obj_valid': 'test the assert_obj_valid function with a valid and invalid AbstractFeature3D object', 'create_InvalidAttachedObject': 'create an InvalidAttachedObject exception to handle invalid attached object scenarios in habitat-sim', 'create_GreedyFollowerError': 'create a GreedyFollowerError exception to handle greedy follower failure scenarios in habitat-sim'}
```

## File: facebookresearch_habitat-sim/src_python/habitat_sim/logging.py

Prompts

```
['review the InvalidAttachedObject exception class and its usage as a RuntimeError subclass', 'review the GreedyFollowerError exception class and its usage as a RuntimeError subclass', 'test the assert_obj_valid function with a valid and invalid AbstractFeature3D object', 'create an InvalidAttachedObject exception to handle invalid attached object scenarios in habitat-sim', 'create a GreedyFollowerError exception to handle greedy follower failure scenarios in habitat-sim', 'use the habitat sim logger to log messages at DEBUG, INFO, WARNING, ERROR, or FATAL levels', 'create a function that safely formats a LogRecord message string handling both formatted and plain messages', 'build a custom logging Formatter subclass that prefixes all log messages with the [Sim] tag', 'configure the logger level to ERROR when sim_is_quiet is true or INFO otherwise using LoggingContext', 'review the HabitatSimFormatter format method to understand how it wraps LogRecord messages with the [Sim] prefix', 'register a new movement controller with the Habitat-Sim registry using the decorator syntax', 'register a new sensor noise model with the Habitat-Sim registry using the decorator syntax', 'retrieve a previously registered movement function by its name from the registry', 'retrieve a previously registered sensor noise model by its name from the registry', 'convert a CamelCase string to snake_case using regex-based name transformation', 'create a Simulator instance from a Configuration object with sim_cfg and agent configurations', 'reset the simulator state and return sensor observations for specified agent ids', 'step the simulation forward with an action and return sensor observations with collision info', 'get sensor observations for one or more agents by their agent ids', 'create a new sensor on a SceneNode using a SensorSpec and register it in the simulator']
```

Usage

```
{'use_logger': 'use the habitat sim logger to log messages at DEBUG, INFO, WARNING, ERROR, or FATAL levels', 'format_message': 'create a function that safely formats a LogRecord message string handling both formatted and plain messages', 'create_HabitatSimFormatter': 'build a custom logging Formatter subclass that prefixes all log messages with the [Sim] tag', 'configure_logger_level': 'configure the logger level to ERROR when sim_is_quiet is true or INFO otherwise using LoggingContext', 'review_HabitatSimFormatter_format': 'review the HabitatSimFormatter format method to understand how it wraps LogRecord messages with the [Sim] prefix'}
```

## File: facebookresearch_habitat-sim/src_python/habitat_sim/registry.py

Prompts

```
['review the InvalidAttachedObject exception class and its usage as a RuntimeError subclass', 'review the GreedyFollowerError exception class and its usage as a RuntimeError subclass', 'test the assert_obj_valid function with a valid and invalid AbstractFeature3D object', 'create an InvalidAttachedObject exception to handle invalid attached object scenarios in habitat-sim', 'create a GreedyFollowerError exception to handle greedy follower failure scenarios in habitat-sim', 'use the habitat sim logger to log messages at DEBUG, INFO, WARNING, ERROR, or FATAL levels', 'create a function that safely formats a LogRecord message string handling both formatted and plain messages', 'build a custom logging Formatter subclass that prefixes all log messages with the [Sim] tag', 'configure the logger level to ERROR when sim_is_quiet is true or INFO otherwise using LoggingContext', 'review the HabitatSimFormatter format method to understand how it wraps LogRecord messages with the [Sim] prefix', 'register a new movement controller with the Habitat-Sim registry using the decorator syntax', 'register a new sensor noise model with the Habitat-Sim registry using the decorator syntax', 'retrieve a previously registered movement function by its name from the registry', 'retrieve a previously registered sensor noise model by its name from the registry', 'convert a CamelCase string to snake_case using regex-based name transformation', 'create a Simulator instance from a Configuration object with sim_cfg and agent configurations', 'reset the simulator state and return sensor observations for specified agent ids', 'step the simulation forward with an action and return sensor observations with collision info', 'get sensor observations for one or more agents by their agent ids', 'create a new sensor on a SceneNode using a SensorSpec and register it in the simulator']
```

Usage

```
{'register_move_fn': 'register a new movement controller with the Habitat-Sim registry using the decorator syntax', 'register_noise_model': 'register a new sensor noise model with the Habitat-Sim registry using the decorator syntax', 'get_move_fn': 'retrieve a previously registered movement function by its name from the registry', 'get_noise_model': 'retrieve a previously registered sensor noise model by its name from the registry', 'camel_to_snake': 'convert a CamelCase string to snake_case using regex-based name transformation'}
```

## File: facebookresearch_habitat-sim/src_python/habitat_sim/simulator.py

Prompts

```
['review the InvalidAttachedObject exception class and its usage as a RuntimeError subclass', 'review the GreedyFollowerError exception class and its usage as a RuntimeError subclass', 'test the assert_obj_valid function with a valid and invalid AbstractFeature3D object', 'create an InvalidAttachedObject exception to handle invalid attached object scenarios in habitat-sim', 'create a GreedyFollowerError exception to handle greedy follower failure scenarios in habitat-sim', 'use the habitat sim logger to log messages at DEBUG, INFO, WARNING, ERROR, or FATAL levels', 'create a function that safely formats a LogRecord message string handling both formatted and plain messages', 'build a custom logging Formatter subclass that prefixes all log messages with the [Sim] tag', 'configure the logger level to ERROR when sim_is_quiet is true or INFO otherwise using LoggingContext', 'review the HabitatSimFormatter format method to understand how it wraps LogRecord messages with the [Sim] prefix', 'register a new movement controller with the Habitat-Sim registry using the decorator syntax', 'register a new sensor noise model with the Habitat-Sim registry using the decorator syntax', 'retrieve a previously registered movement function by its name from the registry', 'retrieve a previously registered sensor noise model by its name from the registry', 'convert a CamelCase string to snake_case using regex-based name transformation', 'create a Simulator instance from a Configuration object with sim_cfg and agent configurations', 'reset the simulator state and return sensor observations for specified agent ids', 'step the simulation forward with an action and return sensor observations with collision info', 'get sensor observations for one or more agents by their agent ids', 'create a new sensor on a SceneNode using a SensorSpec and register it in the simulator']
```

Usage

```
{'create_simulator_instance': 'create a Simulator instance from a Configuration object with sim_cfg and agent configurations', 'reset_simulator': 'reset the simulator state and return sensor observations for specified agent ids', 'step_simulation': 'step the simulation forward with an action and return sensor observations with collision info', 'get_sensor_observations': 'get sensor observations for one or more agents by their agent ids', 'create_sensor': 'create a new sensor on a SceneNode using a SensorSpec and register it in the simulator'}
```

