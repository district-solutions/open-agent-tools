# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/_tensor/debug/comm_mode.py

Prompts

```
['create a CommDebugMode context manager to count functional collective operations in a PyTorch distributed training loop', 'test the CommDebugMode.get_total_counts method to return the sum of all collective communication counts', 'test the CommDebugMode.get_comm_counts method to return a dictionary of per-operation communication counts', "run a PyTorch model's backward pass inside a CommDebugMode context to track all_gather_into_tensor and all_reduce calls", 'review the CommDebugMode.__torch_dispatch__ method that intercepts functional collectives and increments their counts', 'summarize the operator coverage of a PyTorch model against DTensor sharding support', 'get the forward and backward graphs of a PyTorch model with inductor decompositions', 'print a tabulated operator coverage summary for a PyTorch model with DTensor support flags', 'run operator coverage analysis and output results to a CSV file for a PyTorch model', 'test which operators used by a PyTorch model are supported by DTensor sharding propagator', 'visualize the sharding layout of a 1D or 2D DTensor across a device mesh', 'compute the local shape and global offset of a DTensor shard for a given device coordinate', 'create a device-to-coordinate map from a DeviceMesh for a given device type', 'convert tensor shard offsets into row and column range blocks for tabulate rendering', 'create a formatted tabulate table showing DTensor sharding across devices']
```

Usage

```
{'create_CommDebugMode': 'create a CommDebugMode context manager to count functional collective operations in a PyTorch distributed training loop', 'test_get_total_counts': 'test the CommDebugMode.get_total_counts method to return the sum of all collective communication counts', 'test_get_comm_counts': 'test the CommDebugMode.get_comm_counts method to return a dictionary of per-operation communication counts', 'run_CommDebugMode_context': "run a PyTorch model's backward pass inside a CommDebugMode context to track all_gather_into_tensor and all_reduce calls", 'review_CommDebugMode_dispatch': 'review the CommDebugMode.__torch_dispatch__ method that intercepts functional collectives and increments their counts'}
```

## File: pytorch_pytorch/torch/distributed/_tensor/debug/op_coverage.py

Prompts

```
['create a CommDebugMode context manager to count functional collective operations in a PyTorch distributed training loop', 'test the CommDebugMode.get_total_counts method to return the sum of all collective communication counts', 'test the CommDebugMode.get_comm_counts method to return a dictionary of per-operation communication counts', "run a PyTorch model's backward pass inside a CommDebugMode context to track all_gather_into_tensor and all_reduce calls", 'review the CommDebugMode.__torch_dispatch__ method that intercepts functional collectives and increments their counts', 'summarize the operator coverage of a PyTorch model against DTensor sharding support', 'get the forward and backward graphs of a PyTorch model with inductor decompositions', 'print a tabulated operator coverage summary for a PyTorch model with DTensor support flags', 'run operator coverage analysis and output results to a CSV file for a PyTorch model', 'test which operators used by a PyTorch model are supported by DTensor sharding propagator', 'visualize the sharding layout of a 1D or 2D DTensor across a device mesh', 'compute the local shape and global offset of a DTensor shard for a given device coordinate', 'create a device-to-coordinate map from a DeviceMesh for a given device type', 'convert tensor shard offsets into row and column range blocks for tabulate rendering', 'create a formatted tabulate table showing DTensor sharding across devices']
```

Usage

```
{'summarize_op_coverage': 'summarize the operator coverage of a PyTorch model against DTensor sharding support', 'get_inductor_decomp_graphs': 'get the forward and backward graphs of a PyTorch model with inductor decompositions', 'print_op_coverage_summary': 'print a tabulated operator coverage summary for a PyTorch model with DTensor support flags', 'run_op_coverage_csv': 'run operator coverage analysis and output results to a CSV file for a PyTorch model', 'test_dtensor_op_support': 'test which operators used by a PyTorch model are supported by DTensor sharding propagator'}
```

## File: pytorch_pytorch/torch/distributed/_tensor/debug/visualize_sharding.py

Prompts

```
['create a CommDebugMode context manager to count functional collective operations in a PyTorch distributed training loop', 'test the CommDebugMode.get_total_counts method to return the sum of all collective communication counts', 'test the CommDebugMode.get_comm_counts method to return a dictionary of per-operation communication counts', "run a PyTorch model's backward pass inside a CommDebugMode context to track all_gather_into_tensor and all_reduce calls", 'review the CommDebugMode.__torch_dispatch__ method that intercepts functional collectives and increments their counts', 'summarize the operator coverage of a PyTorch model against DTensor sharding support', 'get the forward and backward graphs of a PyTorch model with inductor decompositions', 'print a tabulated operator coverage summary for a PyTorch model with DTensor support flags', 'run operator coverage analysis and output results to a CSV file for a PyTorch model', 'test which operators used by a PyTorch model are supported by DTensor sharding propagator', 'visualize the sharding layout of a 1D or 2D DTensor across a device mesh', 'compute the local shape and global offset of a DTensor shard for a given device coordinate', 'create a device-to-coordinate map from a DeviceMesh for a given device type', 'convert tensor shard offsets into row and column range blocks for tabulate rendering', 'create a formatted tabulate table showing DTensor sharding across devices']
```

Usage

```
{'visualize_sharding_dtensor': 'visualize the sharding layout of a 1D or 2D DTensor across a device mesh', 'compute_local_shape_and_global_offset': 'compute the local shape and global offset of a DTensor shard for a given device coordinate', 'create_device_coordinate_map': 'create a device-to-coordinate map from a DeviceMesh for a given device type', 'convert_offsets_to_table_blocks': 'convert tensor shard offsets into row and column range blocks for tabulate rendering', 'create_sharding_table': 'create a formatted tabulate table showing DTensor sharding across devices'}
```

