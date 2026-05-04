# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/jax/multiagent/decentralized/actor.py

Prompts

```
['build a SimultaneousActingMultiAgentActor that coordinates multiple sub-actors for simultaneous-move multiagent environments', 'create a select_action call that returns actions for all agents from their observations', 'test the observe_first method to initialize all sub-actors with their agent-specific timesteps', 'refactor the observe method to log actions and next timesteps for each sub-actor', 'review the update method that triggers parameter updates across all sub-actors with optional wait', 'build a decentralized multiagent builder with agent types and configs for JAX-based reinforcement learning', 'create a prefixed variable source wrapper that adds agent ID prefixes to variable names', 'create replay tables for all agents using the multiagent environment spec and policy networks', 'build a synchronous decentralized learner set with per-agent sub-learners and prefixed counters', 'create a simultaneous-acting multiagent actor with prefixed variable sources for each sub-actor', 'build networks for all agents in a decentralized multiagent setup using network_factory', 'build policy networks for all agents using policy_network_factory with eval mode', 'build default configs for all agents using default_config_factory with batch size', 'build actor learner builders for all agents using builder_factory', 'review the DefaultSupportedAgent enum to see which RL agents are supported', 'build a SynchronousDecentralizedLearnerSet wrapping multiple agent learners with a custom separator', 'create a learning step that advances all wrapped learners in the decentralized learner set', 'get named variables from sub-learners using prefixed names like learner-var with the separator', 'save the state of all learners in the SynchronousDecentralizedLearnerSet into a SynchronousDecentralizedLearnerSetState', 'restore all learner states from a SynchronousDecentralizedLearnerSetState object back into the learner set']
```

Usage

```
{'build_multiagent_actor': 'build a SimultaneousActingMultiAgentActor that coordinates multiple sub-actors for simultaneous-move multiagent environments', 'create_select_action': 'create a select_action call that returns actions for all agents from their observations', 'test_observe_first': 'test the observe_first method to initialize all sub-actors with their agent-specific timesteps', 'refactor_observe': 'refactor the observe method to log actions and next timesteps for each sub-actor', 'review_update': 'review the update method that triggers parameter updates across all sub-actors with optional wait'}
```

## File: google-deepmind_acme/acme/agents/jax/multiagent/decentralized/builder.py

Prompts

```
['build a SimultaneousActingMultiAgentActor that coordinates multiple sub-actors for simultaneous-move multiagent environments', 'create a select_action call that returns actions for all agents from their observations', 'test the observe_first method to initialize all sub-actors with their agent-specific timesteps', 'refactor the observe method to log actions and next timesteps for each sub-actor', 'review the update method that triggers parameter updates across all sub-actors with optional wait', 'build a decentralized multiagent builder with agent types and configs for JAX-based reinforcement learning', 'create a prefixed variable source wrapper that adds agent ID prefixes to variable names', 'create replay tables for all agents using the multiagent environment spec and policy networks', 'build a synchronous decentralized learner set with per-agent sub-learners and prefixed counters', 'create a simultaneous-acting multiagent actor with prefixed variable sources for each sub-actor', 'build networks for all agents in a decentralized multiagent setup using network_factory', 'build policy networks for all agents using policy_network_factory with eval mode', 'build default configs for all agents using default_config_factory with batch size', 'build actor learner builders for all agents using builder_factory', 'review the DefaultSupportedAgent enum to see which RL agents are supported', 'build a SynchronousDecentralizedLearnerSet wrapping multiple agent learners with a custom separator', 'create a learning step that advances all wrapped learners in the decentralized learner set', 'get named variables from sub-learners using prefixed names like learner-var with the separator', 'save the state of all learners in the SynchronousDecentralizedLearnerSet into a SynchronousDecentralizedLearnerSetState', 'restore all learner states from a SynchronousDecentralizedLearnerSetState object back into the learner set']
```

Usage

```
{'build_decentralized_multiagent_builder': 'build a decentralized multiagent builder with agent types and configs for JAX-based reinforcement learning', 'create_prefixed_variable_source': 'create a prefixed variable source wrapper that adds agent ID prefixes to variable names', 'make_replay_tables': 'create replay tables for all agents using the multiagent environment spec and policy networks', 'make_learner': 'build a synchronous decentralized learner set with per-agent sub-learners and prefixed counters', 'make_actor': 'create a simultaneous-acting multiagent actor with prefixed variable sources for each sub-actor'}
```

