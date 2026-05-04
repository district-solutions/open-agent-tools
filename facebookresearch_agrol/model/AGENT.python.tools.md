# Agent Python Tools

- repo: facebookresearch/agrol
- repo_uri: https://github.com/facebookresearch/agrol

## File: facebookresearch_agrol/model/meta_model.py

Prompts

```
['build a MetaModel PyTorch module with configurable latent dimension, num_layers, and sparse_dim for motion diffusion', 'run the MetaModel forward pass with input features, timesteps, and sparse embeddings to get output predictions', 'create a TimestepEmbeding module that generates sinusoidal positional encodings for diffusion timestep embeddings', 'test the MetaModel mask_cond_sparse method to conditionally zero out sparse embeddings during training', 'review the MetaModel architecture combining DiffMLP backbone with input sparse and output linear processing layers', 'build a DiffMLP network with configurable latent dimension, sequence length, and number of layers for motion processing', 'build a PureMLP network with custom input and output dimensions for direct motion feature transformation', 'create an MLPblock layer with optional embedding support and configurable dimension and sequence parameters', 'create a BaseMLP stack of MLPblock layers with configurable depth and embedding support', 'review the DiffMLP forward pass that processes motion input with embedding through the motion MLP']
```

Usage

```
{'build_MetaModel': 'build a MetaModel PyTorch module with configurable latent dimension, num_layers, and sparse_dim for motion diffusion', 'run_MetaModel_forward': 'run the MetaModel forward pass with input features, timesteps, and sparse embeddings to get output predictions', 'create_TimestepEmbeding': 'create a TimestepEmbeding module that generates sinusoidal positional encodings for diffusion timestep embeddings', 'test_mask_cond_sparse': 'test the MetaModel mask_cond_sparse method to conditionally zero out sparse embeddings during training', 'review_MetaModel_architecture': 'review the MetaModel architecture combining DiffMLP backbone with input sparse and output linear processing layers'}
```

## File: facebookresearch_agrol/model/networks.py

Prompts

```
['build a MetaModel PyTorch module with configurable latent dimension, num_layers, and sparse_dim for motion diffusion', 'run the MetaModel forward pass with input features, timesteps, and sparse embeddings to get output predictions', 'create a TimestepEmbeding module that generates sinusoidal positional encodings for diffusion timestep embeddings', 'test the MetaModel mask_cond_sparse method to conditionally zero out sparse embeddings during training', 'review the MetaModel architecture combining DiffMLP backbone with input sparse and output linear processing layers', 'build a DiffMLP network with configurable latent dimension, sequence length, and number of layers for motion processing', 'build a PureMLP network with custom input and output dimensions for direct motion feature transformation', 'create an MLPblock layer with optional embedding support and configurable dimension and sequence parameters', 'create a BaseMLP stack of MLPblock layers with configurable depth and embedding support', 'review the DiffMLP forward pass that processes motion input with embedding through the motion MLP']
```

Usage

```
{'build_diffmlp_network': 'build a DiffMLP network with configurable latent dimension, sequence length, and number of layers for motion processing', 'build_puremlp_network': 'build a PureMLP network with custom input and output dimensions for direct motion feature transformation', 'create_mlpblock_layer': 'create an MLPblock layer with optional embedding support and configurable dimension and sequence parameters', 'create_basemlp_stack': 'create a BaseMLP stack of MLPblock layers with configurable depth and embedding support', 'review_diffmlp_forward': 'review the DiffMLP forward pass that processes motion input with embedding through the motion MLP'}
```

