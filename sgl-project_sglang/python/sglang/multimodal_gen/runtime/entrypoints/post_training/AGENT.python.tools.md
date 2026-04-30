# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/multimodal_gen/runtime/entrypoints/post_training/utils.py

Prompts

```
['create a function that serializes a PyTorch tensor to a base64-encoded string via safetensors', 'build a function that deserializes a base64-encoded safetensors string back into a PyTorch tensor', 'test the recursive serialization of dicts, lists, and tensors into JSON-safe structures', 'test the recursive deserialization of JSON-safe structures back into PyTorch tensors', 'summarize how tensors are round-tripped through base64-encoded safetensors for HTTP response serialization']
```

Usage

```
{'create_tensor_to_base64': 'create a function that serializes a PyTorch tensor to a base64-encoded string via safetensors', 'build_base64_to_tensor': 'build a function that deserializes a base64-encoded safetensors string back into a PyTorch tensor', 'test_maybe_serialize': 'test the recursive serialization of dicts, lists, and tensors into JSON-safe structures', 'test_maybe_deserialize': 'test the recursive deserialization of JSON-safe structures back into PyTorch tensors', 'summarize_tensor_serialization': 'summarize how tensors are round-tripped through base64-encoded safetensors for HTTP response serialization'}
```

