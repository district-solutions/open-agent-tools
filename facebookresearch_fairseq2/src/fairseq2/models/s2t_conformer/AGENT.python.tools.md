# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/models/s2t_conformer/config.py

Prompts

```
['create an S2TConformerConfig dataclass instance with default model dimension of 256', 'customize S2TConformerConfig by setting model_dim, num_encoder_layers, and dropout_p parameters', 'configure S2TConformerConfig to use relative positional encodings for source sequences', 'register the medium S2T Conformer architecture config with a DependencyContainer', 'summarize the S2TConformerConfig dataclass fields including model_dim, encoder layers, and attention heads', 'create a speech-to-text conformer model from an S2TConformerConfig using the factory function', 'build a conformer encoder with stacked ConformerBlock layers and lazy relative positional encoding', 'create a multihead self-attention module with optional relative positional SDPA for the encoder', 'build a standard transformer decoder layer with self-attention, cross-attention, and feed-forward sublayers', 'create a linear projection layer mapping model dimensions to target vocabulary size', 'convert a fairseq S2T Conformer state dict to fairseq2 format using the key mapping', 'convert an S2T Conformer state dict by stripping the module prefix if present', 'convert an S2T Conformer checkpoint state dict with an S2TConformerConfig for model loading', 'review the convert_s2t_conformer_state_dict function to understand the fairseq to fairseq2 key mapping', 'refactor the convert_s2t_conformer_state_dict function to add support for additional checkpoint formats']
```

Usage

```
{'create_s2t_conformer_config': 'create an S2TConformerConfig dataclass instance with default model dimension of 256', 'customize_s2t_conformer_config': 'customize S2TConformerConfig by setting model_dim, num_encoder_layers, and dropout_p parameters', 'configure_relative_positional_encoding': 'configure S2TConformerConfig to use relative positional encodings for source sequences', 'register_s2t_conformer_configs': 'register the medium S2T Conformer architecture config with a DependencyContainer', 'summarize_s2t_conformer_config': 'summarize the S2TConformerConfig dataclass fields including model_dim, encoder layers, and attention heads'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/s2t_conformer/factory.py

Prompts

```
['create an S2TConformerConfig dataclass instance with default model dimension of 256', 'customize S2TConformerConfig by setting model_dim, num_encoder_layers, and dropout_p parameters', 'configure S2TConformerConfig to use relative positional encodings for source sequences', 'register the medium S2T Conformer architecture config with a DependencyContainer', 'summarize the S2TConformerConfig dataclass fields including model_dim, encoder layers, and attention heads', 'create a speech-to-text conformer model from an S2TConformerConfig using the factory function', 'build a conformer encoder with stacked ConformerBlock layers and lazy relative positional encoding', 'create a multihead self-attention module with optional relative positional SDPA for the encoder', 'build a standard transformer decoder layer with self-attention, cross-attention, and feed-forward sublayers', 'create a linear projection layer mapping model dimensions to target vocabulary size', 'convert a fairseq S2T Conformer state dict to fairseq2 format using the key mapping', 'convert an S2T Conformer state dict by stripping the module prefix if present', 'convert an S2T Conformer checkpoint state dict with an S2TConformerConfig for model loading', 'review the convert_s2t_conformer_state_dict function to understand the fairseq to fairseq2 key mapping', 'refactor the convert_s2t_conformer_state_dict function to add support for additional checkpoint formats']
```

Usage

```
{'create_s2t_conformer_model': 'create a speech-to-text conformer model from an S2TConformerConfig using the factory function', 'create_conformer_encoder': 'build a conformer encoder with stacked ConformerBlock layers and lazy relative positional encoding', 'create_encoder_self_attention': 'create a multihead self-attention module with optional relative positional SDPA for the encoder', 'create_decoder_layer': 'build a standard transformer decoder layer with self-attention, cross-attention, and feed-forward sublayers', 'create_final_projection': 'create a linear projection layer mapping model dimensions to target vocabulary size'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/s2t_conformer/interop.py

Prompts

```
['create an S2TConformerConfig dataclass instance with default model dimension of 256', 'customize S2TConformerConfig by setting model_dim, num_encoder_layers, and dropout_p parameters', 'configure S2TConformerConfig to use relative positional encodings for source sequences', 'register the medium S2T Conformer architecture config with a DependencyContainer', 'summarize the S2TConformerConfig dataclass fields including model_dim, encoder layers, and attention heads', 'create a speech-to-text conformer model from an S2TConformerConfig using the factory function', 'build a conformer encoder with stacked ConformerBlock layers and lazy relative positional encoding', 'create a multihead self-attention module with optional relative positional SDPA for the encoder', 'build a standard transformer decoder layer with self-attention, cross-attention, and feed-forward sublayers', 'create a linear projection layer mapping model dimensions to target vocabulary size', 'convert a fairseq S2T Conformer state dict to fairseq2 format using the key mapping', 'convert an S2T Conformer state dict by stripping the module prefix if present', 'convert an S2T Conformer checkpoint state dict with an S2TConformerConfig for model loading', 'review the convert_s2t_conformer_state_dict function to understand the fairseq to fairseq2 key mapping', 'refactor the convert_s2t_conformer_state_dict function to add support for additional checkpoint formats']
```

Usage

```
{'convert_s2t_conformer_state_dict_fairseq': 'convert a fairseq S2T Conformer state dict to fairseq2 format using the key mapping', 'convert_s2t_conformer_state_dict_module': 'convert an S2T Conformer state dict by stripping the module prefix if present', 'convert_s2t_conformer_state_dict_with_config': 'convert an S2T Conformer checkpoint state dict with an S2TConformerConfig for model loading', 'review_convert_s2t_conformer_state_dict': 'review the convert_s2t_conformer_state_dict function to understand the fairseq to fairseq2 key mapping', 'refactor_convert_s2t_conformer_state_dict': 'refactor the convert_s2t_conformer_state_dict function to add support for additional checkpoint formats'}
```

