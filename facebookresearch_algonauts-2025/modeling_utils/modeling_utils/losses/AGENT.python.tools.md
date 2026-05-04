# Agent Python Tools

- repo: facebookresearch/algonauts-2025
- repo_uri: https://github.com/facebookresearch/algonauts-2025

## File: facebookresearch_algonauts-2025/modeling_utils/modeling_utils/losses/base.py

Prompts

```
['build a TorchLossConfig with a named PyTorch loss and kwargs then call build to get the nn.Module', 'build a custom loss config subclass of BaseLossConfig with a name field and build method', 'review the PearsonLoss class that computes 1 minus Pearson correlation coefficient as a loss', 'review how convert_to_pydantic auto-generates a Pydantic config class from each custom loss nn.Module', 'review update_config_loss which rebuilds the discriminated LossConfig union type from all BaseLossConfig subclasses', 'create a PearsonLoss instance with mean reduction to compute 1 minus Pearson correlation coefficient', 'create a PearsonLoss instance with sum reduction to compute the summed loss across samples', 'create a PearsonLoss instance with a custom dimension for computing correlation along a specific axis', 'run the forward pass of PearsonLoss with two tensors to get the correlation-based loss value', 'review the PearsonLoss class to understand how it computes 1 minus PCC using covariance and standard deviations']
```

Usage

```
{'build_TorchLossConfig': 'build a TorchLossConfig with a named PyTorch loss and kwargs then call build to get the nn.Module', 'build_BaseLossConfig_subclass': 'build a custom loss config subclass of BaseLossConfig with a name field and build method', 'review_PearsonLoss': 'review the PearsonLoss class that computes 1 minus Pearson correlation coefficient as a loss', 'review_convert_to_pydantic': 'review how convert_to_pydantic auto-generates a Pydantic config class from each custom loss nn.Module', 'review_update_config_loss': 'review update_config_loss which rebuilds the discriminated LossConfig union type from all BaseLossConfig subclasses'}
```

## File: facebookresearch_algonauts-2025/modeling_utils/modeling_utils/losses/losses.py

Prompts

```
['build a TorchLossConfig with a named PyTorch loss and kwargs then call build to get the nn.Module', 'build a custom loss config subclass of BaseLossConfig with a name field and build method', 'review the PearsonLoss class that computes 1 minus Pearson correlation coefficient as a loss', 'review how convert_to_pydantic auto-generates a Pydantic config class from each custom loss nn.Module', 'review update_config_loss which rebuilds the discriminated LossConfig union type from all BaseLossConfig subclasses', 'create a PearsonLoss instance with mean reduction to compute 1 minus Pearson correlation coefficient', 'create a PearsonLoss instance with sum reduction to compute the summed loss across samples', 'create a PearsonLoss instance with a custom dimension for computing correlation along a specific axis', 'run the forward pass of PearsonLoss with two tensors to get the correlation-based loss value', 'review the PearsonLoss class to understand how it computes 1 minus PCC using covariance and standard deviations']
```

Usage

```
{'create_PearsonLoss_mean': 'create a PearsonLoss instance with mean reduction to compute 1 minus Pearson correlation coefficient', 'create_PearsonLoss_sum': 'create a PearsonLoss instance with sum reduction to compute the summed loss across samples', 'create_PearsonLoss_custom_dim': 'create a PearsonLoss instance with a custom dimension for computing correlation along a specific axis', 'run_PearsonLoss_forward': 'run the forward pass of PearsonLoss with two tensors to get the correlation-based loss value', 'review_PearsonLoss_implementation': 'review the PearsonLoss class to understand how it computes 1 minus PCC using covariance and standard deviations'}
```

