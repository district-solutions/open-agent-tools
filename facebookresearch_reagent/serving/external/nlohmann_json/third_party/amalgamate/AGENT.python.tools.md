# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/serving/external/nlohmann_json/third_party/amalgamate/amalgamate.py

Prompts

```
['run amalgamate.py with -c config.json -s source_dir to merge C source and header files into a single file', 'run amalgamate.py with -v yes to print detailed config and file processing information during amalgamation', 'run amalgamate.py with -p prologue.h to prepend a timestamped prologue file to the amalgamated output', 'call Amalgamation.generate() to process all source files, resolve includes, and write the merged output to the target file', 'create a TranslationUnit to read a C file, strip pragma once, and recursively inline all include directives']
```

Usage

```
{'run_amalgamate_cli': 'run amalgamate.py with -c config.json -s source_dir to merge C source and header files into a single file', 'run_amalgamate_verbose': 'run amalgamate.py with -v yes to print detailed config and file processing information during amalgamation', 'run_amalgamate_with_prologue': 'run amalgamate.py with -p prologue.h to prepend a timestamped prologue file to the amalgamated output', 'generate_amalgamation': 'call Amalgamation.generate() to process all source files, resolve includes, and write the merged output to the target file', 'process_translation_unit': 'create a TranslationUnit to read a C file, strip pragma once, and recursively inline all include directives'}
```

