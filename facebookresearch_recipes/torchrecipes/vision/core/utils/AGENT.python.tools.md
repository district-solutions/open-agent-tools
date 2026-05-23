# Agent Python Tools

- repo: facebookresearch/recipes
- repo_uri: https://github.com/facebookresearch/recipes

## File: facebookresearch_recipes/torchrecipes/vision/core/utils/lr_scheduler.py

Prompts

```
['build a SequentialLR scheduler by chaining multiple learning rate scheduler callables with milestone steps', 'create a sequence of chained LR schedulers using callables and milestone points for an optimizer', 'test the sequential_lr helper function with sample scheduler callables and milestone values', 'refactor the sequential_lr function to support additional scheduler configuration options', 'review the sequential_lr helper that constructs a SequentialLR from scheduler callables and milestones', 'load model weights from a state dict file into a PyTorch nn.Module in-place', 'extract model weights from a Lightning checkpoint file by filtering on a model name prefix', 'load model weights from a path into a module with strict mode disabled to allow partial matches', 'extract all model weights from a Lightning checkpoint when the model is the Lightning module itself', 'review the load_model_weights function to understand how it loads state dicts from file paths', 'create a RandomDataset with random tensors of a given size and length for testing', 'build a PyTorch Lightning TestModule with two linear layers and MSE loss for training', 'test the TestModule training_step method to compute forward pass and loss on a batch', 'review the TestModule validation_epoch_end method that logs val_loss with optional epoch override', 'create a TrackedTestModule subclass that tracks epochs seen, batches seen, and checkpoint loads']
```

Usage

```
{'build_sequential_lr': 'build a SequentialLR scheduler by chaining multiple learning rate scheduler callables with milestone steps', 'create_sequential_lr_schedulers': 'create a sequence of chained LR schedulers using callables and milestone points for an optimizer', 'test_sequential_lr': 'test the sequential_lr helper function with sample scheduler callables and milestone values', 'refactor_sequential_lr': 'refactor the sequential_lr function to support additional scheduler configuration options', 'review_sequential_lr': 'review the sequential_lr helper that constructs a SequentialLR from scheduler callables and milestones'}
```

## File: facebookresearch_recipes/torchrecipes/vision/core/utils/model_weights.py

Prompts

```
['build a SequentialLR scheduler by chaining multiple learning rate scheduler callables with milestone steps', 'create a sequence of chained LR schedulers using callables and milestone points for an optimizer', 'test the sequential_lr helper function with sample scheduler callables and milestone values', 'refactor the sequential_lr function to support additional scheduler configuration options', 'review the sequential_lr helper that constructs a SequentialLR from scheduler callables and milestones', 'load model weights from a state dict file into a PyTorch nn.Module in-place', 'extract model weights from a Lightning checkpoint file by filtering on a model name prefix', 'load model weights from a path into a module with strict mode disabled to allow partial matches', 'extract all model weights from a Lightning checkpoint when the model is the Lightning module itself', 'review the load_model_weights function to understand how it loads state dicts from file paths', 'create a RandomDataset with random tensors of a given size and length for testing', 'build a PyTorch Lightning TestModule with two linear layers and MSE loss for training', 'test the TestModule training_step method to compute forward pass and loss on a batch', 'review the TestModule validation_epoch_end method that logs val_loss with optional epoch override', 'create a TrackedTestModule subclass that tracks epochs seen, batches seen, and checkpoint loads']
```

Usage

```
{'load_model_weights': 'load model weights from a state dict file into a PyTorch nn.Module in-place', 'extract_model_weights_from_checkpoint': 'extract model weights from a Lightning checkpoint file by filtering on a model name prefix', 'load_model_weights_non_strict': 'load model weights from a path into a module with strict mode disabled to allow partial matches', 'extract_model_weights_no_prefix': 'extract all model weights from a Lightning checkpoint when the model is the Lightning module itself', 'review_load_model_weights': 'review the load_model_weights function to understand how it loads state dicts from file paths'}
```

## File: facebookresearch_recipes/torchrecipes/vision/core/utils/test_module.py

Prompts

```
['build a SequentialLR scheduler by chaining multiple learning rate scheduler callables with milestone steps', 'create a sequence of chained LR schedulers using callables and milestone points for an optimizer', 'test the sequential_lr helper function with sample scheduler callables and milestone values', 'refactor the sequential_lr function to support additional scheduler configuration options', 'review the sequential_lr helper that constructs a SequentialLR from scheduler callables and milestones', 'load model weights from a state dict file into a PyTorch nn.Module in-place', 'extract model weights from a Lightning checkpoint file by filtering on a model name prefix', 'load model weights from a path into a module with strict mode disabled to allow partial matches', 'extract all model weights from a Lightning checkpoint when the model is the Lightning module itself', 'review the load_model_weights function to understand how it loads state dicts from file paths', 'create a RandomDataset with random tensors of a given size and length for testing', 'build a PyTorch Lightning TestModule with two linear layers and MSE loss for training', 'test the TestModule training_step method to compute forward pass and loss on a batch', 'review the TestModule validation_epoch_end method that logs val_loss with optional epoch override', 'create a TrackedTestModule subclass that tracks epochs seen, batches seen, and checkpoint loads']
```

Usage

```
{'create_random_dataset': 'create a RandomDataset with random tensors of a given size and length for testing', 'build_test_module': 'build a PyTorch Lightning TestModule with two linear layers and MSE loss for training', 'test_training_step': 'test the TestModule training_step method to compute forward pass and loss on a batch', 'review_validation_epoch_end': 'review the TestModule validation_epoch_end method that logs val_loss with optional epoch override', 'create_tracked_test_module': 'create a TrackedTestModule subclass that tracks epochs seen, batches seen, and checkpoint loads'}
```

