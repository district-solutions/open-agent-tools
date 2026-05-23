# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/test/cpp/qps/gen_build_yaml.py

Prompts

```
['generate a YAML dict of QPS test cases for scalable, inproc, and low thread count scenarios', 'mutate a scenario JSON to reduce warmup and benchmark seconds for faster test times', 'serialize a scenario JSON to a JSON string after removing non-proto fields', 'calculate the number of threads required for a client or server in a QPS scenario', 'guess the CPU cost for a QPS scenario based on client and server thread counts', 'run generate_args to extract json_run_localhost scenarios and write them to a .bzl file', 'generate a Bazel .bzl file containing JSON_RUN_LOCALHOST_SCENARIOS from the gen_build_yaml test set', 'extract json_run_localhost test scenarios from the generated YAML and deserialize their JSON args', 'review the generate_args function that filters scenarios by name and writes serialized output to a .bzl file', 'refactor generate_args to use if __name__ equals __main__ guard and modern Python 3 encoding', 'generate a Bazel scenarios file by filtering qps_json_driver test scenarios and serializing them', 'extract the third argument from qps_json_driver test scenarios and deserialize JSON scenario data']
```

Usage

```
{'generate_yaml_test_cases': 'generate a YAML dict of QPS test cases for scalable, inproc, and low thread count scenarios', 'mutate_scenario_parameters': 'mutate a scenario JSON to reduce warmup and benchmark seconds for faster test times', 'scenario_json_string_serialize': 'serialize a scenario JSON to a JSON string after removing non-proto fields', 'threads_required_calculate': 'calculate the number of threads required for a client or server in a QPS scenario', 'guess_cpu_cost': 'guess the CPU cost for a QPS scenario based on client and server thread counts'}
```

## File: facebookresearch_torchbeast/third_party/grpc/test/cpp/qps/json_run_localhost_scenario_gen.py

Prompts

```
['generate a YAML dict of QPS test cases for scalable, inproc, and low thread count scenarios', 'mutate a scenario JSON to reduce warmup and benchmark seconds for faster test times', 'serialize a scenario JSON to a JSON string after removing non-proto fields', 'calculate the number of threads required for a client or server in a QPS scenario', 'guess the CPU cost for a QPS scenario based on client and server thread counts', 'run generate_args to extract json_run_localhost scenarios and write them to a .bzl file', 'generate a Bazel .bzl file containing JSON_RUN_LOCALHOST_SCENARIOS from the gen_build_yaml test set', 'extract json_run_localhost test scenarios from the generated YAML and deserialize their JSON args', 'review the generate_args function that filters scenarios by name and writes serialized output to a .bzl file', 'refactor generate_args to use if __name__ equals __main__ guard and modern Python 3 encoding', 'generate a Bazel scenarios file by filtering qps_json_driver test scenarios and serializing them', 'extract the third argument from qps_json_driver test scenarios and deserialize JSON scenario data']
```

Usage

```
{'run_generate_args': 'run generate_args to extract json_run_localhost scenarios and write them to a .bzl file', 'generate_localhost_scenarios_bzl': 'generate a Bazel .bzl file containing JSON_RUN_LOCALHOST_SCENARIOS from the gen_build_yaml test set', 'extract_json_run_localhost_tests': 'extract json_run_localhost test scenarios from the generated YAML and deserialize their JSON args', 'review_generate_args': 'review the generate_args function that filters scenarios by name and writes serialized output to a .bzl file', 'refactor_generate_args': 'refactor generate_args to use if __name__ equals __main__ guard and modern Python 3 encoding'}
```

## File: facebookresearch_torchbeast/third_party/grpc/test/cpp/qps/qps_json_driver_scenario_gen.py

Prompts

```
['generate a YAML dict of QPS test cases for scalable, inproc, and low thread count scenarios', 'mutate a scenario JSON to reduce warmup and benchmark seconds for faster test times', 'serialize a scenario JSON to a JSON string after removing non-proto fields', 'calculate the number of threads required for a client or server in a QPS scenario', 'guess the CPU cost for a QPS scenario based on client and server thread counts', 'run generate_args to extract json_run_localhost scenarios and write them to a .bzl file', 'generate a Bazel .bzl file containing JSON_RUN_LOCALHOST_SCENARIOS from the gen_build_yaml test set', 'extract json_run_localhost test scenarios from the generated YAML and deserialize their JSON args', 'review the generate_args function that filters scenarios by name and writes serialized output to a .bzl file', 'refactor generate_args to use if __name__ equals __main__ guard and modern Python 3 encoding', 'generate a Bazel scenarios file by filtering qps_json_driver test scenarios and serializing them', 'extract the third argument from qps_json_driver test scenarios and deserialize JSON scenario data']
```

Usage

```
{'run_generate_args': 'run generate_args to extract qps_json_driver scenarios from gen_build_yaml and write qps_json_driver_scenarios.bzl', 'generate_qps_scenarios_bzl': 'generate a Bazel scenarios file by filtering qps_json_driver test scenarios and serializing them', 'extract_qps_json_driver_args': 'extract the third argument from qps_json_driver test scenarios and deserialize JSON scenario data', 'review_generate_args': 'review the generate_args function that filters test scenarios and writes a Bazel scenarios file', 'refactor_generate_args': 'refactor generate_args to use Python 3 encoding instead of Python 2 ascii encode calls'}
```

