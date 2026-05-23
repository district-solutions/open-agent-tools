# Agent Python Tools

- repo: facebookresearch/spdl
- repo_uri: https://github.com/facebookresearch/spdl

## File: facebookresearch_spdl/src/spdl/io/_internal/import_utils.py

Prompts

```
['create a function that lazily imports a module only when its attributes are first accessed', 'build a custom module class that delays import until an attribute is accessed via __getattr__', 'review the _LazilyImportedModule class to return a readable string representation of the lazy module', 'summarize the _LazilyImportedModule __dir__ method to list available attributes after lazy import', 'test the _import_once method to ensure the module is imported only once and cached']
```

Usage

```
{'use_lazy_import': 'create a function that lazily imports a module only when its attributes are first accessed', 'use_LazilyImportedModule_getattr': 'build a custom module class that delays import until an attribute is accessed via __getattr__', 'use_LazilyImportedModule_repr': 'review the _LazilyImportedModule class to return a readable string representation of the lazy module', 'use_LazilyImportedModule_dir': 'summarize the _LazilyImportedModule __dir__ method to list available attributes after lazy import', 'use_LazilyImportedModule_import_once': 'test the _import_once method to ensure the module is imported only once and cached'}
```

