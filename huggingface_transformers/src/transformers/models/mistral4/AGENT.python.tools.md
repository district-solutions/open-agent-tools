# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/mistral4/convert_mistral4_weight_to_hf.py

Prompts

```
['convert Mistral4 weights from input directory to HuggingFace format and write to output directory', 'run the Mistral4 weight conversion CLI with input and output directories', 'convert a Mistral params.json configuration into a HuggingFace Mistral3 or Mistral4 config object', 'convert Mistral4 model weights from safetensors shards and write a HuggingFace model to disk', 'fuse per-expert MoE weights across all layers for a Mistral4 model', 'rename and optionally descale Mistral4 state dict shards to HuggingFace key format', 'convert and write Mistral4 tokenizer and vision processor to output directory', 'create a Mistral4ForCausalLM model with a pretrained config for autoregressive text generation', 'build a Mistral4Model base transformer with embedding, rotary embeddings, and stacked decoder layers', 'run Mistral4MoE with top-k expert routing, shared experts, and group-scoring token assignment', 'test Mistral4Attention with LoRA Q projection, compressed KV, MQA, and rotary position embeddings', 'review Mistral4DecoderLayer with RMSNorm, self-attention, and MoE or dense MLP feed-forward network', 'build a Mistral4ForSequenceClassification model for text classification tasks', 'build a Mistral4ForTokenClassification model for token-level prediction tasks', 'test the Mistral4MoE route_tokens_to_experts method with group-aware top-k selection', 'review the Mistral4Attention forward method with MQA compression and rotary embeddings']
```

Usage

```
{'convert_mistral4_weights_to_hf': 'convert Mistral4 weights from input directory to HuggingFace format and write to output directory', 'run_convert_cli_mistral4': 'run the Mistral4 weight conversion CLI with input and output directories', 'convert_mistral4_config_from_params': 'convert a Mistral params.json configuration into a HuggingFace Mistral3 or Mistral4 config object', 'convert_and_write_mistral4_model': 'convert Mistral4 model weights from safetensors shards and write a HuggingFace model to disk', 'fuse_mistral4_expert_weights': 'fuse per-expert MoE weights across all layers for a Mistral4 model', 'convert_mistral4_state_dict': 'rename and optionally descale Mistral4 state dict shards to HuggingFace key format', 'convert_mistral4_processor_and_tokenizer': 'convert and write Mistral4 tokenizer and vision processor to output directory'}
```

## File: huggingface_transformers/src/transformers/models/mistral4/modeling_mistral4.py

Prompts

```
['convert Mistral4 weights from input directory to HuggingFace format and write to output directory', 'run the Mistral4 weight conversion CLI with input and output directories', 'convert a Mistral params.json configuration into a HuggingFace Mistral3 or Mistral4 config object', 'convert Mistral4 model weights from safetensors shards and write a HuggingFace model to disk', 'fuse per-expert MoE weights across all layers for a Mistral4 model', 'rename and optionally descale Mistral4 state dict shards to HuggingFace key format', 'convert and write Mistral4 tokenizer and vision processor to output directory', 'create a Mistral4ForCausalLM model with a pretrained config for autoregressive text generation', 'build a Mistral4Model base transformer with embedding, rotary embeddings, and stacked decoder layers', 'run Mistral4MoE with top-k expert routing, shared experts, and group-scoring token assignment', 'test Mistral4Attention with LoRA Q projection, compressed KV, MQA, and rotary position embeddings', 'review Mistral4DecoderLayer with RMSNorm, self-attention, and MoE or dense MLP feed-forward network', 'build a Mistral4ForSequenceClassification model for text classification tasks', 'build a Mistral4ForTokenClassification model for token-level prediction tasks', 'test the Mistral4MoE route_tokens_to_experts method with group-aware top-k selection', 'review the Mistral4Attention forward method with MQA compression and rotary embeddings']
```

Usage

```
{'create_mistral4_causal_lm': 'create a Mistral4ForCausalLM model with a pretrained config for autoregressive text generation', 'build_mistral4_base_model': 'build a Mistral4Model base transformer with embedding, rotary embeddings, and stacked decoder layers', 'run_mistral4_moe_experts': 'run Mistral4MoE with top-k expert routing, shared experts, and group-scoring token assignment', 'test_mistral4_attention': 'test Mistral4Attention with LoRA Q projection, compressed KV, MQA, and rotary position embeddings', 'review_mistral4_decoder_layer': 'review Mistral4DecoderLayer with RMSNorm, self-attention, and MoE or dense MLP feed-forward network'}
```

## File: huggingface_transformers/src/transformers/models/mistral4/modular_mistral4.py

Prompts

```
['convert Mistral4 weights from input directory to HuggingFace format and write to output directory', 'run the Mistral4 weight conversion CLI with input and output directories', 'convert a Mistral params.json configuration into a HuggingFace Mistral3 or Mistral4 config object', 'convert Mistral4 model weights from safetensors shards and write a HuggingFace model to disk', 'fuse per-expert MoE weights across all layers for a Mistral4 model', 'rename and optionally descale Mistral4 state dict shards to HuggingFace key format', 'convert and write Mistral4 tokenizer and vision processor to output directory', 'create a Mistral4ForCausalLM model with a pretrained config for autoregressive text generation', 'build a Mistral4Model base transformer with embedding, rotary embeddings, and stacked decoder layers', 'run Mistral4MoE with top-k expert routing, shared experts, and group-scoring token assignment', 'test Mistral4Attention with LoRA Q projection, compressed KV, MQA, and rotary position embeddings', 'review Mistral4DecoderLayer with RMSNorm, self-attention, and MoE or dense MLP feed-forward network', 'build a Mistral4ForSequenceClassification model for text classification tasks', 'build a Mistral4ForTokenClassification model for token-level prediction tasks', 'test the Mistral4MoE route_tokens_to_experts method with group-aware top-k selection', 'review the Mistral4Attention forward method with MQA compression and rotary embeddings']
```

Usage

```
{'create_mistral4_causal_lm': 'create a Mistral4ForCausalLM model for autoregressive text generation', 'build_mistral4_sequence_classifier': 'build a Mistral4ForSequenceClassification model for text classification tasks', 'build_mistral4_token_classifier': 'build a Mistral4ForTokenClassification model for token-level prediction tasks', 'test_mistral4_moe_routing': 'test the Mistral4MoE route_tokens_to_experts method with group-aware top-k selection', 'review_mistral4_attention': 'review the Mistral4Attention forward method with MQA compression and rotary embeddings'}
```

