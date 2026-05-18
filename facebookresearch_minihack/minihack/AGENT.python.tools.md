# Agent Python Tools

- repo: facebookresearch/minihack
- repo_uri: https://github.com/facebookresearch/minihack

## File: facebookresearch_minihack/minihack/base.py

Prompts

```
['create a MiniHack environment with a custom .des file and reward configuration', 'reset the MiniHack environment and sample a random level seed for a new episode', 'step the MiniHack environment with an action and receive observation reward and done signals', 'get the screen descriptions of the nine neighboring tiles around the agent in the environment', 'check whether a named object or monster is visible on the current screen of the environment', 'create a LevelGenerator instance with a 10x10 map filled with floor tiles and hardfloor flag', 'add an apple object with percent symbol at coordinates (3, 4) on the generated level map', 'add a hostile jackal monster at coordinates (5, 5) on the generated level map', 'generate the complete NetHack description file string from the LevelGenerator with all added objects and monsters', 'add a random maze starting from the center of the map heading east using mazewalk', 'create a RewardManager instance and add location, message, and coordinate events for a MiniHack task', 'add an eat event to the RewardManager that triggers when the agent eats a specified food item', 'add a kill event to the RewardManager that triggers when the agent kills a specified monster', 'add a positional event to the RewardManager that triggers on taking an action at a named place', 'create a SequentialRewardManager that requires events to be completed in the order they were added', 'create a NetHackWiki instance from a raw or processed wiki JSON file', 'get the cleaned text content of a NetHack wiki page by name', 'get the full data dict for a NetHack wiki page including anchors and categories', 'process an input string to extract and singularize its last noun using NLP', 'process a list of raw wiki JSON pages into a single dict with anchors and redirects']
```

Usage

```
{'create_minihack_env': 'create a MiniHack environment with a custom .des file and reward configuration', 'reset_minihack_env': 'reset the MiniHack environment and sample a random level seed for a new episode', 'step_minihack_env': 'step the MiniHack environment with an action and receive observation reward and done signals', 'get_neighbor_descriptions': 'get the screen descriptions of the nine neighboring tiles around the agent in the environment', 'screen_contains': 'check whether a named object or monster is visible on the current screen of the environment'}
```

## File: facebookresearch_minihack/minihack/level_generator.py

Prompts

```
['create a MiniHack environment with a custom .des file and reward configuration', 'reset the MiniHack environment and sample a random level seed for a new episode', 'step the MiniHack environment with an action and receive observation reward and done signals', 'get the screen descriptions of the nine neighboring tiles around the agent in the environment', 'check whether a named object or monster is visible on the current screen of the environment', 'create a LevelGenerator instance with a 10x10 map filled with floor tiles and hardfloor flag', 'add an apple object with percent symbol at coordinates (3, 4) on the generated level map', 'add a hostile jackal monster at coordinates (5, 5) on the generated level map', 'generate the complete NetHack description file string from the LevelGenerator with all added objects and monsters', 'add a random maze starting from the center of the map heading east using mazewalk', 'create a RewardManager instance and add location, message, and coordinate events for a MiniHack task', 'add an eat event to the RewardManager that triggers when the agent eats a specified food item', 'add a kill event to the RewardManager that triggers when the agent kills a specified monster', 'add a positional event to the RewardManager that triggers on taking an action at a named place', 'create a SequentialRewardManager that requires events to be completed in the order they were added', 'create a NetHackWiki instance from a raw or processed wiki JSON file', 'get the cleaned text content of a NetHack wiki page by name', 'get the full data dict for a NetHack wiki page including anchors and categories', 'process an input string to extract and singularize its last noun using NLP', 'process a list of raw wiki JSON pages into a single dict with anchors and redirects']
```

Usage

```
{'create_level_generator': 'create a LevelGenerator instance with a 10x10 map filled with floor tiles and hardfloor flag', 'add_object_to_map': 'add an apple object with percent symbol at coordinates (3, 4) on the generated level map', 'add_monster_to_map': 'add a hostile jackal monster at coordinates (5, 5) on the generated level map', 'generate_des_file': 'generate the complete NetHack description file string from the LevelGenerator with all added objects and monsters', 'add_mazewalk': 'add a random maze starting from the center of the map heading east using mazewalk'}
```

