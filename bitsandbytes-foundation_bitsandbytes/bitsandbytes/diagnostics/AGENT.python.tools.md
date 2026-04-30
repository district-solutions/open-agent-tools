# Agent Python Tools

- repo: bitsandbytes-foundation/bitsandbytes
- repo_uri: https://github.com/bitsandbytes-foundation/bitsandbytes

## File: bitsandbytes-foundation_bitsandbytes/bitsandbytes/diagnostics/cuda.py

Prompts

```
['build a function to find CUDA libraries in a given path list by scanning for matching library patterns', 'create a function to search for CUDA runtime libraries across environment variables with priority ordering', 'test the diagnostics function that prints PyTorch CUDA or ROCm version and compute capability information', 'run the runtime diagnostics function that checks for duplicate or missing CUDA/ROCm runtime files in environment paths', 'review the function that filters environment variables to identify relevant CUDA library path candidates', 'run the main diagnostics function to check bitsandbytes installation and CUDA availability', 'test the sanity check that validates bitsandbytes Adam optimizer works on CUDA tensors', 'show environment information including platform, Python, PyTorch, and related package versions', "get the installed version of a Python package by name, returning 'not found' if unavailable", 'run CUDA diagnostics by retrieving CUDA specs and printing GPU compatibility information', 'create a formatted header line with customizable width and filler characters', 'create a function that prints text with leading whitespace removed from each line', 'test the print_header function with various text, width, and filler arguments', 'test the print_dedented function with multi-line indented text blocks', 'summarize the diagnostics utility functions for printing formatted headers and dedented text']
```

Usage

```
{'build_find_cuda_libraries': 'build a function to find CUDA libraries in a given path list by scanning for matching library patterns', 'create_find_cudart_libraries': 'create a function to search for CUDA runtime libraries across environment variables with priority ordering', 'test_print_diagnostics': 'test the diagnostics function that prints PyTorch CUDA or ROCm version and compute capability information', 'run_print_runtime_diagnostics': 'run the runtime diagnostics function that checks for duplicate or missing CUDA/ROCm runtime files in environment paths', 'review_is_relevant_candidate_env_var': 'review the function that filters environment variables to identify relevant CUDA library path candidates'}
```

## File: bitsandbytes-foundation_bitsandbytes/bitsandbytes/diagnostics/main.py

Prompts

```
['build a function to find CUDA libraries in a given path list by scanning for matching library patterns', 'create a function to search for CUDA runtime libraries across environment variables with priority ordering', 'test the diagnostics function that prints PyTorch CUDA or ROCm version and compute capability information', 'run the runtime diagnostics function that checks for duplicate or missing CUDA/ROCm runtime files in environment paths', 'review the function that filters environment variables to identify relevant CUDA library path candidates', 'run the main diagnostics function to check bitsandbytes installation and CUDA availability', 'test the sanity check that validates bitsandbytes Adam optimizer works on CUDA tensors', 'show environment information including platform, Python, PyTorch, and related package versions', "get the installed version of a Python package by name, returning 'not found' if unavailable", 'run CUDA diagnostics by retrieving CUDA specs and printing GPU compatibility information', 'create a formatted header line with customizable width and filler characters', 'create a function that prints text with leading whitespace removed from each line', 'test the print_header function with various text, width, and filler arguments', 'test the print_dedented function with multi-line indented text blocks', 'summarize the diagnostics utility functions for printing formatted headers and dedented text']
```

Usage

```
{'run_main_diagnostics': 'run the main diagnostics function to check bitsandbytes installation and CUDA availability', 'test_sanity_check': 'test the sanity check that validates bitsandbytes Adam optimizer works on CUDA tensors', 'show_environment_info': 'show environment information including platform, Python, PyTorch, and related package versions', 'get_package_version': "get the installed version of a Python package by name, returning 'not found' if unavailable", 'run_cuda_diagnostics': 'run CUDA diagnostics by retrieving CUDA specs and printing GPU compatibility information'}
```

## File: bitsandbytes-foundation_bitsandbytes/bitsandbytes/diagnostics/utils.py

Prompts

```
['build a function to find CUDA libraries in a given path list by scanning for matching library patterns', 'create a function to search for CUDA runtime libraries across environment variables with priority ordering', 'test the diagnostics function that prints PyTorch CUDA or ROCm version and compute capability information', 'run the runtime diagnostics function that checks for duplicate or missing CUDA/ROCm runtime files in environment paths', 'review the function that filters environment variables to identify relevant CUDA library path candidates', 'run the main diagnostics function to check bitsandbytes installation and CUDA availability', 'test the sanity check that validates bitsandbytes Adam optimizer works on CUDA tensors', 'show environment information including platform, Python, PyTorch, and related package versions', "get the installed version of a Python package by name, returning 'not found' if unavailable", 'run CUDA diagnostics by retrieving CUDA specs and printing GPU compatibility information', 'create a formatted header line with customizable width and filler characters', 'create a function that prints text with leading whitespace removed from each line', 'test the print_header function with various text, width, and filler arguments', 'test the print_dedented function with multi-line indented text blocks', 'summarize the diagnostics utility functions for printing formatted headers and dedented text']
```

Usage

```
{'create_print_header': 'create a formatted header line with customizable width and filler characters', 'create_print_dedented': 'create a function that prints text with leading whitespace removed from each line', 'test_print_header': 'test the print_header function with various text, width, and filler arguments', 'test_print_dedented': 'test the print_dedented function with multi-line indented text blocks', 'summarize_utils': 'summarize the diagnostics utility functions for printing formatted headers and dedented text'}
```

