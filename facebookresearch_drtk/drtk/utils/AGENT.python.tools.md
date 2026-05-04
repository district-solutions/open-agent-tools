# Agent Python Tools

- repo: facebookresearch/drtk
- repo_uri: https://github.com/facebookresearch/drtk

## File: facebookresearch_drtk/drtk/utils/geometry.py

Prompts

```
['build a python module to compute the transposed Jacobian matrix for mesh triangles given vertex positions and UV coordinates', 'create a function that sums face attributes across all faces for each vertex using scatter add', 'build a python module to compute face normals, edges, and areas from vertex positions and face indices', 'create a function that computes normalized vertex binormals from mesh vertex positions and UV texture coordinates', 'build a python module to compute vertex normals by averaging face normals for each vertex in a mesh', 'index a PyTorch tensor along a given dimension using an index tensor to replace the shape', 'review the index function that indexes a tensor along a dimension with an index tensor', 'test the index function with a tensor of shape [8, 7306, 3] and index tensor [11000, 3]', 'summarize the index function that uses index_select and reshape to index tensors along a dimension', 'refactor the index function to support additional tensor indexing operations beyond index_select', 'load a PyTorch C++ extension module by its name using importlib and th.ops.load_library', 'load a PyTorch extension module that silently skips ImportError when running inside Sphinx documentation builds', 'load a PyTorch extension module and re-raise ImportError if not running in a Sphinx environment', 'review the load_torch_ops function to understand how it imports and loads PyTorch C++ extension libraries', 'summarize the load_torch_ops function which loads PyTorch ops from a named extension module with Sphinx-safe error handling', 'project 3D world-space vertices to pixel-space with optional camera distortion models', 'project camera-space points to pixel-space using pinhole camera intrinsics', 'project camera-space points to distorted pixel-space using radial-tangential distortion model', 'project camera-space points to distorted pixel-space using the fisheye distortion model', 'estimate the maximum field of view from fisheye distortion coefficients']
```

Usage

```
{'compute_face_dpdt': 'build a python module to compute the transposed Jacobian matrix for mesh triangles given vertex positions and UV coordinates', 'aggregate_face_attributes_to_vertices': 'create a function that sums face attributes across all faces for each vertex using scatter add', 'compute_face_info': 'build a python module to compute face normals, edges, and areas from vertex positions and face indices', 'compute_vertex_binormals': 'create a function that computes normalized vertex binormals from mesh vertex positions and UV texture coordinates', 'compute_vertex_normals': 'build a python module to compute vertex normals by averaging face normals for each vertex in a mesh'}
```

## File: facebookresearch_drtk/drtk/utils/indexing.py

Prompts

```
['build a python module to compute the transposed Jacobian matrix for mesh triangles given vertex positions and UV coordinates', 'create a function that sums face attributes across all faces for each vertex using scatter add', 'build a python module to compute face normals, edges, and areas from vertex positions and face indices', 'create a function that computes normalized vertex binormals from mesh vertex positions and UV texture coordinates', 'build a python module to compute vertex normals by averaging face normals for each vertex in a mesh', 'index a PyTorch tensor along a given dimension using an index tensor to replace the shape', 'review the index function that indexes a tensor along a dimension with an index tensor', 'test the index function with a tensor of shape [8, 7306, 3] and index tensor [11000, 3]', 'summarize the index function that uses index_select and reshape to index tensors along a dimension', 'refactor the index function to support additional tensor indexing operations beyond index_select', 'load a PyTorch C++ extension module by its name using importlib and th.ops.load_library', 'load a PyTorch extension module that silently skips ImportError when running inside Sphinx documentation builds', 'load a PyTorch extension module and re-raise ImportError if not running in a Sphinx environment', 'review the load_torch_ops function to understand how it imports and loads PyTorch C++ extension libraries', 'summarize the load_torch_ops function which loads PyTorch ops from a named extension module with Sphinx-safe error handling', 'project 3D world-space vertices to pixel-space with optional camera distortion models', 'project camera-space points to pixel-space using pinhole camera intrinsics', 'project camera-space points to distorted pixel-space using radial-tangential distortion model', 'project camera-space points to distorted pixel-space using the fisheye distortion model', 'estimate the maximum field of view from fisheye distortion coefficients']
```

Usage

```
{'index_tensor_along_dim': 'index a PyTorch tensor along a given dimension using an index tensor to replace the shape', 'review_index_function': 'review the index function that indexes a tensor along a dimension with an index tensor', 'test_index_tensor': 'test the index function with a tensor of shape [8, 7306, 3] and index tensor [11000, 3]', 'summarize_index_function': 'summarize the index function that uses index_select and reshape to index tensors along a dimension', 'refactor_index_function': 'refactor the index function to support additional tensor indexing operations beyond index_select'}
```

