# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/replay_memory/circular_replay_buffer.py

Prompts

```
['create a ReplayBuffer instance with stack_size, replay_capacity, batch_size, update_horizon, and gamma parameters', 'add observation, action, reward, and terminal transitions to the ReplayBuffer using the add method', 'sample a batch of transitions from the ReplayBuffer using sample_transition_batch with a specified batch_size', 'save the ReplayBuffer state to checkpoint files and load it back using save and load methods', 'create DenseMetadata, IDListMetadata, or IDScoreListMetadata from an example using make_replay_element', 'create a PrioritizedReplayBuffer instance with stack size, replay capacity, and batch size parameters', 'sample a batch of valid transition indices using stratified priority sampling from the sum tree', 'set the priority values for given transition indices in the sum tree', 'fetch the priority values for a batch of memory indices from the sum tree', 'create a SumTree instance with a given capacity for prioritized experience replay', 'sample a single element from the SumTree using priority-weighted random selection', 'perform stratified sampling on the SumTree to get a batch of elements', 'set the priority value of a leaf node in the SumTree and update internal nodes', 'get the priority value of a leaf node at a given index in the SumTree', 'convert a dense numpy 2D array into a list of sparse dictionaries mapping indices to values', 'convert a replay buffer into a pandas DataFrame formatted for Hive upload and timeline analysis', 'extract discrete actions from a replay buffer batch and format them as string values', 'extract parametric box actions from a replay buffer batch and convert them to sparse representation', 'compute action probabilities from log probabilities in a replay buffer batch using exponential transform']
```

Usage

```
{'create_replay_buffer': 'create a ReplayBuffer instance with stack_size, replay_capacity, batch_size, update_horizon, and gamma parameters', 'add_transitions_to_buffer': 'add observation, action, reward, and terminal transitions to the ReplayBuffer using the add method', 'sample_transition_batch': 'sample a batch of transitions from the ReplayBuffer using sample_transition_batch with a specified batch_size', 'save_and_load_checkpoints': 'save the ReplayBuffer state to checkpoint files and load it back using save and load methods', 'create_metadata_from_example': 'create DenseMetadata, IDListMetadata, or IDScoreListMetadata from an example using make_replay_element'}
```

## File: facebookresearch_reagent/reagent/replay_memory/prioritized_replay_buffer.py

Prompts

```
['create a ReplayBuffer instance with stack_size, replay_capacity, batch_size, update_horizon, and gamma parameters', 'add observation, action, reward, and terminal transitions to the ReplayBuffer using the add method', 'sample a batch of transitions from the ReplayBuffer using sample_transition_batch with a specified batch_size', 'save the ReplayBuffer state to checkpoint files and load it back using save and load methods', 'create DenseMetadata, IDListMetadata, or IDScoreListMetadata from an example using make_replay_element', 'create a PrioritizedReplayBuffer instance with stack size, replay capacity, and batch size parameters', 'sample a batch of valid transition indices using stratified priority sampling from the sum tree', 'set the priority values for given transition indices in the sum tree', 'fetch the priority values for a batch of memory indices from the sum tree', 'create a SumTree instance with a given capacity for prioritized experience replay', 'sample a single element from the SumTree using priority-weighted random selection', 'perform stratified sampling on the SumTree to get a batch of elements', 'set the priority value of a leaf node in the SumTree and update internal nodes', 'get the priority value of a leaf node at a given index in the SumTree', 'convert a dense numpy 2D array into a list of sparse dictionaries mapping indices to values', 'convert a replay buffer into a pandas DataFrame formatted for Hive upload and timeline analysis', 'extract discrete actions from a replay buffer batch and format them as string values', 'extract parametric box actions from a replay buffer batch and convert them to sparse representation', 'compute action probabilities from log probabilities in a replay buffer batch using exponential transform']
```

Usage

```
{'create_prioritized_replay_buffer': 'create a PrioritizedReplayBuffer instance with stack size, replay capacity, and batch size parameters', 'sample_index_batch': 'sample a batch of valid transition indices using stratified priority sampling from the sum tree', 'sample_transition_batch': 'sample a batch of transitions with sampling probabilities from the prioritized replay buffer', 'set_priority': 'set the priority values for given transition indices in the sum tree', 'get_priority': 'fetch the priority values for a batch of memory indices from the sum tree'}
```

