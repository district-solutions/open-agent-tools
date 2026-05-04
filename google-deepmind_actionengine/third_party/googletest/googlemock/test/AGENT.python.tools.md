# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/third_party/googletest/googlemock/test/gmock_leak_test.py

Prompts

```
['run the GMockLeakTest suite to verify Google Mock catches leaked mock objects by default', 'test that leaked mocks are caught by default using ExpectCall and OnCall test filters', 'test that leaked mocks are not caught when gmock_catch_leaked_mocks flag is set to 0', 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is explicitly enabled', 'test that multiple leaked mock objects are all caught and reported by Google Mock', 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate a new golden file for gmock output test using the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'extract a list of test names that leak mock objects from gmock output', 'convert Windows and Mac line endings to UNIX line endings in test output', 'get the absolute path of the directory where the gmock test python files are located', 'get the absolute path of a gmock test binary given its executable name', 'extract the exit status code from an os.system result across Windows and Unix platforms', 'run a subprocess command and capture its output using the gmock test Subprocess utility', 'set an environment variable for gmock test execution using the SetEnvVar utility']
```

Usage

```
{'run_gmock_leak_tests': 'run the GMockLeakTest suite to verify Google Mock catches leaked mock objects by default', 'test_leaked_mock_default_behavior': 'test that leaked mocks are caught by default using ExpectCall and OnCall test filters', 'test_leaked_mock_disabled': 'test that leaked mocks are not caught when gmock_catch_leaked_mocks flag is set to 0', 'test_leaked_mock_enabled': 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is explicitly enabled', 'test_multiple_leaked_mocks': 'test that multiple leaked mock objects are all caught and reported by Google Mock'}
```

## File: google-deepmind_actionengine/third_party/googletest/googlemock/test/gmock_output_test.py

Prompts

```
['run the GMockLeakTest suite to verify Google Mock catches leaked mock objects by default', 'test that leaked mocks are caught by default using ExpectCall and OnCall test filters', 'test that leaked mocks are not caught when gmock_catch_leaked_mocks flag is set to 0', 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is explicitly enabled', 'test that multiple leaked mock objects are all caught and reported by Google Mock', 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate a new golden file for gmock output test using the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'extract a list of test names that leak mock objects from gmock output', 'convert Windows and Mac line endings to UNIX line endings in test output', 'get the absolute path of the directory where the gmock test python files are located', 'get the absolute path of a gmock test binary given its executable name', 'extract the exit status code from an os.system result across Windows and Unix platforms', 'run a subprocess command and capture its output using the gmock test Subprocess utility', 'set an environment variable for gmock test execution using the SetEnvVar utility']
```

Usage

```
{'run_gmock_output_test': 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate_golden_file': 'generate a new golden file for gmock output test using the --gengolden flag', 'normalize_test_output': 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'extract_leaky_tests': 'extract a list of test names that leak mock objects from gmock output', 'normalize_line_endings': 'convert Windows and Mac line endings to UNIX line endings in test output'}
```

## File: google-deepmind_actionengine/third_party/googletest/googlemock/test/gmock_test_utils.py

Prompts

```
['run the GMockLeakTest suite to verify Google Mock catches leaked mock objects by default', 'test that leaked mocks are caught by default using ExpectCall and OnCall test filters', 'test that leaked mocks are not caught when gmock_catch_leaked_mocks flag is set to 0', 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is explicitly enabled', 'test that multiple leaked mock objects are all caught and reported by Google Mock', 'run the gmock output test to verify Google Mock text output matches the golden file', 'generate a new golden file for gmock output test using the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'extract a list of test names that leak mock objects from gmock output', 'convert Windows and Mac line endings to UNIX line endings in test output', 'get the absolute path of the directory where the gmock test python files are located', 'get the absolute path of a gmock test binary given its executable name', 'extract the exit status code from an os.system result across Windows and Unix platforms', 'run a subprocess command and capture its output using the gmock test Subprocess utility', 'set an environment variable for gmock test execution using the SetEnvVar utility']
```

Usage

```
{'get_source_directory': 'get the absolute path of the directory where the gmock test python files are located', 'get_test_executable_path': 'get the absolute path of a gmock test binary given its executable name', 'get_exit_status': 'extract the exit status code from an os.system result across Windows and Unix platforms', 'run_subprocess': 'run a subprocess command and capture its output using the gmock test Subprocess utility', 'set_env_var': 'set an environment variable for gmock test execution using the SetEnvVar utility'}
```

