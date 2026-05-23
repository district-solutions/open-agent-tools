# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/tools/distrib/python/grpcio_tools/_parallel_compile_patch.py

Prompts

```
['run the _parallel_compile function to compile C/C++ sources in parallel using a thread pool', 'run monkeypatch_compile_maybe to patch distutils CCompiler with parallel compilation when multiple CPUs are available', 'review the _parallel_compile function to understand how it sets up and dispatches parallel C/C++ compilation', 'review the monkeypatch_compile_maybe function to understand the conditional monkey-patching logic for parallel builds', 'summarize the BUILD_EXT_COMPILER_JOBS variable which reads from GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS env var or falls back to cpu count', 'build a python package to compile and install grpcio-tools with protobuf code generator support', 'build the grpcio-tools Cython extension module by setting GRPC_PYTHON_BUILD_WITH_CYTHON environment variable', 'check if the system linker requires libatomic for C++ atomic operations support', 'configure platform-specific compiler and linker arguments for Windows Linux or macOS builds', 'package protobuf descriptor files into the grpc_tools._proto resource directory for distribution']
```

Usage

```
{'run_parallel_compile': 'run the _parallel_compile function to compile C/C++ sources in parallel using a thread pool', 'run_monkeypatch_compile_maybe': 'run monkeypatch_compile_maybe to patch distutils CCompiler with parallel compilation when multiple CPUs are available', 'review_parallel_compile': 'review the _parallel_compile function to understand how it sets up and dispatches parallel C/C++ compilation', 'review_monkeypatch_compile_maybe': 'review the monkeypatch_compile_maybe function to understand the conditional monkey-patching logic for parallel builds', 'summarize_BUILD_EXT_COMPILER_JOBS': 'summarize the BUILD_EXT_COMPILER_JOBS variable which reads from GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS env var or falls back to cpu count'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/distrib/python/grpcio_tools/setup.py

Prompts

```
['run the _parallel_compile function to compile C/C++ sources in parallel using a thread pool', 'run monkeypatch_compile_maybe to patch distutils CCompiler with parallel compilation when multiple CPUs are available', 'review the _parallel_compile function to understand how it sets up and dispatches parallel C/C++ compilation', 'review the monkeypatch_compile_maybe function to understand the conditional monkey-patching logic for parallel builds', 'summarize the BUILD_EXT_COMPILER_JOBS variable which reads from GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS env var or falls back to cpu count', 'build a python package to compile and install grpcio-tools with protobuf code generator support', 'build the grpcio-tools Cython extension module by setting GRPC_PYTHON_BUILD_WITH_CYTHON environment variable', 'check if the system linker requires libatomic for C++ atomic operations support', 'configure platform-specific compiler and linker arguments for Windows Linux or macOS builds', 'package protobuf descriptor files into the grpc_tools._proto resource directory for distribution']
```

Usage

```
{'build_grpcio_tools_package': 'build a python package to compile and install grpcio-tools with protobuf code generator support', 'build_cython_extension': 'build the grpcio-tools Cython extension module by setting GRPC_PYTHON_BUILD_WITH_CYTHON environment variable', 'check_linker_libatomic': 'check if the system linker requires libatomic for C++ atomic operations support', 'configure_platform_compile_args': 'configure platform-specific compiler and linker arguments for Windows Linux or macOS builds', 'package_proto_files': 'package protobuf descriptor files into the grpc_tools._proto resource directory for distribution'}
```

