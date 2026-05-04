# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/rl/ddppo/policy/multimae.py

Prompts

```
['build a MultiMAE visual encoder model from pretrained RGB and depth checkpoints for Habitat navigation', 'create a masked L1 loss function that computes element-wise absolute error with optional validity masking', 'test the MMAE forward pass with robot head RGB and depth observation tensors', 'review the get_model factory function that creates and loads a pretrained multivit_base MultiMAE model', 'refactor the MMAE class to filter visual observation keys from the Habitat observation space', 'build a ResNet-18 model with configurable in_channels, base_planes, and ngroups for feature extraction', 'build a ResNet-50 model with Bottleneck blocks and configurable in_channels, base_planes, and ngroups', 'build a ResNeXt-50 model with grouped convolutions and configurable cardinality for feature extraction', 'build a Squeeze-and-Excitation ResNet-50 model with SEBottleneck blocks for attention-based feature extraction', 'build a Squeeze-and-Excitation ResNeXt-101 model with SEResNeXtBottleneck blocks for deep feature extraction', 'build a PointNavResNetPolicy from an OmegaConf DictConfig with observation and action spaces', 'create a ResNetEncoder to process visual observations through a ResNet backbone with configurable baseplanes', 'run the PointNavResNetNet forward pass with observations, RNN hidden states, previous actions, and masks', 'review the ResNetEncoder layer_init method to verify Kaiming normal weight initialization for Conv2d and Linear layers', 'test the PointNavResNetNet forward pass with GPS, compass, heading, and proximity sensor observations', 'create a RunningMeanAndVar module with n_channels to track running statistics for tensor normalization', 'build a forward pass through RunningMeanAndVar to normalize input tensors using running mean and variance', 'test the RunningMeanAndVar module in training mode to update running mean and variance statistics', 'review the RunningMeanAndVar class for distributed training support with all_reduce operations', "summarize the RunningMeanAndVar implementation using Welford's online algorithm for numerically stable variance computation"]
```

Usage

