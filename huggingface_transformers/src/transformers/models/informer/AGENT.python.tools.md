# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/informer/configuration_informer.py

Prompts

```
['create an InformerConfig instance with prediction_length for time series forecasting', 'build an InformerModel from an InformerConfig for encoder-decoder time series prediction', 'validate InformerConfig cardinality and embedding_dimension match num_static_categorical_features', 'configure InformerConfig with prob or full attention type and sampling factor', 'set InformerConfig input_size, lags_sequence, and scaling for multivariate time series', 'create an InformerForPrediction model for probabilistic time-series forecasting with past and future values', 'build an InformerModel with encoder-decoder architecture for seq2seq time-series prediction', 'run greedy sequence generation from InformerForPrediction to sample future time-series values', 'test the InformerProbSparseAttention module that selects active queries for sparse transformer attention', 'review InformerStdScaler, InformerMeanScaler, and InformerNOPScaler for time-series normalization', 'create an InformerModel instance with InformerConfig for time series forecasting', 'create an InformerForPrediction instance for probabilistic time series prediction with configurable distributions', 'build an InformerProbSparseAttention module with probabilistic sparse attention to reduce quadratic complexity', 'build an InformerEncoder with optional distillation conv layers for efficient long-sequence encoding', 'build an InformerDecoder with cross-attention support for autoregressive time series generation']
```

Usage

```
{'create_informer_config': 'create an InformerConfig instance with prediction_length for time series forecasting', 'build_informer_model': 'build an InformerModel from an InformerConfig for encoder-decoder time series prediction', 'validate_informer_architecture': 'validate InformerConfig cardinality and embedding_dimension match num_static_categorical_features', 'configure_informer_attention': 'configure InformerConfig with prob or full attention type and sampling factor', 'set_informer_feature_sizes': 'set InformerConfig input_size, lags_sequence, and scaling for multivariate time series'}
```

## File: huggingface_transformers/src/transformers/models/informer/modeling_informer.py

Prompts

```
['create an InformerConfig instance with prediction_length for time series forecasting', 'build an InformerModel from an InformerConfig for encoder-decoder time series prediction', 'validate InformerConfig cardinality and embedding_dimension match num_static_categorical_features', 'configure InformerConfig with prob or full attention type and sampling factor', 'set InformerConfig input_size, lags_sequence, and scaling for multivariate time series', 'create an InformerForPrediction model for probabilistic time-series forecasting with past and future values', 'build an InformerModel with encoder-decoder architecture for seq2seq time-series prediction', 'run greedy sequence generation from InformerForPrediction to sample future time-series values', 'test the InformerProbSparseAttention module that selects active queries for sparse transformer attention', 'review InformerStdScaler, InformerMeanScaler, and InformerNOPScaler for time-series normalization', 'create an InformerModel instance with InformerConfig for time series forecasting', 'create an InformerForPrediction instance for probabilistic time series prediction with configurable distributions', 'build an InformerProbSparseAttention module with probabilistic sparse attention to reduce quadratic complexity', 'build an InformerEncoder with optional distillation conv layers for efficient long-sequence encoding', 'build an InformerDecoder with cross-attention support for autoregressive time series generation']
```

Usage

```
{'create_informer_prediction_model': 'create an InformerForPrediction model for probabilistic time-series forecasting with past and future values', 'build_informer_encoder_decoder': 'build an InformerModel with encoder-decoder architecture for seq2seq time-series prediction', 'run_informer_generate': 'run greedy sequence generation from InformerForPrediction to sample future time-series values', 'test_prob_sparse_attention': 'test the InformerProbSparseAttention module that selects active queries for sparse transformer attention', 'review_scaler_normalization': 'review InformerStdScaler, InformerMeanScaler, and InformerNOPScaler for time-series normalization'}
```

## File: huggingface_transformers/src/transformers/models/informer/modular_informer.py

Prompts

```
['create an InformerConfig instance with prediction_length for time series forecasting', 'build an InformerModel from an InformerConfig for encoder-decoder time series prediction', 'validate InformerConfig cardinality and embedding_dimension match num_static_categorical_features', 'configure InformerConfig with prob or full attention type and sampling factor', 'set InformerConfig input_size, lags_sequence, and scaling for multivariate time series', 'create an InformerForPrediction model for probabilistic time-series forecasting with past and future values', 'build an InformerModel with encoder-decoder architecture for seq2seq time-series prediction', 'run greedy sequence generation from InformerForPrediction to sample future time-series values', 'test the InformerProbSparseAttention module that selects active queries for sparse transformer attention', 'review InformerStdScaler, InformerMeanScaler, and InformerNOPScaler for time-series normalization', 'create an InformerModel instance with InformerConfig for time series forecasting', 'create an InformerForPrediction instance for probabilistic time series prediction with configurable distributions', 'build an InformerProbSparseAttention module with probabilistic sparse attention to reduce quadratic complexity', 'build an InformerEncoder with optional distillation conv layers for efficient long-sequence encoding', 'build an InformerDecoder with cross-attention support for autoregressive time series generation']
```

Usage

```
{'create_informer_model': 'create an InformerModel instance with InformerConfig for time series forecasting', 'create_informer_for_prediction': 'create an InformerForPrediction instance for probabilistic time series prediction with configurable distributions', 'build_prob_sparse_attention': 'build an InformerProbSparseAttention module with probabilistic sparse attention to reduce quadratic complexity', 'build_informer_encoder': 'build an InformerEncoder with optional distillation conv layers for efficient long-sequence encoding', 'build_informer_decoder': 'build an InformerDecoder with cross-attention support for autoregressive time series generation'}
```

