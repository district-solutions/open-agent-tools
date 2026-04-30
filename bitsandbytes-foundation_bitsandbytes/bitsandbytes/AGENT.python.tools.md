# Agent Python Tools

- repo: bitsandbytes-foundation/bitsandbytes
- repo_uri: https://github.com/bitsandbytes-foundation/bitsandbytes

## File: bitsandbytes-foundation_bitsandbytes/bitsandbytes/cextension.py

Prompts

```
['get the disk path to the CUDA BNB native library for given CUDA specs', 'load the bitsandbytes native library (CUDA, ROCm, XPU, or CPU) and return the library handler', 'create a BNBNativeLibrary wrapper around a ctypes CDLL for accessing native bitsandbytes functions', 'create a CudaBNBNativeLibrary wrapper with get_context and cget_managed_ptr void pointer return types', 'generate detailed error diagnostics when bitsandbytes native library fails to load', 'get CUDA or HIP specifications including compute capability and version tuple', 'get a sorted list of GPU compute capabilities for all available CUDA devices', 'get the ROCm GPU architecture string such as gfx900 or gfx1030', 'get the CUDA or HIP version as a compact string like 118 for 11.8', 'test whether CUDA is available and retrieve full GPU specifications', 'quantize a tensor using 4-bit quantization with nf4 or fp4 data types', 'dequantize a packed 4-bit quantized tensor back to floating point', 'quantize a tensor in blocks of values using blockwise quantization', 'dequantize a blockwise quantized tensor using absmax scaling', 'perform integer matrix multiplication using cuBLAS with int8 tensors', 'create an OutlierTracer singleton instance and initialize it with a PyTorch model to register forward pre-hooks on Linear layers', 'find outlier dimensions in a weight tensor using z-score thresholding or top-k selection', 'replace all Linear modules in a PyTorch model with a custom replacement module recursively', 'pack a Python dictionary into a torch tensor for storing quant_state items in a state_dict', 'unpack a torch tensor back into a Python dictionary by decoding bytes and parsing JSON']
```

Usage

```
{'get_cuda_bnb_library_path': 'get the disk path to the CUDA BNB native library for given CUDA specs', 'load_native_library': 'load the bitsandbytes native library (CUDA, ROCm, XPU, or CPU) and return the library handler', 'create_bnbnative_library': 'create a BNBNativeLibrary wrapper around a ctypes CDLL for accessing native bitsandbytes functions', 'create_cuda_bnbnative_library': 'create a CudaBNBNativeLibrary wrapper with get_context and cget_managed_ptr void pointer return types', 'handle_library_error': 'generate detailed error diagnostics when bitsandbytes native library fails to load'}
```

## File: bitsandbytes-foundation_bitsandbytes/bitsandbytes/cuda_specs.py

Prompts

```
['get the disk path to the CUDA BNB native library for given CUDA specs', 'load the bitsandbytes native library (CUDA, ROCm, XPU, or CPU) and return the library handler', 'create a BNBNativeLibrary wrapper around a ctypes CDLL for accessing native bitsandbytes functions', 'create a CudaBNBNativeLibrary wrapper with get_context and cget_managed_ptr void pointer return types', 'generate detailed error diagnostics when bitsandbytes native library fails to load', 'get CUDA or HIP specifications including compute capability and version tuple', 'get a sorted list of GPU compute capabilities for all available CUDA devices', 'get the ROCm GPU architecture string such as gfx900 or gfx1030', 'get the CUDA or HIP version as a compact string like 118 for 11.8', 'test whether CUDA is available and retrieve full GPU specifications', 'quantize a tensor using 4-bit quantization with nf4 or fp4 data types', 'dequantize a packed 4-bit quantized tensor back to floating point', 'quantize a tensor in blocks of values using blockwise quantization', 'dequantize a blockwise quantized tensor using absmax scaling', 'perform integer matrix multiplication using cuBLAS with int8 tensors', 'create an OutlierTracer singleton instance and initialize it with a PyTorch model to register forward pre-hooks on Linear layers', 'find outlier dimensions in a weight tensor using z-score thresholding or top-k selection', 'replace all Linear modules in a PyTorch model with a custom replacement module recursively', 'pack a Python dictionary into a torch tensor for storing quant_state items in a state_dict', 'unpack a torch tensor back into a Python dictionary by decoding bytes and parsing JSON']
```

Usage

```
{'get_cuda_specs': 'get CUDA or HIP specifications including compute capability and version tuple', 'get_compute_capabilities': 'get a sorted list of GPU compute capabilities for all available CUDA devices', 'get_rocm_gpu_arch': 'get the ROCm GPU architecture string such as gfx900 or gfx1030', 'get_cuda_version_string': 'get the CUDA or HIP version as a compact string like 118 for 11.8', 'test_cuda_available': 'test whether CUDA is available and retrieve full GPU specifications'}
```

