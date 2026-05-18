# Agent Python Tools

- repo: facebookresearch/mvp
- repo_uri: https://github.com/facebookresearch/mvp

## File: facebookresearch_mvp/models/encoders/geotex.py

Prompts

```
['build a GeoTex Encoder that processes vertex and texture inputs into a latent encoding using VAE reparameterization', 'build a GeoTex Encoder with texin=False that encodes only vertex geometry into a latent space', 'run the Encoder forward pass with verts and optional texture tensors to get latent encoding and KLDIV losses', 'review the Encoder forward method VAE reparameterization trick that samples z from mu and logstd during training', 'refactor the Encoder KLDIV loss computation to support custom divergence metrics beyond standard VAE KL', 'build a variational autoencoder image encoder with configurable inputs and layer depth using the Encoder class', 'create an Encoder instance with ninputs and size parameters to encode multi-view images into latent representations', 'run the Encoder forward pass with a batch of images and a losslist to get encodings and KLDIV losses', 'review the Encoder forward method to understand how it applies padding, downsampling, and reparameterization trick for VAE', 'refactor the Encoder channel progression logic to support custom channel growth beyond the 256 channel cap']
```

Usage

```
{'build_encoder_with_texture': 'build a GeoTex Encoder that processes vertex and texture inputs into a latent encoding using VAE reparameterization', 'build_encoder_without_texture': 'build a GeoTex Encoder with texin=False that encodes only vertex geometry into a latent space', 'run_encoder_forward_pass': 'run the Encoder forward pass with verts and optional texture tensors to get latent encoding and KLDIV losses', 'review_encoder_vae_reparameterization': 'review the Encoder forward method VAE reparameterization trick that samples z from mu and logstd during training', 'refactor_encoder_kldiv_loss': 'refactor the Encoder KLDIV loss computation to support custom divergence metrics beyond standard VAE KL'}
```

## File: facebookresearch_mvp/models/encoders/image.py

Prompts

```
['build a GeoTex Encoder that processes vertex and texture inputs into a latent encoding using VAE reparameterization', 'build a GeoTex Encoder with texin=False that encodes only vertex geometry into a latent space', 'run the Encoder forward pass with verts and optional texture tensors to get latent encoding and KLDIV losses', 'review the Encoder forward method VAE reparameterization trick that samples z from mu and logstd during training', 'refactor the Encoder KLDIV loss computation to support custom divergence metrics beyond standard VAE KL', 'build a variational autoencoder image encoder with configurable inputs and layer depth using the Encoder class', 'create an Encoder instance with ninputs and size parameters to encode multi-view images into latent representations', 'run the Encoder forward pass with a batch of images and a losslist to get encodings and KLDIV losses', 'review the Encoder forward method to understand how it applies padding, downsampling, and reparameterization trick for VAE', 'refactor the Encoder channel progression logic to support custom channel growth beyond the 256 channel cap']
```

Usage

```
{'build_VAE_encoder': 'build a variational autoencoder image encoder with configurable inputs and layer depth using the Encoder class', 'create_encoder_instance': 'create an Encoder instance with ninputs and size parameters to encode multi-view images into latent representations', 'run_encoder_forward': 'run the Encoder forward pass with a batch of images and a losslist to get encodings and KLDIV losses', 'review_Encoder_forward': 'review the Encoder forward method to understand how it applies padding, downsampling, and reparameterization trick for VAE', 'refactor_Encoder_channels': 'refactor the Encoder channel progression logic to support custom channel growth beyond the 256 channel cap'}
```

