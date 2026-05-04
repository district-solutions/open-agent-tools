# Agent Python Tools

- repo: facebookresearch/beanmachine
- repo_uri: https://github.com/facebookresearch/beanmachine

## File: facebookresearch_beanmachine/src/beanmachine/ppl/diagnostics/common_plots.py

Prompts

```
['build a python module that uses trace_helper to convert x/y data into Plotly Scatter traces for MCMC chains', 'create a function that uses plot_helper to generate Plotly traces from PyTorch query_samples with a custom callback', 'test the autocorr function to compute autocorrelation values for a 1D PyTorch tensor across all lags', 'refactor the trace_plot function to return x-axis indices and tensor values for MCMC chain visualization', 'review the SamplesSummary NamedTuple and _samples_info function for extracting MCMC sample metadata from a PyTorch tensor', 'compute the mean of MCMC query samples across chains and samples dimensions', 'compute the standard deviation of MCMC query samples across chains and samples dimensions', 'compute the 2.5, 50, and 97.5 percentile confidence interval for MCMC query samples', 'compute the potential scale reduction factor R-hat diagnostic for MCMC chain convergence', 'compute the effective sample size diagnostic for MCMC chains using FFT-based autocorrelation', 'create a Diagnostics object from MonteCarloSamples to compute MCMC summary statistics and plots', 'summarize MCMC samples by calling summary on a Diagnostics instance to get mean, std, and confidence intervals', 'plot trace and autocorrelation plots for MCMC chains using the trace and autocorr methods on Diagnostics', 'compute the split R-hat convergence diagnostic for MCMC chains using the split_r_hat method on Diagnostics', 'register a custom summary statistic function using summaryfn to extend Diagnostics with new metrics']
```

Usage

```
{'build_trace_helper': 'build a python module that uses trace_helper to convert x/y data into Plotly Scatter traces for MCMC chains', 'create_plot_helper': 'create a function that uses plot_helper to generate Plotly traces from PyTorch query_samples with a custom callback', 'test_autocorr': 'test the autocorr function to compute autocorrelation values for a 1D PyTorch tensor across all lags', 'refactor_trace_plot': 'refactor the trace_plot function to return x-axis indices and tensor values for MCMC chain visualization', 'review_SamplesSummary': 'review the SamplesSummary NamedTuple and _samples_info function for extracting MCMC sample metadata from a PyTorch tensor'}
```

## File: facebookresearch_beanmachine/src/beanmachine/ppl/diagnostics/common_statistics.py

Prompts

```
['build a python module that uses trace_helper to convert x/y data into Plotly Scatter traces for MCMC chains', 'create a function that uses plot_helper to generate Plotly traces from PyTorch query_samples with a custom callback', 'test the autocorr function to compute autocorrelation values for a 1D PyTorch tensor across all lags', 'refactor the trace_plot function to return x-axis indices and tensor values for MCMC chain visualization', 'review the SamplesSummary NamedTuple and _samples_info function for extracting MCMC sample metadata from a PyTorch tensor', 'compute the mean of MCMC query samples across chains and samples dimensions', 'compute the standard deviation of MCMC query samples across chains and samples dimensions', 'compute the 2.5, 50, and 97.5 percentile confidence interval for MCMC query samples', 'compute the potential scale reduction factor R-hat diagnostic for MCMC chain convergence', 'compute the effective sample size diagnostic for MCMC chains using FFT-based autocorrelation', 'create a Diagnostics object from MonteCarloSamples to compute MCMC summary statistics and plots', 'summarize MCMC samples by calling summary on a Diagnostics instance to get mean, std, and confidence intervals', 'plot trace and autocorrelation plots for MCMC chains using the trace and autocorr methods on Diagnostics', 'compute the split R-hat convergence diagnostic for MCMC chains using the split_r_hat method on Diagnostics', 'register a custom summary statistic function using summaryfn to extend Diagnostics with new metrics']
```

Usage

```
{'compute_mean_of_samples': 'compute the mean of MCMC query samples across chains and samples dimensions', 'compute_std_of_samples': 'compute the standard deviation of MCMC query samples across chains and samples dimensions', 'compute_confidence_interval': 'compute the 2.5, 50, and 97.5 percentile confidence interval for MCMC query samples', 'compute_r_hat': 'compute the potential scale reduction factor R-hat diagnostic for MCMC chain convergence', 'compute_effective_sample_size': 'compute the effective sample size diagnostic for MCMC chains using FFT-based autocorrelation'}
```

## File: facebookresearch_beanmachine/src/beanmachine/ppl/diagnostics/diagnostics.py

Prompts

```
['build a python module that uses trace_helper to convert x/y data into Plotly Scatter traces for MCMC chains', 'create a function that uses plot_helper to generate Plotly traces from PyTorch query_samples with a custom callback', 'test the autocorr function to compute autocorrelation values for a 1D PyTorch tensor across all lags', 'refactor the trace_plot function to return x-axis indices and tensor values for MCMC chain visualization', 'review the SamplesSummary NamedTuple and _samples_info function for extracting MCMC sample metadata from a PyTorch tensor', 'compute the mean of MCMC query samples across chains and samples dimensions', 'compute the standard deviation of MCMC query samples across chains and samples dimensions', 'compute the 2.5, 50, and 97.5 percentile confidence interval for MCMC query samples', 'compute the potential scale reduction factor R-hat diagnostic for MCMC chain convergence', 'compute the effective sample size diagnostic for MCMC chains using FFT-based autocorrelation', 'create a Diagnostics object from MonteCarloSamples to compute MCMC summary statistics and plots', 'summarize MCMC samples by calling summary on a Diagnostics instance to get mean, std, and confidence intervals', 'plot trace and autocorrelation plots for MCMC chains using the trace and autocorr methods on Diagnostics', 'compute the split R-hat convergence diagnostic for MCMC chains using the split_r_hat method on Diagnostics', 'register a custom summary statistic function using summaryfn to extend Diagnostics with new metrics']
```

Usage

```
{'create_diagnostics_instance': 'create a Diagnostics object from MonteCarloSamples to compute MCMC summary statistics and plots', 'summarize_mcmc_samples': 'summarize MCMC samples by calling summary on a Diagnostics instance to get mean, std, and confidence intervals', 'plot_trace_and_autocorr': 'plot trace and autocorrelation plots for MCMC chains using the trace and autocorr methods on Diagnostics', 'compute_split_r_hat': 'compute the split R-hat convergence diagnostic for MCMC chains using the split_r_hat method on Diagnostics', 'register_custom_summary_function': 'register a custom summary statistic function using summaryfn to extend Diagnostics with new metrics'}
```

