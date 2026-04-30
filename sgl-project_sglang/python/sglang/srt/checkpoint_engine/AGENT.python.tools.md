# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/checkpoint_engine/checkpoint_engine_worker.py

Prompts

```
['build an SGLangCheckpointEngineWorkerExtensionImpl instance with a model runner to enable checkpoint-engine IPC weight updates', 'run update_weights_from_ipc on the checkpoint engine worker extension to update model weights via ZMQ IPC', 'create a call to get_device_uuid on SGLangCheckpointEngineWorkerExtensionImpl to retrieve the current GPU UUID', 'test get_device_id on SGLangCheckpointEngineWorkerExtensionImpl to verify the current CUDA device ID', 'review get_model_loader on SGLangCheckpointEngineWorkerExtensionImpl to return the model weight loading callable', 'update model weights on a running sglang inference server from a checkpoint using broadcast or p2p method', 'run checkpoint weight update via torchrun with broadcast, p2p, or all update methods against a live sglang endpoint', 'join a checkpoint update using pre-saved metas file to update weights with p2p method', 'split safetensors checkpoint files or tensors across distributed ranks for parallel weight loading', 'check if a sglang inference server endpoint is ready by polling its /ping API']
```

Usage

```
{'build_checkpoint_engine_worker_extension': 'build an SGLangCheckpointEngineWorkerExtensionImpl instance with a model runner to enable checkpoint-engine IPC weight updates', 'run_update_weights_from_ipc': 'run update_weights_from_ipc on the checkpoint engine worker extension to update model weights via ZMQ IPC', 'create_get_device_uuid': 'create a call to get_device_uuid on SGLangCheckpointEngineWorkerExtensionImpl to retrieve the current GPU UUID', 'test_get_device_id': 'test get_device_id on SGLangCheckpointEngineWorkerExtensionImpl to verify the current CUDA device ID', 'review_get_model_loader': 'review get_model_loader on SGLangCheckpointEngineWorkerExtensionImpl to return the model weight loading callable'}
```

## File: sgl-project_sglang/python/sglang/srt/checkpoint_engine/update.py

Prompts

```
['build an SGLangCheckpointEngineWorkerExtensionImpl instance with a model runner to enable checkpoint-engine IPC weight updates', 'run update_weights_from_ipc on the checkpoint engine worker extension to update model weights via ZMQ IPC', 'create a call to get_device_uuid on SGLangCheckpointEngineWorkerExtensionImpl to retrieve the current GPU UUID', 'test get_device_id on SGLangCheckpointEngineWorkerExtensionImpl to verify the current CUDA device ID', 'review get_model_loader on SGLangCheckpointEngineWorkerExtensionImpl to return the model weight loading callable', 'update model weights on a running sglang inference server from a checkpoint using broadcast or p2p method', 'run checkpoint weight update via torchrun with broadcast, p2p, or all update methods against a live sglang endpoint', 'join a checkpoint update using pre-saved metas file to update weights with p2p method', 'split safetensors checkpoint files or tensors across distributed ranks for parallel weight loading', 'check if a sglang inference server endpoint is ready by polling its /ping API']
```

Usage

```
{'update_weights_checkpoint': 'update model weights on a running sglang inference server from a checkpoint using broadcast or p2p method', 'run_checkpoint_update_cli': 'run checkpoint weight update via torchrun with broadcast, p2p, or all update methods against a live sglang endpoint', 'join_checkpoint_with_metas': 'join a checkpoint update using pre-saved metas file to update weights with p2p method', 'split_checkpoint_tensors': 'split safetensors checkpoint files or tensors across distributed ranks for parallel weight loading', 'check_sglang_server_ready': 'check if a sglang inference server endpoint is ready by polling its /ping API'}
```

