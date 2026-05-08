# Agent Python Tools

- repo: facebookresearch/fairscale
- repo_uri: https://github.com/facebookresearch/fairscale

## File: facebookresearch_fairscale/fairscale/experimental/nn/data_parallel/gossip/utils/cuda_metering.py

Prompts

```
['create a CudaEventRecorder instance to start timing a named CUDA event', 'stop a CudaEventRecorder to record the end time of a CUDA event', 'get the CUDA event timings since last reset with average and standard deviation', 'get all CUDA event timings ever recorded with average and standard deviation', 'reset the CUDA event recorder timings to start fresh measurements', 'flatten a list of PyTorch tensors into a single contiguous 1D buffer for efficient communication', 'unflatten a 1D tensor buffer back into a list of tensors with original shapes', 'group a list of PyTorch tensors by their data types into a dictionary', 'communicate a list of tensors using a communication operation like all_reduce with automatic dtype grouping', 'create and initialize a new PyTorch distributed process group with the given ranks']
```

Usage

```
{'create_cuda_event_recorder': 'create a CudaEventRecorder instance to start timing a named CUDA event', 'stop_cuda_event_recorder': 'stop a CudaEventRecorder to record the end time of a CUDA event', 'get_cuda_timings': 'get the CUDA event timings since last reset with average and standard deviation', 'get_all_cuda_timings': 'get all CUDA event timings ever recorded with average and standard deviation', 'reset_cuda_timings': 'reset the CUDA event recorder timings to start fresh measurements'}
```

## File: facebookresearch_fairscale/fairscale/experimental/nn/data_parallel/gossip/utils/helpers.py

Prompts

```
['create a CudaEventRecorder instance to start timing a named CUDA event', 'stop a CudaEventRecorder to record the end time of a CUDA event', 'get the CUDA event timings since last reset with average and standard deviation', 'get all CUDA event timings ever recorded with average and standard deviation', 'reset the CUDA event recorder timings to start fresh measurements', 'flatten a list of PyTorch tensors into a single contiguous 1D buffer for efficient communication', 'unflatten a 1D tensor buffer back into a list of tensors with original shapes', 'group a list of PyTorch tensors by their data types into a dictionary', 'communicate a list of tensors using a communication operation like all_reduce with automatic dtype grouping', 'create and initialize a new PyTorch distributed process group with the given ranks']
```

Usage

```
{'flatten_tensors': 'flatten a list of PyTorch tensors into a single contiguous 1D buffer for efficient communication', 'unflatten_tensors': 'unflatten a 1D tensor buffer back into a list of tensors with original shapes', 'group_by_dtype': 'group a list of PyTorch tensors by their data types into a dictionary', 'communicate': 'communicate a list of tensors using a communication operation like all_reduce with automatic dtype grouping', 'create_process_group': 'create and initialize a new PyTorch distributed process group with the given ranks'}
```

