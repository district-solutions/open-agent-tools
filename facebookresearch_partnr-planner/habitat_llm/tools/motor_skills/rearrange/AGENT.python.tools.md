# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/rearrange/nn_rearrange_skill.py

Prompts

```
['initialize a RearrangeSkillPolicy with config, observation space, action space, batch size, env, and agent uid', 'set the rearrange target using a comma-separated string with object, relation, receptacle, constraint, and reference', 'execute the active atomic skill and transition to the next skill in the nav-pick-nav-place sequence', 'review the RearrangeSkillPolicy class that composes NavSkillPolicy, PickSkillPolicy, and PlaceSkillPolicy into a rearrange sequence', 'summarize the RearrangeSkillPolicy which manages a four-step atomic skill sequence for object rearrangement in Habitat', 'instantiate OracleRearrangeSkill with config, observation space, action space, batch size, env, and agent uid', 'call set_target with a comma-separated arg string specifying object, relation, furniture, constraint, and reference object', 'call the argument_types property to retrieve the list of required argument type strings for rearrange', 'call reset with batch indices to reset the rearrange skill and all underlying atomic skills', 'call _is_skill_done with observations, hidden states, prev actions, masks, and batch index to check completion']
```

Usage

```
{'init_RearrangeSkillPolicy': 'initialize a RearrangeSkillPolicy with config, observation space, action space, batch size, env, and agent uid', 'set_target_RearrangeSkillPolicy': 'set the rearrange target using a comma-separated string with object, relation, receptacle, constraint, and reference', 'act_RearrangeSkillPolicy': 'execute the active atomic skill and transition to the next skill in the nav-pick-nav-place sequence', 'review_RearrangeSkillPolicy_class': 'review the RearrangeSkillPolicy class that composes NavSkillPolicy, PickSkillPolicy, and PlaceSkillPolicy into a rearrange sequence', 'summarize_RearrangeSkillPolicy': 'summarize the RearrangeSkillPolicy which manages a four-step atomic skill sequence for object rearrangement in Habitat'}
```

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/rearrange/oracle_rearrange_skill.py

Prompts

```
['initialize a RearrangeSkillPolicy with config, observation space, action space, batch size, env, and agent uid', 'set the rearrange target using a comma-separated string with object, relation, receptacle, constraint, and reference', 'execute the active atomic skill and transition to the next skill in the nav-pick-nav-place sequence', 'review the RearrangeSkillPolicy class that composes NavSkillPolicy, PickSkillPolicy, and PlaceSkillPolicy into a rearrange sequence', 'summarize the RearrangeSkillPolicy which manages a four-step atomic skill sequence for object rearrangement in Habitat', 'instantiate OracleRearrangeSkill with config, observation space, action space, batch size, env, and agent uid', 'call set_target with a comma-separated arg string specifying object, relation, furniture, constraint, and reference object', 'call the argument_types property to retrieve the list of required argument type strings for rearrange', 'call reset with batch indices to reset the rearrange skill and all underlying atomic skills', 'call _is_skill_done with observations, hidden states, prev actions, masks, and batch index to check completion']
```

Usage

```
{'instantiate_OracleRearrangeSkill': 'instantiate OracleRearrangeSkill with config, observation space, action space, batch size, env, and agent uid', 'set_target_rearrange': 'call set_target with a comma-separated arg string specifying object, relation, furniture, constraint, and reference object', 'get_argument_types': 'call the argument_types property to retrieve the list of required argument type strings for rearrange', 'reset_skill': 'call reset with batch indices to reset the rearrange skill and all underlying atomic skills', 'check_skill_done': 'call _is_skill_done with observations, hidden states, prev actions, masks, and batch index to check completion'}
```