## File: facebookresearch_drtk/drtk/utils/load_torch_ops.py

Prompts

```
['build a python module to compute the transposed Jacobian matrix for mesh triangles given vertex positions and UV coordinates', 'create a function that sums face attributes across all faces for each vertex using scatter add', 'build a python module to compute face normals, edges, and areas from vertex positions and face indices', 'create a function that computes normalized vertex binormals from mesh vertex positions and UV texture coordinates', 'build a python module to compute vertex normals by averaging face normals for each vertex in a mesh', 'index a PyTorch tensor along a given dimension using an index tensor to replace the shape', 'review the index function that indexes a tensor along a dimension with an index tensor', 'test the index function with a tensor of shape [8, 7306, 3] and index tensor [11000, 3]', 'summarize the index function that uses index_select and reshape to index tensors along a dimension', 'refactor the index function to support additional tensor indexing operations beyond index_select', 'load a PyTorch C++ extension module by its name using importlib and th.ops.load_library', 'load a PyTorch extension module that silently skips ImportError when running inside Sphinx documentation builds', 'load a PyTorch extension module and re-raise ImportError if not running in a Sphinx environment', 'review the load_torch_ops function to understand how it imports and loads PyTorch C++ extension libraries', 'summarize the load_torch_ops function which loads PyTorch ops from a named extension module with Sphinx-safe error handling', 'project 3D world-space vertices to pixel-space with optional camera distortion models', 'project camera-space points to pixel-space using pinhole camera intrinsics', 'project camera-space points to distorted pixel-space using radial-tangential distortion model', 'project camera-space points to distorted pixel-space using the fisheye distortion model', 'estimate the maximum field of view from fisheye distortion coefficients']
```

Usage

```
{'load_torch_ops': 'load a PyTorch C++ extension module by its name using importlib and th.ops.load_library', 'load_torch_ops_sphinx_safe': 'load a PyTorch extension module that silently skips ImportError when running inside Sphinx documentation builds', 'load_torch_ops_import_error': 'load a PyTorch extension module and re-raise ImportError if not running in a Sphinx environment', 'review_load_torch_ops': 'review the load_torch_ops function to understand how it imports and loads PyTorch C++ extension libraries', 'summarize_load_torch_ops': 'summarize the load_torch_ops function which loads PyTorch ops from a named extension module with Sphinx-safe error handling'}
```

## File: facebookresearch_drtk/drtk/utils/projection.py

Prompts

```
['build a python module to compute the transposed Jacobian matrix for mesh triangles given vertex positions and UV coordinates', 'create a function that sums face attributes across all faces for each vertex using scatter add', 'build a python module to compute face normals, edges, and areas from vertex positions and face indices', 'create a function that computes normalized vertex binormals from mesh vertex positions and UV texture coordinates', 'build a python module to compute vertex normals by averaging face normals for each vertex in a mesh', 'index a PyTorch tensor along a given dimension using an index tensor to replace the shape', 'review the index function that indexes a tensor along a dimension with an index tensor', 'test the index function with a tensor of shape [8, 7306, 3] and index tensor [11000, 3]', 'summarize the index function that uses index_select and reshape to index tensors along a dimension', 'refactor the index function to support additional tensor indexing operations beyond index_select', 'load a PyTorch C++ extension module by its name using importlib and th.ops.load_library', 'load a PyTorch extension module that silently skips ImportError when running inside Sphinx documentation builds', 'load a PyTorch extension module and re-raise ImportError if not running in a Sphinx environment', 'review the load_torch_ops function to understand how it imports and loads PyTorch C++ extension libraries', 'summarize the load_torch_ops function which loads PyTorch ops from a named extension module with Sphinx-safe error handling', 'project 3D world-space vertices to pixel-space with optional camera distortion models', 'project camera-space points to pixel-space using pinhole camera intrinsics', 'project camera-space points to distorted pixel-space using radial-tangential distortion model', 'project camera-space points to distorted pixel-space using the fisheye distortion model', 'estimate the maximum field of view from fisheye distortion coefficients']
```

Usage

```
{'project_points': 'project 3D world-space vertices to pixel-space with optional camera distortion models', 'project_pinhole': 'project camera-space points to pixel-space using pinhole camera intrinsics', 'project_pinhole_distort_rt': 'project camera-space points to distorted pixel-space using radial-tangential distortion model', 'project_fisheye_distort': 'project camera-space points to distorted pixel-space using the fisheye distortion model', 'estimate_fisheye_fov': 'estimate the maximum field of view from fisheye distortion coefficients'}
```

