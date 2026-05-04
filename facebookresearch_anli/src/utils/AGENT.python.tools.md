# Agent Python Tools

- repo: facebookresearch/anli
- repo_uri: https://github.com/facebookresearch/anli

## File: facebookresearch_anli/src/utils/common.py

Prompts

```
['save a list of dictionaries to a JSONL file with one JSON object per line', 'load a JSONL file and return a list of deserialized dictionaries or registered objects', 'save a Python object to a JSON file using the custom JsonableObjectEncoder', 'load and deserialize a JSON file with support for registered JsonableObj classes', 'register a JsonableObj subclass so it can be serialized and deserialized by name', 'convert a list of dictionaries to a dict indexed by a specified key field', 'convert a dictionary of items back into a plain list of values', 'append fields from a lookup dictionary into each item of a list by key', 'append fields from a nested HotpotQA-style dictionary into a list of items by key', 'merge sub-item results from a forward list back into an original dictionary by parent key', 'create a ScoreLogger instance initialized with a dictionary of score fields to track', 'call incorporate_results on a ScoreLogger to compare new scores and update if improved', 'call logging_to_file on a ScoreLogger to save the logged results history to a JSON file', 'generate a timestamped directory path for saving model checkpoints under a given model name', 'get the current date and time formatted as a string like MM-DD[HH:MM:SS]']
```

Usage

```
{'save_jsonl': 'save a list of dictionaries to a JSONL file with one JSON object per line', 'load_jsonl': 'load a JSONL file and return a list of deserialized dictionaries or registered objects', 'save_json': 'save a Python object to a JSON file using the custom JsonableObjectEncoder', 'load_json': 'load and deserialize a JSON file with support for registered JsonableObj classes', 'register_class': 'register a JsonableObj subclass so it can be serialized and deserialized by name'}
```

## File: facebookresearch_anli/src/utils/list_dict_data_tool.py

Prompts

```
['save a list of dictionaries to a JSONL file with one JSON object per line', 'load a JSONL file and return a list of deserialized dictionaries or registered objects', 'save a Python object to a JSON file using the custom JsonableObjectEncoder', 'load and deserialize a JSON file with support for registered JsonableObj classes', 'register a JsonableObj subclass so it can be serialized and deserialized by name', 'convert a list of dictionaries to a dict indexed by a specified key field', 'convert a dictionary of items back into a plain list of values', 'append fields from a lookup dictionary into each item of a list by key', 'append fields from a nested HotpotQA-style dictionary into a list of items by key', 'merge sub-item results from a forward list back into an original dictionary by parent key', 'create a ScoreLogger instance initialized with a dictionary of score fields to track', 'call incorporate_results on a ScoreLogger to compare new scores and update if improved', 'call logging_to_file on a ScoreLogger to save the logged results history to a JSON file', 'generate a timestamped directory path for saving model checkpoints under a given model name', 'get the current date and time formatted as a string like MM-DD[HH:MM:SS]']
```

Usage

```
{'convert_list_to_dict_by_key': 'convert a list of dictionaries to a dict indexed by a specified key field', 'convert_dict_to_list': 'convert a dictionary of items back into a plain list of values', 'append_fields_from_dict_to_list': 'append fields from a lookup dictionary into each item of a list by key', 'append_hotpot_style_fields': 'append fields from a nested HotpotQA-style dictionary into a list of items by key', 'merge_subfields_into_dict': 'merge sub-item results from a forward list back into an original dictionary by parent key'}
```

## File: facebookresearch_anli/src/utils/save_tool.py

Prompts

```
['save a list of dictionaries to a JSONL file with one JSON object per line', 'load a JSONL file and return a list of deserialized dictionaries or registered objects', 'save a Python object to a JSON file using the custom JsonableObjectEncoder', 'load and deserialize a JSON file with support for registered JsonableObj classes', 'register a JsonableObj subclass so it can be serialized and deserialized by name', 'convert a list of dictionaries to a dict indexed by a specified key field', 'convert a dictionary of items back into a plain list of values', 'append fields from a lookup dictionary into each item of a list by key', 'append fields from a nested HotpotQA-style dictionary into a list of items by key', 'merge sub-item results from a forward list back into an original dictionary by parent key', 'create a ScoreLogger instance initialized with a dictionary of score fields to track', 'call incorporate_results on a ScoreLogger to compare new scores and update if improved', 'call logging_to_file on a ScoreLogger to save the logged results history to a JSON file', 'generate a timestamped directory path for saving model checkpoints under a given model name', 'get the current date and time formatted as a string like MM-DD[HH:MM:SS]']
```

Usage

```
{'create_ScoreLogger': 'create a ScoreLogger instance initialized with a dictionary of score fields to track', 'incorporate_results_ScoreLogger': 'call incorporate_results on a ScoreLogger to compare new scores and update if improved', 'logging_to_file_ScoreLogger': 'call logging_to_file on a ScoreLogger to save the logged results history to a JSON file', 'gen_file_prefix': 'generate a timestamped directory path for saving model checkpoints under a given model name', 'get_cur_time_str': 'get the current date and time formatted as a string like MM-DD[HH:MM:SS]'}
```

