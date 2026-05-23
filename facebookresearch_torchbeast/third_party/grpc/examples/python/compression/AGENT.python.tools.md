# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/examples/python/compression/client.py

Prompts

```
['run a gRPC client with channel and call level compression options against a server', 'run the gRPC client with gzip compression on both channel and individual calls', 'run the gRPC client with deflate compression on the channel and no compression on calls', 'run the gRPC client with no compression to a localhost server on port 50051', 'run the gRPC client with gzip compression against a custom server host and port', 'run a gRPC server with gzip or deflate compression on a specified port', 'run the gRPC server with no compression enabled on the default port 50051', 'run the gRPC server and suppress compression on every nth response', 'review the Greeter class SayHello method that returns HelloReply with optional compression suppression', 'review the Greeter class _should_suppress_compression method that uses a thread-safe counter to decide compression']
```

Usage

```
{'run_client_with_compression': 'run a gRPC client with channel and call level compression options against a server', 'run_client_gzip': 'run the gRPC client with gzip compression on both channel and individual calls', 'run_client_deflate': 'run the gRPC client with deflate compression on the channel and no compression on calls', 'run_client_no_compression': 'run the gRPC client with no compression to a localhost server on port 50051', 'run_client_custom_server': 'run the gRPC client with gzip compression against a custom server host and port'}
```

## File: facebookresearch_torchbeast/third_party/grpc/examples/python/compression/server.py

Prompts

```
['run a gRPC client with channel and call level compression options against a server', 'run the gRPC client with gzip compression on both channel and individual calls', 'run the gRPC client with deflate compression on the channel and no compression on calls', 'run the gRPC client with no compression to a localhost server on port 50051', 'run the gRPC client with gzip compression against a custom server host and port', 'run a gRPC server with gzip or deflate compression on a specified port', 'run the gRPC server with no compression enabled on the default port 50051', 'run the gRPC server and suppress compression on every nth response', 'review the Greeter class SayHello method that returns HelloReply with optional compression suppression', 'review the Greeter class _should_suppress_compression method that uses a thread-safe counter to decide compression']
```

Usage

```
{'run_grpc_compression_server': 'run a gRPC server with gzip or deflate compression on a specified port', 'run_server_with_no_compression': 'run the gRPC server with no compression enabled on the default port 50051', 'run_server_selective_compression': 'run the gRPC server and suppress compression on every nth response', 'review_Greeter_SayHello': 'review the Greeter class SayHello method that returns HelloReply with optional compression suppression', 'review_Greeter_should_suppress_compression': 'review the Greeter class _should_suppress_compression method that uses a thread-safe counter to decide compression'}
```

