# Agent Python Tools

- repo: facebookresearch/pplbench
- repo_uri: https://github.com/facebookresearch/pplbench

## File: facebookresearch_pplbench/pplbench/ppls/numpyro/base_numpyro_impl.py

Prompts

```
['implement a subclass of BaseNumPyroImplementation to define a custom NumPyro statistical model for PPLBench', 'define the abstract model method using NumPyro primitives to represent a statistical model with observed data', 'define the extract_data_from_numpyro method to convert NumPyro inference samples into an xarray Dataset', 'review the BaseNumPyroImplementation abstract class and its required methods for NumPyro model integration', 'refactor a BaseNumPyroImplementation subclass to update the model or sample extraction logic', 'run MCMC inference with NUTS algorithm on an xarray Dataset using NumPyro', 'run MCMC warmup phase separately to collect warmup samples before final inference', 'review the MCMC class that extends BaseNumPyroInference for probabilistic programming inference', 'review the BaseNumPyroInference class that initializes a NumPyro implementation from model attributes', 'summarize the MCMC infer method that splits RNG keys and merges warmup with post-warmup samples', 'create a LogisticRegression instance with n samples, k features, and prior scale parameters', 'run the NumPyro logistic regression model on an xarray Dataset with X and Y variables', 'extract MCMC samples from NumPyro inference output into an xarray Dataset with alpha and beta', 'review the LogisticRegression class prior distributions for alpha and beta parameters', 'summarize the LogisticRegression class that implements a Bernoulli logistic regression model with NumPyro', 'create a RobustRegression instance with n, k, alpha_scale, beta_scale, beta_loc, and sigma_mean parameters', 'run the RobustRegression model method with an xarray Dataset containing X and Y data', 'extract MCMC samples from NumPyro output into an xarray Dataset with alpha, beta, nu, and sigma', 'review the RobustRegression model using Student-T likelihood with Gamma-distributed degrees of freedom nu', 'refactor the RobustRegression model to change the Normal, Gamma, or Exponential prior distributions']
```

Usage

```
{'implement_BaseNumPyroImplementation': 'implement a subclass of BaseNumPyroImplementation to define a custom NumPyro statistical model for PPLBench', 'define_model_method': 'define the abstract model method using NumPyro primitives to represent a statistical model with observed data', 'define_extract_data_from_numpyro': 'define the extract_data_from_numpyro method to convert NumPyro inference samples into an xarray Dataset', 'review_BaseNumPyroImplementation': 'review the BaseNumPyroImplementation abstract class and its required methods for NumPyro model integration', 'refactor_BaseNumPyroImplementation_subclass': 'refactor a BaseNumPyroImplementation subclass to update the model or sample extraction logic'}
```

## File: facebookresearch_pplbench/pplbench/ppls/numpyro/inference.py

Prompts

```
['implement a subclass of BaseNumPyroImplementation to define a custom NumPyro statistical model for PPLBench', 'define the abstract model method using NumPyro primitives to represent a statistical model with observed data', 'define the extract_data_from_numpyro method to convert NumPyro inference samples into an xarray Dataset', 'review the BaseNumPyroImplementation abstract class and its required methods for NumPyro model integration', 'refactor a BaseNumPyroImplementation subclass to update the model or sample extraction logic', 'run MCMC inference with NUTS algorithm on an xarray Dataset using NumPyro', 'run MCMC warmup phase separately to collect warmup samples before final inference', 'review the MCMC class that extends BaseNumPyroInference for probabilistic programming inference', 'review the BaseNumPyroInference class that initializes a NumPyro implementation from model attributes', 'summarize the MCMC infer method that splits RNG keys and merges warmup with post-warmup samples', 'create a LogisticRegression instance with n samples, k features, and prior scale parameters', 'run the NumPyro logistic regression model on an xarray Dataset with X and Y variables', 'extract MCMC samples from NumPyro inference output into an xarray Dataset with alpha and beta', 'review the LogisticRegression class prior distributions for alpha and beta parameters', 'summarize the LogisticRegression class that implements a Bernoulli logistic regression model with NumPyro', 'create a RobustRegression instance with n, k, alpha_scale, beta_scale, beta_loc, and sigma_mean parameters', 'run the RobustRegression model method with an xarray Dataset containing X and Y data', 'extract MCMC samples from NumPyro output into an xarray Dataset with alpha, beta, nu, and sigma', 'review the RobustRegression model using Student-T likelihood with Gamma-distributed degrees of freedom nu', 'refactor the RobustRegression model to change the Normal, Gamma, or Exponential prior distributions']
```

Usage

```
{'run_MCMC_infer': 'run MCMC inference with NUTS algorithm on an xarray Dataset using NumPyro', 'run_MCMC_warmup': 'run MCMC warmup phase separately to collect warmup samples before final inference', 'review_MCMC_class': 'review the MCMC class that extends BaseNumPyroInference for probabilistic programming inference', 'review_BaseNumPyroInference': 'review the BaseNumPyroInference class that initializes a NumPyro implementation from model attributes', 'summarize_MCMC_infer': 'summarize the MCMC infer method that splits RNG keys and merges warmup with post-warmup samples'}
```

