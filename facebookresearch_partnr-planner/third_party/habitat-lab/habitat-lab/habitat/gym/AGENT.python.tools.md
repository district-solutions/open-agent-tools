# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/gym/gym_definitions.py

Prompts

```
['create a gym environment from a habitat-lab or habitat-baseline DictConfig object', 'build a gym environment from a habitat config YAML file path with optional overrides', 'add a third-person RGB sensor to the default agent in a habitat simulator config', 'register a new gym environment with an entry point and kwargs if not already registered', 'extract the env_task name from a habitat-lab or habitat-baseline DictConfig', 'build a python module to wrap a gym environment with EnvCountEpisodeWrapper to count episodes', 'create an EnvCountEpisodeWrapper instance wrapping a habitat gym environment to track episode counts', 'test the EnvCountEpisodeWrapper step method to verify episode counter increments on done', 'test the EnvCountEpisodeWrapper reset method to verify episode counter increments on reset', 'review the EnvCountEpisodeWrapper number_of_episodes property to understand fallback behavior when env lacks it', 'build a python module that wraps a gym environment to ensure its observation space is a dictionary', 'create an EnvObsDictWrapper instance that wraps a gym environment and converts Box observation spaces to Dict', 'test the EnvObsDictWrapper step method to verify it wraps observations into a dictionary when needed', 'test the EnvObsDictWrapper reset method to verify it returns dictionary-wrapped observations on environment reset', 'review the EnvObsDictWrapper class and its approach to wrapping Box observation spaces into Dict spaces', 'wrap a Habitat RLEnv with HabGymWrapper to expose a standard OpenAI Gym interface with Box or Discrete action spaces', 'create a gym Box or Discrete action space from a Habitat task action space using create_action_space', 'convert a numpy array continuous action vector into a Habitat-compatible action dictionary using continuous_vector_action_to_hab_dict', 'filter a Habitat observation space to only include specified keys using filter_observation_space', 'render the wrapped Habitat environment as an RGB array or human display using HabGymWrapper render method']
```

Usage

