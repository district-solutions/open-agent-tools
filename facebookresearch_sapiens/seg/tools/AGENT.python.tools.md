# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/seg/tools/test.py

Prompts

```
['test a MMSeg segmentation model with a config file and checkpoint using the CLI', 'run model evaluation and dump metric results to a specified work directory as JSON', 'test a segmentation model and show prediction results with optional wait time between displays', 'test a segmentation model with test time augmentation enabled via the --tta flag', 'test a model and save output predictions to a directory for offline evaluation', 'train a segmentation model using a config file path and optional work directory', 'resume training from an auto-detected or specified checkpoint path in the work directory', 'enable automatic mixed precision training by switching the optimizer wrapper to AmpOptimWrapper', 'override config settings at runtime using key=value pairs merged into the config file', 'launch distributed training jobs using pytorch, slurm, or mpi launchers with local rank support']
```

Usage

```
{'test_segmentation_model': 'test a MMSeg segmentation model with a config file and checkpoint using the CLI', 'run_model_evaluation': 'run model evaluation and dump metric results to a specified work directory as JSON', 'test_with_visualization': 'test a segmentation model and show prediction results with optional wait time between displays', 'test_with_tta': 'test a segmentation model with test time augmentation enabled via the --tta flag', 'save_prediction_output': 'test a model and save output predictions to a directory for offline evaluation'}
```

## File: facebookresearch_sapiens/seg/tools/train.py

Prompts

```
['test a MMSeg segmentation model with a config file and checkpoint using the CLI', 'run model evaluation and dump metric results to a specified work directory as JSON', 'test a segmentation model and show prediction results with optional wait time between displays', 'test a segmentation model with test time augmentation enabled via the --tta flag', 'test a model and save output predictions to a directory for offline evaluation', 'train a segmentation model using a config file path and optional work directory', 'resume training from an auto-detected or specified checkpoint path in the work directory', 'enable automatic mixed precision training by switching the optimizer wrapper to AmpOptimWrapper', 'override config settings at runtime using key=value pairs merged into the config file', 'launch distributed training jobs using pytorch, slurm, or mpi launchers with local rank support']
```

Usage

```
{'train_segmentor_with_config': 'train a segmentation model using a config file path and optional work directory', 'resume_training_from_checkpoint': 'resume training from an auto-detected or specified checkpoint path in the work directory', 'enable_amp_training': 'enable automatic mixed precision training by switching the optimizer wrapper to AmpOptimWrapper', 'override_config_options': 'override config settings at runtime using key=value pairs merged into the config file', 'launch_distributed_training': 'launch distributed training jobs using pytorch, slurm, or mpi launchers with local rank support'}
```

