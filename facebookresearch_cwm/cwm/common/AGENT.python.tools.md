# Agent Python Tools

- repo: facebookresearch/cwm
- repo_uri: https://github.com/facebookresearch/cwm

## File: facebookresearch_cwm/cwm/common/environment.py

Prompts

```
['initialize PyTorch distributed process group with NCCL backend for multi-GPU or multi-node training', 'set environment variables including Triton cache directory and configure multiprocessing start method', 'set random seeds for Python, NumPy, and PyTorch with optional deterministic algorithm mode', 'configure PyTorch CUDA flags for TF32 matmul, BF16 reduction, and autograd anomaly detection', 'get the global process rank from torchrun or SLURM environment variables', 'load a YAML parameters file into a typed dataclass instance using load_params', 'save a dataclass instance as a YAML parameters file using save_params', 'load a JSON parameters file into a typed dataclass instance using load_params_from_json', 'save a dataclass instance as a JSON parameters file using save_params_to_json', 'load dataclass parameters from CLI arguments with optional config file and preset support using load_from_cli']
```

Usage

```
{'init_torch_distributed': 'initialize PyTorch distributed process group with NCCL backend for multi-GPU or multi-node training', 'setup_env': 'set environment variables including Triton cache directory and configure multiprocessing start method', 'set_seed': 'set random seeds for Python, NumPy, and PyTorch with optional deterministic algorithm mode', 'setup_torch_flags': 'configure PyTorch CUDA flags for TF32 matmul, BF16 reduction, and autograd anomaly detection', 'get_global_rank': 'get the global process rank from torchrun or SLURM environment variables'}
```

## File: facebookresearch_cwm/cwm/common/params.py

Prompts

```
['initialize PyTorch distributed process group with NCCL backend for multi-GPU or multi-node training', 'set environment variables including Triton cache directory and configure multiprocessing start method', 'set random seeds for Python, NumPy, and PyTorch with optional deterministic algorithm mode', 'configure PyTorch CUDA flags for TF32 matmul, BF16 reduction, and autograd anomaly detection', 'get the global process rank from torchrun or SLURM environment variables', 'load a YAML parameters file into a typed dataclass instance using load_params', 'save a dataclass instance as a YAML parameters file using save_params', 'load a JSON parameters file into a typed dataclass instance using load_params_from_json', 'save a dataclass instance as a JSON parameters file using save_params_to_json', 'load dataclass parameters from CLI arguments with optional config file and preset support using load_from_cli']
```

Usage

```
{'load_params_from_yaml': 'load a YAML parameters file into a typed dataclass instance using load_params', 'save_params_to_yaml': 'save a dataclass instance as a YAML parameters file using save_params', 'load_params_from_json': 'load a JSON parameters file into a typed dataclass instance using load_params_from_json', 'save_params_to_json': 'save a dataclass instance as a JSON parameters file using save_params_to_json', 'load_from_cli': 'load dataclass parameters from CLI arguments with optional config file and preset support using load_from_cli'}
```

