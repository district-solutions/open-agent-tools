# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio/_parallel_compile_patch.py

Prompts

```
['call monkeypatch_compile_maybe to enable parallel compilation of C/C++ files in distutils build_ext', 'use _parallel_compile to compile C/C++ source files in parallel using a ThreadPool', 'set the GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS environment variable to control the number of parallel compilation jobs', 'review the _parallel_compile function to understand how it patches distutils.ccompiler.CCompiler.compile for parallel builds', 'summarize how monkeypatch_compile_maybe replaces CCompiler.compile with _parallel_compile when more than one CPU is available', 'monkeypatch the CCompiler spawn method to handle long command lines on Windows', 'spawn a compiler command using a temporary command file when the command line exceeds 8191 characters', 'call the original CCompiler spawn method with the given command arguments', 'review the monkeypatch_spawn function that patches CCompiler.spawn for Windows command line limits', 'summarize the _commandfile_spawn function that writes long commands to a temp file', 'build sphinx HTML documentation from the gRPC Python source directory to a build output directory', 'build a grpcio project metadata module that writes the current version string to a Python file', 'try to cythonize a list of distutils extension modules with optional linetracing support', 'clean gRPC Python build artifacts including compiled Cython files, cache directories, and egg-info', 'gather and fetch install or test dependencies for the grpcio project using setuptools build eggs', 'diagnose a build_ext compilation error by running C checks and reporting missing source files', 'diagnose a compilation error by checking for missing Python.h headers and Cython source files', 'diagnose a missing _needs_stub attribute error caused by an outdated setuptools version', 'compile a C source string using a distutils compiler in a temporary directory', 'expect a C source string to compile successfully and raise an error if it fails']
```

Usage

