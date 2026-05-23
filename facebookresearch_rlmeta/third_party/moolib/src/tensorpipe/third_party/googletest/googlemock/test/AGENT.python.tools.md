# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/third_party/moolib/src/tensorpipe/third_party/googletest/googlemock/test/gmock_leak_test.py

Prompts

```
['run the GMockLeakTest to verify leaked mock objects are caught by default', 'run the GMockLeakTest to verify leak detection can be disabled with gmock_catch_leaked_mocks flag', 'run the GMockLeakTest to verify leaked mocks are caught when explicitly enabled', 'run the GMockLeakTest to verify leak detection works with explicit flag value of 1', 'run the GMockLeakTest to verify multiple leaked mock objects are all caught', 'run the gmock output test to verify Google Mock framework text output matches the golden file', 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize Google Test output by removing headers, footers, locations, and memory addresses', 'extract a list of test names that leak mock objects from test output using regex', 'remove all file location info from Google Test program output and replace with FILE colon hash', 'get the absolute path of the directory where gmock test .py files are located', 'get the absolute path of a gmock test binary given its executable name', 'get the exit status code from an os.system command result on Unix or Windows', 'run a subprocess command and capture its output using the Subprocess utility class', 'set an environment variable using the SetEnvVar utility for cross-platform compatibility', 'test that Convert returns empty string when given empty Pump source input', 'test that Convert passes plain C++ code like includes through unchanged', 'test Pump variable declarations using $var and reference them with $name in templates', 'test Pump loop generation using $range and $for to produce comma-separated sequences', 'test StripMetaComments to remove $$ meta comments from Pump source text']
```

Usage

```
{'run_leak_test_default': 'run the GMockLeakTest to verify leaked mock objects are caught by default', 'run_leak_test_disabled': 'run the GMockLeakTest to verify leak detection can be disabled with gmock_catch_leaked_mocks flag', 'run_leak_test_enabled': 'run the GMockLeakTest to verify leaked mocks are caught when explicitly enabled', 'run_leak_test_explicit_flag': 'run the GMockLeakTest to verify leak detection works with explicit flag value of 1', 'run_leak_test_multiple': 'run the GMockLeakTest to verify multiple leaked mock objects are all caught'}
```

## File: facebookresearch_rlmeta/third_party/moolib/src/tensorpipe/third_party/googletest/googlemock/test/gmock_output_test.py

Prompts

```
['run the GMockLeakTest to verify leaked mock objects are caught by default', 'run the GMockLeakTest to verify leak detection can be disabled with gmock_catch_leaked_mocks flag', 'run the GMockLeakTest to verify leaked mocks are caught when explicitly enabled', 'run the GMockLeakTest to verify leak detection works with explicit flag value of 1', 'run the GMockLeakTest to verify multiple leaked mock objects are all caught', 'run the gmock output test to verify Google Mock framework text output matches the golden file', 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize Google Test output by removing headers, footers, locations, and memory addresses', 'extract a list of test names that leak mock objects from test output using regex', 'remove all file location info from Google Test program output and replace with FILE colon hash', 'get the absolute path of the directory where gmock test .py files are located', 'get the absolute path of a gmock test binary given its executable name', 'get the exit status code from an os.system command result on Unix or Windows', 'run a subprocess command and capture its output using the Subprocess utility class', 'set an environment variable using the SetEnvVar utility for cross-platform compatibility', 'test that Convert returns empty string when given empty Pump source input', 'test that Convert passes plain C++ code like includes through unchanged', 'test Pump variable declarations using $var and reference them with $name in templates', 'test Pump loop generation using $range and $for to produce comma-separated sequences', 'test StripMetaComments to remove $$ meta comments from Pump source text']
```

Usage

```
{'run_gmock_output_test': 'run the gmock output test to verify Google Mock framework text output matches the golden file', 'generate_golden_file': 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize_test_output': 'normalize Google Test output by removing headers, footers, locations, and memory addresses', 'extract_leaky_tests': 'extract a list of test names that leak mock objects from test output using regex', 'remove_locations': 'remove all file location info from Google Test program output and replace with FILE colon hash'}
```

