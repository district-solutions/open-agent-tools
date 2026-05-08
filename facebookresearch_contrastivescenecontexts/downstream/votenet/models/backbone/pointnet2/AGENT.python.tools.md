# Agent Python Tools

- repo: facebookresearch/contrastivescenecontexts
- repo_uri: https://github.com/facebookresearch/contrastivescenecontexts

## File: facebookresearch_contrastivescenecontexts/downstream/votenet/models/backbone/pointnet2/pointnet2_modules.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping for 3D point cloud feature extraction', 'build a PointnetSAModuleVotes layer with RBF pooling and point index support for VoteNet', 'build a PointnetFPModule layer to propagate features from one point set to another via interpolation', 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping', 'test the PointnetSAModuleMSG forward pass and backward gradient computation on sample point clouds', 'test the gradient correctness of pointnet2_utils three_interpolate using torch autograd gradcheck', 'run the interpolation gradient test to verify pointnet2_utils three_interpolate backward pass', 'review the test_interpolation_grad function that validates three_interpolate gradients with random features', 'summarize the test_interpolation_grad function which checks gradient accuracy for three interpolate operations', 'refactor the test_interpolation_grad function to use different batch sizes or feature dimensions', 'build a module that uses furthest_point_sample to iteratively sample N points from a point cloud by largest minimum distance', 'create a function that uses ball_query to find all points within a given radius around each center point', 'test the QueryAndGroup module to group nearby point features using ball query and return grouped tensors', 'refactor the GroupAll module to group all point features into a single set for global pooling', 'review the ThreeNN and ThreeInterpolate functions for finding nearest neighbors and performing weighted interpolation on point cloud features', 'create a SharedMLP module with a list of channel sizes for 2D convolutional layers', 'build a Conv2d module with optional batch normalization and ReLU activation for feature extraction', 'create a Conv1d module with configurable kernel size, stride, padding, and batch normalization', 'create a fully connected layer module with optional batch normalization and pre-activation support', 'build a BNMomentumScheduler to dynamically adjust batch norm momentum across training epochs']
```

Usage

```
{'build_PointnetSAModuleMSG': 'build a PointnetSAModuleMSG layer with multiscale grouping for 3D point cloud feature extraction', 'build_PointnetSAModuleVotes': 'build a PointnetSAModuleVotes layer with RBF pooling and point index support for VoteNet', 'build_PointnetFPModule': 'build a PointnetFPModule layer to propagate features from one point set to another via interpolation', 'build_PointnetLFPModuleMSG': 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping', 'test_PointnetSAModuleMSG': 'test the PointnetSAModuleMSG forward pass and backward gradient computation on sample point clouds'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/votenet/models/backbone/pointnet2/pointnet2_test.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping for 3D point cloud feature extraction', 'build a PointnetSAModuleVotes layer with RBF pooling and point index support for VoteNet', 'build a PointnetFPModule layer to propagate features from one point set to another via interpolation', 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping', 'test the PointnetSAModuleMSG forward pass and backward gradient computation on sample point clouds', 'test the gradient correctness of pointnet2_utils three_interpolate using torch autograd gradcheck', 'run the interpolation gradient test to verify pointnet2_utils three_interpolate backward pass', 'review the test_interpolation_grad function that validates three_interpolate gradients with random features', 'summarize the test_interpolation_grad function which checks gradient accuracy for three interpolate operations', 'refactor the test_interpolation_grad function to use different batch sizes or feature dimensions', 'build a module that uses furthest_point_sample to iteratively sample N points from a point cloud by largest minimum distance', 'create a function that uses ball_query to find all points within a given radius around each center point', 'test the QueryAndGroup module to group nearby point features using ball query and return grouped tensors', 'refactor the GroupAll module to group all point features into a single set for global pooling', 'review the ThreeNN and ThreeInterpolate functions for finding nearest neighbors and performing weighted interpolation on point cloud features', 'create a SharedMLP module with a list of channel sizes for 2D convolutional layers', 'build a Conv2d module with optional batch normalization and ReLU activation for feature extraction', 'create a Conv1d module with configurable kernel size, stride, padding, and batch normalization', 'create a fully connected layer module with optional batch normalization and pre-activation support', 'build a BNMomentumScheduler to dynamically adjust batch norm momentum across training epochs']
```

Usage

```
{'test_interpolation_grad': 'test the gradient correctness of pointnet2_utils three_interpolate using torch autograd gradcheck', 'run_test_interpolation_grad': 'run the interpolation gradient test to verify pointnet2_utils three_interpolate backward pass', 'review_test_interpolation_grad': 'review the test_interpolation_grad function that validates three_interpolate gradients with random features', 'summarize_test_interpolation_grad': 'summarize the test_interpolation_grad function which checks gradient accuracy for three interpolate operations', 'refactor_test_interpolation_grad': 'refactor the test_interpolation_grad function to use different batch sizes or feature dimensions'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/votenet/models/backbone/pointnet2/pointnet2_utils.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping for 3D point cloud feature extraction', 'build a PointnetSAModuleVotes layer with RBF pooling and point index support for VoteNet', 'build a PointnetFPModule layer to propagate features from one point set to another via interpolation', 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping', 'test the PointnetSAModuleMSG forward pass and backward gradient computation on sample point clouds', 'test the gradient correctness of pointnet2_utils three_interpolate using torch autograd gradcheck', 'run the interpolation gradient test to verify pointnet2_utils three_interpolate backward pass', 'review the test_interpolation_grad function that validates three_interpolate gradients with random features', 'summarize the test_interpolation_grad function which checks gradient accuracy for three interpolate operations', 'refactor the test_interpolation_grad function to use different batch sizes or feature dimensions', 'build a module that uses furthest_point_sample to iteratively sample N points from a point cloud by largest minimum distance', 'create a function that uses ball_query to find all points within a given radius around each center point', 'test the QueryAndGroup module to group nearby point features using ball query and return grouped tensors', 'refactor the GroupAll module to group all point features into a single set for global pooling', 'review the ThreeNN and ThreeInterpolate functions for finding nearest neighbors and performing weighted interpolation on point cloud features', 'create a SharedMLP module with a list of channel sizes for 2D convolutional layers', 'build a Conv2d module with optional batch normalization and ReLU activation for feature extraction', 'create a Conv1d module with configurable kernel size, stride, padding, and batch normalization', 'create a fully connected layer module with optional batch normalization and pre-activation support', 'build a BNMomentumScheduler to dynamically adjust batch norm momentum across training epochs']
```

Usage

```
{'build_furthest_point_sampling': 'build a module that uses furthest_point_sample to iteratively sample N points from a point cloud by largest minimum distance', 'create_ball_query': 'create a function that uses ball_query to find all points within a given radius around each center point', 'test_query_and_group': 'test the QueryAndGroup module to group nearby point features using ball query and return grouped tensors', 'refactor_group_all': 'refactor the GroupAll module to group all point features into a single set for global pooling', 'review_three_nn_interpolate': 'review the ThreeNN and ThreeInterpolate functions for finding nearest neighbors and performing weighted interpolation on point cloud features'}
```

## File: facebookresearch_contrastivescenecontexts/downstream/votenet/models/backbone/pointnet2/pytorch_utils.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping for 3D point cloud feature extraction', 'build a PointnetSAModuleVotes layer with RBF pooling and point index support for VoteNet', 'build a PointnetFPModule layer to propagate features from one point set to another via interpolation', 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping', 'test the PointnetSAModuleMSG forward pass and backward gradient computation on sample point clouds', 'test the gradient correctness of pointnet2_utils three_interpolate using torch autograd gradcheck', 'run the interpolation gradient test to verify pointnet2_utils three_interpolate backward pass', 'review the test_interpolation_grad function that validates three_interpolate gradients with random features', 'summarize the test_interpolation_grad function which checks gradient accuracy for three interpolate operations', 'refactor the test_interpolation_grad function to use different batch sizes or feature dimensions', 'build a module that uses furthest_point_sample to iteratively sample N points from a point cloud by largest minimum distance', 'create a function that uses ball_query to find all points within a given radius around each center point', 'test the QueryAndGroup module to group nearby point features using ball query and return grouped tensors', 'refactor the GroupAll module to group all point features into a single set for global pooling', 'review the ThreeNN and ThreeInterpolate functions for finding nearest neighbors and performing weighted interpolation on point cloud features', 'create a SharedMLP module with a list of channel sizes for 2D convolutional layers', 'build a Conv2d module with optional batch normalization and ReLU activation for feature extraction', 'create a Conv1d module with configurable kernel size, stride, padding, and batch normalization', 'create a fully connected layer module with optional batch normalization and pre-activation support', 'build a BNMomentumScheduler to dynamically adjust batch norm momentum across training epochs']
```

Usage

```
{'create_SharedMLP': 'create a SharedMLP module with a list of channel sizes for 2D convolutional layers', 'build_Conv2d': 'build a Conv2d module with optional batch normalization and ReLU activation for feature extraction', 'create_Conv1d': 'create a Conv1d module with configurable kernel size, stride, padding, and batch normalization', 'create_FC': 'create a fully connected layer module with optional batch normalization and pre-activation support', 'build_BNMomentumScheduler': 'build a BNMomentumScheduler to dynamically adjust batch norm momentum across training epochs'}
```

