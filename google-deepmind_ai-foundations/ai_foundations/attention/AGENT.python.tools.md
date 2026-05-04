# Agent Python Tools

- repo: google-deepmind/ai-foundations
- repo_uri: https://github.com/google-deepmind/ai-foundations

## File: google-deepmind_ai-foundations/ai_foundations/attention/modules.py

Prompts

```
['build a transformer block that returns attention weights and QKV matrices for visualization', 'run the Gemma3 1B model forward pass to get attention weights and QKV matrices per layer', 'create an Output dataclass to hold logits, cache, attention weights, and QKV matrices', 'review the AttentionWeightBlock call method that normalizes inputs and applies attention then MLP', 'summarize the AttentionWeightGemma3_1B setup that creates embedder, transformer blocks, and final normalization layer', 'apply an attention mask to logits and compute softmax attention weights', 'compute attention weights from logits by masking invalid positions and applying softmax', 'post-process attention logits using a boolean mask to produce normalized attention probabilities', 'reshape masked and softmaxed attention logits into a 2D probability matrix', 'mask attention logits with K_MASK values then apply softmax normalization', 'extract Q, K, and V matrices for a single attention head from a given transformer layer', 'extract Q, K, and V matrices for all attention heads as lists from a given layer', 'get the query, key, and value projection matrices for a specific transformer layer number', 'reshape Q, K, V projections from 4D batched tensors into 2D sequence-by-embedding matrices', 'broadcast single K and V projections across all attention heads for multi-head analysis']
```

Usage

```
{'build_attention_weight_block': 'build a transformer block that returns attention weights and QKV matrices for visualization', 'run_attention_weight_gemma_forward': 'run the Gemma3 1B model forward pass to get attention weights and QKV matrices per layer', 'create_output_dataclass': 'create an Output dataclass to hold logits, cache, attention weights, and QKV matrices', 'review_attention_weight_block_call': 'review the AttentionWeightBlock call method that normalizes inputs and applies attention then MLP', 'summarize_attention_weight_gemma_setup': 'summarize the AttentionWeightGemma3_1B setup that creates embedder, transformer blocks, and final normalization layer'}
```

## File: google-deepmind_ai-foundations/ai_foundations/attention/post_process_attention.py

Prompts

```
['build a transformer block that returns attention weights and QKV matrices for visualization', 'run the Gemma3 1B model forward pass to get attention weights and QKV matrices per layer', 'create an Output dataclass to hold logits, cache, attention weights, and QKV matrices', 'review the AttentionWeightBlock call method that normalizes inputs and applies attention then MLP', 'summarize the AttentionWeightGemma3_1B setup that creates embedder, transformer blocks, and final normalization layer', 'apply an attention mask to logits and compute softmax attention weights', 'compute attention weights from logits by masking invalid positions and applying softmax', 'post-process attention logits using a boolean mask to produce normalized attention probabilities', 'reshape masked and softmaxed attention logits into a 2D probability matrix', 'mask attention logits with K_MASK values then apply softmax normalization', 'extract Q, K, and V matrices for a single attention head from a given transformer layer', 'extract Q, K, and V matrices for all attention heads as lists from a given layer', 'get the query, key, and value projection matrices for a specific transformer layer number', 'reshape Q, K, V projections from 4D batched tensors into 2D sequence-by-embedding matrices', 'broadcast single K and V projections across all attention heads for multi-head analysis']
```

Usage

```
{'apply_attention_mask': 'apply an attention mask to logits and compute softmax attention weights', 'compute_attention_weights': 'compute attention weights from logits by masking invalid positions and applying softmax', 'post_process_attention_logits': 'post-process attention logits using a boolean mask to produce normalized attention probabilities', 'reshape_attention_probs': 'reshape masked and softmaxed attention logits into a 2D probability matrix', 'mask_and_softmax_logits': 'mask attention logits with K_MASK values then apply softmax normalization'}
```

## File: google-deepmind_ai-foundations/ai_foundations/attention/qkv.py

Prompts

```
['build a transformer block that returns attention weights and QKV matrices for visualization', 'run the Gemma3 1B model forward pass to get attention weights and QKV matrices per layer', 'create an Output dataclass to hold logits, cache, attention weights, and QKV matrices', 'review the AttentionWeightBlock call method that normalizes inputs and applies attention then MLP', 'summarize the AttentionWeightGemma3_1B setup that creates embedder, transformer blocks, and final normalization layer', 'apply an attention mask to logits and compute softmax attention weights', 'compute attention weights from logits by masking invalid positions and applying softmax', 'post-process attention logits using a boolean mask to produce normalized attention probabilities', 'reshape masked and softmaxed attention logits into a 2D probability matrix', 'mask attention logits with K_MASK values then apply softmax normalization', 'extract Q, K, and V matrices for a single attention head from a given transformer layer', 'extract Q, K, and V matrices for all attention heads as lists from a given layer', 'get the query, key, and value projection matrices for a specific transformer layer number', 'reshape Q, K, V projections from 4D batched tensors into 2D sequence-by-embedding matrices', 'broadcast single K and V projections across all attention heads for multi-head analysis']
```

Usage

```
{'extract_qkv_single_head': 'extract Q, K, and V matrices for a single attention head from a given transformer layer', 'extract_qkv_all_heads': 'extract Q, K, and V matrices for all attention heads as lists from a given layer', 'get_matrices_for_layer': 'get the query, key, and value projection matrices for a specific transformer layer number', 'reshape_qkv_to_2d': 'reshape Q, K, V projections from 4D batched tensors into 2D sequence-by-embedding matrices', 'broadcast_kv_to_heads': 'broadcast single K and V projections across all attention heads for multi-head analysis'}
```

