# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/elastic_ep/elastic_ep.py

Prompts

```
['build an ElasticEPStateManager to initialize and manage elastic EP rank state across distributed ranks', 'create an ElasticEPState dataclass with active ranks, last active ranks, and CPU-synced rank tensors', 'test whether the current active ranks match the last recorded active ranks', 'sync the active GPU rank tensor to a CPU clone for cross-process sharing', 'snapshot the current active ranks into the last active ranks field for change detection', 'create an ExpertBackupClient instance with server args and model runner to initialize ZMQ sockets for expert weight backup', 'run the update_weights method to transfer expert weights from remote backup via Mooncake transfer engine', 'run start_transfer_client to register local GPU memory buffers with the Mooncake transfer engine', 'run extract_layer_and_expert_id to parse a PyTorch parameter name and extract layer ID, expert ID, and weight name', 'run the receive_loop background thread to collect weight pointer maps and session IDs from all engines', 'create an ExpertBackupManager to load and backup MoE expert weights from disk into a contiguous CPU buffer', 'backup expert model weights from disk into a contiguous byte buffer with pointer map for Mooncake transfer', 'start a Mooncake transfer server to register the expert weight buffer for remote memory access', 'run the expert backup manager in a dedicated multiprocessing process with Mooncake engine initialization', 'extract the expert index number from a PyTorch parameter name matching the pattern .experts.<id>.']
```

Usage

```
{'build_elastic_ep_state_manager': 'build an ElasticEPStateManager to initialize and manage elastic EP rank state across distributed ranks', 'create_elastic_ep_state': 'create an ElasticEPState dataclass with active ranks, last active ranks, and CPU-synced rank tensors', 'test_is_active_equal_last': 'test whether the current active ranks match the last recorded active ranks', 'sync_active_to_cpu': 'sync the active GPU rank tensor to a CPU clone for cross-process sharing', 'snapshot_active_to_last': 'snapshot the current active ranks into the last active ranks field for change detection'}
```

## File: sgl-project_sglang/python/sglang/srt/elastic_ep/expert_backup_client.py

Prompts

```
['build an ElasticEPStateManager to initialize and manage elastic EP rank state across distributed ranks', 'create an ElasticEPState dataclass with active ranks, last active ranks, and CPU-synced rank tensors', 'test whether the current active ranks match the last recorded active ranks', 'sync the active GPU rank tensor to a CPU clone for cross-process sharing', 'snapshot the current active ranks into the last active ranks field for change detection', 'create an ExpertBackupClient instance with server args and model runner to initialize ZMQ sockets for expert weight backup', 'run the update_weights method to transfer expert weights from remote backup via Mooncake transfer engine', 'run start_transfer_client to register local GPU memory buffers with the Mooncake transfer engine', 'run extract_layer_and_expert_id to parse a PyTorch parameter name and extract layer ID, expert ID, and weight name', 'run the receive_loop background thread to collect weight pointer maps and session IDs from all engines', 'create an ExpertBackupManager to load and backup MoE expert weights from disk into a contiguous CPU buffer', 'backup expert model weights from disk into a contiguous byte buffer with pointer map for Mooncake transfer', 'start a Mooncake transfer server to register the expert weight buffer for remote memory access', 'run the expert backup manager in a dedicated multiprocessing process with Mooncake engine initialization', 'extract the expert index number from a PyTorch parameter name matching the pattern .experts.<id>.']
```

Usage

```
{'create_ExpertBackupClient': 'create an ExpertBackupClient instance with server args and model runner to initialize ZMQ sockets for expert weight backup', 'run_update_weights': 'run the update_weights method to transfer expert weights from remote backup via Mooncake transfer engine', 'run_start_transfer_client': 'run start_transfer_client to register local GPU memory buffers with the Mooncake transfer engine', 'run_extract_layer_and_expert_id': 'run extract_layer_and_expert_id to parse a PyTorch parameter name and extract layer ID, expert ID, and weight name', 'run_receive_loop': 'run the receive_loop background thread to collect weight pointer maps and session IDs from all engines'}
```

## File: sgl-project_sglang/python/sglang/srt/elastic_ep/expert_backup_manager.py

Prompts

```
['build an ElasticEPStateManager to initialize and manage elastic EP rank state across distributed ranks', 'create an ElasticEPState dataclass with active ranks, last active ranks, and CPU-synced rank tensors', 'test whether the current active ranks match the last recorded active ranks', 'sync the active GPU rank tensor to a CPU clone for cross-process sharing', 'snapshot the current active ranks into the last active ranks field for change detection', 'create an ExpertBackupClient instance with server args and model runner to initialize ZMQ sockets for expert weight backup', 'run the update_weights method to transfer expert weights from remote backup via Mooncake transfer engine', 'run start_transfer_client to register local GPU memory buffers with the Mooncake transfer engine', 'run extract_layer_and_expert_id to parse a PyTorch parameter name and extract layer ID, expert ID, and weight name', 'run the receive_loop background thread to collect weight pointer maps and session IDs from all engines', 'create an ExpertBackupManager to load and backup MoE expert weights from disk into a contiguous CPU buffer', 'backup expert model weights from disk into a contiguous byte buffer with pointer map for Mooncake transfer', 'start a Mooncake transfer server to register the expert weight buffer for remote memory access', 'run the expert backup manager in a dedicated multiprocessing process with Mooncake engine initialization', 'extract the expert index number from a PyTorch parameter name matching the pattern .experts.<id>.']
```

Usage

```
{'create_expert_backup_manager': 'create an ExpertBackupManager to load and backup MoE expert weights from disk into a contiguous CPU buffer', 'backup_expert_weights_from_disk': 'backup expert model weights from disk into a contiguous byte buffer with pointer map for Mooncake transfer', 'start_mooncake_transfer_server': 'start a Mooncake transfer server to register the expert weight buffer for remote memory access', 'run_expert_backup_manager_process': 'run the expert backup manager in a dedicated multiprocessing process with Mooncake engine initialization', 'extract_expert_id_from_param': 'extract the expert index number from a PyTorch parameter name matching the pattern .experts.<id>.'}
```