## File: facebookresearch_reagent/reagent/replay_memory/sum_tree.py

Prompts

```
['create a ReplayBuffer instance with stack_size, replay_capacity, batch_size, update_horizon, and gamma parameters', 'add observation, action, reward, and terminal transitions to the ReplayBuffer using the add method', 'sample a batch of transitions from the ReplayBuffer using sample_transition_batch with a specified batch_size', 'save the ReplayBuffer state to checkpoint files and load it back using save and load methods', 'create DenseMetadata, IDListMetadata, or IDScoreListMetadata from an example using make_replay_element', 'create a PrioritizedReplayBuffer instance with stack size, replay capacity, and batch size parameters', 'sample a batch of valid transition indices using stratified priority sampling from the sum tree', 'set the priority values for given transition indices in the sum tree', 'fetch the priority values for a batch of memory indices from the sum tree', 'create a SumTree instance with a given capacity for prioritized experience replay', 'sample a single element from the SumTree using priority-weighted random selection', 'perform stratified sampling on the SumTree to get a batch of elements', 'set the priority value of a leaf node in the SumTree and update internal nodes', 'get the priority value of a leaf node at a given index in the SumTree', 'convert a dense numpy 2D array into a list of sparse dictionaries mapping indices to values', 'convert a replay buffer into a pandas DataFrame formatted for Hive upload and timeline analysis', 'extract discrete actions from a replay buffer batch and format them as string values', 'extract parametric box actions from a replay buffer batch and convert them to sparse representation', 'compute action probabilities from log probabilities in a replay buffer batch using exponential transform']
```

Usage

```
{'create_SumTree': 'create a SumTree instance with a given capacity for prioritized experience replay', 'sample_SumTree': 'sample a single element from the SumTree using priority-weighted random selection', 'stratified_sample_SumTree': 'perform stratified sampling on the SumTree to get a batch of elements', 'set_SumTree_leaf': 'set the priority value of a leaf node in the SumTree and update internal nodes', 'get_SumTree_leaf': 'get the priority value of a leaf node at a given index in the SumTree'}
```

## File: facebookresearch_reagent/reagent/replay_memory/utils.py

Prompts

```
['create a ReplayBuffer instance with stack_size, replay_capacity, batch_size, update_horizon, and gamma parameters', 'add observation, action, reward, and terminal transitions to the ReplayBuffer using the add method', 'sample a batch of transitions from the ReplayBuffer using sample_transition_batch with a specified batch_size', 'save the ReplayBuffer state to checkpoint files and load it back using save and load methods', 'create DenseMetadata, IDListMetadata, or IDScoreListMetadata from an example using make_replay_element', 'create a PrioritizedReplayBuffer instance with stack size, replay capacity, and batch size parameters', 'sample a batch of valid transition indices using stratified priority sampling from the sum tree', 'set the priority values for given transition indices in the sum tree', 'fetch the priority values for a batch of memory indices from the sum tree', 'create a SumTree instance with a given capacity for prioritized experience replay', 'sample a single element from the SumTree using priority-weighted random selection', 'perform stratified sampling on the SumTree to get a batch of elements', 'set the priority value of a leaf node in the SumTree and update internal nodes', 'get the priority value of a leaf node at a given index in the SumTree', 'convert a dense numpy 2D array into a list of sparse dictionaries mapping indices to values', 'convert a replay buffer into a pandas DataFrame formatted for Hive upload and timeline analysis', 'extract discrete actions from a replay buffer batch and format them as string values', 'extract parametric box actions from a replay buffer batch and convert them to sparse representation', 'compute action probabilities from log probabilities in a replay buffer batch using exponential transform']
```

Usage

```
{'convert_dense_to_sparse': 'convert a dense numpy 2D array into a list of sparse dictionaries mapping indices to values', 'replay_buffer_to_dataframe': 'convert a replay buffer into a pandas DataFrame formatted for Hive upload and timeline analysis', 'extract_discrete_actions': 'extract discrete actions from a replay buffer batch and format them as string values', 'extract_parametric_actions': 'extract parametric box actions from a replay buffer batch and convert them to sparse representation', 'compute_action_probability': 'compute action probabilities from log probabilities in a replay buffer batch using exponential transform'}
```

