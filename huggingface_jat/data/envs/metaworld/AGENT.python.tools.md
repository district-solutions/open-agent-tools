# Agent Python Tools

- repo: huggingface/jat
- repo_uri: https://github.com/huggingface/jat

## File: huggingface_jat/data/envs/metaworld/generate_dataset.py

Prompts

```
['run the script to generate a metaworld dataset from a trained sample-factory checkpoint', 'create a train and test dataset by running a loaded policy in a metaworld environment', 'create a gymnasium environment from a full environment name with an optional render mode', 'review the create_dataset function that collects observations actions and rewards from a policy rollout', 'refactor the create_dataset function to make the hardcoded dataset size configurable via arguments', 'run generate_random_score to evaluate a random agent on a metaworld task for 1M timesteps', 'run the script to benchmark random agent scores across all 50 metaworld environments in parallel', 'generate random agent scores for a single metaworld task like metaworld-assembly and save to JSON', 'review the generate_random_score function that runs random actions in a gymnasium metaworld environment', 'summarize the random agent mean and std rewards saved in the metaworld scores dictionary JSON file', 'run the metaworld push environment evaluation using sample_factory enjoy mode', 'create a custom gymnasium environment from a full env name with optional render mode', 'register a custom environment factory function with sample_factory for evaluation', 'parse sample_factory CLI arguments in evaluation mode to get the config parser', 'run the sample_factory enjoy loop with parsed config to evaluate a trained agent', 'run PPO RL training on a MetaWorld environment using sample-factory with default hyperparameters', 'create a Gymnasium environment by name using make_custom_env with an optional render mode', 'override argparse defaults with PPO hyperparameters like learning rate, batch size, and rollout length', 'register a custom environment factory function with sample-factory so it can be instantiated by name', 'run the sample-factory RL training loop with a parsed config to train a PPO agent']
```

Usage

```
{'run_generate_dataset': 'run the script to generate a metaworld dataset from a trained sample-factory checkpoint', 'create_dataset_from_checkpoint': 'create a train and test dataset by running a loaded policy in a metaworld environment', 'make_custom_env_gymnasium': 'create a gymnasium environment from a full environment name with an optional render mode', 'review_create_dataset': 'review the create_dataset function that collects observations actions and rewards from a policy rollout', 'refactor_create_dataset_dataset_size': 'refactor the create_dataset function to make the hardcoded dataset size configurable via arguments'}
```

## File: huggingface_jat/data/envs/metaworld/generate_random_score.py

Prompts

```
['run the script to generate a metaworld dataset from a trained sample-factory checkpoint', 'create a train and test dataset by running a loaded policy in a metaworld environment', 'create a gymnasium environment from a full environment name with an optional render mode', 'review the create_dataset function that collects observations actions and rewards from a policy rollout', 'refactor the create_dataset function to make the hardcoded dataset size configurable via arguments', 'run generate_random_score to evaluate a random agent on a metaworld task for 1M timesteps', 'run the script to benchmark random agent scores across all 50 metaworld environments in parallel', 'generate random agent scores for a single metaworld task like metaworld-assembly and save to JSON', 'review the generate_random_score function that runs random actions in a gymnasium metaworld environment', 'summarize the random agent mean and std rewards saved in the metaworld scores dictionary JSON file', 'run the metaworld push environment evaluation using sample_factory enjoy mode', 'create a custom gymnasium environment from a full env name with optional render mode', 'register a custom environment factory function with sample_factory for evaluation', 'parse sample_factory CLI arguments in evaluation mode to get the config parser', 'run the sample_factory enjoy loop with parsed config to evaluate a trained agent', 'run PPO RL training on a MetaWorld environment using sample-factory with default hyperparameters', 'create a Gymnasium environment by name using make_custom_env with an optional render mode', 'override argparse defaults with PPO hyperparameters like learning rate, batch size, and rollout length', 'register a custom environment factory function with sample-factory so it can be instantiated by name', 'run the sample-factory RL training loop with a parsed config to train a PPO agent']
```

Usage

```
{'run_generate_random_score': 'run generate_random_score to evaluate a random agent on a metaworld task for 1M timesteps', 'run_metaworld_benchmark': 'run the script to benchmark random agent scores across all 50 metaworld environments in parallel', 'generate_random_score_single_task': 'generate random agent scores for a single metaworld task like metaworld-assembly and save to JSON', 'review_generate_random_score': 'review the generate_random_score function that runs random actions in a gymnasium metaworld environment', 'summarize_metaworld_scores': 'summarize the random agent mean and std rewards saved in the metaworld scores dictionary JSON file'}
```

