# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/protobuf/objectivec/DevTools/pddm.py

Prompts

```
['run pddm on source files to expand PDDM-EXPAND directives into debuggable code', 'run pddm with --dry-run to check which files need updating without modifying them', 'run pddm with --collapse to remove all generated code from source files', 'create a MacroCollection to parse and expand PDDM macro definitions from input', 'expand a PDDM macro reference like foo(a, b) using MacroCollection.Expand method', 'create a SourceFile object to parse PDDM directives and process file content', 'process a SourceFile to expand all PDDM-EXPAND sections and get processed content', 'define a PDDM macro with PDDM-DEFINE Name(args) and body lines starting with //%', 'expand PDDM macros in C source code using //%PDDM-EXPAND and //%PDDM-EXPAND-END directives', 'import PDDM macro definitions from external files using //%PDDM-IMPORT-DEFINES directive', 'parse PDDM macro definitions from a text file into a MacroCollection object', 'expand macro invocations like foo(arg1,arg2) using a MacroCollection and the Expand method', 'parse an Objective-C source file into sections with PDDM-DEFINE and PDDM-EXPAND directives', 'process a source file to expand all PDDM-EXPAND blocks using defined macros and a resolver', 'test that invalid macro definitions raise PDDMError with the expected error message']
```

Usage

```
{'run_pddm_cli': 'run pddm on source files to expand PDDM-EXPAND directives into debuggable code', 'run_pddm_dry_run': 'run pddm with --dry-run to check which files need updating without modifying them', 'run_pddm_collapse': 'run pddm with --collapse to remove all generated code from source files', 'create_macro_collection': 'create a MacroCollection to parse and expand PDDM macro definitions from input', 'expand_macro': 'expand a PDDM macro reference like foo(a, b) using MacroCollection.Expand method', 'create_source_file': 'create a SourceFile object to parse PDDM directives and process file content', 'process_source_content': 'process a SourceFile to expand all PDDM-EXPAND sections and get processed content', 'define_pddm_macro': 'define a PDDM macro with PDDM-DEFINE Name(args) and body lines starting with //%', 'expand_pddm_in_code': 'expand PDDM macros in C source code using //%PDDM-EXPAND and //%PDDM-EXPAND-END directives', 'import_pddm_defines': 'import PDDM macro definitions from external files using //%PDDM-IMPORT-DEFINES directive'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/protobuf/objectivec/DevTools/pddm_tests.py

Prompts

```
['run pddm on source files to expand PDDM-EXPAND directives into debuggable code', 'run pddm with --dry-run to check which files need updating without modifying them', 'run pddm with --collapse to remove all generated code from source files', 'create a MacroCollection to parse and expand PDDM macro definitions from input', 'expand a PDDM macro reference like foo(a, b) using MacroCollection.Expand method', 'create a SourceFile object to parse PDDM directives and process file content', 'process a SourceFile to expand all PDDM-EXPAND sections and get processed content', 'define a PDDM macro with PDDM-DEFINE Name(args) and body lines starting with //%', 'expand PDDM macros in C source code using //%PDDM-EXPAND and //%PDDM-EXPAND-END directives', 'import PDDM macro definitions from external files using //%PDDM-IMPORT-DEFINES directive', 'parse PDDM macro definitions from a text file into a MacroCollection object', 'expand macro invocations like foo(arg1,arg2) using a MacroCollection and the Expand method', 'parse an Objective-C source file into sections with PDDM-DEFINE and PDDM-EXPAND directives', 'process a source file to expand all PDDM-EXPAND blocks using defined macros and a resolver', 'test that invalid macro definitions raise PDDMError with the expected error message']
```

Usage

```
{'parse_macro_definitions': 'parse PDDM macro definitions from a text file into a MacroCollection object', 'expand_macro_invocations': 'expand macro invocations like foo(arg1,arg2) using a MacroCollection and the Expand method', 'parse_source_file_sections': 'parse an Objective-C source file into sections with PDDM-DEFINE and PDDM-EXPAND directives', 'process_source_with_expansion': 'process a source file to expand all PDDM-EXPAND blocks using defined macros and a resolver', 'test_macro_parsing_errors': 'test that invalid macro definitions raise PDDMError with the expected error message'}
```

