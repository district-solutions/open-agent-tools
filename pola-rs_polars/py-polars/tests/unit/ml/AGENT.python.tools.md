# Agent Python Tools

- repo: pola-rs/polars
- repo_uri: https://github.com/pola-rs/polars.git

## File: pola-rs_polars/py-polars/tests/unit/ml/test_to_jax.py

Prompts

```
['test converting a polars Series to a JAX array with various integer dtypes and device options', 'test converting a polars DataFrame to a 2D JAX array with default, string, and device parameter variants', 'test converting polars DataFrame columns with fixed-size Array types to JAX arrays including nested 2D arrays', 'test converting a polars DataFrame to a JAX array dictionary with per-column dtypes and type casting', 'test splitting a polars DataFrame into label and features JAX arrays using return_type=dict with label column', 'test converting a polars Series to a PyTorch tensor with correct dtype mapping', 'test converting a polars DataFrame to a PyTorch tensor with shape matching rows and columns', 'test converting a polars DataFrame to a dict of PyTorch tensors keyed by column name', 'test converting a polars DataFrame to a PyTorch Dataset with label and feature support', 'test converting a PyTorch tensor back to a polars DataFrame or Series']
```

Usage

```
{'test_to_jax_from_series': 'test converting a polars Series to a JAX array with various integer dtypes and device options', 'test_to_jax_array': 'test converting a polars DataFrame to a 2D JAX array with default, string, and device parameter variants', 'test_2D_array_cols_to_jax': 'test converting polars DataFrame columns with fixed-size Array types to JAX arrays including nested 2D arrays', 'test_to_jax_dict': 'test converting a polars DataFrame to a JAX array dictionary with per-column dtypes and type casting', 'test_to_jax_feature_label_dict': 'test splitting a polars DataFrame into label and features JAX arrays using return_type=dict with label column'}
```

## File: pola-rs_polars/py-polars/tests/unit/ml/test_torch.py

Prompts

```
['test converting a polars Series to a JAX array with various integer dtypes and device options', 'test converting a polars DataFrame to a 2D JAX array with default, string, and device parameter variants', 'test converting polars DataFrame columns with fixed-size Array types to JAX arrays including nested 2D arrays', 'test converting a polars DataFrame to a JAX array dictionary with per-column dtypes and type casting', 'test splitting a polars DataFrame into label and features JAX arrays using return_type=dict with label column', 'test converting a polars Series to a PyTorch tensor with correct dtype mapping', 'test converting a polars DataFrame to a PyTorch tensor with shape matching rows and columns', 'test converting a polars DataFrame to a dict of PyTorch tensors keyed by column name', 'test converting a polars DataFrame to a PyTorch Dataset with label and feature support', 'test converting a PyTorch tensor back to a polars DataFrame or Series']
```

Usage

```
{'test_series_to_torch': 'test converting a polars Series to a PyTorch tensor with correct dtype mapping', 'test_dataframe_to_torch_tensor': 'test converting a polars DataFrame to a PyTorch tensor with shape matching rows and columns', 'test_dataframe_to_torch_dict': 'test converting a polars DataFrame to a dict of PyTorch tensors keyed by column name', 'test_dataframe_to_torch_dataset': 'test converting a polars DataFrame to a PyTorch Dataset with label and feature support', 'test_from_torch': 'test converting a PyTorch tensor back to a polars DataFrame or Series'}
```

