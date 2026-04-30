# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/prophetnet/configuration_prophetnet.py

Prompts

```
['create a ProphetNetConfig instance with custom encoder and decoder layer sizes', 'configure ProphetNetConfig to predict multiple future tokens with custom ngram value', 'read the default ProphetNetConfig hyperparameters like hidden_size and vocab_size', 'review the ProphetNetConfig class and its num_hidden_layers property behavior', 'summarize the ProphetNetConfig class attributes and their default values', 'convert a ProphetNet PyTorch checkpoint to the current HuggingFace Transformers model structure', 'convert an XLM-ProphetNet PyTorch checkpoint to the current HuggingFace Transformers model structure', 'run the convert_prophetnet script via CLI with checkpoint path and output folder arguments', 'map old ProphetNet weight keys to new HuggingFace Transformers layer names during conversion', 'split combined in_proj_weight and in_proj_bias into separate query, key, and value projection weights', 'build a ProphetNetForConditionalGeneration model for sequence-to-sequence text generation with ngram prediction heads', 'create a ProphetNetEncoder with positional embeddings and multi-head self-attention for source text encoding', 'run a ProphetNetDecoder with ngram self-attention and cross-attention for autoregressive target generation', 'test a ProphetNetModel encoder-decoder pipeline that processes input sequences and produces conditional outputs', 'summarize a ProphetNetForCausalLM decoder-only model for left-to-right language modeling with ngram loss', 'create a ProphetNetTokenizer instance from a vocab file for sequence generation tasks', 'build model inputs from token sequences by adding special tokens like SEP for ProphetNet', 'test the BasicTokenizer class that handles punctuation splitting, lowercasing, and unicode normalization', 'run WordPiece tokenization to split text into subword pieces using a vocabulary with greedy longest-match', 'save the tokenizer vocabulary to a directory as a newline-delimited token file']
```

Usage

```
{'create_prophetnet_config': 'create a ProphetNetConfig instance with custom encoder and decoder layer sizes', 'configure_prophetnet_ngram': 'configure ProphetNetConfig to predict multiple future tokens with custom ngram value', 'read_prophetnet_defaults': 'read the default ProphetNetConfig hyperparameters like hidden_size and vocab_size', 'review_prophetnet_config': 'review the ProphetNetConfig class and its num_hidden_layers property behavior', 'summarize_prophetnet_config': 'summarize the ProphetNetConfig class attributes and their default values'}
```

