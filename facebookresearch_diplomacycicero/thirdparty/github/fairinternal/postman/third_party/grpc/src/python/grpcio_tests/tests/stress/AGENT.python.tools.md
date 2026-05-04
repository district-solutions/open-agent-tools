# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio_tests/tests/stress/client.py

Prompts

```
['run a gRPC stress test client against server addresses with configurable test cases and duration', 'parse a comma separated string of test case names and weights into a dictionary', 'create a secure or insecure gRPC channel to a target server with optional TLS and CA', 'run stress tests by creating channels, stubs, and test runners then wait for completion or exceptions', 'review the run_test function that orchestrates gRPC stress test execution with metrics server and exception handling', 'build a gRPC MetricsService server that publishes stress test QPS data using a histogram', 'create a MetricsServer instance with a histogram to track and report queries per second', 'test the GetAllGauges method to retrieve all gauge responses including python_overall_qps', 'test the GetGauge method to retrieve a specific gauge by name from the metrics server', 'review the MetricsServer _get_qps method that calculates QPS from histogram count and time delta', 'run a TestRunner thread that sends random weighted gRPC requests on a TestService stub', 'create a generator that yields test cases based on their assigned weights using random selection', 'test the TestRunner class by invoking test_interoperability on a gRPC stub with weighted cases', 'review the TestRunner run method and how it catches exceptions and queues them for later inspection', 'summarize how the TestRunner records latency in nanoseconds to a histogram after each test case completes', 'run the gRPC unary stream benchmark to measure RPC latency over 1000 iterations', 'profile the unary stream RPC latency by sending a benchmark request and measuring response time', 'create a gRPC server subprocess using the running server context manager for benchmarking', 'review the Handler class Benchmark method that yields streaming responses for the unary stream service', 'test the gRPC channel options including single-threaded unary stream and max metadata size settings']
```

Usage

