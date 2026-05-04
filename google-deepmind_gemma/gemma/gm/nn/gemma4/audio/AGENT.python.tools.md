# Agent Python Tools

- repo: google-deepmind/gemma
- repo_uri: https://github.com/google-deepmind/gemma

## File: google-deepmind_gemma/gemma/gm/nn/gemma4/audio/_model.py

Prompts

```
['build a python module that uses AudioTokenizer to encode audio waveforms into embeddings', 'create a function that infers a boolean validity mask after temporal compression using infer_mask', 'compute the local causal validity mask for chunked attention using _compute_causal_valid_mask', 'convert int16 int32 uint8 or float audio data to float32 using to_float32', 'review the AudioTokenizer __call__ method that computes audio embeddings from input waveforms', 'test the AudioTokenizer model initialization and output shape with random audio input', 'create a ConformerConfig with custom num_layers, model_dims, and attention heads', 'run the AudioTokenizer forward pass on batched audio waveforms to get embeddings', 'review the SubSamplingBlock module that reduces time dimension by factor of 4', 'summarize the GemaxMelFilterbank module that computes Mel-filterbank spectrograms from audio', 'build a module that computes Mel-filterbank spectrograms from raw audio waveforms using GemaxMelFilterbank', 'build a Conformer audio encoder stack with configurable layers, attention heads, and model dimensions', 'build a subsampling block that reduces audio sequence length via strided convolutions and LayerNorm', 'build a local dot-product attention module with Transformer-XL relative position embeddings and causal masking', 'build a single Conformer layer combining FFN, self-attention, lightweight convolution, and residual connections']
```

Usage

```
{'build_audio_tokenizer': 'build a python module that uses AudioTokenizer to encode audio waveforms into embeddings', 'create_infer_mask': 'create a function that infers a boolean validity mask after temporal compression using infer_mask', 'compute_causal_valid_mask': 'compute the local causal validity mask for chunked attention using _compute_causal_valid_mask', 'convert_audio_to_float32': 'convert int16 int32 uint8 or float audio data to float32 using to_float32', 'review_audiotokenizer_call': 'review the AudioTokenizer __call__ method that computes audio embeddings from input waveforms'}
```

## File: google-deepmind_gemma/gemma/gm/nn/gemma4/audio/_model_test.py

Prompts

```
['build a python module that uses AudioTokenizer to encode audio waveforms into embeddings', 'create a function that infers a boolean validity mask after temporal compression using infer_mask', 'compute the local causal validity mask for chunked attention using _compute_causal_valid_mask', 'convert int16 int32 uint8 or float audio data to float32 using to_float32', 'review the AudioTokenizer __call__ method that computes audio embeddings from input waveforms', 'test the AudioTokenizer model initialization and output shape with random audio input', 'create a ConformerConfig with custom num_layers, model_dims, and attention heads', 'run the AudioTokenizer forward pass on batched audio waveforms to get embeddings', 'review the SubSamplingBlock module that reduces time dimension by factor of 4', 'summarize the GemaxMelFilterbank module that computes Mel-filterbank spectrograms from audio', 'build a module that computes Mel-filterbank spectrograms from raw audio waveforms using GemaxMelFilterbank', 'build a Conformer audio encoder stack with configurable layers, attention heads, and model dimensions', 'build a subsampling block that reduces audio sequence length via strided convolutions and LayerNorm', 'build a local dot-product attention module with Transformer-XL relative position embeddings and causal masking', 'build a single Conformer layer combining FFN, self-attention, lightweight convolution, and residual connections']
```

Usage

```
{'test_audio_tokenizer_initialization': 'test the AudioTokenizer model initialization and output shape with random audio input', 'create_conformer_config': 'create a ConformerConfig with custom num_layers, model_dims, and attention heads', 'run_audio_tokenizer_forward': 'run the AudioTokenizer forward pass on batched audio waveforms to get embeddings', 'review_subsampling_block': 'review the SubSamplingBlock module that reduces time dimension by factor of 4', 'summarize_mel_filterbank': 'summarize the GemaxMelFilterbank module that computes Mel-filterbank spectrograms from audio'}
```

## File: google-deepmind_gemma/gemma/gm/nn/gemma4/audio/_modules.py

Prompts

```
['build a python module that uses AudioTokenizer to encode audio waveforms into embeddings', 'create a function that infers a boolean validity mask after temporal compression using infer_mask', 'compute the local causal validity mask for chunked attention using _compute_causal_valid_mask', 'convert int16 int32 uint8 or float audio data to float32 using to_float32', 'review the AudioTokenizer __call__ method that computes audio embeddings from input waveforms', 'test the AudioTokenizer model initialization and output shape with random audio input', 'create a ConformerConfig with custom num_layers, model_dims, and attention heads', 'run the AudioTokenizer forward pass on batched audio waveforms to get embeddings', 'review the SubSamplingBlock module that reduces time dimension by factor of 4', 'summarize the GemaxMelFilterbank module that computes Mel-filterbank spectrograms from audio', 'build a module that computes Mel-filterbank spectrograms from raw audio waveforms using GemaxMelFilterbank', 'build a Conformer audio encoder stack with configurable layers, attention heads, and model dimensions', 'build a subsampling block that reduces audio sequence length via strided convolutions and LayerNorm', 'build a local dot-product attention module with Transformer-XL relative position embeddings and causal masking', 'build a single Conformer layer combining FFN, self-attention, lightweight convolution, and residual connections']
```

Usage

```
{'build_mel_spectrogram': 'build a module that computes Mel-filterbank spectrograms from raw audio waveforms using GemaxMelFilterbank', 'build_conformer_encoder': 'build a Conformer audio encoder stack with configurable layers, attention heads, and model dimensions', 'build_subsampling_block': 'build a subsampling block that reduces audio sequence length via strided convolutions and LayerNorm', 'build_local_attention': 'build a local dot-product attention module with Transformer-XL relative position embeddings and causal masking', 'build_conformer_layer': 'build a single Conformer layer combining FFN, self-attention, lightweight convolution, and residual connections'}
```

