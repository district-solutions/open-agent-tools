# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/tests/unit/models/olmo/test_olmo_attention.py

Prompts

```
['test that OLMOMultiheadAttention rejects a mismatched rope_encoder encoding dimension', 'test that OLMOMultiheadAttention extra_repr includes the num_heads parameter', 'test that OLMOMultiheadAttention forward pass produces the correct output tensor shape', 'run OLMOMultiheadAttention forward pass with random sequences and an attention bias cache', 'review the OLMOMultiheadAttention class initialization and forward method for correctness', 'test that KV-cached incremental decoding of OLMO2-1B produces identical logits to a full-sequence forward pass', 'run get_olmo_model_hub to obtain a ModelHub instance for loading pretrained OLMO transformer models', 'run hub.load_model to load a pretrained OLMO checkpoint by name with a specified device and dtype', 'run load_tokenizer to load a tokenizer for a given OLMO model and create an encoder for tokenizing text', 'run IncrementalStateBag to manage KV-cache state across step-by-step incremental decoding of transformer models', 'test the _OLMOHuggingFaceConverter to_hg_config method that maps OLMOConfig fields to HuggingFace Olmo2Config or Olmo3Config attributes', 'test the _OLMOHuggingFaceConverter to_hg_state_dict method that converts fairseq2 state dict keys to HuggingFace format with model. and lm_head. prefixes', 'test the convert_olmo_state_dict function for fairseq2 to HuggingFace and back round-trip key equivalence', 'test the _OLMOHuggingFaceConverter to_hg_state_dict method to verify lm_head.weight is omitted when tied_embeddings is True', 'test the _OLMOHuggingFaceConverter to_hg_config method that maps YaRNScaleConfig to Olmo3Config rope_scaling with yarn rope_type']
```

Usage

```
{'test_OLMOMultiheadAttention_init_rejects_mismatched_rope': 'test that OLMOMultiheadAttention rejects a mismatched rope_encoder encoding dimension', 'test_OLMOMultiheadAttention_extra_repr_shows_heads': 'test that OLMOMultiheadAttention extra_repr includes the num_heads parameter', 'test_OLMOMultiheadAttention_forward_correct_shape': 'test that OLMOMultiheadAttention forward pass produces the correct output tensor shape', 'run_OLMOMultiheadAttention_forward': 'run OLMOMultiheadAttention forward pass with random sequences and an attention bias cache', 'review_OLMOMultiheadAttention_class': 'review the OLMOMultiheadAttention class initialization and forward method for correctness'}
```

## File: facebookresearch_fairseq2/tests/unit/models/olmo/test_olmo_incremental_decode.py

Prompts

```
['test that OLMOMultiheadAttention rejects a mismatched rope_encoder encoding dimension', 'test that OLMOMultiheadAttention extra_repr includes the num_heads parameter', 'test that OLMOMultiheadAttention forward pass produces the correct output tensor shape', 'run OLMOMultiheadAttention forward pass with random sequences and an attention bias cache', 'review the OLMOMultiheadAttention class initialization and forward method for correctness', 'test that KV-cached incremental decoding of OLMO2-1B produces identical logits to a full-sequence forward pass', 'run get_olmo_model_hub to obtain a ModelHub instance for loading pretrained OLMO transformer models', 'run hub.load_model to load a pretrained OLMO checkpoint by name with a specified device and dtype', 'run load_tokenizer to load a tokenizer for a given OLMO model and create an encoder for tokenizing text', 'run IncrementalStateBag to manage KV-cache state across step-by-step incremental decoding of transformer models', 'test the _OLMOHuggingFaceConverter to_hg_config method that maps OLMOConfig fields to HuggingFace Olmo2Config or Olmo3Config attributes', 'test the _OLMOHuggingFaceConverter to_hg_state_dict method that converts fairseq2 state dict keys to HuggingFace format with model. and lm_head. prefixes', 'test the convert_olmo_state_dict function for fairseq2 to HuggingFace and back round-trip key equivalence', 'test the _OLMOHuggingFaceConverter to_hg_state_dict method to verify lm_head.weight is omitted when tied_embeddings is True', 'test the _OLMOHuggingFaceConverter to_hg_config method that maps YaRNScaleConfig to Olmo3Config rope_scaling with yarn rope_type']
```

