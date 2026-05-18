# Agent Python Tools

- repo: facebookresearch/minihack
- repo_uri: https://github.com/facebookresearch/minihack

## File: facebookresearch_minihack/minihack/agent/rllib/envs.py

Prompts

```
['create an RLLibNLEEnv instance with a config dict containing observation keys and environment flags', 'reset the RLLibNLEEnv environment and return an OrderedDict of observations with sorted keys', 'step the RLLibNLEEnv environment with an action and return processed observations, reward, done, truncated, and info', 'access the observation_space property of RLLibNLEEnv to get the underlying gym environment observation space', 'close the RLLibNLEEnv environment and release underlying gym environment resources', 'build a Ray RLlib custom TorchModelV2 network wrapping BaseNet for NetHack observations', 'create a forward pass through BaseNet to process glyphs, blstats, and messages into state representations', 'test the Crop module to extract centered crops around x,y coordinates from glyph tensors', 'review the RLLibGlyphEmbedding class to understand glyph-to-idgroup mapping and input preparation', 'summarize the NetHackNet update_running_moments and get_running_std methods for online reward statistics', 'run the train function to start RLlib training with a specified algorithm and environment config', 'get the full environment config from a Hydra DictConfig with seedspath cleared', 'register the RLlibNLE-v0 environment with Ray Tune using the RLLibNLEEnv wrapper', 'merge Hydra config with RLlib algorithm-specific defaults using merge_dicts for PPO, DQN, A2C, or IMPALA', 'setup Weights and Biases logging callbacks with project, entity, group, and tags for training runs']
```

Usage

```
{'create_RLLibNLEEnv': 'create an RLLibNLEEnv instance with a config dict containing observation keys and environment flags', 'reset_RLLibNLEEnv': 'reset the RLLibNLEEnv environment and return an OrderedDict of observations with sorted keys', 'step_RLLibNLEEnv': 'step the RLLibNLEEnv environment with an action and return processed observations, reward, done, truncated, and info', 'access_observation_space_RLLibNLEEnv': 'access the observation_space property of RLLibNLEEnv to get the underlying gym environment observation space', 'close_RLLibNLEEnv': 'close the RLLibNLEEnv environment and release underlying gym environment resources'}
```

## File: facebookresearch_minihack/minihack/agent/rllib/models.py

Prompts

```
['create an RLLibNLEEnv instance with a config dict containing observation keys and environment flags', 'reset the RLLibNLEEnv environment and return an OrderedDict of observations with sorted keys', 'step the RLLibNLEEnv environment with an action and return processed observations, reward, done, truncated, and info', 'access the observation_space property of RLLibNLEEnv to get the underlying gym environment observation space', 'close the RLLibNLEEnv environment and release underlying gym environment resources', 'build a Ray RLlib custom TorchModelV2 network wrapping BaseNet for NetHack observations', 'create a forward pass through BaseNet to process glyphs, blstats, and messages into state representations', 'test the Crop module to extract centered crops around x,y coordinates from glyph tensors', 'review the RLLibGlyphEmbedding class to understand glyph-to-idgroup mapping and input preparation', 'summarize the NetHackNet update_running_moments and get_running_std methods for online reward statistics', 'run the train function to start RLlib training with a specified algorithm and environment config', 'get the full environment config from a Hydra DictConfig with seedspath cleared', 'register the RLlibNLE-v0 environment with Ray Tune using the RLLibNLEEnv wrapper', 'merge Hydra config with RLlib algorithm-specific defaults using merge_dicts for PPO, DQN, A2C, or IMPALA', 'setup Weights and Biases logging callbacks with project, entity, group, and tags for training runs']
```

Usage

```
{'build_rllib_nle_network': 'build a Ray RLlib custom TorchModelV2 network wrapping BaseNet for NetHack observations', 'create_base_net_forward': 'create a forward pass through BaseNet to process glyphs, blstats, and messages into state representations', 'test_crop_module': 'test the Crop module to extract centered crops around x,y coordinates from glyph tensors', 'review_rllib_glyph_embedding': 'review the RLLibGlyphEmbedding class to understand glyph-to-idgroup mapping and input preparation', 'summarize_nethacknet_reward_stats': 'summarize the NetHackNet update_running_moments and get_running_std methods for online reward statistics'}
```

## File: facebookresearch_minihack/minihack/agent/rllib/train.py

Prompts

```
['create an RLLibNLEEnv instance with a config dict containing observation keys and environment flags', 'reset the RLLibNLEEnv environment and return an OrderedDict of observations with sorted keys', 'step the RLLibNLEEnv environment with an action and return processed observations, reward, done, truncated, and info', 'access the observation_space property of RLLibNLEEnv to get the underlying gym environment observation space', 'close the RLLibNLEEnv environment and release underlying gym environment resources', 'build a Ray RLlib custom TorchModelV2 network wrapping BaseNet for NetHack observations', 'create a forward pass through BaseNet to process glyphs, blstats, and messages into state representations', 'test the Crop module to extract centered crops around x,y coordinates from glyph tensors', 'review the RLLibGlyphEmbedding class to understand glyph-to-idgroup mapping and input preparation', 'summarize the NetHackNet update_running_moments and get_running_std methods for online reward statistics', 'run the train function to start RLlib training with a specified algorithm and environment config', 'get the full environment config from a Hydra DictConfig with seedspath cleared', 'register the RLlibNLE-v0 environment with Ray Tune using the RLLibNLEEnv wrapper', 'merge Hydra config with RLlib algorithm-specific defaults using merge_dicts for PPO, DQN, A2C, or IMPALA', 'setup Weights and Biases logging callbacks with project, entity, group, and tags for training runs']
```

Usage

```
{'run_rl_training': 'run the train function to start RLlib training with a specified algorithm and environment config', 'get_full_config': 'get the full environment config from a Hydra DictConfig with seedspath cleared', 'register_rl_env': 'register the RLlibNLE-v0 environment with Ray Tune using the RLLibNLEEnv wrapper', 'merge_algo_config': 'merge Hydra config with RLlib algorithm-specific defaults using merge_dicts for PPO, DQN, A2C, or IMPALA', 'setup_wandb_logging': 'setup Weights and Biases logging callbacks with project, entity, group, and tags for training runs'}
```