## File: facebookresearch_rlmeta/third_party/moolib/src/tensorpipe/third_party/googletest/googlemock/test/gmock_test_utils.py

Prompts

```
['run the GMockLeakTest to verify leaked mock objects are caught by default', 'run the GMockLeakTest to verify leak detection can be disabled with gmock_catch_leaked_mocks flag', 'run the GMockLeakTest to verify leaked mocks are caught when explicitly enabled', 'run the GMockLeakTest to verify leak detection works with explicit flag value of 1', 'run the GMockLeakTest to verify multiple leaked mock objects are all caught', 'run the gmock output test to verify Google Mock framework text output matches the golden file', 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize Google Test output by removing headers, footers, locations, and memory addresses', 'extract a list of test names that leak mock objects from test output using regex', 'remove all file location info from Google Test program output and replace with FILE colon hash', 'get the absolute path of the directory where gmock test .py files are located', 'get the absolute path of a gmock test binary given its executable name', 'get the exit status code from an os.system command result on Unix or Windows', 'run a subprocess command and capture its output using the Subprocess utility class', 'set an environment variable using the SetEnvVar utility for cross-platform compatibility', 'test that Convert returns empty string when given empty Pump source input', 'test that Convert passes plain C++ code like includes through unchanged', 'test Pump variable declarations using $var and reference them with $name in templates', 'test Pump loop generation using $range and $for to produce comma-separated sequences', 'test StripMetaComments to remove $$ meta comments from Pump source text']
```

Usage

```
{'get_source_dir': 'get the absolute path of the directory where gmock test .py files are located', 'get_test_executable_path': 'get the absolute path of a gmock test binary given its executable name', 'get_exit_status': 'get the exit status code from an os.system command result on Unix or Windows', 'run_subprocess': 'run a subprocess command and capture its output using the Subprocess utility class', 'set_env_var': 'set an environment variable using the SetEnvVar utility for cross-platform compatibility'}
```

## File: facebookresearch_rlmeta/third_party/moolib/src/tensorpipe/third_party/googletest/googlemock/test/pump_test.py

Prompts

```
['run the GMockLeakTest to verify leaked mock objects are caught by default', 'run the GMockLeakTest to verify leak detection can be disabled with gmock_catch_leaked_mocks flag', 'run the GMockLeakTest to verify leaked mocks are caught when explicitly enabled', 'run the GMockLeakTest to verify leak detection works with explicit flag value of 1', 'run the GMockLeakTest to verify multiple leaked mock objects are all caught', 'run the gmock output test to verify Google Mock framework text output matches the golden file', 'generate a new golden file by running gmock_output_test.py with the --gengolden flag', 'normalize Google Test output by removing headers, footers, locations, and memory addresses', 'extract a list of test names that leak mock objects from test output using regex', 'remove all file location info from Google Test program output and replace with FILE colon hash', 'get the absolute path of the directory where gmock test .py files are located', 'get the absolute path of a gmock test binary given its executable name', 'get the exit status code from an os.system command result on Unix or Windows', 'run a subprocess command and capture its output using the Subprocess utility class', 'set an environment variable using the SetEnvVar utility for cross-platform compatibility', 'test that Convert returns empty string when given empty Pump source input', 'test that Convert passes plain C++ code like includes through unchanged', 'test Pump variable declarations using $var and reference them with $name in templates', 'test Pump loop generation using $range and $for to produce comma-separated sequences', 'test StripMetaComments to remove $$ meta comments from Pump source text']
```

Usage

```
{'test_pump_convert_empty': 'test that Convert returns empty string when given empty Pump source input', 'test_pump_convert_plain_code': 'test that Convert passes plain C++ code like includes through unchanged', 'test_pump_var_declaration': 'test Pump variable declarations using $var and reference them with $name in templates', 'test_pump_loop_generation': 'test Pump loop generation using $range and $for to produce comma-separated sequences', 'test_strip_meta_comments': 'test StripMetaComments to remove $$ meta comments from Pump source text'}
```

