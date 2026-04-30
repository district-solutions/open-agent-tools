# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/_export/pass_infra/node_metadata.py

Prompts

```
['create a NodeMetadata instance with an initial dictionary of node metadata values', 'test the NodeMetadata __getitem__ method to retrieve a value by key', 'test the NodeMetadata __setitem__ method to set a value and verify protected keys raise RuntimeError', 'test the NodeMetadata __contains__ method to check if a key exists in the metadata', 'test the NodeMetadata copy method to create an independent copy of the metadata', 'create a ProxyValue instance wrapping a torch tensor and an fx proxy or node', 'build access to the underlying torch.fx.Node from a ProxyValue instance', 'test the ProxyValue proxy property raises RuntimeError when no Proxy is attached', 'refactor the ProxyValue to_tensor method to safely extract the wrapped torch.Tensor', 'review the ProxyValue is_tensor method to check if wrapped data is a torch.Tensor']
```

Usage

```
{'create_NodeMetadata': 'create a NodeMetadata instance with an initial dictionary of node metadata values', 'test_NodeMetadata_getitem': 'test the NodeMetadata __getitem__ method to retrieve a value by key', 'test_NodeMetadata_setitem': 'test the NodeMetadata __setitem__ method to set a value and verify protected keys raise RuntimeError', 'test_NodeMetadata_contains': 'test the NodeMetadata __contains__ method to check if a key exists in the metadata', 'test_NodeMetadata_copy': 'test the NodeMetadata copy method to create an independent copy of the metadata'}
```

## File: pytorch_pytorch/torch/_export/pass_infra/proxy_value.py

Prompts

```
['create a NodeMetadata instance with an initial dictionary of node metadata values', 'test the NodeMetadata __getitem__ method to retrieve a value by key', 'test the NodeMetadata __setitem__ method to set a value and verify protected keys raise RuntimeError', 'test the NodeMetadata __contains__ method to check if a key exists in the metadata', 'test the NodeMetadata copy method to create an independent copy of the metadata', 'create a ProxyValue instance wrapping a torch tensor and an fx proxy or node', 'build access to the underlying torch.fx.Node from a ProxyValue instance', 'test the ProxyValue proxy property raises RuntimeError when no Proxy is attached', 'refactor the ProxyValue to_tensor method to safely extract the wrapped torch.Tensor', 'review the ProxyValue is_tensor method to check if wrapped data is a torch.Tensor']
```

Usage

```
{'create_ProxyValue': 'create a ProxyValue instance wrapping a torch tensor and an fx proxy or node', 'build_ProxyValue_node_property': 'build access to the underlying torch.fx.Node from a ProxyValue instance', 'test_ProxyValue_proxy_property': 'test the ProxyValue proxy property raises RuntimeError when no Proxy is attached', 'refactor_ProxyValue_to_tensor': 'refactor the ProxyValue to_tensor method to safely extract the wrapped torch.Tensor', 'review_ProxyValue_is_tensor': 'review the ProxyValue is_tensor method to check if wrapped data is a torch.Tensor'}
```

