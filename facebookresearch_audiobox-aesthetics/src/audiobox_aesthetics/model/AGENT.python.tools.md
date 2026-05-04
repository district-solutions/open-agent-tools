# Agent Python Tools

- repo: facebookresearch/audiobox-aesthetics
- repo_uri: https://github.com/facebookresearch/audiobox-aesthetics

## File: facebookresearch_audiobox-aesthetics/src/audiobox_aesthetics/model/aes.py

Prompts

```
['build an AesMultiOutput model with WavLM encoder and MLP projection heads for audio aesthetics prediction', 'run a forward pass on the AesMultiOutput model with a batch dict containing wav and mask tensors', 'create a Normalize dataclass with mean and std to transform and inverse transform audio features', 'review the AesMultiOutput forward method and its weighted layer sum mechanism for multi-axis audio prediction', 'test the AesMultiOutput model with freeze_encoder set to true to prevent WavLM weight updates during training', 'create an MLP block with 2 layers, gelu activation, and no layer norm or dropout', 'create an MLP block with 3 layers, gelu activation, layer norm, and 0.1 dropout', 'create an MLP block that maps 512 input dimensions to 10 output dimensions with 4 layers', 'create an MLP block with layer norm enabled but zero dropout for stable training', 'create a single layer MLP block that projects input_dim directly to output_dim', 'build a WavLM model from a WavLMConfig to extract audio features from raw waveforms', 'create a WavLMConfig with custom encoder layers, embedding dim, and dropout settings', 'run extract_features on a WavLM model to get transformer representations from audio input', 'build a ConvFeatureExtractionModel with custom conv layers to extract low-level audio features', 'create a TransformerEncoder with configurable layers, attention heads, and relative position embeddings']
```

Usage

```
{'build_aes_multi_output_model': 'build an AesMultiOutput model with WavLM encoder and MLP projection heads for audio aesthetics prediction', 'run_aes_forward_pass': 'run a forward pass on the AesMultiOutput model with a batch dict containing wav and mask tensors', 'create_normalize_transform': 'create a Normalize dataclass with mean and std to transform and inverse transform audio features', 'review_aes_weighted_layer_sum': 'review the AesMultiOutput forward method and its weighted layer sum mechanism for multi-axis audio prediction', 'test_aes_freeze_encoder': 'test the AesMultiOutput model with freeze_encoder set to true to prevent WavLM weight updates during training'}
```

## File: facebookresearch_audiobox-aesthetics/src/audiobox_aesthetics/model/utils.py

Prompts

```
['build an AesMultiOutput model with WavLM encoder and MLP projection heads for audio aesthetics prediction', 'run a forward pass on the AesMultiOutput model with a batch dict containing wav and mask tensors', 'create a Normalize dataclass with mean and std to transform and inverse transform audio features', 'review the AesMultiOutput forward method and its weighted layer sum mechanism for multi-axis audio prediction', 'test the AesMultiOutput model with freeze_encoder set to true to prevent WavLM weight updates during training', 'create an MLP block with 2 layers, gelu activation, and no layer norm or dropout', 'create an MLP block with 3 layers, gelu activation, layer norm, and 0.1 dropout', 'create an MLP block that maps 512 input dimensions to 10 output dimensions with 4 layers', 'create an MLP block with layer norm enabled but zero dropout for stable training', 'create a single layer MLP block that projects input_dim directly to output_dim', 'build a WavLM model from a WavLMConfig to extract audio features from raw waveforms', 'create a WavLMConfig with custom encoder layers, embedding dim, and dropout settings', 'run extract_features on a WavLM model to get transformer representations from audio input', 'build a ConvFeatureExtractionModel with custom conv layers to extract low-level audio features', 'create a TransformerEncoder with configurable layers, attention heads, and relative position embeddings']
```

Usage

```
{'create_mlp_block_basic': 'create an MLP block with 2 layers, gelu activation, and no layer norm or dropout', 'create_mlp_block_with_norm': 'create an MLP block with 3 layers, gelu activation, layer norm, and 0.1 dropout', 'create_mlp_block_custom_dims': 'create an MLP block that maps 512 input dimensions to 10 output dimensions with 4 layers', 'create_mlp_block_no_dropout': 'create an MLP block with layer norm enabled but zero dropout for stable training', 'create_mlp_block_single_layer': 'create a single layer MLP block that projects input_dim directly to output_dim'}
```

## File: facebookresearch_audiobox-aesthetics/src/audiobox_aesthetics/model/wavlm.py

Prompts

```
['build an AesMultiOutput model with WavLM encoder and MLP projection heads for audio aesthetics prediction', 'run a forward pass on the AesMultiOutput model with a batch dict containing wav and mask tensors', 'create a Normalize dataclass with mean and std to transform and inverse transform audio features', 'review the AesMultiOutput forward method and its weighted layer sum mechanism for multi-axis audio prediction', 'test the AesMultiOutput model with freeze_encoder set to true to prevent WavLM weight updates during training', 'create an MLP block with 2 layers, gelu activation, and no layer norm or dropout', 'create an MLP block with 3 layers, gelu activation, layer norm, and 0.1 dropout', 'create an MLP block that maps 512 input dimensions to 10 output dimensions with 4 layers', 'create an MLP block with layer norm enabled but zero dropout for stable training', 'create a single layer MLP block that projects input_dim directly to output_dim', 'build a WavLM model from a WavLMConfig to extract audio features from raw waveforms', 'create a WavLMConfig with custom encoder layers, embedding dim, and dropout settings', 'run extract_features on a WavLM model to get transformer representations from audio input', 'build a ConvFeatureExtractionModel with custom conv layers to extract low-level audio features', 'create a TransformerEncoder with configurable layers, attention heads, and relative position embeddings']
```

Usage

```
{'build_wavlm_model': 'build a WavLM model from a WavLMConfig to extract audio features from raw waveforms', 'create_wavlm_config': 'create a WavLMConfig with custom encoder layers, embedding dim, and dropout settings', 'run_extract_features': 'run extract_features on a WavLM model to get transformer representations from audio input', 'build_conv_feature_extractor': 'build a ConvFeatureExtractionModel with custom conv layers to extract low-level audio features', 'create_transformer_encoder': 'create a TransformerEncoder with configurable layers, attention heads, and relative position embeddings'}
```

