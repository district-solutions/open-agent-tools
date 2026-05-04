# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/mj_envs/mj_envs/envs/arms/push_base_v0.py

Prompts

```
['create a PushBaseV0 environment instance by providing a MuJoCo model path and site configuration kwargs', 'configure the PushBaseV0 environment with robot, object, and target site names plus xyz range parameters', 'get the observation dictionary containing joint positions, velocities, object error, and target error from the simulator', 'compute the reward dictionary with object distance, target distance, bonus, penalty, and dense reward values', 'reset the PushBaseV0 environment by randomizing the target position within the configured xyz range bounds', 'create a ReachBaseV0 MuJoCo environment by passing a model path and site names to the constructor', 'build a ReachBaseV0 environment setup with robot site name, target site name, and target xyz range parameters', 'run get_obs_dict on a ReachBaseV0 environment to extract joint positions, velocities, and reach error from the simulator', 'summarize the reward dictionary from ReachBaseV0 to compute reach distance, bonus, penalty, and dense reward values', 'test resetting a ReachBaseV0 environment to randomize the target site position within the configured xyz range']
```

Usage

```
{'init_PushBaseV0': 'create a PushBaseV0 environment instance by providing a MuJoCo model path and site configuration kwargs', 'setup_PushBaseV0': 'configure the PushBaseV0 environment with robot, object, and target site names plus xyz range parameters', 'get_obs_dict_PushBaseV0': 'get the observation dictionary containing joint positions, velocities, object error, and target error from the simulator', 'get_reward_dict_PushBaseV0': 'compute the reward dictionary with object distance, target distance, bonus, penalty, and dense reward values', 'reset_PushBaseV0': 'reset the PushBaseV0 environment by randomizing the target position within the configured xyz range bounds'}
```

## File: facebookresearch_eai-vc/third_party/mj_envs/mj_envs/envs/arms/reach_base_v0.py

Prompts

```
['create a PushBaseV0 environment instance by providing a MuJoCo model path and site configuration kwargs', 'configure the PushBaseV0 environment with robot, object, and target site names plus xyz range parameters', 'get the observation dictionary containing joint positions, velocities, object error, and target error from the simulator', 'compute the reward dictionary with object distance, target distance, bonus, penalty, and dense reward values', 'reset the PushBaseV0 environment by randomizing the target position within the configured xyz range bounds', 'create a ReachBaseV0 MuJoCo environment by passing a model path and site names to the constructor', 'build a ReachBaseV0 environment setup with robot site name, target site name, and target xyz range parameters', 'run get_obs_dict on a ReachBaseV0 environment to extract joint positions, velocities, and reach error from the simulator', 'summarize the reward dictionary from ReachBaseV0 to compute reach distance, bonus, penalty, and dense reward values', 'test resetting a ReachBaseV0 environment to randomize the target site position within the configured xyz range']
```

Usage

```
{'init_reach_base_env': 'create a ReachBaseV0 MuJoCo environment by passing a model path and site names to the constructor', 'setup_reach_base_env': 'build a ReachBaseV0 environment setup with robot site name, target site name, and target xyz range parameters', 'get_obs_dict': 'run get_obs_dict on a ReachBaseV0 environment to extract joint positions, velocities, and reach error from the simulator', 'get_reward_dict': 'summarize the reward dictionary from ReachBaseV0 to compute reach distance, bonus, penalty, and dense reward values', 'reset_reach_base_env': 'test resetting a ReachBaseV0 environment to randomize the target site position within the configured xyz range'}
```

