# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/rl/ddppo/policy/resnet.py

Prompts

```
['build a ResNet-18 model with BasicBlock for habitat simulation visual policy networks', 'build a ResNet-50 model with Bottleneck blocks for deep reinforcement learning visual features', 'build a ResNeXt-50 model with grouped convolutions and cardinality for improved feature extraction', 'build a SE-ResNet-50 model with squeeze-and-excitation attention for enhanced visual policy learning', 'build a SE-ResNeXt-101 model with attention and grouped convolutions for complex visual tasks', 'build a PointNavResNetPolicy with a resnet18 backbone and GRU recurrent layers for navigation', 'create a PointNavResNetPolicy from an omegaconf DictConfig with observation and action spaces', 'review the ResNetEncoder forward pass that processes visual observations through a ResNet backbone', 'refactor the ResNetCLIPEncoder to swap the pooling strategy between attnpool and avgpool', 'test the PointNavResNetNet forward method with observations, RNN hidden states, and masks', 'create a RunningMeanAndVar module with n_channels to track running mean and variance for tensor normalization', 'build a forward pass through RunningMeanAndVar to normalize input tensors using running mean and variance statistics', 'test the RunningMeanAndVar module in training mode to verify it updates mean and variance incrementally', 'review the RunningMeanAndVar class to understand how it uses distributed all_reduce for multi-GPU mean and variance aggregation', "summarize the RunningMeanAndVar forward method which uses Welford's online algorithm for numerically stable running statistics"]
```

Usage

```
{'build_resnet18_model': 'build a ResNet-18 model with BasicBlock for habitat simulation visual policy networks', 'build_resnet50_model': 'build a ResNet-50 model with Bottleneck blocks for deep reinforcement learning visual features', 'build_resnext50_model': 'build a ResNeXt-50 model with grouped convolutions and cardinality for improved feature extraction', 'build_se_resnet50_model': 'build a SE-ResNet-50 model with squeeze-and-excitation attention for enhanced visual policy learning', 'build_se_resnext101_model': 'build a SE-ResNeXt-101 model with attention and grouped convolutions for complex visual tasks'}
```

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/rl/ddppo/policy/resnet_policy.py

Prompts

```
['build a ResNet-18 model with BasicBlock for habitat simulation visual policy networks', 'build a ResNet-50 model with Bottleneck blocks for deep reinforcement learning visual features', 'build a ResNeXt-50 model with grouped convolutions and cardinality for improved feature extraction', 'build a SE-ResNet-50 model with squeeze-and-excitation attention for enhanced visual policy learning', 'build a SE-ResNeXt-101 model with attention and grouped convolutions for complex visual tasks', 'build a PointNavResNetPolicy with a resnet18 backbone and GRU recurrent layers for navigation', 'create a PointNavResNetPolicy from an omegaconf DictConfig with observation and action spaces', 'review the ResNetEncoder forward pass that processes visual observations through a ResNet backbone', 'refactor the ResNetCLIPEncoder to swap the pooling strategy between attnpool and avgpool', 'test the PointNavResNetNet forward method with observations, RNN hidden states, and masks', 'create a RunningMeanAndVar module with n_channels to track running mean and variance for tensor normalization', 'build a forward pass through RunningMeanAndVar to normalize input tensors using running mean and variance statistics', 'test the RunningMeanAndVar module in training mode to verify it updates mean and variance incrementally', 'review the RunningMeanAndVar class to understand how it uses distributed all_reduce for multi-GPU mean and variance aggregation', "summarize the RunningMeanAndVar forward method which uses Welford's online algorithm for numerically stable running statistics"]
```

Usage

```
{'build_PointNavResNetPolicy': 'build a PointNavResNetPolicy with a resnet18 backbone and GRU recurrent layers for navigation', 'create_PointNavResNetPolicy_from_config': 'create a PointNavResNetPolicy from an omegaconf DictConfig with observation and action spaces', 'review_ResNetEncoder_forward': 'review the ResNetEncoder forward pass that processes visual observations through a ResNet backbone', 'refactor_ResNetCLIPEncoder': 'refactor the ResNetCLIPEncoder to swap the pooling strategy between attnpool and avgpool', 'test_PointNavResNetNet_forward': 'test the PointNavResNetNet forward method with observations, RNN hidden states, and masks'}
```

## File: facebookresearch_habitat-lab/habitat-baselines/habitat_baselines/rl/ddppo/policy/running_mean_and_var.py

Prompts

```
['build a ResNet-18 model with BasicBlock for habitat simulation visual policy networks', 'build a ResNet-50 model with Bottleneck blocks for deep reinforcement learning visual features', 'build a ResNeXt-50 model with grouped convolutions and cardinality for improved feature extraction', 'build a SE-ResNet-50 model with squeeze-and-excitation attention for enhanced visual policy learning', 'build a SE-ResNeXt-101 model with attention and grouped convolutions for complex visual tasks', 'build a PointNavResNetPolicy with a resnet18 backbone and GRU recurrent layers for navigation', 'create a PointNavResNetPolicy from an omegaconf DictConfig with observation and action spaces', 'review the ResNetEncoder forward pass that processes visual observations through a ResNet backbone', 'refactor the ResNetCLIPEncoder to swap the pooling strategy between attnpool and avgpool', 'test the PointNavResNetNet forward method with observations, RNN hidden states, and masks', 'create a RunningMeanAndVar module with n_channels to track running mean and variance for tensor normalization', 'build a forward pass through RunningMeanAndVar to normalize input tensors using running mean and variance statistics', 'test the RunningMeanAndVar module in training mode to verify it updates mean and variance incrementally', 'review the RunningMeanAndVar class to understand how it uses distributed all_reduce for multi-GPU mean and variance aggregation', "summarize the RunningMeanAndVar forward method which uses Welford's online algorithm for numerically stable running statistics"]
```

Usage

```
{'create_RunningMeanAndVar': 'create a RunningMeanAndVar module with n_channels to track running mean and variance for tensor normalization', 'build_RunningMeanAndVar_forward': 'build a forward pass through RunningMeanAndVar to normalize input tensors using running mean and variance statistics', 'test_RunningMeanAndVar_training': 'test the RunningMeanAndVar module in training mode to verify it updates mean and variance incrementally', 'review_RunningMeanAndVar_distributed': 'review the RunningMeanAndVar class to understand how it uses distributed all_reduce for multi-GPU mean and variance aggregation', 'summarize_RunningMeanAndVar_Welford': "summarize the RunningMeanAndVar forward method which uses Welford's online algorithm for numerically stable running statistics"}
```

