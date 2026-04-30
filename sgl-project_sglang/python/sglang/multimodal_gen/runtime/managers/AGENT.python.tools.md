# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/managers/cpu_worker.py

Prompts

```
['create a CPUWorker instance to execute a model on pure CPU platforms with tensor parallelism', 'initialize CPU thread binding to NUMA nodes using SGLANG_CPU_OMP_THREADS_BIND environment variable', 'review the CPUWorker initialization that checks for AMX support and sets up thread binding', 'refactor the CPUWorker class to customize NUMA node thread binding logic for multi-node setups', 'summarize the CPUWorker class that extends GPUWorker for CPU-only model inference with shared memory AllReduce', 'create a ForwardContext dataclass to hold timestep, attention metadata, and forward batch state', 'set the attention backend class on a ForwardContext instance with conflict detection', 'get the current global ForwardContext for accessing attention metadata during a forward pass', 'set a ForwardContext via a context manager that tracks batchsize forward timing stats', 'summarize the ForwardContext module that manages per-forward-pass state and optional batchsize timing', 'run the scheduler process entry point that starts a GPU worker with distributed model parallelism', 'build a GPU worker pipeline that executes multimodal generation on a single GPU', 'execute a forward pass through the model pipeline for a batch of requests', 'update model weights from disk inplace without restarting the server', 'merge LoRA adapter weights into the base model with configurable target and strength', 'run the scheduler event loop that listens for ZMQ requests and coordinates with GPU workers', 'create a Scheduler instance with server args, GPU ID, and port args for multimodal generation', 'handle LoRA weight set, merge, unmerge, and list operations on the GPU worker', 'update model weights from disk for RL workflows with optional cache flush', 'get checksums for specified model weight modules for verification']
```

Usage

