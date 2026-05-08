# Agent Python Tools

- repo: facebookresearch/largeconceptmodel
- repo_uri: https://github.com/facebookresearch/large_concept_model

## File: facebookresearch_largeconceptmodel/lcm/models/two_tower_diffusion_lcm/archs.py

Prompts

```
['build a toy two-tower diffusion LCM config with 2-layer encoder and denoiser', 'build a 1.6B parameter two-tower diffusion LCM config with 5-layer encoder and 13-layer denoiser', 'build a 7B parameter two-tower diffusion LCM config with 5-layer encoder and 14-layer denoiser', 'review the TwoTowerDiffusionLCModelConfig dataclass fields including model_dim, max_seq_len, and denoiser settings', 'summarize how the lcm_arch decorator registers toy_lcm, 1.6B, and 7B model architectures', 'create a TwoTowerDiffusionLCModel from a TwoTowerDiffusionLCModelConfig with optional device and dtype', 'build a complete TwoTowerDiffusionLCModel including sonar normalizer, context encoder, denoiser, and noise scheduler', 'predict the next sentence embeddings using diffusion denoising on a given context batch', 'encode a batch of sonar embeddings through the frontend and causal context encoder', 'denoise a noisy embeddings batch conditioned on an encoded context using the denoiser', 'create an EncoderFrontend module with a SONAR embedding dimension and model dimension', 'create an EncoderFrontendConfig dataclass with dropout, bias, and weight normalization settings', 'run the EncoderFrontend forward pass on sequence tensors with an optional padding mask', 'reset the EncoderFrontend positional embedding parameters using a normal distribution with given std', 'review the EncoderFrontend constructor to understand SONAR embedding dimension and position encoder validation']
```

Usage

```
{'build_toy_two_tower_diffusion_lcm': 'build a toy two-tower diffusion LCM config with 2-layer encoder and denoiser', 'build_two_tower_diffusion_lcm_1_6B': 'build a 1.6B parameter two-tower diffusion LCM config with 5-layer encoder and 13-layer denoiser', 'build_two_tower_diffusion_lcm_7B': 'build a 7B parameter two-tower diffusion LCM config with 5-layer encoder and 14-layer denoiser', 'review_TwoTowerDiffusionLCModelConfig': 'review the TwoTowerDiffusionLCModelConfig dataclass fields including model_dim, max_seq_len, and denoiser settings', 'summarize_lcm_arch_registry': 'summarize how the lcm_arch decorator registers toy_lcm, 1.6B, and 7B model architectures'}
```

## File: facebookresearch_largeconceptmodel/lcm/models/two_tower_diffusion_lcm/builder.py

Prompts

```
['build a toy two-tower diffusion LCM config with 2-layer encoder and denoiser', 'build a 1.6B parameter two-tower diffusion LCM config with 5-layer encoder and 13-layer denoiser', 'build a 7B parameter two-tower diffusion LCM config with 5-layer encoder and 14-layer denoiser', 'review the TwoTowerDiffusionLCModelConfig dataclass fields including model_dim, max_seq_len, and denoiser settings', 'summarize how the lcm_arch decorator registers toy_lcm, 1.6B, and 7B model architectures', 'create a TwoTowerDiffusionLCModel from a TwoTowerDiffusionLCModelConfig with optional device and dtype', 'build a complete TwoTowerDiffusionLCModel including sonar normalizer, context encoder, denoiser, and noise scheduler', 'predict the next sentence embeddings using diffusion denoising on a given context batch', 'encode a batch of sonar embeddings through the frontend and causal context encoder', 'denoise a noisy embeddings batch conditioned on an encoded context using the denoiser', 'create an EncoderFrontend module with a SONAR embedding dimension and model dimension', 'create an EncoderFrontendConfig dataclass with dropout, bias, and weight normalization settings', 'run the EncoderFrontend forward pass on sequence tensors with an optional padding mask', 'reset the EncoderFrontend positional embedding parameters using a normal distribution with given std', 'review the EncoderFrontend constructor to understand SONAR embedding dimension and position encoder validation']
```

Usage

```
{'create_two_tower_diffusion_lcm_model': 'create a TwoTowerDiffusionLCModel from a TwoTowerDiffusionLCModelConfig with optional device and dtype', 'build_model_TwoTowerDiffusionLCModelBuilder': 'build a complete TwoTowerDiffusionLCModel including sonar normalizer, context encoder, denoiser, and noise scheduler', 'predict_next_sentence_TwoTowerDiffusionLCModel': 'predict the next sentence embeddings using diffusion denoising on a given context batch', 'encode_TwoTowerDiffusionLCModel': 'encode a batch of sonar embeddings through the frontend and causal context encoder', 'denoise_TwoTowerDiffusionLCModel': 'denoise a noisy embeddings batch conditioned on an encoded context using the denoiser'}
```

## File: facebookresearch_largeconceptmodel/lcm/models/two_tower_diffusion_lcm/frontend.py

Prompts

```
['build a toy two-tower diffusion LCM config with 2-layer encoder and denoiser', 'build a 1.6B parameter two-tower diffusion LCM config with 5-layer encoder and 13-layer denoiser', 'build a 7B parameter two-tower diffusion LCM config with 5-layer encoder and 14-layer denoiser', 'review the TwoTowerDiffusionLCModelConfig dataclass fields including model_dim, max_seq_len, and denoiser settings', 'summarize how the lcm_arch decorator registers toy_lcm, 1.6B, and 7B model architectures', 'create a TwoTowerDiffusionLCModel from a TwoTowerDiffusionLCModelConfig with optional device and dtype', 'build a complete TwoTowerDiffusionLCModel including sonar normalizer, context encoder, denoiser, and noise scheduler', 'predict the next sentence embeddings using diffusion denoising on a given context batch', 'encode a batch of sonar embeddings through the frontend and causal context encoder', 'denoise a noisy embeddings batch conditioned on an encoded context using the denoiser', 'create an EncoderFrontend module with a SONAR embedding dimension and model dimension', 'create an EncoderFrontendConfig dataclass with dropout, bias, and weight normalization settings', 'run the EncoderFrontend forward pass on sequence tensors with an optional padding mask', 'reset the EncoderFrontend positional embedding parameters using a normal distribution with given std', 'review the EncoderFrontend constructor to understand SONAR embedding dimension and position encoder validation']
```

Usage

```
{'create_encoder_frontend': 'create an EncoderFrontend module with a SONAR embedding dimension and model dimension', 'create_encoder_frontend_config': 'create an EncoderFrontendConfig dataclass with dropout, bias, and weight normalization settings', 'run_encoder_frontend_forward': 'run the EncoderFrontend forward pass on sequence tensors with an optional padding mask', 'reset_encoder_frontend_parameters': 'reset the EncoderFrontend positional embedding parameters using a normal distribution with given std', 'review_encoder_frontend_init': 'review the EncoderFrontend constructor to understand SONAR embedding dimension and position encoder validation'}
```

