# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/tests/core/common/parallelism/test_graph_partition.py

Prompts

```
['test the PartitionStrategy enum values and string parsing for index_split and spatial strategies', 'test partition_atoms_index_split to assign atoms to ranks using contiguous index-based splitting across devices', 'test partition_atoms_spatial to assign atoms to ranks using Morton Z-order curve for spatial locality', 'test that spatial partitioning groups nearby atoms into the same rank for better locality', 'test that both index_split and spatial partitioning produce balanced workloads across all ranks']
```

Usage

```
{'test_partition_strategy_enum': 'test the PartitionStrategy enum values and string parsing for index_split and spatial strategies', 'test_partition_atoms_index_split': 'test partition_atoms_index_split to assign atoms to ranks using contiguous index-based splitting across devices', 'test_partition_atoms_spatial': 'test partition_atoms_spatial to assign atoms to ranks using Morton Z-order curve for spatial locality', 'test_spatial_locality': 'test that spatial partitioning groups nearby atoms into the same rank for better locality', 'test_balanced_partitioning': 'test that both index_split and spatial partitioning produce balanced workloads across all ranks'}
```

