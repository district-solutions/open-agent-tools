# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/third_party/moolib/examples/atari/atari_preprocessing.py

Prompts

```
['create an AtariPreprocessing wrapper around a Gym Atari environment with frame skipping and grayscale', 'reset the AtariPreprocessing environment and return the initial preprocessed observation', 'step the AtariPreprocessing environment with an action and return pooled observation and reward', 'apply random no-ops at episode start to reduce determinism in Atari environments', 'review the AtariPreprocessing class for frame skipping, max pooling, and resizing logic', 'create an Atari gym environment with grayscale observations and frame stacking using config flags', 'create an Atari environment that applies random no-ops at the start of each episode', 'create an Atari environment with configurable sticky action probability for robust training', 'create an Atari environment with 4-frame stacking for temporal observation history', 'create an Atari environment with 84x84 grayscale preprocessing and frame skipping', 'create a Net model with configurable num_actions, input_channels, and optional LSTM for Atari reinforcement learning', 'run the Net forward pass with state, reward, prev_action inputs to get policy logits and baseline', 'create a Net model using create_model with a flags object specifying use_lstm and device', 'test the Net initial_state method to get zero-initialized LSTM hidden and cell states for a batch', 'review the Net forward method that processes Atari frames through residual conv layers and outputs actions']
```

Usage

```
{'create_atari_preprocessing': 'create an AtariPreprocessing wrapper around a Gym Atari environment with frame skipping and grayscale', 'reset_atari_environment': 'reset the AtariPreprocessing environment and return the initial preprocessed observation', 'step_atari_action': 'step the AtariPreprocessing environment with an action and return pooled observation and reward', 'apply_random_noops': 'apply random no-ops at episode start to reduce determinism in Atari environments', 'review_atari_preprocessing_class': 'review the AtariPreprocessing class for frame skipping, max pooling, and resizing logic'}
```

## File: facebookresearch_rlmeta/third_party/moolib/examples/atari/environment.py

Prompts

```
['create an AtariPreprocessing wrapper around a Gym Atari environment with frame skipping and grayscale', 'reset the AtariPreprocessing environment and return the initial preprocessed observation', 'step the AtariPreprocessing environment with an action and return pooled observation and reward', 'apply random no-ops at episode start to reduce determinism in Atari environments', 'review the AtariPreprocessing class for frame skipping, max pooling, and resizing logic', 'create an Atari gym environment with grayscale observations and frame stacking using config flags', 'create an Atari environment that applies random no-ops at the start of each episode', 'create an Atari environment with configurable sticky action probability for robust training', 'create an Atari environment with 4-frame stacking for temporal observation history', 'create an Atari environment with 84x84 grayscale preprocessing and frame skipping', 'create a Net model with configurable num_actions, input_channels, and optional LSTM for Atari reinforcement learning', 'run the Net forward pass with state, reward, prev_action inputs to get policy logits and baseline', 'create a Net model using create_model with a flags object specifying use_lstm and device', 'test the Net initial_state method to get zero-initialized LSTM hidden and cell states for a batch', 'review the Net forward method that processes Atari frames through residual conv layers and outputs actions']
```

Usage

```
{'create_atari_env': 'create an Atari gym environment with grayscale observations and frame stacking using config flags', 'create_env_with_noops': 'create an Atari environment that applies random no-ops at the start of each episode', 'create_env_with_sticky_actions': 'create an Atari environment with configurable sticky action probability for robust training', 'create_framestacked_env': 'create an Atari environment with 4-frame stacking for temporal observation history', 'create_preprocessed_atari_env': 'create an Atari environment with 84x84 grayscale preprocessing and frame skipping'}
```

## File: facebookresearch_rlmeta/third_party/moolib/examples/atari/models.py

Prompts

```
['create an AtariPreprocessing wrapper around a Gym Atari environment with frame skipping and grayscale', 'reset the AtariPreprocessing environment and return the initial preprocessed observation', 'step the AtariPreprocessing environment with an action and return pooled observation and reward', 'apply random no-ops at episode start to reduce determinism in Atari environments', 'review the AtariPreprocessing class for frame skipping, max pooling, and resizing logic', 'create an Atari gym environment with grayscale observations and frame stacking using config flags', 'create an Atari environment that applies random no-ops at the start of each episode', 'create an Atari environment with configurable sticky action probability for robust training', 'create an Atari environment with 4-frame stacking for temporal observation history', 'create an Atari environment with 84x84 grayscale preprocessing and frame skipping', 'create a Net model with configurable num_actions, input_channels, and optional LSTM for Atari reinforcement learning', 'run the Net forward pass with state, reward, prev_action inputs to get policy logits and baseline', 'create a Net model using create_model with a flags object specifying use_lstm and device', 'test the Net initial_state method to get zero-initialized LSTM hidden and cell states for a batch', 'review the Net forward method that processes Atari frames through residual conv layers and outputs actions']
```

Usage

```
{'create_Net_model': 'create a Net model with configurable num_actions, input_channels, and optional LSTM for Atari reinforcement learning', 'run_Net_forward': 'run the Net forward pass with state, reward, prev_action inputs to get policy logits and baseline', 'create_model_with_flags': 'create a Net model using create_model with a flags object specifying use_lstm and device', 'test_Net_initial_state': 'test the Net initial_state method to get zero-initialized LSTM hidden and cell states for a batch', 'review_Net_forward': 'review the Net forward method that processes Atari frames through residual conv layers and outputs actions'}
```

