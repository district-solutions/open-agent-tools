# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/tools/deploy/export_model.py

Prompts

```
['export a detectron2 model to TorchScript format using the tracing export method', 'export a detectron2 model to ONNX format using the caffe2_tracing export method', 'export a detectron2 model to Caffe2 protobuf format using the caffe2_tracing export method', 'export a detectron2 model to TorchScript using the scripting export method', 'run evaluation on an exported detectron2 model using the COCOEvaluator on a test dataset']
```

Usage

```
{'export_model_torchscript': 'export a detectron2 model to TorchScript format using the tracing export method', 'export_model_onnx': 'export a detectron2 model to ONNX format using the caffe2_tracing export method', 'export_model_caffe2': 'export a detectron2 model to Caffe2 protobuf format using the caffe2_tracing export method', 'export_model_scripting': 'export a detectron2 model to TorchScript using the scripting export method', 'run_export_model_eval': 'run evaluation on an exported detectron2 model using the COCOEvaluator on a test dataset'}
```

