# Agent Python Tools

- repo: facebookresearch/nocturne
- repo_uri: https://github.com/facebookresearch/nocturne

## File: facebookresearch_nocturne/scripts/cluster_scripts/run_imitation_cluster.py

Prompts

```
['run an imitation learning experiment on a SLURM cluster using submitit_slurm launcher', 'run a dry run of the imitation learning experiment to print the command without executing', 'create a timestamped snapshot of the codebase for a specific experiment to ensure reproducibility', 'review the make_code_snap function that copies Python and YAML files to a snapshot directory', 'refactor the main function to customize Hydra config overrides for epochs, seeds, or partitions', 'run a PPO reinforcement learning experiment on a SLURM cluster with specified experiment name', 'create a timestamped code snapshot directory copying Python and YAML files for reproducible experiment runs', 'run the PPO cluster script in dry mode to print the command without executing it', 'override Hydra configuration parameters including launcher partition experiment name and algorithm hyperparameters', 'copy experiment code from source directories to a snapshot path preserving directory structure', 'run an RLlib experiment on a SLURM cluster by passing the experiment name as a CLI argument', 'run a dry RLlib experiment on SLURM to print the command without executing it', 'run an RLlib experiment on SLURM with a custom code snapshot path via the --code_path flag', 'create a timestamped code snapshot directory copying Python and YAML files from the project source', 'run a sample factory experiment on a SLURM cluster with the given experiment name', 'run a dry run of the sample factory cluster script to print the command without executing', 'launch the sample factory runner with the APPO algorithm via subprocess on the SLURM cluster', 'create an Overrides instance to collect SLURM command key-value pairs for bash execution', 'add key-value pairs to an Overrides instance using the add method with a key and list of values', 'generate a bash runnable command string from an Overrides instance using the cmd method', 'review the Overrides class and its add and cmd methods for SLURM command construction', 'summarize the Overrides class usage pattern for building SLURM override commands']
```

Usage

```
{'run_imitation_experiment_on_slurm': 'run an imitation learning experiment on a SLURM cluster using submitit_slurm launcher', 'run_dry_run_imitation_experiment': 'run a dry run of the imitation learning experiment to print the command without executing', 'create_code_snapshot': 'create a timestamped snapshot of the codebase for a specific experiment to ensure reproducibility', 'review_make_code_snap': 'review the make_code_snap function that copies Python and YAML files to a snapshot directory', 'refactor_main_overrides': 'refactor the main function to customize Hydra config overrides for epochs, seeds, or partitions'}
```

## File: facebookresearch_nocturne/scripts/cluster_scripts/run_ppo_cluster.py

Prompts

```
['run an imitation learning experiment on a SLURM cluster using submitit_slurm launcher', 'run a dry run of the imitation learning experiment to print the command without executing', 'create a timestamped snapshot of the codebase for a specific experiment to ensure reproducibility', 'review the make_code_snap function that copies Python and YAML files to a snapshot directory', 'refactor the main function to customize Hydra config overrides for epochs, seeds, or partitions', 'run a PPO reinforcement learning experiment on a SLURM cluster with specified experiment name', 'create a timestamped code snapshot directory copying Python and YAML files for reproducible experiment runs', 'run the PPO cluster script in dry mode to print the command without executing it', 'override Hydra configuration parameters including launcher partition experiment name and algorithm hyperparameters', 'copy experiment code from source directories to a snapshot path preserving directory structure', 'run an RLlib experiment on a SLURM cluster by passing the experiment name as a CLI argument', 'run a dry RLlib experiment on SLURM to print the command without executing it', 'run an RLlib experiment on SLURM with a custom code snapshot path via the --code_path flag', 'create a timestamped code snapshot directory copying Python and YAML files from the project source', 'run a sample factory experiment on a SLURM cluster with the given experiment name', 'run a dry run of the sample factory cluster script to print the command without executing', 'launch the sample factory runner with the APPO algorithm via subprocess on the SLURM cluster', 'create an Overrides instance to collect SLURM command key-value pairs for bash execution', 'add key-value pairs to an Overrides instance using the add method with a key and list of values', 'generate a bash runnable command string from an Overrides instance using the cmd method', 'review the Overrides class and its add and cmd methods for SLURM command construction', 'summarize the Overrides class usage pattern for building SLURM override commands']
```

