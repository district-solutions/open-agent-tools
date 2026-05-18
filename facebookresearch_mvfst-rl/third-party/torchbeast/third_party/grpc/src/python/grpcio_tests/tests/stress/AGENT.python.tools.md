# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/src/python/grpcio_tests/tests/stress/client.py

Prompts

```
['run a gRPC stress test client against specified server addresses with configurable test cases', 'parse a comma separated list of test case names and weights into a dictionary', 'create a gRPC channel to a target server with optional TLS and test CA support', 'configure command line arguments for the gRPC stress test client including server addresses and test duration', 'start a gRPC metrics server on a specified port to collect histogram data from test runners', 'build a gRPC MetricsServer to publish stress test QPS data as gauge metrics', 'create a MetricsServer instance with a histogram to track queries per second', 'test the MetricsServer GetAllGauges method to return all gauge responses with QPS data', 'test the MetricsServer GetGauge method to return a specific gauge by name', 'review the MetricsServer _get_qps method that calculates QPS from histogram count and time delta', 'run a TestRunner thread that sends random weighted gRPC requests to a TestService stub', 'create a generator that yields test cases based on their assigned weights for load testing', 'test the TestRunner run method to verify it sends requests and records latency in a histogram', 'review the TestRunner exception handling that catches errors and puts them on an exception queue', 'refactor the weighted test case generator to use Python 3 dict values instead of itervalues']
```

Usage

```
{'run_stress_test': 'run a gRPC stress test client against specified server addresses with configurable test cases', 'parse_weighted_test_cases': 'parse a comma separated list of test case names and weights into a dictionary', 'get_grpc_channel': 'create a gRPC channel to a target server with optional TLS and test CA support', 'configure_test_arguments': 'configure command line arguments for the gRPC stress test client including server addresses and test duration', 'start_metrics_server': 'start a gRPC metrics server on a specified port to collect histogram data from test runners'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/src/python/grpcio_tests/tests/stress/metrics_server.py

Prompts

```
['run a gRPC stress test client against specified server addresses with configurable test cases', 'parse a comma separated list of test case names and weights into a dictionary', 'create a gRPC channel to a target server with optional TLS and test CA support', 'configure command line arguments for the gRPC stress test client including server addresses and test duration', 'start a gRPC metrics server on a specified port to collect histogram data from test runners', 'build a gRPC MetricsServer to publish stress test QPS data as gauge metrics', 'create a MetricsServer instance with a histogram to track queries per second', 'test the MetricsServer GetAllGauges method to return all gauge responses with QPS data', 'test the MetricsServer GetGauge method to return a specific gauge by name', 'review the MetricsServer _get_qps method that calculates QPS from histogram count and time delta', 'run a TestRunner thread that sends random weighted gRPC requests to a TestService stub', 'create a generator that yields test cases based on their assigned weights for load testing', 'test the TestRunner run method to verify it sends requests and records latency in a histogram', 'review the TestRunner exception handling that catches errors and puts them on an exception queue', 'refactor the weighted test case generator to use Python 3 dict values instead of itervalues']
```

Usage

```
{'build_metrics_server': 'build a gRPC MetricsServer to publish stress test QPS data as gauge metrics', 'create_MetricsServer': 'create a MetricsServer instance with a histogram to track queries per second', 'test_GetAllGauges': 'test the MetricsServer GetAllGauges method to return all gauge responses with QPS data', 'test_GetGauge': 'test the MetricsServer GetGauge method to return a specific gauge by name', 'review_get_qps': 'review the MetricsServer _get_qps method that calculates QPS from histogram count and time delta'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/src/python/grpcio_tests/tests/stress/test_runner.py

Prompts

```
['run a gRPC stress test client against specified server addresses with configurable test cases', 'parse a comma separated list of test case names and weights into a dictionary', 'create a gRPC channel to a target server with optional TLS and test CA support', 'configure command line arguments for the gRPC stress test client including server addresses and test duration', 'start a gRPC metrics server on a specified port to collect histogram data from test runners', 'build a gRPC MetricsServer to publish stress test QPS data as gauge metrics', 'create a MetricsServer instance with a histogram to track queries per second', 'test the MetricsServer GetAllGauges method to return all gauge responses with QPS data', 'test the MetricsServer GetGauge method to return a specific gauge by name', 'review the MetricsServer _get_qps method that calculates QPS from histogram count and time delta', 'run a TestRunner thread that sends random weighted gRPC requests to a TestService stub', 'create a generator that yields test cases based on their assigned weights for load testing', 'test the TestRunner run method to verify it sends requests and records latency in a histogram', 'review the TestRunner exception handling that catches errors and puts them on an exception queue', 'refactor the weighted test case generator to use Python 3 dict values instead of itervalues']
```

Usage

```
{'run_TestRunner': 'run a TestRunner thread that sends random weighted gRPC requests to a TestService stub', 'create_weighted_test_case_generator': 'create a generator that yields test cases based on their assigned weights for load testing', 'test_TestRunner_run': 'test the TestRunner run method to verify it sends requests and records latency in a histogram', 'review_TestRunner_exception_handling': 'review the TestRunner exception handling that catches errors and puts them on an exception queue', 'refactor_weighted_test_case_generator': 'refactor the weighted test case generator to use Python 3 dict values instead of itervalues'}
```

