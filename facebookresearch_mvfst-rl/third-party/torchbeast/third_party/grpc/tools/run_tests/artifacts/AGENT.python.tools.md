# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/tools/run_tests/artifacts/artifact_targets.py

Prompts

```
['create a PythonArtifact for manylinux1 x64 cp38-cp38 and generate its build jobspec', 'create a CSharpExtArtifact for linux x64 and generate its build jobspec for the native extension', 'create a ProtocArtifact for macos x64 and generate its build jobspec for protoc binaries', 'create a docker jobspec using create_docker_jobspec with a custom dockerfile dir and shell command', 'call the targets function to get the complete list of all supported artifact build targets', 'create a jobspec for running a distribution test command line with optional workspace isolation', 'build a CSharpDistribTest jobspec to test the C# NuGet package on linux, macos, or windows', 'build a PythonDistribTest jobspec to test the Python package on linux with optional source mode', 'get the full list of supported distribution test targets across all languages and platforms', 'build a C# NuGet or Unity package jobspec for Windows distribution', 'build a Python egg and wheel package jobspec using a Docker container', 'get a list of all supported package build targets including CSharp, Ruby, Python, and PHP']
```

Usage

```
{'create_python_artifact_jobspec': 'create a PythonArtifact for manylinux1 x64 cp38-cp38 and generate its build jobspec', 'create_csharp_artifact_jobspec': 'create a CSharpExtArtifact for linux x64 and generate its build jobspec for the native extension', 'create_protoc_artifact_jobspec': 'create a ProtocArtifact for macos x64 and generate its build jobspec for protoc binaries', 'create_docker_jobspec': 'create a docker jobspec using create_docker_jobspec with a custom dockerfile dir and shell command', 'list_all_artifact_targets': 'call the targets function to get the complete list of all supported artifact build targets'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/tools/run_tests/artifacts/distribtest_targets.py

Prompts

```
['create a PythonArtifact for manylinux1 x64 cp38-cp38 and generate its build jobspec', 'create a CSharpExtArtifact for linux x64 and generate its build jobspec for the native extension', 'create a ProtocArtifact for macos x64 and generate its build jobspec for protoc binaries', 'create a docker jobspec using create_docker_jobspec with a custom dockerfile dir and shell command', 'call the targets function to get the complete list of all supported artifact build targets', 'create a jobspec for running a distribution test command line with optional workspace isolation', 'build a CSharpDistribTest jobspec to test the C# NuGet package on linux, macos, or windows', 'build a PythonDistribTest jobspec to test the Python package on linux with optional source mode', 'get the full list of supported distribution test targets across all languages and platforms', 'build a C# NuGet or Unity package jobspec for Windows distribution', 'build a Python egg and wheel package jobspec using a Docker container', 'get a list of all supported package build targets including CSharp, Ruby, Python, and PHP']
```

Usage

```
{'create_docker_jobspec': 'create a docker jobspec for running a distribution test shell command inside a container', 'create_jobspec': 'create a jobspec for running a distribution test command line with optional workspace isolation', 'build_CSharpDistribTest': 'build a CSharpDistribTest jobspec to test the C# NuGet package on linux, macos, or windows', 'build_PythonDistribTest': 'build a PythonDistribTest jobspec to test the Python package on linux with optional source mode', 'get_targets': 'get the full list of supported distribution test targets across all languages and platforms'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/tools/run_tests/artifacts/package_targets.py

Prompts

```
['create a PythonArtifact for manylinux1 x64 cp38-cp38 and generate its build jobspec', 'create a CSharpExtArtifact for linux x64 and generate its build jobspec for the native extension', 'create a ProtocArtifact for macos x64 and generate its build jobspec for protoc binaries', 'create a docker jobspec using create_docker_jobspec with a custom dockerfile dir and shell command', 'call the targets function to get the complete list of all supported artifact build targets', 'create a jobspec for running a distribution test command line with optional workspace isolation', 'build a CSharpDistribTest jobspec to test the C# NuGet package on linux, macos, or windows', 'build a PythonDistribTest jobspec to test the Python package on linux with optional source mode', 'get the full list of supported distribution test targets across all languages and platforms', 'build a C# NuGet or Unity package jobspec for Windows distribution', 'build a Python egg and wheel package jobspec using a Docker container', 'get a list of all supported package build targets including CSharp, Ruby, Python, and PHP']
```

Usage

```
{'create_docker_jobspec': 'create a docker jobspec for running a shell command inside a gRPC artifact container', 'create_jobspec': 'create a jobspec with a custom command line, working directory, and cpu cost', 'CSharpPackage_build_jobspec': 'build a C# NuGet or Unity package jobspec for Windows distribution', 'PythonPackage_build_jobspec': 'build a Python egg and wheel package jobspec using a Docker container', 'targets': 'get a list of all supported package build targets including CSharp, Ruby, Python, and PHP'}
```

