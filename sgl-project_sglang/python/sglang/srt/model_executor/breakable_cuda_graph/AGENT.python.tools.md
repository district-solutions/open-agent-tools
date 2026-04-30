# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/model_executor/breakable_cuda_graph/breakable_cuda_graph.py

Prompts

```
['create a BreakableCUDAGraph instance for capturing CUDA operations with support for graph breaks', 'use BreakableCUDAGraphCapture as a context manager to begin and end a breakable CUDA graph capture', 'apply the eager_on_graph decorator to skip CUDA graph capture for a specific function', 'call break_graph to insert a graph break and split the CUDA graph into separate segments', 'replay a BreakableCUDAGraph to execute all captured segments including eager break functions', 'check if the breakable CUDA graph context is currently active by calling is_in_breakable_cuda_graph', 'enable the breakable CUDA graph runner by using enable_breakable_cuda_graph as a context manager', 'review the breakable CUDA graph context module to understand the capture and replay lifecycle', 'summarize the is_in_breakable_cuda_graph function that returns a boolean indicating active graph state', 'refactor the _in_breakable_cuda_graph global flag to use thread-local storage for safer concurrency', 'test the checkCudaErrors function that validates CUDA runtime results and raises on errors', 'summarize the checkCudaErrors function that checks CUDA error codes and extracts return values', 'review the _cudaGetErrorString function that converts CUDA error codes to human-readable strings', 'refactor the checkCudaErrors function to remove the duplicate cuda.bindings availability check', 'create a CUDA error handling utility that wraps cuda.bindings runtime calls and raises on failure']
```

Usage

```
{'create_BreakableCUDAGraph': 'create a BreakableCUDAGraph instance for capturing CUDA operations with support for graph breaks', 'use_BreakableCUDAGraphCapture': 'use BreakableCUDAGraphCapture as a context manager to begin and end a breakable CUDA graph capture', 'apply_eager_on_graph': 'apply the eager_on_graph decorator to skip CUDA graph capture for a specific function', 'call_break_graph': 'call break_graph to insert a graph break and split the CUDA graph into separate segments', 'replay_BreakableCUDAGraph': 'replay a BreakableCUDAGraph to execute all captured segments including eager break functions'}
```

## File: sgl-project_sglang/python/sglang/srt/model_executor/breakable_cuda_graph/context.py

Prompts

```
['create a BreakableCUDAGraph instance for capturing CUDA operations with support for graph breaks', 'use BreakableCUDAGraphCapture as a context manager to begin and end a breakable CUDA graph capture', 'apply the eager_on_graph decorator to skip CUDA graph capture for a specific function', 'call break_graph to insert a graph break and split the CUDA graph into separate segments', 'replay a BreakableCUDAGraph to execute all captured segments including eager break functions', 'check if the breakable CUDA graph context is currently active by calling is_in_breakable_cuda_graph', 'enable the breakable CUDA graph runner by using enable_breakable_cuda_graph as a context manager', 'review the breakable CUDA graph context module to understand the capture and replay lifecycle', 'summarize the is_in_breakable_cuda_graph function that returns a boolean indicating active graph state', 'refactor the _in_breakable_cuda_graph global flag to use thread-local storage for safer concurrency', 'test the checkCudaErrors function that validates CUDA runtime results and raises on errors', 'summarize the checkCudaErrors function that checks CUDA error codes and extracts return values', 'review the _cudaGetErrorString function that converts CUDA error codes to human-readable strings', 'refactor the checkCudaErrors function to remove the duplicate cuda.bindings availability check', 'create a CUDA error handling utility that wraps cuda.bindings runtime calls and raises on failure']
```

Usage

```
{'check_breakable_cuda_graph_active': 'check if the breakable CUDA graph context is currently active by calling is_in_breakable_cuda_graph', 'enable_breakable_cuda_graph_context': 'enable the breakable CUDA graph runner by using enable_breakable_cuda_graph as a context manager', 'review_breakable_cuda_graph_context': 'review the breakable CUDA graph context module to understand the capture and replay lifecycle', 'summarize_is_in_breakable_cuda_graph': 'summarize the is_in_breakable_cuda_graph function that returns a boolean indicating active graph state', 'refactor_breakable_cuda_graph_flag': 'refactor the _in_breakable_cuda_graph global flag to use thread-local storage for safer concurrency'}
```

## File: sgl-project_sglang/python/sglang/srt/model_executor/breakable_cuda_graph/cuda_utils.py

Prompts

```
['create a BreakableCUDAGraph instance for capturing CUDA operations with support for graph breaks', 'use BreakableCUDAGraphCapture as a context manager to begin and end a breakable CUDA graph capture', 'apply the eager_on_graph decorator to skip CUDA graph capture for a specific function', 'call break_graph to insert a graph break and split the CUDA graph into separate segments', 'replay a BreakableCUDAGraph to execute all captured segments including eager break functions', 'check if the breakable CUDA graph context is currently active by calling is_in_breakable_cuda_graph', 'enable the breakable CUDA graph runner by using enable_breakable_cuda_graph as a context manager', 'review the breakable CUDA graph context module to understand the capture and replay lifecycle', 'summarize the is_in_breakable_cuda_graph function that returns a boolean indicating active graph state', 'refactor the _in_breakable_cuda_graph global flag to use thread-local storage for safer concurrency', 'test the checkCudaErrors function that validates CUDA runtime results and raises on errors', 'summarize the checkCudaErrors function that checks CUDA error codes and extracts return values', 'review the _cudaGetErrorString function that converts CUDA error codes to human-readable strings', 'refactor the checkCudaErrors function to remove the duplicate cuda.bindings availability check', 'create a CUDA error handling utility that wraps cuda.bindings runtime calls and raises on failure']
```

Usage

```
{'test_checkCudaErrors': 'test the checkCudaErrors function that validates CUDA runtime results and raises on errors', 'summarize_checkCudaErrors': 'summarize the checkCudaErrors function that checks CUDA error codes and extracts return values', 'review__cudaGetErrorString': 'review the _cudaGetErrorString function that converts CUDA error codes to human-readable strings', 'refactor_checkCudaErrors': 'refactor the checkCudaErrors function to remove the duplicate cuda.bindings availability check', 'create_cuda_error_handler': 'create a CUDA error handling utility that wraps cuda.bindings runtime calls and raises on failure'}
```

