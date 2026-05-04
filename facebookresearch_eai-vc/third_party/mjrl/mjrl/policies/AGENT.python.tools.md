# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/mjrl/mjrl/policies/gaussian_linear.py

Prompts

```
['create a LinearPolicy instance with env_spec, min_log_std, init_log_std, and seed parameters', 'get an action from the LinearPolicy by passing an observation and receiving action with metadata', 'set new parameter values on the LinearPolicy model and optionally update the old policy parameters', 'compute the log likelihood of actions given observations using the LinearPolicy model', 'compute the mean KL divergence between new and old distribution info from the LinearPolicy', 'create a Gaussian MLP policy network with configurable hidden layer sizes and log standard deviation', 'get an action from the MLP policy by sampling from the Gaussian distribution for an observation', 'get all trainable parameter values from the MLP policy as a flattened numpy array', 'set MLP policy parameters from a flattened numpy array and update both new and old networks', 'compute the log likelihood of given actions under the MLP policy for a batch of observations', 'create an MPCActor instance with an environment, horizon H, and paths per CPU for model predictive control', 'run get_action on the MPCActor to compute the optimal action for a given environment state', 'test the score_trajectory method to compute discounted cumulative rewards for a list of trajectory paths', 'review the MPCActor constructor to understand how horizon, filter coefficients, and gamma are initialized', 'refactor get_action to customize the Boltzmann-weighted action selection across parallel trajectory rollouts']
```

Usage

```
{'create_LinearPolicy': 'create a LinearPolicy instance with env_spec, min_log_std, init_log_std, and seed parameters', 'get_action_LinearPolicy': 'get an action from the LinearPolicy by passing an observation and receiving action with metadata', 'set_param_values_LinearPolicy': 'set new parameter values on the LinearPolicy model and optionally update the old policy parameters', 'log_likelihood_LinearPolicy': 'compute the log likelihood of actions given observations using the LinearPolicy model', 'mean_kl_LinearPolicy': 'compute the mean KL divergence between new and old distribution info from the LinearPolicy'}
```

## File: facebookresearch_eai-vc/third_party/mjrl/mjrl/policies/gaussian_mlp.py

Prompts

```
['create a LinearPolicy instance with env_spec, min_log_std, init_log_std, and seed parameters', 'get an action from the LinearPolicy by passing an observation and receiving action with metadata', 'set new parameter values on the LinearPolicy model and optionally update the old policy parameters', 'compute the log likelihood of actions given observations using the LinearPolicy model', 'compute the mean KL divergence between new and old distribution info from the LinearPolicy', 'create a Gaussian MLP policy network with configurable hidden layer sizes and log standard deviation', 'get an action from the MLP policy by sampling from the Gaussian distribution for an observation', 'get all trainable parameter values from the MLP policy as a flattened numpy array', 'set MLP policy parameters from a flattened numpy array and update both new and old networks', 'compute the log likelihood of given actions under the MLP policy for a batch of observations', 'create an MPCActor instance with an environment, horizon H, and paths per CPU for model predictive control', 'run get_action on the MPCActor to compute the optimal action for a given environment state', 'test the score_trajectory method to compute discounted cumulative rewards for a list of trajectory paths', 'review the MPCActor constructor to understand how horizon, filter coefficients, and gamma are initialized', 'refactor get_action to customize the Boltzmann-weighted action selection across parallel trajectory rollouts']
```

Usage

```
{'create_MLP_policy': 'create a Gaussian MLP policy network with configurable hidden layer sizes and log standard deviation', 'get_action_MLP': 'get an action from the MLP policy by sampling from the Gaussian distribution for an observation', 'get_param_values_MLP': 'get all trainable parameter values from the MLP policy as a flattened numpy array', 'set_param_values_MLP': 'set MLP policy parameters from a flattened numpy array and update both new and old networks', 'compute_log_likelihood_MLP': 'compute the log likelihood of given actions under the MLP policy for a batch of observations'}
```

## File: facebookresearch_eai-vc/third_party/mjrl/mjrl/policies/mpc_actor.py

Prompts

```
['create a LinearPolicy instance with env_spec, min_log_std, init_log_std, and seed parameters', 'get an action from the LinearPolicy by passing an observation and receiving action with metadata', 'set new parameter values on the LinearPolicy model and optionally update the old policy parameters', 'compute the log likelihood of actions given observations using the LinearPolicy model', 'compute the mean KL divergence between new and old distribution info from the LinearPolicy', 'create a Gaussian MLP policy network with configurable hidden layer sizes and log standard deviation', 'get an action from the MLP policy by sampling from the Gaussian distribution for an observation', 'get all trainable parameter values from the MLP policy as a flattened numpy array', 'set MLP policy parameters from a flattened numpy array and update both new and old networks', 'compute the log likelihood of given actions under the MLP policy for a batch of observations', 'create an MPCActor instance with an environment, horizon H, and paths per CPU for model predictive control', 'run get_action on the MPCActor to compute the optimal action for a given environment state', 'test the score_trajectory method to compute discounted cumulative rewards for a list of trajectory paths', 'review the MPCActor constructor to understand how horizon, filter coefficients, and gamma are initialized', 'refactor get_action to customize the Boltzmann-weighted action selection across parallel trajectory rollouts']
```

Usage

```
{'create_MPCActor': 'create an MPCActor instance with an environment, horizon H, and paths per CPU for model predictive control', 'run_get_action': 'run get_action on the MPCActor to compute the optimal action for a given environment state', 'test_score_trajectory': 'test the score_trajectory method to compute discounted cumulative rewards for a list of trajectory paths', 'review_MPCActor_init': 'review the MPCActor constructor to understand how horizon, filter coefficients, and gamma are initialized', 'refactor_get_action': 'refactor get_action to customize the Boltzmann-weighted action selection across parallel trajectory rollouts'}
```

