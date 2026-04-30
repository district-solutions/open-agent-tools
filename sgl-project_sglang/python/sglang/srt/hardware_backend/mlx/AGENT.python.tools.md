# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/mlx/model_runner.py

Prompts

```
['build an MlxModelRunner instance to load an MLX model on Apple Silicon with configurable pool size and radix cache', 'prefill a request with new token IDs and return the next predicted token ID using prefix slot matching', 'decode one token per request in a batch using the MlxModelRunner with batched or single-request attention', 'extend a chunked request by continuing prefill and syncing new KV cache to the shared pool', 'clear all active request states and release cached KV buffers back to the pool', 'create an MlxModelRunnerStub instance with mlx_pool_size for CPU-side scheduler bookkeeping on Apple Silicon', 'initialize MlxModelRunnerStub with minimal pools, skipping PyTorch weight loading and GPU KV cache allocation', 'load model metadata only in MlxModelRunnerStub without loading PyTorch model weights for MLX inference', 'create a _DummyKVCache that satisfies the KVCache interface without allocating GPU memory', 'create a _DummyModel stand-in so inspect.signature and getattr calls in ModelRunner.__init__ do not crash', 'run the MLX overlap scheduling loop that pipelines two in-flight lazy graphs on the GPU', 'review the MlxPendingJob dataclass that holds unfinished MLX work and graphs queued on the GPU', 'review the SchedulerMlxOverlapMixin class that adds MLX overlap scheduling to the Scheduler', 'refactor event_loop_overlap_mlx to support additional chain-breaking conditions for the MLX scheduling loop', 'summarize the MlxPendingJob dataclass attributes including lazy_tokens, prefills, extends, decode, mode, batch_copy, and reqs', 'initialize the MLX model runner and stub for Apple Silicon tensor parallel inference', 'route forward batch generation through the MLX model runner on Apple Silicon', 'run forward pass through the MLX model runner for prefill and decode modes', "lazily initialize the MLX KV pool after the stub's pools are ready", 'return None since the stub model runner has no real model for padding']
```

Usage

```
{'build_mlx_model_runner': 'build an MlxModelRunner instance to load an MLX model on Apple Silicon with configurable pool size and radix cache', 'prefill_request_tokens': 'prefill a request with new token IDs and return the next predicted token ID using prefix slot matching', 'decode_batch_tokens': 'decode one token per request in a batch using the MlxModelRunner with batched or single-request attention', 'extend_request_tokens': 'extend a chunked request by continuing prefill and syncing new KV cache to the shared pool', 'clear_request_states': 'clear all active request states and release cached KV buffers back to the pool'}
```

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/mlx/model_runner_stub.py

Prompts

```
['build an MlxModelRunner instance to load an MLX model on Apple Silicon with configurable pool size and radix cache', 'prefill a request with new token IDs and return the next predicted token ID using prefix slot matching', 'decode one token per request in a batch using the MlxModelRunner with batched or single-request attention', 'extend a chunked request by continuing prefill and syncing new KV cache to the shared pool', 'clear all active request states and release cached KV buffers back to the pool', 'create an MlxModelRunnerStub instance with mlx_pool_size for CPU-side scheduler bookkeeping on Apple Silicon', 'initialize MlxModelRunnerStub with minimal pools, skipping PyTorch weight loading and GPU KV cache allocation', 'load model metadata only in MlxModelRunnerStub without loading PyTorch model weights for MLX inference', 'create a _DummyKVCache that satisfies the KVCache interface without allocating GPU memory', 'create a _DummyModel stand-in so inspect.signature and getattr calls in ModelRunner.__init__ do not crash', 'run the MLX overlap scheduling loop that pipelines two in-flight lazy graphs on the GPU', 'review the MlxPendingJob dataclass that holds unfinished MLX work and graphs queued on the GPU', 'review the SchedulerMlxOverlapMixin class that adds MLX overlap scheduling to the Scheduler', 'refactor event_loop_overlap_mlx to support additional chain-breaking conditions for the MLX scheduling loop', 'summarize the MlxPendingJob dataclass attributes including lazy_tokens, prefills, extends, decode, mode, batch_copy, and reqs', 'initialize the MLX model runner and stub for Apple Silicon tensor parallel inference', 'route forward batch generation through the MLX model runner on Apple Silicon', 'run forward pass through the MLX model runner for prefill and decode modes', "lazily initialize the MLX KV pool after the stub's pools are ready", 'return None since the stub model runner has no real model for padding']
```

Usage

```
{'create_mlx_model_runner_stub': 'create an MlxModelRunnerStub instance with mlx_pool_size for CPU-side scheduler bookkeeping on Apple Silicon', 'initialize_mlx_model_runner': 'initialize MlxModelRunnerStub with minimal pools, skipping PyTorch weight loading and GPU KV cache allocation', 'load_model_mlx_stub': 'load model metadata only in MlxModelRunnerStub without loading PyTorch model weights for MLX inference', 'create_dummy_kv_cache': 'create a _DummyKVCache that satisfies the KVCache interface without allocating GPU memory', 'create_dummy_model': 'create a _DummyModel stand-in so inspect.signature and getattr calls in ModelRunner.__init__ do not crash'}
```

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/mlx/scheduler_mixin.py

