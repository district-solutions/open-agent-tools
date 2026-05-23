# Agent Python Tools

- repo: facebookresearch/stablesignature
- repo_uri: https://github.com/facebookresearch/stable_signature

## File: facebookresearch_stablesignature/src/taming/modules/util.py

Prompts

```
['count the total number of trainable parameters in a PyTorch model', 'create an ActNorm layer to normalize activations with learnable affine parameters', 'use ActNorm forward pass to normalize input tensors during training', 'use ActNorm reverse pass to denormalize output tensors back to original scale', 'create a Labelator encoder for class-conditional models with quantize interface']
```

Usage

```
{'count_params_model': 'count the total number of trainable parameters in a PyTorch model', 'create_ActNorm_layer': 'create an ActNorm layer to normalize activations with learnable affine parameters', 'use_ActNorm_forward': 'use ActNorm forward pass to normalize input tensors during training', 'use_ActNorm_reverse': 'use ActNorm reverse pass to denormalize output tensors back to original scale', 'create_Labelator_encoder': 'create a Labelator encoder for class-conditional models with quantize interface'}
```

