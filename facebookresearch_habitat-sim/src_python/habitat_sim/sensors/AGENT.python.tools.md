# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src_python/habitat_sim/sensors/sensor_suite.py

Prompts

```
['create a SensorSuite instance to hold all agent sensors as a dictionary keyed by UUID', 'add a habitat_sim sensor to the SensorSuite using the add method which keys by sensor UUID', 'lookup a sensor in the SensorSuite dictionary by its specification UUID string key', 'review the SensorSuite class which extends Dict to hold agent sensors with an add helper method', 'summarize the SensorSuite class that wraps a dictionary of sensors indexed by their UUID', 'draw a sensor observation to the framebuffer using the SimulatorBackend renderer', 'get the rendered observation from the sensor framebuffer with noise model applied', 'enqueue a sensor draw job for asynchronous rendering with the simulator renderer', 'get the observation from a sensor after an async render job completes', 'close a sensor wrapper and release references to the simulator and sensor object']
```

Usage

```
{'create_sensor_suite': 'create a SensorSuite instance to hold all agent sensors as a dictionary keyed by UUID', 'add_sensor_to_suite': 'add a habitat_sim sensor to the SensorSuite using the add method which keys by sensor UUID', 'lookup_sensor_by_uuid': 'lookup a sensor in the SensorSuite dictionary by its specification UUID string key', 'review_sensor_suite_class': 'review the SensorSuite class which extends Dict to hold agent sensors with an add helper method', 'summarize_sensor_suite': 'summarize the SensorSuite class that wraps a dictionary of sensors indexed by their UUID'}
```

## File: facebookresearch_habitat-sim/src_python/habitat_sim/sensors/sensor_wrapper.py

Prompts

```
['create a SensorSuite instance to hold all agent sensors as a dictionary keyed by UUID', 'add a habitat_sim sensor to the SensorSuite using the add method which keys by sensor UUID', 'lookup a sensor in the SensorSuite dictionary by its specification UUID string key', 'review the SensorSuite class which extends Dict to hold agent sensors with an add helper method', 'summarize the SensorSuite class that wraps a dictionary of sensors indexed by their UUID', 'draw a sensor observation to the framebuffer using the SimulatorBackend renderer', 'get the rendered observation from the sensor framebuffer with noise model applied', 'enqueue a sensor draw job for asynchronous rendering with the simulator renderer', 'get the observation from a sensor after an async render job completes', 'close a sensor wrapper and release references to the simulator and sensor object']
```

Usage

```
{'draw_observation': 'draw a sensor observation to the framebuffer using the SimulatorBackend renderer', 'get_observation': 'get the rendered observation from the sensor framebuffer with noise model applied', 'render_async': 'enqueue a sensor draw job for asynchronous rendering with the simulator renderer', 'get_observation_async': 'get the observation from a sensor after an async render job completes', 'close_sensor': 'close a sensor wrapper and release references to the simulator and sensor object'}
```

