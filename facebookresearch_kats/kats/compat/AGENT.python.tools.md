# Agent Python Tools

- repo: facebookresearch/kats
- repo_uri: https://github.com/facebookresearch/kats

## File: facebookresearch_kats/kats/compat/pandas.py

Prompts

```
['test two pandas DataFrames for equality across multiple pandas versions with tolerance options', 'test two pandas Series for equality with dtype, frequency, and categorical checks', 'test two pandas Index objects for equality with optional order and precision checks', 'refactor the convert_precision function to map check_less_precise and rtol to an integer precision value', 'review the pandas compatibility wrapper functions that adapt assert_equal calls across pandas versions', 'calculate the mean squared error between true and predicted values using sklearn compatibility wrapper', 'calculate the mean squared log error between true and predicted values with sklearn version compatibility', 'check the installed sklearn version using the compat.Version object for compatibility checks', 'test the mean squared error function with sample_weight and multioutput parameters', 'test the mean squared log error function with squared parameter across sklearn versions', 'create an ExponentialSmoothing model with trend and seasonal parameters for time series data', 'fit an ExponentialSmoothing model to time series data and return HoltWintersResults', 'create a HoltWintersResults wrapper that normalizes smoothing_trend across statsmodels versions', 'review the ExponentialSmoothing class to understand statsmodels version compatibility handling', 'summarize the HoltWintersResults init logic for statsmodels version 0.12 and below']
```

Usage

```
{'test_assert_frame_equal': 'test two pandas DataFrames for equality across multiple pandas versions with tolerance options', 'test_assert_series_equal': 'test two pandas Series for equality with dtype, frequency, and categorical checks', 'test_assert_index_equal': 'test two pandas Index objects for equality with optional order and precision checks', 'refactor_convert_precision': 'refactor the convert_precision function to map check_less_precise and rtol to an integer precision value', 'review_pandas_compat_wrappers': 'review the pandas compatibility wrapper functions that adapt assert_equal calls across pandas versions'}
```

## File: facebookresearch_kats/kats/compat/sklearn.py

Prompts

```
['test two pandas DataFrames for equality across multiple pandas versions with tolerance options', 'test two pandas Series for equality with dtype, frequency, and categorical checks', 'test two pandas Index objects for equality with optional order and precision checks', 'refactor the convert_precision function to map check_less_precise and rtol to an integer precision value', 'review the pandas compatibility wrapper functions that adapt assert_equal calls across pandas versions', 'calculate the mean squared error between true and predicted values using sklearn compatibility wrapper', 'calculate the mean squared log error between true and predicted values with sklearn version compatibility', 'check the installed sklearn version using the compat.Version object for compatibility checks', 'test the mean squared error function with sample_weight and multioutput parameters', 'test the mean squared log error function with squared parameter across sklearn versions', 'create an ExponentialSmoothing model with trend and seasonal parameters for time series data', 'fit an ExponentialSmoothing model to time series data and return HoltWintersResults', 'create a HoltWintersResults wrapper that normalizes smoothing_trend across statsmodels versions', 'review the ExponentialSmoothing class to understand statsmodels version compatibility handling', 'summarize the HoltWintersResults init logic for statsmodels version 0.12 and below']
```

Usage

```
{'calculate_mean_squared_error': 'calculate the mean squared error between true and predicted values using sklearn compatibility wrapper', 'calculate_mean_squared_log_error': 'calculate the mean squared log error between true and predicted values with sklearn version compatibility', 'check_sklearn_version': 'check the installed sklearn version using the compat.Version object for compatibility checks', 'test_mean_squared_error': 'test the mean squared error function with sample_weight and multioutput parameters', 'test_mean_squared_log_error_squared': 'test the mean squared log error function with squared parameter across sklearn versions'}
```

## File: facebookresearch_kats/kats/compat/statsmodels.py

Prompts

```
['test two pandas DataFrames for equality across multiple pandas versions with tolerance options', 'test two pandas Series for equality with dtype, frequency, and categorical checks', 'test two pandas Index objects for equality with optional order and precision checks', 'refactor the convert_precision function to map check_less_precise and rtol to an integer precision value', 'review the pandas compatibility wrapper functions that adapt assert_equal calls across pandas versions', 'calculate the mean squared error between true and predicted values using sklearn compatibility wrapper', 'calculate the mean squared log error between true and predicted values with sklearn version compatibility', 'check the installed sklearn version using the compat.Version object for compatibility checks', 'test the mean squared error function with sample_weight and multioutput parameters', 'test the mean squared log error function with squared parameter across sklearn versions', 'create an ExponentialSmoothing model with trend and seasonal parameters for time series data', 'fit an ExponentialSmoothing model to time series data and return HoltWintersResults', 'create a HoltWintersResults wrapper that normalizes smoothing_trend across statsmodels versions', 'review the ExponentialSmoothing class to understand statsmodels version compatibility handling', 'summarize the HoltWintersResults init logic for statsmodels version 0.12 and below']
```

Usage

```
{'create_ExponentialSmoothing_model': 'create an ExponentialSmoothing model with trend and seasonal parameters for time series data', 'fit_ExponentialSmoothing': 'fit an ExponentialSmoothing model to time series data and return HoltWintersResults', 'create_HoltWintersResults': 'create a HoltWintersResults wrapper that normalizes smoothing_trend across statsmodels versions', 'review_ExponentialSmoothing_version_compat': 'review the ExponentialSmoothing class to understand statsmodels version compatibility handling', 'summarize_HoltWintersResults_init': 'summarize the HoltWintersResults init logic for statsmodels version 0.12 and below'}
```

