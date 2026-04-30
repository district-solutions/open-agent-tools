# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/connector/serde/safe_serde.py

Prompts

```
['create a SafeSerializer instance to serialize PyTorch tensors to safe tensor bytes', 'build bytes from a PyTorch tensor using SafeSerializer.to_bytes with CPU-contiguous conversion', 'create a SafeDeserializer instance to deserialize safe tensor bytes back to PyTorch tensors as float32', 'test the SafeDeserializer.from_bytes_normal method to convert bytes to a float32 tensor', 'test the SafeDeserializer.from_bytes method to convert bytes to a float32 tensor', 'create a Serializer subclass that converts a PyTorch tensor to bytes with shape and dtype metadata', 'build a Deserializer subclass that reconstructs a PyTorch tensor from serialized bytes', 'test the Serializer.to_bytes method with tensors of varying shapes, dtypes, and devices', 'test the Deserializer.from_bytes method to verify round-trip tensor serialization and deserialization', 'review the Serializer and Deserializer base classes for proper abstract method enforcement and dtype handling']
```

Usage

```
{'create_SafeSerializer': 'create a SafeSerializer instance to serialize PyTorch tensors to safe tensor bytes', 'build_SafeSerializer_to_bytes': 'build bytes from a PyTorch tensor using SafeSerializer.to_bytes with CPU-contiguous conversion', 'create_SafeDeserializer': 'create a SafeDeserializer instance to deserialize safe tensor bytes back to PyTorch tensors as float32', 'test_SafeDeserializer_from_bytes_normal': 'test the SafeDeserializer.from_bytes_normal method to convert bytes to a float32 tensor', 'test_SafeDeserializer_from_bytes': 'test the SafeDeserializer.from_bytes method to convert bytes to a float32 tensor'}
```

## File: sgl-project_sglang/python/sglang/srt/connector/serde/serde.py

Prompts

```
['create a SafeSerializer instance to serialize PyTorch tensors to safe tensor bytes', 'build bytes from a PyTorch tensor using SafeSerializer.to_bytes with CPU-contiguous conversion', 'create a SafeDeserializer instance to deserialize safe tensor bytes back to PyTorch tensors as float32', 'test the SafeDeserializer.from_bytes_normal method to convert bytes to a float32 tensor', 'test the SafeDeserializer.from_bytes method to convert bytes to a float32 tensor', 'create a Serializer subclass that converts a PyTorch tensor to bytes with shape and dtype metadata', 'build a Deserializer subclass that reconstructs a PyTorch tensor from serialized bytes', 'test the Serializer.to_bytes method with tensors of varying shapes, dtypes, and devices', 'test the Deserializer.from_bytes method to verify round-trip tensor serialization and deserialization', 'review the Serializer and Deserializer base classes for proper abstract method enforcement and dtype handling']
```

Usage

```
{'create_serializer': 'create a Serializer subclass that converts a PyTorch tensor to bytes with shape and dtype metadata', 'build_deserializer': 'build a Deserializer subclass that reconstructs a PyTorch tensor from serialized bytes', 'test_to_bytes': 'test the Serializer.to_bytes method with tensors of varying shapes, dtypes, and devices', 'test_from_bytes': 'test the Deserializer.from_bytes method to verify round-trip tensor serialization and deserialization', 'review_serializer_deserializer': 'review the Serializer and Deserializer base classes for proper abstract method enforcement and dtype handling'}
```

