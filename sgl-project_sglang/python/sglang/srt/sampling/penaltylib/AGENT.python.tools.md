# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/sampling/penaltylib/orchestrator.py

Prompts

```
['create a BatchedPenalizerOrchestrator with vocab size, schedule batch, and a set of penalizer types', 'apply all prepared penalizers to logits in-place, optionally expanding per-request penalties for speculative decoding', 'feed output tokens to all registered penalizers for cumulative penalty tracking', 'filter penalizers based on batch keep indices, releasing resources for unused requests', 'merge penalizers from another orchestrator into this one before batch request filtering', 'apply repetition scaling penalties to logits based on token presence in generated output', 'create a batched repetition penalizer that scales logits to penalize repeated tokens', 'filter batched repetition penalizer tensors by keep indices for batch pruning', 'merge two batched repetition penalizers by concatenating their penalty tensors']
```

Usage

```
{'create_batched_penalizer_orchestrator': 'create a BatchedPenalizerOrchestrator with vocab size, schedule batch, and a set of penalizer types', 'apply_penalizers_to_logits': 'apply all prepared penalizers to logits in-place, optionally expanding per-request penalties for speculative decoding', 'cumulate_output_tokens': 'feed output tokens to all registered penalizers for cumulative penalty tracking', 'filter_penalizers_by_indices': 'filter penalizers based on batch keep indices, releasing resources for unused requests', 'merge_penalizers_from_orchestrator': 'merge penalizers from another orchestrator into this one before batch request filtering'}
```

## File: sgl-project_sglang/python/sglang/srt/sampling/penaltylib/repetition_penalty.py

Prompts

```
['create a BatchedPenalizerOrchestrator with vocab size, schedule batch, and a set of penalizer types', 'apply all prepared penalizers to logits in-place, optionally expanding per-request penalties for speculative decoding', 'feed output tokens to all registered penalizers for cumulative penalty tracking', 'filter penalizers based on batch keep indices, releasing resources for unused requests', 'merge penalizers from another orchestrator into this one before batch request filtering', 'apply repetition scaling penalties to logits based on token presence in generated output', 'create a batched repetition penalizer that scales logits to penalize repeated tokens', 'filter batched repetition penalizer tensors by keep indices for batch pruning', 'merge two batched repetition penalizers by concatenating their penalty tensors']
```

Usage

```
{'apply_scaling_penalties': 'apply repetition scaling penalties to logits based on token presence in generated output', 'create_BatchedRepetitionPenalizer': 'create a batched repetition penalizer that scales logits to penalize repeated tokens', 'cumulate_output_tokens': 'cumulate output token IDs into repetition penalty tracking tensor via scatter operation', 'filter_BatchedRepetitionPenalizer': 'filter batched repetition penalizer tensors by keep indices for batch pruning', 'merge_BatchedRepetitionPenalizer': 'merge two batched repetition penalizers by concatenating their penalty tensors'}
```

