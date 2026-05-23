# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/artifacts/artifact_targets.py

Prompts

```
['create a docker jobspec to run a shell command inside a container with environment variables', 'create a jobspec to run a command line task with configurable timeout and retry settings', 'build a Python artifact for a specific platform, architecture, and Python version', 'build protoc and protoc-plugin artifacts for linux, macos, or windows platforms', 'get the list of all supported artifact build targets across languages and platforms', 'build a CSharpDistribTest jobspec to test the C# NuGet package on linux, macos, or windows', 'build a PythonDistribTest jobspec to test the Python distribution package on linux via docker', 'get the full list of supported distribution test targets across C++, C#, Python, Ruby, and PHP7', 'build a C# NuGet package jobspec for Linux using the CSharpPackage class', 'build a C# Unity package jobspec for Linux by passing unity=True to CSharpPackage', 'get the list of all supported package build targets including CSharp, Ruby, Python, and PHP']
```

Usage

```
{'create_docker_jobspec': 'create a docker jobspec to run a shell command inside a container with environment variables', 'create_jobspec': 'create a jobspec to run a command line task with configurable timeout and retry settings', 'build_python_artifact': 'build a Python artifact for a specific platform, architecture, and Python version', 'build_protoc_artifact': 'build protoc and protoc-plugin artifacts for linux, macos, or windows platforms', 'list_artifact_targets': 'get the list of all supported artifact build targets across languages and platforms'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/artifacts/distribtest_targets.py

Prompts

```
['create a docker jobspec to run a shell command inside a container with environment variables', 'create a jobspec to run a command line task with configurable timeout and retry settings', 'build a Python artifact for a specific platform, architecture, and Python version', 'build protoc and protoc-plugin artifacts for linux, macos, or windows platforms', 'get the list of all supported artifact build targets across languages and platforms', 'build a CSharpDistribTest jobspec to test the C# NuGet package on linux, macos, or windows', 'build a PythonDistribTest jobspec to test the Python distribution package on linux via docker', 'get the full list of supported distribution test targets across C++, C#, Python, Ruby, and PHP7', 'build a C# NuGet package jobspec for Linux using the CSharpPackage class', 'build a C# Unity package jobspec for Linux by passing unity=True to CSharpPackage', 'get the list of all supported package build targets including CSharp, Ruby, Python, and PHP']
```

Usage

```
{'create_docker_jobspec': 'create a docker jobspec for running a distribution test task inside a container with a shell command', 'create_jobspec': 'create a jobspec for running a distribution test command with optional workspace isolation and retry settings', 'CSharpDistribTest_build_jobspec': 'build a CSharpDistribTest jobspec to test the C# NuGet package on linux, macos, or windows', 'PythonDistribTest_build_jobspec': 'build a PythonDistribTest jobspec to test the Python distribution package on linux via docker', 'targets': 'get the full list of supported distribution test targets across C++, C#, Python, Ruby, and PHP7'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/artifacts/package_targets.py

Prompts

```
['create a docker jobspec to run a shell command inside a container with environment variables', 'create a jobspec to run a command line task with configurable timeout and retry settings', 'build a Python artifact for a specific platform, architecture, and Python version', 'build protoc and protoc-plugin artifacts for linux, macos, or windows platforms', 'get the list of all supported artifact build targets across languages and platforms', 'build a CSharpDistribTest jobspec to test the C# NuGet package on linux, macos, or windows', 'build a PythonDistribTest jobspec to test the Python distribution package on linux via docker', 'get the full list of supported distribution test targets across C++, C#, Python, Ruby, and PHP7', 'build a C# NuGet package jobspec for Linux using the CSharpPackage class', 'build a C# Unity package jobspec for Linux by passing unity=True to CSharpPackage', 'get the list of all supported package build targets including CSharp, Ruby, Python, and PHP']
```

Usage

```
{'create_docker_jobspec': 'create a docker jobspec for running a shell command inside a gRPC Docker container', 'create_jobspec': 'create a jobspec with a custom command line, environment variables, and retry settings', 'build_CSharpPackage_nuget': 'build a C# NuGet package jobspec for Linux using the CSharpPackage class', 'build_CSharpPackage_unity': 'build a C# Unity package jobspec for Linux by passing unity=True to CSharpPackage', 'get_targets': 'get the list of all supported package build targets including CSharp, Ruby, Python, and PHP'}
```

