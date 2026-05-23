# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/pybind11/pybind11/__main__.py

Prompts

```
['run python -m pybind11 --includes to print include flags for pybind11 and Python headers', 'run python -m pybind11 --cmakedir to print the CMake module directory for setting -Dpybind11_ROOT', 'run python -m pybind11 with no arguments to print the help message and available options', 'review the print_includes function that collects and deduplicates include paths from sysconfig and pybind11', 'review the main function that parses --includes and --cmakedir CLI arguments using argparse', 'get the pybind11 include directory path for compiling C++ extensions', 'get the pybind11 user include directory path with user flag set to true', 'get the pybind11 CMake module directory path for CMake integration', 'review the get_include function to understand how it resolves include paths', 'review the get_cmake_dir function to understand CMake path resolution and error handling', 'build a C++11+ extension module with pybind11 using Pybind11Extension with automatic compiler flags', 'auto detect the highest supported C++ standard level 17 14 or 11 using auto_cpp_level', 'check if a compiler supports a specific flag using has_flag and return boolean result', 'enable parallel compilation with ParallelCompile using environment variable NPY_NUM_BUILD_JOBS to control threads', 'customize build_ext to automatically inject C++ standard level for Pybind11Extension during compilation']
```

Usage

```
{'run_pybind11_includes': 'run python -m pybind11 --includes to print include flags for pybind11 and Python headers', 'run_pybind11_cmakedir': 'run python -m pybind11 --cmakedir to print the CMake module directory for setting -Dpybind11_ROOT', 'run_pybind11_help': 'run python -m pybind11 with no arguments to print the help message and available options', 'review_print_includes': 'review the print_includes function that collects and deduplicates include paths from sysconfig and pybind11', 'review_main': 'review the main function that parses --includes and --cmakedir CLI arguments using argparse'}
```

## File: facebookresearch_torchbeast/third_party/pybind11/pybind11/commands.py

Prompts

```
['run python -m pybind11 --includes to print include flags for pybind11 and Python headers', 'run python -m pybind11 --cmakedir to print the CMake module directory for setting -Dpybind11_ROOT', 'run python -m pybind11 with no arguments to print the help message and available options', 'review the print_includes function that collects and deduplicates include paths from sysconfig and pybind11', 'review the main function that parses --includes and --cmakedir CLI arguments using argparse', 'get the pybind11 include directory path for compiling C++ extensions', 'get the pybind11 user include directory path with user flag set to true', 'get the pybind11 CMake module directory path for CMake integration', 'review the get_include function to understand how it resolves include paths', 'review the get_cmake_dir function to understand CMake path resolution and error handling', 'build a C++11+ extension module with pybind11 using Pybind11Extension with automatic compiler flags', 'auto detect the highest supported C++ standard level 17 14 or 11 using auto_cpp_level', 'check if a compiler supports a specific flag using has_flag and return boolean result', 'enable parallel compilation with ParallelCompile using environment variable NPY_NUM_BUILD_JOBS to control threads', 'customize build_ext to automatically inject C++ standard level for Pybind11Extension during compilation']
```

Usage

```
{'get_include_path': 'get the pybind11 include directory path for compiling C++ extensions', 'get_include_user_path': 'get the pybind11 user include directory path with user flag set to true', 'get_cmake_directory': 'get the pybind11 CMake module directory path for CMake integration', 'review_get_include': 'review the get_include function to understand how it resolves include paths', 'review_get_cmake_dir': 'review the get_cmake_dir function to understand CMake path resolution and error handling'}
```

## File: facebookresearch_torchbeast/third_party/pybind11/pybind11/setup_helpers.py

Prompts

```
['run python -m pybind11 --includes to print include flags for pybind11 and Python headers', 'run python -m pybind11 --cmakedir to print the CMake module directory for setting -Dpybind11_ROOT', 'run python -m pybind11 with no arguments to print the help message and available options', 'review the print_includes function that collects and deduplicates include paths from sysconfig and pybind11', 'review the main function that parses --includes and --cmakedir CLI arguments using argparse', 'get the pybind11 include directory path for compiling C++ extensions', 'get the pybind11 user include directory path with user flag set to true', 'get the pybind11 CMake module directory path for CMake integration', 'review the get_include function to understand how it resolves include paths', 'review the get_cmake_dir function to understand CMake path resolution and error handling', 'build a C++11+ extension module with pybind11 using Pybind11Extension with automatic compiler flags', 'auto detect the highest supported C++ standard level 17 14 or 11 using auto_cpp_level', 'check if a compiler supports a specific flag using has_flag and return boolean result', 'enable parallel compilation with ParallelCompile using environment variable NPY_NUM_BUILD_JOBS to control threads', 'customize build_ext to automatically inject C++ standard level for Pybind11Extension during compilation']
```

Usage

```
{'build_pybind11_extension': 'build a C++11+ extension module with pybind11 using Pybind11Extension with automatic compiler flags', 'auto_detect_cpp_level': 'auto detect the highest supported C++ standard level 17 14 or 11 using auto_cpp_level', 'check_compiler_flag': 'check if a compiler supports a specific flag using has_flag and return boolean result', 'enable_parallel_compile': 'enable parallel compilation with ParallelCompile using environment variable NPY_NUM_BUILD_JOBS to control threads', 'customize_build_ext': 'customize build_ext to automatically inject C++ standard level for Pybind11Extension during compilation'}
```

