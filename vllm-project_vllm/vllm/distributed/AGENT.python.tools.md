# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/distributed/communication_op.py

Prompts

```
['all-reduce a torch tensor across the tensor model parallel group', 'all-gather a torch tensor across the tensor model parallel group along a dimension', 'reduce-scatter a torch tensor across the tensor model parallel group along a dimension', 'gather a torch tensor across the tensor model parallel group to a destination rank', 'broadcast a dictionary of tensors across the tensor model parallel group from a source rank', 'build a KVEventAggregator to aggregate KV cache events across multiple workers and return common events', 'create a ZmqEventPublisher that publishes KV cache event batches over ZMQ with replay support', 'create an EventPublisher from a KVEventsConfig using the EventPublisherFactory registry', 'register a custom event publisher class in the EventPublisherFactory registry by name', 'offset a ZMQ endpoint port by a data parallel rank for multi-rank deployment', 'initialize the distributed environment with world size, rank, backend, and timeout settings', 'initialize tensor, pipeline, data, expert, and decode context model parallel groups from config', 'build a GroupCoordinator instance wrapping PyTorch ProcessGroups for CPU and device communication', 'destroy all initialized model parallel groups including tp, pp, dp, ep, dcp, pcp, and eplb', 'test whether ranks in a process group reside on the same node using shared memory checks', 'create a StatelessGroupCoordinator instance for stateless distributed communication groups independent of PyTorch WORLD group', 'send a dictionary of tensors from one rank to a specific destination rank in the group', 'receive a dictionary of tensors from a specific source rank in the group', 'split a torch tensor along its last dimension into equal partitions with optional contiguity', 'create a stateless process group for metadata communication between distributed processes without polluting global state', 'initialize a stateless torch distributed process group with configurable backend and prefix store', 'compute layer start and end indices for pipeline parallel partitioning with configurable partition sizes', "generate a descriptive rank suffix string identifying a worker's position across all parallel dimensions"]
```

Usage

```
{'all_reduce_tensor': 'all-reduce a torch tensor across the tensor model parallel group', 'all_gather_tensor': 'all-gather a torch tensor across the tensor model parallel group along a dimension', 'reduce_scatter_tensor': 'reduce-scatter a torch tensor across the tensor model parallel group along a dimension', 'gather_tensor': 'gather a torch tensor across the tensor model parallel group to a destination rank', 'broadcast_tensor_dict': 'broadcast a dictionary of tensors across the tensor model parallel group from a source rank'}
```

## File: vllm-project_vllm/vllm/distributed/kv_events.py

Prompts

```
['all-reduce a torch tensor across the tensor model parallel group', 'all-gather a torch tensor across the tensor model parallel group along a dimension', 'reduce-scatter a torch tensor across the tensor model parallel group along a dimension', 'gather a torch tensor across the tensor model parallel group to a destination rank', 'broadcast a dictionary of tensors across the tensor model parallel group from a source rank', 'build a KVEventAggregator to aggregate KV cache events across multiple workers and return common events', 'create a ZmqEventPublisher that publishes KV cache event batches over ZMQ with replay support', 'create an EventPublisher from a KVEventsConfig using the EventPublisherFactory registry', 'register a custom event publisher class in the EventPublisherFactory registry by name', 'offset a ZMQ endpoint port by a data parallel rank for multi-rank deployment', 'initialize the distributed environment with world size, rank, backend, and timeout settings', 'initialize tensor, pipeline, data, expert, and decode context model parallel groups from config', 'build a GroupCoordinator instance wrapping PyTorch ProcessGroups for CPU and device communication', 'destroy all initialized model parallel groups including tp, pp, dp, ep, dcp, pcp, and eplb', 'test whether ranks in a process group reside on the same node using shared memory checks', 'create a StatelessGroupCoordinator instance for stateless distributed communication groups independent of PyTorch WORLD group', 'send a dictionary of tensors from one rank to a specific destination rank in the group', 'receive a dictionary of tensors from a specific source rank in the group', 'split a torch tensor along its last dimension into equal partitions with optional contiguity', 'create a stateless process group for metadata communication between distributed processes without polluting global state', 'initialize a stateless torch distributed process group with configurable backend and prefix store', 'compute layer start and end indices for pipeline parallel partitioning with configurable partition sizes', "generate a descriptive rank suffix string identifying a worker's position across all parallel dimensions"]
```

