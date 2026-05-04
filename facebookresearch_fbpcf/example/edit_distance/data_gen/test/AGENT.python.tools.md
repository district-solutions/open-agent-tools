# Agent Python Tools

- repo: facebookresearch/fbpcf
- repo_uri: https://github.com/facebookresearch/fbpcf

## File: facebookresearch_fbpcf/example/edit_distance/data_gen/test/test_generate_edit_distance_data.py

Prompts

```
['run unit tests for EditDistanceCalculator.edit_distance with various word pairs and cost parameters', 'test edit distance calculation when one or both input strings are empty', 'test edit distance returns zero cost when word and guess are identical', 'test edit distance calculation with custom delete and insert cost values', 'test edit distance accounts for character substitution cost based on ordinal difference']
```

Usage

```
{'test_edit_distance_calculator': 'run unit tests for EditDistanceCalculator.edit_distance with various word pairs and cost parameters', 'test_edit_distance_empty_strings': 'test edit distance calculation when one or both input strings are empty', 'test_edit_distance_identical_strings': 'test edit distance returns zero cost when word and guess are identical', 'test_edit_distance_custom_costs': 'test edit distance calculation with custom delete and insert cost values', 'test_edit_distance_substitution_cost': 'test edit distance accounts for character substitution cost based on ordinal difference'}
```

