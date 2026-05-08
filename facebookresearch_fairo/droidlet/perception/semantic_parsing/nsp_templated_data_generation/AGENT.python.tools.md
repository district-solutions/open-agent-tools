# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/nsp_templated_data_generation/build_scene.py

Prompts

```
['build a scene with reference objects, distractors, and mobs from template attributes for DROID semantic parsing data generation', 'generate a filtered action dictionary and natural language text from template attributes with validation', 'convert a reference object dictionary into game blocks or a mob name using shape schematics', 'recursively search a nested action dictionary for all values matching a given key and return parent-value pairs', 'recursively replace all occurrences of a specific value with a new value in a nested dictionary', 'run generate_dialogue.py with -n 100 to generate 100 action trees and language pairs', 'run generate_dialogue.py with --composite_action flag to generate only composite action sequences', 'run generate_dialogue.py with --no_composite_actions flag to generate only single action sequences', 'run generate_dialogue.py with --length_range 1 10 and --width_range 1 5 to constrain action dimensions', 'run generate_dialogue.py with --mob_file and --block_types_file to load custom entity names', 'create a function that converts a singular word to its plural form using aberrant plural rules', 'build a utility that converts a camelCase or PascalCase string to snake_case format', 'create a function that converts an integer number to its English word representation', 'build a utility that flattens a nested dictionary into a single-level dictionary', 'create a function that finds the span indices of a value within a list of tokenized sentences', 'generate a random Schematic node with Shape or CategoryObject type and optional block type', 'generate a random Shape subclass instance like CubeShape or SphereShape with schematic attributes', 'generate a Location node with Coordinates, AgentPos, or BlockObject type and relative direction', 'generate a BlockObject node with Object or PointedObject type and optional location reference', 'generate a Mob node with a random mob name like creeper or zombie and optional location']
```

Usage

```
{'build_scene': 'build a scene with reference objects, distractors, and mobs from template attributes for DROID semantic parsing data generation', 'get_good_ad': 'generate a filtered action dictionary and natural language text from template attributes with validation', 'specify_object': 'convert a reference object dictionary into game blocks or a mob name using shape schematics', 'get_fields_by_key': 'recursively search a nested action dictionary for all values matching a given key and return parent-value pairs', 'surgery_by_value': 'recursively replace all occurrences of a specific value with a new value in a nested dictionary'}
```

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/nsp_templated_data_generation/generate_dialogue.py

Prompts

```
['build a scene with reference objects, distractors, and mobs from template attributes for DROID semantic parsing data generation', 'generate a filtered action dictionary and natural language text from template attributes with validation', 'convert a reference object dictionary into game blocks or a mob name using shape schematics', 'recursively search a nested action dictionary for all values matching a given key and return parent-value pairs', 'recursively replace all occurrences of a specific value with a new value in a nested dictionary', 'run generate_dialogue.py with -n 100 to generate 100 action trees and language pairs', 'run generate_dialogue.py with --composite_action flag to generate only composite action sequences', 'run generate_dialogue.py with --no_composite_actions flag to generate only single action sequences', 'run generate_dialogue.py with --length_range 1 10 and --width_range 1 5 to constrain action dimensions', 'run generate_dialogue.py with --mob_file and --block_types_file to load custom entity names', 'create a function that converts a singular word to its plural form using aberrant plural rules', 'build a utility that converts a camelCase or PascalCase string to snake_case format', 'create a function that converts an integer number to its English word representation', 'build a utility that flattens a nested dictionary into a single-level dictionary', 'create a function that finds the span indices of a value within a list of tokenized sentences', 'generate a random Schematic node with Shape or CategoryObject type and optional block type', 'generate a random Shape subclass instance like CubeShape or SphereShape with schematic attributes', 'generate a Location node with Coordinates, AgentPos, or BlockObject type and relative direction', 'generate a BlockObject node with Object or PointedObject type and optional location reference', 'generate a Mob node with a random mob name like creeper or zombie and optional location']
```

Usage

```
{'generate_dialogue_actions': 'run generate_dialogue.py with -n 100 to generate 100 action trees and language pairs', 'generate_composite_actions': 'run generate_dialogue.py with --composite_action flag to generate only composite action sequences', 'generate_non_composite_actions': 'run generate_dialogue.py with --no_composite_actions flag to generate only single action sequences', 'generate_actions_with_ranges': 'run generate_dialogue.py with --length_range 1 10 and --width_range 1 5 to constrain action dimensions', 'generate_actions_with_files': 'run generate_dialogue.py with --mob_file and --block_types_file to load custom entity names'}
```

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/nsp_templated_data_generation/generate_utils.py

