# Agent Python Tools

- repo: OpenBMB/VoxCPM
- repo_uri: https://github.com/OpenBMB/VoxCPM

## File: OpenBMB_VoxCPM/src/voxcpm/modules/audiovae/audio_vae.py

Prompts

```
['create an AudioVAE model with default or custom AudioVAEConfig for causal audio encoding and decoding', 'build an AudioVAEConfig with encoder_dim, encoder_rates, latent_dim, decoder_dim, decoder_rates, and sample_rate parameters', 'encode audio data tensor with sample rate into latent representation using AudioVAE.encode', 'decode latent tensor back into audio waveform using AudioVAE.decode', 'preprocess audio data by right-padding to hop_length multiples using AudioVAE.preprocess', 'create an AudioVAE model with causal encoder-decoder for audio waveform compression', 'encode audio waveform tensor into latent representation using the causal encoder', 'decode latent tensor back to audio waveform with optional sample rate conditioning', 'streaming decode audio chunks statefully without redundant overlap decoding', 'configure sample rate conditioning with scale-bias or add embedding for multi-rate audio']
```

Usage

```
{'create_AudioVAE': 'create an AudioVAE model with default or custom AudioVAEConfig for causal audio encoding and decoding', 'build_AudioVAEConfig': 'build an AudioVAEConfig with encoder_dim, encoder_rates, latent_dim, decoder_dim, decoder_rates, and sample_rate parameters', 'encode_audio': 'encode audio data tensor with sample rate into latent representation using AudioVAE.encode', 'decode_audio': 'decode latent tensor back into audio waveform using AudioVAE.decode', 'preprocess_audio': 'preprocess audio data by right-padding to hop_length multiples using AudioVAE.preprocess'}
```

## File: OpenBMB_VoxCPM/src/voxcpm/modules/audiovae/audio_vae_v2.py

Prompts

```
['create an AudioVAE model with default or custom AudioVAEConfig for causal audio encoding and decoding', 'build an AudioVAEConfig with encoder_dim, encoder_rates, latent_dim, decoder_dim, decoder_rates, and sample_rate parameters', 'encode audio data tensor with sample rate into latent representation using AudioVAE.encode', 'decode latent tensor back into audio waveform using AudioVAE.decode', 'preprocess audio data by right-padding to hop_length multiples using AudioVAE.preprocess', 'create an AudioVAE model with causal encoder-decoder for audio waveform compression', 'encode audio waveform tensor into latent representation using the causal encoder', 'decode latent tensor back to audio waveform with optional sample rate conditioning', 'streaming decode audio chunks statefully without redundant overlap decoding', 'configure sample rate conditioning with scale-bias or add embedding for multi-rate audio']
```

Usage

```
{'create_audio_vae_model': 'create an AudioVAE model with causal encoder-decoder for audio waveform compression', 'encode_audio_waveform': 'encode audio waveform tensor into latent representation using the causal encoder', 'decode_latent_to_audio': 'decode latent tensor back to audio waveform with optional sample rate conditioning', 'streaming_decode_audio': 'streaming decode audio chunks statefully without redundant overlap decoding', 'configure_sample_rate_conditioning': 'configure sample rate conditioning with scale-bias or add embedding for multi-rate audio'}
```

