# Agent Python Tools

- repo: facebookresearch/spdl
- repo_uri: https://github.com/facebookresearch/spdl

## File: facebookresearch_spdl/src/spdl/_internal/import_utils.py

Prompts

```
['use lazy_import to defer importing a heavy module until one of its attributes is first accessed', 'create a _LazilyImportedModule wrapper that delays import of a module until an attribute lookup triggers it', 'test lazy_import by accessing the __version__ attribute of a lazily imported module to confirm deferred loading', 'review the _LazilyImportedModule class __getattr__ method to understand how it triggers one-time import on first attribute access', 'refactor the _LazilyImportedModule _import_once method to customize how module attributes are cached after initial import']
```

Usage

```
{'use_lazy_import_defer_module': 'use lazy_import to defer importing a heavy module until one of its attributes is first accessed', 'create_lazy_module_wrapper': 'create a _LazilyImportedModule wrapper that delays import of a module until an attribute lookup triggers it', 'test_lazy_import_version_access': 'test lazy_import by accessing the __version__ attribute of a lazily imported module to confirm deferred loading', 'review_LazilyImportedModule_getattr': 'review the _LazilyImportedModule class __getattr__ method to understand how it triggers one-time import on first attribute access', 'refactor_LazilyImportedModule_import_once': 'refactor the _LazilyImportedModule _import_once method to customize how module attributes are cached after initial import'}
```

