# Agent Python Tools

- repo: facebookresearch/mbrl-lib
- repo_uri: https://github.com/facebookresearch/mbrl-lib

## File: facebookresearch_mbrl-lib/mbrl/planning/core.py

Prompts

```
['create a RandomAgent that samples random actions from a gym environment action space', 'implement a custom Agent subclass with act and plan methods for model-based RL', 'complete an OmegaConf agent configuration with observation and action dimensions from a gym environment', 'load a SAC agent from a Hydra config file and checkpoint directory path', 'review the abstract Agent base class act plan and reset method signatures', 'create a PIDAgent with proportional, integral, and derivative control coefficients for a control system', 'compute a PID control action from an observation using the PIDAgent act method', 'reset the internal previous and cumulative error state of a PIDAgent instance', 'get all PID controller parameters stacked and flattened into a single numpy array', 'retrieve the previous error and cumulative error arrays from a PIDAgent instance', 'create a SACAgent wrapper from an existing pytorch_sac SAC agent instance', 'act with the SACAgent on a single observation to get the mean policy action', 'act with the SACAgent using sample mode to sample actions from the policy', 'act with the SACAgent on a batch of observations in batched mode', 'review the SACAgent class that wraps pytorch_sac SAC for MBRL planning', 'create a CEMOptimizer instance to run Cross-Entropy Method optimization with elite ratio and population size', 'create an MPPIOptimizer instance to run Model Predictive Path Integral optimization with noise sampling', 'create an ICEMOptimizer instance to run Improved Cross-Entropy Method optimization with colored noise', 'create a TrajectoryOptimizer with action bounds and planning horizon to optimize action sequences', 'create a TrajectoryOptimizerAgent that performs trajectory optimization and returns actions given observations']
```

Usage

```
{'create_random_agent': 'create a RandomAgent that samples random actions from a gym environment action space', 'implement_agent_subclass': 'implement a custom Agent subclass with act and plan methods for model-based RL', 'complete_agent_cfg': 'complete an OmegaConf agent configuration with observation and action dimensions from a gym environment', 'load_agent_from_hydra': 'load a SAC agent from a Hydra config file and checkpoint directory path', 'review_agent_base_class': 'review the abstract Agent base class act plan and reset method signatures'}
```

## File: facebookresearch_mbrl-lib/mbrl/planning/linear_feedback.py

Prompts

```
['create a RandomAgent that samples random actions from a gym environment action space', 'implement a custom Agent subclass with act and plan methods for model-based RL', 'complete an OmegaConf agent configuration with observation and action dimensions from a gym environment', 'load a SAC agent from a Hydra config file and checkpoint directory path', 'review the abstract Agent base class act plan and reset method signatures', 'create a PIDAgent with proportional, integral, and derivative control coefficients for a control system', 'compute a PID control action from an observation using the PIDAgent act method', 'reset the internal previous and cumulative error state of a PIDAgent instance', 'get all PID controller parameters stacked and flattened into a single numpy array', 'retrieve the previous error and cumulative error arrays from a PIDAgent instance', 'create a SACAgent wrapper from an existing pytorch_sac SAC agent instance', 'act with the SACAgent on a single observation to get the mean policy action', 'act with the SACAgent using sample mode to sample actions from the policy', 'act with the SACAgent on a batch of observations in batched mode', 'review the SACAgent class that wraps pytorch_sac SAC for MBRL planning', 'create a CEMOptimizer instance to run Cross-Entropy Method optimization with elite ratio and population size', 'create an MPPIOptimizer instance to run Model Predictive Path Integral optimization with noise sampling', 'create an ICEMOptimizer instance to run Improved Cross-Entropy Method optimization with colored noise', 'create a TrajectoryOptimizer with action bounds and planning horizon to optimize action sequences', 'create a TrajectoryOptimizerAgent that performs trajectory optimization and returns actions given observations']
```

Usage

```
{'create_pid_agent': 'create a PIDAgent with proportional, integral, and derivative control coefficients for a control system', 'act_pid_agent': 'compute a PID control action from an observation using the PIDAgent act method', 'reset_pid_errors': 'reset the internal previous and cumulative error state of a PIDAgent instance', 'get_pid_parameters': 'get all PID controller parameters stacked and flattened into a single numpy array', 'get_pid_errors': 'retrieve the previous error and cumulative error arrays from a PIDAgent instance'}
```

