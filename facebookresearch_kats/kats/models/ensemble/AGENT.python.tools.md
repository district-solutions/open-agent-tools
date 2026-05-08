# Agent Python Tools

- repo: facebookresearch/kats
- repo_uri: https://github.com/facebookresearch/kats

## File: facebookresearch_kats/kats/models/ensemble/ensemble.py

Prompts

```
['create a BaseModelParams instance with a model name and model parameters for ensemble configuration', 'create an EnsembleParams object with a list of BaseModelParams to configure multiple base models', 'fit a BaseEnsemble model by calling fit to train all base models in parallel using multiprocessing', 'predict future values from a fitted BaseEnsemble by calling _predict_all with a forecast horizon', 'review the BASE_MODELS dictionary mapping model names to ARIMA, HoltWinters, SARIMA, Prophet, Linear, and Quadratic classes', 'build a KatsEnsemble model to fit multiple forecasting models and aggregate predictions with median or weighted average', 'detect seasonality in time series data using the ACFDetector static method on TimeSeriesData', 'deseasonalize time series data using STL decomposition with additive or multiplicative methods', 'backtest individual ensemble models and compute error metrics like MAPE, RMSE, or MAE for weight calculation', 'aggregate individual model forecasts into a final prediction DataFrame using median or weighted average aggregation', 'create a MedianEnsembleModel with TimeSeriesData and EnsembleParams for univariate time series forecasting', 'predict future values using MedianEnsembleModel predict method with steps and freq kwargs', 'review the MedianEnsembleModel constructor to validate univariate time series input data', 'summarize the MedianEnsembleModel predict method that computes median across base model forecasts', 'test the MedianEnsembleModel forecast output DataFrame containing time and fcst columns', 'create a WeightedAvgEnsemble model with TimeSeriesData and EnsembleParams for univariate time series forecasting', 'predict future values using the WeightedAvgEnsemble model with a specified forecasting horizon and frequency', 'run backtesting on a single model using BackTesterSimple with configurable train test split and error method', 'run parallel backtesting across all ensemble models to compute inverse-error weights for each model', 'review the computed model weights and backtesting errors from the WeightedAvgEnsemble ensemble']
```

Usage

```
{'create_BaseModelParams': 'create a BaseModelParams instance with a model name and model parameters for ensemble configuration', 'create_EnsembleParams': 'create an EnsembleParams object with a list of BaseModelParams to configure multiple base models', 'fit_BaseEnsemble': 'fit a BaseEnsemble model by calling fit to train all base models in parallel using multiprocessing', 'predict_BaseEnsemble': 'predict future values from a fitted BaseEnsemble by calling _predict_all with a forecast horizon', 'review_BASE_MODELS': 'review the BASE_MODELS dictionary mapping model names to ARIMA, HoltWinters, SARIMA, Prophet, Linear, and Quadratic classes'}
```

## File: facebookresearch_kats/kats/models/ensemble/kats_ensemble.py

Prompts

```
['create a BaseModelParams instance with a model name and model parameters for ensemble configuration', 'create an EnsembleParams object with a list of BaseModelParams to configure multiple base models', 'fit a BaseEnsemble model by calling fit to train all base models in parallel using multiprocessing', 'predict future values from a fitted BaseEnsemble by calling _predict_all with a forecast horizon', 'review the BASE_MODELS dictionary mapping model names to ARIMA, HoltWinters, SARIMA, Prophet, Linear, and Quadratic classes', 'build a KatsEnsemble model to fit multiple forecasting models and aggregate predictions with median or weighted average', 'detect seasonality in time series data using the ACFDetector static method on TimeSeriesData', 'deseasonalize time series data using STL decomposition with additive or multiplicative methods', 'backtest individual ensemble models and compute error metrics like MAPE, RMSE, or MAE for weight calculation', 'aggregate individual model forecasts into a final prediction DataFrame using median or weighted average aggregation', 'create a MedianEnsembleModel with TimeSeriesData and EnsembleParams for univariate time series forecasting', 'predict future values using MedianEnsembleModel predict method with steps and freq kwargs', 'review the MedianEnsembleModel constructor to validate univariate time series input data', 'summarize the MedianEnsembleModel predict method that computes median across base model forecasts', 'test the MedianEnsembleModel forecast output DataFrame containing time and fcst columns', 'create a WeightedAvgEnsemble model with TimeSeriesData and EnsembleParams for univariate time series forecasting', 'predict future values using the WeightedAvgEnsemble model with a specified forecasting horizon and frequency', 'run backtesting on a single model using BackTesterSimple with configurable train test split and error method', 'run parallel backtesting across all ensemble models to compute inverse-error weights for each model', 'review the computed model weights and backtesting errors from the WeightedAvgEnsemble ensemble']
```

Usage

```
{'build_ensemble_forecast': 'build a KatsEnsemble model to fit multiple forecasting models and aggregate predictions with median or weighted average', 'detect_seasonality': 'detect seasonality in time series data using the ACFDetector static method on TimeSeriesData', 'deseasonalize_timeseries': 'deseasonalize time series data using STL decomposition with additive or multiplicative methods', 'backtest_ensemble_models': 'backtest individual ensemble models and compute error metrics like MAPE, RMSE, or MAE for weight calculation', 'aggregate_forecast_results': 'aggregate individual model forecasts into a final prediction DataFrame using median or weighted average aggregation'}
```

