# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/compound_skill.py

Prompts

```
['create a CompoundSkill instance that executes a sequence of SkillPolicy skills in order', 'get the low-level action from the currently active skill in the compound skill sequence', 'set the target for all skills in the compound skill instance across the environment', 'reset the compound skill and all sub-skills to their initial state for a new batch', 'check if the compound skill sequence has completed execution for a given batch index', 'initialize a MotorSkillTool with a skill_config to wrap a motor skill for the Habitat environment', 'call set_environment on MotorSkillTool to bind it to a Habitat environment and initialize the skill', 'call process_high_level_action with a target string and observations to get low-level robot actions', 'call get_state_description on MotorSkillTool to retrieve a string describing the current skill state', 'call the to method on MotorSkillTool to move the underlying skill model to a specified device', 'create an NnSkillPolicy instance that loads a neural network checkpoint for a Habitat skill', 'review the NnSkillPolicy constructor to understand how it loads TorchScript or standard PyTorch checkpoints', 'test the _internal_act method to verify action output matches expected action space ranges', 'refactor the _get_filtered_obs method to support dynamic agent UID prefixes in observation keys', 'summarize the set_target method that configures navigation targets in the Habitat simulation environment', 'create a subclass of SkillPolicy that implements _internal_act and argument_types for a new motor skill', 'implement the _internal_act method in a SkillPolicy subclass to return predicted actions and hidden states', 'call set_target on a SkillPolicy instance to assign a target entity by name for pick or place skills', 'call reset on a SkillPolicy instance to clear recurrent hidden states, prev actions, and step counters']
```

Usage

```
{'create_compound_skill': 'create a CompoundSkill instance that executes a sequence of SkillPolicy skills in order', 'get_low_level_action': 'get the low-level action from the currently active skill in the compound skill sequence', 'set_target': 'set the target for all skills in the compound skill instance across the environment', 'reset_compound_skill': 'reset the compound skill and all sub-skills to their initial state for a new batch', 'is_skill_done': 'check if the compound skill sequence has completed execution for a given batch index'}
```

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/motor_skill_tool.py

Prompts

```
['create a CompoundSkill instance that executes a sequence of SkillPolicy skills in order', 'get the low-level action from the currently active skill in the compound skill sequence', 'set the target for all skills in the compound skill instance across the environment', 'reset the compound skill and all sub-skills to their initial state for a new batch', 'check if the compound skill sequence has completed execution for a given batch index', 'initialize a MotorSkillTool with a skill_config to wrap a motor skill for the Habitat environment', 'call set_environment on MotorSkillTool to bind it to a Habitat environment and initialize the skill', 'call process_high_level_action with a target string and observations to get low-level robot actions', 'call get_state_description on MotorSkillTool to retrieve a string describing the current skill state', 'call the to method on MotorSkillTool to move the underlying skill model to a specified device', 'create an NnSkillPolicy instance that loads a neural network checkpoint for a Habitat skill', 'review the NnSkillPolicy constructor to understand how it loads TorchScript or standard PyTorch checkpoints', 'test the _internal_act method to verify action output matches expected action space ranges', 'refactor the _get_filtered_obs method to support dynamic agent UID prefixes in observation keys', 'summarize the set_target method that configures navigation targets in the Habitat simulation environment', 'create a subclass of SkillPolicy that implements _internal_act and argument_types for a new motor skill', 'implement the _internal_act method in a SkillPolicy subclass to return predicted actions and hidden states', 'call set_target on a SkillPolicy instance to assign a target entity by name for pick or place skills', 'call reset on a SkillPolicy instance to clear recurrent hidden states, prev actions, and step counters']
```

Usage

```
{'init_motor_skill_tool': 'initialize a MotorSkillTool with a skill_config to wrap a motor skill for the Habitat environment', 'set_environment': 'call set_environment on MotorSkillTool to bind it to a Habitat environment and initialize the skill', 'process_high_level_action': 'call process_high_level_action with a target string and observations to get low-level robot actions', 'get_state_description': 'call get_state_description on MotorSkillTool to retrieve a string describing the current skill state', 'move_skill_to_device': 'call the to method on MotorSkillTool to move the underlying skill model to a specified device'}
```

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/nn_skill.py

Prompts

