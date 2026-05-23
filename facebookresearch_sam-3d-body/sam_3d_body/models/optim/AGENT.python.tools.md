# Agent Python Tools

- repo: facebookresearch/sam-3d-body
- repo_uri: https://github.com/facebookresearch/sam-3d-body

## File: facebookresearch_sam-3d-body/sam_3d_body/models/optim/fp16_utils.py

Prompts

```
['convert a PyTorch module and its children to float16 while preserving LayerNorm and BatchNorm in float32', "convert a single Conv or Linear module's parameters to float16 for mixed precision training", "convert a single Conv or Linear module's parameters back to float32 from float16", 'zero out all parameters of a PyTorch module by detaching and setting them to zero', 'scale all parameters of a PyTorch module by a given factor using in-place multiplication']
```

Usage

```
{'convert_to_fp16_safe': 'convert a PyTorch module and its children to float16 while preserving LayerNorm and BatchNorm in float32', 'convert_module_to_f16': "convert a single Conv or Linear module's parameters to float16 for mixed precision training", 'convert_module_to_f32': "convert a single Conv or Linear module's parameters back to float32 from float16", 'zero_module': 'zero out all parameters of a PyTorch module by detaching and setting them to zero', 'scale_module': 'scale all parameters of a PyTorch module by a given factor using in-place multiplication'}
```

