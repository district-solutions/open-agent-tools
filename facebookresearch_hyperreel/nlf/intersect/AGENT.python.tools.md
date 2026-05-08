# Agent Python Tools

- repo: facebookresearch/hyperreel
- repo_uri: https://github.com/facebookresearch/hyperreel

## File: facebookresearch_hyperreel/nlf/intersect/base.py

Prompts

```
['create an Intersect nn.Module subclass that computes ray intersection points and distances from z_vals', 'build a uniform weight function that returns ones_like tensors for all ray distances', 'build an ease_max weight function that computes ray direction-based weights clamped between 0 and 1', 'review the Intersect forward method that processes z_vals, applies activation, computes distances, and returns points', 'test the process_z_vals method that scales z_vals, applies inverse contract or disparity conversion', 'create an IntersectPlane instance to compute ray-plane intersections using normal vectors and plane distance', 'create an IntersectEuclideanDistance instance to compute ray intersections using learned per-ray distance offsets', 'create an IntersectEuclideanDistanceUnified instance to compute intersections using Plucker position unification and distance offsets', 'create an IntersectCylinderNew instance to compute ray-cylinder intersections with space transformation and fallback recycling', 'create an IntersectSphereNew instance to compute ray-sphere intersections with space transformation and fallback recycling', 'build a voxel grid intersection module using IntersectVoxelGrid with config and z_channels', 'build a deformable voxel grid intersection using IntersectDeformableVoxelGrid with start normals', 'test the IntersectVoxelGrid intersect method with rays and z_vals tensors', 'test the IntersectDeformableVoxelGrid intersect method with rays and normal distance z_vals', 'review the voxel_intersect_dict registry mapping string keys to intersection classes', 'create an IntersectZPlane instance with z_channels, cfg, and kwargs for ray-plane intersection', 'build z-axis sample points using IntersectZPlane with linear or disparity sampling on CUDA', 'run the IntersectZPlane intersect method to compute ray-to-z-plane intersection distances', 'review the IntersectZPlane z_scale calculation logic based on sample spacing and config', 'test the IntersectZPlane local prediction feature that offsets z_vals by voxel grid origin']
```

Usage

```
{'create_intersect_module': 'create an Intersect nn.Module subclass that computes ray intersection points and distances from z_vals', 'build_uniform_weight_fn': 'build a uniform weight function that returns ones_like tensors for all ray distances', 'build_ease_max_weight_fn': 'build an ease_max weight function that computes ray direction-based weights clamped between 0 and 1', 'review_intersect_forward': 'review the Intersect forward method that processes z_vals, applies activation, computes distances, and returns points', 'test_process_z_vals': 'test the process_z_vals method that scales z_vals, applies inverse contract or disparity conversion'}
```

## File: facebookresearch_hyperreel/nlf/intersect/primitive.py

Prompts

```
['create an Intersect nn.Module subclass that computes ray intersection points and distances from z_vals', 'build a uniform weight function that returns ones_like tensors for all ray distances', 'build an ease_max weight function that computes ray direction-based weights clamped between 0 and 1', 'review the Intersect forward method that processes z_vals, applies activation, computes distances, and returns points', 'test the process_z_vals method that scales z_vals, applies inverse contract or disparity conversion', 'create an IntersectPlane instance to compute ray-plane intersections using normal vectors and plane distance', 'create an IntersectEuclideanDistance instance to compute ray intersections using learned per-ray distance offsets', 'create an IntersectEuclideanDistanceUnified instance to compute intersections using Plucker position unification and distance offsets', 'create an IntersectCylinderNew instance to compute ray-cylinder intersections with space transformation and fallback recycling', 'create an IntersectSphereNew instance to compute ray-sphere intersections with space transformation and fallback recycling', 'build a voxel grid intersection module using IntersectVoxelGrid with config and z_channels', 'build a deformable voxel grid intersection using IntersectDeformableVoxelGrid with start normals', 'test the IntersectVoxelGrid intersect method with rays and z_vals tensors', 'test the IntersectDeformableVoxelGrid intersect method with rays and normal distance z_vals', 'review the voxel_intersect_dict registry mapping string keys to intersection classes', 'create an IntersectZPlane instance with z_channels, cfg, and kwargs for ray-plane intersection', 'build z-axis sample points using IntersectZPlane with linear or disparity sampling on CUDA', 'run the IntersectZPlane intersect method to compute ray-to-z-plane intersection distances', 'review the IntersectZPlane z_scale calculation logic based on sample spacing and config', 'test the IntersectZPlane local prediction feature that offsets z_vals by voxel grid origin']
```

Usage

```
{'create_intersect_plane': 'create an IntersectPlane instance to compute ray-plane intersections using normal vectors and plane distance', 'create_intersect_euclidean_distance': 'create an IntersectEuclideanDistance instance to compute ray intersections using learned per-ray distance offsets', 'create_intersect_euclidean_distance_unified': 'create an IntersectEuclideanDistanceUnified instance to compute intersections using Plucker position unification and distance offsets', 'create_intersect_cylinder_new': 'create an IntersectCylinderNew instance to compute ray-cylinder intersections with space transformation and fallback recycling', 'create_intersect_sphere_new': 'create an IntersectSphereNew instance to compute ray-sphere intersections with space transformation and fallback recycling'}
```

