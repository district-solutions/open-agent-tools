# Agent Python Tools

- repo: facebookresearch/craftassist
- repo_uri: https://github.com/facebookresearch/craftassist

## File: facebookresearch_craftassist/client/pybind11/tools/clang/cindex.py

Prompts

```
['parse a C or C++ source file into a TranslationUnit using Index.parse with command line args', 'get all child cursors of a Cursor by iterating over cursor.get_children() to traverse the AST', 'get the definition cursor for a declaration or reference cursor using cursor.get_definition()', 'iterate over translation unit diagnostics using tu.diagnostics to inspect severity, location, and spelling', 'run code completion at a specific line and column in a TranslationUnit using tu.codeComplete(path, line, column)']
```

Usage

```
{'parse_translation_unit': 'parse a C or C++ source file into a TranslationUnit using Index.parse with command line args', 'cursor_get_children': 'get all child cursors of a Cursor by iterating over cursor.get_children() to traverse the AST', 'cursor_get_definition': 'get the definition cursor for a declaration or reference cursor using cursor.get_definition()', 'diagnostics_iterate': 'iterate over translation unit diagnostics using tu.diagnostics to inspect severity, location, and spelling', 'code_complete': 'run code completion at a specific line and column in a TranslationUnit using tu.codeComplete(path, line, column)'}
```

