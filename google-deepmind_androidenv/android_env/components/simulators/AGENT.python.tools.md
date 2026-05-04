# Agent Python Tools

- repo: google-deepmind/androidenv
- repo_uri: https://github.com/google-deepmind/android_env

## File: google-deepmind_androidenv/android_env/components/simulators/base_simulator.py

Prompts

```
['build a python module that subclasses BaseSimulator to create a custom Android simulator implementation', 'create an InteractionThread that captures screenshots at a configurable rate in a background thread', 'send touch events with x, y coordinates and finger identifiers to the Android simulator', 'get a screenshot from the simulator in sync mode or async mode via the interaction thread', 'launch an Android simulator with error logging and close it to free resources', 'test that FakeSimulator launches without crashing using FakeSimulatorConfig', 'test that FakeSimulator launches and closes without crashing', 'test that FakeSimulator returns a screenshot with the correct shape dimensions', 'test that FakeSimulator calls get_logs when launch raises a SimulatorError', 'test that relaunching FakeSimulator stops and joins the previous InteractionThread']
```

Usage

```
{'build_android_simulator_subclass': 'build a python module that subclasses BaseSimulator to create a custom Android simulator implementation', 'create_interaction_thread': 'create an InteractionThread that captures screenshots at a configurable rate in a background thread', 'send_touch_events': 'send touch events with x, y coordinates and finger identifiers to the Android simulator', 'get_screenshot_sync_async': 'get a screenshot from the simulator in sync mode or async mode via the interaction thread', 'launch_and_close_simulator': 'launch an Android simulator with error logging and close it to free resources'}
```

## File: google-deepmind_androidenv/android_env/components/simulators/base_simulator_test.py

Prompts

```
['build a python module that subclasses BaseSimulator to create a custom Android simulator implementation', 'create an InteractionThread that captures screenshots at a configurable rate in a background thread', 'send touch events with x, y coordinates and finger identifiers to the Android simulator', 'get a screenshot from the simulator in sync mode or async mode via the interaction thread', 'launch an Android simulator with error logging and close it to free resources', 'test that FakeSimulator launches without crashing using FakeSimulatorConfig', 'test that FakeSimulator launches and closes without crashing', 'test that FakeSimulator returns a screenshot with the correct shape dimensions', 'test that FakeSimulator calls get_logs when launch raises a SimulatorError', 'test that relaunching FakeSimulator stops and joins the previous InteractionThread']
```

Usage

```
{'test_FakeSimulator_launch': 'test that FakeSimulator launches without crashing using FakeSimulatorConfig', 'test_FakeSimulator_launch_close': 'test that FakeSimulator launches and closes without crashing', 'test_FakeSimulator_get_screenshot': 'test that FakeSimulator returns a screenshot with the correct shape dimensions', 'test_FakeSimulator_print_logs_on_exception': 'test that FakeSimulator calls get_logs when launch raises a SimulatorError', 'test_FakeSimulator_interaction_thread_relaunch': 'test that relaunching FakeSimulator stops and joins the previous InteractionThread'}
```

