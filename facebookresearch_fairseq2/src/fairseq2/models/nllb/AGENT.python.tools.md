# Agent Python Tools

- repo: facebookresearch/fairseq2
- repo_uri: https://github.com/facebookresearch/fairseq2.git

## File: facebookresearch_fairseq2/src/fairseq2/models/nllb/config.py

Prompts

```
['create an NllbConfig dataclass instance with default model_dim, max_seq_len, and vocab_size values', 'customize an NllbConfig by setting model_dim, num_encoder_layers, and dropout_p parameters', 'register NLLB model architecture configs like dense_300m, dense_600m, dense_1b, and dense_3b into a DependencyContainer', 'review the NLLB dense architecture variants including dense_300m with 6 layers and dense_3b with model_dim 2048', 'summarize the NllbConfig default values for model_dim, ffn_inner_dim, num_encoder_layers, and dropout_p', 'create an NLLB transformer model from an NllbConfig using the create_nllb_model factory function', 'build a custom NLLB model by instantiating NllbFactory with an NllbConfig and calling create_model', 'create a scaled standard embedding layer for the NLLB model using NllbFactory create_embedding method', 'build a transformer encoder with configurable layers and self-attention using NllbFactory create_encoder method', 'create a causal transformer decoder with encoder-decoder cross-attention using NllbFactory create_decoder method', 'convert a fairseq NLLB model state dict to fairseq2 format using convert_nllb_state_dict', 'convert a HuggingFace NLLB model state dict to fairseq2 format by stripping the module prefix', 'review the convert_nllb_state_dict function to understand the fairseq to fairseq2 key mapping rules', 'refactor the NLLB state dict key mapping regex patterns to support a new model architecture', 'test the NLLB control symbol embedding reorder logic that remaps BOS PAD EOS UNK tokens', 'load an NLLB tokenizer from a SentencePiece model path with language config', 'create a source token encoder with language prefix tokens for NLLB translation', 'create a target token encoder with EOS prefix for NLLB translation output', 'create a token decoder to decode NLLB SentencePiece tokens back to text', 'create a raw SentencePiece encoder without language prefix tokens for NLLB']
```

Usage

