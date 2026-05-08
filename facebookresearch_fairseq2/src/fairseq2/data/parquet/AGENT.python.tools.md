# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/data/parquet/arrow_transform.py

Prompts

```
['shuffle the rows of a PyArrow table using a random permutation', 'filter a PyArrow table rows where list-of-strings column values fall within a min and max length range', 'filter a PyArrow table rows where list-of-numbers column values fall within a min and max value range', 'concatenate a list of PyArrow tables into a single combined table', 'filter a PyArrow table rows where list columns have element counts within a specified min and max length range', 'convert a pyarrow table to a nested dict of torch tensors using pyarrow_table_to_torch_dict', 'convert a pyarrow array to a torch tensor using pyarrow_to_torch_tensor with strict mode', 'compute a stable hash for a pyarrow dataset fragment using fragment_stable_hash with an optional seed', 'add partitioning columns to a pyarrow table from a fragment using add_partitioning_values', 'write a pyarrow table to a memory-mapped Arrow file with automatic cleanup using table_to_mmap_table']
```

Usage

```
{'shuffle_pyarrow_table': 'shuffle the rows of a PyArrow table using a random permutation', 'filter_strings_by_length': 'filter a PyArrow table rows where list-of-strings column values fall within a min and max length range', 'filter_list_by_range': 'filter a PyArrow table rows where list-of-numbers column values fall within a min and max value range', 'concat_pyarrow_tables': 'concatenate a list of PyArrow tables into a single combined table', 'filter_list_with_min_max_length': 'filter a PyArrow table rows where list columns have element counts within a specified min and max length range'}
```

## File: facebookresearch_fairseq2/src/fairseq2/data/parquet/utils.py

Prompts

```
['shuffle the rows of a PyArrow table using a random permutation', 'filter a PyArrow table rows where list-of-strings column values fall within a min and max length range', 'filter a PyArrow table rows where list-of-numbers column values fall within a min and max value range', 'concatenate a list of PyArrow tables into a single combined table', 'filter a PyArrow table rows where list columns have element counts within a specified min and max length range', 'convert a pyarrow table to a nested dict of torch tensors using pyarrow_table_to_torch_dict', 'convert a pyarrow array to a torch tensor using pyarrow_to_torch_tensor with strict mode', 'compute a stable hash for a pyarrow dataset fragment using fragment_stable_hash with an optional seed', 'add partitioning columns to a pyarrow table from a fragment using add_partitioning_values', 'write a pyarrow table to a memory-mapped Arrow file with automatic cleanup using table_to_mmap_table']
```

Usage

```
{'convert_pyarrow_table_to_torch_dict': 'convert a pyarrow table to a nested dict of torch tensors using pyarrow_table_to_torch_dict', 'convert_pyarrow_array_to_torch_tensor': 'convert a pyarrow array to a torch tensor using pyarrow_to_torch_tensor with strict mode', 'compute_fragment_stable_hash': 'compute a stable hash for a pyarrow dataset fragment using fragment_stable_hash with an optional seed', 'add_partitioning_values_to_table': 'add partitioning columns to a pyarrow table from a fragment using add_partitioning_values', 'create_memory_mapped_arrow_table': 'write a pyarrow table to a memory-mapped Arrow file with automatic cleanup using table_to_mmap_table'}
```

