# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/examples/python/errors/client.py

Prompts

```
['run the gRPC client that calls SayHello on localhost:50051 and handles rich error status', 'process a gRPC stub by calling SayHello and extracting rpc_status details from RpcError', 'handle QuotaFailure error details by unpacking them from gRPC RpcError status', 'create an insecure gRPC channel to localhost:50051 and instantiate a GreeterStub', 'review the process function that handles gRPC errors and unpacks QuotaFailure details', 'run the gRPC server that sends rich error status from the server side on port 50051', 'create a RESOURCE_EXHAUSTED error status with QuotaFailure details for a given name', 'create a gRPC server with a LimitedGreeter servicer bound to the given server address', 'review the LimitedGreeter SayHello method that aborts with rich status on duplicate greetings', 'serve a gRPC server by starting it and waiting for termination']
```

Usage

```
{'run_grpc_client': 'run the gRPC client that calls SayHello on localhost:50051 and handles rich error status', 'process_grpc_stub': 'process a gRPC stub by calling SayHello and extracting rpc_status details from RpcError', 'handle_quota_failure': 'handle QuotaFailure error details by unpacking them from gRPC RpcError status', 'create_insecure_channel': 'create an insecure gRPC channel to localhost:50051 and instantiate a GreeterStub', 'review_process_function': 'review the process function that handles gRPC errors and unpacks QuotaFailure details'}
```

## File: facebookresearch_torchbeast/third_party/grpc/examples/python/errors/server.py

Prompts

```
['run the gRPC client that calls SayHello on localhost:50051 and handles rich error status', 'process a gRPC stub by calling SayHello and extracting rpc_status details from RpcError', 'handle QuotaFailure error details by unpacking them from gRPC RpcError status', 'create an insecure gRPC channel to localhost:50051 and instantiate a GreeterStub', 'review the process function that handles gRPC errors and unpacks QuotaFailure details', 'run the gRPC server that sends rich error status from the server side on port 50051', 'create a RESOURCE_EXHAUSTED error status with QuotaFailure details for a given name', 'create a gRPC server with a LimitedGreeter servicer bound to the given server address', 'review the LimitedGreeter SayHello method that aborts with rich status on duplicate greetings', 'serve a gRPC server by starting it and waiting for termination']
```

Usage

```
{'run_grpc_error_server': 'run the gRPC server that sends rich error status from the server side on port 50051', 'create_greet_limit_exceed_error_status': 'create a RESOURCE_EXHAUSTED error status with QuotaFailure details for a given name', 'create_server': 'create a gRPC server with a LimitedGreeter servicer bound to the given server address', 'review_LimitedGreeter_SayHello': 'review the LimitedGreeter SayHello method that aborts with rich status on duplicate greetings', 'serve_grpc_server': 'serve a gRPC server by starting it and waiting for termination'}
```

