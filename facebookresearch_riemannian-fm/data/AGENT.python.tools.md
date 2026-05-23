# Agent Python Tools

- repo: facebookresearch/riemannian-fm
- repo_uri: https://github.com/facebookresearch/riemannian-fm

## File: facebookresearch_riemannian-fm/data/synthesize_mesh_data.py

Prompts

```
['generate noisy concentric ring samples in 2D space with a configurable number of samples and random seed', 'create eigenfunction-based mesh samples by sampling a triangle mesh using Laplacian eigenfunctions and saving to numpy', 'generate maze datapairs by sampling random and checkerboard points inside a maze mesh and saving as npz', 'generate maze v2 datapairs using a Gaussian mixture model for target distribution and saving as npz', 'decimate a triangle mesh OBJ file to a simplified version with 5000 faces and write the result']
```

Usage

```
{'generate_rings': 'generate noisy concentric ring samples in 2D space with a configurable number of samples and random seed', 'create_eigfn': 'create eigenfunction-based mesh samples by sampling a triangle mesh using Laplacian eigenfunctions and saving to numpy', 'gen_maze_datapairs': 'generate maze datapairs by sampling random and checkerboard points inside a maze mesh and saving as npz', 'gen_mazev2': 'generate maze v2 datapairs using a Gaussian mixture model for target distribution and saving as npz', 'decimate_mesh': 'decimate a triangle mesh OBJ file to a simplified version with 5000 faces and write the result'}
```

