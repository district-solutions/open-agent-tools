# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/examples/python/cancellation/client.py

Prompts

```
['run a unary gRPC client that finds hashes similar to a given name with a specified Hamming distance', 'run a streaming gRPC client that finds hashes within a range of Hamming distances from a name', 'cancel a pending unary gRPC request by sending SIGINT to the running client process', 'cancel an active streaming gRPC request by sending SIGINT to the running client process', 'run the gRPC cancellation client CLI with a name, ideal distance, and optional server target', 'run the search function to find bytestrings whose SHA1 hash matches a target within a Hamming distance threshold', 'create a function that calculates the Hamming distance between two equal-length strings by counting differing characters', 'test the substring Hamming distance function to find the minimum distance between a target and any substring of a candidate', 'review the search function and ResourceLimitExceededError to understand how maximum hash computation limits are enforced', 'summarize the bytestrings generator that yields all possible bytestrings in ascending order of length using itertools', 'run a gRPC server that demonstrates cancelling long-running RPC requests on a configurable port', 'build a unary gRPC RPC that finds hash names similar to a desired name with hamming distance', 'build a server-streaming gRPC RPC that yields hash name candidates matching a hamming distance range', 'test the HashFinder servicer to verify RPC cancellation when resource limits are exceeded', 'review the HashFinder class and its use of threading events and context callbacks for cancellation']
```

Usage

```
{'run_unary_client': 'run a unary gRPC client that finds hashes similar to a given name with a specified Hamming distance', 'run_streaming_client': 'run a streaming gRPC client that finds hashes within a range of Hamming distances from a name', 'cancel_unary_request': 'cancel a pending unary gRPC request by sending SIGINT to the running client process', 'cancel_streaming_request': 'cancel an active streaming gRPC request by sending SIGINT to the running client process', 'main_cli': 'run the gRPC cancellation client CLI with a name, ideal distance, and optional server target'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/examples/python/cancellation/search.py

Prompts

```
['run a unary gRPC client that finds hashes similar to a given name with a specified Hamming distance', 'run a streaming gRPC client that finds hashes within a range of Hamming distances from a name', 'cancel a pending unary gRPC request by sending SIGINT to the running client process', 'cancel an active streaming gRPC request by sending SIGINT to the running client process', 'run the gRPC cancellation client CLI with a name, ideal distance, and optional server target', 'run the search function to find bytestrings whose SHA1 hash matches a target within a Hamming distance threshold', 'create a function that calculates the Hamming distance between two equal-length strings by counting differing characters', 'test the substring Hamming distance function to find the minimum distance between a target and any substring of a candidate', 'review the search function and ResourceLimitExceededError to understand how maximum hash computation limits are enforced', 'summarize the bytestrings generator that yields all possible bytestrings in ascending order of length using itertools', 'run a gRPC server that demonstrates cancelling long-running RPC requests on a configurable port', 'build a unary gRPC RPC that finds hash names similar to a desired name with hamming distance', 'build a server-streaming gRPC RPC that yields hash name candidates matching a hamming distance range', 'test the HashFinder servicer to verify RPC cancellation when resource limits are exceeded', 'review the HashFinder class and its use of threading events and context callbacks for cancellation']
```

Usage

```
{'run_search_bytestrings': 'run the search function to find bytestrings whose SHA1 hash matches a target within a Hamming distance threshold', 'create_hamming_distance_calc': 'create a function that calculates the Hamming distance between two equal-length strings by counting differing characters', 'test_substring_hamming_distance': 'test the substring Hamming distance function to find the minimum distance between a target and any substring of a candidate', 'review_search_resource_limits': 'review the search function and ResourceLimitExceededError to understand how maximum hash computation limits are enforced', 'summarize_bytestrings_generator': 'summarize the bytestrings generator that yields all possible bytestrings in ascending order of length using itertools'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/examples/python/cancellation/server.py

Prompts

```
['run a unary gRPC client that finds hashes similar to a given name with a specified Hamming distance', 'run a streaming gRPC client that finds hashes within a range of Hamming distances from a name', 'cancel a pending unary gRPC request by sending SIGINT to the running client process', 'cancel an active streaming gRPC request by sending SIGINT to the running client process', 'run the gRPC cancellation client CLI with a name, ideal distance, and optional server target', 'run the search function to find bytestrings whose SHA1 hash matches a target within a Hamming distance threshold', 'create a function that calculates the Hamming distance between two equal-length strings by counting differing characters', 'test the substring Hamming distance function to find the minimum distance between a target and any substring of a candidate', 'review the search function and ResourceLimitExceededError to understand how maximum hash computation limits are enforced', 'summarize the bytestrings generator that yields all possible bytestrings in ascending order of length using itertools', 'run a gRPC server that demonstrates cancelling long-running RPC requests on a configurable port', 'build a unary gRPC RPC that finds hash names similar to a desired name with hamming distance', 'build a server-streaming gRPC RPC that yields hash name candidates matching a hamming distance range', 'test the HashFinder servicer to verify RPC cancellation when resource limits are exceeded', 'review the HashFinder class and its use of threading events and context callbacks for cancellation']
```

Usage

```
{'run_grpc_cancellation_server': 'run a gRPC server that demonstrates cancelling long-running RPC requests on a configurable port', 'build_HashFinder_Find': 'build a unary gRPC RPC that finds hash names similar to a desired name with hamming distance', 'build_HashFinder_FindRange': 'build a server-streaming gRPC RPC that yields hash name candidates matching a hamming distance range', 'test_HashFinder_resource_cancellation': 'test the HashFinder servicer to verify RPC cancellation when resource limits are exceeded', 'review_HashFinder_stop_event_callback': 'review the HashFinder class and its use of threading events and context callbacks for cancellation'}
```

