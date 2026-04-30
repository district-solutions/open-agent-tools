# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/autograd/_functions/tensor.py

Prompts

```
['test the Type.forward method that converts a tensor to a destination data type', 'test the Type.backward method that restores gradient to the original input type', 'test the Resize.forward method that reshapes a tensor while preserving element count', 'test the Resize.backward method that reshapes gradient back to original tensor sizes', 'review the Type.backward method that handles CUDA device context restoration', 'build a function that reshapes a tensor to a given size if sizes differ', 'build a function that reverses tensor expansion by summing over expanded dimensions', 'test the check_onnx_broadcast function for ONNX-compatible broadcasting patterns', 'refactor check_onnx_broadcast to support additional ONNX broadcasting styles', 'review the maybe_unexpand function for correctness on unsqueezed and expanded tensors']
```

Usage

```
{'test_Type_forward': 'test the Type.forward method that converts a tensor to a destination data type', 'test_Type_backward': 'test the Type.backward method that restores gradient to the original input type', 'test_Resize_forward': 'test the Resize.forward method that reshapes a tensor while preserving element count', 'test_Resize_backward': 'test the Resize.backward method that reshapes gradient back to original tensor sizes', 'review_Type_backward': 'review the Type.backward method that handles CUDA device context restoration'}
```

## File: pytorch_pytorch/torch/autograd/_functions/utils.py

Prompts

```
['test the Type.forward method that converts a tensor to a destination data type', 'test the Type.backward method that restores gradient to the original input type', 'test the Resize.forward method that reshapes a tensor while preserving element count', 'test the Resize.backward method that reshapes gradient back to original tensor sizes', 'review the Type.backward method that handles CUDA device context restoration', 'build a function that reshapes a tensor to a given size if sizes differ', 'build a function that reverses tensor expansion by summing over expanded dimensions', 'test the check_onnx_broadcast function for ONNX-compatible broadcasting patterns', 'refactor check_onnx_broadcast to support additional ONNX broadcasting styles', 'review the maybe_unexpand function for correctness on unsqueezed and expanded tensors']
```

Usage

```
{'build_maybe_view': 'build a function that reshapes a tensor to a given size if sizes differ', 'build_maybe_unexpand': 'build a function that reverses tensor expansion by summing over expanded dimensions', 'test_check_onnx_broadcast': 'test the check_onnx_broadcast function for ONNX-compatible broadcasting patterns', 'refactor_check_onnx_broadcast': 'refactor check_onnx_broadcast to support additional ONNX broadcasting styles', 'review_maybe_unexpand': 'review the maybe_unexpand function for correctness on unsqueezed and expanded tensors'}
```

