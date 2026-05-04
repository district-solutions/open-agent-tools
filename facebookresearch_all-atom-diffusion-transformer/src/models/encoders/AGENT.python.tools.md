# Agent Python Tools

- repo: facebookresearch/all-atom-diffusion-transformer
- repo_uri: https://github.com/facebookresearch/all-atom-diffusion-transformer

## File: facebookresearch_all-atom-diffusion-transformer/src/models/encoders/equiformer.py

Prompts

```
['build an EquiformerEncoder with configurable num_layers, sphere_channels, and lmax_list for equivariant crystal structure encoding', 'run the EquiformerEncoder forward pass on a batch object with atom_types, pos, frac_coords, cell, and num_atoms', 'create a GaussianSmearing RBF distance expansion module with configurable start, stop, and num_gaussians parameters', 'generate a radial cutoff graph with periodic boundary conditions using generate_graph for a batch of crystal structures', 'review the EquiformerEncoder no_weight_decay method to identify parameters excluded from weight decay during optimization', 'create a TransformerEncoder with custom d_model, nhead, and num_layers for atom diffusion', 'run the TransformerEncoder forward pass on a batch of atom types and coordinates', 'build sine and cosine positional embeddings from token indices using get_index_embedding', 'review the TransformerEncoder init to customize atom type, position, and fractional coordinate embedders', 'test get_index_embedding to verify positional embedding shapes match expected dimensions']
```

Usage

```
{'build_equiformer_encoder': 'build an EquiformerEncoder with configurable num_layers, sphere_channels, and lmax_list for equivariant crystal structure encoding', 'run_equiformer_forward': 'run the EquiformerEncoder forward pass on a batch object with atom_types, pos, frac_coords, cell, and num_atoms', 'create_gaussian_smearing': 'create a GaussianSmearing RBF distance expansion module with configurable start, stop, and num_gaussians parameters', 'generate_graph_pbc': 'generate a radial cutoff graph with periodic boundary conditions using generate_graph for a batch of crystal structures', 'review_no_weight_decay': 'review the EquiformerEncoder no_weight_decay method to identify parameters excluded from weight decay during optimization'}
```

## File: facebookresearch_all-atom-diffusion-transformer/src/models/encoders/transformer.py

Prompts

```
['build an EquiformerEncoder with configurable num_layers, sphere_channels, and lmax_list for equivariant crystal structure encoding', 'run the EquiformerEncoder forward pass on a batch object with atom_types, pos, frac_coords, cell, and num_atoms', 'create a GaussianSmearing RBF distance expansion module with configurable start, stop, and num_gaussians parameters', 'generate a radial cutoff graph with periodic boundary conditions using generate_graph for a batch of crystal structures', 'review the EquiformerEncoder no_weight_decay method to identify parameters excluded from weight decay during optimization', 'create a TransformerEncoder with custom d_model, nhead, and num_layers for atom diffusion', 'run the TransformerEncoder forward pass on a batch of atom types and coordinates', 'build sine and cosine positional embeddings from token indices using get_index_embedding', 'review the TransformerEncoder init to customize atom type, position, and fractional coordinate embedders', 'test get_index_embedding to verify positional embedding shapes match expected dimensions']
```

Usage

```
{'create_transformer_encoder': 'create a TransformerEncoder with custom d_model, nhead, and num_layers for atom diffusion', 'run_transformer_forward': 'run the TransformerEncoder forward pass on a batch of atom types and coordinates', 'build_index_embedding': 'build sine and cosine positional embeddings from token indices using get_index_embedding', 'review_transformer_encoder_init': 'review the TransformerEncoder init to customize atom type, position, and fractional coordinate embedders', 'test_get_index_embedding': 'test get_index_embedding to verify positional embedding shapes match expected dimensions'}
```

