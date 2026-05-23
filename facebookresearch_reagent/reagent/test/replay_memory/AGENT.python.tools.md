# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/reagent/test/replay_memory/circular_replay_buffer_test.py

Prompts

```
['create a ReplayBuffer with stack_size, replay_capacity, and batch_size parameters', 'add observation, action, reward, and terminal transitions to the replay buffer', 'sample a batch of transitions from the replay buffer with optional custom indices', 'test N-step reward accumulation using update_horizon and gamma parameters', 'check if a transition at a given index is valid for sampling', 'test the CreateFromEnvTest class to verify ReplayBuffer works with RecSim interest exploration environment', 'test the CreateFromEnvTest class to verify ReplayBuffer works with RecSim interest evolution environment', 'run the ReplayBuffer add method with RecSim interest exploration observation action reward and terminal data', 'run the ReplayBuffer add method with RecSim interest evolution observation doc response and log probability data', 'review the CreateFromEnvTest class and its two test methods for RecSim replay buffer integration', 'test the ReplayBuffer with stacked observations across multiple random trajectory lengths', 'test the ReplayBuffer with stacked observations and multi-step timeline format', 'test the ReplayBuffer circular overflow behavior when transitions overwrite older entries', 'test the ReplayBuffer with sparse id_list and id_score_list features', 'test the ReplayBuffer setup by inserting trajectories and sampling all valid transitions', 'create a PrioritizedReplayBuffer with stack size, capacity, and batch size parameters', 'test adding transitions to the replay buffer with and without priority arguments', 'test setting and retrieving priorities for batch indices in the replay buffer', 'test sampling transition batches from the prioritized replay buffer with priority weighting', 'test sampling index batches from the replay buffer and validate cursor boundaries', 'create a SumTree with a given capacity for priority-based experience replay sampling', 'test setting and getting values at specific node indices in a SumTree', 'test sampling from a SumTree using random or explicit query values', 'test stratified sampling to retrieve k evenly spaced samples from a SumTree', 'test tracking the maximum recorded priority value in a SumTree']
```

Usage

```
{'create_replay_buffer': 'create a ReplayBuffer with stack_size, replay_capacity, and batch_size parameters', 'add_transitions': 'add observation, action, reward, and terminal transitions to the replay buffer', 'sample_transition_batch': 'sample a batch of transitions from the replay buffer with optional custom indices', 'test_nstep_reward': 'test N-step reward accumulation using update_horizon and gamma parameters', 'check_valid_transition': 'check if a transition at a given index is valid for sampling'}
```

## File: facebookresearch_reagent/reagent/test/replay_memory/create_from_env_test.py

Prompts

```
['create a ReplayBuffer with stack_size, replay_capacity, and batch_size parameters', 'add observation, action, reward, and terminal transitions to the replay buffer', 'sample a batch of transitions from the replay buffer with optional custom indices', 'test N-step reward accumulation using update_horizon and gamma parameters', 'check if a transition at a given index is valid for sampling', 'test the CreateFromEnvTest class to verify ReplayBuffer works with RecSim interest exploration environment', 'test the CreateFromEnvTest class to verify ReplayBuffer works with RecSim interest evolution environment', 'run the ReplayBuffer add method with RecSim interest exploration observation action reward and terminal data', 'run the ReplayBuffer add method with RecSim interest evolution observation doc response and log probability data', 'review the CreateFromEnvTest class and its two test methods for RecSim replay buffer integration', 'test the ReplayBuffer with stacked observations across multiple random trajectory lengths', 'test the ReplayBuffer with stacked observations and multi-step timeline format', 'test the ReplayBuffer circular overflow behavior when transitions overwrite older entries', 'test the ReplayBuffer with sparse id_list and id_score_list features', 'test the ReplayBuffer setup by inserting trajectories and sampling all valid transitions', 'create a PrioritizedReplayBuffer with stack size, capacity, and batch size parameters', 'test adding transitions to the replay buffer with and without priority arguments', 'test setting and retrieving priorities for batch indices in the replay buffer', 'test sampling transition batches from the prioritized replay buffer with priority weighting', 'test sampling index batches from the replay buffer and validate cursor boundaries', 'create a SumTree with a given capacity for priority-based experience replay sampling', 'test setting and getting values at specific node indices in a SumTree', 'test sampling from a SumTree using random or explicit query values', 'test stratified sampling to retrieve k evenly spaced samples from a SumTree', 'test tracking the maximum recorded priority value in a SumTree']
```

