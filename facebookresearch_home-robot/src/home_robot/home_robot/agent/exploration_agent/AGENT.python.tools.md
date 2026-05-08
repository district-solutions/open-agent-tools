# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot/home_robot/agent/exploration_agent/exploration_agent.py

Prompts

```
['build an ExplorationAgent instance with a config object and optional GPU device ID', 'run the act method on an ExplorationAgent with an Observations object to get a navigation action', 'test the prepare_planner_inputs method with observation tensors and pose delta to get planner inputs', 'review the reset_vectorized method to initialize agent state across all vectorized environments', 'summarize the _preprocess_obs method that converts raw observations into RGB depth tensors and pose deltas', 'create an ExplorationAgentModule instance from a config with environment and semantic map settings', 'run the forward pass of ExplorationAgentModule with observation sequences to predict goal maps and update poses', 'review the ExplorationAgentModule init to understand how GeometricMapModule and FrontierExplorationPolicy are configured', 'summarize the goal_update_steps property that exposes the policy goal update interval', 'test the debug_frontier_map flag to visualize frontier maps during exploration with matplotlib']
```

Usage

```
{'build_exploration_agent': 'build an ExplorationAgent instance with a config object and optional GPU device ID', 'run_act_method': 'run the act method on an ExplorationAgent with an Observations object to get a navigation action', 'test_prepare_planner_inputs': 'test the prepare_planner_inputs method with observation tensors and pose delta to get planner inputs', 'review_reset_vectorized': 'review the reset_vectorized method to initialize agent state across all vectorized environments', 'summarize_preprocess_obs': 'summarize the _preprocess_obs method that converts raw observations into RGB depth tensors and pose deltas'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/agent/exploration_agent/exploration_agent_module.py

Prompts

```
['build an ExplorationAgent instance with a config object and optional GPU device ID', 'run the act method on an ExplorationAgent with an Observations object to get a navigation action', 'test the prepare_planner_inputs method with observation tensors and pose delta to get planner inputs', 'review the reset_vectorized method to initialize agent state across all vectorized environments', 'summarize the _preprocess_obs method that converts raw observations into RGB depth tensors and pose deltas', 'create an ExplorationAgentModule instance from a config with environment and semantic map settings', 'run the forward pass of ExplorationAgentModule with observation sequences to predict goal maps and update poses', 'review the ExplorationAgentModule init to understand how GeometricMapModule and FrontierExplorationPolicy are configured', 'summarize the goal_update_steps property that exposes the policy goal update interval', 'test the debug_frontier_map flag to visualize frontier maps during exploration with matplotlib']
```

Usage

```
{'create_exploration_agent_module': 'create an ExplorationAgentModule instance from a config with environment and semantic map settings', 'run_forward_exploration_agent': 'run the forward pass of ExplorationAgentModule with observation sequences to predict goal maps and update poses', 'review_exploration_agent_init': 'review the ExplorationAgentModule init to understand how GeometricMapModule and FrontierExplorationPolicy are configured', 'summarize_goal_update_steps_property': 'summarize the goal_update_steps property that exposes the policy goal update interval', 'test_debug_frontier_map_flag': 'test the debug_frontier_map flag to visualize frontier maps during exploration with matplotlib'}
```

