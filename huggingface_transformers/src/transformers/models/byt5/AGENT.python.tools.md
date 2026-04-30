# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/byt5/convert_byt5_original_tf_checkpoint_to_pytorch.py

Prompts

```
['convert a TensorFlow T5 checkpoint to a PyTorch model using config file and dump path', 'load TensorFlow checkpoint weights into a PyTorch T5ForConditionalGeneration model', 'build a PyTorch T5ForConditionalGeneration model from a T5Config json configuration file', 'run the CLI script to convert a ByT5 TensorFlow checkpoint to PyTorch format', 'review the load_tf_weights_in_t5 function that maps TensorFlow variable names to PyTorch model attributes', 'create a ByT5 tokenizer instance with custom extra_ids and special tokens for byte-level text tokenization', 'build model input IDs by concatenating sequences and adding end-of-sequence special tokens', 'get a special tokens mask list for token IDs indicating which positions are special tokens', 'convert a text string into byte-level tokens using UTF-8 encoding and character mapping', 'convert a sequence of byte-level tokens back into a decoded UTF-8 string']
```

Usage

```
{'convert_tf_checkpoint_to_pytorch': 'convert a TensorFlow T5 checkpoint to a PyTorch model using config file and dump path', 'load_tf_weights_in_t5': 'load TensorFlow checkpoint weights into a PyTorch T5ForConditionalGeneration model', 'build_pytorch_t5_model': 'build a PyTorch T5ForConditionalGeneration model from a T5Config json configuration file', 'run_tf_to_pytorch_conversion_cli': 'run the CLI script to convert a ByT5 TensorFlow checkpoint to PyTorch format', 'review_load_tf_weights_in_t5': 'review the load_tf_weights_in_t5 function that maps TensorFlow variable names to PyTorch model attributes'}
```

## File: huggingface_transformers/src/transformers/models/byt5/tokenization_byt5.py

Prompts

```
['convert a TensorFlow T5 checkpoint to a PyTorch model using config file and dump path', 'load TensorFlow checkpoint weights into a PyTorch T5ForConditionalGeneration model', 'build a PyTorch T5ForConditionalGeneration model from a T5Config json configuration file', 'run the CLI script to convert a ByT5 TensorFlow checkpoint to PyTorch format', 'review the load_tf_weights_in_t5 function that maps TensorFlow variable names to PyTorch model attributes', 'create a ByT5 tokenizer instance with custom extra_ids and special tokens for byte-level text tokenization', 'build model input IDs by concatenating sequences and adding end-of-sequence special tokens', 'get a special tokens mask list for token IDs indicating which positions are special tokens', 'convert a text string into byte-level tokens using UTF-8 encoding and character mapping', 'convert a sequence of byte-level tokens back into a decoded UTF-8 string']
```

Usage

```
{'create_byt5_tokenizer': 'create a ByT5 tokenizer instance with custom extra_ids and special tokens for byte-level text tokenization', 'build_token_ids_with_special_tokens': 'build model input IDs by concatenating sequences and adding end-of-sequence special tokens', 'get_special_tokens_mask': 'get a special tokens mask list for token IDs indicating which positions are special tokens', 'convert_bytes_to_tokens': 'convert a text string into byte-level tokens using UTF-8 encoding and character mapping', 'convert_tokens_to_string': 'convert a sequence of byte-level tokens back into a decoded UTF-8 string'}
```

