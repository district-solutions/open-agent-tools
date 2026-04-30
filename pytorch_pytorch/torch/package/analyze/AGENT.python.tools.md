# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/package/analyze/find_first_use_of_broken_modules.py

Prompts

```
['find the first dependency path for each broken module in a PackagingError exception', 'test the find_first_use_of_broken_modules function with a PackagingError containing broken modules', 'review the find_first_use_of_broken_modules function to verify it correctly maps broken modules to their first dependency path', 'refactor the find_first_use_of_broken_modules function to extract the broken module detection into a separate helper', 'summarize the find_first_use_of_broken_modules function and its role in debugging PyTorch package export errors', 'test the is_from_package function to check if an object was loaded from a package', 'refactor the is_from_package function to support additional type checks beyond ModuleType', 'review the is_from_package function and its dependency on is_mangled for correctness', 'summarize the is_from_package function behavior for module and non-module objects', 'create a usage example that demonstrates checking if a module or object belongs to a package', 'trace the modules used by a callable by executing it with multiple input tuples', 'test the trace_dependencies function with a simple callable and input tuples', 'refactor trace_dependencies to also track imports instead of only function calls', 'review trace_dependencies for handling nested calls and recursive function traces', 'summarize how trace_dependencies uses sys.setprofile to detect used modules']
```

Usage

```
{'find_first_use_of_broken_modules': 'find the first dependency path for each broken module in a PackagingError exception', 'test_find_first_use_of_broken_modules': 'test the find_first_use_of_broken_modules function with a PackagingError containing broken modules', 'review_find_first_use_of_broken_modules': 'review the find_first_use_of_broken_modules function to verify it correctly maps broken modules to their first dependency path', 'refactor_find_first_use_of_broken_modules': 'refactor the find_first_use_of_broken_modules function to extract the broken module detection into a separate helper', 'summarize_find_first_use_of_broken_modules': 'summarize the find_first_use_of_broken_modules function and its role in debugging PyTorch package export errors'}
```

## File: pytorch_pytorch/torch/package/analyze/is_from_package.py

Prompts

```
['find the first dependency path for each broken module in a PackagingError exception', 'test the find_first_use_of_broken_modules function with a PackagingError containing broken modules', 'review the find_first_use_of_broken_modules function to verify it correctly maps broken modules to their first dependency path', 'refactor the find_first_use_of_broken_modules function to extract the broken module detection into a separate helper', 'summarize the find_first_use_of_broken_modules function and its role in debugging PyTorch package export errors', 'test the is_from_package function to check if an object was loaded from a package', 'refactor the is_from_package function to support additional type checks beyond ModuleType', 'review the is_from_package function and its dependency on is_mangled for correctness', 'summarize the is_from_package function behavior for module and non-module objects', 'create a usage example that demonstrates checking if a module or object belongs to a package', 'trace the modules used by a callable by executing it with multiple input tuples', 'test the trace_dependencies function with a simple callable and input tuples', 'refactor trace_dependencies to also track imports instead of only function calls', 'review trace_dependencies for handling nested calls and recursive function traces', 'summarize how trace_dependencies uses sys.setprofile to detect used modules']
```

Usage

```
{'test_is_from_package': 'test the is_from_package function to check if an object was loaded from a package', 'refactor_is_from_package': 'refactor the is_from_package function to support additional type checks beyond ModuleType', 'review_is_from_package': 'review the is_from_package function and its dependency on is_mangled for correctness', 'summarize_is_from_package': 'summarize the is_from_package function behavior for module and non-module objects', 'create_is_from_package_usage': 'create a usage example that demonstrates checking if a module or object belongs to a package'}
```

## File: pytorch_pytorch/torch/package/analyze/trace_dependencies.py

Prompts

```
['find the first dependency path for each broken module in a PackagingError exception', 'test the find_first_use_of_broken_modules function with a PackagingError containing broken modules', 'review the find_first_use_of_broken_modules function to verify it correctly maps broken modules to their first dependency path', 'refactor the find_first_use_of_broken_modules function to extract the broken module detection into a separate helper', 'summarize the find_first_use_of_broken_modules function and its role in debugging PyTorch package export errors', 'test the is_from_package function to check if an object was loaded from a package', 'refactor the is_from_package function to support additional type checks beyond ModuleType', 'review the is_from_package function and its dependency on is_mangled for correctness', 'summarize the is_from_package function behavior for module and non-module objects', 'create a usage example that demonstrates checking if a module or object belongs to a package', 'trace the modules used by a callable by executing it with multiple input tuples', 'test the trace_dependencies function with a simple callable and input tuples', 'refactor trace_dependencies to also track imports instead of only function calls', 'review trace_dependencies for handling nested calls and recursive function traces', 'summarize how trace_dependencies uses sys.setprofile to detect used modules']
```

Usage

```
{'trace_dependencies_trace_modules': 'trace the modules used by a callable by executing it with multiple input tuples', 'test_trace_dependencies': 'test the trace_dependencies function with a simple callable and input tuples', 'refactor_trace_dependencies': 'refactor trace_dependencies to also track imports instead of only function calls', 'review_trace_dependencies': 'review trace_dependencies for handling nested calls and recursive function traces', 'summarize_trace_dependencies': 'summarize how trace_dependencies uses sys.setprofile to detect used modules'}
```

