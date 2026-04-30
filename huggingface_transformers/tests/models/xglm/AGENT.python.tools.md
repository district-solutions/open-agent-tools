# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/xglm/test_modeling_xglm.py

Prompts

```
['test the XGLMModel forward pass and verify output shapes match expected batch and sequence dimensions', 'test XGLMModel past key values caching and verify outputs match between cached and non-cached forward passes', 'test XGLMModel attention mask with past key values and verify masked outputs are consistent', 'test XGLMModel with large input sequences and verify past key values produce correct outputs', 'test XGLMForCausalLM with labels and verify loss and logits shapes are correct', 'test XGLMForCausalLM with gradient checkpointing enabled and verify forward and backward passes', 'test XGLMModel weight initialization and verify std and mean of projection weights match expected values', 'test XGLMForCausalLM batched text generation with left padding and verify outputs match non-padded results', 'test XGLMForCausalLM sampling-based text generation and verify decoded output matches expected string', 'test XGLMForCausalLM fp16 batched inference and verify no NaN values appear in logits']
```

Usage

```
{'test_xglm_model': 'test the XGLMModel forward pass and verify output shapes match expected batch and sequence dimensions', 'test_xglm_model_past': 'test XGLMModel past key values caching and verify outputs match between cached and non-cached forward passes', 'test_xglm_model_attention_mask_past': 'test XGLMModel attention mask with past key values and verify masked outputs are consistent', 'test_xglm_model_past_large_inputs': 'test XGLMModel with large input sequences and verify past key values produce correct outputs', 'test_xglm_lm_head_model': 'test XGLMForCausalLM with labels and verify loss and logits shapes are correct', 'test_xglm_gradient_checkpointing': 'test XGLMForCausalLM with gradient checkpointing enabled and verify forward and backward passes', 'test_xglm_weight_initialization': 'test XGLMModel weight initialization and verify std and mean of projection weights match expected values', 'test_batch_generation': 'test XGLMForCausalLM batched text generation with left padding and verify outputs match non-padded results', 'test_xglm_sample': 'test XGLMForCausalLM sampling-based text generation and verify decoded output matches expected string', 'test_batched_nan_fp16': 'test XGLMForCausalLM fp16 batched inference and verify no NaN values appear in logits'}
```

