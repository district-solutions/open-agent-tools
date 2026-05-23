# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/python/mox.py

Prompts

```
['create a mock object from a class using Mox().CreateMock(MyClass) for unit testing', 'create a mock that accepts any method call using Mox().CreateMockAnything() without enforcing an interface', 'replace a module attribute with a mock using Mox().StubOutWithMock(obj, attr_name) for testing', 'set expected method calls and return values using mock.Method().AndReturn(value) in record mode', 'use comparators like IsA, StrContains, Regex, or IgnoreArg to match mock method parameters flexibly', 'build the protobuf python package using setup.py with setuptools and find_packages', 'generate Python _pb2.py stubs from .proto files using the protoc compiler', 'get the protobuf version string from google/protobuf/__init__.py without importing it', 'clean generated _pb2.py, .pyc, .so, and .o files from the code tree', 'build the protobuf C++ implementation extension with --cpp_implementation flag', 'test a module function by stubbing it with StubOutForTesting.Set to return a fixed value', 'test a class method by stubbing it with SmartSet to preserve inheritance while replacing behavior', 'test code that calls os.path.exists by stubbing it and restoring with UnsetAll after assertions', 'test a staticmethod by stubbing it with Set which preserves the staticmethod wrapper automatically', 'test inheritance by stubbing an attribute with SmartSet across multiple classes in the MRO']
```

Usage

```
{'create_mock_object': 'create a mock object from a class using Mox().CreateMock(MyClass) for unit testing', 'create_mock_anything': 'create a mock that accepts any method call using Mox().CreateMockAnything() without enforcing an interface', 'stub_out_with_mock': 'replace a module attribute with a mock using Mox().StubOutWithMock(obj, attr_name) for testing', 'setup_mock_expectations': 'set expected method calls and return values using mock.Method().AndReturn(value) in record mode', 'use_comparator_matchers': 'use comparators like IsA, StrContains, Regex, or IgnoreArg to match mock method parameters flexibly'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/python/setup.py

Prompts

```
['create a mock object from a class using Mox().CreateMock(MyClass) for unit testing', 'create a mock that accepts any method call using Mox().CreateMockAnything() without enforcing an interface', 'replace a module attribute with a mock using Mox().StubOutWithMock(obj, attr_name) for testing', 'set expected method calls and return values using mock.Method().AndReturn(value) in record mode', 'use comparators like IsA, StrContains, Regex, or IgnoreArg to match mock method parameters flexibly', 'build the protobuf python package using setup.py with setuptools and find_packages', 'generate Python _pb2.py stubs from .proto files using the protoc compiler', 'get the protobuf version string from google/protobuf/__init__.py without importing it', 'clean generated _pb2.py, .pyc, .so, and .o files from the code tree', 'build the protobuf C++ implementation extension with --cpp_implementation flag', 'test a module function by stubbing it with StubOutForTesting.Set to return a fixed value', 'test a class method by stubbing it with SmartSet to preserve inheritance while replacing behavior', 'test code that calls os.path.exists by stubbing it and restoring with UnsetAll after assertions', 'test a staticmethod by stubbing it with Set which preserves the staticmethod wrapper automatically', 'test inheritance by stubbing an attribute with SmartSet across multiple classes in the MRO']
```

Usage

```
{'build_protobuf_python_package': 'build the protobuf python package using setup.py with setuptools and find_packages', 'generate_proto_files': 'generate Python _pb2.py stubs from .proto files using the protoc compiler', 'get_version': 'get the protobuf version string from google/protobuf/__init__.py without importing it', 'clean_generated_files': 'clean generated _pb2.py, .pyc, .so, and .o files from the code tree', 'build_cpp_extension': 'build the protobuf C++ implementation extension with --cpp_implementation flag'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/python/stubout.py

Prompts

```
['create a mock object from a class using Mox().CreateMock(MyClass) for unit testing', 'create a mock that accepts any method call using Mox().CreateMockAnything() without enforcing an interface', 'replace a module attribute with a mock using Mox().StubOutWithMock(obj, attr_name) for testing', 'set expected method calls and return values using mock.Method().AndReturn(value) in record mode', 'use comparators like IsA, StrContains, Regex, or IgnoreArg to match mock method parameters flexibly', 'build the protobuf python package using setup.py with setuptools and find_packages', 'generate Python _pb2.py stubs from .proto files using the protoc compiler', 'get the protobuf version string from google/protobuf/__init__.py without importing it', 'clean generated _pb2.py, .pyc, .so, and .o files from the code tree', 'build the protobuf C++ implementation extension with --cpp_implementation flag', 'test a module function by stubbing it with StubOutForTesting.Set to return a fixed value', 'test a class method by stubbing it with SmartSet to preserve inheritance while replacing behavior', 'test code that calls os.path.exists by stubbing it and restoring with UnsetAll after assertions', 'test a staticmethod by stubbing it with Set which preserves the staticmethod wrapper automatically', 'test inheritance by stubbing an attribute with SmartSet across multiple classes in the MRO']
```

Usage

```
{'test_stub_out_module_function': 'test a module function by stubbing it with StubOutForTesting.Set to return a fixed value', 'test_stub_out_class_method': 'test a class method by stubbing it with SmartSet to preserve inheritance while replacing behavior', 'test_stub_out_and_restore': 'test code that calls os.path.exists by stubbing it and restoring with UnsetAll after assertions', 'test_stub_out_staticmethod': 'test a staticmethod by stubbing it with Set which preserves the staticmethod wrapper automatically', 'test_smart_stub_multiple_classes': 'test inheritance by stubbing an attribute with SmartSet across multiple classes in the MRO'}
```

