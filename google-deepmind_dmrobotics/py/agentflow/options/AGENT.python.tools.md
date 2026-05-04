# Agent Python Tools

- repo: google-deepmind/dmrobotics
- repo_uri: https://github.com/google-deepmind/dm_robotics

## File: google-deepmind_dmrobotics/py/agentflow/options/basic_options.py

Prompts

```
['create a ConcurrentOption to run multiple options in parallel and merge their actions', 'create a FixedOp option that returns a fixed numpy action for a set number of steps', 'create a LambdaOption to wrap another option with custom on_selected, on_step, or pterm callables', 'create an ArgAdaptor to transform argument specs between a parent and delegate option', 'use options_terminate to build a custom termination condition for specific options in a ConcurrentOption', 'test the FixedOp option to return a fixed action and terminate after N steps', 'test the ConcurrentOption to merge actions from multiple child options and compute termination probability', 'test the LambdaOption to delegate calls to a wrapped option with custom callable hooks', 'test the any_terminates function to compute the probability that at least one option terminates', 'test the ArgAdaptor to transform parent option arguments into adapted arguments for a child option']
```

Usage

```
{'create_ConcurrentOption': 'create a ConcurrentOption to run multiple options in parallel and merge their actions', 'create_FixedOp': 'create a FixedOp option that returns a fixed numpy action for a set number of steps', 'create_LambdaOption': 'create a LambdaOption to wrap another option with custom on_selected, on_step, or pterm callables', 'create_ArgAdaptor': 'create an ArgAdaptor to transform argument specs between a parent and delegate option', 'use_options_terminate': 'use options_terminate to build a custom termination condition for specific options in a ConcurrentOption'}
```

## File: google-deepmind_dmrobotics/py/agentflow/options/basic_options_test.py

Prompts

```
['create a ConcurrentOption to run multiple options in parallel and merge their actions', 'create a FixedOp option that returns a fixed numpy action for a set number of steps', 'create a LambdaOption to wrap another option with custom on_selected, on_step, or pterm callables', 'create an ArgAdaptor to transform argument specs between a parent and delegate option', 'use options_terminate to build a custom termination condition for specific options in a ConcurrentOption', 'test the FixedOp option to return a fixed action and terminate after N steps', 'test the ConcurrentOption to merge actions from multiple child options and compute termination probability', 'test the LambdaOption to delegate calls to a wrapped option with custom callable hooks', 'test the any_terminates function to compute the probability that at least one option terminates', 'test the ArgAdaptor to transform parent option arguments into adapted arguments for a child option']
```

Usage

```
{'test_FixedOp': 'test the FixedOp option to return a fixed action and terminate after N steps', 'test_ConcurrentOption': 'test the ConcurrentOption to merge actions from multiple child options and compute termination probability', 'test_LambdaOption': 'test the LambdaOption to delegate calls to a wrapped option with custom callable hooks', 'test_AnyTerminates': 'test the any_terminates function to compute the probability that at least one option terminates', 'test_ArgAdaptor': 'test the ArgAdaptor to transform parent option arguments into adapted arguments for a child option'}
```

