# Agent Python Tools

- repo: google-deepmind/enn
- repo_uri: https://github.com/google-deepmind/enn

## File: google-deepmind_enn/enn/active_learning/base.py

Prompts

```
['implement a subclass of ActiveLearner that overrides sample_batch and acquisition_size for custom data selection', 'implement a PriorityFn protocol that assigns priority scores to a batch given params, state, and a PRNG key', 'implement a PriorityFnCtor protocol that constructs a PriorityFn from an enn_batch_fwd forwarder', 'implement a PerExamplePriority protocol that calculates per-example priority scores from logits and labels', 'review the ActiveLearner abstract base class and its sample_batch method and acquisition_size property interface', 'build a priority function constructor from a per example priority using make_priority_fn_ctor', 'create uniformly random per example priority scores using uniform_per_example', 'calculate variance per example from ENN logits using variance_per_example', 'compute negative log-likelihood per example from logits and labels using nll_per_example', 'get a named priority function constructor by name using get_priority_fn_ctor', 'create a PrioritizedBatcher with an ENN batch forwarder and default uniform priority function', 'sample a prioritized batch from a data pool using the PrioritizedBatcher sample_batch method', 'set the acquisition size on a PrioritizedBatcher instance to control how many samples to acquire', 'use get_at_index to extract values at specified indices from a JAX pytree structure', 'review the PrioritizedBatcher sample_batch method to understand how candidate scores select top-N data']
```

Usage

```
{'implement_ActiveLearner': 'implement a subclass of ActiveLearner that overrides sample_batch and acquisition_size for custom data selection', 'implement_PriorityFn': 'implement a PriorityFn protocol that assigns priority scores to a batch given params, state, and a PRNG key', 'implement_PriorityFnCtor': 'implement a PriorityFnCtor protocol that constructs a PriorityFn from an enn_batch_fwd forwarder', 'implement_PerExamplePriority': 'implement a PerExamplePriority protocol that calculates per-example priority scores from logits and labels', 'review_ActiveLearner': 'review the ActiveLearner abstract base class and its sample_batch method and acquisition_size property interface'}
```

## File: google-deepmind_enn/enn/active_learning/priorities.py

Prompts

```
['implement a subclass of ActiveLearner that overrides sample_batch and acquisition_size for custom data selection', 'implement a PriorityFn protocol that assigns priority scores to a batch given params, state, and a PRNG key', 'implement a PriorityFnCtor protocol that constructs a PriorityFn from an enn_batch_fwd forwarder', 'implement a PerExamplePriority protocol that calculates per-example priority scores from logits and labels', 'review the ActiveLearner abstract base class and its sample_batch method and acquisition_size property interface', 'build a priority function constructor from a per example priority using make_priority_fn_ctor', 'create uniformly random per example priority scores using uniform_per_example', 'calculate variance per example from ENN logits using variance_per_example', 'compute negative log-likelihood per example from logits and labels using nll_per_example', 'get a named priority function constructor by name using get_priority_fn_ctor', 'create a PrioritizedBatcher with an ENN batch forwarder and default uniform priority function', 'sample a prioritized batch from a data pool using the PrioritizedBatcher sample_batch method', 'set the acquisition size on a PrioritizedBatcher instance to control how many samples to acquire', 'use get_at_index to extract values at specified indices from a JAX pytree structure', 'review the PrioritizedBatcher sample_batch method to understand how candidate scores select top-N data']
```

Usage

```
{'build_priority_fn_ctor': 'build a priority function constructor from a per example priority using make_priority_fn_ctor', 'create_uniform_priority': 'create uniformly random per example priority scores using uniform_per_example', 'calculate_variance_priority': 'calculate variance per example from ENN logits using variance_per_example', 'compute_nll_priority': 'compute negative log-likelihood per example from logits and labels using nll_per_example', 'get_priority_fn_ctor': 'get a named priority function constructor by name using get_priority_fn_ctor'}
```

## File: google-deepmind_enn/enn/active_learning/prioritized.py

Prompts

```
['implement a subclass of ActiveLearner that overrides sample_batch and acquisition_size for custom data selection', 'implement a PriorityFn protocol that assigns priority scores to a batch given params, state, and a PRNG key', 'implement a PriorityFnCtor protocol that constructs a PriorityFn from an enn_batch_fwd forwarder', 'implement a PerExamplePriority protocol that calculates per-example priority scores from logits and labels', 'review the ActiveLearner abstract base class and its sample_batch method and acquisition_size property interface', 'build a priority function constructor from a per example priority using make_priority_fn_ctor', 'create uniformly random per example priority scores using uniform_per_example', 'calculate variance per example from ENN logits using variance_per_example', 'compute negative log-likelihood per example from logits and labels using nll_per_example', 'get a named priority function constructor by name using get_priority_fn_ctor', 'create a PrioritizedBatcher with an ENN batch forwarder and default uniform priority function', 'sample a prioritized batch from a data pool using the PrioritizedBatcher sample_batch method', 'set the acquisition size on a PrioritizedBatcher instance to control how many samples to acquire', 'use get_at_index to extract values at specified indices from a JAX pytree structure', 'review the PrioritizedBatcher sample_batch method to understand how candidate scores select top-N data']
```

Usage

```
{'create_PrioritizedBatcher': 'create a PrioritizedBatcher with an ENN batch forwarder and default uniform priority function', 'sample_batch_PrioritizedBatcher': 'sample a prioritized batch from a data pool using the PrioritizedBatcher sample_batch method', 'set_acquisition_size': 'set the acquisition size on a PrioritizedBatcher instance to control how many samples to acquire', 'get_at_index_pytree': 'use get_at_index to extract values at specified indices from a JAX pytree structure', 'review_PrioritizedBatcher_sample_batch': 'review the PrioritizedBatcher sample_batch method to understand how candidate scores select top-N data'}
```

