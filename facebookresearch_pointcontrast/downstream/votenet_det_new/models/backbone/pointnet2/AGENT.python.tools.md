# Agent Python Tools

- repo: facebookresearch/pointcontrast
- repo_uri: https://github.com/facebookresearch/pointcontrast

## File: facebookresearch_pointcontrast/downstream/votenet_det_new/models/backbone/pointnet2/pointnet2_modules.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping for point cloud feature extraction', 'create a PointnetSAModuleVotes layer supporting point indices for VoteNet ground truth votes', 'run a PointnetFPModule to propagate features from one point set to another via interpolation', 'test the PointnetSAModuleMSGVotes class with custom radii and nsamples for multiscale grouping', 'refactor the PointnetLFPModuleMSG learnable feature propagation layer to support additional pooling strategies', 'test the gradient computation of pointnet2_utils three_interpolate using torch autograd gradcheck', 'run the pointnet2 three interpolate gradient test to verify custom ops correctness', 'review the test_interpolation_grad function that validates three_interpolate gradients with random features', 'summarize the test_interpolation_grad function which checks gradient correctness for pointnet2 interpolation', 'refactor the test_interpolation_grad function to use parameterized test cases for different batch sizes', 'build a module that uses furthest point sampling to select npoint features with largest minimum distance from a point cloud', 'create a QueryAndGroup module to perform ball query and group nearby point features by radius and nsample', 'test the three nearest neighbor search and three interpolate functions for point cloud feature interpolation', 'refactor the GatherOperation to gather specific point features by index from a batched feature tensor', 'review the GroupAll module that groups all point features together into a single batch tensor', 'build a SharedMLP module with a list of channel sizes for 2D convolutional layers', 'create a Conv2d layer with optional batch normalization and ReLU activation', 'create a Conv1d layer with optional batch normalization and kaiming weight initialization', 'create a fully connected layer with optional batch normalization and preactivation support', 'create a BNMomentumScheduler to schedule batch norm momentum across training epochs']
```

Usage

```
{'build_PointnetSAModuleMSG': 'build a PointnetSAModuleMSG layer with multiscale grouping for point cloud feature extraction', 'create_PointnetSAModuleVotes': 'create a PointnetSAModuleVotes layer supporting point indices for VoteNet ground truth votes', 'run_PointnetFPModule': 'run a PointnetFPModule to propagate features from one point set to another via interpolation', 'test_PointnetSAModuleMSGVotes': 'test the PointnetSAModuleMSGVotes class with custom radii and nsamples for multiscale grouping', 'refactor_PointnetLFPModuleMSG': 'refactor the PointnetLFPModuleMSG learnable feature propagation layer to support additional pooling strategies'}
```

## File: facebookresearch_pointcontrast/downstream/votenet_det_new/models/backbone/pointnet2/pointnet2_test.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping for point cloud feature extraction', 'create a PointnetSAModuleVotes layer supporting point indices for VoteNet ground truth votes', 'run a PointnetFPModule to propagate features from one point set to another via interpolation', 'test the PointnetSAModuleMSGVotes class with custom radii and nsamples for multiscale grouping', 'refactor the PointnetLFPModuleMSG learnable feature propagation layer to support additional pooling strategies', 'test the gradient computation of pointnet2_utils three_interpolate using torch autograd gradcheck', 'run the pointnet2 three interpolate gradient test to verify custom ops correctness', 'review the test_interpolation_grad function that validates three_interpolate gradients with random features', 'summarize the test_interpolation_grad function which checks gradient correctness for pointnet2 interpolation', 'refactor the test_interpolation_grad function to use parameterized test cases for different batch sizes', 'build a module that uses furthest point sampling to select npoint features with largest minimum distance from a point cloud', 'create a QueryAndGroup module to perform ball query and group nearby point features by radius and nsample', 'test the three nearest neighbor search and three interpolate functions for point cloud feature interpolation', 'refactor the GatherOperation to gather specific point features by index from a batched feature tensor', 'review the GroupAll module that groups all point features together into a single batch tensor', 'build a SharedMLP module with a list of channel sizes for 2D convolutional layers', 'create a Conv2d layer with optional batch normalization and ReLU activation', 'create a Conv1d layer with optional batch normalization and kaiming weight initialization', 'create a fully connected layer with optional batch normalization and preactivation support', 'create a BNMomentumScheduler to schedule batch norm momentum across training epochs']
```

Usage

```
{'test_interpolation_grad': 'test the gradient computation of pointnet2_utils three_interpolate using torch autograd gradcheck', 'run_interpolation_grad_test': 'run the pointnet2 three interpolate gradient test to verify custom ops correctness', 'review_test_interpolation_grad': 'review the test_interpolation_grad function that validates three_interpolate gradients with random features', 'summarize_test_interpolation_grad': 'summarize the test_interpolation_grad function which checks gradient correctness for pointnet2 interpolation', 'refactor_test_interpolation_grad': 'refactor the test_interpolation_grad function to use parameterized test cases for different batch sizes'}
```

