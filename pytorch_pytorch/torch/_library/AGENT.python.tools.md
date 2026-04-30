# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/_library/abstract_impl.py

Prompts

```
['register an abstract implementation for a PyTorch operator using AbstractImplHolder', 'build a new dynamic size symint for data-dependent output shapes in abstract implementations', 'review the AbstractImplCtx class that provides context for writing abstract implementations', 'build a meta kernel that wraps an abstract impl holder for the Meta dispatch key', 'test the set_ctx_getter context manager that sets the global context getter for abstract impls', 'create a SimpleLibraryRegistry instance to manage PyTorch simple library API registrations', 'find a SimpleOperatorEntry by fully qualified operator name in the singleton registry', 'build a SimpleOperatorEntry for a PyTorch operator overload with abstract impl holder', 'review the singleton SimpleLibraryRegistry used globally for simple torch.library registrations', 'test the SimpleOperatorEntry abstract_impl field holds an AbstractImplHolder for kernel registration', 'create a Kernel instance wrapping a callable with its source location for tracking', 'test the RegistrationHandle class that invokes a destroy callback when .destroy() is called', "build a call to get_source to extract the caller's file path and line number from the stack", "test parse_namespace to split a qualified name like 'aten::sin' into namespace and name parts", 'review is_functional_schema to check if an operator schema is non-mutating with at least one return']
```

Usage

```
{'register_abstract_impl': 'register an abstract implementation for a PyTorch operator using AbstractImplHolder', 'build_new_dynamic_size': 'build a new dynamic size symint for data-dependent output shapes in abstract implementations', 'review_AbstractImplCtx': 'review the AbstractImplCtx class that provides context for writing abstract implementations', 'build_construct_meta_kernel': 'build a meta kernel that wraps an abstract impl holder for the Meta dispatch key', 'test_set_ctx_getter': 'test the set_ctx_getter context manager that sets the global context getter for abstract impls'}
```

## File: pytorch_pytorch/torch/_library/simple_registry.py

Prompts

```
['register an abstract implementation for a PyTorch operator using AbstractImplHolder', 'build a new dynamic size symint for data-dependent output shapes in abstract implementations', 'review the AbstractImplCtx class that provides context for writing abstract implementations', 'build a meta kernel that wraps an abstract impl holder for the Meta dispatch key', 'test the set_ctx_getter context manager that sets the global context getter for abstract impls', 'create a SimpleLibraryRegistry instance to manage PyTorch simple library API registrations', 'find a SimpleOperatorEntry by fully qualified operator name in the singleton registry', 'build a SimpleOperatorEntry for a PyTorch operator overload with abstract impl holder', 'review the singleton SimpleLibraryRegistry used globally for simple torch.library registrations', 'test the SimpleOperatorEntry abstract_impl field holds an AbstractImplHolder for kernel registration', 'create a Kernel instance wrapping a callable with its source location for tracking', 'test the RegistrationHandle class that invokes a destroy callback when .destroy() is called', "build a call to get_source to extract the caller's file path and line number from the stack", "test parse_namespace to split a qualified name like 'aten::sin' into namespace and name parts", 'review is_functional_schema to check if an operator schema is non-mutating with at least one return']
```

Usage

```
{'create_SimpleLibraryRegistry': 'create a SimpleLibraryRegistry instance to manage PyTorch simple library API registrations', 'find_operator_entry': 'find a SimpleOperatorEntry by fully qualified operator name in the singleton registry', 'build_SimpleOperatorEntry': 'build a SimpleOperatorEntry for a PyTorch operator overload with abstract impl holder', 'review_singleton': 'review the singleton SimpleLibraryRegistry used globally for simple torch.library registrations', 'test_SimpleOperatorEntry_abstract_impl': 'test the SimpleOperatorEntry abstract_impl field holds an AbstractImplHolder for kernel registration'}
```

## File: pytorch_pytorch/torch/_library/utils.py

Prompts

```
['register an abstract implementation for a PyTorch operator using AbstractImplHolder', 'build a new dynamic size symint for data-dependent output shapes in abstract implementations', 'review the AbstractImplCtx class that provides context for writing abstract implementations', 'build a meta kernel that wraps an abstract impl holder for the Meta dispatch key', 'test the set_ctx_getter context manager that sets the global context getter for abstract impls', 'create a SimpleLibraryRegistry instance to manage PyTorch simple library API registrations', 'find a SimpleOperatorEntry by fully qualified operator name in the singleton registry', 'build a SimpleOperatorEntry for a PyTorch operator overload with abstract impl holder', 'review the singleton SimpleLibraryRegistry used globally for simple torch.library registrations', 'test the SimpleOperatorEntry abstract_impl field holds an AbstractImplHolder for kernel registration', 'create a Kernel instance wrapping a callable with its source location for tracking', 'test the RegistrationHandle class that invokes a destroy callback when .destroy() is called', "build a call to get_source to extract the caller's file path and line number from the stack", "test parse_namespace to split a qualified name like 'aten::sin' into namespace and name parts", 'review is_functional_schema to check if an operator schema is non-mutating with at least one return']
```

Usage

```
{'create_Kernel': 'create a Kernel instance wrapping a callable with its source location for tracking', 'test_RegistrationHandle': 'test the RegistrationHandle class that invokes a destroy callback when .destroy() is called', 'build_get_source': "build a call to get_source to extract the caller's file path and line number from the stack", 'test_parse_namespace': "test parse_namespace to split a qualified name like 'aten::sin' into namespace and name parts", 'review_is_functional_schema': 'review is_functional_schema to check if an operator schema is non-mutating with at least one return'}
```

