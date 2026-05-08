# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/fairscale/experimental/nn/ampnet_pipe/ampnet.py

Prompts

```
['create a Task for a partition and batch with optional activation checkpointing based on checkpoint_stop index', 'review the AsyncAMPnetEventLoop class and its pipeline parallel event loop methods for AMPnet weight prediction', 'run a forward pass on the first partition and return the result batch and activations PipeMessage', 'run the backward pass by receiving gradient tensors and calling torch.autograd.backward on the stored activations', 'run the trunk event loop across minibatches with warmup forward passes and steady state forward-backward scheduling', 'create an AMPnetPipe instance for asynchronous pipeline parallel training with stale weights', 'interleave training across minibatches using AMPnetPipe with a dataloader, criterion, and optimizer', 'run the AMPnetPipe event loop for head, tail, or intermediate pipeline stages', 'review the AMPnetPipe interleave method for pipeline parallel training configuration', 'summarize the AMPnetPipe class which avoids the bubble issue using stale weights and gradients']
```

Usage

```
{'create_task_without_skip_trackers': 'create a Task for a partition and batch with optional activation checkpointing based on checkpoint_stop index', 'review_AsyncAMPnetEventLoop': 'review the AsyncAMPnetEventLoop class and its pipeline parallel event loop methods for AMPnet weight prediction', 'run_async_send_inner': 'run a forward pass on the first partition and return the result batch and activations PipeMessage', 'run_async_grad_inner': 'run the backward pass by receiving gradient tensors and calling torch.autograd.backward on the stored activations', 'run_event_loop_across_minibatches': 'run the trunk event loop across minibatches with warmup forward passes and steady state forward-backward scheduling'}
```

## File: facebookresearch_fairscale/fairscale/experimental/nn/ampnet_pipe/pipe.py

Prompts

```
['create a Task for a partition and batch with optional activation checkpointing based on checkpoint_stop index', 'review the AsyncAMPnetEventLoop class and its pipeline parallel event loop methods for AMPnet weight prediction', 'run a forward pass on the first partition and return the result batch and activations PipeMessage', 'run the backward pass by receiving gradient tensors and calling torch.autograd.backward on the stored activations', 'run the trunk event loop across minibatches with warmup forward passes and steady state forward-backward scheduling', 'create an AMPnetPipe instance for asynchronous pipeline parallel training with stale weights', 'interleave training across minibatches using AMPnetPipe with a dataloader, criterion, and optimizer', 'run the AMPnetPipe event loop for head, tail, or intermediate pipeline stages', 'review the AMPnetPipe interleave method for pipeline parallel training configuration', 'summarize the AMPnetPipe class which avoids the bubble issue using stale weights and gradients']
```

Usage

```
{'create_AMPnetPipe': 'create an AMPnetPipe instance for asynchronous pipeline parallel training with stale weights', 'interleave_AMPnetPipe': 'interleave training across minibatches using AMPnetPipe with a dataloader, criterion, and optimizer', 'run_AMPnetPipe_event_loop': 'run the AMPnetPipe event loop for head, tail, or intermediate pipeline stages', 'review_AMPnetPipe_interleave': 'review the AMPnetPipe interleave method for pipeline parallel training configuration', 'summarize_AMPnetPipe': 'summarize the AMPnetPipe class which avoids the bubble issue using stale weights and gradients'}
```

