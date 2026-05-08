# Agent Python Tools

- repo: facebookresearch/pytorch3d
- repo_uri: https://github.com/facebookresearch/pytorch3d.git

## File: facebookresearch_pytorch3d/pytorch3d/structures/meshes.py

Prompts

```
['create a Meshes object from a list of vertex and face tensors for a batch of triangulated meshes', 'get the packed representation of vertices as a single tensor of shape sum(V_n) by 3', 'offset the vertices of a Meshes object by a given tensor of offsets in place or out of place', 'scale the vertices of a Meshes object by a scalar or per-mesh scale factor', 'merge multiple Meshes objects into a single batched Meshes object with optional texture joining', 'create a Pointclouds object from a list of tensors with shape (num_points, 3)', 'subsample each cloud in a Pointclouds batch to at most max_points points', 'estimate normals for each point in a Pointclouds batch using neighborhood size', 'join a list of Pointclouds objects into a single batched Pointclouds object', 'compute axis-aligned bounding boxes for each cloud in a Pointclouds batch', 'create a padded tensor from a list of variable-sized PyTorch tensors with a specified pad value', 'convert a padded tensor back into a list of tensors using split sizes to trim padding', 'pack a list of tensors into a single concatenated tensor with index mapping metadata', 'split a packed tensor back into a list of tensors using specified split sizes', 'convert a padded 3D tensor into a packed tensor by removing padding using split sizes or a pad value', 'create a Volumes object from a 5D density tensor with optional features and voxel size', 'create a Volumes object from a list of 4D density tensors with varying spatial sizes', 'convert 3D world coordinates to local volume coordinates using the Volumes world_to_local_coords method', 'convert 3D local volume coordinates to world coordinates using the Volumes local_to_world_coords method', 'get the 3D coordinate grid of a volume in local or world coordinates using get_coord_grid']
```

Usage

```
{'create_meshes_batch': 'create a Meshes object from a list of vertex and face tensors for a batch of triangulated meshes', 'get_verts_packed': 'get the packed representation of vertices as a single tensor of shape sum(V_n) by 3', 'offset_mesh_vertices': 'offset the vertices of a Meshes object by a given tensor of offsets in place or out of place', 'scale_mesh_vertices': 'scale the vertices of a Meshes object by a scalar or per-mesh scale factor', 'join_meshes_as_batch': 'merge multiple Meshes objects into a single batched Meshes object with optional texture joining'}
```

## File: facebookresearch_pytorch3d/pytorch3d/structures/pointclouds.py

Prompts

```
['create a Meshes object from a list of vertex and face tensors for a batch of triangulated meshes', 'get the packed representation of vertices as a single tensor of shape sum(V_n) by 3', 'offset the vertices of a Meshes object by a given tensor of offsets in place or out of place', 'scale the vertices of a Meshes object by a scalar or per-mesh scale factor', 'merge multiple Meshes objects into a single batched Meshes object with optional texture joining', 'create a Pointclouds object from a list of tensors with shape (num_points, 3)', 'subsample each cloud in a Pointclouds batch to at most max_points points', 'estimate normals for each point in a Pointclouds batch using neighborhood size', 'join a list of Pointclouds objects into a single batched Pointclouds object', 'compute axis-aligned bounding boxes for each cloud in a Pointclouds batch', 'create a padded tensor from a list of variable-sized PyTorch tensors with a specified pad value', 'convert a padded tensor back into a list of tensors using split sizes to trim padding', 'pack a list of tensors into a single concatenated tensor with index mapping metadata', 'split a packed tensor back into a list of tensors using specified split sizes', 'convert a padded 3D tensor into a packed tensor by removing padding using split sizes or a pad value', 'create a Volumes object from a 5D density tensor with optional features and voxel size', 'create a Volumes object from a list of 4D density tensors with varying spatial sizes', 'convert 3D world coordinates to local volume coordinates using the Volumes world_to_local_coords method', 'convert 3D local volume coordinates to world coordinates using the Volumes local_to_world_coords method', 'get the 3D coordinate grid of a volume in local or world coordinates using get_coord_grid']
```

Usage

```
{'create_pointclouds_batch': 'create a Pointclouds object from a list of tensors with shape (num_points, 3)', 'subsample_pointclouds': 'subsample each cloud in a Pointclouds batch to at most max_points points', 'estimate_normals_pointclouds': 'estimate normals for each point in a Pointclouds batch using neighborhood size', 'join_pointclouds_as_batch': 'join a list of Pointclouds objects into a single batched Pointclouds object', 'get_bounding_boxes_pointclouds': 'compute axis-aligned bounding boxes for each cloud in a Pointclouds batch'}
```

