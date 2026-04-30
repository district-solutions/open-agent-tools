# Agent Python Tools

- repo: sgl-project/sglang
- repo_uri: https://github.com/sgl-project/sglang

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/npu/graph_runner/npu_graph_runner.py

Prompts

```
['create a NPUGraphRunner class that runs the forward pass of a model with NPU graph and torch.compile', 'run the replay method to execute a captured NPU graph with a forward batch and return logits output', 'build a context manager that patches a model for NPU with optional torch.compile backend', 'test the capture graph method that records a forward pass into an NPU graph with optional torch compile stance', 'refactor the update inputs method to update graph input attributes with sequence lengths for replay', 'create a ViTNpuGraphRunner instance with a vision transformer module for NPU graph capture', 'run the ViTNpuGraphRunner with input tensor, sequence lengths, and rotary embeddings for inference', 'create a NPU graph for the ViT blocks and merger given input shape and sequence lengths', 'replay a captured NPU graph with updated input and rotary embedding data', 'create a NPU graph capturing ViT transformer blocks with optional deepstack merger outputs']
```

Usage

```
{'create_class_npu_graph_runner': 'create a NPUGraphRunner class that runs the forward pass of a model with NPU graph and torch.compile', 'run_method_replay': 'run the replay method to execute a captured NPU graph with a forward batch and return logits output', 'build_function_patch_model_npu': 'build a context manager that patches a model for NPU with optional torch.compile backend', 'test_method_capture_graph': 'test the capture graph method that records a forward pass into an NPU graph with optional torch compile stance', 'refactor_method_update_inputs': 'refactor the update inputs method to update graph input attributes with sequence lengths for replay'}
```

## File: sgl-project_sglang/python/sglang/srt/hardware_backend/npu/graph_runner/vit_npu_graph_runner.py

Prompts

```
['create a NPUGraphRunner class that runs the forward pass of a model with NPU graph and torch.compile', 'run the replay method to execute a captured NPU graph with a forward batch and return logits output', 'build a context manager that patches a model for NPU with optional torch.compile backend', 'test the capture graph method that records a forward pass into an NPU graph with optional torch compile stance', 'refactor the update inputs method to update graph input attributes with sequence lengths for replay', 'create a ViTNpuGraphRunner instance with a vision transformer module for NPU graph capture', 'run the ViTNpuGraphRunner with input tensor, sequence lengths, and rotary embeddings for inference', 'create a NPU graph for the ViT blocks and merger given input shape and sequence lengths', 'replay a captured NPU graph with updated input and rotary embedding data', 'create a NPU graph capturing ViT transformer blocks with optional deepstack merger outputs']
```

Usage

```
{'create_ViTNpuGraphRunner': 'create a ViTNpuGraphRunner instance with a vision transformer module for NPU graph capture', 'run_ViTNpuGraphRunner': 'run the ViTNpuGraphRunner with input tensor, sequence lengths, and rotary embeddings for inference', 'create_graph_ViTNpuGraphRunner': 'create a NPU graph for the ViT blocks and merger given input shape and sequence lengths', 'replay_ViTNpuGraphRunner': 'replay a captured NPU graph with updated input and rotary embedding data', '_create_graph_ViTNpuGraphRunner': 'create a NPU graph capturing ViT transformer blocks with optional deepstack merger outputs'}
```

