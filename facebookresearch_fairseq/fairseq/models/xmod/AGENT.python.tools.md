# Agent Python Tools

- repo: facebookresearch/fairseq
- repo_uri: https://github.com/facebookresearch/fairseq

## File: facebookresearch_fairseq/fairseq/models/xmod/hub_interface.py

Prompts

```
['extract features from tokenized text using the XMOD model with language ID support', 'extract all hidden layer states from the XMOD model for multi-layer feature analysis', 'predict classification output using a named head on tokenized input with the XMOD model', 'predict raw logits from a classification head without applying log softmax normalization', 'review the XMODHubInterface class that extends RobertaHubInterface for multilingual feature extraction and prediction', 'build an XMOD multilingual model instance with XMODEncoder from args and task dictionary', 'load a pretrained XMOD model from a hub URL or local checkpoint path', 'run the XMOD model forward pass with source tokens and optional language ID', 'extract features from the XMODEncoder using extract_features with source tokens', 'configure an XMOD model architecture like xmod_base or xmod_large_prenorm with language list', 'build an Adapter module with configurable reduction factor and quantization noise for language-specific transformations', 'create an XMODTransformerEncoderLayerBase with language adapter modules for multilingual transformer encoding', 'run the lang_adapter method to pass input through language-specific adapter modules by language ID', 'test the XMODTransformerEncoderLayerBase forward pass with attention masks and language IDs', 'review the Adapter class quantization noise configuration and bottleneck reduction factor settings']
```

Usage

```
{'extract_features_tokens': 'extract features from tokenized text using the XMOD model with language ID support', 'extract_features_all_hiddens': 'extract all hidden layer states from the XMOD model for multi-layer feature analysis', 'predict_classification_head': 'predict classification output using a named head on tokenized input with the XMOD model', 'predict_with_logits': 'predict raw logits from a classification head without applying log softmax normalization', 'review_XMODHubInterface': 'review the XMODHubInterface class that extends RobertaHubInterface for multilingual feature extraction and prediction'}
```

## File: facebookresearch_fairseq/fairseq/models/xmod/model.py

Prompts

```
['extract features from tokenized text using the XMOD model with language ID support', 'extract all hidden layer states from the XMOD model for multi-layer feature analysis', 'predict classification output using a named head on tokenized input with the XMOD model', 'predict raw logits from a classification head without applying log softmax normalization', 'review the XMODHubInterface class that extends RobertaHubInterface for multilingual feature extraction and prediction', 'build an XMOD multilingual model instance with XMODEncoder from args and task dictionary', 'load a pretrained XMOD model from a hub URL or local checkpoint path', 'run the XMOD model forward pass with source tokens and optional language ID', 'extract features from the XMODEncoder using extract_features with source tokens', 'configure an XMOD model architecture like xmod_base or xmod_large_prenorm with language list', 'build an Adapter module with configurable reduction factor and quantization noise for language-specific transformations', 'create an XMODTransformerEncoderLayerBase with language adapter modules for multilingual transformer encoding', 'run the lang_adapter method to pass input through language-specific adapter modules by language ID', 'test the XMODTransformerEncoderLayerBase forward pass with attention masks and language IDs', 'review the Adapter class quantization noise configuration and bottleneck reduction factor settings']
```

Usage

```
{'build_xmod_model': 'build an XMOD multilingual model instance with XMODEncoder from args and task dictionary', 'load_xmod_pretrained': 'load a pretrained XMOD model from a hub URL or local checkpoint path', 'run_xmod_forward': 'run the XMOD model forward pass with source tokens and optional language ID', 'extract_xmod_features': 'extract features from the XMODEncoder using extract_features with source tokens', 'configure_xmod_architecture': 'configure an XMOD model architecture like xmod_base or xmod_large_prenorm with language list'}
```

## File: facebookresearch_fairseq/fairseq/models/xmod/transformer_layer_xmod.py

Prompts

```
['extract features from tokenized text using the XMOD model with language ID support', 'extract all hidden layer states from the XMOD model for multi-layer feature analysis', 'predict classification output using a named head on tokenized input with the XMOD model', 'predict raw logits from a classification head without applying log softmax normalization', 'review the XMODHubInterface class that extends RobertaHubInterface for multilingual feature extraction and prediction', 'build an XMOD multilingual model instance with XMODEncoder from args and task dictionary', 'load a pretrained XMOD model from a hub URL or local checkpoint path', 'run the XMOD model forward pass with source tokens and optional language ID', 'extract features from the XMODEncoder using extract_features with source tokens', 'configure an XMOD model architecture like xmod_base or xmod_large_prenorm with language list', 'build an Adapter module with configurable reduction factor and quantization noise for language-specific transformations', 'create an XMODTransformerEncoderLayerBase with language adapter modules for multilingual transformer encoding', 'run the lang_adapter method to pass input through language-specific adapter modules by language ID', 'test the XMODTransformerEncoderLayerBase forward pass with attention masks and language IDs', 'review the Adapter class quantization noise configuration and bottleneck reduction factor settings']
```

Usage

```
{'build_adapter_module': 'build an Adapter module with configurable reduction factor and quantization noise for language-specific transformations', 'create_xmod_encoder_layer': 'create an XMODTransformerEncoderLayerBase with language adapter modules for multilingual transformer encoding', 'run_lang_adapter_forward': 'run the lang_adapter method to pass input through language-specific adapter modules by language ID', 'test_xmod_forward_pass': 'test the XMODTransformerEncoderLayerBase forward pass with attention masks and language IDs', 'review_adapter_quant_noise': 'review the Adapter class quantization noise configuration and bottleneck reduction factor settings'}
```

