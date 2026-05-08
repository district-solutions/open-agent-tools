# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot/home_robot/agent/objectnav_agent/objectnav_agent.py

Prompts

```
['create an ObjectNavAgent instance with a config object for 2D semantic map based object navigation', 'call prepare_planner_inputs to get planner and visualization inputs from observation tensors and pose deltas', 'call act with an Observations object to get a DiscreteNavigationAction and info dict for navigation', 'call reset_vectorized to initialize agent state including timesteps, semantic map, and planner for all environments', 'call _preprocess_obs to convert a raw Observations object into preprocessed tensors for the semantic map module', 'create an ObjectNavAgentModule instance with a config object and optional InstanceMemory for semantic mapping', 'run the forward pass to update maps and predict goal locations from a sequence of observations', 'get the goal update steps interval from the ObjectNavAgentModule policy', 'review the forward method signature and tensor shape expectations for batched observation sequences', 'refactor the debug_frontier_map flag to enable matplotlib visualization of frontier and goal maps', 'create a ResetNavAgent instance with config to navigate a 2D semantic map environment', 'run the act method on ResetNavAgent with observations and point goal to get navigation action', 'prepare planner inputs from observations including obstacle maps, goal maps, and sensor pose data', 'reset the vectorized agent state for all environments including timesteps and semantic map', 'preprocess observations with RGB, depth, and semantic data for the semantic map module', 'initialize a SamplingBasedObjectNavAgent with config and device_id to create an RRT planner and voxel map', 'reset the SamplingBasedObjectNavAgent to clear the voxel map, planner state, and episode panorama steps', 'review the SamplingBasedObjectNavAgent class which extends ObjectNavAgent for 2D semantic map-based object navigation', 'review the act method in SamplingBasedObjectNavAgent which preprocesses observations but raises NotImplementedError', 'refactor the act method in SamplingBasedObjectNavAgent to implement navigation logic instead of raising NotImplementedError']
```

Usage

