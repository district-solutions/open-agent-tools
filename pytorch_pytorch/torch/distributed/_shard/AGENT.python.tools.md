# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/_shard/_utils.py

Prompts

```
['narrow a torch tensor by index using offsets and sizes sequences to extract a shard', 'narrow a torch tensor using ShardMetadata to extract shard offsets and sizes', 'test narrow_tensor_by_index with a torch tensor, offsets, and sizes', 'test narrow_tensor with a torch tensor and ShardMetadata object', 'refactor narrow_tensor_by_index to support additional dimension narrowing logic', 'build a function to shard a contiguous torch.Tensor according to a ChunkShardingSpec across distributed ranks', 'create a function to shard a module parameter in-place by replacing it with a ShardedTensor', 'test the shard_module function that shards all module parameters and hooks outputs per a ShardingPlan', 'refactor the load_with_process_group context manager to set the process group for loading a ShardedTensor', 'summarize the _collect_local_shard function that hooks a module to convert ShardedTensor output back to a local tensor', 'test the _basic_validation function validates that distributed tensor ops have inputs and at least one ShardedTensor', 'review the _basic_validation function ensures all ShardedTensors in args and kwargs share the same ProcessGroup', 'summarize the _basic_validation function that checks for input arguments and uniform ProcessGroup across distributed tensors', 'test the _register_default_op function registers a default op that dispatches via __torch_function__ with DisableTorchFunctionSubclass', 'summarize the _register_default_op function that wraps ops to bypass torch function subclass dispatch and avoid recursion', 'build a python class that extends Sharder to implement a custom sharding strategy for nn.Module', 'create a Sharder subclass that implements the shard method to partition an nn.Module across processes', 'test the Sharder abstract base class and its shard method interface', 'refactor the Sharder class to support additional sharding parameters beyond the nn.Module input', 'review the Sharder.shard abstract method signature and its nn.Module input/output contract']
```

Usage

```
{'narrow_tensor_by_index': 'narrow a torch tensor by index using offsets and sizes sequences to extract a shard', 'narrow_tensor': 'narrow a torch tensor using ShardMetadata to extract shard offsets and sizes', 'test_narrow_tensor_by_index': 'test narrow_tensor_by_index with a torch tensor, offsets, and sizes', 'test_narrow_tensor': 'test narrow_tensor with a torch tensor and ShardMetadata object', 'refactor_narrow_tensor_by_index': 'refactor narrow_tensor_by_index to support additional dimension narrowing logic'}
```

## File: pytorch_pytorch/torch/distributed/_shard/api.py

Prompts

```
['narrow a torch tensor by index using offsets and sizes sequences to extract a shard', 'narrow a torch tensor using ShardMetadata to extract shard offsets and sizes', 'test narrow_tensor_by_index with a torch tensor, offsets, and sizes', 'test narrow_tensor with a torch tensor and ShardMetadata object', 'refactor narrow_tensor_by_index to support additional dimension narrowing logic', 'build a function to shard a contiguous torch.Tensor according to a ChunkShardingSpec across distributed ranks', 'create a function to shard a module parameter in-place by replacing it with a ShardedTensor', 'test the shard_module function that shards all module parameters and hooks outputs per a ShardingPlan', 'refactor the load_with_process_group context manager to set the process group for loading a ShardedTensor', 'summarize the _collect_local_shard function that hooks a module to convert ShardedTensor output back to a local tensor', 'test the _basic_validation function validates that distributed tensor ops have inputs and at least one ShardedTensor', 'review the _basic_validation function ensures all ShardedTensors in args and kwargs share the same ProcessGroup', 'summarize the _basic_validation function that checks for input arguments and uniform ProcessGroup across distributed tensors', 'test the _register_default_op function registers a default op that dispatches via __torch_function__ with DisableTorchFunctionSubclass', 'summarize the _register_default_op function that wraps ops to bypass torch function subclass dispatch and avoid recursion', 'build a python class that extends Sharder to implement a custom sharding strategy for nn.Module', 'create a Sharder subclass that implements the shard method to partition an nn.Module across processes', 'test the Sharder abstract base class and its shard method interface', 'refactor the Sharder class to support additional sharding parameters beyond the nn.Module input', 'review the Sharder.shard abstract method signature and its nn.Module input/output contract']
```

Usage

```
{'build_shard_tensor': 'build a function to shard a contiguous torch.Tensor according to a ChunkShardingSpec across distributed ranks', 'create_shard_parameter': 'create a function to shard a module parameter in-place by replacing it with a ShardedTensor', 'test_shard_module': 'test the shard_module function that shards all module parameters and hooks outputs per a ShardingPlan', 'refactor_load_with_process_group': 'refactor the load_with_process_group context manager to set the process group for loading a ShardedTensor', 'summarize_collect_local_shard': 'summarize the _collect_local_shard function that hooks a module to convert ShardedTensor output back to a local tensor'}
```

