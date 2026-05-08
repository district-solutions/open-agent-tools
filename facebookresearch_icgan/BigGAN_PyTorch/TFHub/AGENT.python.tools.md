# Agent Python Tools

- repo: facebookresearch/icgan
- repo_uri: https://github.com/facebookresearch/ic_gan

## File: facebookresearch_icgan/BigGAN_PyTorch/TFHub/biggan_v1.py

Prompts

```
['create a Generator128 model to generate 128x128 images from latent codes and class embeddings', 'create a Generator256 model to generate 256x256 images from latent codes and class embeddings', 'create a Discriminator model to classify images and compute class-wise matching scores', 'generate truncated normal latent vectors for BigGAN sampling using truncated_z_sample', 'wrap a PyTorch module with SpectralNorm to normalize weights by their largest singular value', 'convert BigGAN TFHub weights to PyTorch for resolution 128, 256, or 512', 'dump TFHub BigGAN module weights to an intermediate HDF5 file for reuse', 'load TensorFlow Hub BigGAN generator weights into a PyTorch state dict', 'convert v1 BigGAN state dict to the main BigGAN PyTorch format', 'generate sample images from a pretrained BigGAN PyTorch model and save to file']
```

Usage

```
{'create_generator_128': 'create a Generator128 model to generate 128x128 images from latent codes and class embeddings', 'create_generator_256': 'create a Generator256 model to generate 256x256 images from latent codes and class embeddings', 'create_discriminator': 'create a Discriminator model to classify images and compute class-wise matching scores', 'generate_truncated_z_samples': 'generate truncated normal latent vectors for BigGAN sampling using truncated_z_sample', 'apply_spectral_norm': 'wrap a PyTorch module with SpectralNorm to normalize weights by their largest singular value'}
```

## File: facebookresearch_icgan/BigGAN_PyTorch/TFHub/converter.py

Prompts

```
['create a Generator128 model to generate 128x128 images from latent codes and class embeddings', 'create a Generator256 model to generate 256x256 images from latent codes and class embeddings', 'create a Discriminator model to classify images and compute class-wise matching scores', 'generate truncated normal latent vectors for BigGAN sampling using truncated_z_sample', 'wrap a PyTorch module with SpectralNorm to normalize weights by their largest singular value', 'convert BigGAN TFHub weights to PyTorch for resolution 128, 256, or 512', 'dump TFHub BigGAN module weights to an intermediate HDF5 file for reuse', 'load TensorFlow Hub BigGAN generator weights into a PyTorch state dict', 'convert v1 BigGAN state dict to the main BigGAN PyTorch format', 'generate sample images from a pretrained BigGAN PyTorch model and save to file']
```

Usage

```
{'convert_biggan_tfhub_to_pytorch': 'convert BigGAN TFHub weights to PyTorch for resolution 128, 256, or 512', 'dump_tfhub_to_hdf5': 'dump TFHub BigGAN module weights to an intermediate HDF5 file for reuse', 'TFHub2Pytorch_load_generator': 'load TensorFlow Hub BigGAN generator weights into a PyTorch state dict', 'convert_from_v1': 'convert v1 BigGAN state dict to the main BigGAN PyTorch format', 'generate_sample': 'generate sample images from a pretrained BigGAN PyTorch model and save to file'}
```

