# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/bazel/test/python_test_repo/namespaced/upper/example/import_no_strip_test.py

Prompts

```
['test that NamespacedExample protobuf can be imported from the namespaced foo.bar package path', 'test that NamespacedServiceStub gRPC stub can be imported from the namespaced package path', 'run the unittest suite to verify namespaced protobuf and gRPC imports work correctly', 'review the ImportTest class and its test methods for namespaced import validation', 'refactor the ImportTest class to add additional namespaced import test cases', 'run the unittest to verify namespaced protobuf imports work correctly in gRPC Bazel builds', 'test that NamespacedExample can be imported from foo.bar.namespaced_example_pb2 and set its value field', 'review the ImportTest unittest class and its two test methods for gRPC namespaced import validation', 'summarize the import_strip_test module that validates protobuf and gRPC stub imports in a namespaced Bazel package', 'test importing NamespacedExample from namespaced.upper.example.namespaced_example_pb2 protobuf module', 'run the ImportTest unittest class to verify namespaced protobuf and gRPC imports', 'refactor the ImportTest class to add meaningful assertions beyond dummy checks']
```

Usage

```
{'test_import_namespaced_example': 'test that NamespacedExample protobuf can be imported from the namespaced foo.bar package path', 'test_grpc_stub_import': 'test that NamespacedServiceStub gRPC stub can be imported from the namespaced package path', 'run_import_test': 'run the unittest suite to verify namespaced protobuf and gRPC imports work correctly', 'review_importtest_class': 'review the ImportTest class and its test methods for namespaced import validation', 'refactor_importtest': 'refactor the ImportTest class to add additional namespaced import test cases'}
```

## File: facebookresearch_torchbeast/third_party/grpc/bazel/test/python_test_repo/namespaced/upper/example/import_strip_test.py

Prompts

```
['test that NamespacedExample protobuf can be imported from the namespaced foo.bar package path', 'test that NamespacedServiceStub gRPC stub can be imported from the namespaced package path', 'run the unittest suite to verify namespaced protobuf and gRPC imports work correctly', 'review the ImportTest class and its test methods for namespaced import validation', 'refactor the ImportTest class to add additional namespaced import test cases', 'run the unittest to verify namespaced protobuf imports work correctly in gRPC Bazel builds', 'test that NamespacedExample can be imported from foo.bar.namespaced_example_pb2 and set its value field', 'review the ImportTest unittest class and its two test methods for gRPC namespaced import validation', 'summarize the import_strip_test module that validates protobuf and gRPC stub imports in a namespaced Bazel package', 'test importing NamespacedExample from namespaced.upper.example.namespaced_example_pb2 protobuf module', 'run the ImportTest unittest class to verify namespaced protobuf and gRPC imports', 'refactor the ImportTest class to add meaningful assertions beyond dummy checks']
```

Usage

```
{'run_import_strip_test': 'run the unittest to verify namespaced protobuf imports work correctly in gRPC Bazel builds', 'test_namespaced_pb2_import': 'test that NamespacedExample can be imported from foo.bar.namespaced_example_pb2 and set its value field', 'test_grpc_stub_import': 'test that NamespacedServiceStub can be imported from foo.bar.namespaced_example_pb2_grpc without errors', 'review_ImportTest_class': 'review the ImportTest unittest class and its two test methods for gRPC namespaced import validation', 'summarize_import_strip_test': 'summarize the import_strip_test module that validates protobuf and gRPC stub imports in a namespaced Bazel package'}
```

## File: facebookresearch_torchbeast/third_party/grpc/bazel/test/python_test_repo/namespaced/upper/example/no_import_no_strip_test.py

Prompts

```
['test that NamespacedExample protobuf can be imported from the namespaced foo.bar package path', 'test that NamespacedServiceStub gRPC stub can be imported from the namespaced package path', 'run the unittest suite to verify namespaced protobuf and gRPC imports work correctly', 'review the ImportTest class and its test methods for namespaced import validation', 'refactor the ImportTest class to add additional namespaced import test cases', 'run the unittest to verify namespaced protobuf imports work correctly in gRPC Bazel builds', 'test that NamespacedExample can be imported from foo.bar.namespaced_example_pb2 and set its value field', 'review the ImportTest unittest class and its two test methods for gRPC namespaced import validation', 'summarize the import_strip_test module that validates protobuf and gRPC stub imports in a namespaced Bazel package', 'test importing NamespacedExample from namespaced.upper.example.namespaced_example_pb2 protobuf module', 'run the ImportTest unittest class to verify namespaced protobuf and gRPC imports', 'refactor the ImportTest class to add meaningful assertions beyond dummy checks']
```

Usage

```
{'test_import_namespaced_pb2': 'test importing NamespacedExample from namespaced.upper.example.namespaced_example_pb2 protobuf module', 'test_grpc_stub_import': 'test importing NamespacedServiceStub from namespaced.upper.example.namespaced_example_pb2_grpc module', 'run_importtest_tests': 'run the ImportTest unittest class to verify namespaced protobuf and gRPC imports', 'review_importtest_class': 'review the ImportTest class and its test methods for namespaced gRPC import validation', 'refactor_importtest_assertions': 'refactor the ImportTest class to add meaningful assertions beyond dummy checks'}
```

## File: facebookresearch_torchbeast/third_party/grpc/bazel/test/python_test_repo/namespaced/upper/example/no_import_strip_test.py

Prompts

```
['test that NamespacedExample protobuf can be imported from the namespaced foo.bar package path', 'test that NamespacedServiceStub gRPC stub can be imported from the namespaced package path', 'run the unittest suite to verify namespaced protobuf and gRPC imports work correctly', 'review the ImportTest class and its test methods for namespaced import validation', 'refactor the ImportTest class to add additional namespaced import test cases', 'run the unittest to verify namespaced protobuf imports work correctly in gRPC Bazel builds', 'test that NamespacedExample can be imported from foo.bar.namespaced_example_pb2 and set its value field', 'review the ImportTest unittest class and its two test methods for gRPC namespaced import validation', 'summarize the import_strip_test module that validates protobuf and gRPC stub imports in a namespaced Bazel package', 'test importing NamespacedExample from namespaced.upper.example.namespaced_example_pb2 protobuf module', 'run the ImportTest unittest class to verify namespaced protobuf and gRPC imports', 'refactor the ImportTest class to add meaningful assertions beyond dummy checks']
```

Usage

```
{'test_import_namespaced_example': 'test that namespaced_example_pb2 NamespacedExample can be imported and instantiated without errors', 'test_grpc_stub_import': 'test that namespaced_example_pb2_grpc NamespacedServiceStub can be imported without errors', 'run_import_test': 'run the ImportTest unittest suite to validate namespaced protobuf and gRPC stub imports', 'review_importtest_class': 'review the ImportTest class and its test methods for namespaced import validation', 'refactor_importtest': 'refactor the ImportTest class to add additional namespaced import assertions'}
```

