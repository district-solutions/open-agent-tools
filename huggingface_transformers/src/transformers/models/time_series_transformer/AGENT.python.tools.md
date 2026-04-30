# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/time_series_transformer/configuration_time_series_transformer.py

Prompts

```
['create a TimeSeriesTransformerConfig instance with prediction_length and context_length for time series forecasting', 'initialize a TimeSeriesTransformerModel from a TimeSeriesTransformerConfig with custom encoder and decoder layers', 'validate a TimeSeriesTransformerConfig architecture ensuring cardinality and embedding_dimension match num_static_categorical_features', 'configure a TimeSeriesTransformerConfig for multivariate targets with custom lags_sequence and distribution_output settings', 'access the TimeSeriesTransformerConfig attribute_map mapping hidden_size to d_model for model compatibility', 'create a TimeSeriesTransformerModel with config, scaler, embedder, encoder, and decoder for time series forecasting', 'train a TimeSeriesTransformerForPrediction model using past values, time features, and future values with nll loss', 'generate greedy sample predictions from a trained TimeSeriesTransformerForPrediction model autoregressively over prediction length', 'embed static categorical features using TimeSeriesFeatureEmbedder with cardinalities and embedding dimensions', 'scale time series data using TimeSeriesMeanScaler or TimeSeriesStdScaler with observed indicators for missing values']
```

Usage

```
{'create_config_time_series_transformer': 'create a TimeSeriesTransformerConfig instance with prediction_length and context_length for time series forecasting', 'initialize_model_from_config': 'initialize a TimeSeriesTransformerModel from a TimeSeriesTransformerConfig with custom encoder and decoder layers', 'validate_config_architecture': 'validate a TimeSeriesTransformerConfig architecture ensuring cardinality and embedding_dimension match num_static_categorical_features', 'configure_multivariate_time_series': 'configure a TimeSeriesTransformerConfig for multivariate targets with custom lags_sequence and distribution_output settings', 'access_config_attribute_map': 'access the TimeSeriesTransformerConfig attribute_map mapping hidden_size to d_model for model compatibility'}
```

## File: huggingface_transformers/src/transformers/models/time_series_transformer/modeling_time_series_transformer.py

Prompts

```
['create a TimeSeriesTransformerConfig instance with prediction_length and context_length for time series forecasting', 'initialize a TimeSeriesTransformerModel from a TimeSeriesTransformerConfig with custom encoder and decoder layers', 'validate a TimeSeriesTransformerConfig architecture ensuring cardinality and embedding_dimension match num_static_categorical_features', 'configure a TimeSeriesTransformerConfig for multivariate targets with custom lags_sequence and distribution_output settings', 'access the TimeSeriesTransformerConfig attribute_map mapping hidden_size to d_model for model compatibility', 'create a TimeSeriesTransformerModel with config, scaler, embedder, encoder, and decoder for time series forecasting', 'train a TimeSeriesTransformerForPrediction model using past values, time features, and future values with nll loss', 'generate greedy sample predictions from a trained TimeSeriesTransformerForPrediction model autoregressively over prediction length', 'embed static categorical features using TimeSeriesFeatureEmbedder with cardinalities and embedding dimensions', 'scale time series data using TimeSeriesMeanScaler or TimeSeriesStdScaler with observed indicators for missing values']
```

Usage

```
{'create_time_series_transformer_model': 'create a TimeSeriesTransformerModel with config, scaler, embedder, encoder, and decoder for time series forecasting', 'train_time_series_transformer_for_prediction': 'train a TimeSeriesTransformerForPrediction model using past values, time features, and future values with nll loss', 'generate_time_series_predictions': 'generate greedy sample predictions from a trained TimeSeriesTransformerForPrediction model autoregressively over prediction length', 'embed_static_categorical_features': 'embed static categorical features using TimeSeriesFeatureEmbedder with cardinalities and embedding dimensions', 'scale_time_series_data': 'scale time series data using TimeSeriesMeanScaler or TimeSeriesStdScaler with observed indicators for missing values'}
```

