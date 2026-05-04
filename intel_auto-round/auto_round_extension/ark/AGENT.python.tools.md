# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round_extension/ark/install_kernel.py

Prompts

```
['run the install_kernel script to auto install the correct auto round kernel library for your torch version', 'get the torch major minor version string from the installed torch package', 'get the auto round major minor version string from the installed auto round package', 'review the KERNEL_MAP that maps torch minor versions to auto round lib package version constraints', 'refactor the main function to support additional torch versions or custom kernel package installation logic', 'create a QuantLinear layer with 4-bit symmetric quantization and group size 128', 'create a QuantLinearGPTQ layer for GPTQ-style 4-bit quantized linear transformation', 'create a QuantLinearAWQ layer for AWQ-style 4-bit quantized linear transformation', 'unpack packed quantized weights and zeros to 8-bit signed tensors using unpack_to_8bit_signed', 'dequantize packed weights back to full precision using dequantize_weight with scales and bits', 'run ark_post_init on a model to repack all QuantLinear modules for inference', 'review the QuantLinear post_init method that repacks weights via the ARK kernel', 'test the QuantLinear forward pass with a bfloat16 input tensor on CPU']
```

Usage

```
{'run_install_kernel': 'run the install_kernel script to auto install the correct auto round kernel library for your torch version', 'get_torch_minor': 'get the torch major minor version string from the installed torch package', 'get_auto_round_minor': 'get the auto round major minor version string from the installed auto round package', 'review_KERNEL_MAP': 'review the KERNEL_MAP that maps torch minor versions to auto round lib package version constraints', 'refactor_main': 'refactor the main function to support additional torch versions or custom kernel package installation logic'}
```

## File: intel_auto-round/auto_round_extension/ark/qlinear.py

Prompts

```
['run the install_kernel script to auto install the correct auto round kernel library for your torch version', 'get the torch major minor version string from the installed torch package', 'get the auto round major minor version string from the installed auto round package', 'review the KERNEL_MAP that maps torch minor versions to auto round lib package version constraints', 'refactor the main function to support additional torch versions or custom kernel package installation logic', 'create a QuantLinear layer with 4-bit symmetric quantization and group size 128', 'create a QuantLinearGPTQ layer for GPTQ-style 4-bit quantized linear transformation', 'create a QuantLinearAWQ layer for AWQ-style 4-bit quantized linear transformation', 'unpack packed quantized weights and zeros to 8-bit signed tensors using unpack_to_8bit_signed', 'dequantize packed weights back to full precision using dequantize_weight with scales and bits', 'run ark_post_init on a model to repack all QuantLinear modules for inference', 'review the QuantLinear post_init method that repacks weights via the ARK kernel', 'test the QuantLinear forward pass with a bfloat16 input tensor on CPU']
```

Usage

```
{'create_quantlinear_layer': 'create a QuantLinear layer with 4-bit symmetric quantization and group size 128', 'create_quantlinear_gptq_layer': 'create a QuantLinearGPTQ layer for GPTQ-style 4-bit quantized linear transformation', 'create_quantlinear_awq_layer': 'create a QuantLinearAWQ layer for AWQ-style 4-bit quantized linear transformation', 'unpack_quantized_weights': 'unpack packed quantized weights and zeros to 8-bit signed tensors using unpack_to_8bit_signed', 'dequantize_weight': 'dequantize packed weights back to full precision using dequantize_weight with scales and bits', 'post_init_model': 'run ark_post_init on a model to repack all QuantLinear modules for inference', 'review_quantlinear_post_init': 'review the QuantLinear post_init method that repacks weights via the ARK kernel', 'test_quantlinear_forward': 'test the QuantLinear forward pass with a bfloat16 input tensor on CPU'}
```

