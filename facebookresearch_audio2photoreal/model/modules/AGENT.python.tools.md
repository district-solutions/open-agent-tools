# Agent Python Tools

- repo: facebookresearch/audio2photoreal
- repo_uri: https://github.com/facebookresearch/audio2photoreal

## File: facebookresearch_audio2photoreal/model/modules/audio_encoder.py

Prompts

```
['build a python module to encode audio using Wav2VecEncoder that extracts wav2vec features from raw audio tensors', 'create a Wav2VecDownsampler module to downsample wav2vec features from 100Hz to 30Hz using conv layers', 'build an AudioTcn module that combines mel spectrogram and wav2vec features with a temporal convolutional network', 'test the weights_init function to verify Xavier uniform initialization on Conv1d layers', 'review the AudioTcn forward pass that processes audio through mel spectrogram and wav2vec feature extraction', 'build a RotaryEmbedding module for language modalities with a given dimension and theta base frequency', 'build a RotaryEmbedding module for pixel modalities with a specified dimension and max frequency', 'test the apply_rotary_emb function by applying rotary embeddings to a tensor with given frequencies', 'test the apply_learned_rotations function by applying learned rotations to a tensor with optional frequency ranges', 'test the rotate_half function by splitting and rotating pairs of values in a tensor', 'build a DiffusionTransformer model with FiLM conditioning for audio to photoreal diffusion tasks', 'build a RegressionTransformer encoder-decoder model with optional causal masking for sequence regression', 'create a causal attention mask tensor for transformer self-attention or cross-attention layers', 'create a FiLMTransformerDecoderLayer with feature-wise linear modulation conditioned on timestep embeddings', 'create a TransformerEncoderLayerRotary with rotary positional embeddings for self-attention']
```

Usage

```
{'build_audio_encoder_with_wav2vec': 'build a python module to encode audio using Wav2VecEncoder that extracts wav2vec features from raw audio tensors', 'create_wav2vec_downsampler': 'create a Wav2VecDownsampler module to downsample wav2vec features from 100Hz to 30Hz using conv layers', 'build_audio_tcn_encoder': 'build an AudioTcn module that combines mel spectrogram and wav2vec features with a temporal convolutional network', 'test_weights_init': 'test the weights_init function to verify Xavier uniform initialization on Conv1d layers', 'review_audiotcn_forward': 'review the AudioTcn forward pass that processes audio through mel spectrogram and wav2vec feature extraction'}
```

## File: facebookresearch_audio2photoreal/model/modules/rotary_embedding_torch.py

Prompts

```
['build a python module to encode audio using Wav2VecEncoder that extracts wav2vec features from raw audio tensors', 'create a Wav2VecDownsampler module to downsample wav2vec features from 100Hz to 30Hz using conv layers', 'build an AudioTcn module that combines mel spectrogram and wav2vec features with a temporal convolutional network', 'test the weights_init function to verify Xavier uniform initialization on Conv1d layers', 'review the AudioTcn forward pass that processes audio through mel spectrogram and wav2vec feature extraction', 'build a RotaryEmbedding module for language modalities with a given dimension and theta base frequency', 'build a RotaryEmbedding module for pixel modalities with a specified dimension and max frequency', 'test the apply_rotary_emb function by applying rotary embeddings to a tensor with given frequencies', 'test the apply_learned_rotations function by applying learned rotations to a tensor with optional frequency ranges', 'test the rotate_half function by splitting and rotating pairs of values in a tensor', 'build a DiffusionTransformer model with FiLM conditioning for audio to photoreal diffusion tasks', 'build a RegressionTransformer encoder-decoder model with optional causal masking for sequence regression', 'create a causal attention mask tensor for transformer self-attention or cross-attention layers', 'create a FiLMTransformerDecoderLayer with feature-wise linear modulation conditioned on timestep embeddings', 'create a TransformerEncoderLayerRotary with rotary positional embeddings for self-attention']
```

Usage

```
{'build_rotary_embedding_lang': 'build a RotaryEmbedding module for language modalities with a given dimension and theta base frequency', 'build_rotary_embedding_pixel': 'build a RotaryEmbedding module for pixel modalities with a specified dimension and max frequency', 'test_apply_rotary_emb': 'test the apply_rotary_emb function by applying rotary embeddings to a tensor with given frequencies', 'test_apply_learned_rotations': 'test the apply_learned_rotations function by applying learned rotations to a tensor with optional frequency ranges', 'test_rotate_half': 'test the rotate_half function by splitting and rotating pairs of values in a tensor'}
```

## File: facebookresearch_audio2photoreal/model/modules/transformer_modules.py

Prompts

```
['build a python module to encode audio using Wav2VecEncoder that extracts wav2vec features from raw audio tensors', 'create a Wav2VecDownsampler module to downsample wav2vec features from 100Hz to 30Hz using conv layers', 'build an AudioTcn module that combines mel spectrogram and wav2vec features with a temporal convolutional network', 'test the weights_init function to verify Xavier uniform initialization on Conv1d layers', 'review the AudioTcn forward pass that processes audio through mel spectrogram and wav2vec feature extraction', 'build a RotaryEmbedding module for language modalities with a given dimension and theta base frequency', 'build a RotaryEmbedding module for pixel modalities with a specified dimension and max frequency', 'test the apply_rotary_emb function by applying rotary embeddings to a tensor with given frequencies', 'test the apply_learned_rotations function by applying learned rotations to a tensor with optional frequency ranges', 'test the rotate_half function by splitting and rotating pairs of values in a tensor', 'build a DiffusionTransformer model with FiLM conditioning for audio to photoreal diffusion tasks', 'build a RegressionTransformer encoder-decoder model with optional causal masking for sequence regression', 'create a causal attention mask tensor for transformer self-attention or cross-attention layers', 'create a FiLMTransformerDecoderLayer with feature-wise linear modulation conditioned on timestep embeddings', 'create a TransformerEncoderLayerRotary with rotary positional embeddings for self-attention']
```

Usage

```
{'build_diffusion_transformer': 'build a DiffusionTransformer model with FiLM conditioning for audio to photoreal diffusion tasks', 'build_regression_transformer': 'build a RegressionTransformer encoder-decoder model with optional causal masking for sequence regression', 'create_causal_mask': 'create a causal attention mask tensor for transformer self-attention or cross-attention layers', 'create_film_decoder_layer': 'create a FiLMTransformerDecoderLayer with feature-wise linear modulation conditioned on timestep embeddings', 'create_rotary_encoder_layer': 'create a TransformerEncoderLayerRotary with rotary positional embeddings for self-attention'}
```

