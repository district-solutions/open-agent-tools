# Agent Python Tools

- repo: facebookresearch/neuralcompression
- repo_uri: https://github.com/facebookresearch/neuralcompression

## File: facebookresearch_neuralcompression/projects/torch_vct/utils/checkpoint_loaders.py

Prompts

```
['load a VCTPipeline model checkpoint from a config file and checkpoint path onto a specified device', 'load a PyTorch model state dict from a checkpoint file and apply it to an instantiated model', 'instantiate a model using hydra.utils from a YAML config file containing model architecture settings', 'save a timestamped copy of the loaded model checkpoint state dict to the checkpoint directory', 'strip the model. prefix from state dict keys when loading checkpoints saved with a model wrapper', 'display a PyTorch tensor image with custom mean and std normalization using matplotlib', 'display a video clip tensor as a grid of frames using matplotlib subplots', 'show an image tensor with custom mean and std values for denormalization before display', 'display a video clip tensor across multiple rows using the nrow parameter', 'review the show_image function that clips and normalizes a tensor for matplotlib display', 'create a memoize cache using create_cache for storing PyTorch computation results', 'apply the memoize decorator to a function to enable result caching on repeated calls', 'bind a memoized function to a cache instance using bind to enable caching', 'inspect cache hit counts for a memoized function using get_total_cache_hits', 'convert lists dicts and tensors into hashable tuples for use as cache keys', 'create a LinearRampCosineLR scheduler with linear warmup followed by cosine annealing for a PyTorch optimizer', 'create a LinearRampLinearLR scheduler with linear warmup followed by constant learning rate for a PyTorch optimizer', 'create a LinearWarmUpCosineLR scheduler with constant warmup followed by cosine annealing for a PyTorch optimizer', 'review the get_lr method of LinearRampCosineLR to understand how it computes closed-form learning rates', 'refactor the ramp_len parameter in LinearRampLinearLR to support dynamic warmup length during training']
```

Usage

```
{'load_model_checkpoint_from_config': 'load a VCTPipeline model checkpoint from a config file and checkpoint path onto a specified device', 'load_model_with_state_dict': 'load a PyTorch model state dict from a checkpoint file and apply it to an instantiated model', 'instantiate_model_from_yaml_config': 'instantiate a model using hydra.utils from a YAML config file containing model architecture settings', 'save_checkpoint_copy': 'save a timestamped copy of the loaded model checkpoint state dict to the checkpoint directory', 'strip_model_prefix_from_state_dict': 'strip the model. prefix from state dict keys when loading checkpoints saved with a model wrapper'}
```

## File: facebookresearch_neuralcompression/projects/torch_vct/utils/datavis.py

Prompts

```
['load a VCTPipeline model checkpoint from a config file and checkpoint path onto a specified device', 'load a PyTorch model state dict from a checkpoint file and apply it to an instantiated model', 'instantiate a model using hydra.utils from a YAML config file containing model architecture settings', 'save a timestamped copy of the loaded model checkpoint state dict to the checkpoint directory', 'strip the model. prefix from state dict keys when loading checkpoints saved with a model wrapper', 'display a PyTorch tensor image with custom mean and std normalization using matplotlib', 'display a video clip tensor as a grid of frames using matplotlib subplots', 'show an image tensor with custom mean and std values for denormalization before display', 'display a video clip tensor across multiple rows using the nrow parameter', 'review the show_image function that clips and normalizes a tensor for matplotlib display', 'create a memoize cache using create_cache for storing PyTorch computation results', 'apply the memoize decorator to a function to enable result caching on repeated calls', 'bind a memoized function to a cache instance using bind to enable caching', 'inspect cache hit counts for a memoized function using get_total_cache_hits', 'convert lists dicts and tensors into hashable tuples for use as cache keys', 'create a LinearRampCosineLR scheduler with linear warmup followed by cosine annealing for a PyTorch optimizer', 'create a LinearRampLinearLR scheduler with linear warmup followed by constant learning rate for a PyTorch optimizer', 'create a LinearWarmUpCosineLR scheduler with constant warmup followed by cosine annealing for a PyTorch optimizer', 'review the get_lr method of LinearRampCosineLR to understand how it computes closed-form learning rates', 'refactor the ramp_len parameter in LinearRampLinearLR to support dynamic warmup length during training']
```

Usage

```
{'show_image_tensor': 'display a PyTorch tensor image with custom mean and std normalization using matplotlib', 'show_video_clip': 'display a video clip tensor as a grid of frames using matplotlib subplots', 'show_image_custom_normalization': 'show an image tensor with custom mean and std values for denormalization before display', 'show_video_multirow': 'display a video clip tensor across multiple rows using the nrow parameter', 'review_show_image': 'review the show_image function that clips and normalizes a tensor for matplotlib display'}
```

