# Agent Python Tools

- repo: facebookresearch/perfect
- repo_uri: https://github.com/facebookresearch/perfect

## File: facebookresearch_perfect/fewshot/utils/utils.py

Prompts

```
['compute the accuracy from a list of losses and ground truth target labels', 'freeze all model parameters except adapters and optionally layernorms for adapter tuning', 'freeze all model parameters except biases and optionally lm_head for bitfit tuning', 'trim a sequence of input token ids by removing padding and limiting mask tokens', 'get a torch aggregation function like min, max, mean, or sum by name']
```

Usage

```
{'compute_accuracy_from_losses': 'compute the accuracy from a list of losses and ground truth target labels', 'set_trainable_params_for_adapters': 'freeze all model parameters except adapters and optionally layernorms for adapter tuning', 'set_trainable_params_for_bitfit': 'freeze all model parameters except biases and optionally lm_head for bitfit tuning', 'trim_input_ids': 'trim a sequence of input token ids by removing padding and limiting mask tokens', 'get_aggregation': 'get a torch aggregation function like min, max, mean, or sum by name'}
```

