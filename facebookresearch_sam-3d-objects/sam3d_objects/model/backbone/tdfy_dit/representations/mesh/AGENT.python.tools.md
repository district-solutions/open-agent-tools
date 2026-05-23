# Agent Python Tools

- repo: facebookresearch/sam-3d-objects
- repo_uri: https://github.com/facebookresearch/sam-3d-objects

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/representations/mesh/cube2mesh.py

Prompts

```
['build a mesh from a SparseTensor by calling SparseFeatures2Mesh with cube features and resolution', 'create a MeshExtractResult object from vertices and faces tensors to compute face normals', 'compute normalized face normals from vertex positions and face indices using MeshExtractResult.comput_face_normals', 'compute normalized vertex normals by averaging adjacent face normals using MeshExtractResult.comput_v_normals', 'extract a named feature layout slice from a tensor using SparseFeatures2Mesh.get_layout with sdf, deform, color, or weights', 'construct a dense 3D grid of vertices and cube indices from a given resolution on GPU', 'construct a voxel grid from sparse coordinates by computing unique vertices and cube connectivity', 'scatter reduce per-cube feature values to per-vertex features using mean or sum reduction', 'convert sparse cube coordinates and features to vertex-level features with optional consistency loss', 'map sparse voxel coordinates and features into a dense 3D attribute tensor with optional SDF initialization']
```

Usage

```
{'build_mesh_from_sparse_tensor': 'build a mesh from a SparseTensor by calling SparseFeatures2Mesh with cube features and resolution', 'create_mesh_extract_result': 'create a MeshExtractResult object from vertices and faces tensors to compute face normals', 'compute_face_normals': 'compute normalized face normals from vertex positions and face indices using MeshExtractResult.comput_face_normals', 'compute_vertex_normals': 'compute normalized vertex normals by averaging adjacent face normals using MeshExtractResult.comput_v_normals', 'extract_feature_layout': 'extract a named feature layout slice from a tensor using SparseFeatures2Mesh.get_layout with sdf, deform, color, or weights'}
```

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/representations/mesh/utils_cube.py

Prompts

```
['build a mesh from a SparseTensor by calling SparseFeatures2Mesh with cube features and resolution', 'create a MeshExtractResult object from vertices and faces tensors to compute face normals', 'compute normalized face normals from vertex positions and face indices using MeshExtractResult.comput_face_normals', 'compute normalized vertex normals by averaging adjacent face normals using MeshExtractResult.comput_v_normals', 'extract a named feature layout slice from a tensor using SparseFeatures2Mesh.get_layout with sdf, deform, color, or weights', 'construct a dense 3D grid of vertices and cube indices from a given resolution on GPU', 'construct a voxel grid from sparse coordinates by computing unique vertices and cube connectivity', 'scatter reduce per-cube feature values to per-vertex features using mean or sum reduction', 'convert sparse cube coordinates and features to vertex-level features with optional consistency loss', 'map sparse voxel coordinates and features into a dense 3D attribute tensor with optional SDF initialization']
```

Usage

```
{'construct_dense_grid': 'construct a dense 3D grid of vertices and cube indices from a given resolution on GPU', 'construct_voxel_grid': 'construct a voxel grid from sparse coordinates by computing unique vertices and cube connectivity', 'cubes_to_verts': 'scatter reduce per-cube feature values to per-vertex features using mean or sum reduction', 'sparse_cube2verts': 'convert sparse cube coordinates and features to vertex-level features with optional consistency loss', 'get_dense_attrs': 'map sparse voxel coordinates and features into a dense 3D attribute tensor with optional SDF initialization'}
```

