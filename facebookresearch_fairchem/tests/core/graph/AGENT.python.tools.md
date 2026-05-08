# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/tests/core/graph/test_atoms_to_graphs.py

Prompts

```
['convert an ASE Atoms object to an AtomicData graph with neighbor edges and cutoff radius', 'convert an ASE Atoms object to AtomicData without computing neighbor edges for inference', 'convert a molecule to AtomicData by creating a periodic box with a specified cell size', 'compute neighbor indices, distances, and cell offsets for an ASE Atoms object using pymatgen', 'reshape neighbor indices and offsets into a PyTorch edge index tensor and cell offsets', 'run pytest tests for graph generation on non-periodic molecules like water, benzene, and ammonia', 'run pytest to verify pymatgen and internal graph generation produce identical results', 'run pytest to test max_neighbors parameter limits incoming edges per atom', 'run pytest to verify cross-molecule edges appear or disappear based on cutoff distance', 'run pytest to test graph generation for complex molecules like ethyl methyl ether', 'test the get_pbc_distances function by collating AtomicData batches and verifying edge index equality', 'run the TestPBC pytest class to validate periodic boundary condition distance calculations', 'create an AtomicData object from ASE atoms using AtomicData.from_ase with max_neigh and radius parameters', 'collate a list of AtomicData objects into a batch using data_list_collater for graph computation', 'compute periodic boundary condition distances using get_pbc_distances with position, edge index, cell, and neighbor tensors', 'test the sum_partitions function that sums tensor values grouped by partition indices', 'test the generate_graph function for building atomic graphs with periodic boundary conditions and max neighbor limits', 'test the filter_edges_by_node_partition function that keeps only edges targeting atoms in a given partition', 'test the get_pbc_distances function for computing interatomic distances with periodic boundary condition offsets', 'test the radius_graph_pbc function for constructing radius-based neighbor graphs with 1D 2D or 3D periodic boundary conditions']
```

Usage

```
{'convert_ase_atoms_to_atomicdata': 'convert an ASE Atoms object to an AtomicData graph with neighbor edges and cutoff radius', 'convert_ase_atoms_without_edges': 'convert an ASE Atoms object to AtomicData without computing neighbor edges for inference', 'convert_molecule_with_cell': 'convert a molecule to AtomicData by creating a periodic box with a specified cell size', 'get_neighbors_pymatgen': 'compute neighbor indices, distances, and cell offsets for an ASE Atoms object using pymatgen', 'reshape_features_to_edge_index': 'reshape neighbor indices and offsets into a PyTorch edge index tensor and cell offsets'}
```

## File: facebookresearch_fairchem/tests/core/graph/test_graph_generation_nopbc.py

Prompts

```
['convert an ASE Atoms object to an AtomicData graph with neighbor edges and cutoff radius', 'convert an ASE Atoms object to AtomicData without computing neighbor edges for inference', 'convert a molecule to AtomicData by creating a periodic box with a specified cell size', 'compute neighbor indices, distances, and cell offsets for an ASE Atoms object using pymatgen', 'reshape neighbor indices and offsets into a PyTorch edge index tensor and cell offsets', 'run pytest tests for graph generation on non-periodic molecules like water, benzene, and ammonia', 'run pytest to verify pymatgen and internal graph generation produce identical results', 'run pytest to test max_neighbors parameter limits incoming edges per atom', 'run pytest to verify cross-molecule edges appear or disappear based on cutoff distance', 'run pytest to test graph generation for complex molecules like ethyl methyl ether', 'test the get_pbc_distances function by collating AtomicData batches and verifying edge index equality', 'run the TestPBC pytest class to validate periodic boundary condition distance calculations', 'create an AtomicData object from ASE atoms using AtomicData.from_ase with max_neigh and radius parameters', 'collate a list of AtomicData objects into a batch using data_list_collater for graph computation', 'compute periodic boundary condition distances using get_pbc_distances with position, edge index, cell, and neighbor tensors', 'test the sum_partitions function that sums tensor values grouped by partition indices', 'test the generate_graph function for building atomic graphs with periodic boundary conditions and max neighbor limits', 'test the filter_edges_by_node_partition function that keeps only edges targeting atoms in a given partition', 'test the get_pbc_distances function for computing interatomic distances with periodic boundary condition offsets', 'test the radius_graph_pbc function for constructing radius-based neighbor graphs with 1D 2D or 3D periodic boundary conditions']
```

Usage

```
{'test_nonpbc_molecule_graph_generation': 'run pytest tests for graph generation on non-periodic molecules like water, benzene, and ammonia', 'test_pymatgen_vs_internal_graph_consistency': 'run pytest to verify pymatgen and internal graph generation produce identical results', 'test_max_neighbors_enforcement': 'run pytest to test max_neighbors parameter limits incoming edges per atom', 'test_separated_systems_graph_generation': 'run pytest to verify cross-molecule edges appear or disappear based on cutoff distance', 'test_complex_geometry_graph_generation': 'run pytest to test graph generation for complex molecules like ethyl methyl ether'}
```

