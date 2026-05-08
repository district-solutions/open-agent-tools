# Agent Python Tools

- repo: facebookresearch/mask2former
- repo_uri: https://github.com/facebookresearch/mask2former

## File: facebookresearch_mask2former/mask2former_video/utils/memory.py

Prompts

```
['wrap a pytorch function with retry_if_cuda_oom to automatically retry on CUDA out of memory errors', 'use retry_if_cuda_oom which clears CUDA cache and retries the function after an OOM error', 'use retry_if_cuda_oom to fall back to CPU execution when GPU memory is exhausted after retries', 'review the retry_if_cuda_oom decorator that handles CUDA OOM by retrying with cache clear and CPU fallback', 'summarize the retry_if_cuda_oom decorator which catches OOM, empties cache, retries, then falls back to CPU']
```

Usage

```
{'use_retry_if_cuda_oom_decorator': 'wrap a pytorch function with retry_if_cuda_oom to automatically retry on CUDA out of memory errors', 'handle_cuda_oom_with_empty_cache': 'use retry_if_cuda_oom which clears CUDA cache and retries the function after an OOM error', 'fallback_to_cpu_on_cuda_oom': 'use retry_if_cuda_oom to fall back to CPU execution when GPU memory is exhausted after retries', 'review_retry_if_cuda_oom_implementation': 'review the retry_if_cuda_oom decorator that handles CUDA OOM by retrying with cache clear and CPU fallback', 'summarize_cuda_oom_retry_logic': 'summarize the retry_if_cuda_oom decorator which catches OOM, empties cache, retries, then falls back to CPU'}
```

