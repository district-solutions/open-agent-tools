# Agent Python Tools

- repo: facebookresearch/habitat-lab
- repo_uri: https://github.com/facebookresearch/habitat-lab

## File: facebookresearch_habitat-lab/habitat-lab/habitat/gym/gym_definitions.py

Prompts

```
['create a gym environment from a habitat-lab or habitat-baseline DictConfig object', 'create a gym environment from a config YAML file path with optional overrides and render mode', 'add a third-person RGB sensor to the default agent in a habitat simulator config', 'extract the env_task name from a habitat-lab or habitat-baseline DictConfig', 'register a gym environment with an entry point and kwargs only if it is not already registered', 'build a python module that wraps a gym environment with EnvCountEpisodeWrapper to count episodes', 'create an EnvCountEpisodeWrapper instance to track the number of episodes in a habitat gym environment', 'test the EnvCountEpisodeWrapper step method to verify episode count increments on done signals', 'review the EnvCountEpisodeWrapper current_episode property to understand how it returns the active episode', 'refactor the EnvCountEpisodeWrapper reset method to customize episode counting behavior on environment reset', 'build a python module that wraps a gym environment to ensure its observation space is a dictionary', "create an EnvObsDictWrapper that converts a Box observation space into a Dict space with key 'obs'", 'test the EnvObsDictWrapper step method to verify observations are wrapped in a dictionary when needed', 'test the EnvObsDictWrapper reset method to verify observations are wrapped in a dictionary when needed', 'review the EnvObsDictWrapper class and its handling of Box versus Dict observation spaces', 'wrap a Habitat RLEnv with HabGymWrapper to expose a standard OpenAI Gym interface', 'create a gym Box or Discrete action space from a Habitat task action space using create_action_space', 'convert a numpy array continuous action vector into a Habitat-compatible action dictionary', 'filter a Habitat observation space to include only specified keys using filter_observation_space', 'render the wrapped Habitat environment as an RGB array or human display using HabGymWrapper render']
```

Usage

```
{'make_gym_from_config': 'create a gym environment from a habitat-lab or habitat-baseline DictConfig object', '_make_habitat_gym_env': 'create a gym environment from a config YAML file path with optional overrides and render mode', '_add_sim_sensor_to_config': 'add a third-person RGB sensor to the default agent in a habitat simulator config', '_get_env_name': 'extract the env_task name from a habitat-lab or habitat-baseline DictConfig', '_try_register': 'register a gym environment with an entry point and kwargs only if it is not already registered'}
```

## File: facebookresearch_habitat-lab/habitat-lab/habitat/gym/gym_env_episode_count_wrapper.py

Prompts

```
['create a gym environment from a habitat-lab or habitat-baseline DictConfig object', 'create a gym environment from a config YAML file path with optional overrides and render mode', 'add a third-person RGB sensor to the default agent in a habitat simulator config', 'extract the env_task name from a habitat-lab or habitat-baseline DictConfig', 'register a gym environment with an entry point and kwargs only if it is not already registered', 'build a python module that wraps a gym environment with EnvCountEpisodeWrapper to count episodes', 'create an EnvCountEpisodeWrapper instance to track the number of episodes in a habitat gym environment', 'test the EnvCountEpisodeWrapper step method to verify episode count increments on done signals', 'review the EnvCountEpisodeWrapper current_episode property to understand how it returns the active episode', 'refactor the EnvCountEpisodeWrapper reset method to customize episode counting behavior on environment reset', 'build a python module that wraps a gym environment to ensure its observation space is a dictionary', "create an EnvObsDictWrapper that converts a Box observation space into a Dict space with key 'obs'", 'test the EnvObsDictWrapper step method to verify observations are wrapped in a dictionary when needed', 'test the EnvObsDictWrapper reset method to verify observations are wrapped in a dictionary when needed', 'review the EnvObsDictWrapper class and its handling of Box versus Dict observation spaces', 'wrap a Habitat RLEnv with HabGymWrapper to expose a standard OpenAI Gym interface', 'create a gym Box or Discrete action space from a Habitat task action space using create_action_space', 'convert a numpy array continuous action vector into a Habitat-compatible action dictionary', 'filter a Habitat observation space to include only specified keys using filter_observation_space', 'render the wrapped Habitat environment as an RGB array or human display using HabGymWrapper render']
```

Usage

```
{'build_env_count_wrapper': 'build a python module that wraps a gym environment with EnvCountEpisodeWrapper to count episodes', 'create_episode_counter': 'create an EnvCountEpisodeWrapper instance to track the number of episodes in a habitat gym environment', 'test_step_episode_count': 'test the EnvCountEpisodeWrapper step method to verify episode count increments on done signals', 'review_current_episode_property': 'review the EnvCountEpisodeWrapper current_episode property to understand how it returns the active episode', 'refactor_reset_counter': 'refactor the EnvCountEpisodeWrapper reset method to customize episode counting behavior on environment reset'}
```

