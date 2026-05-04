# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/tools/run_tests/artifacts/artifact_targets.py

Prompts

```
['create a docker jobspec for building gRPC artifacts with custom environment variables and base images', 'create a jobspec for building gRPC artifacts with configurable timeout retries and workspace support', 'build a Python artifact for manylinux windows or macos platforms with specific Python versions', 'build a C# native extension library for linux macos windows android or ios platforms', 'list all supported gRPC artifact build targets including Python C# Ruby PHP and protoc artifacts', 'build a CSharpDistribTest instance for a given platform and arch then call build_jobspec', 'build a PythonDistribTest instance for a given platform and arch then call build_jobspec', 'get the full list of supported distribution test targets across all languages and platforms', 'build a C# nuget or unity package by creating a jobspec for the dotnet CLI batch script', 'build a python egg and wheel package by creating a docker jobspec for the python build script']
```

Usage

```
{'create_docker_jobspec': 'create a docker jobspec for building gRPC artifacts with custom environment variables and base images', 'create_jobspec': 'create a jobspec for building gRPC artifacts with configurable timeout retries and workspace support', 'build_PythonArtifact': 'build a Python artifact for manylinux windows or macos platforms with specific Python versions', 'build_CSharpExtArtifact': 'build a C# native extension library for linux macos windows android or ios platforms', 'list_targets': 'list all supported gRPC artifact build targets including Python C# Ruby PHP and protoc artifacts'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/tools/run_tests/artifacts/distribtest_targets.py

Prompts

```
['create a docker jobspec for building gRPC artifacts with custom environment variables and base images', 'create a jobspec for building gRPC artifacts with configurable timeout retries and workspace support', 'build a Python artifact for manylinux windows or macos platforms with specific Python versions', 'build a C# native extension library for linux macos windows android or ios platforms', 'list all supported gRPC artifact build targets including Python C# Ruby PHP and protoc artifacts', 'build a CSharpDistribTest instance for a given platform and arch then call build_jobspec', 'build a PythonDistribTest instance for a given platform and arch then call build_jobspec', 'get the full list of supported distribution test targets across all languages and platforms', 'build a C# nuget or unity package by creating a jobspec for the dotnet CLI batch script', 'build a python egg and wheel package by creating a docker jobspec for the python build script']
```

Usage

```
{'create_docker_jobspec': 'create a docker jobspec for running a distribution test shell command inside a container', 'create_jobspec': 'create a jobspec for running a distribution test command with optional workspace isolation', 'build_CSharpDistribTest': 'build a CSharpDistribTest instance for a given platform and arch then call build_jobspec', 'build_PythonDistribTest': 'build a PythonDistribTest instance for a given platform and arch then call build_jobspec', 'targets': 'get the full list of supported distribution test targets across all languages and platforms'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/tools/run_tests/artifacts/package_targets.py

Prompts

```
['create a docker jobspec for building gRPC artifacts with custom environment variables and base images', 'create a jobspec for building gRPC artifacts with configurable timeout retries and workspace support', 'build a Python artifact for manylinux windows or macos platforms with specific Python versions', 'build a C# native extension library for linux macos windows android or ios platforms', 'list all supported gRPC artifact build targets including Python C# Ruby PHP and protoc artifacts', 'build a CSharpDistribTest instance for a given platform and arch then call build_jobspec', 'build a PythonDistribTest instance for a given platform and arch then call build_jobspec', 'get the full list of supported distribution test targets across all languages and platforms', 'build a C# nuget or unity package by creating a jobspec for the dotnet CLI batch script', 'build a python egg and wheel package by creating a docker jobspec for the python build script']
```

Usage

```
{'create_docker_jobspec': 'create a docker jobspec for running a shell command inside a gRPC artifact container', 'create_jobspec': 'create a jobspec for running a build command with configurable retries and cpu cost', 'build_CSharpPackage': 'build a C# nuget or unity package by creating a jobspec for the dotnet CLI batch script', 'build_PythonPackage': 'build a python egg and wheel package by creating a docker jobspec for the python build script', 'list_targets': 'list all supported package build targets including CSharp, Ruby, Python, and PHP packages'}
```

