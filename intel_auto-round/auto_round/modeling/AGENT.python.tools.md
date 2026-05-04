# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round/modeling/finegrained_fp8_patch.py

Prompts

```
['replace all torch.nn.Linear modules in a PyTorch model with FP8Linear modules for fp8 quantization', 'create an FP8Linear layer with configurable block size and dynamic or static activation scheme', 'quantize fp32 weight tensors to fp8 format with per-tile inverse scales using Fp8Quantize', 'dequantize fp8 weight tensors back to fp32 using inverse scales with Fp8Dequantize', 'review the FP8Linear class to understand block size and activation scheme parameters for quantization', 'replace all linear layers in a PyTorch model with FP8Linear layers using a quantization config', 'review the FP8Linear class to understand its FP8 weight storage and per-block inverse scale parameters', 'refactor replace_with_fp8_linear to customize which modules to skip during FP8 conversion', 'summarize the replace_with_fp8_linear function that recursively swaps nn.Linear layers for FP8Linear', 'replace all torch.nn.Linear modules in a model with FP8Linear modules while skipping expert modules', 'apply a patch to transformers to disable expert replacement during FP8 quantization', 'patch FineGrainedFP8HfQuantizer to bypass CUDA device capability validation for FP8 model loading', 'review the FP8 quantization patching logic that overrides transformers replace_with_fp8_linear behavior', 'summarize the oot_replace_with_fp8_linear function that converts Linear layers to FP8Linear with bias handling', 'patch transformers.integrations.finegrained_fp8 with HPU-compatible overrides for Intel Habana processors', 'review the patch_finegrained_fp8 function to verify HPU availability checks and version detection logic', 'test the patch_finegrained_fp8 function to confirm it patches transformers symbols correctly on HPU devices', 'refactor patch_finegrained_fp8 to support additional transformers versions beyond 4.x and 5.x', 'summarize the patch_finegrained_fp8 function that replaces finegrained_fp8 symbols with HPU-compatible versions']
```

Usage

```
{'replace_model_linears_with_fp8': 'replace all torch.nn.Linear modules in a PyTorch model with FP8Linear modules for fp8 quantization', 'create_fp8_linear_layer': 'create an FP8Linear layer with configurable block size and dynamic or static activation scheme', 'quantize_weights_to_fp8': 'quantize fp32 weight tensors to fp8 format with per-tile inverse scales using Fp8Quantize', 'dequantize_fp8_weights_to_fp32': 'dequantize fp8 weight tensors back to fp32 using inverse scales with Fp8Dequantize', 'review_fp8_quantization_config': 'review the FP8Linear class to understand block size and activation scheme parameters for quantization'}
```

## File: intel_auto-round/auto_round/modeling/finegrained_fp8_patch_v4.py

Prompts

```
['replace all torch.nn.Linear modules in a PyTorch model with FP8Linear modules for fp8 quantization', 'create an FP8Linear layer with configurable block size and dynamic or static activation scheme', 'quantize fp32 weight tensors to fp8 format with per-tile inverse scales using Fp8Quantize', 'dequantize fp8 weight tensors back to fp32 using inverse scales with Fp8Dequantize', 'review the FP8Linear class to understand block size and activation scheme parameters for quantization', 'replace all linear layers in a PyTorch model with FP8Linear layers using a quantization config', 'review the FP8Linear class to understand its FP8 weight storage and per-block inverse scale parameters', 'refactor replace_with_fp8_linear to customize which modules to skip during FP8 conversion', 'summarize the replace_with_fp8_linear function that recursively swaps nn.Linear layers for FP8Linear', 'replace all torch.nn.Linear modules in a model with FP8Linear modules while skipping expert modules', 'apply a patch to transformers to disable expert replacement during FP8 quantization', 'patch FineGrainedFP8HfQuantizer to bypass CUDA device capability validation for FP8 model loading', 'review the FP8 quantization patching logic that overrides transformers replace_with_fp8_linear behavior', 'summarize the oot_replace_with_fp8_linear function that converts Linear layers to FP8Linear with bias handling', 'patch transformers.integrations.finegrained_fp8 with HPU-compatible overrides for Intel Habana processors', 'review the patch_finegrained_fp8 function to verify HPU availability checks and version detection logic', 'test the patch_finegrained_fp8 function to confirm it patches transformers symbols correctly on HPU devices', 'refactor patch_finegrained_fp8 to support additional transformers versions beyond 4.x and 5.x', 'summarize the patch_finegrained_fp8 function that replaces finegrained_fp8 symbols with HPU-compatible versions']
```

Usage

```
{'create_fp8_linear_layer': 'create an FP8Linear layer with specified in_features, out_features, block_size, and activation_scheme', 'replace_model_with_fp8_linear': 'replace all linear layers in a PyTorch model with FP8Linear layers using a quantization config', 'review_FP8Linear_class': 'review the FP8Linear class to understand its FP8 weight storage and per-block inverse scale parameters', 'refactor_replace_with_fp8_linear': 'refactor replace_with_fp8_linear to customize which modules to skip during FP8 conversion', 'summarize_replace_with_fp8_linear': 'summarize the replace_with_fp8_linear function that recursively swaps nn.Linear layers for FP8Linear'}
```

