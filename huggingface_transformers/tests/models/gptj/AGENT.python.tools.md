# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/tests/models/gptj/test_modeling_gptj.py

Prompts

```
['test the GPTJModel forward pass and verify output shape matches expected batch, sequence, and hidden dimensions', 'test GPTJModel past key values caching by comparing incremental generation with full sequence outputs', 'test GPTJModel past key values with attention mask to verify masked token handling during incremental generation', 'test GPTJModel past key values with large input batches to verify multi-token incremental generation correctness', 'test GPTJForCausalLM forward pass with labels to verify loss computation and logits shape', 'test GPTJForCausalLM backward pass with gradient checkpointing enabled to verify memory-efficient training', 'test GPTJForCausalLM batch text generation with padded and unpadded inputs using EleutherAI/gpt-j-6B', 'test GPTJForCausalLM deterministic text generation with and without gradient checkpointing', 'test GPTJForCausalLM stochastic sampling generation with and without token type ids', 'test loading GPTJModel from pretrained EleutherAI/gpt-j-6B checkpoint with float16 dtype', 'test GPTJConfig initialization and common configuration attributes', 'build a GPTJModelTester to generate config and input tensors for unit testing GPTJ models']
```

Usage

```
{'test_gptj_model': 'test the GPTJModel forward pass and verify output shape matches expected batch, sequence, and hidden dimensions', 'test_gptj_model_past': 'test GPTJModel past key values caching by comparing incremental generation with full sequence outputs', 'test_gptj_model_attention_mask_past': 'test GPTJModel past key values with attention mask to verify masked token handling during incremental generation', 'test_gptj_model_past_large_inputs': 'test GPTJModel past key values with large input batches to verify multi-token incremental generation correctness', 'test_gptj_lm_head_model': 'test GPTJForCausalLM forward pass with labels to verify loss computation and logits shape', 'test_gptj_gradient_checkpointing': 'test GPTJForCausalLM backward pass with gradient checkpointing enabled to verify memory-efficient training', 'test_batch_generation': 'test GPTJForCausalLM batch text generation with padded and unpadded inputs using EleutherAI/gpt-j-6B', 'test_lm_generate_gptj': 'test GPTJForCausalLM deterministic text generation with and without gradient checkpointing', 'test_gptj_sample': 'test GPTJForCausalLM stochastic sampling generation with and without token type ids', 'test_model_from_pretrained': 'test loading GPTJModel from pretrained EleutherAI/gpt-j-6B checkpoint with float16 dtype', 'test_config': 'test GPTJConfig initialization and common configuration attributes', 'build_gptj_model_tester': 'build a GPTJModelTester to generate config and input tensors for unit testing GPTJ models'}
```

