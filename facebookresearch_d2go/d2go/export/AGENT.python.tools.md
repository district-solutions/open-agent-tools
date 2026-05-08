# Agent Python Tools

- repo: facebookresearch/d2go
- repo_uri: https://github.com/facebookresearch/d2go

## File: facebookresearch_d2go/d2go/export/api.py

Prompts

```
['create a PredictorExportConfig NamedTuple to store model export information including model, data generator, and preprocessing settings', 'implement a subclass of ModelExportMethod abstract class to export a PyTorch model to a deployable format like TorchScript', 'implement the load method in a ModelExportMethod subclass to load an exported model back for inference', 'test the export and load lifecycle of a ModelExportMethod subclass by comparing original and loaded model outputs', 'register a custom ModelExportMethod subclass with the ModelExportMethodRegistry for use in the predictor export pipeline', 'convert a pytorch model and export it to a predictor in the specified deployable format', 'export a pytorch model to a predictor of a given type and save it to output_dir', 'convert a pytorch model by fusing for fp32 or fake quantizing for int8 predictor types', 'convert a pytorch model to an int8 quantized model using post-training quantization or QAT', 'check if a predictor type string indicates an int8 or quantized model format', 'export a PyTorch model to TorchScript using trace or script mode and save to output path', 'create a MobileOptimizationConfig to apply optimize_for_mobile with CPU, Metal, or Vulkan backend', 'load a saved TorchScript model from a file path and wrap it in TorchscriptWrapper', 'export a model with TracingAdapter to handle non-flattened inputs and outputs during tracing', 'parse export_method trigger words like _mobile, @scripting, or @tracing to auto-set export kwargs']
```

Usage

```
{'create_PredictorExportConfig': 'create a PredictorExportConfig NamedTuple to store model export information including model, data generator, and preprocessing settings', 'implement_ModelExportMethod_export': 'implement a subclass of ModelExportMethod abstract class to export a PyTorch model to a deployable format like TorchScript', 'implement_ModelExportMethod_load': 'implement the load method in a ModelExportMethod subclass to load an exported model back for inference', 'test_ModelExportMethod_test_export_and_load': 'test the export and load lifecycle of a ModelExportMethod subclass by comparing original and loaded model outputs', 'register_ModelExportMethodRegistry': 'register a custom ModelExportMethod subclass with the ModelExportMethodRegistry for use in the predictor export pipeline'}
```

## File: facebookresearch_d2go/d2go/export/exporter.py

Prompts

```
['create a PredictorExportConfig NamedTuple to store model export information including model, data generator, and preprocessing settings', 'implement a subclass of ModelExportMethod abstract class to export a PyTorch model to a deployable format like TorchScript', 'implement the load method in a ModelExportMethod subclass to load an exported model back for inference', 'test the export and load lifecycle of a ModelExportMethod subclass by comparing original and loaded model outputs', 'register a custom ModelExportMethod subclass with the ModelExportMethodRegistry for use in the predictor export pipeline', 'convert a pytorch model and export it to a predictor in the specified deployable format', 'export a pytorch model to a predictor of a given type and save it to output_dir', 'convert a pytorch model by fusing for fp32 or fake quantizing for int8 predictor types', 'convert a pytorch model to an int8 quantized model using post-training quantization or QAT', 'check if a predictor type string indicates an int8 or quantized model format', 'export a PyTorch model to TorchScript using trace or script mode and save to output path', 'create a MobileOptimizationConfig to apply optimize_for_mobile with CPU, Metal, or Vulkan backend', 'load a saved TorchScript model from a file path and wrap it in TorchscriptWrapper', 'export a model with TracingAdapter to handle non-flattened inputs and outputs during tracing', 'parse export_method trigger words like _mobile, @scripting, or @tracing to auto-set export kwargs']
```

Usage

```
{'convert_and_export_predictor': 'convert a pytorch model and export it to a predictor in the specified deployable format', 'export_predictor': 'export a pytorch model to a predictor of a given type and save it to output_dir', 'convert_model': 'convert a pytorch model by fusing for fp32 or fake quantizing for int8 predictor types', 'convert_quantized_model': 'convert a pytorch model to an int8 quantized model using post-training quantization or QAT', 'is_predictor_quantized': 'check if a predictor type string indicates an int8 or quantized model format'}
```

## File: facebookresearch_d2go/d2go/export/torchscript.py

Prompts

```
['create a PredictorExportConfig NamedTuple to store model export information including model, data generator, and preprocessing settings', 'implement a subclass of ModelExportMethod abstract class to export a PyTorch model to a deployable format like TorchScript', 'implement the load method in a ModelExportMethod subclass to load an exported model back for inference', 'test the export and load lifecycle of a ModelExportMethod subclass by comparing original and loaded model outputs', 'register a custom ModelExportMethod subclass with the ModelExportMethodRegistry for use in the predictor export pipeline', 'convert a pytorch model and export it to a predictor in the specified deployable format', 'export a pytorch model to a predictor of a given type and save it to output_dir', 'convert a pytorch model by fusing for fp32 or fake quantizing for int8 predictor types', 'convert a pytorch model to an int8 quantized model using post-training quantization or QAT', 'check if a predictor type string indicates an int8 or quantized model format', 'export a PyTorch model to TorchScript using trace or script mode and save to output path', 'create a MobileOptimizationConfig to apply optimize_for_mobile with CPU, Metal, or Vulkan backend', 'load a saved TorchScript model from a file path and wrap it in TorchscriptWrapper', 'export a model with TracingAdapter to handle non-flattened inputs and outputs during tracing', 'parse export_method trigger words like _mobile, @scripting, or @tracing to auto-set export kwargs']
```

Usage

```
{'export_torchscript_model': 'export a PyTorch model to TorchScript using trace or script mode and save to output path', 'optimize_for_mobile': 'create a MobileOptimizationConfig to apply optimize_for_mobile with CPU, Metal, or Vulkan backend', 'load_torchscript_model': 'load a saved TorchScript model from a file path and wrap it in TorchscriptWrapper', 'tracing_adapter_export': 'export a model with TracingAdapter to handle non-flattened inputs and outputs during tracing', 'update_export_kwargs': 'parse export_method trigger words like _mobile, @scripting, or @tracing to auto-set export kwargs'}
```

