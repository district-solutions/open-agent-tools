# Agent Python Tools

- repo: facebookresearch/kats
- repo_uri: https://github.com/facebookresearch/kats

## File: facebookresearch_kats/kats/models/nowcasting/dynamic_nowcasting.py

Prompts

```
['build a NowcastingModel with TimeSeriesData and NowcastingParams for short-term time series forecasting', 'run feature extraction on the NowcastingModel to compute MOM, ROC, LAG, and MA features', 'fit the NowcastingModel using RandomForestRegressor or LinearRegression on extracted features', 'predict future values using the fitted NowcastingModel with step-ahead nowcasting', 'create NowcastingParams with a step value to configure how many steps ahead to forecast', 'create a return-on-change feature column by comparing values n steps back in a time series DataFrame', 'create MACD, MACD signal, and MACD difference columns from a time series DataFrame using fast and slow EMA periods', 'create a Relative Strength Index column to identify overbought or oversold conditions in a time series', 'create two Bollinger Band columns measuring price volatility relative to a rolling moving average window', 'create a True Strength Index momentum oscillator column using two exponential moving average windows', 'create a python module that uses SimplePickleSerializer to serialize an sklearn model to bytes', 'create a python module that uses SimplePickleSerializer to deserialize bytes back into an sklearn model', 'create a python module that calls serialize_for_zippy to pickle an object for Zippydb storage', 'create a python module that calls deserialize_from_zippy to restore a pickled object from Zippydb bytes', 'review the SimplePickleSerializer _jdefault method to understand how sets, bools, ints, and floats are converted', 'extract ROC and LAG features from time series data using the feature_extraction method', 'save the trained sklearn model as bytes or load it back using save_model and load_model', 'build a NowcastingPlusModel with TimeSeriesData and NowcastingParams for short-term time series forecasting', 'fit a NowcastingPlusModel using LassoCV regression on extracted features and labels', 'predict future time series values using a fitted NowcastingPlusModel with polynomial trend adjustment', 'save a fitted NowcastingPlusModel to bytes or load it back from serialized bytes']
```

Usage

```
{'build_nowcasting_model': 'build a NowcastingModel with TimeSeriesData and NowcastingParams for short-term time series forecasting', 'run_feature_extraction': 'run feature extraction on the NowcastingModel to compute MOM, ROC, LAG, and MA features', 'fit_nowcasting_model': 'fit the NowcastingModel using RandomForestRegressor or LinearRegression on extracted features', 'predict_nowcasting': 'predict future values using the fitted NowcastingModel with step-ahead nowcasting', 'create_nowcasting_params': 'create NowcastingParams with a step value to configure how many steps ahead to forecast'}
```

## File: facebookresearch_kats/kats/models/nowcasting/feature_extraction.py

Prompts

```
['build a NowcastingModel with TimeSeriesData and NowcastingParams for short-term time series forecasting', 'run feature extraction on the NowcastingModel to compute MOM, ROC, LAG, and MA features', 'fit the NowcastingModel using RandomForestRegressor or LinearRegression on extracted features', 'predict future values using the fitted NowcastingModel with step-ahead nowcasting', 'create NowcastingParams with a step value to configure how many steps ahead to forecast', 'create a return-on-change feature column by comparing values n steps back in a time series DataFrame', 'create MACD, MACD signal, and MACD difference columns from a time series DataFrame using fast and slow EMA periods', 'create a Relative Strength Index column to identify overbought or oversold conditions in a time series', 'create two Bollinger Band columns measuring price volatility relative to a rolling moving average window', 'create a True Strength Index momentum oscillator column using two exponential moving average windows', 'create a python module that uses SimplePickleSerializer to serialize an sklearn model to bytes', 'create a python module that uses SimplePickleSerializer to deserialize bytes back into an sklearn model', 'create a python module that calls serialize_for_zippy to pickle an object for Zippydb storage', 'create a python module that calls deserialize_from_zippy to restore a pickled object from Zippydb bytes', 'review the SimplePickleSerializer _jdefault method to understand how sets, bools, ints, and floats are converted', 'extract ROC and LAG features from time series data using the feature_extraction method', 'save the trained sklearn model as bytes or load it back using save_model and load_model', 'build a NowcastingPlusModel with TimeSeriesData and NowcastingParams for short-term time series forecasting', 'fit a NowcastingPlusModel using LassoCV regression on extracted features and labels', 'predict future time series values using a fitted NowcastingPlusModel with polynomial trend adjustment', 'save a fitted NowcastingPlusModel to bytes or load it back from serialized bytes']
```

