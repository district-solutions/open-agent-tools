# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/examples/mdetr/utils/args_parse.py

Prompts

```
['build an argparse parser for MDETR with transformer, matcher, and loss configuration arguments', 'create a command-line argument parser to configure MDETR training with dataset and backbone options', 'run the MDETR argument parser to set transformer layers, hidden dimensions, and learning rate', 'review the get_args_parser function that defines MDETR training hyperparameters and model architecture arguments', 'summarize the MDETR argument parser covering transformer config, loss coefficients, and distributed training options', 'initialize distributed training mode by reading RANK and WORLD_SIZE env vars and setting up NCCL backend', 'gather arbitrary picklable data from all GPU ranks into a single list across processes', 'reduce a dictionary of tensor values across all processes with optional averaging', 'disable print output on non-master processes so only rank 0 prints to stdout', 'get a cached Gloo backend process group containing all ranks for CPU-based reduction', 'create a SmoothedValue instance to track smoothed metrics over a sliding window with median and global average', 'use MetricLogger update method to log keyworded metric values including torch tensors as scalars', 'use MetricLogger log_every to iterate over a dataloader and print periodic training progress logs', 'create a RecallTracker to track recall at k for multiple categories with positive and negative hits', 'use RecallTracker report method to get a condensed dict of recall at k per category', 'interpolate a PyTorch tensor with empty channel dimensions using nearest mode', 'interpolate a PyTorch tensor by a given scale factor using bilinear mode', 'interpolate a PyTorch tensor to a specific output size using nearest mode', 'move a list of target dictionaries to a specified PyTorch device excluding metadata keys', 'review the interpolate function to understand how it handles empty batch and channel dimensions']
```

Usage

```
{'build_mdetr_args_parser': 'build an argparse parser for MDETR with transformer, matcher, and loss configuration arguments', 'create_mdetr_config': 'create a command-line argument parser to configure MDETR training with dataset and backbone options', 'run_mdetr_training_config': 'run the MDETR argument parser to set transformer layers, hidden dimensions, and learning rate', 'review_get_args_parser': 'review the get_args_parser function that defines MDETR training hyperparameters and model architecture arguments', 'summarize_mdetr_arguments': 'summarize the MDETR argument parser covering transformer config, loss coefficients, and distributed training options'}
```

## File: facebookresearch_multimodal/examples/mdetr/utils/dist.py

Prompts

```
['build an argparse parser for MDETR with transformer, matcher, and loss configuration arguments', 'create a command-line argument parser to configure MDETR training with dataset and backbone options', 'run the MDETR argument parser to set transformer layers, hidden dimensions, and learning rate', 'review the get_args_parser function that defines MDETR training hyperparameters and model architecture arguments', 'summarize the MDETR argument parser covering transformer config, loss coefficients, and distributed training options', 'initialize distributed training mode by reading RANK and WORLD_SIZE env vars and setting up NCCL backend', 'gather arbitrary picklable data from all GPU ranks into a single list across processes', 'reduce a dictionary of tensor values across all processes with optional averaging', 'disable print output on non-master processes so only rank 0 prints to stdout', 'get a cached Gloo backend process group containing all ranks for CPU-based reduction', 'create a SmoothedValue instance to track smoothed metrics over a sliding window with median and global average', 'use MetricLogger update method to log keyworded metric values including torch tensors as scalars', 'use MetricLogger log_every to iterate over a dataloader and print periodic training progress logs', 'create a RecallTracker to track recall at k for multiple categories with positive and negative hits', 'use RecallTracker report method to get a condensed dict of recall at k per category', 'interpolate a PyTorch tensor with empty channel dimensions using nearest mode', 'interpolate a PyTorch tensor by a given scale factor using bilinear mode', 'interpolate a PyTorch tensor to a specific output size using nearest mode', 'move a list of target dictionaries to a specified PyTorch device excluding metadata keys', 'review the interpolate function to understand how it handles empty batch and channel dimensions']
```

Usage

```
{'init_distributed_mode': 'initialize distributed training mode by reading RANK and WORLD_SIZE env vars and setting up NCCL backend', 'all_gather': 'gather arbitrary picklable data from all GPU ranks into a single list across processes', 'reduce_dict': 'reduce a dictionary of tensor values across all processes with optional averaging', 'setup_for_distributed': 'disable print output on non-master processes so only rank 0 prints to stdout', 'get_global_gloo_group': 'get a cached Gloo backend process group containing all ranks for CPU-based reduction'}
```

