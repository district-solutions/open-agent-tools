# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/data/rlMountainCarContinuous/src/helpers.py

Prompts

```
['load a YAML training config file with seed and learning rate overrides into a DotMap', 'save a Python object to a pickle file creating parent directories as needed', 'load a pickled Python object from a file and return it', 'review the load_config function to understand how YAML configs are parsed with float resolution', 'test saving and loading a Python object using save_pkl_object and load_pkl_object', 'build a split actor-critic Model for MountainCarContinuous-v0 using get_model_ready with an RNG and config', 'create a uniform MLP weight initializer with a configurable scale using default_mlp_init', 'test the Model class forward pass by calling it with an observation tensor and RNG key', 'refactor the Model class to change the number of hidden layers or hidden units for the actor and critic', 'review the Model class split actor-critic architecture that outputs a value estimate and Gaussian policy distribution', 'train a PPO policy for MountainCarContinuous-v0 using JAX, Flax, and Optax with configurable hyperparameters', 'create a BatchManager to manage rollout buffers with GAE lambda discounting for PPO training', 'calculate Generalized Advantage Estimation advantages and targets from values, rewards, and done signals', 'run a vectorized batch evaluation of the trained policy across multiple MountainCarContinuous environments', 'compute the combined PPO actor and critic loss with clipped value targets and entropy regularization']
```

Usage

```
{'load_config_yaml': 'load a YAML training config file with seed and learning rate overrides into a DotMap', 'save_pkl_object': 'save a Python object to a pickle file creating parent directories as needed', 'load_pkl_object': 'load a pickled Python object from a file and return it', 'review_load_config': 'review the load_config function to understand how YAML configs are parsed with float resolution', 'test_save_and_load_pkl': 'test saving and loading a Python object using save_pkl_object and load_pkl_object'}
```

## File: facebookresearch_mlgym/data/rlMountainCarContinuous/src/networks.py

Prompts

```
['load a YAML training config file with seed and learning rate overrides into a DotMap', 'save a Python object to a pickle file creating parent directories as needed', 'load a pickled Python object from a file and return it', 'review the load_config function to understand how YAML configs are parsed with float resolution', 'test saving and loading a Python object using save_pkl_object and load_pkl_object', 'build a split actor-critic Model for MountainCarContinuous-v0 using get_model_ready with an RNG and config', 'create a uniform MLP weight initializer with a configurable scale using default_mlp_init', 'test the Model class forward pass by calling it with an observation tensor and RNG key', 'refactor the Model class to change the number of hidden layers or hidden units for the actor and critic', 'review the Model class split actor-critic architecture that outputs a value estimate and Gaussian policy distribution', 'train a PPO policy for MountainCarContinuous-v0 using JAX, Flax, and Optax with configurable hyperparameters', 'create a BatchManager to manage rollout buffers with GAE lambda discounting for PPO training', 'calculate Generalized Advantage Estimation advantages and targets from values, rewards, and done signals', 'run a vectorized batch evaluation of the trained policy across multiple MountainCarContinuous environments', 'compute the combined PPO actor and critic loss with clipped value targets and entropy regularization']
```

Usage

```
{'build_model_for_mountaincar': 'build a split actor-critic Model for MountainCarContinuous-v0 using get_model_ready with an RNG and config', 'create_mlp_initializer': 'create a uniform MLP weight initializer with a configurable scale using default_mlp_init', 'test_model_forward_pass': 'test the Model class forward pass by calling it with an observation tensor and RNG key', 'refactor_model_hidden_layers': 'refactor the Model class to change the number of hidden layers or hidden units for the actor and critic', 'review_model_actor_critic': 'review the Model class split actor-critic architecture that outputs a value estimate and Gaussian policy distribution'}
```

## File: facebookresearch_mlgym/data/rlMountainCarContinuous/src/policy.py

Prompts

```
['load a YAML training config file with seed and learning rate overrides into a DotMap', 'save a Python object to a pickle file creating parent directories as needed', 'load a pickled Python object from a file and return it', 'review the load_config function to understand how YAML configs are parsed with float resolution', 'test saving and loading a Python object using save_pkl_object and load_pkl_object', 'build a split actor-critic Model for MountainCarContinuous-v0 using get_model_ready with an RNG and config', 'create a uniform MLP weight initializer with a configurable scale using default_mlp_init', 'test the Model class forward pass by calling it with an observation tensor and RNG key', 'refactor the Model class to change the number of hidden layers or hidden units for the actor and critic', 'review the Model class split actor-critic architecture that outputs a value estimate and Gaussian policy distribution', 'train a PPO policy for MountainCarContinuous-v0 using JAX, Flax, and Optax with configurable hyperparameters', 'create a BatchManager to manage rollout buffers with GAE lambda discounting for PPO training', 'calculate Generalized Advantage Estimation advantages and targets from values, rewards, and done signals', 'run a vectorized batch evaluation of the trained policy across multiple MountainCarContinuous environments', 'compute the combined PPO actor and critic loss with clipped value targets and entropy regularization']
```

Usage

```
{'train_ppo_policy': 'train a PPO policy for MountainCarContinuous-v0 using JAX, Flax, and Optax with configurable hyperparameters', 'create_batch_manager': 'create a BatchManager to manage rollout buffers with GAE lambda discounting for PPO training', 'calculate_gae_advantages': 'calculate Generalized Advantage Estimation advantages and targets from values, rewards, and done signals', 'run_rollout_evaluation': 'run a vectorized batch evaluation of the trained policy across multiple MountainCarContinuous environments', 'compute_actor_critic_loss': 'compute the combined PPO actor and critic loss with clipped value targets and entropy regularization'}
```

