# Agent Python Tools

- repo: facebookresearch/blt
- repo_uri: https://github.com/facebookresearch/blt

## File: facebookresearch_blt/bytelatent/data/data_types.py

Prompts

```
['create a BltExample with sample_id, text, tokens, entropies, patch_lengths, and mask fields', 'create a BltSequence with tokens, mask, and optional patch_lengths for a byte latent sequence', 'create a BltPackTokensState to configure token packing with start_token, output_seq_len, and n_views', 'convert a Batch dataclass to a plain Python dictionary using to_python_dict method', 'deserialize a Batch dataclass from a plain Python dictionary using from_python_dict class method', 'check if a given file path is a valid PyArrow dataset file', 'get an fsspec filesystem object for S3 or local file paths with retry config', 'run the CLI command to find local files safe to delete after S3 upload', 'run the CLI command to compare local directory files against an S3 blob directory', 'review the get_fs function that returns fsspec filesystems for S3 or local paths', 'create an NgramProcessor instance with a table directory and ngram-to-size mapping to load lookup tables', 'encode byte array data into n-gram IDs for all configured n-gram sizes using NgramProcessor', 'encode byte array data into n-gram IDs for a single specified n-gram size using NgramProcessor', 'reload n-gram lookup tables from pickle files in a directory with specified size limits per n-gram', 'parse a comma-separated ngram-to-size string like 2:1000,3:5000 into a dictionary mapping', 'build a Patcher from PatcherArgs to tokenize sequences into variable-length patches using entropy or static mode', 'calculate per-token entropies for a batch of token tensors using a loaded entropy model', 'find patch start IDs from entropy scores using a threshold or fixed patch size strategy', 'find patch start IDs by running tokens through a BPE patcher model to predict patch boundaries', 'patch a 2D token tensor into variable-length patch lengths using entropy, BPE, space, or static mode', 'run the pytest test that validates the first training batch matches a pickled fixture', 'test the get_test_config function that resolves the internal BLT test YAML config path', 'test merging default TrainArgs with a YAML config file using OmegaConf', 'test building a data loader from a specific rank and world size for multi-GPU training', 'test creating a batch iterator and fetching the first batch from the data loader']
```

Usage

```
{'create_BltExample': 'create a BltExample with sample_id, text, tokens, entropies, patch_lengths, and mask fields', 'create_BltSequence': 'create a BltSequence with tokens, mask, and optional patch_lengths for a byte latent sequence', 'create_BltPackTokensState': 'create a BltPackTokensState to configure token packing with start_token, output_seq_len, and n_views', 'convert_Batch_to_python_dict': 'convert a Batch dataclass to a plain Python dictionary using to_python_dict method', 'deserialize_Batch_from_python_dict': 'deserialize a Batch dataclass from a plain Python dictionary using from_python_dict class method'}
```

## File: facebookresearch_blt/bytelatent/data/file_util.py

Prompts

```
['create a BltExample with sample_id, text, tokens, entropies, patch_lengths, and mask fields', 'create a BltSequence with tokens, mask, and optional patch_lengths for a byte latent sequence', 'create a BltPackTokensState to configure token packing with start_token, output_seq_len, and n_views', 'convert a Batch dataclass to a plain Python dictionary using to_python_dict method', 'deserialize a Batch dataclass from a plain Python dictionary using from_python_dict class method', 'check if a given file path is a valid PyArrow dataset file', 'get an fsspec filesystem object for S3 or local file paths with retry config', 'run the CLI command to find local files safe to delete after S3 upload', 'run the CLI command to compare local directory files against an S3 blob directory', 'review the get_fs function that returns fsspec filesystems for S3 or local paths', 'create an NgramProcessor instance with a table directory and ngram-to-size mapping to load lookup tables', 'encode byte array data into n-gram IDs for all configured n-gram sizes using NgramProcessor', 'encode byte array data into n-gram IDs for a single specified n-gram size using NgramProcessor', 'reload n-gram lookup tables from pickle files in a directory with specified size limits per n-gram', 'parse a comma-separated ngram-to-size string like 2:1000,3:5000 into a dictionary mapping', 'build a Patcher from PatcherArgs to tokenize sequences into variable-length patches using entropy or static mode', 'calculate per-token entropies for a batch of token tensors using a loaded entropy model', 'find patch start IDs from entropy scores using a threshold or fixed patch size strategy', 'find patch start IDs by running tokens through a BPE patcher model to predict patch boundaries', 'patch a 2D token tensor into variable-length patch lengths using entropy, BPE, space, or static mode', 'run the pytest test that validates the first training batch matches a pickled fixture', 'test the get_test_config function that resolves the internal BLT test YAML config path', 'test merging default TrainArgs with a YAML config file using OmegaConf', 'test building a data loader from a specific rank and world size for multi-GPU training', 'test creating a batch iterator and fetching the first batch from the data loader']
```

