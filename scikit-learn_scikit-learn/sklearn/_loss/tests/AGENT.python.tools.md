# Agent Python Tools

- repo: scikit-learn/scikit-learn
- repo_uri: https://github.com/scikit-learn/scikit-learn

## File: scikit-learn_scikit-learn/sklearn/_loss/tests/test_link.py

Prompts

```
['test the Interval class raises ValueError when low is greater than high', 'test Interval.includes correctly validates arrays against interval bounds with inclusive flags', 'test link and inverse methods are identity transformations for all link functions', 'test link inverse and link methods support in-place output via the out argument', 'test MultinomialLogit.symmetrize_raw_prediction handles multiclass raw predictions', 'test the loss, gradient, and hessian computations at specific values for all supported loss functions', 'test that loss gradients and hessians match numerical derivatives computed via finite differences', 'test that loss functions accept float32 and float64 dtypes and handle readonly memmap-backed arrays', 'test the valid value ranges for y_true and y_pred for each loss function class', 'test that fit_intercept_only returns the correct functional (mean, median, quantile) for each loss type', 'test that sample weights correctly scale loss, gradient, and hessian outputs', 'test that binomial loss matches the alternative z-in {-1,+1} formulation from ESL', 'test that HalfTweedieLoss with log link and HalfTweedieLossIdentity produce consistent results via chain rule', 'test that invalid constructor parameters raise appropriate TypeError or ValueError', 'test that loss instances can be pickled and unpickled with identical behavior']
```

Usage

```
{'test_interval_raises': 'test the Interval class raises ValueError when low is greater than high', 'test_is_in_range': 'test Interval.includes correctly validates arrays against interval bounds with inclusive flags', 'test_link_inverse_identity': 'test link and inverse methods are identity transformations for all link functions', 'test_link_out_argument': 'test link inverse and link methods support in-place output via the out argument', 'test_multinomial_symmetrize': 'test MultinomialLogit.symmetrize_raw_prediction handles multiclass raw predictions'}
```

## File: scikit-learn_scikit-learn/sklearn/_loss/tests/test_loss.py

Prompts

```
['test the Interval class raises ValueError when low is greater than high', 'test Interval.includes correctly validates arrays against interval bounds with inclusive flags', 'test link and inverse methods are identity transformations for all link functions', 'test link inverse and link methods support in-place output via the out argument', 'test MultinomialLogit.symmetrize_raw_prediction handles multiclass raw predictions', 'test the loss, gradient, and hessian computations at specific values for all supported loss functions', 'test that loss gradients and hessians match numerical derivatives computed via finite differences', 'test that loss functions accept float32 and float64 dtypes and handle readonly memmap-backed arrays', 'test the valid value ranges for y_true and y_pred for each loss function class', 'test that fit_intercept_only returns the correct functional (mean, median, quantile) for each loss type', 'test that sample weights correctly scale loss, gradient, and hessian outputs', 'test that binomial loss matches the alternative z-in {-1,+1} formulation from ESL', 'test that HalfTweedieLoss with log link and HalfTweedieLossIdentity produce consistent results via chain rule', 'test that invalid constructor parameters raise appropriate TypeError or ValueError', 'test that loss instances can be pickled and unpickled with identical behavior']
```

Usage

```
{'test_loss_computations': 'test the loss, gradient, and hessian computations at specific values for all supported loss functions', 'test_loss_gradients_numerically': 'test that loss gradients and hessians match numerical derivatives computed via finite differences', 'test_loss_dtype_and_memmap': 'test that loss functions accept float32 and float64 dtypes and handle readonly memmap-backed arrays', 'test_loss_boundary_ranges': 'test the valid value ranges for y_true and y_pred for each loss function class', 'test_fit_intercept_only_functionals': 'test that fit_intercept_only returns the correct functional (mean, median, quantile) for each loss type', 'test_sample_weight_scaling': 'test that sample weights correctly scale loss, gradient, and hessian outputs', 'test_binomial_alternative_formulation': 'test that binomial loss matches the alternative z-in {-1,+1} formulation from ESL', 'test_tweedie_link_consistency': 'test that HalfTweedieLoss with log link and HalfTweedieLossIdentity produce consistent results via chain rule', 'test_loss_parameter_validation': 'test that invalid constructor parameters raise appropriate TypeError or ValueError', 'test_loss_pickle_serialization': 'test that loss instances can be pickled and unpickled with identical behavior'}
```

