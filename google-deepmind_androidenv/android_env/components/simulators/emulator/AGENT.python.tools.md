# Agent Python Tools

- repo: google-deepmind/androidenv
- repo_uri: https://github.com/google-deepmind/android_env

## File: google-deepmind_androidenv/android_env/components/simulators/emulator/emulator_launcher.py

Prompts

```
['launch an Android emulator process with custom GPU mode, headless mode, and snapshot configuration', 'shut down the emulator process with a 30-second timeout before force killing it', 'clean up the emulator launcher temporary directory and close the emulator process', 'get the file path where the emulator stdout and stderr output is logged', 'configure Android SDK, AVD, KVM device, and ADB port environment variables for the emulator', 'test the EmulatorLauncher class to verify it launches an emulator process with correct command args and environment variables', 'test the EmulatorLauncher class to verify it passes the grpc port flag when grpc_port is configured', 'test the EmulatorLauncher class to verify it passes snapshot and migration feature flags when a snapshot name is set', 'test the EmulatorLauncher class to verify it passes network and wifi restriction options when restrict_network is enabled', 'review the EmulatorLauncherTest class and its parameterized test cases for emulator launch configuration validation', 'create an EmulatorSimulator instance with an EmulatorConfig to control an Android emulator', 'send touch events to the emulator screen with x, y coordinates and finger identifiers', 'send keyboard events to the emulator using XKB keycodes and event types', 'save and load emulator snapshots using the snapshot service stub by snapshot name', 'get a screenshot from the emulator as a numpy RGBA array via gRPC', 'test the EmulatorSimulator launch method to verify adb server initializes before emulator process starts', 'test the EmulatorSimulator get_screenshot method to verify it returns an RGB image with correct dimensions', 'test the EmulatorSimulator send_touch method to verify multi-touch events are sent via gRPC stub', 'test the EmulatorSimulator send_key method to verify keyboard events with keydown keyup and keypress types', 'test the EmulatorSimulator save_state and load_state methods to verify snapshot save and load via gRPC']
```

Usage

```
{'launch_android_emulator': 'launch an Android emulator process with custom GPU mode, headless mode, and snapshot configuration', 'shutdown_emulator_gracefully': 'shut down the emulator process with a 30-second timeout before force killing it', 'cleanup_emulator_resources': 'clean up the emulator launcher temporary directory and close the emulator process', 'get_emulator_logfile_path': 'get the file path where the emulator stdout and stderr output is logged', 'configure_emulator_environment': 'configure Android SDK, AVD, KVM device, and ADB port environment variables for the emulator'}
```

## File: google-deepmind_androidenv/android_env/components/simulators/emulator/emulator_launcher_test.py

Prompts

```
['launch an Android emulator process with custom GPU mode, headless mode, and snapshot configuration', 'shut down the emulator process with a 30-second timeout before force killing it', 'clean up the emulator launcher temporary directory and close the emulator process', 'get the file path where the emulator stdout and stderr output is logged', 'configure Android SDK, AVD, KVM device, and ADB port environment variables for the emulator', 'test the EmulatorLauncher class to verify it launches an emulator process with correct command args and environment variables', 'test the EmulatorLauncher class to verify it passes the grpc port flag when grpc_port is configured', 'test the EmulatorLauncher class to verify it passes snapshot and migration feature flags when a snapshot name is set', 'test the EmulatorLauncher class to verify it passes network and wifi restriction options when restrict_network is enabled', 'review the EmulatorLauncherTest class and its parameterized test cases for emulator launch configuration validation', 'create an EmulatorSimulator instance with an EmulatorConfig to control an Android emulator', 'send touch events to the emulator screen with x, y coordinates and finger identifiers', 'send keyboard events to the emulator using XKB keycodes and event types', 'save and load emulator snapshots using the snapshot service stub by snapshot name', 'get a screenshot from the emulator as a numpy RGBA array via gRPC', 'test the EmulatorSimulator launch method to verify adb server initializes before emulator process starts', 'test the EmulatorSimulator get_screenshot method to verify it returns an RGB image with correct dimensions', 'test the EmulatorSimulator send_touch method to verify multi-touch events are sent via gRPC stub', 'test the EmulatorSimulator send_key method to verify keyboard events with keydown keyup and keypress types', 'test the EmulatorSimulator save_state and load_state methods to verify snapshot save and load via gRPC']
```

Usage

```
{'test_EmulatorLauncher_launch': 'test the EmulatorLauncher class to verify it launches an emulator process with correct command args and environment variables', 'test_EmulatorLauncher_grpc_port': 'test the EmulatorLauncher class to verify it passes the grpc port flag when grpc_port is configured', 'test_EmulatorLauncher_snapshot': 'test the EmulatorLauncher class to verify it passes snapshot and migration feature flags when a snapshot name is set', 'test_EmulatorLauncher_network_restrict': 'test the EmulatorLauncher class to verify it passes network and wifi restriction options when restrict_network is enabled', 'review_EmulatorLauncherTest': 'review the EmulatorLauncherTest class and its parameterized test cases for emulator launch configuration validation'}
```