```
{'make_gym_from_config': 'create a gym environment from a habitat-lab or habitat-baseline DictConfig object', '_make_habitat_gym_env': 'build a gym environment from a habitat config YAML file path with optional overrides', '_add_sim_sensor_to_config': 'add a third-person RGB sensor to the default agent in a habitat simulator config', '_try_register': 'register a new gym environment with an entry point and kwargs if not already registered', '_get_env_name': 'extract the env_task name from a habitat-lab or habitat-baseline DictConfig'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/gym/gym_env_episode_count_wrapper.py

Prompts

```
['create a gym environment from a habitat-lab or habitat-baseline DictConfig object', 'build a gym environment from a habitat config YAML file path with optional overrides', 'add a third-person RGB sensor to the default agent in a habitat simulator config', 'register a new gym environment with an entry point and kwargs if not already registered', 'extract the env_task name from a habitat-lab or habitat-baseline DictConfig', 'build a python module to wrap a gym environment with EnvCountEpisodeWrapper to count episodes', 'create an EnvCountEpisodeWrapper instance wrapping a habitat gym environment to track episode counts', 'test the EnvCountEpisodeWrapper step method to verify episode counter increments on done', 'test the EnvCountEpisodeWrapper reset method to verify episode counter increments on reset', 'review the EnvCountEpisodeWrapper number_of_episodes property to understand fallback behavior when env lacks it', 'build a python module that wraps a gym environment to ensure its observation space is a dictionary', 'create an EnvObsDictWrapper instance that wraps a gym environment and converts Box observation spaces to Dict', 'test the EnvObsDictWrapper step method to verify it wraps observations into a dictionary when needed', 'test the EnvObsDictWrapper reset method to verify it returns dictionary-wrapped observations on environment reset', 'review the EnvObsDictWrapper class and its approach to wrapping Box observation spaces into Dict spaces', 'wrap a Habitat RLEnv with HabGymWrapper to expose a standard OpenAI Gym interface with Box or Discrete action spaces', 'create a gym Box or Discrete action space from a Habitat task action space using create_action_space', 'convert a numpy array continuous action vector into a Habitat-compatible action dictionary using continuous_vector_action_to_hab_dict', 'filter a Habitat observation space to only include specified keys using filter_observation_space', 'render the wrapped Habitat environment as an RGB array or human display using HabGymWrapper render method']
```

Usage

```
{'build_env_episode_wrapper': 'build a python module to wrap a gym environment with EnvCountEpisodeWrapper to count episodes', 'create_episode_counter': 'create an EnvCountEpisodeWrapper instance wrapping a habitat gym environment to track episode counts', 'test_step_episode_count': 'test the EnvCountEpisodeWrapper step method to verify episode counter increments on done', 'test_reset_episode_count': 'test the EnvCountEpisodeWrapper reset method to verify episode counter increments on reset', 'review_number_of_episodes_property': 'review the EnvCountEpisodeWrapper number_of_episodes property to understand fallback behavior when env lacks it'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/gym/gym_env_obs_dict_wrapper.py

Prompts

```
['create a gym environment from a habitat-lab or habitat-baseline DictConfig object', 'build a gym environment from a habitat config YAML file path with optional overrides', 'add a third-person RGB sensor to the default agent in a habitat simulator config', 'register a new gym environment with an entry point and kwargs if not already registered', 'extract the env_task name from a habitat-lab or habitat-baseline DictConfig', 'build a python module to wrap a gym environment with EnvCountEpisodeWrapper to count episodes', 'create an EnvCountEpisodeWrapper instance wrapping a habitat gym environment to track episode counts', 'test the EnvCountEpisodeWrapper step method to verify episode counter increments on done', 'test the EnvCountEpisodeWrapper reset method to verify episode counter increments on reset', 'review the EnvCountEpisodeWrapper number_of_episodes property to understand fallback behavior when env lacks it', 'build a python module that wraps a gym environment to ensure its observation space is a dictionary', 'create an EnvObsDictWrapper instance that wraps a gym environment and converts Box observation spaces to Dict', 'test the EnvObsDictWrapper step method to verify it wraps observations into a dictionary when needed', 'test the EnvObsDictWrapper reset method to verify it returns dictionary-wrapped observations on environment reset', 'review the EnvObsDictWrapper class and its approach to wrapping Box observation spaces into Dict spaces', 'wrap a Habitat RLEnv with HabGymWrapper to expose a standard OpenAI Gym interface with Box or Discrete action spaces', 'create a gym Box or Discrete action space from a Habitat task action space using create_action_space', 'convert a numpy array continuous action vector into a Habitat-compatible action dictionary using continuous_vector_action_to_hab_dict', 'filter a Habitat observation space to only include specified keys using filter_observation_space', 'render the wrapped Habitat environment as an RGB array or human display using HabGymWrapper render method']
```

Usage

```
{'build_envobsdictwrapper': 'build a python module that wraps a gym environment to ensure its observation space is a dictionary', 'create_envobsdictwrapper_init': 'create an EnvObsDictWrapper instance that wraps a gym environment and converts Box observation spaces to Dict', 'test_envobsdictwrapper_step': 'test the EnvObsDictWrapper step method to verify it wraps observations into a dictionary when needed', 'test_envobsdictwrapper_reset': 'test the EnvObsDictWrapper reset method to verify it returns dictionary-wrapped observations on environment reset', 'review_envobsdictwrapper_class': 'review the EnvObsDictWrapper class and its approach to wrapping Box observation spaces into Dict spaces'}
```

## File: facebookresearch_partnr-planner/third_party/habitat-lab/habitat-lab/habitat/gym/gym_wrapper.py

Prompts

```
['create a gym environment from a habitat-lab or habitat-baseline DictConfig object', 'build a gym environment from a habitat config YAML file path with optional overrides', 'add a third-person RGB sensor to the default agent in a habitat simulator config', 'register a new gym environment with an entry point and kwargs if not already registered', 'extract the env_task name from a habitat-lab or habitat-baseline DictConfig', 'build a python module to wrap a gym environment with EnvCountEpisodeWrapper to count episodes', 'create an EnvCountEpisodeWrapper instance wrapping a habitat gym environment to track episode counts', 'test the EnvCountEpisodeWrapper step method to verify episode counter increments on done', 'test the EnvCountEpisodeWrapper reset method to verify episode counter increments on reset', 'review the EnvCountEpisodeWrapper number_of_episodes property to understand fallback behavior when env lacks it', 'build a python module that wraps a gym environment to ensure its observation space is a dictionary', 'create an EnvObsDictWrapper instance that wraps a gym environment and converts Box observation spaces to Dict', 'test the EnvObsDictWrapper step method to verify it wraps observations into a dictionary when needed', 'test the EnvObsDictWrapper reset method to verify it returns dictionary-wrapped observations on environment reset', 'review the EnvObsDictWrapper class and its approach to wrapping Box observation spaces into Dict spaces', 'wrap a Habitat RLEnv with HabGymWrapper to expose a standard OpenAI Gym interface with Box or Discrete action spaces', 'create a gym Box or Discrete action space from a Habitat task action space using create_action_space', 'convert a numpy array continuous action vector into a Habitat-compatible action dictionary using continuous_vector_action_to_hab_dict', 'filter a Habitat observation space to only include specified keys using filter_observation_space', 'render the wrapped Habitat environment as an RGB array or human display using HabGymWrapper render method']
```

Usage

```
{'wrap_habitat_env_with_gym': 'wrap a Habitat RLEnv with HabGymWrapper to expose a standard OpenAI Gym interface with Box or Discrete action spaces', 'create_action_space_from_habitat': 'create a gym Box or Discrete action space from a Habitat task action space using create_action_space', 'convert_continuous_action_to_habitat_dict': 'convert a numpy array continuous action vector into a Habitat-compatible action dictionary using continuous_vector_action_to_hab_dict', 'filter_observation_space_by_keys': 'filter a Habitat observation space to only include specified keys using filter_observation_space', 'render_habitat_env_as_rgb_array': 'render the wrapped Habitat environment as an RGB array or human display using HabGymWrapper render method'}
```

