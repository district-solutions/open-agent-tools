# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/tf/dqfd/agent_test.py

Prompts

```
['test the DQfD agent by running an environment loop with demonstrations and a fake discrete environment', 'create a DQfD agent with an environment spec, neural network, demonstration dataset, and replay settings', 'build a demonstration recorder to capture timestep and action pairs for imitation learning episodes', 'create a Sonnet MLP network with flatten and dense layers matching the action spec size', 'run an Acme environment loop with a DQfD agent for a specified number of episodes', 'create a DemonstrationRecorder instance to record RL episode demonstrations as observation action reward tuples', 'run recorder step with a timestep and action to log the current RL transition', 'build a shuffled repeating TensorFlow dataset from recorded demonstrations using make_tf_dataset', 'make a DeepSea demonstration dataset by running an optimal policy episode and recording the trajectory', 'make a stochastic DeepSea dataset with 80 percent success and 20 percent failure episodes']
```

Usage

```
{'test_dqfd_agent': 'test the DQfD agent by running an environment loop with demonstrations and a fake discrete environment', 'create_dqfd_agent': 'create a DQfD agent with an environment spec, neural network, demonstration dataset, and replay settings', 'build_demonstration_recorder': 'build a demonstration recorder to capture timestep and action pairs for imitation learning episodes', 'make_mlpp_network': 'create a Sonnet MLP network with flatten and dense layers matching the action spec size', 'run_environment_loop': 'run an Acme environment loop with a DQfD agent for a specified number of episodes'}
```

## File: google-deepmind_acme/acme/agents/tf/dqfd/bsuite_demonstrations.py

Prompts

```
['test the DQfD agent by running an environment loop with demonstrations and a fake discrete environment', 'create a DQfD agent with an environment spec, neural network, demonstration dataset, and replay settings', 'build a demonstration recorder to capture timestep and action pairs for imitation learning episodes', 'create a Sonnet MLP network with flatten and dense layers matching the action spec size', 'run an Acme environment loop with a DQfD agent for a specified number of episodes', 'create a DemonstrationRecorder instance to record RL episode demonstrations as observation action reward tuples', 'run recorder step with a timestep and action to log the current RL transition', 'build a shuffled repeating TensorFlow dataset from recorded demonstrations using make_tf_dataset', 'make a DeepSea demonstration dataset by running an optimal policy episode and recording the trajectory', 'make a stochastic DeepSea dataset with 80 percent success and 20 percent failure episodes']
```

Usage

```
{'create_demonstration_recorder': 'create a DemonstrationRecorder instance to record RL episode demonstrations as observation action reward tuples', 'run_recorder_step': 'run recorder step with a timestep and action to log the current RL transition', 'build_tf_dataset_from_demos': 'build a shuffled repeating TensorFlow dataset from recorded demonstrations using make_tf_dataset', 'make_deep_sea_dataset': 'make a DeepSea demonstration dataset by running an optimal policy episode and recording the trajectory', 'make_stochastic_deep_sea_dataset': 'make a stochastic DeepSea dataset with 80 percent success and 20 percent failure episodes'}
```

