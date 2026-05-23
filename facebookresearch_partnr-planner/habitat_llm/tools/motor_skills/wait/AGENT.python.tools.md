# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/wait/wait_skill.py

Prompts

```
['create a WaitSkill instance that makes an agent wait for a set number of simulation steps', 'reset the WaitSkill step counters and threshold for specified batch indices', 'set the wait time threshold for the WaitSkill using set_target method', 'parse a numeric wait time value from a string using the get_number method', 'check if the WaitSkill has elapsed enough steps to be considered done']
```

Usage

```
{'create_wait_skill': 'create a WaitSkill instance that makes an agent wait for a set number of simulation steps', 'reset_wait_skill': 'reset the WaitSkill step counters and threshold for specified batch indices', 'set_target_wait_time': 'set the wait time threshold for the WaitSkill using set_target method', 'parse_wait_number': 'parse a numeric wait time value from a string using the get_number method', 'check_skill_done': 'check if the WaitSkill has elapsed enough steps to be considered done'}
```

