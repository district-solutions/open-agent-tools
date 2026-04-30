# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/vaultgemma/configuration_vaultgemma.py

Prompts

```
['create a VaultGemmaConfig instance with custom model parameters like hidden_size and num_hidden_layers', 'build a VaultGemmaConfig using default configuration values for the vaultgemma-1b model', 'test the VaultGemmaConfig validate_architecture method to ensure hidden_size is a multiple of num_attention_heads', 'review the VaultGemmaConfig __post_init__ method that auto-generates layer_types for sliding and full attention layers', 'summarize the VaultGemmaConfig parameters including query_pre_attn_scalar, final_logit_softcapping, and attn_logit_softcapping', 'create a VaultGemmaForCausalLM model for autoregressive text generation with logits softcapping', 'build a VaultGemmaModel encoder with rotary embeddings and sliding window attention', 'test the VaultGemmaAttention module with multi-head grouped query attention and rotary position embeddings', 'review the VaultGemmaDecoderLayer with self-attention, MLP, and residual connections', 'summarize the VaultGemmaMLP gated linear unit feedforward network with gate and up projections', 'build a VaultGemmaModel from a VaultGemmaConfig instance for causal language modeling', 'test the VaultGemmaDecoderLayer forward method with hidden_states, position_embeddings, and attention_mask', 'review the VaultGemmaDecoderLayer __init__ that removes post_attention_layernorm and post_feedforward_layernorm', 'summarize the VaultGemmaAttention __init__ that sets is_causal to True inheriting from Gemma2Attention']
```

Usage

```
{'create_VaultGemmaConfig': 'create a VaultGemmaConfig instance with custom model parameters like hidden_size and num_hidden_layers', 'build_VaultGemmaConfig_from_defaults': 'build a VaultGemmaConfig using default configuration values for the vaultgemma-1b model', 'test_VaultGemmaConfig_validate_architecture': 'test the VaultGemmaConfig validate_architecture method to ensure hidden_size is a multiple of num_attention_heads', 'review_VaultGemmaConfig_post_init': 'review the VaultGemmaConfig __post_init__ method that auto-generates layer_types for sliding and full attention layers', 'summarize_VaultGemmaConfig_parameters': 'summarize the VaultGemmaConfig parameters including query_pre_attn_scalar, final_logit_softcapping, and attn_logit_softcapping'}
```

## File: huggingface_transformers/src/transformers/models/vaultgemma/modeling_vaultgemma.py

Prompts

```
['create a VaultGemmaConfig instance with custom model parameters like hidden_size and num_hidden_layers', 'build a VaultGemmaConfig using default configuration values for the vaultgemma-1b model', 'test the VaultGemmaConfig validate_architecture method to ensure hidden_size is a multiple of num_attention_heads', 'review the VaultGemmaConfig __post_init__ method that auto-generates layer_types for sliding and full attention layers', 'summarize the VaultGemmaConfig parameters including query_pre_attn_scalar, final_logit_softcapping, and attn_logit_softcapping', 'create a VaultGemmaForCausalLM model for autoregressive text generation with logits softcapping', 'build a VaultGemmaModel encoder with rotary embeddings and sliding window attention', 'test the VaultGemmaAttention module with multi-head grouped query attention and rotary position embeddings', 'review the VaultGemmaDecoderLayer with self-attention, MLP, and residual connections', 'summarize the VaultGemmaMLP gated linear unit feedforward network with gate and up projections', 'build a VaultGemmaModel from a VaultGemmaConfig instance for causal language modeling', 'test the VaultGemmaDecoderLayer forward method with hidden_states, position_embeddings, and attention_mask', 'review the VaultGemmaDecoderLayer __init__ that removes post_attention_layernorm and post_feedforward_layernorm', 'summarize the VaultGemmaAttention __init__ that sets is_causal to True inheriting from Gemma2Attention']
```

Usage

```
{'create_vaultgemma_causal_lm': 'create a VaultGemmaForCausalLM model for autoregressive text generation with logits softcapping', 'build_vaultgemma_model': 'build a VaultGemmaModel encoder with rotary embeddings and sliding window attention', 'test_vaultgemma_attention': 'test the VaultGemmaAttention module with multi-head grouped query attention and rotary position embeddings', 'review_vaultgemma_decoder_layer': 'review the VaultGemmaDecoderLayer with self-attention, MLP, and residual connections', 'summarize_vaultgemma_mlp': 'summarize the VaultGemmaMLP gated linear unit feedforward network with gate and up projections'}
```

## File: huggingface_transformers/src/transformers/models/vaultgemma/modular_vaultgemma.py

Prompts

```
['create a VaultGemmaConfig instance with custom model parameters like hidden_size and num_hidden_layers', 'build a VaultGemmaConfig using default configuration values for the vaultgemma-1b model', 'test the VaultGemmaConfig validate_architecture method to ensure hidden_size is a multiple of num_attention_heads', 'review the VaultGemmaConfig __post_init__ method that auto-generates layer_types for sliding and full attention layers', 'summarize the VaultGemmaConfig parameters including query_pre_attn_scalar, final_logit_softcapping, and attn_logit_softcapping', 'create a VaultGemmaForCausalLM model for autoregressive text generation with logits softcapping', 'build a VaultGemmaModel encoder with rotary embeddings and sliding window attention', 'test the VaultGemmaAttention module with multi-head grouped query attention and rotary position embeddings', 'review the VaultGemmaDecoderLayer with self-attention, MLP, and residual connections', 'summarize the VaultGemmaMLP gated linear unit feedforward network with gate and up projections', 'build a VaultGemmaModel from a VaultGemmaConfig instance for causal language modeling', 'test the VaultGemmaDecoderLayer forward method with hidden_states, position_embeddings, and attention_mask', 'review the VaultGemmaDecoderLayer __init__ that removes post_attention_layernorm and post_feedforward_layernorm', 'summarize the VaultGemmaAttention __init__ that sets is_causal to True inheriting from Gemma2Attention']
```

Usage

```
{'create_VaultGemmaConfig': 'create a VaultGemmaConfig instance with custom model parameters like hidden_size and num_hidden_layers', 'build_VaultGemmaModel_from_config': 'build a VaultGemmaModel from a VaultGemmaConfig instance for causal language modeling', 'test_VaultGemmaDecoderLayer_forward': 'test the VaultGemmaDecoderLayer forward method with hidden_states, position_embeddings, and attention_mask', 'review_VaultGemmaDecoderLayer_init': 'review the VaultGemmaDecoderLayer __init__ that removes post_attention_layernorm and post_feedforward_layernorm', 'summarize_VaultGemmaAttention_init': 'summarize the VaultGemmaAttention __init__ that sets is_causal to True inheriting from Gemma2Attention'}
```