## File: huggingface_jat/data/envs/metaworld/push.py

Prompts

```
['run the script to generate a metaworld dataset from a trained sample-factory checkpoint', 'create a train and test dataset by running a loaded policy in a metaworld environment', 'create a gymnasium environment from a full environment name with an optional render mode', 'review the create_dataset function that collects observations actions and rewards from a policy rollout', 'refactor the create_dataset function to make the hardcoded dataset size configurable via arguments', 'run generate_random_score to evaluate a random agent on a metaworld task for 1M timesteps', 'run the script to benchmark random agent scores across all 50 metaworld environments in parallel', 'generate random agent scores for a single metaworld task like metaworld-assembly and save to JSON', 'review the generate_random_score function that runs random actions in a gymnasium metaworld environment', 'summarize the random agent mean and std rewards saved in the metaworld scores dictionary JSON file', 'run the metaworld push environment evaluation using sample_factory enjoy mode', 'create a custom gymnasium environment from a full env name with optional render mode', 'register a custom environment factory function with sample_factory for evaluation', 'parse sample_factory CLI arguments in evaluation mode to get the config parser', 'run the sample_factory enjoy loop with parsed config to evaluate a trained agent', 'run PPO RL training on a MetaWorld environment using sample-factory with default hyperparameters', 'create a Gymnasium environment by name using make_custom_env with an optional render mode', 'override argparse defaults with PPO hyperparameters like learning rate, batch size, and rollout length', 'register a custom environment factory function with sample-factory so it can be instantiated by name', 'run the sample-factory RL training loop with a parsed config to train a PPO agent']
```

Usage

```
{'run_metaworld_push_evaluation': 'run the metaworld push environment evaluation using sample_factory enjoy mode', 'create_custom_gymnasium_env': 'create a custom gymnasium environment from a full env name with optional render mode', 'register_env_with_sample_factory': 'register a custom environment factory function with sample_factory for evaluation', 'parse_sample_factory_args': 'parse sample_factory CLI arguments in evaluation mode to get the config parser', 'run_enjoy_loop': 'run the sample_factory enjoy loop with parsed config to evaluate a trained agent'}
```

## File: huggingface_jat/data/envs/metaworld/train.py

Prompts

```
['run the script to generate a metaworld dataset from a trained sample-factory checkpoint', 'create a train and test dataset by running a loaded policy in a metaworld environment', 'create a gymnasium environment from a full environment name with an optional render mode', 'review the create_dataset function that collects observations actions and rewards from a policy rollout', 'refactor the create_dataset function to make the hardcoded dataset size configurable via arguments', 'run generate_random_score to evaluate a random agent on a metaworld task for 1M timesteps', 'run the script to benchmark random agent scores across all 50 metaworld environments in parallel', 'generate random agent scores for a single metaworld task like metaworld-assembly and save to JSON', 'review the generate_random_score function that runs random actions in a gymnasium metaworld environment', 'summarize the random agent mean and std rewards saved in the metaworld scores dictionary JSON file', 'run the metaworld push environment evaluation using sample_factory enjoy mode', 'create a custom gymnasium environment from a full env name with optional render mode', 'register a custom environment factory function with sample_factory for evaluation', 'parse sample_factory CLI arguments in evaluation mode to get the config parser', 'run the sample_factory enjoy loop with parsed config to evaluate a trained agent', 'run PPO RL training on a MetaWorld environment using sample-factory with default hyperparameters', 'create a Gymnasium environment by name using make_custom_env with an optional render mode', 'override argparse defaults with PPO hyperparameters like learning rate, batch size, and rollout length', 'register a custom environment factory function with sample-factory so it can be instantiated by name', 'run the sample-factory RL training loop with a parsed config to train a PPO agent']
```

Usage

```
{'run_metaworld_rl_training': 'run PPO RL training on a MetaWorld environment using sample-factory with default hyperparameters', 'create_custom_gym_env': 'create a Gymnasium environment by name using make_custom_env with an optional render mode', 'override_ppo_defaults': 'override argparse defaults with PPO hyperparameters like learning rate, batch size, and rollout length', 'register_custom_env': 'register a custom environment factory function with sample-factory so it can be instantiated by name', 'run_rl_training_loop': 'run the sample-factory RL training loop with a parsed config to train a PPO agent'}
```

