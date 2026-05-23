# Agent Python Tools

- repo: facebookresearch/swav
- repo_uri: https://github.com/facebookresearch/swav

## File: facebookresearch_swav/src/logger.py

Prompts

```
['create a logger that writes to both a file and console with elapsed time formatting', 'create a logger with separate log files for each process rank in distributed training', 'reset the elapsed time counter on a logger created by create_logger', 'create a PD_Stats tracker that appends rows to a pickled pandas DataFrame at a given path', 'update a PD_Stats tracker with a new row of statistics and optionally save to disk', 'create a MultiCropDataset instance from an ImageFolder path with configurable crop sizes and scales', 'create a PILRandomGaussianBlur transform that applies random Gaussian blur to PIL images with configurable probability', 'create a color distortion transform using ColorJitter and RandomGrayscale with configurable strength', 'review the MultiCropDataset __getitem__ method that returns multiple augmented crops of a single image', 'test the MultiCropDataset __init__ to verify crop transform pipelines are built correctly', 'build a ResNet-50 model using Bottleneck blocks with 3, 4, 6, 3 layers per stage', 'build a widened ResNet-50 model with a configurable widen factor of 2, 4, or 5', 'create a Bottleneck residual block with 1x1, 3x3, 1x1 convolutions and batch normalization', 'create a BasicBlock residual block with two 3x3 convolutions and batch normalization', 'create a MultiPrototypes module with multiple prototype heads for SwAV clustering', 'initialize distributed training mode by setting world size and rank from SLURM or torch.distributed environment variables', 'initialize an experiment by dumping parameters, creating a checkpoint directory, logger, and training stats object', 'restart training from a checkpoint file by loading state dicts and run variables into provided objects', 'fix random seeds for torch, cuda, and numpy to ensure reproducible results across runs', 'compute the top-k accuracy over model predictions by comparing output logits against target labels']
```

Usage

```
{'create_logger_with_file_and_console': 'create a logger that writes to both a file and console with elapsed time formatting', 'create_logger_for_multi_process': 'create a logger with separate log files for each process rank in distributed training', 'reset_logger_elapsed_time': 'reset the elapsed time counter on a logger created by create_logger', 'create_pandas_stats_tracker': 'create a PD_Stats tracker that appends rows to a pickled pandas DataFrame at a given path', 'update_pandas_stats_row': 'update a PD_Stats tracker with a new row of statistics and optionally save to disk'}
```

## File: facebookresearch_swav/src/multicropdataset.py

Prompts

```
['create a logger that writes to both a file and console with elapsed time formatting', 'create a logger with separate log files for each process rank in distributed training', 'reset the elapsed time counter on a logger created by create_logger', 'create a PD_Stats tracker that appends rows to a pickled pandas DataFrame at a given path', 'update a PD_Stats tracker with a new row of statistics and optionally save to disk', 'create a MultiCropDataset instance from an ImageFolder path with configurable crop sizes and scales', 'create a PILRandomGaussianBlur transform that applies random Gaussian blur to PIL images with configurable probability', 'create a color distortion transform using ColorJitter and RandomGrayscale with configurable strength', 'review the MultiCropDataset __getitem__ method that returns multiple augmented crops of a single image', 'test the MultiCropDataset __init__ to verify crop transform pipelines are built correctly', 'build a ResNet-50 model using Bottleneck blocks with 3, 4, 6, 3 layers per stage', 'build a widened ResNet-50 model with a configurable widen factor of 2, 4, or 5', 'create a Bottleneck residual block with 1x1, 3x3, 1x1 convolutions and batch normalization', 'create a BasicBlock residual block with two 3x3 convolutions and batch normalization', 'create a MultiPrototypes module with multiple prototype heads for SwAV clustering', 'initialize distributed training mode by setting world size and rank from SLURM or torch.distributed environment variables', 'initialize an experiment by dumping parameters, creating a checkpoint directory, logger, and training stats object', 'restart training from a checkpoint file by loading state dicts and run variables into provided objects', 'fix random seeds for torch, cuda, and numpy to ensure reproducible results across runs', 'compute the top-k accuracy over model predictions by comparing output logits against target labels']
```

Usage

```
{'create_multicrop_dataset': 'create a MultiCropDataset instance from an ImageFolder path with configurable crop sizes and scales', 'create_gaussian_blur_transform': 'create a PILRandomGaussianBlur transform that applies random Gaussian blur to PIL images with configurable probability', 'create_color_distortion_transform': 'create a color distortion transform using ColorJitter and RandomGrayscale with configurable strength', 'review_multicropdataset_getitem': 'review the MultiCropDataset __getitem__ method that returns multiple augmented crops of a single image', 'test_multicropdataset_init': 'test the MultiCropDataset __init__ to verify crop transform pipelines are built correctly'}
```

