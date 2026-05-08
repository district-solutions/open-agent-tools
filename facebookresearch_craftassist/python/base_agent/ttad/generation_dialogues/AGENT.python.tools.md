# Agent Python Tools

- repo: facebookresearch/craftassist
- repo_uri: https://github.com/facebookresearch/craftassist

## File: facebookresearch_craftassist/python/base_agent/ttad/generation_dialogues/build_scene.py

Prompts

```
['build a scene with reference objects, distractors, and mobs from template attributes for CraftAssist dialogue generation', 'generate a filtered action dictionary and natural language text from template attributes with validation', 'convert a reference object dictionary into game blocks or a mob name using shape schematics', 'recursively search a nested action dictionary and return all fields matching a given key', 'recursively replace all occurrences of a specific value with a new value in a nested dictionary', 'generate N random action trees and language descriptions for game actions like build, move, destroy, and dig', 'run the CLI tool to generate dialogue action pairs with configurable action types, numeric ranges, and composite action flags', 'create a composite action by combining two actions into a single action sequence with joined text and merged action dicts', 'fix composite action dicts by splitting schematics or reference objects that contain two entities into separate action dicts', 'combine two action dicts by appending the second action sequence to the first after adjusting token spans for sentence length', 'create a function that converts a singular word to its plural form using aberrant plural rules', 'build a utility that converts CamelCase or PascalCase strings to snake_case format', 'create a function that converts an integer number to its English word representation', 'build a utility that flattens a nested dictionary into a single-level dictionary', 'create a function that finds the span indices of a value within a list of tokenized sentences', 'generate a Schematic node with random shape, block type, size, and colour for Minecraft action trees', 'generate a natural language description for a CubeShape or SphereShape node with block type and dimensions', 'generate a Location node with coordinates, relative direction, and steps for Minecraft dialogue generation', 'generate a BlockObject node with Object or PointedObject type, size, colour, and optional location', 'generate a Mob node with a random mob name, repetition, and optional location for Minecraft dialogue']
```

Usage

```
{'build_scene': 'build a scene with reference objects, distractors, and mobs from template attributes for CraftAssist dialogue generation', 'get_good_ad': 'generate a filtered action dictionary and natural language text from template attributes with validation', 'specify_object': 'convert a reference object dictionary into game blocks or a mob name using shape schematics', 'get_fields_by_key': 'recursively search a nested action dictionary and return all fields matching a given key', 'surgery_by_value': 'recursively replace all occurrences of a specific value with a new value in a nested dictionary'}
```

## File: facebookresearch_craftassist/python/base_agent/ttad/generation_dialogues/generate_dialogue.py

Prompts

```
['build a scene with reference objects, distractors, and mobs from template attributes for CraftAssist dialogue generation', 'generate a filtered action dictionary and natural language text from template attributes with validation', 'convert a reference object dictionary into game blocks or a mob name using shape schematics', 'recursively search a nested action dictionary and return all fields matching a given key', 'recursively replace all occurrences of a specific value with a new value in a nested dictionary', 'generate N random action trees and language descriptions for game actions like build, move, destroy, and dig', 'run the CLI tool to generate dialogue action pairs with configurable action types, numeric ranges, and composite action flags', 'create a composite action by combining two actions into a single action sequence with joined text and merged action dicts', 'fix composite action dicts by splitting schematics or reference objects that contain two entities into separate action dicts', 'combine two action dicts by appending the second action sequence to the first after adjusting token spans for sentence length', 'create a function that converts a singular word to its plural form using aberrant plural rules', 'build a utility that converts CamelCase or PascalCase strings to snake_case format', 'create a function that converts an integer number to its English word representation', 'build a utility that flattens a nested dictionary into a single-level dictionary', 'create a function that finds the span indices of a value within a list of tokenized sentences', 'generate a Schematic node with random shape, block type, size, and colour for Minecraft action trees', 'generate a natural language description for a CubeShape or SphereShape node with block type and dimensions', 'generate a Location node with coordinates, relative direction, and steps for Minecraft dialogue generation', 'generate a BlockObject node with Object or PointedObject type, size, colour, and optional location', 'generate a Mob node with a random mob name, repetition, and optional location for Minecraft dialogue']
```

Usage

```
{'generate_actions': 'generate N random action trees and language descriptions for game actions like build, move, destroy, and dig', 'run_generate_dialogue_cli': 'run the CLI tool to generate dialogue action pairs with configurable action types, numeric ranges, and composite action flags', 'create_composite_action': 'create a composite action by combining two actions into a single action sequence with joined text and merged action dicts', 'fix_composite_in_dict': 'fix composite action dicts by splitting schematics or reference objects that contain two entities into separate action dicts', 'combine_dicts': 'combine two action dicts by appending the second action sequence to the first after adjusting token spans for sentence length'}
```