## File: huggingface_transformers/src/transformers/models/prophetnet/convert_prophetnet_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['create a ProphetNetConfig instance with custom encoder and decoder layer sizes', 'configure ProphetNetConfig to predict multiple future tokens with custom ngram value', 'read the default ProphetNetConfig hyperparameters like hidden_size and vocab_size', 'review the ProphetNetConfig class and its num_hidden_layers property behavior', 'summarize the ProphetNetConfig class attributes and their default values', 'convert a ProphetNet PyTorch checkpoint to the current HuggingFace Transformers model structure', 'convert an XLM-ProphetNet PyTorch checkpoint to the current HuggingFace Transformers model structure', 'run the convert_prophetnet script via CLI with checkpoint path and output folder arguments', 'map old ProphetNet weight keys to new HuggingFace Transformers layer names during conversion', 'split combined in_proj_weight and in_proj_bias into separate query, key, and value projection weights', 'build a ProphetNetForConditionalGeneration model for sequence-to-sequence text generation with ngram prediction heads', 'create a ProphetNetEncoder with positional embeddings and multi-head self-attention for source text encoding', 'run a ProphetNetDecoder with ngram self-attention and cross-attention for autoregressive target generation', 'test a ProphetNetModel encoder-decoder pipeline that processes input sequences and produces conditional outputs', 'summarize a ProphetNetForCausalLM decoder-only model for left-to-right language modeling with ngram loss', 'create a ProphetNetTokenizer instance from a vocab file for sequence generation tasks', 'build model inputs from token sequences by adding special tokens like SEP for ProphetNet', 'test the BasicTokenizer class that handles punctuation splitting, lowercasing, and unicode normalization', 'run WordPiece tokenization to split text into subword pieces using a vocabulary with greedy longest-match', 'save the tokenizer vocabulary to a directory as a newline-delimited token file']
```

Usage

```
{'convert_prophetnet_checkpoint': 'convert a ProphetNet PyTorch checkpoint to the current HuggingFace Transformers model structure', 'convert_xprophetnet_checkpoint': 'convert an XLM-ProphetNet PyTorch checkpoint to the current HuggingFace Transformers model structure', 'run_convert_script_cli': 'run the convert_prophetnet script via CLI with checkpoint path and output folder arguments', 'map_prophetnet_weight_keys': 'map old ProphetNet weight keys to new HuggingFace Transformers layer names during conversion', 'split_in_proj_weights': 'split combined in_proj_weight and in_proj_bias into separate query, key, and value projection weights'}
```

## File: huggingface_transformers/src/transformers/models/prophetnet/modeling_prophetnet.py

Prompts

```
['create a ProphetNetConfig instance with custom encoder and decoder layer sizes', 'configure ProphetNetConfig to predict multiple future tokens with custom ngram value', 'read the default ProphetNetConfig hyperparameters like hidden_size and vocab_size', 'review the ProphetNetConfig class and its num_hidden_layers property behavior', 'summarize the ProphetNetConfig class attributes and their default values', 'convert a ProphetNet PyTorch checkpoint to the current HuggingFace Transformers model structure', 'convert an XLM-ProphetNet PyTorch checkpoint to the current HuggingFace Transformers model structure', 'run the convert_prophetnet script via CLI with checkpoint path and output folder arguments', 'map old ProphetNet weight keys to new HuggingFace Transformers layer names during conversion', 'split combined in_proj_weight and in_proj_bias into separate query, key, and value projection weights', 'build a ProphetNetForConditionalGeneration model for sequence-to-sequence text generation with ngram prediction heads', 'create a ProphetNetEncoder with positional embeddings and multi-head self-attention for source text encoding', 'run a ProphetNetDecoder with ngram self-attention and cross-attention for autoregressive target generation', 'test a ProphetNetModel encoder-decoder pipeline that processes input sequences and produces conditional outputs', 'summarize a ProphetNetForCausalLM decoder-only model for left-to-right language modeling with ngram loss', 'create a ProphetNetTokenizer instance from a vocab file for sequence generation tasks', 'build model inputs from token sequences by adding special tokens like SEP for ProphetNet', 'test the BasicTokenizer class that handles punctuation splitting, lowercasing, and unicode normalization', 'run WordPiece tokenization to split text into subword pieces using a vocabulary with greedy longest-match', 'save the tokenizer vocabulary to a directory as a newline-delimited token file']
```

Usage

```
{'build_prophetnet_conditional_generation': 'build a ProphetNetForConditionalGeneration model for sequence-to-sequence text generation with ngram prediction heads', 'create_prophetnet_encoder': 'create a ProphetNetEncoder with positional embeddings and multi-head self-attention for source text encoding', 'run_prophetnet_decoder': 'run a ProphetNetDecoder with ngram self-attention and cross-attention for autoregressive target generation', 'test_prophetnet_model': 'test a ProphetNetModel encoder-decoder pipeline that processes input sequences and produces conditional outputs', 'summarize_prophetnet_causal_lm': 'summarize a ProphetNetForCausalLM decoder-only model for left-to-right language modeling with ngram loss'}
```

## File: huggingface_transformers/src/transformers/models/prophetnet/tokenization_prophetnet.py

Prompts

```
['create a ProphetNetConfig instance with custom encoder and decoder layer sizes', 'configure ProphetNetConfig to predict multiple future tokens with custom ngram value', 'read the default ProphetNetConfig hyperparameters like hidden_size and vocab_size', 'review the ProphetNetConfig class and its num_hidden_layers property behavior', 'summarize the ProphetNetConfig class attributes and their default values', 'convert a ProphetNet PyTorch checkpoint to the current HuggingFace Transformers model structure', 'convert an XLM-ProphetNet PyTorch checkpoint to the current HuggingFace Transformers model structure', 'run the convert_prophetnet script via CLI with checkpoint path and output folder arguments', 'map old ProphetNet weight keys to new HuggingFace Transformers layer names during conversion', 'split combined in_proj_weight and in_proj_bias into separate query, key, and value projection weights', 'build a ProphetNetForConditionalGeneration model for sequence-to-sequence text generation with ngram prediction heads', 'create a ProphetNetEncoder with positional embeddings and multi-head self-attention for source text encoding', 'run a ProphetNetDecoder with ngram self-attention and cross-attention for autoregressive target generation', 'test a ProphetNetModel encoder-decoder pipeline that processes input sequences and produces conditional outputs', 'summarize a ProphetNetForCausalLM decoder-only model for left-to-right language modeling with ngram loss', 'create a ProphetNetTokenizer instance from a vocab file for sequence generation tasks', 'build model inputs from token sequences by adding special tokens like SEP for ProphetNet', 'test the BasicTokenizer class that handles punctuation splitting, lowercasing, and unicode normalization', 'run WordPiece tokenization to split text into subword pieces using a vocabulary with greedy longest-match', 'save the tokenizer vocabulary to a directory as a newline-delimited token file']
```

Usage

```
{'create_prophetnet_tokenizer': 'create a ProphetNetTokenizer instance from a vocab file for sequence generation tasks', 'build_tokenizer_inputs': 'build model inputs from token sequences by adding special tokens like SEP for ProphetNet', 'test_basic_tokenizer': 'test the BasicTokenizer class that handles punctuation splitting, lowercasing, and unicode normalization', 'run_wordpiece_tokenize': 'run WordPiece tokenization to split text into subword pieces using a vocabulary with greedy longest-match', 'save_tokenizer_vocab': 'save the tokenizer vocabulary to a directory as a newline-delimited token file'}
```

