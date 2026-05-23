# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/pretrain/tools/deployment/pytorch2torchscript.py

Prompts

```
['convert a PyTorch model to TorchScript using a config file and checkpoint via CLI', 'trace a PyTorch model with torch.jit.trace using example inputs and save to file', 'create demo multi-modal inputs with random images and metadata for model testing', 'export an MMPretrain FeatureExtractor model to TorchScript with spatial feature map output', 'verify a TorchScript traced model against the original PyTorch model before saving', 'run the CLI tool to compile and export a PyTorch model with torch.compile optimization', 'benchmark a PyTorch model inference latency using CUDA events and streams', "explain a PyTorch model's dynamo compilation graphs and break reasons", 'convert SyncBatchNorm layers to BatchNorm2d and SiLU activations to ReLU in a model', 'create random demo input tensors for testing or training batches']
```

Usage

```
{'convert_pytorch_to_torchscript': 'convert a PyTorch model to TorchScript using a config file and checkpoint via CLI', 'trace_model_with_jit': 'trace a PyTorch model with torch.jit.trace using example inputs and save to file', 'create_demo_mm_inputs': 'create demo multi-modal inputs with random images and metadata for model testing', 'export_feature_extractor_model': 'export an MMPretrain FeatureExtractor model to TorchScript with spatial feature map output', 'verify_torchscript_trace': 'verify a TorchScript traced model against the original PyTorch model before saving'}
```

## File: facebookresearch_sapiens/pretrain/tools/deployment/torch_optimization.py

Prompts

```
['convert a PyTorch model to TorchScript using a config file and checkpoint via CLI', 'trace a PyTorch model with torch.jit.trace using example inputs and save to file', 'create demo multi-modal inputs with random images and metadata for model testing', 'export an MMPretrain FeatureExtractor model to TorchScript with spatial feature map output', 'verify a TorchScript traced model against the original PyTorch model before saving', 'run the CLI tool to compile and export a PyTorch model with torch.compile optimization', 'benchmark a PyTorch model inference latency using CUDA events and streams', "explain a PyTorch model's dynamo compilation graphs and break reasons", 'convert SyncBatchNorm layers to BatchNorm2d and SiLU activations to ReLU in a model', 'create random demo input tensors for testing or training batches']
```

Usage

```
{'run_torch_compile_model': 'run the CLI tool to compile and export a PyTorch model with torch.compile optimization', 'benchmark_model_inference': 'benchmark a PyTorch model inference latency using CUDA events and streams', 'explain_model_compilation': "explain a PyTorch model's dynamo compilation graphs and break reasons", 'convert_batchnorm_to_relu': 'convert SyncBatchNorm layers to BatchNorm2d and SiLU activations to ReLU in a model', 'create_demo_inputs': 'create random demo input tensors for testing or training batches'}
```

