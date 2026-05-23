# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/examples/python/cancellation/client.py

Prompts

```
['run a gRPC unary client that finds hashes similar to a given name with cancellation support', 'run a gRPC streaming client that finds hashes within a range of distances with cancellation support', 'cancel a gRPC unary request when the user sends a SIGINT signal during execution', 'cancel a gRPC streaming request when the user sends a SIGINT signal during execution', 'run the gRPC cancellation example client with command line arguments for name and distance parameters', 'run the search function to find candidate bytestrings matching a target hash within ideal hamming distance', 'calculate the hamming distance between two equal-length strings using _get_hamming_distance', 'calculate the minimum hamming distance between a target and any substring of a candidate string', 'get the base64-encoded SHA1 hash digest of a secret bytestring using _get_hash', 'generate all bytestrings of a given length using _bytestrings_of_length or all bytestrings via _all_bytestrings', 'run a gRPC server that demonstrates request cancellation with hash name search functionality', 'create a HashFinder servicer class that handles Find and FindRange RPC methods with cancellation support', 'implement the Find method that searches for hash names similar to a desired name with resource limits', 'implement the FindRange method that streams hash name candidates with configurable hamming distance thresholds', 'configure the gRPC server with command line arguments for port and maximum hash search limits']
```

Usage

```
{'run_unary_client': 'run a gRPC unary client that finds hashes similar to a given name with cancellation support', 'run_streaming_client': 'run a gRPC streaming client that finds hashes within a range of distances with cancellation support', 'cancel_request_unary': 'cancel a gRPC unary request when the user sends a SIGINT signal during execution', 'cancel_request_streaming': 'cancel a gRPC streaming request when the user sends a SIGINT signal during execution', 'main': 'run the gRPC cancellation example client with command line arguments for name and distance parameters'}
```

## File: facebookresearch_torchbeast/third_party/grpc/examples/python/cancellation/search.py

Prompts

```
['run a gRPC unary client that finds hashes similar to a given name with cancellation support', 'run a gRPC streaming client that finds hashes within a range of distances with cancellation support', 'cancel a gRPC unary request when the user sends a SIGINT signal during execution', 'cancel a gRPC streaming request when the user sends a SIGINT signal during execution', 'run the gRPC cancellation example client with command line arguments for name and distance parameters', 'run the search function to find candidate bytestrings matching a target hash within ideal hamming distance', 'calculate the hamming distance between two equal-length strings using _get_hamming_distance', 'calculate the minimum hamming distance between a target and any substring of a candidate string', 'get the base64-encoded SHA1 hash digest of a secret bytestring using _get_hash', 'generate all bytestrings of a given length using _bytestrings_of_length or all bytestrings via _all_bytestrings', 'run a gRPC server that demonstrates request cancellation with hash name search functionality', 'create a HashFinder servicer class that handles Find and FindRange RPC methods with cancellation support', 'implement the Find method that searches for hash names similar to a desired name with resource limits', 'implement the FindRange method that streams hash name candidates with configurable hamming distance thresholds', 'configure the gRPC server with command line arguments for port and maximum hash search limits']
```

Usage

```
{'run_search_bytestrings': 'run the search function to find candidate bytestrings matching a target hash within ideal hamming distance', 'calculate_hamming_distance': 'calculate the hamming distance between two equal-length strings using _get_hamming_distance', 'calculate_substring_hamming_distance': 'calculate the minimum hamming distance between a target and any substring of a candidate string', 'get_sha1_hash': 'get the base64-encoded SHA1 hash digest of a secret bytestring using _get_hash', 'generate_bytestrings': 'generate all bytestrings of a given length using _bytestrings_of_length or all bytestrings via _all_bytestrings'}
```

## File: facebookresearch_torchbeast/third_party/grpc/examples/python/cancellation/server.py

Prompts

```
['run a gRPC unary client that finds hashes similar to a given name with cancellation support', 'run a gRPC streaming client that finds hashes within a range of distances with cancellation support', 'cancel a gRPC unary request when the user sends a SIGINT signal during execution', 'cancel a gRPC streaming request when the user sends a SIGINT signal during execution', 'run the gRPC cancellation example client with command line arguments for name and distance parameters', 'run the search function to find candidate bytestrings matching a target hash within ideal hamming distance', 'calculate the hamming distance between two equal-length strings using _get_hamming_distance', 'calculate the minimum hamming distance between a target and any substring of a candidate string', 'get the base64-encoded SHA1 hash digest of a secret bytestring using _get_hash', 'generate all bytestrings of a given length using _bytestrings_of_length or all bytestrings via _all_bytestrings', 'run a gRPC server that demonstrates request cancellation with hash name search functionality', 'create a HashFinder servicer class that handles Find and FindRange RPC methods with cancellation support', 'implement the Find method that searches for hash names similar to a desired name with resource limits', 'implement the FindRange method that streams hash name candidates with configurable hamming distance thresholds', 'configure the gRPC server with command line arguments for port and maximum hash search limits']
```

Usage

```
{'run_grpc_cancellation_server': 'run a gRPC server that demonstrates request cancellation with hash name search functionality', 'create_HashFinder_servicer': 'create a HashFinder servicer class that handles Find and FindRange RPC methods with cancellation support', 'implement_Find_method': 'implement the Find method that searches for hash names similar to a desired name with resource limits', 'implement_FindRange_method': 'implement the FindRange method that streams hash name candidates with configurable hamming distance thresholds', 'configure_server_arguments': 'configure the gRPC server with command line arguments for port and maximum hash search limits'}
```

