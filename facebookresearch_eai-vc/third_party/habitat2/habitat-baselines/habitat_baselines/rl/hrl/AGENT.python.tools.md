# Agent Python Tools

- repo: facebookresearch/eai-vc
- repo_uri: https://github.com/facebookresearch/eai-vc

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/rl/hrl/hierarchical_policy.py

Prompts

```
['build a HierarchicalPolicy from config to orchestrate high-level and low-level skill policies for Habitat tasks', 'create an act call on HierarchicalPolicy to get actions from the current active skill for each environment', 'test the _broadcast_skill_ids method to group batch observations by skill ID for efficient processing', 'review the get_policy_info method to extract current skill names and failure status per environment', 'refactor the from_config class method to customize how HierarchicalPolicy is constructed from a Habitat config', 'create a FixedHighLevelPolicy instance from a task spec file with solution actions and skill mappings', 'apply a mask tensor to reset solution action indices for specific environments in the policy', 'get the next skill name and arguments from the precomputed solution plan for each environment', 'review the FixedHighLevelPolicy class that executes hardcoded PDDL solution plans step by step across environments', 'summarize how get_next_skill returns the next planned skill index and arguments based on plan masks', 'find the start and end indices of an action key in a Habitat action space tensor', 'review the find_action_range function that returns start and end indices for an action key in an action space', 'test the find_action_range function with a Habitat ActionSpace and a search key string', 'refactor the find_action_range function to raise a more descriptive error when the search key is not found', 'summarize the find_action_range function that iterates over an action space to compute index ranges']
```

Usage

```
{'build_hierarchical_policy': 'build a HierarchicalPolicy from config to orchestrate high-level and low-level skill policies for Habitat tasks', 'create_act_method': 'create an act call on HierarchicalPolicy to get actions from the current active skill for each environment', 'test_broadcast_skill_ids': 'test the _broadcast_skill_ids method to group batch observations by skill ID for efficient processing', 'review_get_policy_info': 'review the get_policy_info method to extract current skill names and failure status per environment', 'refactor_from_config': 'refactor the from_config class method to customize how HierarchicalPolicy is constructed from a Habitat config'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/rl/hrl/high_level_policy.py

Prompts

```
['build a HierarchicalPolicy from config to orchestrate high-level and low-level skill policies for Habitat tasks', 'create an act call on HierarchicalPolicy to get actions from the current active skill for each environment', 'test the _broadcast_skill_ids method to group batch observations by skill ID for efficient processing', 'review the get_policy_info method to extract current skill names and failure status per environment', 'refactor the from_config class method to customize how HierarchicalPolicy is constructed from a Habitat config', 'create a FixedHighLevelPolicy instance from a task spec file with solution actions and skill mappings', 'apply a mask tensor to reset solution action indices for specific environments in the policy', 'get the next skill name and arguments from the precomputed solution plan for each environment', 'review the FixedHighLevelPolicy class that executes hardcoded PDDL solution plans step by step across environments', 'summarize how get_next_skill returns the next planned skill index and arguments based on plan masks', 'find the start and end indices of an action key in a Habitat action space tensor', 'review the find_action_range function that returns start and end indices for an action key in an action space', 'test the find_action_range function with a Habitat ActionSpace and a search key string', 'refactor the find_action_range function to raise a more descriptive error when the search key is not found', 'summarize the find_action_range function that iterates over an action space to compute index ranges']
```

Usage

```
{'init_FixedHighLevelPolicy': 'create a FixedHighLevelPolicy instance from a task spec file with solution actions and skill mappings', 'apply_mask_FixedHighLevelPolicy': 'apply a mask tensor to reset solution action indices for specific environments in the policy', 'get_next_skill_FixedHighLevelPolicy': 'get the next skill name and arguments from the precomputed solution plan for each environment', 'review_FixedHighLevelPolicy_class': 'review the FixedHighLevelPolicy class that executes hardcoded PDDL solution plans step by step across environments', 'summarize_FixedHighLevelPolicy_get_next_skill': 'summarize how get_next_skill returns the next planned skill index and arguments based on plan masks'}
```

## File: facebookresearch_eai-vc/third_party/habitat2/habitat-baselines/habitat_baselines/rl/hrl/utils.py

Prompts

```
['build a HierarchicalPolicy from config to orchestrate high-level and low-level skill policies for Habitat tasks', 'create an act call on HierarchicalPolicy to get actions from the current active skill for each environment', 'test the _broadcast_skill_ids method to group batch observations by skill ID for efficient processing', 'review the get_policy_info method to extract current skill names and failure status per environment', 'refactor the from_config class method to customize how HierarchicalPolicy is constructed from a Habitat config', 'create a FixedHighLevelPolicy instance from a task spec file with solution actions and skill mappings', 'apply a mask tensor to reset solution action indices for specific environments in the policy', 'get the next skill name and arguments from the precomputed solution plan for each environment', 'review the FixedHighLevelPolicy class that executes hardcoded PDDL solution plans step by step across environments', 'summarize how get_next_skill returns the next planned skill index and arguments based on plan masks', 'find the start and end indices of an action key in a Habitat action space tensor', 'review the find_action_range function that returns start and end indices for an action key in an action space', 'test the find_action_range function with a Habitat ActionSpace and a search key string', 'refactor the find_action_range function to raise a more descriptive error when the search key is not found', 'summarize the find_action_range function that iterates over an action space to compute index ranges']
```

Usage

```
{'find_action_range_indices': 'find the start and end indices of an action key in a Habitat action space tensor', 'review_find_action_range': 'review the find_action_range function that returns start and end indices for an action key in an action space', 'test_find_action_range': 'test the find_action_range function with a Habitat ActionSpace and a search key string', 'refactor_find_action_range_error': 'refactor the find_action_range function to raise a more descriptive error when the search key is not found', 'summarize_find_action_range': 'summarize the find_action_range function that iterates over an action space to compute index ranges'}
```