Usage

```
{'build_kv_event_aggregator': 'build a KVEventAggregator to aggregate KV cache events across multiple workers and return common events', 'create_zmq_event_publisher': 'create a ZmqEventPublisher that publishes KV cache event batches over ZMQ with replay support', 'create_event_publisher_from_config': 'create an EventPublisher from a KVEventsConfig using the EventPublisherFactory registry', 'register_custom_event_publisher': 'register a custom event publisher class in the EventPublisherFactory registry by name', 'offset_zmq_endpoint_port': 'offset a ZMQ endpoint port by a data parallel rank for multi-rank deployment'}
```

## File: vllm-project_vllm/vllm/distributed/parallel_state.py

Prompts

```
['all-reduce a torch tensor across the tensor model parallel group', 'all-gather a torch tensor across the tensor model parallel group along a dimension', 'reduce-scatter a torch tensor across the tensor model parallel group along a dimension', 'gather a torch tensor across the tensor model parallel group to a destination rank', 'broadcast a dictionary of tensors across the tensor model parallel group from a source rank', 'build a KVEventAggregator to aggregate KV cache events across multiple workers and return common events', 'create a ZmqEventPublisher that publishes KV cache event batches over ZMQ with replay support', 'create an EventPublisher from a KVEventsConfig using the EventPublisherFactory registry', 'register a custom event publisher class in the EventPublisherFactory registry by name', 'offset a ZMQ endpoint port by a data parallel rank for multi-rank deployment', 'initialize the distributed environment with world size, rank, backend, and timeout settings', 'initialize tensor, pipeline, data, expert, and decode context model parallel groups from config', 'build a GroupCoordinator instance wrapping PyTorch ProcessGroups for CPU and device communication', 'destroy all initialized model parallel groups including tp, pp, dp, ep, dcp, pcp, and eplb', 'test whether ranks in a process group reside on the same node using shared memory checks', 'create a StatelessGroupCoordinator instance for stateless distributed communication groups independent of PyTorch WORLD group', 'send a dictionary of tensors from one rank to a specific destination rank in the group', 'receive a dictionary of tensors from a specific source rank in the group', 'split a torch tensor along its last dimension into equal partitions with optional contiguity', 'create a stateless process group for metadata communication between distributed processes without polluting global state', 'initialize a stateless torch distributed process group with configurable backend and prefix store', 'compute layer start and end indices for pipeline parallel partitioning with configurable partition sizes', "generate a descriptive rank suffix string identifying a worker's position across all parallel dimensions"]
```

Usage

```
{'init_distributed_environment': 'initialize the distributed environment with world size, rank, backend, and timeout settings', 'initialize_model_parallel': 'initialize tensor, pipeline, data, expert, and decode context model parallel groups from config', 'build_group_coordinator': 'build a GroupCoordinator instance wrapping PyTorch ProcessGroups for CPU and device communication', 'destroy_model_parallel': 'destroy all initialized model parallel groups including tp, pp, dp, ep, dcp, pcp, and eplb', 'test_in_the_same_node_as': 'test whether ranks in a process group reside on the same node using shared memory checks'}
```

## File: vllm-project_vllm/vllm/distributed/stateless_coordinator.py

Prompts

