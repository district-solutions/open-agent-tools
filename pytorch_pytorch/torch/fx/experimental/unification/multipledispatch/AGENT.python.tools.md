# Agent Python Tools

- repo: pytorch/pytorch
- repo_uri: https://github.com/pytorch/pytorch.git

## File: pytorch_pytorch/torch/fx/experimental/unification/multipledispatch/conflict.py

Prompts

```
['test the supercedes function to check if signature A is strictly more specific than signature B', 'test the consistent function to determine if an argument list can satisfy both signatures A and B', 'test the ambiguous function to find signature pairs where neither is strictly more specific than the other', 'test the ambiguities function to find all ambiguous signature pairs in a list of signatures', 'test the ordering function to compute a topological sort of signatures for dispatch resolution', 'create a function that dispatches on input argument types using the dispatch decorator', 'test the dispatch decorator to route function calls based on argument types', 'create a class with methods dispatched on argument types using the dispatch decorator', 'test dispatch with an isolated namespace to avoid global namespace collisions', 'review dispatch behavior when ambiguous type signatures are registered', 'create a Dispatcher with multiple type-based implementations using add() and dispatch()', 'test Dispatcher.__call__ to resolve the correct implementation based on argument types', 'review MethodDispatcher class for dispatching methods on instance objects with type signatures', 'summarize variadic_signature_matches for checking if input types match a variadic signature', 'build ambiguity warning text using warning_text() for dispatched functions with conflicting signatures', 'test if a lambda function raises a specified exception', 'expand a list containing tuples and scalars into all cartesian product combinations', 'run a topological sort on a dependency graph and return an ordered list of nodes', 'group a sequence of items by a key function returning an ordered dictionary', 'get the string name of a type or a tuple of type names', 'create a variadic signature type using Variadic[int] to match any number of int arguments', 'create a variadic signature type using Variadic[(int, str)] to match any number of int or str arguments', 'test whether a type is variadic using the isvariadic function', 'test subclass membership against a variadic signature type using issubclass', 'test equality between two variadic signature types using the __eq__ method']
```

Usage

```
{'test_supercedes': 'test the supercedes function to check if signature A is strictly more specific than signature B', 'test_consistent': 'test the consistent function to determine if an argument list can satisfy both signatures A and B', 'test_ambiguous': 'test the ambiguous function to find signature pairs where neither is strictly more specific than the other', 'test_ambiguities': 'test the ambiguities function to find all ambiguous signature pairs in a list of signatures', 'test_ordering': 'test the ordering function to compute a topological sort of signatures for dispatch resolution'}
```

## File: pytorch_pytorch/torch/fx/experimental/unification/multipledispatch/core.py

Prompts

```
['test the supercedes function to check if signature A is strictly more specific than signature B', 'test the consistent function to determine if an argument list can satisfy both signatures A and B', 'test the ambiguous function to find signature pairs where neither is strictly more specific than the other', 'test the ambiguities function to find all ambiguous signature pairs in a list of signatures', 'test the ordering function to compute a topological sort of signatures for dispatch resolution', 'create a function that dispatches on input argument types using the dispatch decorator', 'test the dispatch decorator to route function calls based on argument types', 'create a class with methods dispatched on argument types using the dispatch decorator', 'test dispatch with an isolated namespace to avoid global namespace collisions', 'review dispatch behavior when ambiguous type signatures are registered', 'create a Dispatcher with multiple type-based implementations using add() and dispatch()', 'test Dispatcher.__call__ to resolve the correct implementation based on argument types', 'review MethodDispatcher class for dispatching methods on instance objects with type signatures', 'summarize variadic_signature_matches for checking if input types match a variadic signature', 'build ambiguity warning text using warning_text() for dispatched functions with conflicting signatures', 'test if a lambda function raises a specified exception', 'expand a list containing tuples and scalars into all cartesian product combinations', 'run a topological sort on a dependency graph and return an ordered list of nodes', 'group a sequence of items by a key function returning an ordered dictionary', 'get the string name of a type or a tuple of type names', 'create a variadic signature type using Variadic[int] to match any number of int arguments', 'create a variadic signature type using Variadic[(int, str)] to match any number of int or str arguments', 'test whether a type is variadic using the isvariadic function', 'test subclass membership against a variadic signature type using issubclass', 'test equality between two variadic signature types using the __eq__ method']
```

