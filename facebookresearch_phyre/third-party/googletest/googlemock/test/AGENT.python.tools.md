# Agent Python Tools

- repo: facebookresearch/phyre
- repo_uri: https://github.com/facebookresearch/phyre

## File: facebookresearch_phyre/third-party/googletest/googlemock/test/gmock_leak_test.py

Prompts

```
['run the GMockLeakTest suite to verify leaked mock objects are caught by Google Mock', 'test that leaked mocks are caught by default when running ExpectCall or OnCall tests', 'test that leaked mocks are not caught when gmock_catch_leaked_mocks is set to 0', 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is enabled', 'test that multiple leaked mocks are caught when gmock_catch_leaked_mocks is enabled', 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate the golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'find test names that leak mock objects from gmock test output using regex', 'convert Windows and Mac line endings to UNIX format in test output strings', 'get the absolute path of the directory where the gmock test .py files are located', 'get the absolute path of a compiled test binary given its executable name', 'extract the exit status code from the result of os.system on Unix or Windows', 'run a subprocess command and capture its output using the Subprocess utility class', 'set an environment variable for test execution using the SetEnvVar utility function']
```

Usage

```
{'run_GMockLeakTest': 'run the GMockLeakTest suite to verify leaked mock objects are caught by Google Mock', 'test_testCatchesLeakedMockByDefault': 'test that leaked mocks are caught by default when running ExpectCall or OnCall tests', 'test_testDoesNotCatchLeakedMockWhenDisabled': 'test that leaked mocks are not caught when gmock_catch_leaked_mocks is set to 0', 'test_testCatchesLeakedMockWhenEnabled': 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is enabled', 'test_testCatchesMultipleLeakedMocks': 'test that multiple leaked mocks are caught when gmock_catch_leaked_mocks is enabled'}
```

## File: facebookresearch_phyre/third-party/googletest/googlemock/test/gmock_output_test.py

Prompts

```
['run the GMockLeakTest suite to verify leaked mock objects are caught by Google Mock', 'test that leaked mocks are caught by default when running ExpectCall or OnCall tests', 'test that leaked mocks are not caught when gmock_catch_leaked_mocks is set to 0', 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is enabled', 'test that multiple leaked mocks are caught when gmock_catch_leaked_mocks is enabled', 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate the golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'find test names that leak mock objects from gmock test output using regex', 'convert Windows and Mac line endings to UNIX format in test output strings', 'get the absolute path of the directory where the gmock test .py files are located', 'get the absolute path of a compiled test binary given its executable name', 'extract the exit status code from the result of os.system on Unix or Windows', 'run a subprocess command and capture its output using the Subprocess utility class', 'set an environment variable for test execution using the SetEnvVar utility function']
```

Usage

```
{'run_gmock_output_test': 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate_golden_file': 'generate the golden file by running gmock_output_test.py with the --gengolden flag', 'normalize_test_output': 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'find_leaky_mock_tests': 'find test names that leak mock objects from gmock test output using regex', 'convert_line_endings': 'convert Windows and Mac line endings to UNIX format in test output strings'}
```

## File: facebookresearch_phyre/third-party/googletest/googlemock/test/gmock_test_utils.py

Prompts

```
['run the GMockLeakTest suite to verify leaked mock objects are caught by Google Mock', 'test that leaked mocks are caught by default when running ExpectCall or OnCall tests', 'test that leaked mocks are not caught when gmock_catch_leaked_mocks is set to 0', 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is enabled', 'test that multiple leaked mocks are caught when gmock_catch_leaked_mocks is enabled', 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate the golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'find test names that leak mock objects from gmock test output using regex', 'convert Windows and Mac line endings to UNIX format in test output strings', 'get the absolute path of the directory where the gmock test .py files are located', 'get the absolute path of a compiled test binary given its executable name', 'extract the exit status code from the result of os.system on Unix or Windows', 'run a subprocess command and capture its output using the Subprocess utility class', 'set an environment variable for test execution using the SetEnvVar utility function']
```

Usage

```
{'get_source_dir': 'get the absolute path of the directory where the gmock test .py files are located', 'get_test_executable_path': 'get the absolute path of a compiled test binary given its executable name', 'get_exit_status': 'extract the exit status code from the result of os.system on Unix or Windows', 'run_subprocess': 'run a subprocess command and capture its output using the Subprocess utility class', 'set_env_var': 'set an environment variable for test execution using the SetEnvVar utility function'}
```

