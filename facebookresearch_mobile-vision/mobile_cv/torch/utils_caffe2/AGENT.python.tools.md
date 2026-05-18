# Agent Python Tools

- repo: facebookresearch/mobile-vision
- repo_uri: https://github.com/facebookresearch/mobile-vision

## File: facebookresearch_mobile-vision/mobile_cv/torch/utils_caffe2/graph_transform.py

Prompts

```
['rename an operator input blob in a Caffe2 predict_net and init_net with automatic re-routing', 'rename an operator output blob in a Caffe2 predict_net and update all downstream consumers', 'identify reshape sub-graphs in a Caffe2 predict_net where shape computation depends on input data', 'remove unnecessary reshape operations before FC layers in a Caffe2 predict_net for ONNX compatibility', 'fuse redundant CPU-to-GPU and GPU-to-CPU copy operations in a Caffe2 predict_net', 'create a Caffe2 constant fill operator from a NumPy array or Int8Tensor blob', 'construct a Caffe2 init_net protobuf from a dictionary of parameter name to blob mappings', 'run a Caffe2 init_net and extract all output blobs as a params dictionary with device options', 'infer the device type of each blob in a Caffe2 predict_net by static analysis', 'check or set a protobuf argument value on a Caffe2 operator with optional override support', 'analyze a Caffe2 NetDef to determine the memory layout order of each blob in the network', 'analyze a Caffe2 NetDef to determine the data type of each blob in the network', 'statically analyze blob status in a Caffe2 NetDef using a custom status updater function', 'review the _update_order_status function to understand how tensor memory layout is propagated through ops', 'review the _update_int8_status function to understand how int8 quantization types are propagated through ops', 'save a Caffe2 network graph as a PNG image file using save_graph', 'save a Caffe2 network graph as a PDF file with blob sizes and ranges', 'save a Caffe2 network graph as an SVG image using save_graph', 'save a Caffe2 graph with a custom blob rename function via save_graph_base', 'modify blob input and output names in Caffe2 ops using _modify_blob_names', 'use the ScopedWS context manager to switch and reset a Caffe2 workspace temporarily', 'create a ScopedWS instance with reset enabled to clear the workspace on entry', 'create a ScopedWS instance with cleanup enabled to reset the workspace on exit', 'fetch a blob by name from the Caffe2 workspace handling both regular and Int8 types', 'review the ScopedWS class and its enter and exit context manager methods']
```

Usage

```
{'rename_op_input': 'rename an operator input blob in a Caffe2 predict_net and init_net with automatic re-routing', 'rename_op_output': 'rename an operator output blob in a Caffe2 predict_net and update all downstream consumers', 'identify_reshape_sub_graph': 'identify reshape sub-graphs in a Caffe2 predict_net where shape computation depends on input data', 'remove_reshape_for_fc': 'remove unnecessary reshape operations before FC layers in a Caffe2 predict_net for ONNX compatibility', 'fuse_copy_between_cpu_and_gpu': 'fuse redundant CPU-to-GPU and GPU-to-CPU copy operations in a Caffe2 predict_net'}
```

## File: facebookresearch_mobile-vision/mobile_cv/torch/utils_caffe2/protobuf.py

Prompts

```
['rename an operator input blob in a Caffe2 predict_net and init_net with automatic re-routing', 'rename an operator output blob in a Caffe2 predict_net and update all downstream consumers', 'identify reshape sub-graphs in a Caffe2 predict_net where shape computation depends on input data', 'remove unnecessary reshape operations before FC layers in a Caffe2 predict_net for ONNX compatibility', 'fuse redundant CPU-to-GPU and GPU-to-CPU copy operations in a Caffe2 predict_net', 'create a Caffe2 constant fill operator from a NumPy array or Int8Tensor blob', 'construct a Caffe2 init_net protobuf from a dictionary of parameter name to blob mappings', 'run a Caffe2 init_net and extract all output blobs as a params dictionary with device options', 'infer the device type of each blob in a Caffe2 predict_net by static analysis', 'check or set a protobuf argument value on a Caffe2 operator with optional override support', 'analyze a Caffe2 NetDef to determine the memory layout order of each blob in the network', 'analyze a Caffe2 NetDef to determine the data type of each blob in the network', 'statically analyze blob status in a Caffe2 NetDef using a custom status updater function', 'review the _update_order_status function to understand how tensor memory layout is propagated through ops', 'review the _update_int8_status function to understand how int8 quantization types are propagated through ops', 'save a Caffe2 network graph as a PNG image file using save_graph', 'save a Caffe2 network graph as a PDF file with blob sizes and ranges', 'save a Caffe2 network graph as an SVG image using save_graph', 'save a Caffe2 graph with a custom blob rename function via save_graph_base', 'modify blob input and output names in Caffe2 ops using _modify_blob_names', 'use the ScopedWS context manager to switch and reset a Caffe2 workspace temporarily', 'create a ScopedWS instance with reset enabled to clear the workspace on entry', 'create a ScopedWS instance with cleanup enabled to reset the workspace on exit', 'fetch a blob by name from the Caffe2 workspace handling both regular and Int8 types', 'review the ScopedWS class and its enter and exit context manager methods']
```

