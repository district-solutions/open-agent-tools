# Agent Python Tools

- repo: huggingface/candle
- repo_uri: https://github.com/huggingface/candle

## File: huggingface_candle/candle-pyo3/tests/bindings/test_linear.py

Prompts

```
['test that a Linear layer can be constructed with input and output dimensions', 'test the Linear layer forward pass with a singular 2D input tensor', 'test the Linear layer forward pass with a batched 3D input tensor', 'test a quantized Linear layer forward pass with q4_0 quantization on a singular input', 'test a quantized Linear layer forward pass with q4_0 quantization on a batched input', 'create a candle.nn.Module subclass that registers tensors and Linear submodules as buffers', 'test that a candle Module can dump and load its state_dict with named tensors', 'test loading quantized Q4_0 tensors into a candle Module via load_state_dict', 'test moving a candle Module to CUDA and back to CPU with cuda and cpu methods', 'test that load_state_dict raises RuntimeError on shape mismatch or missing keys', 'test that two candle Tensors are exactly equal using assert_equal across multiple dtypes', 'test that two candle Tensors are approximately equal using assert_almost_equal with absolute tolerance atol', 'test that two candle Tensors are approximately equal using assert_almost_equal with relative tolerance rtol', 'test creating a candle Tensor and converting it to different dtypes like f32 f64 or u32', 'test that assert_equal raises an AssertionError when comparing two different candle Tensors']
```

Usage

```
{'test_linear_construction': 'test that a Linear layer can be constructed with input and output dimensions', 'test_linear_forward_singular': 'test the Linear layer forward pass with a singular 2D input tensor', 'test_linear_forward_batched': 'test the Linear layer forward pass with a batched 3D input tensor', 'test_quantized_linear_forward_singular': 'test a quantized Linear layer forward pass with q4_0 quantization on a singular input', 'test_quantized_linear_forward_batched': 'test a quantized Linear layer forward pass with q4_0 quantization on a batched input'}
```

## File: huggingface_candle/candle-pyo3/tests/bindings/test_module.py

Prompts

```
['test that a Linear layer can be constructed with input and output dimensions', 'test the Linear layer forward pass with a singular 2D input tensor', 'test the Linear layer forward pass with a batched 3D input tensor', 'test a quantized Linear layer forward pass with q4_0 quantization on a singular input', 'test a quantized Linear layer forward pass with q4_0 quantization on a batched input', 'create a candle.nn.Module subclass that registers tensors and Linear submodules as buffers', 'test that a candle Module can dump and load its state_dict with named tensors', 'test loading quantized Q4_0 tensors into a candle Module via load_state_dict', 'test moving a candle Module to CUDA and back to CPU with cuda and cpu methods', 'test that load_state_dict raises RuntimeError on shape mismatch or missing keys', 'test that two candle Tensors are exactly equal using assert_equal across multiple dtypes', 'test that two candle Tensors are approximately equal using assert_almost_equal with absolute tolerance atol', 'test that two candle Tensors are approximately equal using assert_almost_equal with relative tolerance rtol', 'test creating a candle Tensor and converting it to different dtypes like f32 f64 or u32', 'test that assert_equal raises an AssertionError when comparing two different candle Tensors']
```

Usage

```
{'create_candle_module_subclass': 'create a candle.nn.Module subclass that registers tensors and Linear submodules as buffers', 'test_module_state_dict': 'test that a candle Module can dump and load its state_dict with named tensors', 'test_module_quantized_tensors': 'test loading quantized Q4_0 tensors into a candle Module via load_state_dict', 'test_module_device_transfer': 'test moving a candle Module to CUDA and back to CPU with cuda and cpu methods', 'test_module_error_handling': 'test that load_state_dict raises RuntimeError on shape mismatch or missing keys'}
```

## File: huggingface_candle/candle-pyo3/tests/bindings/test_testing.py

Prompts

```
['test that a Linear layer can be constructed with input and output dimensions', 'test the Linear layer forward pass with a singular 2D input tensor', 'test the Linear layer forward pass with a batched 3D input tensor', 'test a quantized Linear layer forward pass with q4_0 quantization on a singular input', 'test a quantized Linear layer forward pass with q4_0 quantization on a batched input', 'create a candle.nn.Module subclass that registers tensors and Linear submodules as buffers', 'test that a candle Module can dump and load its state_dict with named tensors', 'test loading quantized Q4_0 tensors into a candle Module via load_state_dict', 'test moving a candle Module to CUDA and back to CPU with cuda and cpu methods', 'test that load_state_dict raises RuntimeError on shape mismatch or missing keys', 'test that two candle Tensors are exactly equal using assert_equal across multiple dtypes', 'test that two candle Tensors are approximately equal using assert_almost_equal with absolute tolerance atol', 'test that two candle Tensors are approximately equal using assert_almost_equal with relative tolerance rtol', 'test creating a candle Tensor and converting it to different dtypes like f32 f64 or u32', 'test that assert_equal raises an AssertionError when comparing two different candle Tensors']
```

Usage

```
{'test_assert_equal_tensors': 'test that two candle Tensors are exactly equal using assert_equal across multiple dtypes', 'test_assert_almost_equal_with_atol': 'test that two candle Tensors are approximately equal using assert_almost_equal with absolute tolerance atol', 'test_assert_almost_equal_with_rtol': 'test that two candle Tensors are approximately equal using assert_almost_equal with relative tolerance rtol', 'test_tensor_dtype_conversion': 'test creating a candle Tensor and converting it to different dtypes like f32 f64 or u32', 'test_assertion_raises_on_mismatch': 'test that assert_equal raises an AssertionError when comparing two different candle Tensors'}
```

