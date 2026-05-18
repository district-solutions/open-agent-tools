# Agent Python Tools

- repo: facebookresearch/mlgym
- repo_uri: https://github.com/facebookresearch/mlgym

## File: facebookresearch_mlgym/data/rlMetaMazeMisc/src/helpers.py

Prompts

```
['load a YAML training config file with a custom seed ID and optional learning rate override', 'save a Python object to a pickle file, creating parent directories as needed', 'load a pickled Python object from a file and return it', 'review the load_config function to understand how it parses YAML configs and sets seed and learning rate', 'refactor save_pkl_object to support compression or alternative serialization formats', 'build a Flax Model with split actor-critic MLP architecture for the MetaMaze-misc Gymnax environment', 'instantiate a Model and initialize its parameters using get_model_ready with an RNG and config', 'create a uniform weight initializer with a configurable scale factor using default_mlp_init', 'run a forward pass through the Model to get value estimates and categorical action logits', 'review the Model class flatten_2d and flatten_3d options for reshaping image observations', 'train a PPO policy for MetaMaze-misc environment using JAX and Flax with configurable hyperparameters', 'create a BatchManager to manage rollout buffers with GAE lambda discounting and n-step returns', 'calculate generalized advantage estimation (GAE) advantages and targets from values rewards and dones', 'compute the combined PPO actor and critic loss with clipped value and entropy regularization', 'evaluate a trained policy by running batch rollouts and computing mean cumulative returns']
```

Usage

```
{'load_config_yaml': 'load a YAML training config file with a custom seed ID and optional learning rate override', 'save_pkl_object': 'save a Python object to a pickle file, creating parent directories as needed', 'load_pkl_object': 'load a pickled Python object from a file and return it', 'review_load_config': 'review the load_config function to understand how it parses YAML configs and sets seed and learning rate', 'refactor_save_pkl_object': 'refactor save_pkl_object to support compression or alternative serialization formats'}
```

## File: facebookresearch_mlgym/data/rlMetaMazeMisc/src/networks.py

Prompts

```
['load a YAML training config file with a custom seed ID and optional learning rate override', 'save a Python object to a pickle file, creating parent directories as needed', 'load a pickled Python object from a file and return it', 'review the load_config function to understand how it parses YAML configs and sets seed and learning rate', 'refactor save_pkl_object to support compression or alternative serialization formats', 'build a Flax Model with split actor-critic MLP architecture for the MetaMaze-misc Gymnax environment', 'instantiate a Model and initialize its parameters using get_model_ready with an RNG and config', 'create a uniform weight initializer with a configurable scale factor using default_mlp_init', 'run a forward pass through the Model to get value estimates and categorical action logits', 'review the Model class flatten_2d and flatten_3d options for reshaping image observations', 'train a PPO policy for MetaMaze-misc environment using JAX and Flax with configurable hyperparameters', 'create a BatchManager to manage rollout buffers with GAE lambda discounting and n-step returns', 'calculate generalized advantage estimation (GAE) advantages and targets from values rewards and dones', 'compute the combined PPO actor and critic loss with clipped value and entropy regularization', 'evaluate a trained policy by running batch rollouts and computing mean cumulative returns']
```

Usage

```
{'build_model_for_metamaze': 'build a Flax Model with split actor-critic MLP architecture for the MetaMaze-misc Gymnax environment', 'instantiate_model_and_params': 'instantiate a Model and initialize its parameters using get_model_ready with an RNG and config', 'create_uniform_initializer': 'create a uniform weight initializer with a configurable scale factor using default_mlp_init', 'run_actor_critic_forward_pass': 'run a forward pass through the Model to get value estimates and categorical action logits', 'review_model_flatten_options': 'review the Model class flatten_2d and flatten_3d options for reshaping image observations'}
```

## File: facebookresearch_mlgym/data/rlMetaMazeMisc/src/policy.py

Prompts

```
['load a YAML training config file with a custom seed ID and optional learning rate override', 'save a Python object to a pickle file, creating parent directories as needed', 'load a pickled Python object from a file and return it', 'review the load_config function to understand how it parses YAML configs and sets seed and learning rate', 'refactor save_pkl_object to support compression or alternative serialization formats', 'build a Flax Model with split actor-critic MLP architecture for the MetaMaze-misc Gymnax environment', 'instantiate a Model and initialize its parameters using get_model_ready with an RNG and config', 'create a uniform weight initializer with a configurable scale factor using default_mlp_init', 'run a forward pass through the Model to get value estimates and categorical action logits', 'review the Model class flatten_2d and flatten_3d options for reshaping image observations', 'train a PPO policy for MetaMaze-misc environment using JAX and Flax with configurable hyperparameters', 'create a BatchManager to manage rollout buffers with GAE lambda discounting and n-step returns', 'calculate generalized advantage estimation (GAE) advantages and targets from values rewards and dones', 'compute the combined PPO actor and critic loss with clipped value and entropy regularization', 'evaluate a trained policy by running batch rollouts and computing mean cumulative returns']
```

Usage

```
{'train_ppo_policy': 'train a PPO policy for MetaMaze-misc environment using JAX and Flax with configurable hyperparameters', 'create_batch_manager': 'create a BatchManager to manage rollout buffers with GAE lambda discounting and n-step returns', 'calculate_gae_advantages': 'calculate generalized advantage estimation (GAE) advantages and targets from values rewards and dones', 'compute_actor_critic_loss': 'compute the combined PPO actor and critic loss with clipped value and entropy regularization', 'evaluate_policy_rollout': 'evaluate a trained policy by running batch rollouts and computing mean cumulative returns'}
```