## File: bitsandbytes-foundation_bitsandbytes/bitsandbytes/functional.py

Prompts

```
['get the disk path to the CUDA BNB native library for given CUDA specs', 'load the bitsandbytes native library (CUDA, ROCm, XPU, or CPU) and return the library handler', 'create a BNBNativeLibrary wrapper around a ctypes CDLL for accessing native bitsandbytes functions', 'create a CudaBNBNativeLibrary wrapper with get_context and cget_managed_ptr void pointer return types', 'generate detailed error diagnostics when bitsandbytes native library fails to load', 'get CUDA or HIP specifications including compute capability and version tuple', 'get a sorted list of GPU compute capabilities for all available CUDA devices', 'get the ROCm GPU architecture string such as gfx900 or gfx1030', 'get the CUDA or HIP version as a compact string like 118 for 11.8', 'test whether CUDA is available and retrieve full GPU specifications', 'quantize a tensor using 4-bit quantization with nf4 or fp4 data types', 'dequantize a packed 4-bit quantized tensor back to floating point', 'quantize a tensor in blocks of values using blockwise quantization', 'dequantize a blockwise quantized tensor using absmax scaling', 'perform integer matrix multiplication using cuBLAS with int8 tensors', 'create an OutlierTracer singleton instance and initialize it with a PyTorch model to register forward pre-hooks on Linear layers', 'find outlier dimensions in a weight tensor using z-score thresholding or top-k selection', 'replace all Linear modules in a PyTorch model with a custom replacement module recursively', 'pack a Python dictionary into a torch tensor for storing quant_state items in a state_dict', 'unpack a torch tensor back into a Python dictionary by decoding bytes and parsing JSON']
```

Usage

```
{'quantize_4bit': 'quantize a tensor using 4-bit quantization with nf4 or fp4 data types', 'dequantize_4bit': 'dequantize a packed 4-bit quantized tensor back to floating point', 'quantize_blockwise': 'quantize a tensor in blocks of values using blockwise quantization', 'dequantize_blockwise': 'dequantize a blockwise quantized tensor using absmax scaling', 'igemm': 'perform integer matrix multiplication using cuBLAS with int8 tensors'}
```

## File: bitsandbytes-foundation_bitsandbytes/bitsandbytes/utils.py

Prompts

```
['get the disk path to the CUDA BNB native library for given CUDA specs', 'load the bitsandbytes native library (CUDA, ROCm, XPU, or CPU) and return the library handler', 'create a BNBNativeLibrary wrapper around a ctypes CDLL for accessing native bitsandbytes functions', 'create a CudaBNBNativeLibrary wrapper with get_context and cget_managed_ptr void pointer return types', 'generate detailed error diagnostics when bitsandbytes native library fails to load', 'get CUDA or HIP specifications including compute capability and version tuple', 'get a sorted list of GPU compute capabilities for all available CUDA devices', 'get the ROCm GPU architecture string such as gfx900 or gfx1030', 'get the CUDA or HIP version as a compact string like 118 for 11.8', 'test whether CUDA is available and retrieve full GPU specifications', 'quantize a tensor using 4-bit quantization with nf4 or fp4 data types', 'dequantize a packed 4-bit quantized tensor back to floating point', 'quantize a tensor in blocks of values using blockwise quantization', 'dequantize a blockwise quantized tensor using absmax scaling', 'perform integer matrix multiplication using cuBLAS with int8 tensors', 'create an OutlierTracer singleton instance and initialize it with a PyTorch model to register forward pre-hooks on Linear layers', 'find outlier dimensions in a weight tensor using z-score thresholding or top-k selection', 'replace all Linear modules in a PyTorch model with a custom replacement module recursively', 'pack a Python dictionary into a torch tensor for storing quant_state items in a state_dict', 'unpack a torch tensor back into a Python dictionary by decoding bytes and parsing JSON']
```

Usage

```
{'create_OutlierTracer': 'create an OutlierTracer singleton instance and initialize it with a PyTorch model to register forward pre-hooks on Linear layers', 'find_outlier_dims': 'find outlier dimensions in a weight tensor using z-score thresholding or top-k selection', 'replace_linear': 'replace all Linear modules in a PyTorch model with a custom replacement module recursively', 'pack_dict_to_tensor': 'pack a Python dictionary into a torch tensor for storing quant_state items in a state_dict', 'unpack_tensor_to_dict': 'unpack a torch tensor back into a Python dictionary by decoding bytes and parsing JSON'}
```

