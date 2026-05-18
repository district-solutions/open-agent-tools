# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/mmcv/onnx/info.py

Prompts

```
['call is_custom_op_loaded to check if TensorRT or ONNXRuntime custom ops are available', 'review is_custom_op_loaded which checks for TensorRT plugins or ONNXRuntime op library existence', 'test is_custom_op_loaded to verify it returns True when custom ops are installed', 'refactor is_custom_op_loaded to remove the deprecation warning and migrate to MMDeploy', 'summarize is_custom_op_loaded which probes TensorRT and ONNXRuntime for loaded custom operators', 'register custom ONNX symbolic ops for one_hot, im2col, topk, softmax, pooling, upsample, and padding operations', 'build an ONNX symbolic function that converts image patches to column format using gather and reshape operations', 'create an ONNX symbolic softmax operator that supports dynamic dimensions and optional dtype casting', 'build an ONNX symbolic grid sampler operator with configurable interpolation mode, padding mode, and align corners', 'create an ONNX symbolic roll operator that shifts tensor elements along specified dimensions with dynamic slicing', 'build an ONNX symbolic topk operator that returns the k largest or smallest values along a given dimension']
```

Usage

```
{'check_custom_op_loaded': 'call is_custom_op_loaded to check if TensorRT or ONNXRuntime custom ops are available', 'review_is_custom_op_loaded': 'review is_custom_op_loaded which checks for TensorRT plugins or ONNXRuntime op library existence', 'test_is_custom_op_loaded': 'test is_custom_op_loaded to verify it returns True when custom ops are installed', 'refactor_is_custom_op_loaded': 'refactor is_custom_op_loaded to remove the deprecation warning and migrate to MMDeploy', 'summarize_is_custom_op_loaded': 'summarize is_custom_op_loaded which probes TensorRT and ONNXRuntime for loaded custom operators'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/onnx/symbolic.py

Prompts

```
['call is_custom_op_loaded to check if TensorRT or ONNXRuntime custom ops are available', 'review is_custom_op_loaded which checks for TensorRT plugins or ONNXRuntime op library existence', 'test is_custom_op_loaded to verify it returns True when custom ops are installed', 'refactor is_custom_op_loaded to remove the deprecation warning and migrate to MMDeploy', 'summarize is_custom_op_loaded which probes TensorRT and ONNXRuntime for loaded custom operators', 'register custom ONNX symbolic ops for one_hot, im2col, topk, softmax, pooling, upsample, and padding operations', 'build an ONNX symbolic function that converts image patches to column format using gather and reshape operations', 'create an ONNX symbolic softmax operator that supports dynamic dimensions and optional dtype casting', 'build an ONNX symbolic grid sampler operator with configurable interpolation mode, padding mode, and align corners', 'create an ONNX symbolic roll operator that shifts tensor elements along specified dimensions with dynamic slicing', 'build an ONNX symbolic topk operator that returns the k largest or smallest values along a given dimension']
```

Usage

```
{'register_extra_symbolics': 'register custom ONNX symbolic ops for one_hot, im2col, topk, softmax, pooling, upsample, and padding operations', 'im2col': 'build an ONNX symbolic function that converts image patches to column format using gather and reshape operations', 'softmax': 'create an ONNX symbolic softmax operator that supports dynamic dimensions and optional dtype casting', 'grid_sampler': 'build an ONNX symbolic grid sampler operator with configurable interpolation mode, padding mode, and align corners', 'roll': 'create an ONNX symbolic roll operator that shifts tensor elements along specified dimensions with dynamic slicing', 'topk': 'build an ONNX symbolic topk operator that returns the k largest or smallest values along a given dimension'}
```

