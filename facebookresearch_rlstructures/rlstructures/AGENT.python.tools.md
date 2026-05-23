# Agent Python Tools

- repo: facebookresearch/rlstructures
- repo_uri: https://github.com/facebookresearch/rlstructures

## File: facebookresearch_rlstructures/rlstructures/core.py

Prompts

```
['create a DictTensor from a dictionary of PyTorch tensors sharing the same batch dimension', 'create a TemporalDictTensor from a dictionary of BxT tensors with optional per-batch length tensor', 'use masked_tensor to combine two tensors elementwise using a binary mask tensor', 'use masked_dicttensor to combine two DictTensors elementwise using a binary mask tensor', 'create a Trajectories object pairing a DictTensor info with a TemporalDictTensor of trajectory data', 'review the VecEnv base class for vectorized RL environments and its abstract methods', 'implement the VecEnv step method to execute one timestep across all running environment instances', 'implement the VecEnv reset method to initialize environment instances with optional env_info DictTensor', 'implement the VecEnv close method to terminate all running environment instances', 'use the VecEnv n_envs method to get the number of environment instances in the batch']
```

Usage

```
{'create_DictTensor': 'create a DictTensor from a dictionary of PyTorch tensors sharing the same batch dimension', 'create_TemporalDictTensor': 'create a TemporalDictTensor from a dictionary of BxT tensors with optional per-batch length tensor', 'use_masked_tensor': 'use masked_tensor to combine two tensors elementwise using a binary mask tensor', 'use_masked_dicttensor': 'use masked_dicttensor to combine two DictTensors elementwise using a binary mask tensor', 'create_Trajectories': 'create a Trajectories object pairing a DictTensor info with a TemporalDictTensor of trajectory data'}
```

## File: facebookresearch_rlstructures/rlstructures/env.py

Prompts

```
['create a DictTensor from a dictionary of PyTorch tensors sharing the same batch dimension', 'create a TemporalDictTensor from a dictionary of BxT tensors with optional per-batch length tensor', 'use masked_tensor to combine two tensors elementwise using a binary mask tensor', 'use masked_dicttensor to combine two DictTensors elementwise using a binary mask tensor', 'create a Trajectories object pairing a DictTensor info with a TemporalDictTensor of trajectory data', 'review the VecEnv base class for vectorized RL environments and its abstract methods', 'implement the VecEnv step method to execute one timestep across all running environment instances', 'implement the VecEnv reset method to initialize environment instances with optional env_info DictTensor', 'implement the VecEnv close method to terminate all running environment instances', 'use the VecEnv n_envs method to get the number of environment instances in the batch']
```

Usage

```
{'review_VecEnv_class': 'review the VecEnv base class for vectorized RL environments and its abstract methods', 'implement_VecEnv_step': 'implement the VecEnv step method to execute one timestep across all running environment instances', 'implement_VecEnv_reset': 'implement the VecEnv reset method to initialize environment instances with optional env_info DictTensor', 'implement_VecEnv_close': 'implement the VecEnv close method to terminate all running environment instances', 'use_VecEnv_n_envs': 'use the VecEnv n_envs method to get the number of environment instances in the batch'}
```

