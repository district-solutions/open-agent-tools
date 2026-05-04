# Agent Python Tools

- repo: google-deepmind/enn
- repo_uri: https://github.com/google-deepmind/enn

## File: google-deepmind_enn/enn/networks/resnet/base.py

Prompts

```
['build a ResNet forward function with a specified number of output classes and config', 'create an EnsembleResNetENN with a configurable number of ensemble members and output classes', 'test the resnet_model forward function to verify NHWC to HWCN transpose on TPU devices', 'review the EnsembleResNetENN class init to understand how Haiku transforms and ensembles are wired together', 'summarize the resnet_model function and its forward_fn closure that handles image transpose and model inference', 'build a ResNet-18 V1 model using CanonicalResNets.RESNET_18 config for CIFAR10 classification with Haiku and JAX', 'build a ResNet-50 V2 model using CanonicalResNets.RESNET_50 config for ImageNet classification with Haiku and JAX', 'create a ResNetConfig dataclass with custom channels_per_group, blocks_per_group, strides_per_group, and resnet_block_version settings', 'create a ResBlockV2 preactivation bottleneck block with 1x1, 3x3, 1x1 conv layers and optional projection shortcut', 'review the _make_resnet_blocks function that constructs a sequence of ResBlockV1 or ResBlockV2 instances from a ResNetConfig', 'build a ResnetMlpPrior network with configurable hidden sizes and prior scale for ImageNet classification', 'build a ResnetCnnPrior network with configurable conv layers and prior scale for ImageNet classification', 'review the ResnetMlpPrior class init to understand how the MLP prior is wired into the ResNet model', 'review the ResnetCnnPrior class init to understand how the CNN prior conv layers are configured', 'refactor the ResnetMlpPrior class to support dynamic prior scaling based on training epoch', 'test the EnsembleResNetENN forward pass and verify output shape matches expected batch and class dimensions', 'run parameterized tests for ResNet 18 and ResNet 50 across multiple batch sizes and image sizes', 'initialize and apply an EnsembleResNetENN model to random input images using JAX and Haiku', 'parse the network output from an ENN model to extract logits with the expected shape']
```

Usage

```
{'build_resnet_forward_fn': 'build a ResNet forward function with a specified number of output classes and config', 'create_ensemble_resnet_enn': 'create an EnsembleResNetENN with a configurable number of ensemble members and output classes', 'test_resnet_model_transpose': 'test the resnet_model forward function to verify NHWC to HWCN transpose on TPU devices', 'review_ensemble_resnet_init': 'review the EnsembleResNetENN class init to understand how Haiku transforms and ensembles are wired together', 'summarize_resnet_forward_fn': 'summarize the resnet_model function and its forward_fn closure that handles image transpose and model inference'}
```

## File: google-deepmind_enn/enn/networks/resnet/lib.py

Prompts

```
['build a ResNet forward function with a specified number of output classes and config', 'create an EnsembleResNetENN with a configurable number of ensemble members and output classes', 'test the resnet_model forward function to verify NHWC to HWCN transpose on TPU devices', 'review the EnsembleResNetENN class init to understand how Haiku transforms and ensembles are wired together', 'summarize the resnet_model function and its forward_fn closure that handles image transpose and model inference', 'build a ResNet-18 V1 model using CanonicalResNets.RESNET_18 config for CIFAR10 classification with Haiku and JAX', 'build a ResNet-50 V2 model using CanonicalResNets.RESNET_50 config for ImageNet classification with Haiku and JAX', 'create a ResNetConfig dataclass with custom channels_per_group, blocks_per_group, strides_per_group, and resnet_block_version settings', 'create a ResBlockV2 preactivation bottleneck block with 1x1, 3x3, 1x1 conv layers and optional projection shortcut', 'review the _make_resnet_blocks function that constructs a sequence of ResBlockV1 or ResBlockV2 instances from a ResNetConfig', 'build a ResnetMlpPrior network with configurable hidden sizes and prior scale for ImageNet classification', 'build a ResnetCnnPrior network with configurable conv layers and prior scale for ImageNet classification', 'review the ResnetMlpPrior class init to understand how the MLP prior is wired into the ResNet model', 'review the ResnetCnnPrior class init to understand how the CNN prior conv layers are configured', 'refactor the ResnetMlpPrior class to support dynamic prior scaling based on training epoch', 'test the EnsembleResNetENN forward pass and verify output shape matches expected batch and class dimensions', 'run parameterized tests for ResNet 18 and ResNet 50 across multiple batch sizes and image sizes', 'initialize and apply an EnsembleResNetENN model to random input images using JAX and Haiku', 'parse the network output from an ENN model to extract logits with the expected shape']
```

Usage

```
{'build_resnet_v1_cifar': 'build a ResNet-18 V1 model using CanonicalResNets.RESNET_18 config for CIFAR10 classification with Haiku and JAX', 'build_resnet_v2_imagenet': 'build a ResNet-50 V2 model using CanonicalResNets.RESNET_50 config for ImageNet classification with Haiku and JAX', 'create_resnet_config': 'create a ResNetConfig dataclass with custom channels_per_group, blocks_per_group, strides_per_group, and resnet_block_version settings', 'create_resblock_v2_bottleneck': 'create a ResBlockV2 preactivation bottleneck block with 1x1, 3x3, 1x1 conv layers and optional projection shortcut', 'review_make_resnet_blocks': 'review the _make_resnet_blocks function that constructs a sequence of ResBlockV1 or ResBlockV2 instances from a ResNetConfig'}
```

