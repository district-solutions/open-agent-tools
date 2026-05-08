# Agent Python Tools

- repo: facebookresearch/dacvae
- repo_uri: https://github.com/facebookresearch/dacvae

## File: facebookresearch_dacvae/dacvae/model/base.py

Prompts

```
['compress an audio file into discrete codes using CodecMixin compress method and save as DACFile', 'decompress a DACFile of discrete codes back into an AudioSignal using CodecMixin decompress method', 'save a DACFile object with compressed audio codes and metadata to a .dacvae file on disk', 'load a DACFile object from a .dacvae file on disk using the DACFile load class method', 'calculate the output length of a codec model given an input length using get_output_length', 'encode audio data into latent representations using the DACVAE model encoder', 'decode latent encoded frames back into audio using the DACVAE model decoder', 'load a pre-trained DACVAE model from HuggingFace Hub or a local weights file', 'encode audio data into quantized latent codes using the DAC model with residual vector quantization', 'decode latent codes into audio with an optional embedded watermark message using the DAC decoder', 'build a Period Discriminator (MPD) module to analyze audio waveforms across specified sample periods', 'build a Scale Discriminator (MSD) module to analyze audio at different sampling rates using 1D convolutions', 'build a Multi-band Spectrogram Discriminator (MRD) module to analyze complex spectrograms across frequency bands', 'build a combined Discriminator module that runs MPD, MSD, and MRD discriminators on audio input', 'test the Discriminator forward pass by passing a batch of audio tensors and inspecting feature map outputs']
```

Usage

```
{'compress_audio_to_codes': 'compress an audio file into discrete codes using CodecMixin compress method and save as DACFile', 'decompress_codes_to_audio': 'decompress a DACFile of discrete codes back into an AudioSignal using CodecMixin decompress method', 'save_DACFile': 'save a DACFile object with compressed audio codes and metadata to a .dacvae file on disk', 'load_DACFile': 'load a DACFile object from a .dacvae file on disk using the DACFile load class method', 'get_codec_output_length': 'calculate the output length of a codec model given an input length using get_output_length'}
```

## File: facebookresearch_dacvae/dacvae/model/dacvae.py

Prompts

```
['compress an audio file into discrete codes using CodecMixin compress method and save as DACFile', 'decompress a DACFile of discrete codes back into an AudioSignal using CodecMixin decompress method', 'save a DACFile object with compressed audio codes and metadata to a .dacvae file on disk', 'load a DACFile object from a .dacvae file on disk using the DACFile load class method', 'calculate the output length of a codec model given an input length using get_output_length', 'encode audio data into latent representations using the DACVAE model encoder', 'decode latent encoded frames back into audio using the DACVAE model decoder', 'load a pre-trained DACVAE model from HuggingFace Hub or a local weights file', 'encode audio data into quantized latent codes using the DAC model with residual vector quantization', 'decode latent codes into audio with an optional embedded watermark message using the DAC decoder', 'build a Period Discriminator (MPD) module to analyze audio waveforms across specified sample periods', 'build a Scale Discriminator (MSD) module to analyze audio at different sampling rates using 1D convolutions', 'build a Multi-band Spectrogram Discriminator (MRD) module to analyze complex spectrograms across frequency bands', 'build a combined Discriminator module that runs MPD, MSD, and MRD discriminators on audio input', 'test the Discriminator forward pass by passing a batch of audio tensors and inspecting feature map outputs']
```

Usage

```
{'encode_audio_with_DACVAE': 'encode audio data into latent representations using the DACVAE model encoder', 'decode_latents_with_DACVAE': 'decode latent encoded frames back into audio using the DACVAE model decoder', 'load_DACVAE_from_hub': 'load a pre-trained DACVAE model from HuggingFace Hub or a local weights file', 'encode_audio_with_DAC': 'encode audio data into quantized latent codes using the DAC model with residual vector quantization', 'decode_with_watermark': 'decode latent codes into audio with an optional embedded watermark message using the DAC decoder'}
```

## File: facebookresearch_dacvae/dacvae/model/discriminator.py

Prompts

```
['compress an audio file into discrete codes using CodecMixin compress method and save as DACFile', 'decompress a DACFile of discrete codes back into an AudioSignal using CodecMixin decompress method', 'save a DACFile object with compressed audio codes and metadata to a .dacvae file on disk', 'load a DACFile object from a .dacvae file on disk using the DACFile load class method', 'calculate the output length of a codec model given an input length using get_output_length', 'encode audio data into latent representations using the DACVAE model encoder', 'decode latent encoded frames back into audio using the DACVAE model decoder', 'load a pre-trained DACVAE model from HuggingFace Hub or a local weights file', 'encode audio data into quantized latent codes using the DAC model with residual vector quantization', 'decode latent codes into audio with an optional embedded watermark message using the DAC decoder', 'build a Period Discriminator (MPD) module to analyze audio waveforms across specified sample periods', 'build a Scale Discriminator (MSD) module to analyze audio at different sampling rates using 1D convolutions', 'build a Multi-band Spectrogram Discriminator (MRD) module to analyze complex spectrograms across frequency bands', 'build a combined Discriminator module that runs MPD, MSD, and MRD discriminators on audio input', 'test the Discriminator forward pass by passing a batch of audio tensors and inspecting feature map outputs']
```

Usage

```
{'build_MPD': 'build a Period Discriminator (MPD) module to analyze audio waveforms across specified sample periods', 'build_MSD': 'build a Scale Discriminator (MSD) module to analyze audio at different sampling rates using 1D convolutions', 'build_MRD': 'build a Multi-band Spectrogram Discriminator (MRD) module to analyze complex spectrograms across frequency bands', 'build_Discriminator': 'build a combined Discriminator module that runs MPD, MSD, and MRD discriminators on audio input', 'test_Discriminator_forward': 'test the Discriminator forward pass by passing a batch of audio tensors and inspecting feature map outputs'}
```

