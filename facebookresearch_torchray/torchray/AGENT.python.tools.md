# Agent Python Tools

- repo: facebookresearch/torchray
- repo_uri: https://github.com/facebookresearch/torchray

## File: facebookresearch_torchray/torchray/utils.py

Prompts

```
['read an image from file path or URL and return it as a PyTorch tensor in the [0, 1] range', 'apply a 2D Gaussian filter to smooth an image tensor with configurable sigma and padding parameters', 'spatially resample a tensor to a target size using a 2x2 transformation matrix with bilinear interpolation', 'display a batch of image tensors as a mosaic grid with individual tile scaling and configurable spacing', 'read and return the TorchRay configuration from .torchrayrc file or use default MongoDB and benchmark settings']
```

Usage

```
{'imread_load_image': 'read an image from file path or URL and return it as a PyTorch tensor in the [0, 1] range', 'imsmooth_gaussian_blur': 'apply a 2D Gaussian filter to smooth an image tensor with configurable sigma and padding parameters', 'resample_spatial_transform': 'spatially resample a tensor to a target size using a 2x2 transformation matrix with bilinear interpolation', 'imarraysc_display_mosaic': 'display a batch of image tensors as a mosaic grid with individual tile scaling and configurable spacing', 'get_config_torchray': 'read and return the TorchRay configuration from .torchrayrc file or use default MongoDB and benchmark settings'}
```

