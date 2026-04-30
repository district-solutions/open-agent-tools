# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/transformers/models/bloom/modeling_bloom.py

Prompts

```
['build an ALiBi tensor for BLOOM attention using gaudi_bloom_build_alibi_tensor with attention mask and num heads', 'run the Gaudi-optimized BLOOM attention forward pass with hidden states, ALiBi tensor, and attention mask', 'run the Gaudi-optimized BLOOM transformer block forward pass with layer norm, self attention, and MLP', 'run the full Gaudi-optimized BLOOM model forward pass with input IDs, past key values, and attention mask', 'run the Gaudi-optimized BLOOM causal LM forward pass to get logits and optional loss from labels']
```

Usage

```
{'build_alibi_tensor': 'build an ALiBi tensor for BLOOM attention using gaudi_bloom_build_alibi_tensor with attention mask and num heads', 'run_gaudi_bloom_attention_forward': 'run the Gaudi-optimized BLOOM attention forward pass with hidden states, ALiBi tensor, and attention mask', 'run_gaudi_bloom_block_forward': 'run the Gaudi-optimized BLOOM transformer block forward pass with layer norm, self attention, and MLP', 'run_gaudi_bloom_model_forward': 'run the full Gaudi-optimized BLOOM model forward pass with input IDs, past key values, and attention mask', 'run_gaudi_bloom_for_causal_lm_forward': 'run the Gaudi-optimized BLOOM causal LM forward pass to get logits and optional loss from labels'}
```

