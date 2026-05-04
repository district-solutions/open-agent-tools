# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio/_parallel_compile_patch.py

Prompts

```
['run parallel C/C++ compilation by calling _parallel_compile with sources and output_dir arguments', 'run monkeypatch_compile_maybe to enable parallel compilation when GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS is greater than 1', 'review the _parallel_compile function that uses ThreadPool to compile C/C++ source files in parallel', 'review the monkeypatch_compile_maybe function that patches distutils CCompiler.compile for parallel builds', 'summarize the BUILD_EXT_COMPILER_JOBS variable read from the GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS environment variable', 'run monkeypatch_spawn to patch CCompiler.spawn for Windows command line length limits', 'review the _commandfile_spawn function that writes long commands to a temporary file', 'test monkeypatch_spawn to verify CCompiler.spawn is replaced with _commandfile_spawn', 'refactor _commandfile_spawn to support additional compiler command file directives', 'summarize the MAX_COMMAND_LENGTH constant set to 8191 for Windows command line limit', 'run the SphinxDocumentation command to generate HTML documentation from the gRPC Python Sphinx source directory', 'run the BuildProjectMetadata command to generate the grpcio version metadata module file', 'run try_cythonize on a list of distutils Extension objects to generate C source files from Cython', 'run check_and_update_cythonization to replace .pyx sources with pre-generated C or C++ counterparts', 'run the Gather command with test or install flags to fetch build eggs for grpcio dependencies', 'diagnose a build_ext error by analyzing the exception type and providing actionable error messages', 'diagnose a compilation error by checking for missing Python.h headers and missing Cython source files', 'diagnose an attribute error caused by missing _needs_stub in older setuptools versions', 'compile a C source string using a distutils compiler in a temporary directory', 'expect a C source string to compile successfully and raise an error if it fails']
```

Usage

