# Agent Python Tools

- repo: facebookresearch/fairo
- repo_uri: https://github.com/facebookresearch/fairo

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/nsp_transformer_model/processing_scripts/gen_cross_valid_chunks.py

Prompts

```
['run the script to partition a dataset into k chunks for cross validation', 'run the script to create train and valid splits from k dataset chunks', 'partition a dataset into k shuffled chunks and write each chunk to a separate directory', 'create train and validation splits from pre-partitioned chunks for k-fold cross validation', 'review the partition_dataset function that shuffles and splits annotated data into k equal chunks', 'create a k-fold cross validation train and valid split from chunked annotated data directories', 'generate recombined chat and tree data by swapping fragments between templates and fragments', 'process a chat string by removing a token span and inserting an unknown token placeholder', 'insert a fragment string into a templated chat at the unknown token placeholder position', 'write recombined data samples to an output directory as JSON from tool1 and tool2 Turk data', 'filter Turk tool1 lines to keep only those matching training dataset phrases and node types', 'filter Turk tool2 lines to keep only those with matching chat, tag, and node type criteria', 'build a dictionary mapping chat commands to their tree insertions parsed from tab-separated lines', 'postprocess a Turk tool generated tree to convert action types and format for model datasets', 'update tree span indices by a given shift amount and reformat Turk-style spans to dataset format']
```

Usage

```
{'run_k_fold_partition': 'run the script to partition a dataset into k chunks for cross validation', 'run_train_valid_split': 'run the script to create train and valid splits from k dataset chunks', 'partition_dataset_function': 'partition a dataset into k shuffled chunks and write each chunk to a separate directory', 'create_train_valid_split_function': 'create train and validation splits from pre-partitioned chunks for k-fold cross validation', 'review_partition_dataset': 'review the partition_dataset function that shuffles and splits annotated data into k equal chunks'}
```

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/nsp_transformer_model/processing_scripts/recombine_data.py

Prompts

```
['run the script to partition a dataset into k chunks for cross validation', 'run the script to create train and valid splits from k dataset chunks', 'partition a dataset into k shuffled chunks and write each chunk to a separate directory', 'create train and validation splits from pre-partitioned chunks for k-fold cross validation', 'review the partition_dataset function that shuffles and splits annotated data into k equal chunks', 'create a k-fold cross validation train and valid split from chunked annotated data directories', 'generate recombined chat and tree data by swapping fragments between templates and fragments', 'process a chat string by removing a token span and inserting an unknown token placeholder', 'insert a fragment string into a templated chat at the unknown token placeholder position', 'write recombined data samples to an output directory as JSON from tool1 and tool2 Turk data', 'filter Turk tool1 lines to keep only those matching training dataset phrases and node types', 'filter Turk tool2 lines to keep only those with matching chat, tag, and node type criteria', 'build a dictionary mapping chat commands to their tree insertions parsed from tab-separated lines', 'postprocess a Turk tool generated tree to convert action types and format for model datasets', 'update tree span indices by a given shift amount and reformat Turk-style spans to dataset format']
```

Usage

```
{'create_k_fold_train_valid_split': 'create a k-fold cross validation train and valid split from chunked annotated data directories', 'generate_recombined_data_from_templates_and_fragments': 'generate recombined chat and tree data by swapping fragments between templates and fragments', 'process_chat_with_span_replacement': 'process a chat string by removing a token span and inserting an unknown token placeholder', 'insert_fragment_into_templated_chat': 'insert a fragment string into a templated chat at the unknown token placeholder position', 'write_recombined_data_chunk': 'write recombined data samples to an output directory as JSON from tool1 and tool2 Turk data'}
```

## File: facebookresearch_fairo/droidlet/perception/semantic_parsing/nsp_transformer_model/processing_scripts/recombine_data_utils.py

Prompts

```
['run the script to partition a dataset into k chunks for cross validation', 'run the script to create train and valid splits from k dataset chunks', 'partition a dataset into k shuffled chunks and write each chunk to a separate directory', 'create train and validation splits from pre-partitioned chunks for k-fold cross validation', 'review the partition_dataset function that shuffles and splits annotated data into k equal chunks', 'create a k-fold cross validation train and valid split from chunked annotated data directories', 'generate recombined chat and tree data by swapping fragments between templates and fragments', 'process a chat string by removing a token span and inserting an unknown token placeholder', 'insert a fragment string into a templated chat at the unknown token placeholder position', 'write recombined data samples to an output directory as JSON from tool1 and tool2 Turk data', 'filter Turk tool1 lines to keep only those matching training dataset phrases and node types', 'filter Turk tool2 lines to keep only those with matching chat, tag, and node type criteria', 'build a dictionary mapping chat commands to their tree insertions parsed from tab-separated lines', 'postprocess a Turk tool generated tree to convert action types and format for model datasets', 'update tree span indices by a given shift amount and reformat Turk-style spans to dataset format']
```

Usage

```
{'filter_tool1_lines': 'filter Turk tool1 lines to keep only those matching training dataset phrases and node types', 'filter_tool2_lines': 'filter Turk tool2 lines to keep only those with matching chat, tag, and node type criteria', 'build_tree_inserts_dict': 'build a dictionary mapping chat commands to their tree insertions parsed from tab-separated lines', 'postprocess_tree': 'postprocess a Turk tool generated tree to convert action types and format for model datasets', 'update_tree_spans': 'update tree span indices by a given shift amount and reformat Turk-style spans to dataset format'}
```

