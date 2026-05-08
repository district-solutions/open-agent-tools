# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/tests/core/models/escaip/test_escaip_forward.py

Prompts

```
['test the EScAIP model compiled vs non-compiled forward pass on GPU for energy forces and stress', 'test the EScAIP model forward pass against fixed results to verify deterministic output on GPU', 'create an EScAIP backbone model with configurable cutoff radius and torch compile options', 'create a full EScAIP model with gradient energy force stress head for molecular property prediction', 'create an EScAIP backbone configuration dictionary with attention normalization and embedding size settings']
```

Usage

```
{'test_compile_full_gpu': 'test the EScAIP model compiled vs non-compiled forward pass on GPU for energy forces and stress', 'test_fixed_forward_full_gpu': 'test the EScAIP model forward pass against fixed results to verify deterministic output on GPU', 'create_get_escaip_backbone': 'create an EScAIP backbone model with configurable cutoff radius and torch compile options', 'create_get_escaip_full': 'create a full EScAIP model with gradient energy force stress head for molecular property prediction', 'create_get_backbone_config': 'create an EScAIP backbone configuration dictionary with attention normalization and embedding size settings'}
```

