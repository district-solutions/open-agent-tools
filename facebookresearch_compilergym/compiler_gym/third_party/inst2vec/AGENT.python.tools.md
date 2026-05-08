# Agent Python Tools

- repo: facebookresearch/compilergym
- repo_uri: https://github.com/facebookresearch/compilergym

## File: facebookresearch_compilergym/compiler_gym/third_party/inst2vec/inst2vec_preprocess.py

Prompts

```
['preprocess a list of LLVM IR files by removing non-representative lines, comments, metadata, and structure definitions', 'extract a dictionary of struct type definitions from a string of LLVM IR code', 'preprocess a single LLVM IR statement by replacing identifiers, labels, floats, ints, and strings with abstract tokens', 'get a list of function names declared in a list of LLVM IR bytecode lines', 'filter a single LLVM IR line to determine if it is representative and should be kept', 'create a regex alternation pattern from a list of string possibilities using any_of', 'get all unique level-1 LLVM IR statement family tags from llvm_IR_stmt_families', 'get all level-2 tags filtered by a given level-1 tag from llvm_IR_stmt_families', 'review the llvm_IR_stmt_families list of regex-based LLVM IR statement family classifications', 'summarize the llvm_IR_stmt_tags list of regex patterns for LLVM IR statement type clustering']
```

Usage

```
{'preprocess_llvm_ir': 'preprocess a list of LLVM IR files by removing non-representative lines, comments, metadata, and structure definitions', 'extract_struct_types': 'extract a dictionary of struct type definitions from a string of LLVM IR code', 'preprocess_statement': 'preprocess a single LLVM IR statement by replacing identifiers, labels, floats, ints, and strings with abstract tokens', 'get_declared_functions': 'get a list of function names declared in a list of LLVM IR bytecode lines', 'filter_ir_line': 'filter a single LLVM IR line to determine if it is representative and should be kept'}
```

## File: facebookresearch_compilergym/compiler_gym/third_party/inst2vec/rgx_utils.py

Prompts

```
['preprocess a list of LLVM IR files by removing non-representative lines, comments, metadata, and structure definitions', 'extract a dictionary of struct type definitions from a string of LLVM IR code', 'preprocess a single LLVM IR statement by replacing identifiers, labels, floats, ints, and strings with abstract tokens', 'get a list of function names declared in a list of LLVM IR bytecode lines', 'filter a single LLVM IR line to determine if it is representative and should be kept', 'create a regex alternation pattern from a list of string possibilities using any_of', 'get all unique level-1 LLVM IR statement family tags from llvm_IR_stmt_families', 'get all level-2 tags filtered by a given level-1 tag from llvm_IR_stmt_families', 'review the llvm_IR_stmt_families list of regex-based LLVM IR statement family classifications', 'summarize the llvm_IR_stmt_tags list of regex patterns for LLVM IR statement type clustering']
```

Usage

```
{'any_of': 'create a regex alternation pattern from a list of string possibilities using any_of', 'get_list_tag_level_1': 'get all unique level-1 LLVM IR statement family tags from llvm_IR_stmt_families', 'get_list_tag_level_2': 'get all level-2 tags filtered by a given level-1 tag from llvm_IR_stmt_families', 'llvm_IR_stmt_families': 'review the llvm_IR_stmt_families list of regex-based LLVM IR statement family classifications', 'llvm_IR_stmt_tags': 'summarize the llvm_IR_stmt_tags list of regex patterns for LLVM IR statement type clustering'}
```

