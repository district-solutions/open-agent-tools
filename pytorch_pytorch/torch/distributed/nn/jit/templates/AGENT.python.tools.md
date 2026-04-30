# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/nn/jit/templates/remote_module_template.py

Prompts

```
['build a remote module template using get_remote_module_template with cuda tensor device handling enabled', 'create a forward_async method that uses rpc.rpc_async to call a remote module on another worker', 'create a forward method that calls rpc.rpc_async and waits for the result from a remote module', 'test the _remote_forward template with cuda device handling for moving cpu tensors to cuda', 'summarize the _remote_forward template for simple remote calls without device mapping']
```

Usage

```
{'build_remote_module_template': 'build a remote module template using get_remote_module_template with cuda tensor device handling enabled', 'create_forward_async_method': 'create a forward_async method that uses rpc.rpc_async to call a remote module on another worker', 'create_forward_method': 'create a forward method that calls rpc.rpc_async and waits for the result from a remote module', 'test_remote_forward_cuda': 'test the _remote_forward template with cuda device handling for moving cpu tensors to cuda', 'summarize_remote_forward_template': 'summarize the _remote_forward template for simple remote calls without device mapping'}
```

