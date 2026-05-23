# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/test/gmock_leak_test.py

Prompts

```
['test that Google Mock catches leaked mock objects by default without any flags', 'test that leaked mocks are ignored when gmock_catch_leaked_mocks is set to 0', 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is enabled', 'test that leaked mocks are caught when gmock_catch_leaked_mocks is explicitly set to 1', 'test that Google Mock catches multiple leaked mock objects in a single test run', 'run the gmock output test to verify Google C++ Mocking Framework text output matches the golden file', 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, memory addresses, and error markers', 'find and return a list of test names that leak mock objects from gmock output', 'remove all file location info from Google Test program output and replace with FILE:#: placeholder', 'get the absolute path of the directory where the gmock test .py files are located', 'get the absolute path of a test binary given its executable name for running gmock tests', 'extract the exit status code from an os.system command result on Unix or Windows', 'run a subprocess command and capture its output using the Subprocess utility class', 'set an environment variable for the current process using the SetEnvVar utility function']
```

Usage

```
{'test_catches_leaked_mock_by_default': 'test that Google Mock catches leaked mock objects by default without any flags', 'test_does_not_catch_leaked_mock_when_disabled': 'test that leaked mocks are ignored when gmock_catch_leaked_mocks is set to 0', 'test_catches_leaked_mock_when_enabled': 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is enabled', 'test_catches_leaked_mock_when_enabled_with_explicit_flag_value': 'test that leaked mocks are caught when gmock_catch_leaked_mocks is explicitly set to 1', 'test_catches_multiple_leaked_mocks': 'test that Google Mock catches multiple leaked mock objects in a single test run'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/test/gmock_output_test.py

Prompts

```
['test that Google Mock catches leaked mock objects by default without any flags', 'test that leaked mocks are ignored when gmock_catch_leaked_mocks is set to 0', 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is enabled', 'test that leaked mocks are caught when gmock_catch_leaked_mocks is explicitly set to 1', 'test that Google Mock catches multiple leaked mock objects in a single test run', 'run the gmock output test to verify Google C++ Mocking Framework text output matches the golden file', 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, memory addresses, and error markers', 'find and return a list of test names that leak mock objects from gmock output', 'remove all file location info from Google Test program output and replace with FILE:#: placeholder', 'get the absolute path of the directory where the gmock test .py files are located', 'get the absolute path of a test binary given its executable name for running gmock tests', 'extract the exit status code from an os.system command result on Unix or Windows', 'run a subprocess command and capture its output using the Subprocess utility class', 'set an environment variable for the current process using the SetEnvVar utility function']
```

Usage

```
{'run_gmock_output_test': 'run the gmock output test to verify Google C++ Mocking Framework text output matches the golden file', 'generate_golden_file': 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize_test_output': 'normalize gmock test output by removing headers, footers, locations, memory addresses, and error markers', 'find_leaky_mock_tests': 'find and return a list of test names that leak mock objects from gmock output', 'remove_file_locations': 'remove all file location info from Google Test program output and replace with FILE:#: placeholder'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/test/gmock_test_utils.py

Prompts

```
['test that Google Mock catches leaked mock objects by default without any flags', 'test that leaked mocks are ignored when gmock_catch_leaked_mocks is set to 0', 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is enabled', 'test that leaked mocks are caught when gmock_catch_leaked_mocks is explicitly set to 1', 'test that Google Mock catches multiple leaked mock objects in a single test run', 'run the gmock output test to verify Google C++ Mocking Framework text output matches the golden file', 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, memory addresses, and error markers', 'find and return a list of test names that leak mock objects from gmock output', 'remove all file location info from Google Test program output and replace with FILE:#: placeholder', 'get the absolute path of the directory where the gmock test .py files are located', 'get the absolute path of a test binary given its executable name for running gmock tests', 'extract the exit status code from an os.system command result on Unix or Windows', 'run a subprocess command and capture its output using the Subprocess utility class', 'set an environment variable for the current process using the SetEnvVar utility function']
```

Usage

```
{'get_source_dir': 'get the absolute path of the directory where the gmock test .py files are located', 'get_test_executable_path': 'get the absolute path of a test binary given its executable name for running gmock tests', 'get_exit_status': 'extract the exit status code from an os.system command result on Unix or Windows', 'run_subprocess': 'run a subprocess command and capture its output using the Subprocess utility class', 'set_env_var': 'set an environment variable for the current process using the SetEnvVar utility function'}
```

