# Agent Python Tools

- repo: facebookresearch/consistentdepth
- repo_uri: https://github.com/facebookresearch/consistent_depth

## File: facebookresearch_consistentdepth/loss/consistency_loss.py

Prompts

```
['compute the weighted mean squared error between input and target tensors using per-pixel weights', 'compute the weighted root mean squared error between input and target tensors using per-pixel weights', 'compute the weighted mean of a tensor using normalized per-element weights', 'compute geometry consistency loss including reprojection error and disparity error for camera pairs', 'run the ConsistencyLoss module on predicted depths and metadata to compute total geometry consistency loss', 'add loss-related arguments to an argparse parser for view baseline, reprojection, and parameter regularization weights', 'generate a formatted string summarizing loss parameters from an options object', 'review the LossParams class and its static methods for argument parsing and string formatting', 'refactor LossParams.add_arguments to support additional loss weight arguments for custom training configurations', 'test the LossParams.make_str method to verify correct formatting of loss parameter strings']
```

Usage

```
{'compute_weighted_mse_loss': 'compute the weighted mean squared error between input and target tensors using per-pixel weights', 'compute_weighted_rmse_loss': 'compute the weighted root mean squared error between input and target tensors using per-pixel weights', 'compute_weighted_mean_loss': 'compute the weighted mean of a tensor using normalized per-element weights', 'compute_geometry_consistency_loss': 'compute geometry consistency loss including reprojection error and disparity error for camera pairs', 'run_consistency_loss': 'run the ConsistencyLoss module on predicted depths and metadata to compute total geometry consistency loss'}
```

## File: facebookresearch_consistentdepth/loss/loss_params.py

Prompts

```
['compute the weighted mean squared error between input and target tensors using per-pixel weights', 'compute the weighted root mean squared error between input and target tensors using per-pixel weights', 'compute the weighted mean of a tensor using normalized per-element weights', 'compute geometry consistency loss including reprojection error and disparity error for camera pairs', 'run the ConsistencyLoss module on predicted depths and metadata to compute total geometry consistency loss', 'add loss-related arguments to an argparse parser for view baseline, reprojection, and parameter regularization weights', 'generate a formatted string summarizing loss parameters from an options object', 'review the LossParams class and its static methods for argument parsing and string formatting', 'refactor LossParams.add_arguments to support additional loss weight arguments for custom training configurations', 'test the LossParams.make_str method to verify correct formatting of loss parameter strings']
```

Usage

```
{'add_loss_arguments_to_parser': 'add loss-related arguments to an argparse parser for view baseline, reprojection, and parameter regularization weights', 'make_loss_params_string': 'generate a formatted string summarizing loss parameters from an options object', 'review_LossParams_class': 'review the LossParams class and its static methods for argument parsing and string formatting', 'refactor_LossParams_add_arguments': 'refactor LossParams.add_arguments to support additional loss weight arguments for custom training configurations', 'test_LossParams_make_str': 'test the LossParams.make_str method to verify correct formatting of loss parameter strings'}
```

