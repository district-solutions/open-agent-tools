# Agent Python Tools

- repo: facebookresearch/metamorph
- repo_uri: https://github.com/facebookresearch/metamorph

## File: facebookresearch_metamorph/metamorph/model/multimodal_projector/builder.py

Prompts

```
['build a linear vision projector that maps mm_hidden_size to hidden_size using build_vision_projector', 'build an MLP vision projector with N GELU layers using build_vision_projector with mlpNx_gelu type', 'build an identity vision projector that passes features through unchanged using build_vision_projector', 'create an IdentityMap module that returns input unchanged and exposes an mm_projector_type config property', 'create a SimpleResBlock module with LayerNorm and a Linear-GELU-Linear residual projection path']
```

Usage

```
{'build_vision_projector_linear': 'build a linear vision projector that maps mm_hidden_size to hidden_size using build_vision_projector', 'build_vision_projector_mlp_gelu': 'build an MLP vision projector with N GELU layers using build_vision_projector with mlpNx_gelu type', 'build_vision_projector_identity': 'build an identity vision projector that passes features through unchanged using build_vision_projector', 'create_identity_map_module': 'create an IdentityMap module that returns input unchanged and exposes an mm_projector_type config property', 'create_simple_resblock_module': 'create a SimpleResBlock module with LayerNorm and a Linear-GELU-Linear residual projection path'}
```

