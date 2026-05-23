# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/rlmeta/storage/circular_buffer.py

Prompts

```
['create a CircularBuffer instance with a given capacity and optional collate function for RL replay storage', 'append a single NestedTensor data sample to the CircularBuffer and get its insertion index', 'extend the CircularBuffer with a batch of data samples, optionally unstacking if stacked is true', 'retrieve a key-value pair from the CircularBuffer by integer index or tensor key using getitem or at', 'check the CircularBuffer capacity, current size, and whether it is empty using the size and empty properties', 'implement a subclass of Storage that provides concrete append, extend, reset, and clear methods', 'review the Storage abstract base class and its abstract methods for capacity, size, append, and extend', 'create a CircularBuffer storage with a given capacity and optional collate function for RL replay', 'test the Storage append and extend methods to verify data insertion and index returns', 'refactor a Storage subclass __getitem__ to support both integer and Tensor indexing', 'create a TensorCircularBuffer instance with a specified capacity for storing tensor data', 'extend the circular buffer with a sequence of nested tensors or stacked data', 'review the TensorCircularBuffer class methods including front, back, at, empty, reset, and clear']
```

Usage

```
{'create_circular_buffer': 'create a CircularBuffer instance with a given capacity and optional collate function for RL replay storage', 'append_data_to_buffer': 'append a single NestedTensor data sample to the CircularBuffer and get its insertion index', 'extend_buffer_with_batch': 'extend the CircularBuffer with a batch of data samples, optionally unstacking if stacked is true', 'get_item_from_buffer': 'retrieve a key-value pair from the CircularBuffer by integer index or tensor key using getitem or at', 'check_buffer_state': 'check the CircularBuffer capacity, current size, and whether it is empty using the size and empty properties'}
```

## File: facebookresearch_rlmeta/rlmeta/storage/storage.py

Prompts

```
['create a CircularBuffer instance with a given capacity and optional collate function for RL replay storage', 'append a single NestedTensor data sample to the CircularBuffer and get its insertion index', 'extend the CircularBuffer with a batch of data samples, optionally unstacking if stacked is true', 'retrieve a key-value pair from the CircularBuffer by integer index or tensor key using getitem or at', 'check the CircularBuffer capacity, current size, and whether it is empty using the size and empty properties', 'implement a subclass of Storage that provides concrete append, extend, reset, and clear methods', 'review the Storage abstract base class and its abstract methods for capacity, size, append, and extend', 'create a CircularBuffer storage with a given capacity and optional collate function for RL replay', 'test the Storage append and extend methods to verify data insertion and index returns', 'refactor a Storage subclass __getitem__ to support both integer and Tensor indexing', 'create a TensorCircularBuffer instance with a specified capacity for storing tensor data', 'extend the circular buffer with a sequence of nested tensors or stacked data', 'review the TensorCircularBuffer class methods including front, back, at, empty, reset, and clear']
```

Usage

```
{'implement_storage_subclass': 'implement a subclass of Storage that provides concrete append, extend, reset, and clear methods', 'review_storage_interface': 'review the Storage abstract base class and its abstract methods for capacity, size, append, and extend', 'create_circular_buffer_storage': 'create a CircularBuffer storage with a given capacity and optional collate function for RL replay', 'test_storage_append_extend': 'test the Storage append and extend methods to verify data insertion and index returns', 'refactor_storage_getitem': 'refactor a Storage subclass __getitem__ to support both integer and Tensor indexing'}
```

## File: facebookresearch_rlmeta/rlmeta/storage/tensor_circular_buffer.py

Prompts

```
['create a CircularBuffer instance with a given capacity and optional collate function for RL replay storage', 'append a single NestedTensor data sample to the CircularBuffer and get its insertion index', 'extend the CircularBuffer with a batch of data samples, optionally unstacking if stacked is true', 'retrieve a key-value pair from the CircularBuffer by integer index or tensor key using getitem or at', 'check the CircularBuffer capacity, current size, and whether it is empty using the size and empty properties', 'implement a subclass of Storage that provides concrete append, extend, reset, and clear methods', 'review the Storage abstract base class and its abstract methods for capacity, size, append, and extend', 'create a CircularBuffer storage with a given capacity and optional collate function for RL replay', 'test the Storage append and extend methods to verify data insertion and index returns', 'refactor a Storage subclass __getitem__ to support both integer and Tensor indexing', 'create a TensorCircularBuffer instance with a specified capacity for storing tensor data', 'extend the circular buffer with a sequence of nested tensors or stacked data', 'review the TensorCircularBuffer class methods including front, back, at, empty, reset, and clear']
```

Usage

```
{'create_TensorCircularBuffer': 'create a TensorCircularBuffer instance with a specified capacity for storing tensor data', 'append_data_to_buffer': 'append nested tensor data to the circular buffer and get the insertion index', 'extend_buffer_with_data': 'extend the circular buffer with a sequence of nested tensors or stacked data', 'get_item_from_buffer': 'get a value from the circular buffer by key or access an item by index', 'review_TensorCircularBuffer_methods': 'review the TensorCircularBuffer class methods including front, back, at, empty, reset, and clear'}
```

