# Agent Python Tools

- repo: facebookresearch/3detr
- repo_uri: https://github.com/facebookresearch/3detr

## File: facebookresearch_3detr/third_party/pointnet2/pointnet2_modules.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping using radii, nsamples, and mlps for point cloud feature extraction', 'build a PointnetSAModuleVotes layer with max avg or rbf pooling for vote net point cloud processing', 'build a PointnetFPModule layer to propagate features from known to unknown points via inverse distance weighted interpolation', 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping to propagate features between point sets', 'run the PointnetSAModuleMSG module on random xyz coordinates and features tensors to extract downsampled point cloud features', 'test the gradient correctness of pointnet2_utils three_interpolate using PyTorch gradcheck', 'run the pointnet2 three interpolate gradient test to verify autograd correctness', 'review the test_interpolation_grad function that validates three_interpolate gradients with hardcoded indices and weights', 'summarize the nested interpolate_func that calls pointnet2_utils three_interpolate with index and weight tensors', 'refactor test_interpolation_grad to parameterize batch size, feature dimension, and number of points', 'sample npoint features from a point cloud using iterative furthest point sampling on xyz coordinates', 'gather selected point features by index from a (B, C, N) feature tensor using gathered indices', 'find the three nearest neighbors of unknown points in a known point set and return distances and indices', 'query points within a given radius around center points and return indices of features in each ball', 'group point cloud features using ball query with radius and optional xyz normalization and uniform sampling', 'build a SharedMLP module with a list of channel sizes for PointNet2 feature extraction', 'create a Conv2d layer with optional batch norm and ReLU activation for 2D convolution', 'create a Conv1d layer with optional batch norm and preact mode for 1D convolution', 'create a Conv3d layer with optional batch norm and kaiming init for 3D convolution', 'create a BNMomentumScheduler to adjust batch norm momentum per epoch using a lambda function']
```

Usage

```
{'build_PointnetSAModuleMSG': 'build a PointnetSAModuleMSG layer with multiscale grouping using radii, nsamples, and mlps for point cloud feature extraction', 'build_PointnetSAModuleVotes': 'build a PointnetSAModuleVotes layer with max avg or rbf pooling for vote net point cloud processing', 'build_PointnetFPModule': 'build a PointnetFPModule layer to propagate features from known to unknown points via inverse distance weighted interpolation', 'build_PointnetLFPModuleMSG': 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping to propagate features between point sets', 'run_PointnetSAModuleMSG': 'run the PointnetSAModuleMSG module on random xyz coordinates and features tensors to extract downsampled point cloud features'}
```

## File: facebookresearch_3detr/third_party/pointnet2/pointnet2_test.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping using radii, nsamples, and mlps for point cloud feature extraction', 'build a PointnetSAModuleVotes layer with max avg or rbf pooling for vote net point cloud processing', 'build a PointnetFPModule layer to propagate features from known to unknown points via inverse distance weighted interpolation', 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping to propagate features between point sets', 'run the PointnetSAModuleMSG module on random xyz coordinates and features tensors to extract downsampled point cloud features', 'test the gradient correctness of pointnet2_utils three_interpolate using PyTorch gradcheck', 'run the pointnet2 three interpolate gradient test to verify autograd correctness', 'review the test_interpolation_grad function that validates three_interpolate gradients with hardcoded indices and weights', 'summarize the nested interpolate_func that calls pointnet2_utils three_interpolate with index and weight tensors', 'refactor test_interpolation_grad to parameterize batch size, feature dimension, and number of points', 'sample npoint features from a point cloud using iterative furthest point sampling on xyz coordinates', 'gather selected point features by index from a (B, C, N) feature tensor using gathered indices', 'find the three nearest neighbors of unknown points in a known point set and return distances and indices', 'query points within a given radius around center points and return indices of features in each ball', 'group point cloud features using ball query with radius and optional xyz normalization and uniform sampling', 'build a SharedMLP module with a list of channel sizes for PointNet2 feature extraction', 'create a Conv2d layer with optional batch norm and ReLU activation for 2D convolution', 'create a Conv1d layer with optional batch norm and preact mode for 1D convolution', 'create a Conv3d layer with optional batch norm and kaiming init for 3D convolution', 'create a BNMomentumScheduler to adjust batch norm momentum per epoch using a lambda function']
```

Usage

```
{'test_interpolation_grad': 'test the gradient correctness of pointnet2_utils three_interpolate using PyTorch gradcheck', 'run_interpolation_test': 'run the pointnet2 three interpolate gradient test to verify autograd correctness', 'review_test_interpolation_grad': 'review the test_interpolation_grad function that validates three_interpolate gradients with hardcoded indices and weights', 'summarize_interpolate_func': 'summarize the nested interpolate_func that calls pointnet2_utils three_interpolate with index and weight tensors', 'refactor_test_interpolation_grad': 'refactor test_interpolation_grad to parameterize batch size, feature dimension, and number of points'}
```

## File: facebookresearch_3detr/third_party/pointnet2/pointnet2_utils.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping using radii, nsamples, and mlps for point cloud feature extraction', 'build a PointnetSAModuleVotes layer with max avg or rbf pooling for vote net point cloud processing', 'build a PointnetFPModule layer to propagate features from known to unknown points via inverse distance weighted interpolation', 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping to propagate features between point sets', 'run the PointnetSAModuleMSG module on random xyz coordinates and features tensors to extract downsampled point cloud features', 'test the gradient correctness of pointnet2_utils three_interpolate using PyTorch gradcheck', 'run the pointnet2 three interpolate gradient test to verify autograd correctness', 'review the test_interpolation_grad function that validates three_interpolate gradients with hardcoded indices and weights', 'summarize the nested interpolate_func that calls pointnet2_utils three_interpolate with index and weight tensors', 'refactor test_interpolation_grad to parameterize batch size, feature dimension, and number of points', 'sample npoint features from a point cloud using iterative furthest point sampling on xyz coordinates', 'gather selected point features by index from a (B, C, N) feature tensor using gathered indices', 'find the three nearest neighbors of unknown points in a known point set and return distances and indices', 'query points within a given radius around center points and return indices of features in each ball', 'group point cloud features using ball query with radius and optional xyz normalization and uniform sampling', 'build a SharedMLP module with a list of channel sizes for PointNet2 feature extraction', 'create a Conv2d layer with optional batch norm and ReLU activation for 2D convolution', 'create a Conv1d layer with optional batch norm and preact mode for 1D convolution', 'create a Conv3d layer with optional batch norm and kaiming init for 3D convolution', 'create a BNMomentumScheduler to adjust batch norm momentum per epoch using a lambda function']
```

Usage

```
{'furthest_point_sample': 'sample npoint features from a point cloud using iterative furthest point sampling on xyz coordinates', 'gather_operation': 'gather selected point features by index from a (B, C, N) feature tensor using gathered indices', 'three_nn': 'find the three nearest neighbors of unknown points in a known point set and return distances and indices', 'ball_query': 'query points within a given radius around center points and return indices of features in each ball', 'query_and_group': 'group point cloud features using ball query with radius and optional xyz normalization and uniform sampling'}
```

## File: facebookresearch_3detr/third_party/pointnet2/pytorch_utils.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping using radii, nsamples, and mlps for point cloud feature extraction', 'build a PointnetSAModuleVotes layer with max avg or rbf pooling for vote net point cloud processing', 'build a PointnetFPModule layer to propagate features from known to unknown points via inverse distance weighted interpolation', 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping to propagate features between point sets', 'run the PointnetSAModuleMSG module on random xyz coordinates and features tensors to extract downsampled point cloud features', 'test the gradient correctness of pointnet2_utils three_interpolate using PyTorch gradcheck', 'run the pointnet2 three interpolate gradient test to verify autograd correctness', 'review the test_interpolation_grad function that validates three_interpolate gradients with hardcoded indices and weights', 'summarize the nested interpolate_func that calls pointnet2_utils three_interpolate with index and weight tensors', 'refactor test_interpolation_grad to parameterize batch size, feature dimension, and number of points', 'sample npoint features from a point cloud using iterative furthest point sampling on xyz coordinates', 'gather selected point features by index from a (B, C, N) feature tensor using gathered indices', 'find the three nearest neighbors of unknown points in a known point set and return distances and indices', 'query points within a given radius around center points and return indices of features in each ball', 'group point cloud features using ball query with radius and optional xyz normalization and uniform sampling', 'build a SharedMLP module with a list of channel sizes for PointNet2 feature extraction', 'create a Conv2d layer with optional batch norm and ReLU activation for 2D convolution', 'create a Conv1d layer with optional batch norm and preact mode for 1D convolution', 'create a Conv3d layer with optional batch norm and kaiming init for 3D convolution', 'create a BNMomentumScheduler to adjust batch norm momentum per epoch using a lambda function']
```

Usage

```
{'build_shared_mlp': 'build a SharedMLP module with a list of channel sizes for PointNet2 feature extraction', 'create_conv2d_layer': 'create a Conv2d layer with optional batch norm and ReLU activation for 2D convolution', 'create_conv1d_layer': 'create a Conv1d layer with optional batch norm and preact mode for 1D convolution', 'create_conv3d_layer': 'create a Conv3d layer with optional batch norm and kaiming init for 3D convolution', 'create_bn_momentum_scheduler': 'create a BNMomentumScheduler to adjust batch norm momentum per epoch using a lambda function'}
```

