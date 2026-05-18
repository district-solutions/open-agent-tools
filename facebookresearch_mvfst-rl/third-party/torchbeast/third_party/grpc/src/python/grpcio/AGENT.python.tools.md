# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/src/python/grpcio/_parallel_compile_patch.py

Prompts

```
['run monkeypatch_compile_maybe to enable parallel C/C++ compilation during gRPC Python extension builds', 'review the _parallel_compile function that uses ThreadPool to compile C/C++ source files in parallel', 'build a gRPC Python extension with GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS set to enable parallel compilation', 'refactor the BUILD_EXT_COMPILER_JOBS environment variable parsing to support additional fallback logic', 'test monkeypatch_compile_maybe to verify CCompiler.compile is patched when jobs are greater than one', 'call monkeypatch_spawn to patch CCompiler.spawn with command file support for long Windows commands', 'review the _commandfile_spawn function that writes escaped args to a temp command file on Windows', 'test that monkeypatch_spawn correctly replaces CCompiler.spawn with the command file variant', 'refactor _commandfile_spawn to use a different escaping strategy for backslashes in command arguments', 'summarize the MAX_COMMAND_LENGTH constant set to 8191 for the Windows command line limit', 'run the SphinxDocumentation command to generate HTML documentation from the gRPC Python Sphinx source directory', 'run the BuildProjectMetadata command to generate the grpcio version metadata module file', 'run try_cythonize on a list of distutils Extension objects to generate C files from Cython sources', 'run the BuildExt command to compile C and C++ extensions with compiler-specific flags and Cython support', 'run the Gather command to fetch install or test dependencies for the grpcio distribution', 'diagnose a compilation error during a Python C extension build by checking for missing Python.h', 'diagnose an AttributeError during build caused by missing _needs_stub in older setuptools versions', 'diagnose a build_ext error by dispatching to the appropriate diagnostic function based on error type', 'compile a C source string using a distutils compiler in a temporary directory', 'expect a C source string to compile successfully and raise an error if it fails']
```

Usage

