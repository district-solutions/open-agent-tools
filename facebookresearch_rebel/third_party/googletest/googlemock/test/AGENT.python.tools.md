# Agent Python Tools

- repo: facebookresearch/rebel
- repo_uri: https://github.com/facebookresearch/rebel

## File: facebookresearch_rebel/third_party/googletest/googlemock/test/gmock_leak_test.py

Prompts

```
['run the GMockLeakTest to verify leaked mocks are caught by default in ExpectCall and OnCall tests', 'run the GMockLeakTest to verify leaked mocks are not caught when gmock_catch_leaked_mocks is disabled', 'run the GMockLeakTest to verify leaked mocks are caught when gmock_catch_leaked_mocks is explicitly enabled', 'run the GMockLeakTest to verify leaked mocks are caught when gmock_catch_leaked_mocks equals 1', 'run the GMockLeakTest to verify multiple leaked mock objects are all caught and reported', 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'extract a list of test names that leak mock objects from gmock output text', 'run a shell command in a subprocess and capture its stdout as a string', 'get the absolute path of the directory where the gmock test source files are located', 'get the absolute path of a test binary given its executable name for running gmock tests', 'extract the exit status code from an os.system result across Windows and Unix platforms', 'run a subprocess command and capture its output using the gmock test Subprocess utility class', 'set an environment variable for the gmock test process using the SetEnvVar utility function', 'test the Pump ConvertFromPumpSource function to convert meta-programming source code with variables and loops', 'test the Pump StripMetaComments function to remove dollar-dollar meta comments from source', 'test the Pump tool variable declaration and reference capabilities using ConvertFromPumpSource', 'test the Pump tool range and for loop meta-programming features using ConvertFromPumpSource', 'test the Pump tool if elif else conditional branching using ConvertFromPumpSource']
```

Usage

```
{'test_leaked_mock_by_default': 'run the GMockLeakTest to verify leaked mocks are caught by default in ExpectCall and OnCall tests', 'test_leaked_mock_disabled': 'run the GMockLeakTest to verify leaked mocks are not caught when gmock_catch_leaked_mocks is disabled', 'test_leaked_mock_enabled': 'run the GMockLeakTest to verify leaked mocks are caught when gmock_catch_leaked_mocks is explicitly enabled', 'test_leaked_mock_explicit_flag': 'run the GMockLeakTest to verify leaked mocks are caught when gmock_catch_leaked_mocks equals 1', 'test_multiple_leaked_mocks': 'run the GMockLeakTest to verify multiple leaked mock objects are all caught and reported'}
```

## File: facebookresearch_rebel/third_party/googletest/googlemock/test/gmock_output_test.py

Prompts

```
['run the GMockLeakTest to verify leaked mocks are caught by default in ExpectCall and OnCall tests', 'run the GMockLeakTest to verify leaked mocks are not caught when gmock_catch_leaked_mocks is disabled', 'run the GMockLeakTest to verify leaked mocks are caught when gmock_catch_leaked_mocks is explicitly enabled', 'run the GMockLeakTest to verify leaked mocks are caught when gmock_catch_leaked_mocks equals 1', 'run the GMockLeakTest to verify multiple leaked mock objects are all caught and reported', 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'extract a list of test names that leak mock objects from gmock output text', 'run a shell command in a subprocess and capture its stdout as a string', 'get the absolute path of the directory where the gmock test source files are located', 'get the absolute path of a test binary given its executable name for running gmock tests', 'extract the exit status code from an os.system result across Windows and Unix platforms', 'run a subprocess command and capture its output using the gmock test Subprocess utility class', 'set an environment variable for the gmock test process using the SetEnvVar utility function', 'test the Pump ConvertFromPumpSource function to convert meta-programming source code with variables and loops', 'test the Pump StripMetaComments function to remove dollar-dollar meta comments from source', 'test the Pump tool variable declaration and reference capabilities using ConvertFromPumpSource', 'test the Pump tool range and for loop meta-programming features using ConvertFromPumpSource', 'test the Pump tool if elif else conditional branching using ConvertFromPumpSource']
```

Usage

```
{'run_gmock_output_test': 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate_golden_file': 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize_test_output': 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'extract_leaky_tests': 'extract a list of test names that leak mock objects from gmock output text', 'run_shell_command': 'run a shell command in a subprocess and capture its stdout as a string'}
```

