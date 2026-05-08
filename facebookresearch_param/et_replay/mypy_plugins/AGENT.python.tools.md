# Agent Python Tools

- repo: facebookresearch/param
- repo_uri: https://github.com/facebookresearch/param

## File: facebookresearch_param/et_replay/mypy_plugins/check_mypy_version.py

Prompts

```
['call get_correct_mypy_version to extract the pinned mypy version from the CI requirements file', 'run the mypy plugin entry point to validate the current mypy version matches the pinned version', 'review the plugin function that compares the runtime mypy version against the correct version from requirements', 'refactor get_correct_mypy_version to parse the mypy version from a different requirements file path', 'summarize the mypy version checking logic that prints an error to stderr when versions mismatch', 'build a mypy plugin that adds SymPy assumption attributes to Basic subclasses for static type checking', 'create a mypy base class hook that registers add_assumptions for sympy.core.basic.Basic', 'create a mypy attribute hook that types free_symbols as a set of sympy.Symbol', 'review the add_assumptions function that injects is_* bool attributes onto SymPy Basic classes', 'test the plugin entry point function that returns the SympyPlugin class for mypy']
```

Usage

```
{'get_correct_mypy_version': 'call get_correct_mypy_version to extract the pinned mypy version from the CI requirements file', 'plugin_version_check': 'run the mypy plugin entry point to validate the current mypy version matches the pinned version', 'review_plugin_entry_point': 'review the plugin function that compares the runtime mypy version against the correct version from requirements', 'refactor_get_correct_mypy_version': 'refactor get_correct_mypy_version to parse the mypy version from a different requirements file path', 'summarize_mypy_version_check': 'summarize the mypy version checking logic that prints an error to stderr when versions mismatch'}
```

## File: facebookresearch_param/et_replay/mypy_plugins/sympy_mypy_plugin.py

Prompts

```
['call get_correct_mypy_version to extract the pinned mypy version from the CI requirements file', 'run the mypy plugin entry point to validate the current mypy version matches the pinned version', 'review the plugin function that compares the runtime mypy version against the correct version from requirements', 'refactor get_correct_mypy_version to parse the mypy version from a different requirements file path', 'summarize the mypy version checking logic that prints an error to stderr when versions mismatch', 'build a mypy plugin that adds SymPy assumption attributes to Basic subclasses for static type checking', 'create a mypy base class hook that registers add_assumptions for sympy.core.basic.Basic', 'create a mypy attribute hook that types free_symbols as a set of sympy.Symbol', 'review the add_assumptions function that injects is_* bool attributes onto SymPy Basic classes', 'test the plugin entry point function that returns the SympyPlugin class for mypy']
```

Usage

```
{'build_sympy_mypy_plugin': 'build a mypy plugin that adds SymPy assumption attributes to Basic subclasses for static type checking', 'create_base_class_hook': 'create a mypy base class hook that registers add_assumptions for sympy.core.basic.Basic', 'create_attribute_hook': 'create a mypy attribute hook that types free_symbols as a set of sympy.Symbol', 'review_add_assumptions': 'review the add_assumptions function that injects is_* bool attributes onto SymPy Basic classes', 'test_plugin_entry_point': 'test the plugin entry point function that returns the SympyPlugin class for mypy'}
```