Usage

```
{'create_function_dispatch': 'create a function that dispatches on input argument types using the dispatch decorator', 'test_DISPATCH_DECORATOR': 'test the dispatch decorator to route function calls based on argument types', 'create_function_dispatch_method': 'create a class with methods dispatched on argument types using the dispatch decorator', 'test_dispatch_namespace': 'test dispatch with an isolated namespace to avoid global namespace collisions', 'review_dispatch_ambiguity': 'review dispatch behavior when ambiguous type signatures are registered'}
```

## File: pytorch_pytorch/torch/fx/experimental/unification/multipledispatch/dispatcher.py

Prompts

```
['test the supercedes function to check if signature A is strictly more specific than signature B', 'test the consistent function to determine if an argument list can satisfy both signatures A and B', 'test the ambiguous function to find signature pairs where neither is strictly more specific than the other', 'test the ambiguities function to find all ambiguous signature pairs in a list of signatures', 'test the ordering function to compute a topological sort of signatures for dispatch resolution', 'create a function that dispatches on input argument types using the dispatch decorator', 'test the dispatch decorator to route function calls based on argument types', 'create a class with methods dispatched on argument types using the dispatch decorator', 'test dispatch with an isolated namespace to avoid global namespace collisions', 'review dispatch behavior when ambiguous type signatures are registered', 'create a Dispatcher with multiple type-based implementations using add() and dispatch()', 'test Dispatcher.__call__ to resolve the correct implementation based on argument types', 'review MethodDispatcher class for dispatching methods on instance objects with type signatures', 'summarize variadic_signature_matches for checking if input types match a variadic signature', 'build ambiguity warning text using warning_text() for dispatched functions with conflicting signatures', 'test if a lambda function raises a specified exception', 'expand a list containing tuples and scalars into all cartesian product combinations', 'run a topological sort on a dependency graph and return an ordered list of nodes', 'group a sequence of items by a key function returning an ordered dictionary', 'get the string name of a type or a tuple of type names', 'create a variadic signature type using Variadic[int] to match any number of int arguments', 'create a variadic signature type using Variadic[(int, str)] to match any number of int or str arguments', 'test whether a type is variadic using the isvariadic function', 'test subclass membership against a variadic signature type using issubclass', 'test equality between two variadic signature types using the __eq__ method']
```

Usage

```
{'create_dispatcher_add_implementations': 'create a Dispatcher with multiple type-based implementations using add() and dispatch()', 'test_dispatcher_call_resolution': 'test Dispatcher.__call__ to resolve the correct implementation based on argument types', 'review_methoddispatcher_class': 'review MethodDispatcher class for dispatching methods on instance objects with type signatures', 'summarize_variadic_signature_matches': 'summarize variadic_signature_matches for checking if input types match a variadic signature', 'build_ambiguity_warning_text': 'build ambiguity warning text using warning_text() for dispatched functions with conflicting signatures'}
```

## File: pytorch_pytorch/torch/fx/experimental/unification/multipledispatch/utils.py

Prompts

