# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/deepseek_v3/test_modeling_deepseek_v3.py

Prompts

```
['test the DeepseekV3ModelTest class which validates DeepseekV3Model, DeepseekV3ForCausalLM, DeepseekV3ForSequenceClassification, and DeepseekV3ForTokenClassification models', 'create a DeepseekV3Config with MoE parameters including n_routed_experts, kv_lora_rank, q_lora_rank, and routed_scaling_factor for model initialization', 'test DeepseekV3ForCausalLM generation with eager and SDPA attention implementations comparing outputs on padded text inputs', 'test torch.compile with static cache implementation on DeepseekV3ForCausalLM generating text from prompt inputs', 'test flex attention implementation with gradient computation on DeepseekV3 model classes with custom head dimensions']
```

Usage

```
{'test_modeling_deepseek_v3': 'test the DeepseekV3ModelTest class which validates DeepseekV3Model, DeepseekV3ForCausalLM, DeepseekV3ForSequenceClassification, and DeepseekV3ForTokenClassification models', 'create_config_deepseek_v3': 'create a DeepseekV3Config with MoE parameters including n_routed_experts, kv_lora_rank, q_lora_rank, and routed_scaling_factor for model initialization', 'test_generation_deepseek_v3': 'test DeepseekV3ForCausalLM generation with eager and SDPA attention implementations comparing outputs on padded text inputs', 'test_compile_static_cache_deepseek_v3': 'test torch.compile with static cache implementation on DeepseekV3ForCausalLM generating text from prompt inputs', 'test_flex_attention_deepseek_v3': 'test flex attention implementation with gradient computation on DeepseekV3 model classes with custom head dimensions'}
```

