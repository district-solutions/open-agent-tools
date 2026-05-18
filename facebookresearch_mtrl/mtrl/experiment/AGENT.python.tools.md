# Agent Python Tools

- repo: facebookresearch/mtrl
- repo_uri: https://github.com/facebookresearch/mtrl

## File: facebookresearch_mtrl/mtrl/experiment/dmcontrol.py

Prompts

```
['create an Experiment instance with a config and optional experiment_id to manage multi-task model lifecycle', 'get an agent action in eval mode given multitask observations and mode list', 'evaluate agent performance across vectorized environments and log per-task episode rewards', 'review the Experiment class that extends multitask Experiment for DMControl multi-task evaluation', 'summarize the evaluate_vec_env_of_tasks method that runs evaluation episodes and logs per-mode rewards', 'build a subclass of Experiment that implements build_envs to create custom training environments', 'run the Experiment lifecycle by calling run to start training and evaluation loops', 'prepare the config to infer encoder feature dimensions from environment observation space metadata', 'get the observation space, action space, and max episode steps from a gym environment', 'periodically save the experiment checkpoint at configured epoch intervals during training', 'build train and eval MetaWorld vectorized environments using the Experiment build_envs method', 'create a mapping from evaluation modes to environment IDs for MetaWorld benchmarks', 'create a dictionary mapping environment names to sequential integer indices across all envs', 'collect trajectory data from a vectorized MetaWorld environment and add transitions to the replay buffer', 'build a multi-task Experiment instance with a Hydra config to manage model lifecycle', 'run the multi-task training loop with periodic evaluation and model checkpointing', 'build train and eval vectorized DMControl environments with multiple tasks and seeds', 'create a mapping from eval modes like eval_interpolation to their environment IDs', 'review the Experiment class methods for multi-task RL training and evaluation', 'clear an experiment and delete all its data metadata and logs using the config', 'get a list of directories to delete when clearing an experiment from the config', 'review the prepare_and_run function that sets seed and runs an experiment via Hydra', 'refactor the clear function to support selective directory deletion instead of removing all dirs']
```

Usage

```
{'init_experiment': 'create an Experiment instance with a config and optional experiment_id to manage multi-task model lifecycle', 'get_action_when_evaluating_vec_env_of_tasks': 'get an agent action in eval mode given multitask observations and mode list', 'evaluate_vec_env_of_tasks': 'evaluate agent performance across vectorized environments and log per-task episode rewards', 'review_Experiment_class': 'review the Experiment class that extends multitask Experiment for DMControl multi-task evaluation', 'summarize_evaluate_vec_env_of_tasks': 'summarize the evaluate_vec_env_of_tasks method that runs evaluation episodes and logs per-mode rewards'}
```

## File: facebookresearch_mtrl/mtrl/experiment/experiment.py

Prompts

```
['create an Experiment instance with a config and optional experiment_id to manage multi-task model lifecycle', 'get an agent action in eval mode given multitask observations and mode list', 'evaluate agent performance across vectorized environments and log per-task episode rewards', 'review the Experiment class that extends multitask Experiment for DMControl multi-task evaluation', 'summarize the evaluate_vec_env_of_tasks method that runs evaluation episodes and logs per-mode rewards', 'build a subclass of Experiment that implements build_envs to create custom training environments', 'run the Experiment lifecycle by calling run to start training and evaluation loops', 'prepare the config to infer encoder feature dimensions from environment observation space metadata', 'get the observation space, action space, and max episode steps from a gym environment', 'periodically save the experiment checkpoint at configured epoch intervals during training', 'build train and eval MetaWorld vectorized environments using the Experiment build_envs method', 'create a mapping from evaluation modes to environment IDs for MetaWorld benchmarks', 'create a dictionary mapping environment names to sequential integer indices across all envs', 'collect trajectory data from a vectorized MetaWorld environment and add transitions to the replay buffer', 'build a multi-task Experiment instance with a Hydra config to manage model lifecycle', 'run the multi-task training loop with periodic evaluation and model checkpointing', 'build train and eval vectorized DMControl environments with multiple tasks and seeds', 'create a mapping from eval modes like eval_interpolation to their environment IDs', 'review the Experiment class methods for multi-task RL training and evaluation', 'clear an experiment and delete all its data metadata and logs using the config', 'get a list of directories to delete when clearing an experiment from the config', 'review the prepare_and_run function that sets seed and runs an experiment via Hydra', 'refactor the clear function to support selective directory deletion instead of removing all dirs']
```

