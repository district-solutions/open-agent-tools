# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/examples/python/errors/client.py

Prompts

```
['run a gRPC client that calls SayHello and handles rich error status on the response', 'process a gRPC stub call and extract QuotaFailure details from rpc_status on RpcError', 'create an insecure gRPC channel to localhost:50051 and build a GreeterStub from it', 'review the process function that handles gRPC RpcError and unpacks QuotaFailure error details', 'refactor the process function to handle additional error detail types beyond QuotaFailure', 'run the gRPC server that sends rich error status from the server side on port 50051', 'create a RESOURCE_EXHAUSTED error status with QuotaFailure details for a given name', 'create a gRPC server with a LimitedGreeter servicer bound to the given server address', 'review the LimitedGreeter SayHello method that aborts with rich status on repeated greetings', 'serve a gRPC server by starting it and waiting for termination']
```

Usage

```
{'run_grpc_client': 'run a gRPC client that calls SayHello and handles rich error status on the response', 'process_rpc_error': 'process a gRPC stub call and extract QuotaFailure details from rpc_status on RpcError', 'create_insecure_channel': 'create an insecure gRPC channel to localhost:50051 and build a GreeterStub from it', 'review_process_function': 'review the process function that handles gRPC RpcError and unpacks QuotaFailure error details', 'refactor_error_handling': 'refactor the process function to handle additional error detail types beyond QuotaFailure'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/examples/python/errors/server.py

Prompts

```
['run a gRPC client that calls SayHello and handles rich error status on the response', 'process a gRPC stub call and extract QuotaFailure details from rpc_status on RpcError', 'create an insecure gRPC channel to localhost:50051 and build a GreeterStub from it', 'review the process function that handles gRPC RpcError and unpacks QuotaFailure error details', 'refactor the process function to handle additional error detail types beyond QuotaFailure', 'run the gRPC server that sends rich error status from the server side on port 50051', 'create a RESOURCE_EXHAUSTED error status with QuotaFailure details for a given name', 'create a gRPC server with a LimitedGreeter servicer bound to the given server address', 'review the LimitedGreeter SayHello method that aborts with rich status on repeated greetings', 'serve a gRPC server by starting it and waiting for termination']
```

Usage

```
{'run_grpc_server': 'run the gRPC server that sends rich error status from the server side on port 50051', 'create_greet_limit_exceed_error_status': 'create a RESOURCE_EXHAUSTED error status with QuotaFailure details for a given name', 'create_server': 'create a gRPC server with a LimitedGreeter servicer bound to the given server address', 'review_LimitedGreeter_SayHello': 'review the LimitedGreeter SayHello method that aborts with rich status on repeated greetings', 'serve_grpc_server': 'serve a gRPC server by starting it and waiting for termination'}
```

