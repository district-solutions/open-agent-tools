# Agent Python Tools

- repo: facebookresearch/mvp
- repo_uri: https://github.com/facebookresearch/mvp

## File: facebookresearch_mvp/models/utils.py

Prompts

```
["initialize a PyTorch module's weights using Xavier uniform initialization with optional gain scaling", 'initialize a sequence of modules with proper gain values based on their following activation functions', 'create a weight-normalized linear layer that normalizes weights by their L2 norm during forward pass', 'create a transposed convolution layer with equalized learning rate, optional demodulation, and adaptive instance modulation', 'convert between rotation matrices and axis-angle representations using Rodrigues formula for 3D rotations', 'build a volumetric autoencoder with encoder, decoder, and raymarcher components for 3D reconstruction', 'run compute_raydirs_ref to compute normalized ray directions from pixel coordinates and camera parameters', 'run compute_rmbounds to compute ray marching start and end bounds for a volume', 'review the Autoencoder forward pass that encodes inputs, decodes volumes, and raymarches to render images', 'test the Autoencoder initialization with dataset statistics, encoder, decoder, and raymarcher components']
```

Usage

```
{'init_module_xavier': "initialize a PyTorch module's weights using Xavier uniform initialization with optional gain scaling", 'init_sequence_blockwise': 'initialize a sequence of modules with proper gain values based on their following activation functions', 'create_weight_norm_linear': 'create a weight-normalized linear layer that normalizes weights by their L2 norm during forward pass', 'create_equalized_lr_conv_transpose': 'create a transposed convolution layer with equalized learning rate, optional demodulation, and adaptive instance modulation', 'convert_rotation_axis_angle': 'convert between rotation matrices and axis-angle representations using Rodrigues formula for 3D rotations'}
```

## File: facebookresearch_mvp/models/volumetric.py

Prompts

```
["initialize a PyTorch module's weights using Xavier uniform initialization with optional gain scaling", 'initialize a sequence of modules with proper gain values based on their following activation functions', 'create a weight-normalized linear layer that normalizes weights by their L2 norm during forward pass', 'create a transposed convolution layer with equalized learning rate, optional demodulation, and adaptive instance modulation', 'convert between rotation matrices and axis-angle representations using Rodrigues formula for 3D rotations', 'build a volumetric autoencoder with encoder, decoder, and raymarcher components for 3D reconstruction', 'run compute_raydirs_ref to compute normalized ray directions from pixel coordinates and camera parameters', 'run compute_rmbounds to compute ray marching start and end bounds for a volume', 'review the Autoencoder forward pass that encodes inputs, decodes volumes, and raymarches to render images', 'test the Autoencoder initialization with dataset statistics, encoder, decoder, and raymarcher components']
```

Usage

```
{'build_volumetric_autoencoder': 'build a volumetric autoencoder with encoder, decoder, and raymarcher components for 3D reconstruction', 'run_compute_raydirs_ref': 'run compute_raydirs_ref to compute normalized ray directions from pixel coordinates and camera parameters', 'run_compute_rmbounds': 'run compute_rmbounds to compute ray marching start and end bounds for a volume', 'review_Autoencoder_forward': 'review the Autoencoder forward pass that encodes inputs, decodes volumes, and raymarches to render images', 'test_Autoencoder_init': 'test the Autoencoder initialization with dataset statistics, encoder, decoder, and raymarcher components'}
```

