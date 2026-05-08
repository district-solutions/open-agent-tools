# Agent Python Tools

- repo: facebookresearch/param
- repo_uri: https://github.com/facebookresearch/param

## File: facebookresearch_param/train/comms/pt/tests/mocks/backend_mock.py

Prompts

```
['mock the all_reduce collective operation by passing collectiveArgs through MockBackendFunction', 'mock the all_gather collective operation by delegating to mock_collective in MockBackendFunction', 'allocate a torch tensor filled with ones using alloc_ones with optional scaleFactor', 'mock the barrier synchronization operation by calling barrier with a custom name', 'get the local rank, global rank, and world size from MockBackendFunction instance']
```

Usage

```
{'mock_all_reduce_collective': 'mock the all_reduce collective operation by passing collectiveArgs through MockBackendFunction', 'mock_all_gather_collective': 'mock the all_gather collective operation by delegating to mock_collective in MockBackendFunction', 'allocate_ones_tensor': 'allocate a torch tensor filled with ones using alloc_ones with optional scaleFactor', 'mock_barrier_sync': 'mock the barrier synchronization operation by calling barrier with a custom name', 'get_rank_info': 'get the local rank, global rank, and world size from MockBackendFunction instance'}
```

