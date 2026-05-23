# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/objectivec/DevTools/pddm.py

Prompts

```
['run pddm to process PDDM directives in a source file and write expanded macros back', 'create a MacroCollection to expand a macro reference like foo(a, b) into generated code', 'build a macro definition with named arguments that can be expanded into C code templates', 'create an IMPORT-DEFINES section to import macro definitions from an external PDDM file', 'run pddm with --dry-run to check if a file needs updating without writing changes', 'parse PDDM macro definitions from a text file into a MacroCollection', 'expand a PDDM macro reference with arguments using MacroCollection.Expand', 'parse an Objective-C source file with PDDM directives into sections', 'process a source file to expand PDDM macros and generate code', 'test that PDDM macro recursion is detected and raises a PDDMError']
```

Usage

```
{'process_pddm_file': 'run pddm to process PDDM directives in a source file and write expanded macros back', 'expand_macro': 'create a MacroCollection to expand a macro reference like foo(a, b) into generated code', 'define_macro': 'build a macro definition with named arguments that can be expanded into C code templates', 'import_defines': 'create an IMPORT-DEFINES section to import macro definitions from an external PDDM file', 'dry_run_check': 'run pddm with --dry-run to check if a file needs updating without writing changes'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/objectivec/DevTools/pddm_tests.py

Prompts

```
['run pddm to process PDDM directives in a source file and write expanded macros back', 'create a MacroCollection to expand a macro reference like foo(a, b) into generated code', 'build a macro definition with named arguments that can be expanded into C code templates', 'create an IMPORT-DEFINES section to import macro definitions from an external PDDM file', 'run pddm with --dry-run to check if a file needs updating without writing changes', 'parse PDDM macro definitions from a text file into a MacroCollection', 'expand a PDDM macro reference with arguments using MacroCollection.Expand', 'parse an Objective-C source file with PDDM directives into sections', 'process a source file to expand PDDM macros and generate code', 'test that PDDM macro recursion is detected and raises a PDDMError']
```

Usage

```
{'parse_pddm_macros': 'parse PDDM macro definitions from a text file into a MacroCollection', 'expand_pddm_macro': 'expand a PDDM macro reference with arguments using MacroCollection.Expand', 'parse_source_file': 'parse an Objective-C source file with PDDM directives into sections', 'process_source_content': 'process a source file to expand PDDM macros and generate code', 'test_pddm_recursion': 'test that PDDM macro recursion is detected and raises a PDDMError'}
```