```
{'run_parallel_compile_patch': 'run monkeypatch_compile_maybe to enable parallel C/C++ compilation during gRPC Python extension builds', 'review_parallel_compile': 'review the _parallel_compile function that uses ThreadPool to compile C/C++ source files in parallel', 'build_grpc_python_extension': 'build a gRPC Python extension with GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS set to enable parallel compilation', 'refactor_compile_jobs': 'refactor the BUILD_EXT_COMPILER_JOBS environment variable parsing to support additional fallback logic', 'test_monkeypatch_compile': 'test monkeypatch_compile_maybe to verify CCompiler.compile is patched when jobs are greater than one'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/src/python/grpcio/_spawn_patch.py

Prompts

```
['run monkeypatch_compile_maybe to enable parallel C/C++ compilation during gRPC Python extension builds', 'review the _parallel_compile function that uses ThreadPool to compile C/C++ source files in parallel', 'build a gRPC Python extension with GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS set to enable parallel compilation', 'refactor the BUILD_EXT_COMPILER_JOBS environment variable parsing to support additional fallback logic', 'test monkeypatch_compile_maybe to verify CCompiler.compile is patched when jobs are greater than one', 'call monkeypatch_spawn to patch CCompiler.spawn with command file support for long Windows commands', 'review the _commandfile_spawn function that writes escaped args to a temp command file on Windows', 'test that monkeypatch_spawn correctly replaces CCompiler.spawn with the command file variant', 'refactor _commandfile_spawn to use a different escaping strategy for backslashes in command arguments', 'summarize the MAX_COMMAND_LENGTH constant set to 8191 for the Windows command line limit', 'run the SphinxDocumentation command to generate HTML documentation from the gRPC Python Sphinx source directory', 'run the BuildProjectMetadata command to generate the grpcio version metadata module file', 'run try_cythonize on a list of distutils Extension objects to generate C files from Cython sources', 'run the BuildExt command to compile C and C++ extensions with compiler-specific flags and Cython support', 'run the Gather command to fetch install or test dependencies for the grpcio distribution', 'diagnose a compilation error during a Python C extension build by checking for missing Python.h', 'diagnose an AttributeError during build caused by missing _needs_stub in older setuptools versions', 'diagnose a build_ext error by dispatching to the appropriate diagnostic function based on error type', 'compile a C source string using a distutils compiler in a temporary directory', 'expect a C source string to compile successfully and raise an error if it fails']
```

Usage

```
{'monkeypatch_spawn': 'call monkeypatch_spawn to patch CCompiler.spawn with command file support for long Windows commands', 'review_commandfile_spawn': 'review the _commandfile_spawn function that writes escaped args to a temp command file on Windows', 'test_monkeypatch_spawn': 'test that monkeypatch_spawn correctly replaces CCompiler.spawn with the command file variant', 'refactor_commandfile_spawn': 'refactor _commandfile_spawn to use a different escaping strategy for backslashes in command arguments', 'summarize_MAX_COMMAND_LENGTH': 'summarize the MAX_COMMAND_LENGTH constant set to 8191 for the Windows command line limit'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/src/python/grpcio/commands.py

Prompts

```
['run monkeypatch_compile_maybe to enable parallel C/C++ compilation during gRPC Python extension builds', 'review the _parallel_compile function that uses ThreadPool to compile C/C++ source files in parallel', 'build a gRPC Python extension with GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS set to enable parallel compilation', 'refactor the BUILD_EXT_COMPILER_JOBS environment variable parsing to support additional fallback logic', 'test monkeypatch_compile_maybe to verify CCompiler.compile is patched when jobs are greater than one', 'call monkeypatch_spawn to patch CCompiler.spawn with command file support for long Windows commands', 'review the _commandfile_spawn function that writes escaped args to a temp command file on Windows', 'test that monkeypatch_spawn correctly replaces CCompiler.spawn with the command file variant', 'refactor _commandfile_spawn to use a different escaping strategy for backslashes in command arguments', 'summarize the MAX_COMMAND_LENGTH constant set to 8191 for the Windows command line limit', 'run the SphinxDocumentation command to generate HTML documentation from the gRPC Python Sphinx source directory', 'run the BuildProjectMetadata command to generate the grpcio version metadata module file', 'run try_cythonize on a list of distutils Extension objects to generate C files from Cython sources', 'run the BuildExt command to compile C and C++ extensions with compiler-specific flags and Cython support', 'run the Gather command to fetch install or test dependencies for the grpcio distribution', 'diagnose a compilation error during a Python C extension build by checking for missing Python.h', 'diagnose an AttributeError during build caused by missing _needs_stub in older setuptools versions', 'diagnose a build_ext error by dispatching to the appropriate diagnostic function based on error type', 'compile a C source string using a distutils compiler in a temporary directory', 'expect a C source string to compile successfully and raise an error if it fails']
```

Usage

```
{'build_sphinx_documentation': 'run the SphinxDocumentation command to generate HTML documentation from the gRPC Python Sphinx source directory', 'build_project_metadata': 'run the BuildProjectMetadata command to generate the grpcio version metadata module file', 'cythonize_extensions': 'run try_cythonize on a list of distutils Extension objects to generate C files from Cython sources', 'build_extensions': 'run the BuildExt command to compile C and C++ extensions with compiler-specific flags and Cython support', 'gather_dependencies': 'run the Gather command to fetch install or test dependencies for the grpcio distribution'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/src/python/grpcio/support.py

Prompts

```
['run monkeypatch_compile_maybe to enable parallel C/C++ compilation during gRPC Python extension builds', 'review the _parallel_compile function that uses ThreadPool to compile C/C++ source files in parallel', 'build a gRPC Python extension with GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS set to enable parallel compilation', 'refactor the BUILD_EXT_COMPILER_JOBS environment variable parsing to support additional fallback logic', 'test monkeypatch_compile_maybe to verify CCompiler.compile is patched when jobs are greater than one', 'call monkeypatch_spawn to patch CCompiler.spawn with command file support for long Windows commands', 'review the _commandfile_spawn function that writes escaped args to a temp command file on Windows', 'test that monkeypatch_spawn correctly replaces CCompiler.spawn with the command file variant', 'refactor _commandfile_spawn to use a different escaping strategy for backslashes in command arguments', 'summarize the MAX_COMMAND_LENGTH constant set to 8191 for the Windows command line limit', 'run the SphinxDocumentation command to generate HTML documentation from the gRPC Python Sphinx source directory', 'run the BuildProjectMetadata command to generate the grpcio version metadata module file', 'run try_cythonize on a list of distutils Extension objects to generate C files from Cython sources', 'run the BuildExt command to compile C and C++ extensions with compiler-specific flags and Cython support', 'run the Gather command to fetch install or test dependencies for the grpcio distribution', 'diagnose a compilation error during a Python C extension build by checking for missing Python.h', 'diagnose an AttributeError during build caused by missing _needs_stub in older setuptools versions', 'diagnose a build_ext error by dispatching to the appropriate diagnostic function based on error type', 'compile a C source string using a distutils compiler in a temporary directory', 'expect a C source string to compile successfully and raise an error if it fails']
```

Usage

```
{'diagnose_compile_error': 'diagnose a compilation error during a Python C extension build by checking for missing Python.h', 'diagnose_attribute_error': 'diagnose an AttributeError during build caused by missing _needs_stub in older setuptools versions', 'diagnose_build_ext_error': 'diagnose a build_ext error by dispatching to the appropriate diagnostic function based on error type', 'compile_c_source': 'compile a C source string using a distutils compiler in a temporary directory', 'expect_compile_success': 'expect a C source string to compile successfully and raise an error if it fails'}
```

