# Agent Python Tools

- repo: facebookresearch/algonauts-2025
- repo_uri: https://github.com/facebookresearch/algonauts-2025

## File: facebookresearch_algonauts-2025/modeling_utils/modeling_utils/models/common.py

Prompts

```
['build a SubjectLayers module with per-subject weight matrices for subject-specific linear transformations', 'build a LayerScale module that applies learnable per-channel scaling with configurable initialization and boost', 'build an MlpConfig pydantic model to configure and construct MLPs with norm and activation options', 'build a Mean module that computes the mean along a specified dimension with optional keepdim', 'review the MlpConfig build method to understand how it constructs MLP or Linear layers from config', 'build an FmriMlp model with a given input dimension, output dimension, and FmriMlpConfig', 'build an FmriMlp model from an FmriMlpConfig using the build method with n_in_channels and n_outputs', 'run a forward pass through the FmriMlp model with input tensor and optional subject IDs', 'review the FmriMlpConfig pydantic model to understand hyperparameters like hidden size, n_blocks, and time_agg options', 'test the FmriMlp model with different time aggregation strategies including in_mean, in_linear, out_mean, and out_linear', 'build a TransformerEncoderConfig with custom heads and depth then call build to create an x_transformers Encoder module', 'build a TransformerEncoderConfig with causal set to True then call build to create an x_transformers Decoder module', 'configure a TransformerEncoderConfig with flash attention, rotary embeddings, and custom dropout values', 'configure a TransformerEncoderConfig to use RMSNorm or ScaleNorm for layer normalization', 'validate that a TransformerEncoderConfig dim is divisible by heads and at least 256 before building']
```

Usage

```
{'build_SubjectLayers': 'build a SubjectLayers module with per-subject weight matrices for subject-specific linear transformations', 'build_LayerScale': 'build a LayerScale module that applies learnable per-channel scaling with configurable initialization and boost', 'build_MlpConfig': 'build an MlpConfig pydantic model to configure and construct MLPs with norm and activation options', 'build_Mean': 'build a Mean module that computes the mean along a specified dimension with optional keepdim', 'review_MlpConfig_build': 'review the MlpConfig build method to understand how it constructs MLP or Linear layers from config'}
```

## File: facebookresearch_algonauts-2025/modeling_utils/modeling_utils/models/fmri_mlp.py

Prompts

```
['build a SubjectLayers module with per-subject weight matrices for subject-specific linear transformations', 'build a LayerScale module that applies learnable per-channel scaling with configurable initialization and boost', 'build an MlpConfig pydantic model to configure and construct MLPs with norm and activation options', 'build a Mean module that computes the mean along a specified dimension with optional keepdim', 'review the MlpConfig build method to understand how it constructs MLP or Linear layers from config', 'build an FmriMlp model with a given input dimension, output dimension, and FmriMlpConfig', 'build an FmriMlp model from an FmriMlpConfig using the build method with n_in_channels and n_outputs', 'run a forward pass through the FmriMlp model with input tensor and optional subject IDs', 'review the FmriMlpConfig pydantic model to understand hyperparameters like hidden size, n_blocks, and time_agg options', 'test the FmriMlp model with different time aggregation strategies including in_mean, in_linear, out_mean, and out_linear', 'build a TransformerEncoderConfig with custom heads and depth then call build to create an x_transformers Encoder module', 'build a TransformerEncoderConfig with causal set to True then call build to create an x_transformers Decoder module', 'configure a TransformerEncoderConfig with flash attention, rotary embeddings, and custom dropout values', 'configure a TransformerEncoderConfig to use RMSNorm or ScaleNorm for layer normalization', 'validate that a TransformerEncoderConfig dim is divisible by heads and at least 256 before building']
```

Usage

```
{'build_fmri_mlp_model': 'build an FmriMlp model with a given input dimension, output dimension, and FmriMlpConfig', 'build_fmri_mlp_from_config': 'build an FmriMlp model from an FmriMlpConfig using the build method with n_in_channels and n_outputs', 'run_fmri_mlp_forward': 'run a forward pass through the FmriMlp model with input tensor and optional subject IDs', 'review_fmri_mlp_config': 'review the FmriMlpConfig pydantic model to understand hyperparameters like hidden size, n_blocks, and time_agg options', 'test_fmri_mlp_time_aggregation': 'test the FmriMlp model with different time aggregation strategies including in_mean, in_linear, out_mean, and out_linear'}
```

## File: facebookresearch_algonauts-2025/modeling_utils/modeling_utils/models/transformer.py

Prompts

```
['build a SubjectLayers module with per-subject weight matrices for subject-specific linear transformations', 'build a LayerScale module that applies learnable per-channel scaling with configurable initialization and boost', 'build an MlpConfig pydantic model to configure and construct MLPs with norm and activation options', 'build a Mean module that computes the mean along a specified dimension with optional keepdim', 'review the MlpConfig build method to understand how it constructs MLP or Linear layers from config', 'build an FmriMlp model with a given input dimension, output dimension, and FmriMlpConfig', 'build an FmriMlp model from an FmriMlpConfig using the build method with n_in_channels and n_outputs', 'run a forward pass through the FmriMlp model with input tensor and optional subject IDs', 'review the FmriMlpConfig pydantic model to understand hyperparameters like hidden size, n_blocks, and time_agg options', 'test the FmriMlp model with different time aggregation strategies including in_mean, in_linear, out_mean, and out_linear', 'build a TransformerEncoderConfig with custom heads and depth then call build to create an x_transformers Encoder module', 'build a TransformerEncoderConfig with causal set to True then call build to create an x_transformers Decoder module', 'configure a TransformerEncoderConfig with flash attention, rotary embeddings, and custom dropout values', 'configure a TransformerEncoderConfig to use RMSNorm or ScaleNorm for layer normalization', 'validate that a TransformerEncoderConfig dim is divisible by heads and at least 256 before building']
```

Usage

```
{'build_transformer_encoder': 'build a TransformerEncoderConfig with custom heads and depth then call build to create an x_transformers Encoder module', 'build_transformer_decoder': 'build a TransformerEncoderConfig with causal set to True then call build to create an x_transformers Decoder module', 'configure_attention_options': 'configure a TransformerEncoderConfig with flash attention, rotary embeddings, and custom dropout values', 'configure_normalization_options': 'configure a TransformerEncoderConfig to use RMSNorm or ScaleNorm for layer normalization', 'validate_transformer_config': 'validate that a TransformerEncoderConfig dim is divisible by heads and at least 256 before building'}
```

