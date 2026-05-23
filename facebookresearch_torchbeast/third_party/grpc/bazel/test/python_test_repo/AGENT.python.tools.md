# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/bazel/test/python_test_repo/helloworld.py

Prompts

```
['run a gRPC Greeter server that responds to SayHello requests with a greeting message', 'test the Greeter client by sending a HelloRequest and verifying the response message', 'create a Greeter servicer class that implements the SayHello RPC method', 'review the Greeter servicer to see how it calculates request duration from timestamps', 'summarize the _listening_server context manager that starts and stops a gRPC server', 'create a GreeterStub client to call the SayHello RPC method on a gRPC channel', 'review the Greeter servicer implementation that calculates request duration and returns HelloReply', 'test the gRPC import and client-server communication using the ImportTest unittest class']
```

Usage

```
{'run_greeter_server': 'run a gRPC Greeter server that responds to SayHello requests with a greeting message', 'test_greeter_client': 'test the Greeter client by sending a HelloRequest and verifying the response message', 'create_greeter_servicer': 'create a Greeter servicer class that implements the SayHello RPC method', 'review_request_duration': 'review the Greeter servicer to see how it calculates request duration from timestamps', 'summarize_listening_server': 'summarize the _listening_server context manager that starts and stops a gRPC server'}
```

## File: facebookresearch_torchbeast/third_party/grpc/bazel/test/python_test_repo/helloworld_moved.py

Prompts

```
['run a gRPC Greeter server that responds to SayHello requests with a greeting message', 'test the Greeter client by sending a HelloRequest and verifying the response message', 'create a Greeter servicer class that implements the SayHello RPC method', 'review the Greeter servicer to see how it calculates request duration from timestamps', 'summarize the _listening_server context manager that starts and stops a gRPC server', 'create a GreeterStub client to call the SayHello RPC method on a gRPC channel', 'review the Greeter servicer implementation that calculates request duration and returns HelloReply', 'test the gRPC import and client-server communication using the ImportTest unittest class']
```

Usage

```
{'test_greeter_client': 'test the Greeter gRPC client by sending a HelloRequest and verifying the response message', 'run_greeter_server': 'run a gRPC server with the Greeter servicer that responds to SayHello requests', 'create_greeter_stub': 'create a GreeterStub client to call the SayHello RPC method on a gRPC channel', 'review_greeter_servicer': 'review the Greeter servicer implementation that calculates request duration and returns HelloReply', 'test_grpc_import': 'test the gRPC import and client-server communication using the ImportTest unittest class'}
```