Usage

```
{'create_const_fill_op': 'create a Caffe2 constant fill operator from a NumPy array or Int8Tensor blob', 'construct_init_net_from_params': 'construct a Caffe2 init_net protobuf from a dictionary of parameter name to blob mappings', 'get_params_from_init_net': 'run a Caffe2 init_net and extract all output blobs as a params dictionary with device options', 'infer_device_type': 'infer the device type of each blob in a Caffe2 predict_net by static analysis', 'check_set_pb_arg': 'check or set a protobuf argument value on a Caffe2 operator with optional override support'}
```

## File: facebookresearch_mobile-vision/mobile_cv/torch/utils_caffe2/state_transition.py

Prompts

```
['rename an operator input blob in a Caffe2 predict_net and init_net with automatic re-routing', 'rename an operator output blob in a Caffe2 predict_net and update all downstream consumers', 'identify reshape sub-graphs in a Caffe2 predict_net where shape computation depends on input data', 'remove unnecessary reshape operations before FC layers in a Caffe2 predict_net for ONNX compatibility', 'fuse redundant CPU-to-GPU and GPU-to-CPU copy operations in a Caffe2 predict_net', 'create a Caffe2 constant fill operator from a NumPy array or Int8Tensor blob', 'construct a Caffe2 init_net protobuf from a dictionary of parameter name to blob mappings', 'run a Caffe2 init_net and extract all output blobs as a params dictionary with device options', 'infer the device type of each blob in a Caffe2 predict_net by static analysis', 'check or set a protobuf argument value on a Caffe2 operator with optional override support', 'analyze a Caffe2 NetDef to determine the memory layout order of each blob in the network', 'analyze a Caffe2 NetDef to determine the data type of each blob in the network', 'statically analyze blob status in a Caffe2 NetDef using a custom status updater function', 'review the _update_order_status function to understand how tensor memory layout is propagated through ops', 'review the _update_int8_status function to understand how int8 quantization types are propagated through ops', 'save a Caffe2 network graph as a PNG image file using save_graph', 'save a Caffe2 network graph as a PDF file with blob sizes and ranges', 'save a Caffe2 network graph as an SVG image using save_graph', 'save a Caffe2 graph with a custom blob rename function via save_graph_base', 'modify blob input and output names in Caffe2 ops using _modify_blob_names', 'use the ScopedWS context manager to switch and reset a Caffe2 workspace temporarily', 'create a ScopedWS instance with reset enabled to clear the workspace on entry', 'create a ScopedWS instance with cleanup enabled to reset the workspace on exit', 'fetch a blob by name from the Caffe2 workspace handling both regular and Int8 types', 'review the ScopedWS class and its enter and exit context manager methods']
```

Usage

```
{'analyze_order': 'analyze a Caffe2 NetDef to determine the memory layout order of each blob in the network', 'analyze_type': 'analyze a Caffe2 NetDef to determine the data type of each blob in the network', 'static_static_analyzer': 'statically analyze blob status in a Caffe2 NetDef using a custom status updater function', 'review_update_order_status': 'review the _update_order_status function to understand how tensor memory layout is propagated through ops', 'review_update_int8_status': 'review the _update_int8_status function to understand how int8 quantization types are propagated through ops'}
```

## File: facebookresearch_mobile-vision/mobile_cv/torch/utils_caffe2/vis.py

Prompts

