# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/distributed/communication_op.py

Prompts

```
['all-reduce a tensor across the tensor model parallel group', 'fuse tensor model parallel all-reduce with RMS normalization in a single operation', 'all-gather a tensor across the tensor model parallel group along a dimension', 'gather a tensor from all ranks in the tensor model parallel group to a destination rank', 'broadcast a dictionary of tensors and scalar values across the tensor model parallel group', 'create a NaiveDistributed instance with rank, world_size, and rendezvous directory for file-based distributed coordination', 'test the all_gather_object method to collect serialized Python objects from all ranks via filesystem', 'run the scatter method to distribute torch tensors from a source rank to all ranks in the group', 'test the barrier method to synchronize all ranks and verify every rank has joined', 'build a naive distributed singleton using set_naive_distributed and retrieve it with get_naive_distributed', 'initialize the distributed environment with world size, rank, and backend configuration', 'initialize tensor, pipeline, and MoE model parallel groups with configurable parallel sizes', 'create a custom parallel group from a list of ranks with a specified communication backend', 'perform an all-reduce operation on a tensor across all ranks using the optimal communicator backend', 'create a StatelessProcessGroup instance using TCPStore without polluting PyTorch global distributed state', 'split a PyTorch tensor along its last dimension into equal contiguous partitions', 'get start and end layer indices for pipeline parallel layer distribution across ranks', 'send and receive pickled metadata objects between distributed process ranks via TCPStore', 'broadcast metadata objects from a source rank to all other ranks in a distributed group']
```

Usage

```
{'all_reduce_tensor_model_parallel': 'all-reduce a tensor across the tensor model parallel group', 'fused_allreduce_rmsnorm': 'fuse tensor model parallel all-reduce with RMS normalization in a single operation', 'all_gather_tensor_model_parallel': 'all-gather a tensor across the tensor model parallel group along a dimension', 'gather_tensor_model_parallel': 'gather a tensor from all ranks in the tensor model parallel group to a destination rank', 'broadcast_tensor_dict': 'broadcast a dictionary of tensors and scalar values across the tensor model parallel group'}
```

## File: sgl-project_sglang/python/sglang/srt/distributed/naive_distributed.py

Prompts

```
['all-reduce a tensor across the tensor model parallel group', 'fuse tensor model parallel all-reduce with RMS normalization in a single operation', 'all-gather a tensor across the tensor model parallel group along a dimension', 'gather a tensor from all ranks in the tensor model parallel group to a destination rank', 'broadcast a dictionary of tensors and scalar values across the tensor model parallel group', 'create a NaiveDistributed instance with rank, world_size, and rendezvous directory for file-based distributed coordination', 'test the all_gather_object method to collect serialized Python objects from all ranks via filesystem', 'run the scatter method to distribute torch tensors from a source rank to all ranks in the group', 'test the barrier method to synchronize all ranks and verify every rank has joined', 'build a naive distributed singleton using set_naive_distributed and retrieve it with get_naive_distributed', 'initialize the distributed environment with world size, rank, and backend configuration', 'initialize tensor, pipeline, and MoE model parallel groups with configurable parallel sizes', 'create a custom parallel group from a list of ranks with a specified communication backend', 'perform an all-reduce operation on a tensor across all ranks using the optimal communicator backend', 'create a StatelessProcessGroup instance using TCPStore without polluting PyTorch global distributed state', 'split a PyTorch tensor along its last dimension into equal contiguous partitions', 'get start and end layer indices for pipeline parallel layer distribution across ranks', 'send and receive pickled metadata objects between distributed process ranks via TCPStore', 'broadcast metadata objects from a source rank to all other ranks in a distributed group']
```

Usage

```
{'create_NaiveDistributed': 'create a NaiveDistributed instance with rank, world_size, and rendezvous directory for file-based distributed coordination', 'test_all_gather_object': 'test the all_gather_object method to collect serialized Python objects from all ranks via filesystem', 'run_scatter_tensor': 'run the scatter method to distribute torch tensors from a source rank to all ranks in the group', 'test_barrier': 'test the barrier method to synchronize all ranks and verify every rank has joined', 'build_naive_distributed_singleton': 'build a naive distributed singleton using set_naive_distributed and retrieve it with get_naive_distributed'}
```

