# Agent Python Tools

- repo: facebookresearch/denoisedmdp
- repo_uri: https://github.com/facebookresearch/denoised_mdp

## File: facebookresearch_denoisedmdp/config.py

Prompts

```
['create a Config attrs class to define RL training hyperparameters, environment, device, and output settings', 'create an InstantiatedConfig that resolves output directories, preemption checkpoints, and logging paths from a Config', 'call to_config_and_instantiate to convert an OmegaConf DictConfig into a Config and InstantiatedConfig tuple', 'call get_dotted_name to get the fully qualified module and class name string for a given class', 'configure the Hydra ConfigStore with default config nodes for policy learning strategies like dynamics_backprop and sac', 'run the denoised MDP training loop with hydra config to train a world model and policy', 'create a ModelTrainer instance with config, summary writer, and environment seeds for training', 'train the world model and policy for a given number of iterations using replay buffer data', 'test the trained policy on the test environment and optionally save visualization videos', 'resume training from a saved checkpoint directory with replay buffer and model state']
```

Usage

```
{'create_Config': 'create a Config attrs class to define RL training hyperparameters, environment, device, and output settings', 'create_InstantiatedConfig': 'create an InstantiatedConfig that resolves output directories, preemption checkpoints, and logging paths from a Config', 'call_to_config_and_instantiate': 'call to_config_and_instantiate to convert an OmegaConf DictConfig into a Config and InstantiatedConfig tuple', 'call_get_dotted_name': 'call get_dotted_name to get the fully qualified module and class name string for a given class', 'configure_Hydra_ConfigStore': 'configure the Hydra ConfigStore with default config nodes for policy learning strategies like dynamics_backprop and sac'}
```

## File: facebookresearch_denoisedmdp/main.py

Prompts

```
['create a Config attrs class to define RL training hyperparameters, environment, device, and output settings', 'create an InstantiatedConfig that resolves output directories, preemption checkpoints, and logging paths from a Config', 'call to_config_and_instantiate to convert an OmegaConf DictConfig into a Config and InstantiatedConfig tuple', 'call get_dotted_name to get the fully qualified module and class name string for a given class', 'configure the Hydra ConfigStore with default config nodes for policy learning strategies like dynamics_backprop and sac', 'run the denoised MDP training loop with hydra config to train a world model and policy', 'create a ModelTrainer instance with config, summary writer, and environment seeds for training', 'train the world model and policy for a given number of iterations using replay buffer data', 'test the trained policy on the test environment and optionally save visualization videos', 'resume training from a saved checkpoint directory with replay buffer and model state']
```

Usage

```
{'run_denoised_mdp_training': 'run the denoised MDP training loop with hydra config to train a world model and policy', 'create_model_trainer': 'create a ModelTrainer instance with config, summary writer, and environment seeds for training', 'train_world_model_and_policy': 'train the world model and policy for a given number of iterations using replay buffer data', 'test_policy_with_visualization': 'test the trained policy on the test environment and optionally save visualization videos', 'resume_training_from_checkpoint': 'resume training from a saved checkpoint directory with replay buffer and model state'}
```

