# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/ao/pruning/_experimental/activation_sparsifier/activation_sparsifier.py

Prompts

```
['create an ActivationSparsifier to sparsify neural network activations using configurable aggregate, reduce, and mask functions', 'register a model layer with the ActivationSparsifier to collect and aggregate its input activations', 'run the ActivationSparsifier step to compute sparsification masks from accumulated activations', 'squash the ActivationSparsifier masks and attach sparsify hooks to apply pruning during forward passes', 'get the ActivationSparsifier state dict containing masks, data groups, and defaults for serialization']
```

Usage

```
{'create_ActivationSparsifier': 'create an ActivationSparsifier to sparsify neural network activations using configurable aggregate, reduce, and mask functions', 'register_layer_ActivationSparsifier': 'register a model layer with the ActivationSparsifier to collect and aggregate its input activations', 'step_ActivationSparsifier': 'run the ActivationSparsifier step to compute sparsification masks from accumulated activations', 'squash_mask_ActivationSparsifier': 'squash the ActivationSparsifier masks and attach sparsify hooks to apply pruning during forward passes', 'state_dict_ActivationSparsifier': 'get the ActivationSparsifier state dict containing masks, data groups, and defaults for serialization'}
```

