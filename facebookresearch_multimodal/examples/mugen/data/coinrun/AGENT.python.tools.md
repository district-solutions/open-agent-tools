# Agent Python Tools

- repo: facebookresearch/multimodal
- repo_uri: https://github.com/facebookresearch/multimodal

## File: facebookresearch_multimodal/examples/mugen/data/coinrun/construct_from_json.py

Prompts

```
['define a semantic color map mapping CoinRun world objects, monsters, and the alien to integer labels', 'generate file paths for all CoinRun game assets including walls, coins, crates, and monsters', 'create an Asset object that loads, resizes, and optionally flips a game sprite image file', 'load all game assets from file paths into an asset map with semantic colors and alpha binarization', 'render a CoinRun game frame as a PIL Image with monsters, the agent, and world tiles', 'create a Game instance by loading game state and frames from a JSON file', 'save a Game object with its frames and maze data to a JSON file', 'create an Agent with position, velocity, and computed pose based on movement state', 'create a Monster with position, theme type, and walk animation mode logic', 'summarize a Frame object containing agent state, monsters, and coins eaten at a timestep', 'convert a CoinRun game object into a natural language text description of agent actions', 'create a Sequence object to represent a segment of agent movement with start and end frames', 'process game metadata to populate coin collection, shield changes, and monster kills for a Sequence', 'generate a natural language text description from a Sequence object based on pose type and events', 'merge multiple Sequence objects into one by combining their frames, coins, and monster data']
```

Usage

```
{'define_semantic_color_map': 'define a semantic color map mapping CoinRun world objects, monsters, and the alien to integer labels', 'generate_asset_paths': 'generate file paths for all CoinRun game assets including walls, coins, crates, and monsters', 'Asset_class': 'create an Asset object that loads, resizes, and optionally flips a game sprite image file', 'load_assets': 'load all game assets from file paths into an asset map with semantic colors and alpha binarization', 'draw_game_frame': 'render a CoinRun game frame as a PIL Image with monsters, the agent, and world tiles'}
```

## File: facebookresearch_multimodal/examples/mugen/data/coinrun/game.py

Prompts

```
['define a semantic color map mapping CoinRun world objects, monsters, and the alien to integer labels', 'generate file paths for all CoinRun game assets including walls, coins, crates, and monsters', 'create an Asset object that loads, resizes, and optionally flips a game sprite image file', 'load all game assets from file paths into an asset map with semantic colors and alpha binarization', 'render a CoinRun game frame as a PIL Image with monsters, the agent, and world tiles', 'create a Game instance by loading game state and frames from a JSON file', 'save a Game object with its frames and maze data to a JSON file', 'create an Agent with position, velocity, and computed pose based on movement state', 'create a Monster with position, theme type, and walk animation mode logic', 'summarize a Frame object containing agent state, monsters, and coins eaten at a timestep', 'convert a CoinRun game object into a natural language text description of agent actions', 'create a Sequence object to represent a segment of agent movement with start and end frames', 'process game metadata to populate coin collection, shield changes, and monster kills for a Sequence', 'generate a natural language text description from a Sequence object based on pose type and events', 'merge multiple Sequence objects into one by combining their frames, coins, and monster data']
```

Usage

```
{'create_Game_from_json': 'create a Game instance by loading game state and frames from a JSON file', 'save_Game_to_json': 'save a Game object with its frames and maze data to a JSON file', 'create_Agent_with_pose': 'create an Agent with position, velocity, and computed pose based on movement state', 'create_Monster_with_animation': 'create a Monster with position, theme type, and walk animation mode logic', 'summarize_Frame_data': 'summarize a Frame object containing agent state, monsters, and coins eaten at a timestep'}
```

## File: facebookresearch_multimodal/examples/mugen/data/coinrun/generate_text_desc.py

Prompts

```
['define a semantic color map mapping CoinRun world objects, monsters, and the alien to integer labels', 'generate file paths for all CoinRun game assets including walls, coins, crates, and monsters', 'create an Asset object that loads, resizes, and optionally flips a game sprite image file', 'load all game assets from file paths into an asset map with semantic colors and alpha binarization', 'render a CoinRun game frame as a PIL Image with monsters, the agent, and world tiles', 'create a Game instance by loading game state and frames from a JSON file', 'save a Game object with its frames and maze data to a JSON file', 'create an Agent with position, velocity, and computed pose based on movement state', 'create a Monster with position, theme type, and walk animation mode logic', 'summarize a Frame object containing agent state, monsters, and coins eaten at a timestep', 'convert a CoinRun game object into a natural language text description of agent actions', 'create a Sequence object to represent a segment of agent movement with start and end frames', 'process game metadata to populate coin collection, shield changes, and monster kills for a Sequence', 'generate a natural language text description from a Sequence object based on pose type and events', 'merge multiple Sequence objects into one by combining their frames, coins, and monster data']
```

Usage

```
{'convert_game_to_text_desc': 'convert a CoinRun game object into a natural language text description of agent actions', 'create_Sequence_class': 'create a Sequence object to represent a segment of agent movement with start and end frames', 'process_metadata_Sequence': 'process game metadata to populate coin collection, shield changes, and monster kills for a Sequence', 'generate_text_desc_Sequence': 'generate a natural language text description from a Sequence object based on pose type and events', 'merge_sequences_Sequence': 'merge multiple Sequence objects into one by combining their frames, coins, and monster data'}
```

