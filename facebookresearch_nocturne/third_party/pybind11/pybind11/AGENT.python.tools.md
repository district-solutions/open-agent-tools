# Agent Python Tools

- repo: facebookresearch/nocturne
- repo_uri: https://github.com/facebookresearch/nocturne

## File: facebookresearch_nocturne/third_party/pybind11/pybind11/__main__.py

Prompts

```
['run python -m pybind11 --includes to print include flags for pybind11 and Python headers', 'run python -m pybind11 --cmakedir to print the CMake module directory for pybind11', 'run python -m pybind11 with no arguments to print the help message and available options', 'review the print_includes function that collects and deduplicates include paths from sysconfig and pybind11', 'review the main function that parses --includes and --cmakedir CLI arguments using argparse', 'get the pybind11 include directory path for compiling C++ extensions', 'get the pybind11 include directory path using the user install flag', 'get the pybind11 CMake module directory path for CMake integration', 'review the get_include function to understand how it resolves include paths', 'review the get_cmake_dir function to understand CMake directory resolution', 'build a C++11+ extension module using Pybind11Extension with automatic compiler flags for the target platform', 'build pybind11 extensions using the customized build_ext class that auto-detects the highest supported C++ standard level', 'generate Pybind11Extension objects from source files located directly in a Python source tree using intree_extensions', 'enable parallel compilation of C++ sources using ParallelCompile with configurable thread count via environment variable', 'check if a specific compiler flag is supported using has_flag by compiling a test file with the flag']
```

Usage

```
{'run_pybind11_includes': 'run python -m pybind11 --includes to print include flags for pybind11 and Python headers', 'run_pybind11_cmakedir': 'run python -m pybind11 --cmakedir to print the CMake module directory for pybind11', 'run_pybind11_help': 'run python -m pybind11 with no arguments to print the help message and available options', 'review_print_includes': 'review the print_includes function that collects and deduplicates include paths from sysconfig and pybind11', 'review_main_parser': 'review the main function that parses --includes and --cmakedir CLI arguments using argparse'}
```

## File: facebookresearch_nocturne/third_party/pybind11/pybind11/commands.py

Prompts

```
['run python -m pybind11 --includes to print include flags for pybind11 and Python headers', 'run python -m pybind11 --cmakedir to print the CMake module directory for pybind11', 'run python -m pybind11 with no arguments to print the help message and available options', 'review the print_includes function that collects and deduplicates include paths from sysconfig and pybind11', 'review the main function that parses --includes and --cmakedir CLI arguments using argparse', 'get the pybind11 include directory path for compiling C++ extensions', 'get the pybind11 include directory path using the user install flag', 'get the pybind11 CMake module directory path for CMake integration', 'review the get_include function to understand how it resolves include paths', 'review the get_cmake_dir function to understand CMake directory resolution', 'build a C++11+ extension module using Pybind11Extension with automatic compiler flags for the target platform', 'build pybind11 extensions using the customized build_ext class that auto-detects the highest supported C++ standard level', 'generate Pybind11Extension objects from source files located directly in a Python source tree using intree_extensions', 'enable parallel compilation of C++ sources using ParallelCompile with configurable thread count via environment variable', 'check if a specific compiler flag is supported using has_flag by compiling a test file with the flag']
```

Usage

```
{'get_include_path': 'get the pybind11 include directory path for compiling C++ extensions', 'get_include_user': 'get the pybind11 include directory path using the user install flag', 'get_cmake_dir_path': 'get the pybind11 CMake module directory path for CMake integration', 'review_get_include': 'review the get_include function to understand how it resolves include paths', 'review_get_cmake_dir': 'review the get_cmake_dir function to understand CMake directory resolution'}
```

## File: facebookresearch_nocturne/third_party/pybind11/pybind11/setup_helpers.py

Prompts

```
['run python -m pybind11 --includes to print include flags for pybind11 and Python headers', 'run python -m pybind11 --cmakedir to print the CMake module directory for pybind11', 'run python -m pybind11 with no arguments to print the help message and available options', 'review the print_includes function that collects and deduplicates include paths from sysconfig and pybind11', 'review the main function that parses --includes and --cmakedir CLI arguments using argparse', 'get the pybind11 include directory path for compiling C++ extensions', 'get the pybind11 include directory path using the user install flag', 'get the pybind11 CMake module directory path for CMake integration', 'review the get_include function to understand how it resolves include paths', 'review the get_cmake_dir function to understand CMake directory resolution', 'build a C++11+ extension module using Pybind11Extension with automatic compiler flags for the target platform', 'build pybind11 extensions using the customized build_ext class that auto-detects the highest supported C++ standard level', 'generate Pybind11Extension objects from source files located directly in a Python source tree using intree_extensions', 'enable parallel compilation of C++ sources using ParallelCompile with configurable thread count via environment variable', 'check if a specific compiler flag is supported using has_flag by compiling a test file with the flag']
```

Usage

```
{'build_pybind11_extension': 'build a C++11+ extension module using Pybind11Extension with automatic compiler flags for the target platform', 'build_pybind11_extensions_with_build_ext': 'build pybind11 extensions using the customized build_ext class that auto-detects the highest supported C++ standard level', 'generate_intree_extensions': 'generate Pybind11Extension objects from source files located directly in a Python source tree using intree_extensions', 'enable_parallel_compile': 'enable parallel compilation of C++ sources using ParallelCompile with configurable thread count via environment variable', 'check_compiler_flag_support': 'check if a specific compiler flag is supported using has_flag by compiling a test file with the flag'}
```

