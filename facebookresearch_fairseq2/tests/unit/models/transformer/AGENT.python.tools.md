# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/tests/unit/models/transformer/test_attention.py

Prompts

```
['test TorchSDPA and NaiveSDPA produce close results with causal or identity attention bias', 'test StandardMultiheadAttention works when query and key dimensions differ for encoder-decoder attention', 'create a CausalAttentionBias instance to mask future tokens in scaled dot-product attention', 'create an IdentityBias instance for unmasked scaled dot-product attention computation', 'run StandardMultiheadAttention forward pass with query, key, value tensors and a BatchLayout', 'test the CausalAttentionBias class to verify it produces correct causal masking tensors', 'test the CausalAttentionBias class with an attention window length parameter for sliding window masking', 'test the ALiBiAttentionBias class to verify it produces correct linear bias tensors per head', 'create a materialized attention bias tensor from a CausalAttentionBias or ALiBiAttentionBias with query and key batch layouts', 'review the BatchLayout class used to define sequence dimensions for query and key tensors in attention bias materialization']
```

Usage

```
{'test_torch_sdpa_vs_naive_sdpa': 'test TorchSDPA and NaiveSDPA produce close results with causal or identity attention bias', 'test_standard_multihead_attention_variable_dims': 'test StandardMultiheadAttention works when query and key dimensions differ for encoder-decoder attention', 'create_causal_attention_bias': 'create a CausalAttentionBias instance to mask future tokens in scaled dot-product attention', 'create_identity_attention_bias': 'create an IdentityBias instance for unmasked scaled dot-product attention computation', 'run_standard_multihead_attention_forward': 'run StandardMultiheadAttention forward pass with query, key, value tensors and a BatchLayout'}
```

## File: facebookresearch_fairseq2/tests/unit/models/transformer/test_attention_bias.py

Prompts

```
['test TorchSDPA and NaiveSDPA produce close results with causal or identity attention bias', 'test StandardMultiheadAttention works when query and key dimensions differ for encoder-decoder attention', 'create a CausalAttentionBias instance to mask future tokens in scaled dot-product attention', 'create an IdentityBias instance for unmasked scaled dot-product attention computation', 'run StandardMultiheadAttention forward pass with query, key, value tensors and a BatchLayout', 'test the CausalAttentionBias class to verify it produces correct causal masking tensors', 'test the CausalAttentionBias class with an attention window length parameter for sliding window masking', 'test the ALiBiAttentionBias class to verify it produces correct linear bias tensors per head', 'create a materialized attention bias tensor from a CausalAttentionBias or ALiBiAttentionBias with query and key batch layouts', 'review the BatchLayout class used to define sequence dimensions for query and key tensors in attention bias materialization']
```

Usage

```
{'test_CausalAttentionBias': 'test the CausalAttentionBias class to verify it produces correct causal masking tensors', 'test_CausalAttentionBias_window': 'test the CausalAttentionBias class with an attention window length parameter for sliding window masking', 'test_ALiBiAttentionBias': 'test the ALiBiAttentionBias class to verify it produces correct linear bias tensors per head', 'create_materialize_attention_bias': 'create a materialized attention bias tensor from a CausalAttentionBias or ALiBiAttentionBias with query and key batch layouts', 'review_BatchLayout': 'review the BatchLayout class used to define sequence dimensions for query and key tensors in attention bias materialization'}
```

