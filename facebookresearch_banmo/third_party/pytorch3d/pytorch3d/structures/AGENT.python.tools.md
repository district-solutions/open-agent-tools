# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/pytorch3d/pytorch3d/structures/meshes.py

Prompts

```
['create a Meshes object from a list of vertex and face tensors for batched 3D mesh processing', 'get the packed vertex tensor of shape (sum(V_n), 3) from a Meshes object', 'offset the vertices of a Meshes object in place by a given 3D displacement tensor', 'join multiple Meshes objects into a single batched Meshes object with optional texture merging', 'join a batch of meshes into a single unified mesh with combined textures', 'create a Pointclouds object from a list of 3D point tensors with optional normals and features', 'estimate surface normals for each point in a Pointclouds batch using neighborhood analysis', 'subsample each cloud in a Pointclouds batch to at most a specified number of points', 'compute axis-aligned bounding boxes for each cloud in a Pointclouds batch', 'merge a list of Pointclouds objects into a single batched Pointclouds object', 'create a padded tensor from a list of PyTorch tensors with configurable pad size and pad value', 'transform a padded tensor into a list of tensors using optional split sizes', 'pack a list of PyTorch tensors into a single tensor along the first dimension', 'split a packed tensor into a list of tensors using specified split sizes', 'convert a padded 3D tensor into a packed tensor using split sizes or a pad value filter', 'create a Volumes object from a 5D tensor of densities with optional features and voxel size', 'get the 3D coordinate grid of a Volumes object in world or local coordinates', 'convert 3D point coordinates from world space to the local coordinate frame of a Volumes object', 'convert 3D point coordinates from the local coordinate frame to world space using a Volumes object', 'update the padded densities and features tensors of a Volumes object and return a new Volumes instance']
```

Usage

```
{'create_meshes_batch': 'create a Meshes object from a list of vertex and face tensors for batched 3D mesh processing', 'get_verts_packed': 'get the packed vertex tensor of shape (sum(V_n), 3) from a Meshes object', 'offset_mesh_vertices': 'offset the vertices of a Meshes object in place by a given 3D displacement tensor', 'join_meshes_as_batch': 'join multiple Meshes objects into a single batched Meshes object with optional texture merging', 'join_meshes_as_scene': 'join a batch of meshes into a single unified mesh with combined textures'}
```

## File: facebookresearch_banmo/third_party/pytorch3d/pytorch3d/structures/pointclouds.py

Prompts

```
['create a Meshes object from a list of vertex and face tensors for batched 3D mesh processing', 'get the packed vertex tensor of shape (sum(V_n), 3) from a Meshes object', 'offset the vertices of a Meshes object in place by a given 3D displacement tensor', 'join multiple Meshes objects into a single batched Meshes object with optional texture merging', 'join a batch of meshes into a single unified mesh with combined textures', 'create a Pointclouds object from a list of 3D point tensors with optional normals and features', 'estimate surface normals for each point in a Pointclouds batch using neighborhood analysis', 'subsample each cloud in a Pointclouds batch to at most a specified number of points', 'compute axis-aligned bounding boxes for each cloud in a Pointclouds batch', 'merge a list of Pointclouds objects into a single batched Pointclouds object', 'create a padded tensor from a list of PyTorch tensors with configurable pad size and pad value', 'transform a padded tensor into a list of tensors using optional split sizes', 'pack a list of PyTorch tensors into a single tensor along the first dimension', 'split a packed tensor into a list of tensors using specified split sizes', 'convert a padded 3D tensor into a packed tensor using split sizes or a pad value filter', 'create a Volumes object from a 5D tensor of densities with optional features and voxel size', 'get the 3D coordinate grid of a Volumes object in world or local coordinates', 'convert 3D point coordinates from world space to the local coordinate frame of a Volumes object', 'convert 3D point coordinates from the local coordinate frame to world space using a Volumes object', 'update the padded densities and features tensors of a Volumes object and return a new Volumes instance']
```

Usage

```
{'create_pointclouds_batch': 'create a Pointclouds object from a list of 3D point tensors with optional normals and features', 'estimate_normals_pointclouds': 'estimate surface normals for each point in a Pointclouds batch using neighborhood analysis', 'subsample_pointclouds': 'subsample each cloud in a Pointclouds batch to at most a specified number of points', 'get_bounding_boxes_pointclouds': 'compute axis-aligned bounding boxes for each cloud in a Pointclouds batch', 'join_pointclouds_as_batch': 'merge a list of Pointclouds objects into a single batched Pointclouds object'}
```

