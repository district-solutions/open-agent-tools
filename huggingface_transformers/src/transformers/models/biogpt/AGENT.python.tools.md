# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/biogpt/convert_biogpt_original_pytorch_checkpoint_to_pytorch.py

Prompts

```
['convert a BioGpt fairseq PyTorch checkpoint to HuggingFace transformers format', 'load a fairseq dictionary from a text file with symbol and count pairs', 'add a word symbol to a fairseq Dictionary with optional count and overwrite flag', 'rewrite fairseq dictionary keys by stripping word-break @@ suffixes and adding </w> endings', 'run the BioGpt checkpoint conversion script from the command line with checkpoint and output paths', 'create a BioGptForCausalLM model for causal language modeling with past key value caching', 'build a BioGptForTokenClassification model for token-level classification tasks', 'test a BioGptForSequenceClassification model for sequence classification or regression', 'run the BioGptModel forward pass with input ids, attention mask, and past key values', 'review the BioGptAttention multi-headed attention module with cross-attention support', 'build a BioGPT causal language model with a language modeling head for next-token prediction', 'create a BioGPT sequence classifier with a linear classification head on the last token', 'create a BioGPT token classifier with a linear layer for per-token classification tasks', 'build the base BioGPT transformer model with encoder layers, embeddings, and causal attention', 'test the BioGptDecoderLayer forward pass with self-attention, dropout, and residual connections', 'create a BioGptTokenizer instance with vocab and merges files for Moses BPE tokenization', 'build model inputs with special tokens for BioGPT single or paired sequences', 'tokenize text using Moses tokenization followed by Byte-Pair Encoding BPE', 'convert a sequence of BPE tokens back to a detokenized string', 'save the tokenizer vocabulary and merges files to a directory']
```

Usage

```
{'convert_biogpt_checkpoint': 'convert a BioGpt fairseq PyTorch checkpoint to HuggingFace transformers format', 'load_biogpt_dictionary': 'load a fairseq dictionary from a text file with symbol and count pairs', 'add_symbol_to_dictionary': 'add a word symbol to a fairseq Dictionary with optional count and overwrite flag', 'rewrite_dictionary_keys': 'rewrite fairseq dictionary keys by stripping word-break @@ suffixes and adding </w> endings', 'run_conversion_cli': 'run the BioGpt checkpoint conversion script from the command line with checkpoint and output paths'}
```

## File: huggingface_transformers/src/transformers/models/biogpt/modeling_biogpt.py

Prompts

```
['convert a BioGpt fairseq PyTorch checkpoint to HuggingFace transformers format', 'load a fairseq dictionary from a text file with symbol and count pairs', 'add a word symbol to a fairseq Dictionary with optional count and overwrite flag', 'rewrite fairseq dictionary keys by stripping word-break @@ suffixes and adding </w> endings', 'run the BioGpt checkpoint conversion script from the command line with checkpoint and output paths', 'create a BioGptForCausalLM model for causal language modeling with past key value caching', 'build a BioGptForTokenClassification model for token-level classification tasks', 'test a BioGptForSequenceClassification model for sequence classification or regression', 'run the BioGptModel forward pass with input ids, attention mask, and past key values', 'review the BioGptAttention multi-headed attention module with cross-attention support', 'build a BioGPT causal language model with a language modeling head for next-token prediction', 'create a BioGPT sequence classifier with a linear classification head on the last token', 'create a BioGPT token classifier with a linear layer for per-token classification tasks', 'build the base BioGPT transformer model with encoder layers, embeddings, and causal attention', 'test the BioGptDecoderLayer forward pass with self-attention, dropout, and residual connections', 'create a BioGptTokenizer instance with vocab and merges files for Moses BPE tokenization', 'build model inputs with special tokens for BioGPT single or paired sequences', 'tokenize text using Moses tokenization followed by Byte-Pair Encoding BPE', 'convert a sequence of BPE tokens back to a detokenized string', 'save the tokenizer vocabulary and merges files to a directory']
```

Usage

```
{'create_biogpt_causal_lm': 'create a BioGptForCausalLM model for causal language modeling with past key value caching', 'build_biogpt_token_classifier': 'build a BioGptForTokenClassification model for token-level classification tasks', 'test_biogpt_sequence_classifier': 'test a BioGptForSequenceClassification model for sequence classification or regression', 'run_biogpt_forward': 'run the BioGptModel forward pass with input ids, attention mask, and past key values', 'review_biogpt_attention': 'review the BioGptAttention multi-headed attention module with cross-attention support'}
```

