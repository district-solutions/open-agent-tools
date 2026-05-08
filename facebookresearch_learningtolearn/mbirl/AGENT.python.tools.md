# Agent Python Tools

- repo: facebookresearch/learningtolearn
- repo_uri: https://github.com/facebookresearch/learningtolearn

## File: facebookresearch_learningtolearn/mbirl/generate_expert_demo.py

Prompts

```
['run the script to generate and save KUKA robot expert demonstration trajectories for the placing experiment', 'create a GroundTruthForwardModel instance wrapping a DifferentiableRobotModel for forward kinematics computation', 'run forward_kin on a joint configuration tensor to compute scaled robot link keypoints', 'summarize how the main block generates 6 randomized placing trajectories with linearly interpolated keypoints', 'review the GroundTruthForwardModel class and its forward_kin method for computing keypoints from robot links', 'create a GroundTruthKeypointMPCWrapper instance with a robot model, time horizon, and keypoint dimension', 'run the forward method to compute desired joint states and keypoints from current state and action', 'run the roll_out method to simulate joint states and keypoint positions over the action sequence horizon', 'reset the action sequence parameters to zero using the reset_actions method', 'review the GroundTruthKeypointMPCWrapper class for keypoint MPC optimization with forward kinematics and joint limit clamping', 'create a LearnableWeightedCost module with configurable dimension and optional fixed weights for weighted MSE loss', 'create a LearnableTimeDepWeightedCost module with time-dependent weights across a time horizon for trajectory cost', 'create an RBFWeights module that generates radial basis function weights from a kernel matrix and learnable parameters', 'create a LearnableRBFWeightedCost module that computes RBF-smoothed weighted MSE loss over a time horizon', 'create an IRLLoss callable that computes the mean squared error between predicted and target trajectories']
```

Usage

```
{'run_generate_expert_demo': 'run the script to generate and save KUKA robot expert demonstration trajectories for the placing experiment', 'create_GroundTruthForwardModel': 'create a GroundTruthForwardModel instance wrapping a DifferentiableRobotModel for forward kinematics computation', 'run_forward_kin': 'run forward_kin on a joint configuration tensor to compute scaled robot link keypoints', 'summarize_trajectory_generation': 'summarize how the main block generates 6 randomized placing trajectories with linearly interpolated keypoints', 'review_GroundTruthForwardModel': 'review the GroundTruthForwardModel class and its forward_kin method for computing keypoints from robot links'}
```

## File: facebookresearch_learningtolearn/mbirl/keypoint_mpc.py

Prompts

```
['run the script to generate and save KUKA robot expert demonstration trajectories for the placing experiment', 'create a GroundTruthForwardModel instance wrapping a DifferentiableRobotModel for forward kinematics computation', 'run forward_kin on a joint configuration tensor to compute scaled robot link keypoints', 'summarize how the main block generates 6 randomized placing trajectories with linearly interpolated keypoints', 'review the GroundTruthForwardModel class and its forward_kin method for computing keypoints from robot links', 'create a GroundTruthKeypointMPCWrapper instance with a robot model, time horizon, and keypoint dimension', 'run the forward method to compute desired joint states and keypoints from current state and action', 'run the roll_out method to simulate joint states and keypoint positions over the action sequence horizon', 'reset the action sequence parameters to zero using the reset_actions method', 'review the GroundTruthKeypointMPCWrapper class for keypoint MPC optimization with forward kinematics and joint limit clamping', 'create a LearnableWeightedCost module with configurable dimension and optional fixed weights for weighted MSE loss', 'create a LearnableTimeDepWeightedCost module with time-dependent weights across a time horizon for trajectory cost', 'create an RBFWeights module that generates radial basis function weights from a kernel matrix and learnable parameters', 'create a LearnableRBFWeightedCost module that computes RBF-smoothed weighted MSE loss over a time horizon', 'create an IRLLoss callable that computes the mean squared error between predicted and target trajectories']
```

Usage

```
{'create_GroundTruthKeypointMPCWrapper': 'create a GroundTruthKeypointMPCWrapper instance with a robot model, time horizon, and keypoint dimension', 'run_forward_method': 'run the forward method to compute desired joint states and keypoints from current state and action', 'run_roll_out_method': 'run the roll_out method to simulate joint states and keypoint positions over the action sequence horizon', 'reset_reset_actions': 'reset the action sequence parameters to zero using the reset_actions method', 'review_GroundTruthKeypointMPCWrapper': 'review the GroundTruthKeypointMPCWrapper class for keypoint MPC optimization with forward kinematics and joint limit clamping'}
```

## File: facebookresearch_learningtolearn/mbirl/learnable_costs.py

Prompts

```
['run the script to generate and save KUKA robot expert demonstration trajectories for the placing experiment', 'create a GroundTruthForwardModel instance wrapping a DifferentiableRobotModel for forward kinematics computation', 'run forward_kin on a joint configuration tensor to compute scaled robot link keypoints', 'summarize how the main block generates 6 randomized placing trajectories with linearly interpolated keypoints', 'review the GroundTruthForwardModel class and its forward_kin method for computing keypoints from robot links', 'create a GroundTruthKeypointMPCWrapper instance with a robot model, time horizon, and keypoint dimension', 'run the forward method to compute desired joint states and keypoints from current state and action', 'run the roll_out method to simulate joint states and keypoint positions over the action sequence horizon', 'reset the action sequence parameters to zero using the reset_actions method', 'review the GroundTruthKeypointMPCWrapper class for keypoint MPC optimization with forward kinematics and joint limit clamping', 'create a LearnableWeightedCost module with configurable dimension and optional fixed weights for weighted MSE loss', 'create a LearnableTimeDepWeightedCost module with time-dependent weights across a time horizon for trajectory cost', 'create an RBFWeights module that generates radial basis function weights from a kernel matrix and learnable parameters', 'create a LearnableRBFWeightedCost module that computes RBF-smoothed weighted MSE loss over a time horizon', 'create an IRLLoss callable that computes the mean squared error between predicted and target trajectories']
```

Usage

```
{'create_learnable_weighted_cost': 'create a LearnableWeightedCost module with configurable dimension and optional fixed weights for weighted MSE loss', 'create_learnable_time_dependent_cost': 'create a LearnableTimeDepWeightedCost module with time-dependent weights across a time horizon for trajectory cost', 'create_rbf_weights': 'create an RBFWeights module that generates radial basis function weights from a kernel matrix and learnable parameters', 'create_learnable_rbf_weighted_cost': 'create a LearnableRBFWeightedCost module that computes RBF-smoothed weighted MSE loss over a time horizon', 'create_iroll_loss': 'create an IRLLoss callable that computes the mean squared error between predicted and target trajectories'}
```

