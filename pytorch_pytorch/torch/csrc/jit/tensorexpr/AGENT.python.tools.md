# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/csrc/jit/tensorexpr/codegen_external.py

Prompts

```
['run the codegen_external script to generate external NNC function wrappers from native_functions.yaml', 'build external C++ function registrations for PyTorch aten operations using gen_external with native_functions and tags paths', 'generate nnc_aten wrapper functions that construct tensors from raw buffers and call aten ops for out-variant functions', 'parse native_functions.yaml and tags.yaml to extract aten function schemas with out variants and tensor-only arguments', 'write generated external function declarations and registrations to C++ using FileManager with a template file']
```

Usage

```
{'run_codegen_external': 'run the codegen_external script to generate external NNC function wrappers from native_functions.yaml', 'build_external_function_registrations': 'build external C++ function registrations for PyTorch aten operations using gen_external with native_functions and tags paths', 'generate_nnc_aten_wrappers': 'generate nnc_aten wrapper functions that construct tensors from raw buffers and call aten ops for out-variant functions', 'parse_native_yaml_functions': 'parse native_functions.yaml and tags.yaml to extract aten function schemas with out variants and tensor-only arguments', 'write_codegen_output_with_template': 'write generated external function declarations and registrations to C++ using FileManager with a template file'}
```