## File: facebookresearch_pplbench/pplbench/ppls/numpyro/logistic_regression.py

Prompts

```
['implement a subclass of BaseNumPyroImplementation to define a custom NumPyro statistical model for PPLBench', 'define the abstract model method using NumPyro primitives to represent a statistical model with observed data', 'define the extract_data_from_numpyro method to convert NumPyro inference samples into an xarray Dataset', 'review the BaseNumPyroImplementation abstract class and its required methods for NumPyro model integration', 'refactor a BaseNumPyroImplementation subclass to update the model or sample extraction logic', 'run MCMC inference with NUTS algorithm on an xarray Dataset using NumPyro', 'run MCMC warmup phase separately to collect warmup samples before final inference', 'review the MCMC class that extends BaseNumPyroInference for probabilistic programming inference', 'review the BaseNumPyroInference class that initializes a NumPyro implementation from model attributes', 'summarize the MCMC infer method that splits RNG keys and merges warmup with post-warmup samples', 'create a LogisticRegression instance with n samples, k features, and prior scale parameters', 'run the NumPyro logistic regression model on an xarray Dataset with X and Y variables', 'extract MCMC samples from NumPyro inference output into an xarray Dataset with alpha and beta', 'review the LogisticRegression class prior distributions for alpha and beta parameters', 'summarize the LogisticRegression class that implements a Bernoulli logistic regression model with NumPyro', 'create a RobustRegression instance with n, k, alpha_scale, beta_scale, beta_loc, and sigma_mean parameters', 'run the RobustRegression model method with an xarray Dataset containing X and Y data', 'extract MCMC samples from NumPyro output into an xarray Dataset with alpha, beta, nu, and sigma', 'review the RobustRegression model using Student-T likelihood with Gamma-distributed degrees of freedom nu', 'refactor the RobustRegression model to change the Normal, Gamma, or Exponential prior distributions']
```

Usage

```
{'create_logistic_regression_model': 'create a LogisticRegression instance with n samples, k features, and prior scale parameters', 'run_logistic_regression_model': 'run the NumPyro logistic regression model on an xarray Dataset with X and Y variables', 'extract_data_from_numpyro_samples': 'extract MCMC samples from NumPyro inference output into an xarray Dataset with alpha and beta', 'review_logistic_regression_prior': 'review the LogisticRegression class prior distributions for alpha and beta parameters', 'summarize_logistic_regression_implementation': 'summarize the LogisticRegression class that implements a Bernoulli logistic regression model with NumPyro'}
```

## File: facebookresearch_pplbench/pplbench/ppls/numpyro/robust_regression.py

Prompts

```
['implement a subclass of BaseNumPyroImplementation to define a custom NumPyro statistical model for PPLBench', 'define the abstract model method using NumPyro primitives to represent a statistical model with observed data', 'define the extract_data_from_numpyro method to convert NumPyro inference samples into an xarray Dataset', 'review the BaseNumPyroImplementation abstract class and its required methods for NumPyro model integration', 'refactor a BaseNumPyroImplementation subclass to update the model or sample extraction logic', 'run MCMC inference with NUTS algorithm on an xarray Dataset using NumPyro', 'run MCMC warmup phase separately to collect warmup samples before final inference', 'review the MCMC class that extends BaseNumPyroInference for probabilistic programming inference', 'review the BaseNumPyroInference class that initializes a NumPyro implementation from model attributes', 'summarize the MCMC infer method that splits RNG keys and merges warmup with post-warmup samples', 'create a LogisticRegression instance with n samples, k features, and prior scale parameters', 'run the NumPyro logistic regression model on an xarray Dataset with X and Y variables', 'extract MCMC samples from NumPyro inference output into an xarray Dataset with alpha and beta', 'review the LogisticRegression class prior distributions for alpha and beta parameters', 'summarize the LogisticRegression class that implements a Bernoulli logistic regression model with NumPyro', 'create a RobustRegression instance with n, k, alpha_scale, beta_scale, beta_loc, and sigma_mean parameters', 'run the RobustRegression model method with an xarray Dataset containing X and Y data', 'extract MCMC samples from NumPyro output into an xarray Dataset with alpha, beta, nu, and sigma', 'review the RobustRegression model using Student-T likelihood with Gamma-distributed degrees of freedom nu', 'refactor the RobustRegression model to change the Normal, Gamma, or Exponential prior distributions']
```

Usage

```
{'create_robust_regression_instance': 'create a RobustRegression instance with n, k, alpha_scale, beta_scale, beta_loc, and sigma_mean parameters', 'run_robust_regression_model': 'run the RobustRegression model method with an xarray Dataset containing X and Y data', 'extract_samples_from_numpyro': 'extract MCMC samples from NumPyro output into an xarray Dataset with alpha, beta, nu, and sigma', 'review_robust_regression_model': 'review the RobustRegression model using Student-T likelihood with Gamma-distributed degrees of freedom nu', 'refactor_robust_regression_priors': 'refactor the RobustRegression model to change the Normal, Gamma, or Exponential prior distributions'}
```