```
['all-reduce a torch tensor across the tensor model parallel group', 'all-gather a torch tensor across the tensor model parallel group along a dimension', 'reduce-scatter a torch tensor across the tensor model parallel group along a dimension', 'gather a torch tensor across the tensor model parallel group to a destination rank', 'broadcast a dictionary of tensors across the tensor model parallel group from a source rank', 'build a KVEventAggregator to aggregate KV cache events across multiple workers and return common events', 'create a ZmqEventPublisher that publishes KV cache event batches over ZMQ with replay support', 'create an EventPublisher from a KVEventsConfig using the EventPublisherFactory registry', 'register a custom event publisher class in the EventPublisherFactory registry by name', 'offset a ZMQ endpoint port by a data parallel rank for multi-rank deployment', 'initialize the distributed environment with world size, rank, backend, and timeout settings', 'initialize tensor, pipeline, data, expert, and decode context model parallel groups from config', 'build a GroupCoordinator instance wrapping PyTorch ProcessGroups for CPU and device communication', 'destroy all initialized model parallel groups including tp, pp, dp, ep, dcp, pcp, and eplb', 'test whether ranks in a process group reside on the same node using shared memory checks', 'create a StatelessGroupCoordinator instance for stateless distributed communication groups independent of PyTorch WORLD group', 'send a dictionary of tensors from one rank to a specific destination rank in the group', 'receive a dictionary of tensors from a specific source rank in the group', 'split a torch tensor along its last dimension into equal partitions with optional contiguity', 'create a stateless process group for metadata communication between distributed processes without polluting global state', 'initialize a stateless torch distributed process group with configurable backend and prefix store', 'compute layer start and end indices for pipeline parallel partitioning with configurable partition sizes', "generate a descriptive rank suffix string identifying a worker's position across all parallel dimensions"]
```

Usage

```
{'create_StatelessGroupCoordinator': 'create a StatelessGroupCoordinator instance for stateless distributed communication groups independent of PyTorch WORLD group', 'broadcast_tensor_dict': 'broadcast a dictionary of tensors from one rank to all other ranks in the group', 'send_tensor_dict': 'send a dictionary of tensors from one rank to a specific destination rank in the group', 'recv_tensor_dict': 'receive a dictionary of tensors from a specific source rank in the group', 'gather_tensor': 'gather tensors from all ranks in the group to a single destination rank'}
```

## File: vllm-project_vllm/vllm/distributed/utils.py

Prompts

```
['all-reduce a torch tensor across the tensor model parallel group', 'all-gather a torch tensor across the tensor model parallel group along a dimension', 'reduce-scatter a torch tensor across the tensor model parallel group along a dimension', 'gather a torch tensor across the tensor model parallel group to a destination rank', 'broadcast a dictionary of tensors across the tensor model parallel group from a source rank', 'build a KVEventAggregator to aggregate KV cache events across multiple workers and return common events', 'create a ZmqEventPublisher that publishes KV cache event batches over ZMQ with replay support', 'create an EventPublisher from a KVEventsConfig using the EventPublisherFactory registry', 'register a custom event publisher class in the EventPublisherFactory registry by name', 'offset a ZMQ endpoint port by a data parallel rank for multi-rank deployment', 'initialize the distributed environment with world size, rank, backend, and timeout settings', 'initialize tensor, pipeline, data, expert, and decode context model parallel groups from config', 'build a GroupCoordinator instance wrapping PyTorch ProcessGroups for CPU and device communication', 'destroy all initialized model parallel groups including tp, pp, dp, ep, dcp, pcp, and eplb', 'test whether ranks in a process group reside on the same node using shared memory checks', 'create a StatelessGroupCoordinator instance for stateless distributed communication groups independent of PyTorch WORLD group', 'send a dictionary of tensors from one rank to a specific destination rank in the group', 'receive a dictionary of tensors from a specific source rank in the group', 'split a torch tensor along its last dimension into equal partitions with optional contiguity', 'create a stateless process group for metadata communication between distributed processes without polluting global state', 'initialize a stateless torch distributed process group with configurable backend and prefix store', 'compute layer start and end indices for pipeline parallel partitioning with configurable partition sizes', "generate a descriptive rank suffix string identifying a worker's position across all parallel dimensions"]
```

Usage

```
{'build_split_tensor_along_last_dim': 'split a torch tensor along its last dimension into equal partitions with optional contiguity', 'create_stateless_process_group': 'create a stateless process group for metadata communication between distributed processes without polluting global state', 'run_stateless_init_torch_distributed_process_group': 'initialize a stateless torch distributed process group with configurable backend and prefix store', 'build_get_pp_indices': 'compute layer start and end indices for pipeline parallel partitioning with configurable partition sizes', 'get_worker_rank_suffix': "generate a descriptive rank suffix string identifying a worker's position across all parallel dimensions"}
```

