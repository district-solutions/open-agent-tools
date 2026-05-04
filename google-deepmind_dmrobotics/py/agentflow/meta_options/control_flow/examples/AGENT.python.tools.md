# Agent Python Tools

- repo: google-deepmind/dmrobotics
- repo_uri: https://github.com/google-deepmind/dm_robotics

## File: google-deepmind_dmrobotics/py/agentflow/meta_options/control_flow/examples/common.py

Prompts

```
['create a DummyEnv instance that returns random observations and accepts 4-dimensional bounded actions', 'create a DummySubTask that maps 2D agent actions to 4D parent actions via hstack', 'create a DummyPolicy that returns random actions matching the given action spec shape', 'create a DummyOption that returns random actions padded with zeros to match parent action dimensions', 'test the DummyEnv step method by passing a random action and verifying the returned TimeStep', 'build a control-flow graph that composes reach, insert, extract, and recovery options for a robot insertion experiment', 'create a Cond option that conditionally runs a learned insertion policy or a reach option based on proximity', 'create a Repeat loop that retries a reach-or-insert option a fixed number of times', 'create a While loop that continuously executes a sequence of reset, insert, and post-insert options', 'create a Sequence that chains scripted reset, retry loop, and conditional post-insert options together']
```

Usage

```
{'create_DummyEnv': 'create a DummyEnv instance that returns random observations and accepts 4-dimensional bounded actions', 'create_DummySubTask': 'create a DummySubTask that maps 2D agent actions to 4D parent actions via hstack', 'create_DummyPolicy': 'create a DummyPolicy that returns random actions matching the given action spec shape', 'create_DummyOption': 'create a DummyOption that returns random actions padded with zeros to match parent action dimensions', 'test_DummyEnv_step': 'test the DummyEnv step method by passing a random action and verifying the returned TimeStep'}
```

## File: google-deepmind_dmrobotics/py/agentflow/meta_options/control_flow/examples/simple_insertion.py

Prompts

```
['create a DummyEnv instance that returns random observations and accepts 4-dimensional bounded actions', 'create a DummySubTask that maps 2D agent actions to 4D parent actions via hstack', 'create a DummyPolicy that returns random actions matching the given action spec shape', 'create a DummyOption that returns random actions padded with zeros to match parent action dimensions', 'test the DummyEnv step method by passing a random action and verifying the returned TimeStep', 'build a control-flow graph that composes reach, insert, extract, and recovery options for a robot insertion experiment', 'create a Cond option that conditionally runs a learned insertion policy or a reach option based on proximity', 'create a Repeat loop that retries a reach-or-insert option a fixed number of times', 'create a While loop that continuously executes a sequence of reset, insert, and post-insert options', 'create a Sequence that chains scripted reset, retry loop, and conditional post-insert options together']
```

Usage

```
{'build_insertion_experiment_graph': 'build a control-flow graph that composes reach, insert, extract, and recovery options for a robot insertion experiment', 'create_cond_option': 'create a Cond option that conditionally runs a learned insertion policy or a reach option based on proximity', 'create_repeat_loop': 'create a Repeat loop that retries a reach-or-insert option a fixed number of times', 'create_while_loop': 'create a While loop that continuously executes a sequence of reset, insert, and post-insert options', 'create_sequence_composition': 'create a Sequence that chains scripted reset, retry loop, and conditional post-insert options together'}
```

