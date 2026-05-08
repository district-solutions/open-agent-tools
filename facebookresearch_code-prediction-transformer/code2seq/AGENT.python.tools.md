# Agent Python Tools

- repo: facebookresearch/code-prediction-transformer
- repo_uri: https://github.com/facebookresearch/code-prediction-transformer

## File: facebookresearch_code-prediction-transformer/code2seq/code2seq_model.py

Prompts

```
['build a Code2SeqModel instance with token and subtoken vocab sizes and a loss function', 'run a forward pass through the Code2SeqModel with starts, paths, ends, and targets tensors', 'embed code paths using the node embedding and bidirectional LSTM in Code2SeqModel', 'compute softmax attention weights over embedded tensors using EmbeddingAttentionLayer', 'reset all multi-dimensional parameters in the Code2SeqModel using Xavier uniform initialization', 'create a PyTorch Dataset that loads data points from a JSON-lines file with efficient seek-based access', 'get the total number of data points in the code2seq Dataset by calling len on it', 'retrieve a single data point from the Dataset by index using seek-based file reading', 'collate a batch of target, starts, paths, and ends into padded PyTorch tensors for model input', 'pad variable-length start, path, and end sequences to uniform dimensions using the collate combine helper', 'run generate_data.py to extract terminal-to-terminal paths from AST files and write datapoints to output', 'extract all valid paths between terminal nodes in an AST using DFS with a max path length constraint', 'get leaf node indices from an AST filtered by id type such as attr, num, name, or param', 'get all paths for target nodes in an AST with random sampling capped at a max number of paths', 'load a pickled vocabulary file and return a word-to-index mapping with an unknown token fallback', 'run the generate_vocab script to create a code2seq vocabulary pickle file from a JSON-lines input', 'create a token-type vocabulary from a JSON-lines code dataset using the code2seq generate_vocab tool', 'create a subtoken-type vocabulary by tokenizing terminal nodes from a JSON-lines code dataset', 'create an output-type vocabulary from terminal nodes of a JSON-lines code dataset', 'review the get_value function to understand how it extracts tokens, subtokens, or output nodes from parsed JSON lines']
```

Usage

```
{'build_code2seq_model': 'build a Code2SeqModel instance with token and subtoken vocab sizes and a loss function', 'run_forward_pass': 'run a forward pass through the Code2SeqModel with starts, paths, ends, and targets tensors', 'embed_code_paths': 'embed code paths using the node embedding and bidirectional LSTM in Code2SeqModel', 'compute_attention_weights': 'compute softmax attention weights over embedded tensors using EmbeddingAttentionLayer', 'reset_model_parameters': 'reset all multi-dimensional parameters in the Code2SeqModel using Xavier uniform initialization'}
```

## File: facebookresearch_code-prediction-transformer/code2seq/dataset.py

Prompts

```
['build a Code2SeqModel instance with token and subtoken vocab sizes and a loss function', 'run a forward pass through the Code2SeqModel with starts, paths, ends, and targets tensors', 'embed code paths using the node embedding and bidirectional LSTM in Code2SeqModel', 'compute softmax attention weights over embedded tensors using EmbeddingAttentionLayer', 'reset all multi-dimensional parameters in the Code2SeqModel using Xavier uniform initialization', 'create a PyTorch Dataset that loads data points from a JSON-lines file with efficient seek-based access', 'get the total number of data points in the code2seq Dataset by calling len on it', 'retrieve a single data point from the Dataset by index using seek-based file reading', 'collate a batch of target, starts, paths, and ends into padded PyTorch tensors for model input', 'pad variable-length start, path, and end sequences to uniform dimensions using the collate combine helper', 'run generate_data.py to extract terminal-to-terminal paths from AST files and write datapoints to output', 'extract all valid paths between terminal nodes in an AST using DFS with a max path length constraint', 'get leaf node indices from an AST filtered by id type such as attr, num, name, or param', 'get all paths for target nodes in an AST with random sampling capped at a max number of paths', 'load a pickled vocabulary file and return a word-to-index mapping with an unknown token fallback', 'run the generate_vocab script to create a code2seq vocabulary pickle file from a JSON-lines input', 'create a token-type vocabulary from a JSON-lines code dataset using the code2seq generate_vocab tool', 'create a subtoken-type vocabulary by tokenizing terminal nodes from a JSON-lines code dataset', 'create an output-type vocabulary from terminal nodes of a JSON-lines code dataset', 'review the get_value function to understand how it extracts tokens, subtokens, or output nodes from parsed JSON lines']
```

Usage

```
{'create_dataset_from_jsonl': 'create a PyTorch Dataset that loads data points from a JSON-lines file with efficient seek-based access', 'get_dataset_length': 'get the total number of data points in the code2seq Dataset by calling len on it', 'retrieve_data_point_by_index': 'retrieve a single data point from the Dataset by index using seek-based file reading', 'collate_batch_into_tensors': 'collate a batch of target, starts, paths, and ends into padded PyTorch tensors for model input', 'pad_sequences_with_combine': 'pad variable-length start, path, and end sequences to uniform dimensions using the collate combine helper'}
```