```
['test the supercedes function to check if signature A is strictly more specific than signature B', 'test the consistent function to determine if an argument list can satisfy both signatures A and B', 'test the ambiguous function to find signature pairs where neither is strictly more specific than the other', 'test the ambiguities function to find all ambiguous signature pairs in a list of signatures', 'test the ordering function to compute a topological sort of signatures for dispatch resolution', 'create a function that dispatches on input argument types using the dispatch decorator', 'test the dispatch decorator to route function calls based on argument types', 'create a class with methods dispatched on argument types using the dispatch decorator', 'test dispatch with an isolated namespace to avoid global namespace collisions', 'review dispatch behavior when ambiguous type signatures are registered', 'create a Dispatcher with multiple type-based implementations using add() and dispatch()', 'test Dispatcher.__call__ to resolve the correct implementation based on argument types', 'review MethodDispatcher class for dispatching methods on instance objects with type signatures', 'summarize variadic_signature_matches for checking if input types match a variadic signature', 'build ambiguity warning text using warning_text() for dispatched functions with conflicting signatures', 'test if a lambda function raises a specified exception', 'expand a list containing tuples and scalars into all cartesian product combinations', 'run a topological sort on a dependency graph and return an ordered list of nodes', 'group a sequence of items by a key function returning an ordered dictionary', 'get the string name of a type or a tuple of type names', 'create a variadic signature type using Variadic[int] to match any number of int arguments', 'create a variadic signature type using Variadic[(int, str)] to match any number of int or str arguments', 'test whether a type is variadic using the isvariadic function', 'test subclass membership against a variadic signature type using issubclass', 'test equality between two variadic signature types using the __eq__ method']
```

Usage

```
{'test_raises': 'test if a lambda function raises a specified exception', 'expand_tuples': 'expand a list containing tuples and scalars into all cartesian product combinations', 'run_toposort': 'run a topological sort on a dependency graph and return an ordered list of nodes', 'groupby': 'group a sequence of items by a key function returning an ordered dictionary', 'typename': 'get the string name of a type or a tuple of type names'}
```

## File: pytorch_pytorch/torch/fx/experimental/unification/multipledispatch/variadic.py

Prompts

```
['test the supercedes function to check if signature A is strictly more specific than signature B', 'test the consistent function to determine if an argument list can satisfy both signatures A and B', 'test the ambiguous function to find signature pairs where neither is strictly more specific than the other', 'test the ambiguities function to find all ambiguous signature pairs in a list of signatures', 'test the ordering function to compute a topological sort of signatures for dispatch resolution', 'create a function that dispatches on input argument types using the dispatch decorator', 'test the dispatch decorator to route function calls based on argument types', 'create a class with methods dispatched on argument types using the dispatch decorator', 'test dispatch with an isolated namespace to avoid global namespace collisions', 'review dispatch behavior when ambiguous type signatures are registered', 'create a Dispatcher with multiple type-based implementations using add() and dispatch()', 'test Dispatcher.__call__ to resolve the correct implementation based on argument types', 'review MethodDispatcher class for dispatching methods on instance objects with type signatures', 'summarize variadic_signature_matches for checking if input types match a variadic signature', 'build ambiguity warning text using warning_text() for dispatched functions with conflicting signatures', 'test if a lambda function raises a specified exception', 'expand a list containing tuples and scalars into all cartesian product combinations', 'run a topological sort on a dependency graph and return an ordered list of nodes', 'group a sequence of items by a key function returning an ordered dictionary', 'get the string name of a type or a tuple of type names', 'create a variadic signature type using Variadic[int] to match any number of int arguments', 'create a variadic signature type using Variadic[(int, str)] to match any number of int or str arguments', 'test whether a type is variadic using the isvariadic function', 'test subclass membership against a variadic signature type using issubclass', 'test equality between two variadic signature types using the __eq__ method']
```

Usage

```
{'create_Variadic_signature': 'create a variadic signature type using Variadic[int] to match any number of int arguments', 'create_Variadic_tuple_signature': 'create a variadic signature type using Variadic[(int, str)] to match any number of int or str arguments', 'test_isvariadic': 'test whether a type is variadic using the isvariadic function', 'test_issubclass_variadic': 'test subclass membership against a variadic signature type using issubclass', 'test_Variadic_equality': 'test equality between two variadic signature types using the __eq__ method'}
```