```
{'run_parallel_compile': 'run parallel C/C++ compilation by calling _parallel_compile with sources and output_dir arguments', 'run_monkeypatch_compile_maybe': 'run monkeypatch_compile_maybe to enable parallel compilation when GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS is greater than 1', 'review_parallel_compile': 'review the _parallel_compile function that uses ThreadPool to compile C/C++ source files in parallel', 'review_monkeypatch_compile_maybe': 'review the monkeypatch_compile_maybe function that patches distutils CCompiler.compile for parallel builds', 'summarize_BUILD_EXT_COMPILER_JOBS': 'summarize the BUILD_EXT_COMPILER_JOBS variable read from the GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS environment variable'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio/_spawn_patch.py

Prompts

```
['run parallel C/C++ compilation by calling _parallel_compile with sources and output_dir arguments', 'run monkeypatch_compile_maybe to enable parallel compilation when GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS is greater than 1', 'review the _parallel_compile function that uses ThreadPool to compile C/C++ source files in parallel', 'review the monkeypatch_compile_maybe function that patches distutils CCompiler.compile for parallel builds', 'summarize the BUILD_EXT_COMPILER_JOBS variable read from the GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS environment variable', 'run monkeypatch_spawn to patch CCompiler.spawn for Windows command line length limits', 'review the _commandfile_spawn function that writes long commands to a temporary file', 'test monkeypatch_spawn to verify CCompiler.spawn is replaced with _commandfile_spawn', 'refactor _commandfile_spawn to support additional compiler command file directives', 'summarize the MAX_COMMAND_LENGTH constant set to 8191 for Windows command line limit', 'run the SphinxDocumentation command to generate HTML documentation from the gRPC Python Sphinx source directory', 'run the BuildProjectMetadata command to generate the grpcio version metadata module file', 'run try_cythonize on a list of distutils Extension objects to generate C source files from Cython', 'run check_and_update_cythonization to replace .pyx sources with pre-generated C or C++ counterparts', 'run the Gather command with test or install flags to fetch build eggs for grpcio dependencies', 'diagnose a build_ext error by analyzing the exception type and providing actionable error messages', 'diagnose a compilation error by checking for missing Python.h headers and missing Cython source files', 'diagnose an attribute error caused by missing _needs_stub in older setuptools versions', 'compile a C source string using a distutils compiler in a temporary directory', 'expect a C source string to compile successfully and raise an error if it fails']
```

Usage

```
{'run_monkeypatch_spawn': 'run monkeypatch_spawn to patch CCompiler.spawn for Windows command line length limits', 'review_commandfile_spawn': 'review the _commandfile_spawn function that writes long commands to a temporary file', 'test_monkeypatch_spawn': 'test monkeypatch_spawn to verify CCompiler.spawn is replaced with _commandfile_spawn', 'refactor_commandfile_spawn': 'refactor _commandfile_spawn to support additional compiler command file directives', 'summarize_MAX_COMMAND_LENGTH': 'summarize the MAX_COMMAND_LENGTH constant set to 8191 for Windows command line limit'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio/commands.py

Prompts

```
['run parallel C/C++ compilation by calling _parallel_compile with sources and output_dir arguments', 'run monkeypatch_compile_maybe to enable parallel compilation when GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS is greater than 1', 'review the _parallel_compile function that uses ThreadPool to compile C/C++ source files in parallel', 'review the monkeypatch_compile_maybe function that patches distutils CCompiler.compile for parallel builds', 'summarize the BUILD_EXT_COMPILER_JOBS variable read from the GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS environment variable', 'run monkeypatch_spawn to patch CCompiler.spawn for Windows command line length limits', 'review the _commandfile_spawn function that writes long commands to a temporary file', 'test monkeypatch_spawn to verify CCompiler.spawn is replaced with _commandfile_spawn', 'refactor _commandfile_spawn to support additional compiler command file directives', 'summarize the MAX_COMMAND_LENGTH constant set to 8191 for Windows command line limit', 'run the SphinxDocumentation command to generate HTML documentation from the gRPC Python Sphinx source directory', 'run the BuildProjectMetadata command to generate the grpcio version metadata module file', 'run try_cythonize on a list of distutils Extension objects to generate C source files from Cython', 'run check_and_update_cythonization to replace .pyx sources with pre-generated C or C++ counterparts', 'run the Gather command with test or install flags to fetch build eggs for grpcio dependencies', 'diagnose a build_ext error by analyzing the exception type and providing actionable error messages', 'diagnose a compilation error by checking for missing Python.h headers and missing Cython source files', 'diagnose an attribute error caused by missing _needs_stub in older setuptools versions', 'compile a C source string using a distutils compiler in a temporary directory', 'expect a C source string to compile successfully and raise an error if it fails']
```

Usage

```
{'build_sphinx_documentation': 'run the SphinxDocumentation command to generate HTML documentation from the gRPC Python Sphinx source directory', 'build_project_metadata': 'run the BuildProjectMetadata command to generate the grpcio version metadata module file', 'cythonize_extensions': 'run try_cythonize on a list of distutils Extension objects to generate C source files from Cython', 'check_cythonization': 'run check_and_update_cythonization to replace .pyx sources with pre-generated C or C++ counterparts', 'gather_dependencies': 'run the Gather command with test or install flags to fetch build eggs for grpcio dependencies'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/src/python/grpcio/support.py

Prompts

```
['run parallel C/C++ compilation by calling _parallel_compile with sources and output_dir arguments', 'run monkeypatch_compile_maybe to enable parallel compilation when GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS is greater than 1', 'review the _parallel_compile function that uses ThreadPool to compile C/C++ source files in parallel', 'review the monkeypatch_compile_maybe function that patches distutils CCompiler.compile for parallel builds', 'summarize the BUILD_EXT_COMPILER_JOBS variable read from the GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS environment variable', 'run monkeypatch_spawn to patch CCompiler.spawn for Windows command line length limits', 'review the _commandfile_spawn function that writes long commands to a temporary file', 'test monkeypatch_spawn to verify CCompiler.spawn is replaced with _commandfile_spawn', 'refactor _commandfile_spawn to support additional compiler command file directives', 'summarize the MAX_COMMAND_LENGTH constant set to 8191 for Windows command line limit', 'run the SphinxDocumentation command to generate HTML documentation from the gRPC Python Sphinx source directory', 'run the BuildProjectMetadata command to generate the grpcio version metadata module file', 'run try_cythonize on a list of distutils Extension objects to generate C source files from Cython', 'run check_and_update_cythonization to replace .pyx sources with pre-generated C or C++ counterparts', 'run the Gather command with test or install flags to fetch build eggs for grpcio dependencies', 'diagnose a build_ext error by analyzing the exception type and providing actionable error messages', 'diagnose a compilation error by checking for missing Python.h headers and missing Cython source files', 'diagnose an attribute error caused by missing _needs_stub in older setuptools versions', 'compile a C source string using a distutils compiler in a temporary directory', 'expect a C source string to compile successfully and raise an error if it fails']
```

Usage

```
{'diagnose_build_ext_error': 'diagnose a build_ext error by analyzing the exception type and providing actionable error messages', 'diagnose_compile_error': 'diagnose a compilation error by checking for missing Python.h headers and missing Cython source files', 'diagnose_attribute_error': 'diagnose an attribute error caused by missing _needs_stub in older setuptools versions', 'compile_c_source': 'compile a C source string using a distutils compiler in a temporary directory', 'expect_compile_check': 'expect a C source string to compile successfully and raise an error if it fails'}
```