## File: facebookresearch_habitat-lab/habitat-lab/habitat/gym/gym_env_obs_dict_wrapper.py

Prompts

```
['create a gym environment from a habitat-lab or habitat-baseline DictConfig object', 'create a gym environment from a config YAML file path with optional overrides and render mode', 'add a third-person RGB sensor to the default agent in a habitat simulator config', 'extract the env_task name from a habitat-lab or habitat-baseline DictConfig', 'register a gym environment with an entry point and kwargs only if it is not already registered', 'build a python module that wraps a gym environment with EnvCountEpisodeWrapper to count episodes', 'create an EnvCountEpisodeWrapper instance to track the number of episodes in a habitat gym environment', 'test the EnvCountEpisodeWrapper step method to verify episode count increments on done signals', 'review the EnvCountEpisodeWrapper current_episode property to understand how it returns the active episode', 'refactor the EnvCountEpisodeWrapper reset method to customize episode counting behavior on environment reset', 'build a python module that wraps a gym environment to ensure its observation space is a dictionary', "create an EnvObsDictWrapper that converts a Box observation space into a Dict space with key 'obs'", 'test the EnvObsDictWrapper step method to verify observations are wrapped in a dictionary when needed', 'test the EnvObsDictWrapper reset method to verify observations are wrapped in a dictionary when needed', 'review the EnvObsDictWrapper class and its handling of Box versus Dict observation spaces', 'wrap a Habitat RLEnv with HabGymWrapper to expose a standard OpenAI Gym interface', 'create a gym Box or Discrete action space from a Habitat task action space using create_action_space', 'convert a numpy array continuous action vector into a Habitat-compatible action dictionary', 'filter a Habitat observation space to include only specified keys using filter_observation_space', 'render the wrapped Habitat environment as an RGB array or human display using HabGymWrapper render']
```

Usage

```
{'build_env_obs_dict_wrapper': 'build a python module that wraps a gym environment to ensure its observation space is a dictionary', 'create_wrapper_for_box_space': "create an EnvObsDictWrapper that converts a Box observation space into a Dict space with key 'obs'", 'test_step_observation_wrapping': 'test the EnvObsDictWrapper step method to verify observations are wrapped in a dictionary when needed', 'test_reset_observation_wrapping': 'test the EnvObsDictWrapper reset method to verify observations are wrapped in a dictionary when needed', 'review_env_obs_dict_wrapper_class': 'review the EnvObsDictWrapper class and its handling of Box versus Dict observation spaces'}
```

## File: facebookresearch_habitat-lab/habitat-lab/habitat/gym/gym_wrapper.py

Prompts

```
['create a gym environment from a habitat-lab or habitat-baseline DictConfig object', 'create a gym environment from a config YAML file path with optional overrides and render mode', 'add a third-person RGB sensor to the default agent in a habitat simulator config', 'extract the env_task name from a habitat-lab or habitat-baseline DictConfig', 'register a gym environment with an entry point and kwargs only if it is not already registered', 'build a python module that wraps a gym environment with EnvCountEpisodeWrapper to count episodes', 'create an EnvCountEpisodeWrapper instance to track the number of episodes in a habitat gym environment', 'test the EnvCountEpisodeWrapper step method to verify episode count increments on done signals', 'review the EnvCountEpisodeWrapper current_episode property to understand how it returns the active episode', 'refactor the EnvCountEpisodeWrapper reset method to customize episode counting behavior on environment reset', 'build a python module that wraps a gym environment to ensure its observation space is a dictionary', "create an EnvObsDictWrapper that converts a Box observation space into a Dict space with key 'obs'", 'test the EnvObsDictWrapper step method to verify observations are wrapped in a dictionary when needed', 'test the EnvObsDictWrapper reset method to verify observations are wrapped in a dictionary when needed', 'review the EnvObsDictWrapper class and its handling of Box versus Dict observation spaces', 'wrap a Habitat RLEnv with HabGymWrapper to expose a standard OpenAI Gym interface', 'create a gym Box or Discrete action space from a Habitat task action space using create_action_space', 'convert a numpy array continuous action vector into a Habitat-compatible action dictionary', 'filter a Habitat observation space to include only specified keys using filter_observation_space', 'render the wrapped Habitat environment as an RGB array or human display using HabGymWrapper render']
```

Usage

```
{'wrap_habitat_env_in_gym': 'wrap a Habitat RLEnv with HabGymWrapper to expose a standard OpenAI Gym interface', 'create_action_space_from_habitat': 'create a gym Box or Discrete action space from a Habitat task action space using create_action_space', 'convert_continuous_action_to_habitat_dict': 'convert a numpy array continuous action vector into a Habitat-compatible action dictionary', 'filter_observation_space_by_keys': 'filter a Habitat observation space to include only specified keys using filter_observation_space', 'render_habitat_env_as_rgb_array': 'render the wrapped Habitat environment as an RGB array or human display using HabGymWrapper render'}
```

