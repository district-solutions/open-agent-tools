# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/bazel/test/python_test_repo/helloworld.py

Prompts

```
['run the gRPC Greeter server using _listening_server context manager on localhost', 'test the Greeter SayHello method by sending a HelloRequest and verifying the response message', 'create a Greeter servicer that responds to SayHello requests with a greeting and request duration', 'review the ImportTest class that tests gRPC client-server communication with timestamp tracking', 'summarize the _listening_server context manager that starts and stops a gRPC server on a dynamic port', 'refactor the Greeter SayHello method to compute request in-flight duration from timestamp']
```

Usage

```
{'run_greeter_server': 'run the gRPC Greeter server using _listening_server context manager on localhost', 'test_SayHello': 'test the Greeter SayHello method by sending a HelloRequest and verifying the response message', 'create_Greeter_servicer': 'create a Greeter servicer that responds to SayHello requests with a greeting and request duration', 'review_ImportTest': 'review the ImportTest class that tests gRPC client-server communication with timestamp tracking', 'summarize_listening_server': 'summarize the _listening_server context manager that starts and stops a gRPC server on a dynamic port'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/bazel/test/python_test_repo/helloworld_moved.py

Prompts

```
['run the gRPC Greeter server using _listening_server context manager on localhost', 'test the Greeter SayHello method by sending a HelloRequest and verifying the response message', 'create a Greeter servicer that responds to SayHello requests with a greeting and request duration', 'review the ImportTest class that tests gRPC client-server communication with timestamp tracking', 'summarize the _listening_server context manager that starts and stops a gRPC server on a dynamic port', 'refactor the Greeter SayHello method to compute request in-flight duration from timestamp']
```

Usage

```
{'run_greeter_server': 'run the gRPC Greeter server using _listening_server context manager on localhost', 'test_SayHello': 'test the Greeter SayHello RPC method returns Hello reply with request duration', 'create_Greeter_servicer': 'create a Greeter servicer class that extends GreeterServicer and implements SayHello', 'review_ImportTest': 'review the ImportTest unittest class that validates the gRPC helloworld client and server', 'refactor_SayHello': 'refactor the Greeter SayHello method to compute request in-flight duration from timestamp'}
```

