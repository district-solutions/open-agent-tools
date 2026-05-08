# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/examples/simultaneous_translation/modules/fixed_pre_decision.py

Prompts

```
['build a fixed stride monotonic attention model using the fixed_pooling_monotonic_attention decorator with WaitKAttention', 'create a WaitKAttentionFixedStride class registered as waitk_fixed_pre_decision for simultaneous translation', 'create a MonotonicAttentionFixedStride class registered as hard_aligned_fixed_pre_decision for simultaneous translation', 'create a MonotonicInfiniteLookbackAttentionFixedStride class registered as infinite_lookback_fixed_pre_decision for simultaneous translation', 'review the fixed_pooling_monotonic_attention decorator that creates FixedStrideMonotonicAttention with average or last pooling strategies', 'build a MonotonicAttention module for hard-aligned simultaneous translation with learnable p_choose strategy', 'build a MonotonicInfiniteLookbackAttention module with soft attention projections for infinite lookback', 'build a WaitKAttention module with fixed lagging for controllable latency simultaneous translation', 'build a ChunkwiseAttention module with Mocha chunk size for chunk-based simultaneous translation', 'review the MonotonicAttention forward method that computes p_choose, alpha, beta and returns attention output', 'build a TransformerMonotonicEncoderLayer that applies causal attention masking to encoder inputs', 'build a TransformerMonotonicDecoderLayer with monotonic attention for simultaneous translation', 'test the prune_incremental_state method to trim prev_key and prev_value buffers', 'review the TransformerMonotonicDecoderLayer forward method for self-attention and encoder-attention steps', 'summarize the monotonic transformer layer classes for simultaneous translation with constrained attention']
```

Usage

```
{'build_fixed_stride_monotonic_attention': 'build a fixed stride monotonic attention model using the fixed_pooling_monotonic_attention decorator with WaitKAttention', 'create_waitk_fixed_pre_decision': 'create a WaitKAttentionFixedStride class registered as waitk_fixed_pre_decision for simultaneous translation', 'create_hard_aligned_fixed_pre_decision': 'create a MonotonicAttentionFixedStride class registered as hard_aligned_fixed_pre_decision for simultaneous translation', 'create_infinite_lookback_fixed_pre_decision': 'create a MonotonicInfiniteLookbackAttentionFixedStride class registered as infinite_lookback_fixed_pre_decision for simultaneous translation', 'review_fixed_pooling_monotonic_attention': 'review the fixed_pooling_monotonic_attention decorator that creates FixedStrideMonotonicAttention with average or last pooling strategies'}
```

## File: facebookresearch_fairseq/examples/simultaneous_translation/modules/monotonic_multihead_attention.py

Prompts

```
['build a fixed stride monotonic attention model using the fixed_pooling_monotonic_attention decorator with WaitKAttention', 'create a WaitKAttentionFixedStride class registered as waitk_fixed_pre_decision for simultaneous translation', 'create a MonotonicAttentionFixedStride class registered as hard_aligned_fixed_pre_decision for simultaneous translation', 'create a MonotonicInfiniteLookbackAttentionFixedStride class registered as infinite_lookback_fixed_pre_decision for simultaneous translation', 'review the fixed_pooling_monotonic_attention decorator that creates FixedStrideMonotonicAttention with average or last pooling strategies', 'build a MonotonicAttention module for hard-aligned simultaneous translation with learnable p_choose strategy', 'build a MonotonicInfiniteLookbackAttention module with soft attention projections for infinite lookback', 'build a WaitKAttention module with fixed lagging for controllable latency simultaneous translation', 'build a ChunkwiseAttention module with Mocha chunk size for chunk-based simultaneous translation', 'review the MonotonicAttention forward method that computes p_choose, alpha, beta and returns attention output', 'build a TransformerMonotonicEncoderLayer that applies causal attention masking to encoder inputs', 'build a TransformerMonotonicDecoderLayer with monotonic attention for simultaneous translation', 'test the prune_incremental_state method to trim prev_key and prev_value buffers', 'review the TransformerMonotonicDecoderLayer forward method for self-attention and encoder-attention steps', 'summarize the monotonic transformer layer classes for simultaneous translation with constrained attention']
```

Usage

```
{'build_monotonic_attention': 'build a MonotonicAttention module for hard-aligned simultaneous translation with learnable p_choose strategy', 'build_infinite_lookback_attention': 'build a MonotonicInfiniteLookbackAttention module with soft attention projections for infinite lookback', 'build_waitk_attention': 'build a WaitKAttention module with fixed lagging for controllable latency simultaneous translation', 'build_chunkwise_attention': 'build a ChunkwiseAttention module with Mocha chunk size for chunk-based simultaneous translation', 'review_monotonic_attention_forward': 'review the MonotonicAttention forward method that computes p_choose, alpha, beta and returns attention output'}
```

## File: facebookresearch_fairseq/examples/simultaneous_translation/modules/monotonic_transformer_layer.py

Prompts

```
['build a fixed stride monotonic attention model using the fixed_pooling_monotonic_attention decorator with WaitKAttention', 'create a WaitKAttentionFixedStride class registered as waitk_fixed_pre_decision for simultaneous translation', 'create a MonotonicAttentionFixedStride class registered as hard_aligned_fixed_pre_decision for simultaneous translation', 'create a MonotonicInfiniteLookbackAttentionFixedStride class registered as infinite_lookback_fixed_pre_decision for simultaneous translation', 'review the fixed_pooling_monotonic_attention decorator that creates FixedStrideMonotonicAttention with average or last pooling strategies', 'build a MonotonicAttention module for hard-aligned simultaneous translation with learnable p_choose strategy', 'build a MonotonicInfiniteLookbackAttention module with soft attention projections for infinite lookback', 'build a WaitKAttention module with fixed lagging for controllable latency simultaneous translation', 'build a ChunkwiseAttention module with Mocha chunk size for chunk-based simultaneous translation', 'review the MonotonicAttention forward method that computes p_choose, alpha, beta and returns attention output', 'build a TransformerMonotonicEncoderLayer that applies causal attention masking to encoder inputs', 'build a TransformerMonotonicDecoderLayer with monotonic attention for simultaneous translation', 'test the prune_incremental_state method to trim prev_key and prev_value buffers', 'review the TransformerMonotonicDecoderLayer forward method for self-attention and encoder-attention steps', 'summarize the monotonic transformer layer classes for simultaneous translation with constrained attention']
```

Usage

```
{'build_monotonic_encoder_layer': 'build a TransformerMonotonicEncoderLayer that applies causal attention masking to encoder inputs', 'build_monotonic_decoder_layer': 'build a TransformerMonotonicDecoderLayer with monotonic attention for simultaneous translation', 'test_prune_incremental_state': 'test the prune_incremental_state method to trim prev_key and prev_value buffers', 'review_decoder_forward': 'review the TransformerMonotonicDecoderLayer forward method for self-attention and encoder-attention steps', 'summarize_monotonic_transformer_layer': 'summarize the monotonic transformer layer classes for simultaneous translation with constrained attention'}
```