```
['create a CompoundSkill instance that executes a sequence of SkillPolicy skills in order', 'get the low-level action from the currently active skill in the compound skill sequence', 'set the target for all skills in the compound skill instance across the environment', 'reset the compound skill and all sub-skills to their initial state for a new batch', 'check if the compound skill sequence has completed execution for a given batch index', 'initialize a MotorSkillTool with a skill_config to wrap a motor skill for the Habitat environment', 'call set_environment on MotorSkillTool to bind it to a Habitat environment and initialize the skill', 'call process_high_level_action with a target string and observations to get low-level robot actions', 'call get_state_description on MotorSkillTool to retrieve a string describing the current skill state', 'call the to method on MotorSkillTool to move the underlying skill model to a specified device', 'create an NnSkillPolicy instance that loads a neural network checkpoint for a Habitat skill', 'review the NnSkillPolicy constructor to understand how it loads TorchScript or standard PyTorch checkpoints', 'test the _internal_act method to verify action output matches expected action space ranges', 'refactor the _get_filtered_obs method to support dynamic agent UID prefixes in observation keys', 'summarize the set_target method that configures navigation targets in the Habitat simulation environment', 'create a subclass of SkillPolicy that implements _internal_act and argument_types for a new motor skill', 'implement the _internal_act method in a SkillPolicy subclass to return predicted actions and hidden states', 'call set_target on a SkillPolicy instance to assign a target entity by name for pick or place skills', 'call reset on a SkillPolicy instance to clear recurrent hidden states, prev actions, and step counters']
```

Usage

```
{'create_NnSkillPolicy': 'create an NnSkillPolicy instance that loads a neural network checkpoint for a Habitat skill', 'review_NnSkillPolicy_init': 'review the NnSkillPolicy constructor to understand how it loads TorchScript or standard PyTorch checkpoints', 'test_internal_act': 'test the _internal_act method to verify action output matches expected action space ranges', 'refactor_get_filtered_obs': 'refactor the _get_filtered_obs method to support dynamic agent UID prefixes in observation keys', 'summarize_set_target': 'summarize the set_target method that configures navigation targets in the Habitat simulation environment'}
```

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/skill.py

Prompts

```
['create a CompoundSkill instance that executes a sequence of SkillPolicy skills in order', 'get the low-level action from the currently active skill in the compound skill sequence', 'set the target for all skills in the compound skill instance across the environment', 'reset the compound skill and all sub-skills to their initial state for a new batch', 'check if the compound skill sequence has completed execution for a given batch index', 'initialize a MotorSkillTool with a skill_config to wrap a motor skill for the Habitat environment', 'call set_environment on MotorSkillTool to bind it to a Habitat environment and initialize the skill', 'call process_high_level_action with a target string and observations to get low-level robot actions', 'call get_state_description on MotorSkillTool to retrieve a string describing the current skill state', 'call the to method on MotorSkillTool to move the underlying skill model to a specified device', 'create an NnSkillPolicy instance that loads a neural network checkpoint for a Habitat skill', 'review the NnSkillPolicy constructor to understand how it loads TorchScript or standard PyTorch checkpoints', 'test the _internal_act method to verify action output matches expected action space ranges', 'refactor the _get_filtered_obs method to support dynamic agent UID prefixes in observation keys', 'summarize the set_target method that configures navigation targets in the Habitat simulation environment', 'create a subclass of SkillPolicy that implements _internal_act and argument_types for a new motor skill', 'implement the _internal_act method in a SkillPolicy subclass to return predicted actions and hidden states', 'call set_target on a SkillPolicy instance to assign a target entity by name for pick or place skills', 'call reset on a SkillPolicy instance to clear recurrent hidden states, prev actions, and step counters']
```

Usage

```
{'create_skill_policy_subclass': 'create a subclass of SkillPolicy that implements _internal_act and argument_types for a new motor skill', 'implement_internal_act': 'implement the _internal_act method in a SkillPolicy subclass to return predicted actions and hidden states', 'set_skill_target': 'call set_target on a SkillPolicy instance to assign a target entity by name for pick or place skills', 'reset_skill_state': 'call reset on a SkillPolicy instance to clear recurrent hidden states, prev actions, and step counters', 'get_low_level_action': 'call get_low_level_action on a SkillPolicy instance to produce a clipped low-level action and text response'}
```