```
['rename an operator input blob in a Caffe2 predict_net and init_net with automatic re-routing', 'rename an operator output blob in a Caffe2 predict_net and update all downstream consumers', 'identify reshape sub-graphs in a Caffe2 predict_net where shape computation depends on input data', 'remove unnecessary reshape operations before FC layers in a Caffe2 predict_net for ONNX compatibility', 'fuse redundant CPU-to-GPU and GPU-to-CPU copy operations in a Caffe2 predict_net', 'create a Caffe2 constant fill operator from a NumPy array or Int8Tensor blob', 'construct a Caffe2 init_net protobuf from a dictionary of parameter name to blob mappings', 'run a Caffe2 init_net and extract all output blobs as a params dictionary with device options', 'infer the device type of each blob in a Caffe2 predict_net by static analysis', 'check or set a protobuf argument value on a Caffe2 operator with optional override support', 'analyze a Caffe2 NetDef to determine the memory layout order of each blob in the network', 'analyze a Caffe2 NetDef to determine the data type of each blob in the network', 'statically analyze blob status in a Caffe2 NetDef using a custom status updater function', 'review the _update_order_status function to understand how tensor memory layout is propagated through ops', 'review the _update_int8_status function to understand how int8 quantization types are propagated through ops', 'save a Caffe2 network graph as a PNG image file using save_graph', 'save a Caffe2 network graph as a PDF file with blob sizes and ranges', 'save a Caffe2 network graph as an SVG image using save_graph', 'save a Caffe2 graph with a custom blob rename function via save_graph_base', 'modify blob input and output names in Caffe2 ops using _modify_blob_names', 'use the ScopedWS context manager to switch and reset a Caffe2 workspace temporarily', 'create a ScopedWS instance with reset enabled to clear the workspace on entry', 'create a ScopedWS instance with cleanup enabled to reset the workspace on exit', 'fetch a blob by name from the Caffe2 workspace handling both regular and Int8 types', 'review the ScopedWS class and its enter and exit context manager methods']
```

Usage

```
{'save_graph_png': 'save a Caffe2 network graph as a PNG image file using save_graph', 'save_graph_pdf': 'save a Caffe2 network graph as a PDF file with blob sizes and ranges', 'save_graph_svg': 'save a Caffe2 network graph as an SVG image using save_graph', 'save_graph_base_custom_rename': 'save a Caffe2 graph with a custom blob rename function via save_graph_base', 'modify_blob_names': 'modify blob input and output names in Caffe2 ops using _modify_blob_names'}
```

## File: facebookresearch_mobile-vision/mobile_cv/torch/utils_caffe2/ws_utils.py

Prompts

```
['rename an operator input blob in a Caffe2 predict_net and init_net with automatic re-routing', 'rename an operator output blob in a Caffe2 predict_net and update all downstream consumers', 'identify reshape sub-graphs in a Caffe2 predict_net where shape computation depends on input data', 'remove unnecessary reshape operations before FC layers in a Caffe2 predict_net for ONNX compatibility', 'fuse redundant CPU-to-GPU and GPU-to-CPU copy operations in a Caffe2 predict_net', 'create a Caffe2 constant fill operator from a NumPy array or Int8Tensor blob', 'construct a Caffe2 init_net protobuf from a dictionary of parameter name to blob mappings', 'run a Caffe2 init_net and extract all output blobs as a params dictionary with device options', 'infer the device type of each blob in a Caffe2 predict_net by static analysis', 'check or set a protobuf argument value on a Caffe2 operator with optional override support', 'analyze a Caffe2 NetDef to determine the memory layout order of each blob in the network', 'analyze a Caffe2 NetDef to determine the data type of each blob in the network', 'statically analyze blob status in a Caffe2 NetDef using a custom status updater function', 'review the _update_order_status function to understand how tensor memory layout is propagated through ops', 'review the _update_int8_status function to understand how int8 quantization types are propagated through ops', 'save a Caffe2 network graph as a PNG image file using save_graph', 'save a Caffe2 network graph as a PDF file with blob sizes and ranges', 'save a Caffe2 network graph as an SVG image using save_graph', 'save a Caffe2 graph with a custom blob rename function via save_graph_base', 'modify blob input and output names in Caffe2 ops using _modify_blob_names', 'use the ScopedWS context manager to switch and reset a Caffe2 workspace temporarily', 'create a ScopedWS instance with reset enabled to clear the workspace on entry', 'create a ScopedWS instance with cleanup enabled to reset the workspace on exit', 'fetch a blob by name from the Caffe2 workspace handling both regular and Int8 types', 'review the ScopedWS class and its enter and exit context manager methods']
```

Usage

```
{'use_scopedws_context_manager': 'use the ScopedWS context manager to switch and reset a Caffe2 workspace temporarily', 'create_scopedws_with_reset': 'create a ScopedWS instance with reset enabled to clear the workspace on entry', 'create_scopedws_with_cleanup': 'create a ScopedWS instance with cleanup enabled to reset the workspace on exit', 'fetch_any_blob': 'fetch a blob by name from the Caffe2 workspace handling both regular and Int8 types', 'review_scopedws_class': 'review the ScopedWS class and its enter and exit context manager methods'}
```

