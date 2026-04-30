# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/mpt/test_modeling_mpt.py

Prompts

```
['test the MptModel forward pass and verify output shape matches expected batch, sequence, and hidden dimensions', 'test MptModel past key values caching and verify outputs match between cached and non-cached forward passes', 'test MptForCausalLM with labels to verify loss computation and logits shape', 'test MptForSequenceClassification to verify logits shape matches batch size and number of labels', 'test MptForTokenClassification to verify logits shape matches batch, sequence length, and label count', 'test MptForCausalLM with gradient checkpointing enabled and verify backward pass', 'test MptModel weight initialization by verifying c_proj weight std and mean match expected values', 'test MptConfig creation with attn_config as dictionary to verify flash attention parameters are set correctly', 'test MptForCausalLM generation with 4-bit quantized mpt-7b model and verify decoded output matches expected text', 'test batched generation with 4-bit quantized mpt-7b model and verify each decoded output matches expected text']
```

Usage

```
{'test_mpt_model': 'test the MptModel forward pass and verify output shape matches expected batch, sequence, and hidden dimensions', 'test_mpt_model_past': 'test MptModel past key values caching and verify outputs match between cached and non-cached forward passes', 'test_mpt_lm_head_model': 'test MptForCausalLM with labels to verify loss computation and logits shape', 'test_mpt_sequence_classification_model': 'test MptForSequenceClassification to verify logits shape matches batch size and number of labels', 'test_mpt_token_classification_model': 'test MptForTokenClassification to verify logits shape matches batch, sequence length, and label count', 'test_mpt_gradient_checkpointing': 'test MptForCausalLM with gradient checkpointing enabled and verify backward pass', 'test_mpt_weight_initialization': 'test MptModel weight initialization by verifying c_proj weight std and mean match expected values', 'test_mpt_config_attn_config_as_dict': 'test MptConfig creation with attn_config as dictionary to verify flash attention parameters are set correctly', 'test_generation_mpt_7b': 'test MptForCausalLM generation with 4-bit quantized mpt-7b model and verify decoded output matches expected text', 'test_generation_batched_mpt_7b': 'test batched generation with 4-bit quantized mpt-7b model and verify each decoded output matches expected text'}
```

