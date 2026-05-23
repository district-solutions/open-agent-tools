# Agent Python Tools

- repo: facebookresearch/torchdim
- repo_uri: https://github.com/facebookresearch/torchdim

## File: facebookresearch_torchdim/third_party/functorch/codegen/gen.py

Prompts

```
['run the functorch codegen script to generate vmap plumbing C++ headers', 'run generate_code to produce VmapGeneratedPlumbing.h in the specified install directory', 'run the codegen script with a custom ATen source path via the -s flag', 'run the codegen script with a custom output directory via the -d flag', 'review the generate_code function that parses native_functions.yaml and writes vmap plumbing headers', 'run the script to generate functorch_lagging_op_db.py from PyTorch op_db', 'create a function that counts leading spaces in a string line', 'create a function that removes common leading indentation from multiline code', 'test the num_leading_spaces function with strings containing varying whitespace', 'test the deindent function with indented multiline Python code strings', 'generate C++ vmap plumbing code for a list of native functions', 'generate vmap batch rule plumbing for a single native function schema', 'compute batch rule plumbing for a native function if it is on the allowlist', 'generate C++ unwrap code for tensor and optional tensor arguments at a batch level', 'generate C++ wrapped return statements for tensor and tensor list return types']
```

Usage

```
{'run_codegen_main': 'run the functorch codegen script to generate vmap plumbing C++ headers', 'run_generate_code': 'run generate_code to produce VmapGeneratedPlumbing.h in the specified install directory', 'run_codegen_with_source_path': 'run the codegen script with a custom ATen source path via the -s flag', 'run_codegen_with_install_dir': 'run the codegen script with a custom output directory via the -d flag', 'review_generate_code': 'review the generate_code function that parses native_functions.yaml and writes vmap plumbing headers'}
```

## File: facebookresearch_torchdim/third_party/functorch/codegen/gen_functorch_lagging_op_db.py

Prompts

```
['run the functorch codegen script to generate vmap plumbing C++ headers', 'run generate_code to produce VmapGeneratedPlumbing.h in the specified install directory', 'run the codegen script with a custom ATen source path via the -s flag', 'run the codegen script with a custom output directory via the -d flag', 'review the generate_code function that parses native_functions.yaml and writes vmap plumbing headers', 'run the script to generate functorch_lagging_op_db.py from PyTorch op_db', 'create a function that counts leading spaces in a string line', 'create a function that removes common leading indentation from multiline code', 'test the num_leading_spaces function with strings containing varying whitespace', 'test the deindent function with indented multiline Python code strings', 'generate C++ vmap plumbing code for a list of native functions', 'generate vmap batch rule plumbing for a single native function schema', 'compute batch rule plumbing for a native function if it is on the allowlist', 'generate C++ unwrap code for tensor and optional tensor arguments at a batch level', 'generate C++ wrapped return statements for tensor and tensor list return types']
```

Usage

```
{'run_gen_functorch_lagging_op_db': 'run the script to generate functorch_lagging_op_db.py from PyTorch op_db', 'create_function_num_leading_spaces': 'create a function that counts leading spaces in a string line', 'create_function_deindent': 'create a function that removes common leading indentation from multiline code', 'test_num_leading_spaces': 'test the num_leading_spaces function with strings containing varying whitespace', 'test_deindent': 'test the deindent function with indented multiline Python code strings'}
```

## File: facebookresearch_torchdim/third_party/functorch/codegen/gen_vmap_plumbing.py

Prompts

```
['run the functorch codegen script to generate vmap plumbing C++ headers', 'run generate_code to produce VmapGeneratedPlumbing.h in the specified install directory', 'run the codegen script with a custom ATen source path via the -s flag', 'run the codegen script with a custom output directory via the -d flag', 'review the generate_code function that parses native_functions.yaml and writes vmap plumbing headers', 'run the script to generate functorch_lagging_op_db.py from PyTorch op_db', 'create a function that counts leading spaces in a string line', 'create a function that removes common leading indentation from multiline code', 'test the num_leading_spaces function with strings containing varying whitespace', 'test the deindent function with indented multiline Python code strings', 'generate C++ vmap plumbing code for a list of native functions', 'generate vmap batch rule plumbing for a single native function schema', 'compute batch rule plumbing for a native function if it is on the allowlist', 'generate C++ unwrap code for tensor and optional tensor arguments at a batch level', 'generate C++ wrapped return statements for tensor and tensor list return types']
```

Usage

```
{'gen_all_vmap_plumbing': 'generate C++ vmap plumbing code for a list of native functions', 'gen_vmap_plumbing': 'generate vmap batch rule plumbing for a single native function schema', 'ComputeBatchRulePlumbing': 'compute batch rule plumbing for a native function if it is on the allowlist', 'gen_unwraps': 'generate C++ unwrap code for tensor and optional tensor arguments at a batch level', 'gen_returns': 'generate C++ wrapped return statements for tensor and tensor list return types'}
```

