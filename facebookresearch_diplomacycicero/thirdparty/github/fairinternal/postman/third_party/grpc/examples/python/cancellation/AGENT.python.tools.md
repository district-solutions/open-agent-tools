# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/examples/python/cancellation/client.py

Prompts

```
['run a unary gRPC client that finds hashes similar to a given name with cancellation support', 'run a streaming gRPC client that finds hash ranges with a specified interesting Hamming distance', 'cancel an in-flight gRPC request when the user sends a SIGINT signal via Ctrl+C', 'review the run_unary_client function that creates a gRPC stub and sends a Find request with wait_for_ready', 'review the run_streaming_client function that streams FindRange results and supports SIGINT cancellation', 'run the search function to find bytestrings whose SHA1 hash matches a target within a Hamming distance threshold', 'create a function that calculates the Hamming distance between two equal-length strings by counting differing characters', 'test the substring Hamming distance function to find the minimum distance between a target and any substring of a candidate', 'review the search function and ResourceLimitExceededError to understand how maximum hash computation limits are enforced', 'summarize the bytestrings generator that yields all possible bytestrings in ascending order of length', 'run a gRPC server that demonstrates cancelling long-running RPC requests on a configurable port', 'run the HashFinder Find RPC to search for a hash similar to a desired name', 'run the HashFinder FindRange streaming RPC to find hashes within a hamming distance range', 'review the HashFinder gRPC servicer class that handles cancellation via threading events', 'refactor the gRPC server setup to use multiple worker threads instead of a single servicer thread']
```

Usage

```
{'run_unary_grpc_client': 'run a unary gRPC client that finds hashes similar to a given name with cancellation support', 'run_streaming_grpc_client': 'run a streaming gRPC client that finds hash ranges with a specified interesting Hamming distance', 'cancel_grpc_request_on_sigint': 'cancel an in-flight gRPC request when the user sends a SIGINT signal via Ctrl+C', 'review_run_unary_client': 'review the run_unary_client function that creates a gRPC stub and sends a Find request with wait_for_ready', 'review_run_streaming_client': 'review the run_streaming_client function that streams FindRange results and supports SIGINT cancellation'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/examples/python/cancellation/search.py

Prompts

```
['run a unary gRPC client that finds hashes similar to a given name with cancellation support', 'run a streaming gRPC client that finds hash ranges with a specified interesting Hamming distance', 'cancel an in-flight gRPC request when the user sends a SIGINT signal via Ctrl+C', 'review the run_unary_client function that creates a gRPC stub and sends a Find request with wait_for_ready', 'review the run_streaming_client function that streams FindRange results and supports SIGINT cancellation', 'run the search function to find bytestrings whose SHA1 hash matches a target within a Hamming distance threshold', 'create a function that calculates the Hamming distance between two equal-length strings by counting differing characters', 'test the substring Hamming distance function to find the minimum distance between a target and any substring of a candidate', 'review the search function and ResourceLimitExceededError to understand how maximum hash computation limits are enforced', 'summarize the bytestrings generator that yields all possible bytestrings in ascending order of length', 'run a gRPC server that demonstrates cancelling long-running RPC requests on a configurable port', 'run the HashFinder Find RPC to search for a hash similar to a desired name', 'run the HashFinder FindRange streaming RPC to find hashes within a hamming distance range', 'review the HashFinder gRPC servicer class that handles cancellation via threading events', 'refactor the gRPC server setup to use multiple worker threads instead of a single servicer thread']
```

Usage

```
{'run_search_bytestrings': 'run the search function to find bytestrings whose SHA1 hash matches a target within a Hamming distance threshold', 'create_hamming_distance_calc': 'create a function that calculates the Hamming distance between two equal-length strings by counting differing characters', 'test_substring_hamming_distance': 'test the substring Hamming distance function to find the minimum distance between a target and any substring of a candidate', 'review_search_resource_limits': 'review the search function and ResourceLimitExceededError to understand how maximum hash computation limits are enforced', 'summarize_bytestrings_generator': 'summarize the bytestrings generator that yields all possible bytestrings in ascending order of length'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/examples/python/cancellation/server.py

Prompts

```
['run a unary gRPC client that finds hashes similar to a given name with cancellation support', 'run a streaming gRPC client that finds hash ranges with a specified interesting Hamming distance', 'cancel an in-flight gRPC request when the user sends a SIGINT signal via Ctrl+C', 'review the run_unary_client function that creates a gRPC stub and sends a Find request with wait_for_ready', 'review the run_streaming_client function that streams FindRange results and supports SIGINT cancellation', 'run the search function to find bytestrings whose SHA1 hash matches a target within a Hamming distance threshold', 'create a function that calculates the Hamming distance between two equal-length strings by counting differing characters', 'test the substring Hamming distance function to find the minimum distance between a target and any substring of a candidate', 'review the search function and ResourceLimitExceededError to understand how maximum hash computation limits are enforced', 'summarize the bytestrings generator that yields all possible bytestrings in ascending order of length', 'run a gRPC server that demonstrates cancelling long-running RPC requests on a configurable port', 'run the HashFinder Find RPC to search for a hash similar to a desired name', 'run the HashFinder FindRange streaming RPC to find hashes within a hamming distance range', 'review the HashFinder gRPC servicer class that handles cancellation via threading events', 'refactor the gRPC server setup to use multiple worker threads instead of a single servicer thread']
```

Usage

```
{'run_grpc_cancellation_server': 'run a gRPC server that demonstrates cancelling long-running RPC requests on a configurable port', 'run_HashFinder_Find': 'run the HashFinder Find RPC to search for a hash similar to a desired name', 'run_HashFinder_FindRange': 'run the HashFinder FindRange streaming RPC to find hashes within a hamming distance range', 'review_HashFinder_class': 'review the HashFinder gRPC servicer class that handles cancellation via threading events', 'refactor_running_server': 'refactor the gRPC server setup to use multiple worker threads instead of a single servicer thread'}
```

