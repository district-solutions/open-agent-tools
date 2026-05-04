# Agent Python Tools

- repo: facebookresearch/benchmarl
- repo_uri: https://github.com/facebookresearch/benchmarl

## File: facebookresearch_benchmarl/benchmarl/environments/meltingpot/common.py

Prompts

```
['create a MeltingpotEnv with a given substrate name, categorical actions, and device using MeltingPotClass get_env_fun', 'get a list of TorchRL transforms including DoubleToFloat and FlattenObservation for INTERACTION_INVENTORIES keys', 'get DTypeCastTransform for RGB observation keys to cast uint8 to float for replay buffer storage', 'get the observation spec filtered to only include group keys present in the environment group map', 'get the global state spec containing only the RGB key from the environment observation spec']
```

Usage

```
{'create_meltingpot_env': 'create a MeltingpotEnv with a given substrate name, categorical actions, and device using MeltingPotClass get_env_fun', 'get_env_transforms': 'get a list of TorchRL transforms including DoubleToFloat and FlattenObservation for INTERACTION_INVENTORIES keys', 'get_replay_buffer_transforms': 'get DTypeCastTransform for RGB observation keys to cast uint8 to float for replay buffer storage', 'get_observation_spec': 'get the observation spec filtered to only include group keys present in the environment group map', 'get_state_spec': 'get the global state spec containing only the RGB key from the environment observation spec'}
```

