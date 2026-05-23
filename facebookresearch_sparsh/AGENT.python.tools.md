# Agent Python Tools

- repo: facebookresearch/sparsh
- repo_uri: https://github.com/facebookresearch/sparsh

## File: facebookresearch_sparsh/demo_forcefield.py

Prompts

```
['run a demo of a trained force field model using the latest checkpoint and Hydra config', 'run the Hydra-configured main entry point to load experiment config and execute the demo', 'load the latest .pth checkpoint file from the model checkpoints directory', 'instantiate a force field model and demo runner using hydra.utils.instantiate from config', 'set test parameters including task name, sensor, checkpoint, and output path for the demo', 'run the test function to evaluate model checkpoints on digit and gelsight sensor datasets', 'create a test dataset and dataloader for digit or gelsight sensor data using hydra config', 'build a test dataset and dataloader by dispatching to the appropriate sensor type handler', 'create a test dataset for reskin sensor data (currently raises NotImplementedError)', 'run the tactile SSL model training pipeline with Hydra config and WandB logging', 'run the dataloader creation function to build train and validation PyTorch DataLoaders from config', 'run the vision-based dataloader builder for digit, gelsight_mini, and gelsight sensor types', 'run the magnetic-based dataloader builder for tdex and reskin tactile sensor datasets', 'run the checkpoint resume logic to restore a previous training run from SLURM or config', 'run the tactile SSL training pipeline with hydra config and wandb logging', 'initialize a wandb run with project entity group tags and notes from config', 'build train and validation dataloaders for digit or gelsight tactile sensor datasets', 'build train and validation dataloaders for reskin tactile sensor datasets using ConcatDataset', 'attempt to resume a previous experiment from saved checkpoints and wandb logs']
```

Usage

```
{'run_demo_forcefield': 'run a demo of a trained force field model using the latest checkpoint and Hydra config', 'run_main_entry': 'run the Hydra-configured main entry point to load experiment config and execute the demo', 'load_latest_checkpoint': 'load the latest .pth checkpoint file from the model checkpoints directory', 'instantiate_model_hydra': 'instantiate a force field model and demo runner using hydra.utils.instantiate from config', 'set_test_params': 'set test parameters including task name, sensor, checkpoint, and output path for the demo'}
```

## File: facebookresearch_sparsh/test_task.py

Prompts

```
['run a demo of a trained force field model using the latest checkpoint and Hydra config', 'run the Hydra-configured main entry point to load experiment config and execute the demo', 'load the latest .pth checkpoint file from the model checkpoints directory', 'instantiate a force field model and demo runner using hydra.utils.instantiate from config', 'set test parameters including task name, sensor, checkpoint, and output path for the demo', 'run the test function to evaluate model checkpoints on digit and gelsight sensor datasets', 'create a test dataset and dataloader for digit or gelsight sensor data using hydra config', 'build a test dataset and dataloader by dispatching to the appropriate sensor type handler', 'create a test dataset for reskin sensor data (currently raises NotImplementedError)', 'run the tactile SSL model training pipeline with Hydra config and WandB logging', 'run the dataloader creation function to build train and validation PyTorch DataLoaders from config', 'run the vision-based dataloader builder for digit, gelsight_mini, and gelsight sensor types', 'run the magnetic-based dataloader builder for tdex and reskin tactile sensor datasets', 'run the checkpoint resume logic to restore a previous training run from SLURM or config', 'run the tactile SSL training pipeline with hydra config and wandb logging', 'initialize a wandb run with project entity group tags and notes from config', 'build train and validation dataloaders for digit or gelsight tactile sensor datasets', 'build train and validation dataloaders for reskin tactile sensor datasets using ConcatDataset', 'attempt to resume a previous experiment from saved checkpoints and wandb logs']
```

Usage

```
{'run_test_evaluation': 'run the test function to evaluate model checkpoints on digit and gelsight sensor datasets', 'get_dataset_digit': 'create a test dataset and dataloader for digit or gelsight sensor data using hydra config', 'get_test_dataset': 'build a test dataset and dataloader by dispatching to the appropriate sensor type handler', 'run_main_entry': 'run the hydra main entry point to load config and execute model testing across checkpoints', 'get_dataset_reskin': 'create a test dataset for reskin sensor data (currently raises NotImplementedError)'}
```

