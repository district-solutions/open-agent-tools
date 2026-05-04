# Agent Python Tools

- repo: google-deepmind/enn
- repo_uri: https://github.com/google-deepmind/enn

## File: google-deepmind_enn/enn/metrics/base.py

Prompts

```
['create a running average aggregator from a MetricCalculator to aggregate metrics across batches', 'compute the average log likelihood from sampled values using the LogSumExp trick for numerical stability', 'create a MetricsState NamedTuple to track aggregated metric value, call count, and extra statistics', 'implement a MetricCalculator protocol that calculates a metric from logits and labels arrays', 'implement an AggregateMetricCalculator protocol that aggregates metrics over logits and labels with state', 'build a polyadic NLL calculator using make_nll_polyadic_calculator with tau and kappa hyperparameters', 'build a joint NLL calculator using make_nll_joint_calculator with a configurable tau batch size', 'calculate joint log likelihood aggregated over ENN samples using calculate_joint_ll with logits and labels', 'reshape logits and labels into smaller equal-sized batches using reshape_to_smaller_batches for batched evaluation', 'review the polyadic NLL metric implementation that resamples tau observations from kappa anchor points', 'compute marginal log likelihood aggregated over ensemble of networks samples from logits and labels', 'compute classification accuracy aggregated over ensemble of networks samples from logits and labels', 'compute joint log likelihood from class probabilities and labels using log of assigned probabilities', 'create a metric calculator that returns marginal negative log likelihood from logits and labels', 'create a metric calculator that returns classification accuracy from logits and labels', 'test average_sampled_log_likelihood with negative infinity and constant log likelihood values', 'test make_nll_polyadic_calculator to compute polyadic negative log likelihood from logits and labels', 'test SingleBatchECE calculator to compute expected calibration error from a single batch of logits and labels', 'test ExpectedCalibrationError calculator to compute ECE incrementally across multiple batches of logits and labels', 'test dyadic match scoring using make_nll_polyadic_calculator with random logits and integer labels']
```

Usage

```
{'make_average_aggregator': 'create a running average aggregator from a MetricCalculator to aggregate metrics across batches', 'average_sampled_log_likelihood': 'compute the average log likelihood from sampled values using the LogSumExp trick for numerical stability', 'MetricsState': 'create a MetricsState NamedTuple to track aggregated metric value, call count, and extra statistics', 'MetricCalculator': 'implement a MetricCalculator protocol that calculates a metric from logits and labels arrays', 'AggregateMetricCalculator': 'implement an AggregateMetricCalculator protocol that aggregates metrics over logits and labels with state'}
```

## File: google-deepmind_enn/enn/metrics/joint.py

Prompts

```
['create a running average aggregator from a MetricCalculator to aggregate metrics across batches', 'compute the average log likelihood from sampled values using the LogSumExp trick for numerical stability', 'create a MetricsState NamedTuple to track aggregated metric value, call count, and extra statistics', 'implement a MetricCalculator protocol that calculates a metric from logits and labels arrays', 'implement an AggregateMetricCalculator protocol that aggregates metrics over logits and labels with state', 'build a polyadic NLL calculator using make_nll_polyadic_calculator with tau and kappa hyperparameters', 'build a joint NLL calculator using make_nll_joint_calculator with a configurable tau batch size', 'calculate joint log likelihood aggregated over ENN samples using calculate_joint_ll with logits and labels', 'reshape logits and labels into smaller equal-sized batches using reshape_to_smaller_batches for batched evaluation', 'review the polyadic NLL metric implementation that resamples tau observations from kappa anchor points', 'compute marginal log likelihood aggregated over ensemble of networks samples from logits and labels', 'compute classification accuracy aggregated over ensemble of networks samples from logits and labels', 'compute joint log likelihood from class probabilities and labels using log of assigned probabilities', 'create a metric calculator that returns marginal negative log likelihood from logits and labels', 'create a metric calculator that returns classification accuracy from logits and labels', 'test average_sampled_log_likelihood with negative infinity and constant log likelihood values', 'test make_nll_polyadic_calculator to compute polyadic negative log likelihood from logits and labels', 'test SingleBatchECE calculator to compute expected calibration error from a single batch of logits and labels', 'test ExpectedCalibrationError calculator to compute ECE incrementally across multiple batches of logits and labels', 'test dyadic match scoring using make_nll_polyadic_calculator with random logits and integer labels']
```

Usage

```
{'build_polyadic_nll_calculator': 'build a polyadic NLL calculator using make_nll_polyadic_calculator with tau and kappa hyperparameters', 'build_joint_nll_calculator': 'build a joint NLL calculator using make_nll_joint_calculator with a configurable tau batch size', 'calculate_joint_log_likelihood': 'calculate joint log likelihood aggregated over ENN samples using calculate_joint_ll with logits and labels', 'reshape_to_smaller_batches': 'reshape logits and labels into smaller equal-sized batches using reshape_to_smaller_batches for batched evaluation', 'review_polyadic_nll_metric': 'review the polyadic NLL metric implementation that resamples tau observations from kappa anchor points'}
```

