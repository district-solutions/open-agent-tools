# Agent Python Tools

- repo: facebookresearch/pytorch3d
- repo_uri: https://github.com/facebookresearch/pytorch3d.git

## File: facebookresearch_pytorch3d/pytorch3d/datasets/shapenet_base.py

Prompts

```
['render 3D ShapeNet mesh models to images using a configurable camera and shader', 'load an OBJ mesh file and return vertices, face indices, and texture atlas tensors', 'get the synset_id and model_id dictionary for a given dataset index', 'resolve model_ids, categories, or sample_nums into a list of valid dataset indices', 'sample random model indices from a given ShapeNet category or the entire dataset', 'collate a list of dictionaries with verts and faces into a single Meshes batch', 'collate batched mesh dictionaries that include textures atlas data into a Meshes object', 'use collate_batched_meshes as a collate_fn for a torch DataLoader to return Meshes objects', 'handle an empty or None batch by returning None from collate_batched_meshes', 'collate a batch of dictionaries without verts or faces keys and get no mesh object']
```

Usage

```
{'render_shapenet_models': 'render 3D ShapeNet mesh models to images using a configurable camera and shader', 'load_mesh_from_obj': 'load an OBJ mesh file and return vertices, face indices, and texture atlas tensors', 'get_item_ids_by_index': 'get the synset_id and model_id dictionary for a given dataset index', 'handle_render_inputs': 'resolve model_ids, categories, or sample_nums into a list of valid dataset indices', 'sample_idxs_from_category': 'sample random model indices from a given ShapeNet category or the entire dataset'}
```

## File: facebookresearch_pytorch3d/pytorch3d/datasets/utils.py

Prompts

```
['render 3D ShapeNet mesh models to images using a configurable camera and shader', 'load an OBJ mesh file and return vertices, face indices, and texture atlas tensors', 'get the synset_id and model_id dictionary for a given dataset index', 'resolve model_ids, categories, or sample_nums into a list of valid dataset indices', 'sample random model indices from a given ShapeNet category or the entire dataset', 'collate a list of dictionaries with verts and faces into a single Meshes batch', 'collate batched mesh dictionaries that include textures atlas data into a Meshes object', 'use collate_batched_meshes as a collate_fn for a torch DataLoader to return Meshes objects', 'handle an empty or None batch by returning None from collate_batched_meshes', 'collate a batch of dictionaries without verts or faces keys and get no mesh object']
```

Usage

```
{'collate_batched_meshes_basic': 'collate a list of dictionaries with verts and faces into a single Meshes batch', 'collate_batched_meshes_with_textures': 'collate batched mesh dictionaries that include textures atlas data into a Meshes object', 'collate_batched_meshes_dataloader': 'use collate_batched_meshes as a collate_fn for a torch DataLoader to return Meshes objects', 'collate_batched_meshes_empty_batch': 'handle an empty or None batch by returning None from collate_batched_meshes', 'collate_batched_meshes_no_mesh_keys': 'collate a batch of dictionaries without verts or faces keys and get no mesh object'}
```

