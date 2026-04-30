# Agent Python Tools

- repo: lucidrains/x-transformers
- repo_uri: https://github.com/lucidrains/x-transformers

## File: lucidrains_x-transformers/tests/test_external.py

Prompts

```
['test the flash_pack_seq feature of Attend, Attention, and AttentionLayers against standard padding baselines', 'test the Attend class with flash_pack_seq=True and flash=False for causal and non-causal attention', 'test the Attention class with flash_pack_seq=True for self-attention and cross-attention modes', 'test the AttentionLayers class with attn_flash_pack_seq=True and cross_attend=True', 'test numerical equivalence between standard padding and flash_pack_seq block masking implementations', 'test the XTransformer class for encoder-decoder bilingual translation with tied embeddings', 'test the TransformerWrapper class with KV cache for efficient autoregressive generation', 'test the Decoder class with cross-attention and external key-value projections', 'test the ContinuousTransformerWrapper with continuous autoregressive sequence generation', 'test the NeoMLP class for deep residual multilayer perceptron forward pass']
```

Usage

```
{'test_flash_pack_seq': 'test the flash_pack_seq feature of Attend, Attention, and AttentionLayers against standard padding baselines', 'test_Attend_flash_pack_seq': 'test the Attend class with flash_pack_seq=True and flash=False for causal and non-causal attention', 'test_Attention_flash_pack_seq': 'test the Attention class with flash_pack_seq=True for self-attention and cross-attention modes', 'test_AttentionLayers_flash_pack_seq': 'test the AttentionLayers class with attn_flash_pack_seq=True and cross_attend=True', 'test_flash_attention_equivalence': 'test numerical equivalence between standard padding and flash_pack_seq block masking implementations'}
```

## File: lucidrains_x-transformers/tests/test_x_transformers.py

Prompts

```
['test the flash_pack_seq feature of Attend, Attention, and AttentionLayers against standard padding baselines', 'test the Attend class with flash_pack_seq=True and flash=False for causal and non-causal attention', 'test the Attention class with flash_pack_seq=True for self-attention and cross-attention modes', 'test the AttentionLayers class with attn_flash_pack_seq=True and cross_attend=True', 'test numerical equivalence between standard padding and flash_pack_seq block masking implementations', 'test the XTransformer class for encoder-decoder bilingual translation with tied embeddings', 'test the TransformerWrapper class with KV cache for efficient autoregressive generation', 'test the Decoder class with cross-attention and external key-value projections', 'test the ContinuousTransformerWrapper with continuous autoregressive sequence generation', 'test the NeoMLP class for deep residual multilayer perceptron forward pass']
```

Usage

```
{'test_xtransformer_bilingual_translation': 'test the XTransformer class for encoder-decoder bilingual translation with tied embeddings', 'test_transformerwrapper_kv_cache_inference': 'test the TransformerWrapper class with KV cache for efficient autoregressive generation', 'test_decoder_cross_attention_with_context': 'test the Decoder class with cross-attention and external key-value projections', 'test_continuous_wrapper_autoregressive_generation': 'test the ContinuousTransformerWrapper with continuous autoregressive sequence generation', 'test_neo_mlp_deep_residual_network': 'test the NeoMLP class for deep residual multilayer perceptron forward pass'}
```