## File: facebookresearch_swav/src/resnet50.py

Prompts

```
['create a logger that writes to both a file and console with elapsed time formatting', 'create a logger with separate log files for each process rank in distributed training', 'reset the elapsed time counter on a logger created by create_logger', 'create a PD_Stats tracker that appends rows to a pickled pandas DataFrame at a given path', 'update a PD_Stats tracker with a new row of statistics and optionally save to disk', 'create a MultiCropDataset instance from an ImageFolder path with configurable crop sizes and scales', 'create a PILRandomGaussianBlur transform that applies random Gaussian blur to PIL images with configurable probability', 'create a color distortion transform using ColorJitter and RandomGrayscale with configurable strength', 'review the MultiCropDataset __getitem__ method that returns multiple augmented crops of a single image', 'test the MultiCropDataset __init__ to verify crop transform pipelines are built correctly', 'build a ResNet-50 model using Bottleneck blocks with 3, 4, 6, 3 layers per stage', 'build a widened ResNet-50 model with a configurable widen factor of 2, 4, or 5', 'create a Bottleneck residual block with 1x1, 3x3, 1x1 convolutions and batch normalization', 'create a BasicBlock residual block with two 3x3 convolutions and batch normalization', 'create a MultiPrototypes module with multiple prototype heads for SwAV clustering', 'initialize distributed training mode by setting world size and rank from SLURM or torch.distributed environment variables', 'initialize an experiment by dumping parameters, creating a checkpoint directory, logger, and training stats object', 'restart training from a checkpoint file by loading state dicts and run variables into provided objects', 'fix random seeds for torch, cuda, and numpy to ensure reproducible results across runs', 'compute the top-k accuracy over model predictions by comparing output logits against target labels']
```

Usage

```
{'build_resnet50_model': 'build a ResNet-50 model using Bottleneck blocks with 3, 4, 6, 3 layers per stage', 'build_wide_resnet50': 'build a widened ResNet-50 model with a configurable widen factor of 2, 4, or 5', 'create_bottleneck_block': 'create a Bottleneck residual block with 1x1, 3x3, 1x1 convolutions and batch normalization', 'create_basicblock': 'create a BasicBlock residual block with two 3x3 convolutions and batch normalization', 'create_multi_prototypes': 'create a MultiPrototypes module with multiple prototype heads for SwAV clustering'}
```

## File: facebookresearch_swav/src/utils.py

Prompts

```
['create a logger that writes to both a file and console with elapsed time formatting', 'create a logger with separate log files for each process rank in distributed training', 'reset the elapsed time counter on a logger created by create_logger', 'create a PD_Stats tracker that appends rows to a pickled pandas DataFrame at a given path', 'update a PD_Stats tracker with a new row of statistics and optionally save to disk', 'create a MultiCropDataset instance from an ImageFolder path with configurable crop sizes and scales', 'create a PILRandomGaussianBlur transform that applies random Gaussian blur to PIL images with configurable probability', 'create a color distortion transform using ColorJitter and RandomGrayscale with configurable strength', 'review the MultiCropDataset __getitem__ method that returns multiple augmented crops of a single image', 'test the MultiCropDataset __init__ to verify crop transform pipelines are built correctly', 'build a ResNet-50 model using Bottleneck blocks with 3, 4, 6, 3 layers per stage', 'build a widened ResNet-50 model with a configurable widen factor of 2, 4, or 5', 'create a Bottleneck residual block with 1x1, 3x3, 1x1 convolutions and batch normalization', 'create a BasicBlock residual block with two 3x3 convolutions and batch normalization', 'create a MultiPrototypes module with multiple prototype heads for SwAV clustering', 'initialize distributed training mode by setting world size and rank from SLURM or torch.distributed environment variables', 'initialize an experiment by dumping parameters, creating a checkpoint directory, logger, and training stats object', 'restart training from a checkpoint file by loading state dicts and run variables into provided objects', 'fix random seeds for torch, cuda, and numpy to ensure reproducible results across runs', 'compute the top-k accuracy over model predictions by comparing output logits against target labels']
```

Usage

```
{'init_distributed_mode': 'initialize distributed training mode by setting world size and rank from SLURM or torch.distributed environment variables', 'initialize_exp': 'initialize an experiment by dumping parameters, creating a checkpoint directory, logger, and training stats object', 'restart_from_checkpoint': 'restart training from a checkpoint file by loading state dicts and run variables into provided objects', 'fix_random_seeds': 'fix random seeds for torch, cuda, and numpy to ensure reproducible results across runs', 'accuracy': 'compute the top-k accuracy over model predictions by comparing output logits against target labels'}
```