```
{'create_cpu_worker': 'create a CPUWorker instance to execute a model on pure CPU platforms with tensor parallelism', 'init_cpu_threads_binding': 'initialize CPU thread binding to NUMA nodes using SGLANG_CPU_OMP_THREADS_BIND environment variable', 'review_cpu_worker_init': 'review the CPUWorker initialization that checks for AMX support and sets up thread binding', 'refactor_cpu_worker': 'refactor the CPUWorker class to customize NUMA node thread binding logic for multi-node setups', 'summarize_cpu_worker': 'summarize the CPUWorker class that extends GPUWorker for CPU-only model inference with shared memory AllReduce'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/managers/forward_context.py

Prompts

```
['create a CPUWorker instance to execute a model on pure CPU platforms with tensor parallelism', 'initialize CPU thread binding to NUMA nodes using SGLANG_CPU_OMP_THREADS_BIND environment variable', 'review the CPUWorker initialization that checks for AMX support and sets up thread binding', 'refactor the CPUWorker class to customize NUMA node thread binding logic for multi-node setups', 'summarize the CPUWorker class that extends GPUWorker for CPU-only model inference with shared memory AllReduce', 'create a ForwardContext dataclass to hold timestep, attention metadata, and forward batch state', 'set the attention backend class on a ForwardContext instance with conflict detection', 'get the current global ForwardContext for accessing attention metadata during a forward pass', 'set a ForwardContext via a context manager that tracks batchsize forward timing stats', 'summarize the ForwardContext module that manages per-forward-pass state and optional batchsize timing', 'run the scheduler process entry point that starts a GPU worker with distributed model parallelism', 'build a GPU worker pipeline that executes multimodal generation on a single GPU', 'execute a forward pass through the model pipeline for a batch of requests', 'update model weights from disk inplace without restarting the server', 'merge LoRA adapter weights into the base model with configurable target and strength', 'run the scheduler event loop that listens for ZMQ requests and coordinates with GPU workers', 'create a Scheduler instance with server args, GPU ID, and port args for multimodal generation', 'handle LoRA weight set, merge, unmerge, and list operations on the GPU worker', 'update model weights from disk for RL workflows with optional cache flush', 'get checksums for specified model weight modules for verification']
```

Usage

```
{'create_forward_context_dataclass': 'create a ForwardContext dataclass to hold timestep, attention metadata, and forward batch state', 'set_attn_backend_cls': 'set the attention backend class on a ForwardContext instance with conflict detection', 'get_forward_context': 'get the current global ForwardContext for accessing attention metadata during a forward pass', 'set_forward_context': 'set a ForwardContext via a context manager that tracks batchsize forward timing stats', 'summarize_forward_context': 'summarize the ForwardContext module that manages per-forward-pass state and optional batchsize timing'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/managers/gpu_worker.py

Prompts

```
['create a CPUWorker instance to execute a model on pure CPU platforms with tensor parallelism', 'initialize CPU thread binding to NUMA nodes using SGLANG_CPU_OMP_THREADS_BIND environment variable', 'review the CPUWorker initialization that checks for AMX support and sets up thread binding', 'refactor the CPUWorker class to customize NUMA node thread binding logic for multi-node setups', 'summarize the CPUWorker class that extends GPUWorker for CPU-only model inference with shared memory AllReduce', 'create a ForwardContext dataclass to hold timestep, attention metadata, and forward batch state', 'set the attention backend class on a ForwardContext instance with conflict detection', 'get the current global ForwardContext for accessing attention metadata during a forward pass', 'set a ForwardContext via a context manager that tracks batchsize forward timing stats', 'summarize the ForwardContext module that manages per-forward-pass state and optional batchsize timing', 'run the scheduler process entry point that starts a GPU worker with distributed model parallelism', 'build a GPU worker pipeline that executes multimodal generation on a single GPU', 'execute a forward pass through the model pipeline for a batch of requests', 'update model weights from disk inplace without restarting the server', 'merge LoRA adapter weights into the base model with configurable target and strength', 'run the scheduler event loop that listens for ZMQ requests and coordinates with GPU workers', 'create a Scheduler instance with server args, GPU ID, and port args for multimodal generation', 'handle LoRA weight set, merge, unmerge, and list operations on the GPU worker', 'update model weights from disk for RL workflows with optional cache flush', 'get checksums for specified model weight modules for verification']
```

Usage

```
{'run_scheduler_process': 'run the scheduler process entry point that starts a GPU worker with distributed model parallelism', 'build_pipeline': 'build a GPU worker pipeline that executes multimodal generation on a single GPU', 'execute_forward': 'execute a forward pass through the model pipeline for a batch of requests', 'update_weights_from_disk': 'update model weights from disk inplace without restarting the server', 'merge_lora_weights': 'merge LoRA adapter weights into the base model with configurable target and strength'}
```

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/managers/scheduler.py

Prompts

```
['create a CPUWorker instance to execute a model on pure CPU platforms with tensor parallelism', 'initialize CPU thread binding to NUMA nodes using SGLANG_CPU_OMP_THREADS_BIND environment variable', 'review the CPUWorker initialization that checks for AMX support and sets up thread binding', 'refactor the CPUWorker class to customize NUMA node thread binding logic for multi-node setups', 'summarize the CPUWorker class that extends GPUWorker for CPU-only model inference with shared memory AllReduce', 'create a ForwardContext dataclass to hold timestep, attention metadata, and forward batch state', 'set the attention backend class on a ForwardContext instance with conflict detection', 'get the current global ForwardContext for accessing attention metadata during a forward pass', 'set a ForwardContext via a context manager that tracks batchsize forward timing stats', 'summarize the ForwardContext module that manages per-forward-pass state and optional batchsize timing', 'run the scheduler process entry point that starts a GPU worker with distributed model parallelism', 'build a GPU worker pipeline that executes multimodal generation on a single GPU', 'execute a forward pass through the model pipeline for a batch of requests', 'update model weights from disk inplace without restarting the server', 'merge LoRA adapter weights into the base model with configurable target and strength', 'run the scheduler event loop that listens for ZMQ requests and coordinates with GPU workers', 'create a Scheduler instance with server args, GPU ID, and port args for multimodal generation', 'handle LoRA weight set, merge, unmerge, and list operations on the GPU worker', 'update model weights from disk for RL workflows with optional cache flush', 'get checksums for specified model weight modules for verification']
```

Usage

```
{'run_scheduler_event_loop': 'run the scheduler event loop that listens for ZMQ requests and coordinates with GPU workers', 'create_scheduler_instance': 'create a Scheduler instance with server args, GPU ID, and port args for multimodal generation', 'handle_lora_weight_operations': 'handle LoRA weight set, merge, unmerge, and list operations on the GPU worker', 'update_model_weights_from_disk': 'update model weights from disk for RL workflows with optional cache flush', 'get_model_weights_checksum': 'get checksums for specified model weight modules for verification'}
```