## File: facebookresearch_rebel/third_party/googletest/googlemock/test/gmock_test_utils.py

Prompts

```
['run the GMockLeakTest to verify leaked mocks are caught by default in ExpectCall and OnCall tests', 'run the GMockLeakTest to verify leaked mocks are not caught when gmock_catch_leaked_mocks is disabled', 'run the GMockLeakTest to verify leaked mocks are caught when gmock_catch_leaked_mocks is explicitly enabled', 'run the GMockLeakTest to verify leaked mocks are caught when gmock_catch_leaked_mocks equals 1', 'run the GMockLeakTest to verify multiple leaked mock objects are all caught and reported', 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'extract a list of test names that leak mock objects from gmock output text', 'run a shell command in a subprocess and capture its stdout as a string', 'get the absolute path of the directory where the gmock test source files are located', 'get the absolute path of a test binary given its executable name for running gmock tests', 'extract the exit status code from an os.system result across Windows and Unix platforms', 'run a subprocess command and capture its output using the gmock test Subprocess utility class', 'set an environment variable for the gmock test process using the SetEnvVar utility function', 'test the Pump ConvertFromPumpSource function to convert meta-programming source code with variables and loops', 'test the Pump StripMetaComments function to remove dollar-dollar meta comments from source', 'test the Pump tool variable declaration and reference capabilities using ConvertFromPumpSource', 'test the Pump tool range and for loop meta-programming features using ConvertFromPumpSource', 'test the Pump tool if elif else conditional branching using ConvertFromPumpSource']
```

Usage

```
{'get_source_directory': 'get the absolute path of the directory where the gmock test source files are located', 'get_test_executable_path': 'get the absolute path of a test binary given its executable name for running gmock tests', 'get_exit_status': 'extract the exit status code from an os.system result across Windows and Unix platforms', 'run_subprocess': 'run a subprocess command and capture its output using the gmock test Subprocess utility class', 'set_env_var': 'set an environment variable for the gmock test process using the SetEnvVar utility function'}
```

## File: facebookresearch_rebel/third_party/googletest/googlemock/test/pump_test.py

Prompts

```
['run the GMockLeakTest to verify leaked mocks are caught by default in ExpectCall and OnCall tests', 'run the GMockLeakTest to verify leaked mocks are not caught when gmock_catch_leaked_mocks is disabled', 'run the GMockLeakTest to verify leaked mocks are caught when gmock_catch_leaked_mocks is explicitly enabled', 'run the GMockLeakTest to verify leaked mocks are caught when gmock_catch_leaked_mocks equals 1', 'run the GMockLeakTest to verify multiple leaked mock objects are all caught and reported', 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'extract a list of test names that leak mock objects from gmock output text', 'run a shell command in a subprocess and capture its stdout as a string', 'get the absolute path of the directory where the gmock test source files are located', 'get the absolute path of a test binary given its executable name for running gmock tests', 'extract the exit status code from an os.system result across Windows and Unix platforms', 'run a subprocess command and capture its output using the gmock test Subprocess utility class', 'set an environment variable for the gmock test process using the SetEnvVar utility function', 'test the Pump ConvertFromPumpSource function to convert meta-programming source code with variables and loops', 'test the Pump StripMetaComments function to remove dollar-dollar meta comments from source', 'test the Pump tool variable declaration and reference capabilities using ConvertFromPumpSource', 'test the Pump tool range and for loop meta-programming features using ConvertFromPumpSource', 'test the Pump tool if elif else conditional branching using ConvertFromPumpSource']
```

Usage

```
{'test_pump_convert_from_source': 'test the Pump ConvertFromPumpSource function to convert meta-programming source code with variables and loops', 'test_pump_strip_meta_comments': 'test the Pump StripMetaComments function to remove dollar-dollar meta comments from source', 'test_pump_var_declarations': 'test the Pump tool variable declaration and reference capabilities using ConvertFromPumpSource', 'test_pump_range_loops': 'test the Pump tool range and for loop meta-programming features using ConvertFromPumpSource', 'test_pump_conditionals': 'test the Pump tool if elif else conditional branching using ConvertFromPumpSource'}
```

