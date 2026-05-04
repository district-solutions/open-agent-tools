# Agent Python Tools

- repo: google-deepmind/gemma
- repo_uri: https://github.com/google-deepmind/gemma

## File: google-deepmind_gemma/gemma/gm/losses/_dpo.py

Prompts

```
['build a DpoLoss instance with custom tau temperature and label smoothing parameters', 'compute the DPO loss values using policy logits, anchor logits, tokens, and sequence mask', 'compute per-token log probabilities from logits, targets, and sequence mask using log softmax', 'review the DpoLoss get_values method to understand how preference deltas are computed with tau scaling', 'refactor the DpoLoss class to support dynamic schedules for tau and label smoothing parameters', 'build an NpoLoss instance with a custom tau temperature for preference optimization training', 'compute the NPO loss by calling get_values with policy logits, anchor logits, tokens, and sequence mask', 'review the NpoLoss class to understand how it computes preference optimization loss using policy and anchor logits', 'refactor the NpoLoss class to use a dynamic tau schedule instead of a fixed float temperature value']
```

Usage

```
{'build_dpo_loss_class': 'build a DpoLoss instance with custom tau temperature and label smoothing parameters', 'compute_dpo_loss_get_values': 'compute the DPO loss values using policy logits, anchor logits, tokens, and sequence mask', 'compute_logprobs_for_target': 'compute per-token log probabilities from logits, targets, and sequence mask using log softmax', 'review_DpoLoss_get_values': 'review the DpoLoss get_values method to understand how preference deltas are computed with tau scaling', 'refactor_DpoLoss_schedules': 'refactor the DpoLoss class to support dynamic schedules for tau and label smoothing parameters'}
```

## File: google-deepmind_gemma/gemma/gm/losses/_npo.py

Prompts

```
['build a DpoLoss instance with custom tau temperature and label smoothing parameters', 'compute the DPO loss values using policy logits, anchor logits, tokens, and sequence mask', 'compute per-token log probabilities from logits, targets, and sequence mask using log softmax', 'review the DpoLoss get_values method to understand how preference deltas are computed with tau scaling', 'refactor the DpoLoss class to support dynamic schedules for tau and label smoothing parameters', 'build an NpoLoss instance with a custom tau temperature for preference optimization training', 'compute the NPO loss by calling get_values with policy logits, anchor logits, tokens, and sequence mask', 'review the NpoLoss class to understand how it computes preference optimization loss using policy and anchor logits', 'refactor the NpoLoss class to use a dynamic tau schedule instead of a fixed float temperature value']
```

Usage

```
{'build_npo_loss_instance': 'build an NpoLoss instance with a custom tau temperature for preference optimization training', 'compute_npo_loss_get_values': 'compute the NPO loss by calling get_values with policy logits, anchor logits, tokens, and sequence mask', 'compute_logprobs_for_target': 'compute per-token log probabilities for target tokens from logits using log softmax and sequence masking', 'review_npoloss_class': 'review the NpoLoss class to understand how it computes preference optimization loss using policy and anchor logits', 'refactor_npoloss_tau_schedule': 'refactor the NpoLoss class to use a dynamic tau schedule instead of a fixed float temperature value'}
```

