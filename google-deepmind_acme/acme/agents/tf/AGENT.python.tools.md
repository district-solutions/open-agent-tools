# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/tf/actors.py

Prompts

```
['build a feed-forward actor with a Sonnet policy network and optional replay adder', 'build a recurrent actor with an RNN policy network and internal state tracking', 'select an action from a feed-forward actor given an observation tensor', 'select an action from a recurrent actor that maintains internal RNN state', 'update actor weights by syncing variables from the learner via the variable client', 'test the FeedForwardActor with a Sonnet sequential network in an EnvironmentLoop', 'test the RecurrentActor with a Sonnet DeepRNN network in an EnvironmentLoop', 'create a fake dm_env Environment using specs and fakes for testing actors', 'run a FeedForwardActor through an EnvironmentLoop for a specified number of steps', 'run a RecurrentActor through an EnvironmentLoop for a specified number of steps']
```

Usage

```
{'build_feedforward_actor': 'build a feed-forward actor with a Sonnet policy network and optional replay adder', 'build_recurrent_actor': 'build a recurrent actor with an RNN policy network and internal state tracking', 'select_action_feedforward': 'select an action from a feed-forward actor given an observation tensor', 'select_action_recurrent': 'select an action from a recurrent actor that maintains internal RNN state', 'update_actor_weights': 'update actor weights by syncing variables from the learner via the variable client'}
```

## File: google-deepmind_acme/acme/agents/tf/actors_test.py

Prompts

```
['build a feed-forward actor with a Sonnet policy network and optional replay adder', 'build a recurrent actor with an RNN policy network and internal state tracking', 'select an action from a feed-forward actor given an observation tensor', 'select an action from a recurrent actor that maintains internal RNN state', 'update actor weights by syncing variables from the learner via the variable client', 'test the FeedForwardActor with a Sonnet sequential network in an EnvironmentLoop', 'test the RecurrentActor with a Sonnet DeepRNN network in an EnvironmentLoop', 'create a fake dm_env Environment using specs and fakes for testing actors', 'run a FeedForwardActor through an EnvironmentLoop for a specified number of steps', 'run a RecurrentActor through an EnvironmentLoop for a specified number of steps']
```

Usage

```
{'test_feedforward_actor': 'test the FeedForwardActor with a Sonnet sequential network in an EnvironmentLoop', 'test_recurrent_actor': 'test the RecurrentActor with a Sonnet DeepRNN network in an EnvironmentLoop', 'create_fake_environment': 'create a fake dm_env Environment using specs and fakes for testing actors', 'run_feedforward_actor_loop': 'run a FeedForwardActor through an EnvironmentLoop for a specified number of steps', 'run_recurrent_actor_loop': 'run a RecurrentActor through an EnvironmentLoop for a specified number of steps'}
```

