# Agent Python Tools

- repo: facebookresearch/luckmatters
- repo_uri: https://github.com/facebookresearch/luckmatters

## File: facebookresearch_luckmatters/ssl/real-dataset/models/mlp_head.py

Prompts

```
['create an MLPHead projection head with configurable batch norm, bias, and ReLU options', 'create a CustomBN layer that normalizes features using configurable mean and std modes', 'test the MLPHead forward pass with a sample tensor through the projection layers', 'review the MLPHead _grad_hook method that registers backward hooks for gradient adjustment', 'refactor the MLPHead _create_normalization method to support additional normalization strategies', 'build a ResNet18 encoder with custom BN variants and convolution resampling for self-supervised learning', 'create a Conv2dExtSetIndependent module that resamples low-gradient filters using input activation patterns', 'create a Conv2dExtSetDiff module that replaces low-gradient filters with pairwise input patch differences', 'create a BatchNorm2dExt layer with configurable backprop_mean and backprop_var options for projection control', 'create an ExtendedBasicBlock wrapping a ResNet BasicBlock with custom BN variants and extended convolution layers']
```

Usage

```
{'create_mlp_head': 'create an MLPHead projection head with configurable batch norm, bias, and ReLU options', 'create_custom_bn': 'create a CustomBN layer that normalizes features using configurable mean and std modes', 'test_mlp_head_forward': 'test the MLPHead forward pass with a sample tensor through the projection layers', 'review_mlp_head_grad_hook': 'review the MLPHead _grad_hook method that registers backward hooks for gradient adjustment', 'refactor_mlp_head_normalization': 'refactor the MLPHead _create_normalization method to support additional normalization strategies'}
```

## File: facebookresearch_luckmatters/ssl/real-dataset/models/resnet_base_network.py

Prompts

```
['create an MLPHead projection head with configurable batch norm, bias, and ReLU options', 'create a CustomBN layer that normalizes features using configurable mean and std modes', 'test the MLPHead forward pass with a sample tensor through the projection layers', 'review the MLPHead _grad_hook method that registers backward hooks for gradient adjustment', 'refactor the MLPHead _create_normalization method to support additional normalization strategies', 'build a ResNet18 encoder with custom BN variants and convolution resampling for self-supervised learning', 'create a Conv2dExtSetIndependent module that resamples low-gradient filters using input activation patterns', 'create a Conv2dExtSetDiff module that replaces low-gradient filters with pairwise input patch differences', 'create a BatchNorm2dExt layer with configurable backprop_mean and backprop_var options for projection control', 'create an ExtendedBasicBlock wrapping a ResNet BasicBlock with custom BN variants and extended convolution layers']
```

Usage

```
{'build_resnet18_encoder': 'build a ResNet18 encoder with custom BN variants and convolution resampling for self-supervised learning', 'create_conv2dext_setindependent': 'create a Conv2dExtSetIndependent module that resamples low-gradient filters using input activation patterns', 'create_conv2dext_setdiff': 'create a Conv2dExtSetDiff module that replaces low-gradient filters with pairwise input patch differences', 'create_batchnorm2dext': 'create a BatchNorm2dExt layer with configurable backprop_mean and backprop_var options for projection control', 'create_extendedbasicblock': 'create an ExtendedBasicBlock wrapping a ResNet BasicBlock with custom BN variants and extended convolution layers'}
```