```
{'run_stress_test_client': 'run a gRPC stress test client against server addresses with configurable test cases and duration', 'parse_weighted_test_cases': 'parse a comma separated string of test case names and weights into a dictionary', 'create_grpc_channel': 'create a secure or insecure gRPC channel to a target server with optional TLS and CA', 'run_test_with_args': 'run stress tests by creating channels, stubs, and test runners then wait for completion or exceptions', 'review_run_test': 'review the run_test function that orchestrates gRPC stress test execution with metrics server and exception handling'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio_tests/tests/stress/metrics_server.py

Prompts

```
['run a gRPC stress test client against server addresses with configurable test cases and duration', 'parse a comma separated string of test case names and weights into a dictionary', 'create a secure or insecure gRPC channel to a target server with optional TLS and CA', 'run stress tests by creating channels, stubs, and test runners then wait for completion or exceptions', 'review the run_test function that orchestrates gRPC stress test execution with metrics server and exception handling', 'build a gRPC MetricsService server that publishes stress test QPS data using a histogram', 'create a MetricsServer instance with a histogram to track and report queries per second', 'test the GetAllGauges method to retrieve all gauge responses including python_overall_qps', 'test the GetGauge method to retrieve a specific gauge by name from the metrics server', 'review the MetricsServer _get_qps method that calculates QPS from histogram count and time delta', 'run a TestRunner thread that sends random weighted gRPC requests on a TestService stub', 'create a generator that yields test cases based on their assigned weights using random selection', 'test the TestRunner class by invoking test_interoperability on a gRPC stub with weighted cases', 'review the TestRunner run method and how it catches exceptions and queues them for later inspection', 'summarize how the TestRunner records latency in nanoseconds to a histogram after each test case completes', 'run the gRPC unary stream benchmark to measure RPC latency over 1000 iterations', 'profile the unary stream RPC latency by sending a benchmark request and measuring response time', 'create a gRPC server subprocess using the running server context manager for benchmarking', 'review the Handler class Benchmark method that yields streaming responses for the unary stream service', 'test the gRPC channel options including single-threaded unary stream and max metadata size settings']
```

Usage

```
{'build_metrics_server': 'build a gRPC MetricsService server that publishes stress test QPS data using a histogram', 'create_MetricsServer': 'create a MetricsServer instance with a histogram to track and report queries per second', 'test_GetAllGauges': 'test the GetAllGauges method to retrieve all gauge responses including python_overall_qps', 'test_GetGauge': 'test the GetGauge method to retrieve a specific gauge by name from the metrics server', 'review_MetricsServer_get_qps': 'review the MetricsServer _get_qps method that calculates QPS from histogram count and time delta'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio_tests/tests/stress/test_runner.py

Prompts

```
['run a gRPC stress test client against server addresses with configurable test cases and duration', 'parse a comma separated string of test case names and weights into a dictionary', 'create a secure or insecure gRPC channel to a target server with optional TLS and CA', 'run stress tests by creating channels, stubs, and test runners then wait for completion or exceptions', 'review the run_test function that orchestrates gRPC stress test execution with metrics server and exception handling', 'build a gRPC MetricsService server that publishes stress test QPS data using a histogram', 'create a MetricsServer instance with a histogram to track and report queries per second', 'test the GetAllGauges method to retrieve all gauge responses including python_overall_qps', 'test the GetGauge method to retrieve a specific gauge by name from the metrics server', 'review the MetricsServer _get_qps method that calculates QPS from histogram count and time delta', 'run a TestRunner thread that sends random weighted gRPC requests on a TestService stub', 'create a generator that yields test cases based on their assigned weights using random selection', 'test the TestRunner class by invoking test_interoperability on a gRPC stub with weighted cases', 'review the TestRunner run method and how it catches exceptions and queues them for later inspection', 'summarize how the TestRunner records latency in nanoseconds to a histogram after each test case completes', 'run the gRPC unary stream benchmark to measure RPC latency over 1000 iterations', 'profile the unary stream RPC latency by sending a benchmark request and measuring response time', 'create a gRPC server subprocess using the running server context manager for benchmarking', 'review the Handler class Benchmark method that yields streaming responses for the unary stream service', 'test the gRPC channel options including single-threaded unary stream and max metadata size settings']
```

Usage

```
{'run_test_runner_thread': 'run a TestRunner thread that sends random weighted gRPC requests on a TestService stub', 'create_weighted_test_case_generator': 'create a generator that yields test cases based on their assigned weights using random selection', 'test_test_runner_interoperability': 'test the TestRunner class by invoking test_interoperability on a gRPC stub with weighted cases', 'review_test_runner_exception_handling': 'review the TestRunner run method and how it catches exceptions and queues them for later inspection', 'summarize_test_runner_histogram': 'summarize how the TestRunner records latency in nanoseconds to a histogram after each test case completes'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio_tests/tests/stress/unary_stream_benchmark.py

Prompts

```
['run a gRPC stress test client against server addresses with configurable test cases and duration', 'parse a comma separated string of test case names and weights into a dictionary', 'create a secure or insecure gRPC channel to a target server with optional TLS and CA', 'run stress tests by creating channels, stubs, and test runners then wait for completion or exceptions', 'review the run_test function that orchestrates gRPC stress test execution with metrics server and exception handling', 'build a gRPC MetricsService server that publishes stress test QPS data using a histogram', 'create a MetricsServer instance with a histogram to track and report queries per second', 'test the GetAllGauges method to retrieve all gauge responses including python_overall_qps', 'test the GetGauge method to retrieve a specific gauge by name from the metrics server', 'review the MetricsServer _get_qps method that calculates QPS from histogram count and time delta', 'run a TestRunner thread that sends random weighted gRPC requests on a TestService stub', 'create a generator that yields test cases based on their assigned weights using random selection', 'test the TestRunner class by invoking test_interoperability on a gRPC stub with weighted cases', 'review the TestRunner run method and how it catches exceptions and queues them for later inspection', 'summarize how the TestRunner records latency in nanoseconds to a histogram after each test case completes', 'run the gRPC unary stream benchmark to measure RPC latency over 1000 iterations', 'profile the unary stream RPC latency by sending a benchmark request and measuring response time', 'create a gRPC server subprocess using the running server context manager for benchmarking', 'review the Handler class Benchmark method that yields streaming responses for the unary stream service', 'test the gRPC channel options including single-threaded unary stream and max metadata size settings']
```

Usage

```
{'run_unary_stream_benchmark': 'run the gRPC unary stream benchmark to measure RPC latency over 1000 iterations', 'profile_unary_stream_latency': 'profile the unary stream RPC latency by sending a benchmark request and measuring response time', 'create_grpc_server_subprocess': 'create a gRPC server subprocess using the running server context manager for benchmarking', 'review_Handler_Benchmark': 'review the Handler class Benchmark method that yields streaming responses for the unary stream service', 'test_GRPC_CHANNEL_OPTIONS': 'test the gRPC channel options including single-threaded unary stream and max metadata size settings'}
```

