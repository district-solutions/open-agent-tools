# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/v1/worker/gpu/spec_decode/probabilistic_rejection_sampler_utils.py

Prompts

```
['run probabilistic_rejection_sample to sample tokens from target and draft logits using rejection sampling', 'test probabilistic_rejection_sample with target logits, draft logits, temperature, and seed tensors', 'refactor probabilistic_rejection_sample to support different vocabulary block sizes for GPU memory optimization', 'review probabilistic_rejection_sample for numerical stability in logsumexp and residual logit computation', 'summarize probabilistic_rejection_sample which performs speculative decoding rejection sampling with greedy and temperature-based paths', 'test the synthetic_rejection_sample function that performs GPU-accelerated rejection sampling for speculative decoding', 'run compute_synthetic_rejection_sampler_params to calculate base acceptance rate and decay factor for a given average probability and number of speculative steps', 'review the _synthetic_rejection_sample_kernel triton kernel that performs per-request synthetic rejection sampling on GPU', 'refactor compute_synthetic_rejection_sampler_params to support configurable minimum acceptance decay factor', 'summarize the synthetic rejection sampler utilities for vLLM speculative decoding', 'create a DraftTokensHandler instance for managing draft token data in speculative decoding', 'set draft tokens from an InputBatch and torch.Tensor for structured output validation', 'get draft token IDs as DraftTokenIds with request IDs and token lists', 'test the DraftTokensHandler class with async CUDA stream synchronization', 'review the DraftTokensHandler class and its GPU async copy workflow']
```

Usage

```
{'run_probabilistic_rejection_sample': 'run probabilistic_rejection_sample to sample tokens from target and draft logits using rejection sampling', 'test_probabilistic_rejection_sample': 'test probabilistic_rejection_sample with target logits, draft logits, temperature, and seed tensors', 'refactor_probabilistic_rejection_sample': 'refactor probabilistic_rejection_sample to support different vocabulary block sizes for GPU memory optimization', 'review_probabilistic_rejection_sample': 'review probabilistic_rejection_sample for numerical stability in logsumexp and residual logit computation', 'summarize_probabilistic_rejection_sample': 'summarize probabilistic_rejection_sample which performs speculative decoding rejection sampling with greedy and temperature-based paths'}
```

## File: vllm-project_vllm/vllm/v1/worker/gpu/spec_decode/synthetic_rejection_sampler_utils.py

Prompts

```
['run probabilistic_rejection_sample to sample tokens from target and draft logits using rejection sampling', 'test probabilistic_rejection_sample with target logits, draft logits, temperature, and seed tensors', 'refactor probabilistic_rejection_sample to support different vocabulary block sizes for GPU memory optimization', 'review probabilistic_rejection_sample for numerical stability in logsumexp and residual logit computation', 'summarize probabilistic_rejection_sample which performs speculative decoding rejection sampling with greedy and temperature-based paths', 'test the synthetic_rejection_sample function that performs GPU-accelerated rejection sampling for speculative decoding', 'run compute_synthetic_rejection_sampler_params to calculate base acceptance rate and decay factor for a given average probability and number of speculative steps', 'review the _synthetic_rejection_sample_kernel triton kernel that performs per-request synthetic rejection sampling on GPU', 'refactor compute_synthetic_rejection_sampler_params to support configurable minimum acceptance decay factor', 'summarize the synthetic rejection sampler utilities for vLLM speculative decoding', 'create a DraftTokensHandler instance for managing draft token data in speculative decoding', 'set draft tokens from an InputBatch and torch.Tensor for structured output validation', 'get draft token IDs as DraftTokenIds with request IDs and token lists', 'test the DraftTokensHandler class with async CUDA stream synchronization', 'review the DraftTokensHandler class and its GPU async copy workflow']
```

Usage

```
{'test_synthetic_rejection_sample': 'test the synthetic_rejection_sample function that performs GPU-accelerated rejection sampling for speculative decoding', 'run_compute_synthetic_rejection_sampler_params': 'run compute_synthetic_rejection_sampler_params to calculate base acceptance rate and decay factor for a given average probability and number of speculative steps', 'review_synthetic_rejection_sample_kernel': 'review the _synthetic_rejection_sample_kernel triton kernel that performs per-request synthetic rejection sampling on GPU', 'refactor_compute_synthetic_rejection_sampler_params': 'refactor compute_synthetic_rejection_sampler_params to support configurable minimum acceptance decay factor', 'summarize_synthetic_rejection_sampler_utils': 'summarize the synthetic rejection sampler utilities for vLLM speculative decoding'}
```

## File: vllm-project_vllm/vllm/v1/worker/gpu/spec_decode/utils.py

Prompts

```
['run probabilistic_rejection_sample to sample tokens from target and draft logits using rejection sampling', 'test probabilistic_rejection_sample with target logits, draft logits, temperature, and seed tensors', 'refactor probabilistic_rejection_sample to support different vocabulary block sizes for GPU memory optimization', 'review probabilistic_rejection_sample for numerical stability in logsumexp and residual logit computation', 'summarize probabilistic_rejection_sample which performs speculative decoding rejection sampling with greedy and temperature-based paths', 'test the synthetic_rejection_sample function that performs GPU-accelerated rejection sampling for speculative decoding', 'run compute_synthetic_rejection_sampler_params to calculate base acceptance rate and decay factor for a given average probability and number of speculative steps', 'review the _synthetic_rejection_sample_kernel triton kernel that performs per-request synthetic rejection sampling on GPU', 'refactor compute_synthetic_rejection_sampler_params to support configurable minimum acceptance decay factor', 'summarize the synthetic rejection sampler utilities for vLLM speculative decoding', 'create a DraftTokensHandler instance for managing draft token data in speculative decoding', 'set draft tokens from an InputBatch and torch.Tensor for structured output validation', 'get draft token IDs as DraftTokenIds with request IDs and token lists', 'test the DraftTokensHandler class with async CUDA stream synchronization', 'review the DraftTokensHandler class and its GPU async copy workflow']
```

Usage

```
{'create_DraftTokensHandler': 'create a DraftTokensHandler instance for managing draft token data in speculative decoding', 'set_draft_tokens': 'set draft tokens from an InputBatch and torch.Tensor for structured output validation', 'get_draft_tokens': 'get draft token IDs as DraftTokenIds with request IDs and token lists', 'test_DraftTokensHandler': 'test the DraftTokensHandler class with async CUDA stream synchronization', 'review_DraftTokensHandler': 'review the DraftTokensHandler class and its GPU async copy workflow'}
```

