# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/example/server.py

Prompts

```
['run a postman server on localhost:12345 that serves bound Python functions over RPC', 'bind a Python function to a postman server with a specified name and batch size', 'bind a function to the server with batch size 2 and wait_till_full enabled', 'create a simple math function handler that returns 42 times the input plus one', 'gracefully stop the postman server and wait for it to finish on keyboard interrupt', 'create a postman server and bind a function with batch_size and wait_till_full options', 'create a postman ComputationQueue with a specified batch_size for batched processing', 'bind a ComputationQueue to a postman server using bind_queue with a name', 'review how to use queue.get, batch.get_inputs, and batch.set_outputs for processing', 'run a postman server on localhost:12345 with bound handlers for replay and model queries', 'create a TorchScript model with a single linear layer and scripted forward method', 'build a NestPrioritizedReplay buffer with capacity 1000 and configurable alpha beta epsilon parameters', 'test the ModelQueue by getting and releasing a model to query its state dict', 'review the postman server bind method to attach query_state_dict and add_replay handlers']
```

Usage

```
{'run_postman_server': 'run a postman server on localhost:12345 that serves bound Python functions over RPC', 'bind_function_to_server': 'bind a Python function to a postman server with a specified name and batch size', 'bind_batched_function': 'bind a function to the server with batch size 2 and wait_till_full enabled', 'create_pyfunc_handler': 'create a simple math function handler that returns 42 times the input plus one', 'stop_and_wait_server': 'gracefully stop the postman server and wait for it to finish on keyboard interrupt'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/example/server_queue.py

Prompts

```
['run a postman server on localhost:12345 that serves bound Python functions over RPC', 'bind a Python function to a postman server with a specified name and batch size', 'bind a function to the server with batch size 2 and wait_till_full enabled', 'create a simple math function handler that returns 42 times the input plus one', 'gracefully stop the postman server and wait for it to finish on keyboard interrupt', 'create a postman server and bind a function with batch_size and wait_till_full options', 'create a postman ComputationQueue with a specified batch_size for batched processing', 'bind a ComputationQueue to a postman server using bind_queue with a name', 'review how to use queue.get, batch.get_inputs, and batch.set_outputs for processing', 'run a postman server on localhost:12345 with bound handlers for replay and model queries', 'create a TorchScript model with a single linear layer and scripted forward method', 'build a NestPrioritizedReplay buffer with capacity 1000 and configurable alpha beta epsilon parameters', 'test the ModelQueue by getting and releasing a model to query its state dict', 'review the postman server bind method to attach query_state_dict and add_replay handlers']
```

Usage

```
{'run_postman_server': 'run a postman server on localhost:12345 with bound functions and computation queues', 'create_server_bind': 'create a postman server and bind a function with batch_size and wait_till_full options', 'create_computation_queue': 'create a postman ComputationQueue with a specified batch_size for batched processing', 'bind_queue_to_server': 'bind a ComputationQueue to a postman server using bind_queue with a name', 'review_batch_operations': 'review how to use queue.get, batch.get_inputs, and batch.set_outputs for processing'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/example/test_replay_server.py

Prompts

```
['run a postman server on localhost:12345 that serves bound Python functions over RPC', 'bind a Python function to a postman server with a specified name and batch size', 'bind a function to the server with batch size 2 and wait_till_full enabled', 'create a simple math function handler that returns 42 times the input plus one', 'gracefully stop the postman server and wait for it to finish on keyboard interrupt', 'create a postman server and bind a function with batch_size and wait_till_full options', 'create a postman ComputationQueue with a specified batch_size for batched processing', 'bind a ComputationQueue to a postman server using bind_queue with a name', 'review how to use queue.get, batch.get_inputs, and batch.set_outputs for processing', 'run a postman server on localhost:12345 with bound handlers for replay and model queries', 'create a TorchScript model with a single linear layer and scripted forward method', 'build a NestPrioritizedReplay buffer with capacity 1000 and configurable alpha beta epsilon parameters', 'test the ModelQueue by getting and releasing a model to query its state dict', 'review the postman server bind method to attach query_state_dict and add_replay handlers']
```

Usage

```
{'run_postman_replay_server': 'run a postman server on localhost:12345 with bound handlers for replay and model queries', 'create_torch_script_model': 'create a TorchScript model with a single linear layer and scripted forward method', 'build_prioritized_replay_buffer': 'build a NestPrioritizedReplay buffer with capacity 1000 and configurable alpha beta epsilon parameters', 'test_model_queue': 'test the ModelQueue by getting and releasing a model to query its state dict', 'review_server_bind_handlers': 'review the postman server bind method to attach query_state_dict and add_replay handlers'}
```

