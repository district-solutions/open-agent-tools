# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/v1/worker/gpu/metrics/logits.py

Prompts

```
['test the get_num_nans function to count NaN values in a logits tensor per request', 'run get_num_nans on a torch.Tensor of logits to get per-request NaN counts as an int32 tensor', 'review the get_num_nans function that launches a Triton kernel to count NaNs across vocab dimensions', 'refactor the get_num_nans function to support dynamic BLOCK_SIZE configuration for different vocab sizes', 'review the _num_nans_kernel Triton JIT kernel that iterates over vocab blocks counting NaN values per request']
```

Usage

```
{'test_get_num_nans': 'test the get_num_nans function to count NaN values in a logits tensor per request', 'run_get_num_nans': 'run get_num_nans on a torch.Tensor of logits to get per-request NaN counts as an int32 tensor', 'review_get_num_nans': 'review the get_num_nans function that launches a Triton kernel to count NaNs across vocab dimensions', 'refactor_get_num_nans': 'refactor the get_num_nans function to support dynamic BLOCK_SIZE configuration for different vocab sizes', 'review__num_nans_kernel': 'review the _num_nans_kernel Triton JIT kernel that iterates over vocab blocks counting NaN values per request'}
```

