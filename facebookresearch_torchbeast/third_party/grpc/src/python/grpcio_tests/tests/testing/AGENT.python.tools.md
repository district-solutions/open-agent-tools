# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_tests/tests/testing/_client_application.py

Prompts

```
['run a gRPC client scenario on a channel and return an Outcome', 'create a thread-safe iterator pipe that blocks until values are added', 'run a unary-unary gRPC call and compare the response to expected', 'run a stream-stream gRPC call by feeding requests through a Pipe', 'run multiple concurrent stream-unary gRPC calls and verify all responses', 'test the ClientTest class to verify successful unary-unary gRPC client RPC behavior', 'test the ClientTest class to verify successful unary-stream gRPC client RPC behavior', 'test the ClientTest class to verify successful stream-unary gRPC client RPC behavior', 'test the ClientTest class to verify successful bidirectional stream gRPC client RPC behavior', 'test the ClientTest class to verify concurrent bidirectional stream gRPC client RPCs', 'implement a gRPC server servicer class that handles unary and streaming RPC calls', 'review the UnUn unary-unary RPC method that handles abort requests with permission denied status', 'review the UnStre unary-stream RPC method that validates requests and yields streaming responses', 'review the StreUn stream-unary RPC method that sends initial metadata and processes request iterators', 'review the StreStre stream-stream RPC method that yields multiple responses for streaming requests', 'test the unary-unary RPC call on a gRPC testing server and verify response and status code', 'test the unary-stream RPC call on a gRPC testing server and verify trailing metadata and status', 'test the stream-unary RPC call by sending multiple requests and verifying the final response', 'test the bidirectional stream RPC by sending requests and collecting responses from the server', 'test that the servicer context abort returns PERMISSION_DENIED and handles success queries', 'test the TimeTest class sleep_for method that sleeps for a given quantum duration', 'test the TimeTest class call_in method that schedules a callback after a delay', 'test the StrictFakeTimeTest cancel method that cancels a scheduled future callback', 'test the TimeTest class call_at method that schedules a callback at a specific time', 'review the TimeNoter class call_times method that returns recorded call times as a tuple']
```

Usage