## File: facebookresearch_fairchem/tests/core/graph/test_pbc.py

Prompts

```
['convert an ASE Atoms object to an AtomicData graph with neighbor edges and cutoff radius', 'convert an ASE Atoms object to AtomicData without computing neighbor edges for inference', 'convert a molecule to AtomicData by creating a periodic box with a specified cell size', 'compute neighbor indices, distances, and cell offsets for an ASE Atoms object using pymatgen', 'reshape neighbor indices and offsets into a PyTorch edge index tensor and cell offsets', 'run pytest tests for graph generation on non-periodic molecules like water, benzene, and ammonia', 'run pytest to verify pymatgen and internal graph generation produce identical results', 'run pytest to test max_neighbors parameter limits incoming edges per atom', 'run pytest to verify cross-molecule edges appear or disappear based on cutoff distance', 'run pytest to test graph generation for complex molecules like ethyl methyl ether', 'test the get_pbc_distances function by collating AtomicData batches and verifying edge index equality', 'run the TestPBC pytest class to validate periodic boundary condition distance calculations', 'create an AtomicData object from ASE atoms using AtomicData.from_ase with max_neigh and radius parameters', 'collate a list of AtomicData objects into a batch using data_list_collater for graph computation', 'compute periodic boundary condition distances using get_pbc_distances with position, edge index, cell, and neighbor tensors', 'test the sum_partitions function that sums tensor values grouped by partition indices', 'test the generate_graph function for building atomic graphs with periodic boundary conditions and max neighbor limits', 'test the filter_edges_by_node_partition function that keeps only edges targeting atoms in a given partition', 'test the get_pbc_distances function for computing interatomic distances with periodic boundary condition offsets', 'test the radius_graph_pbc function for constructing radius-based neighbor graphs with 1D 2D or 3D periodic boundary conditions']
```

Usage

```
{'test_pbc_distances': 'test the get_pbc_distances function by collating AtomicData batches and verifying edge index equality', 'run_TestPBC_class': 'run the TestPBC pytest class to validate periodic boundary condition distance calculations', 'create_atomicdata_from_ase': 'create an AtomicData object from ASE atoms using AtomicData.from_ase with max_neigh and radius parameters', 'collate_atomicdata_batch': 'collate a list of AtomicData objects into a batch using data_list_collater for graph computation', 'compute_pbc_distances': 'compute periodic boundary condition distances using get_pbc_distances with position, edge index, cell, and neighbor tensors'}
```

## File: facebookresearch_fairchem/tests/core/graph/test_radius_graph.py

Prompts

```
['convert an ASE Atoms object to an AtomicData graph with neighbor edges and cutoff radius', 'convert an ASE Atoms object to AtomicData without computing neighbor edges for inference', 'convert a molecule to AtomicData by creating a periodic box with a specified cell size', 'compute neighbor indices, distances, and cell offsets for an ASE Atoms object using pymatgen', 'reshape neighbor indices and offsets into a PyTorch edge index tensor and cell offsets', 'run pytest tests for graph generation on non-periodic molecules like water, benzene, and ammonia', 'run pytest to verify pymatgen and internal graph generation produce identical results', 'run pytest to test max_neighbors parameter limits incoming edges per atom', 'run pytest to verify cross-molecule edges appear or disappear based on cutoff distance', 'run pytest to test graph generation for complex molecules like ethyl methyl ether', 'test the get_pbc_distances function by collating AtomicData batches and verifying edge index equality', 'run the TestPBC pytest class to validate periodic boundary condition distance calculations', 'create an AtomicData object from ASE atoms using AtomicData.from_ase with max_neigh and radius parameters', 'collate a list of AtomicData objects into a batch using data_list_collater for graph computation', 'compute periodic boundary condition distances using get_pbc_distances with position, edge index, cell, and neighbor tensors', 'test the sum_partitions function that sums tensor values grouped by partition indices', 'test the generate_graph function for building atomic graphs with periodic boundary conditions and max neighbor limits', 'test the filter_edges_by_node_partition function that keeps only edges targeting atoms in a given partition', 'test the get_pbc_distances function for computing interatomic distances with periodic boundary condition offsets', 'test the radius_graph_pbc function for constructing radius-based neighbor graphs with 1D 2D or 3D periodic boundary conditions']
```

Usage

```
{'test_sum_partitions': 'test the sum_partitions function that sums tensor values grouped by partition indices', 'test_generate_graph': 'test the generate_graph function for building atomic graphs with periodic boundary conditions and max neighbor limits', 'test_filter_edges_by_node_partition': 'test the filter_edges_by_node_partition function that keeps only edges targeting atoms in a given partition', 'test_get_pbc_distances': 'test the get_pbc_distances function for computing interatomic distances with periodic boundary condition offsets', 'test_radius_graph_pbc': 'test the radius_graph_pbc function for constructing radius-based neighbor graphs with 1D 2D or 3D periodic boundary conditions'}
```

