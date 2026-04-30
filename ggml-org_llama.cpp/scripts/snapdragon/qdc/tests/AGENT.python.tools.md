# Agent Python Tools

- repo: ggml-org/llama.cpp
- repo_uri: https://github.com/ggml-org/llama.cpp

## File: ggml-org_llama.cpp/scripts/snapdragon/qdc/tests/run_backend_ops_posix.py

Prompts

```
['test the backend_ops_htp0 function to run test-backend-ops on HTP0 backend with mxfp4, fp16, or q4_0 type_a', 'run the test-backend-ops posix script via pytest to execute on-device HTP0 backend tests', 'install the test-backend-ops bundle to the device before running backend operations tests', 'run the test-backend-ops adb command with GGML_HEXAGON environment variables on the HTP0 backend', 'write the test-backend-ops stdout output to a qdc log file for test result tracking', 'test llama-completion on CPU, GPU, and NPU backends with the installed GGUF model', 'test llama-bench performance on CPU, GPU, and NPU backends with the installed GGUF model', 'run the session-scoped install fixture to push llama-cli binary and download the GGUF model', 'run all bench and completion tests on CPU, GPU, and NPU backends via pytest', 'run the test suite and generate JUnit XML results for the bench and completion tests', 'run an adb shell command on the Android device and return the exit code and output', 'write a log file to the QDC logs directory on the Android device', 'push the llama_cpp_bundle to the Android device if a check binary is missing', 'create AppiumOptions configured for UiAutomator2 Android device automation', 'get on-device paths for bundle, logs, libraries, and binaries']
```

Usage

```
{'test_backend_ops_htp0': 'test the backend_ops_htp0 function to run test-backend-ops on HTP0 backend with mxfp4, fp16, or q4_0 type_a', 'run_test_backend_ops_posix': 'run the test-backend-ops posix script via pytest to execute on-device HTP0 backend tests', 'install_backend_ops_bundle': 'install the test-backend-ops bundle to the device before running backend operations tests', 'run_adb_test_command': 'run the test-backend-ops adb command with GGML_HEXAGON environment variables on the HTP0 backend', 'write_qdc_test_log': 'write the test-backend-ops stdout output to a qdc log file for test result tracking'}
```

## File: ggml-org_llama.cpp/scripts/snapdragon/qdc/tests/run_bench_tests_posix.py

Prompts

```
['test the backend_ops_htp0 function to run test-backend-ops on HTP0 backend with mxfp4, fp16, or q4_0 type_a', 'run the test-backend-ops posix script via pytest to execute on-device HTP0 backend tests', 'install the test-backend-ops bundle to the device before running backend operations tests', 'run the test-backend-ops adb command with GGML_HEXAGON environment variables on the HTP0 backend', 'write the test-backend-ops stdout output to a qdc log file for test result tracking', 'test llama-completion on CPU, GPU, and NPU backends with the installed GGUF model', 'test llama-bench performance on CPU, GPU, and NPU backends with the installed GGUF model', 'run the session-scoped install fixture to push llama-cli binary and download the GGUF model', 'run all bench and completion tests on CPU, GPU, and NPU backends via pytest', 'run the test suite and generate JUnit XML results for the bench and completion tests', 'run an adb shell command on the Android device and return the exit code and output', 'write a log file to the QDC logs directory on the Android device', 'push the llama_cpp_bundle to the Android device if a check binary is missing', 'create AppiumOptions configured for UiAutomator2 Android device automation', 'get on-device paths for bundle, logs, libraries, and binaries']
```

Usage

```
{'test_llama_completion': 'test llama-completion on CPU, GPU, and NPU backends with the installed GGUF model', 'test_llama_bench': 'test llama-bench performance on CPU, GPU, and NPU backends with the installed GGUF model', 'install_fixture': 'run the session-scoped install fixture to push llama-cli binary and download the GGUF model', 'run_bench_tests_posix': 'run all bench and completion tests on CPU, GPU, and NPU backends via pytest', 'generate_junit_results': 'run the test suite and generate JUnit XML results for the bench and completion tests'}
```

## File: ggml-org_llama.cpp/scripts/snapdragon/qdc/tests/utils.py

Prompts

```
['test the backend_ops_htp0 function to run test-backend-ops on HTP0 backend with mxfp4, fp16, or q4_0 type_a', 'run the test-backend-ops posix script via pytest to execute on-device HTP0 backend tests', 'install the test-backend-ops bundle to the device before running backend operations tests', 'run the test-backend-ops adb command with GGML_HEXAGON environment variables on the HTP0 backend', 'write the test-backend-ops stdout output to a qdc log file for test result tracking', 'test llama-completion on CPU, GPU, and NPU backends with the installed GGUF model', 'test llama-bench performance on CPU, GPU, and NPU backends with the installed GGUF model', 'run the session-scoped install fixture to push llama-cli binary and download the GGUF model', 'run all bench and completion tests on CPU, GPU, and NPU backends via pytest', 'run the test suite and generate JUnit XML results for the bench and completion tests', 'run an adb shell command on the Android device and return the exit code and output', 'write a log file to the QDC logs directory on the Android device', 'push the llama_cpp_bundle to the Android device if a check binary is missing', 'create AppiumOptions configured for UiAutomator2 Android device automation', 'get on-device paths for bundle, logs, libraries, and binaries']
```

Usage

```
{'run_adb_command': 'run an adb shell command on the Android device and return the exit code and output', 'write_qdc_log': 'write a log file to the QDC logs directory on the Android device', 'push_bundle_if_needed': 'push the llama_cpp_bundle to the Android device if a check binary is missing', 'create_appium_options': 'create AppiumOptions configured for UiAutomator2 Android device automation', 'get_device_paths': 'get on-device paths for bundle, logs, libraries, and binaries'}
```

