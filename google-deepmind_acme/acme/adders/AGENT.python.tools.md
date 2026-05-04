# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/adders/base.py

Prompts

```
['implement a concrete Adder subclass that buffers transitions and sends them to a replay buffer', 'implement the add_first method to initialize a trajectory with the first observation timestep', 'implement the add method to record an action and resulting timestep into the replay buffer', 'implement the reset method to clear the adder buffer between episodes', 'review the Adder abstract base class and its three abstract methods for replay buffer integration', 'create a ForkingAdder that forks data into several other adders', 'create an IgnoreExtrasAdder that wraps an adder and ignores extras', 'test the ForkingAdder reset method to verify it resets all wrapped adders', 'test the IgnoreExtrasAdder to verify it discards extras when calling add', 'refactor the ForkingAdder to support conditional forwarding to a subset of adders']
```

Usage

```
{'implement_Adder': 'implement a concrete Adder subclass that buffers transitions and sends them to a replay buffer', 'implement_add_first': 'implement the add_first method to initialize a trajectory with the first observation timestep', 'implement_add': 'implement the add method to record an action and resulting timestep into the replay buffer', 'implement_reset': 'implement the reset method to clear the adder buffer between episodes', 'review_Adder_interface': 'review the Adder abstract base class and its three abstract methods for replay buffer integration'}
```

## File: google-deepmind_acme/acme/adders/wrappers.py

Prompts

```
['implement a concrete Adder subclass that buffers transitions and sends them to a replay buffer', 'implement the add_first method to initialize a trajectory with the first observation timestep', 'implement the add method to record an action and resulting timestep into the replay buffer', 'implement the reset method to clear the adder buffer between episodes', 'review the Adder abstract base class and its three abstract methods for replay buffer integration', 'create a ForkingAdder that forks data into several other adders', 'create an IgnoreExtrasAdder that wraps an adder and ignores extras', 'test the ForkingAdder reset method to verify it resets all wrapped adders', 'test the IgnoreExtrasAdder to verify it discards extras when calling add', 'refactor the ForkingAdder to support conditional forwarding to a subset of adders']
```

Usage

```
{'create_forking_adder': 'create a ForkingAdder that forks data into several other adders', 'create_ignore_extras_adder': 'create an IgnoreExtrasAdder that wraps an adder and ignores extras', 'test_forking_adder_reset': 'test the ForkingAdder reset method to verify it resets all wrapped adders', 'test_ignore_extras_adder': 'test the IgnoreExtrasAdder to verify it discards extras when calling add', 'refactor_forking_adder': 'refactor the ForkingAdder to support conditional forwarding to a subset of adders'}
```

