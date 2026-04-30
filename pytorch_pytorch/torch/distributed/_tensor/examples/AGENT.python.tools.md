# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/_tensor/examples/checkpoint_example.py

Prompts

```
['build a tensor-parallel model by sharding parameters with parallelize_module and ColwiseParallel', 'create a 2D replicated and sharded model using distribute_module with Replicate and Shard placements', 'test a model with parameters sharded only on a sub-mesh using distribute_module', 'run a distributed checkpoint example with DTensor model parameters across a device mesh', 'spawn distributed workers with mp.spawn to run a checkpoint example across multiple processes', 'build a ConvNeXt neural network model with configurable depths, dims, and number of classes', 'create a LayerNorm module that normalizes activations across channel dimensions with learnable weight and bias', 'create a ConvNeXt Block with depthwise conv, pointwise convs, GELU activation, and layer normalization', 'test training a ConvNeXt model with DTensor sharding across multiple GPUs using DeviceMesh', 'distribute a PyTorch module across a DeviceMesh with replicated parameters via distribute_module']
```

Usage

```
{'build_tensor_parallel_model': 'build a tensor-parallel model by sharding parameters with parallelize_module and ColwiseParallel', 'create_partial_replicate_2d_model': 'create a 2D replicated and sharded model using distribute_module with Replicate and Shard placements', 'test_model_in_submesh': 'test a model with parameters sharded only on a sub-mesh using distribute_module', 'run_checkpoint_example': 'run a distributed checkpoint example with DTensor model parameters across a device mesh', 'spawn_distributed_workers': 'spawn distributed workers with mp.spawn to run a checkpoint example across multiple processes'}
```

## File: pytorch_pytorch/torch/distributed/_tensor/examples/convnext_example.py

Prompts

```
['build a tensor-parallel model by sharding parameters with parallelize_module and ColwiseParallel', 'create a 2D replicated and sharded model using distribute_module with Replicate and Shard placements', 'test a model with parameters sharded only on a sub-mesh using distribute_module', 'run a distributed checkpoint example with DTensor model parameters across a device mesh', 'spawn distributed workers with mp.spawn to run a checkpoint example across multiple processes', 'build a ConvNeXt neural network model with configurable depths, dims, and number of classes', 'create a LayerNorm module that normalizes activations across channel dimensions with learnable weight and bias', 'create a ConvNeXt Block with depthwise conv, pointwise convs, GELU activation, and layer normalization', 'test training a ConvNeXt model with DTensor sharding across multiple GPUs using DeviceMesh', 'distribute a PyTorch module across a DeviceMesh with replicated parameters via distribute_module']
```

Usage

```
{'build_convnext_model': 'build a ConvNeXt neural network model with configurable depths, dims, and number of classes', 'create_layer_norm': 'create a LayerNorm module that normalizes activations across channel dimensions with learnable weight and bias', 'create_block': 'create a ConvNeXt Block with depthwise conv, pointwise convs, GELU activation, and layer normalization', 'test_distributed_train': 'test training a ConvNeXt model with DTensor sharding across multiple GPUs using DeviceMesh', 'distribute_module': 'distribute a PyTorch module across a DeviceMesh with replicated parameters via distribute_module'}
```

