# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/openai_privacy_filter/convert_openai_privacy_filter_weights_to_hf.py

Prompts

```
['convert an OpenAI Privacy Filter checkpoint to HuggingFace Transformers format using CLI', 'build an OpenAIPrivacyFilterConfig from original config dict and state dict tensors', 'convert OpenAI Privacy Filter state dict weights to HuggingFace model format', 'create an OpenAIPrivacyFilterConverter tokenizer from o200k_base vocab with special tokens', 'split a combined qkv tensor into separate q, k, v tensors using model config', 'build an OpenAIPrivacyFilterModel with config and input_ids for forward pass inference', 'create an OpenAIPrivacyFilterForTokenClassification model from config for token classification tasks', 'test OpenAIPrivacyFilterAttention with query key value tensors and sliding window sinks parameter', 'review OpenAIPrivacyFilterExperts TopKRouter for mixture-of-experts routing with fp32 accumulation', 'summarize OpenAIPrivacyFilterEncoderLayer forward with layernorm residual attention mlp blocks', 'create an OpenAIPrivacyFilterConfig with NER labels for privacy token classification', 'build an OpenAIPrivacyFilterModel with sliding window attention and MoE MLP for privacy filtering', 'build an OpenAIPrivacyFilterForTokenClassification model to detect private entities in text', 'review the OpenAIPrivacyFilterAttention class with sink tokens and per-token QK scaling', 'review the OpenAIPrivacyFilterExperts class with fp32 accumulation and gating for MoE']
```

Usage

```
{'convert_openai_privacy_filter_checkpoint': 'convert an OpenAI Privacy Filter checkpoint to HuggingFace Transformers format using CLI', 'build_openai_privacy_filter_config': 'build an OpenAIPrivacyFilterConfig from original config dict and state dict tensors', 'convert_state_dict_weights': 'convert OpenAI Privacy Filter state dict weights to HuggingFace model format', 'create_openai_privacy_filter_converter': 'create an OpenAIPrivacyFilterConverter tokenizer from o200k_base vocab with special tokens', 'split_qkv_tensor_weights': 'split a combined qkv tensor into separate q, k, v tensors using model config'}
```

## File: huggingface_transformers/src/transformers/models/openai_privacy_filter/modeling_openai_privacy_filter.py

Prompts

```
['convert an OpenAI Privacy Filter checkpoint to HuggingFace Transformers format using CLI', 'build an OpenAIPrivacyFilterConfig from original config dict and state dict tensors', 'convert OpenAI Privacy Filter state dict weights to HuggingFace model format', 'create an OpenAIPrivacyFilterConverter tokenizer from o200k_base vocab with special tokens', 'split a combined qkv tensor into separate q, k, v tensors using model config', 'build an OpenAIPrivacyFilterModel with config and input_ids for forward pass inference', 'create an OpenAIPrivacyFilterForTokenClassification model from config for token classification tasks', 'test OpenAIPrivacyFilterAttention with query key value tensors and sliding window sinks parameter', 'review OpenAIPrivacyFilterExperts TopKRouter for mixture-of-experts routing with fp32 accumulation', 'summarize OpenAIPrivacyFilterEncoderLayer forward with layernorm residual attention mlp blocks', 'create an OpenAIPrivacyFilterConfig with NER labels for privacy token classification', 'build an OpenAIPrivacyFilterModel with sliding window attention and MoE MLP for privacy filtering', 'build an OpenAIPrivacyFilterForTokenClassification model to detect private entities in text', 'review the OpenAIPrivacyFilterAttention class with sink tokens and per-token QK scaling', 'review the OpenAIPrivacyFilterExperts class with fp32 accumulation and gating for MoE']
```

Usage

```
{'build_privacy_filter_model': 'build an OpenAIPrivacyFilterModel with config and input_ids for forward pass inference', 'create_token_classifier': 'create an OpenAIPrivacyFilterForTokenClassification model from config for token classification tasks', 'test_attention_with_sinks': 'test OpenAIPrivacyFilterAttention with query key value tensors and sliding window sinks parameter', 'review_moe_expert_routing': 'review OpenAIPrivacyFilterExperts TopKRouter for mixture-of-experts routing with fp32 accumulation', 'summarize_encoder_layer': 'summarize OpenAIPrivacyFilterEncoderLayer forward with layernorm residual attention mlp blocks'}
```

## File: huggingface_transformers/src/transformers/models/openai_privacy_filter/modular_openai_privacy_filter.py

Prompts

```
['convert an OpenAI Privacy Filter checkpoint to HuggingFace Transformers format using CLI', 'build an OpenAIPrivacyFilterConfig from original config dict and state dict tensors', 'convert OpenAI Privacy Filter state dict weights to HuggingFace model format', 'create an OpenAIPrivacyFilterConverter tokenizer from o200k_base vocab with special tokens', 'split a combined qkv tensor into separate q, k, v tensors using model config', 'build an OpenAIPrivacyFilterModel with config and input_ids for forward pass inference', 'create an OpenAIPrivacyFilterForTokenClassification model from config for token classification tasks', 'test OpenAIPrivacyFilterAttention with query key value tensors and sliding window sinks parameter', 'review OpenAIPrivacyFilterExperts TopKRouter for mixture-of-experts routing with fp32 accumulation', 'summarize OpenAIPrivacyFilterEncoderLayer forward with layernorm residual attention mlp blocks', 'create an OpenAIPrivacyFilterConfig with NER labels for privacy token classification', 'build an OpenAIPrivacyFilterModel with sliding window attention and MoE MLP for privacy filtering', 'build an OpenAIPrivacyFilterForTokenClassification model to detect private entities in text', 'review the OpenAIPrivacyFilterAttention class with sink tokens and per-token QK scaling', 'review the OpenAIPrivacyFilterExperts class with fp32 accumulation and gating for MoE']
```

Usage

```
{'create_OpenAIPrivacyFilterConfig': 'create an OpenAIPrivacyFilterConfig with NER labels for privacy token classification', 'build_OpenAIPrivacyFilterModel': 'build an OpenAIPrivacyFilterModel with sliding window attention and MoE MLP for privacy filtering', 'build_OpenAIPrivacyFilterForTokenClassification': 'build an OpenAIPrivacyFilterForTokenClassification model to detect private entities in text', 'review_OpenAIPrivacyFilterAttention': 'review the OpenAIPrivacyFilterAttention class with sink tokens and per-token QK scaling', 'review_OpenAIPrivacyFilterExperts': 'review the OpenAIPrivacyFilterExperts class with fp32 accumulation and gating for MoE'}
```

