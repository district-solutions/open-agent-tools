# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/git/test_modeling_git.py

Prompts

```
['test the GitVisionModel forward pass with pixel values and verify output shape matches expected sequence length', 'test the GitModel forward pass with input_ids, attention_mask, and pixel values to verify last_hidden_state shape', 'test GitForCausalLM inference with and without pixel values, and verify loss computation during training', 'test batched image captioning generation with GitForCausalLM using generate method with no input_ids', 'test that the KV cache is formatted correctly for GitForCausalLM generate with image tokens included in sequence length']
```

Usage

```
{'test_git_vision_model_forward': 'test the GitVisionModel forward pass with pixel values and verify output shape matches expected sequence length', 'test_git_model_forward': 'test the GitModel forward pass with input_ids, attention_mask, and pixel values to verify last_hidden_state shape', 'test_git_causal_lm_training': 'test GitForCausalLM inference with and without pixel values, and verify loss computation during training', 'test_batched_image_captioning': 'test batched image captioning generation with GitForCausalLM using generate method with no input_ids', 'test_past_key_values_format': 'test that the KV cache is formatted correctly for GitForCausalLM generate with image tokens included in sequence length'}
```

