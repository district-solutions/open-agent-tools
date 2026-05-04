# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/examples/python/errors/client.py

Prompts

```
['run the gRPC client example that handles rich error status on the client side', 'run the process function to call SayHello and handle QuotaFailure errors from the gRPC stub', 'run main to create an insecure gRPC channel on localhost:50051 and invoke the GreeterStub', 'review the process function to understand how rpc_status.from_call extracts error details', 'refactor the process function to handle additional error detail types beyond QuotaFailure', 'run the gRPC server that sends rich error status from the server side on port 50051', 'create a RESOURCE_EXHAUSTED error status with QuotaFailure details for a given name', 'create a gRPC server with a LimitedGreeter servicer bound to the given server address', 'review the LimitedGreeter SayHello method that aborts with rich status on duplicate greetings', 'serve a gRPC server by starting it and waiting for termination']
```

Usage

```
{'run_grpc_error_client': 'run the gRPC client example that handles rich error status on the client side', 'run_process_stub': 'run the process function to call SayHello and handle QuotaFailure errors from the gRPC stub', 'run_main_channel': 'run main to create an insecure gRPC channel on localhost:50051 and invoke the GreeterStub', 'review_process_error_handling': 'review the process function to understand how rpc_status.from_call extracts error details', 'refactor_process_quota_failure': 'refactor the process function to handle additional error detail types beyond QuotaFailure'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/examples/python/errors/server.py

Prompts

```
['run the gRPC client example that handles rich error status on the client side', 'run the process function to call SayHello and handle QuotaFailure errors from the gRPC stub', 'run main to create an insecure gRPC channel on localhost:50051 and invoke the GreeterStub', 'review the process function to understand how rpc_status.from_call extracts error details', 'refactor the process function to handle additional error detail types beyond QuotaFailure', 'run the gRPC server that sends rich error status from the server side on port 50051', 'create a RESOURCE_EXHAUSTED error status with QuotaFailure details for a given name', 'create a gRPC server with a LimitedGreeter servicer bound to the given server address', 'review the LimitedGreeter SayHello method that aborts with rich status on duplicate greetings', 'serve a gRPC server by starting it and waiting for termination']
```

Usage

```
{'run_grpc_error_server': 'run the gRPC server that sends rich error status from the server side on port 50051', 'create_greet_limit_exceed_error_status': 'create a RESOURCE_EXHAUSTED error status with QuotaFailure details for a given name', 'create_server': 'create a gRPC server with a LimitedGreeter servicer bound to the given server address', 'review_LimitedGreeter_SayHello': 'review the LimitedGreeter SayHello method that aborts with rich status on duplicate greetings', 'serve_grpc_server': 'serve a gRPC server by starting it and waiting for termination'}
```

