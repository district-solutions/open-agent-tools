# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/protobuf/objectivec/DevTools/pddm.py

Prompts

```
['run the pddm command line tool to process PDDM directives in source files', 'run pddm with --dry-run to check if files need updating without writing changes', 'run pddm with --collapse to remove all generated code from source files', 'expand macro references using MacroCollection.Expand to resolve PDDM macro invocations', 'parse PDDM macro definitions from source lines using MacroCollection.ParseLines', 'expand macro invocations like foo(a,b) using a MacroCollection and return substituted text', 'parse a source file into sections separating PDDM-DEFINE and PDDM-EXPAND blocks', 'process a source file to expand all PDDM-EXPAND blocks and return generated content', 'test that the PDDM macro system detects and raises errors on recursive macro invocations']
```

Usage

```
{'run_pddm_cli': 'run the pddm command line tool to process PDDM directives in source files', 'run_pddm_dry_run': 'run pddm with --dry-run to check if files need updating without writing changes', 'run_pddm_collapse': 'run pddm with --collapse to remove all generated code from source files', 'expand_macro_collection': 'expand macro references using MacroCollection.Expand to resolve PDDM macro invocations', 'parse_macro_definitions': 'parse PDDM macro definitions from source lines using MacroCollection.ParseLines'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/protobuf/objectivec/DevTools/pddm_tests.py

Prompts

```
['run the pddm command line tool to process PDDM directives in source files', 'run pddm with --dry-run to check if files need updating without writing changes', 'run pddm with --collapse to remove all generated code from source files', 'expand macro references using MacroCollection.Expand to resolve PDDM macro invocations', 'parse PDDM macro definitions from source lines using MacroCollection.ParseLines', 'expand macro invocations like foo(a,b) using a MacroCollection and return substituted text', 'parse a source file into sections separating PDDM-DEFINE and PDDM-EXPAND blocks', 'process a source file to expand all PDDM-EXPAND blocks and return generated content', 'test that the PDDM macro system detects and raises errors on recursive macro invocations']
```

Usage

```
{'parse_macro_definitions': 'parse PDDM-DEFINE macro definitions from a text file into a MacroCollection', 'expand_macros': 'expand macro invocations like foo(a,b) using a MacroCollection and return substituted text', 'parse_source_file_sections': 'parse a source file into sections separating PDDM-DEFINE and PDDM-EXPAND blocks', 'process_source_content': 'process a source file to expand all PDDM-EXPAND blocks and return generated content', 'test_macro_recursion_detection': 'test that the PDDM macro system detects and raises errors on recursive macro invocations'}
```