Usage

```
{'validate_arrow_file': 'check if a given file path is a valid PyArrow dataset file', 'get_filesystem_for_path': 'get an fsspec filesystem object for S3 or local file paths with retry config', 'run_print_local_to_delete': 'run the CLI command to find local files safe to delete after S3 upload', 'run_compare_local_to_blob': 'run the CLI command to compare local directory files against an S3 blob directory', 'review_get_fs': 'review the get_fs function that returns fsspec filesystems for S3 or local paths'}
```

## File: facebookresearch_blt/bytelatent/data/ngram_processor.py

Prompts

```
['create a BltExample with sample_id, text, tokens, entropies, patch_lengths, and mask fields', 'create a BltSequence with tokens, mask, and optional patch_lengths for a byte latent sequence', 'create a BltPackTokensState to configure token packing with start_token, output_seq_len, and n_views', 'convert a Batch dataclass to a plain Python dictionary using to_python_dict method', 'deserialize a Batch dataclass from a plain Python dictionary using from_python_dict class method', 'check if a given file path is a valid PyArrow dataset file', 'get an fsspec filesystem object for S3 or local file paths with retry config', 'run the CLI command to find local files safe to delete after S3 upload', 'run the CLI command to compare local directory files against an S3 blob directory', 'review the get_fs function that returns fsspec filesystems for S3 or local paths', 'create an NgramProcessor instance with a table directory and ngram-to-size mapping to load lookup tables', 'encode byte array data into n-gram IDs for all configured n-gram sizes using NgramProcessor', 'encode byte array data into n-gram IDs for a single specified n-gram size using NgramProcessor', 'reload n-gram lookup tables from pickle files in a directory with specified size limits per n-gram', 'parse a comma-separated ngram-to-size string like 2:1000,3:5000 into a dictionary mapping', 'build a Patcher from PatcherArgs to tokenize sequences into variable-length patches using entropy or static mode', 'calculate per-token entropies for a batch of token tensors using a loaded entropy model', 'find patch start IDs from entropy scores using a threshold or fixed patch size strategy', 'find patch start IDs by running tokens through a BPE patcher model to predict patch boundaries', 'patch a 2D token tensor into variable-length patch lengths using entropy, BPE, space, or static mode', 'run the pytest test that validates the first training batch matches a pickled fixture', 'test the get_test_config function that resolves the internal BLT test YAML config path', 'test merging default TrainArgs with a YAML config file using OmegaConf', 'test building a data loader from a specific rank and world size for multi-GPU training', 'test creating a batch iterator and fetching the first batch from the data loader']
```

Usage

```
{'create_NgramProcessor': 'create an NgramProcessor instance with a table directory and ngram-to-size mapping to load lookup tables', 'encode_token_ngrams': 'encode byte array data into n-gram IDs for all configured n-gram sizes using NgramProcessor', 'encode_single_ngram_table': 'encode byte array data into n-gram IDs for a single specified n-gram size using NgramProcessor', 'reload_tables': 'reload n-gram lookup tables from pickle files in a directory with specified size limits per n-gram', 'parse_ngram_to_size': 'parse a comma-separated ngram-to-size string like 2:1000,3:5000 into a dictionary mapping'}
```

## File: facebookresearch_blt/bytelatent/data/patcher.py

Prompts

