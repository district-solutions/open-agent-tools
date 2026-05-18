# Agent Python Tools

- repo: facebookresearch/odin
- repo_uri: https://github.com/facebookresearch/odin

## File: facebookresearch_odin/code/calData.py

Prompts

```
['run testData to compute confidence scores for in-distribution and out-of-distribution images using gradient-based perturbations', 'run testGaussian to compute confidence scores using Gaussian random noise as out-of-distribution data', 'run testUni to compute confidence scores using uniform random noise as out-of-distribution data', 'refactor testData to use modern PyTorch tensors instead of deprecated Variable and manual softmax', 'review testGaussian and testUni for duplicated confidence calculation and gradient perturbation logic', 'build a DenseNet3 model with specified depth, growth rate, and number of classes for image classification', 'create a BasicBlock with batch norm, relu, and 3x3 convolution that concatenates input with output', 'create a BottleneckBlock with 1x1 and 3x3 convolutions using 4x intermediate planes and dropout', 'create a TransitionBlock with 1x1 convolution and average pooling to reduce feature map dimensions', 'create a DenseBlock with N layers where each layer concatenates outputs using growth rate', 'build a WideResNet model with specified depth, num_classes, widen_factor, and dropout rate for image classification', 'create a BasicBlock with configurable input/output planes, stride, and dropout rate for residual connections', 'create a NetworkBlock that stacks multiple BasicBlock layers with specified stride and dropout rate', 'run a WideResNet forward pass on input tensor to get classification logits', 'review the WideResNet weight initialization using He normal init for conv layers and zero bias']
```

Usage

```
{'run_testData': 'run testData to compute confidence scores for in-distribution and out-of-distribution images using gradient-based perturbations', 'run_testGaussian': 'run testGaussian to compute confidence scores using Gaussian random noise as out-of-distribution data', 'run_testUni': 'run testUni to compute confidence scores using uniform random noise as out-of-distribution data', 'refactor_testData': 'refactor testData to use modern PyTorch tensors instead of deprecated Variable and manual softmax', 'review_testGaussian': 'review testGaussian and testUni for duplicated confidence calculation and gradient perturbation logic'}
```

## File: facebookresearch_odin/code/densenet.py

Prompts

```
['run testData to compute confidence scores for in-distribution and out-of-distribution images using gradient-based perturbations', 'run testGaussian to compute confidence scores using Gaussian random noise as out-of-distribution data', 'run testUni to compute confidence scores using uniform random noise as out-of-distribution data', 'refactor testData to use modern PyTorch tensors instead of deprecated Variable and manual softmax', 'review testGaussian and testUni for duplicated confidence calculation and gradient perturbation logic', 'build a DenseNet3 model with specified depth, growth rate, and number of classes for image classification', 'create a BasicBlock with batch norm, relu, and 3x3 convolution that concatenates input with output', 'create a BottleneckBlock with 1x1 and 3x3 convolutions using 4x intermediate planes and dropout', 'create a TransitionBlock with 1x1 convolution and average pooling to reduce feature map dimensions', 'create a DenseBlock with N layers where each layer concatenates outputs using growth rate', 'build a WideResNet model with specified depth, num_classes, widen_factor, and dropout rate for image classification', 'create a BasicBlock with configurable input/output planes, stride, and dropout rate for residual connections', 'create a NetworkBlock that stacks multiple BasicBlock layers with specified stride and dropout rate', 'run a WideResNet forward pass on input tensor to get classification logits', 'review the WideResNet weight initialization using He normal init for conv layers and zero bias']
```

Usage

```
{'build_densenet_model': 'build a DenseNet3 model with specified depth, growth rate, and number of classes for image classification', 'create_basicblock': 'create a BasicBlock with batch norm, relu, and 3x3 convolution that concatenates input with output', 'create_bottleneckblock': 'create a BottleneckBlock with 1x1 and 3x3 convolutions using 4x intermediate planes and dropout', 'create_transitionblock': 'create a TransitionBlock with 1x1 convolution and average pooling to reduce feature map dimensions', 'create_denseblock': 'create a DenseBlock with N layers where each layer concatenates outputs using growth rate'}
```

## File: facebookresearch_odin/code/wideresnet.py

Prompts

```
['run testData to compute confidence scores for in-distribution and out-of-distribution images using gradient-based perturbations', 'run testGaussian to compute confidence scores using Gaussian random noise as out-of-distribution data', 'run testUni to compute confidence scores using uniform random noise as out-of-distribution data', 'refactor testData to use modern PyTorch tensors instead of deprecated Variable and manual softmax', 'review testGaussian and testUni for duplicated confidence calculation and gradient perturbation logic', 'build a DenseNet3 model with specified depth, growth rate, and number of classes for image classification', 'create a BasicBlock with batch norm, relu, and 3x3 convolution that concatenates input with output', 'create a BottleneckBlock with 1x1 and 3x3 convolutions using 4x intermediate planes and dropout', 'create a TransitionBlock with 1x1 convolution and average pooling to reduce feature map dimensions', 'create a DenseBlock with N layers where each layer concatenates outputs using growth rate', 'build a WideResNet model with specified depth, num_classes, widen_factor, and dropout rate for image classification', 'create a BasicBlock with configurable input/output planes, stride, and dropout rate for residual connections', 'create a NetworkBlock that stacks multiple BasicBlock layers with specified stride and dropout rate', 'run a WideResNet forward pass on input tensor to get classification logits', 'review the WideResNet weight initialization using He normal init for conv layers and zero bias']
```

Usage

```
{'build_WideResNet_model': 'build a WideResNet model with specified depth, num_classes, widen_factor, and dropout rate for image classification', 'create_BasicBlock': 'create a BasicBlock with configurable input/output planes, stride, and dropout rate for residual connections', 'create_NetworkBlock': 'create a NetworkBlock that stacks multiple BasicBlock layers with specified stride and dropout rate', 'run_WideResNet_forward': 'run a WideResNet forward pass on input tensor to get classification logits', 'review_WideResNet_initialization': 'review the WideResNet weight initialization using He normal init for conv layers and zero bias'}
```

