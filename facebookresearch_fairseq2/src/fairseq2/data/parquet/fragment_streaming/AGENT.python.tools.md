# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/data/parquet/fragment_streaming/builder.py

Prompts

```
['build a ParquetFragmentStreamer pipeline to shard parquet fragments across distributed training ranks', 'create a ParquetFragmentStreamer with a FragmentStreamingConfig to stream parquet dataset fragments', 'review the ParquetFragmentStreamer full_schema property to inspect the parquet dataset schema', 'test the build_pipeline method to verify even and uneven sharding across world_size ranks', 'refactor the ParquetFragmentStreamer to handle files_circular_shift with fragment shuffle window conflicts', 'create a FragmentStreamingConfig dataclass to configure parquet dataset fragment streaming with path and shuffle options', 'create a ParquetDatasetLimitOptions dataclass to limit dataset loading by files, fragments, or rows', 'add a partition filter to a FragmentStreamingConfig to prune parquet partitions before reading', 'configure the fragment_shuffle_window on FragmentStreamingConfig to control randomization of row groups across files', 'set a ParquetDatasetLimitOptions on FragmentStreamingConfig to load only a fraction of files or rows', 'create a PyArrow Parquet dataset wrapper with hive partitioning and optional partition filters from a file path', 'build a data pipeline builder that lists and optionally splits Parquet fragments into row groups with shuffling and limits', 'create a streaming data pipeline builder that iterates over Parquet fragments with windowed shuffling and circular file shifting', 'build a PyArrow compute expression from a filter string, list of filters, or existing expression for dataset filtering', 'create a rejection sampling smoother to balance fragment distribution across partition groups using configurable alpha and min count']
```

Usage

```
{'build_parquet_fragment_pipeline': 'build a ParquetFragmentStreamer pipeline to shard parquet fragments across distributed training ranks', 'create_fragment_streamer_config': 'create a ParquetFragmentStreamer with a FragmentStreamingConfig to stream parquet dataset fragments', 'review_parquet_dataset_schema': 'review the ParquetFragmentStreamer full_schema property to inspect the parquet dataset schema', 'test_fragment_sharding': 'test the build_pipeline method to verify even and uneven sharding across world_size ranks', 'refactor_circular_shift_logic': 'refactor the ParquetFragmentStreamer to handle files_circular_shift with fragment shuffle window conflicts'}
```

## File: facebookresearch_fairseq2/src/fairseq2/data/parquet/fragment_streaming/config.py

Prompts

```
['build a ParquetFragmentStreamer pipeline to shard parquet fragments across distributed training ranks', 'create a ParquetFragmentStreamer with a FragmentStreamingConfig to stream parquet dataset fragments', 'review the ParquetFragmentStreamer full_schema property to inspect the parquet dataset schema', 'test the build_pipeline method to verify even and uneven sharding across world_size ranks', 'refactor the ParquetFragmentStreamer to handle files_circular_shift with fragment shuffle window conflicts', 'create a FragmentStreamingConfig dataclass to configure parquet dataset fragment streaming with path and shuffle options', 'create a ParquetDatasetLimitOptions dataclass to limit dataset loading by files, fragments, or rows', 'add a partition filter to a FragmentStreamingConfig to prune parquet partitions before reading', 'configure the fragment_shuffle_window on FragmentStreamingConfig to control randomization of row groups across files', 'set a ParquetDatasetLimitOptions on FragmentStreamingConfig to load only a fraction of files or rows', 'create a PyArrow Parquet dataset wrapper with hive partitioning and optional partition filters from a file path', 'build a data pipeline builder that lists and optionally splits Parquet fragments into row groups with shuffling and limits', 'create a streaming data pipeline builder that iterates over Parquet fragments with windowed shuffling and circular file shifting', 'build a PyArrow compute expression from a filter string, list of filters, or existing expression for dataset filtering', 'create a rejection sampling smoother to balance fragment distribution across partition groups using configurable alpha and min count']
```

Usage

```
{'create_fragment_streaming_config': 'create a FragmentStreamingConfig dataclass to configure parquet dataset fragment streaming with path and shuffle options', 'create_parquet_dataset_limit_options': 'create a ParquetDatasetLimitOptions dataclass to limit dataset loading by files, fragments, or rows', 'add_partition_filter': 'add a partition filter to a FragmentStreamingConfig to prune parquet partitions before reading', 'configure_fragment_shuffle_window': 'configure the fragment_shuffle_window on FragmentStreamingConfig to control randomization of row groups across files', 'set_parquet_dataset_limit': 'set a ParquetDatasetLimitOptions on FragmentStreamingConfig to load only a fraction of files or rows'}
```

## File: facebookresearch_fairseq2/src/fairseq2/data/parquet/fragment_streaming/primitives.py

Prompts

```
['build a ParquetFragmentStreamer pipeline to shard parquet fragments across distributed training ranks', 'create a ParquetFragmentStreamer with a FragmentStreamingConfig to stream parquet dataset fragments', 'review the ParquetFragmentStreamer full_schema property to inspect the parquet dataset schema', 'test the build_pipeline method to verify even and uneven sharding across world_size ranks', 'refactor the ParquetFragmentStreamer to handle files_circular_shift with fragment shuffle window conflicts', 'create a FragmentStreamingConfig dataclass to configure parquet dataset fragment streaming with path and shuffle options', 'create a ParquetDatasetLimitOptions dataclass to limit dataset loading by files, fragments, or rows', 'add a partition filter to a FragmentStreamingConfig to prune parquet partitions before reading', 'configure the fragment_shuffle_window on FragmentStreamingConfig to control randomization of row groups across files', 'set a ParquetDatasetLimitOptions on FragmentStreamingConfig to load only a fraction of files or rows', 'create a PyArrow Parquet dataset wrapper with hive partitioning and optional partition filters from a file path', 'build a data pipeline builder that lists and optionally splits Parquet fragments into row groups with shuffling and limits', 'create a streaming data pipeline builder that iterates over Parquet fragments with windowed shuffling and circular file shifting', 'build a PyArrow compute expression from a filter string, list of filters, or existing expression for dataset filtering', 'create a rejection sampling smoother to balance fragment distribution across partition groups using configurable alpha and min count']
```

Usage

```
{'init_parquet_dataset': 'create a PyArrow Parquet dataset wrapper with hive partitioning and optional partition filters from a file path', 'list_parquet_fragments': 'build a data pipeline builder that lists and optionally splits Parquet fragments into row groups with shuffling and limits', 'stream_parquet_fragments': 'create a streaming data pipeline builder that iterates over Parquet fragments with windowed shuffling and circular file shifting', 'process_filter': 'build a PyArrow compute expression from a filter string, list of filters, or existing expression for dataset filtering', 'RejectionDistributionSmoother': 'create a rejection sampling smoother to balance fragment distribution across partition groups using configurable alpha and min count'}
```

