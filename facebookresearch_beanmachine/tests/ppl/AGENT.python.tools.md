# Agent Python Tools

- repo: facebookresearch/beanmachine
- repo_uri: https://github.com/facebookresearch/beanmachine

## File: facebookresearch_beanmachine/tests/ppl/smoke_test.py

Prompts

```
['run a Python function decorated with bm.random_variable to define a Bernoulli or Normal random variable', 'run a Python function decorated with bm.functional to define a deterministic sum over random variables', 'run bm.CompositionalInference to infer posterior samples for query variables conditioned on observed evidence', 'run bm.SingleSiteNoUTurnSampler to perform NUTS MCMC sampling with adaptive warmup for a Normal random variable', 'run bm.Diagnostics on inference samples to generate summary statistics and convergence diagnostics']
```

Usage

```
{'run_random_variable_decorator': 'run a Python function decorated with bm.random_variable to define a Bernoulli or Normal random variable', 'run_functional_decorator': 'run a Python function decorated with bm.functional to define a deterministic sum over random variables', 'run_compositional_inference': 'run bm.CompositionalInference to infer posterior samples for query variables conditioned on observed evidence', 'run_nuts_sampler': 'run bm.SingleSiteNoUTurnSampler to perform NUTS MCMC sampling with adaptive warmup for a Normal random variable', 'run_diagnostics': 'run bm.Diagnostics on inference samples to generate summary statistics and convergence diagnostics'}
```

