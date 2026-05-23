# Agent Python Tools

- repo: facebookresearch/spiritlm
- repo_uri: https://github.com/facebookresearch/spiritlm

## File: facebookresearch_spiritlm/spiritlm/speech_tokenizer/f0/f0_extractor.py

Prompts

```
['create a pYAPT F0 extractor instance using load_f0_extractor with method pyaapt', 'create an FCPE F0 extractor instance using load_f0_extractor with method fcpe and a device', 'run the pYAAPTF0Extractor forward pass on an audio file path to extract fundamental frequency', 'run the FCPEF0Extractor forward pass on a numpy waveform to extract fundamental frequency and voicing', 'review the F0Extractor base class forward method and load_audio for audio loading and resampling', 'build a python module to create an F0Tokenizer that extracts and quantizes fundamental frequency from audio waveforms', 'create a function that quantizes f0 and vuv tensors using a VQ-VAE model with optional speaker normalization', 'run the F0Tokenizer forward pass to extract f0 from audio and return quantized tokens or dense f0 values', 'review the F0Tokenizer constructor to understand how f0 extractors, VQ-VAE quantizers, and speaker stats are loaded', 'test the F0Tokenizer device property to verify the model is correctly placed on the target device', 'load a VQVAE model from a checkpoint file along with its config.yaml', 'encode speech features into discrete F0 codes using the VQVAE encoder and bottleneck', 'decode discrete F0 codes back to continuous speech features using the VQVAE decoder', 'build a multi-level Encoder with Resnet1D blocks and configurable downsampling strides', 'build a multi-level Decoder with skip connections and transposed convolutions for upsampling']
```

Usage

```
{'load_f0_extractor_pyaapt': 'create a pYAPT F0 extractor instance using load_f0_extractor with method pyaapt', 'load_f0_extractor_fcpe': 'create an FCPE F0 extractor instance using load_f0_extractor with method fcpe and a device', 'run_pYAAPT_forward': 'run the pYAAPTF0Extractor forward pass on an audio file path to extract fundamental frequency', 'run_FCPE_forward': 'run the FCPEF0Extractor forward pass on a numpy waveform to extract fundamental frequency and voicing', 'review_F0Extractor_base': 'review the F0Extractor base class forward method and load_audio for audio loading and resampling'}
```

## File: facebookresearch_spiritlm/spiritlm/speech_tokenizer/f0/f0_tokenizer.py

Prompts

```
['create a pYAPT F0 extractor instance using load_f0_extractor with method pyaapt', 'create an FCPE F0 extractor instance using load_f0_extractor with method fcpe and a device', 'run the pYAAPTF0Extractor forward pass on an audio file path to extract fundamental frequency', 'run the FCPEF0Extractor forward pass on a numpy waveform to extract fundamental frequency and voicing', 'review the F0Extractor base class forward method and load_audio for audio loading and resampling', 'build a python module to create an F0Tokenizer that extracts and quantizes fundamental frequency from audio waveforms', 'create a function that quantizes f0 and vuv tensors using a VQ-VAE model with optional speaker normalization', 'run the F0Tokenizer forward pass to extract f0 from audio and return quantized tokens or dense f0 values', 'review the F0Tokenizer constructor to understand how f0 extractors, VQ-VAE quantizers, and speaker stats are loaded', 'test the F0Tokenizer device property to verify the model is correctly placed on the target device', 'load a VQVAE model from a checkpoint file along with its config.yaml', 'encode speech features into discrete F0 codes using the VQVAE encoder and bottleneck', 'decode discrete F0 codes back to continuous speech features using the VQVAE decoder', 'build a multi-level Encoder with Resnet1D blocks and configurable downsampling strides', 'build a multi-level Decoder with skip connections and transposed convolutions for upsampling']
```

Usage

```
{'build_F0Tokenizer': 'build a python module to create an F0Tokenizer that extracts and quantizes fundamental frequency from audio waveforms', 'create_F0Tokenizer_quantize_vqvae': 'create a function that quantizes f0 and vuv tensors using a VQ-VAE model with optional speaker normalization', 'run_F0Tokenizer_forward': 'run the F0Tokenizer forward pass to extract f0 from audio and return quantized tokens or dense f0 values', 'review_F0Tokenizer_init': 'review the F0Tokenizer constructor to understand how f0 extractors, VQ-VAE quantizers, and speaker stats are loaded', 'test_F0Tokenizer_device': 'test the F0Tokenizer device property to verify the model is correctly placed on the target device'}
```

## File: facebookresearch_spiritlm/spiritlm/speech_tokenizer/f0/vqvae.py

Prompts

```
['create a pYAPT F0 extractor instance using load_f0_extractor with method pyaapt', 'create an FCPE F0 extractor instance using load_f0_extractor with method fcpe and a device', 'run the pYAAPTF0Extractor forward pass on an audio file path to extract fundamental frequency', 'run the FCPEF0Extractor forward pass on a numpy waveform to extract fundamental frequency and voicing', 'review the F0Extractor base class forward method and load_audio for audio loading and resampling', 'build a python module to create an F0Tokenizer that extracts and quantizes fundamental frequency from audio waveforms', 'create a function that quantizes f0 and vuv tensors using a VQ-VAE model with optional speaker normalization', 'run the F0Tokenizer forward pass to extract f0 from audio and return quantized tokens or dense f0 values', 'review the F0Tokenizer constructor to understand how f0 extractors, VQ-VAE quantizers, and speaker stats are loaded', 'test the F0Tokenizer device property to verify the model is correctly placed on the target device', 'load a VQVAE model from a checkpoint file along with its config.yaml', 'encode speech features into discrete F0 codes using the VQVAE encoder and bottleneck', 'decode discrete F0 codes back to continuous speech features using the VQVAE decoder', 'build a multi-level Encoder with Resnet1D blocks and configurable downsampling strides', 'build a multi-level Decoder with skip connections and transposed convolutions for upsampling']
```

Usage

```
{'load_vqvae_model': 'load a VQVAE model from a checkpoint file along with its config.yaml', 'encode_speech_to_codes': 'encode speech features into discrete F0 codes using the VQVAE encoder and bottleneck', 'decode_codes_to_speech': 'decode discrete F0 codes back to continuous speech features using the VQVAE decoder', 'build_encoder_with_resnet1d': 'build a multi-level Encoder with Resnet1D blocks and configurable downsampling strides', 'build_decoder_with_skip_connections': 'build a multi-level Decoder with skip connections and transposed convolutions for upsampling'}
```