## File: facebookresearch_pytorch3d/pytorch3d/structures/utils.py

Prompts

```
['create a Meshes object from a list of vertex and face tensors for a batch of triangulated meshes', 'get the packed representation of vertices as a single tensor of shape sum(V_n) by 3', 'offset the vertices of a Meshes object by a given tensor of offsets in place or out of place', 'scale the vertices of a Meshes object by a scalar or per-mesh scale factor', 'merge multiple Meshes objects into a single batched Meshes object with optional texture joining', 'create a Pointclouds object from a list of tensors with shape (num_points, 3)', 'subsample each cloud in a Pointclouds batch to at most max_points points', 'estimate normals for each point in a Pointclouds batch using neighborhood size', 'join a list of Pointclouds objects into a single batched Pointclouds object', 'compute axis-aligned bounding boxes for each cloud in a Pointclouds batch', 'create a padded tensor from a list of variable-sized PyTorch tensors with a specified pad value', 'convert a padded tensor back into a list of tensors using split sizes to trim padding', 'pack a list of tensors into a single concatenated tensor with index mapping metadata', 'split a packed tensor back into a list of tensors using specified split sizes', 'convert a padded 3D tensor into a packed tensor by removing padding using split sizes or a pad value', 'create a Volumes object from a 5D density tensor with optional features and voxel size', 'create a Volumes object from a list of 4D density tensors with varying spatial sizes', 'convert 3D world coordinates to local volume coordinates using the Volumes world_to_local_coords method', 'convert 3D local volume coordinates to world coordinates using the Volumes local_to_world_coords method', 'get the 3D coordinate grid of a volume in local or world coordinates using get_coord_grid']
```

Usage

```
{'list_to_padded': 'create a padded tensor from a list of variable-sized PyTorch tensors with a specified pad value', 'padded_to_list': 'convert a padded tensor back into a list of tensors using split sizes to trim padding', 'list_to_packed': 'pack a list of tensors into a single concatenated tensor with index mapping metadata', 'packed_to_list': 'split a packed tensor back into a list of tensors using specified split sizes', 'padded_to_packed': 'convert a padded 3D tensor into a packed tensor by removing padding using split sizes or a pad value'}
```

## File: facebookresearch_pytorch3d/pytorch3d/structures/volumes.py

Prompts

```
['create a Meshes object from a list of vertex and face tensors for a batch of triangulated meshes', 'get the packed representation of vertices as a single tensor of shape sum(V_n) by 3', 'offset the vertices of a Meshes object by a given tensor of offsets in place or out of place', 'scale the vertices of a Meshes object by a scalar or per-mesh scale factor', 'merge multiple Meshes objects into a single batched Meshes object with optional texture joining', 'create a Pointclouds object from a list of tensors with shape (num_points, 3)', 'subsample each cloud in a Pointclouds batch to at most max_points points', 'estimate normals for each point in a Pointclouds batch using neighborhood size', 'join a list of Pointclouds objects into a single batched Pointclouds object', 'compute axis-aligned bounding boxes for each cloud in a Pointclouds batch', 'create a padded tensor from a list of variable-sized PyTorch tensors with a specified pad value', 'convert a padded tensor back into a list of tensors using split sizes to trim padding', 'pack a list of tensors into a single concatenated tensor with index mapping metadata', 'split a packed tensor back into a list of tensors using specified split sizes', 'convert a padded 3D tensor into a packed tensor by removing padding using split sizes or a pad value', 'create a Volumes object from a 5D density tensor with optional features and voxel size', 'create a Volumes object from a list of 4D density tensors with varying spatial sizes', 'convert 3D world coordinates to local volume coordinates using the Volumes world_to_local_coords method', 'convert 3D local volume coordinates to world coordinates using the Volumes local_to_world_coords method', 'get the 3D coordinate grid of a volume in local or world coordinates using get_coord_grid']
```

Usage

```
{'create_volumes_from_tensor': 'create a Volumes object from a 5D density tensor with optional features and voxel size', 'create_volumes_from_list': 'create a Volumes object from a list of 4D density tensors with varying spatial sizes', 'convert_world_to_local_coords': 'convert 3D world coordinates to local volume coordinates using the Volumes world_to_local_coords method', 'convert_local_to_world_coords': 'convert 3D local volume coordinates to world coordinates using the Volumes local_to_world_coords method', 'get_volume_coord_grid': 'get the 3D coordinate grid of a volume in local or world coordinates using get_coord_grid'}
```

