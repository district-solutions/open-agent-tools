# Agent Python Tools

- repo: facebookresearch/fbpcf
- repo_uri: https://github.com/facebookresearch/fbpcf

## File: facebookresearch_fbpcf/example/edit_distance/data_gen/edit_distance_calculator.py

Prompts

```
['calculate the edit distance between two strings using custom insert and delete costs', 'calculate the edit distance between two words using equal insert and delete costs', 'calculate the absolute ordinal distance between two individual characters', 'review the EditDistanceCalculator class and its dynamic programming approach to edit distance computation', 'refactor the edit_distance method to support substitution cost as a configurable parameter', 'run the CLI to generate edit distance benchmark data files for PCF with a word dictionary and threshold', 'create a function that reads a dictionary text file and returns a lowercase stripped list of words', 'write edit distance game parameters including threshold, delete cost, and insert cost to a CSV file', 'generate player 1 and player 2 input CSV files with random word pairs and sender messages for benchmarking']
```

Usage

```
{'calculate_edit_distance': 'calculate the edit distance between two strings using custom insert and delete costs', 'calculate_edit_distance_with_default_costs': 'calculate the edit distance between two words using equal insert and delete costs', 'calculate_character_distance': 'calculate the absolute ordinal distance between two individual characters', 'review_EditDistanceCalculator': 'review the EditDistanceCalculator class and its dynamic programming approach to edit distance computation', 'refactor_edit_distance': 'refactor the edit_distance method to support substitution cost as a configurable parameter'}
```

## File: facebookresearch_fbpcf/example/edit_distance/data_gen/generate_edit_distance_data.py

Prompts

```
['calculate the edit distance between two strings using custom insert and delete costs', 'calculate the edit distance between two words using equal insert and delete costs', 'calculate the absolute ordinal distance between two individual characters', 'review the EditDistanceCalculator class and its dynamic programming approach to edit distance computation', 'refactor the edit_distance method to support substitution cost as a configurable parameter', 'run the CLI to generate edit distance benchmark data files for PCF with a word dictionary and threshold', 'create a function that reads a dictionary text file and returns a lowercase stripped list of words', 'write edit distance game parameters including threshold, delete cost, and insert cost to a CSV file', 'generate player 1 and player 2 input CSV files with random word pairs and sender messages for benchmarking']
```

Usage

```
{'generate_edit_distance_dataset': 'run the CLI to generate edit distance benchmark data files for PCF with a word dictionary and threshold', 'read_dictionary_file': 'create a function that reads a dictionary text file and returns a lowercase stripped list of words', 'calculate_edit_distance': 'use the EditDistanceCalculator to compute the edit distance between two words with custom delete and insert costs', 'write_game_parameters': 'write edit distance game parameters including threshold, delete cost, and insert cost to a CSV file', 'generate_player_inputs': 'generate player 1 and player 2 input CSV files with random word pairs and sender messages for benchmarking'}
```

