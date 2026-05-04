# Agent Python Tools

- repo: facebookresearch/egolifter
- repo_uri: https://github.com/facebookresearch/egolifter

## File: facebookresearch_egolifter/model/networks/deform.py

Prompts

```
['build a DeformNetwork module to compute 3D Gaussian deformation from position and time tensors', 'run the DeformNetwork forward pass with position and time tensors to get deformation outputs', 'create an Embedder instance to generate frequency-based positional embeddings for input tensors', 'test the get_embedder function to return an embedding lambda and output dimension for a given multiresolution', 'review the Embedder embed method to concatenate periodic function outputs across frequency bands', 'create an xyz position encoder using a 2-layer MLP with ReLU activations on embedded coordinates', 'test the DeformNetwork decoders to verify xyz displacement, quaternion rotation, scaling, and probability outputs', 'review the DeformNetwork encoder_2 skip connection that concatenates xyz embedding and time embedding with hidden state']
```

Usage

```
{'build_DeformNetwork': 'build a DeformNetwork module to compute 3D Gaussian deformation from position and time tensors', 'run_DeformNetwork_forward': 'run the DeformNetwork forward pass with position and time tensors to get deformation outputs', 'create_Embedder': 'create an Embedder instance to generate frequency-based positional embeddings for input tensors', 'test_get_embedder': 'test the get_embedder function to return an embedding lambda and output dimension for a given multiresolution', 'review_Embedder_embed': 'review the Embedder embed method to concatenate periodic function outputs across frequency bands'}
```

## File: facebookresearch_egolifter/model/networks/deform2.py

Prompts

```
['build a DeformNetwork module to compute 3D Gaussian deformation from position and time tensors', 'run the DeformNetwork forward pass with position and time tensors to get deformation outputs', 'create an Embedder instance to generate frequency-based positional embeddings for input tensors', 'test the get_embedder function to return an embedding lambda and output dimension for a given multiresolution', 'review the Embedder embed method to concatenate periodic function outputs across frequency bands', 'create an xyz position encoder using a 2-layer MLP with ReLU activations on embedded coordinates', 'test the DeformNetwork decoders to verify xyz displacement, quaternion rotation, scaling, and probability outputs', 'review the DeformNetwork encoder_2 skip connection that concatenates xyz embedding and time embedding with hidden state']
```

Usage

```
{'build_DeformNetwork': 'build a DeformNetwork model with configurable depth, width, and multiresolution frequency encoding for 3D deformation', 'run_DeformNetwork_forward': 'run the DeformNetwork forward pass with position tensor x and time tensor t to predict deformation', 'create_DeformNetwork_encoder_xyz': 'create an xyz position encoder using a 2-layer MLP with ReLU activations on embedded coordinates', 'test_DeformNetwork_decoder_outputs': 'test the DeformNetwork decoders to verify xyz displacement, quaternion rotation, scaling, and probability outputs', 'review_DeformNetwork_skip_connections': 'review the DeformNetwork encoder_2 skip connection that concatenates xyz embedding and time embedding with hidden state'}
```

