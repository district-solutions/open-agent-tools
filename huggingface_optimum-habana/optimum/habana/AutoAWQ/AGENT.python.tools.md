# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/optimum/habana/AutoAWQ/gemm_hpu.py

Prompts

```
['create a WQLinear_HPU module for 4-bit quantized linear layers on Intel HPU devices', 'run hpu_post_init on a model to preprocess all WQLinear_HPU submodules before inference', 'unpack AWQ quantized weights and zeros tensors and reverse their packing order', 'pack a tensor into a compressed int32 format by bits per value', 'create a WQLinear_HPU module from an existing nn.Linear layer for HPU inference']
```

Usage

```
{'create_WQLinear_HPU': 'create a WQLinear_HPU module for 4-bit quantized linear layers on Intel HPU devices', 'use_hpu_post_init': 'run hpu_post_init on a model to preprocess all WQLinear_HPU submodules before inference', 'use_unpack_weight_and_zeros': 'unpack AWQ quantized weights and zeros tensors and reverse their packing order', 'use_pack_tensor': 'pack a tensor into a compressed int32 format by bits per value', 'use_WQLinear_HPU_from_linear': 'create a WQLinear_HPU module from an existing nn.Linear layer for HPU inference'}
```

