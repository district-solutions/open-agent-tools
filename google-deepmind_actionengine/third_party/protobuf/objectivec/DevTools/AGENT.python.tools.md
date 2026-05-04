# Agent Python Tools

- repo: google-deepmind/actionengine
- repo_uri: https://github.com/google-deepmind/actionengine

## File: google-deepmind_actionengine/third_party/protobuf/objectivec/DevTools/pddm.py

Prompts

```
['run pddm on a source file to expand PDDM macro directives into debuggable code', 'run pddm in dry-run mode to check if a source file needs macro expansion updates', 'run pddm with collapse option to remove all generated macro expansion code from a file', 'create a MacroCollection and parse macro definitions from a file-like stream', 'create a MacroCollection and expand a macro reference string like foo(a, b) into code', 'test the pddm macro collection parsing for PDDM-DEFINE directives with various argument patterns', 'test the pddm macro expansion with arg options like dollar sign S, l, L, u, U', 'test the pddm source file processing with PDDM-EXPAND and PDDM-DEFINE sections', 'test the pddm macro recursion detection when macros reference each other in a cycle', 'test the pddm error handling for undefined macros, arg mismatches, and invalid directives']
```

Usage

```
{'run_pddm_expand': 'run pddm on a source file to expand PDDM macro directives into debuggable code', 'run_pddm_dry_run': 'run pddm in dry-run mode to check if a source file needs macro expansion updates', 'run_pddm_collapse': 'run pddm with collapse option to remove all generated macro expansion code from a file', 'create_macrocollection_parse': 'create a MacroCollection and parse macro definitions from a file-like stream', 'create_macrocollection_expand': 'create a MacroCollection and expand a macro reference string like foo(a, b) into code'}
```

## File: google-deepmind_actionengine/third_party/protobuf/objectivec/DevTools/pddm_tests.py

Prompts

```
['run pddm on a source file to expand PDDM macro directives into debuggable code', 'run pddm in dry-run mode to check if a source file needs macro expansion updates', 'run pddm with collapse option to remove all generated macro expansion code from a file', 'create a MacroCollection and parse macro definitions from a file-like stream', 'create a MacroCollection and expand a macro reference string like foo(a, b) into code', 'test the pddm macro collection parsing for PDDM-DEFINE directives with various argument patterns', 'test the pddm macro expansion with arg options like dollar sign S, l, L, u, U', 'test the pddm source file processing with PDDM-EXPAND and PDDM-DEFINE sections', 'test the pddm macro recursion detection when macros reference each other in a cycle', 'test the pddm error handling for undefined macros, arg mismatches, and invalid directives']
```

Usage

```
{'test_pddm_macro_parsing': 'test the pddm macro collection parsing for PDDM-DEFINE directives with various argument patterns', 'test_pddm_macro_expansion': 'test the pddm macro expansion with arg options like dollar sign S, l, L, u, U', 'test_pddm_source_file_processing': 'test the pddm source file processing with PDDM-EXPAND and PDDM-DEFINE sections', 'test_pddm_macro_recursion_detection': 'test the pddm macro recursion detection when macros reference each other in a cycle', 'test_pddm_error_handling': 'test the pddm error handling for undefined macros, arg mismatches, and invalid directives'}
```

