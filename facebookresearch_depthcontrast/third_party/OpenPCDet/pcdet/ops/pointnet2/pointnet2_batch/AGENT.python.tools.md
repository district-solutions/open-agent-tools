# Agent Python Tools

- repo: facebookresearch/depthcontrast
- repo_uri: https://github.com/facebookresearch/depthcontrast

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/ops/pointnet2/pointnet2_batch/pointnet2_modules.py

Prompts

```
['build a PointnetSAModule with a specified MLP to perform single-scale set abstraction on point cloud features', 'build a PointnetSAModuleMSG with multiple radii and nsamples for multiscale grouping on point cloud data', 'run a PointnetFPModule to propagate features from known points to unknown points using nearest neighbor interpolation', 'review the PointnetSAModuleMSG forward pass that performs ball query grouping, MLP processing, and max pooling', 'test the PointnetFPModule forward method to interpolate known features onto unknown point positions', 'build a module that uses furthest_point_sample to select npoint features with largest minimum distance from a point cloud', 'build a module that uses gather_operation to gather features at specified index positions from a tensor', 'build a module that uses three_nn to find the three nearest neighbors of unknown points in known points', 'build a module that uses three_interpolate to perform weighted linear interpolation on three nearest neighbor features', 'build a module that uses QueryAndGroup to perform ball query and group features within a radius around centroids']
```

Usage

```
{'build_PointnetSAModule': 'build a PointnetSAModule with a specified MLP to perform single-scale set abstraction on point cloud features', 'build_PointnetSAModuleMSG': 'build a PointnetSAModuleMSG with multiple radii and nsamples for multiscale grouping on point cloud data', 'run_PointnetFPModule': 'run a PointnetFPModule to propagate features from known points to unknown points using nearest neighbor interpolation', 'review_PointnetSAModuleMSG_forward': 'review the PointnetSAModuleMSG forward pass that performs ball query grouping, MLP processing, and max pooling', 'test_PointnetFPModule_forward': 'test the PointnetFPModule forward method to interpolate known features onto unknown point positions'}
```

## File: facebookresearch_depthcontrast/third_party/OpenPCDet/pcdet/ops/pointnet2/pointnet2_batch/pointnet2_utils.py

Prompts

```
['build a PointnetSAModule with a specified MLP to perform single-scale set abstraction on point cloud features', 'build a PointnetSAModuleMSG with multiple radii and nsamples for multiscale grouping on point cloud data', 'run a PointnetFPModule to propagate features from known points to unknown points using nearest neighbor interpolation', 'review the PointnetSAModuleMSG forward pass that performs ball query grouping, MLP processing, and max pooling', 'test the PointnetFPModule forward method to interpolate known features onto unknown point positions', 'build a module that uses furthest_point_sample to select npoint features with largest minimum distance from a point cloud', 'build a module that uses gather_operation to gather features at specified index positions from a tensor', 'build a module that uses three_nn to find the three nearest neighbors of unknown points in known points', 'build a module that uses three_interpolate to perform weighted linear interpolation on three nearest neighbor features', 'build a module that uses QueryAndGroup to perform ball query and group features within a radius around centroids']
```

Usage

```
{'build_furthest_point_sampling': 'build a module that uses furthest_point_sample to select npoint features with largest minimum distance from a point cloud', 'build_gather_operation': 'build a module that uses gather_operation to gather features at specified index positions from a tensor', 'build_three_nn': 'build a module that uses three_nn to find the three nearest neighbors of unknown points in known points', 'build_three_interpolate': 'build a module that uses three_interpolate to perform weighted linear interpolation on three nearest neighbor features', 'build_query_and_group': 'build a module that uses QueryAndGroup to perform ball query and group features within a radius around centroids'}
```

