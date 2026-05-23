# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/nav/nn_nav_skill.py

Prompts

```
['create a NavSkillPolicy instance with config, observation space, action space, and batch size', 'check if the navigation skill is done by comparing agent distance to goal threshold', 'get the current state description string which returns Walking for the navigation skill', 'get the list of argument types required for navigation targets like objects and rooms', 'review the NavSkillPolicy class to understand navigation completion logic and state management', 'set a navigation target pose for the agent to reach a named entity like Object, Furniture, or Receptacle', 'compute the shortest path from the agent current position to a target point using the simulator pathfinder', 'check if the agent collides with objects given a transformation and the navmesh navigability', 'execute a navigation step by computing velocity commands or teleport actions to move the agent toward the target', 'check if the agent has reached the navigation goal by evaluating distance and angle thresholds', 'set the navigation target position using an x,y,yaw coordinate string for the agent', 'parse a comma-separated x,y,yaw string into floating point navigation coordinates', 'snap a target position to the nearest unoccluded navmesh point using embodied_unoccluded_navmesh_snap', 'review the OraclePointNavSkill class that extends OracleNavSkill for point-based navigation in Habitat sim', 'summarize the set_target method that parses coordinates and snaps to navmesh with up to 200 attempts']
```

Usage

```
{'create_nav_skill_policy': 'create a NavSkillPolicy instance with config, observation space, action space, and batch size', 'check_skill_done': 'check if the navigation skill is done by comparing agent distance to goal threshold', 'get_state_description': 'get the current state description string which returns Walking for the navigation skill', 'get_argument_types': 'get the list of argument types required for navigation targets like objects and rooms', 'review_nav_skill_policy': 'review the NavSkillPolicy class to understand navigation completion logic and state management'}
```

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/nav/oracle_nav_skill.py

Prompts

```
['create a NavSkillPolicy instance with config, observation space, action space, and batch size', 'check if the navigation skill is done by comparing agent distance to goal threshold', 'get the current state description string which returns Walking for the navigation skill', 'get the list of argument types required for navigation targets like objects and rooms', 'review the NavSkillPolicy class to understand navigation completion logic and state management', 'set a navigation target pose for the agent to reach a named entity like Object, Furniture, or Receptacle', 'compute the shortest path from the agent current position to a target point using the simulator pathfinder', 'check if the agent collides with objects given a transformation and the navmesh navigability', 'execute a navigation step by computing velocity commands or teleport actions to move the agent toward the target', 'check if the agent has reached the navigation goal by evaluating distance and angle thresholds', 'set the navigation target position using an x,y,yaw coordinate string for the agent', 'parse a comma-separated x,y,yaw string into floating point navigation coordinates', 'snap a target position to the nearest unoccluded navmesh point using embodied_unoccluded_navmesh_snap', 'review the OraclePointNavSkill class that extends OracleNavSkill for point-based navigation in Habitat sim', 'summarize the set_target method that parses coordinates and snaps to navmesh with up to 200 attempts']
```

Usage

```
{'set_target_navigation': 'set a navigation target pose for the agent to reach a named entity like Object, Furniture, or Receptacle', 'compute_shortest_path': 'compute the shortest path from the agent current position to a target point using the simulator pathfinder', 'check_collision_navmesh': 'check if the agent collides with objects given a transformation and the navmesh navigability', 'execute_navigation_action': 'execute a navigation step by computing velocity commands or teleport actions to move the agent toward the target', 'check_skill_completion': 'check if the agent has reached the navigation goal by evaluating distance and angle thresholds'}
```

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/nav/oracle_point_nav_skill.py

Prompts

```
['create a NavSkillPolicy instance with config, observation space, action space, and batch size', 'check if the navigation skill is done by comparing agent distance to goal threshold', 'get the current state description string which returns Walking for the navigation skill', 'get the list of argument types required for navigation targets like objects and rooms', 'review the NavSkillPolicy class to understand navigation completion logic and state management', 'set a navigation target pose for the agent to reach a named entity like Object, Furniture, or Receptacle', 'compute the shortest path from the agent current position to a target point using the simulator pathfinder', 'check if the agent collides with objects given a transformation and the navmesh navigability', 'execute a navigation step by computing velocity commands or teleport actions to move the agent toward the target', 'check if the agent has reached the navigation goal by evaluating distance and angle thresholds', 'set the navigation target position using an x,y,yaw coordinate string for the agent', 'parse a comma-separated x,y,yaw string into floating point navigation coordinates', 'snap a target position to the nearest unoccluded navmesh point using embodied_unoccluded_navmesh_snap', 'review the OraclePointNavSkill class that extends OracleNavSkill for point-based navigation in Habitat sim', 'summarize the set_target method that parses coordinates and snaps to navmesh with up to 200 attempts']
```

Usage

```
{'set_target_position': 'set the navigation target position using an x,y,yaw coordinate string for the agent', 'parse_target_coordinates': 'parse a comma-separated x,y,yaw string into floating point navigation coordinates', 'snap_to_navmesh': 'snap a target position to the nearest unoccluded navmesh point using embodied_unoccluded_navmesh_snap', 'review_oracle_point_nav_skill': 'review the OraclePointNavSkill class that extends OracleNavSkill for point-based navigation in Habitat sim', 'summarize_set_target_method': 'summarize the set_target method that parses coordinates and snaps to navmesh with up to 200 attempts'}
```

