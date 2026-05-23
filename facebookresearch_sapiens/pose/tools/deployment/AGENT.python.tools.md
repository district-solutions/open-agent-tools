# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pose/tools/deployment/pytorch2torchscript.py

Prompts

```
['convert a PyTorch MMPose model to TorchScript format for deployment', 'export a PyTorch model to TorchScript and verify outputs match between frameworks', 'convert SyncBatchNorm layers to regular BatchNorm2d for TorchScript compatibility', 'create synthetic demo inputs with random images and metadata for model testing', 'check if the installed PyTorch version meets minimum requirements for TorchScript conversion', 'run a benchmark on a pose estimation model to measure average inference time in milliseconds', 'compile a pose estimation model using torch.compile with dynamic batch sizes and save as torch export', "explain a model's torch dynamo compilation to get graphs, graph counts, and break reasons", 'convert SyncBatchNorm layers to BatchNorm2d in a PyTorch module for deployment optimization', 'generate demo input tensors for pose estimation models with bounding boxes and image metadata']
```

Usage

```
{'convert_pytorch_to_torchscript': 'convert a PyTorch MMPose model to TorchScript format for deployment', 'export_model_with_verification': 'export a PyTorch model to TorchScript and verify outputs match between frameworks', 'convert_syncbatchnorm_to_batchnorm': 'convert SyncBatchNorm layers to regular BatchNorm2d for TorchScript compatibility', 'create_demo_inputs_for_testing': 'create synthetic demo inputs with random images and metadata for model testing', 'check_torch_version_compatibility': 'check if the installed PyTorch version meets minimum requirements for TorchScript conversion'}
```

## File: facebookresearch_sapiens/pose/tools/deployment/torch_optimization.py

Prompts

```
['convert a PyTorch MMPose model to TorchScript format for deployment', 'export a PyTorch model to TorchScript and verify outputs match between frameworks', 'convert SyncBatchNorm layers to regular BatchNorm2d for TorchScript compatibility', 'create synthetic demo inputs with random images and metadata for model testing', 'check if the installed PyTorch version meets minimum requirements for TorchScript conversion', 'run a benchmark on a pose estimation model to measure average inference time in milliseconds', 'compile a pose estimation model using torch.compile with dynamic batch sizes and save as torch export', "explain a model's torch dynamo compilation to get graphs, graph counts, and break reasons", 'convert SyncBatchNorm layers to BatchNorm2d in a PyTorch module for deployment optimization', 'generate demo input tensors for pose estimation models with bounding boxes and image metadata']
```

Usage

```
{'benchmark_pose_model': 'run a benchmark on a pose estimation model to measure average inference time in milliseconds', 'compile_pose_model': 'compile a pose estimation model using torch.compile with dynamic batch sizes and save as torch export', 'explain_model_compilation': "explain a model's torch dynamo compilation to get graphs, graph counts, and break reasons", 'convert_batchnorm': 'convert SyncBatchNorm layers to BatchNorm2d in a PyTorch module for deployment optimization', 'generate_demo_inputs': 'generate demo input tensors for pose estimation models with bounding boxes and image metadata'}
```

