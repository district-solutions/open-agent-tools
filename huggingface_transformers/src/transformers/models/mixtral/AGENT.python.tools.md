# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/mixtral/convert_mixtral_weights_to_hf.py

Prompts

```
['convert Mixtral model weights from Mistral checkpoint format to Hugging Face Transformers format', 'run the CLI script to convert Mixtral 7B weights from input_dir to output_dir', 'build a state dict that maps Mistral checkpoint keys to Hugging Face Mixtral layer names', 'compute the intermediate FFN dimension size with ffn_dim_multiplier and multiple_of alignment', 'permute attention query and key weights for sliced rotary position embeddings', 'build a MixtralForCausalLM model with autoregressive text generation and MoE routing', 'create a forward pass through MixtralModel with input_ids, attention_mask, and past_key_values caching', 'test the load_balancing_loss_func that penalizes unbalanced expert routing across layers', 'run MixtralSparseMoeBlock with top-k expert selection and weighted expert aggregation', 'review MixtralAttention with grouped-query attention, rotary embeddings, and KV cache support', 'build a MixtralForCausalLM model for autoregressive text generation with sparse mixture-of-experts', 'create a MixtralSparseMoeBlock with top-k router and expert selection for MoE forward pass', 'test the MixtralTopKRouter to compute softmax routing weights and select top-k experts per token', 'run a MixtralDecoderLayer with self-attention and MoE-MLP using residual connections and RMSNorm', 'summarize the load_balancing_loss_func that computes auxiliary loss to penalize unbalanced expert routing']
```

Usage

```
{'convert_mixtral_weights_to_hf_format': 'convert Mixtral model weights from Mistral checkpoint format to Hugging Face Transformers format', 'run_mixtral_weight_conversion_cli': 'run the CLI script to convert Mixtral 7B weights from input_dir to output_dir', 'build_mixtral_state_dict_conversion': 'build a state dict that maps Mistral checkpoint keys to Hugging Face Mixtral layer names', 'compute_ffn_intermediate_size': 'compute the intermediate FFN dimension size with ffn_dim_multiplier and multiple_of alignment', 'permute_attention_weights_for_rope': 'permute attention query and key weights for sliced rotary position embeddings'}
```

## File: huggingface_transformers/src/transformers/models/mixtral/modeling_mixtral.py

Prompts

```
['convert Mixtral model weights from Mistral checkpoint format to Hugging Face Transformers format', 'run the CLI script to convert Mixtral 7B weights from input_dir to output_dir', 'build a state dict that maps Mistral checkpoint keys to Hugging Face Mixtral layer names', 'compute the intermediate FFN dimension size with ffn_dim_multiplier and multiple_of alignment', 'permute attention query and key weights for sliced rotary position embeddings', 'build a MixtralForCausalLM model with autoregressive text generation and MoE routing', 'create a forward pass through MixtralModel with input_ids, attention_mask, and past_key_values caching', 'test the load_balancing_loss_func that penalizes unbalanced expert routing across layers', 'run MixtralSparseMoeBlock with top-k expert selection and weighted expert aggregation', 'review MixtralAttention with grouped-query attention, rotary embeddings, and KV cache support', 'build a MixtralForCausalLM model for autoregressive text generation with sparse mixture-of-experts', 'create a MixtralSparseMoeBlock with top-k router and expert selection for MoE forward pass', 'test the MixtralTopKRouter to compute softmax routing weights and select top-k experts per token', 'run a MixtralDecoderLayer with self-attention and MoE-MLP using residual connections and RMSNorm', 'summarize the load_balancing_loss_func that computes auxiliary loss to penalize unbalanced expert routing']
```

Usage

```
{'build_mixtral_causal_lm': 'build a MixtralForCausalLM model with autoregressive text generation and MoE routing', 'create_mixtral_model_forward': 'create a forward pass through MixtralModel with input_ids, attention_mask, and past_key_values caching', 'test_moe_load_balancing_loss': 'test the load_balancing_loss_func that penalizes unbalanced expert routing across layers', 'run_mixtral_sparse_moe_block': 'run MixtralSparseMoeBlock with top-k expert selection and weighted expert aggregation', 'review_mixtral_attention': 'review MixtralAttention with grouped-query attention, rotary embeddings, and KV cache support'}
```

## File: huggingface_transformers/src/transformers/models/mixtral/modular_mixtral.py

Prompts

```
['convert Mixtral model weights from Mistral checkpoint format to Hugging Face Transformers format', 'run the CLI script to convert Mixtral 7B weights from input_dir to output_dir', 'build a state dict that maps Mistral checkpoint keys to Hugging Face Mixtral layer names', 'compute the intermediate FFN dimension size with ffn_dim_multiplier and multiple_of alignment', 'permute attention query and key weights for sliced rotary position embeddings', 'build a MixtralForCausalLM model with autoregressive text generation and MoE routing', 'create a forward pass through MixtralModel with input_ids, attention_mask, and past_key_values caching', 'test the load_balancing_loss_func that penalizes unbalanced expert routing across layers', 'run MixtralSparseMoeBlock with top-k expert selection and weighted expert aggregation', 'review MixtralAttention with grouped-query attention, rotary embeddings, and KV cache support', 'build a MixtralForCausalLM model for autoregressive text generation with sparse mixture-of-experts', 'create a MixtralSparseMoeBlock with top-k router and expert selection for MoE forward pass', 'test the MixtralTopKRouter to compute softmax routing weights and select top-k experts per token', 'run a MixtralDecoderLayer with self-attention and MoE-MLP using residual connections and RMSNorm', 'summarize the load_balancing_loss_func that computes auxiliary loss to penalize unbalanced expert routing']
```

Usage

```
{'build_mixtral_for_causal_lm': 'build a MixtralForCausalLM model for autoregressive text generation with sparse mixture-of-experts', 'create_mixtral_sparse_moe_block': 'create a MixtralSparseMoeBlock with top-k router and expert selection for MoE forward pass', 'test_mixtral_topk_router': 'test the MixtralTopKRouter to compute softmax routing weights and select top-k experts per token', 'run_mixtral_decoder_layer': 'run a MixtralDecoderLayer with self-attention and MoE-MLP using residual connections and RMSNorm', 'summarize_load_balancing_loss_func': 'summarize the load_balancing_loss_func that computes auxiliary loss to penalize unbalanced expert routing'}
```