## File: facebookresearch_mbrl-lib/mbrl/planning/sac_wrapper.py

Prompts

```
['create a RandomAgent that samples random actions from a gym environment action space', 'implement a custom Agent subclass with act and plan methods for model-based RL', 'complete an OmegaConf agent configuration with observation and action dimensions from a gym environment', 'load a SAC agent from a Hydra config file and checkpoint directory path', 'review the abstract Agent base class act plan and reset method signatures', 'create a PIDAgent with proportional, integral, and derivative control coefficients for a control system', 'compute a PID control action from an observation using the PIDAgent act method', 'reset the internal previous and cumulative error state of a PIDAgent instance', 'get all PID controller parameters stacked and flattened into a single numpy array', 'retrieve the previous error and cumulative error arrays from a PIDAgent instance', 'create a SACAgent wrapper from an existing pytorch_sac SAC agent instance', 'act with the SACAgent on a single observation to get the mean policy action', 'act with the SACAgent using sample mode to sample actions from the policy', 'act with the SACAgent on a batch of observations in batched mode', 'review the SACAgent class that wraps pytorch_sac SAC for MBRL planning', 'create a CEMOptimizer instance to run Cross-Entropy Method optimization with elite ratio and population size', 'create an MPPIOptimizer instance to run Model Predictive Path Integral optimization with noise sampling', 'create an ICEMOptimizer instance to run Improved Cross-Entropy Method optimization with colored noise', 'create a TrajectoryOptimizer with action bounds and planning horizon to optimize action sequences', 'create a TrajectoryOptimizerAgent that performs trajectory optimization and returns actions given observations']
```

Usage

```
{'create_sac_agent': 'create a SACAgent wrapper from an existing pytorch_sac SAC agent instance', 'act_sac_agent_observation': 'act with the SACAgent on a single observation to get the mean policy action', 'act_sac_agent_sample': 'act with the SACAgent using sample mode to sample actions from the policy', 'act_sac_agent_batched': 'act with the SACAgent on a batch of observations in batched mode', 'review_sac_agent_wrapper': 'review the SACAgent class that wraps pytorch_sac SAC for MBRL planning'}
```

## File: facebookresearch_mbrl-lib/mbrl/planning/trajectory_opt.py

Prompts

```
['create a RandomAgent that samples random actions from a gym environment action space', 'implement a custom Agent subclass with act and plan methods for model-based RL', 'complete an OmegaConf agent configuration with observation and action dimensions from a gym environment', 'load a SAC agent from a Hydra config file and checkpoint directory path', 'review the abstract Agent base class act plan and reset method signatures', 'create a PIDAgent with proportional, integral, and derivative control coefficients for a control system', 'compute a PID control action from an observation using the PIDAgent act method', 'reset the internal previous and cumulative error state of a PIDAgent instance', 'get all PID controller parameters stacked and flattened into a single numpy array', 'retrieve the previous error and cumulative error arrays from a PIDAgent instance', 'create a SACAgent wrapper from an existing pytorch_sac SAC agent instance', 'act with the SACAgent on a single observation to get the mean policy action', 'act with the SACAgent using sample mode to sample actions from the policy', 'act with the SACAgent on a batch of observations in batched mode', 'review the SACAgent class that wraps pytorch_sac SAC for MBRL planning', 'create a CEMOptimizer instance to run Cross-Entropy Method optimization with elite ratio and population size', 'create an MPPIOptimizer instance to run Model Predictive Path Integral optimization with noise sampling', 'create an ICEMOptimizer instance to run Improved Cross-Entropy Method optimization with colored noise', 'create a TrajectoryOptimizer with action bounds and planning horizon to optimize action sequences', 'create a TrajectoryOptimizerAgent that performs trajectory optimization and returns actions given observations']
```

Usage

```
{'create_cem_optimizer': 'create a CEMOptimizer instance to run Cross-Entropy Method optimization with elite ratio and population size', 'create_mppi_optimizer': 'create an MPPIOptimizer instance to run Model Predictive Path Integral optimization with noise sampling', 'create_icem_optimizer': 'create an ICEMOptimizer instance to run Improved Cross-Entropy Method optimization with colored noise', 'create_trajectory_optimizer': 'create a TrajectoryOptimizer with action bounds and planning horizon to optimize action sequences', 'create_trajectory_optimizer_agent': 'create a TrajectoryOptimizerAgent that performs trajectory optimization and returns actions given observations'}
```

