# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_tests/tests_py3_only/unit/_leak_test.py

Prompts

```
['run the gRPC memory leak smoke test for short-lived channels without explicit close', 'test memory leak detection by performing 5000 single-shot RPC calls and checking RSS growth', 'get the current process maximum resident set size using resource.getrusage', 'format a byte count into a human-readable string like MiB or GiB', 'start a gRPC test server with a generic handler on a random localhost port', 'test the grpc experimental simple stubs unary-unary RPC call over insecure and secure channels', 'test the grpc experimental simple stubs unary-stream, stream-unary, and stream-stream RPC calls', 'test that grpc simple stubs channel cache creates, caches, and evicts channels correctly', 'test that grpc simple stubs enforces a maximum total number of cached channels under stress', 'test that grpc simple stubs default timeout and wait_for_ready behavior trigger deadline exceeded']
```

Usage

```
{'run_leak_test': 'run the gRPC memory leak smoke test for short-lived channels without explicit close', 'test_single_shot_rpcs': 'test memory leak detection by performing 5000 single-shot RPC calls and checking RSS growth', 'get_max_rss': 'get the current process maximum resident set size using resource.getrusage', 'pretty_print_bytes': 'format a byte count into a human-readable string like MiB or GiB', 'start_test_server': 'start a gRPC test server with a generic handler on a random localhost port'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_tests/tests_py3_only/unit/_simple_stubs_test.py

Prompts

```
['run the gRPC memory leak smoke test for short-lived channels without explicit close', 'test memory leak detection by performing 5000 single-shot RPC calls and checking RSS growth', 'get the current process maximum resident set size using resource.getrusage', 'format a byte count into a human-readable string like MiB or GiB', 'start a gRPC test server with a generic handler on a random localhost port', 'test the grpc experimental simple stubs unary-unary RPC call over insecure and secure channels', 'test the grpc experimental simple stubs unary-stream, stream-unary, and stream-stream RPC calls', 'test that grpc simple stubs channel cache creates, caches, and evicts channels correctly', 'test that grpc simple stubs enforces a maximum total number of cached channels under stress', 'test that grpc simple stubs default timeout and wait_for_ready behavior trigger deadline exceeded']
```

Usage

```
{'test_grpc_simple_stubs_unary_unary': 'test the grpc experimental simple stubs unary-unary RPC call over insecure and secure channels', 'test_grpc_simple_stubs_streaming': 'test the grpc experimental simple stubs unary-stream, stream-unary, and stream-stream RPC calls', 'test_channel_caching_eviction': 'test that grpc simple stubs channel cache creates, caches, and evicts channels correctly', 'test_channel_limit_enforcement': 'test that grpc simple stubs enforces a maximum total number of cached channels under stress', 'test_default_timeout_and_wait_for_ready': 'test that grpc simple stubs default timeout and wait_for_ready behavior trigger deadline exceeded'}
```

