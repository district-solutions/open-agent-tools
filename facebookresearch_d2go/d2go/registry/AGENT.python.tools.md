# Agent Python Tools

- repo: facebookresearch/d2go
- repo_uri: https://github.com/facebookresearch/d2go

## File: facebookresearch_d2go/d2go/registry/bootstrap.py

Prompts

```
['bootstrap all d2go registries by scanning and lazily registering objects from all Python files in the package', 'break out of the bootstrap process mid-execution to skip remaining unexecutable code in a file', 'decorate a function to return a MagicMock during bootstrap instead of executing the real function body', 'use the BootstrapStatus enum to check if a file was CACHED, FULLY_IMPORTED, PARTIALLY_IMPORTED, or FAILED during bootstrap', 'inspect a CachedResult dataclass to view the sha1 hash, registered names, and bootstrap status for a file']
```

Usage

```
{'bootstrap_registries': 'bootstrap all d2go registries by scanning and lazily registering objects from all Python files in the package', 'break_bootstrap': 'break out of the bootstrap process mid-execution to skip remaining unexecutable code in a file', 'lazy_on_bootstrap': 'decorate a function to return a MagicMock during bootstrap instead of executing the real function body', 'BootstrapStatus': 'use the BootstrapStatus enum to check if a file was CACHED, FULLY_IMPORTED, PARTIALLY_IMPORTED, or FAILED during bootstrap', 'CachedResult': 'inspect a CachedResult dataclass to view the sha1 hash, registered names, and bootstrap status for a file'}
```

