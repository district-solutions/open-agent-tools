# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/olmo/convert_olmo_weights_to_hf.py

Prompts

```
['convert OLMo model weights from EleutherAI format to HuggingFace Transformers format using CLI', 'write OLMo checkpoint weights from input directory to HuggingFace model format in output directory', 'write GPTNeoX tokenizer from OLMo tokenizer JSON file to HuggingFace compatible format', 'compute the intermediate feed-forward layer size using FFN dim multiplier and multiple of 256', 'fix OLMo EOS token ID bug by changing incorrect value 0 to correct value 50279', 'create an OlmoForCausalLM model for autoregressive text generation with HuggingFace transformers', 'build an OlmoDecoderLayer with multi-headed attention, MLP, and pre-norm residual connections', 'test the OlmoAttention forward pass with query, key, value projections and rotary position embeddings', 'review the OlmoModel forward method that processes input embeddings through stacked decoder layers', 'summarize the OlmoMLP class implementing gated linear unit feed-forward network', 'build an OlmoForCausalLM model from an OlmoConfig for autoregressive text generation', 'create an OlmoModel with OlmoDecoderLayers and OlmoLayerNorm for transformer inference', 'run OlmoAttention with query, key, value projections and rotary position embeddings', 'test OlmoRotaryEmbedding forward pass that returns float32 cos and sin position embeddings', 'review OlmoMLP with separate gate and up projections instead of fused GELU multiplicative gating']
```

Usage

```
{'convert_olmo_weights_to_hf': 'convert OLMo model weights from EleutherAI format to HuggingFace Transformers format using CLI', 'write_olmo_model': 'write OLMo checkpoint weights from input directory to HuggingFace model format in output directory', 'write_olmo_tokenizer': 'write GPTNeoX tokenizer from OLMo tokenizer JSON file to HuggingFace compatible format', 'compute_intermediate_size': 'compute the intermediate feed-forward layer size using FFN dim multiplier and multiple of 256', 'fix_olmo_eos_token_id': 'fix OLMo EOS token ID bug by changing incorrect value 0 to correct value 50279'}
```

## File: huggingface_transformers/src/transformers/models/olmo/modeling_olmo.py

Prompts

```
['convert OLMo model weights from EleutherAI format to HuggingFace Transformers format using CLI', 'write OLMo checkpoint weights from input directory to HuggingFace model format in output directory', 'write GPTNeoX tokenizer from OLMo tokenizer JSON file to HuggingFace compatible format', 'compute the intermediate feed-forward layer size using FFN dim multiplier and multiple of 256', 'fix OLMo EOS token ID bug by changing incorrect value 0 to correct value 50279', 'create an OlmoForCausalLM model for autoregressive text generation with HuggingFace transformers', 'build an OlmoDecoderLayer with multi-headed attention, MLP, and pre-norm residual connections', 'test the OlmoAttention forward pass with query, key, value projections and rotary position embeddings', 'review the OlmoModel forward method that processes input embeddings through stacked decoder layers', 'summarize the OlmoMLP class implementing gated linear unit feed-forward network', 'build an OlmoForCausalLM model from an OlmoConfig for autoregressive text generation', 'create an OlmoModel with OlmoDecoderLayers and OlmoLayerNorm for transformer inference', 'run OlmoAttention with query, key, value projections and rotary position embeddings', 'test OlmoRotaryEmbedding forward pass that returns float32 cos and sin position embeddings', 'review OlmoMLP with separate gate and up projections instead of fused GELU multiplicative gating']
```

Usage

```
{'create_olmo_causal_lm_model': 'create an OlmoForCausalLM model for autoregressive text generation with HuggingFace transformers', 'build_olmo_decoder_layer': 'build an OlmoDecoderLayer with multi-headed attention, MLP, and pre-norm residual connections', 'test_olmo_attention_forward': 'test the OlmoAttention forward pass with query, key, value projections and rotary position embeddings', 'review_olmo_model_forward': 'review the OlmoModel forward method that processes input embeddings through stacked decoder layers', 'summarize_olmo_mlp_gated': 'summarize the OlmoMLP class implementing gated linear unit feed-forward network'}
```

## File: huggingface_transformers/src/transformers/models/olmo/modular_olmo.py

Prompts

```
['convert OLMo model weights from EleutherAI format to HuggingFace Transformers format using CLI', 'write OLMo checkpoint weights from input directory to HuggingFace model format in output directory', 'write GPTNeoX tokenizer from OLMo tokenizer JSON file to HuggingFace compatible format', 'compute the intermediate feed-forward layer size using FFN dim multiplier and multiple of 256', 'fix OLMo EOS token ID bug by changing incorrect value 0 to correct value 50279', 'create an OlmoForCausalLM model for autoregressive text generation with HuggingFace transformers', 'build an OlmoDecoderLayer with multi-headed attention, MLP, and pre-norm residual connections', 'test the OlmoAttention forward pass with query, key, value projections and rotary position embeddings', 'review the OlmoModel forward method that processes input embeddings through stacked decoder layers', 'summarize the OlmoMLP class implementing gated linear unit feed-forward network', 'build an OlmoForCausalLM model from an OlmoConfig for autoregressive text generation', 'create an OlmoModel with OlmoDecoderLayers and OlmoLayerNorm for transformer inference', 'run OlmoAttention with query, key, value projections and rotary position embeddings', 'test OlmoRotaryEmbedding forward pass that returns float32 cos and sin position embeddings', 'review OlmoMLP with separate gate and up projections instead of fused GELU multiplicative gating']
```

Usage

```
{'build_olmo_causal_lm': 'build an OlmoForCausalLM model from an OlmoConfig for autoregressive text generation', 'create_olmo_model': 'create an OlmoModel with OlmoDecoderLayers and OlmoLayerNorm for transformer inference', 'run_olmo_attention': 'run OlmoAttention with query, key, value projections and rotary position embeddings', 'test_olmo_rotary_embedding': 'test OlmoRotaryEmbedding forward pass that returns float32 cos and sin position embeddings', 'review_olmo_mlp': 'review OlmoMLP with separate gate and up projections instead of fused GELU multiplicative gating'}
```

