# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/distributed/nn/api/remote_module.py

Prompts

```
['create a RemoteModule that instantiates an nn.Linear layer on a remote worker over RPC', 'create a TorchScript-able RemoteModule with a module interface class on a remote worker', 'initialize a RemoteModule from an existing module RRef to share the same underlying remote module', 'get a list of RRef pointers to remote module parameters for use with DistributedOptimizer', 'run a RemoteModule forward pass asynchronously and return a Future for the remote computation result']
```

Usage

```
{'create_remote_module': 'create a RemoteModule that instantiates an nn.Linear layer on a remote worker over RPC', 'create_remote_module_scriptable': 'create a TorchScript-able RemoteModule with a module interface class on a remote worker', 'init_remote_module_from_rref': 'initialize a RemoteModule from an existing module RRef to share the same underlying remote module', 'get_remote_parameters': 'get a list of RRef pointers to remote module parameters for use with DistributedOptimizer', 'run_forward_async': 'run a RemoteModule forward pass asynchronously and return a Future for the remote computation result'}
```