## File: huggingface_transformers/src/transformers/models/biogpt/modular_biogpt.py

Prompts

```
['convert a BioGpt fairseq PyTorch checkpoint to HuggingFace transformers format', 'load a fairseq dictionary from a text file with symbol and count pairs', 'add a word symbol to a fairseq Dictionary with optional count and overwrite flag', 'rewrite fairseq dictionary keys by stripping word-break @@ suffixes and adding </w> endings', 'run the BioGpt checkpoint conversion script from the command line with checkpoint and output paths', 'create a BioGptForCausalLM model for causal language modeling with past key value caching', 'build a BioGptForTokenClassification model for token-level classification tasks', 'test a BioGptForSequenceClassification model for sequence classification or regression', 'run the BioGptModel forward pass with input ids, attention mask, and past key values', 'review the BioGptAttention multi-headed attention module with cross-attention support', 'build a BioGPT causal language model with a language modeling head for next-token prediction', 'create a BioGPT sequence classifier with a linear classification head on the last token', 'create a BioGPT token classifier with a linear layer for per-token classification tasks', 'build the base BioGPT transformer model with encoder layers, embeddings, and causal attention', 'test the BioGptDecoderLayer forward pass with self-attention, dropout, and residual connections', 'create a BioGptTokenizer instance with vocab and merges files for Moses BPE tokenization', 'build model inputs with special tokens for BioGPT single or paired sequences', 'tokenize text using Moses tokenization followed by Byte-Pair Encoding BPE', 'convert a sequence of BPE tokens back to a detokenized string', 'save the tokenizer vocabulary and merges files to a directory']
```

Usage

```
{'build_biogpt_causal_lm': 'build a BioGPT causal language model with a language modeling head for next-token prediction', 'create_biogpt_sequence_classifier': 'create a BioGPT sequence classifier with a linear classification head on the last token', 'create_biogpt_token_classifier': 'create a BioGPT token classifier with a linear layer for per-token classification tasks', 'build_biogpt_model': 'build the base BioGPT transformer model with encoder layers, embeddings, and causal attention', 'test_biogpt_decoder_layer': 'test the BioGptDecoderLayer forward pass with self-attention, dropout, and residual connections'}
```

## File: huggingface_transformers/src/transformers/models/biogpt/tokenization_biogpt.py

Prompts

```
['convert a BioGpt fairseq PyTorch checkpoint to HuggingFace transformers format', 'load a fairseq dictionary from a text file with symbol and count pairs', 'add a word symbol to a fairseq Dictionary with optional count and overwrite flag', 'rewrite fairseq dictionary keys by stripping word-break @@ suffixes and adding </w> endings', 'run the BioGpt checkpoint conversion script from the command line with checkpoint and output paths', 'create a BioGptForCausalLM model for causal language modeling with past key value caching', 'build a BioGptForTokenClassification model for token-level classification tasks', 'test a BioGptForSequenceClassification model for sequence classification or regression', 'run the BioGptModel forward pass with input ids, attention mask, and past key values', 'review the BioGptAttention multi-headed attention module with cross-attention support', 'build a BioGPT causal language model with a language modeling head for next-token prediction', 'create a BioGPT sequence classifier with a linear classification head on the last token', 'create a BioGPT token classifier with a linear layer for per-token classification tasks', 'build the base BioGPT transformer model with encoder layers, embeddings, and causal attention', 'test the BioGptDecoderLayer forward pass with self-attention, dropout, and residual connections', 'create a BioGptTokenizer instance with vocab and merges files for Moses BPE tokenization', 'build model inputs with special tokens for BioGPT single or paired sequences', 'tokenize text using Moses tokenization followed by Byte-Pair Encoding BPE', 'convert a sequence of BPE tokens back to a detokenized string', 'save the tokenizer vocabulary and merges files to a directory']
```

Usage

```
{'create_biogpt_tokenizer': 'create a BioGptTokenizer instance with vocab and merges files for Moses BPE tokenization', 'build_inputs_special_tokens': 'build model inputs with special tokens for BioGPT single or paired sequences', 'tokenize_text_bpe': 'tokenize text using Moses tokenization followed by Byte-Pair Encoding BPE', 'convert_tokens_to_string': 'convert a sequence of BPE tokens back to a detokenized string', 'save_vocabulary_files': 'save the tokenizer vocabulary and merges files to a directory'}
```

