# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_tests/tests/stress/client.py

Prompts

```
['run the gRPC Python stress test client against specified server addresses with weighted test cases', 'run the stress test with parsed arguments including server addresses, test cases, and duration', 'create a gRPC channel to a target server with optional TLS and test CA support', 'parse a comma separated string of test case names and weights into a dictionary', 'build an argparse parser for the gRPC stress test client with server and test configuration options', 'build a python module to create a gRPC MetricsServer that publishes stress test QPS data', 'create a MetricsServer instance with a histogram to track queries per second for stress testing', 'test the MetricsServer GetAllGauges method to return all gauge responses including python_overall_qps', 'test the MetricsServer GetGauge method to return a specific gauge by name or raise an exception', 'review the MetricsServer _get_qps method to calculate QPS from histogram count and time delta', 'run a TestRunner thread that sends weighted random gRPC test requests on a stub', 'create a generator that yields test cases selected by their assigned weights', 'test the TestRunner run method to verify it executes test cases and records latency', 'review the TestRunner class to understand how exceptions are captured and queued', 'refactor the weighted test case generator to support dynamic weight updates', 'run the gRPC unary stream benchmark to measure RPC latency over 1000 iterations', 'profile the latency of a unary-stream gRPC call with a given message size and response count', 'start a gRPC server subprocess that streams benchmark responses for stress testing', 'review the Handler servicer class that yields BenchmarkResponse payloads in a streaming RPC', 'test the gRPC channel options configured for single-threaded unary stream benchmarking']
```

Usage

