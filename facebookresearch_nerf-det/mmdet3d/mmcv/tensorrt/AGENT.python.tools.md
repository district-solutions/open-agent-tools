# Agent Python Tools

- repo: facebookresearch/nerf-det
- repo_uri: https://github.com/facebookresearch/nerf-det

## File: facebookresearch_nerf-det/mmdet3d/mmcv/tensorrt/init_plugins.py

Prompts

```
['get the file path to the TensorRT plugins shared library using glob pattern matching', 'check if the TensorRT plugins library has already been loaded into the current process', 'load the TensorRT plugins shared library into the current process using ctypes CDLL', 'review the deprecation warnings in init_plugins that recommend migrating to MMDeploy', 'refactor the TensorRT plugin loading logic to remove repeated deprecation warning code', 'preprocess an ONNX model to transform NonMaxSuppression inputs into attributes for TensorRT compatibility', 'convert NonMaxSuppression node inputs like max_output_boxes_per_class and iou_threshold into static attributes', 'rename InstanceNormalization ops to MMCVInstanceNormalization for custom TensorRT plugin support', 'remove Constant nodes that were consumed and inlined into NonMaxSuppression attributes during preprocessing', 'review the preprocess_onnx function and its deprecation warning recommending migration to MMDeploy', 'convert an ONNX model file to a TensorRT ICudaEngine with optimization profiles and fp16 mode', 'serialize a TensorRT ICudaEngine to a binary file on disk for later reuse', 'deserialize a TensorRT ICudaEngine from a binary file on disk back into memory', 'convert a TensorRT DataType enum value to its corresponding PyTorch torch.dtype', 'wrap a TensorRT engine in a PyTorch nn.Module to run inference with dict inputs and outputs']
```

Usage

```
{'get_tensorrt_op_path': 'get the file path to the TensorRT plugins shared library using glob pattern matching', 'is_tensorrt_plugin_loaded': 'check if the TensorRT plugins library has already been loaded into the current process', 'load_tensorrt_plugin': 'load the TensorRT plugins shared library into the current process using ctypes CDLL', 'review_deprecation_warnings': 'review the deprecation warnings in init_plugins that recommend migrating to MMDeploy', 'refactor_plugin_loading': 'refactor the TensorRT plugin loading logic to remove repeated deprecation warning code'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/tensorrt/preprocess.py

Prompts

```
['get the file path to the TensorRT plugins shared library using glob pattern matching', 'check if the TensorRT plugins library has already been loaded into the current process', 'load the TensorRT plugins shared library into the current process using ctypes CDLL', 'review the deprecation warnings in init_plugins that recommend migrating to MMDeploy', 'refactor the TensorRT plugin loading logic to remove repeated deprecation warning code', 'preprocess an ONNX model to transform NonMaxSuppression inputs into attributes for TensorRT compatibility', 'convert NonMaxSuppression node inputs like max_output_boxes_per_class and iou_threshold into static attributes', 'rename InstanceNormalization ops to MMCVInstanceNormalization for custom TensorRT plugin support', 'remove Constant nodes that were consumed and inlined into NonMaxSuppression attributes during preprocessing', 'review the preprocess_onnx function and its deprecation warning recommending migration to MMDeploy', 'convert an ONNX model file to a TensorRT ICudaEngine with optimization profiles and fp16 mode', 'serialize a TensorRT ICudaEngine to a binary file on disk for later reuse', 'deserialize a TensorRT ICudaEngine from a binary file on disk back into memory', 'convert a TensorRT DataType enum value to its corresponding PyTorch torch.dtype', 'wrap a TensorRT engine in a PyTorch nn.Module to run inference with dict inputs and outputs']
```

Usage

```
{'preprocess_onnx_model_for_tensorrt': 'preprocess an ONNX model to transform NonMaxSuppression inputs into attributes for TensorRT compatibility', 'convert_nms_inputs_to_attributes': 'convert NonMaxSuppression node inputs like max_output_boxes_per_class and iou_threshold into static attributes', 'rename_instancenormalization_op': 'rename InstanceNormalization ops to MMCVInstanceNormalization for custom TensorRT plugin support', 'remove_unused_constant_nodes': 'remove Constant nodes that were consumed and inlined into NonMaxSuppression attributes during preprocessing', 'review_preprocess_onnx_deprecation': 'review the preprocess_onnx function and its deprecation warning recommending migration to MMDeploy'}
```

## File: facebookresearch_nerf-det/mmdet3d/mmcv/tensorrt/tensorrt_utils.py

Prompts

```
['get the file path to the TensorRT plugins shared library using glob pattern matching', 'check if the TensorRT plugins library has already been loaded into the current process', 'load the TensorRT plugins shared library into the current process using ctypes CDLL', 'review the deprecation warnings in init_plugins that recommend migrating to MMDeploy', 'refactor the TensorRT plugin loading logic to remove repeated deprecation warning code', 'preprocess an ONNX model to transform NonMaxSuppression inputs into attributes for TensorRT compatibility', 'convert NonMaxSuppression node inputs like max_output_boxes_per_class and iou_threshold into static attributes', 'rename InstanceNormalization ops to MMCVInstanceNormalization for custom TensorRT plugin support', 'remove Constant nodes that were consumed and inlined into NonMaxSuppression attributes during preprocessing', 'review the preprocess_onnx function and its deprecation warning recommending migration to MMDeploy', 'convert an ONNX model file to a TensorRT ICudaEngine with optimization profiles and fp16 mode', 'serialize a TensorRT ICudaEngine to a binary file on disk for later reuse', 'deserialize a TensorRT ICudaEngine from a binary file on disk back into memory', 'convert a TensorRT DataType enum value to its corresponding PyTorch torch.dtype', 'wrap a TensorRT engine in a PyTorch nn.Module to run inference with dict inputs and outputs']
```

Usage

```
{'convert_onnx_to_tensorrt_engine': 'convert an ONNX model file to a TensorRT ICudaEngine with optimization profiles and fp16 mode', 'save_tensorrt_engine_to_disk': 'serialize a TensorRT ICudaEngine to a binary file on disk for later reuse', 'load_tensorrt_engine_from_disk': 'deserialize a TensorRT ICudaEngine from a binary file on disk back into memory', 'convert_tensorrt_dtype_to_torch': 'convert a TensorRT DataType enum value to its corresponding PyTorch torch.dtype', 'wrap_tensorrt_engine_as_module': 'wrap a TensorRT engine in a PyTorch nn.Module to run inference with dict inputs and outputs'}
```

