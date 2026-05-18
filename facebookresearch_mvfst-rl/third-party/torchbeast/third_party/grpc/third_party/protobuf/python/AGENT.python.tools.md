# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/protobuf/python/mox.py

Prompts

```
['create a mock object from a class using Mox().CreateMock(MyClass) for unit testing', 'create a mock that accepts any method call using Mox().CreateMockAnything() without interface enforcement', "stub out a module attribute with a mock using Mox().StubOutWithMock(module, 'attr_name')", 'set up mock method return values with mock.Method().AndReturn(value) or mock.Method().AndRaise(Exception)', 'use comparators like IsA, StrContains, Regex, or IgnoreArg to match mock method parameters flexibly', 'test code by subclassing MoxTestBase for automatic mock verification and stub cleanup after each test', 'generate a _pb2.py Python module from a .proto file using the Protocol Compiler', 'build the protobuf Python package by generating proto files and running setuptools build', 'clean the working directory by removing all generated _pb2.py, .pyc, .so, and .o files', 'run the Python conformance test suite against the protobuf C++ implementation', 'get the protobuf version string from the google/protobuf/__init__.py file', 'create a StubOutForTesting instance and use Set to replace os.path.exists with a lambda that returns true', 'use SmartSet to replace a class method while preserving proper inheritance across the MRO', 'call UnsetAll to reverse all Set calls and restore original function definitions', 'call SmartUnsetAll to reverse all SmartSet calls and restore original class and module attributes', 'use Set to replace a staticmethod while preserving its staticmethod wrapper for later restoration']
```

Usage

```
{'create_mock_object': 'create a mock object from a class using Mox().CreateMock(MyClass) for unit testing', 'create_mock_anything': 'create a mock that accepts any method call using Mox().CreateMockAnything() without interface enforcement', 'stub_out_with_mock': "stub out a module attribute with a mock using Mox().StubOutWithMock(module, 'attr_name')", 'setup_mock_expectations': 'set up mock method return values with mock.Method().AndReturn(value) or mock.Method().AndRaise(Exception)', 'use_comparator_matchers': 'use comparators like IsA, StrContains, Regex, or IgnoreArg to match mock method parameters flexibly', 'test_with_moxtestbase': 'test code by subclassing MoxTestBase for automatic mock verification and stub cleanup after each test'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/protobuf/python/setup.py

Prompts

```
['create a mock object from a class using Mox().CreateMock(MyClass) for unit testing', 'create a mock that accepts any method call using Mox().CreateMockAnything() without interface enforcement', "stub out a module attribute with a mock using Mox().StubOutWithMock(module, 'attr_name')", 'set up mock method return values with mock.Method().AndReturn(value) or mock.Method().AndRaise(Exception)', 'use comparators like IsA, StrContains, Regex, or IgnoreArg to match mock method parameters flexibly', 'test code by subclassing MoxTestBase for automatic mock verification and stub cleanup after each test', 'generate a _pb2.py Python module from a .proto file using the Protocol Compiler', 'build the protobuf Python package by generating proto files and running setuptools build', 'clean the working directory by removing all generated _pb2.py, .pyc, .so, and .o files', 'run the Python conformance test suite against the protobuf C++ implementation', 'get the protobuf version string from the google/protobuf/__init__.py file', 'create a StubOutForTesting instance and use Set to replace os.path.exists with a lambda that returns true', 'use SmartSet to replace a class method while preserving proper inheritance across the MRO', 'call UnsetAll to reverse all Set calls and restore original function definitions', 'call SmartUnsetAll to reverse all SmartSet calls and restore original class and module attributes', 'use Set to replace a staticmethod while preserving its staticmethod wrapper for later restoration']
```

Usage

```
{'generate_proto_from_file': 'generate a _pb2.py Python module from a .proto file using the Protocol Compiler', 'build_protobuf_python_package': 'build the protobuf Python package by generating proto files and running setuptools build', 'clean_generated_files': 'clean the working directory by removing all generated _pb2.py, .pyc, .so, and .o files', 'run_conformance_tests': 'run the Python conformance test suite against the protobuf C++ implementation', 'get_protobuf_version': 'get the protobuf version string from the google/protobuf/__init__.py file'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/protobuf/python/stubout.py

Prompts

```
['create a mock object from a class using Mox().CreateMock(MyClass) for unit testing', 'create a mock that accepts any method call using Mox().CreateMockAnything() without interface enforcement', "stub out a module attribute with a mock using Mox().StubOutWithMock(module, 'attr_name')", 'set up mock method return values with mock.Method().AndReturn(value) or mock.Method().AndRaise(Exception)', 'use comparators like IsA, StrContains, Regex, or IgnoreArg to match mock method parameters flexibly', 'test code by subclassing MoxTestBase for automatic mock verification and stub cleanup after each test', 'generate a _pb2.py Python module from a .proto file using the Protocol Compiler', 'build the protobuf Python package by generating proto files and running setuptools build', 'clean the working directory by removing all generated _pb2.py, .pyc, .so, and .o files', 'run the Python conformance test suite against the protobuf C++ implementation', 'get the protobuf version string from the google/protobuf/__init__.py file', 'create a StubOutForTesting instance and use Set to replace os.path.exists with a lambda that returns true', 'use SmartSet to replace a class method while preserving proper inheritance across the MRO', 'call UnsetAll to reverse all Set calls and restore original function definitions', 'call SmartUnsetAll to reverse all SmartSet calls and restore original class and module attributes', 'use Set to replace a staticmethod while preserving its staticmethod wrapper for later restoration']
```

Usage

```
{'stub_out_module_function': 'create a StubOutForTesting instance and use Set to replace os.path.exists with a lambda that returns true', 'stub_out_class_method': 'use SmartSet to replace a class method while preserving proper inheritance across the MRO', 'restore_all_stubs': 'call UnsetAll to reverse all Set calls and restore original function definitions', 'restore_smart_stubs': 'call SmartUnsetAll to reverse all SmartSet calls and restore original class and module attributes', 'stub_staticmethod': 'use Set to replace a staticmethod while preserving its staticmethod wrapper for later restoration'}
```

