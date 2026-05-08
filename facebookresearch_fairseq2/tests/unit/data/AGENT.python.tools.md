# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/tests/unit/data/test_collater.py

Prompts

```
['create a Collater to stack a bucket of lists into transposed nested lists', 'create a Collater to stack a bucket of PyTorch tensors into a single batched tensor', 'create a Collater with pad_value and pad_to_multiple to pad ragged sequence tensors', 'create a Collater with CollateOptionsOverride to apply different padding per dict key path', 'test the Collater collating ragged sequence tensors and returning seqs, seq_lens, and is_ragged', 'test the FileMapper class to map a file pathname to its binary data content', 'test the FileMapper class with an offset specifier to read from a byte offset', 'test the FileMapper class with offset and size specifiers to read a byte range', 'test the FileMapper class with a root directory to resolve relative pathnames', 'test the FileMapper class error handling for invalid input types and malformed pathnames', 'create a MemoryBlock from a Python array buffer that shares memory with the original array', 'create a MemoryBlock from a buffer with copy=True to snapshot data independent of the original', 'test that a MemoryBlock supports memoryview access to inspect itemsize, shape, and strides', 'test a MemoryBlock created from a float array and cast the memoryview back to floats', 'test pickling a MemoryBlock with protocol 5 and verify data survives serialization and deserialization', 'test that read_pickle_wrapped_iterator correctly saves and restores pipeline state via state_dict', 'test that read_iterator raises TypeError when given a non-picklable generator', 'test that calling reset on a pickle-wrapped iterator pipeline restarts iteration from the beginning', 'test that state_dict and load_state_dict resume iteration from the saved position', 'test the example_generator helper function that yields integers from 0 to 9']
```

Usage

```
{'create_collater_basic': 'create a Collater to stack a bucket of lists into transposed nested lists', 'create_collater_tensors': 'create a Collater to stack a bucket of PyTorch tensors into a single batched tensor', 'create_collater_with_padding': 'create a Collater with pad_value and pad_to_multiple to pad ragged sequence tensors', 'create_collater_with_overrides': 'create a Collater with CollateOptionsOverride to apply different padding per dict key path', 'test_collater_ragged_sequences': 'test the Collater collating ragged sequence tensors and returning seqs, seq_lens, and is_ragged'}
```

## File: facebookresearch_fairseq2/tests/unit/data/test_file_mapper.py

Prompts

```
['create a Collater to stack a bucket of lists into transposed nested lists', 'create a Collater to stack a bucket of PyTorch tensors into a single batched tensor', 'create a Collater with pad_value and pad_to_multiple to pad ragged sequence tensors', 'create a Collater with CollateOptionsOverride to apply different padding per dict key path', 'test the Collater collating ragged sequence tensors and returning seqs, seq_lens, and is_ragged', 'test the FileMapper class to map a file pathname to its binary data content', 'test the FileMapper class with an offset specifier to read from a byte offset', 'test the FileMapper class with offset and size specifiers to read a byte range', 'test the FileMapper class with a root directory to resolve relative pathnames', 'test the FileMapper class error handling for invalid input types and malformed pathnames', 'create a MemoryBlock from a Python array buffer that shares memory with the original array', 'create a MemoryBlock from a buffer with copy=True to snapshot data independent of the original', 'test that a MemoryBlock supports memoryview access to inspect itemsize, shape, and strides', 'test a MemoryBlock created from a float array and cast the memoryview back to floats', 'test pickling a MemoryBlock with protocol 5 and verify data survives serialization and deserialization', 'test that read_pickle_wrapped_iterator correctly saves and restores pipeline state via state_dict', 'test that read_iterator raises TypeError when given a non-picklable generator', 'test that calling reset on a pickle-wrapped iterator pipeline restarts iteration from the beginning', 'test that state_dict and load_state_dict resume iteration from the saved position', 'test the example_generator helper function that yields integers from 0 to 9']
```

Usage

```
{'test_FileMapper_basic': 'test the FileMapper class to map a file pathname to its binary data content', 'test_FileMapper_offset': 'test the FileMapper class with an offset specifier to read from a byte offset', 'test_FileMapper_offset_size': 'test the FileMapper class with offset and size specifiers to read a byte range', 'test_FileMapper_root_dir': 'test the FileMapper class with a root directory to resolve relative pathnames', 'test_FileMapper_validation': 'test the FileMapper class error handling for invalid input types and malformed pathnames'}
```