## File: google-deepmind_acme/acme/agents/jax/multiagent/decentralized/factories.py

Prompts

```
['build a SimultaneousActingMultiAgentActor that coordinates multiple sub-actors for simultaneous-move multiagent environments', 'create a select_action call that returns actions for all agents from their observations', 'test the observe_first method to initialize all sub-actors with their agent-specific timesteps', 'refactor the observe method to log actions and next timesteps for each sub-actor', 'review the update method that triggers parameter updates across all sub-actors with optional wait', 'build a decentralized multiagent builder with agent types and configs for JAX-based reinforcement learning', 'create a prefixed variable source wrapper that adds agent ID prefixes to variable names', 'create replay tables for all agents using the multiagent environment spec and policy networks', 'build a synchronous decentralized learner set with per-agent sub-learners and prefixed counters', 'create a simultaneous-acting multiagent actor with prefixed variable sources for each sub-actor', 'build networks for all agents in a decentralized multiagent setup using network_factory', 'build policy networks for all agents using policy_network_factory with eval mode', 'build default configs for all agents using default_config_factory with batch size', 'build actor learner builders for all agents using builder_factory', 'review the DefaultSupportedAgent enum to see which RL agents are supported', 'build a SynchronousDecentralizedLearnerSet wrapping multiple agent learners with a custom separator', 'create a learning step that advances all wrapped learners in the decentralized learner set', 'get named variables from sub-learners using prefixed names like learner-var with the separator', 'save the state of all learners in the SynchronousDecentralizedLearnerSet into a SynchronousDecentralizedLearnerSetState', 'restore all learner states from a SynchronousDecentralizedLearnerSetState object back into the learner set']
```

Usage

```
{'build_multiagent_networks': 'build networks for all agents in a decentralized multiagent setup using network_factory', 'build_multiagent_policy_networks': 'build policy networks for all agents using policy_network_factory with eval mode', 'build_multiagent_configs': 'build default configs for all agents using default_config_factory with batch size', 'build_multiagent_builders': 'build actor learner builders for all agents using builder_factory', 'review_default_supported_agent_enum': 'review the DefaultSupportedAgent enum to see which RL agents are supported'}
```

## File: google-deepmind_acme/acme/agents/jax/multiagent/decentralized/learner_set.py

Prompts

```
['build a SimultaneousActingMultiAgentActor that coordinates multiple sub-actors for simultaneous-move multiagent environments', 'create a select_action call that returns actions for all agents from their observations', 'test the observe_first method to initialize all sub-actors with their agent-specific timesteps', 'refactor the observe method to log actions and next timesteps for each sub-actor', 'review the update method that triggers parameter updates across all sub-actors with optional wait', 'build a decentralized multiagent builder with agent types and configs for JAX-based reinforcement learning', 'create a prefixed variable source wrapper that adds agent ID prefixes to variable names', 'create replay tables for all agents using the multiagent environment spec and policy networks', 'build a synchronous decentralized learner set with per-agent sub-learners and prefixed counters', 'create a simultaneous-acting multiagent actor with prefixed variable sources for each sub-actor', 'build networks for all agents in a decentralized multiagent setup using network_factory', 'build policy networks for all agents using policy_network_factory with eval mode', 'build default configs for all agents using default_config_factory with batch size', 'build actor learner builders for all agents using builder_factory', 'review the DefaultSupportedAgent enum to see which RL agents are supported', 'build a SynchronousDecentralizedLearnerSet wrapping multiple agent learners with a custom separator', 'create a learning step that advances all wrapped learners in the decentralized learner set', 'get named variables from sub-learners using prefixed names like learner-var with the separator', 'save the state of all learners in the SynchronousDecentralizedLearnerSet into a SynchronousDecentralizedLearnerSetState', 'restore all learner states from a SynchronousDecentralizedLearnerSetState object back into the learner set']
```

Usage

```
{'build_multiagent_learner_set': 'build a SynchronousDecentralizedLearnerSet wrapping multiple agent learners with a custom separator', 'create_learner_step': 'create a learning step that advances all wrapped learners in the decentralized learner set', 'get_variables_from_learners': 'get named variables from sub-learners using prefixed names like learner-var with the separator', 'save_learner_set_state': 'save the state of all learners in the SynchronousDecentralizedLearnerSet into a SynchronousDecentralizedLearnerSetState', 'restore_learner_set_state': 'restore all learner states from a SynchronousDecentralizedLearnerSetState object back into the learner set'}
```

