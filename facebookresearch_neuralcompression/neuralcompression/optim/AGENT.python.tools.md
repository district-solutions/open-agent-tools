# Agent Python Tools

- repo: facebookresearch/neuralcompression
- repo_uri: https://github.com/facebookresearch/neuralcompression

## File: facebookresearch_neuralcompression/neuralcompression/optim/_identity.py

Prompts

```
['create an IdentitySchedule that keeps the learning rate constant for a PyTorch optimizer', 'build a PyTorch optimizer paired with an IdentitySchedule LambdaLR that never changes the learning rate', 'test the IdentitySchedule class by calling step and verifying the learning rate remains unchanged', 'review the IdentitySchedule constructor to understand how it wraps LambdaLR with a constant step function', 'summarize the IdentitySchedule class as a no-op learning rate scheduler extending PyTorch LambdaLR', 'create a RampConstCosineLRSchedule that ramps LR up, holds constant, then decays with cosine', 'build an optimizer wrapped with a ramp-constant-cosine learning rate schedule for training', 'test the RampConstCosineLRSchedule step function returns correct LR values across ramp, constant, and cosine phases', 'review the RampConstCosineLRSchedule constructor to verify num_ramp_steps, num_cosine_steps, and min_val parameters', 'summarize the RampConstCosineLRSchedule class that extends LambdaLR for three-phase learning rate scheduling', 'create a RampCosineLRSchedule that ramps learning rate then applies cosine decay for training', 'build an optimizer with RampCosineLRSchedule to warm up learning rate before cosine annealing', 'test the RampCosineLRSchedule step function returns correct LR during ramp and cosine phases', 'review the RampCosineLRSchedule class to understand how min_val prevents learning rate from dropping too low', 'summarize the RampCosineLRSchedule learning rate schedule that combines linear warmup with cosine decay']
```

Usage

```
{'create_identity_schedule': 'create an IdentitySchedule that keeps the learning rate constant for a PyTorch optimizer', 'build_optimizer_with_identity_lr': 'build a PyTorch optimizer paired with an IdentitySchedule LambdaLR that never changes the learning rate', 'test_IdentitySchedule_step': 'test the IdentitySchedule class by calling step and verifying the learning rate remains unchanged', 'review_IdentitySchedule_init': 'review the IdentitySchedule constructor to understand how it wraps LambdaLR with a constant step function', 'summarize_IdentitySchedule': 'summarize the IdentitySchedule class as a no-op learning rate scheduler extending PyTorch LambdaLR'}
```

## File: facebookresearch_neuralcompression/neuralcompression/optim/_ramp_const_cosine.py

Prompts

```
['create an IdentitySchedule that keeps the learning rate constant for a PyTorch optimizer', 'build a PyTorch optimizer paired with an IdentitySchedule LambdaLR that never changes the learning rate', 'test the IdentitySchedule class by calling step and verifying the learning rate remains unchanged', 'review the IdentitySchedule constructor to understand how it wraps LambdaLR with a constant step function', 'summarize the IdentitySchedule class as a no-op learning rate scheduler extending PyTorch LambdaLR', 'create a RampConstCosineLRSchedule that ramps LR up, holds constant, then decays with cosine', 'build an optimizer wrapped with a ramp-constant-cosine learning rate schedule for training', 'test the RampConstCosineLRSchedule step function returns correct LR values across ramp, constant, and cosine phases', 'review the RampConstCosineLRSchedule constructor to verify num_ramp_steps, num_cosine_steps, and min_val parameters', 'summarize the RampConstCosineLRSchedule class that extends LambdaLR for three-phase learning rate scheduling', 'create a RampCosineLRSchedule that ramps learning rate then applies cosine decay for training', 'build an optimizer with RampCosineLRSchedule to warm up learning rate before cosine annealing', 'test the RampCosineLRSchedule step function returns correct LR during ramp and cosine phases', 'review the RampCosineLRSchedule class to understand how min_val prevents learning rate from dropping too low', 'summarize the RampCosineLRSchedule learning rate schedule that combines linear warmup with cosine decay']
```

Usage

```
{'create_ramp_const_cosine_lr_schedule': 'create a RampConstCosineLRSchedule that ramps LR up, holds constant, then decays with cosine', 'build_optimizer_with_ramp_const_cosine': 'build an optimizer wrapped with a ramp-constant-cosine learning rate schedule for training', 'test_RampConstCosineLRSchedule_step_fn': 'test the RampConstCosineLRSchedule step function returns correct LR values across ramp, constant, and cosine phases', 'review_RampConstCosineLRSchedule_init': 'review the RampConstCosineLRSchedule constructor to verify num_ramp_steps, num_cosine_steps, and min_val parameters', 'summarize_RampConstCosineLRSchedule': 'summarize the RampConstCosineLRSchedule class that extends LambdaLR for three-phase learning rate scheduling'}
```

## File: facebookresearch_neuralcompression/neuralcompression/optim/_ramp_cosine.py

Prompts

```
['create an IdentitySchedule that keeps the learning rate constant for a PyTorch optimizer', 'build a PyTorch optimizer paired with an IdentitySchedule LambdaLR that never changes the learning rate', 'test the IdentitySchedule class by calling step and verifying the learning rate remains unchanged', 'review the IdentitySchedule constructor to understand how it wraps LambdaLR with a constant step function', 'summarize the IdentitySchedule class as a no-op learning rate scheduler extending PyTorch LambdaLR', 'create a RampConstCosineLRSchedule that ramps LR up, holds constant, then decays with cosine', 'build an optimizer wrapped with a ramp-constant-cosine learning rate schedule for training', 'test the RampConstCosineLRSchedule step function returns correct LR values across ramp, constant, and cosine phases', 'review the RampConstCosineLRSchedule constructor to verify num_ramp_steps, num_cosine_steps, and min_val parameters', 'summarize the RampConstCosineLRSchedule class that extends LambdaLR for three-phase learning rate scheduling', 'create a RampCosineLRSchedule that ramps learning rate then applies cosine decay for training', 'build an optimizer with RampCosineLRSchedule to warm up learning rate before cosine annealing', 'test the RampCosineLRSchedule step function returns correct LR during ramp and cosine phases', 'review the RampCosineLRSchedule class to understand how min_val prevents learning rate from dropping too low', 'summarize the RampCosineLRSchedule learning rate schedule that combines linear warmup with cosine decay']
```

Usage

```
{'create_ramp_cosine_lr_schedule': 'create a RampCosineLRSchedule that ramps learning rate then applies cosine decay for training', 'build_optimizer_with_ramp_cosine': 'build an optimizer with RampCosineLRSchedule to warm up learning rate before cosine annealing', 'test_ramp_cosine_step_fn': 'test the RampCosineLRSchedule step function returns correct LR during ramp and cosine phases', 'review_ramp_cosine_min_val': 'review the RampCosineLRSchedule class to understand how min_val prevents learning rate from dropping too low', 'summarize_ramp_cosine_schedule': 'summarize the RampCosineLRSchedule learning rate schedule that combines linear warmup with cosine decay'}
```

