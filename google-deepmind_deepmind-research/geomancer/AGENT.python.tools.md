# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/geomancer/data_writer.py

Prompts

```
['render a 3D mesh image using MuJoCo physics with a given quaternion rotation and light direction', 'compute image tangent vectors by finite differences for quaternion rotation and light direction perturbations', 'get vectors normal to a unit vector using singular value decomposition', 'run the data writer CLI to render images and save shards with latents and tangents to NPZ files', 'review the render function that builds a MuJoCo MJCF scene and renders a 3D mesh', 'run the GEOMANCER fit function to estimate manifold components from a dataset of points', 'build a k-nearest neighbors graph from numpy data using make_nearest_neighbors_graph', 'run the orthogonal FFDiag algorithm to simultaneously diagonalize a set of matrices', 'cluster subspace dimensions from Laplacian eigenvectors using cluster_subspaces and ffdiag', "test the sym_op function to verify QXQ' transformation on symmetric matrices with optional zero trace", 'test the vec_to_sym function to convert a vector back into a symmetric matrix representation', 'test the ffdiag function to find a common diagonalizing matrix for a set of matrices', 'test the make_nearest_neighbors_graph function to build a k-nearest-neighbor graph from 2D data points', 'run the full geomancer test suite covering sym_op, ffdiag, and nearest neighbor graph construction', 'run GEOMANCER on a product of synthetic manifolds like S^2 x S^2 using the CLI', 'generate synthetic data points from a product of SO(n) and sphere manifolds with make_product_manifold', 'compute an orthonormal tangent space basis for a given SO(n) orthonormal matrix using make_so_tangent', 'compute the tangent space basis for a point on a sphere using make_sphere_tangent', 'compute orthonormal tangent bases for each submanifold in a product manifold using make_true_tangents']
```

Usage

```
{'render_mesh_image': 'render a 3D mesh image using MuJoCo physics with a given quaternion rotation and light direction', 'compute_tangent_vectors': 'compute image tangent vectors by finite differences for quaternion rotation and light direction perturbations', 'get_normal_vectors': 'get vectors normal to a unit vector using singular value decomposition', 'run_data_writer': 'run the data writer CLI to render images and save shards with latents and tangents to NPZ files', 'review_render_function': 'review the render function that builds a MuJoCo MJCF scene and renders a 3D mesh'}
```

## File: google-deepmind_deepmind-research/geomancer/geomancer.py

Prompts

```
['render a 3D mesh image using MuJoCo physics with a given quaternion rotation and light direction', 'compute image tangent vectors by finite differences for quaternion rotation and light direction perturbations', 'get vectors normal to a unit vector using singular value decomposition', 'run the data writer CLI to render images and save shards with latents and tangents to NPZ files', 'review the render function that builds a MuJoCo MJCF scene and renders a 3D mesh', 'run the GEOMANCER fit function to estimate manifold components from a dataset of points', 'build a k-nearest neighbors graph from numpy data using make_nearest_neighbors_graph', 'run the orthogonal FFDiag algorithm to simultaneously diagonalize a set of matrices', 'cluster subspace dimensions from Laplacian eigenvectors using cluster_subspaces and ffdiag', "test the sym_op function to verify QXQ' transformation on symmetric matrices with optional zero trace", 'test the vec_to_sym function to convert a vector back into a symmetric matrix representation', 'test the ffdiag function to find a common diagonalizing matrix for a set of matrices', 'test the make_nearest_neighbors_graph function to build a k-nearest-neighbor graph from 2D data points', 'run the full geomancer test suite covering sym_op, ffdiag, and nearest neighbor graph construction', 'run GEOMANCER on a product of synthetic manifolds like S^2 x S^2 using the CLI', 'generate synthetic data points from a product of SO(n) and sphere manifolds with make_product_manifold', 'compute an orthonormal tangent space basis for a given SO(n) orthonormal matrix using make_so_tangent', 'compute the tangent space basis for a point on a sphere using make_sphere_tangent', 'compute orthonormal tangent bases for each submanifold in a product manifold using make_true_tangents']
```

Usage

```
{'run_GEOMANCER_fit': 'run the GEOMANCER fit function to estimate manifold components from a dataset of points', 'build_knn_graph': 'build a k-nearest neighbors graph from numpy data using make_nearest_neighbors_graph', 'compute_tangent_vectors': 'compute tangent vectors for each data point using make_tangents with a neighbor graph', 'run_ffdiag_diagonalization': 'run the orthogonal FFDiag algorithm to simultaneously diagonalize a set of matrices', 'cluster_eigenvector_subspaces': 'cluster subspace dimensions from Laplacian eigenvectors using cluster_subspaces and ffdiag'}
```

