# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/timesfm2_5/convert_timesfm2_5_original_to_hf.py

Prompts

```
['convert TimesFM 2.5 original checkpoint to Hugging Face Transformers format with safetensors serialization', 'verify converted TimesFM 2.5 model outputs match original model within tolerance thresholds', 'download TimesFM 2.5 checkpoint from Hugging Face Hub and return local safetensors path', 'access nested model attributes with list and tuple indexing support', 'run TimesFM 2.5 model conversion CLI with output directory and optional Hugging Face repo ID', 'create a TimesFm2_5Model instance for time series forecasting with configurable hidden size and layers', 'build a TimesFm2_5ModelForPrediction instance for quantile and mean time series prediction', 'run a forward pass on TimesFm2_5ModelForPrediction to generate point and quantile forecasts', 'test the reversible instance normalization (_revin) for time series normalization and denormalization', 'review the TimesFm2_5Attention class with learnable per-dimension query scaling and rotary embeddings', 'build a TimesFM 2.5 configuration object with patch length, context length, and horizon length parameters', 'test the TimesFM 2.5 model loss computation using MSE and quantile loss on future values']
```

Usage

```
{'convert_timesfm2_5_checkpoint': 'convert TimesFM 2.5 original checkpoint to Hugging Face Transformers format with safetensors serialization', 'verify_timesfm2_5_outputs': 'verify converted TimesFM 2.5 model outputs match original model within tolerance thresholds', 'download_timesfm2_5_checkpoint': 'download TimesFM 2.5 checkpoint from Hugging Face Hub and return local safetensors path', 'access_nested_model_attributes': 'access nested model attributes with list and tuple indexing support', 'run_timesfm2_5_conversion_cli': 'run TimesFM 2.5 model conversion CLI with output directory and optional Hugging Face repo ID'}
```

## File: huggingface_transformers/src/transformers/models/timesfm2_5/modeling_timesfm2_5.py

Prompts

```
['convert TimesFM 2.5 original checkpoint to Hugging Face Transformers format with safetensors serialization', 'verify converted TimesFM 2.5 model outputs match original model within tolerance thresholds', 'download TimesFM 2.5 checkpoint from Hugging Face Hub and return local safetensors path', 'access nested model attributes with list and tuple indexing support', 'run TimesFM 2.5 model conversion CLI with output directory and optional Hugging Face repo ID', 'create a TimesFm2_5Model instance for time series forecasting with configurable hidden size and layers', 'build a TimesFm2_5ModelForPrediction instance for quantile and mean time series prediction', 'run a forward pass on TimesFm2_5ModelForPrediction to generate point and quantile forecasts', 'test the reversible instance normalization (_revin) for time series normalization and denormalization', 'review the TimesFm2_5Attention class with learnable per-dimension query scaling and rotary embeddings', 'build a TimesFM 2.5 configuration object with patch length, context length, and horizon length parameters', 'test the TimesFM 2.5 model loss computation using MSE and quantile loss on future values']
```

Usage

```
{'create_timesfm2_5_model': 'create a TimesFm2_5Model instance for time series forecasting with configurable hidden size and layers', 'build_timesfm2_5_prediction': 'build a TimesFm2_5ModelForPrediction instance for quantile and mean time series prediction', 'run_timesfm2_5_forecast': 'run a forward pass on TimesFm2_5ModelForPrediction to generate point and quantile forecasts', 'test_timesfm2_5_revin': 'test the reversible instance normalization (_revin) for time series normalization and denormalization', 'review_timesfm2_5_attention': 'review the TimesFm2_5Attention class with learnable per-dimension query scaling and rotary embeddings'}
```

## File: huggingface_transformers/src/transformers/models/timesfm2_5/modular_timesfm2_5.py

Prompts

```
['convert TimesFM 2.5 original checkpoint to Hugging Face Transformers format with safetensors serialization', 'verify converted TimesFM 2.5 model outputs match original model within tolerance thresholds', 'download TimesFM 2.5 checkpoint from Hugging Face Hub and return local safetensors path', 'access nested model attributes with list and tuple indexing support', 'run TimesFM 2.5 model conversion CLI with output directory and optional Hugging Face repo ID', 'create a TimesFm2_5Model instance for time series forecasting with configurable hidden size and layers', 'build a TimesFm2_5ModelForPrediction instance for quantile and mean time series prediction', 'run a forward pass on TimesFm2_5ModelForPrediction to generate point and quantile forecasts', 'test the reversible instance normalization (_revin) for time series normalization and denormalization', 'review the TimesFm2_5Attention class with learnable per-dimension query scaling and rotary embeddings', 'build a TimesFM 2.5 configuration object with patch length, context length, and horizon length parameters', 'test the TimesFM 2.5 model loss computation using MSE and quantile loss on future values']
```

Usage

```
{'create_timesfm2_5_model': 'create a TimesFM 2.5 forecasting model for time series prediction with configurable quantiles', 'build_timesfm2_5_config': 'build a TimesFM 2.5 configuration object with patch length, context length, and horizon length parameters', 'run_timesfm2_5_forecast': 'run the TimesFM 2.5 model to produce point and quantile forecasts from past time series values', 'test_timesfm2_5_loss': 'test the TimesFM 2.5 model loss computation using MSE and quantile loss on future values', 'review_timesfm2_5_attention': 'review the TimesFM 2.5 attention mechanism with learnable per-dimension query scaling'}
```

