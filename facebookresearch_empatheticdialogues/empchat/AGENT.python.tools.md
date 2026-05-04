# Agent Python Tools

- repo: facebookresearch/empatheticdialogues
- repo_uri: https://github.com/facebookresearch/empatheticdialogues

## File: facebookresearch_empatheticdialogues/empchat/bert_local.py

Prompts

```
['build a BertAdapter module with two BERT wrappers for context and candidate encoding', 'create a BertAdapter instance with opt config and dictionary to initialize dual BERT models', 'run the BertAdapter forward pass to encode context and candidate token sequences into embeddings', 'review the BertAdapter init method that resets unused token embeddings with random normal values', 'summarize the BertAdapter forward method that optionally L2 normalizes context and candidate embeddings', 'create a BertAdapter or TransformerAdapter model from an options object and dictionary words', 'load a saved model checkpoint along with its word dictionary from a file path', 'save a model state dict, word dictionary, options, and optimizer state to a file', "load pre-trained word embeddings from a text file into a model's embedding table", 'score candidate responses against context embeddings using dot product and return top-k matches', 'create sinusoidal position codes for a given number of positions and embedding dimension', 'build a TransformerModel with configurable heads, layers, dimension, and vocabulary size for sequence encoding', 'run multi-head self-attention on a batched sequence tensor with a padding mask', 'build a TransformerFFN feed-forward network with configurable hidden dimension and dropout', 'run a TransformerAdapter to encode context and candidate sequences using shared embeddings and dual transformers', 'build an argparse parser with 40+ arguments for BERT and transformer dialogue model training', 'create training options by parsing CLI args or using defaults with get_opt', 'set default model directory, name, log file, and model file paths for a training run', 'configure a logger that writes to console and an optional log file with config details', 'review the util module functions get_opt, get_parser, set_defaults, and get_logger']
```

Usage

```
{'build_BertAdapter': 'build a BertAdapter module with two BERT wrappers for context and candidate encoding', 'create_BertAdapter_init': 'create a BertAdapter instance with opt config and dictionary to initialize dual BERT models', 'run_BertAdapter_forward': 'run the BertAdapter forward pass to encode context and candidate token sequences into embeddings', 'review_BertAdapter_embedding_reset': 'review the BertAdapter init method that resets unused token embeddings with random normal values', 'summarize_BertAdapter_normalization': 'summarize the BertAdapter forward method that optionally L2 normalizes context and candidate embeddings'}
```

## File: facebookresearch_empatheticdialogues/empchat/models.py

Prompts

```
['build a BertAdapter module with two BERT wrappers for context and candidate encoding', 'create a BertAdapter instance with opt config and dictionary to initialize dual BERT models', 'run the BertAdapter forward pass to encode context and candidate token sequences into embeddings', 'review the BertAdapter init method that resets unused token embeddings with random normal values', 'summarize the BertAdapter forward method that optionally L2 normalizes context and candidate embeddings', 'create a BertAdapter or TransformerAdapter model from an options object and dictionary words', 'load a saved model checkpoint along with its word dictionary from a file path', 'save a model state dict, word dictionary, options, and optimizer state to a file', "load pre-trained word embeddings from a text file into a model's embedding table", 'score candidate responses against context embeddings using dot product and return top-k matches', 'create sinusoidal position codes for a given number of positions and embedding dimension', 'build a TransformerModel with configurable heads, layers, dimension, and vocabulary size for sequence encoding', 'run multi-head self-attention on a batched sequence tensor with a padding mask', 'build a TransformerFFN feed-forward network with configurable hidden dimension and dropout', 'run a TransformerAdapter to encode context and candidate sequences using shared embeddings and dual transformers', 'build an argparse parser with 40+ arguments for BERT and transformer dialogue model training', 'create training options by parsing CLI args or using defaults with get_opt', 'set default model directory, name, log file, and model file paths for a training run', 'configure a logger that writes to console and an optional log file with config details', 'review the util module functions get_opt, get_parser, set_defaults, and get_logger']
```

Usage

```
{'create_model': 'create a BertAdapter or TransformerAdapter model from an options object and dictionary words', 'load_model': 'load a saved model checkpoint along with its word dictionary from a file path', 'save_model': 'save a model state dict, word dictionary, options, and optimizer state to a file', 'load_embeddings': "load pre-trained word embeddings from a text file into a model's embedding table", 'score_candidates': 'score candidate responses against context embeddings using dot product and return top-k matches'}
```

