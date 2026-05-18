# Agent Python Tools

- repo: facebookresearch/meshrcnn
- repo_uri: https://github.com/facebookresearch/meshrcnn

## File: facebookresearch_meshrcnn/shapenet/modeling/backbone.py

Prompts

```
['build a ResNet backbone using build_backbone with a pretrained resnet50 model', 'create a ResNetBackbone instance by wrapping a torchvision ResNet model', 'run forward pass on images through ResNetBackbone to get multi-scale feature maps', 'review the _FEAT_DIMS dictionary to check feature channel dimensions for each ResNet variant', 'test the build_backbone function with resnet18 and verify it returns backbone and feat_dims', 'build a mesh prediction model from a config using build_model to instantiate the registered architecture', 'create a VoxMeshHead that extracts voxel scores then cubifies them into refined 3D meshes from images', 'create a SphereInitHead that initializes an icosphere mesh and refines it using image features from a backbone', 'create a Pixel2MeshHead that refines an icosphere mesh with subdivision using image features from a backbone', 'review the VoxMeshHead cubify method that converts voxel probability scores into 3D meshes using marching cubes']
```

Usage

```
{'build_resnet_backbone': 'build a ResNet backbone using build_backbone with a pretrained resnet50 model', 'create_resnet_backbone_instance': 'create a ResNetBackbone instance by wrapping a torchvision ResNet model', 'forward_multi_scale_features': 'run forward pass on images through ResNetBackbone to get multi-scale feature maps', 'review_feat_dims': 'review the _FEAT_DIMS dictionary to check feature channel dimensions for each ResNet variant', 'test_build_backbone': 'test the build_backbone function with resnet18 and verify it returns backbone and feat_dims'}
```

## File: facebookresearch_meshrcnn/shapenet/modeling/mesh_arch.py

Prompts

```
['build a ResNet backbone using build_backbone with a pretrained resnet50 model', 'create a ResNetBackbone instance by wrapping a torchvision ResNet model', 'run forward pass on images through ResNetBackbone to get multi-scale feature maps', 'review the _FEAT_DIMS dictionary to check feature channel dimensions for each ResNet variant', 'test the build_backbone function with resnet18 and verify it returns backbone and feat_dims', 'build a mesh prediction model from a config using build_model to instantiate the registered architecture', 'create a VoxMeshHead that extracts voxel scores then cubifies them into refined 3D meshes from images', 'create a SphereInitHead that initializes an icosphere mesh and refines it using image features from a backbone', 'create a Pixel2MeshHead that refines an icosphere mesh with subdivision using image features from a backbone', 'review the VoxMeshHead cubify method that converts voxel probability scores into 3D meshes using marching cubes']
```

Usage

```
{'build_model_from_cfg': 'build a mesh prediction model from a config using build_model to instantiate the registered architecture', 'create_voxmeshhead_for_voxel_to_mesh': 'create a VoxMeshHead that extracts voxel scores then cubifies them into refined 3D meshes from images', 'create_sphereinithead_for_sphere_init': 'create a SphereInitHead that initializes an icosphere mesh and refines it using image features from a backbone', 'create_pixel2meshhead_with_subdivision': 'create a Pixel2MeshHead that refines an icosphere mesh with subdivision using image features from a backbone', 'review_voxmeshhead_cubify_method': 'review the VoxMeshHead cubify method that converts voxel probability scores into 3D meshes using marching cubes'}
```

