# Agent Python Tools

- repo: bitsandbytes-foundation/bitsandbytes
- repo_uri: https://github.com/bitsandbytes-foundation/bitsandbytes

## File: bitsandbytes-foundation_bitsandbytes/bitsandbytes/backends/triton/kernels_4bit.py

Prompts

```
['quantize a PyTorch tensor blockwise to FP4 or NF4 format using Triton kernels', 'dequantize FP4 or NF4 quantized tensor data back to floating point using Triton', 'dequantize quantized tensor data using a custom codebook tensor with Triton kernels', 'quantize a tensor to 4-bit indices using a codebook-based binary search approach', 'dequantize FP4 packed uint8 data to floating point using a Triton tree kernel', 'dequantize a quantized 8-bit tensor back to full precision using Triton kernels', 'quantize a float tensor to 8-bit using blockwise quantization with a Triton kernel', 'quantize normalized values to 8-bit indices using binary search over a codebook', 'dequantize 8-bit indices back to float values using a codebook and absmax scales', 'launch a Triton kernel to dequantize 8-bit tensors in split blocks', 'create a 32-bit optimizer update using Triton kernels for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'create an 8-bit blockwise optimizer update using Triton kernels with dequantization and requantization for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'create a pure PyTorch 8-bit blockwise optimizer update with blockwise dequantization, 32-bit computation, and requantization for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'create an 8-bit blockwise optimizer update using PyTorch computation with Triton-based quantization and dequantization for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'summarize the Triton kernel functions for 1-state and 2-state 8-bit blockwise optimizer updates supporting Momentum, RMSprop, Adagrad, Lion, Adam, and AdEMAMix', 'quantize a float32 tensor to 8-bit using blockwise quantization with a codebook and blocksize', 'dequantize 8-bit blockwise quantized data back to float using absmax, codebook, and blocksize', 'quantize a 16/32-bit float tensor to 4-bit blockwise with nf4 or fp4 quantization type', 'dequantize 4-bit blockwise quantized data back to float using absmax, codebook, and blocksize', 'perform 8-bit blockwise optimizer update for adam with quantized state tensors and absmax values']
```

Usage

```
{'quantize_4bit_blockwise_triton': 'quantize a PyTorch tensor blockwise to FP4 or NF4 format using Triton kernels', 'dequantize_4bit_impl': 'dequantize FP4 or NF4 quantized tensor data back to floating point using Triton', 'dequantize_4bit_impl_passing_code': 'dequantize quantized tensor data using a custom codebook tensor with Triton kernels', 'quantize_4bit_blockwise_kernel': 'quantize a tensor to 4-bit indices using a codebook-based binary search approach', 'dequantize_fp4_kernel': 'dequantize FP4 packed uint8 data to floating point using a Triton tree kernel'}
```

## File: bitsandbytes-foundation_bitsandbytes/bitsandbytes/backends/triton/kernels_8bit_quant.py

Prompts

```
['quantize a PyTorch tensor blockwise to FP4 or NF4 format using Triton kernels', 'dequantize FP4 or NF4 quantized tensor data back to floating point using Triton', 'dequantize quantized tensor data using a custom codebook tensor with Triton kernels', 'quantize a tensor to 4-bit indices using a codebook-based binary search approach', 'dequantize FP4 packed uint8 data to floating point using a Triton tree kernel', 'dequantize a quantized 8-bit tensor back to full precision using Triton kernels', 'quantize a float tensor to 8-bit using blockwise quantization with a Triton kernel', 'quantize normalized values to 8-bit indices using binary search over a codebook', 'dequantize 8-bit indices back to float values using a codebook and absmax scales', 'launch a Triton kernel to dequantize 8-bit tensors in split blocks', 'create a 32-bit optimizer update using Triton kernels for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'create an 8-bit blockwise optimizer update using Triton kernels with dequantization and requantization for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'create a pure PyTorch 8-bit blockwise optimizer update with blockwise dequantization, 32-bit computation, and requantization for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'create an 8-bit blockwise optimizer update using PyTorch computation with Triton-based quantization and dequantization for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'summarize the Triton kernel functions for 1-state and 2-state 8-bit blockwise optimizer updates supporting Momentum, RMSprop, Adagrad, Lion, Adam, and AdEMAMix', 'quantize a float32 tensor to 8-bit using blockwise quantization with a codebook and blocksize', 'dequantize 8-bit blockwise quantized data back to float using absmax, codebook, and blocksize', 'quantize a 16/32-bit float tensor to 4-bit blockwise with nf4 or fp4 quantization type', 'dequantize 4-bit blockwise quantized data back to float using absmax, codebook, and blocksize', 'perform 8-bit blockwise optimizer update for adam with quantized state tensors and absmax values']
```

Usage

```
{'dequant_8bit_blockwise': 'dequantize a quantized 8-bit tensor back to full precision using Triton kernels', 'quantize_blockwise_triton': 'quantize a float tensor to 8-bit using blockwise quantization with a Triton kernel', 'quantize_8bit_blockwise_kernel_util': 'quantize normalized values to 8-bit indices using binary search over a codebook', 'dequant_8bit_blockwise_kernel_util': 'dequantize 8-bit indices back to float values using a codebook and absmax scales', 'dequant_8bit_kernel': 'launch a Triton kernel to dequantize 8-bit tensors in split blocks'}
```