```
{'create_nllb_config': 'create an NllbConfig dataclass instance with default model_dim, max_seq_len, and vocab_size values', 'customize_nllb_config': 'customize an NllbConfig by setting model_dim, num_encoder_layers, and dropout_p parameters', 'register_nllb_configs': 'register NLLB model architecture configs like dense_300m, dense_600m, dense_1b, and dense_3b into a DependencyContainer', 'review_nllb_architectures': 'review the NLLB dense architecture variants including dense_300m with 6 layers and dense_3b with model_dim 2048', 'summarize_nllb_config_defaults': 'summarize the NllbConfig default values for model_dim, ffn_inner_dim, num_encoder_layers, and dropout_p'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/nllb/factory.py

Prompts

```
['create an NllbConfig dataclass instance with default model_dim, max_seq_len, and vocab_size values', 'customize an NllbConfig by setting model_dim, num_encoder_layers, and dropout_p parameters', 'register NLLB model architecture configs like dense_300m, dense_600m, dense_1b, and dense_3b into a DependencyContainer', 'review the NLLB dense architecture variants including dense_300m with 6 layers and dense_3b with model_dim 2048', 'summarize the NllbConfig default values for model_dim, ffn_inner_dim, num_encoder_layers, and dropout_p', 'create an NLLB transformer model from an NllbConfig using the create_nllb_model factory function', 'build a custom NLLB model by instantiating NllbFactory with an NllbConfig and calling create_model', 'create a scaled standard embedding layer for the NLLB model using NllbFactory create_embedding method', 'build a transformer encoder with configurable layers and self-attention using NllbFactory create_encoder method', 'create a causal transformer decoder with encoder-decoder cross-attention using NllbFactory create_decoder method', 'convert a fairseq NLLB model state dict to fairseq2 format using convert_nllb_state_dict', 'convert a HuggingFace NLLB model state dict to fairseq2 format by stripping the module prefix', 'review the convert_nllb_state_dict function to understand the fairseq to fairseq2 key mapping rules', 'refactor the NLLB state dict key mapping regex patterns to support a new model architecture', 'test the NLLB control symbol embedding reorder logic that remaps BOS PAD EOS UNK tokens', 'load an NLLB tokenizer from a SentencePiece model path with language config', 'create a source token encoder with language prefix tokens for NLLB translation', 'create a target token encoder with EOS prefix for NLLB translation output', 'create a token decoder to decode NLLB SentencePiece tokens back to text', 'create a raw SentencePiece encoder without language prefix tokens for NLLB']
```

Usage

```
{'create_nllb_model': 'create an NLLB transformer model from an NllbConfig using the create_nllb_model factory function', 'create_nllb_model_with_factory': 'build a custom NLLB model by instantiating NllbFactory with an NllbConfig and calling create_model', 'create_nllb_embedding': 'create a scaled standard embedding layer for the NLLB model using NllbFactory create_embedding method', 'create_nllb_encoder': 'build a transformer encoder with configurable layers and self-attention using NllbFactory create_encoder method', 'create_nllb_decoder': 'create a causal transformer decoder with encoder-decoder cross-attention using NllbFactory create_decoder method'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/nllb/interop.py

Prompts

```
['create an NllbConfig dataclass instance with default model_dim, max_seq_len, and vocab_size values', 'customize an NllbConfig by setting model_dim, num_encoder_layers, and dropout_p parameters', 'register NLLB model architecture configs like dense_300m, dense_600m, dense_1b, and dense_3b into a DependencyContainer', 'review the NLLB dense architecture variants including dense_300m with 6 layers and dense_3b with model_dim 2048', 'summarize the NllbConfig default values for model_dim, ffn_inner_dim, num_encoder_layers, and dropout_p', 'create an NLLB transformer model from an NllbConfig using the create_nllb_model factory function', 'build a custom NLLB model by instantiating NllbFactory with an NllbConfig and calling create_model', 'create a scaled standard embedding layer for the NLLB model using NllbFactory create_embedding method', 'build a transformer encoder with configurable layers and self-attention using NllbFactory create_encoder method', 'create a causal transformer decoder with encoder-decoder cross-attention using NllbFactory create_decoder method', 'convert a fairseq NLLB model state dict to fairseq2 format using convert_nllb_state_dict', 'convert a HuggingFace NLLB model state dict to fairseq2 format by stripping the module prefix', 'review the convert_nllb_state_dict function to understand the fairseq to fairseq2 key mapping rules', 'refactor the NLLB state dict key mapping regex patterns to support a new model architecture', 'test the NLLB control symbol embedding reorder logic that remaps BOS PAD EOS UNK tokens', 'load an NLLB tokenizer from a SentencePiece model path with language config', 'create a source token encoder with language prefix tokens for NLLB translation', 'create a target token encoder with EOS prefix for NLLB translation output', 'create a token decoder to decode NLLB SentencePiece tokens back to text', 'create a raw SentencePiece encoder without language prefix tokens for NLLB']
```

Usage

```
{'convert_nllb_state_dict_fairseq': 'convert a fairseq NLLB model state dict to fairseq2 format using convert_nllb_state_dict', 'convert_nllb_state_dict_hf': 'convert a HuggingFace NLLB model state dict to fairseq2 format by stripping the module prefix', 'review_convert_nllb_state_dict': 'review the convert_nllb_state_dict function to understand the fairseq to fairseq2 key mapping rules', 'refactor_nllb_key_map': 'refactor the NLLB state dict key mapping regex patterns to support a new model architecture', 'test_nllb_embedding_reorder': 'test the NLLB control symbol embedding reorder logic that remaps BOS PAD EOS UNK tokens'}
```

## File: facebookresearch_fairseq2/src/fairseq2/models/nllb/tokenizer.py

Prompts

```
['create an NllbConfig dataclass instance with default model_dim, max_seq_len, and vocab_size values', 'customize an NllbConfig by setting model_dim, num_encoder_layers, and dropout_p parameters', 'register NLLB model architecture configs like dense_300m, dense_600m, dense_1b, and dense_3b into a DependencyContainer', 'review the NLLB dense architecture variants including dense_300m with 6 layers and dense_3b with model_dim 2048', 'summarize the NllbConfig default values for model_dim, ffn_inner_dim, num_encoder_layers, and dropout_p', 'create an NLLB transformer model from an NllbConfig using the create_nllb_model factory function', 'build a custom NLLB model by instantiating NllbFactory with an NllbConfig and calling create_model', 'create a scaled standard embedding layer for the NLLB model using NllbFactory create_embedding method', 'build a transformer encoder with configurable layers and self-attention using NllbFactory create_encoder method', 'create a causal transformer decoder with encoder-decoder cross-attention using NllbFactory create_decoder method', 'convert a fairseq NLLB model state dict to fairseq2 format using convert_nllb_state_dict', 'convert a HuggingFace NLLB model state dict to fairseq2 format by stripping the module prefix', 'review the convert_nllb_state_dict function to understand the fairseq to fairseq2 key mapping rules', 'refactor the NLLB state dict key mapping regex patterns to support a new model architecture', 'test the NLLB control symbol embedding reorder logic that remaps BOS PAD EOS UNK tokens', 'load an NLLB tokenizer from a SentencePiece model path with language config', 'create a source token encoder with language prefix tokens for NLLB translation', 'create a target token encoder with EOS prefix for NLLB translation output', 'create a token decoder to decode NLLB SentencePiece tokens back to text', 'create a raw SentencePiece encoder without language prefix tokens for NLLB']
```

Usage

```
{'load_nllb_tokenizer': 'load an NLLB tokenizer from a SentencePiece model path with language config', 'create_encoder_source': 'create a source token encoder with language prefix tokens for NLLB translation', 'create_encoder_target': 'create a target token encoder with EOS prefix for NLLB translation output', 'create_decoder': 'create a token decoder to decode NLLB SentencePiece tokens back to text', 'create_raw_encoder': 'create a raw SentencePiece encoder without language prefix tokens for NLLB'}
```

