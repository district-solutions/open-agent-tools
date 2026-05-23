# Agent Python Tools

- repo: facebookresearch/fastmri
- repo_uri: https://github.com/facebookresearch/fastmri

## File: facebookresearch_fastmri/fastmri_examples/varnet/varnet_reproduce_20201111/varnet_brain_leaderboard.py

Prompts

```
['run the varnet brain leaderboard training script with default 32 GPU DDP configuration', 'test the varnet brain model using the leaderboard script in test mode', 'build an argument parser for varnet brain training with mask type and acceleration settings', 'create a VarNetDataTransform with equispaced k-space mask for multicoil MRI data', 'review the cli_main function that orchestrates varnet model training and testing with PyTorch Lightning', 'run the VarNet knee MRI reconstruction training pipeline with configurable mask types and acceleration rates', 'test a trained VarNet model on knee MRI data using the PyTorch Lightning test mode', 'build argument parser with defaults for VarNet knee leaderboard training including mask, model, and trainer config', 'configure model checkpointing and auto-resume from the latest checkpoint in the checkpoints directory']
```

Usage

```
{'run_varnet_brain_training': 'run the varnet brain leaderboard training script with default 32 GPU DDP configuration', 'test_varnet_brain_model': 'test the varnet brain model using the leaderboard script in test mode', 'build_varnet_args_parser': 'build an argument parser for varnet brain training with mask type and acceleration settings', 'create_varnet_data_transform': 'create a VarNetDataTransform with equispaced k-space mask for multicoil MRI data', 'review_varnet_cli_main': 'review the cli_main function that orchestrates varnet model training and testing with PyTorch Lightning'}
```

## File: facebookresearch_fastmri/fastmri_examples/varnet/varnet_reproduce_20201111/varnet_knee_leaderboard.py

Prompts

```
['run the varnet brain leaderboard training script with default 32 GPU DDP configuration', 'test the varnet brain model using the leaderboard script in test mode', 'build an argument parser for varnet brain training with mask type and acceleration settings', 'create a VarNetDataTransform with equispaced k-space mask for multicoil MRI data', 'review the cli_main function that orchestrates varnet model training and testing with PyTorch Lightning', 'run the VarNet knee MRI reconstruction training pipeline with configurable mask types and acceleration rates', 'test a trained VarNet model on knee MRI data using the PyTorch Lightning test mode', 'build argument parser with defaults for VarNet knee leaderboard training including mask, model, and trainer config', 'configure model checkpointing and auto-resume from the latest checkpoint in the checkpoints directory']
```

Usage

```
{'run_varnet_knee_training': 'run the VarNet knee MRI reconstruction training pipeline with configurable mask types and acceleration rates', 'test_varnet_knee_model': 'test a trained VarNet model on knee MRI data using the PyTorch Lightning test mode', 'build_args_varnet': 'build argument parser with defaults for VarNet knee leaderboard training including mask, model, and trainer config', 'create_varnet_data_transform': 'create VarNetDataTransform instances with k-space masks for training validation and test data splits', 'configure_varnet_checkpointing': 'configure model checkpointing and auto-resume from the latest checkpoint in the checkpoints directory'}
```

