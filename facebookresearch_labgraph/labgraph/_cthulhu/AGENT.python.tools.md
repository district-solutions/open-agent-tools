# Agent Python Tools

- repo: facebookresearch/labgraph
- repo_uri: https://github.com/facebookresearch/labgraph

## File: facebookresearch_labgraph/labgraph/_cthulhu/clock.py

Prompts

```
['create an ExperimentClock instance to get the current simulation time via get_time', 'create a ClockController and call start with a start_time to begin the simulation clock', 'use ClockController set_time to set the current time and optionally start running the clock', 'use ClockController tick to advance the simulation clock forward by a specified increment', 'use ClockController set_realtime_factor to adjust the clock speed while preserving paused or running state', 'create a Consumer that wraps a Cthulhu StreamConsumer with a Labgraph message callback', 'create a Producer that wraps a Cthulhu StreamProducer to emit Labgraph messages', 'register a named stream with a Labgraph message type in the Cthulhu stream registry', 'get an existing StreamInterface from the Cthulhu stream registry by its name', 'format a PerformanceSummary object into a human-readable string with runtime and drop stats']
```

Usage

```
{'create_experiment_clock': 'create an ExperimentClock instance to get the current simulation time via get_time', 'start_clock_controller': 'create a ClockController and call start with a start_time to begin the simulation clock', 'set_clock_time': 'use ClockController set_time to set the current time and optionally start running the clock', 'tick_clock_forward': 'use ClockController tick to advance the simulation clock forward by a specified increment', 'set_realtime_factor': 'use ClockController set_realtime_factor to adjust the clock speed while preserving paused or running state'}
```

## File: facebookresearch_labgraph/labgraph/_cthulhu/cthulhu.py

Prompts

```
['create an ExperimentClock instance to get the current simulation time via get_time', 'create a ClockController and call start with a start_time to begin the simulation clock', 'use ClockController set_time to set the current time and optionally start running the clock', 'use ClockController tick to advance the simulation clock forward by a specified increment', 'use ClockController set_realtime_factor to adjust the clock speed while preserving paused or running state', 'create a Consumer that wraps a Cthulhu StreamConsumer with a Labgraph message callback', 'create a Producer that wraps a Cthulhu StreamProducer to emit Labgraph messages', 'register a named stream with a Labgraph message type in the Cthulhu stream registry', 'get an existing StreamInterface from the Cthulhu stream registry by its name', 'format a PerformanceSummary object into a human-readable string with runtime and drop stats']
```

Usage

```
{'create_consumer_with_callback': 'create a Consumer that wraps a Cthulhu StreamConsumer with a Labgraph message callback', 'create_producer_for_stream': 'create a Producer that wraps a Cthulhu StreamProducer to emit Labgraph messages', 'register_stream_with_message_type': 'register a named stream with a Labgraph message type in the Cthulhu stream registry', 'get_stream_by_name': 'get an existing StreamInterface from the Cthulhu stream registry by its name', 'format_performance_summary': 'format a PerformanceSummary object into a human-readable string with runtime and drop stats'}
```

