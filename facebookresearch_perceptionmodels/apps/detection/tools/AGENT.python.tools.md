# Agent Python Tools

- repo: facebookresearch/perceptionmodels
- repo_uri: https://github.com/facebookresearch/perception_models

## File: facebookresearch_perceptionmodels/apps/detection/tools/convert_d2.py

Prompts

```
['run convert_d2.py to convert a vision encoder checkpoint to detectron2 format with interpolated embeddings', 'run interpolate_pos_embed to bicubic interpolate positional embeddings from one patch grid size to another', 'run convert_d2.py to bicubic interpolate conv1 patch embedding weights to a new patch size', 'run convert_d2.py with --prefix to strip a key prefix from all checkpoint state dict entries', 'run convert_d2.py with --keep_pe to convert a checkpoint while preserving original positional embeddings', 'run a detection model training pipeline using a LazyConfig python config file with DDP support', 'run evaluation on a detection model using a test dataloader and evaluator from config', 'resume training from a saved checkpoint using DetectionCheckpointer with resume flag', 'review the do_train function that instantiates models, optimizers, and registers training hooks', 'review the do_test function that runs inference on a dataset and prints CSV results', 'run distributed model training on a SLURM cluster using torchrun and a LazyConfig python config file', 'run evaluation only on a trained detection model by passing --eval-only with a config file and checkpoint path', 'resume interrupted training from the last checkpoint in the output directory using the --resume flag', 'run inference on a test dataset using the model and dataloader defined in the LazyConfig and print results in CSV format', 'run the full training loop with DDP model wrapping, optimizer, LR scheduler, periodic checkpointing, and evaluation hooks']
```

Usage

```
{'convert_checkpoint_to_d2_format': 'run convert_d2.py to convert a vision encoder checkpoint to detectron2 format with interpolated embeddings', 'interpolate_positional_embeddings': 'run interpolate_pos_embed to bicubic interpolate positional embeddings from one patch grid size to another', 'interpolate_patch_embeddings': 'run convert_d2.py to bicubic interpolate conv1 patch embedding weights to a new patch size', 'strip_prefix_from_checkpoint': 'run convert_d2.py with --prefix to strip a key prefix from all checkpoint state dict entries', 'convert_checkpoint_keep_positional_embeddings': 'run convert_d2.py with --keep_pe to convert a checkpoint while preserving original positional embeddings'}
```

## File: facebookresearch_perceptionmodels/apps/detection/tools/lazyconfig_train_net_pe.py

Prompts

```
['run convert_d2.py to convert a vision encoder checkpoint to detectron2 format with interpolated embeddings', 'run interpolate_pos_embed to bicubic interpolate positional embeddings from one patch grid size to another', 'run convert_d2.py to bicubic interpolate conv1 patch embedding weights to a new patch size', 'run convert_d2.py with --prefix to strip a key prefix from all checkpoint state dict entries', 'run convert_d2.py with --keep_pe to convert a checkpoint while preserving original positional embeddings', 'run a detection model training pipeline using a LazyConfig python config file with DDP support', 'run evaluation on a detection model using a test dataloader and evaluator from config', 'resume training from a saved checkpoint using DetectionCheckpointer with resume flag', 'review the do_train function that instantiates models, optimizers, and registers training hooks', 'review the do_test function that runs inference on a dataset and prints CSV results', 'run distributed model training on a SLURM cluster using torchrun and a LazyConfig python config file', 'run evaluation only on a trained detection model by passing --eval-only with a config file and checkpoint path', 'resume interrupted training from the last checkpoint in the output directory using the --resume flag', 'run inference on a test dataset using the model and dataloader defined in the LazyConfig and print results in CSV format', 'run the full training loop with DDP model wrapping, optimizer, LR scheduler, periodic checkpointing, and evaluation hooks']
```

Usage

```
{'run_detection_model_training': 'run a detection model training pipeline using a LazyConfig python config file with DDP support', 'run_model_evaluation': 'run evaluation on a detection model using a test dataloader and evaluator from config', 'resume_training_from_checkpoint': 'resume training from a saved checkpoint using DetectionCheckpointer with resume flag', 'review_do_train_function': 'review the do_train function that instantiates models, optimizers, and registers training hooks', 'review_do_test_function': 'review the do_test function that runs inference on a dataset and prints CSV results'}
```

## File: facebookresearch_perceptionmodels/apps/detection/tools/lazyconfig_train_net_pe_slurm.py

Prompts

```
['run convert_d2.py to convert a vision encoder checkpoint to detectron2 format with interpolated embeddings', 'run interpolate_pos_embed to bicubic interpolate positional embeddings from one patch grid size to another', 'run convert_d2.py to bicubic interpolate conv1 patch embedding weights to a new patch size', 'run convert_d2.py with --prefix to strip a key prefix from all checkpoint state dict entries', 'run convert_d2.py with --keep_pe to convert a checkpoint while preserving original positional embeddings', 'run a detection model training pipeline using a LazyConfig python config file with DDP support', 'run evaluation on a detection model using a test dataloader and evaluator from config', 'resume training from a saved checkpoint using DetectionCheckpointer with resume flag', 'review the do_train function that instantiates models, optimizers, and registers training hooks', 'review the do_test function that runs inference on a dataset and prints CSV results', 'run distributed model training on a SLURM cluster using torchrun and a LazyConfig python config file', 'run evaluation only on a trained detection model by passing --eval-only with a config file and checkpoint path', 'resume interrupted training from the last checkpoint in the output directory using the --resume flag', 'run inference on a test dataset using the model and dataloader defined in the LazyConfig and print results in CSV format', 'run the full training loop with DDP model wrapping, optimizer, LR scheduler, periodic checkpointing, and evaluation hooks']
```

Usage

```
{'run_slurm_training': 'run distributed model training on a SLURM cluster using torchrun and a LazyConfig python config file', 'run_evaluation_only': 'run evaluation only on a trained detection model by passing --eval-only with a config file and checkpoint path', 'resume_training': 'resume interrupted training from the last checkpoint in the output directory using the --resume flag', 'run_do_test': 'run inference on a test dataset using the model and dataloader defined in the LazyConfig and print results in CSV format', 'run_do_train': 'run the full training loop with DDP model wrapping, optimizer, LR scheduler, periodic checkpointing, and evaluation hooks'}
```

