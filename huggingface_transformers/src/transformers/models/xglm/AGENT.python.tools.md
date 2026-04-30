# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/xglm/convert_xglm_original_ckpt_to_trfms.py

Prompts

```
['convert a fairseq XGLM checkpoint from disk to a Hugging Face XGLMForCausalLM model', 'remove ignored keys like decoder.version and output_projection.weight from a model state dict', "create an nn.Linear layer from an embedding layer's weight matrix for the LM head", 'build an XGLMConfig from fairseq checkpoint arguments including layers, heads, and embedding dimensions', 'run the CLI script to convert a fairseq XGLM model.pt to a saved PyTorch model folder', 'create an XGLMForCausalLM model with a language modeling head for autoregressive text generation', 'build an XGLMModel with sinusoidal positional embeddings and multi-headed self-attention layers', 'test the XGLMAttention module with multi-headed attention, key-value caching, and cross-attention support', 'review the XGLMDecoderLayer with self-attention, cross-attention, and feed-forward residual connections', 'summarize the XGLMScaledWordEmbedding and XGLMSinusoidalPositionalEmbedding modules for token and position encoding']
```

Usage

```
{'convert_fairseq_xglm_checkpoint': 'convert a fairseq XGLM checkpoint from disk to a Hugging Face XGLMForCausalLM model', 'remove_ignore_keys_from_state_dict': 'remove ignored keys like decoder.version and output_projection.weight from a model state dict', 'create_linear_layer_from_embeddings': "create an nn.Linear layer from an embedding layer's weight matrix for the LM head", 'build_xglm_config_from_fairseq_args': 'build an XGLMConfig from fairseq checkpoint arguments including layers, heads, and embedding dimensions', 'run_checkpoint_conversion_cli': 'run the CLI script to convert a fairseq XGLM model.pt to a saved PyTorch model folder'}
```

## File: huggingface_transformers/src/transformers/models/xglm/modeling_xglm.py

Prompts

```
['convert a fairseq XGLM checkpoint from disk to a Hugging Face XGLMForCausalLM model', 'remove ignored keys like decoder.version and output_projection.weight from a model state dict', "create an nn.Linear layer from an embedding layer's weight matrix for the LM head", 'build an XGLMConfig from fairseq checkpoint arguments including layers, heads, and embedding dimensions', 'run the CLI script to convert a fairseq XGLM model.pt to a saved PyTorch model folder', 'create an XGLMForCausalLM model with a language modeling head for autoregressive text generation', 'build an XGLMModel with sinusoidal positional embeddings and multi-headed self-attention layers', 'test the XGLMAttention module with multi-headed attention, key-value caching, and cross-attention support', 'review the XGLMDecoderLayer with self-attention, cross-attention, and feed-forward residual connections', 'summarize the XGLMScaledWordEmbedding and XGLMSinusoidalPositionalEmbedding modules for token and position encoding']
```

Usage

```
{'create_xglm_causal_lm': 'create an XGLMForCausalLM model with a language modeling head for autoregressive text generation', 'build_xglm_model': 'build an XGLMModel with sinusoidal positional embeddings and multi-headed self-attention layers', 'test_xglm_attention': 'test the XGLMAttention module with multi-headed attention, key-value caching, and cross-attention support', 'review_xglm_decoder_layer': 'review the XGLMDecoderLayer with self-attention, cross-attention, and feed-forward residual connections', 'summarize_xglm_embedding': 'summarize the XGLMScaledWordEmbedding and XGLMSinusoidalPositionalEmbedding modules for token and position encoding'}
```

