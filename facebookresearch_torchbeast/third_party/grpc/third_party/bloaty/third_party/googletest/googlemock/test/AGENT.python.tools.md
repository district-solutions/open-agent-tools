# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/third_party/bloaty/third_party/googletest/googlemock/test/gmock_leak_test.py

Prompts

```
['run the GMockLeakTest suite to verify leaked mock objects are caught by Google Mock', 'test that leaked mock objects are caught by default using ExpectCall and OnCall filters', 'test that leaked mocks are not caught when gmock_catch_leaked_mocks flag is set to 0', 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is explicitly enabled', 'test that multiple leaked mock objects are all caught when leak detection is enabled', 'normalize Google Test output by removing headers, footers, locations, and memory addresses', 'remove Google Test result report header and footer lines from test output text', 'remove file location info like FILE_NAME:LINE_NUMBER from Google Test program output', 'find and return a list of test names that leak mock objects from output text', 'run the gmock output test command and compare normalized output against a golden file', 'get the absolute path of the directory where the gmock test .py files are located', 'get the absolute path of a gmock test binary given its executable name', 'extract the exit status code from an os.system result on Unix or Windows', 'run a subprocess command and capture its output using the Subprocess utility class', 'set an environment variable using the SetEnvVar utility for gmock test configuration']
```

Usage

```
{'run_gmock_leak_test': 'run the GMockLeakTest suite to verify leaked mock objects are caught by Google Mock', 'test_catches_leaked_mock_by_default': 'test that leaked mock objects are caught by default using ExpectCall and OnCall filters', 'test_does_not_catch_leaked_mock_when_disabled': 'test that leaked mocks are not caught when gmock_catch_leaked_mocks flag is set to 0', 'test_catches_leaked_mock_when_enabled': 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is explicitly enabled', 'test_catches_multiple_leaked_mocks': 'test that multiple leaked mock objects are all caught when leak detection is enabled'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/bloaty/third_party/googletest/googlemock/test/gmock_output_test.py

Prompts

```
['run the GMockLeakTest suite to verify leaked mock objects are caught by Google Mock', 'test that leaked mock objects are caught by default using ExpectCall and OnCall filters', 'test that leaked mocks are not caught when gmock_catch_leaked_mocks flag is set to 0', 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is explicitly enabled', 'test that multiple leaked mock objects are all caught when leak detection is enabled', 'normalize Google Test output by removing headers, footers, locations, and memory addresses', 'remove Google Test result report header and footer lines from test output text', 'remove file location info like FILE_NAME:LINE_NUMBER from Google Test program output', 'find and return a list of test names that leak mock objects from output text', 'run the gmock output test command and compare normalized output against a golden file', 'get the absolute path of the directory where the gmock test .py files are located', 'get the absolute path of a gmock test binary given its executable name', 'extract the exit status code from an os.system result on Unix or Windows', 'run a subprocess command and capture its output using the Subprocess utility class', 'set an environment variable using the SetEnvVar utility for gmock test configuration']
```

Usage

```
{'normalize_test_output': 'normalize Google Test output by removing headers, footers, locations, and memory addresses', 'remove_report_header_footer': 'remove Google Test result report header and footer lines from test output text', 'remove_file_locations': 'remove file location info like FILE_NAME:LINE_NUMBER from Google Test program output', 'find_leaky_mock_tests': 'find and return a list of test names that leak mock objects from output text', 'run_gmock_output_test': 'run the gmock output test command and compare normalized output against a golden file'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/bloaty/third_party/googletest/googlemock/test/gmock_test_utils.py

Prompts

```
['run the GMockLeakTest suite to verify leaked mock objects are caught by Google Mock', 'test that leaked mock objects are caught by default using ExpectCall and OnCall filters', 'test that leaked mocks are not caught when gmock_catch_leaked_mocks flag is set to 0', 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is explicitly enabled', 'test that multiple leaked mock objects are all caught when leak detection is enabled', 'normalize Google Test output by removing headers, footers, locations, and memory addresses', 'remove Google Test result report header and footer lines from test output text', 'remove file location info like FILE_NAME:LINE_NUMBER from Google Test program output', 'find and return a list of test names that leak mock objects from output text', 'run the gmock output test command and compare normalized output against a golden file', 'get the absolute path of the directory where the gmock test .py files are located', 'get the absolute path of a gmock test binary given its executable name', 'extract the exit status code from an os.system result on Unix or Windows', 'run a subprocess command and capture its output using the Subprocess utility class', 'set an environment variable using the SetEnvVar utility for gmock test configuration']
```

Usage

```
{'get_source_dir': 'get the absolute path of the directory where the gmock test .py files are located', 'get_test_executable_path': 'get the absolute path of a gmock test binary given its executable name', 'get_exit_status': 'extract the exit status code from an os.system result on Unix or Windows', 'run_subprocess': 'run a subprocess command and capture its output using the Subprocess utility class', 'set_env_var': 'set an environment variable using the SetEnvVar utility for gmock test configuration'}
```

