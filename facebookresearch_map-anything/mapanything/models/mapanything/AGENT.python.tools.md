# Agent Python Tools

- repo: facebookresearch/map-anything
- repo_uri: https://github.com/facebookresearch/map-anything

## File: facebookresearch_map-anything/mapanything/models/mapanything/ablations.py

Prompts

```
['build a MapAnythingAblations multi-view model with encoder, info sharing transformer, and prediction head configs', 'run a forward pass on a list of view dicts to predict 3D pointmaps and camera poses', 'initialize a multi-view attention transformer with cross, global, or alternating attention and optional RoPE encoding', 'encode and fuse ray directions, depths, camera quaternions, and translations into image encoder features', 'load pretrained MapAnything weights from a checkpoint file for all or specific submodules', 'run the MapAnything model infer method to predict 3D pointmaps, depth, and camera poses from input images', 'run the MapAnything model forward pass to encode views and produce scene representations with optional geometric inputs', 'build a MapAnything model instance by providing encoder, info sharing, prediction head, and geometric input configs', 'run the downstream prediction heads to produce dense outputs, pose outputs, and scale predictions from transformer features', 'review the MapAnything model initialization to understand encoder factory, multi-view transformer, and adaptor setup', 'build a ModularDUSt3R model with encoder, info sharing transformer, and prediction head configs', 'run the ModularDUSt3R forward pass on two view dicts containing image tensors', 'encode two image batches through the ViT encoder using _encode_image_pairs method', 'encode symmetrized image pairs for both view orderings using _encode_symmetrized method', 'run the downstream prediction head on decoded features using _downstream_head method']
```

Usage

```
{'build_MapAnythingAblations_model': 'build a MapAnythingAblations multi-view model with encoder, info sharing transformer, and prediction head configs', 'run_forward_pass': 'run a forward pass on a list of view dicts to predict 3D pointmaps and camera poses', 'initialize_info_sharing_transformer': 'initialize a multi-view attention transformer with cross, global, or alternating attention and optional RoPE encoding', 'encode_and_fuse_geometric_inputs': 'encode and fuse ray directions, depths, camera quaternions, and translations into image encoder features', 'load_pretrained_weights': 'load pretrained MapAnything weights from a checkpoint file for all or specific submodules'}
```

## File: facebookresearch_map-anything/mapanything/models/mapanything/model.py

Prompts

```
['build a MapAnythingAblations multi-view model with encoder, info sharing transformer, and prediction head configs', 'run a forward pass on a list of view dicts to predict 3D pointmaps and camera poses', 'initialize a multi-view attention transformer with cross, global, or alternating attention and optional RoPE encoding', 'encode and fuse ray directions, depths, camera quaternions, and translations into image encoder features', 'load pretrained MapAnything weights from a checkpoint file for all or specific submodules', 'run the MapAnything model infer method to predict 3D pointmaps, depth, and camera poses from input images', 'run the MapAnything model forward pass to encode views and produce scene representations with optional geometric inputs', 'build a MapAnything model instance by providing encoder, info sharing, prediction head, and geometric input configs', 'run the downstream prediction heads to produce dense outputs, pose outputs, and scale predictions from transformer features', 'review the MapAnything model initialization to understand encoder factory, multi-view transformer, and adaptor setup', 'build a ModularDUSt3R model with encoder, info sharing transformer, and prediction head configs', 'run the ModularDUSt3R forward pass on two view dicts containing image tensors', 'encode two image batches through the ViT encoder using _encode_image_pairs method', 'encode symmetrized image pairs for both view orderings using _encode_symmetrized method', 'run the downstream prediction head on decoded features using _downstream_head method']
```

Usage

```
{'run_MapAnything_infer': 'run the MapAnything model infer method to predict 3D pointmaps, depth, and camera poses from input images', 'run_MapAnything_forward': 'run the MapAnything model forward pass to encode views and produce scene representations with optional geometric inputs', 'build_MapAnything_model': 'build a MapAnything model instance by providing encoder, info sharing, prediction head, and geometric input configs', 'run_MapAnything_downstream_head': 'run the downstream prediction heads to produce dense outputs, pose outputs, and scale predictions from transformer features', 'review_MapAnything_initialization': 'review the MapAnything model initialization to understand encoder factory, multi-view transformer, and adaptor setup'}
```

## File: facebookresearch_map-anything/mapanything/models/mapanything/modular_dust3r.py

Prompts

```
['build a MapAnythingAblations multi-view model with encoder, info sharing transformer, and prediction head configs', 'run a forward pass on a list of view dicts to predict 3D pointmaps and camera poses', 'initialize a multi-view attention transformer with cross, global, or alternating attention and optional RoPE encoding', 'encode and fuse ray directions, depths, camera quaternions, and translations into image encoder features', 'load pretrained MapAnything weights from a checkpoint file for all or specific submodules', 'run the MapAnything model infer method to predict 3D pointmaps, depth, and camera poses from input images', 'run the MapAnything model forward pass to encode views and produce scene representations with optional geometric inputs', 'build a MapAnything model instance by providing encoder, info sharing, prediction head, and geometric input configs', 'run the downstream prediction heads to produce dense outputs, pose outputs, and scale predictions from transformer features', 'review the MapAnything model initialization to understand encoder factory, multi-view transformer, and adaptor setup', 'build a ModularDUSt3R model with encoder, info sharing transformer, and prediction head configs', 'run the ModularDUSt3R forward pass on two view dicts containing image tensors', 'encode two image batches through the ViT encoder using _encode_image_pairs method', 'encode symmetrized image pairs for both view orderings using _encode_symmetrized method', 'run the downstream prediction head on decoded features using _downstream_head method']
```

Usage

```
{'build_ModularDUSt3R': 'build a ModularDUSt3R model with encoder, info sharing transformer, and prediction head configs', 'run_forward_ModularDUSt3R': 'run the ModularDUSt3R forward pass on two view dicts containing image tensors', 'encode_image_pairs_ModularDUSt3R': 'encode two image batches through the ViT encoder using _encode_image_pairs method', 'encode_symmetrized_ModularDUSt3R': 'encode symmetrized image pairs for both view orderings using _encode_symmetrized method', 'run_downstream_head_ModularDUSt3R': 'run the downstream prediction head on decoded features using _downstream_head method'}
```

