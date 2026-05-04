# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/parlai_diplomacy/agents/generator_custom_inference/agents.py

Prompts

```
['build a BART agent that uses nucleus top-p sampling with probability cutoff for text generation', 'create a nucleus sampling decoder that greedily selects special tokens when their probability exceeds a threshold', 'review the rank_eval_label_candidates method to understand how candidate responses are scored by summed per-token cross-entropy loss', 'refactor the _generate method to use fast prefix token decoding that precomputes logprobs for forced prefix tokens', 'test the _mask_nucleus method to verify it returns a boolean mask indicating which tokens fall outside the top-p nucleus']
```

Usage

```
{'build_nucleus_sampling_agent': 'build a BART agent that uses nucleus top-p sampling with probability cutoff for text generation', 'create_nucleus_special_sampling': 'create a nucleus sampling decoder that greedily selects special tokens when their probability exceeds a threshold', 'review_rank_eval_label_candidates': 'review the rank_eval_label_candidates method to understand how candidate responses are scored by summed per-token cross-entropy loss', 'refactor_generate_with_prefix_tokens': 'refactor the _generate method to use fast prefix token decoding that precomputes logprobs for forced prefix tokens', 'test_mask_nucleus': 'test the _mask_nucleus method to verify it returns a boolean mask indicating which tokens fall outside the top-p nucleus'}
```

