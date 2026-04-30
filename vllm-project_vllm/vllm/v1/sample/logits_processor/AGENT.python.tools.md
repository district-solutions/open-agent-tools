# Agent Python Tools

- repo: vllm-project/vllm
- repo_uri: https://github.com/vllm-project/vllm

## File: vllm-project_vllm/vllm/v1/sample/logits_processor/builtin.py

Prompts

```
['build a MinPLogitsProcessor to filter tokens below min_p threshold scaled by max probability', 'create a LogitBiasLogitsProcessor to add bias values to specific token logits for requested sequences', 'test the MinTokensLogitsProcessor to inhibit stop tokens until minimum output length is reached', 'refactor the ThinkingTokenBudgetLogitsProcessor to enforce a budget on thinking section token count', 'summarize the process_dict_updates utility that manages sparse dict state across batch add, remove, and move operations', 'create a LogitsProcessor subclass with apply, is_argmax_invariant, and update_state methods', 'test the BatchUpdate dataclass with removed, added, and moved request sequences', 'test the MoveDirectionality enum with UNIDIRECTIONAL and SWAP values', 'review the LogitsProcessor.validate_params method that validates SamplingParams', 'review the LogitsProcessor.apply method that modifies and returns batch logits tensors', 'build a BatchUpdateBuilder to track persistent batch state changes and build batch update data structures', 'create a BatchUpdateBuilder, register removed and added requests, then call get_and_reset to produce a BatchUpdate', 'test the BatchUpdateBuilder removed_append, peek_removed, and pop_removed methods', 'create a LogitsProcessors collection that splits initialized logits processors into argmax-invariant and non-argmax-invariant lists', 'review the BatchUpdateBuilder class for tracking batch state changes and building batch update data structures']
```

Usage

```
{'build_minp_logits_processor': 'build a MinPLogitsProcessor to filter tokens below min_p threshold scaled by max probability', 'create_logit_bias_processor': 'create a LogitBiasLogitsProcessor to add bias values to specific token logits for requested sequences', 'test_min_tokens_processor': 'test the MinTokensLogitsProcessor to inhibit stop tokens until minimum output length is reached', 'refactor_thinking_token_budget': 'refactor the ThinkingTokenBudgetLogitsProcessor to enforce a budget on thinking section token count', 'summarize_process_dict_updates': 'summarize the process_dict_updates utility that manages sparse dict state across batch add, remove, and move operations'}
```

## File: vllm-project_vllm/vllm/v1/sample/logits_processor/interface.py

Prompts

```
['build a MinPLogitsProcessor to filter tokens below min_p threshold scaled by max probability', 'create a LogitBiasLogitsProcessor to add bias values to specific token logits for requested sequences', 'test the MinTokensLogitsProcessor to inhibit stop tokens until minimum output length is reached', 'refactor the ThinkingTokenBudgetLogitsProcessor to enforce a budget on thinking section token count', 'summarize the process_dict_updates utility that manages sparse dict state across batch add, remove, and move operations', 'create a LogitsProcessor subclass with apply, is_argmax_invariant, and update_state methods', 'test the BatchUpdate dataclass with removed, added, and moved request sequences', 'test the MoveDirectionality enum with UNIDIRECTIONAL and SWAP values', 'review the LogitsProcessor.validate_params method that validates SamplingParams', 'review the LogitsProcessor.apply method that modifies and returns batch logits tensors', 'build a BatchUpdateBuilder to track persistent batch state changes and build batch update data structures', 'create a BatchUpdateBuilder, register removed and added requests, then call get_and_reset to produce a BatchUpdate', 'test the BatchUpdateBuilder removed_append, peek_removed, and pop_removed methods', 'create a LogitsProcessors collection that splits initialized logits processors into argmax-invariant and non-argmax-invariant lists', 'review the BatchUpdateBuilder class for tracking batch state changes and building batch update data structures']
```

Usage

```
{'create_LogitsProcessor': 'create a LogitsProcessor subclass with apply, is_argmax_invariant, and update_state methods', 'test_BatchUpdate': 'test the BatchUpdate dataclass with removed, added, and moved request sequences', 'test_MoveDirectionality': 'test the MoveDirectionality enum with UNIDIRECTIONAL and SWAP values', 'review_LogitsProcessor_validate_params': 'review the LogitsProcessor.validate_params method that validates SamplingParams', 'review_LogitsProcessor_apply': 'review the LogitsProcessor.apply method that modifies and returns batch logits tensors'}
```

## File: vllm-project_vllm/vllm/v1/sample/logits_processor/state.py

Prompts

```
['build a MinPLogitsProcessor to filter tokens below min_p threshold scaled by max probability', 'create a LogitBiasLogitsProcessor to add bias values to specific token logits for requested sequences', 'test the MinTokensLogitsProcessor to inhibit stop tokens until minimum output length is reached', 'refactor the ThinkingTokenBudgetLogitsProcessor to enforce a budget on thinking section token count', 'summarize the process_dict_updates utility that manages sparse dict state across batch add, remove, and move operations', 'create a LogitsProcessor subclass with apply, is_argmax_invariant, and update_state methods', 'test the BatchUpdate dataclass with removed, added, and moved request sequences', 'test the MoveDirectionality enum with UNIDIRECTIONAL and SWAP values', 'review the LogitsProcessor.validate_params method that validates SamplingParams', 'review the LogitsProcessor.apply method that modifies and returns batch logits tensors', 'build a BatchUpdateBuilder to track persistent batch state changes and build batch update data structures', 'create a BatchUpdateBuilder, register removed and added requests, then call get_and_reset to produce a BatchUpdate', 'test the BatchUpdateBuilder removed_append, peek_removed, and pop_removed methods', 'create a LogitsProcessors collection that splits initialized logits processors into argmax-invariant and non-argmax-invariant lists', 'review the BatchUpdateBuilder class for tracking batch state changes and building batch update data structures']
```

Usage

```
{'build_batch_update_builder': 'build a BatchUpdateBuilder to track persistent batch state changes and build batch update data structures', 'create_batch_update': 'create a BatchUpdateBuilder, register removed and added requests, then call get_and_reset to produce a BatchUpdate', 'test_batch_update_builder': 'test the BatchUpdateBuilder removed_append, peek_removed, and pop_removed methods', 'create_logits_processors': 'create a LogitsProcessors collection that splits initialized logits processors into argmax-invariant and non-argmax-invariant lists', 'review_batch_update_builder': 'review the BatchUpdateBuilder class for tracking batch state changes and building batch update data structures'}
```

