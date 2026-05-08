# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/tests/third_party/gccinvocation/gccinvocation_test.py

Prompts

```
['parse a gcc command line string into an argv list handling quotes and spaces', 'create a GccInvocation object from an argv list to extract sources defines and include paths', 'create a GccInvocation object from a raw command line string using the from_cmdline class method', 'extract preprocessor defines and include paths from a gcc invocation using the defines and includepaths properties', 'restrict a multi-source gcc invocation to a single source file using restrict_to_one_source']
```

Usage

```
{'parse_cmdline_to_argv': 'parse a gcc command line string into an argv list handling quotes and spaces', 'parse_gcc_invocation_from_argv': 'create a GccInvocation object from an argv list to extract sources defines and include paths', 'parse_gcc_invocation_from_cmdline': 'create a GccInvocation object from a raw command line string using the from_cmdline class method', 'extract_gcc_defines_and_includes': 'extract preprocessor defines and include paths from a gcc invocation using the defines and includepaths properties', 'restrict_gcc_to_one_source': 'restrict a multi-source gcc invocation to a single source file using restrict_to_one_source'}
```