## File: facebookresearch_hyperreel/nlf/intersect/voxel.py

Prompts

```
['create an Intersect nn.Module subclass that computes ray intersection points and distances from z_vals', 'build a uniform weight function that returns ones_like tensors for all ray distances', 'build an ease_max weight function that computes ray direction-based weights clamped between 0 and 1', 'review the Intersect forward method that processes z_vals, applies activation, computes distances, and returns points', 'test the process_z_vals method that scales z_vals, applies inverse contract or disparity conversion', 'create an IntersectPlane instance to compute ray-plane intersections using normal vectors and plane distance', 'create an IntersectEuclideanDistance instance to compute ray intersections using learned per-ray distance offsets', 'create an IntersectEuclideanDistanceUnified instance to compute intersections using Plucker position unification and distance offsets', 'create an IntersectCylinderNew instance to compute ray-cylinder intersections with space transformation and fallback recycling', 'create an IntersectSphereNew instance to compute ray-sphere intersections with space transformation and fallback recycling', 'build a voxel grid intersection module using IntersectVoxelGrid with config and z_channels', 'build a deformable voxel grid intersection using IntersectDeformableVoxelGrid with start normals', 'test the IntersectVoxelGrid intersect method with rays and z_vals tensors', 'test the IntersectDeformableVoxelGrid intersect method with rays and normal distance z_vals', 'review the voxel_intersect_dict registry mapping string keys to intersection classes', 'create an IntersectZPlane instance with z_channels, cfg, and kwargs for ray-plane intersection', 'build z-axis sample points using IntersectZPlane with linear or disparity sampling on CUDA', 'run the IntersectZPlane intersect method to compute ray-to-z-plane intersection distances', 'review the IntersectZPlane z_scale calculation logic based on sample spacing and config', 'test the IntersectZPlane local prediction feature that offsets z_vals by voxel grid origin']
```

Usage

```
{'build_voxel_grid_intersection': 'build a voxel grid intersection module using IntersectVoxelGrid with config and z_channels', 'build_deformable_voxel_grid': 'build a deformable voxel grid intersection using IntersectDeformableVoxelGrid with start normals', 'test_intersect_voxel_grid': 'test the IntersectVoxelGrid intersect method with rays and z_vals tensors', 'test_deformable_intersect': 'test the IntersectDeformableVoxelGrid intersect method with rays and normal distance z_vals', 'review_voxel_intersect_dict': 'review the voxel_intersect_dict registry mapping string keys to intersection classes'}
```

## File: facebookresearch_hyperreel/nlf/intersect/z.py

Prompts

```
['create an Intersect nn.Module subclass that computes ray intersection points and distances from z_vals', 'build a uniform weight function that returns ones_like tensors for all ray distances', 'build an ease_max weight function that computes ray direction-based weights clamped between 0 and 1', 'review the Intersect forward method that processes z_vals, applies activation, computes distances, and returns points', 'test the process_z_vals method that scales z_vals, applies inverse contract or disparity conversion', 'create an IntersectPlane instance to compute ray-plane intersections using normal vectors and plane distance', 'create an IntersectEuclideanDistance instance to compute ray intersections using learned per-ray distance offsets', 'create an IntersectEuclideanDistanceUnified instance to compute intersections using Plucker position unification and distance offsets', 'create an IntersectCylinderNew instance to compute ray-cylinder intersections with space transformation and fallback recycling', 'create an IntersectSphereNew instance to compute ray-sphere intersections with space transformation and fallback recycling', 'build a voxel grid intersection module using IntersectVoxelGrid with config and z_channels', 'build a deformable voxel grid intersection using IntersectDeformableVoxelGrid with start normals', 'test the IntersectVoxelGrid intersect method with rays and z_vals tensors', 'test the IntersectDeformableVoxelGrid intersect method with rays and normal distance z_vals', 'review the voxel_intersect_dict registry mapping string keys to intersection classes', 'create an IntersectZPlane instance with z_channels, cfg, and kwargs for ray-plane intersection', 'build z-axis sample points using IntersectZPlane with linear or disparity sampling on CUDA', 'run the IntersectZPlane intersect method to compute ray-to-z-plane intersection distances', 'review the IntersectZPlane z_scale calculation logic based on sample spacing and config', 'test the IntersectZPlane local prediction feature that offsets z_vals by voxel grid origin']
```

Usage

```
{'create_IntersectZPlane': 'create an IntersectZPlane instance with z_channels, cfg, and kwargs for ray-plane intersection', 'build_z_samples': 'build z-axis sample points using IntersectZPlane with linear or disparity sampling on CUDA', 'run_intersect_method': 'run the IntersectZPlane intersect method to compute ray-to-z-plane intersection distances', 'review_z_scale_calculation': 'review the IntersectZPlane z_scale calculation logic based on sample spacing and config', 'test_local_prediction': 'test the IntersectZPlane local prediction feature that offsets z_vals by voxel grid origin'}
```

