# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/models/mistral/config.py

Prompts

```
['create a MistralConfig instance with default 7b architecture values', 'create a MistralConfig with custom model_dim, num_layers, and ffn_inner_dim', 'register Mistral model configs into a DependencyContainer using ConfigRegistrar', 'review the MistralConfig dataclass to understand default 7b model architecture parameters', 'summarize the MistralConfig fields including model_dim, max_seq_len, and attention settings', 'create a Mistral TransformerLM model from a MistralConfig using the factory function', 'create a TransformerLMDecoder with decoder layers, position encoder, and layer norm via MistralFactory', 'create a StandardMultiheadAttention module with causal bias and rotary position encoding for Mistral', 'create a GLUFeedForwardNetwork for a Mistral decoder layer using the factory method', 'create an RMSNorm layer normalization module for a Mistral model using the factory', 'convert a Mistral reference model state dict to fairseq2 format using a key mapping', 'review the convert_mistral_state_dict function that maps reference checkpoint keys to fairseq2 decoder keys', 'test the convert_mistral_state_dict function with a sample state dict and MistralConfig', 'refactor the convert_mistral_state_dict function to support additional Mistral checkpoint formats', 'summarize the convert_mistral_state_dict function and its regex-based key mapping logic', 'load a Mistral tokenizer from a SentencePiece model file path and return a Tokenizer instance', 'create a BasicSentencePieceTokenizer by loading a SentencePiece model from a given file path', 'review the load_mistral_tokenizer function to understand how it loads and wraps a SentencePiece model', 'summarize the load_mistral_tokenizer function that loads a SentencePiece model and returns a Tokenizer', 'test the load_mistral_tokenizer function by loading a SentencePiece model from a file path']
```

Usage

