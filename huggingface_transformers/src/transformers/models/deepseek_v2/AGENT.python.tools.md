# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/deepseek_v2/configuration_deepseek_v2.py

Prompts

```
['create a DeepseekV2Config instance with custom model parameters for DeepSeek-V2 architecture', 'create a DeepseekV2Config with MoE settings including n_routed_experts, topk_method, and n_shared_experts', 'create a DeepseekV2Config with MLa settings including kv_lora_rank, q_lora_rank, and head_dim', 'test the DeepseekV2Config.validate_architecture method to ensure hidden_size is a multiple of num_attention_heads', 'summarize the DeepseekV2Config class and its key parameters for initializing a DeepSeek-V2 model', 'create a DeepseekV2ForCausalLM model from config and generate text from a prompt', 'build a DeepseekV2Model base transformer with embedding, rotary embeddings, and decoder layers', 'test the DeepseekV2Moe module that routes tokens to experts using greedy or group_limited_greedy strategies', 'review the DeepseekV2Attention module with MQA, low-rank Q projection, and RoPE embeddings', 'summarize the DeepseekV2Experts module that computes per-expert forward passes with token weighting', 'create a DeepseekV2Config with custom hyperparameters for model initialization', 'build a DeepseekV2Moe module with routed and shared experts for mixture-of-layers inference', 'test DeepseekV2Attention with multi-query grouped attention and low-rank query projection', 'build a DeepseekV2DecoderLayer with attention and MoE or dense MLP based on layer index', 'summarize DeepseekV2RotaryEmbedding forward pass with dynamic RoPE frequency computation']
```

Usage

```
{'create_deepseek_v2_config': 'create a DeepseekV2Config instance with custom model parameters for DeepSeek-V2 architecture', 'create_deepseek_v2_config_with_moe': 'create a DeepseekV2Config with MoE settings including n_routed_experts, topk_method, and n_shared_experts', 'create_deepseek_v2_config_with_mla': 'create a DeepseekV2Config with MLa settings including kv_lora_rank, q_lora_rank, and head_dim', 'test_validate_architecture': 'test the DeepseekV2Config.validate_architecture method to ensure hidden_size is a multiple of num_attention_heads', 'summarize_deepseek_v2_config': 'summarize the DeepseekV2Config class and its key parameters for initializing a DeepSeek-V2 model'}
```

## File: huggingface_transformers/src/transformers/models/deepseek_v2/modeling_deepseek_v2.py

Prompts

```
['create a DeepseekV2Config instance with custom model parameters for DeepSeek-V2 architecture', 'create a DeepseekV2Config with MoE settings including n_routed_experts, topk_method, and n_shared_experts', 'create a DeepseekV2Config with MLa settings including kv_lora_rank, q_lora_rank, and head_dim', 'test the DeepseekV2Config.validate_architecture method to ensure hidden_size is a multiple of num_attention_heads', 'summarize the DeepseekV2Config class and its key parameters for initializing a DeepSeek-V2 model', 'create a DeepseekV2ForCausalLM model from config and generate text from a prompt', 'build a DeepseekV2Model base transformer with embedding, rotary embeddings, and decoder layers', 'test the DeepseekV2Moe module that routes tokens to experts using greedy or group_limited_greedy strategies', 'review the DeepseekV2Attention module with MQA, low-rank Q projection, and RoPE embeddings', 'summarize the DeepseekV2Experts module that computes per-expert forward passes with token weighting', 'create a DeepseekV2Config with custom hyperparameters for model initialization', 'build a DeepseekV2Moe module with routed and shared experts for mixture-of-layers inference', 'test DeepseekV2Attention with multi-query grouped attention and low-rank query projection', 'build a DeepseekV2DecoderLayer with attention and MoE or dense MLP based on layer index', 'summarize DeepseekV2RotaryEmbedding forward pass with dynamic RoPE frequency computation']
```

Usage

```
{'create_deepseekv2_causal_lm': 'create a DeepseekV2ForCausalLM model from config and generate text from a prompt', 'build_deepseekv2_base_model': 'build a DeepseekV2Model base transformer with embedding, rotary embeddings, and decoder layers', 'test_deepseekv2_moe_routing': 'test the DeepseekV2Moe module that routes tokens to experts using greedy or group_limited_greedy strategies', 'review_deepseekv2_attention': 'review the DeepseekV2Attention module with MQA, low-rank Q projection, and RoPE embeddings', 'summarize_deepseekv2_experts': 'summarize the DeepseekV2Experts module that computes per-expert forward passes with token weighting'}
```

## File: huggingface_transformers/src/transformers/models/deepseek_v2/modular_deepseek_v2.py

Prompts

```
['create a DeepseekV2Config instance with custom model parameters for DeepSeek-V2 architecture', 'create a DeepseekV2Config with MoE settings including n_routed_experts, topk_method, and n_shared_experts', 'create a DeepseekV2Config with MLa settings including kv_lora_rank, q_lora_rank, and head_dim', 'test the DeepseekV2Config.validate_architecture method to ensure hidden_size is a multiple of num_attention_heads', 'summarize the DeepseekV2Config class and its key parameters for initializing a DeepSeek-V2 model', 'create a DeepseekV2ForCausalLM model from config and generate text from a prompt', 'build a DeepseekV2Model base transformer with embedding, rotary embeddings, and decoder layers', 'test the DeepseekV2Moe module that routes tokens to experts using greedy or group_limited_greedy strategies', 'review the DeepseekV2Attention module with MQA, low-rank Q projection, and RoPE embeddings', 'summarize the DeepseekV2Experts module that computes per-expert forward passes with token weighting', 'create a DeepseekV2Config with custom hyperparameters for model initialization', 'build a DeepseekV2Moe module with routed and shared experts for mixture-of-layers inference', 'test DeepseekV2Attention with multi-query grouped attention and low-rank query projection', 'build a DeepseekV2DecoderLayer with attention and MoE or dense MLP based on layer index', 'summarize DeepseekV2RotaryEmbedding forward pass with dynamic RoPE frequency computation']
```

Usage

```
{'create_config_deepseek_v2': 'create a DeepseekV2Config with custom hyperparameters for model initialization', 'build_deepseek_v2_moe': 'build a DeepseekV2Moe module with routed and shared experts for mixture-of-layers inference', 'test_deepseek_v2_attention': 'test DeepseekV2Attention with multi-query grouped attention and low-rank query projection', 'build_deepseek_v2_decoder_layer': 'build a DeepseekV2DecoderLayer with attention and MoE or dense MLP based on layer index', 'summarize_deepseek_v2_rotary_embedding': 'summarize DeepseekV2RotaryEmbedding forward pass with dynamic RoPE frequency computation'}
```

