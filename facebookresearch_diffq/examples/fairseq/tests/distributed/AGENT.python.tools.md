# Agent Python Tools

- repo: facebookresearch/diffq
- repo_uri: https://github.com/facebookresearch/diffq

## File: facebookresearch_diffq/examples/fairseq/tests/distributed/test_distributed_utils.py

Prompts

```
['test broadcasting a Python string object across 2 distributed processes using spawn_and_init', 'test broadcasting a PyTorch tensor across 2 distributed processes using spawn_and_init', 'test broadcasting a complex nested dict with tensors and primitives across processes', 'run dist_utils.broadcast_object to send an object from rank 0 to all ranks in a group', 'review the TestDistributedUtils class and its broadcast_object test methods for CUDA and GPU requirements', 'spawn multiple processes using torch.multiprocessing.spawn with a custom function and world size', 'initialize a distributed process group with NCCL backend and file-based init method', 'initialize distributed processes and run a function with a new communication group', 'test whether two objects are equal supporting dicts, lists, tuples, sets, and PyTorch tensors', 'review the objects_are_equal function for recursive comparison of nested dicts, lists, and tensors']
```

Usage

```
{'test_broadcast_object_python': 'test broadcasting a Python string object across 2 distributed processes using spawn_and_init', 'test_broadcast_object_tensor': 'test broadcasting a PyTorch tensor across 2 distributed processes using spawn_and_init', 'test_broadcast_object_complex': 'test broadcasting a complex nested dict with tensors and primitives across processes', 'run_broadcast_object': 'run dist_utils.broadcast_object to send an object from rank 0 to all ranks in a group', 'review_test_distributed_utils': 'review the TestDistributedUtils class and its broadcast_object test methods for CUDA and GPU requirements'}
```

## File: facebookresearch_diffq/examples/fairseq/tests/distributed/utils.py

Prompts

```
['test broadcasting a Python string object across 2 distributed processes using spawn_and_init', 'test broadcasting a PyTorch tensor across 2 distributed processes using spawn_and_init', 'test broadcasting a complex nested dict with tensors and primitives across processes', 'run dist_utils.broadcast_object to send an object from rank 0 to all ranks in a group', 'review the TestDistributedUtils class and its broadcast_object test methods for CUDA and GPU requirements', 'spawn multiple processes using torch.multiprocessing.spawn with a custom function and world size', 'initialize a distributed process group with NCCL backend and file-based init method', 'initialize distributed processes and run a function with a new communication group', 'test whether two objects are equal supporting dicts, lists, tuples, sets, and PyTorch tensors', 'review the objects_are_equal function for recursive comparison of nested dicts, lists, and tensors']
```

Usage

```
{'spawn_distributed_processes': 'spawn multiple processes using torch.multiprocessing.spawn with a custom function and world size', 'init_distributed_process_group': 'initialize a distributed process group with NCCL backend and file-based init method', 'init_and_run_fn': 'initialize distributed processes and run a function with a new communication group', 'test_objects_are_equal': 'test whether two objects are equal supporting dicts, lists, tuples, sets, and PyTorch tensors', 'review_objects_are_equal': 'review the objects_are_equal function for recursive comparison of nested dicts, lists, and tensors'}
```

