# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/v1/sample/rejection_sampler.py

Prompts

```
['run the RejectionSampler forward pass with draft probabilities, target logits, and sampling metadata to produce sampled token IDs', 'parse the rejection sampler output by filtering placeholder tokens and returning per-request token ID lists', 'apply temperature scaling, top-k, and top-p constraints to target logits for non-greedy sampling', 'generate uniform random probability samples for rejection sampling with optional per-request seeding', 'sample recovered tokens from the adjusted probability distribution when draft tokens are rejected', 'build a vLLM Sampler module that samples next tokens from model logits with temperature, top_k, and top_p', 'run the Sampler forward pass to sample tokens from logits with sampling metadata and optional logprobs', 'test the gather_logprobs method to retrieve top-k logprobs and ranks for sampled tokens', 'refactor the apply_penalties method to apply repetition, frequency, and presence penalties to logits', 'review the gather_specific_token_logprobs method that computes logprobs for specific token IDs using a fused Triton kernel', 'create a ThinkingBudgetStateHolder instance with reasoning config, max sequences, and device parameters', 'sync per-request thinking budget state by adding, removing, or moving requests in a batch update', 'update thinking budget state from output token IDs and speculative token IDs after sampling', 'apply logit masking and forcing to end-of-thinking tokens when the thinking budget is exceeded', 'check if the thinking budget state holder has any tracked requests with active thinking token budgets']
```

Usage

```
{'run_rejection_sampler_forward': 'run the RejectionSampler forward pass with draft probabilities, target logits, and sampling metadata to produce sampled token IDs', 'parse_rejection_sampler_output': 'parse the rejection sampler output by filtering placeholder tokens and returning per-request token ID lists', 'apply_sampling_constraints': 'apply temperature scaling, top-k, and top-p constraints to target logits for non-greedy sampling', 'generate_uniform_probs': 'generate uniform random probability samples for rejection sampling with optional per-request seeding', 'sample_recovered_tokens': 'sample recovered tokens from the adjusted probability distribution when draft tokens are rejected'}
```

## File: vllm-project_vllm/vllm/v1/sample/sampler.py

Prompts

```
['run the RejectionSampler forward pass with draft probabilities, target logits, and sampling metadata to produce sampled token IDs', 'parse the rejection sampler output by filtering placeholder tokens and returning per-request token ID lists', 'apply temperature scaling, top-k, and top-p constraints to target logits for non-greedy sampling', 'generate uniform random probability samples for rejection sampling with optional per-request seeding', 'sample recovered tokens from the adjusted probability distribution when draft tokens are rejected', 'build a vLLM Sampler module that samples next tokens from model logits with temperature, top_k, and top_p', 'run the Sampler forward pass to sample tokens from logits with sampling metadata and optional logprobs', 'test the gather_logprobs method to retrieve top-k logprobs and ranks for sampled tokens', 'refactor the apply_penalties method to apply repetition, frequency, and presence penalties to logits', 'review the gather_specific_token_logprobs method that computes logprobs for specific token IDs using a fused Triton kernel', 'create a ThinkingBudgetStateHolder instance with reasoning config, max sequences, and device parameters', 'sync per-request thinking budget state by adding, removing, or moving requests in a batch update', 'update thinking budget state from output token IDs and speculative token IDs after sampling', 'apply logit masking and forcing to end-of-thinking tokens when the thinking budget is exceeded', 'check if the thinking budget state holder has any tracked requests with active thinking token budgets']
```

Usage

```
{'build_Sampler': 'build a vLLM Sampler module that samples next tokens from model logits with temperature, top_k, and top_p', 'run_Sampler_forward': 'run the Sampler forward pass to sample tokens from logits with sampling metadata and optional logprobs', 'test_gather_logprobs': 'test the gather_logprobs method to retrieve top-k logprobs and ranks for sampled tokens', 'refactor_apply_penalties': 'refactor the apply_penalties method to apply repetition, frequency, and presence penalties to logits', 'review_gather_specific_token_logprobs': 'review the gather_specific_token_logprobs method that computes logprobs for specific token IDs using a fused Triton kernel'}
```

## File: vllm-project_vllm/vllm/v1/sample/thinking_budget_state.py

Prompts

```
['run the RejectionSampler forward pass with draft probabilities, target logits, and sampling metadata to produce sampled token IDs', 'parse the rejection sampler output by filtering placeholder tokens and returning per-request token ID lists', 'apply temperature scaling, top-k, and top-p constraints to target logits for non-greedy sampling', 'generate uniform random probability samples for rejection sampling with optional per-request seeding', 'sample recovered tokens from the adjusted probability distribution when draft tokens are rejected', 'build a vLLM Sampler module that samples next tokens from model logits with temperature, top_k, and top_p', 'run the Sampler forward pass to sample tokens from logits with sampling metadata and optional logprobs', 'test the gather_logprobs method to retrieve top-k logprobs and ranks for sampled tokens', 'refactor the apply_penalties method to apply repetition, frequency, and presence penalties to logits', 'review the gather_specific_token_logprobs method that computes logprobs for specific token IDs using a fused Triton kernel', 'create a ThinkingBudgetStateHolder instance with reasoning config, max sequences, and device parameters', 'sync per-request thinking budget state by adding, removing, or moving requests in a batch update', 'update thinking budget state from output token IDs and speculative token IDs after sampling', 'apply logit masking and forcing to end-of-thinking tokens when the thinking budget is exceeded', 'check if the thinking budget state holder has any tracked requests with active thinking token budgets']
```

Usage

```
{'create_thinking_budget_state_holder': 'create a ThinkingBudgetStateHolder instance with reasoning config, max sequences, and device parameters', 'sync_batch_per_request_state': 'sync per-request thinking budget state by adding, removing, or moving requests in a batch update', 'update_thinking_state_from_sampling': 'update thinking budget state from output token IDs and speculative token IDs after sampling', 'apply_forcing_to_logits': 'apply logit masking and forcing to end-of-thinking tokens when the thinking budget is exceeded', 'check_tracked_requests': 'check if the thinking budget state holder has any tracked requests with active thinking token budgets'}
```