```
{'run_scenario': 'run a gRPC client scenario on a channel and return an Outcome', 'create_Pipe': 'create a thread-safe iterator pipe that blocks until values are added', 'run_unary_unary': 'run a unary-unary gRPC call and compare the response to expected', 'run_stream_stream': 'run a stream-stream gRPC call by feeding requests through a Pipe', 'run_concurrent_stream_unary': 'run multiple concurrent stream-unary gRPC calls and verify all responses'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_tests/tests/testing/_client_test.py

Prompts

```
['run a gRPC client scenario on a channel and return an Outcome', 'create a thread-safe iterator pipe that blocks until values are added', 'run a unary-unary gRPC call and compare the response to expected', 'run a stream-stream gRPC call by feeding requests through a Pipe', 'run multiple concurrent stream-unary gRPC calls and verify all responses', 'test the ClientTest class to verify successful unary-unary gRPC client RPC behavior', 'test the ClientTest class to verify successful unary-stream gRPC client RPC behavior', 'test the ClientTest class to verify successful stream-unary gRPC client RPC behavior', 'test the ClientTest class to verify successful bidirectional stream gRPC client RPC behavior', 'test the ClientTest class to verify concurrent bidirectional stream gRPC client RPCs', 'implement a gRPC server servicer class that handles unary and streaming RPC calls', 'review the UnUn unary-unary RPC method that handles abort requests with permission denied status', 'review the UnStre unary-stream RPC method that validates requests and yields streaming responses', 'review the StreUn stream-unary RPC method that sends initial metadata and processes request iterators', 'review the StreStre stream-stream RPC method that yields multiple responses for streaming requests', 'test the unary-unary RPC call on a gRPC testing server and verify response and status code', 'test the unary-stream RPC call on a gRPC testing server and verify trailing metadata and status', 'test the stream-unary RPC call by sending multiple requests and verifying the final response', 'test the bidirectional stream RPC by sending requests and collecting responses from the server', 'test that the servicer context abort returns PERMISSION_DENIED and handles success queries', 'test the TimeTest class sleep_for method that sleeps for a given quantum duration', 'test the TimeTest class call_in method that schedules a callback after a delay', 'test the StrictFakeTimeTest cancel method that cancels a scheduled future callback', 'test the TimeTest class call_at method that schedules a callback at a specific time', 'review the TimeNoter class call_times method that returns recorded call times as a tuple']
```

Usage

```
{'test_unary_unary_client': 'test the ClientTest class to verify successful unary-unary gRPC client RPC behavior', 'test_unary_stream_client': 'test the ClientTest class to verify successful unary-stream gRPC client RPC behavior', 'test_stream_unary_client': 'test the ClientTest class to verify successful stream-unary gRPC client RPC behavior', 'test_stream_stream_client': 'test the ClientTest class to verify successful bidirectional stream gRPC client RPC behavior', 'test_concurrent_stream_stream': 'test the ClientTest class to verify concurrent bidirectional stream gRPC client RPCs'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_tests/tests/testing/_server_application.py

Prompts

```
['run a gRPC client scenario on a channel and return an Outcome', 'create a thread-safe iterator pipe that blocks until values are added', 'run a unary-unary gRPC call and compare the response to expected', 'run a stream-stream gRPC call by feeding requests through a Pipe', 'run multiple concurrent stream-unary gRPC calls and verify all responses', 'test the ClientTest class to verify successful unary-unary gRPC client RPC behavior', 'test the ClientTest class to verify successful unary-stream gRPC client RPC behavior', 'test the ClientTest class to verify successful stream-unary gRPC client RPC behavior', 'test the ClientTest class to verify successful bidirectional stream gRPC client RPC behavior', 'test the ClientTest class to verify concurrent bidirectional stream gRPC client RPCs', 'implement a gRPC server servicer class that handles unary and streaming RPC calls', 'review the UnUn unary-unary RPC method that handles abort requests with permission denied status', 'review the UnStre unary-stream RPC method that validates requests and yields streaming responses', 'review the StreUn stream-unary RPC method that sends initial metadata and processes request iterators', 'review the StreStre stream-stream RPC method that yields multiple responses for streaming requests', 'test the unary-unary RPC call on a gRPC testing server and verify response and status code', 'test the unary-stream RPC call on a gRPC testing server and verify trailing metadata and status', 'test the stream-unary RPC call by sending multiple requests and verifying the final response', 'test the bidirectional stream RPC by sending requests and collecting responses from the server', 'test that the servicer context abort returns PERMISSION_DENIED and handles success queries', 'test the TimeTest class sleep_for method that sleeps for a given quantum duration', 'test the TimeTest class call_in method that schedules a callback after a delay', 'test the StrictFakeTimeTest cancel method that cancels a scheduled future callback', 'test the TimeTest class call_at method that schedules a callback at a specific time', 'review the TimeNoter class call_times method that returns recorded call times as a tuple']
```

Usage

```
{'implement_FirstServiceServicer': 'implement a gRPC server servicer class that handles unary and streaming RPC calls', 'review_UnUn_method': 'review the UnUn unary-unary RPC method that handles abort requests with permission denied status', 'review_UnStre_method': 'review the UnStre unary-stream RPC method that validates requests and yields streaming responses', 'review_StreUn_method': 'review the StreUn stream-unary RPC method that sends initial metadata and processes request iterators', 'review_StreStre_method': 'review the StreStre stream-stream RPC method that yields multiple responses for streaming requests'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_tests/tests/testing/_server_test.py

Prompts

```
['run a gRPC client scenario on a channel and return an Outcome', 'create a thread-safe iterator pipe that blocks until values are added', 'run a unary-unary gRPC call and compare the response to expected', 'run a stream-stream gRPC call by feeding requests through a Pipe', 'run multiple concurrent stream-unary gRPC calls and verify all responses', 'test the ClientTest class to verify successful unary-unary gRPC client RPC behavior', 'test the ClientTest class to verify successful unary-stream gRPC client RPC behavior', 'test the ClientTest class to verify successful stream-unary gRPC client RPC behavior', 'test the ClientTest class to verify successful bidirectional stream gRPC client RPC behavior', 'test the ClientTest class to verify concurrent bidirectional stream gRPC client RPCs', 'implement a gRPC server servicer class that handles unary and streaming RPC calls', 'review the UnUn unary-unary RPC method that handles abort requests with permission denied status', 'review the UnStre unary-stream RPC method that validates requests and yields streaming responses', 'review the StreUn stream-unary RPC method that sends initial metadata and processes request iterators', 'review the StreStre stream-stream RPC method that yields multiple responses for streaming requests', 'test the unary-unary RPC call on a gRPC testing server and verify response and status code', 'test the unary-stream RPC call on a gRPC testing server and verify trailing metadata and status', 'test the stream-unary RPC call by sending multiple requests and verifying the final response', 'test the bidirectional stream RPC by sending requests and collecting responses from the server', 'test that the servicer context abort returns PERMISSION_DENIED and handles success queries', 'test the TimeTest class sleep_for method that sleeps for a given quantum duration', 'test the TimeTest class call_in method that schedules a callback after a delay', 'test the StrictFakeTimeTest cancel method that cancels a scheduled future callback', 'test the TimeTest class call_at method that schedules a callback at a specific time', 'review the TimeNoter class call_times method that returns recorded call times as a tuple']
```

Usage

```
{'test_unary_unary_rpc': 'test the unary-unary RPC call on a gRPC testing server and verify response and status code', 'test_unary_stream_rpc': 'test the unary-stream RPC call on a gRPC testing server and verify trailing metadata and status', 'test_stream_unary_rpc': 'test the stream-unary RPC call by sending multiple requests and verifying the final response', 'test_stream_stream_rpc': 'test the bidirectional stream RPC by sending requests and collecting responses from the server', 'test_servicer_context_abort': 'test that the servicer context abort returns PERMISSION_DENIED and handles success queries'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_tests/tests/testing/_time_test.py

Prompts

```
['run a gRPC client scenario on a channel and return an Outcome', 'create a thread-safe iterator pipe that blocks until values are added', 'run a unary-unary gRPC call and compare the response to expected', 'run a stream-stream gRPC call by feeding requests through a Pipe', 'run multiple concurrent stream-unary gRPC calls and verify all responses', 'test the ClientTest class to verify successful unary-unary gRPC client RPC behavior', 'test the ClientTest class to verify successful unary-stream gRPC client RPC behavior', 'test the ClientTest class to verify successful stream-unary gRPC client RPC behavior', 'test the ClientTest class to verify successful bidirectional stream gRPC client RPC behavior', 'test the ClientTest class to verify concurrent bidirectional stream gRPC client RPCs', 'implement a gRPC server servicer class that handles unary and streaming RPC calls', 'review the UnUn unary-unary RPC method that handles abort requests with permission denied status', 'review the UnStre unary-stream RPC method that validates requests and yields streaming responses', 'review the StreUn stream-unary RPC method that sends initial metadata and processes request iterators', 'review the StreStre stream-stream RPC method that yields multiple responses for streaming requests', 'test the unary-unary RPC call on a gRPC testing server and verify response and status code', 'test the unary-stream RPC call on a gRPC testing server and verify trailing metadata and status', 'test the stream-unary RPC call by sending multiple requests and verifying the final response', 'test the bidirectional stream RPC by sending requests and collecting responses from the server', 'test that the servicer context abort returns PERMISSION_DENIED and handles success queries', 'test the TimeTest class sleep_for method that sleeps for a given quantum duration', 'test the TimeTest class call_in method that schedules a callback after a delay', 'test the StrictFakeTimeTest cancel method that cancels a scheduled future callback', 'test the TimeTest class call_at method that schedules a callback at a specific time', 'review the TimeNoter class call_times method that returns recorded call times as a tuple']
```

Usage

```
{'test_TimeTest_sleep_for': 'test the TimeTest class sleep_for method that sleeps for a given quantum duration', 'test_TimeTest_call_in': 'test the TimeTest class call_in method that schedules a callback after a delay', 'test_StrictFakeTimeTest_cancel': 'test the StrictFakeTimeTest cancel method that cancels a scheduled future callback', 'test_TimeTest_call_at': 'test the TimeTest class call_at method that schedules a callback at a specific time', 'review_TimeNoter_call_times': 'review the TimeNoter class call_times method that returns recorded call times as a tuple'}
```

