# Agent Python Tools

- repo: google-deepmind/androidenv
- repo_uri: https://github.com/google-deepmind/android_env

## File: google-deepmind_androidenv/android_env/components/simulators/fake/fake_simulator.py

Prompts

```
['create a FakeSimulator instance with a FakeSimulatorConfig to test AndroidEnv without a real device', 'create a FakeAdbController that returns fake output for adb shell service check and dumpsys commands', 'create a FakeLogStream wrapping a FakeStream to simulate ADB log output with reward and episode end messages', 'test the FakeSimulator _get_screenshot_impl method to return a random RGB numpy array matching screen dimensions', 'test the FakeStream iterator that yields weighted random log lines until kill is called', 'test the FakeSimulator returns adb_device_name equal to fake_simulator', 'test the FakeSimulator launches and closes without crashing', 'test the FakeSimulator get_screenshot returns a 320x480x3 uint8 numpy array', 'test the FakeSimulator create_log_stream yields reward and episode end log lines', 'test the FakeSimulator adb_controller executes shell commands like dumpsys input and service check']
```

Usage

```
{'create_fakesimulator': 'create a FakeSimulator instance with a FakeSimulatorConfig to test AndroidEnv without a real device', 'create_fakeadbcontroller': 'create a FakeAdbController that returns fake output for adb shell service check and dumpsys commands', 'create_fakelogstream': 'create a FakeLogStream wrapping a FakeStream to simulate ADB log output with reward and episode end messages', 'test_fakesimulator_screenshot': 'test the FakeSimulator _get_screenshot_impl method to return a random RGB numpy array matching screen dimensions', 'test_fakestream_iterator': 'test the FakeStream iterator that yields weighted random log lines until kill is called'}
```

## File: google-deepmind_androidenv/android_env/components/simulators/fake/fake_simulator_test.py

Prompts

```
['create a FakeSimulator instance with a FakeSimulatorConfig to test AndroidEnv without a real device', 'create a FakeAdbController that returns fake output for adb shell service check and dumpsys commands', 'create a FakeLogStream wrapping a FakeStream to simulate ADB log output with reward and episode end messages', 'test the FakeSimulator _get_screenshot_impl method to return a random RGB numpy array matching screen dimensions', 'test the FakeStream iterator that yields weighted random log lines until kill is called', 'test the FakeSimulator returns adb_device_name equal to fake_simulator', 'test the FakeSimulator launches and closes without crashing', 'test the FakeSimulator get_screenshot returns a 320x480x3 uint8 numpy array', 'test the FakeSimulator create_log_stream yields reward and episode end log lines', 'test the FakeSimulator adb_controller executes shell commands like dumpsys input and service check']
```

Usage

```
{'test_FakeSimulator_device_name': 'test the FakeSimulator returns adb_device_name equal to fake_simulator', 'test_FakeSimulator_launch_close': 'test the FakeSimulator launches and closes without crashing', 'test_FakeSimulator_get_screenshot': 'test the FakeSimulator get_screenshot returns a 320x480x3 uint8 numpy array', 'test_FakeSimulator_log_stream': 'test the FakeSimulator create_log_stream yields reward and episode end log lines', 'test_FakeSimulator_adb_output': 'test the FakeSimulator adb_controller executes shell commands like dumpsys input and service check'}
```

