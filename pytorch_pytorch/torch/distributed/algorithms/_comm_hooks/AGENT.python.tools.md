# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/algorithms/_comm_hooks/default_hooks.py

Prompts

```
['create a DefaultState instance with a process group for default gradient communication hooks', 'create a LowPrecisionState instance with a process group and parameter dtype for low-precision gradient hooks', 'run the allreduce_hook to average and all-reduce gradients across ranks with pre/post division factors', 'run the fp16_compress_hook to cast gradients to float16, communicate, and cast back to original precision', 'run the bf16_compress_hook to cast gradients to bfloat16, communicate, and cast back to original precision']
```

Usage

```
{'create_default_state': 'create a DefaultState instance with a process group for default gradient communication hooks', 'create_low_precision_state': 'create a LowPrecisionState instance with a process group and parameter dtype for low-precision gradient hooks', 'run_allreduce_hook': 'run the allreduce_hook to average and all-reduce gradients across ranks with pre/post division factors', 'run_fp16_compress_hook': 'run the fp16_compress_hook to cast gradients to float16, communicate, and cast back to original precision', 'run_bf16_compress_hook': 'run the bf16_compress_hook to cast gradients to bfloat16, communicate, and cast back to original precision'}
```

