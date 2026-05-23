# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_reflection/reflection_commands.py

Prompts

```
['build grpc protobuf modules from proto files using the BuildPackageProtos setuptools command', 'copy reflection.proto and LICENSE files to the grpc_reflection package directory using Preprocess', 'run the Preprocess setuptools command to copy proto modules and LICENSE before building', 'review the Preprocess class that copies reflection.proto and LICENSE during the setup process', 'review the BuildPackageProtos class that generates pb2.py modules from proto files', 'build the grpcio-reflection Python package using setuptools and pip install', 'run the build_package_protos setuptools command to compile protobuf definitions', 'review the _NoOpCommand class that provides no-op fallback for missing build commands', 'review the setuptools.setup call that configures the grpcio-reflection package metadata and dependencies']
```

Usage

```
{'build_package_protos': 'build grpc protobuf modules from proto files using the BuildPackageProtos setuptools command', 'preprocess_copy_protos': 'copy reflection.proto and LICENSE files to the grpc_reflection package directory using Preprocess', 'run_preprocess_command': 'run the Preprocess setuptools command to copy proto modules and LICENSE before building', 'review_preprocess_class': 'review the Preprocess class that copies reflection.proto and LICENSE during the setup process', 'review_buildpackageprotos_class': 'review the BuildPackageProtos class that generates pb2.py modules from proto files'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_reflection/setup.py

Prompts

```
['build grpc protobuf modules from proto files using the BuildPackageProtos setuptools command', 'copy reflection.proto and LICENSE files to the grpc_reflection package directory using Preprocess', 'run the Preprocess setuptools command to copy proto modules and LICENSE before building', 'review the Preprocess class that copies reflection.proto and LICENSE during the setup process', 'review the BuildPackageProtos class that generates pb2.py modules from proto files', 'build the grpcio-reflection Python package using setuptools and pip install', 'run the build_package_protos setuptools command to compile protobuf definitions', 'review the _NoOpCommand class that provides no-op fallback for missing build commands', 'review the setuptools.setup call that configures the grpcio-reflection package metadata and dependencies']
```

Usage

```
{'build_grpcio_reflection_package': 'build the grpcio-reflection Python package using setuptools and pip install', 'run_preprocess_command': 'run the preprocess setuptools command to prepare proto files before packaging', 'run_build_package_protos_command': 'run the build_package_protos setuptools command to compile protobuf definitions', 'review_NoOpCommand_class': 'review the _NoOpCommand class that provides no-op fallback for missing build commands', 'review_setuptools_setup_call': 'review the setuptools.setup call that configures the grpcio-reflection package metadata and dependencies'}
```

