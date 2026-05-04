# Agent Python Tools

- repo: facebookresearch/denoisedmdp
- repo_uri: https://github.com/facebookresearch/denoised_mdp

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/abc.py

Prompts

```
['create a gym Box observation space from an ObsOutputKind enum with height, width, and channel parameters', 'convert a uint8 image tensor to normalized float32 by dividing by 255 and subtracting 0.5', 'resize a uint8 numpy array image to a target shape using OpenCV INTER_LINEAR interpolation', 'convert a uint8 numpy image to a PyTorch observation tensor with optional resizing and normalization', 'process a batched observation tensor into float32 format suitable as neural network input', 'build a Python module to interact with an AutoResetEnvBase environment using a custom interactor and yield EnvInteractData steps', 'run a random actor against an AutoResetEnvBase environment for a specified number of steps', 'run a world model agent against an AutoResetEnvBase environment and yield interaction data steps', 'create a custom interactor class by subclassing Interactor and implementing init_state and act_and_update_state methods', 'build a BasicEnvState NamedTuple to track episode count, step count, observations, rewards, and done flags', 'create a batched auto-reset environment from an env factory function with a given seed and batch shape', 'wrap a scalar environment with AutoResetWrapper to automatically reset on episode termination', 'split a random seed into n independent SeedSequences for parallel environment seeding', 'stack a list of tensors along dim 0 or convert a list to a single tensor', 'create a ConcatEnv that runs multiple environments in parallel and stacks their observations and rewards']
```

Usage

```
{'create_observation_space': 'create a gym Box observation space from an ObsOutputKind enum with height, width, and channel parameters', 'convert_uint8_to_float32': 'convert a uint8 image tensor to normalized float32 by dividing by 255 and subtracting 0.5', 'resize_uint8_image': 'resize a uint8 numpy array image to a target shape using OpenCV INTER_LINEAR interpolation', 'convert_image_to_observation': 'convert a uint8 numpy image to a PyTorch observation tensor with optional resizing and normalization', 'process_observation_for_network': 'process a batched observation tensor into float32 format suitable as neural network input'}
```

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/interaction.py

Prompts

```
['create a gym Box observation space from an ObsOutputKind enum with height, width, and channel parameters', 'convert a uint8 image tensor to normalized float32 by dividing by 255 and subtracting 0.5', 'resize a uint8 numpy array image to a target shape using OpenCV INTER_LINEAR interpolation', 'convert a uint8 numpy image to a PyTorch observation tensor with optional resizing and normalization', 'process a batched observation tensor into float32 format suitable as neural network input', 'build a Python module to interact with an AutoResetEnvBase environment using a custom interactor and yield EnvInteractData steps', 'run a random actor against an AutoResetEnvBase environment for a specified number of steps', 'run a world model agent against an AutoResetEnvBase environment and yield interaction data steps', 'create a custom interactor class by subclassing Interactor and implementing init_state and act_and_update_state methods', 'build a BasicEnvState NamedTuple to track episode count, step count, observations, rewards, and done flags', 'create a batched auto-reset environment from an env factory function with a given seed and batch shape', 'wrap a scalar environment with AutoResetWrapper to automatically reset on episode termination', 'split a random seed into n independent SeedSequences for parallel environment seeding', 'stack a list of tensors along dim 0 or convert a list to a single tensor', 'create a ConcatEnv that runs multiple environments in parallel and stacks their observations and rewards']
```

Usage

```
{'env_interact': 'build a Python module to interact with an AutoResetEnvBase environment using a custom interactor and yield EnvInteractData steps', 'env_interact_random_actor': 'run a random actor against an AutoResetEnvBase environment for a specified number of steps', 'env_interact_with_model': 'run a world model agent against an AutoResetEnvBase environment and yield interaction data steps', 'Interactor': 'create a custom interactor class by subclassing Interactor and implementing init_state and act_and_update_state methods', 'BasicEnvState': 'build a BasicEnvState NamedTuple to track episode count, step count, observations, rewards, and done flags'}
```

## File: facebookresearch_denoisedmdp/denoised_mdp/envs/utils.py

Prompts

```
['create a gym Box observation space from an ObsOutputKind enum with height, width, and channel parameters', 'convert a uint8 image tensor to normalized float32 by dividing by 255 and subtracting 0.5', 'resize a uint8 numpy array image to a target shape using OpenCV INTER_LINEAR interpolation', 'convert a uint8 numpy image to a PyTorch observation tensor with optional resizing and normalization', 'process a batched observation tensor into float32 format suitable as neural network input', 'build a Python module to interact with an AutoResetEnvBase environment using a custom interactor and yield EnvInteractData steps', 'run a random actor against an AutoResetEnvBase environment for a specified number of steps', 'run a world model agent against an AutoResetEnvBase environment and yield interaction data steps', 'create a custom interactor class by subclassing Interactor and implementing init_state and act_and_update_state methods', 'build a BasicEnvState NamedTuple to track episode count, step count, observations, rewards, and done flags', 'create a batched auto-reset environment from an env factory function with a given seed and batch shape', 'wrap a scalar environment with AutoResetWrapper to automatically reset on episode termination', 'split a random seed into n independent SeedSequences for parallel environment seeding', 'stack a list of tensors along dim 0 or convert a list to a single tensor', 'create a ConcatEnv that runs multiple environments in parallel and stacks their observations and rewards']
```

Usage

```
{'create_batched_auto_reset_env': 'create a batched auto-reset environment from an env factory function with a given seed and batch shape', 'wrap_env_with_auto_reset': 'wrap a scalar environment with AutoResetWrapper to automatically reset on episode termination', 'split_random_seed': 'split a random seed into n independent SeedSequences for parallel environment seeding', 'stack_tensors_or_as_tensor': 'stack a list of tensors along dim 0 or convert a list to a single tensor', 'create_concat_env': 'create a ConcatEnv that runs multiple environments in parallel and stacks their observations and rewards'}
```

