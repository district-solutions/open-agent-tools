# Agent Python Tools

- repo: facebookresearch/alphanet
- repo_uri: https://github.com/facebookresearch/alphanet

## File: facebookresearch_alphanet/loss_ops.py

Prompts

```
['build a PyTorch module using CrossEntropyLossSoft for inplace distillation in image classification', 'build a knowledge distillation loss with KLLossSoft combining KL divergence and cross entropy', 'build a label-smoothed cross entropy loss using CrossEntropyLossSmooth for image classification training', 'build an adaptive knowledge distillation loss using AdaptiveLossSoft with configurable alpha bounds', 'test the f_divergence function to compute f-divergence loss and gradient for two logit distributions', 'run distributed evolutionary search for neural architecture search across multiple GPUs and nodes', 'run the eval_worker function to evaluate sub-networks on a specific GPU in a distributed setting', 'review the eval_worker function that handles distributed sub-network evaluation and evolutionary search logic', 'build a CLI module to run parallel supernet evolutionary search with configurable machine rank and seed', 'summarize how the Pareto frontier tracks the best FLOPs versus accuracy trade-offs during evolution', 'run the AlphaNet training script with a config file and distributed GPU settings', 'build training arguments and environment from a config file for DDP setup', 'train one epoch using the sandwich rule to sample max, min, and random subnets', 'validate the attentive NAS min and max subnets on the validation dataset', 'initialize a per-GPU worker that creates the model, optimizer, and runs the training loop']
```

Usage

```
{'build_CrossEntropyLossSoft': 'build a PyTorch module using CrossEntropyLossSoft for inplace distillation in image classification', 'build_KLLossSoft': 'build a knowledge distillation loss with KLLossSoft combining KL divergence and cross entropy', 'build_CrossEntropyLossSmooth': 'build a label-smoothed cross entropy loss using CrossEntropyLossSmooth for image classification training', 'build_AdaptiveLossSoft': 'build an adaptive knowledge distillation loss using AdaptiveLossSoft with configurable alpha bounds', 'test_f_divergence': 'test the f_divergence function to compute f-divergence loss and gradient for two logit distributions'}
```

## File: facebookresearch_alphanet/parallel_supernet_evo_search.py

Prompts

```
['build a PyTorch module using CrossEntropyLossSoft for inplace distillation in image classification', 'build a knowledge distillation loss with KLLossSoft combining KL divergence and cross entropy', 'build a label-smoothed cross entropy loss using CrossEntropyLossSmooth for image classification training', 'build an adaptive knowledge distillation loss using AdaptiveLossSoft with configurable alpha bounds', 'test the f_divergence function to compute f-divergence loss and gradient for two logit distributions', 'run distributed evolutionary search for neural architecture search across multiple GPUs and nodes', 'run the eval_worker function to evaluate sub-networks on a specific GPU in a distributed setting', 'review the eval_worker function that handles distributed sub-network evaluation and evolutionary search logic', 'build a CLI module to run parallel supernet evolutionary search with configurable machine rank and seed', 'summarize how the Pareto frontier tracks the best FLOPs versus accuracy trade-offs during evolution', 'run the AlphaNet training script with a config file and distributed GPU settings', 'build training arguments and environment from a config file for DDP setup', 'train one epoch using the sandwich rule to sample max, min, and random subnets', 'validate the attentive NAS min and max subnets on the validation dataset', 'initialize a per-GPU worker that creates the model, optimizer, and runs the training loop']
```

Usage

```
{'run_parallel_evo_search': 'run distributed evolutionary search for neural architecture search across multiple GPUs and nodes', 'run_eval_worker': 'run the eval_worker function to evaluate sub-networks on a specific GPU in a distributed setting', 'review_eval_worker': 'review the eval_worker function that handles distributed sub-network evaluation and evolutionary search logic', 'build_evo_search_cli': 'build a CLI module to run parallel supernet evolutionary search with configurable machine rank and seed', 'summarize_pareto_frontier': 'summarize how the Pareto frontier tracks the best FLOPs versus accuracy trade-offs during evolution'}
```

## File: facebookresearch_alphanet/train_alphanet.py

Prompts

```
['build a PyTorch module using CrossEntropyLossSoft for inplace distillation in image classification', 'build a knowledge distillation loss with KLLossSoft combining KL divergence and cross entropy', 'build a label-smoothed cross entropy loss using CrossEntropyLossSmooth for image classification training', 'build an adaptive knowledge distillation loss using AdaptiveLossSoft with configurable alpha bounds', 'test the f_divergence function to compute f-divergence loss and gradient for two logit distributions', 'run distributed evolutionary search for neural architecture search across multiple GPUs and nodes', 'run the eval_worker function to evaluate sub-networks on a specific GPU in a distributed setting', 'review the eval_worker function that handles distributed sub-network evaluation and evolutionary search logic', 'build a CLI module to run parallel supernet evolutionary search with configurable machine rank and seed', 'summarize how the Pareto frontier tracks the best FLOPs versus accuracy trade-offs during evolution', 'run the AlphaNet training script with a config file and distributed GPU settings', 'build training arguments and environment from a config file for DDP setup', 'train one epoch using the sandwich rule to sample max, min, and random subnets', 'validate the attentive NAS min and max subnets on the validation dataset', 'initialize a per-GPU worker that creates the model, optimizer, and runs the training loop']
```

Usage

```
{'run_alphanet_training': 'run the AlphaNet training script with a config file and distributed GPU settings', 'build_args_and_env': 'build training arguments and environment from a config file for DDP setup', 'train_epoch': 'train one epoch using the sandwich rule to sample max, min, and random subnets', 'validate_subnets': 'validate the attentive NAS min and max subnets on the validation dataset', 'main_worker': 'initialize a per-GPU worker that creates the model, optimizer, and runs the training loop'}
```

