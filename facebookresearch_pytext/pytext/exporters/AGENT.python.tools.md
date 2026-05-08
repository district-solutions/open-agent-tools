# Agent Python Tools

- repo: facebookresearch/pytext
- repo_uri: https://github.com/facebookresearch/pytext

## File: facebookresearch_pytext/pytext/exporters/custom_exporters.py

Prompts

```
['export a PyTorch model to Caffe2 init and predict net protobuf files using InitPredictNetExporter', 'get a model exporter class by ExporterType name using the get_exporter factory function', 'save a Caffe2 protobuf net model to a file path using save_caffe2_pb_net', 'get feature metadata for dense and non-dense features using DenseFeatureExporter get_feature_metadata', 'get the init_net.pb and predict_net.pb file paths for a given export directory', 'create a ModelExporter instance from feature config, target config, and common metadata', 'get input names, dummy model input, and vocab map from feature config and field metadata', 'prepend feature numericalization operators to a Caffe2 ONNX backend representation using vocab map', 'export a PyTorch model graph to tensorboard metric channels with optional raw operator export']
```

Usage

```
{'export_pytorch_to_caffe2': 'export a PyTorch model to Caffe2 init and predict net protobuf files using InitPredictNetExporter', 'get_exporter_by_type': 'get a model exporter class by ExporterType name using the get_exporter factory function', 'save_caffe2_pb_net': 'save a Caffe2 protobuf net model to a file path using save_caffe2_pb_net', 'get_dense_feature_metadata': 'get feature metadata for dense and non-dense features using DenseFeatureExporter get_feature_metadata', 'get_export_paths': 'get the init_net.pb and predict_net.pb file paths for a given export directory'}
```

## File: facebookresearch_pytext/pytext/exporters/exporter.py

Prompts

```
['export a PyTorch model to Caffe2 init and predict net protobuf files using InitPredictNetExporter', 'get a model exporter class by ExporterType name using the get_exporter factory function', 'save a Caffe2 protobuf net model to a file path using save_caffe2_pb_net', 'get feature metadata for dense and non-dense features using DenseFeatureExporter get_feature_metadata', 'get the init_net.pb and predict_net.pb file paths for a given export directory', 'create a ModelExporter instance from feature config, target config, and common metadata', 'get input names, dummy model input, and vocab map from feature config and field metadata', 'prepend feature numericalization operators to a Caffe2 ONNX backend representation using vocab map', 'export a PyTorch model graph to tensorboard metric channels with optional raw operator export']
```

Usage

```
{'export_pytorch_to_caffe2': 'export a PyTorch model to a Caffe2 predictor file using ONNX conversion and save to path', 'create_model_exporter_from_config': 'create a ModelExporter instance from feature config, target config, and common metadata', 'get_feature_metadata': 'get input names, dummy model input, and vocab map from feature config and field metadata', 'prepend_numericalize_operators': 'prepend feature numericalization operators to a Caffe2 ONNX backend representation using vocab map', 'export_model_to_tensorboard_metrics': 'export a PyTorch model graph to tensorboard metric channels with optional raw operator export'}
```

