# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/test/cpp/qps/gen_build_yaml.py

Prompts

```
['generate a YAML test configuration for gRPC QPS scenarios across scalable and inproc categories', 'mutate a QPS scenario JSON to reduce warmup and benchmark seconds for faster test execution', 'create a JSON string from a QPS scenario after removing non-proto fields and mutating parameters', 'calculate the number of threads required for a client or server in a QPS scenario', 'estimate the CPU cost for a QPS scenario based on client and server thread requirements', 'run generate_args to extract json_run_localhost scenarios from gen_build_yaml and write them to json_run_localhost_scenarios.bzl', 'review generate_args to understand how it filters and serializes localhost test scenarios into a Bazel file', 'refactor generate_args to use Python 3 compatible string encoding instead of encode ascii ignore', 'summarize generate_args which filters gen_build_yaml tests for json_run_localhost and writes a Bazel scenarios file', 'test generate_args to verify it correctly extracts and serializes localhost scenarios from the build YAML', 'run generate_args to produce qps_json_driver_scenarios.bzl from the build YAML test scenarios']
```

Usage

```
{'generate_yaml': 'generate a YAML test configuration for gRPC QPS scenarios across scalable and inproc categories', 'mutate_scenario': 'mutate a QPS scenario JSON to reduce warmup and benchmark seconds for faster test execution', 'scenario_json_string': 'create a JSON string from a QPS scenario after removing non-proto fields and mutating parameters', 'threads_required': 'calculate the number of threads required for a client or server in a QPS scenario', 'guess_cpu': 'estimate the CPU cost for a QPS scenario based on client and server thread requirements'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/test/cpp/qps/json_run_localhost_scenario_gen.py

Prompts

```
['generate a YAML test configuration for gRPC QPS scenarios across scalable and inproc categories', 'mutate a QPS scenario JSON to reduce warmup and benchmark seconds for faster test execution', 'create a JSON string from a QPS scenario after removing non-proto fields and mutating parameters', 'calculate the number of threads required for a client or server in a QPS scenario', 'estimate the CPU cost for a QPS scenario based on client and server thread requirements', 'run generate_args to extract json_run_localhost scenarios from gen_build_yaml and write them to json_run_localhost_scenarios.bzl', 'review generate_args to understand how it filters and serializes localhost test scenarios into a Bazel file', 'refactor generate_args to use Python 3 compatible string encoding instead of encode ascii ignore', 'summarize generate_args which filters gen_build_yaml tests for json_run_localhost and writes a Bazel scenarios file', 'test generate_args to verify it correctly extracts and serializes localhost scenarios from the build YAML', 'run generate_args to produce qps_json_driver_scenarios.bzl from the build YAML test scenarios']
```

Usage

```
{'generate_args': 'run generate_args to extract json_run_localhost scenarios from gen_build_yaml and write them to json_run_localhost_scenarios.bzl', 'review_generate_args': 'review generate_args to understand how it filters and serializes localhost test scenarios into a Bazel file', 'refactor_generate_args': 'refactor generate_args to use Python 3 compatible string encoding instead of encode ascii ignore', 'summarize_generate_args': 'summarize generate_args which filters gen_build_yaml tests for json_run_localhost and writes a Bazel scenarios file', 'test_generate_args': 'test generate_args to verify it correctly extracts and serializes localhost scenarios from the build YAML'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/test/cpp/qps/qps_json_driver_scenario_gen.py

Prompts

```
['generate a YAML test configuration for gRPC QPS scenarios across scalable and inproc categories', 'mutate a QPS scenario JSON to reduce warmup and benchmark seconds for faster test execution', 'create a JSON string from a QPS scenario after removing non-proto fields and mutating parameters', 'calculate the number of threads required for a client or server in a QPS scenario', 'estimate the CPU cost for a QPS scenario based on client and server thread requirements', 'run generate_args to extract json_run_localhost scenarios from gen_build_yaml and write them to json_run_localhost_scenarios.bzl', 'review generate_args to understand how it filters and serializes localhost test scenarios into a Bazel file', 'refactor generate_args to use Python 3 compatible string encoding instead of encode ascii ignore', 'summarize generate_args which filters gen_build_yaml tests for json_run_localhost and writes a Bazel scenarios file', 'test generate_args to verify it correctly extracts and serializes localhost scenarios from the build YAML', 'run generate_args to produce qps_json_driver_scenarios.bzl from the build YAML test scenarios']
```

Usage

```
{'generate_qps_scenarios_bzl': 'run generate_args to produce qps_json_driver_scenarios.bzl from the build YAML test scenarios', 'review_generate_args': 'review the generate_args function that filters qps_json_driver scenarios and writes a Bazel .bzl file', 'refactor_generate_args': 'refactor generate_args to use Python 3 encoding instead of encode ascii ignore calls', 'summarize_generate_args': 'summarize the generate_args function that extracts and serializes QPS driver scenarios from gen_build_yaml', 'test_generate_args': 'test the generate_args function to verify it correctly writes QPS_JSON_DRIVER_SCENARIOS to the .bzl output file'}
```

