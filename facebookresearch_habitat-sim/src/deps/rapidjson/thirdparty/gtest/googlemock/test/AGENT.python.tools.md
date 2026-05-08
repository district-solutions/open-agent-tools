# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/rapidjson/thirdparty/gtest/googlemock/test/gmock_leak_test.py

Prompts

```
['run the gmock leak detection test suite to verify leaked mock objects are caught by default', 'test that gmock catches leaked mock objects by default using ExpectCall and OnCall filters', 'test that gmock does not catch leaked mocks when gmock_catch_leaked_mocks is set to 0', 'test that gmock catches leaked mocks when gmock_catch_leaked_mocks flag is explicitly enabled', 'test that gmock catches multiple leaked mock objects in a single test run', 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate a golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'detect and list test names that have leaked mock objects from gmock output', 'remove file location info from Google Test output and replace with normalized FILE:#: format', 'get the absolute path of the directory where the gmock test .py files reside', 'get the absolute path of a gmock test binary given its executable name', 'extract the exit status code from the result of os.system on Unix or Windows', 'run a subprocess command and capture its output using the Subprocess utility class', 'set an environment variable using the SetEnvVar utility for cross-platform compatibility']
```

Usage

```
{'run_gmock_leak_tests': 'run the gmock leak detection test suite to verify leaked mock objects are caught by default', 'test_leaked_mock_default': 'test that gmock catches leaked mock objects by default using ExpectCall and OnCall filters', 'test_leaked_mock_disabled': 'test that gmock does not catch leaked mocks when gmock_catch_leaked_mocks is set to 0', 'test_leaked_mock_enabled': 'test that gmock catches leaked mocks when gmock_catch_leaked_mocks flag is explicitly enabled', 'test_multiple_leaked_mocks': 'test that gmock catches multiple leaked mock objects in a single test run'}
```

## File: facebookresearch_habitat-sim/src/deps/rapidjson/thirdparty/gtest/googlemock/test/gmock_output_test.py

Prompts

```
['run the gmock leak detection test suite to verify leaked mock objects are caught by default', 'test that gmock catches leaked mock objects by default using ExpectCall and OnCall filters', 'test that gmock does not catch leaked mocks when gmock_catch_leaked_mocks is set to 0', 'test that gmock catches leaked mocks when gmock_catch_leaked_mocks flag is explicitly enabled', 'test that gmock catches multiple leaked mock objects in a single test run', 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate a golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'detect and list test names that have leaked mock objects from gmock output', 'remove file location info from Google Test output and replace with normalized FILE:#: format', 'get the absolute path of the directory where the gmock test .py files reside', 'get the absolute path of a gmock test binary given its executable name', 'extract the exit status code from the result of os.system on Unix or Windows', 'run a subprocess command and capture its output using the Subprocess utility class', 'set an environment variable using the SetEnvVar utility for cross-platform compatibility']
```

Usage

```
{'run_gmock_output_test': 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate_golden_file': 'generate a golden file by running gmock_output_test.py with the --gengolden flag', 'normalize_test_output': 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'detect_leaked_mocks': 'detect and list test names that have leaked mock objects from gmock output', 'remove_file_locations': 'remove file location info from Google Test output and replace with normalized FILE:#: format'}
```

## File: facebookresearch_habitat-sim/src/deps/rapidjson/thirdparty/gtest/googlemock/test/gmock_test_utils.py

Prompts

```
['run the gmock leak detection test suite to verify leaked mock objects are caught by default', 'test that gmock catches leaked mock objects by default using ExpectCall and OnCall filters', 'test that gmock does not catch leaked mocks when gmock_catch_leaked_mocks is set to 0', 'test that gmock catches leaked mocks when gmock_catch_leaked_mocks flag is explicitly enabled', 'test that gmock catches multiple leaked mock objects in a single test run', 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate a golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'detect and list test names that have leaked mock objects from gmock output', 'remove file location info from Google Test output and replace with normalized FILE:#: format', 'get the absolute path of the directory where the gmock test .py files reside', 'get the absolute path of a gmock test binary given its executable name', 'extract the exit status code from the result of os.system on Unix or Windows', 'run a subprocess command and capture its output using the Subprocess utility class', 'set an environment variable using the SetEnvVar utility for cross-platform compatibility']
```

Usage

```
{'get_source_dir': 'get the absolute path of the directory where the gmock test .py files reside', 'get_test_executable_path': 'get the absolute path of a gmock test binary given its executable name', 'get_exit_status': 'extract the exit status code from the result of os.system on Unix or Windows', 'run_subprocess': 'run a subprocess command and capture its output using the Subprocess utility class', 'set_env_var': 'set an environment variable using the SetEnvVar utility for cross-platform compatibility'}
```

