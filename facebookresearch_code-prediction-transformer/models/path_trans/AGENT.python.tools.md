# Agent Python Tools

- repo: facebookresearch/code-prediction-transformer
- repo_uri: https://github.com/facebookresearch/code-prediction-transformer

## File: facebookresearch_code-prediction-transformer/models/path_trans/dataset.py

Prompts

```
['create a Setup instance that builds a Vocab and Dataset from filepaths for the path_trans model', 'convert dependency paths, extensions, and root paths into vocabulary indices using the Vocab convert method', 'collate a batch of sequences into padded PyTorch tensors with input, target, and root path data', 'pad root paths to uniform length within a batch using the combine_root_paths helper function', 'build a Dataset instance from a file path and IDs file for path-based code prediction training', 'run the CLI tool to generate datapoints from an AST file with configurable context and path length', 'create a function that extracts leaf tokens and their indices from an AST node list', 'build ancestor chains for each node in an AST by traversing parent-child relationships', 'get root-to-leaf paths with a configurable max path length for given leaf IDs', 'generate augmented datapoints from an AST using a sliding window approach when tokens exceed max length']
```

Usage

```
{'create_setup_instance': 'create a Setup instance that builds a Vocab and Dataset from filepaths for the path_trans model', 'convert_tokens_with_vocab': 'convert dependency paths, extensions, and root paths into vocabulary indices using the Vocab convert method', 'collate_batch_sequences': 'collate a batch of sequences into padded PyTorch tensors with input, target, and root path data', 'pad_root_paths': 'pad root paths to uniform length within a batch using the combine_root_paths helper function', 'build_dataset_for_training': 'build a Dataset instance from a file path and IDs file for path-based code prediction training'}
```

## File: facebookresearch_code-prediction-transformer/models/path_trans/generate_data.py

Prompts

```
['create a Setup instance that builds a Vocab and Dataset from filepaths for the path_trans model', 'convert dependency paths, extensions, and root paths into vocabulary indices using the Vocab convert method', 'collate a batch of sequences into padded PyTorch tensors with input, target, and root path data', 'pad root paths to uniform length within a batch using the combine_root_paths helper function', 'build a Dataset instance from a file path and IDs file for path-based code prediction training', 'run the CLI tool to generate datapoints from an AST file with configurable context and path length', 'create a function that extracts leaf tokens and their indices from an AST node list', 'build ancestor chains for each node in an AST by traversing parent-child relationships', 'get root-to-leaf paths with a configurable max path length for given leaf IDs', 'generate augmented datapoints from an AST using a sliding window approach when tokens exceed max length']
```

Usage

```
{'generate_datapoints_from_ast': 'run the CLI tool to generate datapoints from an AST file with configurable context and path length', 'extract_leaf_tokens_from_ast': 'create a function that extracts leaf tokens and their indices from an AST node list', 'build_ancestor_chains_for_ast': 'build ancestor chains for each node in an AST by traversing parent-child relationships', 'get_root_paths_for_leaves': 'get root-to-leaf paths with a configurable max path length for given leaf IDs', 'generate_augmented_datapoints_with_sliding_window': 'generate augmented datapoints from an AST using a sliding window approach when tokens exceed max length'}
```

