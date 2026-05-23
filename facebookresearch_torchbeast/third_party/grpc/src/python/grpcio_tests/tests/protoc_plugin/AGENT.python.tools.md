# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_tests/tests/protoc_plugin/_python_plugin_test.py

Prompts

```
['test that the generated gRPC Python module exposes TestServiceStub, TestServiceServicer, and add_TestServiceServicer_to_server', 'test a unary gRPC call by sending a SimpleRequest and verifying the SimpleResponse payload matches expected size', 'test a server-streaming gRPC call that yields multiple StreamingOutputCallResponse messages with configurable payload sizes', 'test a full-duplex streaming gRPC call where client and server exchange messages concurrently via request and response iterators', 'test the simple stub API that allows calling gRPC methods directly without creating explicit channel and stub objects', 'run the unittest test suite for gRPC protoc plugin split definitions across multiple protoc styles', 'test that generated protobuf modules expose Request, Response, TestServiceStub, and TestServiceServicer attributes', 'test end-to-end gRPC service call using a generated stub, servicer, and insecure channel', 'review the four protoc invocation styles: Mid2016, SingleExecution, ProtoBeforeGrpc, and GrpcBeforeProto', 'summarize the factory function that dynamically creates test case classes for split vs same proto configurations', 'test the gRPC Python protoc plugin by running PythonPluginTest to verify stub and servicer generation', 'run the _ServicerMethods class to implement UnaryCall, StreamingOutputCall, StreamingInputCall, FullDuplexCall, and HalfDuplexCall RPC handlers', 'create a gRPC service with _CreateService context manager that yields a servicer backend and client stub pair', 'test incomplete servicer behavior using _CreateIncompleteService to verify UNIMPLEMENTED status code errors', 'review the PythonPluginTest class to understand how all five gRPC call types are tested including futures, timeouts, and cancellation']
```

Usage

```
{'test_grpc_python_plugin_stub_attributes': 'test that the generated gRPC Python module exposes TestServiceStub, TestServiceServicer, and add_TestServiceServicer_to_server', 'test_unary_rpc_call': 'test a unary gRPC call by sending a SimpleRequest and verifying the SimpleResponse payload matches expected size', 'test_streaming_output_rpc': 'test a server-streaming gRPC call that yields multiple StreamingOutputCallResponse messages with configurable payload sizes', 'test_full_duplex_streaming_rpc': 'test a full-duplex streaming gRPC call where client and server exchange messages concurrently via request and response iterators', 'test_simple_stub_sugar_api': 'test the simple stub API that allows calling gRPC methods directly without creating explicit channel and stub objects'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_tests/tests/protoc_plugin/_split_definitions_test.py

Prompts

```
['test that the generated gRPC Python module exposes TestServiceStub, TestServiceServicer, and add_TestServiceServicer_to_server', 'test a unary gRPC call by sending a SimpleRequest and verifying the SimpleResponse payload matches expected size', 'test a server-streaming gRPC call that yields multiple StreamingOutputCallResponse messages with configurable payload sizes', 'test a full-duplex streaming gRPC call where client and server exchange messages concurrently via request and response iterators', 'test the simple stub API that allows calling gRPC methods directly without creating explicit channel and stub objects', 'run the unittest test suite for gRPC protoc plugin split definitions across multiple protoc styles', 'test that generated protobuf modules expose Request, Response, TestServiceStub, and TestServiceServicer attributes', 'test end-to-end gRPC service call using a generated stub, servicer, and insecure channel', 'review the four protoc invocation styles: Mid2016, SingleExecution, ProtoBeforeGrpc, and GrpcBeforeProto', 'summarize the factory function that dynamically creates test case classes for split vs same proto configurations', 'test the gRPC Python protoc plugin by running PythonPluginTest to verify stub and servicer generation', 'run the _ServicerMethods class to implement UnaryCall, StreamingOutputCall, StreamingInputCall, FullDuplexCall, and HalfDuplexCall RPC handlers', 'create a gRPC service with _CreateService context manager that yields a servicer backend and client stub pair', 'test incomplete servicer behavior using _CreateIncompleteService to verify UNIMPLEMENTED status code errors', 'review the PythonPluginTest class to understand how all five gRPC call types are tested including futures, timeouts, and cancellation']
```

Usage

```
{'run_split_definitions_test': 'run the unittest test suite for gRPC protoc plugin split definitions across multiple protoc styles', 'test_imported_attributes': 'test that generated protobuf modules expose Request, Response, TestServiceStub, and TestServiceServicer attributes', 'test_call': 'test end-to-end gRPC service call using a generated stub, servicer, and insecure channel', 'review_protoc_styles': 'review the four protoc invocation styles: Mid2016, SingleExecution, ProtoBeforeGrpc, and GrpcBeforeProto', 'summarize_create_test_case_class': 'summarize the factory function that dynamically creates test case classes for split vs same proto configurations'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_tests/tests/protoc_plugin/beta_python_plugin_test.py

Prompts

```
['test that the generated gRPC Python module exposes TestServiceStub, TestServiceServicer, and add_TestServiceServicer_to_server', 'test a unary gRPC call by sending a SimpleRequest and verifying the SimpleResponse payload matches expected size', 'test a server-streaming gRPC call that yields multiple StreamingOutputCallResponse messages with configurable payload sizes', 'test a full-duplex streaming gRPC call where client and server exchange messages concurrently via request and response iterators', 'test the simple stub API that allows calling gRPC methods directly without creating explicit channel and stub objects', 'run the unittest test suite for gRPC protoc plugin split definitions across multiple protoc styles', 'test that generated protobuf modules expose Request, Response, TestServiceStub, and TestServiceServicer attributes', 'test end-to-end gRPC service call using a generated stub, servicer, and insecure channel', 'review the four protoc invocation styles: Mid2016, SingleExecution, ProtoBeforeGrpc, and GrpcBeforeProto', 'summarize the factory function that dynamically creates test case classes for split vs same proto configurations', 'test the gRPC Python protoc plugin by running PythonPluginTest to verify stub and servicer generation', 'run the _ServicerMethods class to implement UnaryCall, StreamingOutputCall, StreamingInputCall, FullDuplexCall, and HalfDuplexCall RPC handlers', 'create a gRPC service with _CreateService context manager that yields a servicer backend and client stub pair', 'test incomplete servicer behavior using _CreateIncompleteService to verify UNIMPLEMENTED status code errors', 'review the PythonPluginTest class to understand how all five gRPC call types are tested including futures, timeouts, and cancellation']
```

Usage

```
{'test_PythonPluginTest': 'test the gRPC Python protoc plugin by running PythonPluginTest to verify stub and servicer generation', 'run_ServicerMethods': 'run the _ServicerMethods class to implement UnaryCall, StreamingOutputCall, StreamingInputCall, FullDuplexCall, and HalfDuplexCall RPC handlers', 'create_CreateService': 'create a gRPC service with _CreateService context manager that yields a servicer backend and client stub pair', 'test_CreateIncompleteService': 'test incomplete servicer behavior using _CreateIncompleteService to verify UNIMPLEMENTED status code errors', 'review_PythonPluginTest': 'review the PythonPluginTest class to understand how all five gRPC call types are tested including futures, timeouts, and cancellation'}
```

