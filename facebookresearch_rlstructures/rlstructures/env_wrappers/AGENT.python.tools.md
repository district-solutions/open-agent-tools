# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/rlstructures/env_wrappers/devicewrapper.py

Prompts

```
['create a DeviceEnv wrapper to move environment observations between CPU and GPU devices', 'reset the DeviceEnv wrapper and move observations to the target device', 'step the DeviceEnv wrapper by moving policy output to the from_device and results to the to_device', 'close the DeviceEnv wrapper and delegate cleanup to the underlying environment', 'get the number of parallel environments from the DeviceEnv wrapper', 'create a GymEnv wrapper to wrap a list of gym environments with a shared seed', 'reset all gym environments in the GymEnv wrapper and return initial frames and running env indices', 'step all running gym environments with policy output actions and return observations and rewards', 'create a GymEnvInf wrapper that automatically resets each environment instance when it stops', 'format a gym observation frame into a PyTorch tensor supporting dict, list, numpy, and LazyFrame types']
```

Usage

```
{'create_DeviceEnv_wrapper': 'create a DeviceEnv wrapper to move environment observations between CPU and GPU devices', 'reset_DeviceEnv': 'reset the DeviceEnv wrapper and move observations to the target device', 'step_DeviceEnv': 'step the DeviceEnv wrapper by moving policy output to the from_device and results to the to_device', 'close_DeviceEnv': 'close the DeviceEnv wrapper and delegate cleanup to the underlying environment', 'n_envs_DeviceEnv': 'get the number of parallel environments from the DeviceEnv wrapper'}
```

## File: facebookresearch_rlstructures/rlstructures/env_wrappers/gymenv.py

Prompts

```
['create a DeviceEnv wrapper to move environment observations between CPU and GPU devices', 'reset the DeviceEnv wrapper and move observations to the target device', 'step the DeviceEnv wrapper by moving policy output to the from_device and results to the to_device', 'close the DeviceEnv wrapper and delegate cleanup to the underlying environment', 'get the number of parallel environments from the DeviceEnv wrapper', 'create a GymEnv wrapper to wrap a list of gym environments with a shared seed', 'reset all gym environments in the GymEnv wrapper and return initial frames and running env indices', 'step all running gym environments with policy output actions and return observations and rewards', 'create a GymEnvInf wrapper that automatically resets each environment instance when it stops', 'format a gym observation frame into a PyTorch tensor supporting dict, list, numpy, and LazyFrame types']
```

Usage

```
{'create_GymEnv_wrapper': 'create a GymEnv wrapper to wrap a list of gym environments with a shared seed', 'reset_GymEnv': 'reset all gym environments in the GymEnv wrapper and return initial frames and running env indices', 'step_GymEnv': 'step all running gym environments with policy output actions and return observations and rewards', 'create_GymEnvInf_wrapper': 'create a GymEnvInf wrapper that automatically resets each environment instance when it stops', 'format_frame_observation': 'format a gym observation frame into a PyTorch tensor supporting dict, list, numpy, and LazyFrame types'}
```

