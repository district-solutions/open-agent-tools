# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/afmoe/test_modeling_afmoe.py

Prompts

```
['test the AfmoeForCausalLM model to verify router logits are returned without auxiliary loss when output_router_logits is enabled', 'test the AfmoeModel to verify legacy fused expert weight conversion mapping is registered in the conversion mapping', 'test AfmoeForCausalLM generation with static cache and torch.compile to verify outputs match dynamic cache generation', 'create an AfmoeModelTester subclass to configure and run unit tests for AfmoeModel with MoE-specific parameters', 'test AfmoeModel and AfmoeForCausalLM for model outputs equivalence across different attention implementations']
```

Usage

```
{'test_model_router_logits_without_aux_loss': 'test the AfmoeForCausalLM model to verify router logits are returned without auxiliary loss when output_router_logits is enabled', 'test_moe_legacy_conversion_mapping': 'test the AfmoeModel to verify legacy fused expert weight conversion mapping is registered in the conversion mapping', 'test_compile_static_cache': 'test AfmoeForCausalLM generation with static cache and torch.compile to verify outputs match dynamic cache generation', 'create_afmoe_model_tester': 'create an AfmoeModelTester subclass to configure and run unit tests for AfmoeModel with MoE-specific parameters', 'test_model_outputs_equivalence': 'test AfmoeModel and AfmoeForCausalLM for model outputs equivalence across different attention implementations'}
```

