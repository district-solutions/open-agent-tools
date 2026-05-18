# Agent Python Tools

- repo: facebookresearch/mobile-vision
- repo_uri: https://github.com/facebookresearch/mobile-vision

## File: facebookresearch_mobile-vision/mobile_cv/predictor/api.py

Prompts

```
['create a PredictorWrapper from a structured folder containing predictor_info.json and model files', 'instantiate a callable class object from a FuncInfo NamedTuple using dynamic import', 'generate a FuncInfo NamedTuple from a class object and its constructor parameters', 'convert a PredictorInfo NamedTuple to a serializable dictionary for JSON storage', 'load predictor configuration from a JSON file and construct a PredictorWrapper with models', 'load a TorchScript model from a path and return a TorchscriptWrapper instance', 'load a Caffe2 model from protobuf files and return a Caffe2Wrapper instance', 'create a Caffe2Wrapper from predict_net and init_net protobuf NetDef objects', 'run inference on a Caffe2Wrapper by passing input tensors through its forward method', 'create a TorchscriptWrapper around a loaded TorchScript module for uniform nn.Module inference']
```

Usage

```
{'create_predictor_from_dir': 'create a PredictorWrapper from a structured folder containing predictor_info.json and model files', 'instantiate_func_info': 'instantiate a callable class object from a FuncInfo NamedTuple using dynamic import', 'gen_func_info_from_class': 'generate a FuncInfo NamedTuple from a class object and its constructor parameters', 'convert_predictor_info_to_dict': 'convert a PredictorInfo NamedTuple to a serializable dictionary for JSON storage', 'load_predictor_from_json': 'load predictor configuration from a JSON file and construct a PredictorWrapper with models'}
```

## File: facebookresearch_mobile-vision/mobile_cv/predictor/model_wrappers.py

Prompts

```
['create a PredictorWrapper from a structured folder containing predictor_info.json and model files', 'instantiate a callable class object from a FuncInfo NamedTuple using dynamic import', 'generate a FuncInfo NamedTuple from a class object and its constructor parameters', 'convert a PredictorInfo NamedTuple to a serializable dictionary for JSON storage', 'load predictor configuration from a JSON file and construct a PredictorWrapper with models', 'load a TorchScript model from a path and return a TorchscriptWrapper instance', 'load a Caffe2 model from protobuf files and return a Caffe2Wrapper instance', 'create a Caffe2Wrapper from predict_net and init_net protobuf NetDef objects', 'run inference on a Caffe2Wrapper by passing input tensors through its forward method', 'create a TorchscriptWrapper around a loaded TorchScript module for uniform nn.Module inference']
```

Usage

```
{'load_model_torchscript': 'load a TorchScript model from a path and return a TorchscriptWrapper instance', 'load_model_caffe2': 'load a Caffe2 model from protobuf files and return a Caffe2Wrapper instance', 'create_caffe2_wrapper': 'create a Caffe2Wrapper from predict_net and init_net protobuf NetDef objects', 'run_caffe2_inference': 'run inference on a Caffe2Wrapper by passing input tensors through its forward method', 'create_torchscript_wrapper': 'create a TorchscriptWrapper around a loaded TorchScript module for uniform nn.Module inference'}
```

