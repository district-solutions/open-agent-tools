# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/pick/nn_pick_skill.py

Prompts

```
['create a PickSkillPolicy instance with config, observation space, action space, and batch size for robot picking', 'review the PickSkillPolicy _internal_act method that orchestrates picking, arm retraction, and grasping checks', 'test the PickSkillPolicy _is_skill_done method to verify completion when agent holds object at rest position', 'refactor the PickSkillPolicy _check_grasping method to validate gripper capacity, object movability, and furniture containment', 'summarize the PickSkillPolicy _try_to_pick method that issues oracle pick actions when end-effector is near target', 'initialize OraclePickSkill with config, action space, batch size, env, and agent uid for picking objects', 'reset the OraclePickSkill state and step counter for a new batch of episodes', 'get a human-readable string describing the current picking state of the OraclePickSkill agent', 'check if the pick skill is complete by verifying action issued and gripper holds target object', 'execute the oracle pick action by checking preconditions and issuing gripper commands to pick an object', 'create an OraclePointPickSkill instance with config, observation_space, action_space, batch_size, env, and agent_uid', 'set the grasp target by providing x,y,z world coordinates as a comma-separated string', 'find the closest object within snap distance to a given 3D coordinate in the simulation', 'review the OraclePointPickSkill class that extends OraclePickSkill for coordinate-based object selection', 'refactor the selection_snap_distance threshold logic to customize object proximity matching behavior']
```

Usage

```
{'create_PickSkillPolicy': 'create a PickSkillPolicy instance with config, observation space, action space, and batch size for robot picking', 'review_PickSkillPolicy__internal_act': 'review the PickSkillPolicy _internal_act method that orchestrates picking, arm retraction, and grasping checks', 'test_PickSkillPolicy__is_skill_done': 'test the PickSkillPolicy _is_skill_done method to verify completion when agent holds object at rest position', 'refactor_PickSkillPolicy__check_grasping': 'refactor the PickSkillPolicy _check_grasping method to validate gripper capacity, object movability, and furniture containment', 'summarize_PickSkillPolicy__try_to_pick': 'summarize the PickSkillPolicy _try_to_pick method that issues oracle pick actions when end-effector is near target'}
```

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/pick/oracle_pick_skill.py

Prompts

```
['create a PickSkillPolicy instance with config, observation space, action space, and batch size for robot picking', 'review the PickSkillPolicy _internal_act method that orchestrates picking, arm retraction, and grasping checks', 'test the PickSkillPolicy _is_skill_done method to verify completion when agent holds object at rest position', 'refactor the PickSkillPolicy _check_grasping method to validate gripper capacity, object movability, and furniture containment', 'summarize the PickSkillPolicy _try_to_pick method that issues oracle pick actions when end-effector is near target', 'initialize OraclePickSkill with config, action space, batch size, env, and agent uid for picking objects', 'reset the OraclePickSkill state and step counter for a new batch of episodes', 'get a human-readable string describing the current picking state of the OraclePickSkill agent', 'check if the pick skill is complete by verifying action issued and gripper holds target object', 'execute the oracle pick action by checking preconditions and issuing gripper commands to pick an object', 'create an OraclePointPickSkill instance with config, observation_space, action_space, batch_size, env, and agent_uid', 'set the grasp target by providing x,y,z world coordinates as a comma-separated string', 'find the closest object within snap distance to a given 3D coordinate in the simulation', 'review the OraclePointPickSkill class that extends OraclePickSkill for coordinate-based object selection', 'refactor the selection_snap_distance threshold logic to customize object proximity matching behavior']
```

Usage

```
{'init_OraclePickSkill': 'initialize OraclePickSkill with config, action space, batch size, env, and agent uid for picking objects', 'reset_OraclePickSkill': 'reset the OraclePickSkill state and step counter for a new batch of episodes', 'get_state_description_OraclePickSkill': 'get a human-readable string describing the current picking state of the OraclePickSkill agent', 'is_skill_done_OraclePickSkill': 'check if the pick skill is complete by verifying action issued and gripper holds target object', 'internal_act_OraclePickSkill': 'execute the oracle pick action by checking preconditions and issuing gripper commands to pick an object'}
```

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/pick/oracle_point_pick_skill.py

Prompts

```
['create a PickSkillPolicy instance with config, observation space, action space, and batch size for robot picking', 'review the PickSkillPolicy _internal_act method that orchestrates picking, arm retraction, and grasping checks', 'test the PickSkillPolicy _is_skill_done method to verify completion when agent holds object at rest position', 'refactor the PickSkillPolicy _check_grasping method to validate gripper capacity, object movability, and furniture containment', 'summarize the PickSkillPolicy _try_to_pick method that issues oracle pick actions when end-effector is near target', 'initialize OraclePickSkill with config, action space, batch size, env, and agent uid for picking objects', 'reset the OraclePickSkill state and step counter for a new batch of episodes', 'get a human-readable string describing the current picking state of the OraclePickSkill agent', 'check if the pick skill is complete by verifying action issued and gripper holds target object', 'execute the oracle pick action by checking preconditions and issuing gripper commands to pick an object', 'create an OraclePointPickSkill instance with config, observation_space, action_space, batch_size, env, and agent_uid', 'set the grasp target by providing x,y,z world coordinates as a comma-separated string', 'find the closest object within snap distance to a given 3D coordinate in the simulation', 'review the OraclePointPickSkill class that extends OraclePickSkill for coordinate-based object selection', 'refactor the selection_snap_distance threshold logic to customize object proximity matching behavior']
```

Usage

```
{'create_oracle_point_pick_skill': 'create an OraclePointPickSkill instance with config, observation_space, action_space, batch_size, env, and agent_uid', 'set_target_by_coordinates': 'set the grasp target by providing x,y,z world coordinates as a comma-separated string', 'find_closest_object_to_point': 'find the closest object within snap distance to a given 3D coordinate in the simulation', 'review_oracle_point_pick_skill_class': 'review the OraclePointPickSkill class that extends OraclePickSkill for coordinate-based object selection', 'refactor_selection_snap_distance': 'refactor the selection_snap_distance threshold logic to customize object proximity matching behavior'}
```