## File: google-deepmind_enn/enn/metrics/marginal.py

Prompts

```
['create a running average aggregator from a MetricCalculator to aggregate metrics across batches', 'compute the average log likelihood from sampled values using the LogSumExp trick for numerical stability', 'create a MetricsState NamedTuple to track aggregated metric value, call count, and extra statistics', 'implement a MetricCalculator protocol that calculates a metric from logits and labels arrays', 'implement an AggregateMetricCalculator protocol that aggregates metrics over logits and labels with state', 'build a polyadic NLL calculator using make_nll_polyadic_calculator with tau and kappa hyperparameters', 'build a joint NLL calculator using make_nll_joint_calculator with a configurable tau batch size', 'calculate joint log likelihood aggregated over ENN samples using calculate_joint_ll with logits and labels', 'reshape logits and labels into smaller equal-sized batches using reshape_to_smaller_batches for batched evaluation', 'review the polyadic NLL metric implementation that resamples tau observations from kappa anchor points', 'compute marginal log likelihood aggregated over ensemble of networks samples from logits and labels', 'compute classification accuracy aggregated over ensemble of networks samples from logits and labels', 'compute joint log likelihood from class probabilities and labels using log of assigned probabilities', 'create a metric calculator that returns marginal negative log likelihood from logits and labels', 'create a metric calculator that returns classification accuracy from logits and labels', 'test average_sampled_log_likelihood with negative infinity and constant log likelihood values', 'test make_nll_polyadic_calculator to compute polyadic negative log likelihood from logits and labels', 'test SingleBatchECE calculator to compute expected calibration error from a single batch of logits and labels', 'test ExpectedCalibrationError calculator to compute ECE incrementally across multiple batches of logits and labels', 'test dyadic match scoring using make_nll_polyadic_calculator with random logits and integer labels']
```

Usage

```
{'calculate_marginal_ll': 'compute marginal log likelihood aggregated over ensemble of networks samples from logits and labels', 'calculate_accuracy': 'compute classification accuracy aggregated over ensemble of networks samples from logits and labels', 'categorical_log_likelihood': 'compute joint log likelihood from class probabilities and labels using log of assigned probabilities', 'make_nll_marginal_calculator': 'create a metric calculator that returns marginal negative log likelihood from logits and labels', 'make_accuracy_calculator': 'create a metric calculator that returns classification accuracy from logits and labels'}
```

## File: google-deepmind_enn/enn/metrics/metrics_test.py

Prompts

```
['create a running average aggregator from a MetricCalculator to aggregate metrics across batches', 'compute the average log likelihood from sampled values using the LogSumExp trick for numerical stability', 'create a MetricsState NamedTuple to track aggregated metric value, call count, and extra statistics', 'implement a MetricCalculator protocol that calculates a metric from logits and labels arrays', 'implement an AggregateMetricCalculator protocol that aggregates metrics over logits and labels with state', 'build a polyadic NLL calculator using make_nll_polyadic_calculator with tau and kappa hyperparameters', 'build a joint NLL calculator using make_nll_joint_calculator with a configurable tau batch size', 'calculate joint log likelihood aggregated over ENN samples using calculate_joint_ll with logits and labels', 'reshape logits and labels into smaller equal-sized batches using reshape_to_smaller_batches for batched evaluation', 'review the polyadic NLL metric implementation that resamples tau observations from kappa anchor points', 'compute marginal log likelihood aggregated over ensemble of networks samples from logits and labels', 'compute classification accuracy aggregated over ensemble of networks samples from logits and labels', 'compute joint log likelihood from class probabilities and labels using log of assigned probabilities', 'create a metric calculator that returns marginal negative log likelihood from logits and labels', 'create a metric calculator that returns classification accuracy from logits and labels', 'test average_sampled_log_likelihood with negative infinity and constant log likelihood values', 'test make_nll_polyadic_calculator to compute polyadic negative log likelihood from logits and labels', 'test SingleBatchECE calculator to compute expected calibration error from a single batch of logits and labels', 'test ExpectedCalibrationError calculator to compute ECE incrementally across multiple batches of logits and labels', 'test dyadic match scoring using make_nll_polyadic_calculator with random logits and integer labels']
```

Usage

```
{'test_average_sampled_log_likelihood': 'test average_sampled_log_likelihood with negative infinity and constant log likelihood values', 'test_nll_polyadic_calculator': 'test make_nll_polyadic_calculator to compute polyadic negative log likelihood from logits and labels', 'test_single_batch_ece': 'test SingleBatchECE calculator to compute expected calibration error from a single batch of logits and labels', 'test_expected_calibration_error': 'test ExpectedCalibrationError calculator to compute ECE incrementally across multiple batches of logits and labels', 'test_dyadic_matches': 'test dyadic match scoring using make_nll_polyadic_calculator with random logits and integer labels'}
```