```
['create a BltExample with sample_id, text, tokens, entropies, patch_lengths, and mask fields', 'create a BltSequence with tokens, mask, and optional patch_lengths for a byte latent sequence', 'create a BltPackTokensState to configure token packing with start_token, output_seq_len, and n_views', 'convert a Batch dataclass to a plain Python dictionary using to_python_dict method', 'deserialize a Batch dataclass from a plain Python dictionary using from_python_dict class method', 'check if a given file path is a valid PyArrow dataset file', 'get an fsspec filesystem object for S3 or local file paths with retry config', 'run the CLI command to find local files safe to delete after S3 upload', 'run the CLI command to compare local directory files against an S3 blob directory', 'review the get_fs function that returns fsspec filesystems for S3 or local paths', 'create an NgramProcessor instance with a table directory and ngram-to-size mapping to load lookup tables', 'encode byte array data into n-gram IDs for all configured n-gram sizes using NgramProcessor', 'encode byte array data into n-gram IDs for a single specified n-gram size using NgramProcessor', 'reload n-gram lookup tables from pickle files in a directory with specified size limits per n-gram', 'parse a comma-separated ngram-to-size string like 2:1000,3:5000 into a dictionary mapping', 'build a Patcher from PatcherArgs to tokenize sequences into variable-length patches using entropy or static mode', 'calculate per-token entropies for a batch of token tensors using a loaded entropy model', 'find patch start IDs from entropy scores using a threshold or fixed patch size strategy', 'find patch start IDs by running tokens through a BPE patcher model to predict patch boundaries', 'patch a 2D token tensor into variable-length patch lengths using entropy, BPE, space, or static mode', 'run the pytest test that validates the first training batch matches a pickled fixture', 'test the get_test_config function that resolves the internal BLT test YAML config path', 'test merging default TrainArgs with a YAML config file using OmegaConf', 'test building a data loader from a specific rank and world size for multi-GPU training', 'test creating a batch iterator and fetching the first batch from the data loader']
```

Usage

```
{'build_Patcher': 'build a Patcher from PatcherArgs to tokenize sequences into variable-length patches using entropy or static mode', 'calculate_entropies_tokens': 'calculate per-token entropies for a batch of token tensors using a loaded entropy model', 'find_entropy_patch_start_ids': 'find patch start IDs from entropy scores using a threshold or fixed patch size strategy', 'find_bpe_patcher_patch_start_ids': 'find patch start IDs by running tokens through a BPE patcher model to predict patch boundaries', 'patch_tokens': 'patch a 2D token tensor into variable-length patch lengths using entropy, BPE, space, or static mode'}
```

## File: facebookresearch_blt/bytelatent/data/test_data.py

Prompts

```
['create a BltExample with sample_id, text, tokens, entropies, patch_lengths, and mask fields', 'create a BltSequence with tokens, mask, and optional patch_lengths for a byte latent sequence', 'create a BltPackTokensState to configure token packing with start_token, output_seq_len, and n_views', 'convert a Batch dataclass to a plain Python dictionary using to_python_dict method', 'deserialize a Batch dataclass from a plain Python dictionary using from_python_dict class method', 'check if a given file path is a valid PyArrow dataset file', 'get an fsspec filesystem object for S3 or local file paths with retry config', 'run the CLI command to find local files safe to delete after S3 upload', 'run the CLI command to compare local directory files against an S3 blob directory', 'review the get_fs function that returns fsspec filesystems for S3 or local paths', 'create an NgramProcessor instance with a table directory and ngram-to-size mapping to load lookup tables', 'encode byte array data into n-gram IDs for all configured n-gram sizes using NgramProcessor', 'encode byte array data into n-gram IDs for a single specified n-gram size using NgramProcessor', 'reload n-gram lookup tables from pickle files in a directory with specified size limits per n-gram', 'parse a comma-separated ngram-to-size string like 2:1000,3:5000 into a dictionary mapping', 'build a Patcher from PatcherArgs to tokenize sequences into variable-length patches using entropy or static mode', 'calculate per-token entropies for a batch of token tensors using a loaded entropy model', 'find patch start IDs from entropy scores using a threshold or fixed patch size strategy', 'find patch start IDs by running tokens through a BPE patcher model to predict patch boundaries', 'patch a 2D token tensor into variable-length patch lengths using entropy, BPE, space, or static mode', 'run the pytest test that validates the first training batch matches a pickled fixture', 'test the get_test_config function that resolves the internal BLT test YAML config path', 'test merging default TrainArgs with a YAML config file using OmegaConf', 'test building a data loader from a specific rank and world size for multi-GPU training', 'test creating a batch iterator and fetching the first batch from the data loader']
```

Usage

```
{'run_test_first_batch_matches': 'run the pytest test that validates the first training batch matches a pickled fixture', 'test_get_test_config': 'test the get_test_config function that resolves the internal BLT test YAML config path', 'test_train_args_config_merge': 'test merging default TrainArgs with a YAML config file using OmegaConf', 'test_data_loader_build_from_rank': 'test building a data loader from a specific rank and world size for multi-GPU training', 'test_batch_iteration': 'test creating a batch iterator and fetching the first batch from the data loader'}
```

