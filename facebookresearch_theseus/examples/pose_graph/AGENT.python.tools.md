# Agent Python Tools

- repo: facebookresearch/theseus
- repo_uri: https://github.com/facebookresearch/theseus

## File: facebookresearch_theseus/examples/pose_graph/pose_graph_cube.py

Prompts

```
['run pose graph optimization on cube datasets using GaussNewton optimizer with sparse linearization', 'create a PoseGraphDataset from SE3 poses and edges with configurable batch size for optimization', 'build an Objective with Between relative pose costs and Difference prior costs for pose graph optimization', 'run batch optimization on pose graph data and measure forward pass time and memory usage', 'read 3D pose graph data from g2o files and concatenate poses and edges across multiple datasets', 'create a function that computes SE3 pose loss between optimized poses and ground truth poses', 'get batch data from a PoseGraphDataset including poses, ground truth poses, and relative pose edges', 'print a histogram of pose graph optimization results comparing optimized poses against edges', 'run pose graph optimization with Welsch robust loss and outer loop hyperparameter tuning via Adam']
```

Usage

```
{'run_pose_graph_optimization': 'run pose graph optimization on cube datasets using GaussNewton optimizer with sparse linearization', 'create_pose_graph_dataset': 'create a PoseGraphDataset from SE3 poses and edges with configurable batch size for optimization', 'build_objective_with_costs': 'build an Objective with Between relative pose costs and Difference prior costs for pose graph optimization', 'run_batch_optimization': 'run batch optimization on pose graph data and measure forward pass time and memory usage', 'read_g2o_pose_graph': 'read 3D pose graph data from g2o files and concatenate poses and edges across multiple datasets'}
```

## File: facebookresearch_theseus/examples/pose_graph/pose_graph_synthetic.py

Prompts

```
['run pose graph optimization on cube datasets using GaussNewton optimizer with sparse linearization', 'create a PoseGraphDataset from SE3 poses and edges with configurable batch size for optimization', 'build an Objective with Between relative pose costs and Difference prior costs for pose graph optimization', 'run batch optimization on pose graph data and measure forward pass time and memory usage', 'read 3D pose graph data from g2o files and concatenate poses and edges across multiple datasets', 'create a function that computes SE3 pose loss between optimized poses and ground truth poses', 'get batch data from a PoseGraphDataset including poses, ground truth poses, and relative pose edges', 'print a histogram of pose graph optimization results comparing optimized poses against edges', 'run pose graph optimization with Welsch robust loss and outer loop hyperparameter tuning via Adam']
```

Usage

```
{'run_pose_graph_optimization': 'run a synthetic 3D pose graph optimization using Theseus with configurable noise and loop closures', 'create_pose_loss_function': 'create a function that computes SE3 pose loss between optimized poses and ground truth poses', 'get_batch_data_from_pose_graph': 'get batch data from a PoseGraphDataset including poses, ground truth poses, and relative pose edges', 'print_pose_histogram': 'print a histogram of pose graph optimization results comparing optimized poses against edges', 'run_pose_graph_with_robust_loss': 'run pose graph optimization with Welsch robust loss and outer loop hyperparameter tuning via Adam'}
```

