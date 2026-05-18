# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/examples/python/compression/client.py

Prompts

```
['run the gRPC client with gzip compression on the channel to a localhost server', 'run the gRPC client with deflate compression on individual calls to a remote server', 'run the gRPC client with no compression to connect to a helloworld server', 'review the run_client function that creates an insecure channel and calls SayHello with compression', 'refactor the _COMPRESSION_OPTIONS dictionary to add a new compression algorithm like zstd', 'run a gRPC server with gzip or deflate compression on a specified port', 'run the gRPC server with no compression enabled on port 50051', 'run the gRPC server that skips compression every nth response', 'review the Greeter class SayHello method that returns a HelloReply with optional compression suppression', 'review the Greeter _should_suppress_compression method that uses a thread-safe counter to decide compression']
```

Usage

```
{'run_client_with_gzip_compression': 'run the gRPC client with gzip compression on the channel to a localhost server', 'run_client_with_deflate_compression': 'run the gRPC client with deflate compression on individual calls to a remote server', 'run_client_no_compression': 'run the gRPC client with no compression to connect to a helloworld server', 'review_run_client_function': 'review the run_client function that creates an insecure channel and calls SayHello with compression', 'refactor_compression_options': 'refactor the _COMPRESSION_OPTIONS dictionary to add a new compression algorithm like zstd'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/examples/python/compression/server.py

Prompts

```
['run the gRPC client with gzip compression on the channel to a localhost server', 'run the gRPC client with deflate compression on individual calls to a remote server', 'run the gRPC client with no compression to connect to a helloworld server', 'review the run_client function that creates an insecure channel and calls SayHello with compression', 'refactor the _COMPRESSION_OPTIONS dictionary to add a new compression algorithm like zstd', 'run a gRPC server with gzip or deflate compression on a specified port', 'run the gRPC server with no compression enabled on port 50051', 'run the gRPC server that skips compression every nth response', 'review the Greeter class SayHello method that returns a HelloReply with optional compression suppression', 'review the Greeter _should_suppress_compression method that uses a thread-safe counter to decide compression']
```

Usage

```
{'run_grpc_compression_server': 'run a gRPC server with gzip or deflate compression on a specified port', 'run_server_with_no_compression': 'run the gRPC server with no compression enabled on port 50051', 'run_server_selective_compression': 'run the gRPC server that skips compression every nth response', 'review_Greeter_SayHello': 'review the Greeter class SayHello method that returns a HelloReply with optional compression suppression', 'review_Greeter_should_suppress_compression': 'review the Greeter _should_suppress_compression method that uses a thread-safe counter to decide compression'}
```

