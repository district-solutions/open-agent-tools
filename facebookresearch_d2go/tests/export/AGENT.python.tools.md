# Agent Python Tools

- repo: facebookresearch/d2go
- repo_uri: https://github.com/facebookresearch/d2go

## File: facebookresearch_d2go/tests/export/test_api.py

Prompts

```
['test convert_and_export_predictor to export a PyTorch model to TorchScript predictor format', 'test create_predictor to load and run an exported predictor from a directory path', 'test PredictorExportConfig to configure model export with data_generator and run_func_info settings', 'test TwoPartSimpleModel to export a model split into two parts around a non-traceable function', 'test ScriptingOnlyModel to export a model with control flow loops using TorchScript scripting mode', 'test the update_export_kwargs_from_export_method decorator with various torchscript export method strings', 'test that torchscript_mobile export method sets mobile_optimization backend to CPU', 'test that torchscript_mobile-metal export method sets mobile_optimization backend to metal', 'test that torchscript_mobile-vulkan export method sets mobile_optimization backend to vulkan', 'test that torchscript_mobile@tracing and @scripting set jit_mode to trace or script']
```

Usage

```
{'test_convert_and_export_predictor': 'test convert_and_export_predictor to export a PyTorch model to TorchScript predictor format', 'test_create_predictor': 'test create_predictor to load and run an exported predictor from a directory path', 'test_PredictorExportConfig': 'test PredictorExportConfig to configure model export with data_generator and run_func_info settings', 'test_TwoPartSimpleModel': 'test TwoPartSimpleModel to export a model split into two parts around a non-traceable function', 'test_ScriptingOnlyModel': 'test ScriptingOnlyModel to export a model with control flow loops using TorchScript scripting mode'}
```

## File: facebookresearch_d2go/tests/export/test_torchscript.py

Prompts

```
['test convert_and_export_predictor to export a PyTorch model to TorchScript predictor format', 'test create_predictor to load and run an exported predictor from a directory path', 'test PredictorExportConfig to configure model export with data_generator and run_func_info settings', 'test TwoPartSimpleModel to export a model split into two parts around a non-traceable function', 'test ScriptingOnlyModel to export a model with control flow loops using TorchScript scripting mode', 'test the update_export_kwargs_from_export_method decorator with various torchscript export method strings', 'test that torchscript_mobile export method sets mobile_optimization backend to CPU', 'test that torchscript_mobile-metal export method sets mobile_optimization backend to metal', 'test that torchscript_mobile-vulkan export method sets mobile_optimization backend to vulkan', 'test that torchscript_mobile@tracing and @scripting set jit_mode to trace or script']
```

Usage

```
{'test_torchscript_export_methods': 'test the update_export_kwargs_from_export_method decorator with various torchscript export method strings', 'test_mobile_optimization_cpu': 'test that torchscript_mobile export method sets mobile_optimization backend to CPU', 'test_mobile_optimization_metal': 'test that torchscript_mobile-metal export method sets mobile_optimization backend to metal', 'test_mobile_optimization_vulkan': 'test that torchscript_mobile-vulkan export method sets mobile_optimization backend to vulkan', 'test_jit_mode_tracing_scripting': 'test that torchscript_mobile@tracing and @scripting set jit_mode to trace or script'}
```

