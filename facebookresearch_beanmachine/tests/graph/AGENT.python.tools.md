# Agent Python Tools

- repo: facebookresearch/beanmachine
- repo_uri: https://github.com/facebookresearch/beanmachine

## File: facebookresearch_beanmachine/tests/graph/cavi_test.py

Prompts

```
['build a probabilistic graph with Bernoulli distributions and run variational inference using CAVI', 'test Gibbs sampling inference on a probabilistic graph with observed and queried variables', 'run coordinate ascent variational inference on a noisy-OR model with multiple Bernoulli priors', 'create a graph with a tabular distribution conditioned on a constant simplex matrix and a sample', 'review the ELBO values across variational inference iterations to confirm convergence', 'build a Bayesian network graph using Graph and add_distribution with TABULAR type for boolean variables', 'create a Bernoulli distribution with a probability constant and run rejection sampling inference', 'run inference on a Beta distribution with two positive real parents using rejection sampling', 'test a Categorical distribution by sampling from a simplex matrix and verifying histogram matches', 'query a graph with observed nodes and run Gibbs sampling to get posterior samples', 'run the eight schools hierarchical Bayesian model test using NMC inference on a BeanMachine graph', 'run the bivariate Gaussian distribution test using NMC inference with EXP_PRODUCT factors on a BeanMachine graph', 'run the probit regression test using NMC inference with Bernoulli likelihood and PHI operator on a BeanMachine graph', 'run the CLARA-GP model test using NMC inference with Gaussian process factors and labeler sensitivity specificity', 'create a Gaussian process factor using the create_GPfactor class method with squared exponential covariance on a BeanMachine graph', 'test beanmachine graph operators like EXP, LOG, NEGATE, ADD, MULTIPLY, and POW with type validation', 'test adding constant nodes of types real, probability, natural, bool, neg_real, and pos_real to a graph', 'test adding constant matrix nodes for bool, real, natural, positive, negative, probability, and col_simplex types', 'test arithmetic operations on graph nodes and verify inference results match expected mathematical values', 'test sampling from distributions like BERNOULLI and BETA with type conversion operators like TO_REAL and TO_PROBABILITY']
```

Usage

```
{'build_graph_variational_inference': 'build a probabilistic graph with Bernoulli distributions and run variational inference using CAVI', 'test_gibbs_sampling_inference': 'test Gibbs sampling inference on a probabilistic graph with observed and queried variables', 'run_cavi_on_noisy_or_model': 'run coordinate ascent variational inference on a noisy-OR model with multiple Bernoulli priors', 'create_tabular_distribution_graph': 'create a graph with a tabular distribution conditioned on a constant simplex matrix and a sample', 'review_elbo_convergence': 'review the ELBO values across variational inference iterations to confirm convergence'}
```

## File: facebookresearch_beanmachine/tests/graph/graph_test.py

Prompts

```
['build a probabilistic graph with Bernoulli distributions and run variational inference using CAVI', 'test Gibbs sampling inference on a probabilistic graph with observed and queried variables', 'run coordinate ascent variational inference on a noisy-OR model with multiple Bernoulli priors', 'create a graph with a tabular distribution conditioned on a constant simplex matrix and a sample', 'review the ELBO values across variational inference iterations to confirm convergence', 'build a Bayesian network graph using Graph and add_distribution with TABULAR type for boolean variables', 'create a Bernoulli distribution with a probability constant and run rejection sampling inference', 'run inference on a Beta distribution with two positive real parents using rejection sampling', 'test a Categorical distribution by sampling from a simplex matrix and verifying histogram matches', 'query a graph with observed nodes and run Gibbs sampling to get posterior samples', 'run the eight schools hierarchical Bayesian model test using NMC inference on a BeanMachine graph', 'run the bivariate Gaussian distribution test using NMC inference with EXP_PRODUCT factors on a BeanMachine graph', 'run the probit regression test using NMC inference with Bernoulli likelihood and PHI operator on a BeanMachine graph', 'run the CLARA-GP model test using NMC inference with Gaussian process factors and labeler sensitivity specificity', 'create a Gaussian process factor using the create_GPfactor class method with squared exponential covariance on a BeanMachine graph', 'test beanmachine graph operators like EXP, LOG, NEGATE, ADD, MULTIPLY, and POW with type validation', 'test adding constant nodes of types real, probability, natural, bool, neg_real, and pos_real to a graph', 'test adding constant matrix nodes for bool, real, natural, positive, negative, probability, and col_simplex types', 'test arithmetic operations on graph nodes and verify inference results match expected mathematical values', 'test sampling from distributions like BERNOULLI and BETA with type conversion operators like TO_REAL and TO_PROBABILITY']
```

Usage

```
{'build_bayesian_network_graph': 'build a Bayesian network graph using Graph and add_distribution with TABULAR type for boolean variables', 'create_bernoulli_inference': 'create a Bernoulli distribution with a probability constant and run rejection sampling inference', 'run_beta_distribution_inference': 'run inference on a Beta distribution with two positive real parents using rejection sampling', 'test_categorical_distribution': 'test a Categorical distribution by sampling from a simplex matrix and verifying histogram matches', 'query_graph_with_observations': 'query a graph with observed nodes and run Gibbs sampling to get posterior samples'}
```

