# Agent Python Tools

- repo: facebookresearch/neuralvolumes
- repo_uri: https://github.com/facebookresearch/neuralvolumes

## File: facebookresearch_neuralvolumes/models/neurvol1.py

Prompts

```
['build an Autoencoder with encoder, decoder, volsampler, colorcal, and dataset for neural volume rendering', 'run the Autoencoder forward pass with camera parameters, pixel coordinates, and optional image input', 'review the Autoencoder state_dict override that omits background parameters when estimatebg is false', 'refactor the Autoencoder raymarching loop to customize step size jitter or volume sampling behavior', 'summarize the Autoencoder forward method that performs encoding, decoding, ray marching, color correction, and loss computation', "initialize a PyTorch module's weights with Xavier uniform initialization and zero bias", 'initialize all modules in a Sequential with gain values matching their following activation functions', 'apply Xavier uniform weight initialization to a Conv or Linear layer with a given gain', 'convert a batch of axis-angle rotation vectors into 3x3 rotation matrices using Rodrigues formula', 'convert a batch of quaternion vectors into 3x3 rotation matrices for 3D transformations']
```

Usage

```
{'build_Autoencoder': 'build an Autoencoder with encoder, decoder, volsampler, colorcal, and dataset for neural volume rendering', 'run_Autoencoder_forward': 'run the Autoencoder forward pass with camera parameters, pixel coordinates, and optional image input', 'review_Autoencoder_state_dict': 'review the Autoencoder state_dict override that omits background parameters when estimatebg is false', 'refactor_Autoencoder_raymarching': 'refactor the Autoencoder raymarching loop to customize step size jitter or volume sampling behavior', 'summarize_Autoencoder_forward': 'summarize the Autoencoder forward method that performs encoding, decoding, ray marching, color correction, and loss computation'}
```

## File: facebookresearch_neuralvolumes/models/utils.py

Prompts

```
['build an Autoencoder with encoder, decoder, volsampler, colorcal, and dataset for neural volume rendering', 'run the Autoencoder forward pass with camera parameters, pixel coordinates, and optional image input', 'review the Autoencoder state_dict override that omits background parameters when estimatebg is false', 'refactor the Autoencoder raymarching loop to customize step size jitter or volume sampling behavior', 'summarize the Autoencoder forward method that performs encoding, decoding, ray marching, color correction, and loss computation', "initialize a PyTorch module's weights with Xavier uniform initialization and zero bias", 'initialize all modules in a Sequential with gain values matching their following activation functions', 'apply Xavier uniform weight initialization to a Conv or Linear layer with a given gain', 'convert a batch of axis-angle rotation vectors into 3x3 rotation matrices using Rodrigues formula', 'convert a batch of quaternion vectors into 3x3 rotation matrices for 3D transformations']
```

Usage

```
{'initmod_initialize_module': "initialize a PyTorch module's weights with Xavier uniform initialization and zero bias", 'initseq_initialize_sequence': 'initialize all modules in a Sequential with gain values matching their following activation functions', 'xavier_uniform_apply_weights': 'apply Xavier uniform weight initialization to a Conv or Linear layer with a given gain', 'rodrigues_rotation_matrix': 'convert a batch of axis-angle rotation vectors into 3x3 rotation matrices using Rodrigues formula', 'quaternion_rotation_matrix': 'convert a batch of quaternion vectors into 3x3 rotation matrices for 3D transformations'}
```