Usage

```
{'build_experiment_class': 'build a subclass of Experiment that implements build_envs to create custom training environments', 'run_experiment': 'run the Experiment lifecycle by calling run to start training and evaluation loops', 'prepare_config_encoder': 'prepare the config to infer encoder feature dimensions from environment observation space metadata', 'get_env_metadata': 'get the observation space, action space, and max episode steps from a gym environment', 'periodic_save_experiment': 'periodically save the experiment checkpoint at configured epoch intervals during training'}
```

## File: facebookresearch_mtrl/mtrl/experiment/metaworld.py

Prompts

```
['create an Experiment instance with a config and optional experiment_id to manage multi-task model lifecycle', 'get an agent action in eval mode given multitask observations and mode list', 'evaluate agent performance across vectorized environments and log per-task episode rewards', 'review the Experiment class that extends multitask Experiment for DMControl multi-task evaluation', 'summarize the evaluate_vec_env_of_tasks method that runs evaluation episodes and logs per-mode rewards', 'build a subclass of Experiment that implements build_envs to create custom training environments', 'run the Experiment lifecycle by calling run to start training and evaluation loops', 'prepare the config to infer encoder feature dimensions from environment observation space metadata', 'get the observation space, action space, and max episode steps from a gym environment', 'periodically save the experiment checkpoint at configured epoch intervals during training', 'build train and eval MetaWorld vectorized environments using the Experiment build_envs method', 'create a mapping from evaluation modes to environment IDs for MetaWorld benchmarks', 'create a dictionary mapping environment names to sequential integer indices across all envs', 'collect trajectory data from a vectorized MetaWorld environment and add transitions to the replay buffer', 'build a multi-task Experiment instance with a Hydra config to manage model lifecycle', 'run the multi-task training loop with periodic evaluation and model checkpointing', 'build train and eval vectorized DMControl environments with multiple tasks and seeds', 'create a mapping from eval modes like eval_interpolation to their environment IDs', 'review the Experiment class methods for multi-task RL training and evaluation', 'clear an experiment and delete all its data metadata and logs using the config', 'get a list of directories to delete when clearing an experiment from the config', 'review the prepare_and_run function that sets seed and runs an experiment via Hydra', 'refactor the clear function to support selective directory deletion instead of removing all dirs']
```

Usage

```
{'build_metaworld_envs': 'build train and eval MetaWorld vectorized environments using the Experiment build_envs method', 'create_eval_modes_to_env_ids': 'create a mapping from evaluation modes to environment IDs for MetaWorld benchmarks', 'create_env_id_to_index_map': 'create a dictionary mapping environment names to sequential integer indices across all envs', 'evaluate_vec_env_of_tasks': 'evaluate agent performance on multiple MetaWorld tasks and log episode reward and success metrics', 'collect_trajectory': 'collect trajectory data from a vectorized MetaWorld environment and add transitions to the replay buffer'}
```

## File: facebookresearch_mtrl/mtrl/experiment/multitask.py

Prompts

