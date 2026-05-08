# Agent Python Tools

- repo: facebookresearch/home-robot
- repo_uri: https://github.com/facebookresearch/home-robot

## File: facebookresearch_home-robot/src/home_robot/home_robot/navigation_policy/exploration/frontier_exploration_policy.py

Prompts

```
['create a FrontierExplorationPolicy with seen_frontier or been_close_to_frontier strategy', 'run the forward pass on semantic map features to get a binary goal map', 'get the frontier map by selecting unexplored areas and applying morphological dilation', 'explore the closest unexplored region by calling the explore method with map features', 'review the FrontierExplorationPolicy class and its frontier selection using morphological operations']
```

Usage

```
{'create_FrontierExplorationPolicy': 'create a FrontierExplorationPolicy with seen_frontier or been_close_to_frontier strategy', 'run_forward_goal_map': 'run the forward pass on semantic map features to get a binary goal map', 'get_frontier_map': 'get the frontier map by selecting unexplored areas and applying morphological dilation', 'explore_unexplored_region': 'explore the closest unexplored region by calling the explore method with map features', 'review_FrontierExplorationPolicy': 'review the FrontierExplorationPolicy class and its frontier selection using morphological operations'}
```

