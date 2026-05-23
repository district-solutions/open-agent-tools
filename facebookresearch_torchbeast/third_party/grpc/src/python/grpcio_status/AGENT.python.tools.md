# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_status/setup.py

Prompts

```
['build the grpcio-status Python package using setuptools and pip install', 'review the _NoOpCommand class that provides a no-op setuptools command', 'review the INSTALL_REQUIRES tuple listing protobuf, grpcio, and googleapis-common-protos dependencies', 'review the COMMAND_CLASS dict that wires preprocess and build_package_protos setuptools commands', 'summarize the setuptools.setup call that configures the grpcio-status package metadata and dependencies', 'run the Preprocess setuptools command to copy status.proto and LICENSE files into the grpc_status package directory', 'build a custom setuptools command using Preprocess that copies the status.proto file during the GRPC Python package build', 'review the Preprocess run method to understand how it copies status.proto and LICENSE files during setup', 'refactor the Preprocess class to add custom user_options or modify the file copy logic for the grpcio_status package', 'summarize the Preprocess setuptools Command class that handles proto and LICENSE file copying for grpcio_status']
```

Usage

```
{'build_grpcio_status_package': 'build the grpcio-status Python package using setuptools and pip install', 'review_NoOpCommand_class': 'review the _NoOpCommand class that provides a no-op setuptools command', 'review_install_requires': 'review the INSTALL_REQUIRES tuple listing protobuf, grpcio, and googleapis-common-protos dependencies', 'review_command_class': 'review the COMMAND_CLASS dict that wires preprocess and build_package_protos setuptools commands', 'summarize_setup_call': 'summarize the setuptools.setup call that configures the grpcio-status package metadata and dependencies'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_status/status_commands.py

Prompts

```
['build the grpcio-status Python package using setuptools and pip install', 'review the _NoOpCommand class that provides a no-op setuptools command', 'review the INSTALL_REQUIRES tuple listing protobuf, grpcio, and googleapis-common-protos dependencies', 'review the COMMAND_CLASS dict that wires preprocess and build_package_protos setuptools commands', 'summarize the setuptools.setup call that configures the grpcio-status package metadata and dependencies', 'run the Preprocess setuptools command to copy status.proto and LICENSE files into the grpc_status package directory', 'build a custom setuptools command using Preprocess that copies the status.proto file during the GRPC Python package build', 'review the Preprocess run method to understand how it copies status.proto and LICENSE files during setup', 'refactor the Preprocess class to add custom user_options or modify the file copy logic for the grpcio_status package', 'summarize the Preprocess setuptools Command class that handles proto and LICENSE file copying for grpcio_status']
```

Usage

```
{'run_Preprocess': 'run the Preprocess setuptools command to copy status.proto and LICENSE files into the grpc_status package directory', 'build_Preprocess_command': 'build a custom setuptools command using Preprocess that copies the status.proto file during the GRPC Python package build', 'review_Preprocess_run': 'review the Preprocess run method to understand how it copies status.proto and LICENSE files during setup', 'refactor_Preprocess': 'refactor the Preprocess class to add custom user_options or modify the file copy logic for the grpcio_status package', 'summarize_Preprocess': 'summarize the Preprocess setuptools Command class that handles proto and LICENSE file copying for grpcio_status'}
```

