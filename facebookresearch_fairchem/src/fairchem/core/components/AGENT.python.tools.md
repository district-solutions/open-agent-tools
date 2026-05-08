# Agent Python Tools

- repo: facebookresearch/fairchem
- repo_uri: https://github.com/facebookresearch/fairchem

## File: facebookresearch_fairchem/src/fairchem/core/components/reducer.py

Prompts

```
['implement a new Reducer subclass that overrides reduce, save_state, and load_state methods', 'use MockReducer to test runner reduction logic without actual file I/O operations', 'override the reduce method in a Reducer subclass to process results from a specific Runner type', 'implement save_state in a Reducer subclass to persist reduction state to a checkpoint location', 'implement load_state in a Reducer subclass to restore reduction state from a checkpoint location', 'create a subclass of Runner that implements run, save_state, and load_state abstract methods', 'use MockRunner to test run, save_state, and load_state with configurable x, y, z values', 'implement PreemptableMixin with save_simulation_state and load_simulation_state for STOPFAIR preemption support', 'handle STOPFAIR sentinel detection by calling check_stopfair and handle_stopfair on a PreemptableMixin subclass', 'save an atomic checkpoint with resume_config and portable_config using PreemptableMixin save_state method']
```

Usage

```
{'implement_reducer_subclass': 'implement a new Reducer subclass that overrides reduce, save_state, and load_state methods', 'use_mockreducer_for_testing': 'use MockReducer to test runner reduction logic without actual file I/O operations', 'override_reduce_method': 'override the reduce method in a Reducer subclass to process results from a specific Runner type', 'implement_checkpoint_save': 'implement save_state in a Reducer subclass to persist reduction state to a checkpoint location', 'implement_checkpoint_load': 'implement load_state in a Reducer subclass to restore reduction state from a checkpoint location'}
```

## File: facebookresearch_fairchem/src/fairchem/core/components/runner.py

Prompts

```
['implement a new Reducer subclass that overrides reduce, save_state, and load_state methods', 'use MockReducer to test runner reduction logic without actual file I/O operations', 'override the reduce method in a Reducer subclass to process results from a specific Runner type', 'implement save_state in a Reducer subclass to persist reduction state to a checkpoint location', 'implement load_state in a Reducer subclass to restore reduction state from a checkpoint location', 'create a subclass of Runner that implements run, save_state, and load_state abstract methods', 'use MockRunner to test run, save_state, and load_state with configurable x, y, z values', 'implement PreemptableMixin with save_simulation_state and load_simulation_state for STOPFAIR preemption support', 'handle STOPFAIR sentinel detection by calling check_stopfair and handle_stopfair on a PreemptableMixin subclass', 'save an atomic checkpoint with resume_config and portable_config using PreemptableMixin save_state method']
```

Usage

```
{'create_runner_subclass': 'create a subclass of Runner that implements run, save_state, and load_state abstract methods', 'use_mockrunner_for_testing': 'use MockRunner to test run, save_state, and load_state with configurable x, y, z values', 'implement_preemptablemixin': 'implement PreemptableMixin with save_simulation_state and load_simulation_state for STOPFAIR preemption support', 'handle_stopfair_preemption': 'handle STOPFAIR sentinel detection by calling check_stopfair and handle_stopfair on a PreemptableMixin subclass', 'save_atomic_checkpoint': 'save an atomic checkpoint with resume_config and portable_config using PreemptableMixin save_state method'}
```