## File: facebookresearch_empatheticdialogues/empchat/transformer_local.py

Prompts

```
['build a BertAdapter module with two BERT wrappers for context and candidate encoding', 'create a BertAdapter instance with opt config and dictionary to initialize dual BERT models', 'run the BertAdapter forward pass to encode context and candidate token sequences into embeddings', 'review the BertAdapter init method that resets unused token embeddings with random normal values', 'summarize the BertAdapter forward method that optionally L2 normalizes context and candidate embeddings', 'create a BertAdapter or TransformerAdapter model from an options object and dictionary words', 'load a saved model checkpoint along with its word dictionary from a file path', 'save a model state dict, word dictionary, options, and optimizer state to a file', "load pre-trained word embeddings from a text file into a model's embedding table", 'score candidate responses against context embeddings using dot product and return top-k matches', 'create sinusoidal position codes for a given number of positions and embedding dimension', 'build a TransformerModel with configurable heads, layers, dimension, and vocabulary size for sequence encoding', 'run multi-head self-attention on a batched sequence tensor with a padding mask', 'build a TransformerFFN feed-forward network with configurable hidden dimension and dropout', 'run a TransformerAdapter to encode context and candidate sequences using shared embeddings and dual transformers', 'build an argparse parser with 40+ arguments for BERT and transformer dialogue model training', 'create training options by parsing CLI args or using defaults with get_opt', 'set default model directory, name, log file, and model file paths for a training run', 'configure a logger that writes to console and an optional log file with config details', 'review the util module functions get_opt, get_parser, set_defaults, and get_logger']
```

Usage

```
{'create_positional_embeddings': 'create sinusoidal position codes for a given number of positions and embedding dimension', 'build_transformer_model': 'build a TransformerModel with configurable heads, layers, dimension, and vocabulary size for sequence encoding', 'run_multihead_attention': 'run multi-head self-attention on a batched sequence tensor with a padding mask', 'build_transformer_ffn': 'build a TransformerFFN feed-forward network with configurable hidden dimension and dropout', 'run_transformer_adapter': 'run a TransformerAdapter to encode context and candidate sequences using shared embeddings and dual transformers'}
```

## File: facebookresearch_empatheticdialogues/empchat/util.py

Prompts

```
['build a BertAdapter module with two BERT wrappers for context and candidate encoding', 'create a BertAdapter instance with opt config and dictionary to initialize dual BERT models', 'run the BertAdapter forward pass to encode context and candidate token sequences into embeddings', 'review the BertAdapter init method that resets unused token embeddings with random normal values', 'summarize the BertAdapter forward method that optionally L2 normalizes context and candidate embeddings', 'create a BertAdapter or TransformerAdapter model from an options object and dictionary words', 'load a saved model checkpoint along with its word dictionary from a file path', 'save a model state dict, word dictionary, options, and optimizer state to a file', "load pre-trained word embeddings from a text file into a model's embedding table", 'score candidate responses against context embeddings using dot product and return top-k matches', 'create sinusoidal position codes for a given number of positions and embedding dimension', 'build a TransformerModel with configurable heads, layers, dimension, and vocabulary size for sequence encoding', 'run multi-head self-attention on a batched sequence tensor with a padding mask', 'build a TransformerFFN feed-forward network with configurable hidden dimension and dropout', 'run a TransformerAdapter to encode context and candidate sequences using shared embeddings and dual transformers', 'build an argparse parser with 40+ arguments for BERT and transformer dialogue model training', 'create training options by parsing CLI args or using defaults with get_opt', 'set default model directory, name, log file, and model file paths for a training run', 'configure a logger that writes to console and an optional log file with config details', 'review the util module functions get_opt, get_parser, set_defaults, and get_logger']
```

Usage

```
{'build_argparse_parser': 'build an argparse parser with 40+ arguments for BERT and transformer dialogue model training', 'create_opt_from_args': 'create training options by parsing CLI args or using defaults with get_opt', 'set_model_defaults': 'set default model directory, name, log file, and model file paths for a training run', 'configure_logger': 'configure a logger that writes to console and an optional log file with config details', 'review_util_functions': 'review the util module functions get_opt, get_parser, set_defaults, and get_logger'}
```

