# Agent Python Tools

- repo: algorithmicsuperintelligence/openevolve
- repo_uri: https://github.com/algorithmicsuperintelligence/openevolve

## File: algorithmicsuperintelligence_openevolve/examples/attention_optimization/scripts/debug_real_execution.py

Prompts

```
['check which MLIR tools like mlir-opt and mlir-translate are available on the system', 'test MLIR to LLVM IR translation using a simple floating point addition function', 'test parsing, canonicalization, and LLVM translation of an existing MLIR file', 'suggest fixes to enable real MLIR execution including tool installation and simulation improvements', 'run the full MLIR real execution debug tool to check tools and test translation', 'run the script to fix tensor.expand_shape syntax in the MLIR self-attention file', 'run the script to add missing output_shape attributes to tensor.expand_shape ops', 'review the add_output_shape function that extracts tensor dimensions from MLIR output types', 'refactor the script to accept an input MLIR file path via command-line arguments', 'summarize the script that patches MLIR tensor.expand_shape operations with output_shape attributes', 'run the MLIR lowering pipeline to convert an MLIR file to LLVM-compatible IR using mlir-opt passes', 'verify that mlir-opt and mlir-translate tools are installed and available on the system path', 'find and list all available MLIR conversion passes for arith, func, llvm, std, and scf dialects', 'test different lowering pass combinations on an MLIR file to find sequences that successfully translate to LLVM IR', 'create a fully lowered MLIR file by applying a pass sequence and optionally save the LLVM IR output', 'run the mlir syntax test script to verify baseline attention and tiling pass syntax', 'test the mlir baseline attention syntax using mlir-opt to parse affine maps and linalg generic ops', 'test the linalg tiling pass by running mlir-opt with a canonicalize and cse pipeline', 'verify mlir-opt is installed and working by running the mlir syntax test script', 'validate an mlir program that implements scaled dot-product attention with query key and value tensors']
```

Usage

```
{'check_mlir_tools': 'check which MLIR tools like mlir-opt and mlir-translate are available on the system', 'test_mlir_translate': 'test MLIR to LLVM IR translation using a simple floating point addition function', 'test_actual_mlir_file': 'test parsing, canonicalization, and LLVM translation of an existing MLIR file', 'suggest_fixes': 'suggest fixes to enable real MLIR execution including tool installation and simulation improvements', 'run_main': 'run the full MLIR real execution debug tool to check tools and test translation'}
```

## File: algorithmicsuperintelligence_openevolve/examples/attention_optimization/scripts/fix_tensor_shapes.py

Prompts

```
['check which MLIR tools like mlir-opt and mlir-translate are available on the system', 'test MLIR to LLVM IR translation using a simple floating point addition function', 'test parsing, canonicalization, and LLVM translation of an existing MLIR file', 'suggest fixes to enable real MLIR execution including tool installation and simulation improvements', 'run the full MLIR real execution debug tool to check tools and test translation', 'run the script to fix tensor.expand_shape syntax in the MLIR self-attention file', 'run the script to add missing output_shape attributes to tensor.expand_shape ops', 'review the add_output_shape function that extracts tensor dimensions from MLIR output types', 'refactor the script to accept an input MLIR file path via command-line arguments', 'summarize the script that patches MLIR tensor.expand_shape operations with output_shape attributes', 'run the MLIR lowering pipeline to convert an MLIR file to LLVM-compatible IR using mlir-opt passes', 'verify that mlir-opt and mlir-translate tools are installed and available on the system path', 'find and list all available MLIR conversion passes for arith, func, llvm, std, and scf dialects', 'test different lowering pass combinations on an MLIR file to find sequences that successfully translate to LLVM IR', 'create a fully lowered MLIR file by applying a pass sequence and optionally save the LLVM IR output', 'run the mlir syntax test script to verify baseline attention and tiling pass syntax', 'test the mlir baseline attention syntax using mlir-opt to parse affine maps and linalg generic ops', 'test the linalg tiling pass by running mlir-opt with a canonicalize and cse pipeline', 'verify mlir-opt is installed and working by running the mlir syntax test script', 'validate an mlir program that implements scaled dot-product attention with query key and value tensors']
```

Usage

```
{'run_fix_tensor_shapes': 'run the script to fix tensor.expand_shape syntax in the MLIR self-attention file', 'run_add_output_shape': 'run the script to add missing output_shape attributes to tensor.expand_shape ops', 'review_add_output_shape': 'review the add_output_shape function that extracts tensor dimensions from MLIR output types', 'refactor_fix_tensor_shapes': 'refactor the script to accept an input MLIR file path via command-line arguments', 'summarize_fix_tensor_shapes': 'summarize the script that patches MLIR tensor.expand_shape operations with output_shape attributes'}
```

