# Agent Python Tools

- repo: huggingface/optimum-habana
- repo_uri: https://github.com/huggingface/optimum-habana

## File: huggingface_optimum-habana/examples/pytorch-image-models/inference.py

Prompts

```
['run a TIMM model inference on a dataset using Gaudi2 HPU device with graph mode', 'run image classification inference with mixed precision AMP on HPU using float16 or bfloat16', 'run a TIMM model inference with torchscript compilation for optimized performance on HPU', 'run a TIMM model inference with torch.compile inductor backend for optimized performance', 'save inference results to CSV, JSON, or Parquet format with top-k class predictions and probabilities', 'run a TIMM model training loop on Intel Gaudi2 HPU devices using the argparse CLI', 'run one epoch of training with gradient accumulation, AMP, and EMA model updates', 'run validation on a TIMM model and return loss, top1, and top5 accuracy metrics', 'run argument parsing that loads YAML config files and merges with CLI overrides', 'run distributed process group cleanup after training completes', 'run validation on a trained model and compute loss, top1, and top5 accuracy metrics', 'run cleanup to destroy the distributed process group after training completes']
```

Usage

```
{'run_timm_inference_gaudi2': 'run a TIMM model inference on a dataset using Gaudi2 HPU device with graph mode', 'run_inference_mixed_precision': 'run image classification inference with mixed precision AMP on HPU using float16 or bfloat16', 'run_inference_torchscript': 'run a TIMM model inference with torchscript compilation for optimized performance on HPU', 'run_inference_torchcompile': 'run a TIMM model inference with torch.compile inductor backend for optimized performance', 'save_results_csv_json_parquet': 'save inference results to CSV, JSON, or Parquet format with top-k class predictions and probabilities'}
```

## File: huggingface_optimum-habana/examples/pytorch-image-models/train_hpu_graph.py

Prompts

```
['run a TIMM model inference on a dataset using Gaudi2 HPU device with graph mode', 'run image classification inference with mixed precision AMP on HPU using float16 or bfloat16', 'run a TIMM model inference with torchscript compilation for optimized performance on HPU', 'run a TIMM model inference with torch.compile inductor backend for optimized performance', 'save inference results to CSV, JSON, or Parquet format with top-k class predictions and probabilities', 'run a TIMM model training loop on Intel Gaudi2 HPU devices using the argparse CLI', 'run one epoch of training with gradient accumulation, AMP, and EMA model updates', 'run validation on a TIMM model and return loss, top1, and top5 accuracy metrics', 'run argument parsing that loads YAML config files and merges with CLI overrides', 'run distributed process group cleanup after training completes', 'run validation on a trained model and compute loss, top1, and top5 accuracy metrics', 'run cleanup to destroy the distributed process group after training completes']
```

Usage

```
{'run_timm_training_hpu': 'run a TIMM model training loop on Intel Gaudi2 HPU devices using the argparse CLI', 'run_train_one_epoch': 'run one epoch of training with gradient accumulation, AMP, and EMA model updates', 'run_validate': 'run validation on a TIMM model and return loss, top1, and top5 accuracy metrics', 'run_parse_args': 'run argument parsing that loads YAML config files and merges with CLI overrides', 'run_cleanup': 'run distributed process group cleanup after training completes'}
```

## File: huggingface_optimum-habana/examples/pytorch-image-models/train_hpu_lazy.py

Prompts

```
['run a TIMM model inference on a dataset using Gaudi2 HPU device with graph mode', 'run image classification inference with mixed precision AMP on HPU using float16 or bfloat16', 'run a TIMM model inference with torchscript compilation for optimized performance on HPU', 'run a TIMM model inference with torch.compile inductor backend for optimized performance', 'save inference results to CSV, JSON, or Parquet format with top-k class predictions and probabilities', 'run a TIMM model training loop on Intel Gaudi2 HPU devices using the argparse CLI', 'run one epoch of training with gradient accumulation, AMP, and EMA model updates', 'run validation on a TIMM model and return loss, top1, and top5 accuracy metrics', 'run argument parsing that loads YAML config files and merges with CLI overrides', 'run distributed process group cleanup after training completes', 'run validation on a trained model and compute loss, top1, and top5 accuracy metrics', 'run cleanup to destroy the distributed process group after training completes']
```

Usage

```
{'run_timm_training_hpu': 'run a pytorch timm model training script on Intel Gaudi2 HPU devices with lazy mode', 'run_train_one_epoch': 'run one epoch of model training with gradient accumulation and HPU mark_step synchronization', 'run_validate_model': 'run validation on a trained model and compute loss, top1, and top5 accuracy metrics', 'run_parse_args': 'run the argument parser to load YAML config and CLI arguments for training setup', 'run_cleanup_distributed': 'run cleanup to destroy the distributed process group after training completes'}
```

