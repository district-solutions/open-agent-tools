# Agent Python Tools

- repo: facebookresearch/distributed-faiss
- repo_uri: https://github.com/facebookresearch/distributed-faiss

## File: facebookresearch_distributed-faiss/tests/test_client.py

Prompts

```
['test the IndexClient.read_server_list method by reading a server list file and validating hostname and port tuples', 'test the IndexClient.read_server_list method with total_max_timeout=0 to verify it raises an exception on mismatched server counts', 'run the TestClient unittest suite to verify IndexClient.read_server_list parses server list files correctly', 'review the TestClient class and its test_read_server_list method to understand server list parsing assertions', 'refactor the TestClient test_read_server_list method to add additional edge case assertions for malformed server list files', 'test the IndexState.get_aggregated_states method with mixed training states', 'test the IndexState enum values NOT_TRAINED TRAINING ADD and TRAINED', 'run the TestIndexState unittest suite for distributed FAISS index state aggregation', 'review the IndexState.get_aggregated_states logic for consistency across distributed nodes', 'refactor the TestIndexState tests to cover edge cases like empty state lists', 'create a flat index with IndexClient, add embeddings, train, and search for nearest neighbors', 'test that data is balanced across multiple IndexServer instances when using IndexClient with multiple ports', 'run the unittest test suite to verify IndexServer, IndexClient, and IndexCfg integration behavior', 'load batched random embeddings and metadata into a distributed FAISS index using load_batched_data', 'aggregate search results from multiple servers using IndexClient._aggregate_results to find min or max distances', 'run a distributed FAISS RPC client that creates an index, adds data, trains, and searches', 'add random training data to a distributed FAISS client index using torch tensors', 'trigger async training on a distributed FAISS client index', 'test a single FAISS server with 10 parallel client processes using multiprocessing', 'test a single FAISS server with 10 in-process clients adding data and searching']
```

Usage

```
{'test_read_server_list': 'test the IndexClient.read_server_list method by reading a server list file and validating hostname and port tuples', 'test_read_server_list_timeout': 'test the IndexClient.read_server_list method with total_max_timeout=0 to verify it raises an exception on mismatched server counts', 'run_test_client': 'run the TestClient unittest suite to verify IndexClient.read_server_list parses server list files correctly', 'review_test_client': 'review the TestClient class and its test_read_server_list method to understand server list parsing assertions', 'refactor_test_client': 'refactor the TestClient test_read_server_list method to add additional edge case assertions for malformed server list files'}
```

## File: facebookresearch_distributed-faiss/tests/test_index_state.py

Prompts

```
['test the IndexClient.read_server_list method by reading a server list file and validating hostname and port tuples', 'test the IndexClient.read_server_list method with total_max_timeout=0 to verify it raises an exception on mismatched server counts', 'run the TestClient unittest suite to verify IndexClient.read_server_list parses server list files correctly', 'review the TestClient class and its test_read_server_list method to understand server list parsing assertions', 'refactor the TestClient test_read_server_list method to add additional edge case assertions for malformed server list files', 'test the IndexState.get_aggregated_states method with mixed training states', 'test the IndexState enum values NOT_TRAINED TRAINING ADD and TRAINED', 'run the TestIndexState unittest suite for distributed FAISS index state aggregation', 'review the IndexState.get_aggregated_states logic for consistency across distributed nodes', 'refactor the TestIndexState tests to cover edge cases like empty state lists', 'create a flat index with IndexClient, add embeddings, train, and search for nearest neighbors', 'test that data is balanced across multiple IndexServer instances when using IndexClient with multiple ports', 'run the unittest test suite to verify IndexServer, IndexClient, and IndexCfg integration behavior', 'load batched random embeddings and metadata into a distributed FAISS index using load_batched_data', 'aggregate search results from multiple servers using IndexClient._aggregate_results to find min or max distances', 'run a distributed FAISS RPC client that creates an index, adds data, trains, and searches', 'add random training data to a distributed FAISS client index using torch tensors', 'trigger async training on a distributed FAISS client index', 'test a single FAISS server with 10 parallel client processes using multiprocessing', 'test a single FAISS server with 10 in-process clients adding data and searching']
```

Usage

```
{'test_get_aggregated_states': 'test the IndexState.get_aggregated_states method with mixed training states', 'test_index_state_enum': 'test the IndexState enum values NOT_TRAINED TRAINING ADD and TRAINED', 'run_test_index_state': 'run the TestIndexState unittest suite for distributed FAISS index state aggregation', 'review_index_state_aggregation': 'review the IndexState.get_aggregated_states logic for consistency across distributed nodes', 'refactor_test_index_state': 'refactor the TestIndexState tests to cover edge cases like empty state lists'}
```

