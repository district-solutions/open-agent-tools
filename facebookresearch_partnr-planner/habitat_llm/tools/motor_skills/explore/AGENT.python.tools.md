# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/explore/explore_skill.py

Prompts

```
['initialize an ExploreSkill agent with config, observation space, action space, batch size, env, and agent uid', 'convert a discrete action (forward, turn left, turn right) into linear and angular velocity values', "retrieve the agent's current x, y, orientation pose from the Habitat simulator", 'compute the relative pose change (dx, dy, do) between the current and last timestep', 'update observation info with sensor pose change and concatenated RGB-depth state from observations', 'build a python module to instantiate OracleExploreSkill with config, observation space, action space, batch size, env, and agent uid', 'create a function that sets the target room name and populates the furniture queue for exploration', 'test the OracleExploreSkill reset method to clear furniture queue, target, and node reached state', 'refactor the OracleExploreSkill _internal_act method to navigate to next furniture in queue and delegate to nav skill', 'review the OracleExploreSkill _is_skill_done method that returns a BoolTensor indicating exploration completion']
```

Usage

```
{'init_ExploreSkill': 'initialize an ExploreSkill agent with config, observation space, action space, batch size, env, and agent uid', 'discrete_action_to_vel': 'convert a discrete action (forward, turn left, turn right) into linear and angular velocity values', 'get_sim_location': "retrieve the agent's current x, y, orientation pose from the Habitat simulator", 'get_pose_change': 'compute the relative pose change (dx, dy, do) between the current and last timestep', 'update_obs_info': 'update observation info with sensor pose change and concatenated RGB-depth state from observations'}
```

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/explore/oracle_explore_skill.py

Prompts

```
['initialize an ExploreSkill agent with config, observation space, action space, batch size, env, and agent uid', 'convert a discrete action (forward, turn left, turn right) into linear and angular velocity values', "retrieve the agent's current x, y, orientation pose from the Habitat simulator", 'compute the relative pose change (dx, dy, do) between the current and last timestep', 'update observation info with sensor pose change and concatenated RGB-depth state from observations', 'build a python module to instantiate OracleExploreSkill with config, observation space, action space, batch size, env, and agent uid', 'create a function that sets the target room name and populates the furniture queue for exploration', 'test the OracleExploreSkill reset method to clear furniture queue, target, and node reached state', 'refactor the OracleExploreSkill _internal_act method to navigate to next furniture in queue and delegate to nav skill', 'review the OracleExploreSkill _is_skill_done method that returns a BoolTensor indicating exploration completion']
```

Usage

```
{'build_OracleExploreSkill': 'build a python module to instantiate OracleExploreSkill with config, observation space, action space, batch size, env, and agent uid', 'create_set_target': 'create a function that sets the target room name and populates the furniture queue for exploration', 'test_reset': 'test the OracleExploreSkill reset method to clear furniture queue, target, and node reached state', 'refactor_internal_act': 'refactor the OracleExploreSkill _internal_act method to navigate to next furniture in queue and delegate to nav skill', 'review_is_skill_done': 'review the OracleExploreSkill _is_skill_done method that returns a BoolTensor indicating exploration completion'}
```

