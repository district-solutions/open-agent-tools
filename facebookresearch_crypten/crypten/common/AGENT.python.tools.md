# Agent Python Tools

- repo: facebookresearch/crypten
- repo_uri: https://github.com/facebookresearch/crypten

## File: facebookresearch_crypten/crypten/common/rng.py

Prompts

```
['generate a random tensor of long integers from a signed ring with a configurable ring size', 'generate a random k-bit tensor of long integers with a configurable bit length', 'generate a random ring element tensor using a custom ring size smaller than 2 to the 64th', 'generate a random 32-bit tensor of long integers using the k-bit helper function', 'generate a random ring element tensor on a CUDA device returning a CUDALongTensor', 'safely deserialize a pickled byte string using a restricted allowlist of safe classes', 'register a custom class as safe for deserialization by the RestrictedUnpickler', 'override pickle Unpickler find_class to restrict deserialization to an allowlist of safe classes', 'get the source code lines and file path for a Python object using inspect', 'register a class as safe for deserialization via the RestrictedUnpickler class method', 'check if an input is a Torch tensor or CUDALongTensor using is_tensor', 'check if a tensor is a float type (float16, float32, float64) using is_float_tensor', 'check if a tensor is an int type (uint8, int8, int16, int32, int64) using is_int_tensor', 'check if a tensor elements match specific dtype types using _is_type_tensor', 'review the tensor type-checking helper functions for float, int, and base tensor detection', 'compute the number of overflows and underflows in a list of secret sharing tensors', 'compute Chebyshev series coefficients for approximating a function over a given width and number of terms', 'concatenate a list of tensors along a dimension with CUDALongTensor fallback support', 'stack a list of tensors along a new dimension with CUDALongTensor fallback support', 'compute the input padding tuple for a convolutional gradient given stride, padding, and kernel size']
```

Usage

```
{'generate_random_ring_element': 'generate a random tensor of long integers from a signed ring with a configurable ring size', 'generate_kbit_random_tensor': 'generate a random k-bit tensor of long integers with a configurable bit length', 'generate_random_ring_element_custom_ring': 'generate a random ring element tensor using a custom ring size smaller than 2 to the 64th', 'generate_kbit_random_tensor_32bit': 'generate a random 32-bit tensor of long integers using the k-bit helper function', 'generate_random_ring_element_cuda': 'generate a random ring element tensor on a CUDA device returning a CUDALongTensor'}
```

## File: facebookresearch_crypten/crypten/common/serial.py

Prompts

```
['generate a random tensor of long integers from a signed ring with a configurable ring size', 'generate a random k-bit tensor of long integers with a configurable bit length', 'generate a random ring element tensor using a custom ring size smaller than 2 to the 64th', 'generate a random 32-bit tensor of long integers using the k-bit helper function', 'generate a random ring element tensor on a CUDA device returning a CUDALongTensor', 'safely deserialize a pickled byte string using a restricted allowlist of safe classes', 'register a custom class as safe for deserialization by the RestrictedUnpickler', 'override pickle Unpickler find_class to restrict deserialization to an allowlist of safe classes', 'get the source code lines and file path for a Python object using inspect', 'register a class as safe for deserialization via the RestrictedUnpickler class method', 'check if an input is a Torch tensor or CUDALongTensor using is_tensor', 'check if a tensor is a float type (float16, float32, float64) using is_float_tensor', 'check if a tensor is an int type (uint8, int8, int16, int32, int64) using is_int_tensor', 'check if a tensor elements match specific dtype types using _is_type_tensor', 'review the tensor type-checking helper functions for float, int, and base tensor detection', 'compute the number of overflows and underflows in a list of secret sharing tensors', 'compute Chebyshev series coefficients for approximating a function over a given width and number of terms', 'concatenate a list of tensors along a dimension with CUDALongTensor fallback support', 'stack a list of tensors along a new dimension with CUDALongTensor fallback support', 'compute the input padding tuple for a convolutional gradient given stride, padding, and kernel size']
```

Usage

```
{'restricted_loads': 'safely deserialize a pickled byte string using a restricted allowlist of safe classes', 'register_safe_class': 'register a custom class as safe for deserialization by the RestrictedUnpickler', 'RestrictedUnpickler_find_class': 'override pickle Unpickler find_class to restrict deserialization to an allowlist of safe classes', 'get_source_lines_and_file': 'get the source code lines and file path for a Python object using inspect', 'RestrictedUnpickler_register_safe_class': 'register a class as safe for deserialization via the RestrictedUnpickler class method'}
```

