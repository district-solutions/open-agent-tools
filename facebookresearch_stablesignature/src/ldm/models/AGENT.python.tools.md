# Agent Python Tools

- repo: facebookresearch/stablesignature
- repo_uri: https://github.com/facebookresearch/stable_signature

## File: facebookresearch_stablesignature/src/ldm/models/autoencoder.py

Prompts

```
['encode input images into a DiagonalGaussianDistribution posterior using AutoencoderKL encoder and quant_conv', 'decode latent vectors back to image space using AutoencoderKL post_quant_conv and decoder', 'initialize an AutoencoderKL model from a checkpoint file with optional ignored keys', 'use the ema_scope context manager to temporarily switch to EMA weights for inference', 'create an IdentityFirstStage pass-through module that returns inputs unchanged with optional VQ interface']
```

Usage

```
{'encode_images_with_autoencoderkl': 'encode input images into a DiagonalGaussianDistribution posterior using AutoencoderKL encoder and quant_conv', 'decode_latents_with_autoencoderkl': 'decode latent vectors back to image space using AutoencoderKL post_quant_conv and decoder', 'init_autoencoderkl_from_ckpt': 'initialize an AutoencoderKL model from a checkpoint file with optional ignored keys', 'use_ema_scope_for_inference': 'use the ema_scope context manager to temporarily switch to EMA weights for inference', 'create_identity_first_stage_module': 'create an IdentityFirstStage pass-through module that returns inputs unchanged with optional VQ interface'}
```

