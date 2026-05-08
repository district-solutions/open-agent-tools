# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/data/parquet/fragment_loading/builder.py

Prompts

```
['create a SafeFragment wrapper around a ParquetFileFragment to handle expired AWS session tokens', 'load a Parquet fragment into a PyArrow table with automatic retry on OSError', 'compute a stable hash of a Parquet file fragment for deterministic ordering', 'build a DataPipelineBuilder that loads Parquet fragments with parallel calls and prefetching', 'apply a ParquetFragmentLoader to a fragment pipeline with configurable columns, filters, and caching', 'create a NamedColumns subclass to map and rename dataset columns when loading parquet fragments', 'call get_flatten_columns on a NamedColumns instance to get the full list of columns to load', 'call get_renaming_mapper on a NamedColumns instance to get the original to renamed column mapping dict', 'create a FragmentLoadingConfig to configure parquet fragment loading with column selection, filtering, and caching options', 'review a FragmentLoadingConfig to check drop_null, filters, parallel fragment count, and cache settings']
```

Usage

```
{'create_safe_fragment_wrapper': 'create a SafeFragment wrapper around a ParquetFileFragment to handle expired AWS session tokens', 'load_parquet_fragment_with_retry': 'load a Parquet fragment into a PyArrow table with automatic retry on OSError', 'compute_fragment_stable_hash': 'compute a stable hash of a Parquet file fragment for deterministic ordering', 'build_fragment_loading_pipeline': 'build a DataPipelineBuilder that loads Parquet fragments with parallel calls and prefetching', 'apply_fragment_loader_to_pipeline': 'apply a ParquetFragmentLoader to a fragment pipeline with configurable columns, filters, and caching'}
```

## File: facebookresearch_fairseq2/src/fairseq2/data/parquet/fragment_loading/config.py

Prompts

```
['create a SafeFragment wrapper around a ParquetFileFragment to handle expired AWS session tokens', 'load a Parquet fragment into a PyArrow table with automatic retry on OSError', 'compute a stable hash of a Parquet file fragment for deterministic ordering', 'build a DataPipelineBuilder that loads Parquet fragments with parallel calls and prefetching', 'apply a ParquetFragmentLoader to a fragment pipeline with configurable columns, filters, and caching', 'create a NamedColumns subclass to map and rename dataset columns when loading parquet fragments', 'call get_flatten_columns on a NamedColumns instance to get the full list of columns to load', 'call get_renaming_mapper on a NamedColumns instance to get the original to renamed column mapping dict', 'create a FragmentLoadingConfig to configure parquet fragment loading with column selection, filtering, and caching options', 'review a FragmentLoadingConfig to check drop_null, filters, parallel fragment count, and cache settings']
```

Usage

```
{'create_named_columns_subclass': 'create a NamedColumns subclass to map and rename dataset columns when loading parquet fragments', 'get_flatten_columns': 'call get_flatten_columns on a NamedColumns instance to get the full list of columns to load', 'get_renaming_mapper': 'call get_renaming_mapper on a NamedColumns instance to get the original to renamed column mapping dict', 'create_fragment_loading_config': 'create a FragmentLoadingConfig to configure parquet fragment loading with column selection, filtering, and caching options', 'review_fragment_loading_config': 'review a FragmentLoadingConfig to check drop_null, filters, parallel fragment count, and cache settings'}
```

