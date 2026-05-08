# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/docs/generate_cc_rst.py

Prompts

```
['run the script to auto-generate RST documentation files from C++ header and proto files', 'create an RST-style formatted header string with a configurable underline character', 'walk the compiler_gym source directory to find all .h and .proto header files', 'generate RST files with doxygenfile directives for each C++ header found in the source tree', 'remove stale RST files from the output directory that no longer correspond to source headers']
```

Usage

```
{'generate_rst_from_headers': 'run the script to auto-generate RST documentation files from C++ header and proto files', 'create_rst_header': 'create an RST-style formatted header string with a configurable underline character', 'walk_source_for_headers': 'walk the compiler_gym source directory to find all .h and .proto header files', 'generate_doxygen_rst': 'generate RST files with doxygenfile directives for each C++ header found in the source tree', 'cleanup_stale_rst': 'remove stale RST files from the output directory that no longer correspond to source headers'}
```

