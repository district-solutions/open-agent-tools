# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/src/python/grpcio_channelz/channelz_commands.py

Prompts

```
['run the Preprocess setuptools command to copy channelz.proto and LICENSE files into the package directory', 'run the BuildPackageProtos setuptools command to generate *_pb2.py modules from proto files', 'review the Preprocess.run method that copies channelz.proto and LICENSE using shutil.copyfile', 'review the BuildPackageProtos.run method that delegates to grpc_tools.command.build_package_protos', 'refactor the Preprocess class to accept user_options for customizing proto and LICENSE source paths', 'run setup.py to build and install the grpcio-channelz Python package', 'run the preprocess setuptools command to prepare channelz protobuf files before packaging', 'run the build_package_protos setuptools command to compile protobuf definitions for the channelz package', 'install the grpcio-channelz package via pip using setup.py with protobuf and grpcio dependencies', 'review the _NoOpCommand class that provides a no-op fallback for setuptools commands when channelz_commands is unavailable']
```

Usage

```
{'run_Preprocess_copy_proto': 'run the Preprocess setuptools command to copy channelz.proto and LICENSE files into the package directory', 'run_BuildPackageProtos_generate_pb2': 'run the BuildPackageProtos setuptools command to generate *_pb2.py modules from proto files', 'review_Preprocess_run': 'review the Preprocess.run method that copies channelz.proto and LICENSE using shutil.copyfile', 'review_BuildPackageProtos_run': 'review the BuildPackageProtos.run method that delegates to grpc_tools.command.build_package_protos', 'refactor_Preprocess_add_options': 'refactor the Preprocess class to accept user_options for customizing proto and LICENSE source paths'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/src/python/grpcio_channelz/setup.py

Prompts

```
['run the Preprocess setuptools command to copy channelz.proto and LICENSE files into the package directory', 'run the BuildPackageProtos setuptools command to generate *_pb2.py modules from proto files', 'review the Preprocess.run method that copies channelz.proto and LICENSE using shutil.copyfile', 'review the BuildPackageProtos.run method that delegates to grpc_tools.command.build_package_protos', 'refactor the Preprocess class to accept user_options for customizing proto and LICENSE source paths', 'run setup.py to build and install the grpcio-channelz Python package', 'run the preprocess setuptools command to prepare channelz protobuf files before packaging', 'run the build_package_protos setuptools command to compile protobuf definitions for the channelz package', 'install the grpcio-channelz package via pip using setup.py with protobuf and grpcio dependencies', 'review the _NoOpCommand class that provides a no-op fallback for setuptools commands when channelz_commands is unavailable']
```

Usage

```
{'build_grpcio_channelz_package': 'run setup.py to build and install the grpcio-channelz Python package', 'run_preprocess_command': 'run the preprocess setuptools command to prepare channelz protobuf files before packaging', 'run_build_package_protos_command': 'run the build_package_protos setuptools command to compile protobuf definitions for the channelz package', 'install_grpcio_channelz': 'install the grpcio-channelz package via pip using setup.py with protobuf and grpcio dependencies', 'review_NoOpCommand_class': 'review the _NoOpCommand class that provides a no-op fallback for setuptools commands when channelz_commands is unavailable'}
```

