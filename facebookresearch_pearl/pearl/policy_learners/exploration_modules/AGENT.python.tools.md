# Agent Python Tools

- repo: facebookresearch/pearl
- repo_uri: https://github.com/facebookresearch/pearl

## File: facebookresearch_pearl/pearl/policy_learners/exploration_modules/exploration_module.py

Prompts

```
['implement a subclass of ExplorationModule that overrides act and compare methods for a custom strategy', 'use the ExplorationType enum to select between UNIFORM, BOLTZMANN, REPRESENTATION, EPISTEMICNN, or VALUE strategies', 'call the act method on an ExplorationModule subclass to select an action from a subjective state and action space', 'call the reset method on an ExplorationModule to clear its internal state before a new episode', 'call the compare method on two ExplorationModule instances to get a string describing their differences', 'create an ExplorationModuleWrapper instance wrapping an existing ExplorationModule for delegated behavior', 'reset the ExplorationModuleWrapper to delegate reset to the wrapped exploration module', 'call act on the ExplorationModuleWrapper to get an Action from the wrapped module', 'call learn on the ExplorationModuleWrapper to train the wrapped module from a replay buffer', 'review the ExplorationModuleWrapper class and its delegation pattern for exploration modules']
```

Usage

```
{'implement_exploration_module_subclass': 'implement a subclass of ExplorationModule that overrides act and compare methods for a custom strategy', 'use_exploration_type_enum': 'use the ExplorationType enum to select between UNIFORM, BOLTZMANN, REPRESENTATION, EPISTEMICNN, or VALUE strategies', 'call_act_method': 'call the act method on an ExplorationModule subclass to select an action from a subjective state and action space', 'call_reset_method': 'call the reset method on an ExplorationModule to clear its internal state before a new episode', 'call_compare_method': 'call the compare method on two ExplorationModule instances to get a string describing their differences'}
```

## File: facebookresearch_pearl/pearl/policy_learners/exploration_modules/exploration_module_wrapper.py

Prompts

```
['implement a subclass of ExplorationModule that overrides act and compare methods for a custom strategy', 'use the ExplorationType enum to select between UNIFORM, BOLTZMANN, REPRESENTATION, EPISTEMICNN, or VALUE strategies', 'call the act method on an ExplorationModule subclass to select an action from a subjective state and action space', 'call the reset method on an ExplorationModule to clear its internal state before a new episode', 'call the compare method on two ExplorationModule instances to get a string describing their differences', 'create an ExplorationModuleWrapper instance wrapping an existing ExplorationModule for delegated behavior', 'reset the ExplorationModuleWrapper to delegate reset to the wrapped exploration module', 'call act on the ExplorationModuleWrapper to get an Action from the wrapped module', 'call learn on the ExplorationModuleWrapper to train the wrapped module from a replay buffer', 'review the ExplorationModuleWrapper class and its delegation pattern for exploration modules']
```

Usage

```
{'create_exploration_module_wrapper': 'create an ExplorationModuleWrapper instance wrapping an existing ExplorationModule for delegated behavior', 'reset_exploration_module_wrapper': 'reset the ExplorationModuleWrapper to delegate reset to the wrapped exploration module', 'act_exploration_module_wrapper': 'call act on the ExplorationModuleWrapper to get an Action from the wrapped module', 'learn_exploration_module_wrapper': 'call learn on the ExplorationModuleWrapper to train the wrapped module from a replay buffer', 'review_exploration_module_wrapper_class': 'review the ExplorationModuleWrapper class and its delegation pattern for exploration modules'}
```

