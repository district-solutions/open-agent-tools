# Agent Python Tools

- repo: facebookresearch/craftassist
- repo_uri: https://github.com/facebookresearch/craftassist

## File: facebookresearch_craftassist/python/base_agent/ttad/ttad_model/processing_scripts/read_data.py

Prompts

```
['read a file of JSON action trees and parse each into an ActionTree with top-down, DFS, and MRF representations', 'parse JSON action tree lines from a file into structured ActionTree objects with descriptions', 'extract action descriptions from JSON action tree dictionaries and remove them from the tree data', 'build top-down, DFS, and MRF representations from an ActionTree root node', 'print a randomly selected parsed action tree entry from the generated data list', 'tokenize a string into words with character offsets using spaCy English tokenizer', 'remove bracket characters from a sentence and return cleaned text with word spans', 'load rephrased sentence pairs from CSV files and process bracket annotations', 'build rephrased sentence trees by mapping bracket spans onto original valid tree structures', 'export processed rephrase trees as a JSON file for downstream use']
```

Usage

```
{'read_generations': 'read a file of JSON action trees and parse each into an ActionTree with top-down, DFS, and MRF representations', 'parse_action_trees': 'parse JSON action tree lines from a file into structured ActionTree objects with descriptions', 'extract_action_descriptions': 'extract action descriptions from JSON action tree dictionaries and remove them from the tree data', 'build_action_representations': 'build top-down, DFS, and MRF representations from an ActionTree root node', 'sample_generated_data': 'print a randomly selected parsed action tree entry from the generated data list'}
```

## File: facebookresearch_craftassist/python/base_agent/ttad/ttad_model/processing_scripts/read_rephrased.py

Prompts

```
['read a file of JSON action trees and parse each into an ActionTree with top-down, DFS, and MRF representations', 'parse JSON action tree lines from a file into structured ActionTree objects with descriptions', 'extract action descriptions from JSON action tree dictionaries and remove them from the tree data', 'build top-down, DFS, and MRF representations from an ActionTree root node', 'print a randomly selected parsed action tree entry from the generated data list', 'tokenize a string into words with character offsets using spaCy English tokenizer', 'remove bracket characters from a sentence and return cleaned text with word spans', 'load rephrased sentence pairs from CSV files and process bracket annotations', 'build rephrased sentence trees by mapping bracket spans onto original valid tree structures', 'export processed rephrase trees as a JSON file for downstream use']
```

Usage

```
{'word_tokenize': 'tokenize a string into words with character offsets using spaCy English tokenizer', 'remove_brackets': 'remove bracket characters from a sentence and return cleaned text with word spans', 'process_rephrased_csv': 'load rephrased sentence pairs from CSV files and process bracket annotations', 'build_rephrase_trees': 'build rephrased sentence trees by mapping bracket spans onto original valid tree structures', 'export_rephrase_trees': 'export processed rephrase trees as a JSON file for downstream use'}
```

