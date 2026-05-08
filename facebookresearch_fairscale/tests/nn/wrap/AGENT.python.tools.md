# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/tests/nn/wrap/test_wrap.py

Prompts

```
['test wrapping a PyTorch nn.Linear module with FSDP using enable_wrap and wrap', 'test auto wrapping child modules based on min_num_params threshold using default_auto_wrap_policy', 'test auto wrapping the root module by setting skip_params_check_for_root to True', 'test preventing certain modules from being wrapped by adding them to force_leaf_modules', 'test forward and backward passes through an auto-wrapped FSDP model with mixed precision']
```

Usage

```
{'test_wrap_with_FSDP': 'test wrapping a PyTorch nn.Linear module with FSDP using enable_wrap and wrap', 'test_auto_wrap_policy': 'test auto wrapping child modules based on min_num_params threshold using default_auto_wrap_policy', 'test_auto_wrap_skip_root': 'test auto wrapping the root module by setting skip_params_check_for_root to True', 'test_force_leaf_modules': 'test preventing certain modules from being wrapped by adding them to force_leaf_modules', 'test_FSDP_forward_backward': 'test forward and backward passes through an auto-wrapped FSDP model with mixed precision'}
```

