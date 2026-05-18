# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/examples/omnivore/train.py

Prompts

```
['run the omnivore multimodal model training loop with image, video, and rgbd modalities', 'evaluate a trained omnivore model on validation data with clip and video-level accuracy', 'train one epoch of the omnivore model with gradient accumulation for video inputs', 'configure training arguments including optimizer, lr scheduler, and modality options for omnivore', 'resume omnivore training from a saved checkpoint with model, optimizer, and EMA state', 'create a MetricLogger to track and log training metrics with smoothed values over an iterable', 'use SmoothedValue to track a rolling window of values with median and global average', 'compute top-k classification accuracy from model output and target tensors', 'initialize distributed training mode from environment variables and configure process group', 'setup an ExponentialMovingAverage wrapper for a PyTorch model with a specified decay rate']
```

Usage

```
{'run_omnivore_training': 'run the omnivore multimodal model training loop with image, video, and rgbd modalities', 'evaluate_omnivore_model': 'evaluate a trained omnivore model on validation data with clip and video-level accuracy', 'train_one_epoch_omnivore': 'train one epoch of the omnivore model with gradient accumulation for video inputs', 'configure_omnivore_args': 'configure training arguments including optimizer, lr scheduler, and modality options for omnivore', 'resume_omnivore_checkpoint': 'resume omnivore training from a saved checkpoint with model, optimizer, and EMA state'}
```

## File: facebookresearch_multimodal/examples/omnivore/utils.py

Prompts

```
['run the omnivore multimodal model training loop with image, video, and rgbd modalities', 'evaluate a trained omnivore model on validation data with clip and video-level accuracy', 'train one epoch of the omnivore model with gradient accumulation for video inputs', 'configure training arguments including optimizer, lr scheduler, and modality options for omnivore', 'resume omnivore training from a saved checkpoint with model, optimizer, and EMA state', 'create a MetricLogger to track and log training metrics with smoothed values over an iterable', 'use SmoothedValue to track a rolling window of values with median and global average', 'compute top-k classification accuracy from model output and target tensors', 'initialize distributed training mode from environment variables and configure process group', 'setup an ExponentialMovingAverage wrapper for a PyTorch model with a specified decay rate']
```

Usage

```
{'create_metric_logger': 'create a MetricLogger to track and log training metrics with smoothed values over an iterable', 'use_smoothed_value': 'use SmoothedValue to track a rolling window of values with median and global average', 'compute_accuracy': 'compute top-k classification accuracy from model output and target tensors', 'init_distributed_mode': 'initialize distributed training mode from environment variables and configure process group', 'setup_exponential_moving_average': 'setup an ExponentialMovingAverage wrapper for a PyTorch model with a specified decay rate'}
```

