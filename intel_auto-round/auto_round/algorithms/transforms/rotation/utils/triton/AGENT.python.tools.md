# Agent Python Tools

- repo: intel/auto-round
- repo_uri: https://github.com/intel/auto-round

## File: intel_auto-round/auto_round/algorithms/transforms/rotation/utils/triton/mxfp4.py

Prompts

```
['build a python module that applies hadamard transform and group-wise FP4 quantize dequantize to a CUDA tensor', 'run the mxfp4 forward kernel on a CUDA tensor with a hadamard matrix and return the quantized output', 'test the mxfp4 forward kernel wrapper in quest mode using gaussian-based per-group scaling on a CUDA tensor', 'test the mxfp4 forward kernel wrapper with return clip mask enabled to track values exceeding the FP4 range', 'review the mxfp4 forward kernel quantization logic that maps scaled values to FP4 levels zero point five one one point five two three four six']
```

Usage

```
{'build_mxfp4_quantize': 'build a python module that applies hadamard transform and group-wise FP4 quantize dequantize to a CUDA tensor', 'run_mxfp4_forward_kernel': 'run the mxfp4 forward kernel on a CUDA tensor with a hadamard matrix and return the quantized output', 'test_mxfp4_wrapper_quest_mode': 'test the mxfp4 forward kernel wrapper in quest mode using gaussian-based per-group scaling on a CUDA tensor', 'test_mxfp4_wrapper_clip_mask': 'test the mxfp4 forward kernel wrapper with return clip mask enabled to track values exceeding the FP4 range', 'review_mxfp4_quantization_levels': 'review the mxfp4 forward kernel quantization logic that maps scaled values to FP4 levels zero point five one one point five two three four six'}
```