```
{'run_stress_test_client': 'run the gRPC Python stress test client against specified server addresses with weighted test cases', 'run_test_with_args': 'run the stress test with parsed arguments including server addresses, test cases, and duration', 'get_grpc_channel': 'create a gRPC channel to a target server with optional TLS and test CA support', 'parse_weighted_test_cases': 'parse a comma separated string of test case names and weights into a dictionary', 'build_argparse_parser': 'build an argparse parser for the gRPC stress test client with server and test configuration options'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_tests/tests/stress/metrics_server.py

Prompts

```
['run the gRPC Python stress test client against specified server addresses with weighted test cases', 'run the stress test with parsed arguments including server addresses, test cases, and duration', 'create a gRPC channel to a target server with optional TLS and test CA support', 'parse a comma separated string of test case names and weights into a dictionary', 'build an argparse parser for the gRPC stress test client with server and test configuration options', 'build a python module to create a gRPC MetricsServer that publishes stress test QPS data', 'create a MetricsServer instance with a histogram to track queries per second for stress testing', 'test the MetricsServer GetAllGauges method to return all gauge responses including python_overall_qps', 'test the MetricsServer GetGauge method to return a specific gauge by name or raise an exception', 'review the MetricsServer _get_qps method to calculate QPS from histogram count and time delta', 'run a TestRunner thread that sends weighted random gRPC test requests on a stub', 'create a generator that yields test cases selected by their assigned weights', 'test the TestRunner run method to verify it executes test cases and records latency', 'review the TestRunner class to understand how exceptions are captured and queued', 'refactor the weighted test case generator to support dynamic weight updates', 'run the gRPC unary stream benchmark to measure RPC latency over 1000 iterations', 'profile the latency of a unary-stream gRPC call with a given message size and response count', 'start a gRPC server subprocess that streams benchmark responses for stress testing', 'review the Handler servicer class that yields BenchmarkResponse payloads in a streaming RPC', 'test the gRPC channel options configured for single-threaded unary stream benchmarking']
```

Usage

```
{'build_metrics_server': 'build a python module to create a gRPC MetricsServer that publishes stress test QPS data', 'create_MetricsServer': 'create a MetricsServer instance with a histogram to track queries per second for stress testing', 'test_GetAllGauges': 'test the MetricsServer GetAllGauges method to return all gauge responses including python_overall_qps', 'test_GetGauge': 'test the MetricsServer GetGauge method to return a specific gauge by name or raise an exception', 'review_get_qps': 'review the MetricsServer _get_qps method to calculate QPS from histogram count and time delta'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_tests/tests/stress/test_runner.py

Prompts

```
['run the gRPC Python stress test client against specified server addresses with weighted test cases', 'run the stress test with parsed arguments including server addresses, test cases, and duration', 'create a gRPC channel to a target server with optional TLS and test CA support', 'parse a comma separated string of test case names and weights into a dictionary', 'build an argparse parser for the gRPC stress test client with server and test configuration options', 'build a python module to create a gRPC MetricsServer that publishes stress test QPS data', 'create a MetricsServer instance with a histogram to track queries per second for stress testing', 'test the MetricsServer GetAllGauges method to return all gauge responses including python_overall_qps', 'test the MetricsServer GetGauge method to return a specific gauge by name or raise an exception', 'review the MetricsServer _get_qps method to calculate QPS from histogram count and time delta', 'run a TestRunner thread that sends weighted random gRPC test requests on a stub', 'create a generator that yields test cases selected by their assigned weights', 'test the TestRunner run method to verify it executes test cases and records latency', 'review the TestRunner class to understand how exceptions are captured and queued', 'refactor the weighted test case generator to support dynamic weight updates', 'run the gRPC unary stream benchmark to measure RPC latency over 1000 iterations', 'profile the latency of a unary-stream gRPC call with a given message size and response count', 'start a gRPC server subprocess that streams benchmark responses for stress testing', 'review the Handler servicer class that yields BenchmarkResponse payloads in a streaming RPC', 'test the gRPC channel options configured for single-threaded unary stream benchmarking']
```

Usage

```
{'run_TestRunner': 'run a TestRunner thread that sends weighted random gRPC test requests on a stub', 'create_weighted_test_case_generator': 'create a generator that yields test cases selected by their assigned weights', 'test_TestRunner_run': 'test the TestRunner run method to verify it executes test cases and records latency', 'review_TestRunner_exception_handling': 'review the TestRunner class to understand how exceptions are captured and queued', 'refactor_weighted_test_case_generator': 'refactor the weighted test case generator to support dynamic weight updates'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_tests/tests/stress/unary_stream_benchmark.py

Prompts

```
['run the gRPC Python stress test client against specified server addresses with weighted test cases', 'run the stress test with parsed arguments including server addresses, test cases, and duration', 'create a gRPC channel to a target server with optional TLS and test CA support', 'parse a comma separated string of test case names and weights into a dictionary', 'build an argparse parser for the gRPC stress test client with server and test configuration options', 'build a python module to create a gRPC MetricsServer that publishes stress test QPS data', 'create a MetricsServer instance with a histogram to track queries per second for stress testing', 'test the MetricsServer GetAllGauges method to return all gauge responses including python_overall_qps', 'test the MetricsServer GetGauge method to return a specific gauge by name or raise an exception', 'review the MetricsServer _get_qps method to calculate QPS from histogram count and time delta', 'run a TestRunner thread that sends weighted random gRPC test requests on a stub', 'create a generator that yields test cases selected by their assigned weights', 'test the TestRunner run method to verify it executes test cases and records latency', 'review the TestRunner class to understand how exceptions are captured and queued', 'refactor the weighted test case generator to support dynamic weight updates', 'run the gRPC unary stream benchmark to measure RPC latency over 1000 iterations', 'profile the latency of a unary-stream gRPC call with a given message size and response count', 'start a gRPC server subprocess that streams benchmark responses for stress testing', 'review the Handler servicer class that yields BenchmarkResponse payloads in a streaming RPC', 'test the gRPC channel options configured for single-threaded unary stream benchmarking']
```

Usage

```
{'run_unary_stream_benchmark': 'run the gRPC unary stream benchmark to measure RPC latency over 1000 iterations', 'profile_rpc_latency': 'profile the latency of a unary-stream gRPC call with a given message size and response count', 'start_benchmark_server': 'start a gRPC server subprocess that streams benchmark responses for stress testing', 'review_Handler_class': 'review the Handler servicer class that yields BenchmarkResponse payloads in a streaming RPC', 'test_GRPC_CHANNEL_OPTIONS': 'test the gRPC channel options configured for single-threaded unary stream benchmarking'}
```

