# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/core/graph/compute.py

Prompts

```
['generate a graph representation from atomic structure data with cutoff distance and max neighbors', 'filter graph edges to keep only those where the target atom belongs to the node partition', 'compute interatomic distances with periodic boundary condition corrections from edge indices and cell offsets', 'review the generate_graph function to understand radius graph PBC version selection and edge filtering logic', 'refactor filter_edges_by_node_partition to support additional edge filtering criteria beyond node partition membership', 'build a k-nearest neighbor graph for periodic atomic structures using radius_graph_pbc with a cutoff radius', 'build an optimized grid-based k-nearest neighbor graph for periodic atomic structures using radius_graph_pbc_v2', 'test the get_max_neighbors_mask function to filter edges so each atom has at most N neighbors', 'review the canonical_pbc function that validates and normalizes periodic boundary condition tensors across a batch', 'refactor the sum_partitions function to sum values within partitions defined by cumulative index boundaries', 'build a radius graph with PBC support using NVIDIA nvalchemiops acceleration for molecular structures', 'create a nearest neighbor search using NVIDIA nvalchemiops with cutoff radius and periodic boundary conditions', 'create a neighbor search from an ASE Atoms object using NVIDIA nvalchemiops and return distances', 'test the NVIDIA accelerated radius graph generation function with batched molecular data and PBC tensors', 'review the get_neighbors_nvidia function for input validation, batched neighbor search, and max neighbor masking']
```

Usage

```
{'generate_graph_from_atomic_structure': 'generate a graph representation from atomic structure data with cutoff distance and max neighbors', 'filter_edges_by_node_partition': 'filter graph edges to keep only those where the target atom belongs to the node partition', 'compute_pbc_distances': 'compute interatomic distances with periodic boundary condition corrections from edge indices and cell offsets', 'review_generate_graph': 'review the generate_graph function to understand radius graph PBC version selection and edge filtering logic', 'refactor_filter_edges': 'refactor filter_edges_by_node_partition to support additional edge filtering criteria beyond node partition membership'}
```

## File: facebookresearch_fairchem/src/fairchem/core/graph/radius_graph_pbc.py

Prompts

```
['generate a graph representation from atomic structure data with cutoff distance and max neighbors', 'filter graph edges to keep only those where the target atom belongs to the node partition', 'compute interatomic distances with periodic boundary condition corrections from edge indices and cell offsets', 'review the generate_graph function to understand radius graph PBC version selection and edge filtering logic', 'refactor filter_edges_by_node_partition to support additional edge filtering criteria beyond node partition membership', 'build a k-nearest neighbor graph for periodic atomic structures using radius_graph_pbc with a cutoff radius', 'build an optimized grid-based k-nearest neighbor graph for periodic atomic structures using radius_graph_pbc_v2', 'test the get_max_neighbors_mask function to filter edges so each atom has at most N neighbors', 'review the canonical_pbc function that validates and normalizes periodic boundary condition tensors across a batch', 'refactor the sum_partitions function to sum values within partitions defined by cumulative index boundaries', 'build a radius graph with PBC support using NVIDIA nvalchemiops acceleration for molecular structures', 'create a nearest neighbor search using NVIDIA nvalchemiops with cutoff radius and periodic boundary conditions', 'create a neighbor search from an ASE Atoms object using NVIDIA nvalchemiops and return distances', 'test the NVIDIA accelerated radius graph generation function with batched molecular data and PBC tensors', 'review the get_neighbors_nvidia function for input validation, batched neighbor search, and max neighbor masking']
```

Usage

```
{'build_radius_graph_pbc': 'build a k-nearest neighbor graph for periodic atomic structures using radius_graph_pbc with a cutoff radius', 'build_radius_graph_pbc_v2': 'build an optimized grid-based k-nearest neighbor graph for periodic atomic structures using radius_graph_pbc_v2', 'test_get_max_neighbors_mask': 'test the get_max_neighbors_mask function to filter edges so each atom has at most N neighbors', 'review_canonical_pbc': 'review the canonical_pbc function that validates and normalizes periodic boundary condition tensors across a batch', 'refactor_sum_partitions': 'refactor the sum_partitions function to sum values within partitions defined by cumulative index boundaries'}
```

## File: facebookresearch_fairchem/src/fairchem/core/graph/radius_graph_pbc_nvidia.py

Prompts

```
['generate a graph representation from atomic structure data with cutoff distance and max neighbors', 'filter graph edges to keep only those where the target atom belongs to the node partition', 'compute interatomic distances with periodic boundary condition corrections from edge indices and cell offsets', 'review the generate_graph function to understand radius graph PBC version selection and edge filtering logic', 'refactor filter_edges_by_node_partition to support additional edge filtering criteria beyond node partition membership', 'build a k-nearest neighbor graph for periodic atomic structures using radius_graph_pbc with a cutoff radius', 'build an optimized grid-based k-nearest neighbor graph for periodic atomic structures using radius_graph_pbc_v2', 'test the get_max_neighbors_mask function to filter edges so each atom has at most N neighbors', 'review the canonical_pbc function that validates and normalizes periodic boundary condition tensors across a batch', 'refactor the sum_partitions function to sum values within partitions defined by cumulative index boundaries', 'build a radius graph with PBC support using NVIDIA nvalchemiops acceleration for molecular structures', 'create a nearest neighbor search using NVIDIA nvalchemiops with cutoff radius and periodic boundary conditions', 'create a neighbor search from an ASE Atoms object using NVIDIA nvalchemiops and return distances', 'test the NVIDIA accelerated radius graph generation function with batched molecular data and PBC tensors', 'review the get_neighbors_nvidia function for input validation, batched neighbor search, and max neighbor masking']
```

Usage

```
{'build_radius_graph_pbc_nvidia': 'build a radius graph with PBC support using NVIDIA nvalchemiops acceleration for molecular structures', 'create_get_neighbors_nvidia': 'create a nearest neighbor search using NVIDIA nvalchemiops with cutoff radius and periodic boundary conditions', 'create_get_neighbors_nvidia_atoms': 'create a neighbor search from an ASE Atoms object using NVIDIA nvalchemiops and return distances', 'test_radius_graph_pbc_nvidia': 'test the NVIDIA accelerated radius graph generation function with batched molecular data and PBC tensors', 'review_get_neighbors_nvidia': 'review the get_neighbors_nvidia function for input validation, batched neighbor search, and max neighbor masking'}
```

