# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/third_party/googletest/googlemock/test/gmock_leak_test.py

Prompts

```
['test that GMockLeakTest catches leaked mock objects by default using ExpectCall and OnCall', 'test that GMockLeakTest does not catch leaked mocks when gmock_catch_leaked_mocks is set to 0', 'test that GMockLeakTest catches leaked mocks when gmock_catch_leaked_mocks flag is enabled', 'test that GMockLeakTest catches leaked mocks when gmock_catch_leaked_mocks is explicitly set to 1', 'test that GMockLeakTest catches multiple leaked mock objects in a single test run', 'run the gmock output test to verify Google C++ Mocking Framework text output matches the golden file', 'generate a new golden file for gmock output test by running with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, memory addresses, and error markers', 'extract a list of test names that leak mock objects from gmock test output using regex', 'remove all file location info from Google Test program output and replace with FILE:#: placeholder', 'get the absolute path of the directory where the gmock test .py files are located', 'get the absolute path of a test binary given its executable name for running gmock tests', 'extract the exit status code from an os.system result across Windows and Unix platforms', 'run a subprocess command and capture its output using the gmock test Subprocess utility', 'run the gmock unit test suite by calling the Main entry point function']
```

Usage

```
{'test_leaked_mock_by_default': 'test that GMockLeakTest catches leaked mock objects by default using ExpectCall and OnCall', 'test_leaked_mock_disabled': 'test that GMockLeakTest does not catch leaked mocks when gmock_catch_leaked_mocks is set to 0', 'test_leaked_mock_enabled': 'test that GMockLeakTest catches leaked mocks when gmock_catch_leaked_mocks flag is enabled', 'test_leaked_mock_explicit_flag': 'test that GMockLeakTest catches leaked mocks when gmock_catch_leaked_mocks is explicitly set to 1', 'test_multiple_leaked_mocks': 'test that GMockLeakTest catches multiple leaked mock objects in a single test run'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/googletest/googlemock/test/gmock_output_test.py

Prompts

```
['test that GMockLeakTest catches leaked mock objects by default using ExpectCall and OnCall', 'test that GMockLeakTest does not catch leaked mocks when gmock_catch_leaked_mocks is set to 0', 'test that GMockLeakTest catches leaked mocks when gmock_catch_leaked_mocks flag is enabled', 'test that GMockLeakTest catches leaked mocks when gmock_catch_leaked_mocks is explicitly set to 1', 'test that GMockLeakTest catches multiple leaked mock objects in a single test run', 'run the gmock output test to verify Google C++ Mocking Framework text output matches the golden file', 'generate a new golden file for gmock output test by running with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, memory addresses, and error markers', 'extract a list of test names that leak mock objects from gmock test output using regex', 'remove all file location info from Google Test program output and replace with FILE:#: placeholder', 'get the absolute path of the directory where the gmock test .py files are located', 'get the absolute path of a test binary given its executable name for running gmock tests', 'extract the exit status code from an os.system result across Windows and Unix platforms', 'run a subprocess command and capture its output using the gmock test Subprocess utility', 'run the gmock unit test suite by calling the Main entry point function']
```

Usage

```
{'run_gmock_output_test': 'run the gmock output test to verify Google C++ Mocking Framework text output matches the golden file', 'generate_golden_file': 'generate a new golden file for gmock output test by running with the --gengolden flag', 'normalize_test_output': 'normalize gmock test output by removing headers, footers, locations, memory addresses, and error markers', 'extract_leaky_tests': 'extract a list of test names that leak mock objects from gmock test output using regex', 'remove_file_locations': 'remove all file location info from Google Test program output and replace with FILE:#: placeholder'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/googletest/googlemock/test/gmock_test_utils.py

Prompts

```
['test that GMockLeakTest catches leaked mock objects by default using ExpectCall and OnCall', 'test that GMockLeakTest does not catch leaked mocks when gmock_catch_leaked_mocks is set to 0', 'test that GMockLeakTest catches leaked mocks when gmock_catch_leaked_mocks flag is enabled', 'test that GMockLeakTest catches leaked mocks when gmock_catch_leaked_mocks is explicitly set to 1', 'test that GMockLeakTest catches multiple leaked mock objects in a single test run', 'run the gmock output test to verify Google C++ Mocking Framework text output matches the golden file', 'generate a new golden file for gmock output test by running with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, memory addresses, and error markers', 'extract a list of test names that leak mock objects from gmock test output using regex', 'remove all file location info from Google Test program output and replace with FILE:#: placeholder', 'get the absolute path of the directory where the gmock test .py files are located', 'get the absolute path of a test binary given its executable name for running gmock tests', 'extract the exit status code from an os.system result across Windows and Unix platforms', 'run a subprocess command and capture its output using the gmock test Subprocess utility', 'run the gmock unit test suite by calling the Main entry point function']
```

Usage

```
{'get_source_dir': 'get the absolute path of the directory where the gmock test .py files are located', 'get_test_executable_path': 'get the absolute path of a test binary given its executable name for running gmock tests', 'get_exit_status': 'extract the exit status code from an os.system result across Windows and Unix platforms', 'run_subprocess': 'run a subprocess command and capture its output using the gmock test Subprocess utility', 'run_main': 'run the gmock unit test suite by calling the Main entry point function'}
```

