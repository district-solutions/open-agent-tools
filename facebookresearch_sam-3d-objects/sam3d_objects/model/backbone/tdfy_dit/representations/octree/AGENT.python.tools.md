# Agent Python Tools

- repo: facebookresearch/sam-3d-objects
- repo_uri: https://github.com/facebookresearch/sam-3d-objects

## File: facebookresearch_sam-3d-objects/sam3d_objects/model/backbone/tdfy_dit/representations/octree/octree_dfs.py

Prompts

```
['create a DfsOctree instance with voxel primitives for sparse 3D scene representation', 'create a DfsOctree instance with gaussian primitives for 3D Gaussian splatting', 'create a DfsOctree instance with trivec primitives for 3D scene representation', 'subdivide octree leaf nodes by passing a mask with value 1 to structure_control', 'merge octree leaf nodes into parents by passing a mask with value -1 to structure_control']
```

Usage

```
{'create_octree_voxel': 'create a DfsOctree instance with voxel primitives for sparse 3D scene representation', 'create_octree_gaussian': 'create a DfsOctree instance with gaussian primitives for 3D Gaussian splatting', 'create_octree_trivec': 'create a DfsOctree instance with trivec primitives for 3D scene representation', 'subdivide_octree_nodes': 'subdivide octree leaf nodes by passing a mask with value 1 to structure_control', 'merge_octree_nodes': 'merge octree leaf nodes into parents by passing a mask with value -1 to structure_control'}
```