Usage

```
{'run_ppo_cluster_experiment': 'run a PPO reinforcement learning experiment on a SLURM cluster with specified experiment name', 'make_code_snapshot': 'create a timestamped code snapshot directory copying Python and YAML files for reproducible experiment runs', 'run_dry_mode': 'run the PPO cluster script in dry mode to print the command without executing it', 'override_hydra_config': 'override Hydra configuration parameters including launcher partition experiment name and algorithm hyperparameters', 'copy_experiment_code': 'copy experiment code from source directories to a snapshot path preserving directory structure'}
```

## File: facebookresearch_nocturne/scripts/cluster_scripts/run_rllib_cluster.py

Prompts

```
['run an imitation learning experiment on a SLURM cluster using submitit_slurm launcher', 'run a dry run of the imitation learning experiment to print the command without executing', 'create a timestamped snapshot of the codebase for a specific experiment to ensure reproducibility', 'review the make_code_snap function that copies Python and YAML files to a snapshot directory', 'refactor the main function to customize Hydra config overrides for epochs, seeds, or partitions', 'run a PPO reinforcement learning experiment on a SLURM cluster with specified experiment name', 'create a timestamped code snapshot directory copying Python and YAML files for reproducible experiment runs', 'run the PPO cluster script in dry mode to print the command without executing it', 'override Hydra configuration parameters including launcher partition experiment name and algorithm hyperparameters', 'copy experiment code from source directories to a snapshot path preserving directory structure', 'run an RLlib experiment on a SLURM cluster by passing the experiment name as a CLI argument', 'run a dry RLlib experiment on SLURM to print the command without executing it', 'run an RLlib experiment on SLURM with a custom code snapshot path via the --code_path flag', 'create a timestamped code snapshot directory copying Python and YAML files from the project source', 'run a sample factory experiment on a SLURM cluster with the given experiment name', 'run a dry run of the sample factory cluster script to print the command without executing', 'launch the sample factory runner with the APPO algorithm via subprocess on the SLURM cluster', 'create an Overrides instance to collect SLURM command key-value pairs for bash execution', 'add key-value pairs to an Overrides instance using the add method with a key and list of values', 'generate a bash runnable command string from an Overrides instance using the cmd method', 'review the Overrides class and its add and cmd methods for SLURM command construction', 'summarize the Overrides class usage pattern for building SLURM override commands']
```

Usage

```
{'run_rllib_experiment': 'run an RLlib experiment on a SLURM cluster by passing the experiment name as a CLI argument', 'run_rllib_dry': 'run a dry RLlib experiment on SLURM to print the command without executing it', 'run_rllib_custom_path': 'run an RLlib experiment on SLURM with a custom code snapshot path via the --code_path flag', 'make_code_snap': 'create a timestamped code snapshot directory copying Python and YAML files from the project source', 'review_make_code_snap': 'review the make_code_snap function that copies project code to a snapshot directory for reproducible runs'}
```

## File: facebookresearch_nocturne/scripts/cluster_scripts/run_sample_factory_cluster.py

Prompts