## File: facebookresearch_minihack/minihack/reward_manager.py

Prompts

```
['create a MiniHack environment with a custom .des file and reward configuration', 'reset the MiniHack environment and sample a random level seed for a new episode', 'step the MiniHack environment with an action and receive observation reward and done signals', 'get the screen descriptions of the nine neighboring tiles around the agent in the environment', 'check whether a named object or monster is visible on the current screen of the environment', 'create a LevelGenerator instance with a 10x10 map filled with floor tiles and hardfloor flag', 'add an apple object with percent symbol at coordinates (3, 4) on the generated level map', 'add a hostile jackal monster at coordinates (5, 5) on the generated level map', 'generate the complete NetHack description file string from the LevelGenerator with all added objects and monsters', 'add a random maze starting from the center of the map heading east using mazewalk', 'create a RewardManager instance and add location, message, and coordinate events for a MiniHack task', 'add an eat event to the RewardManager that triggers when the agent eats a specified food item', 'add a kill event to the RewardManager that triggers when the agent kills a specified monster', 'add a positional event to the RewardManager that triggers on taking an action at a named place', 'create a SequentialRewardManager that requires events to be completed in the order they were added', 'create a NetHackWiki instance from a raw or processed wiki JSON file', 'get the cleaned text content of a NetHack wiki page by name', 'get the full data dict for a NetHack wiki page including anchors and categories', 'process an input string to extract and singularize its last noun using NLP', 'process a list of raw wiki JSON pages into a single dict with anchors and redirects']
```

Usage

```
{'create_reward_manager': 'create a RewardManager instance and add location, message, and coordinate events for a MiniHack task', 'add_eat_event': 'add an eat event to the RewardManager that triggers when the agent eats a specified food item', 'add_kill_event': 'add a kill event to the RewardManager that triggers when the agent kills a specified monster', 'add_positional_event': 'add a positional event to the RewardManager that triggers on taking an action at a named place', 'create_sequential_reward_manager': 'create a SequentialRewardManager that requires events to be completed in the order they were added'}
```

## File: facebookresearch_minihack/minihack/wiki.py

Prompts

```
['create a MiniHack environment with a custom .des file and reward configuration', 'reset the MiniHack environment and sample a random level seed for a new episode', 'step the MiniHack environment with an action and receive observation reward and done signals', 'get the screen descriptions of the nine neighboring tiles around the agent in the environment', 'check whether a named object or monster is visible on the current screen of the environment', 'create a LevelGenerator instance with a 10x10 map filled with floor tiles and hardfloor flag', 'add an apple object with percent symbol at coordinates (3, 4) on the generated level map', 'add a hostile jackal monster at coordinates (5, 5) on the generated level map', 'generate the complete NetHack description file string from the LevelGenerator with all added objects and monsters', 'add a random maze starting from the center of the map heading east using mazewalk', 'create a RewardManager instance and add location, message, and coordinate events for a MiniHack task', 'add an eat event to the RewardManager that triggers when the agent eats a specified food item', 'add a kill event to the RewardManager that triggers when the agent kills a specified monster', 'add a positional event to the RewardManager that triggers on taking an action at a named place', 'create a SequentialRewardManager that requires events to be completed in the order they were added', 'create a NetHackWiki instance from a raw or processed wiki JSON file', 'get the cleaned text content of a NetHack wiki page by name', 'get the full data dict for a NetHack wiki page including anchors and categories', 'process an input string to extract and singularize its last noun using NLP', 'process a list of raw wiki JSON pages into a single dict with anchors and redirects']
```

Usage

```
{'create_NetHackWiki': 'create a NetHackWiki instance from a raw or processed wiki JSON file', 'get_page_text_NetHackWiki': 'get the cleaned text content of a NetHack wiki page by name', 'get_page_data_NetHackWiki': 'get the full data dict for a NetHack wiki page including anchors and categories', 'process_TextProcessor': 'process an input string to extract and singularize its last noun using NLP', 'process_json_function': 'process a list of raw wiki JSON pages into a single dict with anchors and redirects'}
```