```
{'create_ObjectNavAgent': 'create an ObjectNavAgent instance with a config object for 2D semantic map based object navigation', 'call_prepare_planner_inputs': 'call prepare_planner_inputs to get planner and visualization inputs from observation tensors and pose deltas', 'call_act': 'call act with an Observations object to get a DiscreteNavigationAction and info dict for navigation', 'call_reset_vectorized': 'call reset_vectorized to initialize agent state including timesteps, semantic map, and planner for all environments', 'call_preprocess_obs': 'call _preprocess_obs to convert a raw Observations object into preprocessed tensors for the semantic map module'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/agent/objectnav_agent/objectnav_agent_module.py

Prompts

```
['create an ObjectNavAgent instance with a config object for 2D semantic map based object navigation', 'call prepare_planner_inputs to get planner and visualization inputs from observation tensors and pose deltas', 'call act with an Observations object to get a DiscreteNavigationAction and info dict for navigation', 'call reset_vectorized to initialize agent state including timesteps, semantic map, and planner for all environments', 'call _preprocess_obs to convert a raw Observations object into preprocessed tensors for the semantic map module', 'create an ObjectNavAgentModule instance with a config object and optional InstanceMemory for semantic mapping', 'run the forward pass to update maps and predict goal locations from a sequence of observations', 'get the goal update steps interval from the ObjectNavAgentModule policy', 'review the forward method signature and tensor shape expectations for batched observation sequences', 'refactor the debug_frontier_map flag to enable matplotlib visualization of frontier and goal maps', 'create a ResetNavAgent instance with config to navigate a 2D semantic map environment', 'run the act method on ResetNavAgent with observations and point goal to get navigation action', 'prepare planner inputs from observations including obstacle maps, goal maps, and sensor pose data', 'reset the vectorized agent state for all environments including timesteps and semantic map', 'preprocess observations with RGB, depth, and semantic data for the semantic map module', 'initialize a SamplingBasedObjectNavAgent with config and device_id to create an RRT planner and voxel map', 'reset the SamplingBasedObjectNavAgent to clear the voxel map, planner state, and episode panorama steps', 'review the SamplingBasedObjectNavAgent class which extends ObjectNavAgent for 2D semantic map-based object navigation', 'review the act method in SamplingBasedObjectNavAgent which preprocesses observations but raises NotImplementedError', 'refactor the act method in SamplingBasedObjectNavAgent to implement navigation logic instead of raising NotImplementedError']
```

Usage

```
{'init_ObjectNavAgentModule': 'create an ObjectNavAgentModule instance with a config object and optional InstanceMemory for semantic mapping', 'forward_ObjectNavAgentModule': 'run the forward pass to update maps and predict goal locations from a sequence of observations', 'property_goal_update_steps': 'get the goal update steps interval from the ObjectNavAgentModule policy', 'review_ObjectNavAgentModule_forward': 'review the forward method signature and tensor shape expectations for batched observation sequences', 'refactor_debug_frontier_map': 'refactor the debug_frontier_map flag to enable matplotlib visualization of frontier and goal maps'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/agent/objectnav_agent/reset_nav_agent.py

Prompts

```
['create an ObjectNavAgent instance with a config object for 2D semantic map based object navigation', 'call prepare_planner_inputs to get planner and visualization inputs from observation tensors and pose deltas', 'call act with an Observations object to get a DiscreteNavigationAction and info dict for navigation', 'call reset_vectorized to initialize agent state including timesteps, semantic map, and planner for all environments', 'call _preprocess_obs to convert a raw Observations object into preprocessed tensors for the semantic map module', 'create an ObjectNavAgentModule instance with a config object and optional InstanceMemory for semantic mapping', 'run the forward pass to update maps and predict goal locations from a sequence of observations', 'get the goal update steps interval from the ObjectNavAgentModule policy', 'review the forward method signature and tensor shape expectations for batched observation sequences', 'refactor the debug_frontier_map flag to enable matplotlib visualization of frontier and goal maps', 'create a ResetNavAgent instance with config to navigate a 2D semantic map environment', 'run the act method on ResetNavAgent with observations and point goal to get navigation action', 'prepare planner inputs from observations including obstacle maps, goal maps, and sensor pose data', 'reset the vectorized agent state for all environments including timesteps and semantic map', 'preprocess observations with RGB, depth, and semantic data for the semantic map module', 'initialize a SamplingBasedObjectNavAgent with config and device_id to create an RRT planner and voxel map', 'reset the SamplingBasedObjectNavAgent to clear the voxel map, planner state, and episode panorama steps', 'review the SamplingBasedObjectNavAgent class which extends ObjectNavAgent for 2D semantic map-based object navigation', 'review the act method in SamplingBasedObjectNavAgent which preprocesses observations but raises NotImplementedError', 'refactor the act method in SamplingBasedObjectNavAgent to implement navigation logic instead of raising NotImplementedError']
```

Usage

```
{'create_ResetNavAgent': 'create a ResetNavAgent instance with config to navigate a 2D semantic map environment', 'run_act_method': 'run the act method on ResetNavAgent with observations and point goal to get navigation action', 'prepare_planner_inputs': 'prepare planner inputs from observations including obstacle maps, goal maps, and sensor pose data', 'reset_vectorized_agent': 'reset the vectorized agent state for all environments including timesteps and semantic map', 'preprocess_observations': 'preprocess observations with RGB, depth, and semantic data for the semantic map module'}
```

## File: facebookresearch_home-robot/src/home_robot/home_robot/agent/objectnav_agent/sampling_agent.py

Prompts

```
['create an ObjectNavAgent instance with a config object for 2D semantic map based object navigation', 'call prepare_planner_inputs to get planner and visualization inputs from observation tensors and pose deltas', 'call act with an Observations object to get a DiscreteNavigationAction and info dict for navigation', 'call reset_vectorized to initialize agent state including timesteps, semantic map, and planner for all environments', 'call _preprocess_obs to convert a raw Observations object into preprocessed tensors for the semantic map module', 'create an ObjectNavAgentModule instance with a config object and optional InstanceMemory for semantic mapping', 'run the forward pass to update maps and predict goal locations from a sequence of observations', 'get the goal update steps interval from the ObjectNavAgentModule policy', 'review the forward method signature and tensor shape expectations for batched observation sequences', 'refactor the debug_frontier_map flag to enable matplotlib visualization of frontier and goal maps', 'create a ResetNavAgent instance with config to navigate a 2D semantic map environment', 'run the act method on ResetNavAgent with observations and point goal to get navigation action', 'prepare planner inputs from observations including obstacle maps, goal maps, and sensor pose data', 'reset the vectorized agent state for all environments including timesteps and semantic map', 'preprocess observations with RGB, depth, and semantic data for the semantic map module', 'initialize a SamplingBasedObjectNavAgent with config and device_id to create an RRT planner and voxel map', 'reset the SamplingBasedObjectNavAgent to clear the voxel map, planner state, and episode panorama steps', 'review the SamplingBasedObjectNavAgent class which extends ObjectNavAgent for 2D semantic map-based object navigation', 'review the act method in SamplingBasedObjectNavAgent which preprocesses observations but raises NotImplementedError', 'refactor the act method in SamplingBasedObjectNavAgent to implement navigation logic instead of raising NotImplementedError']
```

Usage

```
{'init_sampling_agent': 'initialize a SamplingBasedObjectNavAgent with config and device_id to create an RRT planner and voxel map', 'reset_sampling_agent': 'reset the SamplingBasedObjectNavAgent to clear the voxel map, planner state, and episode panorama steps', 'review_sampling_agent_class': 'review the SamplingBasedObjectNavAgent class which extends ObjectNavAgent for 2D semantic map-based object navigation', 'review_act_method': 'review the act method in SamplingBasedObjectNavAgent which preprocesses observations but raises NotImplementedError', 'refactor_act_method': 'refactor the act method in SamplingBasedObjectNavAgent to implement navigation logic instead of raising NotImplementedError'}
```

