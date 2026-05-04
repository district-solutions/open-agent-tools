# Agent Python Tools

- repo: facebookresearch/beanmachine
- repo_uri: https://github.com/facebookresearch/beanmachine

## File: facebookresearch_beanmachine/tests/ppl/inference/proposer/nmc/single_site_half_space_newtonian_monte_carlo_proposer_test.py

Prompts

```
['test SingleSiteHalfSpaceNMCProposer compute_alpha_beta method with a Gamma distribution in a BeanMachine World', 'test the SampleNormalModel class that defines Normal random variables foo and bar using bm.random_variable', 'test the SampleLogisticRegressionModel class with theta_0, theta_1, x, and Bernoulli y random variables', 'test the SampleFallbackModel class that defines a Gamma foo and Normal bar random variable', 'review the SingleSiteHalfSpaceNewtonianMonteCarloProposerTest class and its test cases for the NMC proposer', 'test the SingleSiteRealSpaceNewtonianMonteCarloProposer mean and scale_tril computation for a MultivariateNormal distribution', 'test the Newtonian Monte Carlo proposer proposal distribution when the target node has a child node', 'test the proposer mean and scale_tril computation for independent identically distributed variables', 'test multi-mean scale_tril computation during inference on a logistic regression model with Bernoulli observations', 'test the adaptive alpha and beta prior computation from accepted learning rates in the proposer', 'test SingleSiteSimplexSpaceNMCProposer.compute_alpha to verify predicted alpha matches Dirichlet distribution parameters', 'test SingleSiteNewtonianMonteCarlo.infer with Beta-Bernoulli coin flip model and observed heads', 'run SingleSiteNewtonianMonteCarlo inference with queries, observations, num_samples, and num_chains parameters', 'create a SingleSiteSimplexSpaceNMCProposer instance for a Dirichlet random variable in a World context', 'test that compute_alpha returns valid alpha values matching the original Dirichlet tensor sum']
```

Usage

```
{'test_compute_alpha_beta_for_gamma': 'test SingleSiteHalfSpaceNMCProposer compute_alpha_beta method with a Gamma distribution in a BeanMachine World', 'test_sample_normal_model': 'test the SampleNormalModel class that defines Normal random variables foo and bar using bm.random_variable', 'test_sample_logistic_regression_model': 'test the SampleLogisticRegressionModel class with theta_0, theta_1, x, and Bernoulli y random variables', 'test_sample_fallback_model': 'test the SampleFallbackModel class that defines a Gamma foo and Normal bar random variable', 'review_single_site_half_space_nmc_proposer': 'review the SingleSiteHalfSpaceNewtonianMonteCarloProposerTest class and its test cases for the NMC proposer'}
```

## File: facebookresearch_beanmachine/tests/ppl/inference/proposer/nmc/single_site_real_space_newtonian_monte_carlo_proposer_test.py

Prompts

```
['test SingleSiteHalfSpaceNMCProposer compute_alpha_beta method with a Gamma distribution in a BeanMachine World', 'test the SampleNormalModel class that defines Normal random variables foo and bar using bm.random_variable', 'test the SampleLogisticRegressionModel class with theta_0, theta_1, x, and Bernoulli y random variables', 'test the SampleFallbackModel class that defines a Gamma foo and Normal bar random variable', 'review the SingleSiteHalfSpaceNewtonianMonteCarloProposerTest class and its test cases for the NMC proposer', 'test the SingleSiteRealSpaceNewtonianMonteCarloProposer mean and scale_tril computation for a MultivariateNormal distribution', 'test the Newtonian Monte Carlo proposer proposal distribution when the target node has a child node', 'test the proposer mean and scale_tril computation for independent identically distributed variables', 'test multi-mean scale_tril computation during inference on a logistic regression model with Bernoulli observations', 'test the adaptive alpha and beta prior computation from accepted learning rates in the proposer', 'test SingleSiteSimplexSpaceNMCProposer.compute_alpha to verify predicted alpha matches Dirichlet distribution parameters', 'test SingleSiteNewtonianMonteCarlo.infer with Beta-Bernoulli coin flip model and observed heads', 'run SingleSiteNewtonianMonteCarlo inference with queries, observations, num_samples, and num_chains parameters', 'create a SingleSiteSimplexSpaceNMCProposer instance for a Dirichlet random variable in a World context', 'test that compute_alpha returns valid alpha values matching the original Dirichlet tensor sum']
```