## File: facebookresearch_beanmachine/tests/graph/nmc_test.py

Prompts

```
['build a probabilistic graph with Bernoulli distributions and run variational inference using CAVI', 'test Gibbs sampling inference on a probabilistic graph with observed and queried variables', 'run coordinate ascent variational inference on a noisy-OR model with multiple Bernoulli priors', 'create a graph with a tabular distribution conditioned on a constant simplex matrix and a sample', 'review the ELBO values across variational inference iterations to confirm convergence', 'build a Bayesian network graph using Graph and add_distribution with TABULAR type for boolean variables', 'create a Bernoulli distribution with a probability constant and run rejection sampling inference', 'run inference on a Beta distribution with two positive real parents using rejection sampling', 'test a Categorical distribution by sampling from a simplex matrix and verifying histogram matches', 'query a graph with observed nodes and run Gibbs sampling to get posterior samples', 'run the eight schools hierarchical Bayesian model test using NMC inference on a BeanMachine graph', 'run the bivariate Gaussian distribution test using NMC inference with EXP_PRODUCT factors on a BeanMachine graph', 'run the probit regression test using NMC inference with Bernoulli likelihood and PHI operator on a BeanMachine graph', 'run the CLARA-GP model test using NMC inference with Gaussian process factors and labeler sensitivity specificity', 'create a Gaussian process factor using the create_GPfactor class method with squared exponential covariance on a BeanMachine graph', 'test beanmachine graph operators like EXP, LOG, NEGATE, ADD, MULTIPLY, and POW with type validation', 'test adding constant nodes of types real, probability, natural, bool, neg_real, and pos_real to a graph', 'test adding constant matrix nodes for bool, real, natural, positive, negative, probability, and col_simplex types', 'test arithmetic operations on graph nodes and verify inference results match expected mathematical values', 'test sampling from distributions like BERNOULLI and BETA with type conversion operators like TO_REAL and TO_PROBABILITY']
```

Usage

```
{'test_eight_schools_nmc_inference': 'run the eight schools hierarchical Bayesian model test using NMC inference on a BeanMachine graph', 'test_bivariate_gaussian_nmc_inference': 'run the bivariate Gaussian distribution test using NMC inference with EXP_PRODUCT factors on a BeanMachine graph', 'test_probit_regression_nmc_inference': 'run the probit regression test using NMC inference with Bernoulli likelihood and PHI operator on a BeanMachine graph', 'test_clara_gp_nmc_inference': 'run the CLARA-GP model test using NMC inference with Gaussian process factors and labeler sensitivity specificity', 'create_GPfactor_helper': 'create a Gaussian process factor using the create_GPfactor class method with squared exponential covariance on a BeanMachine graph'}
```

## File: facebookresearch_beanmachine/tests/graph/operator_test.py

Prompts

```
['build a probabilistic graph with Bernoulli distributions and run variational inference using CAVI', 'test Gibbs sampling inference on a probabilistic graph with observed and queried variables', 'run coordinate ascent variational inference on a noisy-OR model with multiple Bernoulli priors', 'create a graph with a tabular distribution conditioned on a constant simplex matrix and a sample', 'review the ELBO values across variational inference iterations to confirm convergence', 'build a Bayesian network graph using Graph and add_distribution with TABULAR type for boolean variables', 'create a Bernoulli distribution with a probability constant and run rejection sampling inference', 'run inference on a Beta distribution with two positive real parents using rejection sampling', 'test a Categorical distribution by sampling from a simplex matrix and verifying histogram matches', 'query a graph with observed nodes and run Gibbs sampling to get posterior samples', 'run the eight schools hierarchical Bayesian model test using NMC inference on a BeanMachine graph', 'run the bivariate Gaussian distribution test using NMC inference with EXP_PRODUCT factors on a BeanMachine graph', 'run the probit regression test using NMC inference with Bernoulli likelihood and PHI operator on a BeanMachine graph', 'run the CLARA-GP model test using NMC inference with Gaussian process factors and labeler sensitivity specificity', 'create a Gaussian process factor using the create_GPfactor class method with squared exponential covariance on a BeanMachine graph', 'test beanmachine graph operators like EXP, LOG, NEGATE, ADD, MULTIPLY, and POW with type validation', 'test adding constant nodes of types real, probability, natural, bool, neg_real, and pos_real to a graph', 'test adding constant matrix nodes for bool, real, natural, positive, negative, probability, and col_simplex types', 'test arithmetic operations on graph nodes and verify inference results match expected mathematical values', 'test sampling from distributions like BERNOULLI and BETA with type conversion operators like TO_REAL and TO_PROBABILITY']
```

Usage

```
{'test_graph_operators': 'test beanmachine graph operators like EXP, LOG, NEGATE, ADD, MULTIPLY, and POW with type validation', 'test_constant_nodes': 'test adding constant nodes of types real, probability, natural, bool, neg_real, and pos_real to a graph', 'test_matrix_constants': 'test adding constant matrix nodes for bool, real, natural, positive, negative, probability, and col_simplex types', 'test_arithmetic_inference': 'test arithmetic operations on graph nodes and verify inference results match expected mathematical values', 'test_distribution_sampling': 'test sampling from distributions like BERNOULLI and BETA with type conversion operators like TO_REAL and TO_PROBABILITY'}
```