## File: pytorch_pytorch/torch/distributed/_shard/common_op_utils.py

Prompts

```
['narrow a torch tensor by index using offsets and sizes sequences to extract a shard', 'narrow a torch tensor using ShardMetadata to extract shard offsets and sizes', 'test narrow_tensor_by_index with a torch tensor, offsets, and sizes', 'test narrow_tensor with a torch tensor and ShardMetadata object', 'refactor narrow_tensor_by_index to support additional dimension narrowing logic', 'build a function to shard a contiguous torch.Tensor according to a ChunkShardingSpec across distributed ranks', 'create a function to shard a module parameter in-place by replacing it with a ShardedTensor', 'test the shard_module function that shards all module parameters and hooks outputs per a ShardingPlan', 'refactor the load_with_process_group context manager to set the process group for loading a ShardedTensor', 'summarize the _collect_local_shard function that hooks a module to convert ShardedTensor output back to a local tensor', 'test the _basic_validation function validates that distributed tensor ops have inputs and at least one ShardedTensor', 'review the _basic_validation function ensures all ShardedTensors in args and kwargs share the same ProcessGroup', 'summarize the _basic_validation function that checks for input arguments and uniform ProcessGroup across distributed tensors', 'test the _register_default_op function registers a default op that dispatches via __torch_function__ with DisableTorchFunctionSubclass', 'summarize the _register_default_op function that wraps ops to bypass torch function subclass dispatch and avoid recursion', 'build a python class that extends Sharder to implement a custom sharding strategy for nn.Module', 'create a Sharder subclass that implements the shard method to partition an nn.Module across processes', 'test the Sharder abstract base class and its shard method interface', 'refactor the Sharder class to support additional sharding parameters beyond the nn.Module input', 'review the Sharder.shard abstract method signature and its nn.Module input/output contract']
```

Usage

```
{'test_basic_validation': 'test the _basic_validation function validates that distributed tensor ops have inputs and at least one ShardedTensor', 'review_basic_validation': 'review the _basic_validation function ensures all ShardedTensors in args and kwargs share the same ProcessGroup', 'summarize_basic_validation': 'summarize the _basic_validation function that checks for input arguments and uniform ProcessGroup across distributed tensors', 'test_register_default_op': 'test the _register_default_op function registers a default op that dispatches via __torch_function__ with DisableTorchFunctionSubclass', 'summarize_register_default_op': 'summarize the _register_default_op function that wraps ops to bypass torch function subclass dispatch and avoid recursion'}
```

## File: pytorch_pytorch/torch/distributed/_shard/sharder.py

Prompts

```
['narrow a torch tensor by index using offsets and sizes sequences to extract a shard', 'narrow a torch tensor using ShardMetadata to extract shard offsets and sizes', 'test narrow_tensor_by_index with a torch tensor, offsets, and sizes', 'test narrow_tensor with a torch tensor and ShardMetadata object', 'refactor narrow_tensor_by_index to support additional dimension narrowing logic', 'build a function to shard a contiguous torch.Tensor according to a ChunkShardingSpec across distributed ranks', 'create a function to shard a module parameter in-place by replacing it with a ShardedTensor', 'test the shard_module function that shards all module parameters and hooks outputs per a ShardingPlan', 'refactor the load_with_process_group context manager to set the process group for loading a ShardedTensor', 'summarize the _collect_local_shard function that hooks a module to convert ShardedTensor output back to a local tensor', 'test the _basic_validation function validates that distributed tensor ops have inputs and at least one ShardedTensor', 'review the _basic_validation function ensures all ShardedTensors in args and kwargs share the same ProcessGroup', 'summarize the _basic_validation function that checks for input arguments and uniform ProcessGroup across distributed tensors', 'test the _register_default_op function registers a default op that dispatches via __torch_function__ with DisableTorchFunctionSubclass', 'summarize the _register_default_op function that wraps ops to bypass torch function subclass dispatch and avoid recursion', 'build a python class that extends Sharder to implement a custom sharding strategy for nn.Module', 'create a Sharder subclass that implements the shard method to partition an nn.Module across processes', 'test the Sharder abstract base class and its shard method interface', 'refactor the Sharder class to support additional sharding parameters beyond the nn.Module input', 'review the Sharder.shard abstract method signature and its nn.Module input/output contract']
```

Usage

```
{'build_SHARDER': 'build a python class that extends Sharder to implement a custom sharding strategy for nn.Module', 'create_SHARDER_shard': 'create a Sharder subclass that implements the shard method to partition an nn.Module across processes', 'test_SHARDER': 'test the Sharder abstract base class and its shard method interface', 'refactor_SHARDER': 'refactor the Sharder class to support additional sharding parameters beyond the nn.Module input', 'review_SHARDER_shard': 'review the Sharder.shard abstract method signature and its nn.Module input/output contract'}
```

