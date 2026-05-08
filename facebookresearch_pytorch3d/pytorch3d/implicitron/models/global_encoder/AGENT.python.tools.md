# Agent Python Tools

- repo: facebookresearch/pytorch3d
- repo_uri: https://github.com/facebookresearch/pytorch3d.git

## File: facebookresearch_pytorch3d/pytorch3d/implicitron/models/global_encoder/autodecoder.py

Prompts

```
['create an Autodecoder instance that maps string or integer keys to optimizable embedding vectors', 'forward a batch of string keys or long tensor indices through the Autodecoder to get embedding codes', 'calculate the mean squared norm of the Autodecoder embedding weights for regularization', 'load an Autodecoder state dict that includes the key map for string-to-id mappings', 'build a key map dictionary that assigns incremental integer IDs to string keys', 'create a HarmonicTimeEncoder to generate harmonic embeddings of frame timestamps with configurable n_harmonic_functions', 'create a SequenceAutodecoder to encode frame sequence identifiers using an autodecoder module', 'build a subclass of GlobalEncoderBase to implement custom global frame-specific encoding logic', 'test the HarmonicTimeEncoder forward pass with a frame_timestamp tensor and verify output shape', 'review the SequenceAutodecoder calculate_squared_encoding_norm method to understand autodecoder norm loss reporting']
```

Usage

```
{'create_autodecoder_embeddings': 'create an Autodecoder instance that maps string or integer keys to optimizable embedding vectors', 'forward_autodecoder_codes': 'forward a batch of string keys or long tensor indices through the Autodecoder to get embedding codes', 'calculate_squared_encoding_norm': 'calculate the mean squared norm of the Autodecoder embedding weights for regularization', 'load_autodecoder_state': 'load an Autodecoder state dict that includes the key map for string-to-id mappings', 'build_key_map': 'build a key map dictionary that assigns incremental integer IDs to string keys'}
```

## File: facebookresearch_pytorch3d/pytorch3d/implicitron/models/global_encoder/global_encoder.py

Prompts

```
['create an Autodecoder instance that maps string or integer keys to optimizable embedding vectors', 'forward a batch of string keys or long tensor indices through the Autodecoder to get embedding codes', 'calculate the mean squared norm of the Autodecoder embedding weights for regularization', 'load an Autodecoder state dict that includes the key map for string-to-id mappings', 'build a key map dictionary that assigns incremental integer IDs to string keys', 'create a HarmonicTimeEncoder to generate harmonic embeddings of frame timestamps with configurable n_harmonic_functions', 'create a SequenceAutodecoder to encode frame sequence identifiers using an autodecoder module', 'build a subclass of GlobalEncoderBase to implement custom global frame-specific encoding logic', 'test the HarmonicTimeEncoder forward pass with a frame_timestamp tensor and verify output shape', 'review the SequenceAutodecoder calculate_squared_encoding_norm method to understand autodecoder norm loss reporting']
```

Usage

```
{'create_harmonic_time_encoder': 'create a HarmonicTimeEncoder to generate harmonic embeddings of frame timestamps with configurable n_harmonic_functions', 'create_sequence_autodecoder': 'create a SequenceAutodecoder to encode frame sequence identifiers using an autodecoder module', 'build_global_encoder_subclass': 'build a subclass of GlobalEncoderBase to implement custom global frame-specific encoding logic', 'test_harmonic_time_encoder_forward': 'test the HarmonicTimeEncoder forward pass with a frame_timestamp tensor and verify output shape', 'review_sequence_autodecoder_norm': 'review the SequenceAutodecoder calculate_squared_encoding_norm method to understand autodecoder norm loss reporting'}
```