## File: facebookresearch_neuralcompression/projects/torch_vct/utils/memoize.py

Prompts

```
['load a VCTPipeline model checkpoint from a config file and checkpoint path onto a specified device', 'load a PyTorch model state dict from a checkpoint file and apply it to an instantiated model', 'instantiate a model using hydra.utils from a YAML config file containing model architecture settings', 'save a timestamped copy of the loaded model checkpoint state dict to the checkpoint directory', 'strip the model. prefix from state dict keys when loading checkpoints saved with a model wrapper', 'display a PyTorch tensor image with custom mean and std normalization using matplotlib', 'display a video clip tensor as a grid of frames using matplotlib subplots', 'show an image tensor with custom mean and std values for denormalization before display', 'display a video clip tensor across multiple rows using the nrow parameter', 'review the show_image function that clips and normalizes a tensor for matplotlib display', 'create a memoize cache using create_cache for storing PyTorch computation results', 'apply the memoize decorator to a function to enable result caching on repeated calls', 'bind a memoized function to a cache instance using bind to enable caching', 'inspect cache hit counts for a memoized function using get_total_cache_hits', 'convert lists dicts and tensors into hashable tuples for use as cache keys', 'create a LinearRampCosineLR scheduler with linear warmup followed by cosine annealing for a PyTorch optimizer', 'create a LinearRampLinearLR scheduler with linear warmup followed by constant learning rate for a PyTorch optimizer', 'create a LinearWarmUpCosineLR scheduler with constant warmup followed by cosine annealing for a PyTorch optimizer', 'review the get_lr method of LinearRampCosineLR to understand how it computes closed-form learning rates', 'refactor the ramp_len parameter in LinearRampLinearLR to support dynamic warmup length during training']
```

Usage

```
{'create_cache': 'create a memoize cache using create_cache for storing PyTorch computation results', 'memoize_decorator': 'apply the memoize decorator to a function to enable result caching on repeated calls', 'bind_function_to_cache': 'bind a memoized function to a cache instance using bind to enable caching', 'inspect_cache_hits': 'inspect cache hit counts for a memoized function using get_total_cache_hits', 'ensure_hashable': 'convert lists dicts and tensors into hashable tuples for use as cache keys'}
```

## File: facebookresearch_neuralcompression/projects/torch_vct/utils/schedulers.py

Prompts

```
['load a VCTPipeline model checkpoint from a config file and checkpoint path onto a specified device', 'load a PyTorch model state dict from a checkpoint file and apply it to an instantiated model', 'instantiate a model using hydra.utils from a YAML config file containing model architecture settings', 'save a timestamped copy of the loaded model checkpoint state dict to the checkpoint directory', 'strip the model. prefix from state dict keys when loading checkpoints saved with a model wrapper', 'display a PyTorch tensor image with custom mean and std normalization using matplotlib', 'display a video clip tensor as a grid of frames using matplotlib subplots', 'show an image tensor with custom mean and std values for denormalization before display', 'display a video clip tensor across multiple rows using the nrow parameter', 'review the show_image function that clips and normalizes a tensor for matplotlib display', 'create a memoize cache using create_cache for storing PyTorch computation results', 'apply the memoize decorator to a function to enable result caching on repeated calls', 'bind a memoized function to a cache instance using bind to enable caching', 'inspect cache hit counts for a memoized function using get_total_cache_hits', 'convert lists dicts and tensors into hashable tuples for use as cache keys', 'create a LinearRampCosineLR scheduler with linear warmup followed by cosine annealing for a PyTorch optimizer', 'create a LinearRampLinearLR scheduler with linear warmup followed by constant learning rate for a PyTorch optimizer', 'create a LinearWarmUpCosineLR scheduler with constant warmup followed by cosine annealing for a PyTorch optimizer', 'review the get_lr method of LinearRampCosineLR to understand how it computes closed-form learning rates', 'refactor the ramp_len parameter in LinearRampLinearLR to support dynamic warmup length during training']
```

Usage

```
{'create_linear_ramp_cosine_scheduler': 'create a LinearRampCosineLR scheduler with linear warmup followed by cosine annealing for a PyTorch optimizer', 'create_linear_ramp_linear_scheduler': 'create a LinearRampLinearLR scheduler with linear warmup followed by constant learning rate for a PyTorch optimizer', 'create_linear_warmup_cosine_scheduler': 'create a LinearWarmUpCosineLR scheduler with constant warmup followed by cosine annealing for a PyTorch optimizer', 'review_lr_scheduler_get_lr': 'review the get_lr method of LinearRampCosineLR to understand how it computes closed-form learning rates', 'refactor_lr_scheduler_ramp_len': 'refactor the ramp_len parameter in LinearRampLinearLR to support dynamic warmup length during training'}
```

