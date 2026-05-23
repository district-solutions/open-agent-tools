# Agent Python Tools

- repo: facebookresearch/stopes
- repo_uri: https://github.com/facebookresearch/stopes

## File: facebookresearch_stopes/stopes/modules/nmt_bitext_eval_utils.py

Prompts

```
['run SplitConcatBitextFiles module to filter and split a mined bitext TSV into source and target files', 'call split_mined_tsv to parse a scored bitext TSV and split columns into separate language files', 'call moses_clean_corpus to clean a parallel corpus using Moses clean-corpus-n.perl with length heuristics', 'call determine_valid_test_bleu to find the best validation BLEU score and matching test result', 'call parse_generated_bleu_files to parse multiple BLEU output files and group results by valid or test split', 'run a PartitionedDataMapper subclass to transform batches of input shards into output datasets', 'create a BatchMapper subclass with a __call__ method that transforms a batch to a batch', 'use the stopes_data_mapper decorator to wrap a BatchMapper class into a PartitionedDataMapper', 'get the source code for each class in a given class hierarchy using get_class_hierarchy_code', 'configure a PartitionedDataMapperConfig with input and output dataset sharding configs for batch processing', 'run distributed fairseq model training with multi-GPU support and checkpoint management', 'create a TrainFairseqConfig with GPU count, output directory, and fairseq training parameters', 'review the TrainFairseqModule requirements method to calculate cluster resource allocation for training jobs', 'review the TrainFairseqModule run method to understand distributed training setup and fairseq execution', 'review the TrainFairseqModule name method to understand task naming conventions for translation and other tasks']
```

Usage

```
{'run_split_concat_bitext_files': 'run SplitConcatBitextFiles module to filter and split a mined bitext TSV into source and target files', 'call_split_mined_tsv': 'call split_mined_tsv to parse a scored bitext TSV and split columns into separate language files', 'call_moses_clean_corpus': 'call moses_clean_corpus to clean a parallel corpus using Moses clean-corpus-n.perl with length heuristics', 'call_determine_valid_test_bleu': 'call determine_valid_test_bleu to find the best validation BLEU score and matching test result', 'call_parse_generated_bleu_files': 'call parse_generated_bleu_files to parse multiple BLEU output files and group results by valid or test split'}
```

## File: facebookresearch_stopes/stopes/modules/partitioned_data_mapper.py

Prompts

```
['run SplitConcatBitextFiles module to filter and split a mined bitext TSV into source and target files', 'call split_mined_tsv to parse a scored bitext TSV and split columns into separate language files', 'call moses_clean_corpus to clean a parallel corpus using Moses clean-corpus-n.perl with length heuristics', 'call determine_valid_test_bleu to find the best validation BLEU score and matching test result', 'call parse_generated_bleu_files to parse multiple BLEU output files and group results by valid or test split', 'run a PartitionedDataMapper subclass to transform batches of input shards into output datasets', 'create a BatchMapper subclass with a __call__ method that transforms a batch to a batch', 'use the stopes_data_mapper decorator to wrap a BatchMapper class into a PartitionedDataMapper', 'get the source code for each class in a given class hierarchy using get_class_hierarchy_code', 'configure a PartitionedDataMapperConfig with input and output dataset sharding configs for batch processing', 'run distributed fairseq model training with multi-GPU support and checkpoint management', 'create a TrainFairseqConfig with GPU count, output directory, and fairseq training parameters', 'review the TrainFairseqModule requirements method to calculate cluster resource allocation for training jobs', 'review the TrainFairseqModule run method to understand distributed training setup and fairseq execution', 'review the TrainFairseqModule name method to understand task naming conventions for translation and other tasks']
```

Usage

```
{'run_partitioned_data_mapper': 'run a PartitionedDataMapper subclass to transform batches of input shards into output datasets', 'create_batch_mapper': 'create a BatchMapper subclass with a __call__ method that transforms a batch to a batch', 'use_stopess_data_mapper_decorator': 'use the stopes_data_mapper decorator to wrap a BatchMapper class into a PartitionedDataMapper', 'get_class_hierarchy_code': 'get the source code for each class in a given class hierarchy using get_class_hierarchy_code', 'configure_partitioned_data_mapper': 'configure a PartitionedDataMapperConfig with input and output dataset sharding configs for batch processing'}
```

## File: facebookresearch_stopes/stopes/modules/train_fairseq_module.py

Prompts

```
['run SplitConcatBitextFiles module to filter and split a mined bitext TSV into source and target files', 'call split_mined_tsv to parse a scored bitext TSV and split columns into separate language files', 'call moses_clean_corpus to clean a parallel corpus using Moses clean-corpus-n.perl with length heuristics', 'call determine_valid_test_bleu to find the best validation BLEU score and matching test result', 'call parse_generated_bleu_files to parse multiple BLEU output files and group results by valid or test split', 'run a PartitionedDataMapper subclass to transform batches of input shards into output datasets', 'create a BatchMapper subclass with a __call__ method that transforms a batch to a batch', 'use the stopes_data_mapper decorator to wrap a BatchMapper class into a PartitionedDataMapper', 'get the source code for each class in a given class hierarchy using get_class_hierarchy_code', 'configure a PartitionedDataMapperConfig with input and output dataset sharding configs for batch processing', 'run distributed fairseq model training with multi-GPU support and checkpoint management', 'create a TrainFairseqConfig with GPU count, output directory, and fairseq training parameters', 'review the TrainFairseqModule requirements method to calculate cluster resource allocation for training jobs', 'review the TrainFairseqModule run method to understand distributed training setup and fairseq execution', 'review the TrainFairseqModule name method to understand task naming conventions for translation and other tasks']
```

Usage

```
{'run_fairseq_training': 'run distributed fairseq model training with multi-GPU support and checkpoint management', 'configure_train_fairseq': 'create a TrainFairseqConfig with GPU count, output directory, and fairseq training parameters', 'review_requirements_method': 'review the TrainFairseqModule requirements method to calculate cluster resource allocation for training jobs', 'review_run_method': 'review the TrainFairseqModule run method to understand distributed training setup and fairseq execution', 'review_name_method': 'review the TrainFairseqModule name method to understand task naming conventions for translation and other tasks'}
```

