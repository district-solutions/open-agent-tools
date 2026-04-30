# Agent Python Tools

- repo: unslothai/unsloth
- repo_uri: https://github.com/unslothai/unsloth.git

## File: unslothai_unsloth/unsloth/utils/attention_dispatch.py

Prompts

```
['select an attention backend based on availability and priority order', 'run attention using config and context info with Q, K, V tensors', 'create an AttentionConfig dataclass with backend, head counts, and backend-specific kwargs', 'create an AttentionContext dataclass with batch, sequence, and mask metadata', 'build an attention pipeline using FlashAttention, xFormers, or SDPA backends', 'run formatted_int to convert a numeric value into a human-readable string with K, M, or B suffix', 'get model info from the Hugging Face Hub for a specific model_id with optional properties', 'list models from the Hugging Face Hub filtered by author, search query, sort order, and limit', 'test formatted_int with values under 1000, under 1 million, under 1 billion, and over 1 billion', 'test list_models with author unsloth, sort by downloads, limit 10, and search query', 'configure an SFTConfig to enable packed, padding-free training batches', 'enable runtime packed batch support on an existing Unsloth model and trainer', 'build an xFormers block-diagonal causal attention mask from packed sequence lengths', 'build a scaled-dot-product attention mask for packed sequences with optional sliding window', 'mask final tokens of packed samples in shift_labels so cross-entropy ignores boundaries']
```

Usage

```
{'select_attention_backend': 'select an attention backend based on availability and priority order', 'run_attention': 'run attention using config and context info with Q, K, V tensors', 'create_AttnetionConfig': 'create an AttentionConfig dataclass with backend, head counts, and backend-specific kwargs', 'create_AttnetionContext': 'create an AttentionContext dataclass with batch, sequence, and mask metadata', 'build_attention_backend': 'build an attention pipeline using FlashAttention, xFormers, or SDPA backends'}
```

## File: unslothai_unsloth/unsloth/utils/hf_hub.py

Prompts

```
['select an attention backend based on availability and priority order', 'run attention using config and context info with Q, K, V tensors', 'create an AttentionConfig dataclass with backend, head counts, and backend-specific kwargs', 'create an AttentionContext dataclass with batch, sequence, and mask metadata', 'build an attention pipeline using FlashAttention, xFormers, or SDPA backends', 'run formatted_int to convert a numeric value into a human-readable string with K, M, or B suffix', 'get model info from the Hugging Face Hub for a specific model_id with optional properties', 'list models from the Hugging Face Hub filtered by author, search query, sort order, and limit', 'test formatted_int with values under 1000, under 1 million, under 1 billion, and over 1 billion', 'test list_models with author unsloth, sort by downloads, limit 10, and search query', 'configure an SFTConfig to enable packed, padding-free training batches', 'enable runtime packed batch support on an existing Unsloth model and trainer', 'build an xFormers block-diagonal causal attention mask from packed sequence lengths', 'build a scaled-dot-product attention mask for packed sequences with optional sliding window', 'mask final tokens of packed samples in shift_labels so cross-entropy ignores boundaries']
```

Usage

```
{'run_formatted_int': 'run formatted_int to convert a numeric value into a human-readable string with K, M, or B suffix', 'get_model_info': 'get model info from the Hugging Face Hub for a specific model_id with optional properties', 'list_models': 'list models from the Hugging Face Hub filtered by author, search query, sort order, and limit', 'test_formatted_int': 'test formatted_int with values under 1000, under 1 million, under 1 billion, and over 1 billion', 'test_list_models': 'test list_models with author unsloth, sort by downloads, limit 10, and search query'}
```

## File: unslothai_unsloth/unsloth/utils/packing.py

Prompts

```
['select an attention backend based on availability and priority order', 'run attention using config and context info with Q, K, V tensors', 'create an AttentionConfig dataclass with backend, head counts, and backend-specific kwargs', 'create an AttentionContext dataclass with batch, sequence, and mask metadata', 'build an attention pipeline using FlashAttention, xFormers, or SDPA backends', 'run formatted_int to convert a numeric value into a human-readable string with K, M, or B suffix', 'get model info from the Hugging Face Hub for a specific model_id with optional properties', 'list models from the Hugging Face Hub filtered by author, search query, sort order, and limit', 'test formatted_int with values under 1000, under 1 million, under 1 billion, and over 1 billion', 'test list_models with author unsloth, sort by downloads, limit 10, and search query', 'configure an SFTConfig to enable packed, padding-free training batches', 'enable runtime packed batch support on an existing Unsloth model and trainer', 'build an xFormers block-diagonal causal attention mask from packed sequence lengths', 'build a scaled-dot-product attention mask for packed sequences with optional sliding window', 'mask final tokens of packed samples in shift_labels so cross-entropy ignores boundaries']
```

Usage

```
{'configure_sample_packing': 'configure an SFTConfig to enable packed, padding-free training batches', 'enable_sample_packing': 'enable runtime packed batch support on an existing Unsloth model and trainer', 'build_xformers_block_causal_mask': 'build an xFormers block-diagonal causal attention mask from packed sequence lengths', 'build_sdpa_packed_attention_mask': 'build a scaled-dot-product attention mask for packed sequences with optional sliding window', 'mask_packed_sequence_boundaries': 'mask final tokens of packed samples in shift_labels so cross-entropy ignores boundaries'}
```