## File: intel_auto-round/auto_round/modeling/fp8_quant.py

Prompts

```
['replace all torch.nn.Linear modules in a PyTorch model with FP8Linear modules for fp8 quantization', 'create an FP8Linear layer with configurable block size and dynamic or static activation scheme', 'quantize fp32 weight tensors to fp8 format with per-tile inverse scales using Fp8Quantize', 'dequantize fp8 weight tensors back to fp32 using inverse scales with Fp8Dequantize', 'review the FP8Linear class to understand block size and activation scheme parameters for quantization', 'replace all linear layers in a PyTorch model with FP8Linear layers using a quantization config', 'review the FP8Linear class to understand its FP8 weight storage and per-block inverse scale parameters', 'refactor replace_with_fp8_linear to customize which modules to skip during FP8 conversion', 'summarize the replace_with_fp8_linear function that recursively swaps nn.Linear layers for FP8Linear', 'replace all torch.nn.Linear modules in a model with FP8Linear modules while skipping expert modules', 'apply a patch to transformers to disable expert replacement during FP8 quantization', 'patch FineGrainedFP8HfQuantizer to bypass CUDA device capability validation for FP8 model loading', 'review the FP8 quantization patching logic that overrides transformers replace_with_fp8_linear behavior', 'summarize the oot_replace_with_fp8_linear function that converts Linear layers to FP8Linear with bias handling', 'patch transformers.integrations.finegrained_fp8 with HPU-compatible overrides for Intel Habana processors', 'review the patch_finegrained_fp8 function to verify HPU availability checks and version detection logic', 'test the patch_finegrained_fp8 function to confirm it patches transformers symbols correctly on HPU devices', 'refactor patch_finegrained_fp8 to support additional transformers versions beyond 4.x and 5.x', 'summarize the patch_finegrained_fp8 function that replaces finegrained_fp8 symbols with HPU-compatible versions']
```

Usage

```
{'replace_linear_with_fp8': 'replace all torch.nn.Linear modules in a model with FP8Linear modules while skipping expert modules', 'patch_fp8_expert_replacement': 'apply a patch to transformers to disable expert replacement during FP8 quantization', 'bypass_cuda_device_check': 'patch FineGrainedFP8HfQuantizer to bypass CUDA device capability validation for FP8 model loading', 'review_fp8_quant_patch': 'review the FP8 quantization patching logic that overrides transformers replace_with_fp8_linear behavior', 'summarize_oot_replace_with_fp8_linear': 'summarize the oot_replace_with_fp8_linear function that converts Linear layers to FP8Linear with bias handling'}
```

## File: intel_auto-round/auto_round/modeling/hpu_patch.py

Prompts

```
['replace all torch.nn.Linear modules in a PyTorch model with FP8Linear modules for fp8 quantization', 'create an FP8Linear layer with configurable block size and dynamic or static activation scheme', 'quantize fp32 weight tensors to fp8 format with per-tile inverse scales using Fp8Quantize', 'dequantize fp8 weight tensors back to fp32 using inverse scales with Fp8Dequantize', 'review the FP8Linear class to understand block size and activation scheme parameters for quantization', 'replace all linear layers in a PyTorch model with FP8Linear layers using a quantization config', 'review the FP8Linear class to understand its FP8 weight storage and per-block inverse scale parameters', 'refactor replace_with_fp8_linear to customize which modules to skip during FP8 conversion', 'summarize the replace_with_fp8_linear function that recursively swaps nn.Linear layers for FP8Linear', 'replace all torch.nn.Linear modules in a model with FP8Linear modules while skipping expert modules', 'apply a patch to transformers to disable expert replacement during FP8 quantization', 'patch FineGrainedFP8HfQuantizer to bypass CUDA device capability validation for FP8 model loading', 'review the FP8 quantization patching logic that overrides transformers replace_with_fp8_linear behavior', 'summarize the oot_replace_with_fp8_linear function that converts Linear layers to FP8Linear with bias handling', 'patch transformers.integrations.finegrained_fp8 with HPU-compatible overrides for Intel Habana processors', 'review the patch_finegrained_fp8 function to verify HPU availability checks and version detection logic', 'test the patch_finegrained_fp8 function to confirm it patches transformers symbols correctly on HPU devices', 'refactor patch_finegrained_fp8 to support additional transformers versions beyond 4.x and 5.x', 'summarize the patch_finegrained_fp8 function that replaces finegrained_fp8 symbols with HPU-compatible versions']
```

Usage

```
{'patch_finegrained_fp8': 'patch transformers.integrations.finegrained_fp8 with HPU-compatible overrides for Intel Habana processors', 'review_patch_finegrained_fp8': 'review the patch_finegrained_fp8 function to verify HPU availability checks and version detection logic', 'test_patch_finegrained_fp8': 'test the patch_finegrained_fp8 function to confirm it patches transformers symbols correctly on HPU devices', 'refactor_patch_finegrained_fp8': 'refactor patch_finegrained_fp8 to support additional transformers versions beyond 4.x and 5.x', 'summarize_patch_finegrained_fp8': 'summarize the patch_finegrained_fp8 function that replaces finegrained_fp8 symbols with HPU-compatible versions'}
```