```
['run an imitation learning experiment on a SLURM cluster using submitit_slurm launcher', 'run a dry run of the imitation learning experiment to print the command without executing', 'create a timestamped snapshot of the codebase for a specific experiment to ensure reproducibility', 'review the make_code_snap function that copies Python and YAML files to a snapshot directory', 'refactor the main function to customize Hydra config overrides for epochs, seeds, or partitions', 'run a PPO reinforcement learning experiment on a SLURM cluster with specified experiment name', 'create a timestamped code snapshot directory copying Python and YAML files for reproducible experiment runs', 'run the PPO cluster script in dry mode to print the command without executing it', 'override Hydra configuration parameters including launcher partition experiment name and algorithm hyperparameters', 'copy experiment code from source directories to a snapshot path preserving directory structure', 'run an RLlib experiment on a SLURM cluster by passing the experiment name as a CLI argument', 'run a dry RLlib experiment on SLURM to print the command without executing it', 'run an RLlib experiment on SLURM with a custom code snapshot path via the --code_path flag', 'create a timestamped code snapshot directory copying Python and YAML files from the project source', 'run a sample factory experiment on a SLURM cluster with the given experiment name', 'run a dry run of the sample factory cluster script to print the command without executing', 'launch the sample factory runner with the APPO algorithm via subprocess on the SLURM cluster', 'create an Overrides instance to collect SLURM command key-value pairs for bash execution', 'add key-value pairs to an Overrides instance using the add method with a key and list of values', 'generate a bash runnable command string from an Overrides instance using the cmd method', 'review the Overrides class and its add and cmd methods for SLURM command construction', 'summarize the Overrides class usage pattern for building SLURM override commands']
```

Usage

```
{'run_sample_factory_experiment': 'run a sample factory experiment on a SLURM cluster with the given experiment name', 'run_dry_run': 'run a dry run of the sample factory cluster script to print the command without executing', 'make_code_snapshot': 'make a code snapshot by copying Python and YAML files to a timestamped directory for the experiment', 'override_hydra_config': 'override Hydra config values for launcher, partition, seed, and collision penalty before launching', 'launch_sample_factory_with_appon': 'launch the sample factory runner with the APPO algorithm via subprocess on the SLURM cluster'}
```

## File: facebookresearch_nocturne/scripts/cluster_scripts/utils.py

Prompts

```
['run an imitation learning experiment on a SLURM cluster using submitit_slurm launcher', 'run a dry run of the imitation learning experiment to print the command without executing', 'create a timestamped snapshot of the codebase for a specific experiment to ensure reproducibility', 'review the make_code_snap function that copies Python and YAML files to a snapshot directory', 'refactor the main function to customize Hydra config overrides for epochs, seeds, or partitions', 'run a PPO reinforcement learning experiment on a SLURM cluster with specified experiment name', 'create a timestamped code snapshot directory copying Python and YAML files for reproducible experiment runs', 'run the PPO cluster script in dry mode to print the command without executing it', 'override Hydra configuration parameters including launcher partition experiment name and algorithm hyperparameters', 'copy experiment code from source directories to a snapshot path preserving directory structure', 'run an RLlib experiment on a SLURM cluster by passing the experiment name as a CLI argument', 'run a dry RLlib experiment on SLURM to print the command without executing it', 'run an RLlib experiment on SLURM with a custom code snapshot path via the --code_path flag', 'create a timestamped code snapshot directory copying Python and YAML files from the project source', 'run a sample factory experiment on a SLURM cluster with the given experiment name', 'run a dry run of the sample factory cluster script to print the command without executing', 'launch the sample factory runner with the APPO algorithm via subprocess on the SLURM cluster', 'create an Overrides instance to collect SLURM command key-value pairs for bash execution', 'add key-value pairs to an Overrides instance using the add method with a key and list of values', 'generate a bash runnable command string from an Overrides instance using the cmd method', 'review the Overrides class and its add and cmd methods for SLURM command construction', 'summarize the Overrides class usage pattern for building SLURM override commands']
```

Usage

```
{'create_Overrides_instance': 'create an Overrides instance to collect SLURM command key-value pairs for bash execution', 'add_key_value_pairs': 'add key-value pairs to an Overrides instance using the add method with a key and list of values', 'generate_bash_command': 'generate a bash runnable command string from an Overrides instance using the cmd method', 'review_Overrides_class': 'review the Overrides class and its add and cmd methods for SLURM command construction', 'summarize_Overrides_usage': 'summarize the Overrides class usage pattern for building SLURM override commands'}
```

