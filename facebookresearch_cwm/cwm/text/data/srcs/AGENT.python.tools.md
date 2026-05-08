# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/cwm/text/data/srcs/jsonl.py

Prompts

```
['load a JSONL file into a Dataset of DictDatum objects using from_jsonl', 'load JSONL files matching a glob pattern into a Dataset using from_jsonl', 'load a JSONL dataset with lenient JSON parsing that skips malformed lines', 'parse a single text line into a DictDatum using _from_text_file_line', 'register the jsonl source type with Dataset using the from_jsonl decorator', 'create a OneFileLines iterator to read lines from a text file with encoding support', 'use from_text_file_lines to create a Dataset from a single text file path', 'use from_text_file_lines to chain multiple files from a directory into a Dataset', 'use from_text_file_lines with a regex pattern to filter files in a directory', 'review the OneFileLines state_dict and load_state_dict methods for checkpointing iteration progress']
```

Usage

```
{'load_jsonl_dataset': 'load a JSONL file into a Dataset of DictDatum objects using from_jsonl', 'load_jsonl_with_pattern': 'load JSONL files matching a glob pattern into a Dataset using from_jsonl', 'load_jsonl_non_strict': 'load a JSONL dataset with lenient JSON parsing that skips malformed lines', 'parse_jsonl_line': 'parse a single text line into a DictDatum using _from_text_file_line', 'register_jsonl_source': 'register the jsonl source type with Dataset using the from_jsonl decorator'}
```

## File: facebookresearch_cwm/cwm/text/data/srcs/text_file_lines.py

Prompts

```
['load a JSONL file into a Dataset of DictDatum objects using from_jsonl', 'load JSONL files matching a glob pattern into a Dataset using from_jsonl', 'load a JSONL dataset with lenient JSON parsing that skips malformed lines', 'parse a single text line into a DictDatum using _from_text_file_line', 'register the jsonl source type with Dataset using the from_jsonl decorator', 'create a OneFileLines iterator to read lines from a text file with encoding support', 'use from_text_file_lines to create a Dataset from a single text file path', 'use from_text_file_lines to chain multiple files from a directory into a Dataset', 'use from_text_file_lines with a regex pattern to filter files in a directory', 'review the OneFileLines state_dict and load_state_dict methods for checkpointing iteration progress']
```

Usage

```
{'create_OneFileLines_iterator': 'create a OneFileLines iterator to read lines from a text file with encoding support', 'use_from_text_file_lines_single': 'use from_text_file_lines to create a Dataset from a single text file path', 'use_from_text_file_lines_directory': 'use from_text_file_lines to chain multiple files from a directory into a Dataset', 'use_from_text_file_lines_pattern': 'use from_text_file_lines with a regex pattern to filter files in a directory', 'review_OneFileLines_state': 'review the OneFileLines state_dict and load_state_dict methods for checkpointing iteration progress'}
```

