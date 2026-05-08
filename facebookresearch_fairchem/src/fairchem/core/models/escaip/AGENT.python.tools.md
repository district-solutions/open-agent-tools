# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/core/models/escaip/EScAIP.py

Prompts

```
['build an EScAIP backbone model with configurable graph attention transformer blocks and readout layers', 'run the EScAIP backbone forward pass on AtomicData to get node and edge features', 'create an EScAIP direct force head that predicts atomic forces from edge and node features', 'create an EScAIP energy head that predicts molecular energy using global or node readouts', 'create an EScAIP gradient-based head that computes energy, forces, and stress via autograd', 'initialize an EScAIPConfigs dataclass from a flat kwargs dictionary with nested dataclass support', 'initialize a GlobalConfigs dataclass from a flat kwargs dictionary with defaults and required fields', 'resolve forward reference string type hints to actual class objects for dataclass fields', 'create a top-level EScAIPConfigs object that nests GlobalConfigs, MolecularGraphConfigs, GNN configs, and RegularizationConfigs', 'create a MolecularGraphConfigs dataclass to configure periodic boundary conditions, KNN, and distance functions', 'create a GraphAttentionData dataclass instance with tensor fields for graph attention network data', 'map a GraphAttentionData instance tensors to a specified torch device like cuda or cpu', 'flatten a GraphAttentionData instance into a tuple of tensors using a pytree spec', 'register the GraphAttentionData dataclass with torch.export for serialization with a custom type name', 'register a custom pytree flatten spec for GraphAttentionData with torch.fx for tracing support']
```

Usage

```
{'build_EScAIP_backbone': 'build an EScAIP backbone model with configurable graph attention transformer blocks and readout layers', 'run_EScAIP_backbone_forward': 'run the EScAIP backbone forward pass on AtomicData to get node and edge features', 'create_EScAIP_direct_force_head': 'create an EScAIP direct force head that predicts atomic forces from edge and node features', 'create_EScAIP_energy_head': 'create an EScAIP energy head that predicts molecular energy using global or node readouts', 'create_EScAIP_grad_energy_force_stress_head': 'create an EScAIP gradient-based head that computes energy, forces, and stress via autograd'}
```

## File: facebookresearch_fairchem/src/fairchem/core/models/escaip/configs.py

Prompts

```
['build an EScAIP backbone model with configurable graph attention transformer blocks and readout layers', 'run the EScAIP backbone forward pass on AtomicData to get node and edge features', 'create an EScAIP direct force head that predicts atomic forces from edge and node features', 'create an EScAIP energy head that predicts molecular energy using global or node readouts', 'create an EScAIP gradient-based head that computes energy, forces, and stress via autograd', 'initialize an EScAIPConfigs dataclass from a flat kwargs dictionary with nested dataclass support', 'initialize a GlobalConfigs dataclass from a flat kwargs dictionary with defaults and required fields', 'resolve forward reference string type hints to actual class objects for dataclass fields', 'create a top-level EScAIPConfigs object that nests GlobalConfigs, MolecularGraphConfigs, GNN configs, and RegularizationConfigs', 'create a MolecularGraphConfigs dataclass to configure periodic boundary conditions, KNN, and distance functions', 'create a GraphAttentionData dataclass instance with tensor fields for graph attention network data', 'map a GraphAttentionData instance tensors to a specified torch device like cuda or cpu', 'flatten a GraphAttentionData instance into a tuple of tensors using a pytree spec', 'register the GraphAttentionData dataclass with torch.export for serialization with a custom type name', 'register a custom pytree flatten spec for GraphAttentionData with torch.fx for tracing support']
```

Usage

```
{'init_configs_EScAIPConfigs': 'initialize an EScAIPConfigs dataclass from a flat kwargs dictionary with nested dataclass support', 'init_configs_GlobalConfigs': 'initialize a GlobalConfigs dataclass from a flat kwargs dictionary with defaults and required fields', 'resolve_type_hint': 'resolve forward reference string type hints to actual class objects for dataclass fields', 'create_EScAIPConfigs': 'create a top-level EScAIPConfigs object that nests GlobalConfigs, MolecularGraphConfigs, GNN configs, and RegularizationConfigs', 'create_MolecularGraphConfigs': 'create a MolecularGraphConfigs dataclass to configure periodic boundary conditions, KNN, and distance functions'}
```

## File: facebookresearch_fairchem/src/fairchem/core/models/escaip/custom_types.py

Prompts

```
['build an EScAIP backbone model with configurable graph attention transformer blocks and readout layers', 'run the EScAIP backbone forward pass on AtomicData to get node and edge features', 'create an EScAIP direct force head that predicts atomic forces from edge and node features', 'create an EScAIP energy head that predicts molecular energy using global or node readouts', 'create an EScAIP gradient-based head that computes energy, forces, and stress via autograd', 'initialize an EScAIPConfigs dataclass from a flat kwargs dictionary with nested dataclass support', 'initialize a GlobalConfigs dataclass from a flat kwargs dictionary with defaults and required fields', 'resolve forward reference string type hints to actual class objects for dataclass fields', 'create a top-level EScAIPConfigs object that nests GlobalConfigs, MolecularGraphConfigs, GNN configs, and RegularizationConfigs', 'create a MolecularGraphConfigs dataclass to configure periodic boundary conditions, KNN, and distance functions', 'create a GraphAttentionData dataclass instance with tensor fields for graph attention network data', 'map a GraphAttentionData instance tensors to a specified torch device like cuda or cpu', 'flatten a GraphAttentionData instance into a tuple of tensors using a pytree spec', 'register the GraphAttentionData dataclass with torch.export for serialization with a custom type name', 'register a custom pytree flatten spec for GraphAttentionData with torch.fx for tracing support']
```

Usage

```
{'create_GraphAttentionData': 'create a GraphAttentionData dataclass instance with tensor fields for graph attention network data', 'map_graph_attention_data_to_device': 'map a GraphAttentionData instance tensors to a specified torch device like cuda or cpu', 'flatten_graph_attention_data_with_spec': 'flatten a GraphAttentionData instance into a tuple of tensors using a pytree spec', 'register_GraphAttentionData_for_torch_export': 'register the GraphAttentionData dataclass with torch.export for serialization with a custom type name', 'register_GraphAttentionData_pytree_flatten': 'register a custom pytree flatten spec for GraphAttentionData with torch.fx for tracing support'}
```

