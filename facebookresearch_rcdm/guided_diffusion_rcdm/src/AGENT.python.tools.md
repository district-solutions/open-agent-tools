# Agent Python Tools

- repo: facebookresearch/rcdm
- repo_uri: https://github.com/facebookresearch/rcdm

## File: facebookresearch_rcdm/guided_diffusion_rcdm/src/logger.py

Prompts

```
['create a logger with file and console handlers using create_logger with a filepath and process rank', 'create a LogFormatter instance that formats log records with level name, timestamp, and elapsed time', 'create a PD_Stats object to track and persist statistics as a pickled pandas DataFrame', 'update a PD_Stats tracker with a new row of data and optionally save to pickle file', 'reset the logger elapsed time by calling the reset_time method attached to the logger', 'create a MultiCropDataset instance from an ImageFolder path with configurable crop sizes and scales', 'use MultiCropDataset getitem to return multiple augmented crops of a single image', 'create a PILRandomGaussianBlur transform that applies random Gaussian blur to PIL images with configurable probability', 'use get_color_distortion to build a Compose transform with random color jitter and grayscale augmentation', 'review the MultiCropDataset class and its augmentation pipeline for self-supervised learning data loading', 'build a ResNet-50 model using Bottleneck blocks with configurable projection head and prototype layers', 'build a ResNet-101 model using Bottleneck blocks with 23 blocks in the third stage', 'build a ResNeXt-50 32x4d model with grouped convolutions and 4 width per group', 'build a widened ResNet-50 model with 2x, 4x, or 5x channel width multiplier', 'run forward pass through ResNet backbone and projection head on image tensor inputs', 'initialize distributed training mode by setting world size, rank, and NCCL backend from environment variables', 'initialize an experiment by dumping parameters, creating a checkpoint directory, logger, and training stats object', 'restart training from a checkpoint file by loading state dicts and run variables into provided objects', 'fix random seeds for PyTorch, CUDA, and NumPy to ensure reproducible results across runs', 'compute top-k classification accuracy by comparing model output predictions against target labels']
```

Usage

```
{'create_logger_with_file_and_console_handlers': 'create a logger with file and console handlers using create_logger with a filepath and process rank', 'create_log_formatter_with_elapsed_time': 'create a LogFormatter instance that formats log records with level name, timestamp, and elapsed time', 'create_pd_stats_tracker': 'create a PD_Stats object to track and persist statistics as a pickled pandas DataFrame', 'update_pd_stats_with_row': 'update a PD_Stats tracker with a new row of data and optionally save to pickle file', 'reset_logger_elapsed_time': 'reset the logger elapsed time by calling the reset_time method attached to the logger'}
```

## File: facebookresearch_rcdm/guided_diffusion_rcdm/src/multicropdataset.py

Prompts

```
['create a logger with file and console handlers using create_logger with a filepath and process rank', 'create a LogFormatter instance that formats log records with level name, timestamp, and elapsed time', 'create a PD_Stats object to track and persist statistics as a pickled pandas DataFrame', 'update a PD_Stats tracker with a new row of data and optionally save to pickle file', 'reset the logger elapsed time by calling the reset_time method attached to the logger', 'create a MultiCropDataset instance from an ImageFolder path with configurable crop sizes and scales', 'use MultiCropDataset getitem to return multiple augmented crops of a single image', 'create a PILRandomGaussianBlur transform that applies random Gaussian blur to PIL images with configurable probability', 'use get_color_distortion to build a Compose transform with random color jitter and grayscale augmentation', 'review the MultiCropDataset class and its augmentation pipeline for self-supervised learning data loading', 'build a ResNet-50 model using Bottleneck blocks with configurable projection head and prototype layers', 'build a ResNet-101 model using Bottleneck blocks with 23 blocks in the third stage', 'build a ResNeXt-50 32x4d model with grouped convolutions and 4 width per group', 'build a widened ResNet-50 model with 2x, 4x, or 5x channel width multiplier', 'run forward pass through ResNet backbone and projection head on image tensor inputs', 'initialize distributed training mode by setting world size, rank, and NCCL backend from environment variables', 'initialize an experiment by dumping parameters, creating a checkpoint directory, logger, and training stats object', 'restart training from a checkpoint file by loading state dicts and run variables into provided objects', 'fix random seeds for PyTorch, CUDA, and NumPy to ensure reproducible results across runs', 'compute top-k classification accuracy by comparing model output predictions against target labels']
```

Usage

```
{'create_multicropdataset': 'create a MultiCropDataset instance from an ImageFolder path with configurable crop sizes and scales', 'use_getitem_multicropdataset': 'use MultiCropDataset getitem to return multiple augmented crops of a single image', 'create_pilrandomgaussianblur': 'create a PILRandomGaussianBlur transform that applies random Gaussian blur to PIL images with configurable probability', 'use_get_color_distortion': 'use get_color_distortion to build a Compose transform with random color jitter and grayscale augmentation', 'review_multicropdataset_augmentation': 'review the MultiCropDataset class and its augmentation pipeline for self-supervised learning data loading'}
```

