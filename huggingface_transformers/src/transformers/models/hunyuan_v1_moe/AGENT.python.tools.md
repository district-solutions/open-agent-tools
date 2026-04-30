# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/hunyuan_v1_moe/modeling_hunyuan_v1_moe.py

Prompts

```
['create a HunYuanMoEV1ForCausalLM model for autoregressive text generation with rotary embeddings and MoE layers', 'build a HunYuanMoEV1Model encoder with embedding tokens, decoder layers, RMS norm, and rotary position embeddings', 'run multi-headed attention with query key value projections, rotary position embedding, and KV caching via past_key_values', 'test the mixture-of-experts routing where a gate selects top-k experts per token and aggregates their outputs', 'review the DynamicNTKAlphaRotary embedding that extends RoPE with configurable alpha scaling for longer context windows', 'build a HunYuanMoEV1Moe block with gate routing, top-k expert selection, and shared MLP residual', 'create a HunYuanMoEV1DecoderLayer with MoE attention, RMS norm, and mixture-of-experts feed-forward', 'review HunYuanMoEV1PreTrainedModel weight initialization including DynamicNTKAlphaRotary and expert parameters']
```

Usage

```
{'create_model_causal_lm': 'create a HunYuanMoEV1ForCausalLM model for autoregressive text generation with rotary embeddings and MoE layers', 'build_model_encoder': 'build a HunYuanMoEV1Model encoder with embedding tokens, decoder layers, RMS norm, and rotary position embeddings', 'run_attention_forward': 'run multi-headed attention with query key value projections, rotary position embedding, and KV caching via past_key_values', 'test_moe_routing': 'test the mixture-of-experts routing where a gate selects top-k experts per token and aggregates their outputs', 'review_rope_embedding': 'review the DynamicNTKAlphaRotary embedding that extends RoPE with configurable alpha scaling for longer context windows'}
```

## File: huggingface_transformers/src/transformers/models/hunyuan_v1_moe/modular_hunyuan_v1_moe.py

Prompts

```
['create a HunYuanMoEV1ForCausalLM model for autoregressive text generation with rotary embeddings and MoE layers', 'build a HunYuanMoEV1Model encoder with embedding tokens, decoder layers, RMS norm, and rotary position embeddings', 'run multi-headed attention with query key value projections, rotary position embedding, and KV caching via past_key_values', 'test the mixture-of-experts routing where a gate selects top-k experts per token and aggregates their outputs', 'review the DynamicNTKAlphaRotary embedding that extends RoPE with configurable alpha scaling for longer context windows', 'build a HunYuanMoEV1Moe block with gate routing, top-k expert selection, and shared MLP residual', 'create a HunYuanMoEV1DecoderLayer with MoE attention, RMS norm, and mixture-of-experts feed-forward', 'review HunYuanMoEV1PreTrainedModel weight initialization including DynamicNTKAlphaRotary and expert parameters']
```

Usage

```
{'build_moe_block': 'build a HunYuanMoEV1Moe block with gate routing, top-k expert selection, and shared MLP residual', 'create_decoder_layer': 'create a HunYuanMoEV1DecoderLayer with MoE attention, RMS norm, and mixture-of-experts feed-forward', 'run_attention_forward': 'run HunYuanMoEV1Attention with query key layernorm, rotary embeddings, and KV cache support', 'test_moe_routing': 'test the HunYuanMoEV1Moe route_tokens_to_experts method for softmax routing and top-k expert aggregation', 'review_pretrained_model_init': 'review HunYuanMoEV1PreTrainedModel weight initialization including DynamicNTKAlphaRotary and expert parameters'}
```

