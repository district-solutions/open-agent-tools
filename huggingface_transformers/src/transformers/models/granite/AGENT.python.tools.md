# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/granite/modeling_granite.py

Prompts

```
['create a GraniteForCausalLM model with a GraniteConfig for autoregressive text generation', 'build a GraniteModel with embedding tokens, decoder layers, RMS norm, and rotary embeddings for inference', 'run GraniteAttention multi-headed self-attention with rotary position embeddings and KV caching', 'test GraniteDecoderLayer with input layernorm, attention, MLP, and residual connections', 'summarize GraniteMLP using gate and up projections with SiLU activation and down projection', 'build a GraniteForCausalLM model with custom embedding, residual, and logits scaling for causal language modeling', 'create a GraniteAttention module with configurable attention multiplier for multi-headed attention', 'build a GraniteDecoderLayer with residual multiplier and GraniteAttention for transformer decoder blocks', 'run a GraniteForCausalLM forward pass with input_ids, attention_mask, and optional past_key_values for generation']
```

Usage

```
{'create_granite_causal_lm': 'create a GraniteForCausalLM model with a GraniteConfig for autoregressive text generation', 'build_granite_model': 'build a GraniteModel with embedding tokens, decoder layers, RMS norm, and rotary embeddings for inference', 'run_granite_attention': 'run GraniteAttention multi-headed self-attention with rotary position embeddings and KV caching', 'test_granite_decoder_layer': 'test GraniteDecoderLayer with input layernorm, attention, MLP, and residual connections', 'summarize_granite_mlp': 'summarize GraniteMLP using gate and up projections with SiLU activation and down projection'}
```

## File: huggingface_transformers/src/transformers/models/granite/modular_granite.py

Prompts

```
['create a GraniteForCausalLM model with a GraniteConfig for autoregressive text generation', 'build a GraniteModel with embedding tokens, decoder layers, RMS norm, and rotary embeddings for inference', 'run GraniteAttention multi-headed self-attention with rotary position embeddings and KV caching', 'test GraniteDecoderLayer with input layernorm, attention, MLP, and residual connections', 'summarize GraniteMLP using gate and up projections with SiLU activation and down projection', 'build a GraniteForCausalLM model with custom embedding, residual, and logits scaling for causal language modeling', 'create a GraniteAttention module with configurable attention multiplier for multi-headed attention', 'build a GraniteDecoderLayer with residual multiplier and GraniteAttention for transformer decoder blocks', 'run a GraniteForCausalLM forward pass with input_ids, attention_mask, and optional past_key_values for generation']
```

Usage

```
{'build_granite_causal_lm': 'build a GraniteForCausalLM model with custom embedding, residual, and logits scaling for causal language modeling', 'create_granite_attention': 'create a GraniteAttention module with configurable attention multiplier for multi-headed attention', 'build_granite_decoder_layer': 'build a GraniteDecoderLayer with residual multiplier and GraniteAttention for transformer decoder blocks', 'build_granite_model': 'build a GraniteModel with embedding multiplier and stacked GraniteDecoderLayers as the base transformer', 'run_granite_forward': 'run a GraniteForCausalLM forward pass with input_ids, attention_mask, and optional past_key_values for generation'}
```

