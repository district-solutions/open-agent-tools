# Agent Python Tools

- repo: facebookresearch/cruxeval
- repo_uri: https://github.com/facebookresearch/cruxeval

## File: facebookresearch_cruxeval/data/filter/analyze_ops.py

Prompts

```
['run annotate on Python code to detect undesirable operations like big numbers, float ops, and true division', 'check an assert line to validate it matches the expected pattern of assert f(args) == literal', 'use filter_trace as a sys.settrace callback to inspect BINARY and INPLACE bytecode operations at runtime', 'test the annotate function by running the built-in test that checks code with big power ops and safe code', 'raise a ForbiddenException when code contains forbidden patterns like import, eval, exec, or open']
```

Usage

```
{'annotate_code_for_bad_ops': 'run annotate on Python code to detect undesirable operations like big numbers, float ops, and true division', 'check_assert_statement': 'check an assert line to validate it matches the expected pattern of assert f(args) == literal', 'filter_trace_bytecode_ops': 'use filter_trace as a sys.settrace callback to inspect BINARY and INPLACE bytecode operations at runtime', 'test_annotate_function': 'test the annotate function by running the built-in test that checks code with big power ops and safe code', 'raise_forbidden_exception': 'raise a ForbiddenException when code contains forbidden patterns like import, eval, exec, or open'}
```