## File: google-deepmind_androidenv/android_env/components/simulators/emulator/emulator_simulator.py

Prompts

```
['launch an Android emulator process with custom GPU mode, headless mode, and snapshot configuration', 'shut down the emulator process with a 30-second timeout before force killing it', 'clean up the emulator launcher temporary directory and close the emulator process', 'get the file path where the emulator stdout and stderr output is logged', 'configure Android SDK, AVD, KVM device, and ADB port environment variables for the emulator', 'test the EmulatorLauncher class to verify it launches an emulator process with correct command args and environment variables', 'test the EmulatorLauncher class to verify it passes the grpc port flag when grpc_port is configured', 'test the EmulatorLauncher class to verify it passes snapshot and migration feature flags when a snapshot name is set', 'test the EmulatorLauncher class to verify it passes network and wifi restriction options when restrict_network is enabled', 'review the EmulatorLauncherTest class and its parameterized test cases for emulator launch configuration validation', 'create an EmulatorSimulator instance with an EmulatorConfig to control an Android emulator', 'send touch events to the emulator screen with x, y coordinates and finger identifiers', 'send keyboard events to the emulator using XKB keycodes and event types', 'save and load emulator snapshots using the snapshot service stub by snapshot name', 'get a screenshot from the emulator as a numpy RGBA array via gRPC', 'test the EmulatorSimulator launch method to verify adb server initializes before emulator process starts', 'test the EmulatorSimulator get_screenshot method to verify it returns an RGB image with correct dimensions', 'test the EmulatorSimulator send_touch method to verify multi-touch events are sent via gRPC stub', 'test the EmulatorSimulator send_key method to verify keyboard events with keydown keyup and keypress types', 'test the EmulatorSimulator save_state and load_state methods to verify snapshot save and load via gRPC']
```

Usage

```
{'create_emulator_simulator': 'create an EmulatorSimulator instance with an EmulatorConfig to control an Android emulator', 'send_touch_events': 'send touch events to the emulator screen with x, y coordinates and finger identifiers', 'send_key_events': 'send keyboard events to the emulator using XKB keycodes and event types', 'save_load_emulator_state': 'save and load emulator snapshots using the snapshot service stub by snapshot name', 'get_emulator_screenshot': 'get a screenshot from the emulator as a numpy RGBA array via gRPC'}
```

## File: google-deepmind_androidenv/android_env/components/simulators/emulator/emulator_simulator_test.py

Prompts

```
['launch an Android emulator process with custom GPU mode, headless mode, and snapshot configuration', 'shut down the emulator process with a 30-second timeout before force killing it', 'clean up the emulator launcher temporary directory and close the emulator process', 'get the file path where the emulator stdout and stderr output is logged', 'configure Android SDK, AVD, KVM device, and ADB port environment variables for the emulator', 'test the EmulatorLauncher class to verify it launches an emulator process with correct command args and environment variables', 'test the EmulatorLauncher class to verify it passes the grpc port flag when grpc_port is configured', 'test the EmulatorLauncher class to verify it passes snapshot and migration feature flags when a snapshot name is set', 'test the EmulatorLauncher class to verify it passes network and wifi restriction options when restrict_network is enabled', 'review the EmulatorLauncherTest class and its parameterized test cases for emulator launch configuration validation', 'create an EmulatorSimulator instance with an EmulatorConfig to control an Android emulator', 'send touch events to the emulator screen with x, y coordinates and finger identifiers', 'send keyboard events to the emulator using XKB keycodes and event types', 'save and load emulator snapshots using the snapshot service stub by snapshot name', 'get a screenshot from the emulator as a numpy RGBA array via gRPC', 'test the EmulatorSimulator launch method to verify adb server initializes before emulator process starts', 'test the EmulatorSimulator get_screenshot method to verify it returns an RGB image with correct dimensions', 'test the EmulatorSimulator send_touch method to verify multi-touch events are sent via gRPC stub', 'test the EmulatorSimulator send_key method to verify keyboard events with keydown keyup and keypress types', 'test the EmulatorSimulator save_state and load_state methods to verify snapshot save and load via gRPC']
```

Usage

```
{'test_emulator_simulator_launch': 'test the EmulatorSimulator launch method to verify adb server initializes before emulator process starts', 'test_emulator_screenshot': 'test the EmulatorSimulator get_screenshot method to verify it returns an RGB image with correct dimensions', 'test_emulator_touch_input': 'test the EmulatorSimulator send_touch method to verify multi-touch events are sent via gRPC stub', 'test_emulator_key_input': 'test the EmulatorSimulator send_key method to verify keyboard events with keydown keyup and keypress types', 'test_emulator_state_save_load': 'test the EmulatorSimulator save_state and load_state methods to verify snapshot save and load via gRPC'}
```