## File: algorithmicsuperintelligence_openevolve/examples/attention_optimization/scripts/mlir_lowering_pipeline.py

Prompts

```
['check which MLIR tools like mlir-opt and mlir-translate are available on the system', 'test MLIR to LLVM IR translation using a simple floating point addition function', 'test parsing, canonicalization, and LLVM translation of an existing MLIR file', 'suggest fixes to enable real MLIR execution including tool installation and simulation improvements', 'run the full MLIR real execution debug tool to check tools and test translation', 'run the script to fix tensor.expand_shape syntax in the MLIR self-attention file', 'run the script to add missing output_shape attributes to tensor.expand_shape ops', 'review the add_output_shape function that extracts tensor dimensions from MLIR output types', 'refactor the script to accept an input MLIR file path via command-line arguments', 'summarize the script that patches MLIR tensor.expand_shape operations with output_shape attributes', 'run the MLIR lowering pipeline to convert an MLIR file to LLVM-compatible IR using mlir-opt passes', 'verify that mlir-opt and mlir-translate tools are installed and available on the system path', 'find and list all available MLIR conversion passes for arith, func, llvm, std, and scf dialects', 'test different lowering pass combinations on an MLIR file to find sequences that successfully translate to LLVM IR', 'create a fully lowered MLIR file by applying a pass sequence and optionally save the LLVM IR output', 'run the mlir syntax test script to verify baseline attention and tiling pass syntax', 'test the mlir baseline attention syntax using mlir-opt to parse affine maps and linalg generic ops', 'test the linalg tiling pass by running mlir-opt with a canonicalize and cse pipeline', 'verify mlir-opt is installed and working by running the mlir syntax test script', 'validate an mlir program that implements scaled dot-product attention with query key and value tensors']
```

Usage

```
{'run_mlir_lowering_pipeline': 'run the MLIR lowering pipeline to convert an MLIR file to LLVM-compatible IR using mlir-opt passes', 'verify_mlir_tools': 'verify that mlir-opt and mlir-translate tools are installed and available on the system path', 'find_available_passes': 'find and list all available MLIR conversion passes for arith, func, llvm, std, and scf dialects', 'test_lowering_passes': 'test different lowering pass combinations on an MLIR file to find sequences that successfully translate to LLVM IR', 'create_lowered_file': 'create a fully lowered MLIR file by applying a pass sequence and optionally save the LLVM IR output'}
```

## File: algorithmicsuperintelligence_openevolve/examples/attention_optimization/scripts/mlir_syntax_test.py

Prompts

```
['check which MLIR tools like mlir-opt and mlir-translate are available on the system', 'test MLIR to LLVM IR translation using a simple floating point addition function', 'test parsing, canonicalization, and LLVM translation of an existing MLIR file', 'suggest fixes to enable real MLIR execution including tool installation and simulation improvements', 'run the full MLIR real execution debug tool to check tools and test translation', 'run the script to fix tensor.expand_shape syntax in the MLIR self-attention file', 'run the script to add missing output_shape attributes to tensor.expand_shape ops', 'review the add_output_shape function that extracts tensor dimensions from MLIR output types', 'refactor the script to accept an input MLIR file path via command-line arguments', 'summarize the script that patches MLIR tensor.expand_shape operations with output_shape attributes', 'run the MLIR lowering pipeline to convert an MLIR file to LLVM-compatible IR using mlir-opt passes', 'verify that mlir-opt and mlir-translate tools are installed and available on the system path', 'find and list all available MLIR conversion passes for arith, func, llvm, std, and scf dialects', 'test different lowering pass combinations on an MLIR file to find sequences that successfully translate to LLVM IR', 'create a fully lowered MLIR file by applying a pass sequence and optionally save the LLVM IR output', 'run the mlir syntax test script to verify baseline attention and tiling pass syntax', 'test the mlir baseline attention syntax using mlir-opt to parse affine maps and linalg generic ops', 'test the linalg tiling pass by running mlir-opt with a canonicalize and cse pipeline', 'verify mlir-opt is installed and working by running the mlir syntax test script', 'validate an mlir program that implements scaled dot-product attention with query key and value tensors']
```

Usage

```
{'run_mlir_syntax_tests': 'run the mlir syntax test script to verify baseline attention and tiling pass syntax', 'test_mlir_baseline_syntax': 'test the mlir baseline attention syntax using mlir-opt to parse affine maps and linalg generic ops', 'test_linalg_tiling_pass': 'test the linalg tiling pass by running mlir-opt with a canonicalize and cse pipeline', 'verify_mlir_installation': 'verify mlir-opt is installed and working by running the mlir syntax test script', 'validate_attention_mlir_program': 'validate an mlir program that implements scaled dot-product attention with query key and value tensors'}
```

