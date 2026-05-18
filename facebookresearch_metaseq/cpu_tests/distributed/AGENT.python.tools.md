# Agent Python Tools

- repo: facebookresearch/metaseq
- repo_uri: https://github.com/facebookresearch/metaseq

## File: facebookresearch_metaseq/cpu_tests/distributed/test_module_proxy_wrapper.py

Prompts

```
['test the MockDDPWrapper class to verify it correctly forwards the forward pass to the wrapped module', 'test the Model class to verify the linear layer forward pass produces correct output', 'test the ModuleProxyWrapper to verify attribute get and set operations are correctly forwarded', 'test the ModuleProxyWrapper state_dict method to ensure it returns the same state dict as the underlying module', 'test the ModuleProxyWrapper load_state_dict method to verify it correctly loads weights and produces matching forward output']
```

Usage

```
{'test_MockDDPWrapper_forward': 'test the MockDDPWrapper class to verify it correctly forwards the forward pass to the wrapped module', 'test_Model_forward': 'test the Model class to verify the linear layer forward pass produces correct output', 'test_getattr_forwarding': 'test the ModuleProxyWrapper to verify attribute get and set operations are correctly forwarded', 'test_state_dict': 'test the ModuleProxyWrapper state_dict method to ensure it returns the same state dict as the underlying module', 'test_load_state_dict': 'test the ModuleProxyWrapper load_state_dict method to verify it correctly loads weights and produces matching forward output'}
```