## File: google-deepmind_deepmind-research/geomancer/geomancer_test.py

Prompts

```
['render a 3D mesh image using MuJoCo physics with a given quaternion rotation and light direction', 'compute image tangent vectors by finite differences for quaternion rotation and light direction perturbations', 'get vectors normal to a unit vector using singular value decomposition', 'run the data writer CLI to render images and save shards with latents and tangents to NPZ files', 'review the render function that builds a MuJoCo MJCF scene and renders a 3D mesh', 'run the GEOMANCER fit function to estimate manifold components from a dataset of points', 'build a k-nearest neighbors graph from numpy data using make_nearest_neighbors_graph', 'run the orthogonal FFDiag algorithm to simultaneously diagonalize a set of matrices', 'cluster subspace dimensions from Laplacian eigenvectors using cluster_subspaces and ffdiag', "test the sym_op function to verify QXQ' transformation on symmetric matrices with optional zero trace", 'test the vec_to_sym function to convert a vector back into a symmetric matrix representation', 'test the ffdiag function to find a common diagonalizing matrix for a set of matrices', 'test the make_nearest_neighbors_graph function to build a k-nearest-neighbor graph from 2D data points', 'run the full geomancer test suite covering sym_op, ffdiag, and nearest neighbor graph construction', 'run GEOMANCER on a product of synthetic manifolds like S^2 x S^2 using the CLI', 'generate synthetic data points from a product of SO(n) and sphere manifolds with make_product_manifold', 'compute an orthonormal tangent space basis for a given SO(n) orthonormal matrix using make_so_tangent', 'compute the tangent space basis for a point on a sphere using make_sphere_tangent', 'compute orthonormal tangent bases for each submanifold in a product manifold using make_true_tangents']
```

Usage

```
{'test_sym_op': "test the sym_op function to verify QXQ' transformation on symmetric matrices with optional zero trace", 'test_vec_to_sym': 'test the vec_to_sym function to convert a vector back into a symmetric matrix representation', 'test_ffdiag': 'test the ffdiag function to find a common diagonalizing matrix for a set of matrices', 'test_make_nearest_neighbors_graph': 'test the make_nearest_neighbors_graph function to build a k-nearest-neighbor graph from 2D data points', 'test_geomancer_test_suite': 'run the full geomancer test suite covering sym_op, ffdiag, and nearest neighbor graph construction'}
```

## File: google-deepmind_deepmind-research/geomancer/train.py

Prompts

```
['render a 3D mesh image using MuJoCo physics with a given quaternion rotation and light direction', 'compute image tangent vectors by finite differences for quaternion rotation and light direction perturbations', 'get vectors normal to a unit vector using singular value decomposition', 'run the data writer CLI to render images and save shards with latents and tangents to NPZ files', 'review the render function that builds a MuJoCo MJCF scene and renders a 3D mesh', 'run the GEOMANCER fit function to estimate manifold components from a dataset of points', 'build a k-nearest neighbors graph from numpy data using make_nearest_neighbors_graph', 'run the orthogonal FFDiag algorithm to simultaneously diagonalize a set of matrices', 'cluster subspace dimensions from Laplacian eigenvectors using cluster_subspaces and ffdiag', "test the sym_op function to verify QXQ' transformation on symmetric matrices with optional zero trace", 'test the vec_to_sym function to convert a vector back into a symmetric matrix representation', 'test the ffdiag function to find a common diagonalizing matrix for a set of matrices', 'test the make_nearest_neighbors_graph function to build a k-nearest-neighbor graph from 2D data points', 'run the full geomancer test suite covering sym_op, ffdiag, and nearest neighbor graph construction', 'run GEOMANCER on a product of synthetic manifolds like S^2 x S^2 using the CLI', 'generate synthetic data points from a product of SO(n) and sphere manifolds with make_product_manifold', 'compute an orthonormal tangent space basis for a given SO(n) orthonormal matrix using make_so_tangent', 'compute the tangent space basis for a point on a sphere using make_sphere_tangent', 'compute orthonormal tangent bases for each submanifold in a product manifold using make_true_tangents']
```

Usage

```
{'run_geomancer_on_synthetic_manifolds': 'run GEOMANCER on a product of synthetic manifolds like S^2 x S^2 using the CLI', 'generate_product_manifold_data': 'generate synthetic data points from a product of SO(n) and sphere manifolds with make_product_manifold', 'compute_so_tangent_basis': 'compute an orthonormal tangent space basis for a given SO(n) orthonormal matrix using make_so_tangent', 'compute_sphere_tangent_basis': 'compute the tangent space basis for a point on a sphere using make_sphere_tangent', 'compute_true_tangents_for_manifold': 'compute orthonormal tangent bases for each submanifold in a product manifold using make_true_tangents'}
```

