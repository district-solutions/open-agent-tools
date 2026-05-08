# Agent Python Tools

- repo: facebookresearch/crypten
- repo_uri: https://github.com/facebookresearch/crypten

## File: facebookresearch_crypten/crypten/communicator/communicator.py

Prompts

```
['initialize the Communicator class before using any distributed communication operations', 'send a tensor to a destination rank or receive a tensor from a source rank', 'reduce tensor data across all parties so every party gets the final result', 'broadcast a tensor from a source rank to all other parties in the group', 'get or print communication statistics including rounds, bytes, and time elapsed', 'initialize a DistributedCommunicator with a given rank and world size for multi-party computation', 'perform an all-reduce operation across all processes with optional batched tensor support', 'send a pickled Python object to a destination rank and receive an object from a source rank', 'initialize an InProcessCommunicator with a given rank and world size for in-process distributed communication', 'send a tensor to a destination rank and receive a tensor from a source rank using the mailbox', 'gather tensors from all ranks into a sorted list on each rank using the in-process mailbox']
```

Usage

```
{'initialize_communicator': 'initialize the Communicator class before using any distributed communication operations', 'send_recv_tensor': 'send a tensor to a destination rank or receive a tensor from a source rank', 'all_reduce_tensor': 'reduce tensor data across all parties so every party gets the final result', 'broadcast_tensor': 'broadcast a tensor from a source rank to all other parties in the group', 'get_communication_stats': 'get or print communication statistics including rounds, bytes, and time elapsed'}
```

## File: facebookresearch_crypten/crypten/communicator/distributed_communicator.py

Prompts

```
['initialize the Communicator class before using any distributed communication operations', 'send a tensor to a destination rank or receive a tensor from a source rank', 'reduce tensor data across all parties so every party gets the final result', 'broadcast a tensor from a source rank to all other parties in the group', 'get or print communication statistics including rounds, bytes, and time elapsed', 'initialize a DistributedCommunicator with a given rank and world size for multi-party computation', 'perform an all-reduce operation across all processes with optional batched tensor support', 'send a pickled Python object to a destination rank and receive an object from a source rank', 'initialize an InProcessCommunicator with a given rank and world size for in-process distributed communication', 'send a tensor to a destination rank and receive a tensor from a source rank using the mailbox', 'gather tensors from all ranks into a sorted list on each rank using the in-process mailbox']
```

Usage

```
{'initialize_distributed_communicator': 'initialize a DistributedCommunicator with a given rank and world size for multi-party computation', 'send_recv_tensor': 'send a torch tensor to a destination rank and receive a tensor from a source rank', 'all_reduce_tensors': 'perform an all-reduce operation across all processes with optional batched tensor support', 'send_recv_object': 'send a pickled Python object to a destination rank and receive an object from a source rank', 'broadcast_tensor': 'broadcast a tensor from a source rank to all processes in the communicator group'}
```

## File: facebookresearch_crypten/crypten/communicator/in_process_communicator.py

Prompts

```
['initialize the Communicator class before using any distributed communication operations', 'send a tensor to a destination rank or receive a tensor from a source rank', 'reduce tensor data across all parties so every party gets the final result', 'broadcast a tensor from a source rank to all other parties in the group', 'get or print communication statistics including rounds, bytes, and time elapsed', 'initialize a DistributedCommunicator with a given rank and world size for multi-party computation', 'perform an all-reduce operation across all processes with optional batched tensor support', 'send a pickled Python object to a destination rank and receive an object from a source rank', 'initialize an InProcessCommunicator with a given rank and world size for in-process distributed communication', 'send a tensor to a destination rank and receive a tensor from a source rank using the mailbox', 'gather tensors from all ranks into a sorted list on each rank using the in-process mailbox']
```

Usage

```
{'initialize_InProcessCommunicator': 'initialize an InProcessCommunicator with a given rank and world size for in-process distributed communication', 'send_recv_tensors': 'send a tensor to a destination rank and receive a tensor from a source rank using the mailbox', 'all_reduce_tensor': 'reduce a tensor across all ranks using a reduce operation like SUM and return the result to all', 'all_gather_tensors': 'gather tensors from all ranks into a sorted list on each rank using the in-process mailbox', 'broadcast_tensor': 'broadcast a tensor from a source rank to all other ranks in the in-process communicator'}
```

