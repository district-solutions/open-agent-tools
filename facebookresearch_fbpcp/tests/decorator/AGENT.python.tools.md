# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/tests/decorator/test_error_handler.py

Prompts

```
['test the error_handler decorator converts generic exceptions into PcpError', 'test the error_handler decorator maps AWS ThrottlingException to ThrottlingError', 'test the error_handler decorator maps GCP TooManyRequests to ThrottlingError', 'test the error_handler decorator maps AWS LimitExceededException to LimitExceededError', 'test the error_handler decorator preserves function args and kwargs when wrapping', 'test the duration_time decorator to measure execution time of sync and async methods', 'test the request_counter decorator to count method invocations on sync and async methods', 'test the error_counter decorator to count exceptions raised by sync and async methods', 'test a class implementing MetricsGetter with has_metrics and get_metrics methods', 'test metrics decorators that auto-detect and wrap both sync and async coroutine functions']
```

Usage

```
{'test_error_handler_pcp_error': 'test the error_handler decorator converts generic exceptions into PcpError', 'test_error_handler_throttling': 'test the error_handler decorator maps AWS ThrottlingException to ThrottlingError', 'test_error_handler_gcp_throttling': 'test the error_handler decorator maps GCP TooManyRequests to ThrottlingError', 'test_error_handler_limit_exceeded': 'test the error_handler decorator maps AWS LimitExceededException to LimitExceededError', 'test_error_handler_wrapped_args': 'test the error_handler decorator preserves function args and kwargs when wrapping'}
```

## File: facebookresearch_fbpcp/tests/decorator/test_metrics.py

Prompts

```
['test the error_handler decorator converts generic exceptions into PcpError', 'test the error_handler decorator maps AWS ThrottlingException to ThrottlingError', 'test the error_handler decorator maps GCP TooManyRequests to ThrottlingError', 'test the error_handler decorator maps AWS LimitExceededException to LimitExceededError', 'test the error_handler decorator preserves function args and kwargs when wrapping', 'test the duration_time decorator to measure execution time of sync and async methods', 'test the request_counter decorator to count method invocations on sync and async methods', 'test the error_counter decorator to count exceptions raised by sync and async methods', 'test a class implementing MetricsGetter with has_metrics and get_metrics methods', 'test metrics decorators that auto-detect and wrap both sync and async coroutine functions']
```

Usage

```
{'test_duration_time_decorator': 'test the duration_time decorator to measure execution time of sync and async methods', 'test_request_counter_decorator': 'test the request_counter decorator to count method invocations on sync and async methods', 'test_error_counter_decorator': 'test the error_counter decorator to count exceptions raised by sync and async methods', 'test_metricsgetter_implementation': 'test a class implementing MetricsGetter with has_metrics and get_metrics methods', 'test_sync_and_async_decorators': 'test metrics decorators that auto-detect and wrap both sync and async coroutine functions'}
```