## File: facebookresearch_craftassist/python/base_agent/ttad/generation_dialogues/generate_utils.py

Prompts

```
['build a scene with reference objects, distractors, and mobs from template attributes for CraftAssist dialogue generation', 'generate a filtered action dictionary and natural language text from template attributes with validation', 'convert a reference object dictionary into game blocks or a mob name using shape schematics', 'recursively search a nested action dictionary and return all fields matching a given key', 'recursively replace all occurrences of a specific value with a new value in a nested dictionary', 'generate N random action trees and language descriptions for game actions like build, move, destroy, and dig', 'run the CLI tool to generate dialogue action pairs with configurable action types, numeric ranges, and composite action flags', 'create a composite action by combining two actions into a single action sequence with joined text and merged action dicts', 'fix composite action dicts by splitting schematics or reference objects that contain two entities into separate action dicts', 'combine two action dicts by appending the second action sequence to the first after adjusting token spans for sentence length', 'create a function that converts a singular word to its plural form using aberrant plural rules', 'build a utility that converts CamelCase or PascalCase strings to snake_case format', 'create a function that converts an integer number to its English word representation', 'build a utility that flattens a nested dictionary into a single-level dictionary', 'create a function that finds the span indices of a value within a list of tokenized sentences', 'generate a Schematic node with random shape, block type, size, and colour for Minecraft action trees', 'generate a natural language description for a CubeShape or SphereShape node with block type and dimensions', 'generate a Location node with coordinates, relative direction, and steps for Minecraft dialogue generation', 'generate a BlockObject node with Object or PointedObject type, size, colour, and optional location', 'generate a Mob node with a random mob name, repetition, and optional location for Minecraft dialogue']
```

Usage

```
{'make_plural_word': 'create a function that converts a singular word to its plural form using aberrant plural rules', 'convert_to_snake_case': 'build a utility that converts CamelCase or PascalCase strings to snake_case format', 'int_to_words': 'create a function that converts an integer number to its English word representation', 'flatten_nested_dict': 'build a utility that flattens a nested dictionary into a single-level dictionary', 'find_span_in_list': 'create a function that finds the span indices of a value within a list of tokenized sentences'}
```

## File: facebookresearch_craftassist/python/base_agent/ttad/generation_dialogues/tree_components.py

Prompts

```
['build a scene with reference objects, distractors, and mobs from template attributes for CraftAssist dialogue generation', 'generate a filtered action dictionary and natural language text from template attributes with validation', 'convert a reference object dictionary into game blocks or a mob name using shape schematics', 'recursively search a nested action dictionary and return all fields matching a given key', 'recursively replace all occurrences of a specific value with a new value in a nested dictionary', 'generate N random action trees and language descriptions for game actions like build, move, destroy, and dig', 'run the CLI tool to generate dialogue action pairs with configurable action types, numeric ranges, and composite action flags', 'create a composite action by combining two actions into a single action sequence with joined text and merged action dicts', 'fix composite action dicts by splitting schematics or reference objects that contain two entities into separate action dicts', 'combine two action dicts by appending the second action sequence to the first after adjusting token spans for sentence length', 'create a function that converts a singular word to its plural form using aberrant plural rules', 'build a utility that converts CamelCase or PascalCase strings to snake_case format', 'create a function that converts an integer number to its English word representation', 'build a utility that flattens a nested dictionary into a single-level dictionary', 'create a function that finds the span indices of a value within a list of tokenized sentences', 'generate a Schematic node with random shape, block type, size, and colour for Minecraft action trees', 'generate a natural language description for a CubeShape or SphereShape node with block type and dimensions', 'generate a Location node with coordinates, relative direction, and steps for Minecraft dialogue generation', 'generate a BlockObject node with Object or PointedObject type, size, colour, and optional location', 'generate a Mob node with a random mob name, repetition, and optional location for Minecraft dialogue']
```

Usage

```
{'generate_schematic_node': 'generate a Schematic node with random shape, block type, size, and colour for Minecraft action trees', 'generate_shape_description': 'generate a natural language description for a CubeShape or SphereShape node with block type and dimensions', 'generate_location_node': 'generate a Location node with coordinates, relative direction, and steps for Minecraft dialogue generation', 'generate_block_object': 'generate a BlockObject node with Object or PointedObject type, size, colour, and optional location', 'generate_mob_node': 'generate a Mob node with a random mob name, repetition, and optional location for Minecraft dialogue'}
```

