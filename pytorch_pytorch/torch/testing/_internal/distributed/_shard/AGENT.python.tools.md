# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/testing/_internal/distributed/_shard/test_common.py

Prompts

```
['create a SimpleMegatronLM module with two linear layers, GELU activation, and optional CUDA rank', 'test the SimpleMegatronLM forward pass through fc1, gelu, and fc2 layers', 'build a SimpleMegatronLM instance and extract its weights handling ShardedTensor local tensors', 'test the SimpleMegatronLM get_biases method returning fc1 and fc2 biases', 'review the SimpleMegatronLM get_weight_grads and get_bias_grads methods returning gradients']
```

Usage

```
{'create_SimpleMegatronLM': 'create a SimpleMegatronLM module with two linear layers, GELU activation, and optional CUDA rank', 'test_SimpleMegatronLM_forward': 'test the SimpleMegatronLM forward pass through fc1, gelu, and fc2 layers', 'build_SimpleMegatronLM_weights': 'build a SimpleMegatronLM instance and extract its weights handling ShardedTensor local tensors', 'test_SimpleMegatronLM_biases': 'test the SimpleMegatronLM get_biases method returning fc1 and fc2 biases', 'review_SimpleMegatronLM_grads': 'review the SimpleMegatronLM get_weight_grads and get_bias_grads methods returning gradients'}
```

