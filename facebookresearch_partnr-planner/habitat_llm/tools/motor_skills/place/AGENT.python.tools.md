# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/place/nn_place_skill.py

Prompts

```
['create a PlaceSkillPolicy and call set_target with a comma-separated arg string to configure placement', 'call reset on PlaceSkillPolicy to clear target position, spatial relation, and placement state variables', 'build a placement routine that calls sample_place_location on a Furniture entity to find valid target poses', 'test the _is_skill_done method to verify the agent is not holding an object and arm is at rest', 'summarize the argument_types property to return OBJECT, SPATIAL_RELATION, FURNITURE, and optional constraint grammar', 'use OraclePlaceSkill to place an object on furniture or floor in a simulated environment', 'call set_target with a comma-separated string specifying object, relation, place entity, constraint, and reference object', 'call reset on OraclePlaceSkill to clear placement state and prepare for a new placement task', 'use _is_skill_done to check if the place action was issued and the object was successfully released', 'call get_state_description to get a human-readable string describing the current placement task state']
```

Usage

```
{'set_target_for_place_skill': 'create a PlaceSkillPolicy and call set_target with a comma-separated arg string to configure placement', 'reset_place_skill_policy': 'call reset on PlaceSkillPolicy to clear target position, spatial relation, and placement state variables', 'sample_placement_location': 'build a placement routine that calls sample_place_location on a Furniture entity to find valid target poses', 'check_if_skill_done': 'test the _is_skill_done method to verify the agent is not holding an object and arm is at rest', 'get_argument_types_for_place': 'summarize the argument_types property to return OBJECT, SPATIAL_RELATION, FURNITURE, and optional constraint grammar'}
```

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/place/oracle_place_skill.py

Prompts

```
['create a PlaceSkillPolicy and call set_target with a comma-separated arg string to configure placement', 'call reset on PlaceSkillPolicy to clear target position, spatial relation, and placement state variables', 'build a placement routine that calls sample_place_location on a Furniture entity to find valid target poses', 'test the _is_skill_done method to verify the agent is not holding an object and arm is at rest', 'summarize the argument_types property to return OBJECT, SPATIAL_RELATION, FURNITURE, and optional constraint grammar', 'use OraclePlaceSkill to place an object on furniture or floor in a simulated environment', 'call set_target with a comma-separated string specifying object, relation, place entity, constraint, and reference object', 'call reset on OraclePlaceSkill to clear placement state and prepare for a new placement task', 'use _is_skill_done to check if the place action was issued and the object was successfully released', 'call get_state_description to get a human-readable string describing the current placement task state']
```

Usage

```
{'use_oracle_place_skill_to_place_objects': 'use OraclePlaceSkill to place an object on furniture or floor in a simulated environment', 'set_target_for_placement': 'call set_target with a comma-separated string specifying object, relation, place entity, constraint, and reference object', 'reset_oracle_place_skill_state': 'call reset on OraclePlaceSkill to clear placement state and prepare for a new placement task', 'check_placement_completion': 'use _is_skill_done to check if the place action was issued and the object was successfully released', 'get_placement_state_description': 'call get_state_description to get a human-readable string describing the current placement task state'}
```

