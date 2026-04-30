# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/autoformer/configuration_autoformer.py

Prompts

```
['create an AutoformerConfig instance for time series forecasting with default settings', 'build an AutoformerConfig with custom prediction_length, context_length, and distribution_output parameters', 'validate the AutoformerConfig architecture ensuring cardinality and embedding_dimension match num_static_categorical_features', 'review the AutoformerConfig class properties including d_model, encoder_layers, and lags_sequence', 'summarize the AutoformerConfig __post_init__ method that sets context_length, lags_sequence, and feature_size', 'create an Autoformer model for autoregressive time series forecasting with trend and seasonality decomposition', 'run time series prediction using AutoformerForPrediction with past values, time features, and observed masks', 'build lagged subsequences from a time series sequence using configurable lags for extra context', 'test the Autoformer autocorrelation attention mechanism that discovers period-based dependencies via FFT', 'summarize how AutoformerSeriesDecompositionLayer splits a time series into seasonal and trend components']
```

Usage

```
{'create_autoformer_config': 'create an AutoformerConfig instance for time series forecasting with default settings', 'build_autoformer_config_custom': 'build an AutoformerConfig with custom prediction_length, context_length, and distribution_output parameters', 'validate_autoformer_architecture': 'validate the AutoformerConfig architecture ensuring cardinality and embedding_dimension match num_static_categorical_features', 'review_autoformer_config_properties': 'review the AutoformerConfig class properties including d_model, encoder_layers, and lags_sequence', 'summarize_autoformer_post_init': 'summarize the AutoformerConfig __post_init__ method that sets context_length, lags_sequence, and feature_size'}
```

## File: huggingface_transformers/src/transformers/models/autoformer/modeling_autoformer.py

Prompts

```
['create an AutoformerConfig instance for time series forecasting with default settings', 'build an AutoformerConfig with custom prediction_length, context_length, and distribution_output parameters', 'validate the AutoformerConfig architecture ensuring cardinality and embedding_dimension match num_static_categorical_features', 'review the AutoformerConfig class properties including d_model, encoder_layers, and lags_sequence', 'summarize the AutoformerConfig __post_init__ method that sets context_length, lags_sequence, and feature_size', 'create an Autoformer model for autoregressive time series forecasting with trend and seasonality decomposition', 'run time series prediction using AutoformerForPrediction with past values, time features, and observed masks', 'build lagged subsequences from a time series sequence using configurable lags for extra context', 'test the Autoformer autocorrelation attention mechanism that discovers period-based dependencies via FFT', 'summarize how AutoformerSeriesDecompositionLayer splits a time series into seasonal and trend components']
```

Usage

```
{'create_autoregressive_time_series_model': 'create an Autoformer model for autoregressive time series forecasting with trend and seasonality decomposition', 'run_time_series_prediction': 'run time series prediction using AutoformerForPrediction with past values, time features, and observed masks', 'build_lagged_subsequence_extractor': 'build lagged subsequences from a time series sequence using configurable lags for extra context', 'test_auto_correlation_attention': 'test the Autoformer autocorrelation attention mechanism that discovers period-based dependencies via FFT', 'summarize_series_decomposition': 'summarize how AutoformerSeriesDecompositionLayer splits a time series into seasonal and trend components'}
```

