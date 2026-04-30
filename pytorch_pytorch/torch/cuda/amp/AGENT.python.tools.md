# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/cuda/amp/autocast_mode.py

Prompts

```
['create a cuda autocast context manager for mixed-precision training with float16 dtype', 'test the autocast decorator applied to a function for automatic dtype casting on cuda tensors', 'build a custom_fwd decorator for a forward method of a torch.autograd.Function with cast_inputs set', 'create a custom_bwd decorator for a backward method that restores the forward autocast state', 'review the autocast_mode module autocast class, custom_fwd, and custom_bwd for mixed-precision cuda support', 'test the amp_definitely_not_available function to check if CUDA and torch_xla are unavailable', 'create a torch.cuda.amp.GradScaler instance with custom init_scale, growth_factor, and growth_interval settings', 'scale a PyTorch loss tensor with GradScaler.scale before calling backward to create scaled gradients', 'call GradScaler.step to unscale gradients, skip optimizer.step if NaNs detected, and return its result', 'call GradScaler.update to adjust the scale factor by backoff_factor or growth_factor based on inf/NaN history', 'call GradScaler.unscale_ to unscale optimizer gradients in-place so they can be inspected or clipped before step']
```

Usage

```
{'create_autocast_context': 'create a cuda autocast context manager for mixed-precision training with float16 dtype', 'test_autocast_decorator': 'test the autocast decorator applied to a function for automatic dtype casting on cuda tensors', 'build_custom_fwd_autograd': 'build a custom_fwd decorator for a forward method of a torch.autograd.Function with cast_inputs set', 'create_custom_bwd_autograd': 'create a custom_bwd decorator for a backward method that restores the forward autocast state', 'review_autocast_mode': 'review the autocast_mode module autocast class, custom_fwd, and custom_bwd for mixed-precision cuda support'}
```

## File: pytorch_pytorch/torch/cuda/amp/common.py

Prompts

```
['create a cuda autocast context manager for mixed-precision training with float16 dtype', 'test the autocast decorator applied to a function for automatic dtype casting on cuda tensors', 'build a custom_fwd decorator for a forward method of a torch.autograd.Function with cast_inputs set', 'create a custom_bwd decorator for a backward method that restores the forward autocast state', 'review the autocast_mode module autocast class, custom_fwd, and custom_bwd for mixed-precision cuda support', 'test the amp_definitely_not_available function to check if CUDA and torch_xla are unavailable', 'create a torch.cuda.amp.GradScaler instance with custom init_scale, growth_factor, and growth_interval settings', 'scale a PyTorch loss tensor with GradScaler.scale before calling backward to create scaled gradients', 'call GradScaler.step to unscale gradients, skip optimizer.step if NaNs detected, and return its result', 'call GradScaler.update to adjust the scale factor by backoff_factor or growth_factor based on inf/NaN history', 'call GradScaler.unscale_ to unscale optimizer gradients in-place so they can be inspected or clipped before step']
```

Usage

```
{'test_amp_definitely_not_available': 'test the amp_definitely_not_available function to check if CUDA and torch_xla are unavailable'}
```

## File: pytorch_pytorch/torch/cuda/amp/grad_scaler.py

Prompts

```
['create a cuda autocast context manager for mixed-precision training with float16 dtype', 'test the autocast decorator applied to a function for automatic dtype casting on cuda tensors', 'build a custom_fwd decorator for a forward method of a torch.autograd.Function with cast_inputs set', 'create a custom_bwd decorator for a backward method that restores the forward autocast state', 'review the autocast_mode module autocast class, custom_fwd, and custom_bwd for mixed-precision cuda support', 'test the amp_definitely_not_available function to check if CUDA and torch_xla are unavailable', 'create a torch.cuda.amp.GradScaler instance with custom init_scale, growth_factor, and growth_interval settings', 'scale a PyTorch loss tensor with GradScaler.scale before calling backward to create scaled gradients', 'call GradScaler.step to unscale gradients, skip optimizer.step if NaNs detected, and return its result', 'call GradScaler.update to adjust the scale factor by backoff_factor or growth_factor based on inf/NaN history', 'call GradScaler.unscale_ to unscale optimizer gradients in-place so they can be inspected or clipped before step']
```

Usage

```
{'create_GradScaler': 'create a torch.cuda.amp.GradScaler instance with custom init_scale, growth_factor, and growth_interval settings', 'scale_loss_backward': 'scale a PyTorch loss tensor with GradScaler.scale before calling backward to create scaled gradients', 'step_optimizer_skip_nan': 'call GradScaler.step to unscale gradients, skip optimizer.step if NaNs detected, and return its result', 'update_scale_factor': 'call GradScaler.update to adjust the scale factor by backoff_factor or growth_factor based on inf/NaN history', 'unscale_gradients_clip': 'call GradScaler.unscale_ to unscale optimizer gradients in-place so they can be inspected or clipped before step'}
```

