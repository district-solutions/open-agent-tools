# Agent Python Tools

- repo: facebookresearch/flowmm
- repo_uri: https://github.com/facebookresearch/flowmm

## File: facebookresearch_flowmm/src/flowmm/rfm/manifold_getter.py

Prompts

```
['create a ManifoldGetter instance with simplex atom manifold, flat torus coords, and SPD lattice manifold', 'build a forward pass converting batch atom types, frac coords, lengths, and angles into manifold flat representation', 'convert geometry representation with batch, atom types, frac coords, and lattices into manifold flat representation', 'convert manifold flat representation back to crystal structure with atom types, frac coords, and lattice matrix', 'get VMapManifolds and dimension info for a batch given num atoms, atom types, coord dims, and split manifold flag', 'create a VMapManifolds instance from a list of geoopt Manifold objects for batched manifold operations', 'use VMapManifolds projx method to project batched tensors onto their respective manifolds', 'use VMapManifolds proju method to project batched tangent vectors onto tangent spaces of manifolds', 'use VMapManifolds random method to generate random points on each manifold in the batch', 'use VMapManifolds inner method to compute inner products of tangent vectors across batched manifolds']
```

Usage

```
{'create_ManifoldGetter': 'create a ManifoldGetter instance with simplex atom manifold, flat torus coords, and SPD lattice manifold', 'build_forward_manifold_flatrep': 'build a forward pass converting batch atom types, frac coords, lengths, and angles into manifold flat representation', 'convert_georep_to_flatrep': 'convert geometry representation with batch, atom types, frac coords, and lattices into manifold flat representation', 'convert_flatrep_to_crystal': 'convert manifold flat representation back to crystal structure with atom types, frac coords, and lattice matrix', 'get_manifolds_for_batch': 'get VMapManifolds and dimension info for a batch given num atoms, atom types, coord dims, and split manifold flag'}
```

## File: facebookresearch_flowmm/src/flowmm/rfm/vmap.py

Prompts

```
['create a ManifoldGetter instance with simplex atom manifold, flat torus coords, and SPD lattice manifold', 'build a forward pass converting batch atom types, frac coords, lengths, and angles into manifold flat representation', 'convert geometry representation with batch, atom types, frac coords, and lattices into manifold flat representation', 'convert manifold flat representation back to crystal structure with atom types, frac coords, and lattice matrix', 'get VMapManifolds and dimension info for a batch given num atoms, atom types, coord dims, and split manifold flag', 'create a VMapManifolds instance from a list of geoopt Manifold objects for batched manifold operations', 'use VMapManifolds projx method to project batched tensors onto their respective manifolds', 'use VMapManifolds proju method to project batched tangent vectors onto tangent spaces of manifolds', 'use VMapManifolds random method to generate random points on each manifold in the batch', 'use VMapManifolds inner method to compute inner products of tangent vectors across batched manifolds']
```

Usage

```
{'create_VMapManifolds': 'create a VMapManifolds instance from a list of geoopt Manifold objects for batched manifold operations', 'use_vmap_projx': 'use VMapManifolds projx method to project batched tensors onto their respective manifolds', 'use_vmap_proju': 'use VMapManifolds proju method to project batched tangent vectors onto tangent spaces of manifolds', 'use_vmap_random': 'use VMapManifolds random method to generate random points on each manifold in the batch', 'use_vmap_inner': 'use VMapManifolds inner method to compute inner products of tangent vectors across batched manifolds'}
```

