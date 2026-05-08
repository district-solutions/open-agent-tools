# Agent Python Tools

- repo: facebookresearch/r-mae
- repo_uri: https://github.com/facebookresearch/r-mae

## File: facebookresearch_r-mae/pretrain/optim/lars.py

Prompts

```
['create a LARS optimizer instance with custom learning rate, weight decay, momentum, and trust coefficient', 'run a training step with the LARS optimizer to update model parameters using adaptive local learning rates', 'review the LARS optimizer step method to understand how weight decay is applied only to parameters with more than 1 dimension', 'refactor the LARS optimizer to adjust the trust coefficient for scaling update norms relative to parameter norms', 'summarize the LARS optimizer momentum update logic that maintains a moving average of gradients per parameter', 'create an OSS optimizer wrapping Adam to shard optimizer state across distributed ranks', 'run a single optimization step on the sharded OSS optimizer and broadcast updated parameters', 'clip the gradient norm across all OSS optimizer shards using all-reduce synchronization', 'consolidate the sharded optimizer state dict from all ranks into a single global state', 'refresh the OSS optimizer partitioning when parameter trainability changes during training']
```

Usage

```
{'create_LARS_optimizer': 'create a LARS optimizer instance with custom learning rate, weight decay, momentum, and trust coefficient', 'run_LARS_step': 'run a training step with the LARS optimizer to update model parameters using adaptive local learning rates', 'review_LARS_weight_decay': 'review the LARS optimizer step method to understand how weight decay is applied only to parameters with more than 1 dimension', 'refactor_LARS_trust_coefficient': 'refactor the LARS optimizer to adjust the trust coefficient for scaling update norms relative to parameter norms', 'summarize_LARS_momentum': 'summarize the LARS optimizer momentum update logic that maintains a moving average of gradients per parameter'}
```

## File: facebookresearch_r-mae/pretrain/optim/oss.py

Prompts

```
['create a LARS optimizer instance with custom learning rate, weight decay, momentum, and trust coefficient', 'run a training step with the LARS optimizer to update model parameters using adaptive local learning rates', 'review the LARS optimizer step method to understand how weight decay is applied only to parameters with more than 1 dimension', 'refactor the LARS optimizer to adjust the trust coefficient for scaling update norms relative to parameter norms', 'summarize the LARS optimizer momentum update logic that maintains a moving average of gradients per parameter', 'create an OSS optimizer wrapping Adam to shard optimizer state across distributed ranks', 'run a single optimization step on the sharded OSS optimizer and broadcast updated parameters', 'clip the gradient norm across all OSS optimizer shards using all-reduce synchronization', 'consolidate the sharded optimizer state dict from all ranks into a single global state', 'refresh the OSS optimizer partitioning when parameter trainability changes during training']
```

Usage

```
{'create_OSS_optimizer': 'create an OSS optimizer wrapping Adam to shard optimizer state across distributed ranks', 'run_OSS_step': 'run a single optimization step on the sharded OSS optimizer and broadcast updated parameters', 'clip_OSS_grad_norm': 'clip the gradient norm across all OSS optimizer shards using all-reduce synchronization', 'consolidate_OSS_state_dict': 'consolidate the sharded optimizer state dict from all ranks into a single global state', 'refresh_OSS_trainable': 'refresh the OSS optimizer partitioning when parameter trainability changes during training'}
```