```
{'create_mistral_config_default': 'create a MistralConfig instance with default 7b architecture values', 'create_mistral_config_custom': 'create a MistralConfig with custom model_dim, num_layers, and ffn_inner_dim', 'register_mistral_configs': 'register Mistral model configs into a DependencyContainer using ConfigRegistrar', 'review_mistral_config_architecture': 'review the MistralConfig dataclass to understand default 7b model architecture parameters', 'summarize_mistral_config_fields': 'summarize the MistralConfig fields including model_dim, max_seq_len, and attention settings'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/mistral/factory.py

Prompts

```
['create a MistralConfig instance with default 7b architecture values', 'create a MistralConfig with custom model_dim, num_layers, and ffn_inner_dim', 'register Mistral model configs into a DependencyContainer using ConfigRegistrar', 'review the MistralConfig dataclass to understand default 7b model architecture parameters', 'summarize the MistralConfig fields including model_dim, max_seq_len, and attention settings', 'create a Mistral TransformerLM model from a MistralConfig using the factory function', 'create a TransformerLMDecoder with decoder layers, position encoder, and layer norm via MistralFactory', 'create a StandardMultiheadAttention module with causal bias and rotary position encoding for Mistral', 'create a GLUFeedForwardNetwork for a Mistral decoder layer using the factory method', 'create an RMSNorm layer normalization module for a Mistral model using the factory', 'convert a Mistral reference model state dict to fairseq2 format using a key mapping', 'review the convert_mistral_state_dict function that maps reference checkpoint keys to fairseq2 decoder keys', 'test the convert_mistral_state_dict function with a sample state dict and MistralConfig', 'refactor the convert_mistral_state_dict function to support additional Mistral checkpoint formats', 'summarize the convert_mistral_state_dict function and its regex-based key mapping logic', 'load a Mistral tokenizer from a SentencePiece model file path and return a Tokenizer instance', 'create a BasicSentencePieceTokenizer by loading a SentencePiece model from a given file path', 'review the load_mistral_tokenizer function to understand how it loads and wraps a SentencePiece model', 'summarize the load_mistral_tokenizer function that loads a SentencePiece model and returns a Tokenizer', 'test the load_mistral_tokenizer function by loading a SentencePiece model from a file path']
```

Usage

```
{'create_mistral_model': 'create a Mistral TransformerLM model from a MistralConfig using the factory function', 'create_mistral_decoder': 'create a TransformerLMDecoder with decoder layers, position encoder, and layer norm via MistralFactory', 'create_mistral_self_attention': 'create a StandardMultiheadAttention module with causal bias and rotary position encoding for Mistral', 'create_mistral_ffn': 'create a GLUFeedForwardNetwork for a Mistral decoder layer using the factory method', 'create_mistral_layer_norm': 'create an RMSNorm layer normalization module for a Mistral model using the factory'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/mistral/interop.py

Prompts

```
['create a MistralConfig instance with default 7b architecture values', 'create a MistralConfig with custom model_dim, num_layers, and ffn_inner_dim', 'register Mistral model configs into a DependencyContainer using ConfigRegistrar', 'review the MistralConfig dataclass to understand default 7b model architecture parameters', 'summarize the MistralConfig fields including model_dim, max_seq_len, and attention settings', 'create a Mistral TransformerLM model from a MistralConfig using the factory function', 'create a TransformerLMDecoder with decoder layers, position encoder, and layer norm via MistralFactory', 'create a StandardMultiheadAttention module with causal bias and rotary position encoding for Mistral', 'create a GLUFeedForwardNetwork for a Mistral decoder layer using the factory method', 'create an RMSNorm layer normalization module for a Mistral model using the factory', 'convert a Mistral reference model state dict to fairseq2 format using a key mapping', 'review the convert_mistral_state_dict function that maps reference checkpoint keys to fairseq2 decoder keys', 'test the convert_mistral_state_dict function with a sample state dict and MistralConfig', 'refactor the convert_mistral_state_dict function to support additional Mistral checkpoint formats', 'summarize the convert_mistral_state_dict function and its regex-based key mapping logic', 'load a Mistral tokenizer from a SentencePiece model file path and return a Tokenizer instance', 'create a BasicSentencePieceTokenizer by loading a SentencePiece model from a given file path', 'review the load_mistral_tokenizer function to understand how it loads and wraps a SentencePiece model', 'summarize the load_mistral_tokenizer function that loads a SentencePiece model and returns a Tokenizer', 'test the load_mistral_tokenizer function by loading a SentencePiece model from a file path']
```

Usage

```
{'convert_mistral_state_dict': 'convert a Mistral reference model state dict to fairseq2 format using a key mapping', 'review_convert_mistral_state_dict': 'review the convert_mistral_state_dict function that maps reference checkpoint keys to fairseq2 decoder keys', 'test_convert_mistral_state_dict': 'test the convert_mistral_state_dict function with a sample state dict and MistralConfig', 'refactor_convert_mistral_state_dict': 'refactor the convert_mistral_state_dict function to support additional Mistral checkpoint formats', 'summarize_convert_mistral_state_dict': 'summarize the convert_mistral_state_dict function and its regex-based key mapping logic'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/mistral/tokenizer.py

Prompts

```
['create a MistralConfig instance with default 7b architecture values', 'create a MistralConfig with custom model_dim, num_layers, and ffn_inner_dim', 'register Mistral model configs into a DependencyContainer using ConfigRegistrar', 'review the MistralConfig dataclass to understand default 7b model architecture parameters', 'summarize the MistralConfig fields including model_dim, max_seq_len, and attention settings', 'create a Mistral TransformerLM model from a MistralConfig using the factory function', 'create a TransformerLMDecoder with decoder layers, position encoder, and layer norm via MistralFactory', 'create a StandardMultiheadAttention module with causal bias and rotary position encoding for Mistral', 'create a GLUFeedForwardNetwork for a Mistral decoder layer using the factory method', 'create an RMSNorm layer normalization module for a Mistral model using the factory', 'convert a Mistral reference model state dict to fairseq2 format using a key mapping', 'review the convert_mistral_state_dict function that maps reference checkpoint keys to fairseq2 decoder keys', 'test the convert_mistral_state_dict function with a sample state dict and MistralConfig', 'refactor the convert_mistral_state_dict function to support additional Mistral checkpoint formats', 'summarize the convert_mistral_state_dict function and its regex-based key mapping logic', 'load a Mistral tokenizer from a SentencePiece model file path and return a Tokenizer instance', 'create a BasicSentencePieceTokenizer by loading a SentencePiece model from a given file path', 'review the load_mistral_tokenizer function to understand how it loads and wraps a SentencePiece model', 'summarize the load_mistral_tokenizer function that loads a SentencePiece model and returns a Tokenizer', 'test the load_mistral_tokenizer function by loading a SentencePiece model from a file path']
```

Usage

```
{'load_mistral_tokenizer': 'load a Mistral tokenizer from a SentencePiece model file path and return a Tokenizer instance', 'create_mistral_tokenizer': 'create a BasicSentencePieceTokenizer by loading a SentencePiece model from a given file path', 'review_load_mistral_tokenizer': 'review the load_mistral_tokenizer function to understand how it loads and wraps a SentencePiece model', 'summarize_load_mistral_tokenizer': 'summarize the load_mistral_tokenizer function that loads a SentencePiece model and returns a Tokenizer', 'test_load_mistral_tokenizer': 'test the load_mistral_tokenizer function by loading a SentencePiece model from a file path'}
```