## File: facebookresearch_sparsh/train.py

Prompts

```
['run a demo of a trained force field model using the latest checkpoint and Hydra config', 'run the Hydra-configured main entry point to load experiment config and execute the demo', 'load the latest .pth checkpoint file from the model checkpoints directory', 'instantiate a force field model and demo runner using hydra.utils.instantiate from config', 'set test parameters including task name, sensor, checkpoint, and output path for the demo', 'run the test function to evaluate model checkpoints on digit and gelsight sensor datasets', 'create a test dataset and dataloader for digit or gelsight sensor data using hydra config', 'build a test dataset and dataloader by dispatching to the appropriate sensor type handler', 'create a test dataset for reskin sensor data (currently raises NotImplementedError)', 'run the tactile SSL model training pipeline with Hydra config and WandB logging', 'run the dataloader creation function to build train and validation PyTorch DataLoaders from config', 'run the vision-based dataloader builder for digit, gelsight_mini, and gelsight sensor types', 'run the magnetic-based dataloader builder for tdex and reskin tactile sensor datasets', 'run the checkpoint resume logic to restore a previous training run from SLURM or config', 'run the tactile SSL training pipeline with hydra config and wandb logging', 'initialize a wandb run with project entity group tags and notes from config', 'build train and validation dataloaders for digit or gelsight tactile sensor datasets', 'build train and validation dataloaders for reskin tactile sensor datasets using ConcatDataset', 'attempt to resume a previous experiment from saved checkpoints and wandb logs']
```

Usage

```
{'run_train': 'run the tactile SSL model training pipeline with Hydra config and WandB logging', 'run_get_dataloaders': 'run the dataloader creation function to build train and validation PyTorch DataLoaders from config', 'run_get_dataloaders_vision_based': 'run the vision-based dataloader builder for digit, gelsight_mini, and gelsight sensor types', 'run_get_dataloaders_magnetic_based': 'run the magnetic-based dataloader builder for tdex and reskin tactile sensor datasets', 'run_attempt_resume': 'run the checkpoint resume logic to restore a previous training run from SLURM or config'}
```

## File: facebookresearch_sparsh/train_task.py

Prompts

```
['run a demo of a trained force field model using the latest checkpoint and Hydra config', 'run the Hydra-configured main entry point to load experiment config and execute the demo', 'load the latest .pth checkpoint file from the model checkpoints directory', 'instantiate a force field model and demo runner using hydra.utils.instantiate from config', 'set test parameters including task name, sensor, checkpoint, and output path for the demo', 'run the test function to evaluate model checkpoints on digit and gelsight sensor datasets', 'create a test dataset and dataloader for digit or gelsight sensor data using hydra config', 'build a test dataset and dataloader by dispatching to the appropriate sensor type handler', 'create a test dataset for reskin sensor data (currently raises NotImplementedError)', 'run the tactile SSL model training pipeline with Hydra config and WandB logging', 'run the dataloader creation function to build train and validation PyTorch DataLoaders from config', 'run the vision-based dataloader builder for digit, gelsight_mini, and gelsight sensor types', 'run the magnetic-based dataloader builder for tdex and reskin tactile sensor datasets', 'run the checkpoint resume logic to restore a previous training run from SLURM or config', 'run the tactile SSL training pipeline with hydra config and wandb logging', 'initialize a wandb run with project entity group tags and notes from config', 'build train and validation dataloaders for digit or gelsight tactile sensor datasets', 'build train and validation dataloaders for reskin tactile sensor datasets using ConcatDataset', 'attempt to resume a previous experiment from saved checkpoints and wandb logs']
```

Usage

```
{'run_train_task': 'run the tactile SSL training pipeline with hydra config and wandb logging', 'init_wandb': 'initialize a wandb run with project entity group tags and notes from config', 'get_dataloader_digit': 'build train and validation dataloaders for digit or gelsight tactile sensor datasets', 'get_dataloader_reskin': 'build train and validation dataloaders for reskin tactile sensor datasets using ConcatDataset', 'attempt_resume': 'attempt to resume a previous experiment from saved checkpoints and wandb logs'}
```