Usage

```
{'test_olmo2_incremental_decode': 'test that KV-cached incremental decoding of OLMO2-1B produces identical logits to a full-sequence forward pass', 'run_get_olmo_model_hub': 'run get_olmo_model_hub to obtain a ModelHub instance for loading pretrained OLMO transformer models', 'run_load_model': 'run hub.load_model to load a pretrained OLMO checkpoint by name with a specified device and dtype', 'run_load_tokenizer': 'run load_tokenizer to load a tokenizer for a given OLMO model and create an encoder for tokenizing text', 'run_incremental_state_bag': 'run IncrementalStateBag to manage KV-cache state across step-by-step incremental decoding of transformer models'}
```

## File: facebookresearch_fairseq2/tests/unit/models/olmo/test_olmo_interop.py

Prompts

```
['test that OLMOMultiheadAttention rejects a mismatched rope_encoder encoding dimension', 'test that OLMOMultiheadAttention extra_repr includes the num_heads parameter', 'test that OLMOMultiheadAttention forward pass produces the correct output tensor shape', 'run OLMOMultiheadAttention forward pass with random sequences and an attention bias cache', 'review the OLMOMultiheadAttention class initialization and forward method for correctness', 'test that KV-cached incremental decoding of OLMO2-1B produces identical logits to a full-sequence forward pass', 'run get_olmo_model_hub to obtain a ModelHub instance for loading pretrained OLMO transformer models', 'run hub.load_model to load a pretrained OLMO checkpoint by name with a specified device and dtype', 'run load_tokenizer to load a tokenizer for a given OLMO model and create an encoder for tokenizing text', 'run IncrementalStateBag to manage KV-cache state across step-by-step incremental decoding of transformer models', 'test the _OLMOHuggingFaceConverter to_hg_config method that maps OLMOConfig fields to HuggingFace Olmo2Config or Olmo3Config attributes', 'test the _OLMOHuggingFaceConverter to_hg_state_dict method that converts fairseq2 state dict keys to HuggingFace format with model. and lm_head. prefixes', 'test the convert_olmo_state_dict function for fairseq2 to HuggingFace and back round-trip key equivalence', 'test the _OLMOHuggingFaceConverter to_hg_state_dict method to verify lm_head.weight is omitted when tied_embeddings is True', 'test the _OLMOHuggingFaceConverter to_hg_config method that maps YaRNScaleConfig to Olmo3Config rope_scaling with yarn rope_type']
```

Usage

```
{'test_OLMOHuggingFaceConverter_to_hg_config': 'test the _OLMOHuggingFaceConverter to_hg_config method that maps OLMOConfig fields to HuggingFace Olmo2Config or Olmo3Config attributes', 'test_OLMOHuggingFaceConverter_to_hg_state_dict': 'test the _OLMOHuggingFaceConverter to_hg_state_dict method that converts fairseq2 state dict keys to HuggingFace format with model. and lm_head. prefixes', 'test_convert_olmo_state_dict_round_trip': 'test the convert_olmo_state_dict function for fairseq2 to HuggingFace and back round-trip key equivalence', 'test_OLMOHuggingFaceConverter_tied_embeddings': 'test the _OLMOHuggingFaceConverter to_hg_state_dict method to verify lm_head.weight is omitted when tied_embeddings is True', 'test_OLMOHuggingFaceConverter_yarn_config': 'test the _OLMOHuggingFaceConverter to_hg_config method that maps YaRNScaleConfig to Olmo3Config rope_scaling with yarn rope_type'}
```

