# Agent Python Tools

- repo: facebookresearch/mbrl-lib
- repo_uri: https://github.com/facebookresearch/mbrl-lib

## File: facebookresearch_mbrl-lib/mbrl/types.py

Prompts

```
['create a TransitionBatch dataclass instance with obs, act, next_obs, rewards, terminateds, and truncateds tensors', 'use the TransitionBatch astuple method to convert a batch into a 6-element transition tuple', 'index a TransitionBatch with __getitem__ to extract a subset of transitions by slice or index', 'use add_new_batch_dim on a TransitionBatch to reshape transitions into a new nested batch dimension', 'use RewardFnType, TermFnType, ObsProcessFnType, TensorType, and ModelInput type aliases for MBRL function signatures']
```

Usage

```
{'create_transition_batch': 'create a TransitionBatch dataclass instance with obs, act, next_obs, rewards, terminateds, and truncateds tensors', 'use_astuple': 'use the TransitionBatch astuple method to convert a batch into a 6-element transition tuple', 'index_transition_batch': 'index a TransitionBatch with __getitem__ to extract a subset of transitions by slice or index', 'reshape_batch_dim': 'use add_new_batch_dim on a TransitionBatch to reshape transitions into a new nested batch dimension', 'use_type_aliases': 'use RewardFnType, TermFnType, ObsProcessFnType, TensorType, and ModelInput type aliases for MBRL function signatures'}
```