Usage

```
{'test_recsim_interest_exploration': 'test the CreateFromEnvTest class to verify ReplayBuffer works with RecSim interest exploration environment', 'test_recsim_interest_evolution': 'test the CreateFromEnvTest class to verify ReplayBuffer works with RecSim interest evolution environment', 'run_replay_buffer_add_interest_exploration': 'run the ReplayBuffer add method with RecSim interest exploration observation action reward and terminal data', 'run_replay_buffer_add_interest_evolution': 'run the ReplayBuffer add method with RecSim interest evolution observation doc response and log probability data', 'review_CreateFromEnvTest': 'review the CreateFromEnvTest class and its two test methods for RecSim replay buffer integration'}
```

## File: facebookresearch_reagent/reagent/test/replay_memory/extra_replay_buffer_test.py

Prompts

```
['create a ReplayBuffer with stack_size, replay_capacity, and batch_size parameters', 'add observation, action, reward, and terminal transitions to the replay buffer', 'sample a batch of transitions from the replay buffer with optional custom indices', 'test N-step reward accumulation using update_horizon and gamma parameters', 'check if a transition at a given index is valid for sampling', 'test the CreateFromEnvTest class to verify ReplayBuffer works with RecSim interest exploration environment', 'test the CreateFromEnvTest class to verify ReplayBuffer works with RecSim interest evolution environment', 'run the ReplayBuffer add method with RecSim interest exploration observation action reward and terminal data', 'run the ReplayBuffer add method with RecSim interest evolution observation doc response and log probability data', 'review the CreateFromEnvTest class and its two test methods for RecSim replay buffer integration', 'test the ReplayBuffer with stacked observations across multiple random trajectory lengths', 'test the ReplayBuffer with stacked observations and multi-step timeline format', 'test the ReplayBuffer circular overflow behavior when transitions overwrite older entries', 'test the ReplayBuffer with sparse id_list and id_score_list features', 'test the ReplayBuffer setup by inserting trajectories and sampling all valid transitions', 'create a PrioritizedReplayBuffer with stack size, capacity, and batch size parameters', 'test adding transitions to the replay buffer with and without priority arguments', 'test setting and retrieving priorities for batch indices in the replay buffer', 'test sampling transition batches from the prioritized replay buffer with priority weighting', 'test sampling index batches from the replay buffer and validate cursor boundaries', 'create a SumTree with a given capacity for priority-based experience replay sampling', 'test setting and getting values at specific node indices in a SumTree', 'test sampling from a SumTree using random or explicit query values', 'test stratified sampling to retrieve k evenly spaced samples from a SumTree', 'test tracking the maximum recorded priority value in a SumTree']
```

Usage

```
{'test_replay_buffer_stacking': 'test the ReplayBuffer with stacked observations across multiple random trajectory lengths', 'test_replay_buffer_multistep': 'test the ReplayBuffer with stacked observations and multi-step timeline format', 'test_replay_buffer_overflow': 'test the ReplayBuffer circular overflow behavior when transitions overwrite older entries', 'test_replay_buffer_sparse_features': 'test the ReplayBuffer with sparse id_list and id_score_list features', 'test_setup_replay_buffer': 'test the ReplayBuffer setup by inserting trajectories and sampling all valid transitions'}
```

## File: facebookresearch_reagent/reagent/test/replay_memory/prioritized_replay_buffer_test.py

Prompts

