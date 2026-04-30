# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/blt/convert_blt_weights_to_hf.py

Prompts

```
['merge a main config and entropy params config into a unified BLT configuration dictionary', 'apply weight key mappings to convert original BLT tensor names to HuggingFace naming conventions', 'merge main model weights and entropy model weights into a unified state dict', 'convert ModuleList hash embeddings into a single fused embedding weight tensor', 'convert a BLT model from HuggingFace Hub format to a unified HuggingFace-compatible format', 'create a ByteLevel BPE tokenizer with BLT-specific vocabulary and save it to a directory', 'create a tokenizer config JSON file for the converted BLT model', 'upload a converted model directory to the Hugging Face Hub repository', 'create a BltForCausalLM model from a BltConfig for autoregressive text generation', 'build a BltModel forward pass with input_ids, patch_lengths, and attention_mask for encoder-decoder processing', 'run patch length computation from token entropies using BltPatcher with configurable threshold and patch_size', 'create a cross-attention mask for patch-based attention between sequence tokens and patch embeddings', 'compute hash-based token embeddings using polynomial rolling hashes over byte groups for the local encoder', 'build a BLT causal language model with BltForCausalLM for autoregressive text generation', 'create a BltModel forward pass that encodes input tokens through local encoder, global transformer, and local decoder', 'run the BltPatcher to compute token entropies and generate adaptive patch lengths for byte-level token grouping', 'review the BltCrossAttention module that enables cross-attention between patches and hidden states']
```

Usage

```
{'merge_configurations': 'merge a main config and entropy params config into a unified BLT configuration dictionary', 'apply_weight_mapping': 'apply weight key mappings to convert original BLT tensor names to HuggingFace naming conventions', 'merge_weights': 'merge main model weights and entropy model weights into a unified state dict', 'convert_hash_embeddings_to_fused': 'convert ModuleList hash embeddings into a single fused embedding weight tensor', 'convert_hf_blt_to_unified': 'convert a BLT model from HuggingFace Hub format to a unified HuggingFace-compatible format', 'create_tokenizer_json': 'create a ByteLevel BPE tokenizer with BLT-specific vocabulary and save it to a directory', 'create_tokenizer_config': 'create a tokenizer config JSON file for the converted BLT model', 'push_to_hub': 'upload a converted model directory to the Hugging Face Hub repository'}
```

## File: huggingface_transformers/src/transformers/models/blt/modeling_blt.py

Prompts

```
['merge a main config and entropy params config into a unified BLT configuration dictionary', 'apply weight key mappings to convert original BLT tensor names to HuggingFace naming conventions', 'merge main model weights and entropy model weights into a unified state dict', 'convert ModuleList hash embeddings into a single fused embedding weight tensor', 'convert a BLT model from HuggingFace Hub format to a unified HuggingFace-compatible format', 'create a ByteLevel BPE tokenizer with BLT-specific vocabulary and save it to a directory', 'create a tokenizer config JSON file for the converted BLT model', 'upload a converted model directory to the Hugging Face Hub repository', 'create a BltForCausalLM model from a BltConfig for autoregressive text generation', 'build a BltModel forward pass with input_ids, patch_lengths, and attention_mask for encoder-decoder processing', 'run patch length computation from token entropies using BltPatcher with configurable threshold and patch_size', 'create a cross-attention mask for patch-based attention between sequence tokens and patch embeddings', 'compute hash-based token embeddings using polynomial rolling hashes over byte groups for the local encoder', 'build a BLT causal language model with BltForCausalLM for autoregressive text generation', 'create a BltModel forward pass that encodes input tokens through local encoder, global transformer, and local decoder', 'run the BltPatcher to compute token entropies and generate adaptive patch lengths for byte-level token grouping', 'review the BltCrossAttention module that enables cross-attention between patches and hidden states']
```

Usage

```
{'create_blt_causal_lm_model': 'create a BltForCausalLM model from a BltConfig for autoregressive text generation', 'build_blt_model_forward_pass': 'build a BltModel forward pass with input_ids, patch_lengths, and attention_mask for encoder-decoder processing', 'run_blt_patch_length_computation': 'run patch length computation from token entropies using BltPatcher with configurable threshold and patch_size', 'create_blt_cross_attention_mask': 'create a cross-attention mask for patch-based attention between sequence tokens and patch embeddings', 'compute_hash_embeddings': 'compute hash-based token embeddings using polynomial rolling hashes over byte groups for the local encoder'}
```

## File: huggingface_transformers/src/transformers/models/blt/modular_blt.py

Prompts

```
['merge a main config and entropy params config into a unified BLT configuration dictionary', 'apply weight key mappings to convert original BLT tensor names to HuggingFace naming conventions', 'merge main model weights and entropy model weights into a unified state dict', 'convert ModuleList hash embeddings into a single fused embedding weight tensor', 'convert a BLT model from HuggingFace Hub format to a unified HuggingFace-compatible format', 'create a ByteLevel BPE tokenizer with BLT-specific vocabulary and save it to a directory', 'create a tokenizer config JSON file for the converted BLT model', 'upload a converted model directory to the Hugging Face Hub repository', 'create a BltForCausalLM model from a BltConfig for autoregressive text generation', 'build a BltModel forward pass with input_ids, patch_lengths, and attention_mask for encoder-decoder processing', 'run patch length computation from token entropies using BltPatcher with configurable threshold and patch_size', 'create a cross-attention mask for patch-based attention between sequence tokens and patch embeddings', 'compute hash-based token embeddings using polynomial rolling hashes over byte groups for the local encoder', 'build a BLT causal language model with BltForCausalLM for autoregressive text generation', 'create a BltModel forward pass that encodes input tokens through local encoder, global transformer, and local decoder', 'run the BltPatcher to compute token entropies and generate adaptive patch lengths for byte-level token grouping', 'review the BltCrossAttention module that enables cross-attention between patches and hidden states']
```

Usage

```
{'build_blt_causal_lm': 'build a BLT causal language model with BltForCausalLM for autoregressive text generation', 'create_blt_model_forward': 'create a BltModel forward pass that encodes input tokens through local encoder, global transformer, and local decoder', 'run_blt_patcher_entropy': 'run the BltPatcher to compute token entropies and generate adaptive patch lengths for byte-level token grouping', 'compute_hash_embeddings': 'compute hash-enhanced token embeddings using rolling polynomial hashes over byte groups', 'review_blt_cross_attention': 'review the BltCrossAttention module that enables cross-attention between patches and hidden states'}
```

