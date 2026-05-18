# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/examples/python/metadata/helloworld_pb2_grpc.py

Prompts

```
['create a GreeterStub client from a gRPC channel to call SayHello remotely', 'implement a GreeterServicer subclass that overrides SayHello to return a greeting response', 'add a GreeterServicer instance to a gRPC server using add_GreeterServicer_to_server', 'review the GreeterStub class and its unary_unary channel binding for the SayHello RPC', 'test a custom GreeterServicer subclass to verify SayHello returns the expected HelloReply', 'run the gRPC client that sends metadata headers to a Greeter service on localhost:50051', 'create an insecure gRPC channel to localhost:50051 using grpc.insecure_channel as a context manager', 'send custom string and binary metadata headers with a gRPC SayHello RPC call using with_call', 'read trailing metadata from a gRPC call response using call.trailing_metadata', 'review the run function that demonstrates gRPC metadata passing with initial and trailing headers', 'run the gRPC Greeter server on port 50051 that handles SayHello RPC calls', 'review the Greeter class SayHello method that reads invocation metadata and sets trailing metadata', 'build a gRPC server that reads initial metadata and sets trailing metadata on responses', 'test the Greeter SayHello method to verify it returns HelloReply with the request name', 'refactor the serve function to use a secure port instead of add_insecure_port']
```

Usage

```
{'create_greeter_stub': 'create a GreeterStub client from a gRPC channel to call SayHello remotely', 'implement_greeter_servicer': 'implement a GreeterServicer subclass that overrides SayHello to return a greeting response', 'add_servicer_to_server': 'add a GreeterServicer instance to a gRPC server using add_GreeterServicer_to_server', 'review_greeter_stub': 'review the GreeterStub class and its unary_unary channel binding for the SayHello RPC', 'test_greeter_servicer': 'test a custom GreeterServicer subclass to verify SayHello returns the expected HelloReply'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/examples/python/metadata/metadata_client.py

Prompts

```
['create a GreeterStub client from a gRPC channel to call SayHello remotely', 'implement a GreeterServicer subclass that overrides SayHello to return a greeting response', 'add a GreeterServicer instance to a gRPC server using add_GreeterServicer_to_server', 'review the GreeterStub class and its unary_unary channel binding for the SayHello RPC', 'test a custom GreeterServicer subclass to verify SayHello returns the expected HelloReply', 'run the gRPC client that sends metadata headers to a Greeter service on localhost:50051', 'create an insecure gRPC channel to localhost:50051 using grpc.insecure_channel as a context manager', 'send custom string and binary metadata headers with a gRPC SayHello RPC call using with_call', 'read trailing metadata from a gRPC call response using call.trailing_metadata', 'review the run function that demonstrates gRPC metadata passing with initial and trailing headers', 'run the gRPC Greeter server on port 50051 that handles SayHello RPC calls', 'review the Greeter class SayHello method that reads invocation metadata and sets trailing metadata', 'build a gRPC server that reads initial metadata and sets trailing metadata on responses', 'test the Greeter SayHello method to verify it returns HelloReply with the request name', 'refactor the serve function to use a secure port instead of add_insecure_port']
```

Usage

```
{'run_grpc_metadata_client': 'run the gRPC client that sends metadata headers to a Greeter service on localhost:50051', 'create_grpc_insecure_channel': 'create an insecure gRPC channel to localhost:50051 using grpc.insecure_channel as a context manager', 'send_metadata_with_rpc_call': 'send custom string and binary metadata headers with a gRPC SayHello RPC call using with_call', 'read_trailing_metadata': 'read trailing metadata from a gRPC call response using call.trailing_metadata', 'review_run_function': 'review the run function that demonstrates gRPC metadata passing with initial and trailing headers'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/examples/python/metadata/metadata_server.py

Prompts

```
['create a GreeterStub client from a gRPC channel to call SayHello remotely', 'implement a GreeterServicer subclass that overrides SayHello to return a greeting response', 'add a GreeterServicer instance to a gRPC server using add_GreeterServicer_to_server', 'review the GreeterStub class and its unary_unary channel binding for the SayHello RPC', 'test a custom GreeterServicer subclass to verify SayHello returns the expected HelloReply', 'run the gRPC client that sends metadata headers to a Greeter service on localhost:50051', 'create an insecure gRPC channel to localhost:50051 using grpc.insecure_channel as a context manager', 'send custom string and binary metadata headers with a gRPC SayHello RPC call using with_call', 'read trailing metadata from a gRPC call response using call.trailing_metadata', 'review the run function that demonstrates gRPC metadata passing with initial and trailing headers', 'run the gRPC Greeter server on port 50051 that handles SayHello RPC calls', 'review the Greeter class SayHello method that reads invocation metadata and sets trailing metadata', 'build a gRPC server that reads initial metadata and sets trailing metadata on responses', 'test the Greeter SayHello method to verify it returns HelloReply with the request name', 'refactor the serve function to use a secure port instead of add_insecure_port']
```

Usage

```
{'run_greeter_server': 'run the gRPC Greeter server on port 50051 that handles SayHello RPC calls', 'review_Greeter_SayHello': 'review the Greeter class SayHello method that reads invocation metadata and sets trailing metadata', 'build_gRPC_metadata_server': 'build a gRPC server that reads initial metadata and sets trailing metadata on responses', 'test_Greeter_SayHello': 'test the Greeter SayHello method to verify it returns HelloReply with the request name', 'refactor_serve': 'refactor the serve function to use a secure port instead of add_insecure_port'}
```

