# Agent Python Tools

- repo: unslothai/unsloth
- repo_uri: https://github.com/unslothai/unsloth.git

## File: unslothai_unsloth/unsloth/kernels/moe/grouped_gemm/interface.py

Prompts

```
['run grouped MoE GEMM with forward and backward passes using torch tensors and expert routing config', 'create a torch.autograd.Function for grouped GEMM with configurable forward and backward kernel params', 'run grouped GEMM forward pass for MoE MLP with optional token permutation and TMA acceleration', 'run grouped GEMM backward pass to compute input gradients dX with expert routing and permutation support', 'run grouped GEMM backward pass to compute weight gradients dW with expert routing and permutation support']
```

Usage

```
{'run_grouped_gemm': 'run grouped MoE GEMM with forward and backward passes using torch tensors and expert routing config', 'create_grouped_gemm_autograd': 'create a torch.autograd.Function for grouped GEMM with configurable forward and backward kernel params', 'run_grouped_gemm_forward': 'run grouped GEMM forward pass for MoE MLP with optional token permutation and TMA acceleration', 'run_grouped_gemm_dX': 'run grouped GEMM backward pass to compute input gradients dX with expert routing and permutation support', 'run_grouped_gemm_dW': 'run grouped GEMM backward pass to compute weight gradients dW with expert routing and permutation support'}
```

