# Agent Python Tools

- repo: facebookresearch/kill-the-bits
- repo_uri: https://github.com/facebookresearch/kill-the-bits

## File: facebookresearch_kill-the-bits/src/inference.py

Prompts

```
['run inference on a quantized ResNet model using a compressed state dict and print top-1 accuracy', 'run inference on a quantized ResNet18 model using CPU instead of GPU', 'run inference on a quantized semi-supervised ResNet50 model with non-compressed layers', 'test the to_device function that moves all tensors in a state dict to a specified device', 'review the main function that reconstructs weights from centroids and assignments then evaluates accuracy']
```

Usage

```
{'run_quantized_model_inference': 'run inference on a quantized ResNet model using a compressed state dict and print top-1 accuracy', 'run_inference_on_cpu': 'run inference on a quantized ResNet18 model using CPU instead of GPU', 'run_inference_resnet50_semisup': 'run inference on a quantized semi-supervised ResNet50 model with non-compressed layers', 'test_to_device': 'test the to_device function that moves all tensors in a state dict to a specified device', 'review_main_inference_flow': 'review the main function that reconstructs weights from centroids and assignments then evaluates accuracy'}
```

