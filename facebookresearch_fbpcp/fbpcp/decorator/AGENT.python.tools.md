# Agent Python Tools

- repo: facebookresearch/fbpcp
- repo_uri: https://github.com/facebookresearch/fbpcp

## File: facebookresearch_fbpcp/fbpcp/decorator/error_handler.py

Prompts

```
['use the error_handler decorator to wrap functions that may raise AWS, GCP, or Kubernetes exceptions', 'map AWS ClientError exceptions to PcpError subclasses using the error_handler decorator on boto3 calls', 'map GCP GoogleCloudError exceptions to PcpError subclasses using the error_handler decorator on GCP SDK calls', 'map Kubernetes OpenApiException errors to PcpError subclasses using the error_handler decorator on k8s client calls', 'wrap any function with error_handler to catch unhandled exceptions and raise them as PcpError', 'create a decorator that counts each method call using request_counter for metrics tracking', 'create a decorator that counts exceptions raised by a method using error_counter for error tracking', 'create a decorator that measures method execution time in milliseconds using duration_time', 'review the request_counter decorator to understand how it supports both sync and async methods', 'refactor the metrics decorators to use a custom metrics backend instead of MetricsGetter']
```

Usage

```
{'use_error_handler_decorator': 'use the error_handler decorator to wrap functions that may raise AWS, GCP, or Kubernetes exceptions', 'map_aws_errors': 'map AWS ClientError exceptions to PcpError subclasses using the error_handler decorator on boto3 calls', 'map_gcp_errors': 'map GCP GoogleCloudError exceptions to PcpError subclasses using the error_handler decorator on GCP SDK calls', 'map_k8s_errors': 'map Kubernetes OpenApiException errors to PcpError subclasses using the error_handler decorator on k8s client calls', 'handle_generic_exceptions': 'wrap any function with error_handler to catch unhandled exceptions and raise them as PcpError'}
```

## File: facebookresearch_fbpcp/fbpcp/decorator/metrics.py

Prompts

```
['use the error_handler decorator to wrap functions that may raise AWS, GCP, or Kubernetes exceptions', 'map AWS ClientError exceptions to PcpError subclasses using the error_handler decorator on boto3 calls', 'map GCP GoogleCloudError exceptions to PcpError subclasses using the error_handler decorator on GCP SDK calls', 'map Kubernetes OpenApiException errors to PcpError subclasses using the error_handler decorator on k8s client calls', 'wrap any function with error_handler to catch unhandled exceptions and raise them as PcpError', 'create a decorator that counts each method call using request_counter for metrics tracking', 'create a decorator that counts exceptions raised by a method using error_counter for error tracking', 'create a decorator that measures method execution time in milliseconds using duration_time', 'review the request_counter decorator to understand how it supports both sync and async methods', 'refactor the metrics decorators to use a custom metrics backend instead of MetricsGetter']
```

Usage

```
{'create_request_counter_decorator': 'create a decorator that counts each method call using request_counter for metrics tracking', 'create_error_counter_decorator': 'create a decorator that counts exceptions raised by a method using error_counter for error tracking', 'create_duration_time_decorator': 'create a decorator that measures method execution time in milliseconds using duration_time', 'review_request_counter_async_support': 'review the request_counter decorator to understand how it supports both sync and async methods', 'refactor_metrics_decorator_for_custom_backend': 'refactor the metrics decorators to use a custom metrics backend instead of MetricsGetter'}
```

