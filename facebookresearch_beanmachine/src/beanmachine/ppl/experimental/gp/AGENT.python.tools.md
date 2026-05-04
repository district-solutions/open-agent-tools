# Agent Python Tools

- repo: facebookresearch/beanmachine
- repo_uri: https://github.com/facebookresearch/beanmachine

## File: facebookresearch_beanmachine/src/beanmachine/ppl/experimental/gp/models.py

Prompts

```
['create a SimpleGP Gaussian process model with mean, kernel, and likelihood components for Bean Machine sampling', 'run the SimpleGP forward method to compute a MultivariateNormal distribution from input data', 'load sampled tensors into a SimpleGP model using bm_load_samples with a random variable dictionary', 'create a BoTorchGP model that extends SimpleGP with BoTorch compatibility and multi-output support', 'compute the posterior distribution from a BoTorchGP model conditioned on new test data with optional observation noise']
```

Usage

```
{'create_SimpleGP_model': 'create a SimpleGP Gaussian process model with mean, kernel, and likelihood components for Bean Machine sampling', 'run_SimpleGP_forward': 'run the SimpleGP forward method to compute a MultivariateNormal distribution from input data', 'load_SimpleGP_bm_samples': 'load sampled tensors into a SimpleGP model using bm_load_samples with a random variable dictionary', 'create_BoTorchGP_model': 'create a BoTorchGP model that extends SimpleGP with BoTorch compatibility and multi-output support', 'compute_BoTorchGP_posterior': 'compute the posterior distribution from a BoTorchGP model conditioned on new test data with optional observation noise'}
```

