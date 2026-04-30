# Agent Python Tools

- repo: huggingface/transformers
- repo_uri: https://github.com/huggingface/transformers.git

## File: huggingface_transformers/src/transformers/models/timesfm/convert_timesfm_orignal_to_hf.py

Prompts

```
['build a Hugging Face TimesFm model from the original TimesFm checkpoint weights', 'convert the TimesFm 2.0 500m checkpoint to Hugging Face Transformers format', 'test that the converted TimesFm model produces outputs matching the original model', 'compare point and quantile forecast outputs between original and converted TimesFm models', 'run the TimesFm conversion script with a custom output directory and Hugging Face repo ID', 'create a TimesFmModel instance for time series feature extraction with patch-based encoding', 'run TimesFmModelForPrediction to generate quantile and mean forecasts from historical time series data', 'build a TimesFmAttention layer with per-dim query scaling and configurable causal masking', 'test the masked mean and standard deviation computation for patch-normalized time series inputs', 'sumstand the TimesFmDecoderLayer transformer block with RMSNorm, attention, and residual MLP', 'create a TimesFmModelForPrediction instance for quantile and mean time series forecasting', 'build a forward pass through the TimesFmModel encoder with past values, padding, and frequency inputs', 'run time series forecasting with TimesFmModelForPrediction returning mean and quantile predictions', 'test the _timesfm_masked_mean_std method that computes masked mean and standard deviation over time series patches', 'review the TimesFmAttention class with per-dim query scaling and causal attention mask generation']
```

Usage

```
{'build_timesfm_hf_model': 'build a Hugging Face TimesFm model from the original TimesFm checkpoint weights', 'convert_timesfm_checkpoint': 'convert the TimesFm 2.0 500m checkpoint to Hugging Face Transformers format', 'test_timesfm_output_match': 'test that the converted TimesFm model produces outputs matching the original model', 'compare_timesfm_outputs': 'compare point and quantile forecast outputs between original and converted TimesFm models', 'run_timesfm_conversion': 'run the TimesFm conversion script with a custom output directory and Hugging Face repo ID'}
```

## File: huggingface_transformers/src/transformers/models/timesfm/modeling_timesfm.py

Prompts

```
['build a Hugging Face TimesFm model from the original TimesFm checkpoint weights', 'convert the TimesFm 2.0 500m checkpoint to Hugging Face Transformers format', 'test that the converted TimesFm model produces outputs matching the original model', 'compare point and quantile forecast outputs between original and converted TimesFm models', 'run the TimesFm conversion script with a custom output directory and Hugging Face repo ID', 'create a TimesFmModel instance for time series feature extraction with patch-based encoding', 'run TimesFmModelForPrediction to generate quantile and mean forecasts from historical time series data', 'build a TimesFmAttention layer with per-dim query scaling and configurable causal masking', 'test the masked mean and standard deviation computation for patch-normalized time series inputs', 'sumstand the TimesFmDecoderLayer transformer block with RMSNorm, attention, and residual MLP', 'create a TimesFmModelForPrediction instance for quantile and mean time series forecasting', 'build a forward pass through the TimesFmModel encoder with past values, padding, and frequency inputs', 'run time series forecasting with TimesFmModelForPrediction returning mean and quantile predictions', 'test the _timesfm_masked_mean_std method that computes masked mean and standard deviation over time series patches', 'review the TimesFmAttention class with per-dim query scaling and causal attention mask generation']
```

Usage

```
{'create_timesfm_model': 'create a TimesFmModel instance for time series feature extraction with patch-based encoding', 'run_timesfm_prediction': 'run TimesFmModelForPrediction to generate quantile and mean forecasts from historical time series data', 'build_timesfm_attention': 'build a TimesFmAttention layer with per-dim query scaling and configurable causal masking', 'test_timesfm_normalization': 'test the masked mean and standard deviation computation for patch-normalized time series inputs', 'summarize_timesfm_decoder': 'sumstand the TimesFmDecoderLayer transformer block with RMSNorm, attention, and residual MLP'}
```

## File: huggingface_transformers/src/transformers/models/timesfm/modular_timesfm.py

Prompts

```
['build a Hugging Face TimesFm model from the original TimesFm checkpoint weights', 'convert the TimesFm 2.0 500m checkpoint to Hugging Face Transformers format', 'test that the converted TimesFm model produces outputs matching the original model', 'compare point and quantile forecast outputs between original and converted TimesFm models', 'run the TimesFm conversion script with a custom output directory and Hugging Face repo ID', 'create a TimesFmModel instance for time series feature extraction with patch-based encoding', 'run TimesFmModelForPrediction to generate quantile and mean forecasts from historical time series data', 'build a TimesFmAttention layer with per-dim query scaling and configurable causal masking', 'test the masked mean and standard deviation computation for patch-normalized time series inputs', 'sumstand the TimesFmDecoderLayer transformer block with RMSNorm, attention, and residual MLP', 'create a TimesFmModelForPrediction instance for quantile and mean time series forecasting', 'build a forward pass through the TimesFmModel encoder with past values, padding, and frequency inputs', 'run time series forecasting with TimesFmModelForPrediction returning mean and quantile predictions', 'test the _timesfm_masked_mean_std method that computes masked mean and standard deviation over time series patches', 'review the TimesFmAttention class with per-dim query scaling and causal attention mask generation']
```

Usage

```
{'create_timesfm_model_for_prediction': 'create a TimesFmModelForPrediction instance for quantile and mean time series forecasting', 'build_timesfm_model_forward_pass': 'build a forward pass through the TimesFmModel encoder with past values, padding, and frequency inputs', 'run_timesfm_forecast_with_quantiles': 'run time series forecasting with TimesFmModelForPrediction returning mean and quantile predictions', 'test_timesfm_masked_mean_std': 'test the _timesfm_masked_mean_std method that computes masked mean and standard deviation over time series patches', 'review_timesfm_attention_scaling': 'review the TimesFmAttention class with per-dim query scaling and causal attention mask generation'}
```