```
['create an Experiment instance with a config and optional experiment_id to manage multi-task model lifecycle', 'get an agent action in eval mode given multitask observations and mode list', 'evaluate agent performance across vectorized environments and log per-task episode rewards', 'review the Experiment class that extends multitask Experiment for DMControl multi-task evaluation', 'summarize the evaluate_vec_env_of_tasks method that runs evaluation episodes and logs per-mode rewards', 'build a subclass of Experiment that implements build_envs to create custom training environments', 'run the Experiment lifecycle by calling run to start training and evaluation loops', 'prepare the config to infer encoder feature dimensions from environment observation space metadata', 'get the observation space, action space, and max episode steps from a gym environment', 'periodically save the experiment checkpoint at configured epoch intervals during training', 'build train and eval MetaWorld vectorized environments using the Experiment build_envs method', 'create a mapping from evaluation modes to environment IDs for MetaWorld benchmarks', 'create a dictionary mapping environment names to sequential integer indices across all envs', 'collect trajectory data from a vectorized MetaWorld environment and add transitions to the replay buffer', 'build a multi-task Experiment instance with a Hydra config to manage model lifecycle', 'run the multi-task training loop with periodic evaluation and model checkpointing', 'build train and eval vectorized DMControl environments with multiple tasks and seeds', 'create a mapping from eval modes like eval_interpolation to their environment IDs', 'review the Experiment class methods for multi-task RL training and evaluation', 'clear an experiment and delete all its data metadata and logs using the config', 'get a list of directories to delete when clearing an experiment from the config', 'review the prepare_and_run function that sets seed and runs an experiment via Hydra', 'refactor the clear function to support selective directory deletion instead of removing all dirs']
```

Usage

```
{'build_multitask_experiment': 'build a multi-task Experiment instance with a Hydra config to manage model lifecycle', 'run_experiment_training_loop': 'run the multi-task training loop with periodic evaluation and model checkpointing', 'build_dmcontrol_vec_envs': 'build train and eval vectorized DMControl environments with multiple tasks and seeds', 'create_eval_modes_mapping': 'create a mapping from eval modes like eval_interpolation to their environment IDs', 'review_experiment_class': 'review the Experiment class methods for multi-task RL training and evaluation'}
```

## File: facebookresearch_mtrl/mtrl/experiment/utils.py

Prompts

```
['create an Experiment instance with a config and optional experiment_id to manage multi-task model lifecycle', 'get an agent action in eval mode given multitask observations and mode list', 'evaluate agent performance across vectorized environments and log per-task episode rewards', 'review the Experiment class that extends multitask Experiment for DMControl multi-task evaluation', 'summarize the evaluate_vec_env_of_tasks method that runs evaluation episodes and logs per-mode rewards', 'build a subclass of Experiment that implements build_envs to create custom training environments', 'run the Experiment lifecycle by calling run to start training and evaluation loops', 'prepare the config to infer encoder feature dimensions from environment observation space metadata', 'get the observation space, action space, and max episode steps from a gym environment', 'periodically save the experiment checkpoint at configured epoch intervals during training', 'build train and eval MetaWorld vectorized environments using the Experiment build_envs method', 'create a mapping from evaluation modes to environment IDs for MetaWorld benchmarks', 'create a dictionary mapping environment names to sequential integer indices across all envs', 'collect trajectory data from a vectorized MetaWorld environment and add transitions to the replay buffer', 'build a multi-task Experiment instance with a Hydra config to manage model lifecycle', 'run the multi-task training loop with periodic evaluation and model checkpointing', 'build train and eval vectorized DMControl environments with multiple tasks and seeds', 'create a mapping from eval modes like eval_interpolation to their environment IDs', 'review the Experiment class methods for multi-task RL training and evaluation', 'clear an experiment and delete all its data metadata and logs using the config', 'get a list of directories to delete when clearing an experiment from the config', 'review the prepare_and_run function that sets seed and runs an experiment via Hydra', 'refactor the clear function to support selective directory deletion instead of removing all dirs']
```

Usage

```
{'run_experiment': 'run a configured MTRL experiment by setting the seed and instantiating the experiment builder', 'clear_experiment': 'clear an experiment and delete all its data metadata and logs using the config', 'get_dirs_to_delete': 'get a list of directories to delete when clearing an experiment from the config', 'review_prepare_and_run': 'review the prepare_and_run function that sets seed and runs an experiment via Hydra', 'refactor_clear': 'refactor the clear function to support selective directory deletion instead of removing all dirs'}
```

