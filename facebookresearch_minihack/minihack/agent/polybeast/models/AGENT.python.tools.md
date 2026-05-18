# Agent Python Tools

- repo: facebookresearch/minihack
- repo_uri: https://github.com/facebookresearch/minihack

## File: facebookresearch_minihack/minihack/agent/polybeast/models/base.py

Prompts

```
['build a BaseNet neural network for NetHack agent with configurable CNN, transformer, and message models', 'create a RandomNet agent that samples random actions with uniform policy logits', 'review the Crop module that calculates centered crops around given x,y coordinates using grid sampling', 'test the NetHackNet update_running_moments method to maintain a running mean and variance of rewards', 'refactor the BaseNet forward pass to support custom message models like GRU, LSTM, or CNN', 'build a Random Network Distillation network for intrinsic reward in MiniHack reinforcement learning agents', 'build a RIDE network with forward and inverse dynamics models for intrinsic reward learning', 'create an intrinsic reward network base class with running mean and standard deviation tracking', 'test the RNDNet forward pass to compute target and predicted state representations for novelty', 'review the RIDENet forward and inverse dynamics models for state embedding and action prediction', 'build a python module to compute the policy gradient loss using logits, actions, and advantages tensors', 'create a function that computes the entropy loss from softmax logits for policy regularization', 'build a python module to compute the baseline loss as half the sum of squared advantages', 'create a function that computes the forward dynamics loss between predicted and actual next embeddings', 'build a python module to compute the inverse dynamics loss between predicted and true actions']
```

Usage

```
{'build_BaseNet_model': 'build a BaseNet neural network for NetHack agent with configurable CNN, transformer, and message models', 'create_RandomNet_agent': 'create a RandomNet agent that samples random actions with uniform policy logits', 'review_Crop_module': 'review the Crop module that calculates centered crops around given x,y coordinates using grid sampling', 'test_NetHackNet_running_moments': 'test the NetHackNet update_running_moments method to maintain a running mean and variance of rewards', 'refactor_BaseNet_forward': 'refactor the BaseNet forward pass to support custom message models like GRU, LSTM, or CNN'}
```

## File: facebookresearch_minihack/minihack/agent/polybeast/models/intrinsic.py

Prompts

```
['build a BaseNet neural network for NetHack agent with configurable CNN, transformer, and message models', 'create a RandomNet agent that samples random actions with uniform policy logits', 'review the Crop module that calculates centered crops around given x,y coordinates using grid sampling', 'test the NetHackNet update_running_moments method to maintain a running mean and variance of rewards', 'refactor the BaseNet forward pass to support custom message models like GRU, LSTM, or CNN', 'build a Random Network Distillation network for intrinsic reward in MiniHack reinforcement learning agents', 'build a RIDE network with forward and inverse dynamics models for intrinsic reward learning', 'create an intrinsic reward network base class with running mean and standard deviation tracking', 'test the RNDNet forward pass to compute target and predicted state representations for novelty', 'review the RIDENet forward and inverse dynamics models for state embedding and action prediction', 'build a python module to compute the policy gradient loss using logits, actions, and advantages tensors', 'create a function that computes the entropy loss from softmax logits for policy regularization', 'build a python module to compute the baseline loss as half the sum of squared advantages', 'create a function that computes the forward dynamics loss between predicted and actual next embeddings', 'build a python module to compute the inverse dynamics loss between predicted and true actions']
```

Usage

```
{'build_RNDNet': 'build a Random Network Distillation network for intrinsic reward in MiniHack reinforcement learning agents', 'build_RIDENet': 'build a RIDE network with forward and inverse dynamics models for intrinsic reward learning', 'create_IntrinsicRewardNet': 'create an intrinsic reward network base class with running mean and standard deviation tracking', 'test_RNDNet_forward': 'test the RNDNet forward pass to compute target and predicted state representations for novelty', 'review_RIDENet_dynamics': 'review the RIDENet forward and inverse dynamics models for state embedding and action prediction'}
```

## File: facebookresearch_minihack/minihack/agent/polybeast/models/losses.py

Prompts

```
['build a BaseNet neural network for NetHack agent with configurable CNN, transformer, and message models', 'create a RandomNet agent that samples random actions with uniform policy logits', 'review the Crop module that calculates centered crops around given x,y coordinates using grid sampling', 'test the NetHackNet update_running_moments method to maintain a running mean and variance of rewards', 'refactor the BaseNet forward pass to support custom message models like GRU, LSTM, or CNN', 'build a Random Network Distillation network for intrinsic reward in MiniHack reinforcement learning agents', 'build a RIDE network with forward and inverse dynamics models for intrinsic reward learning', 'create an intrinsic reward network base class with running mean and standard deviation tracking', 'test the RNDNet forward pass to compute target and predicted state representations for novelty', 'review the RIDENet forward and inverse dynamics models for state embedding and action prediction', 'build a python module to compute the policy gradient loss using logits, actions, and advantages tensors', 'create a function that computes the entropy loss from softmax logits for policy regularization', 'build a python module to compute the baseline loss as half the sum of squared advantages', 'create a function that computes the forward dynamics loss between predicted and actual next embeddings', 'build a python module to compute the inverse dynamics loss between predicted and true actions']
```

Usage

```
{'compute_policy_gradient_loss': 'build a python module to compute the policy gradient loss using logits, actions, and advantages tensors', 'compute_entropy_loss': 'create a function that computes the entropy loss from softmax logits for policy regularization', 'compute_baseline_loss': 'build a python module to compute the baseline loss as half the sum of squared advantages', 'compute_forward_dynamics_loss': 'create a function that computes the forward dynamics loss between predicted and actual next embeddings', 'compute_inverse_dynamics_loss': 'build a python module to compute the inverse dynamics loss between predicted and true actions'}
```

