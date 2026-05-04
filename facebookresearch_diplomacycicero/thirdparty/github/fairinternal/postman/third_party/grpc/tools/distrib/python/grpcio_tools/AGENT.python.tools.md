# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/tools/distrib/python/grpcio_tools/_parallel_compile_patch.py

Prompts

```
['run the _parallel_compile function to compile C/C++ sources in parallel using a ThreadPool', 'run monkeypatch_compile_maybe to patch distutils CCompiler with parallel compilation when GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS is greater than 1', 'review the _parallel_compile function that uses multiprocessing ThreadPool to compile individual C/C++ files in parallel', 'review the monkeypatch_compile_maybe function that conditionally monkey-patches distutils.ccompiler.CCompiler.compile for parallel builds', 'summarize the BUILD_EXT_COMPILER_JOBS variable read from the GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS environment variable', 'build the grpcio-tools Python package by running python setup.py build to compile the protoc compiler C++ extension', 'test if the system linker requires the libatomic library by compiling a small C++ atomic test program', 'configure the grpc_tools._protoc_compiler C++ extension module with platform-specific compile and link flags', 'copy protobuf descriptor files from the include directory into the grpc_tools._proto package data directory', 'install the grpcio-tools package with pip to get the Protobuf code generator for gRPC']
```

Usage

```
{'run_parallel_compile': 'run the _parallel_compile function to compile C/C++ sources in parallel using a ThreadPool', 'run_monkeypatch_compile_maybe': 'run monkeypatch_compile_maybe to patch distutils CCompiler with parallel compilation when GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS is greater than 1', 'review_parallel_compile': 'review the _parallel_compile function that uses multiprocessing ThreadPool to compile individual C/C++ files in parallel', 'review_monkeypatch_compile_maybe': 'review the monkeypatch_compile_maybe function that conditionally monkey-patches distutils.ccompiler.CCompiler.compile for parallel builds', 'summarize_BUILD_EXT_COMPILER_JOBS': 'summarize the BUILD_EXT_COMPILER_JOBS variable read from the GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS environment variable'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/tools/distrib/python/grpcio_tools/setup.py

Prompts

```
['run the _parallel_compile function to compile C/C++ sources in parallel using a ThreadPool', 'run monkeypatch_compile_maybe to patch distutils CCompiler with parallel compilation when GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS is greater than 1', 'review the _parallel_compile function that uses multiprocessing ThreadPool to compile individual C/C++ files in parallel', 'review the monkeypatch_compile_maybe function that conditionally monkey-patches distutils.ccompiler.CCompiler.compile for parallel builds', 'summarize the BUILD_EXT_COMPILER_JOBS variable read from the GRPC_PYTHON_BUILD_EXT_COMPILER_JOBS environment variable', 'build the grpcio-tools Python package by running python setup.py build to compile the protoc compiler C++ extension', 'test if the system linker requires the libatomic library by compiling a small C++ atomic test program', 'configure the grpc_tools._protoc_compiler C++ extension module with platform-specific compile and link flags', 'copy protobuf descriptor files from the include directory into the grpc_tools._proto package data directory', 'install the grpcio-tools package with pip to get the Protobuf code generator for gRPC']
```

Usage

```
{'build_grpcio_tools_package': 'build the grpcio-tools Python package by running python setup.py build to compile the protoc compiler C++ extension', 'check_linker_need_libatomic': 'test if the system linker requires the libatomic library by compiling a small C++ atomic test program', 'configure_extension_modules': 'configure the grpc_tools._protoc_compiler C++ extension module with platform-specific compile and link flags', 'copy_proto_resources': 'copy protobuf descriptor files from the include directory into the grpc_tools._proto package data directory', 'install_grpcio_tools': 'install the grpcio-tools package with pip to get the Protobuf code generator for gRPC'}
```

