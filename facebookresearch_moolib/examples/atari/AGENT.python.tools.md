# Agent Python Tools

- repo: facebookresearch/moolib
- repo_uri: https://github.com/facebookresearch/moolib

## File: facebookresearch_moolib/examples/atari/atari_preprocessing.py

Prompts

```
['create an AtariPreprocessing wrapper around a Gym Atari environment with frame skipping and grayscale', 'reset the Atari environment with random no-ops applied before the first observation', 'step the Atari environment with frame skipping, max pooling, and reward accumulation', 'fetch a grayscale screen observation directly from the ALE into a numpy buffer', 'pool two grayscale frames via max pooling and resize to 84x84 for DQN input', 'create a Gym Atari environment with grayscale observations and action repeat flags', 'create an Atari environment that applies random no-ops at the start of episodes', 'create an Atari environment wrapped with 4-frame stacking for temporal context', 'create an Atari environment with configurable sticky action probability for robustness', 'create an Atari environment with 84x84 screen resizing and terminal on life loss disabled', 'create a Net model with configurable num_actions, input_channels, and optional LSTM for Atari RL', 'run the Net forward pass with state, reward, prev_action inputs to get policy logits and actions', 'create a Net model from flags object with use_lstm setting and move to specified device', 'review the Net initial_state method that returns LSTM hidden and cell states for batch inference', 'test the Net resnet1 and resnet2 residual blocks with feature convolutions for Atari image processing']
```

Usage

```
{'create_atari_preprocessing_wrapper': 'create an AtariPreprocessing wrapper around a Gym Atari environment with frame skipping and grayscale', 'reset_atari_environment_with_noops': 'reset the Atari environment with random no-ops applied before the first observation', 'step_atari_with_frame_skip': 'step the Atari environment with frame skipping, max pooling, and reward accumulation', 'fetch_grayscale_observation': 'fetch a grayscale screen observation directly from the ALE into a numpy buffer', 'pool_and_resize_frames': 'pool two grayscale frames via max pooling and resize to 84x84 for DQN input'}
```

## File: facebookresearch_moolib/examples/atari/environment.py

Prompts

```
['create an AtariPreprocessing wrapper around a Gym Atari environment with frame skipping and grayscale', 'reset the Atari environment with random no-ops applied before the first observation', 'step the Atari environment with frame skipping, max pooling, and reward accumulation', 'fetch a grayscale screen observation directly from the ALE into a numpy buffer', 'pool two grayscale frames via max pooling and resize to 84x84 for DQN input', 'create a Gym Atari environment with grayscale observations and action repeat flags', 'create an Atari environment that applies random no-ops at the start of episodes', 'create an Atari environment wrapped with 4-frame stacking for temporal context', 'create an Atari environment with configurable sticky action probability for robustness', 'create an Atari environment with 84x84 screen resizing and terminal on life loss disabled', 'create a Net model with configurable num_actions, input_channels, and optional LSTM for Atari RL', 'run the Net forward pass with state, reward, prev_action inputs to get policy logits and actions', 'create a Net model from flags object with use_lstm setting and move to specified device', 'review the Net initial_state method that returns LSTM hidden and cell states for batch inference', 'test the Net resnet1 and resnet2 residual blocks with feature convolutions for Atari image processing']
```

Usage

```
{'create_atari_env': 'create a Gym Atari environment with grayscale observations and action repeat flags', 'create_env_with_noops': 'create an Atari environment that applies random no-ops at the start of episodes', 'create_framestacked_env': 'create an Atari environment wrapped with 4-frame stacking for temporal context', 'create_env_with_sticky_actions': 'create an Atari environment with configurable sticky action probability for robustness', 'create_env_with_preprocessing': 'create an Atari environment with 84x84 screen resizing and terminal on life loss disabled'}
```

## File: facebookresearch_moolib/examples/atari/models.py

Prompts

```
['create an AtariPreprocessing wrapper around a Gym Atari environment with frame skipping and grayscale', 'reset the Atari environment with random no-ops applied before the first observation', 'step the Atari environment with frame skipping, max pooling, and reward accumulation', 'fetch a grayscale screen observation directly from the ALE into a numpy buffer', 'pool two grayscale frames via max pooling and resize to 84x84 for DQN input', 'create a Gym Atari environment with grayscale observations and action repeat flags', 'create an Atari environment that applies random no-ops at the start of episodes', 'create an Atari environment wrapped with 4-frame stacking for temporal context', 'create an Atari environment with configurable sticky action probability for robustness', 'create an Atari environment with 84x84 screen resizing and terminal on life loss disabled', 'create a Net model with configurable num_actions, input_channels, and optional LSTM for Atari RL', 'run the Net forward pass with state, reward, prev_action inputs to get policy logits and actions', 'create a Net model from flags object with use_lstm setting and move to specified device', 'review the Net initial_state method that returns LSTM hidden and cell states for batch inference', 'test the Net resnet1 and resnet2 residual blocks with feature convolutions for Atari image processing']
```

Usage

```
{'create_Net_model': 'create a Net model with configurable num_actions, input_channels, and optional LSTM for Atari RL', 'run_Net_forward': 'run the Net forward pass with state, reward, prev_action inputs to get policy logits and actions', 'create_model_from_flags': 'create a Net model from flags object with use_lstm setting and move to specified device', 'review_Net_initial_state': 'review the Net initial_state method that returns LSTM hidden and cell states for batch inference', 'test_Net_resnet_blocks': 'test the Net resnet1 and resnet2 residual blocks with feature convolutions for Atari image processing'}
```

