# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/testing/_internal/opinfo/core.py

Prompts

```
["create an OpInfo dataclass that describes a PyTorch operator's properties, dtypes, and test directives for automated testing", 'test the SampleInput class that represents sample inputs to a PyTorch operator with tensor inputs, args, and kwargs', 'build a ReductionOpInfo for testing reduction operators that reduce dimensions to a single value with consistent API validation', 'test the BinaryUfuncInfo class for universal binary functions that are elementwise with method and inplace variants', 'review the UnaryUfuncInfo class for universal unary functions that are elementwise with domain constraints and NumPy references', 'test the get_supported_dtypes function to determine supported dtypes for a PyTorch operator', 'build dtype dispatch selection using dtypes_dispatch_hint to choose appropriate COMPLETE_DTYPES_DISPATCH or EXTENSIBLE_DTYPE_DISPATCH', 'create a reference_reduction_numpy wrapper that converts PyTorch reduction kwargs to NumPy equivalents', 'create a np_unary_ufunc_integer_promotion_wrapper that handles integer-to-floating point type promotion for NumPy ufuncs', 'test the prod_numpy function that fixes integer overflow by casting to int64 or uint64 before calling np.prod']
```

Usage

```
{'create_OpInfo': "create an OpInfo dataclass that describes a PyTorch operator's properties, dtypes, and test directives for automated testing", 'test_SampleInput': 'test the SampleInput class that represents sample inputs to a PyTorch operator with tensor inputs, args, and kwargs', 'build_ReductionOpInfo': 'build a ReductionOpInfo for testing reduction operators that reduce dimensions to a single value with consistent API validation', 'test_BinaryUfuncInfo': 'test the BinaryUfuncInfo class for universal binary functions that are elementwise with method and inplace variants', 'review_UnaryUfuncInfo': 'review the UnaryUfuncInfo class for universal unary functions that are elementwise with domain constraints and NumPy references'}
```

## File: pytorch_pytorch/torch/testing/_internal/opinfo/utils.py

Prompts

```
["create an OpInfo dataclass that describes a PyTorch operator's properties, dtypes, and test directives for automated testing", 'test the SampleInput class that represents sample inputs to a PyTorch operator with tensor inputs, args, and kwargs', 'build a ReductionOpInfo for testing reduction operators that reduce dimensions to a single value with consistent API validation', 'test the BinaryUfuncInfo class for universal binary functions that are elementwise with method and inplace variants', 'review the UnaryUfuncInfo class for universal unary functions that are elementwise with domain constraints and NumPy references', 'test the get_supported_dtypes function to determine supported dtypes for a PyTorch operator', 'build dtype dispatch selection using dtypes_dispatch_hint to choose appropriate COMPLETE_DTYPES_DISPATCH or EXTENSIBLE_DTYPE_DISPATCH', 'create a reference_reduction_numpy wrapper that converts PyTorch reduction kwargs to NumPy equivalents', 'create a np_unary_ufunc_integer_promotion_wrapper that handles integer-to-floating point type promotion for NumPy ufuncs', 'test the prod_numpy function that fixes integer overflow by casting to int64 or uint64 before calling np.prod']
```

Usage

```
{'test_get_supported_dtypes': 'test the get_supported_dtypes function to determine supported dtypes for a PyTorch operator', 'build_dtypes_dispatch': 'build dtype dispatch selection using dtypes_dispatch_hint to choose appropriate COMPLETE_DTYPES_DISPATCH or EXTENSIBLE_DTYPE_DISPATCH', 'create_reference_reduction_numpy': 'create a reference_reduction_numpy wrapper that converts PyTorch reduction kwargs to NumPy equivalents', 'create_np_unary_ufunc_integer_promotion_wrapper': 'create a np_unary_ufunc_integer_promotion_wrapper that handles integer-to-floating point type promotion for NumPy ufuncs', 'test_prod_numpy': 'test the prod_numpy function that fixes integer overflow by casting to int64 or uint64 before calling np.prod'}
```

