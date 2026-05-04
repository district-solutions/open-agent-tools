# Agent Python Tools

- repo: google-deepmind/acme
- repo_uri: https://github.com/google-deepmind/acme

## File: google-deepmind_acme/acme/agents/jax/lfd/builder.py

Prompts

```
['build an LfdBuilder instance wrapping an off-policy algorithm builder with demonstrations and config', 'create a callable factory returning an infinite iterator of action and timestep demonstration pairs', 'make an LfdAdder that mixes demonstrations with online experience using a configurable demonstration ratio', 'make replay tables by delegating to the underlying off-policy algorithm builder', 'make an actor by delegating to the underlying off-policy algorithm builder', 'build an LfdAdder that mixes offline demonstrations with collected episodes at a target ratio', 'create an iterator yielding action timestep pairs for use with LfdAdder demonstrations', 'test the LfdAdder add_first method to verify demonstration prefilling before agent episodes', 'review the LfdAdder demonstration ratio logic to understand delta step count balancing', 'refactor the LfdAdder reset method to handle reverb connection resets internally', 'test the LfdAdder maintains the correct demonstration to collected data ratio', 'run the absltest unit tests for the LfD adder implementation', 'create a TestStatisticsAdder subclass that tracks observation counts by episode type', 'generate demonstration episodes as a generator yielding action timestep pairs', 'review the LfdAdderTest class and its test_adder method for correctness']
```

Usage

```
{'build_lfd_builder': 'build an LfdBuilder instance wrapping an off-policy algorithm builder with demonstrations and config', 'create_demonstrations_factory': 'create a callable factory returning an infinite iterator of action and timestep demonstration pairs', 'make_adder_lfd': 'make an LfdAdder that mixes demonstrations with online experience using a configurable demonstration ratio', 'make_replay_tables': 'make replay tables by delegating to the underlying off-policy algorithm builder', 'make_actor': 'make an actor by delegating to the underlying off-policy algorithm builder'}
```

## File: google-deepmind_acme/acme/agents/jax/lfd/lfd_adder.py

Prompts

```
['build an LfdBuilder instance wrapping an off-policy algorithm builder with demonstrations and config', 'create a callable factory returning an infinite iterator of action and timestep demonstration pairs', 'make an LfdAdder that mixes demonstrations with online experience using a configurable demonstration ratio', 'make replay tables by delegating to the underlying off-policy algorithm builder', 'make an actor by delegating to the underlying off-policy algorithm builder', 'build an LfdAdder that mixes offline demonstrations with collected episodes at a target ratio', 'create an iterator yielding action timestep pairs for use with LfdAdder demonstrations', 'test the LfdAdder add_first method to verify demonstration prefilling before agent episodes', 'review the LfdAdder demonstration ratio logic to understand delta step count balancing', 'refactor the LfdAdder reset method to handle reverb connection resets internally', 'test the LfdAdder maintains the correct demonstration to collected data ratio', 'run the absltest unit tests for the LfD adder implementation', 'create a TestStatisticsAdder subclass that tracks observation counts by episode type', 'generate demonstration episodes as a generator yielding action timestep pairs', 'review the LfdAdderTest class and its test_adder method for correctness']
```

Usage

```
{'build_lfd_adder': 'build an LfdAdder that mixes offline demonstrations with collected episodes at a target ratio', 'create_demonstration_iterator': 'create an iterator yielding action timestep pairs for use with LfdAdder demonstrations', 'test_lfd_adder_add_first': 'test the LfdAdder add_first method to verify demonstration prefilling before agent episodes', 'review_lfd_adder_ratio': 'review the LfdAdder demonstration ratio logic to understand delta step count balancing', 'refactor_lfd_adder_reset': 'refactor the LfdAdder reset method to handle reverb connection resets internally'}
```

## File: google-deepmind_acme/acme/agents/jax/lfd/lfd_adder_test.py

Prompts

```
['build an LfdBuilder instance wrapping an off-policy algorithm builder with demonstrations and config', 'create a callable factory returning an infinite iterator of action and timestep demonstration pairs', 'make an LfdAdder that mixes demonstrations with online experience using a configurable demonstration ratio', 'make replay tables by delegating to the underlying off-policy algorithm builder', 'make an actor by delegating to the underlying off-policy algorithm builder', 'build an LfdAdder that mixes offline demonstrations with collected episodes at a target ratio', 'create an iterator yielding action timestep pairs for use with LfdAdder demonstrations', 'test the LfdAdder add_first method to verify demonstration prefilling before agent episodes', 'review the LfdAdder demonstration ratio logic to understand delta step count balancing', 'refactor the LfdAdder reset method to handle reverb connection resets internally', 'test the LfdAdder maintains the correct demonstration to collected data ratio', 'run the absltest unit tests for the LfD adder implementation', 'create a TestStatisticsAdder subclass that tracks observation counts by episode type', 'generate demonstration episodes as a generator yielding action timestep pairs', 'review the LfdAdderTest class and its test_adder method for correctness']
```

Usage

```
{'test_lfd_adder_demonstration_ratio': 'test the LfdAdder maintains the correct demonstration to collected data ratio', 'run_lfd_adder_unit_tests': 'run the absltest unit tests for the LfD adder implementation', 'create_test_statistics_adder': 'create a TestStatisticsAdder subclass that tracks observation counts by episode type', 'generate_demonstration_episodes': 'generate demonstration episodes as a generator yielding action timestep pairs', 'review_lfd_adder_test': 'review the LfdAdderTest class and its test_adder method for correctness'}
```