## File: facebookresearch_code-prediction-transformer/code2seq/generate_data.py

Prompts

```
['build a Code2SeqModel instance with token and subtoken vocab sizes and a loss function', 'run a forward pass through the Code2SeqModel with starts, paths, ends, and targets tensors', 'embed code paths using the node embedding and bidirectional LSTM in Code2SeqModel', 'compute softmax attention weights over embedded tensors using EmbeddingAttentionLayer', 'reset all multi-dimensional parameters in the Code2SeqModel using Xavier uniform initialization', 'create a PyTorch Dataset that loads data points from a JSON-lines file with efficient seek-based access', 'get the total number of data points in the code2seq Dataset by calling len on it', 'retrieve a single data point from the Dataset by index using seek-based file reading', 'collate a batch of target, starts, paths, and ends into padded PyTorch tensors for model input', 'pad variable-length start, path, and end sequences to uniform dimensions using the collate combine helper', 'run generate_data.py to extract terminal-to-terminal paths from AST files and write datapoints to output', 'extract all valid paths between terminal nodes in an AST using DFS with a max path length constraint', 'get leaf node indices from an AST filtered by id type such as attr, num, name, or param', 'get all paths for target nodes in an AST with random sampling capped at a max number of paths', 'load a pickled vocabulary file and return a word-to-index mapping with an unknown token fallback', 'run the generate_vocab script to create a code2seq vocabulary pickle file from a JSON-lines input', 'create a token-type vocabulary from a JSON-lines code dataset using the code2seq generate_vocab tool', 'create a subtoken-type vocabulary by tokenizing terminal nodes from a JSON-lines code dataset', 'create an output-type vocabulary from terminal nodes of a JSON-lines code dataset', 'review the get_value function to understand how it extracts tokens, subtokens, or output nodes from parsed JSON lines']
```

Usage

```
{'generate_data_points_from_ast': 'run generate_data.py to extract terminal-to-terminal paths from AST files and write datapoints to output', 'extract_paths_from_ast': 'extract all valid paths between terminal nodes in an AST using DFS with a max path length constraint', 'get_leaf_nodes_by_type': 'get leaf node indices from an AST filtered by id type such as attr, num, name, or param', 'get_all_paths_with_sampling': 'get all paths for target nodes in an AST with random sampling capped at a max number of paths', 'load_word_to_index_vocab': 'load a pickled vocabulary file and return a word-to-index mapping with an unknown token fallback'}
```

## File: facebookresearch_code-prediction-transformer/code2seq/generate_vocab.py

Prompts

```
['build a Code2SeqModel instance with token and subtoken vocab sizes and a loss function', 'run a forward pass through the Code2SeqModel with starts, paths, ends, and targets tensors', 'embed code paths using the node embedding and bidirectional LSTM in Code2SeqModel', 'compute softmax attention weights over embedded tensors using EmbeddingAttentionLayer', 'reset all multi-dimensional parameters in the Code2SeqModel using Xavier uniform initialization', 'create a PyTorch Dataset that loads data points from a JSON-lines file with efficient seek-based access', 'get the total number of data points in the code2seq Dataset by calling len on it', 'retrieve a single data point from the Dataset by index using seek-based file reading', 'collate a batch of target, starts, paths, and ends into padded PyTorch tensors for model input', 'pad variable-length start, path, and end sequences to uniform dimensions using the collate combine helper', 'run generate_data.py to extract terminal-to-terminal paths from AST files and write datapoints to output', 'extract all valid paths between terminal nodes in an AST using DFS with a max path length constraint', 'get leaf node indices from an AST filtered by id type such as attr, num, name, or param', 'get all paths for target nodes in an AST with random sampling capped at a max number of paths', 'load a pickled vocabulary file and return a word-to-index mapping with an unknown token fallback', 'run the generate_vocab script to create a code2seq vocabulary pickle file from a JSON-lines input', 'create a token-type vocabulary from a JSON-lines code dataset using the code2seq generate_vocab tool', 'create a subtoken-type vocabulary by tokenizing terminal nodes from a JSON-lines code dataset', 'create an output-type vocabulary from terminal nodes of a JSON-lines code dataset', 'review the get_value function to understand how it extracts tokens, subtokens, or output nodes from parsed JSON lines']
```

Usage

```
{'run_generate_vocab_cli': 'run the generate_vocab script to create a code2seq vocabulary pickle file from a JSON-lines input', 'create_token_vocab': 'create a token-type vocabulary from a JSON-lines code dataset using the code2seq generate_vocab tool', 'create_subtoken_vocab': 'create a subtoken-type vocabulary by tokenizing terminal nodes from a JSON-lines code dataset', 'create_output_vocab': 'create an output-type vocabulary from terminal nodes of a JSON-lines code dataset', 'review_get_value': 'review the get_value function to understand how it extracts tokens, subtokens, or output nodes from parsed JSON lines'}
```

