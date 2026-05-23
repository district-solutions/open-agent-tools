# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/third_party/pybind11/pybind11/__main__.py

Prompts

```
['run python -m pybind11 --includes to print include flags for pybind11 and Python headers', 'run python -m pybind11 --cmakedir to print the CMake module directory for pybind11', 'run python -m pybind11 with no arguments to print the help message and available options', 'review the print_includes function that collects and deduplicates Python and pybind11 include directories', 'review the main function that parses --includes and --cmakedir CLI arguments using argparse', 'get the pybind11 include directory path for compiling C++ extensions', 'get the pybind11 include directory path with the user flag for legacy compatibility', 'get the pybind11 CMake module directory path for CMake-based builds', 'review the get_include function to understand how it resolves installed vs source paths', 'review the get_cmake_dir function to understand CMake path resolution and ImportError handling', 'build a C++11+ extension module using Pybind11Extension with automatic compiler flags for Windows, macOS, and Unix', 'build extensions using the customized build_ext class that auto-detects the highest supported C++ standard level', 'generate Pybind11Extension objects from source files located directly in a Python source tree using intree_extensions', 'install parallel compilation into distutils by calling ParallelCompile with an environment variable and install method', 'check if a compiler supports a specific flag by calling has_flag with the compiler and flag string']
```

Usage

```
{'run_pybind11_includes': 'run python -m pybind11 --includes to print include flags for pybind11 and Python headers', 'run_pybind11_cmakedir': 'run python -m pybind11 --cmakedir to print the CMake module directory for pybind11', 'run_pybind11_help': 'run python -m pybind11 with no arguments to print the help message and available options', 'review_print_includes': 'review the print_includes function that collects and deduplicates Python and pybind11 include directories', 'review_main_parser': 'review the main function that parses --includes and --cmakedir CLI arguments using argparse'}
```

## File: facebookresearch_rlmeta/third_party/pybind11/pybind11/commands.py

Prompts

```
['run python -m pybind11 --includes to print include flags for pybind11 and Python headers', 'run python -m pybind11 --cmakedir to print the CMake module directory for pybind11', 'run python -m pybind11 with no arguments to print the help message and available options', 'review the print_includes function that collects and deduplicates Python and pybind11 include directories', 'review the main function that parses --includes and --cmakedir CLI arguments using argparse', 'get the pybind11 include directory path for compiling C++ extensions', 'get the pybind11 include directory path with the user flag for legacy compatibility', 'get the pybind11 CMake module directory path for CMake-based builds', 'review the get_include function to understand how it resolves installed vs source paths', 'review the get_cmake_dir function to understand CMake path resolution and ImportError handling', 'build a C++11+ extension module using Pybind11Extension with automatic compiler flags for Windows, macOS, and Unix', 'build extensions using the customized build_ext class that auto-detects the highest supported C++ standard level', 'generate Pybind11Extension objects from source files located directly in a Python source tree using intree_extensions', 'install parallel compilation into distutils by calling ParallelCompile with an environment variable and install method', 'check if a compiler supports a specific flag by calling has_flag with the compiler and flag string']
```

Usage

```
{'get_include_path': 'get the pybind11 include directory path for compiling C++ extensions', 'get_include_user_mode': 'get the pybind11 include directory path with the user flag for legacy compatibility', 'get_cmake_directory': 'get the pybind11 CMake module directory path for CMake-based builds', 'review_get_include': 'review the get_include function to understand how it resolves installed vs source paths', 'review_get_cmake_dir': 'review the get_cmake_dir function to understand CMake path resolution and ImportError handling'}
```

## File: facebookresearch_rlmeta/third_party/pybind11/pybind11/setup_helpers.py

Prompts

```
['run python -m pybind11 --includes to print include flags for pybind11 and Python headers', 'run python -m pybind11 --cmakedir to print the CMake module directory for pybind11', 'run python -m pybind11 with no arguments to print the help message and available options', 'review the print_includes function that collects and deduplicates Python and pybind11 include directories', 'review the main function that parses --includes and --cmakedir CLI arguments using argparse', 'get the pybind11 include directory path for compiling C++ extensions', 'get the pybind11 include directory path with the user flag for legacy compatibility', 'get the pybind11 CMake module directory path for CMake-based builds', 'review the get_include function to understand how it resolves installed vs source paths', 'review the get_cmake_dir function to understand CMake path resolution and ImportError handling', 'build a C++11+ extension module using Pybind11Extension with automatic compiler flags for Windows, macOS, and Unix', 'build extensions using the customized build_ext class that auto-detects the highest supported C++ standard level', 'generate Pybind11Extension objects from source files located directly in a Python source tree using intree_extensions', 'install parallel compilation into distutils by calling ParallelCompile with an environment variable and install method', 'check if a compiler supports a specific flag by calling has_flag with the compiler and flag string']
```

Usage

```
{'build_pybind11_extension': 'build a C++11+ extension module using Pybind11Extension with automatic compiler flags for Windows, macOS, and Unix', 'build_ext_auto_cpp_level': 'build extensions using the customized build_ext class that auto-detects the highest supported C++ standard level', 'generate_intree_extensions': 'generate Pybind11Extension objects from source files located directly in a Python source tree using intree_extensions', 'parallel_compile_install': 'install parallel compilation into distutils by calling ParallelCompile with an environment variable and install method', 'check_compiler_flag_support': 'check if a compiler supports a specific flag by calling has_flag with the compiler and flag string'}
```

