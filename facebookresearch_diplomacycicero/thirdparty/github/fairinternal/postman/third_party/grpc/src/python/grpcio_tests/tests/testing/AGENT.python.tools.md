# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio_tests/tests/testing/_client_application.py

Prompts

```
['run a gRPC client scenario like unary unary or stream stream on a given channel', 'create a thread-safe Pipe iterator that blocks until values are added or closed', 'run a unary unary gRPC call and compare the response to the expected outcome', 'run a bidirectional stream gRPC call by sending requests and verifying paired responses', 'run multiple concurrent stream unary gRPC calls and verify all return satisfactory outcomes', 'test the ClientTest class to verify successful unary-unary gRPC client calls with a fake server', 'test the ClientTest class to verify bidirectional streaming gRPC client calls with request and response handling', 'test the ClientTest class to verify concurrent bidirectional streaming RPCs across multiple channels', 'test the ClientTest class to verify client-side cancellation of unary-unary gRPC calls', 'test the ClientTest class to verify deadline exceeded behavior on infinite request streams', 'implement a gRPC servicer class that handles unary-unary, unary-stream, stream-unary, and stream-stream RPCs', 'test the StreUn RPC method to send initial metadata and process a stream of requests into a single response', 'review the FirstServiceServicer abort handling logic that uses a thread-safe RLock to track abort success or failure status', 'test the TimeTest class to verify sleep_for delays execution by the specified quantum duration', 'test the TimeTest class to verify sleep_until waits until the specified absolute time', 'test the TimeTest class to verify call_in schedules a callback after a delay', 'test the TimeTest class to verify call_at schedules a callback at an absolute time', 'test the TimeTest class to verify cancelling a scheduled future prevents the callback from executing']
```

Usage

