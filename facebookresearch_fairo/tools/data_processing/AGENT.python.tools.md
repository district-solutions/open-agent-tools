# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/tools/data_processing/autocomplete_postprocess.py

Prompts

```
['run the CLI to apply grammar updates to an annotated dataset using --source_path and --output_file', 'traverse an action dictionary and map string values to word-level span indices in a command', 'get the word-level start and end span indices of a text substring within a command string', 'recursively traverse a nested action dictionary and replace matching string values with their span indices', 'write a list of dataset lines to a file with newline separators', 'run the script to preprocess text annotation files into a JSON command-to-action map', 'create a JSON map of commands to action dictionaries from text files in a directory', 'write a dictionary of commands and actions to a JSON output file', 'filter parsed commands against a commands.txt whitelist to keep only those needing annotation', 'parse pipe-delimited lines from text files into command strings and JSON action dictionaries']
```

Usage

```
{'run_autocomplete_postprocess_cli': 'run the CLI to apply grammar updates to an annotated dataset using --source_path and --output_file', 'traverse_tree_command_action_dict': 'traverse an action dictionary and map string values to word-level span indices in a command', 'get_span_range_text_command': 'get the word-level start and end span indices of a text substring within a command string', 'traverse_subtree_command_action_dict': 'recursively traverse a nested action dictionary and replace matching string values with their span indices', 'write_file_dataset_lines': 'write a list of dataset lines to a file with newline separators'}
```

## File: facebookresearch_fairo/tools/data_processing/preprocess_datasets_for_autocomplete.py

Prompts

```
['run the CLI to apply grammar updates to an annotated dataset using --source_path and --output_file', 'traverse an action dictionary and map string values to word-level span indices in a command', 'get the word-level start and end span indices of a text substring within a command string', 'recursively traverse a nested action dictionary and replace matching string values with their span indices', 'write a list of dataset lines to a file with newline separators', 'run the script to preprocess text annotation files into a JSON command-to-action map', 'create a JSON map of commands to action dictionaries from text files in a directory', 'write a dictionary of commands and actions to a JSON output file', 'filter parsed commands against a commands.txt whitelist to keep only those needing annotation', 'parse pipe-delimited lines from text files into command strings and JSON action dictionaries']
```

Usage

```
{'run_preprocess_datasets_for_autocomplete': 'run the script to preprocess text annotation files into a JSON command-to-action map', 'create_JSON_from_txt': 'create a JSON map of commands to action dictionaries from text files in a directory', 'write_JSON': 'write a dictionary of commands and actions to a JSON output file', 'filter_commands_to_annotate': 'filter parsed commands against a commands.txt whitelist to keep only those needing annotation', 'parse_pipe_delimited_command_action_pairs': 'parse pipe-delimited lines from text files into command strings and JSON action dictionaries'}
```

