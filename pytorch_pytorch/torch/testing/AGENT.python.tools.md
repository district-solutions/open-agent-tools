# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/testing/_comparison.py

Prompts

```
['test torch.testing.assert_close to verify two tensors are numerically close within tolerance', 'test torch.testing.assert_close to verify two Python scalars are numerically close within tolerance', 'test torch.testing.assert_close to verify nested sequences of tensors and scalars are elementwise close', 'test torch.testing.assert_close to verify quantized tensors are close via dequantized comparison', 'test torch.testing.assert_close to verify sparse COO and CSR tensors are close with index equality checks', 'create a tensor with given shape, dtype, device, and uniform random values in a specified range', 'create an integral tensor with random values using make_tensor with dtype and device', 'create a complex tensor with random values using make_tensor for complex dtypes', 'create a tensor with make_tensor excluding zero values by replacing them with dtype-specific small positive values', 'create a noncontiguous tensor with make_tensor for testing memory layout behavior']
```

Usage

```
{'test_assert_close_tensors': 'test torch.testing.assert_close to verify two tensors are numerically close within tolerance', 'test_assert_close_scalars': 'test torch.testing.assert_close to verify two Python scalars are numerically close within tolerance', 'test_assert_close_sequences': 'test torch.testing.assert_close to verify nested sequences of tensors and scalars are elementwise close', 'test_assert_close_quantized': 'test torch.testing.assert_close to verify quantized tensors are close via dequantized comparison', 'test_assert_close_sparse': 'test torch.testing.assert_close to verify sparse COO and CSR tensors are close with index equality checks'}
```

## File: pytorch_pytorch/torch/testing/_creation.py

Prompts

```
['test torch.testing.assert_close to verify two tensors are numerically close within tolerance', 'test torch.testing.assert_close to verify two Python scalars are numerically close within tolerance', 'test torch.testing.assert_close to verify nested sequences of tensors and scalars are elementwise close', 'test torch.testing.assert_close to verify quantized tensors are close via dequantized comparison', 'test torch.testing.assert_close to verify sparse COO and CSR tensors are close with index equality checks', 'create a tensor with given shape, dtype, device, and uniform random values in a specified range', 'create an integral tensor with random values using make_tensor with dtype and device', 'create a complex tensor with random values using make_tensor for complex dtypes', 'create a tensor with make_tensor excluding zero values by replacing them with dtype-specific small positive values', 'create a noncontiguous tensor with make_tensor for testing memory layout behavior']
```

Usage

```
{'create_tensor_make_tensor': 'create a tensor with given shape, dtype, device, and uniform random values in a specified range', 'create_tensor_integral_make_tensor': 'create an integral tensor with random values using make_tensor with dtype and device', 'create_tensor_complex_make_tensor': 'create a complex tensor with random values using make_tensor for complex dtypes', 'create_tensor_exclude_zero_make_tensor': 'create a tensor with make_tensor excluding zero values by replacing them with dtype-specific small positive values', 'create_tensor_noncontiguous_make_tensor': 'create a noncontiguous tensor with make_tensor for testing memory layout behavior'}
```

