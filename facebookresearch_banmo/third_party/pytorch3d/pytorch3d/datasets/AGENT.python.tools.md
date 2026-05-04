# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/pytorch3d/pytorch3d/datasets/shapenet_base.py

Prompts

```
['render ShapeNet 3D models to images by model_ids, categories, or dataset indices using HardPhongShader', 'load an OBJ model file into vertices, face indices, and texture atlas tensors via load_obj', 'get the synset_id and model_id dictionary for a given dataset index', 'resolve model_ids, categories, sample_nums, or idxs into valid dataset indices for rendering', 'randomly sample a number of model indices from a given ShapeNet category or the entire dataset', 'collate a list of dictionaries with verts and faces into a single batched Meshes object for a PyTorch DataLoader', 'create a collated dictionary from a list of object dictionaries grouping values by key', 'build a Meshes object from verts, faces, and optional TexturesAtlas in a collated batch', 'review the collate_batched_meshes function to understand how it merges batch dictionaries into Meshes', 'test the collate_batched_meshes function with an empty or None batch to verify it returns None']
```

Usage

```
{'render_shapenet_models': 'render ShapeNet 3D models to images by model_ids, categories, or dataset indices using HardPhongShader', 'load_mesh_from_obj': 'load an OBJ model file into vertices, face indices, and texture atlas tensors via load_obj', 'get_item_ids_by_index': 'get the synset_id and model_id dictionary for a given dataset index', 'handle_render_inputs': 'resolve model_ids, categories, sample_nums, or idxs into valid dataset indices for rendering', 'sample_idxs_from_category': 'randomly sample a number of model indices from a given ShapeNet category or the entire dataset'}
```

## File: facebookresearch_banmo/third_party/pytorch3d/pytorch3d/datasets/utils.py

Prompts

```
['render ShapeNet 3D models to images by model_ids, categories, or dataset indices using HardPhongShader', 'load an OBJ model file into vertices, face indices, and texture atlas tensors via load_obj', 'get the synset_id and model_id dictionary for a given dataset index', 'resolve model_ids, categories, sample_nums, or idxs into valid dataset indices for rendering', 'randomly sample a number of model indices from a given ShapeNet category or the entire dataset', 'collate a list of dictionaries with verts and faces into a single batched Meshes object for a PyTorch DataLoader', 'create a collated dictionary from a list of object dictionaries grouping values by key', 'build a Meshes object from verts, faces, and optional TexturesAtlas in a collated batch', 'review the collate_batched_meshes function to understand how it merges batch dictionaries into Meshes', 'test the collate_batched_meshes function with an empty or None batch to verify it returns None']
```

Usage

```
{'collate_mesh_batch_for_dataloader': 'collate a list of dictionaries with verts and faces into a single batched Meshes object for a PyTorch DataLoader', 'create_collated_dict_from_batch': 'create a collated dictionary from a list of object dictionaries grouping values by key', 'build_meshes_with_textures': 'build a Meshes object from verts, faces, and optional TexturesAtlas in a collated batch', 'review_collate_batched_meshes': 'review the collate_batched_meshes function to understand how it merges batch dictionaries into Meshes', 'test_collate_empty_batch': 'test the collate_batched_meshes function with an empty or None batch to verify it returns None'}
```

