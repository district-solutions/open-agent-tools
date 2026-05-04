# Agent Python Tools

- repo: facebookresearch/elf
- repo_uri: https://github.com/facebookresearch/elf

## File: facebookresearch_elf/vendor/pybind11/tools/clang/cindex.py

Prompts

```
['parse a C or C++ source file into a TranslationUnit using Index.parse with command line args', 'inspect the children of a Cursor by iterating over cursor.get_children to traverse the AST', 'get compilation diagnostics from a TranslationUnit by iterating over tu.diagnostics to find errors and warnings', 'query the file, line, and column of a SourceLocation via its file, line, and column properties', 'walk the AST in depth-first preorder using cursor.walk_preorder to yield all descendant cursors']
```

Usage

```
{'parse_translation_unit': 'parse a C or C++ source file into a TranslationUnit using Index.parse with command line args', 'inspect_cursor_children': 'inspect the children of a Cursor by iterating over cursor.get_children to traverse the AST', 'get_diagnostics': 'get compilation diagnostics from a TranslationUnit by iterating over tu.diagnostics to find errors and warnings', 'query_source_location': 'query the file, line, and column of a SourceLocation via its file, line, and column properties', 'walk_ast_preorder': 'walk the AST in depth-first preorder using cursor.walk_preorder to yield all descendant cursors'}
```

