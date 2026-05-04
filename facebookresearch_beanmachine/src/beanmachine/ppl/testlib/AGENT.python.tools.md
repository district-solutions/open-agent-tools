# Agent Python Tools

- repo: facebookresearch/beanmachine
- repo_uri: https://github.com/facebookresearch/beanmachine

## File: facebookresearch_beanmachine/src/beanmachine/ppl/testlib/abstract_conjugate.py

Prompts

```
['compute the posterior mean and standard deviation for a beta binomial conjugate model', 'compute the posterior mean and standard deviation for a gamma gamma conjugate model', 'compute the posterior mean and standard deviation for a gamma normal conjugate model', 'compute the posterior mean and standard deviation for a normal normal conjugate model', 'compute the posterior mean and standard deviation for a dirichlet categorical conjugate model', 'test if a sample mean equals a true mean using the Dunn-Sidak correction', 'compute the confidence interval for mean equality hypothesis testing with tensor inputs', 'test if a sample variance equals a true variance using chi-squared bounds', 'compute the confidence interval for variance equality hypothesis testing with tensor inputs', 'compute the inverse chi-squared CDF at a given probability and degrees of freedom']
```

Usage

```
{'compute_beta_binomial_moments': 'compute the posterior mean and standard deviation for a beta binomial conjugate model', 'compute_gamma_gamma_moments': 'compute the posterior mean and standard deviation for a gamma gamma conjugate model', 'compute_gamma_normal_moments': 'compute the posterior mean and standard deviation for a gamma normal conjugate model', 'compute_normal_normal_moments': 'compute the posterior mean and standard deviation for a normal normal conjugate model', 'compute_dirichlet_categorical_moments': 'compute the posterior mean and standard deviation for a dirichlet categorical conjugate model'}
```

## File: facebookresearch_beanmachine/src/beanmachine/ppl/testlib/hypothesis_testing.py

Prompts

```
['compute the posterior mean and standard deviation for a beta binomial conjugate model', 'compute the posterior mean and standard deviation for a gamma gamma conjugate model', 'compute the posterior mean and standard deviation for a gamma normal conjugate model', 'compute the posterior mean and standard deviation for a normal normal conjugate model', 'compute the posterior mean and standard deviation for a dirichlet categorical conjugate model', 'test if a sample mean equals a true mean using the Dunn-Sidak correction', 'compute the confidence interval for mean equality hypothesis testing with tensor inputs', 'test if a sample variance equals a true variance using chi-squared bounds', 'compute the confidence interval for variance equality hypothesis testing with tensor inputs', 'compute the inverse chi-squared CDF at a given probability and degrees of freedom']
```

Usage

```
{'test_mean_equality_hypothesis': 'test if a sample mean equals a true mean using the Dunn-Sidak correction', 'compute_mean_confidence_interval': 'compute the confidence interval for mean equality hypothesis testing with tensor inputs', 'test_variance_equality_hypothesis': 'test if a sample variance equals a true variance using chi-squared bounds', 'compute_variance_confidence_interval': 'compute the confidence interval for variance equality hypothesis testing with tensor inputs', 'compute_inverse_chi2_cdf': 'compute the inverse chi-squared CDF at a given probability and degrees of freedom'}
```

