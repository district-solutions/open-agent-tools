# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/core/models/allscaip/AllScAIP.py

Prompts

```
['build an AllScAIP backbone model with graph attention blocks and configurable transformer layers', 'build a direct force prediction head using a feedforward network on node representations', 'build an energy prediction head that aggregates per-node energy outputs with scatter reduction', 'build a gradient-based head that computes energy, forces, and stress via autograd', 'validate ASE atoms data charge and spin values against acceptable ranges for inference', 'create an AllScAIPConfigs dataclass instance with nested global, molecular graph, GNN, and regularization config objects', 'create a GlobalConfigs dataclass to set model hyperparameters like hidden size, num layers, and activation function', 'create a MolecularGraphConfigs dataclass to configure KNN graph construction, cutoff radius, and chunked graph settings', 'initialize a nested AllScAIPConfigs dataclass from a flat dictionary of keyword arguments with defaults', 'resolve a forward reference string type hint to its actual class object for dataclass field introspection', 'create a GraphAttentionData dataclass instance with atomic numbers, charge, spin, edge, and node tensors for graph attention networks', 'move a GraphAttentionData instance and all its tensor fields to a specified torch device using the to method', 'flatten a GraphAttentionData instance into a tuple of tensors using the flatten_graph_attention_data_with_spec function for pytree serialization', 'register the GraphAttentionData dataclass with torch.export for TorchScript serialization using register_dataclass', 'register a custom pytree flatten spec for GraphAttentionData with torch.fx for FX graph tracing support']
```

Usage

```
{'build_AllScAIPBackbone': 'build an AllScAIP backbone model with graph attention blocks and configurable transformer layers', 'build_AllScAIPDirectForceHead': 'build a direct force prediction head using a feedforward network on node representations', 'build_AllScAIPEnergyHead': 'build an energy prediction head that aggregates per-node energy outputs with scatter reduction', 'build_AllScAIPGradientEnergyForceStressHead': 'build a gradient-based head that computes energy, forces, and stress via autograd', 'validate_atoms_data_AllScAIPBackbone': 'validate ASE atoms data charge and spin values against acceptable ranges for inference'}
```

## File: facebookresearch_fairchem/src/fairchem/core/models/allscaip/configs.py

Prompts

```
['build an AllScAIP backbone model with graph attention blocks and configurable transformer layers', 'build a direct force prediction head using a feedforward network on node representations', 'build an energy prediction head that aggregates per-node energy outputs with scatter reduction', 'build a gradient-based head that computes energy, forces, and stress via autograd', 'validate ASE atoms data charge and spin values against acceptable ranges for inference', 'create an AllScAIPConfigs dataclass instance with nested global, molecular graph, GNN, and regularization config objects', 'create a GlobalConfigs dataclass to set model hyperparameters like hidden size, num layers, and activation function', 'create a MolecularGraphConfigs dataclass to configure KNN graph construction, cutoff radius, and chunked graph settings', 'initialize a nested AllScAIPConfigs dataclass from a flat dictionary of keyword arguments with defaults', 'resolve a forward reference string type hint to its actual class object for dataclass field introspection', 'create a GraphAttentionData dataclass instance with atomic numbers, charge, spin, edge, and node tensors for graph attention networks', 'move a GraphAttentionData instance and all its tensor fields to a specified torch device using the to method', 'flatten a GraphAttentionData instance into a tuple of tensors using the flatten_graph_attention_data_with_spec function for pytree serialization', 'register the GraphAttentionData dataclass with torch.export for TorchScript serialization using register_dataclass', 'register a custom pytree flatten spec for GraphAttentionData with torch.fx for FX graph tracing support']
```

Usage

```
{'create_AllScAIPConfigs': 'create an AllScAIPConfigs dataclass instance with nested global, molecular graph, GNN, and regularization config objects', 'create_GlobalConfigs': 'create a GlobalConfigs dataclass to set model hyperparameters like hidden size, num layers, and activation function', 'create_MolecularGraphConfigs': 'create a MolecularGraphConfigs dataclass to configure KNN graph construction, cutoff radius, and chunked graph settings', 'init_configs': 'initialize a nested AllScAIPConfigs dataclass from a flat dictionary of keyword arguments with defaults', 'resolve_type_hint': 'resolve a forward reference string type hint to its actual class object for dataclass field introspection'}
```

## File: facebookresearch_fairchem/src/fairchem/core/models/allscaip/custom_types.py

Prompts

```
['build an AllScAIP backbone model with graph attention blocks and configurable transformer layers', 'build a direct force prediction head using a feedforward network on node representations', 'build an energy prediction head that aggregates per-node energy outputs with scatter reduction', 'build a gradient-based head that computes energy, forces, and stress via autograd', 'validate ASE atoms data charge and spin values against acceptable ranges for inference', 'create an AllScAIPConfigs dataclass instance with nested global, molecular graph, GNN, and regularization config objects', 'create a GlobalConfigs dataclass to set model hyperparameters like hidden size, num layers, and activation function', 'create a MolecularGraphConfigs dataclass to configure KNN graph construction, cutoff radius, and chunked graph settings', 'initialize a nested AllScAIPConfigs dataclass from a flat dictionary of keyword arguments with defaults', 'resolve a forward reference string type hint to its actual class object for dataclass field introspection', 'create a GraphAttentionData dataclass instance with atomic numbers, charge, spin, edge, and node tensors for graph attention networks', 'move a GraphAttentionData instance and all its tensor fields to a specified torch device using the to method', 'flatten a GraphAttentionData instance into a tuple of tensors using the flatten_graph_attention_data_with_spec function for pytree serialization', 'register the GraphAttentionData dataclass with torch.export for TorchScript serialization using register_dataclass', 'register a custom pytree flatten spec for GraphAttentionData with torch.fx for FX graph tracing support']
```

Usage

```
{'create_graph_attention_data': 'create a GraphAttentionData dataclass instance with atomic numbers, charge, spin, edge, and node tensors for graph attention networks', 'move_graph_attention_data_to_device': 'move a GraphAttentionData instance and all its tensor fields to a specified torch device using the to method', 'flatten_graph_attention_data': 'flatten a GraphAttentionData instance into a tuple of tensors using the flatten_graph_attention_data_with_spec function for pytree serialization', 'register_graph_attention_data_for_torch_export': 'register the GraphAttentionData dataclass with torch.export for TorchScript serialization using register_dataclass', 'register_pytree_flatten_spec': 'register a custom pytree flatten spec for GraphAttentionData with torch.fx for FX graph tracing support'}
```

