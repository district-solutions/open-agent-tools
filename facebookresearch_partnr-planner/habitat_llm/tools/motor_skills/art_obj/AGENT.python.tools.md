# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/art_obj/nn_close_skill.py

Prompts

```
['build a CloseSkillPolicy instance to control an agent closing articulated objects in a Habitat simulation', 'create a neural network policy that closes furniture like fridge doors by reaching handles and triggering oracle close actions', 'test the _internal_act method to verify the agent retracts its arm and populates close action tensors correctly', 'review the get_state_description method to understand how it reports the agent closing state from the world graph', 'refactor the CloseSkillPolicy constructor to customize action range indices for close flag, object id, and surface parameters', 'create an OpenSkillPolicy instance to control a robot agent opening articulated objects in Habitat simulation', 'test the _is_skill_done method to check if the opening skill completed by comparing joint positions to resting state', 'review the _get_art_obj_info method that retrieves articulated object info and validates if target is openable furniture', 'refactor the _get_oracle_skill_param method to customize distance checks and grasp validation for oracle open actions', 'summarize the _internal_act method that generates oracle open actions when the robot arm reaches the articulated object handle', 'build an oracle skill policy that opens or closes articulated furniture in a Habitat simulation', 'create an OracleOpenSkill instance that opens articulated furniture like cabinets or drawers in the sim', 'create an OracleCloseSkill instance that closes articulated furniture like cabinets or drawers in the sim', 'review the _internal_act method that issues open or close actions on articulated objects']
```

Usage

```
{'build_CloseSkillPolicy': 'build a CloseSkillPolicy instance to control an agent closing articulated objects in a Habitat simulation', 'create_close_action_policy': 'create a neural network policy that closes furniture like fridge doors by reaching handles and triggering oracle close actions', 'test_internal_act': 'test the _internal_act method to verify the agent retracts its arm and populates close action tensors correctly', 'review_get_state_description': 'review the get_state_description method to understand how it reports the agent closing state from the world graph', 'refactor_CloseSkillPolicy_init': 'refactor the CloseSkillPolicy constructor to customize action range indices for close flag, object id, and surface parameters'}
```

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/art_obj/nn_open_skill.py

Prompts

```
['build a CloseSkillPolicy instance to control an agent closing articulated objects in a Habitat simulation', 'create a neural network policy that closes furniture like fridge doors by reaching handles and triggering oracle close actions', 'test the _internal_act method to verify the agent retracts its arm and populates close action tensors correctly', 'review the get_state_description method to understand how it reports the agent closing state from the world graph', 'refactor the CloseSkillPolicy constructor to customize action range indices for close flag, object id, and surface parameters', 'create an OpenSkillPolicy instance to control a robot agent opening articulated objects in Habitat simulation', 'test the _is_skill_done method to check if the opening skill completed by comparing joint positions to resting state', 'review the _get_art_obj_info method that retrieves articulated object info and validates if target is openable furniture', 'refactor the _get_oracle_skill_param method to customize distance checks and grasp validation for oracle open actions', 'summarize the _internal_act method that generates oracle open actions when the robot arm reaches the articulated object handle', 'build an oracle skill policy that opens or closes articulated furniture in a Habitat simulation', 'create an OracleOpenSkill instance that opens articulated furniture like cabinets or drawers in the sim', 'create an OracleCloseSkill instance that closes articulated furniture like cabinets or drawers in the sim', 'review the _internal_act method that issues open or close actions on articulated objects']
```

Usage

```
{'create_OpenSkillPolicy': 'create an OpenSkillPolicy instance to control a robot agent opening articulated objects in Habitat simulation', 'test_is_skill_done': 'test the _is_skill_done method to check if the opening skill completed by comparing joint positions to resting state', 'review_get_art_obj_info': 'review the _get_art_obj_info method that retrieves articulated object info and validates if target is openable furniture', 'refactor_get_oracle_skill_param': 'refactor the _get_oracle_skill_param method to customize distance checks and grasp validation for oracle open actions', 'summarize_internal_act': 'summarize the _internal_act method that generates oracle open actions when the robot arm reaches the articulated object handle'}
```

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/art_obj/oracle_open_close_skill.py

Prompts

```
['build a CloseSkillPolicy instance to control an agent closing articulated objects in a Habitat simulation', 'create a neural network policy that closes furniture like fridge doors by reaching handles and triggering oracle close actions', 'test the _internal_act method to verify the agent retracts its arm and populates close action tensors correctly', 'review the get_state_description method to understand how it reports the agent closing state from the world graph', 'refactor the CloseSkillPolicy constructor to customize action range indices for close flag, object id, and surface parameters', 'create an OpenSkillPolicy instance to control a robot agent opening articulated objects in Habitat simulation', 'test the _is_skill_done method to check if the opening skill completed by comparing joint positions to resting state', 'review the _get_art_obj_info method that retrieves articulated object info and validates if target is openable furniture', 'refactor the _get_oracle_skill_param method to customize distance checks and grasp validation for oracle open actions', 'summarize the _internal_act method that generates oracle open actions when the robot arm reaches the articulated object handle', 'build an oracle skill policy that opens or closes articulated furniture in a Habitat simulation', 'create an OracleOpenSkill instance that opens articulated furniture like cabinets or drawers in the sim', 'create an OracleCloseSkill instance that closes articulated furniture like cabinets or drawers in the sim', 'review the _internal_act method that issues open or close actions on articulated objects']
```

Usage

```
{'build_OracleOpenCloseSkill': 'build an oracle skill policy that opens or closes articulated furniture in a Habitat simulation', 'create_OracleOpenSkill': 'create an OracleOpenSkill instance that opens articulated furniture like cabinets or drawers in the sim', 'create_OracleCloseSkill': 'create an OracleCloseSkill instance that closes articulated furniture like cabinets or drawers in the sim', 'review_internal_act': 'review the _internal_act method that issues open or close actions on articulated objects', 'test_is_skill_done': 'test the _is_skill_done method that returns whether the open or close action succeeded'}
```