## File: facebookresearch_kats/kats/models/ensemble/median_ensemble.py

Prompts

```
['create a BaseModelParams instance with a model name and model parameters for ensemble configuration', 'create an EnsembleParams object with a list of BaseModelParams to configure multiple base models', 'fit a BaseEnsemble model by calling fit to train all base models in parallel using multiprocessing', 'predict future values from a fitted BaseEnsemble by calling _predict_all with a forecast horizon', 'review the BASE_MODELS dictionary mapping model names to ARIMA, HoltWinters, SARIMA, Prophet, Linear, and Quadratic classes', 'build a KatsEnsemble model to fit multiple forecasting models and aggregate predictions with median or weighted average', 'detect seasonality in time series data using the ACFDetector static method on TimeSeriesData', 'deseasonalize time series data using STL decomposition with additive or multiplicative methods', 'backtest individual ensemble models and compute error metrics like MAPE, RMSE, or MAE for weight calculation', 'aggregate individual model forecasts into a final prediction DataFrame using median or weighted average aggregation', 'create a MedianEnsembleModel with TimeSeriesData and EnsembleParams for univariate time series forecasting', 'predict future values using MedianEnsembleModel predict method with steps and freq kwargs', 'review the MedianEnsembleModel constructor to validate univariate time series input data', 'summarize the MedianEnsembleModel predict method that computes median across base model forecasts', 'test the MedianEnsembleModel forecast output DataFrame containing time and fcst columns', 'create a WeightedAvgEnsemble model with TimeSeriesData and EnsembleParams for univariate time series forecasting', 'predict future values using the WeightedAvgEnsemble model with a specified forecasting horizon and frequency', 'run backtesting on a single model using BackTesterSimple with configurable train test split and error method', 'run parallel backtesting across all ensemble models to compute inverse-error weights for each model', 'review the computed model weights and backtesting errors from the WeightedAvgEnsemble ensemble']
```

Usage

```
{'create_MedianEnsembleModel': 'create a MedianEnsembleModel with TimeSeriesData and EnsembleParams for univariate time series forecasting', 'predict_MedianEnsembleModel': 'predict future values using MedianEnsembleModel predict method with steps and freq kwargs', 'review_MedianEnsembleModel_init': 'review the MedianEnsembleModel constructor to validate univariate time series input data', 'summarize_MedianEnsembleModel_predict': 'summarize the MedianEnsembleModel predict method that computes median across base model forecasts', 'test_MedianEnsembleModel_fcst': 'test the MedianEnsembleModel forecast output DataFrame containing time and fcst columns'}
```

## File: facebookresearch_kats/kats/models/ensemble/weighted_avg_ensemble.py

Prompts

```
['create a BaseModelParams instance with a model name and model parameters for ensemble configuration', 'create an EnsembleParams object with a list of BaseModelParams to configure multiple base models', 'fit a BaseEnsemble model by calling fit to train all base models in parallel using multiprocessing', 'predict future values from a fitted BaseEnsemble by calling _predict_all with a forecast horizon', 'review the BASE_MODELS dictionary mapping model names to ARIMA, HoltWinters, SARIMA, Prophet, Linear, and Quadratic classes', 'build a KatsEnsemble model to fit multiple forecasting models and aggregate predictions with median or weighted average', 'detect seasonality in time series data using the ACFDetector static method on TimeSeriesData', 'deseasonalize time series data using STL decomposition with additive or multiplicative methods', 'backtest individual ensemble models and compute error metrics like MAPE, RMSE, or MAE for weight calculation', 'aggregate individual model forecasts into a final prediction DataFrame using median or weighted average aggregation', 'create a MedianEnsembleModel with TimeSeriesData and EnsembleParams for univariate time series forecasting', 'predict future values using MedianEnsembleModel predict method with steps and freq kwargs', 'review the MedianEnsembleModel constructor to validate univariate time series input data', 'summarize the MedianEnsembleModel predict method that computes median across base model forecasts', 'test the MedianEnsembleModel forecast output DataFrame containing time and fcst columns', 'create a WeightedAvgEnsemble model with TimeSeriesData and EnsembleParams for univariate time series forecasting', 'predict future values using the WeightedAvgEnsemble model with a specified forecasting horizon and frequency', 'run backtesting on a single model using BackTesterSimple with configurable train test split and error method', 'run parallel backtesting across all ensemble models to compute inverse-error weights for each model', 'review the computed model weights and backtesting errors from the WeightedAvgEnsemble ensemble']
```

Usage

```
{'create_WeightedAvgEnsemble': 'create a WeightedAvgEnsemble model with TimeSeriesData and EnsembleParams for univariate time series forecasting', 'predict_WeightedAvgEnsemble': 'predict future values using the WeightedAvgEnsemble model with a specified forecasting horizon and frequency', 'run_backtester_single': 'run backtesting on a single model using BackTesterSimple with configurable train test split and error method', 'run_backtester_all': 'run parallel backtesting across all ensemble models to compute inverse-error weights for each model', 'review_WeightedAvgEnsemble_weights': 'review the computed model weights and backtesting errors from the WeightedAvgEnsemble ensemble'}
```