Usage

```
{'create_ROC_feature': 'create a return-on-change feature column by comparing values n steps back in a time series DataFrame', 'create_MACD_feature': 'create MACD, MACD signal, and MACD difference columns from a time series DataFrame using fast and slow EMA periods', 'create_RSI_feature': 'create a Relative Strength Index column to identify overbought or oversold conditions in a time series', 'create_BollingerBands_feature': 'create two Bollinger Band columns measuring price volatility relative to a rolling moving average window', 'create_TSI_feature': 'create a True Strength Index momentum oscillator column using two exponential moving average windows'}
```

## File: facebookresearch_kats/kats/models/nowcasting/model_io.py

Prompts

```
['build a NowcastingModel with TimeSeriesData and NowcastingParams for short-term time series forecasting', 'run feature extraction on the NowcastingModel to compute MOM, ROC, LAG, and MA features', 'fit the NowcastingModel using RandomForestRegressor or LinearRegression on extracted features', 'predict future values using the fitted NowcastingModel with step-ahead nowcasting', 'create NowcastingParams with a step value to configure how many steps ahead to forecast', 'create a return-on-change feature column by comparing values n steps back in a time series DataFrame', 'create MACD, MACD signal, and MACD difference columns from a time series DataFrame using fast and slow EMA periods', 'create a Relative Strength Index column to identify overbought or oversold conditions in a time series', 'create two Bollinger Band columns measuring price volatility relative to a rolling moving average window', 'create a True Strength Index momentum oscillator column using two exponential moving average windows', 'create a python module that uses SimplePickleSerializer to serialize an sklearn model to bytes', 'create a python module that uses SimplePickleSerializer to deserialize bytes back into an sklearn model', 'create a python module that calls serialize_for_zippy to pickle an object for Zippydb storage', 'create a python module that calls deserialize_from_zippy to restore a pickled object from Zippydb bytes', 'review the SimplePickleSerializer _jdefault method to understand how sets, bools, ints, and floats are converted', 'extract ROC and LAG features from time series data using the feature_extraction method', 'save the trained sklearn model as bytes or load it back using save_model and load_model', 'build a NowcastingPlusModel with TimeSeriesData and NowcastingParams for short-term time series forecasting', 'fit a NowcastingPlusModel using LassoCV regression on extracted features and labels', 'predict future time series values using a fitted NowcastingPlusModel with polynomial trend adjustment', 'save a fitted NowcastingPlusModel to bytes or load it back from serialized bytes']
```

Usage

```
{'serialize_model_with_pickle': 'create a python module that uses SimplePickleSerializer to serialize an sklearn model to bytes', 'deserialize_model_from_pickle': 'create a python module that uses SimplePickleSerializer to deserialize bytes back into an sklearn model', 'serialize_for_zippy': 'create a python module that calls serialize_for_zippy to pickle an object for Zippydb storage', 'deserialize_from_zippy': 'create a python module that calls deserialize_from_zippy to restore a pickled object from Zippydb bytes', 'review_SimplePickleSerializer_jdefault': 'review the SimplePickleSerializer _jdefault method to understand how sets, bools, ints, and floats are converted'}
```

## File: facebookresearch_kats/kats/models/nowcasting/nowcasting.py

Prompts

