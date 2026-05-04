# Agent Python Tools

- repo: facebookresearch/all-atom-diffusion-transformer
- repo_uri: https://github.com/facebookresearch/all-atom-diffusion-transformer

## File: facebookresearch_all-atom-diffusion-transformer/src/models/components/kabsch_utils.py

Prompts

```
['build a python module to align two sets of 3D points using the differentiable Kabsch algorithm', 'create a function that applies rotation and translation to a set of 3D points', 'test the random_rotation_matrix function to generate a valid 3x3 rotation matrix from a random quaternion', 'refactor the differentiable_kabsch function to handle numerically unstable SVD by adding noise and recomputing', 'review the rototranslate function and its inverse mode for undoing rotation and translation on 3D points', 'build a radial cutoff graph with periodic boundary conditions for crystal atom positions', 'compute pairwise distances between atoms corrected for periodic boundary conditions using cell offsets', 'compute the number of neighbors per image from an edge index and atom counts', 'filter edges so each atom has at most a threshold number of nearest neighbors', 'review the radius_graph_pbc function to understand how unit cell repetitions are calculated']
```

Usage

```
{'build_kabsch_alignment': 'build a python module to align two sets of 3D points using the differentiable Kabsch algorithm', 'create_rototranslate_points': 'create a function that applies rotation and translation to a set of 3D points', 'test_random_rotation_matrix': 'test the random_rotation_matrix function to generate a valid 3x3 rotation matrix from a random quaternion', 'refactor_differentiable_kabsch': 'refactor the differentiable_kabsch function to handle numerically unstable SVD by adding noise and recomputing', 'review_rototranslate_inverse': 'review the rototranslate function and its inverse mode for undoing rotation and translation on 3D points'}
```

## File: facebookresearch_all-atom-diffusion-transformer/src/models/components/radius_graph_utils.py

Prompts

```
['build a python module to align two sets of 3D points using the differentiable Kabsch algorithm', 'create a function that applies rotation and translation to a set of 3D points', 'test the random_rotation_matrix function to generate a valid 3x3 rotation matrix from a random quaternion', 'refactor the differentiable_kabsch function to handle numerically unstable SVD by adding noise and recomputing', 'review the rototranslate function and its inverse mode for undoing rotation and translation on 3D points', 'build a radial cutoff graph with periodic boundary conditions for crystal atom positions', 'compute pairwise distances between atoms corrected for periodic boundary conditions using cell offsets', 'compute the number of neighbors per image from an edge index and atom counts', 'filter edges so each atom has at most a threshold number of nearest neighbors', 'review the radius_graph_pbc function to understand how unit cell repetitions are calculated']
```

Usage

```
{'build_radius_graph_pbc': 'build a radial cutoff graph with periodic boundary conditions for crystal atom positions', 'compute_pbc_distances': 'compute pairwise distances between atoms corrected for periodic boundary conditions using cell offsets', 'compute_neighbors_per_image': 'compute the number of neighbors per image from an edge index and atom counts', 'filter_max_neighbors': 'filter edges so each atom has at most a threshold number of nearest neighbors', 'review_radius_graph_pbc': 'review the radius_graph_pbc function to understand how unit cell repetitions are calculated'}
```

