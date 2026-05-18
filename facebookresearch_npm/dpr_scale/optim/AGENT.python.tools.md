# Agent Python Tools

- repo: facebookresearch/npm
- repo_uri: https://github.com/facebookresearch/npm

## File: facebookresearch_npm/dpr_scale/optim/madgrad.py

Prompts

```
['create a MADGRAD optimizer instance with custom learning rate, momentum, and weight decay for model training', 'run a single optimization step using the MADGRAD optimizer to update model parameters based on computed gradients', 'add a new parameter group to the MADGRAD optimizer for fine-tuning frozen layers during training', 'review the MADGRAD optimizer initialize_state method that sets up grad_sum_sq, s, and x0 state tensors', 'refactor the MADGRAD optimizer step method to handle sparse gradient updates with momentum and weight decay']
```

Usage

```
{'create_madgrad_optimizer': 'create a MADGRAD optimizer instance with custom learning rate, momentum, and weight decay for model training', 'run_madgrad_step': 'run a single optimization step using the MADGRAD optimizer to update model parameters based on computed gradients', 'add_madgrad_param_group': 'add a new parameter group to the MADGRAD optimizer for fine-tuning frozen layers during training', 'review_madgrad_initialize_state': 'review the MADGRAD optimizer initialize_state method that sets up grad_sum_sq, s, and x0 state tensors', 'refactor_madgrad_sparse_gradients': 'refactor the MADGRAD optimizer step method to handle sparse gradient updates with momentum and weight decay'}
```

