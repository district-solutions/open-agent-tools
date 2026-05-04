# Agent Python Tools

- repo: facebookresearch/audiocraft
- repo_uri: https://github.com/facebookresearch/audiocraft.git

## File: facebookresearch_audiocraft/audiocraft/environment.py

Prompts

```
['get the detected compute cluster type for the current AudioCraft environment', 'get the selected team name from the AudioCraft environment configuration', 'resolve a path containing the //reference placeholder to the actual reference directory', 'apply regex-based dataset path mapping rules to transform file paths across clusters', 'get the SLURM partitions as a comma-separated string for the current team and cluster', 'run the AudioCraft training loop using dora and hydra configuration', 'get a Solver object from a Dora experiment signature for use in a notebook', 'get a Solver object from a Dora XP with optional config overrides and checkpoint restore', 'initialize random seeds and system settings for reproducible distributed training', 'resolve dataset manifest paths to absolute paths for Dora git clone repositories']
```

Usage

```
{'get_cluster_type': 'get the detected compute cluster type for the current AudioCraft environment', 'get_team_name': 'get the selected team name from the AudioCraft environment configuration', 'resolve_reference_path': 'resolve a path containing the //reference placeholder to the actual reference directory', 'apply_dataset_mappers': 'apply regex-based dataset path mapping rules to transform file paths across clusters', 'get_slurm_partitions': 'get the SLURM partitions as a comma-separated string for the current team and cluster'}
```

## File: facebookresearch_audiocraft/audiocraft/train.py

Prompts

```
['get the detected compute cluster type for the current AudioCraft environment', 'get the selected team name from the AudioCraft environment configuration', 'resolve a path containing the //reference placeholder to the actual reference directory', 'apply regex-based dataset path mapping rules to transform file paths across clusters', 'get the SLURM partitions as a comma-separated string for the current team and cluster', 'run the AudioCraft training loop using dora and hydra configuration', 'get a Solver object from a Dora experiment signature for use in a notebook', 'get a Solver object from a Dora XP with optional config overrides and checkpoint restore', 'initialize random seeds and system settings for reproducible distributed training', 'resolve dataset manifest paths to absolute paths for Dora git clone repositories']
```

Usage

```
{'run_training_loop': 'run the AudioCraft training loop using dora and hydra configuration', 'get_solver_from_sig': 'get a Solver object from a Dora experiment signature for use in a notebook', 'get_solver_from_xp': 'get a Solver object from a Dora XP with optional config overrides and checkpoint restore', 'init_seed_and_system': 'initialize random seeds and system settings for reproducible distributed training', 'resolve_config_dset_paths': 'resolve dataset manifest paths to absolute paths for Dora git clone repositories'}
```

