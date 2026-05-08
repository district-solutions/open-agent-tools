# Agent Python Tools

- repo: facebookresearch/kats
- repo_uri: https://github.com/facebookresearch/kats

## File: facebookresearch_kats/kats/tests/conftest.py

Prompts

```
['summarize the pytest_sessionstart hook that sets the matplotlib backend to Agg for headless testing', 'create a TimeSeriesData object from a pandas DataFrame with time and value columns', 'create a TimeSeriesData object from separate time and value pandas Series', 'interpolate missing values in a TimeSeriesData object using linear or ffill methods', 'set or convert the timezone of a TimeSeriesData object to a specified timezone like US/Eastern', 'create an IntervalAnomaly object with start time, end time, and optional confidence score', 'test the BaseEnsemble model by fitting and forecasting on monthly time series data', 'test the MedianEnsembleModel by fitting and predicting on daily time series data', 'test the WeightedAvgEnsemble model with backtesting on dummy time series data', 'test the KatsEnsemble model with median aggregation and additive decomposition on monthly data', 'test the KatsEnsemble model with weighted average aggregation and multiplicative decomposition on daily data', 'run the TestMinimal test suite to verify kats.models is installed and importable', 'run the test_minimal_install test to verify optional dependencies like torch are not required', 'run the TestMinimal unittest class to validate both install and minimal install checks', 'review the test_install method that asserts kats.models is not None', 'review the test_minimal_install method that checks optional imports fail gracefully']
```

Usage

```
{'summarize_pytest_sessionstart': 'summarize the pytest_sessionstart hook that sets the matplotlib backend to Agg for headless testing'}
```

## File: facebookresearch_kats/kats/tests/test_consts.py

Prompts

```
['summarize the pytest_sessionstart hook that sets the matplotlib backend to Agg for headless testing', 'create a TimeSeriesData object from a pandas DataFrame with time and value columns', 'create a TimeSeriesData object from separate time and value pandas Series', 'interpolate missing values in a TimeSeriesData object using linear or ffill methods', 'set or convert the timezone of a TimeSeriesData object to a specified timezone like US/Eastern', 'create an IntervalAnomaly object with start time, end time, and optional confidence score', 'test the BaseEnsemble model by fitting and forecasting on monthly time series data', 'test the MedianEnsembleModel by fitting and predicting on daily time series data', 'test the WeightedAvgEnsemble model with backtesting on dummy time series data', 'test the KatsEnsemble model with median aggregation and additive decomposition on monthly data', 'test the KatsEnsemble model with weighted average aggregation and multiplicative decomposition on daily data', 'run the TestMinimal test suite to verify kats.models is installed and importable', 'run the test_minimal_install test to verify optional dependencies like torch are not required', 'run the TestMinimal unittest class to validate both install and minimal install checks', 'review the test_install method that asserts kats.models is not None', 'review the test_minimal_install method that checks optional imports fail gracefully']
```

Usage

```
{'create_TimeSeriesData_from_dataframe': 'create a TimeSeriesData object from a pandas DataFrame with time and value columns', 'create_TimeSeriesData_from_series': 'create a TimeSeriesData object from separate time and value pandas Series', 'interpolate_TimeSeriesData_missing_values': 'interpolate missing values in a TimeSeriesData object using linear or ffill methods', 'set_timezone_TimeSeriesData': 'set or convert the timezone of a TimeSeriesData object to a specified timezone like US/Eastern', 'create_IntervalAnomaly_with_confidence': 'create an IntervalAnomaly object with start time, end time, and optional confidence score'}
```

## File: facebookresearch_kats/kats/tests/test_ensemble.py

Prompts

```
['summarize the pytest_sessionstart hook that sets the matplotlib backend to Agg for headless testing', 'create a TimeSeriesData object from a pandas DataFrame with time and value columns', 'create a TimeSeriesData object from separate time and value pandas Series', 'interpolate missing values in a TimeSeriesData object using linear or ffill methods', 'set or convert the timezone of a TimeSeriesData object to a specified timezone like US/Eastern', 'create an IntervalAnomaly object with start time, end time, and optional confidence score', 'test the BaseEnsemble model by fitting and forecasting on monthly time series data', 'test the MedianEnsembleModel by fitting and predicting on daily time series data', 'test the WeightedAvgEnsemble model with backtesting on dummy time series data', 'test the KatsEnsemble model with median aggregation and additive decomposition on monthly data', 'test the KatsEnsemble model with weighted average aggregation and multiplicative decomposition on daily data', 'run the TestMinimal test suite to verify kats.models is installed and importable', 'run the test_minimal_install test to verify optional dependencies like torch are not required', 'run the TestMinimal unittest class to validate both install and minimal install checks', 'review the test_install method that asserts kats.models is not None', 'review the test_minimal_install method that checks optional imports fail gracefully']
```

Usage

```
{'test_BaseEnsemble_forecast': 'test the BaseEnsemble model by fitting and forecasting on monthly time series data', 'test_MedianEnsembleModel_forecast': 'test the MedianEnsembleModel by fitting and predicting on daily time series data', 'test_WeightedAvgEnsemble_backtest': 'test the WeightedAvgEnsemble model with backtesting on dummy time series data', 'test_KatsEnsemble_median_aggregation': 'test the KatsEnsemble model with median aggregation and additive decomposition on monthly data', 'test_KatsEnsemble_weightedavg_aggregation': 'test the KatsEnsemble model with weighted average aggregation and multiplicative decomposition on daily data'}
```

## File: facebookresearch_kats/kats/tests/test_minimal.py

Prompts

```
['summarize the pytest_sessionstart hook that sets the matplotlib backend to Agg for headless testing', 'create a TimeSeriesData object from a pandas DataFrame with time and value columns', 'create a TimeSeriesData object from separate time and value pandas Series', 'interpolate missing values in a TimeSeriesData object using linear or ffill methods', 'set or convert the timezone of a TimeSeriesData object to a specified timezone like US/Eastern', 'create an IntervalAnomaly object with start time, end time, and optional confidence score', 'test the BaseEnsemble model by fitting and forecasting on monthly time series data', 'test the MedianEnsembleModel by fitting and predicting on daily time series data', 'test the WeightedAvgEnsemble model with backtesting on dummy time series data', 'test the KatsEnsemble model with median aggregation and additive decomposition on monthly data', 'test the KatsEnsemble model with weighted average aggregation and multiplicative decomposition on daily data', 'run the TestMinimal test suite to verify kats.models is installed and importable', 'run the test_minimal_install test to verify optional dependencies like torch are not required', 'run the TestMinimal unittest class to validate both install and minimal install checks', 'review the test_install method that asserts kats.models is not None', 'review the test_minimal_install method that checks optional imports fail gracefully']
```

Usage

```
{'test_kats_install': 'run the TestMinimal test suite to verify kats.models is installed and importable', 'test_kats_minimal_install': 'run the test_minimal_install test to verify optional dependencies like torch are not required', 'test_TestMinimal_class': 'run the TestMinimal unittest class to validate both install and minimal install checks', 'review_TestMinimal_test_install': 'review the test_install method that asserts kats.models is not None', 'review_TestMinimal_test_minimal_install': 'review the test_minimal_install method that checks optional imports fail gracefully'}
```

