# Agent Python Tools

- repo: facebookresearch/meshrcnn
- repo_uri: https://github.com/facebookresearch/meshrcnn

## File: facebookresearch_meshrcnn/meshrcnn/structures/mask.py

Prompts

```
['crop a mask tensor within a bounding box and resize it to a specified mask size', 'batch crop multiple masks within their corresponding bounding boxes and resize to a uniform size', 'test the crop_mask_within_box function with a sample mask tensor and bounding box coordinates', 'review the crop_mask_within_box function to understand its crop, resize, and binarize pipeline', 'refactor the batch_crop_masks_within_box function to improve GPU efficiency for mask cropping operations', 'batch crop 3D meshes within bounding boxes using camera matrices and return a Meshes structure', 'create a MeshInstances object from a list of vertex and face tensor pairs for mesh management', 'move a MeshInstances object and all its mesh tensors to a specified PyTorch device', 'index into a MeshInstances object using int, slice, or boolean tensor to select specific meshes', 'iterate over a MeshInstances object to access individual mesh vertex and face tensor pairs', 'batch crop voxels within 3D bounding boxes using camera matrices and voxel side length', 'create a VoxelInstances object from a list of PyTorch voxel tensors for batched operations', 'downsample a 3D voxel tensor by a factor using max or mean pooling across dimensions', 'convert normalized 3D vertex coordinates into a binary voxel grid of a specified size', 'normalize 3D vertex coordinates by centering and scaling to a unit bounding box']
```

Usage

```
{'crop_mask_within_box': 'crop a mask tensor within a bounding box and resize it to a specified mask size', 'batch_crop_masks_within_box': 'batch crop multiple masks within their corresponding bounding boxes and resize to a uniform size', 'test_crop_mask_within_box': 'test the crop_mask_within_box function with a sample mask tensor and bounding box coordinates', 'review_crop_mask_within_box': 'review the crop_mask_within_box function to understand its crop, resize, and binarize pipeline', 'refactor_batch_crop_masks_within_box': 'refactor the batch_crop_masks_within_box function to improve GPU efficiency for mask cropping operations'}
```

## File: facebookresearch_meshrcnn/meshrcnn/structures/mesh.py

Prompts

```
['crop a mask tensor within a bounding box and resize it to a specified mask size', 'batch crop multiple masks within their corresponding bounding boxes and resize to a uniform size', 'test the crop_mask_within_box function with a sample mask tensor and bounding box coordinates', 'review the crop_mask_within_box function to understand its crop, resize, and binarize pipeline', 'refactor the batch_crop_masks_within_box function to improve GPU efficiency for mask cropping operations', 'batch crop 3D meshes within bounding boxes using camera matrices and return a Meshes structure', 'create a MeshInstances object from a list of vertex and face tensor pairs for mesh management', 'move a MeshInstances object and all its mesh tensors to a specified PyTorch device', 'index into a MeshInstances object using int, slice, or boolean tensor to select specific meshes', 'iterate over a MeshInstances object to access individual mesh vertex and face tensor pairs', 'batch crop voxels within 3D bounding boxes using camera matrices and voxel side length', 'create a VoxelInstances object from a list of PyTorch voxel tensors for batched operations', 'downsample a 3D voxel tensor by a factor using max or mean pooling across dimensions', 'convert normalized 3D vertex coordinates into a binary voxel grid of a specified size', 'normalize 3D vertex coordinates by centering and scaling to a unit bounding box']
```

Usage

```
{'batch_crop_meshes_within_box': 'batch crop 3D meshes within bounding boxes using camera matrices and return a Meshes structure', 'create_MeshInstances': 'create a MeshInstances object from a list of vertex and face tensor pairs for mesh management', 'move_MeshInstances_to_device': 'move a MeshInstances object and all its mesh tensors to a specified PyTorch device', 'index_MeshInstances': 'index into a MeshInstances object using int, slice, or boolean tensor to select specific meshes', 'iterate_MeshInstances': 'iterate over a MeshInstances object to access individual mesh vertex and face tensor pairs'}
```

## File: facebookresearch_meshrcnn/meshrcnn/structures/voxel.py

Prompts

```
['crop a mask tensor within a bounding box and resize it to a specified mask size', 'batch crop multiple masks within their corresponding bounding boxes and resize to a uniform size', 'test the crop_mask_within_box function with a sample mask tensor and bounding box coordinates', 'review the crop_mask_within_box function to understand its crop, resize, and binarize pipeline', 'refactor the batch_crop_masks_within_box function to improve GPU efficiency for mask cropping operations', 'batch crop 3D meshes within bounding boxes using camera matrices and return a Meshes structure', 'create a MeshInstances object from a list of vertex and face tensor pairs for mesh management', 'move a MeshInstances object and all its mesh tensors to a specified PyTorch device', 'index into a MeshInstances object using int, slice, or boolean tensor to select specific meshes', 'iterate over a MeshInstances object to access individual mesh vertex and face tensor pairs', 'batch crop voxels within 3D bounding boxes using camera matrices and voxel side length', 'create a VoxelInstances object from a list of PyTorch voxel tensors for batched operations', 'downsample a 3D voxel tensor by a factor using max or mean pooling across dimensions', 'convert normalized 3D vertex coordinates into a binary voxel grid of a specified size', 'normalize 3D vertex coordinates by centering and scaling to a unit bounding box']
```

Usage

```
{'batch_crop_voxels_within_box': 'batch crop voxels within 3D bounding boxes using camera matrices and voxel side length', 'create_VoxelInstances': 'create a VoxelInstances object from a list of PyTorch voxel tensors for batched operations', 'downsample_voxel_tensor': 'downsample a 3D voxel tensor by a factor using max or mean pooling across dimensions', 'verts2voxel': 'convert normalized 3D vertex coordinates into a binary voxel grid of a specified size', 'normalize_verts': 'normalize 3D vertex coordinates by centering and scaling to a unit bounding box'}
```

