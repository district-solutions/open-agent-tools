# Agent Python Tools

- repo: huggingface/candle
- repo_uri: https://github.com/huggingface/candle

## File: huggingface_candle/candle-pyo3/tests/native/test_shape.py

Prompts

```
['test that candle tensors return correct absolute shapes when created with rand function', 'test that candle tensor reshape correctly infers dimensions when using negative one', 'test that creating a candle tensor with negative dimensions raises an OverflowError', 'test that creating a candle tensor with non-integer arguments raises a TypeError', 'test that reshaping a candle tensor with invalid dimensions raises a ValueError', 'create a candle Tensor from a scalar, list, or nested list of numbers', 'quantize a candle Tensor to a GGML format like q4_0, q8_0, or q4k', 'index and slice a candle Tensor using integers, slices, ellipsis, or another Tensor', 'add, subtract, multiply, or divide candle Tensors with scalar or broadcasting support', 'move a candle Tensor to a different device or cast it to a different dtype using to', 'test that saving and loading tensors via safetensors preserves values, shapes, and dtypes', 'test that saving and loading quantized tensors via gguf preserves values, shapes, and metadata', 'run save_safetensors to write a dictionary of candle tensors to a safetensors file', 'run load_safetensors to read tensors from a safetensors file and verify their properties', 'run save_gguf to write quantized tensors and metadata to a gguf file']
```

Usage

```
{'test_tensor_shape_validation': 'test that candle tensors return correct absolute shapes when created with rand function', 'test_tensor_reshape_inferred_dim': 'test that candle tensor reshape correctly infers dimensions when using negative one', 'test_rand_overflow_error': 'test that creating a candle tensor with negative dimensions raises an OverflowError', 'test_rand_type_error': 'test that creating a candle tensor with non-integer arguments raises a TypeError', 'test_reshape_value_error': 'test that reshaping a candle tensor with invalid dimensions raises a ValueError'}
```

## File: huggingface_candle/candle-pyo3/tests/native/test_tensor.py

Prompts

```
['test that candle tensors return correct absolute shapes when created with rand function', 'test that candle tensor reshape correctly infers dimensions when using negative one', 'test that creating a candle tensor with negative dimensions raises an OverflowError', 'test that creating a candle tensor with non-integer arguments raises a TypeError', 'test that reshaping a candle tensor with invalid dimensions raises a ValueError', 'create a candle Tensor from a scalar, list, or nested list of numbers', 'quantize a candle Tensor to a GGML format like q4_0, q8_0, or q4k', 'index and slice a candle Tensor using integers, slices, ellipsis, or another Tensor', 'add, subtract, multiply, or divide candle Tensors with scalar or broadcasting support', 'move a candle Tensor to a different device or cast it to a different dtype using to', 'test that saving and loading tensors via safetensors preserves values, shapes, and dtypes', 'test that saving and loading quantized tensors via gguf preserves values, shapes, and metadata', 'run save_safetensors to write a dictionary of candle tensors to a safetensors file', 'run load_safetensors to read tensors from a safetensors file and verify their properties', 'run save_gguf to write quantized tensors and metadata to a gguf file']
```

Usage

```
{'create_tensor_from_data': 'create a candle Tensor from a scalar, list, or nested list of numbers', 'quantize_tensor_ggml': 'quantize a candle Tensor to a GGML format like q4_0, q8_0, or q4k', 'slice_and_index_tensor': 'index and slice a candle Tensor using integers, slices, ellipsis, or another Tensor', 'perform_tensor_arithmetic': 'add, subtract, multiply, or divide candle Tensors with scalar or broadcasting support', 'move_tensor_device_dtype': 'move a candle Tensor to a different device or cast it to a different dtype using to'}
```

## File: huggingface_candle/candle-pyo3/tests/native/test_utils.py

Prompts

```
['test that candle tensors return correct absolute shapes when created with rand function', 'test that candle tensor reshape correctly infers dimensions when using negative one', 'test that creating a candle tensor with negative dimensions raises an OverflowError', 'test that creating a candle tensor with non-integer arguments raises a TypeError', 'test that reshaping a candle tensor with invalid dimensions raises a ValueError', 'create a candle Tensor from a scalar, list, or nested list of numbers', 'quantize a candle Tensor to a GGML format like q4_0, q8_0, or q4k', 'index and slice a candle Tensor using integers, slices, ellipsis, or another Tensor', 'add, subtract, multiply, or divide candle Tensors with scalar or broadcasting support', 'move a candle Tensor to a different device or cast it to a different dtype using to', 'test that saving and loading tensors via safetensors preserves values, shapes, and dtypes', 'test that saving and loading quantized tensors via gguf preserves values, shapes, and metadata', 'run save_safetensors to write a dictionary of candle tensors to a safetensors file', 'run load_safetensors to read tensors from a safetensors file and verify their properties', 'run save_gguf to write quantized tensors and metadata to a gguf file']
```

Usage

```
{'test_safetensors_roundtrip': 'test that saving and loading tensors via safetensors preserves values, shapes, and dtypes', 'test_gguf_roundtrip': 'test that saving and loading quantized tensors via gguf preserves values, shapes, and metadata', 'run_save_safetensors': 'run save_safetensors to write a dictionary of candle tensors to a safetensors file', 'run_load_safetensors': 'run load_safetensors to read tensors from a safetensors file and verify their properties', 'run_save_gguf': 'run save_gguf to write quantized tensors and metadata to a gguf file'}
```

