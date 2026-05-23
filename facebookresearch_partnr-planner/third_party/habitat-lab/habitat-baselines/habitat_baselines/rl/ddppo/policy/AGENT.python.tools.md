# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-baselines/habitat_baselines/rl/ddppo/policy/resnet.py

Prompts

```
['build a ResNet18 model with BasicBlock for image feature extraction in habitat navigation', 'build a ResNet50 model with Bottleneck blocks for deep visual feature extraction', 'build a ResNeXt50 model with grouped convolutions and cardinality for efficient feature learning', 'build an SE-ResNet50 model with squeeze-and-excitation attention for channel-wise feature recalibration', 'build an SE-ResNeXt101 model combining grouped convolutions and SE attention for deep visual tasks', 'build a point navigation policy using ResNet backbone with configurable RNN type and hidden size', 'build a neural network that fuses visual features with goal vectors and processes through RNN', 'build a ResNet-based visual encoder for RGB and depth observations with optional input normalization', 'build a CLIP-based visual encoder using pretrained RN50 model with attention or average pooling', 'build a PointNavResNetPolicy instance from an OmegaConf DictConfig with observation and action spaces', 'create a RunningMeanAndVar PyTorch module to normalize tensor inputs by running mean and variance', 'initialize a RunningMeanAndVar module with a specified number of channels for batch normalization', 'run the forward pass of RunningMeanAndVar to normalize input tensors using learned statistics', "update running mean and variance statistics during training using Welford's online algorithm", 'aggregate mean and variance statistics across distributed processes using torch distributed all_reduce']
```

Usage

```
{'build_resnet18_model': 'build a ResNet18 model with BasicBlock for image feature extraction in habitat navigation', 'build_resnet50_model': 'build a ResNet50 model with Bottleneck blocks for deep visual feature extraction', 'build_resnext50_model': 'build a ResNeXt50 model with grouped convolutions and cardinality for efficient feature learning', 'build_se_resnet50_model': 'build an SE-ResNet50 model with squeeze-and-excitation attention for channel-wise feature recalibration', 'build_se_resnext101_model': 'build an SE-ResNeXt101 model combining grouped convolutions and SE attention for deep visual tasks'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-baselines/habitat_baselines/rl/ddppo/policy/resnet_policy.py

Prompts

```
['build a ResNet18 model with BasicBlock for image feature extraction in habitat navigation', 'build a ResNet50 model with Bottleneck blocks for deep visual feature extraction', 'build a ResNeXt50 model with grouped convolutions and cardinality for efficient feature learning', 'build an SE-ResNet50 model with squeeze-and-excitation attention for channel-wise feature recalibration', 'build an SE-ResNeXt101 model combining grouped convolutions and SE attention for deep visual tasks', 'build a point navigation policy using ResNet backbone with configurable RNN type and hidden size', 'build a neural network that fuses visual features with goal vectors and processes through RNN', 'build a ResNet-based visual encoder for RGB and depth observations with optional input normalization', 'build a CLIP-based visual encoder using pretrained RN50 model with attention or average pooling', 'build a PointNavResNetPolicy instance from an OmegaConf DictConfig with observation and action spaces', 'create a RunningMeanAndVar PyTorch module to normalize tensor inputs by running mean and variance', 'initialize a RunningMeanAndVar module with a specified number of channels for batch normalization', 'run the forward pass of RunningMeanAndVar to normalize input tensors using learned statistics', "update running mean and variance statistics during training using Welford's online algorithm", 'aggregate mean and variance statistics across distributed processes using torch distributed all_reduce']
```

Usage

```
{'build_PointNavResNetPolicy': 'build a point navigation policy using ResNet backbone with configurable RNN type and hidden size', 'build_PointNavResNetNet': 'build a neural network that fuses visual features with goal vectors and processes through RNN', 'build_ResNetEncoder': 'build a ResNet-based visual encoder for RGB and depth observations with optional input normalization', 'build_ResNetCLIPEncoder': 'build a CLIP-based visual encoder using pretrained RN50 model with attention or average pooling', 'build_PointNavResNetPolicy_from_config': 'build a PointNavResNetPolicy instance from an OmegaConf DictConfig with observation and action spaces'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-baselines/habitat_baselines/rl/ddppo/policy/running_mean_and_var.py

Prompts

```
['build a ResNet18 model with BasicBlock for image feature extraction in habitat navigation', 'build a ResNet50 model with Bottleneck blocks for deep visual feature extraction', 'build a ResNeXt50 model with grouped convolutions and cardinality for efficient feature learning', 'build an SE-ResNet50 model with squeeze-and-excitation attention for channel-wise feature recalibration', 'build an SE-ResNeXt101 model combining grouped convolutions and SE attention for deep visual tasks', 'build a point navigation policy using ResNet backbone with configurable RNN type and hidden size', 'build a neural network that fuses visual features with goal vectors and processes through RNN', 'build a ResNet-based visual encoder for RGB and depth observations with optional input normalization', 'build a CLIP-based visual encoder using pretrained RN50 model with attention or average pooling', 'build a PointNavResNetPolicy instance from an OmegaConf DictConfig with observation and action spaces', 'create a RunningMeanAndVar PyTorch module to normalize tensor inputs by running mean and variance', 'initialize a RunningMeanAndVar module with a specified number of channels for batch normalization', 'run the forward pass of RunningMeanAndVar to normalize input tensors using learned statistics', "update running mean and variance statistics during training using Welford's online algorithm", 'aggregate mean and variance statistics across distributed processes using torch distributed all_reduce']
```

Usage

```
{'create_RunningMeanAndVar_module': 'create a RunningMeanAndVar PyTorch module to normalize tensor inputs by running mean and variance', 'initialize_RunningMeanAndVar': 'initialize a RunningMeanAndVar module with a specified number of channels for batch normalization', 'forward_RunningMeanAndVar': 'run the forward pass of RunningMeanAndVar to normalize input tensors using learned statistics', 'update_running_statistics': "update running mean and variance statistics during training using Welford's online algorithm", 'distrib_all_reduce_statistics': 'aggregate mean and variance statistics across distributed processes using torch distributed all_reduce'}
```

