# Agent Python Tools

- repo: facebookresearch/codellama
- repo_uri: https://github.com/facebookresearch/codellama.git

## File: facebookresearch_codellama/llama/generation.py

Prompts

```
['build a Llama model instance from checkpoint directory and tokenizer path with model parallel support', 'generate token sequences from prompt tokens using temperature sampling and top-p nucleus sampling', 'complete text prompts by generating continuations with configurable temperature and top-p parameters', 'infill missing text between a prefix and suffix using the Llama infilling model', 'complete a multi-turn chat dialog with system user and assistant message roles', 'build a Llama transformer model using ModelArgs to configure dim, layers, heads, and vocab size', 'run the transformer forward pass with token tensors and a start position for inference', 'create a ModelArgs dataclass to configure the Llama model dimensions, layers, and sequence length', 'apply rotary positional embeddings to query and key tensors using precomputed freqs_cis', 'build an RMSNorm layer to normalize tensor inputs with configurable dimension and epsilon', 'create a Tokenizer instance by loading a SentencePiece model from a model file path', 'encode a string into a list of token IDs with optional BOS and EOS tokens', 'decode a list of token IDs back into a human-readable string', 'encode a string into token IDs without an implicit leading space for infilling tasks', 'look up the string piece representation of a single token ID']
```

Usage

```
{'build_Llama': 'build a Llama model instance from checkpoint directory and tokenizer path with model parallel support', 'generate_Llama_generate': 'generate token sequences from prompt tokens using temperature sampling and top-p nucleus sampling', 'complete_Llama_text_completion': 'complete text prompts by generating continuations with configurable temperature and top-p parameters', 'infill_Llama_text_infilling': 'infill missing text between a prefix and suffix using the Llama infilling model', 'chat_Llama_chat_completion': 'complete a multi-turn chat dialog with system user and assistant message roles'}
```

## File: facebookresearch_codellama/llama/model.py

Prompts

```
['build a Llama model instance from checkpoint directory and tokenizer path with model parallel support', 'generate token sequences from prompt tokens using temperature sampling and top-p nucleus sampling', 'complete text prompts by generating continuations with configurable temperature and top-p parameters', 'infill missing text between a prefix and suffix using the Llama infilling model', 'complete a multi-turn chat dialog with system user and assistant message roles', 'build a Llama transformer model using ModelArgs to configure dim, layers, heads, and vocab size', 'run the transformer forward pass with token tensors and a start position for inference', 'create a ModelArgs dataclass to configure the Llama model dimensions, layers, and sequence length', 'apply rotary positional embeddings to query and key tensors using precomputed freqs_cis', 'build an RMSNorm layer to normalize tensor inputs with configurable dimension and epsilon', 'create a Tokenizer instance by loading a SentencePiece model from a model file path', 'encode a string into a list of token IDs with optional BOS and EOS tokens', 'decode a list of token IDs back into a human-readable string', 'encode a string into token IDs without an implicit leading space for infilling tasks', 'look up the string piece representation of a single token ID']
```

Usage

```
{'build_transformer_model': 'build a Llama transformer model using ModelArgs to configure dim, layers, heads, and vocab size', 'run_transformer_forward': 'run the transformer forward pass with token tensors and a start position for inference', 'create_modelargs_config': 'create a ModelArgs dataclass to configure the Llama model dimensions, layers, and sequence length', 'apply_rotary_embedding': 'apply rotary positional embeddings to query and key tensors using precomputed freqs_cis', 'build_rmsnorm_layer': 'build an RMSNorm layer to normalize tensor inputs with configurable dimension and epsilon'}
```

## File: facebookresearch_codellama/llama/tokenizer.py

Prompts

```
['build a Llama model instance from checkpoint directory and tokenizer path with model parallel support', 'generate token sequences from prompt tokens using temperature sampling and top-p nucleus sampling', 'complete text prompts by generating continuations with configurable temperature and top-p parameters', 'infill missing text between a prefix and suffix using the Llama infilling model', 'complete a multi-turn chat dialog with system user and assistant message roles', 'build a Llama transformer model using ModelArgs to configure dim, layers, heads, and vocab size', 'run the transformer forward pass with token tensors and a start position for inference', 'create a ModelArgs dataclass to configure the Llama model dimensions, layers, and sequence length', 'apply rotary positional embeddings to query and key tensors using precomputed freqs_cis', 'build an RMSNorm layer to normalize tensor inputs with configurable dimension and epsilon', 'create a Tokenizer instance by loading a SentencePiece model from a model file path', 'encode a string into a list of token IDs with optional BOS and EOS tokens', 'decode a list of token IDs back into a human-readable string', 'encode a string into token IDs without an implicit leading space for infilling tasks', 'look up the string piece representation of a single token ID']
```

Usage

```
{'create_tokenizer': 'create a Tokenizer instance by loading a SentencePiece model from a model file path', 'encode_text': 'encode a string into a list of token IDs with optional BOS and EOS tokens', 'decode_tokens': 'decode a list of token IDs back into a human-readable string', 'encode_infilling': 'encode a string into token IDs without an implicit leading space for infilling tasks', 'token_piece_lookup': 'look up the string piece representation of a single token ID'}
```

