# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_testing/setup.py

Prompts

```
['run the setuptools setup for the grpcio-testing package to install gRPC Python testing utilities', 'review the _NoOpCommand class that provides a no-op setuptools command for fallback when testing_commands is unavailable', 'build the grpcio-testing package using setuptools with protobuf and grpcio as dependencies', 'review the COMMAND_CLASS dictionary that maps the preprocess command to either Preprocess or _NoOpCommand', 'review the INSTALL_REQUIRES tuple that specifies protobuf and grpcio version constraints for the package', 'run the Preprocess setuptools command to copy the LICENSE file into the grpcio_testing directory', 'build a custom setuptools command by subclassing Preprocess to add extra setup steps', 'review the Preprocess run method to understand how it copies the LICENSE file during setup', 'refactor the Preprocess class to support copying additional files beyond the LICENSE', 'test the Preprocess command to verify it correctly copies the LICENSE file when it exists']
```

Usage

```
{'run_setup_grpcio_testing': 'run the setuptools setup for the grpcio-testing package to install gRPC Python testing utilities', 'review_NoOpCommand': 'review the _NoOpCommand class that provides a no-op setuptools command for fallback when testing_commands is unavailable', 'build_grpcio_testing_package': 'build the grpcio-testing package using setuptools with protobuf and grpcio as dependencies', 'review_COMMAND_CLASS': 'review the COMMAND_CLASS dictionary that maps the preprocess command to either Preprocess or _NoOpCommand', 'review_INSTALL_REQUIRES': 'review the INSTALL_REQUIRES tuple that specifies protobuf and grpcio version constraints for the package'}
```

## File: facebookresearch_torchbeast/third_party/grpc/src/python/grpcio_testing/testing_commands.py

Prompts

```
['run the setuptools setup for the grpcio-testing package to install gRPC Python testing utilities', 'review the _NoOpCommand class that provides a no-op setuptools command for fallback when testing_commands is unavailable', 'build the grpcio-testing package using setuptools with protobuf and grpcio as dependencies', 'review the COMMAND_CLASS dictionary that maps the preprocess command to either Preprocess or _NoOpCommand', 'review the INSTALL_REQUIRES tuple that specifies protobuf and grpcio version constraints for the package', 'run the Preprocess setuptools command to copy the LICENSE file into the grpcio_testing directory', 'build a custom setuptools command by subclassing Preprocess to add extra setup steps', 'review the Preprocess run method to understand how it copies the LICENSE file during setup', 'refactor the Preprocess class to support copying additional files beyond the LICENSE', 'test the Preprocess command to verify it correctly copies the LICENSE file when it exists']
```

Usage

```
{'run_Preprocess': 'run the Preprocess setuptools command to copy the LICENSE file into the grpcio_testing directory', 'build_Preprocess_command': 'build a custom setuptools command by subclassing Preprocess to add extra setup steps', 'review_Preprocess_run': 'review the Preprocess run method to understand how it copies the LICENSE file during setup', 'refactor_Preprocess': 'refactor the Preprocess class to support copying additional files beyond the LICENSE', 'test_Preprocess': 'test the Preprocess command to verify it correctly copies the LICENSE file when it exists'}
```

