# Agent Python Tools

- repo: google-deepmind/androidenv
- repo_uri: https://github.com/google-deepmind/android_env

## File: google-deepmind_androidenv/setup.py

Prompts

```
['run the generate_protos setuptools command to build Python gRPC bindings for all AndroidEnv proto files', 'install the android_env package with pip which auto-generates protobuf bindings during the build_py stage', 'run the build_ext command which triggers proto generation before compiling C extension modules', 'review the _GenerateProtoFiles class to understand how grpc_tools.protoc compiles each proto definition', 'refactor the _ANDROID_ENV_PROTOS tuple to add or remove proto files included in the binding generation']
```

Usage

```
{'generate_protobuf_bindings': 'run the generate_protos setuptools command to build Python gRPC bindings for all AndroidEnv proto files', 'build_package_with_protos': 'install the android_env package with pip which auto-generates protobuf bindings during the build_py stage', 'build_ext_with_protos': 'run the build_ext command which triggers proto generation before compiling C extension modules', 'review_PROTO_GENERATION': 'review the _GenerateProtoFiles class to understand how grpc_tools.protoc compiles each proto definition', 'refactor_PROTO_LIST': 'refactor the _ANDROID_ENV_PROTOS tuple to add or remove proto files included in the binding generation'}
```

