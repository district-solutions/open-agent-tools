# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/fairdiplomacy/models/preprocess_adjacency.py

Prompts

```
['normalize an NxN adjacency matrix with symmetric normalization for graph convolutional networks', 'preprocess a numpy adjacency matrix by adding self-loops and applying degree normalization', 'compute the D^(-1/2) * (A+I) * D^(-1/2) normalized adjacency matrix from a raw adjacency matrix', 'add identity self-loops to an adjacency matrix and normalize using the inverse square root of row sums', 'prepare an adjacency matrix for graph convolution layers by symmetrically normalizing it with numpy', 'get the full list of valid Diplomacy orders on the standard map as a sorted list', 'get a dictionary mapping each unit to its list of valid orders on the standard map', 'get a dictionary mapping each unit to its list of order vocabulary indices', 'compute alignment vectors for board locations given locs, phase flag, tokens per loc, and decoder length', 'compute the adjacency matrix for the Diplomacy map showing which locations are adjacent to each other']
```

Usage

```
{'normalize_adjacency_for_gcn': 'normalize an NxN adjacency matrix with symmetric normalization for graph convolutional networks', 'preprocess_adjacency_matrix': 'preprocess a numpy adjacency matrix by adding self-loops and applying degree normalization', 'compute_normalized_adjacency': 'compute the D^(-1/2) * (A+I) * D^(-1/2) normalized adjacency matrix from a raw adjacency matrix', 'add_self_loops_and_normalize': 'add identity self-loops to an adjacency matrix and normalize using the inverse square root of row sums', 'prepare_graph_convolution_input': 'prepare an adjacency matrix for graph convolution layers by symmetrically normalizing it with numpy'}
```

## File: facebookresearch_diplomacycicero/fairdiplomacy/models/state_space.py

Prompts

```
['normalize an NxN adjacency matrix with symmetric normalization for graph convolutional networks', 'preprocess a numpy adjacency matrix by adding self-loops and applying degree normalization', 'compute the D^(-1/2) * (A+I) * D^(-1/2) normalized adjacency matrix from a raw adjacency matrix', 'add identity self-loops to an adjacency matrix and normalize using the inverse square root of row sums', 'prepare an adjacency matrix for graph convolution layers by symmetrically normalizing it with numpy', 'get the full list of valid Diplomacy orders on the standard map as a sorted list', 'get a dictionary mapping each unit to its list of valid orders on the standard map', 'get a dictionary mapping each unit to its list of order vocabulary indices', 'compute alignment vectors for board locations given locs, phase flag, tokens per loc, and decoder length', 'compute the adjacency matrix for the Diplomacy map showing which locations are adjacent to each other']
```

Usage

```
{'get_order_vocabulary': 'get the full list of valid Diplomacy orders on the standard map as a sorted list', 'get_order_vocabulary_by_unit': 'get a dictionary mapping each unit to its list of valid orders on the standard map', 'get_order_vocabulary_idxs_by_unit': 'get a dictionary mapping each unit to its list of order vocabulary indices', 'get_board_alignments': 'compute alignment vectors for board locations given locs, phase flag, tokens per loc, and decoder length', 'get_adjacency_matrix': 'compute the adjacency matrix for the Diplomacy map showing which locations are adjacent to each other'}
```

