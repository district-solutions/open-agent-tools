# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/labgraph/_cthulhu/tests/test_clock.py

Prompts

```
['test the ClockController tick method to manually advance experiment clock time by increments', 'test the ExperimentClock get_time method returns system time when clock is started normally', 'test the ClockController set_realtime_factor method to speed up experiment clock relative to system time', 'create a ClockController instance to pause and manually control experiment clock time', 'create an ExperimentClock instance to read the current experiment time from the clock manager', 'test the Labgraph Cthulhu Producer and Consumer wrappers to publish and subscribe to messages on a registered stream', 'test the Labgraph Cthulhu wrappers to stream messages through a multi-producer multi-consumer graph with transformation', 'run register_stream to create a named stream interface for a custom Message subclass', 'run Producer and Consumer context managers to publish and receive typed messages on a registered stream', 'run produce_message on a Producer instance to publish a typed message to the stream']
```

Usage

```
{'test_manual_busy_tick': 'test the ClockController tick method to manually advance experiment clock time by increments', 'test_regular_clock_time': 'test the ExperimentClock get_time method returns system time when clock is started normally', 'test_clock_with_realtime_factor': 'test the ClockController set_realtime_factor method to speed up experiment clock relative to system time', 'create_clock_controller': 'create a ClockController instance to pause and manually control experiment clock time', 'create_experiment_clock': 'create an ExperimentClock instance to read the current experiment time from the clock manager'}
```

## File: facebookresearch_labgraph/labgraph/_cthulhu/tests/test_cthulhu.py

Prompts

```
['test the ClockController tick method to manually advance experiment clock time by increments', 'test the ExperimentClock get_time method returns system time when clock is started normally', 'test the ClockController set_realtime_factor method to speed up experiment clock relative to system time', 'create a ClockController instance to pause and manually control experiment clock time', 'create an ExperimentClock instance to read the current experiment time from the clock manager', 'test the Labgraph Cthulhu Producer and Consumer wrappers to publish and subscribe to messages on a registered stream', 'test the Labgraph Cthulhu wrappers to stream messages through a multi-producer multi-consumer graph with transformation', 'run register_stream to create a named stream interface for a custom Message subclass', 'run Producer and Consumer context managers to publish and receive typed messages on a registered stream', 'run produce_message on a Producer instance to publish a typed message to the stream']
```

Usage

```
{'test_producer_consumer': 'test the Labgraph Cthulhu Producer and Consumer wrappers to publish and subscribe to messages on a registered stream', 'test_complex_graph': 'test the Labgraph Cthulhu wrappers to stream messages through a multi-producer multi-consumer graph with transformation', 'run_register_stream': 'run register_stream to create a named stream interface for a custom Message subclass', 'run_producer_consumer': 'run Producer and Consumer context managers to publish and receive typed messages on a registered stream', 'run_produce_message': 'run produce_message on a Producer instance to publish a typed message to the stream'}
```

