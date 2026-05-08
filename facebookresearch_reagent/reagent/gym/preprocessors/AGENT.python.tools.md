# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/gym/preprocessors/default_preprocessors.py

Prompts

```
['create a RecsimObsPreprocessor from a gym environment using the create_from_env class method', 'call the RecsimObsPreprocessor on a single observation to get FeatureData with user and doc features', 'build a RecsimObsPreprocessor with num_docs, discrete_keys, and box_keys parameters for custom config', 'review the RecsimObsPreprocessor create_from_env method to inspect gym observation space parsing logic', 'summarize the RecsimObsPreprocessor call method that converts observations into one-hot and box feature tensors', 'create a replay buffer inserter for a gym environment using make_replay_buffer_inserter', 'add a transition to a replay buffer using BasicReplayBufferInserter', 'create a RecSimReplayBufferInserter from a RecSim gym environment using create_for_env', 'insert a RecSim transition into a replay buffer using RecSimReplayBufferInserter', 'use the ReplayBufferInserter callable type alias for typing replay buffer inserter functions', 'create a DiscreteDqnInputMaker to one-hot encode actions and prepare discrete DQN training input', 'create a PolicyNetworkInputMaker to normalize continuous actions and prepare policy network training input', 'create a SlateQInputMaker to prepare SlateQ training input with item masks and position rewards', 'create a MemoryNetworkInputMaker to reshape state action and reward tensors for memory network training', 'create a ParametricDqnInputMaker to prepare parametric DQN input with possible actions and one-hot encoded actions']
```

Usage

```
{'create_recsim_preprocessor_from_env': 'create a RecsimObsPreprocessor from a gym environment using the create_from_env class method', 'call_recsim_preprocessor_on_observation': 'call the RecsimObsPreprocessor on a single observation to get FeatureData with user and doc features', 'build_recsim_preprocessor_manually': 'build a RecsimObsPreprocessor with num_docs, discrete_keys, and box_keys parameters for custom config', 'review_recsim_preprocessor_obs_space': 'review the RecsimObsPreprocessor create_from_env method to inspect gym observation space parsing logic', 'summarize_recsim_preprocessor_call': 'summarize the RecsimObsPreprocessor call method that converts observations into one-hot and box feature tensors'}
```

## File: facebookresearch_reagent/reagent/gym/preprocessors/replay_buffer_inserters.py

Prompts

```
['create a RecsimObsPreprocessor from a gym environment using the create_from_env class method', 'call the RecsimObsPreprocessor on a single observation to get FeatureData with user and doc features', 'build a RecsimObsPreprocessor with num_docs, discrete_keys, and box_keys parameters for custom config', 'review the RecsimObsPreprocessor create_from_env method to inspect gym observation space parsing logic', 'summarize the RecsimObsPreprocessor call method that converts observations into one-hot and box feature tensors', 'create a replay buffer inserter for a gym environment using make_replay_buffer_inserter', 'add a transition to a replay buffer using BasicReplayBufferInserter', 'create a RecSimReplayBufferInserter from a RecSim gym environment using create_for_env', 'insert a RecSim transition into a replay buffer using RecSimReplayBufferInserter', 'use the ReplayBufferInserter callable type alias for typing replay buffer inserter functions', 'create a DiscreteDqnInputMaker to one-hot encode actions and prepare discrete DQN training input', 'create a PolicyNetworkInputMaker to normalize continuous actions and prepare policy network training input', 'create a SlateQInputMaker to prepare SlateQ training input with item masks and position rewards', 'create a MemoryNetworkInputMaker to reshape state action and reward tensors for memory network training', 'create a ParametricDqnInputMaker to prepare parametric DQN input with possible actions and one-hot encoded actions']
```

Usage

```
{'make_replay_buffer_inserter': 'create a replay buffer inserter for a gym environment using make_replay_buffer_inserter', 'BasicReplayBufferInserter_call': 'add a transition to a replay buffer using BasicReplayBufferInserter', 'RecSimReplayBufferInserter_create_for_env': 'create a RecSimReplayBufferInserter from a RecSim gym environment using create_for_env', 'RecSimReplayBufferInserter_call': 'insert a RecSim transition into a replay buffer using RecSimReplayBufferInserter', 'ReplayBufferInserter_type': 'use the ReplayBufferInserter callable type alias for typing replay buffer inserter functions'}
```

## File: facebookresearch_reagent/reagent/gym/preprocessors/trainer_preprocessor.py

Prompts

```
['create a RecsimObsPreprocessor from a gym environment using the create_from_env class method', 'call the RecsimObsPreprocessor on a single observation to get FeatureData with user and doc features', 'build a RecsimObsPreprocessor with num_docs, discrete_keys, and box_keys parameters for custom config', 'review the RecsimObsPreprocessor create_from_env method to inspect gym observation space parsing logic', 'summarize the RecsimObsPreprocessor call method that converts observations into one-hot and box feature tensors', 'create a replay buffer inserter for a gym environment using make_replay_buffer_inserter', 'add a transition to a replay buffer using BasicReplayBufferInserter', 'create a RecSimReplayBufferInserter from a RecSim gym environment using create_for_env', 'insert a RecSim transition into a replay buffer using RecSimReplayBufferInserter', 'use the ReplayBufferInserter callable type alias for typing replay buffer inserter functions', 'create a DiscreteDqnInputMaker to one-hot encode actions and prepare discrete DQN training input', 'create a PolicyNetworkInputMaker to normalize continuous actions and prepare policy network training input', 'create a SlateQInputMaker to prepare SlateQ training input with item masks and position rewards', 'create a MemoryNetworkInputMaker to reshape state action and reward tensors for memory network training', 'create a ParametricDqnInputMaker to prepare parametric DQN input with possible actions and one-hot encoded actions']
```

Usage

```
{'create_discrete_dqn_input': 'create a DiscreteDqnInputMaker to one-hot encode actions and prepare discrete DQN training input', 'create_policy_network_input': 'create a PolicyNetworkInputMaker to normalize continuous actions and prepare policy network training input', 'create_slateq_input': 'create a SlateQInputMaker to prepare SlateQ training input with item masks and position rewards', 'create_memory_network_input': 'create a MemoryNetworkInputMaker to reshape state action and reward tensors for memory network training', 'create_parametric_dqn_input': 'create a ParametricDqnInputMaker to prepare parametric DQN input with possible actions and one-hot encoded actions'}
```

