# Agent Python Tools

- repo: facebookresearch/habitat-challenge
- repo_uri: https://github.com/facebookresearch/habitat-challenge

## File: facebookresearch_habitat-challenge/agents/agent.py

Prompts

```
['run the RandomAgent in local evaluation mode with a specified action space via argparse CLI', 'run the RandomAgent in remote evaluation mode against the Habitat challenge benchmark server', 'create a RandomAgent instance that returns random velocity, waypoint, or discrete actions based on config', 'review the RandomAgent act method to understand how it selects random actions for each action space type', 'refactor the RandomAgent class to support additional action spaces beyond velocity, waypoint, and discrete waypoint control', 'build a Hydra SearchPathPlugin subclass that appends a custom config search path for habitat challenge', 'create a config search path entry with provider habitat_challenge pointing to file:///configs', 'review the HabitatChallengeConfigPlugin class and its manipulate_search_path method that appends a file-based config path', 'refactor the HabitatChallengeConfigPlugin to support dynamic config paths instead of hardcoded file:///configs', 'test the HabitatChallengeConfigPlugin manipulate_search_path method to verify it appends the correct provider and path', 'run the PPOAgent act method to get navigation actions from sensor observations', 'run the PPOAgent reset method to initialize recurrent hidden states and masks', 'run the main CLI to submit a PPOAgent to a Habitat challenge for evaluation', 'create a PPOAgent instance from a DictConfig with loaded model checkpoint weights', 'test the set_random_seed function to seed random, numpy, numba, and torch']
```

Usage

```
{'run_random_agent_local': 'run the RandomAgent in local evaluation mode with a specified action space via argparse CLI', 'run_random_agent_remote': 'run the RandomAgent in remote evaluation mode against the Habitat challenge benchmark server', 'create_random_agent': 'create a RandomAgent instance that returns random velocity, waypoint, or discrete actions based on config', 'review_random_agent_act': 'review the RandomAgent act method to understand how it selects random actions for each action space type', 'refactor_random_agent': 'refactor the RandomAgent class to support additional action spaces beyond velocity, waypoint, and discrete waypoint control'}
```

## File: facebookresearch_habitat-challenge/agents/config.py

Prompts

```
['run the RandomAgent in local evaluation mode with a specified action space via argparse CLI', 'run the RandomAgent in remote evaluation mode against the Habitat challenge benchmark server', 'create a RandomAgent instance that returns random velocity, waypoint, or discrete actions based on config', 'review the RandomAgent act method to understand how it selects random actions for each action space type', 'refactor the RandomAgent class to support additional action spaces beyond velocity, waypoint, and discrete waypoint control', 'build a Hydra SearchPathPlugin subclass that appends a custom config search path for habitat challenge', 'create a config search path entry with provider habitat_challenge pointing to file:///configs', 'review the HabitatChallengeConfigPlugin class and its manipulate_search_path method that appends a file-based config path', 'refactor the HabitatChallengeConfigPlugin to support dynamic config paths instead of hardcoded file:///configs', 'test the HabitatChallengeConfigPlugin manipulate_search_path method to verify it appends the correct provider and path', 'run the PPOAgent act method to get navigation actions from sensor observations', 'run the PPOAgent reset method to initialize recurrent hidden states and masks', 'run the main CLI to submit a PPOAgent to a Habitat challenge for evaluation', 'create a PPOAgent instance from a DictConfig with loaded model checkpoint weights', 'test the set_random_seed function to seed random, numpy, numba, and torch']
```

Usage

```
{'build_hydra_config_plugin': 'build a Hydra SearchPathPlugin subclass that appends a custom config search path for habitat challenge', 'create_config_search_path_entry': 'create a config search path entry with provider habitat_challenge pointing to file:///configs', 'review_HabitatChallengeConfigPlugin_manipulate_search_path': 'review the HabitatChallengeConfigPlugin class and its manipulate_search_path method that appends a file-based config path', 'refactor_HabitatChallengeConfigPlugin': 'refactor the HabitatChallengeConfigPlugin to support dynamic config paths instead of hardcoded file:///configs', 'test_HabitatChallengeConfigPlugin': 'test the HabitatChallengeConfigPlugin manipulate_search_path method to verify it appends the correct provider and path'}
```

## File: facebookresearch_habitat-challenge/agents/habitat_baselines_agent.py

Prompts

```
['run the RandomAgent in local evaluation mode with a specified action space via argparse CLI', 'run the RandomAgent in remote evaluation mode against the Habitat challenge benchmark server', 'create a RandomAgent instance that returns random velocity, waypoint, or discrete actions based on config', 'review the RandomAgent act method to understand how it selects random actions for each action space type', 'refactor the RandomAgent class to support additional action spaces beyond velocity, waypoint, and discrete waypoint control', 'build a Hydra SearchPathPlugin subclass that appends a custom config search path for habitat challenge', 'create a config search path entry with provider habitat_challenge pointing to file:///configs', 'review the HabitatChallengeConfigPlugin class and its manipulate_search_path method that appends a file-based config path', 'refactor the HabitatChallengeConfigPlugin to support dynamic config paths instead of hardcoded file:///configs', 'test the HabitatChallengeConfigPlugin manipulate_search_path method to verify it appends the correct provider and path', 'run the PPOAgent act method to get navigation actions from sensor observations', 'run the PPOAgent reset method to initialize recurrent hidden states and masks', 'run the main CLI to submit a PPOAgent to a Habitat challenge for evaluation', 'create a PPOAgent instance from a DictConfig with loaded model checkpoint weights', 'test the set_random_seed function to seed random, numpy, numba, and torch']
```

Usage

```
{'run_PPOAgent_act': 'run the PPOAgent act method to get navigation actions from sensor observations', 'run_PPOAgent_reset': 'run the PPOAgent reset method to initialize recurrent hidden states and masks', 'run_main_cli': 'run the main CLI to submit a PPOAgent to a Habitat challenge for evaluation', 'create_PPOAgent': 'create a PPOAgent instance from a DictConfig with loaded model checkpoint weights', 'test_set_random_seed': 'test the set_random_seed function to seed random, numpy, numba, and torch'}
```

