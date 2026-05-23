# Agent Python Tools

- repo: facebookresearch/torchdim
- repo_uri: https://github.com/facebookresearch/torchdim

## File: facebookresearch_torchdim/third_party/functorch/examples/dp_cifar10/cifar10_opacus.py

Prompts

```
['run CIFAR10 training with differential privacy using Opacus and a ResNet18 model on GPU', 'run CIFAR10 training with vanilla SGD by passing the --disable-dp flag to skip privacy', 'run CIFAR10 DP training with secure RNG enabled via the --secure-rng flag for trustworthy privacy', 'run CIFAR10 DP training using per-layer gradient clipping by passing the --clip_per_layer flag', 'run CIFAR10 DP training with Adam or RMSprop optimizer by setting --optim to the desired optimizer', 'train a ResNet18 model on CIFAR10 with per-sample gradient clipping and Gaussian noise injection', 'clip per-sample gradients to a max norm, accumulate them, and add Gaussian noise for differential privacy', 'compute the L2 norms of per-sample gradients across all model parameters for gradient clipping', 'save a model checkpoint with state dict, optimizer state, and best accuracy to disk']
```

Usage

```
{'run_dp_cifar10_training': 'run CIFAR10 training with differential privacy using Opacus and a ResNet18 model on GPU', 'run_cifar10_without_dp': 'run CIFAR10 training with vanilla SGD by passing the --disable-dp flag to skip privacy', 'run_cifar10_with_secure_rng': 'run CIFAR10 DP training with secure RNG enabled via the --secure-rng flag for trustworthy privacy', 'run_cifar10_with_per_layer_clipping': 'run CIFAR10 DP training using per-layer gradient clipping by passing the --clip_per_layer flag', 'run_cifar10_with_different_optimizer': 'run CIFAR10 DP training with Adam or RMSprop optimizer by setting --optim to the desired optimizer'}
```

## File: facebookresearch_torchdim/third_party/functorch/examples/dp_cifar10/cifar10_transforms.py

Prompts

```
['run CIFAR10 training with differential privacy using Opacus and a ResNet18 model on GPU', 'run CIFAR10 training with vanilla SGD by passing the --disable-dp flag to skip privacy', 'run CIFAR10 DP training with secure RNG enabled via the --secure-rng flag for trustworthy privacy', 'run CIFAR10 DP training using per-layer gradient clipping by passing the --clip_per_layer flag', 'run CIFAR10 DP training with Adam or RMSprop optimizer by setting --optim to the desired optimizer', 'train a ResNet18 model on CIFAR10 with per-sample gradient clipping and Gaussian noise injection', 'clip per-sample gradients to a max norm, accumulate them, and add Gaussian noise for differential privacy', 'compute the L2 norms of per-sample gradients across all model parameters for gradient clipping', 'save a model checkpoint with state dict, optimizer state, and best accuracy to disk']
```

Usage

```
{'run_dp_cifar10_training': 'run CIFAR10 training with differential privacy using functorch vmap and grad_and_value', 'train_dp_model': 'train a ResNet18 model on CIFAR10 with per-sample gradient clipping and Gaussian noise injection', 'clip_and_accumulate_and_add_noise': 'clip per-sample gradients to a max norm, accumulate them, and add Gaussian noise for differential privacy', 'compute_norms': 'compute the L2 norms of per-sample gradients across all model parameters for gradient clipping', 'save_checkpoint': 'save a model checkpoint with state dict, optimizer state, and best accuracy to disk'}
```

