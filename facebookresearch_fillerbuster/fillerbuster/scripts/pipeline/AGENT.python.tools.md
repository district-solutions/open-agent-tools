# Agent Python Tools

- repo: facebookresearch/fillerbuster
- repo_uri: https://github.com/facebookresearch/fillerbuster

## File: facebookresearch_fillerbuster/fillerbuster/scripts/pipeline/eval.py

Prompts

```
['run the fillerbuster evaluation pipeline with distributed training on validation batches', 'create a validation dataloader using NerfstudioDataset with configurable patch size and batch size', 'run a single evaluation step on the pipeline with image origins and directions', 'get ray origins and directions from a batch for the evaluation pipeline', 'load the fillerbuster pipeline and initialize distributed data parallel training', 'run the fillerbuster distributed training pipeline with tyro CLI and a TrainConfig', 'build a fillerbuster pipeline using get_pipeline with config, local_rank, global_rank, and logger', 'create a FillerbusterData training dataset with patch_size, num_patches, and ray augmentation settings', 'create a NerfstudioDataset validation dataset with specified patch_size, strides, and camera resolution scale', 'compute ray origins and directions from a batch using get_origins_and_directions with shape and device']
```

Usage

```
{'run_evaluation_pipeline': 'run the fillerbuster evaluation pipeline with distributed training on validation batches', 'create_validation_dataloader': 'create a validation dataloader using NerfstudioDataset with configurable patch size and batch size', 'run_eval_step': 'run a single evaluation step on the pipeline with image origins and directions', 'get_origins_and_directions': 'get ray origins and directions from a batch for the evaluation pipeline', 'load_pipeline_checkpoints': 'load the fillerbuster pipeline and initialize distributed data parallel training'}
```

## File: facebookresearch_fillerbuster/fillerbuster/scripts/pipeline/train.py

Prompts

```
['run the fillerbuster evaluation pipeline with distributed training on validation batches', 'create a validation dataloader using NerfstudioDataset with configurable patch size and batch size', 'run a single evaluation step on the pipeline with image origins and directions', 'get ray origins and directions from a batch for the evaluation pipeline', 'load the fillerbuster pipeline and initialize distributed data parallel training', 'run the fillerbuster distributed training pipeline with tyro CLI and a TrainConfig', 'build a fillerbuster pipeline using get_pipeline with config, local_rank, global_rank, and logger', 'create a FillerbusterData training dataset with patch_size, num_patches, and ray augmentation settings', 'create a NerfstudioDataset validation dataset with specified patch_size, strides, and camera resolution scale', 'compute ray origins and directions from a batch using get_origins_and_directions with shape and device']
```

Usage

```
{'run_distributed_training': 'run the fillerbuster distributed training pipeline with tyro CLI and a TrainConfig', 'build_pipeline': 'build a fillerbuster pipeline using get_pipeline with config, local_rank, global_rank, and logger', 'create_training_dataset': 'create a FillerbusterData training dataset with patch_size, num_patches, and ray augmentation settings', 'create_validation_dataset': 'create a NerfstudioDataset validation dataset with specified patch_size, strides, and camera resolution scale', 'compute_ray_origins_directions': 'compute ray origins and directions from a batch using get_origins_and_directions with shape and device'}
```

