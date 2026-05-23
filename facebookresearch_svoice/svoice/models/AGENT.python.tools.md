# Agent Python Tools

- repo: facebookresearch/svoice
- repo_uri: https://github.com/facebookresearch/svoice

## File: facebookresearch_svoice/svoice/models/sisnr_loss.py

Prompts

```
['calculate SI-SNR loss between source and estimated source signals with permutation invariant training', 'calculate SI-SNR with permutation invariant training for source separation using batched audio tensors', 'reorder estimated source signals according to the best permutation that maximizes SI-SNR', 'create a binary mask tensor to zero out padding positions in audio sequences by length', 'review the SI-SNR loss module for source separation tasks using PyTorch tensors', 'build a SWave model for speech separation with configurable N, L, H, R, C, sr, and segment hyperparameters', 'create a Separator module with DPMulCat RNN for chunked speech feature separation across multiple speakers', 'run the Encoder forward pass to convert raw waveform mixture into N-dimensional feature representations using conv1d', 'run the Decoder forward pass to reconstruct separated waveforms from feature representations using overlap and add', 'review the DPMulCat dual-path RNN architecture with row and column GRNN processing and skip connections']
```

Usage

```
{'cal_loss_si_snr': 'calculate SI-SNR loss between source and estimated source signals with permutation invariant training', 'cal_si_snr_with_pit': 'calculate SI-SNR with permutation invariant training for source separation using batched audio tensors', 'reorder_source_permutations': 'reorder estimated source signals according to the best permutation that maximizes SI-SNR', 'get_mask_padding': 'create a binary mask tensor to zero out padding positions in audio sequences by length', 'review_sisnr_loss': 'review the SI-SNR loss module for source separation tasks using PyTorch tensors'}
```

## File: facebookresearch_svoice/svoice/models/swave.py

Prompts

```
['calculate SI-SNR loss between source and estimated source signals with permutation invariant training', 'calculate SI-SNR with permutation invariant training for source separation using batched audio tensors', 'reorder estimated source signals according to the best permutation that maximizes SI-SNR', 'create a binary mask tensor to zero out padding positions in audio sequences by length', 'review the SI-SNR loss module for source separation tasks using PyTorch tensors', 'build a SWave model for speech separation with configurable N, L, H, R, C, sr, and segment hyperparameters', 'create a Separator module with DPMulCat RNN for chunked speech feature separation across multiple speakers', 'run the Encoder forward pass to convert raw waveform mixture into N-dimensional feature representations using conv1d', 'run the Decoder forward pass to reconstruct separated waveforms from feature representations using overlap and add', 'review the DPMulCat dual-path RNN architecture with row and column GRNN processing and skip connections']
```

Usage

```
{'build_swave_model': 'build a SWave model for speech separation with configurable N, L, H, R, C, sr, and segment hyperparameters', 'create_separator_network': 'create a Separator module with DPMulCat RNN for chunked speech feature separation across multiple speakers', 'run_encoder_forward': 'run the Encoder forward pass to convert raw waveform mixture into N-dimensional feature representations using conv1d', 'run_decoder_forward': 'run the Decoder forward pass to reconstruct separated waveforms from feature representations using overlap and add', 'review_dpmulcat_layers': 'review the DPMulCat dual-path RNN architecture with row and column GRNN processing and skip connections'}
```

