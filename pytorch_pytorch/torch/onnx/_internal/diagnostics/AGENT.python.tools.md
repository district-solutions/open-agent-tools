# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/onnx/_internal/diagnostics/_diagnostic.py

Prompts

```
['create a diagnostic context for torch.onnx export with a name and version', 'diagnose a torch.onnx export issue with a rule, level, and message', 'dump the sarif diagnostic log to a file with optional gzip compression', 'create an export diagnostic context as a context manager for torch.onnx.export', 'record the c++ call stack in a torchscript onnx export diagnostic', 'create the _POERules diagnostic collection with all ONNX export diagnostic rules for PyTorch', 'review the _NodeMissingOnnxShapeInference rule that reports nodes missing ONNX shape inference', 'test the _MissingStandardSymbolicFunction rule for unsupported PyTorch operators in ONNX export', 'build the _FxNodeToOnnx rule that tracks FX node to ONNX node transformation during export', 'summarize the _OpLevelDebugging rule that reports op level validation failures during ONNX export']
```

Usage

```
{'create_diagnostic_context': 'create a diagnostic context for torch.onnx export with a name and version', 'diagnose_export_issue': 'diagnose a torch.onnx export issue with a rule, level, and message', 'dump_sarif_log': 'dump the sarif diagnostic log to a file with optional gzip compression', 'create_export_context': 'create an export diagnostic context as a context manager for torch.onnx.export', 'record_cpp_call_stack': 'record the c++ call stack in a torchscript onnx export diagnostic'}
```

## File: pytorch_pytorch/torch/onnx/_internal/diagnostics/_rules.py

Prompts

```
['create a diagnostic context for torch.onnx export with a name and version', 'diagnose a torch.onnx export issue with a rule, level, and message', 'dump the sarif diagnostic log to a file with optional gzip compression', 'create an export diagnostic context as a context manager for torch.onnx.export', 'record the c++ call stack in a torchscript onnx export diagnostic', 'create the _POERules diagnostic collection with all ONNX export diagnostic rules for PyTorch', 'review the _NodeMissingOnnxShapeInference rule that reports nodes missing ONNX shape inference', 'test the _MissingStandardSymbolicFunction rule for unsupported PyTorch operators in ONNX export', 'build the _FxNodeToOnnx rule that tracks FX node to ONNX node transformation during export', 'summarize the _OpLevelDebugging rule that reports op level validation failures during ONNX export']
```

Usage

```
{'create_poerules': 'create the _POERules diagnostic collection with all ONNX export diagnostic rules for PyTorch', 'review_node_missing_onnx_shape_inference': 'review the _NodeMissingOnnxShapeInference rule that reports nodes missing ONNX shape inference', 'test_missing_standard_symbolic_function': 'test the _MissingStandardSymbolicFunction rule for unsupported PyTorch operators in ONNX export', 'build_fx_node_to_onnx': 'build the _FxNodeToOnnx rule that tracks FX node to ONNX node transformation during export', 'summarize_op_level_debugging': 'summarize the _OpLevelDebugging rule that reports op level validation failures during ONNX export'}
```

