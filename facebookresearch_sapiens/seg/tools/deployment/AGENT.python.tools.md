# Agent Python Tools

- repo: facebookresearch/sapiens
- repo_uri: https://github.com/facebookresearch/sapiens

## File: facebookresearch_sapiens/seg/tools/deployment/pytorch2torchscript.py

Prompts

```
['convert a MMSegmentation PyTorch model to TorchScript format for deployment with optional verification', 'convert SyncBatchNorm layers to standard BatchNorm2d in a segmentation model for TorchScript compatibility', 'generate dummy image inputs and metadata for testing a segmentation model with specified shape and classes', 'parse command line arguments for config path, checkpoint, output file, and input shape parameters', 'check that the installed PyTorch version meets the minimum requirement of 1.8.0 for TorchScript export', 'run the sparsification CLI tool to sparsify an MMSeg model checkpoint and save it', 'apply 2:4 fake sparsity to all linear layers in a PyTorch model using WeightNormSparsifier', 'apply 2:4 sparsity and convert linear layer weights to sparse semi-structured tensors', 'parse command line arguments for the MMSeg model sparsification tool', 'load an MMSeg model from config and checkpoint, sparsify it, and save the sparse checkpoint', 'compile a PyTorch segmentation model with torch.compile using default, reduce-overhead, or max-autotune modes and save the exported model', "benchmark a segmentation model's inference latency on CUDA using timed events and multiple warmup iterations", 'convert a PyTorch segmentation model to TensorRT with optional INT8 quantization via a calibration dataloader loop', "explain a PyTorch model's dynamo compilation by extracting graphs, graph counts, and break reasons", "fuse Conv-BN-Activation module sequences in a segmentation model's decode head for optimized inference"]
```

Usage

```
{'convert_pytorch_to_torchscript': 'convert a MMSegmentation PyTorch model to TorchScript format for deployment with optional verification', 'convert_syncbatchnorm_to_batchnorm': 'convert SyncBatchNorm layers to standard BatchNorm2d in a segmentation model for TorchScript compatibility', 'generate_demo_inputs': 'generate dummy image inputs and metadata for testing a segmentation model with specified shape and classes', 'parse_cli_args': 'parse command line arguments for config path, checkpoint, output file, and input shape parameters', 'check_torch_version': 'check that the installed PyTorch version meets the minimum requirement of 1.8.0 for TorchScript export'}
```

## File: facebookresearch_sapiens/seg/tools/deployment/sparsification.py

Prompts

```
['convert a MMSegmentation PyTorch model to TorchScript format for deployment with optional verification', 'convert SyncBatchNorm layers to standard BatchNorm2d in a segmentation model for TorchScript compatibility', 'generate dummy image inputs and metadata for testing a segmentation model with specified shape and classes', 'parse command line arguments for config path, checkpoint, output file, and input shape parameters', 'check that the installed PyTorch version meets the minimum requirement of 1.8.0 for TorchScript export', 'run the sparsification CLI tool to sparsify an MMSeg model checkpoint and save it', 'apply 2:4 fake sparsity to all linear layers in a PyTorch model using WeightNormSparsifier', 'apply 2:4 sparsity and convert linear layer weights to sparse semi-structured tensors', 'parse command line arguments for the MMSeg model sparsification tool', 'load an MMSeg model from config and checkpoint, sparsify it, and save the sparse checkpoint', 'compile a PyTorch segmentation model with torch.compile using default, reduce-overhead, or max-autotune modes and save the exported model', "benchmark a segmentation model's inference latency on CUDA using timed events and multiple warmup iterations", 'convert a PyTorch segmentation model to TensorRT with optional INT8 quantization via a calibration dataloader loop', "explain a PyTorch model's dynamo compilation by extracting graphs, graph counts, and break reasons", "fuse Conv-BN-Activation module sequences in a segmentation model's decode head for optimized inference"]
```

Usage

```
{'run_sparsification_cli': 'run the sparsification CLI tool to sparsify an MMSeg model checkpoint and save it', 'apply_fake_sparsity': 'apply 2:4 fake sparsity to all linear layers in a PyTorch model using WeightNormSparsifier', 'apply_sparse': 'apply 2:4 sparsity and convert linear layer weights to sparse semi-structured tensors', 'parse_args': 'parse command line arguments for the MMSeg model sparsification tool', 'main': 'load an MMSeg model from config and checkpoint, sparsify it, and save the sparse checkpoint'}
```

## File: facebookresearch_sapiens/seg/tools/deployment/torch_optimization.py

Prompts

```
['convert a MMSegmentation PyTorch model to TorchScript format for deployment with optional verification', 'convert SyncBatchNorm layers to standard BatchNorm2d in a segmentation model for TorchScript compatibility', 'generate dummy image inputs and metadata for testing a segmentation model with specified shape and classes', 'parse command line arguments for config path, checkpoint, output file, and input shape parameters', 'check that the installed PyTorch version meets the minimum requirement of 1.8.0 for TorchScript export', 'run the sparsification CLI tool to sparsify an MMSeg model checkpoint and save it', 'apply 2:4 fake sparsity to all linear layers in a PyTorch model using WeightNormSparsifier', 'apply 2:4 sparsity and convert linear layer weights to sparse semi-structured tensors', 'parse command line arguments for the MMSeg model sparsification tool', 'load an MMSeg model from config and checkpoint, sparsify it, and save the sparse checkpoint', 'compile a PyTorch segmentation model with torch.compile using default, reduce-overhead, or max-autotune modes and save the exported model', "benchmark a segmentation model's inference latency on CUDA using timed events and multiple warmup iterations", 'convert a PyTorch segmentation model to TensorRT with optional INT8 quantization via a calibration dataloader loop', "explain a PyTorch model's dynamo compilation by extracting graphs, graph counts, and break reasons", "fuse Conv-BN-Activation module sequences in a segmentation model's decode head for optimized inference"]
```

Usage

```
{'compile_model_torch_compile': 'compile a PyTorch segmentation model with torch.compile using default, reduce-overhead, or max-autotune modes and save the exported model', 'benchmark_model_inference': "benchmark a segmentation model's inference latency on CUDA using timed events and multiple warmup iterations", 'convert_to_tensorrt': 'convert a PyTorch segmentation model to TensorRT with optional INT8 quantization via a calibration dataloader loop', 'explain_model_dynamo': "explain a PyTorch model's dynamo compilation by extracting graphs, graph counts, and break reasons", 'fuse_model_modules': "fuse Conv-BN-Activation module sequences in a segmentation model's decode head for optimized inference"}
```

