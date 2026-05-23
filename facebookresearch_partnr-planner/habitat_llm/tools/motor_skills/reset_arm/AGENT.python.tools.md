# Agent Python Tools

- repo: facebookresearch/partnr-planner
- repo_uri: https://github.com/facebookresearch/partnr-planner

## File: facebookresearch_partnr-planner/habitat_llm/tools/motor_skills/reset_arm/reset_arm_skill.py

Prompts

```
['create a ResetArmSkill instance with config, action space, and batch size to reset robot arm joints', 'review the ResetArmSkill reset method to reinitialize skill state for given batch indices', 'review the ResetArmSkill _is_skill_done method to check if arm joints are within tolerance of target', 'review the ResetArmSkill _internal_act method to compute normalized delta actions for arm joint control', 'refactor the ResetArmSkill _internal_act method to normalize arm actions using initial delta for convergence']
```

Usage

```
{'create_ResetArmSkill': 'create a ResetArmSkill instance with config, action space, and batch size to reset robot arm joints', 'review_ResetArmSkill_reset': 'review the ResetArmSkill reset method to reinitialize skill state for given batch indices', 'review_ResetArmSkill_is_skill_done': 'review the ResetArmSkill _is_skill_done method to check if arm joints are within tolerance of target', 'review_ResetArmSkill_internal_act': 'review the ResetArmSkill _internal_act method to compute normalized delta actions for arm joint control', 'refactor_ResetArmSkill_internal_act': 'refactor the ResetArmSkill _internal_act method to normalize arm actions using initial delta for convergence'}
```

