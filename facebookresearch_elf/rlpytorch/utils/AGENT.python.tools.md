# Agent Python Tools

- repo: facebookresearch/elf
- repo_uri: https://github.com/facebookresearch/elf

## File: facebookresearch_elf/rlpytorch/utils/hist_states.py

Prompts

```
['create a HistState instance with history length T and an optional init_state_func for initial state generation', 'preprocess agent IDs and sequence positions to clear old game states and initialize new ones', 'feed hidden state tensors into the HistState queues for each agent ID with bounded history length', 'retrieve the newest or oldest batched hidden states for a list of agent IDs at a given time offset', 'apply a transformation function across all time steps of the history states for a batch of agent IDs', 'calculate the approximate memory footprint of a Python object and all its nested contents', 'calculate the total memory size of a dictionary including all keys and values recursively', 'calculate the total memory size of a list including all nested elements recursively', 'calculate the memory footprint of an object with verbose output to stderr for debugging', 'calculate the memory size of an object using custom handlers for user-defined container types', 'convert a numpy image array to float32 normalized and transposed tensor format', 'serialize a python object to msgpack binary format with numpy array support', 'time a named code block using the Timer context manager and print summary', 'perform safe queue get or put operations with a done flag and timeout', 'track forward prediction errors across delays using the ForwardTracker class']
```

Usage

```
{'create_HistState': 'create a HistState instance with history length T and an optional init_state_func for initial state generation', 'preprocess_HistState': 'preprocess agent IDs and sequence positions to clear old game states and initialize new ones', 'feed_HistState': 'feed hidden state tensors into the HistState queues for each agent ID with bounded history length', 'get_newest_oldest_HistState': 'retrieve the newest or oldest batched hidden states for a list of agent IDs at a given time offset', 'map_HistState': 'apply a transformation function across all time steps of the history states for a batch of agent IDs'}
```

## File: facebookresearch_elf/rlpytorch/utils/size_utils.py

Prompts

```
['create a HistState instance with history length T and an optional init_state_func for initial state generation', 'preprocess agent IDs and sequence positions to clear old game states and initialize new ones', 'feed hidden state tensors into the HistState queues for each agent ID with bounded history length', 'retrieve the newest or oldest batched hidden states for a list of agent IDs at a given time offset', 'apply a transformation function across all time steps of the history states for a batch of agent IDs', 'calculate the approximate memory footprint of a Python object and all its nested contents', 'calculate the total memory size of a dictionary including all keys and values recursively', 'calculate the total memory size of a list including all nested elements recursively', 'calculate the memory footprint of an object with verbose output to stderr for debugging', 'calculate the memory size of an object using custom handlers for user-defined container types', 'convert a numpy image array to float32 normalized and transposed tensor format', 'serialize a python object to msgpack binary format with numpy array support', 'time a named code block using the Timer context manager and print summary', 'perform safe queue get or put operations with a done flag and timeout', 'track forward prediction errors across delays using the ForwardTracker class']
```

Usage

```
{'calculate_total_size_of_object': 'calculate the approximate memory footprint of a Python object and all its nested contents', 'calculate_size_of_dict': 'calculate the total memory size of a dictionary including all keys and values recursively', 'calculate_size_of_list': 'calculate the total memory size of a list including all nested elements recursively', 'calculate_size_with_verbose_output': 'calculate the memory footprint of an object with verbose output to stderr for debugging', 'calculate_size_with_custom_handlers': 'calculate the memory size of an object using custom handlers for user-defined container types'}
```

## File: facebookresearch_elf/rlpytorch/utils/utils.py

Prompts

```
['create a HistState instance with history length T and an optional init_state_func for initial state generation', 'preprocess agent IDs and sequence positions to clear old game states and initialize new ones', 'feed hidden state tensors into the HistState queues for each agent ID with bounded history length', 'retrieve the newest or oldest batched hidden states for a list of agent IDs at a given time offset', 'apply a transformation function across all time steps of the history states for a batch of agent IDs', 'calculate the approximate memory footprint of a Python object and all its nested contents', 'calculate the total memory size of a dictionary including all keys and values recursively', 'calculate the total memory size of a list including all nested elements recursively', 'calculate the memory footprint of an object with verbose output to stderr for debugging', 'calculate the memory size of an object using custom handlers for user-defined container types', 'convert a numpy image array to float32 normalized and transposed tensor format', 'serialize a python object to msgpack binary format with numpy array support', 'time a named code block using the Timer context manager and print summary', 'perform safe queue get or put operations with a done flag and timeout', 'track forward prediction errors across delays using the ForwardTracker class']
```

Usage

```
{'convert_numpy_image': 'convert a numpy image array to float32 normalized and transposed tensor format', 'serialize_with_msgpack': 'serialize a python object to msgpack binary format with numpy array support', 'time_code_block': 'time a named code block using the Timer context manager and print summary', 'safe_queue_operations': 'perform safe queue get or put operations with a done flag and timeout', 'track_forward_predictions': 'track forward prediction errors across delays using the ForwardTracker class'}
```

