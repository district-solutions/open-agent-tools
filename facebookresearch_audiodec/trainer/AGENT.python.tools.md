# Agent Python Tools

- repo: facebookresearch/audiodec
- repo_uri: https://github.com/facebookresearch/audiodec

## File: facebookresearch_audiodec/trainer/trainerGAN.py

Prompts

```
['run the TrainerGAN training loop for generator and discriminator models with tensorboard logging', 'save a GAN training checkpoint with generator and discriminator model states and optimizer states', 'load a GAN training checkpoint to restore generator and discriminator models and training state', 'compute the adversarial loss with optional feature matching loss for the GAN generator', 'compute the discriminator loss combining real and fake prediction losses for the GAN discriminator', 'compute metric losses including mel spectrogram, multi-resolution STFT, and waveform shape losses', 'update the GAN generator model parameters using gradient descent with optional gradient clipping', 'update the GAN discriminator model parameters using gradient descent with optional gradient clipping', 'run the TrainerVQGAN training loop with vector quantization loss and perplexity tracking', 'compute and record the vector quantization loss with configurable lambda weighting for VQGAN training', 'record perplexity metrics for vector quantization codebook usage during VQGAN training', 'run evaluation on the development dataset and log averaged loss metrics to tensorboard']
```

Usage

```
{'run_GAN_training': 'run the TrainerGAN training loop for generator and discriminator models with tensorboard logging', 'save_GAN_checkpoint': 'save a GAN training checkpoint with generator and discriminator model states and optimizer states', 'load_GAN_checkpoint': 'load a GAN training checkpoint to restore generator and discriminator models and training state', 'compute_adversarial_loss': 'compute the adversarial loss with optional feature matching loss for the GAN generator', 'compute_discriminator_loss': 'compute the discriminator loss combining real and fake prediction losses for the GAN discriminator', 'compute_metric_loss': 'compute metric losses including mel spectrogram, multi-resolution STFT, and waveform shape losses', 'update_generator': 'update the GAN generator model parameters using gradient descent with optional gradient clipping', 'update_discriminator': 'update the GAN discriminator model parameters using gradient descent with optional gradient clipping', 'run_VQGAN_training': 'run the TrainerVQGAN training loop with vector quantization loss and perplexity tracking', 'compute_VQ_loss': 'compute and record the vector quantization loss with configurable lambda weighting for VQGAN training', 'record_perplexity': 'record perplexity metrics for vector quantization codebook usage during VQGAN training', 'evaluate_GAN_model': 'run evaluation on the development dataset and log averaged loss metrics to tensorboard'}
```

