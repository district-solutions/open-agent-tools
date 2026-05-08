# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/models/w2vbert/config.py

Prompts

```
['create a W2VBertConfig with default 600m architecture settings for a w2v-BERT model', 'validate a W2VBertConfig to check layer_drop_p, encoder layers, and codebook constraints', 'register the 300m and 600m w2v-BERT architecture presets into a DependencyContainer', 'customize the nested Wav2Vec2EncoderConfig to change model_dim, attention heads, or ffn_inner_dim', 'configure temporal and spatial masking parameters like span_len and max_prob in the w2v2_config', 'create a W2VBertModel from a W2VBertConfig using the create_w2vbert_model convenience function', 'create a W2VBertModel by instantiating W2VBertFactory with a config and calling create_model', 'create a Wav2Vec2Model from the W2VBertFactory using the create_wav2vec2_model method', 'review the W2VBertFactory create_model method to understand config validation for layer_drop_p and codebook constraints', 'summarize the W2VBertFactory class and how it constructs a W2VBertModel from a Wav2Vec2Model', 'convert a fairseq W2V-BERT state dict to the fairseq2 format using convert_w2vbert_state_dict', 'convert a W2V-BERT checkpoint state dict with a W2VBertConfig for fairseq2 model loading', 'convert a W2V-BERT state dict and strip the module prefix for DataParallel checkpoints', 'review the convert_w2vbert_state_dict key mapping regex patterns for fairseq to fairseq2 parameter name translation', 'test the convert_w2vbert_state_dict function with a sample fairseq W2V-BERT checkpoint and W2VBertConfig', 'build a W2VBertModel from a Wav2Vec2Model with BERT encoder layers for masked prediction', 'run the W2VBertModel forward pass on audio sequences to get loss and output', 'compute the combined BERT and Wav2Vec2 loss from a W2VBertOutput with configurable weights', 'extract target codebook indices from the Wav2Vec2 vector quantizer output for BERT targets', 'review the W2VBertOutput dataclass containing w2v2_output, bert_logits, and bert_targets tensors']
```

Usage

