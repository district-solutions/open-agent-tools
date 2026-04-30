# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/diffllama/test_modeling_diffllama.py

Prompts

```
['test the DiffLlamaModel forward pass with input_ids and attention_mask', 'test DiffLlamaForSequenceClassification with single_label and multi_label problem types', 'test DiffLlamaForTokenClassification forward pass with token labels', 'test DiffLlamaForCausalLM config loading with old and new rope parameter formats', 'test DiffLlamaForCausalLM generation with flash_attention_2 and padding_side right', 'test DiffLlamaForCausalLM generation with StaticCache and torch.compile', 'test DiffLlamaForCausalLM forward with 4D stacked causal attention masks', 'test DiffLlamaForCausalLM forward with 4D causal mask and StaticCache', 'test DiffLlamaForCausalLM forward with partial 4D stacked causal mask in two passes', 'test DiffLlamaForCausalLM eager and sdpa attention produce matching generation outputs']
```

Usage

```
{'test_diffllama_model_forward': 'test the DiffLlamaModel forward pass with input_ids and attention_mask', 'test_diffllama_sequence_classification': 'test DiffLlamaForSequenceClassification with single_label and multi_label problem types', 'test_diffllama_token_classification': 'test DiffLlamaForTokenClassification forward pass with token labels', 'test_diffllama_rope_config_loading': 'test DiffLlamaForCausalLM config loading with old and new rope parameter formats', 'test_diffllama_flash_attention_2_generate': 'test DiffLlamaForCausalLM generation with flash_attention_2 and padding_side right', 'test_diffllama_static_cache_compile': 'test DiffLlamaForCausalLM generation with StaticCache and torch.compile', 'test_diffllama_4d_stacked_causal_mask': 'test DiffLlamaForCausalLM forward with 4D stacked causal attention masks', 'test_diffllama_4d_causal_mask_static_cache': 'test DiffLlamaForCausalLM forward with 4D causal mask and StaticCache', 'test_diffllama_partial_stacked_causal_mask': 'test DiffLlamaForCausalLM forward with partial 4D stacked causal mask in two passes', 'test_diffllama_eager_matches_sdpa_generate': 'test DiffLlamaForCausalLM eager and sdpa attention produce matching generation outputs'}
```

