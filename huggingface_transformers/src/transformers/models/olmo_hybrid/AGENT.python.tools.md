# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/olmo_hybrid/configuration_olmo_hybrid.py

Prompts

```
['create an OlmoHybridConfig instance with default or custom model hyperparameters', 'build a mixed linear and full attention layer type schedule across transformer layers', 'validate that the OlmoHybridConfig has at least one linear and one full attention layer', 'configure linear attention parameters including key/value heads, head dims, and GatedDeltaNet init ranges', 'initialize rope parameters, RMS norm epsilon, and attention dropout for the OlmoHybrid model', 'convert an OLMo Hybrid model checkpoint to HuggingFace format with configurable dtype and sequence length', 'create a HuggingFace OlmoHybridForCausalLM model from an OLMo Hybrid distributed checkpoint directory', "build a HuggingFace tokenizer from an OLMo config's tokenizer identifier and save it alongside the converted model", "load an OLMo Hybrid distributed checkpoint's model state dict using a restricted pickle unpickler", 'convert OLMo Hybrid layer weights to HuggingFace naming conventions for both full attention and linear attention (FLA) layers', 'build an OlmoHybridForCausalLM model with tokenizer for text generation', 'create an OlmoHybridLinearAttentionDecoderLayer with gated delta rule linear attention', 'run forward pass on OlmoHybridAttentionDecoderLayer with full multi-head attention and RoPE', 'test OlmoHybridDynamicCache for managing KV and recurrent states across hybrid layers', 'review OlmoHybridGatedDeltaNet linear attention with separate q/k/v conv1d and chunk-gated delta rule', 'create an OlmoHybridConfig with mixed linear and full attention layer types', 'build an OlmoHybridModel with alternating linear and full attention decoder layers', 'run forward pass on OlmoHybridForCausalLM with dynamic cache for text generation', 'test OlmoHybridGatedDeltaNet with separate q/k/v conv1d and chunk-gated delta rule', 'review OlmoHybridDynamicCache managing KV cache and recurrent states across hybrid layers']
```

Usage

```
{'create_olmo_hybrid_config': 'create an OlmoHybridConfig instance with default or custom model hyperparameters', 'build_hybrid_layer_types': 'build a mixed linear and full attention layer type schedule across transformer layers', 'validate_olmo_hybrid_architecture': 'validate that the OlmoHybridConfig has at least one linear and one full attention layer', 'configure_linear_attention_params': 'configure linear attention parameters including key/value heads, head dims, and GatedDeltaNet init ranges', 'initialize_rope_and_norm_params': 'initialize rope parameters, RMS norm epsilon, and attention dropout for the OlmoHybrid model'}
```

## File: huggingface_transformers/src/transformers/models/olmo_hybrid/convert_olmo_hybrid_weights_to_hf.py

Prompts

```
['create an OlmoHybridConfig instance with default or custom model hyperparameters', 'build a mixed linear and full attention layer type schedule across transformer layers', 'validate that the OlmoHybridConfig has at least one linear and one full attention layer', 'configure linear attention parameters including key/value heads, head dims, and GatedDeltaNet init ranges', 'initialize rope parameters, RMS norm epsilon, and attention dropout for the OlmoHybrid model', 'convert an OLMo Hybrid model checkpoint to HuggingFace format with configurable dtype and sequence length', 'create a HuggingFace OlmoHybridForCausalLM model from an OLMo Hybrid distributed checkpoint directory', "build a HuggingFace tokenizer from an OLMo config's tokenizer identifier and save it alongside the converted model", "load an OLMo Hybrid distributed checkpoint's model state dict using a restricted pickle unpickler", 'convert OLMo Hybrid layer weights to HuggingFace naming conventions for both full attention and linear attention (FLA) layers', 'build an OlmoHybridForCausalLM model with tokenizer for text generation', 'create an OlmoHybridLinearAttentionDecoderLayer with gated delta rule linear attention', 'run forward pass on OlmoHybridAttentionDecoderLayer with full multi-head attention and RoPE', 'test OlmoHybridDynamicCache for managing KV and recurrent states across hybrid layers', 'review OlmoHybridGatedDeltaNet linear attention with separate q/k/v conv1d and chunk-gated delta rule', 'create an OlmoHybridConfig with mixed linear and full attention layer types', 'build an OlmoHybridModel with alternating linear and full attention decoder layers', 'run forward pass on OlmoHybridForCausalLM with dynamic cache for text generation', 'test OlmoHybridGatedDeltaNet with separate q/k/v conv1d and chunk-gated delta rule', 'review OlmoHybridDynamicCache managing KV cache and recurrent states across hybrid layers']
```

Usage

```
{'convert_olmo_hybrid_checkpoint': 'convert an OLMo Hybrid model checkpoint to HuggingFace format with configurable dtype and sequence length', 'create_hf_model_olmo_hybrid': 'create a HuggingFace OlmoHybridForCausalLM model from an OLMo Hybrid distributed checkpoint directory', 'build_tokenizer_olmo_hf': "build a HuggingFace tokenizer from an OLMo config's tokenizer identifier and save it alongside the converted model", 'load_olmo_distributed_checkpoint': "load an OLMo Hybrid distributed checkpoint's model state dict using a restricted pickle unpickler", 'convert_olmo_layer_weights': 'convert OLMo Hybrid layer weights to HuggingFace naming conventions for both full attention and linear attention (FLA) layers'}
```

