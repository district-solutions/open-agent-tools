# Agent Python Tools

- repo: facebookresearch/code-prediction-transformer
- repo_uri: https://github.com/facebookresearch/code-prediction-transformer

## File: facebookresearch_code-prediction-transformer/models/path_trans_variation/dataset.py

Prompts

```
['create a Setup instance that builds a Vocab from a vocab file path', 'create a Setup instance that builds a Dataset from file paths', 'convert a sequence of tokens to vocabulary indices using Vocab convert method', 'collate a batch of sequences into padded PyTorch tensors using Dataset collate', 'review the Dataset collate method to understand how sequences are padded and shifted', 'run generate_data.py with an AST JSON-lines file to produce augmented datapoints for training', 'use get_leaf_info to extract leaf tokens and their indices from an AST node list', 'use get_dps to generate sliding window datapoints with configurable max length from an AST', 'run the script with --ast_fp and --out_fp arguments to generate and write datapoints to a file', 'set the --n_ctx argument to control the maximum number of tokens per generated datapoint']
```

Usage

```
{'create_setup_vocab': 'create a Setup instance that builds a Vocab from a vocab file path', 'create_setup_dataset': 'create a Setup instance that builds a Dataset from file paths', 'convert_vocab_tokens': 'convert a sequence of tokens to vocabulary indices using Vocab convert method', 'collate_dataset_sequences': 'collate a batch of sequences into padded PyTorch tensors using Dataset collate', 'review_dataset_collate_padding': 'review the Dataset collate method to understand how sequences are padded and shifted'}
```

## File: facebookresearch_code-prediction-transformer/models/path_trans_variation/generate_data.py

Prompts

```
['create a Setup instance that builds a Vocab from a vocab file path', 'create a Setup instance that builds a Dataset from file paths', 'convert a sequence of tokens to vocabulary indices using Vocab convert method', 'collate a batch of sequences into padded PyTorch tensors using Dataset collate', 'review the Dataset collate method to understand how sequences are padded and shifted', 'run generate_data.py with an AST JSON-lines file to produce augmented datapoints for training', 'use get_leaf_info to extract leaf tokens and their indices from an AST node list', 'use get_dps to generate sliding window datapoints with configurable max length from an AST', 'run the script with --ast_fp and --out_fp arguments to generate and write datapoints to a file', 'set the --n_ctx argument to control the maximum number of tokens per generated datapoint']
```

Usage

```
{'generate_datapoints_from_ast': 'run generate_data.py with an AST JSON-lines file to produce augmented datapoints for training', 'extract_leaf_tokens_from_ast': 'use get_leaf_info to extract leaf tokens and their indices from an AST node list', 'create_augmented_windows': 'use get_dps to generate sliding window datapoints with configurable max length from an AST', 'run_cli_datapoint_generation': 'run the script with --ast_fp and --out_fp arguments to generate and write datapoints to a file', 'configure_context_length': 'set the --n_ctx argument to control the maximum number of tokens per generated datapoint'}
```