## File: facebookresearch_distributed-faiss/tests/test_integration.py

Prompts

```
['test the IndexClient.read_server_list method by reading a server list file and validating hostname and port tuples', 'test the IndexClient.read_server_list method with total_max_timeout=0 to verify it raises an exception on mismatched server counts', 'run the TestClient unittest suite to verify IndexClient.read_server_list parses server list files correctly', 'review the TestClient class and its test_read_server_list method to understand server list parsing assertions', 'refactor the TestClient test_read_server_list method to add additional edge case assertions for malformed server list files', 'test the IndexState.get_aggregated_states method with mixed training states', 'test the IndexState enum values NOT_TRAINED TRAINING ADD and TRAINED', 'run the TestIndexState unittest suite for distributed FAISS index state aggregation', 'review the IndexState.get_aggregated_states logic for consistency across distributed nodes', 'refactor the TestIndexState tests to cover edge cases like empty state lists', 'create a flat index with IndexClient, add embeddings, train, and search for nearest neighbors', 'test that data is balanced across multiple IndexServer instances when using IndexClient with multiple ports', 'run the unittest test suite to verify IndexServer, IndexClient, and IndexCfg integration behavior', 'load batched random embeddings and metadata into a distributed FAISS index using load_batched_data', 'aggregate search results from multiple servers using IndexClient._aggregate_results to find min or max distances', 'run a distributed FAISS RPC client that creates an index, adds data, trains, and searches', 'add random training data to a distributed FAISS client index using torch tensors', 'trigger async training on a distributed FAISS client index', 'test a single FAISS server with 10 parallel client processes using multiprocessing', 'test a single FAISS server with 10 in-process clients adding data and searching']
```

Usage

```
{'create_flat_index_and_search': 'create a flat index with IndexClient, add embeddings, train, and search for nearest neighbors', 'test_multi_server_index_distribution': 'test that data is balanced across multiple IndexServer instances when using IndexClient with multiple ports', 'run_integration_tests_for_distributed_faiss': 'run the unittest test suite to verify IndexServer, IndexClient, and IndexCfg integration behavior', 'load_batched_embeddings_into_index': 'load batched random embeddings and metadata into a distributed FAISS index using load_batched_data', 'aggregate_search_results_from_multiple_servers': 'aggregate search results from multiple servers using IndexClient._aggregate_results to find min or max distances'}
```

## File: facebookresearch_distributed-faiss/tests/test_rpc.py

Prompts

```
['test the IndexClient.read_server_list method by reading a server list file and validating hostname and port tuples', 'test the IndexClient.read_server_list method with total_max_timeout=0 to verify it raises an exception on mismatched server counts', 'run the TestClient unittest suite to verify IndexClient.read_server_list parses server list files correctly', 'review the TestClient class and its test_read_server_list method to understand server list parsing assertions', 'refactor the TestClient test_read_server_list method to add additional edge case assertions for malformed server list files', 'test the IndexState.get_aggregated_states method with mixed training states', 'test the IndexState enum values NOT_TRAINED TRAINING ADD and TRAINED', 'run the TestIndexState unittest suite for distributed FAISS index state aggregation', 'review the IndexState.get_aggregated_states logic for consistency across distributed nodes', 'refactor the TestIndexState tests to cover edge cases like empty state lists', 'create a flat index with IndexClient, add embeddings, train, and search for nearest neighbors', 'test that data is balanced across multiple IndexServer instances when using IndexClient with multiple ports', 'run the unittest test suite to verify IndexServer, IndexClient, and IndexCfg integration behavior', 'load batched random embeddings and metadata into a distributed FAISS index using load_batched_data', 'aggregate search results from multiple servers using IndexClient._aggregate_results to find min or max distances', 'run a distributed FAISS RPC client that creates an index, adds data, trains, and searches', 'add random training data to a distributed FAISS client index using torch tensors', 'trigger async training on a distributed FAISS client index', 'test a single FAISS server with 10 parallel client processes using multiprocessing', 'test a single FAISS server with 10 in-process clients adding data and searching']
```

Usage

```
{'run_client_rpc': 'run a distributed FAISS RPC client that creates an index, adds data, trains, and searches', 'add_train_data_client': 'add random training data to a distributed FAISS client index using torch tensors', 'call_async_train': 'trigger async training on a distributed FAISS client index', 'test_single_server_multiple_clients_threaded': 'test a single FAISS server with 10 parallel client processes using multiprocessing', 'test_single_server_multiple_clients': 'test a single FAISS server with 10 in-process clients adding data and searching'}
```

