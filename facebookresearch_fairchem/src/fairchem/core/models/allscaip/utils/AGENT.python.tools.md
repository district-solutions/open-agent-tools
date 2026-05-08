# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/core/models/allscaip/utils/allscaip_radius_graph.py

Prompts

```
['build a biknn radius graph from an AtomicData object with configurable cutoff and soft KNN parameters', 'build radius graphs for a batch of atomic systems with position, cell, and image ID lists', 'build a biknn radius graph for a single system given positions, cell, image IDs, and cutoff', 'build a memory-efficient chunked radius graph for large systems by processing source atoms in chunks', 'compute the argsort of values within each segment using a vectorized cumsum-based approach', 'build a module that preprocesses atomic data into a GraphAttentionData object using a Bi-KNN radius graph', 'create a function that expands edge distances using Gaussian, sigmoid, or SiLU smearing basis functions', 'compute frequency vectors from edge direction tensors using spherical harmonics for neighbor attention', 'calculate bond-orientational order per node using spherical harmonics and neighbor direction vectors', 'pad a batch of molecular graphs to fixed size for torch.compile and unpad results afterward', 'build a feedforward layer with a specified hidden dimension and activation function', 'build a feedforward layer using a hidden layer multiplier to expand intermediate dimensions', 'build a feedforward layer with configurable dropout for regularization', 'build a feedforward layer with zero multiplier that returns a single linear projection', 'build a feedforward layer with custom input and output dimensions instead of hidden_dim']
```

Usage

```
{'build_biknn_radius_graph': 'build a biknn radius graph from an AtomicData object with configurable cutoff and soft KNN parameters', 'build_batched_radius_graph': 'build radius graphs for a batch of atomic systems with position, cell, and image ID lists', 'build_single_radius_graph': 'build a biknn radius graph for a single system given positions, cell, image IDs, and cutoff', 'build_chunked_radius_graph': 'build a memory-efficient chunked radius graph for large systems by processing source atoms in chunks', 'compute_segment_argsort': 'compute the argsort of values within each segment using a vectorized cumsum-based approach'}
```

## File: facebookresearch_fairchem/src/fairchem/core/models/allscaip/utils/data_preprocess.py

Prompts

```
['build a biknn radius graph from an AtomicData object with configurable cutoff and soft KNN parameters', 'build radius graphs for a batch of atomic systems with position, cell, and image ID lists', 'build a biknn radius graph for a single system given positions, cell, image IDs, and cutoff', 'build a memory-efficient chunked radius graph for large systems by processing source atoms in chunks', 'compute the argsort of values within each segment using a vectorized cumsum-based approach', 'build a module that preprocesses atomic data into a GraphAttentionData object using a Bi-KNN radius graph', 'create a function that expands edge distances using Gaussian, sigmoid, or SiLU smearing basis functions', 'compute frequency vectors from edge direction tensors using spherical harmonics for neighbor attention', 'calculate bond-orientational order per node using spherical harmonics and neighbor direction vectors', 'pad a batch of molecular graphs to fixed size for torch.compile and unpad results afterward', 'build a feedforward layer with a specified hidden dimension and activation function', 'build a feedforward layer using a hidden layer multiplier to expand intermediate dimensions', 'build a feedforward layer with configurable dropout for regularization', 'build a feedforward layer with zero multiplier that returns a single linear projection', 'build a feedforward layer with custom input and output dimensions instead of hidden_dim']
```

Usage

```
{'build_radius_graph_preprocess': 'build a module that preprocesses atomic data into a GraphAttentionData object using a Bi-KNN radius graph', 'create_edge_distance_expansion': 'create a function that expands edge distances using Gaussian, sigmoid, or SiLU smearing basis functions', 'compute_frequency_vectors': 'compute frequency vectors from edge direction tensors using spherical harmonics for neighbor attention', 'calculate_bond_orientational_order': 'calculate bond-orientational order per node using spherical harmonics and neighbor direction vectors', 'pad_and_unpad_batch': 'pad a batch of molecular graphs to fixed size for torch.compile and unpad results afterward'}
```

## File: facebookresearch_fairchem/src/fairchem/core/models/allscaip/utils/nn_utils.py

Prompts

```
['build a biknn radius graph from an AtomicData object with configurable cutoff and soft KNN parameters', 'build radius graphs for a batch of atomic systems with position, cell, and image ID lists', 'build a biknn radius graph for a single system given positions, cell, image IDs, and cutoff', 'build a memory-efficient chunked radius graph for large systems by processing source atoms in chunks', 'compute the argsort of values within each segment using a vectorized cumsum-based approach', 'build a module that preprocesses atomic data into a GraphAttentionData object using a Bi-KNN radius graph', 'create a function that expands edge distances using Gaussian, sigmoid, or SiLU smearing basis functions', 'compute frequency vectors from edge direction tensors using spherical harmonics for neighbor attention', 'calculate bond-orientational order per node using spherical harmonics and neighbor direction vectors', 'pad a batch of molecular graphs to fixed size for torch.compile and unpad results afterward', 'build a feedforward layer with a specified hidden dimension and activation function', 'build a feedforward layer using a hidden layer multiplier to expand intermediate dimensions', 'build a feedforward layer with configurable dropout for regularization', 'build a feedforward layer with zero multiplier that returns a single linear projection', 'build a feedforward layer with custom input and output dimensions instead of hidden_dim']
```

Usage

```
{'build_feedforward_layer': 'build a feedforward layer with a specified hidden dimension and activation function', 'build_feedforward_with_multiplier': 'build a feedforward layer using a hidden layer multiplier to expand intermediate dimensions', 'build_feedforward_with_dropout': 'build a feedforward layer with configurable dropout for regularization', 'build_feedforward_identity': 'build a feedforward layer with zero multiplier that returns a single linear projection', 'build_feedforward_custom_dims': 'build a feedforward layer with custom input and output dimensions instead of hidden_dim'}
```