Usage

```
{'test_proposer_mean_scale_tril': 'test the SingleSiteRealSpaceNewtonianMonteCarloProposer mean and scale_tril computation for a MultivariateNormal distribution', 'test_proposer_with_child_node': 'test the Newtonian Monte Carlo proposer proposal distribution when the target node has a child node', 'test_proposer_for_iids': 'test the proposer mean and scale_tril computation for independent identically distributed variables', 'test_proposer_logistic_regression_inference': 'test multi-mean scale_tril computation during inference on a logistic regression model with Bernoulli observations', 'test_adaptive_alpha_beta': 'test the adaptive alpha and beta prior computation from accepted learning rates in the proposer'}
```

## File: facebookresearch_beanmachine/tests/ppl/inference/proposer/nmc/single_site_simplex_newtonian_monte_carlo_proposer_test.py

Prompts

```
['test SingleSiteHalfSpaceNMCProposer compute_alpha_beta method with a Gamma distribution in a BeanMachine World', 'test the SampleNormalModel class that defines Normal random variables foo and bar using bm.random_variable', 'test the SampleLogisticRegressionModel class with theta_0, theta_1, x, and Bernoulli y random variables', 'test the SampleFallbackModel class that defines a Gamma foo and Normal bar random variable', 'review the SingleSiteHalfSpaceNewtonianMonteCarloProposerTest class and its test cases for the NMC proposer', 'test the SingleSiteRealSpaceNewtonianMonteCarloProposer mean and scale_tril computation for a MultivariateNormal distribution', 'test the Newtonian Monte Carlo proposer proposal distribution when the target node has a child node', 'test the proposer mean and scale_tril computation for independent identically distributed variables', 'test multi-mean scale_tril computation during inference on a logistic regression model with Bernoulli observations', 'test the adaptive alpha and beta prior computation from accepted learning rates in the proposer', 'test SingleSiteSimplexSpaceNMCProposer.compute_alpha to verify predicted alpha matches Dirichlet distribution parameters', 'test SingleSiteNewtonianMonteCarlo.infer with Beta-Bernoulli coin flip model and observed heads', 'run SingleSiteNewtonianMonteCarlo inference with queries, observations, num_samples, and num_chains parameters', 'create a SingleSiteSimplexSpaceNMCProposer instance for a Dirichlet random variable in a World context', 'test that compute_alpha returns valid alpha values matching the original Dirichlet tensor sum']
```

Usage

```
{'test_SingleSiteSimplexSpaceNMCProposer_compute_alpha': 'test SingleSiteSimplexSpaceNMCProposer.compute_alpha to verify predicted alpha matches Dirichlet distribution parameters', 'test_SingleSiteNewtonianMonteCarlo_infer': 'test SingleSiteNewtonianMonteCarlo.infer with Beta-Bernoulli coin flip model and observed heads', 'run_SingleSiteNewtonianMonteCarlo_inference': 'run SingleSiteNewtonianMonteCarlo inference with queries, observations, num_samples, and num_chains parameters', 'create_SingleSiteSimplexSpaceNMCProposer': 'create a SingleSiteSimplexSpaceNMCProposer instance for a Dirichlet random variable in a World context', 'test_Dirichlet_alpha_computation': 'test that compute_alpha returns valid alpha values matching the original Dirichlet tensor sum'}
```