## File: facebookresearch_crypten/crypten/common/tensor_types.py

Prompts

```
['generate a random tensor of long integers from a signed ring with a configurable ring size', 'generate a random k-bit tensor of long integers with a configurable bit length', 'generate a random ring element tensor using a custom ring size smaller than 2 to the 64th', 'generate a random 32-bit tensor of long integers using the k-bit helper function', 'generate a random ring element tensor on a CUDA device returning a CUDALongTensor', 'safely deserialize a pickled byte string using a restricted allowlist of safe classes', 'register a custom class as safe for deserialization by the RestrictedUnpickler', 'override pickle Unpickler find_class to restrict deserialization to an allowlist of safe classes', 'get the source code lines and file path for a Python object using inspect', 'register a class as safe for deserialization via the RestrictedUnpickler class method', 'check if an input is a Torch tensor or CUDALongTensor using is_tensor', 'check if a tensor is a float type (float16, float32, float64) using is_float_tensor', 'check if a tensor is an int type (uint8, int8, int16, int32, int64) using is_int_tensor', 'check if a tensor elements match specific dtype types using _is_type_tensor', 'review the tensor type-checking helper functions for float, int, and base tensor detection', 'compute the number of overflows and underflows in a list of secret sharing tensors', 'compute Chebyshev series coefficients for approximating a function over a given width and number of terms', 'concatenate a list of tensors along a dimension with CUDALongTensor fallback support', 'stack a list of tensors along a new dimension with CUDALongTensor fallback support', 'compute the input padding tuple for a convolutional gradient given stride, padding, and kernel size']
```

Usage

```
{'check_is_tensor': 'check if an input is a Torch tensor or CUDALongTensor using is_tensor', 'check_is_float_tensor': 'check if a tensor is a float type (float16, float32, float64) using is_float_tensor', 'check_is_int_tensor': 'check if a tensor is an int type (uint8, int8, int16, int32, int64) using is_int_tensor', 'check_is_type_tensor': 'check if a tensor elements match specific dtype types using _is_type_tensor', 'review_tensor_type_checking': 'review the tensor type-checking helper functions for float, int, and base tensor detection'}
```

## File: facebookresearch_crypten/crypten/common/util.py

Prompts

```
['generate a random tensor of long integers from a signed ring with a configurable ring size', 'generate a random k-bit tensor of long integers with a configurable bit length', 'generate a random ring element tensor using a custom ring size smaller than 2 to the 64th', 'generate a random 32-bit tensor of long integers using the k-bit helper function', 'generate a random ring element tensor on a CUDA device returning a CUDALongTensor', 'safely deserialize a pickled byte string using a restricted allowlist of safe classes', 'register a custom class as safe for deserialization by the RestrictedUnpickler', 'override pickle Unpickler find_class to restrict deserialization to an allowlist of safe classes', 'get the source code lines and file path for a Python object using inspect', 'register a class as safe for deserialization via the RestrictedUnpickler class method', 'check if an input is a Torch tensor or CUDALongTensor using is_tensor', 'check if a tensor is a float type (float16, float32, float64) using is_float_tensor', 'check if a tensor is an int type (uint8, int8, int16, int32, int64) using is_int_tensor', 'check if a tensor elements match specific dtype types using _is_type_tensor', 'review the tensor type-checking helper functions for float, int, and base tensor detection', 'compute the number of overflows and underflows in a list of secret sharing tensors', 'compute Chebyshev series coefficients for approximating a function over a given width and number of terms', 'concatenate a list of tensors along a dimension with CUDALongTensor fallback support', 'stack a list of tensors along a new dimension with CUDALongTensor fallback support', 'compute the input padding tuple for a convolutional gradient given stride, padding, and kernel size']
```

Usage

```
{'count_wraps_shares': 'compute the number of overflows and underflows in a list of secret sharing tensors', 'compute_chebyshev_series': 'compute Chebyshev series coefficients for approximating a function over a given width and number of terms', 'torch_cat_tensors': 'concatenate a list of tensors along a dimension with CUDALongTensor fallback support', 'torch_stack_tensors': 'stack a list of tensors along a new dimension with CUDALongTensor fallback support', 'grad_input_padding': 'compute the input padding tuple for a convolutional gradient given stride, padding, and kernel size'}
```