```
{'build_MMAE_model': 'build a MultiMAE visual encoder model from pretrained RGB and depth checkpoints for Habitat navigation', 'create_masked_l1_loss': 'create a masked L1 loss function that computes element-wise absolute error with optional validity masking', 'test_MMAE_forward': 'test the MMAE forward pass with robot head RGB and depth observation tensors', 'review_get_model': 'review the get_model factory function that creates and loads a pretrained multivit_base MultiMAE model', 'refactor_MMAE_visual_keys': 'refactor the MMAE class to filter visual observation keys from the Habitat observation space'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/rl/ddppo/policy/resnet.py

Prompts

```
['build a MultiMAE visual encoder model from pretrained RGB and depth checkpoints for Habitat navigation', 'create a masked L1 loss function that computes element-wise absolute error with optional validity masking', 'test the MMAE forward pass with robot head RGB and depth observation tensors', 'review the get_model factory function that creates and loads a pretrained multivit_base MultiMAE model', 'refactor the MMAE class to filter visual observation keys from the Habitat observation space', 'build a ResNet-18 model with configurable in_channels, base_planes, and ngroups for feature extraction', 'build a ResNet-50 model with Bottleneck blocks and configurable in_channels, base_planes, and ngroups', 'build a ResNeXt-50 model with grouped convolutions and configurable cardinality for feature extraction', 'build a Squeeze-and-Excitation ResNet-50 model with SEBottleneck blocks for attention-based feature extraction', 'build a Squeeze-and-Excitation ResNeXt-101 model with SEResNeXtBottleneck blocks for deep feature extraction', 'build a PointNavResNetPolicy from an OmegaConf DictConfig with observation and action spaces', 'create a ResNetEncoder to process visual observations through a ResNet backbone with configurable baseplanes', 'run the PointNavResNetNet forward pass with observations, RNN hidden states, previous actions, and masks', 'review the ResNetEncoder layer_init method to verify Kaiming normal weight initialization for Conv2d and Linear layers', 'test the PointNavResNetNet forward pass with GPS, compass, heading, and proximity sensor observations', 'create a RunningMeanAndVar module with n_channels to track running statistics for tensor normalization', 'build a forward pass through RunningMeanAndVar to normalize input tensors using running mean and variance', 'test the RunningMeanAndVar module in training mode to update running mean and variance statistics', 'review the RunningMeanAndVar class for distributed training support with all_reduce operations', "summarize the RunningMeanAndVar implementation using Welford's online algorithm for numerically stable variance computation"]
```

Usage

```
{'build_resnet18_model': 'build a ResNet-18 model with configurable in_channels, base_planes, and ngroups for feature extraction', 'build_resnet50_model': 'build a ResNet-50 model with Bottleneck blocks and configurable in_channels, base_planes, and ngroups', 'build_resnext50_model': 'build a ResNeXt-50 model with grouped convolutions and configurable cardinality for feature extraction', 'build_se_resnet50_model': 'build a Squeeze-and-Excitation ResNet-50 model with SEBottleneck blocks for attention-based feature extraction', 'build_se_resnext101_model': 'build a Squeeze-and-Excitation ResNeXt-101 model with SEResNeXtBottleneck blocks for deep feature extraction'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/rl/ddppo/policy/resnet_policy.py

Prompts

```
['build a MultiMAE visual encoder model from pretrained RGB and depth checkpoints for Habitat navigation', 'create a masked L1 loss function that computes element-wise absolute error with optional validity masking', 'test the MMAE forward pass with robot head RGB and depth observation tensors', 'review the get_model factory function that creates and loads a pretrained multivit_base MultiMAE model', 'refactor the MMAE class to filter visual observation keys from the Habitat observation space', 'build a ResNet-18 model with configurable in_channels, base_planes, and ngroups for feature extraction', 'build a ResNet-50 model with Bottleneck blocks and configurable in_channels, base_planes, and ngroups', 'build a ResNeXt-50 model with grouped convolutions and configurable cardinality for feature extraction', 'build a Squeeze-and-Excitation ResNet-50 model with SEBottleneck blocks for attention-based feature extraction', 'build a Squeeze-and-Excitation ResNeXt-101 model with SEResNeXtBottleneck blocks for deep feature extraction', 'build a PointNavResNetPolicy from an OmegaConf DictConfig with observation and action spaces', 'create a ResNetEncoder to process visual observations through a ResNet backbone with configurable baseplanes', 'run the PointNavResNetNet forward pass with observations, RNN hidden states, previous actions, and masks', 'review the ResNetEncoder layer_init method to verify Kaiming normal weight initialization for Conv2d and Linear layers', 'test the PointNavResNetNet forward pass with GPS, compass, heading, and proximity sensor observations', 'create a RunningMeanAndVar module with n_channels to track running statistics for tensor normalization', 'build a forward pass through RunningMeanAndVar to normalize input tensors using running mean and variance', 'test the RunningMeanAndVar module in training mode to update running mean and variance statistics', 'review the RunningMeanAndVar class for distributed training support with all_reduce operations', "summarize the RunningMeanAndVar implementation using Welford's online algorithm for numerically stable variance computation"]
```

Usage

```
{'build_PointNavResNetPolicy_from_config': 'build a PointNavResNetPolicy from an OmegaConf DictConfig with observation and action spaces', 'create_ResNetEncoder_for_visual_obs': 'create a ResNetEncoder to process visual observations through a ResNet backbone with configurable baseplanes', 'run_PointNavResNetNet_forward': 'run the PointNavResNetNet forward pass with observations, RNN hidden states, previous actions, and masks', 'review_ResNetEncoder_layer_init': 'review the ResNetEncoder layer_init method to verify Kaiming normal weight initialization for Conv2d and Linear layers', 'test_PointNavResNetNet_sensor_embeddings': 'test the PointNavResNetNet forward pass with GPS, compass, heading, and proximity sensor observations'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/rl/ddppo/policy/running_mean_and_var.py

Prompts

```
['build a MultiMAE visual encoder model from pretrained RGB and depth checkpoints for Habitat navigation', 'create a masked L1 loss function that computes element-wise absolute error with optional validity masking', 'test the MMAE forward pass with robot head RGB and depth observation tensors', 'review the get_model factory function that creates and loads a pretrained multivit_base MultiMAE model', 'refactor the MMAE class to filter visual observation keys from the Habitat observation space', 'build a ResNet-18 model with configurable in_channels, base_planes, and ngroups for feature extraction', 'build a ResNet-50 model with Bottleneck blocks and configurable in_channels, base_planes, and ngroups', 'build a ResNeXt-50 model with grouped convolutions and configurable cardinality for feature extraction', 'build a Squeeze-and-Excitation ResNet-50 model with SEBottleneck blocks for attention-based feature extraction', 'build a Squeeze-and-Excitation ResNeXt-101 model with SEResNeXtBottleneck blocks for deep feature extraction', 'build a PointNavResNetPolicy from an OmegaConf DictConfig with observation and action spaces', 'create a ResNetEncoder to process visual observations through a ResNet backbone with configurable baseplanes', 'run the PointNavResNetNet forward pass with observations, RNN hidden states, previous actions, and masks', 'review the ResNetEncoder layer_init method to verify Kaiming normal weight initialization for Conv2d and Linear layers', 'test the PointNavResNetNet forward pass with GPS, compass, heading, and proximity sensor observations', 'create a RunningMeanAndVar module with n_channels to track running statistics for tensor normalization', 'build a forward pass through RunningMeanAndVar to normalize input tensors using running mean and variance', 'test the RunningMeanAndVar module in training mode to update running mean and variance statistics', 'review the RunningMeanAndVar class for distributed training support with all_reduce operations', "summarize the RunningMeanAndVar implementation using Welford's online algorithm for numerically stable variance computation"]
```

Usage

```
{'create_running_mean_var_module': 'create a RunningMeanAndVar module with n_channels to track running statistics for tensor normalization', 'build_running_mean_var_forward': 'build a forward pass through RunningMeanAndVar to normalize input tensors using running mean and variance', 'test_running_mean_var_training': 'test the RunningMeanAndVar module in training mode to update running mean and variance statistics', 'review_running_mean_var_distributed': 'review the RunningMeanAndVar class for distributed training support with all_reduce operations', 'summarize_running_mean_var_welford': "summarize the RunningMeanAndVar implementation using Welford's online algorithm for numerically stable variance computation"}
```

