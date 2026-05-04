# Agent Python Tools

- repo: facebookresearch/beanmachine
- repo_uri: https://github.com/facebookresearch/beanmachine

## File: facebookresearch_beanmachine/src/beanmachine/ppl/distributions/delta.py

Prompts

```
['create a Delta distribution with a tensor value and optional log_density for MAP estimation', 'sample from a Delta distribution using rsample to get the deterministic value expanded to sample shape', 'compute the log probability of a value against a Delta distribution with added log_density', 'expand a Delta distribution to a new batch shape while preserving event shape', 'get the mean and variance properties of a Delta distribution returning value and zeros', 'create a Flat distribution with a specified shape tuple for use as an improper prior', 'sample zeros from a Flat distribution using the sample method with the configured shape', 'reparameterize sample zeros from a Flat distribution given a sample_shape argument', 'compute the log probability of a value against a Flat distribution returning zero', 'review the Flat class extending torch.distributions.Distribution for improper prior usage in probabilistic programming', 'create a function that broadcasts multiple tensor shapes together similar to numpy broadcast', 'build a Unit distribution instance with a log_factor tensor for pyro factor statements', 'sample empty tensors from a Unit distribution using the sample method', 'compute the log probability of a value against a Unit distribution using broadcast_shape', 'expand a Unit distribution to a new batch_shape while preserving the log_factor']
```

Usage

```
{'create_delta_distribution': 'create a Delta distribution with a tensor value and optional log_density for MAP estimation', 'sample_from_delta': 'sample from a Delta distribution using rsample to get the deterministic value expanded to sample shape', 'compute_log_prob_delta': 'compute the log probability of a value against a Delta distribution with added log_density', 'expand_delta_distribution': 'expand a Delta distribution to a new batch shape while preserving event shape', 'get_delta_mean_variance': 'get the mean and variance properties of a Delta distribution returning value and zeros'}
```

## File: facebookresearch_beanmachine/src/beanmachine/ppl/distributions/flat.py

Prompts

```
['create a Delta distribution with a tensor value and optional log_density for MAP estimation', 'sample from a Delta distribution using rsample to get the deterministic value expanded to sample shape', 'compute the log probability of a value against a Delta distribution with added log_density', 'expand a Delta distribution to a new batch shape while preserving event shape', 'get the mean and variance properties of a Delta distribution returning value and zeros', 'create a Flat distribution with a specified shape tuple for use as an improper prior', 'sample zeros from a Flat distribution using the sample method with the configured shape', 'reparameterize sample zeros from a Flat distribution given a sample_shape argument', 'compute the log probability of a value against a Flat distribution returning zero', 'review the Flat class extending torch.distributions.Distribution for improper prior usage in probabilistic programming', 'create a function that broadcasts multiple tensor shapes together similar to numpy broadcast', 'build a Unit distribution instance with a log_factor tensor for pyro factor statements', 'sample empty tensors from a Unit distribution using the sample method', 'compute the log probability of a value against a Unit distribution using broadcast_shape', 'expand a Unit distribution to a new batch_shape while preserving the log_factor']
```

Usage

```
{'create_flat_distribution': 'create a Flat distribution with a specified shape tuple for use as an improper prior', 'sample_flat_distribution': 'sample zeros from a Flat distribution using the sample method with the configured shape', 'rsample_flat_distribution': 'reparameterize sample zeros from a Flat distribution given a sample_shape argument', 'log_prob_flat_distribution': 'compute the log probability of a value against a Flat distribution returning zero', 'review_flat_distribution_class': 'review the Flat class extending torch.distributions.Distribution for improper prior usage in probabilistic programming'}
```

## File: facebookresearch_beanmachine/src/beanmachine/ppl/distributions/unit.py

Prompts

```
['create a Delta distribution with a tensor value and optional log_density for MAP estimation', 'sample from a Delta distribution using rsample to get the deterministic value expanded to sample shape', 'compute the log probability of a value against a Delta distribution with added log_density', 'expand a Delta distribution to a new batch shape while preserving event shape', 'get the mean and variance properties of a Delta distribution returning value and zeros', 'create a Flat distribution with a specified shape tuple for use as an improper prior', 'sample zeros from a Flat distribution using the sample method with the configured shape', 'reparameterize sample zeros from a Flat distribution given a sample_shape argument', 'compute the log probability of a value against a Flat distribution returning zero', 'review the Flat class extending torch.distributions.Distribution for improper prior usage in probabilistic programming', 'create a function that broadcasts multiple tensor shapes together similar to numpy broadcast', 'build a Unit distribution instance with a log_factor tensor for pyro factor statements', 'sample empty tensors from a Unit distribution using the sample method', 'compute the log probability of a value against a Unit distribution using broadcast_shape', 'expand a Unit distribution to a new batch_shape while preserving the log_factor']
```

Usage

```
{'create_broadcast_shape': 'create a function that broadcasts multiple tensor shapes together similar to numpy broadcast', 'build_unit_distribution': 'build a Unit distribution instance with a log_factor tensor for pyro factor statements', 'sample_unit_distribution': 'sample empty tensors from a Unit distribution using the sample method', 'compute_unit_log_prob': 'compute the log probability of a value against a Unit distribution using broadcast_shape', 'expand_unit_distribution': 'expand a Unit distribution to a new batch_shape while preserving the log_factor'}
```