```
{'create_w2vbert_config': 'create a W2VBertConfig with default 600m architecture settings for a w2v-BERT model', 'validate_w2vbert_config': 'validate a W2VBertConfig to check layer_drop_p, encoder layers, and codebook constraints', 'register_w2vbert_configs': 'register the 300m and 600m w2v-BERT architecture presets into a DependencyContainer', 'customize_w2vbert_encoder': 'customize the nested Wav2Vec2EncoderConfig to change model_dim, attention heads, or ffn_inner_dim', 'configure_w2vbert_masking': 'configure temporal and spatial masking parameters like span_len and max_prob in the w2v2_config'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/w2vbert/factory.py

Prompts

```
['create a W2VBertConfig with default 600m architecture settings for a w2v-BERT model', 'validate a W2VBertConfig to check layer_drop_p, encoder layers, and codebook constraints', 'register the 300m and 600m w2v-BERT architecture presets into a DependencyContainer', 'customize the nested Wav2Vec2EncoderConfig to change model_dim, attention heads, or ffn_inner_dim', 'configure temporal and spatial masking parameters like span_len and max_prob in the w2v2_config', 'create a W2VBertModel from a W2VBertConfig using the create_w2vbert_model convenience function', 'create a W2VBertModel by instantiating W2VBertFactory with a config and calling create_model', 'create a Wav2Vec2Model from the W2VBertFactory using the create_wav2vec2_model method', 'review the W2VBertFactory create_model method to understand config validation for layer_drop_p and codebook constraints', 'summarize the W2VBertFactory class and how it constructs a W2VBertModel from a Wav2Vec2Model', 'convert a fairseq W2V-BERT state dict to the fairseq2 format using convert_w2vbert_state_dict', 'convert a W2V-BERT checkpoint state dict with a W2VBertConfig for fairseq2 model loading', 'convert a W2V-BERT state dict and strip the module prefix for DataParallel checkpoints', 'review the convert_w2vbert_state_dict key mapping regex patterns for fairseq to fairseq2 parameter name translation', 'test the convert_w2vbert_state_dict function with a sample fairseq W2V-BERT checkpoint and W2VBertConfig', 'build a W2VBertModel from a Wav2Vec2Model with BERT encoder layers for masked prediction', 'run the W2VBertModel forward pass on audio sequences to get loss and output', 'compute the combined BERT and Wav2Vec2 loss from a W2VBertOutput with configurable weights', 'extract target codebook indices from the Wav2Vec2 vector quantizer output for BERT targets', 'review the W2VBertOutput dataclass containing w2v2_output, bert_logits, and bert_targets tensors']
```

Usage

```
{'create_w2vbert_model': 'create a W2VBertModel from a W2VBertConfig using the create_w2vbert_model convenience function', 'create_w2vbert_model_with_factory': 'create a W2VBertModel by instantiating W2VBertFactory with a config and calling create_model', 'create_wav2vec2_model_from_factory': 'create a Wav2Vec2Model from the W2VBertFactory using the create_wav2vec2_model method', 'review_w2vbert_factory_validation': 'review the W2VBertFactory create_model method to understand config validation for layer_drop_p and codebook constraints', 'summarize_w2vbert_model_creation': 'summarize the W2VBertFactory class and how it constructs a W2VBertModel from a Wav2Vec2Model'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/w2vbert/interop.py

Prompts

```
['create a W2VBertConfig with default 600m architecture settings for a w2v-BERT model', 'validate a W2VBertConfig to check layer_drop_p, encoder layers, and codebook constraints', 'register the 300m and 600m w2v-BERT architecture presets into a DependencyContainer', 'customize the nested Wav2Vec2EncoderConfig to change model_dim, attention heads, or ffn_inner_dim', 'configure temporal and spatial masking parameters like span_len and max_prob in the w2v2_config', 'create a W2VBertModel from a W2VBertConfig using the create_w2vbert_model convenience function', 'create a W2VBertModel by instantiating W2VBertFactory with a config and calling create_model', 'create a Wav2Vec2Model from the W2VBertFactory using the create_wav2vec2_model method', 'review the W2VBertFactory create_model method to understand config validation for layer_drop_p and codebook constraints', 'summarize the W2VBertFactory class and how it constructs a W2VBertModel from a Wav2Vec2Model', 'convert a fairseq W2V-BERT state dict to the fairseq2 format using convert_w2vbert_state_dict', 'convert a W2V-BERT checkpoint state dict with a W2VBertConfig for fairseq2 model loading', 'convert a W2V-BERT state dict and strip the module prefix for DataParallel checkpoints', 'review the convert_w2vbert_state_dict key mapping regex patterns for fairseq to fairseq2 parameter name translation', 'test the convert_w2vbert_state_dict function with a sample fairseq W2V-BERT checkpoint and W2VBertConfig', 'build a W2VBertModel from a Wav2Vec2Model with BERT encoder layers for masked prediction', 'run the W2VBertModel forward pass on audio sequences to get loss and output', 'compute the combined BERT and Wav2Vec2 loss from a W2VBertOutput with configurable weights', 'extract target codebook indices from the Wav2Vec2 vector quantizer output for BERT targets', 'review the W2VBertOutput dataclass containing w2v2_output, bert_logits, and bert_targets tensors']
```

Usage

```
{'convert_w2vbert_state_dict_fairseq_to_fairseq2': 'convert a fairseq W2V-BERT state dict to the fairseq2 format using convert_w2vbert_state_dict', 'convert_w2vbert_state_dict_with_config': 'convert a W2V-BERT checkpoint state dict with a W2VBertConfig for fairseq2 model loading', 'convert_w2vbert_state_dict_strip_module_prefix': 'convert a W2V-BERT state dict and strip the module prefix for DataParallel checkpoints', 'review_convert_w2vbert_state_dict_key_map': 'review the convert_w2vbert_state_dict key mapping regex patterns for fairseq to fairseq2 parameter name translation', 'test_convert_w2vbert_state_dict': 'test the convert_w2vbert_state_dict function with a sample fairseq W2V-BERT checkpoint and W2VBertConfig'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/w2vbert/model.py

Prompts

```
['create a W2VBertConfig with default 600m architecture settings for a w2v-BERT model', 'validate a W2VBertConfig to check layer_drop_p, encoder layers, and codebook constraints', 'register the 300m and 600m w2v-BERT architecture presets into a DependencyContainer', 'customize the nested Wav2Vec2EncoderConfig to change model_dim, attention heads, or ffn_inner_dim', 'configure temporal and spatial masking parameters like span_len and max_prob in the w2v2_config', 'create a W2VBertModel from a W2VBertConfig using the create_w2vbert_model convenience function', 'create a W2VBertModel by instantiating W2VBertFactory with a config and calling create_model', 'create a Wav2Vec2Model from the W2VBertFactory using the create_wav2vec2_model method', 'review the W2VBertFactory create_model method to understand config validation for layer_drop_p and codebook constraints', 'summarize the W2VBertFactory class and how it constructs a W2VBertModel from a Wav2Vec2Model', 'convert a fairseq W2V-BERT state dict to the fairseq2 format using convert_w2vbert_state_dict', 'convert a W2V-BERT checkpoint state dict with a W2VBertConfig for fairseq2 model loading', 'convert a W2V-BERT state dict and strip the module prefix for DataParallel checkpoints', 'review the convert_w2vbert_state_dict key mapping regex patterns for fairseq to fairseq2 parameter name translation', 'test the convert_w2vbert_state_dict function with a sample fairseq W2V-BERT checkpoint and W2VBertConfig', 'build a W2VBertModel from a Wav2Vec2Model with BERT encoder layers for masked prediction', 'run the W2VBertModel forward pass on audio sequences to get loss and output', 'compute the combined BERT and Wav2Vec2 loss from a W2VBertOutput with configurable weights', 'extract target codebook indices from the Wav2Vec2 vector quantizer output for BERT targets', 'review the W2VBertOutput dataclass containing w2v2_output, bert_logits, and bert_targets tensors']
```

Usage

```
{'build_w2vbert_model': 'build a W2VBertModel from a Wav2Vec2Model with BERT encoder layers for masked prediction', 'run_w2vbert_forward': 'run the W2VBertModel forward pass on audio sequences to get loss and output', 'compute_w2vbert_loss': 'compute the combined BERT and Wav2Vec2 loss from a W2VBertOutput with configurable weights', 'extract_target_indices': 'extract target codebook indices from the Wav2Vec2 vector quantizer output for BERT targets', 'review_w2vbert_output': 'review the W2VBertOutput dataclass containing w2v2_output, bert_logits, and bert_targets tensors'}
```

