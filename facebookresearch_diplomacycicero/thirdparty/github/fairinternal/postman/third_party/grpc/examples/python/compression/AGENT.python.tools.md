# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/examples/python/compression/client.py

Prompts

```
['run a gRPC client with channel and call compression options against a target server', 'run the gRPC client using gzip compression for both channel and individual RPC calls', 'run the gRPC client using deflate compression for channel-level data compression', 'run the gRPC client with no compression enabled on the channel or calls', 'run the gRPC client against a custom server host and port with chosen compression', 'run a gRPC server with gzip or deflate compression on a specified port', 'run the gRPC server with no compression using the default settings', 'run the gRPC server that skips compression on every nth response', 'review the Greeter class SayHello method that returns a HelloReply with optional compression suppression', 'review the Greeter _should_suppress_compression method that uses a thread-safe counter to decide compression']
```

Usage

```
{'run_client_with_compression': 'run a gRPC client with channel and call compression options against a target server', 'run_client_gzip': 'run the gRPC client using gzip compression for both channel and individual RPC calls', 'run_client_deflate': 'run the gRPC client using deflate compression for channel-level data compression', 'run_client_no_compression': 'run the gRPC client with no compression enabled on the channel or calls', 'run_client_custom_server': 'run the gRPC client against a custom server host and port with chosen compression'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/examples/python/compression/server.py

Prompts

```
['run a gRPC client with channel and call compression options against a target server', 'run the gRPC client using gzip compression for both channel and individual RPC calls', 'run the gRPC client using deflate compression for channel-level data compression', 'run the gRPC client with no compression enabled on the channel or calls', 'run the gRPC client against a custom server host and port with chosen compression', 'run a gRPC server with gzip or deflate compression on a specified port', 'run the gRPC server with no compression using the default settings', 'run the gRPC server that skips compression on every nth response', 'review the Greeter class SayHello method that returns a HelloReply with optional compression suppression', 'review the Greeter _should_suppress_compression method that uses a thread-safe counter to decide compression']
```

Usage

```
{'run_grpc_compression_server': 'run a gRPC server with gzip or deflate compression on a specified port', 'run_server_with_no_compression': 'run the gRPC server with no compression using the default settings', 'run_server_selective_compression': 'run the gRPC server that skips compression on every nth response', 'review_Greeter_SayHello': 'review the Greeter class SayHello method that returns a HelloReply with optional compression suppression', 'review_Greeter_should_suppress_compression': 'review the Greeter _should_suppress_compression method that uses a thread-safe counter to decide compression'}
```

