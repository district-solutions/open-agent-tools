# Agent Python Tools

- repo: facebookresearch/audiodec
- repo_uri: https://github.com/facebookresearch/audiodec

## File: facebookresearch_audiodec/models/vocoder/HiFiGAN.py

Prompts

```
['build a HiFiGAN causal generator with upsampling scales and residual blocks for vocoder synthesis', 'build a HiFiGAN streaming generator with step-by-step decode and buffer reset for real-time inference', 'build a HiFiGAN multi-scale and multi-period discriminator for adversarial training of vocoder models', 'run the HiFiGAN generator forward pass to synthesize waveform from mel-spectrogram input tensor', 'test the HiFiGAN discriminator forward pass on audio waveform tensor for adversarial loss', 'build a UnivNet multi-resolution spectral and multi-period discriminator for adversarial vocoder training', 'run the UnivNet discriminator forward pass on an audio waveform tensor to get outputs', 'build a UnivNet discriminator with custom FFT sizes, hop sizes, and window lengths', 'build a UnivNet discriminator with flat channel mode to flatten multi-channel input', 'test the UnivNet discriminator combining multi-resolution spectral and multi-period discriminator outputs']
```

Usage

```
{'build_hifigan_generator': 'build a HiFiGAN causal generator with upsampling scales and residual blocks for vocoder synthesis', 'build_stream_generator': 'build a HiFiGAN streaming generator with step-by-step decode and buffer reset for real-time inference', 'build_discriminator': 'build a HiFiGAN multi-scale and multi-period discriminator for adversarial training of vocoder models', 'run_generator_forward': 'run the HiFiGAN generator forward pass to synthesize waveform from mel-spectrogram input tensor', 'test_discriminator_forward': 'test the HiFiGAN discriminator forward pass on audio waveform tensor for adversarial loss'}
```

## File: facebookresearch_audiodec/models/vocoder/UnivNet.py

Prompts

```
['build a HiFiGAN causal generator with upsampling scales and residual blocks for vocoder synthesis', 'build a HiFiGAN streaming generator with step-by-step decode and buffer reset for real-time inference', 'build a HiFiGAN multi-scale and multi-period discriminator for adversarial training of vocoder models', 'run the HiFiGAN generator forward pass to synthesize waveform from mel-spectrogram input tensor', 'test the HiFiGAN discriminator forward pass on audio waveform tensor for adversarial loss', 'build a UnivNet multi-resolution spectral and multi-period discriminator for adversarial vocoder training', 'run the UnivNet discriminator forward pass on an audio waveform tensor to get outputs', 'build a UnivNet discriminator with custom FFT sizes, hop sizes, and window lengths', 'build a UnivNet discriminator with flat channel mode to flatten multi-channel input', 'test the UnivNet discriminator combining multi-resolution spectral and multi-period discriminator outputs']
```

Usage

```
{'build_univnet_discriminator': 'build a UnivNet multi-resolution spectral and multi-period discriminator for adversarial vocoder training', 'run_discriminator_forward': 'run the UnivNet discriminator forward pass on an audio waveform tensor to get outputs', 'build_discriminator_with_custom_fft': 'build a UnivNet discriminator with custom FFT sizes, hop sizes, and window lengths', 'build_discriminator_with_flat_channel': 'build a UnivNet discriminator with flat channel mode to flatten multi-channel input', 'test_discriminator_mrsd_mpd': 'test the UnivNet discriminator combining multi-resolution spectral and multi-period discriminator outputs'}
```

