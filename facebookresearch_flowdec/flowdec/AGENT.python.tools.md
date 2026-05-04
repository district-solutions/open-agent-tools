# Agent Python Tools

- repo: facebookresearch/flowdec
- repo_uri: https://github.com/facebookresearch/flowdec

## File: facebookresearch_flowdec/flowdec/losses.py

Prompts

```
['build a TorchPESQSpeechLoss module to compute PESQ loss between predicted and reference speech tensors', 'create a MultiScaleSTFTLoss module to compute multi-scale STFT loss between estimated and reference audio signals', 'create a MelSpectrogramLoss module to compute multi-scale mel spectrogram distance between two audio signals', 'review the MultiScaleSTFTLoss forward method that computes STFT loss across multiple window lengths', 'test the MelSpectrogramLoss to method that moves all mel transform modules to a target device', 'create a new EnhancementModel subclass with a backbone, feature extractor, and learning rate for audio enhancement', 'enhance a noisy audio waveform using FlowModel with an Euler ODE solver and configurable timesteps', 'enhance a noisy audio waveform using RegressionModel trained with L2 loss', 'enhance a noisy audio waveform using ScoreModel with a predictor-corrector SDE sampler', 'evaluate an EnhancementModel on a list of audio files and compute quality metrics like PESQ', 'build an Ornstein-Uhlenbeck Variance Exploding SDE with theta, sigma_min, sigma_max parameters for diffusion', 'build an Ornstein-Uhlenbeck Variance Preserving SDE with beta_min, beta_max, and stiffness parameters', 'build a Brownian Bridge Exponential Diffusion SDE with c and k parameters for ICASSP 2024', 'review the SDE reverse method to create a reverse-time SDE or ODE from a score model', 'test the SDE discretize method to get Euler-Maruyama drift and diffusion coefficients']
```

Usage

```
{'build_pesq_speech_loss': 'build a TorchPESQSpeechLoss module to compute PESQ loss between predicted and reference speech tensors', 'create_multiscale_stft_loss': 'create a MultiScaleSTFTLoss module to compute multi-scale STFT loss between estimated and reference audio signals', 'create_mel_spectrogram_loss': 'create a MelSpectrogramLoss module to compute multi-scale mel spectrogram distance between two audio signals', 'review_multiscale_stft_loss_forward': 'review the MultiScaleSTFTLoss forward method that computes STFT loss across multiple window lengths', 'test_mel_spectrogram_loss_to': 'test the MelSpectrogramLoss to method that moves all mel transform modules to a target device'}
```

## File: facebookresearch_flowdec/flowdec/model.py

Prompts

```
['build a TorchPESQSpeechLoss module to compute PESQ loss between predicted and reference speech tensors', 'create a MultiScaleSTFTLoss module to compute multi-scale STFT loss between estimated and reference audio signals', 'create a MelSpectrogramLoss module to compute multi-scale mel spectrogram distance between two audio signals', 'review the MultiScaleSTFTLoss forward method that computes STFT loss across multiple window lengths', 'test the MelSpectrogramLoss to method that moves all mel transform modules to a target device', 'create a new EnhancementModel subclass with a backbone, feature extractor, and learning rate for audio enhancement', 'enhance a noisy audio waveform using FlowModel with an Euler ODE solver and configurable timesteps', 'enhance a noisy audio waveform using RegressionModel trained with L2 loss', 'enhance a noisy audio waveform using ScoreModel with a predictor-corrector SDE sampler', 'evaluate an EnhancementModel on a list of audio files and compute quality metrics like PESQ', 'build an Ornstein-Uhlenbeck Variance Exploding SDE with theta, sigma_min, sigma_max parameters for diffusion', 'build an Ornstein-Uhlenbeck Variance Preserving SDE with beta_min, beta_max, and stiffness parameters', 'build a Brownian Bridge Exponential Diffusion SDE with c and k parameters for ICASSP 2024', 'review the SDE reverse method to create a reverse-time SDE or ODE from a score model', 'test the SDE discretize method to get Euler-Maruyama drift and diffusion coefficients']
```

Usage

```
{'create_enhancement_model': 'create a new EnhancementModel subclass with a backbone, feature extractor, and learning rate for audio enhancement', 'enhance_audio_with_flow_model': 'enhance a noisy audio waveform using FlowModel with an Euler ODE solver and configurable timesteps', 'enhance_audio_with_regression_model': 'enhance a noisy audio waveform using RegressionModel trained with L2 loss', 'enhance_audio_with_score_model': 'enhance a noisy audio waveform using ScoreModel with a predictor-corrector SDE sampler', 'evaluate_enhancement_model': 'evaluate an EnhancementModel on a list of audio files and compute quality metrics like PESQ'}
```

## File: facebookresearch_flowdec/flowdec/sdes.py

Prompts

```
['build a TorchPESQSpeechLoss module to compute PESQ loss between predicted and reference speech tensors', 'create a MultiScaleSTFTLoss module to compute multi-scale STFT loss between estimated and reference audio signals', 'create a MelSpectrogramLoss module to compute multi-scale mel spectrogram distance between two audio signals', 'review the MultiScaleSTFTLoss forward method that computes STFT loss across multiple window lengths', 'test the MelSpectrogramLoss to method that moves all mel transform modules to a target device', 'create a new EnhancementModel subclass with a backbone, feature extractor, and learning rate for audio enhancement', 'enhance a noisy audio waveform using FlowModel with an Euler ODE solver and configurable timesteps', 'enhance a noisy audio waveform using RegressionModel trained with L2 loss', 'enhance a noisy audio waveform using ScoreModel with a predictor-corrector SDE sampler', 'evaluate an EnhancementModel on a list of audio files and compute quality metrics like PESQ', 'build an Ornstein-Uhlenbeck Variance Exploding SDE with theta, sigma_min, sigma_max parameters for diffusion', 'build an Ornstein-Uhlenbeck Variance Preserving SDE with beta_min, beta_max, and stiffness parameters', 'build a Brownian Bridge Exponential Diffusion SDE with c and k parameters for ICASSP 2024', 'review the SDE reverse method to create a reverse-time SDE or ODE from a score model', 'test the SDE discretize method to get Euler-Maruyama drift and diffusion coefficients']
```

Usage

```
{'build_OUVESDE': 'build an Ornstein-Uhlenbeck Variance Exploding SDE with theta, sigma_min, sigma_max parameters for diffusion', 'build_OUVPSDE': 'build an Ornstein-Uhlenbeck Variance Preserving SDE with beta_min, beta_max, and stiffness parameters', 'build_BBEDSDE': 'build a Brownian Bridge Exponential Diffusion SDE with c and k parameters for ICASSP 2024', 'review_SDE_reverse': 'review the SDE reverse method to create a reverse-time SDE or ODE from a score model', 'test_SDE_discretize': 'test the SDE discretize method to get Euler-Maruyama drift and diffusion coefficients'}
```