## File: facebookresearch_banmo/third_party/pytorch3d/pytorch3d/structures/utils.py

Prompts

```
['create a Meshes object from a list of vertex and face tensors for batched 3D mesh processing', 'get the packed vertex tensor of shape (sum(V_n), 3) from a Meshes object', 'offset the vertices of a Meshes object in place by a given 3D displacement tensor', 'join multiple Meshes objects into a single batched Meshes object with optional texture merging', 'join a batch of meshes into a single unified mesh with combined textures', 'create a Pointclouds object from a list of 3D point tensors with optional normals and features', 'estimate surface normals for each point in a Pointclouds batch using neighborhood analysis', 'subsample each cloud in a Pointclouds batch to at most a specified number of points', 'compute axis-aligned bounding boxes for each cloud in a Pointclouds batch', 'merge a list of Pointclouds objects into a single batched Pointclouds object', 'create a padded tensor from a list of PyTorch tensors with configurable pad size and pad value', 'transform a padded tensor into a list of tensors using optional split sizes', 'pack a list of PyTorch tensors into a single tensor along the first dimension', 'split a packed tensor into a list of tensors using specified split sizes', 'convert a padded 3D tensor into a packed tensor using split sizes or a pad value filter', 'create a Volumes object from a 5D tensor of densities with optional features and voxel size', 'get the 3D coordinate grid of a Volumes object in world or local coordinates', 'convert 3D point coordinates from world space to the local coordinate frame of a Volumes object', 'convert 3D point coordinates from the local coordinate frame to world space using a Volumes object', 'update the padded densities and features tensors of a Volumes object and return a new Volumes instance']
```

Usage

```
{'list_to_padded': 'create a padded tensor from a list of PyTorch tensors with configurable pad size and pad value', 'padded_to_list': 'transform a padded tensor into a list of tensors using optional split sizes', 'list_to_packed': 'pack a list of PyTorch tensors into a single tensor along the first dimension', 'packed_to_list': 'split a packed tensor into a list of tensors using specified split sizes', 'padded_to_packed': 'convert a padded 3D tensor into a packed tensor using split sizes or a pad value filter'}
```

## File: facebookresearch_banmo/third_party/pytorch3d/pytorch3d/structures/volumes.py

Prompts

```
['create a Meshes object from a list of vertex and face tensors for batched 3D mesh processing', 'get the packed vertex tensor of shape (sum(V_n), 3) from a Meshes object', 'offset the vertices of a Meshes object in place by a given 3D displacement tensor', 'join multiple Meshes objects into a single batched Meshes object with optional texture merging', 'join a batch of meshes into a single unified mesh with combined textures', 'create a Pointclouds object from a list of 3D point tensors with optional normals and features', 'estimate surface normals for each point in a Pointclouds batch using neighborhood analysis', 'subsample each cloud in a Pointclouds batch to at most a specified number of points', 'compute axis-aligned bounding boxes for each cloud in a Pointclouds batch', 'merge a list of Pointclouds objects into a single batched Pointclouds object', 'create a padded tensor from a list of PyTorch tensors with configurable pad size and pad value', 'transform a padded tensor into a list of tensors using optional split sizes', 'pack a list of PyTorch tensors into a single tensor along the first dimension', 'split a packed tensor into a list of tensors using specified split sizes', 'convert a padded 3D tensor into a packed tensor using split sizes or a pad value filter', 'create a Volumes object from a 5D tensor of densities with optional features and voxel size', 'get the 3D coordinate grid of a Volumes object in world or local coordinates', 'convert 3D point coordinates from world space to the local coordinate frame of a Volumes object', 'convert 3D point coordinates from the local coordinate frame to world space using a Volumes object', 'update the padded densities and features tensors of a Volumes object and return a new Volumes instance']
```

Usage

```
{'create_volumes_from_tensor': 'create a Volumes object from a 5D tensor of densities with optional features and voxel size', 'get_coord_grid_world_local': 'get the 3D coordinate grid of a Volumes object in world or local coordinates', 'convert_world_to_local_coords': 'convert 3D point coordinates from world space to the local coordinate frame of a Volumes object', 'convert_local_to_world_coords': 'convert 3D point coordinates from the local coordinate frame to world space using a Volumes object', 'update_padded_volumes': 'update the padded densities and features tensors of a Volumes object and return a new Volumes instance'}
```