## File: google-deepmind_enn/enn/networks/resnet/priors.py

Prompts

```
['build a ResNet forward function with a specified number of output classes and config', 'create an EnsembleResNetENN with a configurable number of ensemble members and output classes', 'test the resnet_model forward function to verify NHWC to HWCN transpose on TPU devices', 'review the EnsembleResNetENN class init to understand how Haiku transforms and ensembles are wired together', 'summarize the resnet_model function and its forward_fn closure that handles image transpose and model inference', 'build a ResNet-18 V1 model using CanonicalResNets.RESNET_18 config for CIFAR10 classification with Haiku and JAX', 'build a ResNet-50 V2 model using CanonicalResNets.RESNET_50 config for ImageNet classification with Haiku and JAX', 'create a ResNetConfig dataclass with custom channels_per_group, blocks_per_group, strides_per_group, and resnet_block_version settings', 'create a ResBlockV2 preactivation bottleneck block with 1x1, 3x3, 1x1 conv layers and optional projection shortcut', 'review the _make_resnet_blocks function that constructs a sequence of ResBlockV1 or ResBlockV2 instances from a ResNetConfig', 'build a ResnetMlpPrior network with configurable hidden sizes and prior scale for ImageNet classification', 'build a ResnetCnnPrior network with configurable conv layers and prior scale for ImageNet classification', 'review the ResnetMlpPrior class init to understand how the MLP prior is wired into the ResNet model', 'review the ResnetCnnPrior class init to understand how the CNN prior conv layers are configured', 'refactor the ResnetMlpPrior class to support dynamic prior scaling based on training epoch', 'test the EnsembleResNetENN forward pass and verify output shape matches expected batch and class dimensions', 'run parameterized tests for ResNet 18 and ResNet 50 across multiple batch sizes and image sizes', 'initialize and apply an EnsembleResNetENN model to random input images using JAX and Haiku', 'parse the network output from an ENN model to extract logits with the expected shape']
```

Usage

```
{'build_resnet_mlp_prior': 'build a ResnetMlpPrior network with configurable hidden sizes and prior scale for ImageNet classification', 'build_resnet_cnn_prior': 'build a ResnetCnnPrior network with configurable conv layers and prior scale for ImageNet classification', 'review_ResnetMlpPrior_init': 'review the ResnetMlpPrior class init to understand how the MLP prior is wired into the ResNet model', 'review_ResnetCnnPrior_init': 'review the ResnetCnnPrior class init to understand how the CNN prior conv layers are configured', 'refactor_ResnetMlpPrior_prior_scale': 'refactor the ResnetMlpPrior class to support dynamic prior scaling based on training epoch'}
```

## File: google-deepmind_enn/enn/networks/resnet/test.py

Prompts

```
['build a ResNet forward function with a specified number of output classes and config', 'create an EnsembleResNetENN with a configurable number of ensemble members and output classes', 'test the resnet_model forward function to verify NHWC to HWCN transpose on TPU devices', 'review the EnsembleResNetENN class init to understand how Haiku transforms and ensembles are wired together', 'summarize the resnet_model function and its forward_fn closure that handles image transpose and model inference', 'build a ResNet-18 V1 model using CanonicalResNets.RESNET_18 config for CIFAR10 classification with Haiku and JAX', 'build a ResNet-50 V2 model using CanonicalResNets.RESNET_50 config for ImageNet classification with Haiku and JAX', 'create a ResNetConfig dataclass with custom channels_per_group, blocks_per_group, strides_per_group, and resnet_block_version settings', 'create a ResBlockV2 preactivation bottleneck block with 1x1, 3x3, 1x1 conv layers and optional projection shortcut', 'review the _make_resnet_blocks function that constructs a sequence of ResBlockV1 or ResBlockV2 instances from a ResNetConfig', 'build a ResnetMlpPrior network with configurable hidden sizes and prior scale for ImageNet classification', 'build a ResnetCnnPrior network with configurable conv layers and prior scale for ImageNet classification', 'review the ResnetMlpPrior class init to understand how the MLP prior is wired into the ResNet model', 'review the ResnetCnnPrior class init to understand how the CNN prior conv layers are configured', 'refactor the ResnetMlpPrior class to support dynamic prior scaling based on training epoch', 'test the EnsembleResNetENN forward pass and verify output shape matches expected batch and class dimensions', 'run parameterized tests for ResNet 18 and ResNet 50 across multiple batch sizes and image sizes', 'initialize and apply an EnsembleResNetENN model to random input images using JAX and Haiku', 'parse the network output from an ENN model to extract logits with the expected shape']
```

Usage

```
{'test_forward_pass': 'test the EnsembleResNetENN forward pass and verify output shape matches expected batch and class dimensions', 'run_parameterized_resnet_tests': 'run parameterized tests for ResNet 18 and ResNet 50 across multiple batch sizes and image sizes', 'create_ensemble_resnet_enn': 'create an EnsembleResNetENN model with a specified number of output classes and ResNet configuration', 'init_and_apply_enn': 'initialize and apply an EnsembleResNetENN model to random input images using JAX and Haiku', 'parse_net_output_logits': 'parse the network output from an ENN model to extract logits with the expected shape'}
```