## File: huggingface_transformers/src/transformers/models/olmo_hybrid/modeling_olmo_hybrid.py

Prompts

```
['create an OlmoHybridConfig instance with default or custom model hyperparameters', 'build a mixed linear and full attention layer type schedule across transformer layers', 'validate that the OlmoHybridConfig has at least one linear and one full attention layer', 'configure linear attention parameters including key/value heads, head dims, and GatedDeltaNet init ranges', 'initialize rope parameters, RMS norm epsilon, and attention dropout for the OlmoHybrid model', 'convert an OLMo Hybrid model checkpoint to HuggingFace format with configurable dtype and sequence length', 'create a HuggingFace OlmoHybridForCausalLM model from an OLMo Hybrid distributed checkpoint directory', "build a HuggingFace tokenizer from an OLMo config's tokenizer identifier and save it alongside the converted model", "load an OLMo Hybrid distributed checkpoint's model state dict using a restricted pickle unpickler", 'convert OLMo Hybrid layer weights to HuggingFace naming conventions for both full attention and linear attention (FLA) layers', 'build an OlmoHybridForCausalLM model with tokenizer for text generation', 'create an OlmoHybridLinearAttentionDecoderLayer with gated delta rule linear attention', 'run forward pass on OlmoHybridAttentionDecoderLayer with full multi-head attention and RoPE', 'test OlmoHybridDynamicCache for managing KV and recurrent states across hybrid layers', 'review OlmoHybridGatedDeltaNet linear attention with separate q/k/v conv1d and chunk-gated delta rule', 'create an OlmoHybridConfig with mixed linear and full attention layer types', 'build an OlmoHybridModel with alternating linear and full attention decoder layers', 'run forward pass on OlmoHybridForCausalLM with dynamic cache for text generation', 'test OlmoHybridGatedDeltaNet with separate q/k/v conv1d and chunk-gated delta rule', 'review OlmoHybridDynamicCache managing KV cache and recurrent states across hybrid layers']
```

Usage

```
{'build_causal_lm_model': 'build an OlmoHybridForCausalLM model with tokenizer for text generation', 'create_linear_attention_layer': 'create an OlmoHybridLinearAttentionDecoderLayer with gated delta rule linear attention', 'run_full_attention_forward': 'run forward pass on OlmoHybridAttentionDecoderLayer with full multi-head attention and RoPE', 'test_dynamic_cache_update': 'test OlmoHybridDynamicCache for managing KV and recurrent states across hybrid layers', 'review_gated_delta_net': 'review OlmoHybridGatedDeltaNet linear attention with separate q/k/v conv1d and chunk-gated delta rule'}
```

## File: huggingface_transformers/src/transformers/models/olmo_hybrid/modular_olmo_hybrid.py

Prompts

```
['create an OlmoHybridConfig instance with default or custom model hyperparameters', 'build a mixed linear and full attention layer type schedule across transformer layers', 'validate that the OlmoHybridConfig has at least one linear and one full attention layer', 'configure linear attention parameters including key/value heads, head dims, and GatedDeltaNet init ranges', 'initialize rope parameters, RMS norm epsilon, and attention dropout for the OlmoHybrid model', 'convert an OLMo Hybrid model checkpoint to HuggingFace format with configurable dtype and sequence length', 'create a HuggingFace OlmoHybridForCausalLM model from an OLMo Hybrid distributed checkpoint directory', "build a HuggingFace tokenizer from an OLMo config's tokenizer identifier and save it alongside the converted model", "load an OLMo Hybrid distributed checkpoint's model state dict using a restricted pickle unpickler", 'convert OLMo Hybrid layer weights to HuggingFace naming conventions for both full attention and linear attention (FLA) layers', 'build an OlmoHybridForCausalLM model with tokenizer for text generation', 'create an OlmoHybridLinearAttentionDecoderLayer with gated delta rule linear attention', 'run forward pass on OlmoHybridAttentionDecoderLayer with full multi-head attention and RoPE', 'test OlmoHybridDynamicCache for managing KV and recurrent states across hybrid layers', 'review OlmoHybridGatedDeltaNet linear attention with separate q/k/v conv1d and chunk-gated delta rule', 'create an OlmoHybridConfig with mixed linear and full attention layer types', 'build an OlmoHybridModel with alternating linear and full attention decoder layers', 'run forward pass on OlmoHybridForCausalLM with dynamic cache for text generation', 'test OlmoHybridGatedDeltaNet with separate q/k/v conv1d and chunk-gated delta rule', 'review OlmoHybridDynamicCache managing KV cache and recurrent states across hybrid layers']
```

Usage

```
{'create_hybrid_config': 'create an OlmoHybridConfig with mixed linear and full attention layer types', 'build_hybrid_model': 'build an OlmoHybridModel with alternating linear and full attention decoder layers', 'run_causal_lm_forward': 'run forward pass on OlmoHybridForCausalLM with dynamic cache for text generation', 'test_gated_delta_net': 'test OlmoHybridGatedDeltaNet with separate q/k/v conv1d and chunk-gated delta rule', 'review_dynamic_cache': 'review OlmoHybridDynamicCache managing KV cache and recurrent states across hybrid layers'}
```