Prompts

```
['build a scene with reference objects, distractors, and mobs from template attributes for DROID semantic parsing data generation', 'generate a filtered action dictionary and natural language text from template attributes with validation', 'convert a reference object dictionary into game blocks or a mob name using shape schematics', 'recursively search a nested action dictionary for all values matching a given key and return parent-value pairs', 'recursively replace all occurrences of a specific value with a new value in a nested dictionary', 'run generate_dialogue.py with -n 100 to generate 100 action trees and language pairs', 'run generate_dialogue.py with --composite_action flag to generate only composite action sequences', 'run generate_dialogue.py with --no_composite_actions flag to generate only single action sequences', 'run generate_dialogue.py with --length_range 1 10 and --width_range 1 5 to constrain action dimensions', 'run generate_dialogue.py with --mob_file and --block_types_file to load custom entity names', 'create a function that converts a singular word to its plural form using aberrant plural rules', 'build a utility that converts a camelCase or PascalCase string to snake_case format', 'create a function that converts an integer number to its English word representation', 'build a utility that flattens a nested dictionary into a single-level dictionary', 'create a function that finds the span indices of a value within a list of tokenized sentences', 'generate a random Schematic node with Shape or CategoryObject type and optional block type', 'generate a random Shape subclass instance like CubeShape or SphereShape with schematic attributes', 'generate a Location node with Coordinates, AgentPos, or BlockObject type and relative direction', 'generate a BlockObject node with Object or PointedObject type and optional location reference', 'generate a Mob node with a random mob name like creeper or zombie and optional location']
```

Usage

```
{'make_plural_word': 'create a function that converts a singular word to its plural form using aberrant plural rules', 'convert_to_snake_case': 'build a utility that converts a camelCase or PascalCase string to snake_case format', 'int_to_words': 'create a function that converts an integer number to its English word representation', 'flatten_nested_dict': 'build a utility that flattens a nested dictionary into a single-level dictionary', 'find_span_in_list': 'create a function that finds the span indices of a value within a list of tokenized sentences'}
```

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/nsp_templated_data_generation/tree_components.py

Prompts

```
['build a scene with reference objects, distractors, and mobs from template attributes for DROID semantic parsing data generation', 'generate a filtered action dictionary and natural language text from template attributes with validation', 'convert a reference object dictionary into game blocks or a mob name using shape schematics', 'recursively search a nested action dictionary for all values matching a given key and return parent-value pairs', 'recursively replace all occurrences of a specific value with a new value in a nested dictionary', 'run generate_dialogue.py with -n 100 to generate 100 action trees and language pairs', 'run generate_dialogue.py with --composite_action flag to generate only composite action sequences', 'run generate_dialogue.py with --no_composite_actions flag to generate only single action sequences', 'run generate_dialogue.py with --length_range 1 10 and --width_range 1 5 to constrain action dimensions', 'run generate_dialogue.py with --mob_file and --block_types_file to load custom entity names', 'create a function that converts a singular word to its plural form using aberrant plural rules', 'build a utility that converts a camelCase or PascalCase string to snake_case format', 'create a function that converts an integer number to its English word representation', 'build a utility that flattens a nested dictionary into a single-level dictionary', 'create a function that finds the span indices of a value within a list of tokenized sentences', 'generate a random Schematic node with Shape or CategoryObject type and optional block type', 'generate a random Shape subclass instance like CubeShape or SphereShape with schematic attributes', 'generate a Location node with Coordinates, AgentPos, or BlockObject type and relative direction', 'generate a BlockObject node with Object or PointedObject type and optional location reference', 'generate a Mob node with a random mob name like creeper or zombie and optional location']
```

Usage

```
{'generate_schematic': 'generate a random Schematic node with Shape or CategoryObject type and optional block type', 'generate_shape': 'generate a random Shape subclass instance like CubeShape or SphereShape with schematic attributes', 'generate_location': 'generate a Location node with Coordinates, AgentPos, or BlockObject type and relative direction', 'generate_block_object': 'generate a BlockObject node with Object or PointedObject type and optional location reference', 'generate_mob': 'generate a Mob node with a random mob name like creeper or zombie and optional location'}
```

