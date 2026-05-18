# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/tests/distributed/test_utils.py

Prompts

```
['test broadcast_object to send a string or tensor from rank 0 to all ranks in a distributed group', 'test all_gather_list to collect objects from all ranks into a single list on each process', 'test broadcast_object with a nested dict containing strings, lists, tuples, sets, and tensors', "test all_gather_list by gathering each rank's tensor and verifying correct ordering across processes", 'test the DistributedTest base class that validates CUDA availability and requires 2 or more GPUs', 'spawn multiple processes and initialize a distributed process group using NCCL backend and a temporary file', 'initialize a PyTorch distributed process group with NCCL backend and set the CUDA device for the current rank', 'initialize distributed processes, create a new process group, then run a user-provided function with rank and group', 'recursively compare two objects for equality supporting dicts, lists, tuples, sets, and PyTorch tensors', 'test the distributed utility functions for spawning processes, initializing process groups, and comparing tensor objects']
```

Usage

```
{'test_broadcast_object': 'test broadcast_object to send a string or tensor from rank 0 to all ranks in a distributed group', 'test_all_gather_list': 'test all_gather_list to collect objects from all ranks into a single list on each process', 'test_broadcast_complex': 'test broadcast_object with a nested dict containing strings, lists, tuples, sets, and tensors', 'test_all_gather_rank_tensor': "test all_gather_list by gathering each rank's tensor and verifying correct ordering across processes", 'test_distributed_setup': 'test the DistributedTest base class that validates CUDA availability and requires 2 or more GPUs'}
```

## File: facebookresearch_metaseq/tests/distributed/utils.py

Prompts

```
['test broadcast_object to send a string or tensor from rank 0 to all ranks in a distributed group', 'test all_gather_list to collect objects from all ranks into a single list on each process', 'test broadcast_object with a nested dict containing strings, lists, tuples, sets, and tensors', "test all_gather_list by gathering each rank's tensor and verifying correct ordering across processes", 'test the DistributedTest base class that validates CUDA availability and requires 2 or more GPUs', 'spawn multiple processes and initialize a distributed process group using NCCL backend and a temporary file', 'initialize a PyTorch distributed process group with NCCL backend and set the CUDA device for the current rank', 'initialize distributed processes, create a new process group, then run a user-provided function with rank and group', 'recursively compare two objects for equality supporting dicts, lists, tuples, sets, and PyTorch tensors', 'test the distributed utility functions for spawning processes, initializing process groups, and comparing tensor objects']
```

Usage

```
{'spawn_and_init': 'spawn multiple processes and initialize a distributed process group using NCCL backend and a temporary file', 'distributed_init': 'initialize a PyTorch distributed process group with NCCL backend and set the CUDA device for the current rank', 'init_and_run': 'initialize distributed processes, create a new process group, then run a user-provided function with rank and group', 'objects_are_equal': 'recursively compare two objects for equality supporting dicts, lists, tuples, sets, and PyTorch tensors', 'test_distributed_utils': 'test the distributed utility functions for spawning processes, initializing process groups, and comparing tensor objects'}
```