## File: facebookresearch_pointcontrast/downstream/votenet_det_new/models/backbone/pointnet2/pointnet2_utils.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping for point cloud feature extraction', 'create a PointnetSAModuleVotes layer supporting point indices for VoteNet ground truth votes', 'run a PointnetFPModule to propagate features from one point set to another via interpolation', 'test the PointnetSAModuleMSGVotes class with custom radii and nsamples for multiscale grouping', 'refactor the PointnetLFPModuleMSG learnable feature propagation layer to support additional pooling strategies', 'test the gradient computation of pointnet2_utils three_interpolate using torch autograd gradcheck', 'run the pointnet2 three interpolate gradient test to verify custom ops correctness', 'review the test_interpolation_grad function that validates three_interpolate gradients with random features', 'summarize the test_interpolation_grad function which checks gradient correctness for pointnet2 interpolation', 'refactor the test_interpolation_grad function to use parameterized test cases for different batch sizes', 'build a module that uses furthest point sampling to select npoint features with largest minimum distance from a point cloud', 'create a QueryAndGroup module to perform ball query and group nearby point features by radius and nsample', 'test the three nearest neighbor search and three interpolate functions for point cloud feature interpolation', 'refactor the GatherOperation to gather specific point features by index from a batched feature tensor', 'review the GroupAll module that groups all point features together into a single batch tensor', 'build a SharedMLP module with a list of channel sizes for 2D convolutional layers', 'create a Conv2d layer with optional batch normalization and ReLU activation', 'create a Conv1d layer with optional batch normalization and kaiming weight initialization', 'create a fully connected layer with optional batch normalization and preactivation support', 'create a BNMomentumScheduler to schedule batch norm momentum across training epochs']
```

Usage

```
{'build_furthest_point_sampling': 'build a module that uses furthest point sampling to select npoint features with largest minimum distance from a point cloud', 'create_ball_query_grouping': 'create a QueryAndGroup module to perform ball query and group nearby point features by radius and nsample', 'test_three_nn_interpolate': 'test the three nearest neighbor search and three interpolate functions for point cloud feature interpolation', 'refactor_gather_operation': 'refactor the GatherOperation to gather specific point features by index from a batched feature tensor', 'review_groupall_module': 'review the GroupAll module that groups all point features together into a single batch tensor'}
```

## File: facebookresearch_pointcontrast/downstream/votenet_det_new/models/backbone/pointnet2/pytorch_utils.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping for point cloud feature extraction', 'create a PointnetSAModuleVotes layer supporting point indices for VoteNet ground truth votes', 'run a PointnetFPModule to propagate features from one point set to another via interpolation', 'test the PointnetSAModuleMSGVotes class with custom radii and nsamples for multiscale grouping', 'refactor the PointnetLFPModuleMSG learnable feature propagation layer to support additional pooling strategies', 'test the gradient computation of pointnet2_utils three_interpolate using torch autograd gradcheck', 'run the pointnet2 three interpolate gradient test to verify custom ops correctness', 'review the test_interpolation_grad function that validates three_interpolate gradients with random features', 'summarize the test_interpolation_grad function which checks gradient correctness for pointnet2 interpolation', 'refactor the test_interpolation_grad function to use parameterized test cases for different batch sizes', 'build a module that uses furthest point sampling to select npoint features with largest minimum distance from a point cloud', 'create a QueryAndGroup module to perform ball query and group nearby point features by radius and nsample', 'test the three nearest neighbor search and three interpolate functions for point cloud feature interpolation', 'refactor the GatherOperation to gather specific point features by index from a batched feature tensor', 'review the GroupAll module that groups all point features together into a single batch tensor', 'build a SharedMLP module with a list of channel sizes for 2D convolutional layers', 'create a Conv2d layer with optional batch normalization and ReLU activation', 'create a Conv1d layer with optional batch normalization and kaiming weight initialization', 'create a fully connected layer with optional batch normalization and preactivation support', 'create a BNMomentumScheduler to schedule batch norm momentum across training epochs']
```

Usage

```
{'build_SharedMLP': 'build a SharedMLP module with a list of channel sizes for 2D convolutional layers', 'create_Conv2d': 'create a Conv2d layer with optional batch normalization and ReLU activation', 'create_Conv1d': 'create a Conv1d layer with optional batch normalization and kaiming weight initialization', 'create_FC': 'create a fully connected layer with optional batch normalization and preactivation support', 'create_BNMomentumScheduler': 'create a BNMomentumScheduler to schedule batch norm momentum across training epochs'}
```

