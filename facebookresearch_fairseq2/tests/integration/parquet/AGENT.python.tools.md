# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/tests/integration/parquet/conftest.py

Prompts

```
['create a pytest fixture that writes a temporary parquet file and yields its fragment', 'create a pytest fixture that generates multiple parquet fragments across separate temp files', 'create a pytest fixture that builds a hive-partitioned parquet dataset in a temp directory', 'create a pytest fixture that writes a parquet file with multiple row groups using a small row group size', 'create a pytest fixture that builds a partitioned parquet dataset with text, tokens, and length columns', 'build a SafeFragment from a parquet file fragment and load all or specific columns into a PyArrow table', 'build a pipeline to list parquet fragments with optional row group splitting and shuffle window support', 'build a batching loop over a single PyArrow table with optional length ordering and max tokens constraints', 'build a complete parquet data loading pipeline using BasicDataLoadingConfig with fragment streaming and table bucketing', 'use pyarrow_table_to_torch_dict to convert a PyArrow table batch into a torch tensor dictionary']
```

Usage

```
{'create_test_parquet_file_fixture': 'create a pytest fixture that writes a temporary parquet file and yields its fragment', 'create_test_fragments_fixture': 'create a pytest fixture that generates multiple parquet fragments across separate temp files', 'create_partitioned_dataset_fixture': 'create a pytest fixture that builds a hive-partitioned parquet dataset in a temp directory', 'create_multi_row_group_dataset_fixture': 'create a pytest fixture that writes a parquet file with multiple row groups using a small row group size', 'create_complex_dataset_fixture': 'create a pytest fixture that builds a partitioned parquet dataset with text, tokens, and length columns'}
```

## File: facebookresearch_fairseq2/tests/integration/parquet/test_parquet_pipeline.py

Prompts

```
['create a pytest fixture that writes a temporary parquet file and yields its fragment', 'create a pytest fixture that generates multiple parquet fragments across separate temp files', 'create a pytest fixture that builds a hive-partitioned parquet dataset in a temp directory', 'create a pytest fixture that writes a parquet file with multiple row groups using a small row group size', 'create a pytest fixture that builds a partitioned parquet dataset with text, tokens, and length columns', 'build a SafeFragment from a parquet file fragment and load all or specific columns into a PyArrow table', 'build a pipeline to list parquet fragments with optional row group splitting and shuffle window support', 'build a batching loop over a single PyArrow table with optional length ordering and max tokens constraints', 'build a complete parquet data loading pipeline using BasicDataLoadingConfig with fragment streaming and table bucketing', 'use pyarrow_table_to_torch_dict to convert a PyArrow table batch into a torch tensor dictionary']
```

Usage

```
{'build_SafeFragment_load': 'build a SafeFragment from a parquet file fragment and load all or specific columns into a PyArrow table', 'build_list_parquet_fragments': 'build a pipeline to list parquet fragments with optional row group splitting and shuffle window support', 'build_build_batching_loop_over_one_table': 'build a batching loop over a single PyArrow table with optional length ordering and max tokens constraints', 'build_build_basic_parquet_data_pipeline': 'build a complete parquet data loading pipeline using BasicDataLoadingConfig with fragment streaming and table bucketing', 'use_pyarrow_table_to_torch_dict': 'use pyarrow_table_to_torch_dict to convert a PyArrow table batch into a torch tensor dictionary'}
```

