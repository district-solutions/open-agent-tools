# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/compiler_gym/views/observation.py

Prompts

```
["request an observation from a named space using env.observation['Autophase'] on a reset CompilerGym environment", 'list all available observation space IDs via env.observation.spaces.keys() after resetting the environment', "get the gym Box spec for a space using env.observation.spaces['Autophase'].space", 'compute an observation by calling the dynamically bound method env.observation.Ir() on the view', 'register a new derived observation space from an existing base space using add_derived_space()', 'create an ObservationSpaceSpec from a protocol buffer using the from_proto class method', 'create a derived observation space with a custom translate callback using make_derived_space', 'check if two ObservationSpaceSpec instances are equal by comparing id, index, space, and flags', 'hash an ObservationSpaceSpec instance by its index for use in sets and dicts', 'inspect the string representation of an ObservationSpaceSpec showing its id', 'get the reward value for a named reward space using env.reward[space_name]', 'reset the RewardView and all registered reward spaces for a new benchmark episode', 'add a new Reward space to the RewardView so it can be queried by name', 'inspect the available reward spaces and their range via env.reward.spaces', 'call a dynamically bound reward method by name such as env.reward.codesize()']
```

Usage

```
{'get_observation_by_space': "request an observation from a named space using env.observation['Autophase'] on a reset CompilerGym environment", 'list_observation_spaces': 'list all available observation space IDs via env.observation.spaces.keys() after resetting the environment', 'get_observation_space_spec': "get the gym Box spec for a space using env.observation.spaces['Autophase'].space", 'call_observation_method': 'compute an observation by calling the dynamically bound method env.observation.Ir() on the view', 'add_derived_observation_space': 'register a new derived observation space from an existing base space using add_derived_space()'}
```

## File: facebookresearch_compilergym/compiler_gym/views/observation_space_spec.py

Prompts

```
["request an observation from a named space using env.observation['Autophase'] on a reset CompilerGym environment", 'list all available observation space IDs via env.observation.spaces.keys() after resetting the environment', "get the gym Box spec for a space using env.observation.spaces['Autophase'].space", 'compute an observation by calling the dynamically bound method env.observation.Ir() on the view', 'register a new derived observation space from an existing base space using add_derived_space()', 'create an ObservationSpaceSpec from a protocol buffer using the from_proto class method', 'create a derived observation space with a custom translate callback using make_derived_space', 'check if two ObservationSpaceSpec instances are equal by comparing id, index, space, and flags', 'hash an ObservationSpaceSpec instance by its index for use in sets and dicts', 'inspect the string representation of an ObservationSpaceSpec showing its id', 'get the reward value for a named reward space using env.reward[space_name]', 'reset the RewardView and all registered reward spaces for a new benchmark episode', 'add a new Reward space to the RewardView so it can be queried by name', 'inspect the available reward spaces and their range via env.reward.spaces', 'call a dynamically bound reward method by name such as env.reward.codesize()']
```

Usage

```
{'create_observation_space_from_proto': 'create an ObservationSpaceSpec from a protocol buffer using the from_proto class method', 'create_derived_observation_space': 'create a derived observation space with a custom translate callback using make_derived_space', 'check_observation_space_equality': 'check if two ObservationSpaceSpec instances are equal by comparing id, index, space, and flags', 'hash_observation_space': 'hash an ObservationSpaceSpec instance by its index for use in sets and dicts', 'inspect_observation_space_repr': 'inspect the string representation of an ObservationSpaceSpec showing its id'}
```

## File: facebookresearch_compilergym/compiler_gym/views/reward.py

Prompts

```
["request an observation from a named space using env.observation['Autophase'] on a reset CompilerGym environment", 'list all available observation space IDs via env.observation.spaces.keys() after resetting the environment', "get the gym Box spec for a space using env.observation.spaces['Autophase'].space", 'compute an observation by calling the dynamically bound method env.observation.Ir() on the view', 'register a new derived observation space from an existing base space using add_derived_space()', 'create an ObservationSpaceSpec from a protocol buffer using the from_proto class method', 'create a derived observation space with a custom translate callback using make_derived_space', 'check if two ObservationSpaceSpec instances are equal by comparing id, index, space, and flags', 'hash an ObservationSpaceSpec instance by its index for use in sets and dicts', 'inspect the string representation of an ObservationSpaceSpec showing its id', 'get the reward value for a named reward space using env.reward[space_name]', 'reset the RewardView and all registered reward spaces for a new benchmark episode', 'add a new Reward space to the RewardView so it can be queried by name', 'inspect the available reward spaces and their range via env.reward.spaces', 'call a dynamically bound reward method by name such as env.reward.codesize()']
```

Usage

```
{'get_reward_for_space': 'get the reward value for a named reward space using env.reward[space_name]', 'reset_reward_view': 'reset the RewardView and all registered reward spaces for a new benchmark episode', 'add_reward_space': 'add a new Reward space to the RewardView so it can be queried by name', 'inspect_reward_spaces': 'inspect the available reward spaces and their range via env.reward.spaces', 'call_reward_by_name': 'call a dynamically bound reward method by name such as env.reward.codesize()'}
```

