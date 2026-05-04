# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/googletest/googlemock/test/gmock_leak_test.py

Prompts

```
['run the GMockLeakTest to verify leaked mocks are caught by default', 'run the test to verify leaked mocks are ignored when catch flag is disabled', 'run the test to verify leaked mocks are caught when catch flag is enabled', 'run the test to verify leaked mocks are caught with explicit flag value of 1', 'run the test to verify multiple leaked mocks are all caught at once', 'run the gmock output test to verify Google C++ Mocking Framework text output matches the golden file', 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, memory addresses, and leaky test names', 'remove Google Test result report header and footer lines from test output using regex substitution', 'extract a list of test names that leak mock objects from gmock test output using regex findall', 'get the absolute path of the directory where gmock test .py files are located', 'get the absolute path of a gmock test binary given its executable name', 'extract the exit status code from an os.system result across Windows and Unix platforms', 'run a subprocess command and capture its output using the Subprocess utility class', 'run the gmock unit test suite by calling the Main entry point function']
```

Usage

```
{'run_GMockLeakTest_testCatchesLeakedMockByDefault': 'run the GMockLeakTest to verify leaked mocks are caught by default', 'run_GMockLeakTest_testDoesNotCatchLeakedMockWhenDisabled': 'run the test to verify leaked mocks are ignored when catch flag is disabled', 'run_GMockLeakTest_testCatchesLeakedMockWhenEnabled': 'run the test to verify leaked mocks are caught when catch flag is enabled', 'run_GMockLeakTest_testCatchesLeakedMockWhenEnabledWithExplictFlagValue': 'run the test to verify leaked mocks are caught with explicit flag value of 1', 'run_GMockLeakTest_testCatchesMultipleLeakedMocks': 'run the test to verify multiple leaked mocks are all caught at once'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/googletest/googlemock/test/gmock_output_test.py

Prompts

```
['run the GMockLeakTest to verify leaked mocks are caught by default', 'run the test to verify leaked mocks are ignored when catch flag is disabled', 'run the test to verify leaked mocks are caught when catch flag is enabled', 'run the test to verify leaked mocks are caught with explicit flag value of 1', 'run the test to verify multiple leaked mocks are all caught at once', 'run the gmock output test to verify Google C++ Mocking Framework text output matches the golden file', 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, memory addresses, and leaky test names', 'remove Google Test result report header and footer lines from test output using regex substitution', 'extract a list of test names that leak mock objects from gmock test output using regex findall', 'get the absolute path of the directory where gmock test .py files are located', 'get the absolute path of a gmock test binary given its executable name', 'extract the exit status code from an os.system result across Windows and Unix platforms', 'run a subprocess command and capture its output using the Subprocess utility class', 'run the gmock unit test suite by calling the Main entry point function']
```

Usage

```
{'run_gmock_output_test': 'run the gmock output test to verify Google C++ Mocking Framework text output matches the golden file', 'generate_golden_file': 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize_test_output': 'normalize gmock test output by removing headers, footers, locations, memory addresses, and leaky test names', 'remove_report_header_and_footer': 'remove Google Test result report header and footer lines from test output using regex substitution', 'get_leaky_tests': 'extract a list of test names that leak mock objects from gmock test output using regex findall'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/googletest/googlemock/test/gmock_test_utils.py

Prompts

```
['run the GMockLeakTest to verify leaked mocks are caught by default', 'run the test to verify leaked mocks are ignored when catch flag is disabled', 'run the test to verify leaked mocks are caught when catch flag is enabled', 'run the test to verify leaked mocks are caught with explicit flag value of 1', 'run the test to verify multiple leaked mocks are all caught at once', 'run the gmock output test to verify Google C++ Mocking Framework text output matches the golden file', 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize gmock test output by removing headers, footers, locations, memory addresses, and leaky test names', 'remove Google Test result report header and footer lines from test output using regex substitution', 'extract a list of test names that leak mock objects from gmock test output using regex findall', 'get the absolute path of the directory where gmock test .py files are located', 'get the absolute path of a gmock test binary given its executable name', 'extract the exit status code from an os.system result across Windows and Unix platforms', 'run a subprocess command and capture its output using the Subprocess utility class', 'run the gmock unit test suite by calling the Main entry point function']
```

Usage

```
{'get_source_directory': 'get the absolute path of the directory where gmock test .py files are located', 'get_test_executable_path': 'get the absolute path of a gmock test binary given its executable name', 'get_exit_status': 'extract the exit status code from an os.system result across Windows and Unix platforms', 'run_subprocess': 'run a subprocess command and capture its output using the Subprocess utility class', 'run_main_tests': 'run the gmock unit test suite by calling the Main entry point function'}
```

