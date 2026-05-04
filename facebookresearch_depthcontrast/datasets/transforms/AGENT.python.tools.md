# Agent Python Tools

- repo: facebookresearch/depthcontrast
- repo_uri: https://github.com/facebookresearch/depthcontrast

## File: facebookresearch_depthcontrast/datasets/transforms/augment3d.py

Prompts

```
['build a python module to apply 3D point cloud augmentation transforms via get_transform3d with a config list', 'create a function that generates an x, y, or z axis rotation matrix using rotx, roty, or rotz', 'create a script that exports a numpy point cloud array to an OBJ file using pc2obj', 'create a tool that writes colored 3D points to a PLY file using write_ply_color or write_ply_rgb', 'review the get_transform3d function to understand subcenter, RandomFlip, RandomRotate, RandomScale, ColorJitter, and randomcuboid augmentation operations', 'create a ChromaticTranslation transform to add random color shifts to point cloud features', 'create a ChromaticAutoContrast transform to randomly enhance color contrast of point cloud features', 'create an ElasticDistortion transform to apply smooth spatial noise to sparse coordinates', 'create a Compose transform to chain multiple coordinate and feature augmentations together', 'create a cfl_collate_fn_factory to batch coords, feats, and labels into MinkowskiEngine sparse tensors', 'create a Voxelizer instance with scale, rotation, and translation augmentation bounds for point cloud data', 'voxelize 3D point cloud coordinates with features and labels using the Voxelizer class', 'clip point cloud coordinates to a specified bounding box using the Voxelizer clip method', 'get the voxelization and rotation transformation matrices from a Voxelizer instance for coordinate transforms', 'voxelize a sequence of temporal point clouds with shared augmentation using voxelize_temporal']
```

Usage

```
{'build_transform3d_pipeline': 'build a python module to apply 3D point cloud augmentation transforms via get_transform3d with a config list', 'create_rotation_matrix': 'create a function that generates an x, y, or z axis rotation matrix using rotx, roty, or rotz', 'export_point_cloud_obj': 'create a script that exports a numpy point cloud array to an OBJ file using pc2obj', 'write_colored_ply': 'create a tool that writes colored 3D points to a PLY file using write_ply_color or write_ply_rgb', 'review_augment3d_transforms': 'review the get_transform3d function to understand subcenter, RandomFlip, RandomRotate, RandomScale, ColorJitter, and randomcuboid augmentation operations'}
```

## File: facebookresearch_depthcontrast/datasets/transforms/transforms.py

Prompts

```
['build a python module to apply 3D point cloud augmentation transforms via get_transform3d with a config list', 'create a function that generates an x, y, or z axis rotation matrix using rotx, roty, or rotz', 'create a script that exports a numpy point cloud array to an OBJ file using pc2obj', 'create a tool that writes colored 3D points to a PLY file using write_ply_color or write_ply_rgb', 'review the get_transform3d function to understand subcenter, RandomFlip, RandomRotate, RandomScale, ColorJitter, and randomcuboid augmentation operations', 'create a ChromaticTranslation transform to add random color shifts to point cloud features', 'create a ChromaticAutoContrast transform to randomly enhance color contrast of point cloud features', 'create an ElasticDistortion transform to apply smooth spatial noise to sparse coordinates', 'create a Compose transform to chain multiple coordinate and feature augmentations together', 'create a cfl_collate_fn_factory to batch coords, feats, and labels into MinkowskiEngine sparse tensors', 'create a Voxelizer instance with scale, rotation, and translation augmentation bounds for point cloud data', 'voxelize 3D point cloud coordinates with features and labels using the Voxelizer class', 'clip point cloud coordinates to a specified bounding box using the Voxelizer clip method', 'get the voxelization and rotation transformation matrices from a Voxelizer instance for coordinate transforms', 'voxelize a sequence of temporal point clouds with shared augmentation using voxelize_temporal']
```

Usage

```
{'create_chromatic_translation_augmentation': 'create a ChromaticTranslation transform to add random color shifts to point cloud features', 'create_chromatic_auto_contrast_augmentation': 'create a ChromaticAutoContrast transform to randomly enhance color contrast of point cloud features', 'create_elastic_distortion_augmentation': 'create an ElasticDistortion transform to apply smooth spatial noise to sparse coordinates', 'compose_multiple_transforms': 'create a Compose transform to chain multiple coordinate and feature augmentations together', 'create_cfl_collate_fn': 'create a cfl_collate_fn_factory to batch coords, feats, and labels into MinkowskiEngine sparse tensors'}
```

## File: facebookresearch_depthcontrast/datasets/transforms/voxelizer.py

Prompts

```
['build a python module to apply 3D point cloud augmentation transforms via get_transform3d with a config list', 'create a function that generates an x, y, or z axis rotation matrix using rotx, roty, or rotz', 'create a script that exports a numpy point cloud array to an OBJ file using pc2obj', 'create a tool that writes colored 3D points to a PLY file using write_ply_color or write_ply_rgb', 'review the get_transform3d function to understand subcenter, RandomFlip, RandomRotate, RandomScale, ColorJitter, and randomcuboid augmentation operations', 'create a ChromaticTranslation transform to add random color shifts to point cloud features', 'create a ChromaticAutoContrast transform to randomly enhance color contrast of point cloud features', 'create an ElasticDistortion transform to apply smooth spatial noise to sparse coordinates', 'create a Compose transform to chain multiple coordinate and feature augmentations together', 'create a cfl_collate_fn_factory to batch coords, feats, and labels into MinkowskiEngine sparse tensors', 'create a Voxelizer instance with scale, rotation, and translation augmentation bounds for point cloud data', 'voxelize 3D point cloud coordinates with features and labels using the Voxelizer class', 'clip point cloud coordinates to a specified bounding box using the Voxelizer clip method', 'get the voxelization and rotation transformation matrices from a Voxelizer instance for coordinate transforms', 'voxelize a sequence of temporal point clouds with shared augmentation using voxelize_temporal']
```

Usage

```
{'create_voxelizer_with_augmentation': 'create a Voxelizer instance with scale, rotation, and translation augmentation bounds for point cloud data', 'voxelize_point_cloud': 'voxelize 3D point cloud coordinates with features and labels using the Voxelizer class', 'clip_point_cloud_coords': 'clip point cloud coordinates to a specified bounding box using the Voxelizer clip method', 'get_transformation_matrix': 'get the voxelization and rotation transformation matrices from a Voxelizer instance for coordinate transforms', 'voxelize_temporal_sequences': 'voxelize a sequence of temporal point clouds with shared augmentation using voxelize_temporal'}
```