```
{'monkeypatch_compile_maybe': 'call monkeypatch_compile_maybe to enable parallel compilation of C/C++ files in distutils build_ext', 'parallel_compile_CCompiler': 'use _parallel_compile to compile C/C++ source files in parallel using a ThreadPool', 'set_GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS': 'set the GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS environment variable to control the number of parallel compilation jobs', 'review_parallel_compile': 'review the _parallel_compile function to understand how it patches distutils.ccompiler.CCompiler.compile for parallel builds', 'summarize_monkeypatch': 'summarize how monkeypatch_compile_maybe replaces CCompiler.compile with _parallel_compile when more than one CPU is available'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio/_spawn_patch.py

Prompts

```
['call monkeypatch_compile_maybe to enable parallel compilation of C/C++ files in distutils build_ext', 'use _parallel_compile to compile C/C++ source files in parallel using a ThreadPool', 'set the GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS environment variable to control the number of parallel compilation jobs', 'review the _parallel_compile function to understand how it patches distutils.ccompiler.CCompiler.compile for parallel builds', 'summarize how monkeypatch_compile_maybe replaces CCompiler.compile with _parallel_compile when more than one CPU is available', 'monkeypatch the CCompiler spawn method to handle long command lines on Windows', 'spawn a compiler command using a temporary command file when the command line exceeds 8191 characters', 'call the original CCompiler spawn method with the given command arguments', 'review the monkeypatch_spawn function that patches CCompiler.spawn for Windows command line limits', 'summarize the _commandfile_spawn function that writes long commands to a temp file', 'build sphinx HTML documentation from the gRPC Python source directory to a build output directory', 'build a grpcio project metadata module that writes the current version string to a Python file', 'try to cythonize a list of distutils extension modules with optional linetracing support', 'clean gRPC Python build artifacts including compiled Cython files, cache directories, and egg-info', 'gather and fetch install or test dependencies for the grpcio project using setuptools build eggs', 'diagnose a build_ext compilation error by running C checks and reporting missing source files', 'diagnose a compilation error by checking for missing Python.h headers and Cython source files', 'diagnose a missing _needs_stub attribute error caused by an outdated setuptools version', 'compile a C source string using a distutils compiler in a temporary directory', 'expect a C source string to compile successfully and raise an error if it fails']
```

Usage

```
{'monkeypatch_spawn': 'monkeypatch the CCompiler spawn method to handle long command lines on Windows', 'commandfile_spawn': 'spawn a compiler command using a temporary command file when the command line exceeds 8191 characters', 'classic_spawn': 'call the original CCompiler spawn method with the given command arguments', 'review_monkeypatch_spawn': 'review the monkeypatch_spawn function that patches CCompiler.spawn for Windows command line limits', 'summarize_commandfile_spawn': 'summarize the _commandfile_spawn function that writes long commands to a temp file'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio/commands.py

Prompts

```
['call monkeypatch_compile_maybe to enable parallel compilation of C/C++ files in distutils build_ext', 'use _parallel_compile to compile C/C++ source files in parallel using a ThreadPool', 'set the GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS environment variable to control the number of parallel compilation jobs', 'review the _parallel_compile function to understand how it patches distutils.ccompiler.CCompiler.compile for parallel builds', 'summarize how monkeypatch_compile_maybe replaces CCompiler.compile with _parallel_compile when more than one CPU is available', 'monkeypatch the CCompiler spawn method to handle long command lines on Windows', 'spawn a compiler command using a temporary command file when the command line exceeds 8191 characters', 'call the original CCompiler spawn method with the given command arguments', 'review the monkeypatch_spawn function that patches CCompiler.spawn for Windows command line limits', 'summarize the _commandfile_spawn function that writes long commands to a temp file', 'build sphinx HTML documentation from the gRPC Python source directory to a build output directory', 'build a grpcio project metadata module that writes the current version string to a Python file', 'try to cythonize a list of distutils extension modules with optional linetracing support', 'clean gRPC Python build artifacts including compiled Cython files, cache directories, and egg-info', 'gather and fetch install or test dependencies for the grpcio project using setuptools build eggs', 'diagnose a build_ext compilation error by running C checks and reporting missing source files', 'diagnose a compilation error by checking for missing Python.h headers and Cython source files', 'diagnose a missing _needs_stub attribute error caused by an outdated setuptools version', 'compile a C source string using a distutils compiler in a temporary directory', 'expect a C source string to compile successfully and raise an error if it fails']
```

Usage

```
{'build_sphinx_documentation': 'build sphinx HTML documentation from the gRPC Python source directory to a build output directory', 'build_project_metadata': 'build a grpcio project metadata module that writes the current version string to a Python file', 'try_cythonize_extensions': 'try to cythonize a list of distutils extension modules with optional linetracing support', 'clean_build_artifacts': 'clean gRPC Python build artifacts including compiled Cython files, cache directories, and egg-info', 'gather_dependencies': 'gather and fetch install or test dependencies for the grpcio project using setuptools build eggs'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio/support.py

Prompts

```
['call monkeypatch_compile_maybe to enable parallel compilation of C/C++ files in distutils build_ext', 'use _parallel_compile to compile C/C++ source files in parallel using a ThreadPool', 'set the GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS environment variable to control the number of parallel compilation jobs', 'review the _parallel_compile function to understand how it patches distutils.ccompiler.CCompiler.compile for parallel builds', 'summarize how monkeypatch_compile_maybe replaces CCompiler.compile with _parallel_compile when more than one CPU is available', 'monkeypatch the CCompiler spawn method to handle long command lines on Windows', 'spawn a compiler command using a temporary command file when the command line exceeds 8191 characters', 'call the original CCompiler spawn method with the given command arguments', 'review the monkeypatch_spawn function that patches CCompiler.spawn for Windows command line limits', 'summarize the _commandfile_spawn function that writes long commands to a temp file', 'build sphinx HTML documentation from the gRPC Python source directory to a build output directory', 'build a grpcio project metadata module that writes the current version string to a Python file', 'try to cythonize a list of distutils extension modules with optional linetracing support', 'clean gRPC Python build artifacts including compiled Cython files, cache directories, and egg-info', 'gather and fetch install or test dependencies for the grpcio project using setuptools build eggs', 'diagnose a build_ext compilation error by running C checks and reporting missing source files', 'diagnose a compilation error by checking for missing Python.h headers and Cython source files', 'diagnose a missing _needs_stub attribute error caused by an outdated setuptools version', 'compile a C source string using a distutils compiler in a temporary directory', 'expect a C source string to compile successfully and raise an error if it fails']
```

Usage

```
{'diagnose_build_ext_error': 'diagnose a build_ext compilation error by running C checks and reporting missing source files', 'diagnose_compile_error': 'diagnose a compilation error by checking for missing Python.h headers and Cython source files', 'diagnose_attribute_error': 'diagnose a missing _needs_stub attribute error caused by an outdated setuptools version', 'compile_c_source': 'compile a C source string using a distutils compiler in a temporary directory', 'expect_compile_success': 'expect a C source string to compile successfully and raise an error if it fails'}
```

