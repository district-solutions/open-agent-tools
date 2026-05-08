# Agent Python Tools

- repo: facebookresearch/param
- repo_uri: https://github.com/facebookresearch/param

## File: facebookresearch_param/et_replay/comm/backend/base_backend.py

Prompts

```
['create a collectiveArgsHolder instance to hold parameters for a collective operation experiment', 'build a tensor filled with ones scaled by a factor using alloc_ones', 'register a custom BaseBackend subclass into the global customized_backend dictionary', 'use the noop method to skip communications or compute in a collective operation', 'call sync_barrier to synchronize all processes in the distributed group', 'initialize a PyTorchDistBackend with bootstrap_info and commsParams to set up distributed process groups', 'run an all_reduce collective operation on a tensor across all ranks with optional quantization', 'run an all_to_all collective operation to exchange tensor chunks between all ranks in the group', 'run an all_gather collective to collect tensors from all ranks into a list on every rank', 'run a reduce_scatter collective to reduce and scatter tensor chunks across all ranks', 'initialize a PyTorchTorchCommsBackend with bootstrap_info and commsParams to set up torchcomms-based distributed communication', 'run an all_reduce collective operation across ranks using the torchcomms backend with sum or max reduce ops', 'create process groups via torchcomms split communicators by calling initialize_groups with synchronized group rank mappings', 'execute async point-to-point send and recv operations using isend and irecv methods on the torchcomms backend', 'allocate random tensors on a specified device with a given dtype and optional scale factor using alloc_random', 'run an all-reduce collective operation across TPU cores using xm.all_reduce with sum or max ops', 'run an all-gather collective operation to gather tensors from all TPU cores along dim 0', 'run an all-to-all collective operation to scatter and gather tensor chunks across TPU cores', 'allocate a random tensor on a TPU device with optional integer or float dtype and scale factor', 'allocate an EmbeddingBag table on a TPU device with uniform random weight initialization']
```

Usage

```
{'create_collectiveArgsHolder': 'create a collectiveArgsHolder instance to hold parameters for a collective operation experiment', 'alloc_ones_tensor': 'build a tensor filled with ones scaled by a factor using alloc_ones', 'register_customized_backend': 'register a custom BaseBackend subclass into the global customized_backend dictionary', 'noop_skip_comms': 'use the noop method to skip communications or compute in a collective operation', 'sync_barrier': 'call sync_barrier to synchronize all processes in the distributed group'}
```

## File: facebookresearch_param/et_replay/comm/backend/pytorch_dist_backend.py

Prompts

```
['create a collectiveArgsHolder instance to hold parameters for a collective operation experiment', 'build a tensor filled with ones scaled by a factor using alloc_ones', 'register a custom BaseBackend subclass into the global customized_backend dictionary', 'use the noop method to skip communications or compute in a collective operation', 'call sync_barrier to synchronize all processes in the distributed group', 'initialize a PyTorchDistBackend with bootstrap_info and commsParams to set up distributed process groups', 'run an all_reduce collective operation on a tensor across all ranks with optional quantization', 'run an all_to_all collective operation to exchange tensor chunks between all ranks in the group', 'run an all_gather collective to collect tensors from all ranks into a list on every rank', 'run a reduce_scatter collective to reduce and scatter tensor chunks across all ranks', 'initialize a PyTorchTorchCommsBackend with bootstrap_info and commsParams to set up torchcomms-based distributed communication', 'run an all_reduce collective operation across ranks using the torchcomms backend with sum or max reduce ops', 'create process groups via torchcomms split communicators by calling initialize_groups with synchronized group rank mappings', 'execute async point-to-point send and recv operations using isend and irecv methods on the torchcomms backend', 'allocate random tensors on a specified device with a given dtype and optional scale factor using alloc_random', 'run an all-reduce collective operation across TPU cores using xm.all_reduce with sum or max ops', 'run an all-gather collective operation to gather tensors from all TPU cores along dim 0', 'run an all-to-all collective operation to scatter and gather tensor chunks across TPU cores', 'allocate a random tensor on a TPU device with optional integer or float dtype and scale factor', 'allocate an EmbeddingBag table on a TPU device with uniform random weight initialization']
```

Usage

```
{'initialize_PyTorchDistBackend': 'initialize a PyTorchDistBackend with bootstrap_info and commsParams to set up distributed process groups', 'run_all_reduce': 'run an all_reduce collective operation on a tensor across all ranks with optional quantization', 'run_all_to_all': 'run an all_to_all collective operation to exchange tensor chunks between all ranks in the group', 'run_all_gather': 'run an all_gather collective to collect tensors from all ranks into a list on every rank', 'run_reduce_scatter': 'run a reduce_scatter collective to reduce and scatter tensor chunks across all ranks'}
```

