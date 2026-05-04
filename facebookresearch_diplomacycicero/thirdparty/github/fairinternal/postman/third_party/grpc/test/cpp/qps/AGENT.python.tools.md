# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/test/cpp/qps/gen_build_yaml.py

Prompts

```
['generate a YAML test configuration for gRPC QPS scenarios with scalable, inproc, and low thread count test entries', 'mutate a QPS scenario JSON to reduce warmup and benchmark seconds for faster test execution', 'calculate the number of threads required for a client or server in a QPS scenario', 'guess the CPU cost for a QPS scenario based on client and server thread requirements', 'check if gcov should be excluded from configs when client channels exceed 100', 'generate a Bazel scenarios file by filtering json_run_localhost test scenarios from the gRPC QPS benchmark YAML', 'run the generate_args function to produce json_run_localhost_scenarios.bzl from the gRPC benchmark test suite', 'review the generate_args function that filters and serializes gRPC localhost QPS scenarios into a Bazel file', 'refactor the generate_args function to use Python 3 compatible encoding instead of Python 2.7 byte strings', 'summarize the generate_args function which extracts json_run_localhost scenarios and writes them to a Bazel .bzl file', 'run generate_args to produce qps_json_driver_scenarios.bzl from gen_build_yaml test scenarios', 'filter test scenarios by name qps_json_driver from the generated YAML test set', 'deserialize JSON scenario arguments extracted from qps_json_driver test entries', 'serialize deserialized scenarios into a Bazel build file with QPS_JSON_DRIVER_SCENARIOS']
```

Usage

```
{'generate_yaml': 'generate a YAML test configuration for gRPC QPS scenarios with scalable, inproc, and low thread count test entries', 'mutate_scenario': 'mutate a QPS scenario JSON to reduce warmup and benchmark seconds for faster test execution', 'threads_required': 'calculate the number of threads required for a client or server in a QPS scenario', 'guess_cpu': 'guess the CPU cost for a QPS scenario based on client and server thread requirements', 'maybe_exclude_gcov': 'check if gcov should be excluded from configs when client channels exceed 100'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/test/cpp/qps/json_run_localhost_scenario_gen.py

Prompts

```
['generate a YAML test configuration for gRPC QPS scenarios with scalable, inproc, and low thread count test entries', 'mutate a QPS scenario JSON to reduce warmup and benchmark seconds for faster test execution', 'calculate the number of threads required for a client or server in a QPS scenario', 'guess the CPU cost for a QPS scenario based on client and server thread requirements', 'check if gcov should be excluded from configs when client channels exceed 100', 'generate a Bazel scenarios file by filtering json_run_localhost test scenarios from the gRPC QPS benchmark YAML', 'run the generate_args function to produce json_run_localhost_scenarios.bzl from the gRPC benchmark test suite', 'review the generate_args function that filters and serializes gRPC localhost QPS scenarios into a Bazel file', 'refactor the generate_args function to use Python 3 compatible encoding instead of Python 2.7 byte strings', 'summarize the generate_args function which extracts json_run_localhost scenarios and writes them to a Bazel .bzl file', 'run generate_args to produce qps_json_driver_scenarios.bzl from gen_build_yaml test scenarios', 'filter test scenarios by name qps_json_driver from the generated YAML test set', 'deserialize JSON scenario arguments extracted from qps_json_driver test entries', 'serialize deserialized scenarios into a Bazel build file with QPS_JSON_DRIVER_SCENARIOS']
```

Usage

```
{'generate_args': 'generate a Bazel scenarios file by filtering json_run_localhost test scenarios from the gRPC QPS benchmark YAML', 'run_generate_args': 'run the generate_args function to produce json_run_localhost_scenarios.bzl from the gRPC benchmark test suite', 'review_generate_args': 'review the generate_args function that filters and serializes gRPC localhost QPS scenarios into a Bazel file', 'refactor_generate_args': 'refactor the generate_args function to use Python 3 compatible encoding instead of Python 2.7 byte strings', 'summarize_generate_args': 'summarize the generate_args function which extracts json_run_localhost scenarios and writes them to a Bazel .bzl file'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/test/cpp/qps/qps_json_driver_scenario_gen.py

Prompts

```
['generate a YAML test configuration for gRPC QPS scenarios with scalable, inproc, and low thread count test entries', 'mutate a QPS scenario JSON to reduce warmup and benchmark seconds for faster test execution', 'calculate the number of threads required for a client or server in a QPS scenario', 'guess the CPU cost for a QPS scenario based on client and server thread requirements', 'check if gcov should be excluded from configs when client channels exceed 100', 'generate a Bazel scenarios file by filtering json_run_localhost test scenarios from the gRPC QPS benchmark YAML', 'run the generate_args function to produce json_run_localhost_scenarios.bzl from the gRPC benchmark test suite', 'review the generate_args function that filters and serializes gRPC localhost QPS scenarios into a Bazel file', 'refactor the generate_args function to use Python 3 compatible encoding instead of Python 2.7 byte strings', 'summarize the generate_args function which extracts json_run_localhost scenarios and writes them to a Bazel .bzl file', 'run generate_args to produce qps_json_driver_scenarios.bzl from gen_build_yaml test scenarios', 'filter test scenarios by name qps_json_driver from the generated YAML test set', 'deserialize JSON scenario arguments extracted from qps_json_driver test entries', 'serialize deserialized scenarios into a Bazel build file with QPS_JSON_DRIVER_SCENARIOS']
```

Usage

```
{'generate_qps_json_driver_scenarios_bzl': 'run generate_args to produce qps_json_driver_scenarios.bzl from gen_build_yaml test scenarios', 'filter_qps_json_driver_tests': 'filter test scenarios by name qps_json_driver from the generated YAML test set', 'deserialize_scenario_json_args': 'deserialize JSON scenario arguments extracted from qps_json_driver test entries', 'serialize_scenarios_to_bzl': 'serialize deserialized scenarios into a Bazel build file with QPS_JSON_DRIVER_SCENARIOS', 'review_generate_args': 'review generate_args which filters, deserializes, and writes QPS JSON driver scenarios to a .bzl file'}
```

