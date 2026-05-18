# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/bloaty/third_party/googletest/googlemock/test/gmock_leak_test.py

Prompts

```
['test that Google Mock catches leaked mock objects by default without any flags', 'test that leaked mocks are not caught when gmock_catch_leaked_mocks is set to 0', 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is enabled', 'test that leaked mocks are caught when gmock_catch_leaked_mocks is explicitly set to 1', 'test that Google Mock catches multiple leaked mock objects in a single test run', 'run the gmock output test suite and compare normalized output against the golden file', 'generate the golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'extract a list of test names that leak mock objects from gmock output', 'remove file location info from Google Test program output and replace with FILE:#:', 'run GetSourceDir to return the absolute path of the directory where Python source files are located', 'run GetTestExecutablePath with an executable name to get the absolute path of the test binary', 'run GetExitStatus with an os.system result code to extract the exit status across platforms', 'run SetEnvVar to set an environment variable for test execution', 'run Main to execute the Google Mock unit test suite']
```

Usage

```
{'test_leaked_mock_by_default': 'test that Google Mock catches leaked mock objects by default without any flags', 'test_leaked_mock_disabled': 'test that leaked mocks are not caught when gmock_catch_leaked_mocks is set to 0', 'test_leaked_mock_enabled': 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is enabled', 'test_leaked_mock_explicit_flag': 'test that leaked mocks are caught when gmock_catch_leaked_mocks is explicitly set to 1', 'test_multiple_leaked_mocks': 'test that Google Mock catches multiple leaked mock objects in a single test run'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/bloaty/third_party/googletest/googlemock/test/gmock_output_test.py

Prompts

```
['test that Google Mock catches leaked mock objects by default without any flags', 'test that leaked mocks are not caught when gmock_catch_leaked_mocks is set to 0', 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is enabled', 'test that leaked mocks are caught when gmock_catch_leaked_mocks is explicitly set to 1', 'test that Google Mock catches multiple leaked mock objects in a single test run', 'run the gmock output test suite and compare normalized output against the golden file', 'generate the golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'extract a list of test names that leak mock objects from gmock output', 'remove file location info from Google Test program output and replace with FILE:#:', 'run GetSourceDir to return the absolute path of the directory where Python source files are located', 'run GetTestExecutablePath with an executable name to get the absolute path of the test binary', 'run GetExitStatus with an os.system result code to extract the exit status across platforms', 'run SetEnvVar to set an environment variable for test execution', 'run Main to execute the Google Mock unit test suite']
```

Usage

```
{'run_gmock_output_test': 'run the gmock output test suite and compare normalized output against the golden file', 'generate_golden_file': 'generate the golden file by running gmock_output_test.py with the --gengolden flag', 'normalize_test_output': 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'extract_leaky_tests': 'extract a list of test names that leak mock objects from gmock output', 'remove_file_locations': 'remove file location info from Google Test program output and replace with FILE:#:'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/bloaty/third_party/googletest/googlemock/test/gmock_test_utils.py

Prompts

```
['test that Google Mock catches leaked mock objects by default without any flags', 'test that leaked mocks are not caught when gmock_catch_leaked_mocks is set to 0', 'test that leaked mocks are caught when gmock_catch_leaked_mocks flag is enabled', 'test that leaked mocks are caught when gmock_catch_leaked_mocks is explicitly set to 1', 'test that Google Mock catches multiple leaked mock objects in a single test run', 'run the gmock output test suite and compare normalized output against the golden file', 'generate the golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, and memory addresses', 'extract a list of test names that leak mock objects from gmock output', 'remove file location info from Google Test program output and replace with FILE:#:', 'run GetSourceDir to return the absolute path of the directory where Python source files are located', 'run GetTestExecutablePath with an executable name to get the absolute path of the test binary', 'run GetExitStatus with an os.system result code to extract the exit status across platforms', 'run SetEnvVar to set an environment variable for test execution', 'run Main to execute the Google Mock unit test suite']
```

Usage

```
{'run_GetSourceDir': 'run GetSourceDir to return the absolute path of the directory where Python source files are located', 'run_GetTestExecutablePath': 'run GetTestExecutablePath with an executable name to get the absolute path of the test binary', 'run_GetExitStatus': 'run GetExitStatus with an os.system result code to extract the exit status across platforms', 'run_SetEnvVar': 'run SetEnvVar to set an environment variable for test execution', 'run_Main': 'run Main to execute the Google Mock unit test suite'}
```

