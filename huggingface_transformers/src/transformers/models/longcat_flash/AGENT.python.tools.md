# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/longcat_flash/modeling_longcat_flash.py

Prompts

```
['create a LongcatFlashForCausalLM model with config for autoregressive text generation', 'build a LongcatFlashMLA multi-head attention module with LoRA-compressed query-key-value projections', 'create a LongcatFlashDecoderLayer with dual sub-layers and shortcut MoE connections', 'build a LongcatFlashMoE mixed-expert module with top-k router and identity experts', 'test the LongcatFlashRotaryEmbedding module for computing rotary position embeddings', 'build a LongcatFlashForCausalLM model from a LongcatFlashConfig for autoregressive text generation', 'run the LongcatFlashModel forward pass with input_ids, attention_mask, and past_key_values for inference', 'build a LongcatFlashMoE module with a TopkRouter and LongcatFlashExperts for mixed-expert feed-forward computation', 'review the LongcatFlashMLA attention class that implements multi-latent attention with LoRA scaling and flash attention support']
```

Usage

```
{'create_longcat_flash_causal_lm': 'create a LongcatFlashForCausalLM model with config for autoregressive text generation', 'build_longcat_flash_mla_attention': 'build a LongcatFlashMLA multi-head attention module with LoRA-compressed query-key-value projections', 'create_longcat_flash_decoder_layer': 'create a LongcatFlashDecoderLayer with dual sub-layers and shortcut MoE connections', 'build_longcat_flash_moe_experts': 'build a LongcatFlashMoE mixed-expert module with top-k router and identity experts', 'test_longcat_flash_rotary_embedding': 'test the LongcatFlashRotaryEmbedding module for computing rotary position embeddings'}
```

## File: huggingface_transformers/src/transformers/models/longcat_flash/modular_longcat_flash.py

Prompts

```
['create a LongcatFlashForCausalLM model with config for autoregressive text generation', 'build a LongcatFlashMLA multi-head attention module with LoRA-compressed query-key-value projections', 'create a LongcatFlashDecoderLayer with dual sub-layers and shortcut MoE connections', 'build a LongcatFlashMoE mixed-expert module with top-k router and identity experts', 'test the LongcatFlashRotaryEmbedding module for computing rotary position embeddings', 'build a LongcatFlashForCausalLM model from a LongcatFlashConfig for autoregressive text generation', 'run the LongcatFlashModel forward pass with input_ids, attention_mask, and past_key_values for inference', 'build a LongcatFlashMoE module with a TopkRouter and LongcatFlashExperts for mixed-expert feed-forward computation', 'review the LongcatFlashMLA attention class that implements multi-latent attention with LoRA scaling and flash attention support']
```

Usage

```
{'build_longcat_flash_causal_lm': 'build a LongcatFlashForCausalLM model from a LongcatFlashConfig for autoregressive text generation', 'create_longcat_flash_decoder_layer': 'create a LongcatFlashDecoderLayer with dual-sublayer attention and shortcut MoE architecture', 'run_longcat_flash_forward': 'run the LongcatFlashModel forward pass with input_ids, attention_mask, and past_key_values for inference', 'build_moe_expert_routing': 'build a LongcatFlashMoE module with a TopkRouter and LongcatFlashExperts for mixed-expert feed-forward computation', 'review_longcat_flash_mla': 'review the LongcatFlashMLA attention class that implements multi-latent attention with LoRA scaling and flash attention support'}
```

