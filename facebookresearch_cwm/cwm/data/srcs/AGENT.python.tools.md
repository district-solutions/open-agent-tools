# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/cwm/data/srcs/list.py

Prompts

```
['create a List dataset from a python list of values for iteration', 'reset the List dataset iterator back to the beginning of values', 'get the next value from the List dataset using the next method', 'serialize the current iteration index of a List dataset to a state dict', 'restore a List dataset iteration index from a previously saved state dict', 'create a Range dataset that iterates from a begin integer to an end integer', 'reset the Range dataset iterator back to its initial begin value', 'iterate through a Range dataset yielding sequential integers from begin to end', 'save the current iteration state of a Range dataset as a state dictionary', 'load a previously saved state dictionary into a Range dataset to resume iteration']
```

Usage

```
{'create_List_dataset': 'create a List dataset from a python list of values for iteration', 'reset_List_iterator': 'reset the List dataset iterator back to the beginning of values', 'iterate_List_next': 'get the next value from the List dataset using the next method', 'serialize_List_state': 'serialize the current iteration index of a List dataset to a state dict', 'restore_List_state': 'restore a List dataset iteration index from a previously saved state dict'}
```

## File: facebookresearch_cwm/cwm/data/srcs/range.py

Prompts

```
['create a List dataset from a python list of values for iteration', 'reset the List dataset iterator back to the beginning of values', 'get the next value from the List dataset using the next method', 'serialize the current iteration index of a List dataset to a state dict', 'restore a List dataset iteration index from a previously saved state dict', 'create a Range dataset that iterates from a begin integer to an end integer', 'reset the Range dataset iterator back to its initial begin value', 'iterate through a Range dataset yielding sequential integers from begin to end', 'save the current iteration state of a Range dataset as a state dictionary', 'load a previously saved state dictionary into a Range dataset to resume iteration']
```

Usage

```
{'create_range_dataset': 'create a Range dataset that iterates from a begin integer to an end integer', 'reset_range_iterator': 'reset the Range dataset iterator back to its initial begin value', 'iterate_range_values': 'iterate through a Range dataset yielding sequential integers from begin to end', 'save_range_state': 'save the current iteration state of a Range dataset as a state dictionary', 'load_range_state': 'load a previously saved state dictionary into a Range dataset to resume iteration'}
```