## File: bitsandbytes-foundation_bitsandbytes/bitsandbytes/backends/triton/kernels_optim.py

Prompts

```
['quantize a PyTorch tensor blockwise to FP4 or NF4 format using Triton kernels', 'dequantize FP4 or NF4 quantized tensor data back to floating point using Triton', 'dequantize quantized tensor data using a custom codebook tensor with Triton kernels', 'quantize a tensor to 4-bit indices using a codebook-based binary search approach', 'dequantize FP4 packed uint8 data to floating point using a Triton tree kernel', 'dequantize a quantized 8-bit tensor back to full precision using Triton kernels', 'quantize a float tensor to 8-bit using blockwise quantization with a Triton kernel', 'quantize normalized values to 8-bit indices using binary search over a codebook', 'dequantize 8-bit indices back to float values using a codebook and absmax scales', 'launch a Triton kernel to dequantize 8-bit tensors in split blocks', 'create a 32-bit optimizer update using Triton kernels for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'create an 8-bit blockwise optimizer update using Triton kernels with dequantization and requantization for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'create a pure PyTorch 8-bit blockwise optimizer update with blockwise dequantization, 32-bit computation, and requantization for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'create an 8-bit blockwise optimizer update using PyTorch computation with Triton-based quantization and dequantization for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'summarize the Triton kernel functions for 1-state and 2-state 8-bit blockwise optimizer updates supporting Momentum, RMSprop, Adagrad, Lion, Adam, and AdEMAMix', 'quantize a float32 tensor to 8-bit using blockwise quantization with a codebook and blocksize', 'dequantize 8-bit blockwise quantized data back to float using absmax, codebook, and blocksize', 'quantize a 16/32-bit float tensor to 4-bit blockwise with nf4 or fp4 quantization type', 'dequantize 4-bit blockwise quantized data back to float using absmax, codebook, and blocksize', 'perform 8-bit blockwise optimizer update for adam with quantized state tensors and absmax values']
```

Usage

```
{'create_optimizer_update_32bit': 'create a 32-bit optimizer update using Triton kernels for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'create_optimizer_update_8bit_blockwise': 'create an 8-bit blockwise optimizer update using Triton kernels with dequantization and requantization for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'create_optimizer_update_8bit_pytorch': 'create a pure PyTorch 8-bit blockwise optimizer update with blockwise dequantization, 32-bit computation, and requantization for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'create_optimizer_update_8bit_triton_quant': 'create an 8-bit blockwise optimizer update using PyTorch computation with Triton-based quantization and dequantization for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'summarize_optimizer_kernels': 'summarize the Triton kernel functions for 1-state and 2-state 8-bit blockwise optimizer updates supporting Momentum, RMSprop, Adagrad, Lion, Adam, and AdEMAMix'}
```

## File: bitsandbytes-foundation_bitsandbytes/bitsandbytes/backends/triton/ops.py

Prompts

```
['quantize a PyTorch tensor blockwise to FP4 or NF4 format using Triton kernels', 'dequantize FP4 or NF4 quantized tensor data back to floating point using Triton', 'dequantize quantized tensor data using a custom codebook tensor with Triton kernels', 'quantize a tensor to 4-bit indices using a codebook-based binary search approach', 'dequantize FP4 packed uint8 data to floating point using a Triton tree kernel', 'dequantize a quantized 8-bit tensor back to full precision using Triton kernels', 'quantize a float tensor to 8-bit using blockwise quantization with a Triton kernel', 'quantize normalized values to 8-bit indices using binary search over a codebook', 'dequantize 8-bit indices back to float values using a codebook and absmax scales', 'launch a Triton kernel to dequantize 8-bit tensors in split blocks', 'create a 32-bit optimizer update using Triton kernels for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'create an 8-bit blockwise optimizer update using Triton kernels with dequantization and requantization for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'create a pure PyTorch 8-bit blockwise optimizer update with blockwise dequantization, 32-bit computation, and requantization for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'create an 8-bit blockwise optimizer update using PyTorch computation with Triton-based quantization and dequantization for Adam, AdEMAMix, Momentum, RMSprop, Adagrad, and Lion', 'summarize the Triton kernel functions for 1-state and 2-state 8-bit blockwise optimizer updates supporting Momentum, RMSprop, Adagrad, Lion, Adam, and AdEMAMix', 'quantize a float32 tensor to 8-bit using blockwise quantization with a codebook and blocksize', 'dequantize 8-bit blockwise quantized data back to float using absmax, codebook, and blocksize', 'quantize a 16/32-bit float tensor to 4-bit blockwise with nf4 or fp4 quantization type', 'dequantize 4-bit blockwise quantized data back to float using absmax, codebook, and blocksize', 'perform 8-bit blockwise optimizer update for adam with quantized state tensors and absmax values']
```

Usage

```
{'quantize_blockwise': 'quantize a float32 tensor to 8-bit using blockwise quantization with a codebook and blocksize', 'dequantize_blockwise': 'dequantize 8-bit blockwise quantized data back to float using absmax, codebook, and blocksize', 'quantize_4bit': 'quantize a 16/32-bit float tensor to 4-bit blockwise with nf4 or fp4 quantization type', 'dequantize_4bit': 'dequantize 4-bit blockwise quantized data back to float using absmax, codebook, and blocksize', 'optimizer_update_8bit_blockwise': 'perform 8-bit blockwise optimizer update for adam with quantized state tensors and absmax values'}
```

