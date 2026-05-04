# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/agent.py

Prompts

```
['build an Agent combining an Actor and Learner with configurable observations per step ratio', 'create an Agent that selects actions by delegating to its underlying Actor policy', 'run the Agent update loop to perform learner gradient steps and sync actor weights', 'refactor the _calculate_num_learner_steps function to adjust learner step frequency based on observations', 'review the Agent observe_first and observe methods for tracking observations and delegating to the Actor', 'create a prioritized n-step replay buffer with configurable priority exponent and discount factor', 'create a single process online queue replay buffer for sequence data with batch sampling', 'create a prioritized sequence replay buffer with burn-in length and delta encoding support', 'review the ReverbReplay dataclass that holds server, adder, data iterator, client, and can_sample fields', 'build a single-process replay infrastructure from an environment spec using reverb tables and adders']
```

Usage

```
{'build_agent_with_actor_learner': 'build an Agent combining an Actor and Learner with configurable observations per step ratio', 'create_agent_select_action': 'create an Agent that selects actions by delegating to its underlying Actor policy', 'run_agent_update_loop': 'run the Agent update loop to perform learner gradient steps and sync actor weights', 'refactor_calculate_learner_steps': 'refactor the _calculate_num_learner_steps function to adjust learner step frequency based on observations', 'review_agent_observe_methods': 'review the Agent observe_first and observe methods for tracking observations and delegating to the Actor'}
```

## File: google-deepmind_acme/acme/agents/replay.py

Prompts

```
['build an Agent combining an Actor and Learner with configurable observations per step ratio', 'create an Agent that selects actions by delegating to its underlying Actor policy', 'run the Agent update loop to perform learner gradient steps and sync actor weights', 'refactor the _calculate_num_learner_steps function to adjust learner step frequency based on observations', 'review the Agent observe_first and observe methods for tracking observations and delegating to the Actor', 'create a prioritized n-step replay buffer with configurable priority exponent and discount factor', 'create a single process online queue replay buffer for sequence data with batch sampling', 'create a prioritized sequence replay buffer with burn-in length and delta encoding support', 'review the ReverbReplay dataclass that holds server, adder, data iterator, client, and can_sample fields', 'build a single-process replay infrastructure from an environment spec using reverb tables and adders']
```

Usage

```
{'create_prioritized_nstep_replay': 'create a prioritized n-step replay buffer with configurable priority exponent and discount factor', 'create_online_queue_replay': 'create a single process online queue replay buffer for sequence data with batch sampling', 'create_prioritized_sequence_replay': 'create a prioritized sequence replay buffer with burn-in length and delta encoding support', 'review_ReverbReplay_dataclass': 'review the ReverbReplay dataclass that holds server, adder, data iterator, client, and can_sample fields', 'build_replay_infrastructure': 'build a single-process replay infrastructure from an environment spec using reverb tables and adders'}
```

