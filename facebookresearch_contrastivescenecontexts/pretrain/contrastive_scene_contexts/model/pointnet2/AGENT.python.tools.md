# Agent Python Tools

- repo: facebookresearch/contrastivescenecontexts
- repo_uri: https://github.com/facebookresearch/contrastivescenecontexts

## File: facebookresearch_contrastivescenecontexts/pretrain/contrastive_scene_contexts/model/pointnet2/pointnet2_modules.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping for point cloud feature extraction', 'build a PointnetSAModuleVotes layer with RBF pooling and point index support for votenet', 'build a PointnetFPModule layer to propagate features from one point set to another via interpolation', 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping', 'test the PointnetSAModuleMSG forward pass and backward gradient computation on sample point clouds', 'test the three_interpolate gradient correctness using torch.autograd.gradcheck on CUDA tensors', 'run the pointnet2 interpolation gradient test via the main entry point', 'review the test_interpolation_grad function to verify gradcheck tolerances and tensor shapes', 'refactor test_interpolation_grad to parameterize batch size, feature dimension, and sample count', 'summarize the pointnet2_test module which validates three_interpolate gradient computation', 'sample points from a point cloud using iterative furthest point sampling to select npoint features', 'find all points within a given radius of center points in a 3D point cloud', 'group nearby point cloud features using ball query with radius and optional xyz normalization', 'gather specific feature vectors from a tensor by index for point cloud processing', 'interpolate features using weighted linear interpolation from three nearest neighbors in a point cloud', 'build a SharedMLP module with a list of channel sizes for 2D conv layers', 'create a Conv2d layer with optional batch normalization and ReLU activation', 'create a Conv1d layer with optional batch normalization and kaiming weight init', 'create a BNMomentumScheduler to adjust batch norm momentum per training epoch', 'review the FC class that builds a linear layer with optional batch norm and activation']
```

Usage

```
{'build_PointnetSAModuleMSG': 'build a PointnetSAModuleMSG layer with multiscale grouping for point cloud feature extraction', 'build_PointnetSAModuleVotes': 'build a PointnetSAModuleVotes layer with RBF pooling and point index support for votenet', 'build_PointnetFPModule': 'build a PointnetFPModule layer to propagate features from one point set to another via interpolation', 'build_PointnetLFPModuleMSG': 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping', 'test_PointnetSAModuleMSG': 'test the PointnetSAModuleMSG forward pass and backward gradient computation on sample point clouds'}
```

## File: facebookresearch_contrastivescenecontexts/pretrain/contrastive_scene_contexts/model/pointnet2/pointnet2_test.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping for point cloud feature extraction', 'build a PointnetSAModuleVotes layer with RBF pooling and point index support for votenet', 'build a PointnetFPModule layer to propagate features from one point set to another via interpolation', 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping', 'test the PointnetSAModuleMSG forward pass and backward gradient computation on sample point clouds', 'test the three_interpolate gradient correctness using torch.autograd.gradcheck on CUDA tensors', 'run the pointnet2 interpolation gradient test via the main entry point', 'review the test_interpolation_grad function to verify gradcheck tolerances and tensor shapes', 'refactor test_interpolation_grad to parameterize batch size, feature dimension, and sample count', 'summarize the pointnet2_test module which validates three_interpolate gradient computation', 'sample points from a point cloud using iterative furthest point sampling to select npoint features', 'find all points within a given radius of center points in a 3D point cloud', 'group nearby point cloud features using ball query with radius and optional xyz normalization', 'gather specific feature vectors from a tensor by index for point cloud processing', 'interpolate features using weighted linear interpolation from three nearest neighbors in a point cloud', 'build a SharedMLP module with a list of channel sizes for 2D conv layers', 'create a Conv2d layer with optional batch normalization and ReLU activation', 'create a Conv1d layer with optional batch normalization and kaiming weight init', 'create a BNMomentumScheduler to adjust batch norm momentum per training epoch', 'review the FC class that builds a linear layer with optional batch norm and activation']
```

Usage

```
{'test_interpolation_grad': 'test the three_interpolate gradient correctness using torch.autograd.gradcheck on CUDA tensors', 'run_pointnet2_test': 'run the pointnet2 interpolation gradient test via the main entry point', 'review_test_interpolation_grad': 'review the test_interpolation_grad function to verify gradcheck tolerances and tensor shapes', 'refactor_test_interpolation_grad': 'refactor test_interpolation_grad to parameterize batch size, feature dimension, and sample count', 'summarize_pointnet2_test': 'summarize the pointnet2_test module which validates three_interpolate gradient computation'}
```

## File: facebookresearch_contrastivescenecontexts/pretrain/contrastive_scene_contexts/model/pointnet2/pointnet2_utils.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping for point cloud feature extraction', 'build a PointnetSAModuleVotes layer with RBF pooling and point index support for votenet', 'build a PointnetFPModule layer to propagate features from one point set to another via interpolation', 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping', 'test the PointnetSAModuleMSG forward pass and backward gradient computation on sample point clouds', 'test the three_interpolate gradient correctness using torch.autograd.gradcheck on CUDA tensors', 'run the pointnet2 interpolation gradient test via the main entry point', 'review the test_interpolation_grad function to verify gradcheck tolerances and tensor shapes', 'refactor test_interpolation_grad to parameterize batch size, feature dimension, and sample count', 'summarize the pointnet2_test module which validates three_interpolate gradient computation', 'sample points from a point cloud using iterative furthest point sampling to select npoint features', 'find all points within a given radius of center points in a 3D point cloud', 'group nearby point cloud features using ball query with radius and optional xyz normalization', 'gather specific feature vectors from a tensor by index for point cloud processing', 'interpolate features using weighted linear interpolation from three nearest neighbors in a point cloud', 'build a SharedMLP module with a list of channel sizes for 2D conv layers', 'create a Conv2d layer with optional batch normalization and ReLU activation', 'create a Conv1d layer with optional batch normalization and kaiming weight init', 'create a BNMomentumScheduler to adjust batch norm momentum per training epoch', 'review the FC class that builds a linear layer with optional batch norm and activation']
```

Usage

```
{'furthest_point_sample': 'sample points from a point cloud using iterative furthest point sampling to select npoint features', 'ball_query': 'find all points within a given radius of center points in a 3D point cloud', 'query_and_group': 'group nearby point cloud features using ball query with radius and optional xyz normalization', 'gather_operation': 'gather specific feature vectors from a tensor by index for point cloud processing', 'three_interpolate': 'interpolate features using weighted linear interpolation from three nearest neighbors in a point cloud'}
```

## File: facebookresearch_contrastivescenecontexts/pretrain/contrastive_scene_contexts/model/pointnet2/pytorch_utils.py

Prompts

```
['build a PointnetSAModuleMSG layer with multiscale grouping for point cloud feature extraction', 'build a PointnetSAModuleVotes layer with RBF pooling and point index support for votenet', 'build a PointnetFPModule layer to propagate features from one point set to another via interpolation', 'build a PointnetLFPModuleMSG learnable feature propagation layer with multiscale grouping', 'test the PointnetSAModuleMSG forward pass and backward gradient computation on sample point clouds', 'test the three_interpolate gradient correctness using torch.autograd.gradcheck on CUDA tensors', 'run the pointnet2 interpolation gradient test via the main entry point', 'review the test_interpolation_grad function to verify gradcheck tolerances and tensor shapes', 'refactor test_interpolation_grad to parameterize batch size, feature dimension, and sample count', 'summarize the pointnet2_test module which validates three_interpolate gradient computation', 'sample points from a point cloud using iterative furthest point sampling to select npoint features', 'find all points within a given radius of center points in a 3D point cloud', 'group nearby point cloud features using ball query with radius and optional xyz normalization', 'gather specific feature vectors from a tensor by index for point cloud processing', 'interpolate features using weighted linear interpolation from three nearest neighbors in a point cloud', 'build a SharedMLP module with a list of channel sizes for 2D conv layers', 'create a Conv2d layer with optional batch normalization and ReLU activation', 'create a Conv1d layer with optional batch normalization and kaiming weight init', 'create a BNMomentumScheduler to adjust batch norm momentum per training epoch', 'review the FC class that builds a linear layer with optional batch norm and activation']
```

Usage

```
{'build_SharedMLP': 'build a SharedMLP module with a list of channel sizes for 2D conv layers', 'create_Conv2d': 'create a Conv2d layer with optional batch normalization and ReLU activation', 'create_Conv1d': 'create a Conv1d layer with optional batch normalization and kaiming weight init', 'create_BNMomentumScheduler': 'create a BNMomentumScheduler to adjust batch norm momentum per training epoch', 'review_FC': 'review the FC class that builds a linear layer with optional batch norm and activation'}
```