```
{'run_grpc_client_scenario': 'run a gRPC client scenario like unary unary or stream stream on a given channel', 'create_Pipe_iterator': 'create a thread-safe Pipe iterator that blocks until values are added or closed', 'run_unary_unary_call': 'run a unary unary gRPC call and compare the response to the expected outcome', 'run_stream_stream_call': 'run a bidirectional stream gRPC call by sending requests and verifying paired responses', 'run_concurrent_stream_unary': 'run multiple concurrent stream unary gRPC calls and verify all return satisfactory outcomes'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio_tests/tests/testing/_client_test.py

Prompts

```
['run a gRPC client scenario like unary unary or stream stream on a given channel', 'create a thread-safe Pipe iterator that blocks until values are added or closed', 'run a unary unary gRPC call and compare the response to the expected outcome', 'run a bidirectional stream gRPC call by sending requests and verifying paired responses', 'run multiple concurrent stream unary gRPC calls and verify all return satisfactory outcomes', 'test the ClientTest class to verify successful unary-unary gRPC client calls with a fake server', 'test the ClientTest class to verify bidirectional streaming gRPC client calls with request and response handling', 'test the ClientTest class to verify concurrent bidirectional streaming RPCs across multiple channels', 'test the ClientTest class to verify client-side cancellation of unary-unary gRPC calls', 'test the ClientTest class to verify deadline exceeded behavior on infinite request streams', 'implement a gRPC servicer class that handles unary-unary, unary-stream, stream-unary, and stream-stream RPCs', 'test the StreUn RPC method to send initial metadata and process a stream of requests into a single response', 'review the FirstServiceServicer abort handling logic that uses a thread-safe RLock to track abort success or failure status', 'test the TimeTest class to verify sleep_for delays execution by the specified quantum duration', 'test the TimeTest class to verify sleep_until waits until the specified absolute time', 'test the TimeTest class to verify call_in schedules a callback after a delay', 'test the TimeTest class to verify call_at schedules a callback at an absolute time', 'test the TimeTest class to verify cancelling a scheduled future prevents the callback from executing']
```

Usage

```
{'test_unary_unary_rpc': 'test the ClientTest class to verify successful unary-unary gRPC client calls with a fake server', 'test_stream_stream_rpc': 'test the ClientTest class to verify bidirectional streaming gRPC client calls with request and response handling', 'test_concurrent_stream_stream': 'test the ClientTest class to verify concurrent bidirectional streaming RPCs across multiple channels', 'test_cancelled_unary_unary': 'test the ClientTest class to verify client-side cancellation of unary-unary gRPC calls', 'test_infinite_request_stream': 'test the ClientTest class to verify deadline exceeded behavior on infinite request streams'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio_tests/tests/testing/_server_application.py

Prompts

```
['run a gRPC client scenario like unary unary or stream stream on a given channel', 'create a thread-safe Pipe iterator that blocks until values are added or closed', 'run a unary unary gRPC call and compare the response to the expected outcome', 'run a bidirectional stream gRPC call by sending requests and verifying paired responses', 'run multiple concurrent stream unary gRPC calls and verify all return satisfactory outcomes', 'test the ClientTest class to verify successful unary-unary gRPC client calls with a fake server', 'test the ClientTest class to verify bidirectional streaming gRPC client calls with request and response handling', 'test the ClientTest class to verify concurrent bidirectional streaming RPCs across multiple channels', 'test the ClientTest class to verify client-side cancellation of unary-unary gRPC calls', 'test the ClientTest class to verify deadline exceeded behavior on infinite request streams', 'implement a gRPC servicer class that handles unary-unary, unary-stream, stream-unary, and stream-stream RPCs', 'test the StreUn RPC method to send initial metadata and process a stream of requests into a single response', 'review the FirstServiceServicer abort handling logic that uses a thread-safe RLock to track abort success or failure status', 'test the TimeTest class to verify sleep_for delays execution by the specified quantum duration', 'test the TimeTest class to verify sleep_until waits until the specified absolute time', 'test the TimeTest class to verify call_in schedules a callback after a delay', 'test the TimeTest class to verify call_at schedules a callback at an absolute time', 'test the TimeTest class to verify cancelling a scheduled future prevents the callback from executing']
```

Usage

```
{'implement_grpc_servicer': 'implement a gRPC servicer class that handles unary-unary, unary-stream, stream-unary, and stream-stream RPCs', 'test_unary_unary_rpc': 'test the UnUn RPC method to handle unary-unary requests with abort and invalid argument logic', 'test_stream_unary_rpc': 'test the StreUn RPC method to send initial metadata and process a stream of requests into a single response', 'test_stream_stream_rpc': 'test the StreStre RPC method to yield multiple responses per streamed request including mutating responses', 'review_abort_handling': 'review the FirstServiceServicer abort handling logic that uses a thread-safe RLock to track abort success or failure status'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio_tests/tests/testing/_time_test.py

Prompts

```
['run a gRPC client scenario like unary unary or stream stream on a given channel', 'create a thread-safe Pipe iterator that blocks until values are added or closed', 'run a unary unary gRPC call and compare the response to the expected outcome', 'run a bidirectional stream gRPC call by sending requests and verifying paired responses', 'run multiple concurrent stream unary gRPC calls and verify all return satisfactory outcomes', 'test the ClientTest class to verify successful unary-unary gRPC client calls with a fake server', 'test the ClientTest class to verify bidirectional streaming gRPC client calls with request and response handling', 'test the ClientTest class to verify concurrent bidirectional streaming RPCs across multiple channels', 'test the ClientTest class to verify client-side cancellation of unary-unary gRPC calls', 'test the ClientTest class to verify deadline exceeded behavior on infinite request streams', 'implement a gRPC servicer class that handles unary-unary, unary-stream, stream-unary, and stream-stream RPCs', 'test the StreUn RPC method to send initial metadata and process a stream of requests into a single response', 'review the FirstServiceServicer abort handling logic that uses a thread-safe RLock to track abort success or failure status', 'test the TimeTest class to verify sleep_for delays execution by the specified quantum duration', 'test the TimeTest class to verify sleep_until waits until the specified absolute time', 'test the TimeTest class to verify call_in schedules a callback after a delay', 'test the TimeTest class to verify call_at schedules a callback at an absolute time', 'test the TimeTest class to verify cancelling a scheduled future prevents the callback from executing']
```

Usage

```
{'test_sleep_for': 'test the TimeTest class to verify sleep_for delays execution by the specified quantum duration', 'test_sleep_until': 'test the TimeTest class to verify sleep_until waits until the specified absolute time', 'test_call_in': 'test the TimeTest class to verify call_in schedules a callback after a delay', 'test_call_at': 'test the TimeTest class to verify call_at schedules a callback at an absolute time', 'test_cancel': 'test the TimeTest class to verify cancelling a scheduled future prevents the callback from executing'}
```

