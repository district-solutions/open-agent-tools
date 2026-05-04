# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/examples/python/metadata/helloworld_pb2_grpc.py

Prompts

```
['create a GreeterStub client using a gRPC channel to call the SayHello RPC method', 'implement a custom GreeterServicer subclass that overrides SayHello to return a greeting response', 'add a GreeterServicer instance to a gRPC server using add_GreeterServicer_to_server', 'review the GreeterStub class to understand how unary_unary RPC calls are configured with serializers', 'test the SayHello RPC method by sending a HelloRequest and verifying the HelloReply response', 'run the gRPC client that sends initial metadata and prints trailing metadata from the server response', 'create an insecure gRPC channel to localhost:50051 using grpc.insecure_channel as a context manager', 'send initial metadata including string and binary key-value pairs with a gRPC SayHello RPC call', 'retrieve trailing metadata from a gRPC call response using call.trailing_metadata()', 'review the run function that demonstrates sending and receiving gRPC metadata via with_call', 'run the gRPC server on port 50051 that reads and sets HTTP2 metadata headers', 'create a Greeter servicer class that handles SayHello RPC calls with metadata support', 'review the SayHello method to see how it reads invocation metadata and sets trailing metadata', 'build a gRPC response that sets trailing metadata like checksum-bin and retry headers', 'test reading initial metadata from the gRPC context using invocation_metadata']
```

Usage

```
{'create_greeter_stub': 'create a GreeterStub client using a gRPC channel to call the SayHello RPC method', 'implement_greeter_servicer': 'implement a custom GreeterServicer subclass that overrides SayHello to return a greeting response', 'add_servicer_to_server': 'add a GreeterServicer instance to a gRPC server using add_GreeterServicer_to_server', 'review_greeter_stub': 'review the GreeterStub class to understand how unary_unary RPC calls are configured with serializers', 'test_say_hello': 'test the SayHello RPC method by sending a HelloRequest and verifying the HelloReply response'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/examples/python/metadata/metadata_client.py

Prompts

```
['create a GreeterStub client using a gRPC channel to call the SayHello RPC method', 'implement a custom GreeterServicer subclass that overrides SayHello to return a greeting response', 'add a GreeterServicer instance to a gRPC server using add_GreeterServicer_to_server', 'review the GreeterStub class to understand how unary_unary RPC calls are configured with serializers', 'test the SayHello RPC method by sending a HelloRequest and verifying the HelloReply response', 'run the gRPC client that sends initial metadata and prints trailing metadata from the server response', 'create an insecure gRPC channel to localhost:50051 using grpc.insecure_channel as a context manager', 'send initial metadata including string and binary key-value pairs with a gRPC SayHello RPC call', 'retrieve trailing metadata from a gRPC call response using call.trailing_metadata()', 'review the run function that demonstrates sending and receiving gRPC metadata via with_call', 'run the gRPC server on port 50051 that reads and sets HTTP2 metadata headers', 'create a Greeter servicer class that handles SayHello RPC calls with metadata support', 'review the SayHello method to see how it reads invocation metadata and sets trailing metadata', 'build a gRPC response that sets trailing metadata like checksum-bin and retry headers', 'test reading initial metadata from the gRPC context using invocation_metadata']
```

Usage

```
{'run_grpc_metadata_client': 'run the gRPC client that sends initial metadata and prints trailing metadata from the server response', 'create_insecure_channel': 'create an insecure gRPC channel to localhost:50051 using grpc.insecure_channel as a context manager', 'send_initial_metadata': 'send initial metadata including string and binary key-value pairs with a gRPC SayHello RPC call', 'retrieve_trailing_metadata': 'retrieve trailing metadata from a gRPC call response using call.trailing_metadata()', 'review_run_function': 'review the run function that demonstrates sending and receiving gRPC metadata via with_call'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/examples/python/metadata/metadata_server.py

Prompts

```
['create a GreeterStub client using a gRPC channel to call the SayHello RPC method', 'implement a custom GreeterServicer subclass that overrides SayHello to return a greeting response', 'add a GreeterServicer instance to a gRPC server using add_GreeterServicer_to_server', 'review the GreeterStub class to understand how unary_unary RPC calls are configured with serializers', 'test the SayHello RPC method by sending a HelloRequest and verifying the HelloReply response', 'run the gRPC client that sends initial metadata and prints trailing metadata from the server response', 'create an insecure gRPC channel to localhost:50051 using grpc.insecure_channel as a context manager', 'send initial metadata including string and binary key-value pairs with a gRPC SayHello RPC call', 'retrieve trailing metadata from a gRPC call response using call.trailing_metadata()', 'review the run function that demonstrates sending and receiving gRPC metadata via with_call', 'run the gRPC server on port 50051 that reads and sets HTTP2 metadata headers', 'create a Greeter servicer class that handles SayHello RPC calls with metadata support', 'review the SayHello method to see how it reads invocation metadata and sets trailing metadata', 'build a gRPC response that sets trailing metadata like checksum-bin and retry headers', 'test reading initial metadata from the gRPC context using invocation_metadata']
```

Usage

```
{'run_grpc_metadata_server': 'run the gRPC server on port 50051 that reads and sets HTTP2 metadata headers', 'create_greeter_servicer': 'create a Greeter servicer class that handles SayHello RPC calls with metadata support', 'review_sayhello_metadata': 'review the SayHello method to see how it reads invocation metadata and sets trailing metadata', 'build_trailing_metadata': 'build a gRPC response that sets trailing metadata like checksum-bin and retry headers', 'test_invocation_metadata': 'test reading initial metadata from the gRPC context using invocation_metadata'}
```