## File: facebookresearch_fairseq2/tests/unit/data/test_memory.py

Prompts

```
['create a Collater to stack a bucket of lists into transposed nested lists', 'create a Collater to stack a bucket of PyTorch tensors into a single batched tensor', 'create a Collater with pad_value and pad_to_multiple to pad ragged sequence tensors', 'create a Collater with CollateOptionsOverride to apply different padding per dict key path', 'test the Collater collating ragged sequence tensors and returning seqs, seq_lens, and is_ragged', 'test the FileMapper class to map a file pathname to its binary data content', 'test the FileMapper class with an offset specifier to read from a byte offset', 'test the FileMapper class with offset and size specifiers to read a byte range', 'test the FileMapper class with a root directory to resolve relative pathnames', 'test the FileMapper class error handling for invalid input types and malformed pathnames', 'create a MemoryBlock from a Python array buffer that shares memory with the original array', 'create a MemoryBlock from a buffer with copy=True to snapshot data independent of the original', 'test that a MemoryBlock supports memoryview access to inspect itemsize, shape, and strides', 'test a MemoryBlock created from a float array and cast the memoryview back to floats', 'test pickling a MemoryBlock with protocol 5 and verify data survives serialization and deserialization', 'test that read_pickle_wrapped_iterator correctly saves and restores pipeline state via state_dict', 'test that read_iterator raises TypeError when given a non-picklable generator', 'test that calling reset on a pickle-wrapped iterator pipeline restarts iteration from the beginning', 'test that state_dict and load_state_dict resume iteration from the saved position', 'test the example_generator helper function that yields integers from 0 to 9']
```

Usage

```
{'create_memoryblock_from_array': 'create a MemoryBlock from a Python array buffer that shares memory with the original array', 'create_memoryblock_with_copy': 'create a MemoryBlock from a buffer with copy=True to snapshot data independent of the original', 'test_memoryblock_memoryview_access': 'test that a MemoryBlock supports memoryview access to inspect itemsize, shape, and strides', 'test_memoryblock_float_array': 'test a MemoryBlock created from a float array and cast the memoryview back to floats', 'test_memoryblock_pickle_roundtrip': 'test pickling a MemoryBlock with protocol 5 and verify data survives serialization and deserialization'}
```

## File: facebookresearch_fairseq2/tests/unit/data/test_read_pickle_wrapped_iterator.py

Prompts

```
['create a Collater to stack a bucket of lists into transposed nested lists', 'create a Collater to stack a bucket of PyTorch tensors into a single batched tensor', 'create a Collater with pad_value and pad_to_multiple to pad ragged sequence tensors', 'create a Collater with CollateOptionsOverride to apply different padding per dict key path', 'test the Collater collating ragged sequence tensors and returning seqs, seq_lens, and is_ragged', 'test the FileMapper class to map a file pathname to its binary data content', 'test the FileMapper class with an offset specifier to read from a byte offset', 'test the FileMapper class with offset and size specifiers to read a byte range', 'test the FileMapper class with a root directory to resolve relative pathnames', 'test the FileMapper class error handling for invalid input types and malformed pathnames', 'create a MemoryBlock from a Python array buffer that shares memory with the original array', 'create a MemoryBlock from a buffer with copy=True to snapshot data independent of the original', 'test that a MemoryBlock supports memoryview access to inspect itemsize, shape, and strides', 'test a MemoryBlock created from a float array and cast the memoryview back to floats', 'test pickling a MemoryBlock with protocol 5 and verify data survives serialization and deserialization', 'test that read_pickle_wrapped_iterator correctly saves and restores pipeline state via state_dict', 'test that read_iterator raises TypeError when given a non-picklable generator', 'test that calling reset on a pickle-wrapped iterator pipeline restarts iteration from the beginning', 'test that state_dict and load_state_dict resume iteration from the saved position', 'test the example_generator helper function that yields integers from 0 to 9']
```

Usage

```
{'test_read_pickle_wrapped_iterator': 'test that read_pickle_wrapped_iterator correctly saves and restores pipeline state via state_dict', 'test_read_iterator_type_error': 'test that read_iterator raises TypeError when given a non-picklable generator', 'test_pipeline_reset': 'test that calling reset on a pickle-wrapped iterator pipeline restarts iteration from the beginning', 'test_pipeline_state_save_restore': 'test that state_dict and load_state_dict resume iteration from the saved position', 'test_example_generator': 'test the example_generator helper function that yields integers from 0 to 9'}
```

