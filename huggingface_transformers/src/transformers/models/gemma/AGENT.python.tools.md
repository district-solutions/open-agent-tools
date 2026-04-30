# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/gemma/convert_gemma_weights_to_hf.py

Prompts

```
['convert Gemma model weights from checkpoint format to HuggingFace transformers format using argparse CLI', 'build a HuggingFace GemmaForCausalLM model from 2B checkpoint weights and save to output directory', 'build a HuggingFace GemmaForCausalLM model from 7B checkpoint weights and save to output directory', 'convert Gemma SentencePiece tokenizer model to HuggingFace GemmaTokenizer format', 'push converted Gemma model and tokenizer to HuggingFace Hub instead of saving locally', 'create a GemmaForCausalLM model for text generation with a pretrained config', 'build a GemmaModel forward pass that processes input embeddings through decoder layers with rotary embeddings', 'test the GemmaAttention module with query key value projections and rotary position embedding application', 'refactor the GemmaDecoderLayer to support gradient checkpointing with input and post-attention layernorm residuals', 'summarize the GemmaMLP module that implements gated linear unit feedforward network with gate up down projections', 'create a GemmaConfig instance with custom model parameters like vocab_size and hidden_size', 'build a GemmaModel with scaled word embeddings and RMS normalization for forward passes', 'run a GemmaForCausalLM model to generate text from a tokenizer prompt with max length', 'review the GemmaMLP class with separate gate and up projections and rowwise down projection']
```

Usage

```
{'convert_gemma_weights_to_hf': 'convert Gemma model weights from checkpoint format to HuggingFace transformers format using argparse CLI', 'build_gemma_model_2b': 'build a HuggingFace GemmaForCausalLM model from 2B checkpoint weights and save to output directory', 'build_gemma_model_7b': 'build a HuggingFace GemmaForCausalLM model from 7B checkpoint weights and save to output directory', 'convert_gemma_tokenizer': 'convert Gemma SentencePiece tokenizer model to HuggingFace GemmaTokenizer format', 'push_gemma_model_to_hub': 'push converted Gemma model and tokenizer to HuggingFace Hub instead of saving locally'}
```

## File: huggingface_transformers/src/transformers/models/gemma/modeling_gemma.py

Prompts

```
['convert Gemma model weights from checkpoint format to HuggingFace transformers format using argparse CLI', 'build a HuggingFace GemmaForCausalLM model from 2B checkpoint weights and save to output directory', 'build a HuggingFace GemmaForCausalLM model from 7B checkpoint weights and save to output directory', 'convert Gemma SentencePiece tokenizer model to HuggingFace GemmaTokenizer format', 'push converted Gemma model and tokenizer to HuggingFace Hub instead of saving locally', 'create a GemmaForCausalLM model for text generation with a pretrained config', 'build a GemmaModel forward pass that processes input embeddings through decoder layers with rotary embeddings', 'test the GemmaAttention module with query key value projections and rotary position embedding application', 'refactor the GemmaDecoderLayer to support gradient checkpointing with input and post-attention layernorm residuals', 'summarize the GemmaMLP module that implements gated linear unit feedforward network with gate up down projections', 'create a GemmaConfig instance with custom model parameters like vocab_size and hidden_size', 'build a GemmaModel with scaled word embeddings and RMS normalization for forward passes', 'run a GemmaForCausalLM model to generate text from a tokenizer prompt with max length', 'review the GemmaMLP class with separate gate and up projections and rowwise down projection']
```

Usage

```
{'create_gemma_causal_lm': 'create a GemmaForCausalLM model for text generation with a pretrained config', 'build_gemma_model_forward': 'build a GemmaModel forward pass that processes input embeddings through decoder layers with rotary embeddings', 'test_gemma_attention': 'test the GemmaAttention module with query key value projections and rotary position embedding application', 'refactor_gemma_decoder_layer': 'refactor the GemmaDecoderLayer to support gradient checkpointing with input and post-attention layernorm residuals', 'summarize_gemma_mlp': 'summarize the GemmaMLP module that implements gated linear unit feedforward network with gate up down projections'}
```

## File: huggingface_transformers/src/transformers/models/gemma/modular_gemma.py

Prompts

```
['convert Gemma model weights from checkpoint format to HuggingFace transformers format using argparse CLI', 'build a HuggingFace GemmaForCausalLM model from 2B checkpoint weights and save to output directory', 'build a HuggingFace GemmaForCausalLM model from 7B checkpoint weights and save to output directory', 'convert Gemma SentencePiece tokenizer model to HuggingFace GemmaTokenizer format', 'push converted Gemma model and tokenizer to HuggingFace Hub instead of saving locally', 'create a GemmaForCausalLM model for text generation with a pretrained config', 'build a GemmaModel forward pass that processes input embeddings through decoder layers with rotary embeddings', 'test the GemmaAttention module with query key value projections and rotary position embedding application', 'refactor the GemmaDecoderLayer to support gradient checkpointing with input and post-attention layernorm residuals', 'summarize the GemmaMLP module that implements gated linear unit feedforward network with gate up down projections', 'create a GemmaConfig instance with custom model parameters like vocab_size and hidden_size', 'build a GemmaModel with scaled word embeddings and RMS normalization for forward passes', 'run a GemmaForCausalLM model to generate text from a tokenizer prompt with max length', 'review the GemmaMLP class with separate gate and up projections and rowwise down projection']
```

Usage

```
{'create_gemma_config': 'create a GemmaConfig instance with custom model parameters like vocab_size and hidden_size', 'build_gemma_model': 'build a GemmaModel with scaled word embeddings and RMS normalization for forward passes', 'run_gemma_causal_lm': 'run a GemmaForCausalLM model to generate text from a tokenizer prompt with max length', 'test_gemma_attention': 'test the GemmaAttention module with configurable bidirectional or causal attention mode', 'review_gemma_mlp': 'review the GemmaMLP class with separate gate and up projections and rowwise down projection'}
```