Prompts

```
['build an MlxModelRunner instance to load an MLX model on Apple Silicon with configurable pool size and radix cache', 'prefill a request with new token IDs and return the next predicted token ID using prefix slot matching', 'decode one token per request in a batch using the MlxModelRunner with batched or single-request attention', 'extend a chunked request by continuing prefill and syncing new KV cache to the shared pool', 'clear all active request states and release cached KV buffers back to the pool', 'create an MlxModelRunnerStub instance with mlx_pool_size for CPU-side scheduler bookkeeping on Apple Silicon', 'initialize MlxModelRunnerStub with minimal pools, skipping PyTorch weight loading and GPU KV cache allocation', 'load model metadata only in MlxModelRunnerStub without loading PyTorch model weights for MLX inference', 'create a _DummyKVCache that satisfies the KVCache interface without allocating GPU memory', 'create a _DummyModel stand-in so inspect.signature and getattr calls in ModelRunner.__init__ do not crash', 'run the MLX overlap scheduling loop that pipelines two in-flight lazy graphs on the GPU', 'review the MlxPendingJob dataclass that holds unfinished MLX work and graphs queued on the GPU', 'review the SchedulerMlxOverlapMixin class that adds MLX overlap scheduling to the Scheduler', 'refactor event_loop_overlap_mlx to support additional chain-breaking conditions for the MLX scheduling loop', 'summarize the MlxPendingJob dataclass attributes including lazy_tokens, prefills, extends, decode, mode, batch_copy, and reqs', 'initialize the MLX model runner and stub for Apple Silicon tensor parallel inference', 'route forward batch generation through the MLX model runner on Apple Silicon', 'run forward pass through the MLX model runner for prefill and decode modes', "lazily initialize the MLX KV pool after the stub's pools are ready", 'return None since the stub model runner has no real model for padding']
```

Usage

```
{'run_event_loop_overlap_mlx': 'run the MLX overlap scheduling loop that pipelines two in-flight lazy graphs on the GPU', 'review_MlxPendingJob': 'review the MlxPendingJob dataclass that holds unfinished MLX work and graphs queued on the GPU', 'review_SchedulerMlxOverlapMixin': 'review the SchedulerMlxOverlapMixin class that adds MLX overlap scheduling to the Scheduler', 'refactor_event_loop_overlap_mlx': 'refactor event_loop_overlap_mlx to support additional chain-breaking conditions for the MLX scheduling loop', 'summarize_MlxPendingJob': 'summarize the MlxPendingJob dataclass attributes including lazy_tokens, prefills, extends, decode, mode, batch_copy, and reqs'}
```

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/mlx/tp_worker.py

Prompts

```
['build an MlxModelRunner instance to load an MLX model on Apple Silicon with configurable pool size and radix cache', 'prefill a request with new token IDs and return the next predicted token ID using prefix slot matching', 'decode one token per request in a batch using the MlxModelRunner with batched or single-request attention', 'extend a chunked request by continuing prefill and syncing new KV cache to the shared pool', 'clear all active request states and release cached KV buffers back to the pool', 'create an MlxModelRunnerStub instance with mlx_pool_size for CPU-side scheduler bookkeeping on Apple Silicon', 'initialize MlxModelRunnerStub with minimal pools, skipping PyTorch weight loading and GPU KV cache allocation', 'load model metadata only in MlxModelRunnerStub without loading PyTorch model weights for MLX inference', 'create a _DummyKVCache that satisfies the KVCache interface without allocating GPU memory', 'create a _DummyModel stand-in so inspect.signature and getattr calls in ModelRunner.__init__ do not crash', 'run the MLX overlap scheduling loop that pipelines two in-flight lazy graphs on the GPU', 'review the MlxPendingJob dataclass that holds unfinished MLX work and graphs queued on the GPU', 'review the SchedulerMlxOverlapMixin class that adds MLX overlap scheduling to the Scheduler', 'refactor event_loop_overlap_mlx to support additional chain-breaking conditions for the MLX scheduling loop', 'summarize the MlxPendingJob dataclass attributes including lazy_tokens, prefills, extends, decode, mode, batch_copy, and reqs', 'initialize the MLX model runner and stub for Apple Silicon tensor parallel inference', 'route forward batch generation through the MLX model runner on Apple Silicon', 'run forward pass through the MLX model runner for prefill and decode modes', "lazily initialize the MLX KV pool after the stub's pools are ready", 'return None since the stub model runner has no real model for padding']
```

Usage

```
{'init_model_runner': 'initialize the MLX model runner and stub for Apple Silicon tensor parallel inference', 'forward_batch_generation': 'route forward batch generation through the MLX model runner on Apple Silicon', 'forward_batch_generation_mlx': 'run forward pass through the MLX model runner for prefill and decode modes', 'ensure_mlx_pool_initialized': "lazily initialize the MLX KV pool after the stub's pools are ready", 'get_pad_input_ids_func': 'return None since the stub model runner has no real model for padding'}
```