## File: facebookresearch_param/et_replay/comm/backend/pytorch_torchcomms_backend.py

Prompts

```
['create a collectiveArgsHolder instance to hold parameters for a collective operation experiment', 'build a tensor filled with ones scaled by a factor using alloc_ones', 'register a custom BaseBackend subclass into the global customized_backend dictionary', 'use the noop method to skip communications or compute in a collective operation', 'call sync_barrier to synchronize all processes in the distributed group', 'initialize a PyTorchDistBackend with bootstrap_info and commsParams to set up distributed process groups', 'run an all_reduce collective operation on a tensor across all ranks with optional quantization', 'run an all_to_all collective operation to exchange tensor chunks between all ranks in the group', 'run an all_gather collective to collect tensors from all ranks into a list on every rank', 'run a reduce_scatter collective to reduce and scatter tensor chunks across all ranks', 'initialize a PyTorchTorchCommsBackend with bootstrap_info and commsParams to set up torchcomms-based distributed communication', 'run an all_reduce collective operation across ranks using the torchcomms backend with sum or max reduce ops', 'create process groups via torchcomms split communicators by calling initialize_groups with synchronized group rank mappings', 'execute async point-to-point send and recv operations using isend and irecv methods on the torchcomms backend', 'allocate random tensors on a specified device with a given dtype and optional scale factor using alloc_random', 'run an all-reduce collective operation across TPU cores using xm.all_reduce with sum or max ops', 'run an all-gather collective operation to gather tensors from all TPU cores along dim 0', 'run an all-to-all collective operation to scatter and gather tensor chunks across TPU cores', 'allocate a random tensor on a TPU device with optional integer or float dtype and scale factor', 'allocate an EmbeddingBag table on a TPU device with uniform random weight initialization']
```

Usage

```
{'initialize_torchcomms_backend': 'initialize a PyTorchTorchCommsBackend with bootstrap_info and commsParams to set up torchcomms-based distributed communication', 'run_all_reduce_collective': 'run an all_reduce collective operation across ranks using the torchcomms backend with sum or max reduce ops', 'create_process_groups': 'create process groups via torchcomms split communicators by calling initialize_groups with synchronized group rank mappings', 'execute_p2p_async_ops': 'execute async point-to-point send and recv operations using isend and irecv methods on the torchcomms backend', 'allocate_random_tensors': 'allocate random tensors on a specified device with a given dtype and optional scale factor using alloc_random'}
```

## File: facebookresearch_param/et_replay/comm/backend/pytorch_tpu_backend.py

Prompts

```
['create a collectiveArgsHolder instance to hold parameters for a collective operation experiment', 'build a tensor filled with ones scaled by a factor using alloc_ones', 'register a custom BaseBackend subclass into the global customized_backend dictionary', 'use the noop method to skip communications or compute in a collective operation', 'call sync_barrier to synchronize all processes in the distributed group', 'initialize a PyTorchDistBackend with bootstrap_info and commsParams to set up distributed process groups', 'run an all_reduce collective operation on a tensor across all ranks with optional quantization', 'run an all_to_all collective operation to exchange tensor chunks between all ranks in the group', 'run an all_gather collective to collect tensors from all ranks into a list on every rank', 'run a reduce_scatter collective to reduce and scatter tensor chunks across all ranks', 'initialize a PyTorchTorchCommsBackend with bootstrap_info and commsParams to set up torchcomms-based distributed communication', 'run an all_reduce collective operation across ranks using the torchcomms backend with sum or max reduce ops', 'create process groups via torchcomms split communicators by calling initialize_groups with synchronized group rank mappings', 'execute async point-to-point send and recv operations using isend and irecv methods on the torchcomms backend', 'allocate random tensors on a specified device with a given dtype and optional scale factor using alloc_random', 'run an all-reduce collective operation across TPU cores using xm.all_reduce with sum or max ops', 'run an all-gather collective operation to gather tensors from all TPU cores along dim 0', 'run an all-to-all collective operation to scatter and gather tensor chunks across TPU cores', 'allocate a random tensor on a TPU device with optional integer or float dtype and scale factor', 'allocate an EmbeddingBag table on a TPU device with uniform random weight initialization']
```

Usage

```
{'run_all_reduce_tpu': 'run an all-reduce collective operation across TPU cores using xm.all_reduce with sum or max ops', 'run_all_gather_tpu': 'run an all-gather collective operation to gather tensors from all TPU cores along dim 0', 'run_all_to_all_tpu': 'run an all-to-all collective operation to scatter and gather tensor chunks across TPU cores', 'alloc_random_tensor_tpu': 'allocate a random tensor on a TPU device with optional integer or float dtype and scale factor', 'alloc_embedding_tables_tpu': 'allocate an EmbeddingBag table on a TPU device with uniform random weight initialization'}
```

