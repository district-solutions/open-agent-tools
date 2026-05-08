# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/data/parquet/table_bucketing/builder.py

Prompts

```
['build a TableBucketer instance with a TableBucketingConfig to bucket PyArrow tables by memory, size, or length', 'apply a TableBucketer to a DataPipelineBuilder to dynamically bucket and batch PyArrow tables', 'review the TableBucketer constructor to understand validation of target_table_memory, target_total_length, and target_table_size', 'refactor the TableBucketer apply method to add custom bucketing strategies beyond memory, size, and length', 'test the TableBucketer apply method with different config targets to verify dynamic bucketing behavior', 'split sequence lengths into chunks where padded length stays under a max tokens threshold', 'compute the length of each row in a PyArrow array handling integers, lists, and strings', 'build a DataPipeline that batches a PyArrow table by fixed size or max tokens with optional shuffling', 'test the compute_length_splits function to verify it correctly groups indices by padded token budget', 'review the build_batching_loop_over_one_table function to understand its batching strategy and reducer options']
```

Usage

```
{'build_TableBucketer': 'build a TableBucketer instance with a TableBucketingConfig to bucket PyArrow tables by memory, size, or length', 'apply_TableBucketer': 'apply a TableBucketer to a DataPipelineBuilder to dynamically bucket and batch PyArrow tables', 'review_TableBucketer_init': 'review the TableBucketer constructor to understand validation of target_table_memory, target_total_length, and target_table_size', 'refactor_TableBucketer_apply': 'refactor the TableBucketer apply method to add custom bucketing strategies beyond memory, size, and length', 'test_TableBucketer_dynamic_bucket': 'test the TableBucketer apply method with different config targets to verify dynamic bucketing behavior'}
```

## File: facebookresearch_fairseq2/src/fairseq2/data/parquet/table_bucketing/primitives.py

Prompts

```
['build a TableBucketer instance with a TableBucketingConfig to bucket PyArrow tables by memory, size, or length', 'apply a TableBucketer to a DataPipelineBuilder to dynamically bucket and batch PyArrow tables', 'review the TableBucketer constructor to understand validation of target_table_memory, target_total_length, and target_table_size', 'refactor the TableBucketer apply method to add custom bucketing strategies beyond memory, size, and length', 'test the TableBucketer apply method with different config targets to verify dynamic bucketing behavior', 'split sequence lengths into chunks where padded length stays under a max tokens threshold', 'compute the length of each row in a PyArrow array handling integers, lists, and strings', 'build a DataPipeline that batches a PyArrow table by fixed size or max tokens with optional shuffling', 'test the compute_length_splits function to verify it correctly groups indices by padded token budget', 'review the build_batching_loop_over_one_table function to understand its batching strategy and reducer options']
```

Usage

```
{'compute_length_splits': 'split sequence lengths into chunks where padded length stays under a max tokens threshold', 'compute_rows_length': 'compute the length of each row in a PyArrow array handling integers, lists, and strings', 'build_batching_loop_over_one_table': 'build a DataPipeline that batches a PyArrow table by fixed size or max tokens with optional shuffling', 'test_compute_length_splits': 'test the compute_length_splits function to verify it correctly groups indices by padded token budget', 'review_build_batching_loop_over_one_table': 'review the build_batching_loop_over_one_table function to understand its batching strategy and reducer options'}
```