## File: facebookresearch_multimodal/examples/mdetr/utils/metrics.py

Prompts

```
['build an argparse parser for MDETR with transformer, matcher, and loss configuration arguments', 'create a command-line argument parser to configure MDETR training with dataset and backbone options', 'run the MDETR argument parser to set transformer layers, hidden dimensions, and learning rate', 'review the get_args_parser function that defines MDETR training hyperparameters and model architecture arguments', 'summarize the MDETR argument parser covering transformer config, loss coefficients, and distributed training options', 'initialize distributed training mode by reading RANK and WORLD_SIZE env vars and setting up NCCL backend', 'gather arbitrary picklable data from all GPU ranks into a single list across processes', 'reduce a dictionary of tensor values across all processes with optional averaging', 'disable print output on non-master processes so only rank 0 prints to stdout', 'get a cached Gloo backend process group containing all ranks for CPU-based reduction', 'create a SmoothedValue instance to track smoothed metrics over a sliding window with median and global average', 'use MetricLogger update method to log keyworded metric values including torch tensors as scalars', 'use MetricLogger log_every to iterate over a dataloader and print periodic training progress logs', 'create a RecallTracker to track recall at k for multiple categories with positive and negative hits', 'use RecallTracker report method to get a condensed dict of recall at k per category', 'interpolate a PyTorch tensor with empty channel dimensions using nearest mode', 'interpolate a PyTorch tensor by a given scale factor using bilinear mode', 'interpolate a PyTorch tensor to a specific output size using nearest mode', 'move a list of target dictionaries to a specified PyTorch device excluding metadata keys', 'review the interpolate function to understand how it handles empty batch and channel dimensions']
```

Usage

```
{'create_SmoothedValue': 'create a SmoothedValue instance to track smoothed metrics over a sliding window with median and global average', 'use_MetricLogger_update': 'use MetricLogger update method to log keyworded metric values including torch tensors as scalars', 'use_MetricLogger_log_every': 'use MetricLogger log_every to iterate over a dataloader and print periodic training progress logs', 'create_RecallTracker': 'create a RecallTracker to track recall at k for multiple categories with positive and negative hits', 'use_RecallTracker_report': 'use RecallTracker report method to get a condensed dict of recall at k per category'}
```

## File: facebookresearch_multimodal/examples/mdetr/utils/misc.py

Prompts

```
['build an argparse parser for MDETR with transformer, matcher, and loss configuration arguments', 'create a command-line argument parser to configure MDETR training with dataset and backbone options', 'run the MDETR argument parser to set transformer layers, hidden dimensions, and learning rate', 'review the get_args_parser function that defines MDETR training hyperparameters and model architecture arguments', 'summarize the MDETR argument parser covering transformer config, loss coefficients, and distributed training options', 'initialize distributed training mode by reading RANK and WORLD_SIZE env vars and setting up NCCL backend', 'gather arbitrary picklable data from all GPU ranks into a single list across processes', 'reduce a dictionary of tensor values across all processes with optional averaging', 'disable print output on non-master processes so only rank 0 prints to stdout', 'get a cached Gloo backend process group containing all ranks for CPU-based reduction', 'create a SmoothedValue instance to track smoothed metrics over a sliding window with median and global average', 'use MetricLogger update method to log keyworded metric values including torch tensors as scalars', 'use MetricLogger log_every to iterate over a dataloader and print periodic training progress logs', 'create a RecallTracker to track recall at k for multiple categories with positive and negative hits', 'use RecallTracker report method to get a condensed dict of recall at k per category', 'interpolate a PyTorch tensor with empty channel dimensions using nearest mode', 'interpolate a PyTorch tensor by a given scale factor using bilinear mode', 'interpolate a PyTorch tensor to a specific output size using nearest mode', 'move a list of target dictionaries to a specified PyTorch device excluding metadata keys', 'review the interpolate function to understand how it handles empty batch and channel dimensions']
```

Usage

```
{'interpolate_empty_tensor': 'interpolate a PyTorch tensor with empty channel dimensions using nearest mode', 'interpolate_with_scale': 'interpolate a PyTorch tensor by a given scale factor using bilinear mode', 'interpolate_with_size': 'interpolate a PyTorch tensor to a specific output size using nearest mode', 'targets_to_device': 'move a list of target dictionaries to a specified PyTorch device excluding metadata keys', 'review_interpolate': 'review the interpolate function to understand how it handles empty batch and channel dimensions'}
```