## File: facebookresearch_rcdm/guided_diffusion_rcdm/src/resnet50.py

Prompts

```
['create a logger with file and console handlers using create_logger with a filepath and process rank', 'create a LogFormatter instance that formats log records with level name, timestamp, and elapsed time', 'create a PD_Stats object to track and persist statistics as a pickled pandas DataFrame', 'update a PD_Stats tracker with a new row of data and optionally save to pickle file', 'reset the logger elapsed time by calling the reset_time method attached to the logger', 'create a MultiCropDataset instance from an ImageFolder path with configurable crop sizes and scales', 'use MultiCropDataset getitem to return multiple augmented crops of a single image', 'create a PILRandomGaussianBlur transform that applies random Gaussian blur to PIL images with configurable probability', 'use get_color_distortion to build a Compose transform with random color jitter and grayscale augmentation', 'review the MultiCropDataset class and its augmentation pipeline for self-supervised learning data loading', 'build a ResNet-50 model using Bottleneck blocks with configurable projection head and prototype layers', 'build a ResNet-101 model using Bottleneck blocks with 23 blocks in the third stage', 'build a ResNeXt-50 32x4d model with grouped convolutions and 4 width per group', 'build a widened ResNet-50 model with 2x, 4x, or 5x channel width multiplier', 'run forward pass through ResNet backbone and projection head on image tensor inputs', 'initialize distributed training mode by setting world size, rank, and NCCL backend from environment variables', 'initialize an experiment by dumping parameters, creating a checkpoint directory, logger, and training stats object', 'restart training from a checkpoint file by loading state dicts and run variables into provided objects', 'fix random seeds for PyTorch, CUDA, and NumPy to ensure reproducible results across runs', 'compute top-k classification accuracy by comparing model output predictions against target labels']
```

Usage

```
{'build_resnet50_model': 'build a ResNet-50 model using Bottleneck blocks with configurable projection head and prototype layers', 'build_resnet101_model': 'build a ResNet-101 model using Bottleneck blocks with 23 blocks in the third stage', 'build_resnext50_model': 'build a ResNeXt-50 32x4d model with grouped convolutions and 4 width per group', 'build_wide_resnet50': 'build a widened ResNet-50 model with 2x, 4x, or 5x channel width multiplier', 'run_resnet_forward': 'run forward pass through ResNet backbone and projection head on image tensor inputs'}
```

## File: facebookresearch_rcdm/guided_diffusion_rcdm/src/utils.py

Prompts

```
['create a logger with file and console handlers using create_logger with a filepath and process rank', 'create a LogFormatter instance that formats log records with level name, timestamp, and elapsed time', 'create a PD_Stats object to track and persist statistics as a pickled pandas DataFrame', 'update a PD_Stats tracker with a new row of data and optionally save to pickle file', 'reset the logger elapsed time by calling the reset_time method attached to the logger', 'create a MultiCropDataset instance from an ImageFolder path with configurable crop sizes and scales', 'use MultiCropDataset getitem to return multiple augmented crops of a single image', 'create a PILRandomGaussianBlur transform that applies random Gaussian blur to PIL images with configurable probability', 'use get_color_distortion to build a Compose transform with random color jitter and grayscale augmentation', 'review the MultiCropDataset class and its augmentation pipeline for self-supervised learning data loading', 'build a ResNet-50 model using Bottleneck blocks with configurable projection head and prototype layers', 'build a ResNet-101 model using Bottleneck blocks with 23 blocks in the third stage', 'build a ResNeXt-50 32x4d model with grouped convolutions and 4 width per group', 'build a widened ResNet-50 model with 2x, 4x, or 5x channel width multiplier', 'run forward pass through ResNet backbone and projection head on image tensor inputs', 'initialize distributed training mode by setting world size, rank, and NCCL backend from environment variables', 'initialize an experiment by dumping parameters, creating a checkpoint directory, logger, and training stats object', 'restart training from a checkpoint file by loading state dicts and run variables into provided objects', 'fix random seeds for PyTorch, CUDA, and NumPy to ensure reproducible results across runs', 'compute top-k classification accuracy by comparing model output predictions against target labels']
```

Usage

```
{'init_distributed_mode': 'initialize distributed training mode by setting world size, rank, and NCCL backend from environment variables', 'initialize_exp': 'initialize an experiment by dumping parameters, creating a checkpoint directory, logger, and training stats object', 'restart_from_checkpoint': 'restart training from a checkpoint file by loading state dicts and run variables into provided objects', 'fix_random_seeds': 'fix random seeds for PyTorch, CUDA, and NumPy to ensure reproducible results across runs', 'accuracy': 'compute top-k classification accuracy by comparing model output predictions against target labels'}
```

