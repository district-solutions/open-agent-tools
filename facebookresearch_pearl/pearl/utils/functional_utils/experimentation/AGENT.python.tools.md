# Agent Python Tools

- repo: facebookresearch/pearl
- repo_uri: https://github.com/facebookresearch/pearl

## File: facebookresearch_pearl/pearl/utils/functional_utils/experimentation/create_offline_data.py

Prompts

```
['create offline RL transition data by running a PearlAgent in an environment and saving tuples to a .pt file', "create offline data with a PearlAgent while running evaluation episodes to measure the agent's final policy performance", 'get episode returns of a data collection agent by loading a pre-saved pickle file of returns', 'get episode returns by stitching trajectories from raw transition tuples stored in a PyTorch .pt file', 'review the create_offline_data function to understand how transition tuples are collected, saved, and evaluated', 'build a python module to compute dynamic font sizes for strings based on max character constraints', 'create a function that calculates appropriate font size for a given string length and maximum constraints', 'test the fontsize_for function with various string lengths and maximum font size parameters', 'refactor the fontsize_for function to support additional font scaling strategies beyond character count', 'review the fontsize_for function to ensure correct font size calculation for plot titles', 'run set_seed with an integer to make PyTorch and Python random operations reproducible', 'test set_seed by calling it with a fixed seed and verifying deterministic tensor outputs', 'review set_seed to confirm it sets seeds for random, torch, and CUDA backends', 'refactor set_seed to optionally skip CUDA seeding when no GPU is available', 'summarize set_seed which seeds Python random, torch CPU, torch CUDA, and disables cuDNN benchmark']
```

Usage

```
{'create_offline_rl_dataset': 'create offline RL transition data by running a PearlAgent in an environment and saving tuples to a .pt file', 'create_offline_data_with_evaluation': "create offline data with a PearlAgent while running evaluation episodes to measure the agent's final policy performance", 'get_data_collection_returns_from_file': 'get episode returns of a data collection agent by loading a pre-saved pickle file of returns', 'get_data_collection_returns_from_transitions': 'get episode returns by stitching trajectories from raw transition tuples stored in a PyTorch .pt file', 'review_create_offline_data_function': 'review the create_offline_data function to understand how transition tuples are collected, saved, and evaluated'}
```

## File: facebookresearch_pearl/pearl/utils/functional_utils/experimentation/plots.py

Prompts

```
['create offline RL transition data by running a PearlAgent in an environment and saving tuples to a .pt file', "create offline data with a PearlAgent while running evaluation episodes to measure the agent's final policy performance", 'get episode returns of a data collection agent by loading a pre-saved pickle file of returns', 'get episode returns by stitching trajectories from raw transition tuples stored in a PyTorch .pt file', 'review the create_offline_data function to understand how transition tuples are collected, saved, and evaluated', 'build a python module to compute dynamic font sizes for strings based on max character constraints', 'create a function that calculates appropriate font size for a given string length and maximum constraints', 'test the fontsize_for function with various string lengths and maximum font size parameters', 'refactor the fontsize_for function to support additional font scaling strategies beyond character count', 'review the fontsize_for function to ensure correct font size calculation for plot titles', 'run set_seed with an integer to make PyTorch and Python random operations reproducible', 'test set_seed by calling it with a fixed seed and verifying deterministic tensor outputs', 'review set_seed to confirm it sets seeds for random, torch, and CUDA backends', 'refactor set_seed to optionally skip CUDA seeding when no GPU is available', 'summarize set_seed which seeds Python random, torch CPU, torch CUDA, and disables cuDNN benchmark']
```

Usage

```
{'build_fontsize_calculator': 'build a python module to compute dynamic font sizes for strings based on max character constraints', 'create_fontsize_for_function': 'create a function that calculates appropriate font size for a given string length and maximum constraints', 'test_fontsize_for': 'test the fontsize_for function with various string lengths and maximum font size parameters', 'refactor_fontsize_for': 'refactor the fontsize_for function to support additional font scaling strategies beyond character count', 'review_fontsize_for': 'review the fontsize_for function to ensure correct font size calculation for plot titles'}
```

## File: facebookresearch_pearl/pearl/utils/functional_utils/experimentation/set_seed.py

Prompts

```
['create offline RL transition data by running a PearlAgent in an environment and saving tuples to a .pt file', "create offline data with a PearlAgent while running evaluation episodes to measure the agent's final policy performance", 'get episode returns of a data collection agent by loading a pre-saved pickle file of returns', 'get episode returns by stitching trajectories from raw transition tuples stored in a PyTorch .pt file', 'review the create_offline_data function to understand how transition tuples are collected, saved, and evaluated', 'build a python module to compute dynamic font sizes for strings based on max character constraints', 'create a function that calculates appropriate font size for a given string length and maximum constraints', 'test the fontsize_for function with various string lengths and maximum font size parameters', 'refactor the fontsize_for function to support additional font scaling strategies beyond character count', 'review the fontsize_for function to ensure correct font size calculation for plot titles', 'run set_seed with an integer to make PyTorch and Python random operations reproducible', 'test set_seed by calling it with a fixed seed and verifying deterministic tensor outputs', 'review set_seed to confirm it sets seeds for random, torch, and CUDA backends', 'refactor set_seed to optionally skip CUDA seeding when no GPU is available', 'summarize set_seed which seeds Python random, torch CPU, torch CUDA, and disables cuDNN benchmark']
```

Usage

```
{'run_set_seed': 'run set_seed with an integer to make PyTorch and Python random operations reproducible', 'test_set_seed': 'test set_seed by calling it with a fixed seed and verifying deterministic tensor outputs', 'review_set_seed': 'review set_seed to confirm it sets seeds for random, torch, and CUDA backends', 'refactor_set_seed': 'refactor set_seed to optionally skip CUDA seeding when no GPU is available', 'summarize_set_seed': 'summarize set_seed which seeds Python random, torch CPU, torch CUDA, and disables cuDNN benchmark'}
```