```
['build a NowcastingModel with TimeSeriesData and NowcastingParams for short-term time series forecasting', 'run feature extraction on the NowcastingModel to compute MOM, ROC, LAG, and MA features', 'fit the NowcastingModel using RandomForestRegressor or LinearRegression on extracted features', 'predict future values using the fitted NowcastingModel with step-ahead nowcasting', 'create NowcastingParams with a step value to configure how many steps ahead to forecast', 'create a return-on-change feature column by comparing values n steps back in a time series DataFrame', 'create MACD, MACD signal, and MACD difference columns from a time series DataFrame using fast and slow EMA periods', 'create a Relative Strength Index column to identify overbought or oversold conditions in a time series', 'create two Bollinger Band columns measuring price volatility relative to a rolling moving average window', 'create a True Strength Index momentum oscillator column using two exponential moving average windows', 'create a python module that uses SimplePickleSerializer to serialize an sklearn model to bytes', 'create a python module that uses SimplePickleSerializer to deserialize bytes back into an sklearn model', 'create a python module that calls serialize_for_zippy to pickle an object for Zippydb storage', 'create a python module that calls deserialize_from_zippy to restore a pickled object from Zippydb bytes', 'review the SimplePickleSerializer _jdefault method to understand how sets, bools, ints, and floats are converted', 'extract ROC and LAG features from time series data using the feature_extraction method', 'save the trained sklearn model as bytes or load it back using save_model and load_model', 'build a NowcastingPlusModel with TimeSeriesData and NowcastingParams for short-term time series forecasting', 'fit a NowcastingPlusModel using LassoCV regression on extracted features and labels', 'predict future time series values using a fitted NowcastingPlusModel with polynomial trend adjustment', 'save a fitted NowcastingPlusModel to bytes or load it back from serialized bytes']
```

Usage

```
{'build_nowcasting_model': 'build a NowcastingModel with TimeSeriesData and NowcastingParams to perform short-term time series forecasting', 'extract_features_nowcasting': 'extract ROC and LAG features from time series data using the feature_extraction method', 'fit_nowcasting_model': 'fit a GradientBoostingRegressor model on extracted features and labels using the fit method', 'predict_nowcasting': 'predict future time series values step ahead using the predict method with an optional external model', 'save_load_nowcasting_model': 'save the trained sklearn model as bytes or load it back using save_model and load_model'}
```

## File: facebookresearch_kats/kats/models/nowcasting/nowcastingplus.py

Prompts

```
['build a NowcastingModel with TimeSeriesData and NowcastingParams for short-term time series forecasting', 'run feature extraction on the NowcastingModel to compute MOM, ROC, LAG, and MA features', 'fit the NowcastingModel using RandomForestRegressor or LinearRegression on extracted features', 'predict future values using the fitted NowcastingModel with step-ahead nowcasting', 'create NowcastingParams with a step value to configure how many steps ahead to forecast', 'create a return-on-change feature column by comparing values n steps back in a time series DataFrame', 'create MACD, MACD signal, and MACD difference columns from a time series DataFrame using fast and slow EMA periods', 'create a Relative Strength Index column to identify overbought or oversold conditions in a time series', 'create two Bollinger Band columns measuring price volatility relative to a rolling moving average window', 'create a True Strength Index momentum oscillator column using two exponential moving average windows', 'create a python module that uses SimplePickleSerializer to serialize an sklearn model to bytes', 'create a python module that uses SimplePickleSerializer to deserialize bytes back into an sklearn model', 'create a python module that calls serialize_for_zippy to pickle an object for Zippydb storage', 'create a python module that calls deserialize_from_zippy to restore a pickled object from Zippydb bytes', 'review the SimplePickleSerializer _jdefault method to understand how sets, bools, ints, and floats are converted', 'extract ROC and LAG features from time series data using the feature_extraction method', 'save the trained sklearn model as bytes or load it back using save_model and load_model', 'build a NowcastingPlusModel with TimeSeriesData and NowcastingParams for short-term time series forecasting', 'fit a NowcastingPlusModel using LassoCV regression on extracted features and labels', 'predict future time series values using a fitted NowcastingPlusModel with polynomial trend adjustment', 'save a fitted NowcastingPlusModel to bytes or load it back from serialized bytes']
```

Usage

```
{'build_nowcastingplus_model': 'build a NowcastingPlusModel with TimeSeriesData and NowcastingParams for short-term time series forecasting', 'run_feature_extraction': 'run feature extraction on NowcastingPlusModel to compute MOM, ROC, LAG, and MA features', 'fit_nowcastingplus_model': 'fit a NowcastingPlusModel using LassoCV regression on extracted features and labels', 'predict_nowcastingplus_forecast': 'predict future time series values using a fitted NowcastingPlusModel with polynomial trend adjustment', 'save_load_nowcastingplus_model': 'save a fitted NowcastingPlusModel to bytes or load it back from serialized bytes'}
```