```
['create a ReplayBuffer with stack_size, replay_capacity, and batch_size parameters', 'add observation, action, reward, and terminal transitions to the replay buffer', 'sample a batch of transitions from the replay buffer with optional custom indices', 'test N-step reward accumulation using update_horizon and gamma parameters', 'check if a transition at a given index is valid for sampling', 'test the CreateFromEnvTest class to verify ReplayBuffer works with RecSim interest exploration environment', 'test the CreateFromEnvTest class to verify ReplayBuffer works with RecSim interest evolution environment', 'run the ReplayBuffer add method with RecSim interest exploration observation action reward and terminal data', 'run the ReplayBuffer add method with RecSim interest evolution observation doc response and log probability data', 'review the CreateFromEnvTest class and its two test methods for RecSim replay buffer integration', 'test the ReplayBuffer with stacked observations across multiple random trajectory lengths', 'test the ReplayBuffer with stacked observations and multi-step timeline format', 'test the ReplayBuffer circular overflow behavior when transitions overwrite older entries', 'test the ReplayBuffer with sparse id_list and id_score_list features', 'test the ReplayBuffer setup by inserting trajectories and sampling all valid transitions', 'create a PrioritizedReplayBuffer with stack size, capacity, and batch size parameters', 'test adding transitions to the replay buffer with and without priority arguments', 'test setting and retrieving priorities for batch indices in the replay buffer', 'test sampling transition batches from the prioritized replay buffer with priority weighting', 'test sampling index batches from the replay buffer and validate cursor boundaries', 'create a SumTree with a given capacity for priority-based experience replay sampling', 'test setting and getting values at specific node indices in a SumTree', 'test sampling from a SumTree using random or explicit query values', 'test stratified sampling to retrieve k evenly spaced samples from a SumTree', 'test tracking the maximum recorded priority value in a SumTree']
```

Usage

```
{'create_PrioritizedReplayBuffer': 'create a PrioritizedReplayBuffer with stack size, capacity, and batch size parameters', 'test_add_with_priority': 'test adding transitions to the replay buffer with and without priority arguments', 'test_set_and_get_priority': 'test setting and retrieving priorities for batch indices in the replay buffer', 'test_sample_transition_batch': 'test sampling transition batches from the prioritized replay buffer with priority weighting', 'test_sample_index_batch': 'test sampling index batches from the replay buffer and validate cursor boundaries'}
```

## File: facebookresearch_reagent/reagent/test/replay_memory/sum_tree_test.py

Prompts

```
['create a ReplayBuffer with stack_size, replay_capacity, and batch_size parameters', 'add observation, action, reward, and terminal transitions to the replay buffer', 'sample a batch of transitions from the replay buffer with optional custom indices', 'test N-step reward accumulation using update_horizon and gamma parameters', 'check if a transition at a given index is valid for sampling', 'test the CreateFromEnvTest class to verify ReplayBuffer works with RecSim interest exploration environment', 'test the CreateFromEnvTest class to verify ReplayBuffer works with RecSim interest evolution environment', 'run the ReplayBuffer add method with RecSim interest exploration observation action reward and terminal data', 'run the ReplayBuffer add method with RecSim interest evolution observation doc response and log probability data', 'review the CreateFromEnvTest class and its two test methods for RecSim replay buffer integration', 'test the ReplayBuffer with stacked observations across multiple random trajectory lengths', 'test the ReplayBuffer with stacked observations and multi-step timeline format', 'test the ReplayBuffer circular overflow behavior when transitions overwrite older entries', 'test the ReplayBuffer with sparse id_list and id_score_list features', 'test the ReplayBuffer setup by inserting trajectories and sampling all valid transitions', 'create a PrioritizedReplayBuffer with stack size, capacity, and batch size parameters', 'test adding transitions to the replay buffer with and without priority arguments', 'test setting and retrieving priorities for batch indices in the replay buffer', 'test sampling transition batches from the prioritized replay buffer with priority weighting', 'test sampling index batches from the replay buffer and validate cursor boundaries', 'create a SumTree with a given capacity for priority-based experience replay sampling', 'test setting and getting values at specific node indices in a SumTree', 'test sampling from a SumTree using random or explicit query values', 'test stratified sampling to retrieve k evenly spaced samples from a SumTree', 'test tracking the maximum recorded priority value in a SumTree']
```

Usage

```
{'create_sumtree': 'create a SumTree with a given capacity for priority-based experience replay sampling', 'test_sumtree_set_get': 'test setting and getting values at specific node indices in a SumTree', 'test_sumtree_sample': 'test sampling from a SumTree using random or explicit query values', 'test_sumtree_stratified_sample': 'test stratified sampling to retrieve k evenly spaced samples from a SumTree', 'test_sumtree_max_priority': 'test tracking the maximum recorded priority value in a SumTree'}
```

