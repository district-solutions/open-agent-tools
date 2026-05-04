# Agent Python Tools

- repo: facebookresearch/depthcontrast
- repo_uri: https://github.com/facebookresearch/depthcontrast

## File: facebookresearch_depthcontrast/third_party/pointnet2/pointnet2_modules.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping for point cloud feature extraction', 'build a single-scale PointnetSAModule layer for point cloud set abstraction', 'build a PointnetSAModuleVotes layer with RBF pooling and point index support for votenet', 'build a PointnetFPModule layer to propagate features from one point set to another via interpolation', 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping', 'test the three_interpolate gradient computation using PyTorch gradcheck with random feature tensors', 'run the pointnet2 interpolation gradient test to verify customized ops correctness', 'review the test_interpolation_grad function that validates three_interpolate gradients with atol and rtol tolerances', 'summarize the interpolate_func nested helper that calls pointnet2_utils three_interpolate with hardcoded indices and weights', 'refactor the test_interpolation_grad function to parameterize batch size feature dim and point count', 'build a python module to run furthest point sampling on a point cloud tensor and return sampled indices', 'build a python module to gather features from a tensor by index and return the selected features', 'build a python module to perform ball query on point cloud coordinates and return neighborhood indices', 'build a python module to use QueryAndGroup for ball query grouping with radius and nsample parameters', 'build a python module to use GroupAll to group all point cloud features into a single group', 'build a SharedMLP module with a list of channel sizes for 2D convolutional layers', 'create a Conv2d layer with optional batch normalization and ReLU activation for point cloud features', 'create a BNMomentumScheduler to dynamically adjust batch norm momentum across training epochs', 'build a fully connected layer with optional batch normalization and preactivation support', 'review the BatchNorm1d wrapper class that initializes batch norm weights to 1 and bias to 0']
```

Usage

```
{'build_PointnetSAModuleMSG': 'build a PointnetSAModuleMSG layer with multiscale grouping for point cloud feature extraction', 'build_PointnetSAModule': 'build a single-scale PointnetSAModule layer for point cloud set abstraction', 'build_PointnetSAModuleVotes': 'build a PointnetSAModuleVotes layer with RBF pooling and point index support for votenet', 'build_PointnetFPModule': 'build a PointnetFPModule layer to propagate features from one point set to another via interpolation', 'build_PointnetLFPModuleMSG': 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping'}
```

## File: facebookresearch_depthcontrast/third_party/pointnet2/pointnet2_test.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping for point cloud feature extraction', 'build a single-scale PointnetSAModule layer for point cloud set abstraction', 'build a PointnetSAModuleVotes layer with RBF pooling and point index support for votenet', 'build a PointnetFPModule layer to propagate features from one point set to another via interpolation', 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping', 'test the three_interpolate gradient computation using PyTorch gradcheck with random feature tensors', 'run the pointnet2 interpolation gradient test to verify customized ops correctness', 'review the test_interpolation_grad function that validates three_interpolate gradients with atol and rtol tolerances', 'summarize the interpolate_func nested helper that calls pointnet2_utils three_interpolate with hardcoded indices and weights', 'refactor the test_interpolation_grad function to parameterize batch size feature dim and point count', 'build a python module to run furthest point sampling on a point cloud tensor and return sampled indices', 'build a python module to gather features from a tensor by index and return the selected features', 'build a python module to perform ball query on point cloud coordinates and return neighborhood indices', 'build a python module to use QueryAndGroup for ball query grouping with radius and nsample parameters', 'build a python module to use GroupAll to group all point cloud features into a single group', 'build a SharedMLP module with a list of channel sizes for 2D convolutional layers', 'create a Conv2d layer with optional batch normalization and ReLU activation for point cloud features', 'create a BNMomentumScheduler to dynamically adjust batch norm momentum across training epochs', 'build a fully connected layer with optional batch normalization and preactivation support', 'review the BatchNorm1d wrapper class that initializes batch norm weights to 1 and bias to 0']
```

Usage

```
{'test_interpolation_grad': 'test the three_interpolate gradient computation using PyTorch gradcheck with random feature tensors', 'run_pointnet2_test': 'run the pointnet2 interpolation gradient test to verify customized ops correctness', 'review_test_interpolation_grad': 'review the test_interpolation_grad function that validates three_interpolate gradients with atol and rtol tolerances', 'summarize_interpolate_func': 'summarize the interpolate_func nested helper that calls pointnet2_utils three_interpolate with hardcoded indices and weights', 'refactor_test_interpolation_grad': 'refactor the test_interpolation_grad function to parameterize batch size feature dim and point count'}
```

## File: facebookresearch_depthcontrast/third_party/pointnet2/pointnet2_utils.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping for point cloud feature extraction', 'build a single-scale PointnetSAModule layer for point cloud set abstraction', 'build a PointnetSAModuleVotes layer with RBF pooling and point index support for votenet', 'build a PointnetFPModule layer to propagate features from one point set to another via interpolation', 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping', 'test the three_interpolate gradient computation using PyTorch gradcheck with random feature tensors', 'run the pointnet2 interpolation gradient test to verify customized ops correctness', 'review the test_interpolation_grad function that validates three_interpolate gradients with atol and rtol tolerances', 'summarize the interpolate_func nested helper that calls pointnet2_utils three_interpolate with hardcoded indices and weights', 'refactor the test_interpolation_grad function to parameterize batch size feature dim and point count', 'build a python module to run furthest point sampling on a point cloud tensor and return sampled indices', 'build a python module to gather features from a tensor by index and return the selected features', 'build a python module to perform ball query on point cloud coordinates and return neighborhood indices', 'build a python module to use QueryAndGroup for ball query grouping with radius and nsample parameters', 'build a python module to use GroupAll to group all point cloud features into a single group', 'build a SharedMLP module with a list of channel sizes for 2D convolutional layers', 'create a Conv2d layer with optional batch normalization and ReLU activation for point cloud features', 'create a BNMomentumScheduler to dynamically adjust batch norm momentum across training epochs', 'build a fully connected layer with optional batch normalization and preactivation support', 'review the BatchNorm1d wrapper class that initializes batch norm weights to 1 and bias to 0']
```

Usage

```
{'build_furthest_point_sample': 'build a python module to run furthest point sampling on a point cloud tensor and return sampled indices', 'build_gather_operation': 'build a python module to gather features from a tensor by index and return the selected features', 'build_ball_query': 'build a python module to perform ball query on point cloud coordinates and return neighborhood indices', 'build_query_and_group': 'build a python module to use QueryAndGroup for ball query grouping with radius and nsample parameters', 'build_group_all': 'build a python module to use GroupAll to group all point cloud features into a single group'}
```

## File: facebookresearch_depthcontrast/third_party/pointnet2/pytorch_utils.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping for point cloud feature extraction', 'build a single-scale PointnetSAModule layer for point cloud set abstraction', 'build a PointnetSAModuleVotes layer with RBF pooling and point index support for votenet', 'build a PointnetFPModule layer to propagate features from one point set to another via interpolation', 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping', 'test the three_interpolate gradient computation using PyTorch gradcheck with random feature tensors', 'run the pointnet2 interpolation gradient test to verify customized ops correctness', 'review the test_interpolation_grad function that validates three_interpolate gradients with atol and rtol tolerances', 'summarize the interpolate_func nested helper that calls pointnet2_utils three_interpolate with hardcoded indices and weights', 'refactor the test_interpolation_grad function to parameterize batch size feature dim and point count', 'build a python module to run furthest point sampling on a point cloud tensor and return sampled indices', 'build a python module to gather features from a tensor by index and return the selected features', 'build a python module to perform ball query on point cloud coordinates and return neighborhood indices', 'build a python module to use QueryAndGroup for ball query grouping with radius and nsample parameters', 'build a python module to use GroupAll to group all point cloud features into a single group', 'build a SharedMLP module with a list of channel sizes for 2D convolutional layers', 'create a Conv2d layer with optional batch normalization and ReLU activation for point cloud features', 'create a BNMomentumScheduler to dynamically adjust batch norm momentum across training epochs', 'build a fully connected layer with optional batch normalization and preactivation support', 'review the BatchNorm1d wrapper class that initializes batch norm weights to 1 and bias to 0']
```

Usage

```
{'build_SharedMLP': 'build a SharedMLP module with a list of channel sizes for 2D convolutional layers', 'create_Conv2d': 'create a Conv2d layer with optional batch normalization and ReLU activation for point cloud features', 'create_BNMomentumScheduler': 'create a BNMomentumScheduler to dynamically adjust batch norm momentum across training epochs', 'build_FC': 'build a fully connected layer with optional batch normalization and preactivation support', 'review_BatchNorm1d': 'review the BatchNorm1d wrapper class that initializes batch norm weights to 1 and bias to 0'}
```

