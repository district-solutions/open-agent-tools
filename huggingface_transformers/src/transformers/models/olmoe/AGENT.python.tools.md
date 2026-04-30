# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/olmoe/convert_olmoe_weights_to_hf.py

Prompts

```
['convert OLMoE checkpoint weights from AllenAI format to HuggingFace Transformers format', 'create an OlmoeConfig from OLMoE checkpoint YAML configuration parameters', 'run the OLMoE weight conversion CLI with input_dir, tokenizer_json_path, and output_dir arguments', 'write a GPTNeoXTokenizerFast from OLMoE tokenizer JSON with EOS and PAD token fixes', 'split fused QKV projection weights into separate q_proj, k_proj, and v_proj tensors', 'create an OlmoeForCausalLM model from pretrained weights for autoregressive text generation', 'build an OlmoeModel with sparse mixture-of-experts transformer layers and rotary embeddings', 'run text generation with OlmoeForCausalLM using tokenizer inputs and max length parameter', 'compute auxiliary load balancing loss for MoE expert routing using gate logits and attention mask', 'apply rotary position embedding to query and key tensors for transformer attention', 'implement an OlmoeSparseMoeBlock with top-K expert routing and gating for sparse MoE inference', 'configure OlmoeAttention with query-key-value normalization and clipping for transformer layers']
```

Usage

```
{'convert_olmoe_weights_to_hf': 'convert OLMoE checkpoint weights from AllenAI format to HuggingFace Transformers format', 'create_olmoe_model_config': 'create an OlmoeConfig from OLMoE checkpoint YAML configuration parameters', 'run_olmoe_conversion_cli': 'run the OLMoE weight conversion CLI with input_dir, tokenizer_json_path, and output_dir arguments', 'write_olmoe_tokenizer': 'write a GPTNeoXTokenizerFast from OLMoE tokenizer JSON with EOS and PAD token fixes', 'split_qkv_projections': 'split fused QKV projection weights into separate q_proj, k_proj, and v_proj tensors'}
```

## File: huggingface_transformers/src/transformers/models/olmoe/modeling_olmoe.py

Prompts

```
['convert OLMoE checkpoint weights from AllenAI format to HuggingFace Transformers format', 'create an OlmoeConfig from OLMoE checkpoint YAML configuration parameters', 'run the OLMoE weight conversion CLI with input_dir, tokenizer_json_path, and output_dir arguments', 'write a GPTNeoXTokenizerFast from OLMoE tokenizer JSON with EOS and PAD token fixes', 'split fused QKV projection weights into separate q_proj, k_proj, and v_proj tensors', 'create an OlmoeForCausalLM model from pretrained weights for autoregressive text generation', 'build an OlmoeModel with sparse mixture-of-experts transformer layers and rotary embeddings', 'run text generation with OlmoeForCausalLM using tokenizer inputs and max length parameter', 'compute auxiliary load balancing loss for MoE expert routing using gate logits and attention mask', 'apply rotary position embedding to query and key tensors for transformer attention', 'implement an OlmoeSparseMoeBlock with top-K expert routing and gating for sparse MoE inference', 'configure OlmoeAttention with query-key-value normalization and clipping for transformer layers']
```

Usage

```
{'create_olmoe_causal_lm': 'create an OlmoeForCausalLM model from pretrained weights for autoregressive text generation', 'build_olmoe_model': 'build an OlmoeModel with sparse mixture-of-experts transformer layers and rotary embeddings', 'run_olmoe_generation': 'run text generation with OlmoeForCausalLM using tokenizer inputs and max length parameter', 'compute_load_balancing_loss': 'compute auxiliary load balancing loss for MoE expert routing using gate logits and attention mask', 'apply_rotary_position_embedding': 'apply rotary position embedding to query and key tensors for transformer attention'}
```

## File: huggingface_transformers/src/transformers/models/olmoe/modular_olmoe.py

Prompts

```
['convert OLMoE checkpoint weights from AllenAI format to HuggingFace Transformers format', 'create an OlmoeConfig from OLMoE checkpoint YAML configuration parameters', 'run the OLMoE weight conversion CLI with input_dir, tokenizer_json_path, and output_dir arguments', 'write a GPTNeoXTokenizerFast from OLMoE tokenizer JSON with EOS and PAD token fixes', 'split fused QKV projection weights into separate q_proj, k_proj, and v_proj tensors', 'create an OlmoeForCausalLM model from pretrained weights for autoregressive text generation', 'build an OlmoeModel with sparse mixture-of-experts transformer layers and rotary embeddings', 'run text generation with OlmoeForCausalLM using tokenizer inputs and max length parameter', 'compute auxiliary load balancing loss for MoE expert routing using gate logits and attention mask', 'apply rotary position embedding to query and key tensors for transformer attention', 'implement an OlmoeSparseMoeBlock with top-K expert routing and gating for sparse MoE inference', 'configure OlmoeAttention with query-key-value normalization and clipping for transformer layers']
```

Usage

```
{'create_olmoe_causal_lm': 'create an OlmoeForCausalLM model from pretrained weights for autoregressive text generation', 'build_olmoe_model': 'build an OlmoeModel with sparse mixture-of-experts transformer layers and rotary embeddings', 'run_olmoe_generation': 'run text generation with OlmoeForCausalLM using tokenizer inputs and max length parameter', 'implement_olmoe_sparse_moe_block': 'implement an OlmoeSparseMoeBlock with top-K expert routing and gating for sparse MoE inference', 'configure_olmoe_attention': 'configure OlmoeAttention with query-key-value normalization and clipping for transformer layers'}
```

