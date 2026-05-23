# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_testing/grpc_testing/_common.py

Prompts

```
['create a function that adds gRPC runtime metadata to a metadata tuple or returns empty fussed metadata', 'build a dictionary mapping RPC names to method descriptors from a list of service descriptors', 'create a named tuple to hold gRPC channel RPC response, trailing metadata, code, and details', 'create a named tuple to hold gRPC server RPC request, requests closed flag, and terminated flag', 'review the abstract base class defining server-side RPC handler methods for metadata, requests, responses, and termination', 'create a StrictRealTime instance to schedule behaviors using real wall clock time', 'create a StrictFakeTime instance with a given start time for deterministic test scheduling', 'test StrictFakeTime by calling sleep_for to advance fake time and trigger mature behaviors', 'test StrictRealTime by calling call_at to schedule a behavior at a specific wall clock time', 'review the _Future class cancel method to understand how scheduled behaviors are removed from the queue']
```

Usage

```
{'fuss_with_metadata': 'create a function that adds gRPC runtime metadata to a metadata tuple or returns empty fussed metadata', 'rpc_names': 'build a dictionary mapping RPC names to method descriptors from a list of service descriptors', 'ChannelRpcRead': 'create a named tuple to hold gRPC channel RPC response, trailing metadata, code, and details', 'ServerRpcRead': 'create a named tuple to hold gRPC server RPC request, requests closed flag, and terminated flag', 'ServerRpcHandler': 'review the abstract base class defining server-side RPC handler methods for metadata, requests, responses, and termination'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_testing/grpc_testing/_time.py

Prompts

```
['create a function that adds gRPC runtime metadata to a metadata tuple or returns empty fussed metadata', 'build a dictionary mapping RPC names to method descriptors from a list of service descriptors', 'create a named tuple to hold gRPC channel RPC response, trailing metadata, code, and details', 'create a named tuple to hold gRPC server RPC request, requests closed flag, and terminated flag', 'review the abstract base class defining server-side RPC handler methods for metadata, requests, responses, and termination', 'create a StrictRealTime instance to schedule behaviors using real wall clock time', 'create a StrictFakeTime instance with a given start time for deterministic test scheduling', 'test StrictFakeTime by calling sleep_for to advance fake time and trigger mature behaviors', 'test StrictRealTime by calling call_at to schedule a behavior at a specific wall clock time', 'review the _Future class cancel method to understand how scheduled behaviors are removed from the queue']
```

Usage

```
{'create_StrictRealTime': 'create a StrictRealTime instance to schedule behaviors using real wall clock time', 'create_StrictFakeTime': 'create a StrictFakeTime instance with a given start time for deterministic test scheduling', 'test_StrictFakeTime_sleep_for': 'test StrictFakeTime by calling sleep_for to advance fake time and trigger mature behaviors', 'test_StrictRealTime_call_at': 'test StrictRealTime by calling call_at to schedule a behavior at a specific wall clock time', 'review__Future_cancel': 'review the _Future class cancel method to understand how scheduled behaviors are removed from the queue'}
```