## File: sgl-project_sglang/python/sglang/srt/distributed/parallel_state.py

Prompts

```
['all-reduce a tensor across the tensor model parallel group', 'fuse tensor model parallel all-reduce with RMS normalization in a single operation', 'all-gather a tensor across the tensor model parallel group along a dimension', 'gather a tensor from all ranks in the tensor model parallel group to a destination rank', 'broadcast a dictionary of tensors and scalar values across the tensor model parallel group', 'create a NaiveDistributed instance with rank, world_size, and rendezvous directory for file-based distributed coordination', 'test the all_gather_object method to collect serialized Python objects from all ranks via filesystem', 'run the scatter method to distribute torch tensors from a source rank to all ranks in the group', 'test the barrier method to synchronize all ranks and verify every rank has joined', 'build a naive distributed singleton using set_naive_distributed and retrieve it with get_naive_distributed', 'initialize the distributed environment with world size, rank, and backend configuration', 'initialize tensor, pipeline, and MoE model parallel groups with configurable parallel sizes', 'create a custom parallel group from a list of ranks with a specified communication backend', 'perform an all-reduce operation on a tensor across all ranks using the optimal communicator backend', 'create a StatelessProcessGroup instance using TCPStore without polluting PyTorch global distributed state', 'split a PyTorch tensor along its last dimension into equal contiguous partitions', 'get start and end layer indices for pipeline parallel layer distribution across ranks', 'send and receive pickled metadata objects between distributed process ranks via TCPStore', 'broadcast metadata objects from a source rank to all other ranks in a distributed group']
```

Usage

```
{'init_distributed_environment': 'initialize the distributed environment with world size, rank, and backend configuration', 'initialize_model_parallel': 'initialize tensor, pipeline, and MoE model parallel groups with configurable parallel sizes', 'create_custom_parallel_group': 'create a custom parallel group from a list of ranks with a specified communication backend', 'perform_all_reduce_operation': 'perform an all-reduce operation on a tensor across all ranks using the optimal communicator backend', 'broadcast_tensor_dict': 'broadcast a dictionary of tensors and metadata from a source rank to all other ranks asynchronously'}
```

## File: sgl-project_sglang/python/sglang/srt/distributed/utils.py

Prompts

```
['all-reduce a tensor across the tensor model parallel group', 'fuse tensor model parallel all-reduce with RMS normalization in a single operation', 'all-gather a tensor across the tensor model parallel group along a dimension', 'gather a tensor from all ranks in the tensor model parallel group to a destination rank', 'broadcast a dictionary of tensors and scalar values across the tensor model parallel group', 'create a NaiveDistributed instance with rank, world_size, and rendezvous directory for file-based distributed coordination', 'test the all_gather_object method to collect serialized Python objects from all ranks via filesystem', 'run the scatter method to distribute torch tensors from a source rank to all ranks in the group', 'test the barrier method to synchronize all ranks and verify every rank has joined', 'build a naive distributed singleton using set_naive_distributed and retrieve it with get_naive_distributed', 'initialize the distributed environment with world size, rank, and backend configuration', 'initialize tensor, pipeline, and MoE model parallel groups with configurable parallel sizes', 'create a custom parallel group from a list of ranks with a specified communication backend', 'perform an all-reduce operation on a tensor across all ranks using the optimal communicator backend', 'create a StatelessProcessGroup instance using TCPStore without polluting PyTorch global distributed state', 'split a PyTorch tensor along its last dimension into equal contiguous partitions', 'get start and end layer indices for pipeline parallel layer distribution across ranks', 'send and receive pickled metadata objects between distributed process ranks via TCPStore', 'broadcast metadata objects from a source rank to all other ranks in a distributed group']
```

Usage

```
{'create_stateless_process_group': 'create a StatelessProcessGroup instance using TCPStore without polluting PyTorch global distributed state', 'split_tensor_along_last_dim': 'split a PyTorch tensor along its last dimension into equal contiguous partitions', 'get_pp_indices': 'get start and end layer indices for pipeline parallel layer distribution across ranks', 'send_receive_metadata_objects': 'send and receive pickled metadata objects between distributed process ranks via TCPStore', 'broadcast_metadata_objects': 'broadcast metadata objects from a source rank to all other ranks in a distributed group'}
```

