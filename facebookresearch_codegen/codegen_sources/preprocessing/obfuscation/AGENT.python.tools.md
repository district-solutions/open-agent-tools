# Agent Python Tools

- repo: facebookresearch/codegen
- repo_uri: https://github.com/facebookresearch/codegen

## File: facebookresearch_codegen/codegen_sources/preprocessing/obfuscation/bobskater_frameUtils.py

Prompts

```
['create a Frame object to track identifiers and scope in a Python AST stack frame', 'add a FrameEntry to a Frame to record an identifier with its source node and context', 'search upward through parent frames to find the first scoped entry for a given identifier ID', 'extract all identifier names from a Python AST node using getIdsFromNode for obfuscation', 'rename identifiers on a Python AST node by setting new names with setIdsOnNode', 'obfuscate a Python source code string by renaming identifiers and optionally removing docstrings', 'obfuscate a Python source file in place by renaming all eligible identifiers', 'generate an infinite iterator of valid Python identifiers that skip reserved keywords', 'build a FrameTrackingNodeVisitor to walk an AST and track all identifier scopes and frames', 'transform an AST by mangling names using an ObfuscationTransformer with a root frame', 'obfuscate a Java program by replacing all identifiers with generated obfuscated names', 'get variable usages and method invocations from a Java program using AST parsing', 'add a declaration node for a class, method, or variable to the declarations dictionary', 'add a method invocation node to the list of nodes that need name replacement', 'compare two javalang token positions to determine ordering or equality', 'create an ObfuscatedNamesGenerator instance to generate obfuscated names for variables, functions, and classes', 'get a new obfuscated name for a variable, function, or class using get_new_name', 'get the complete obfuscation dictionary mapping obfuscated names back to original names', 'check if a function name has already been obfuscated using function_is_obfuscated', 'obfuscate attribute names by passing isAttribute=True to get_new_name', 'cleanup an obfuscated function by renaming tokens and updating the deobfuscation dictionary', 'build a rename dictionary mapping obfuscated tokens to sequential VAR_ FUNC_ or CLASS_ prefixed names', 'rename obfuscated tokens in a string using a provided rename dictionary', 'replace a function name token with FUNC_0 in an obfuscated function string', 'read a pipe separated deobfuscation dictionary string into a Python dictionary']
```

Usage

```
{'create_frame_scope': 'create a Frame object to track identifiers and scope in a Python AST stack frame', 'add_frame_entry': 'add a FrameEntry to a Frame to record an identifier with its source node and context', 'get_scoped_entry': 'search upward through parent frames to find the first scoped entry for a given identifier ID', 'extract_ids_from_ast': 'extract all identifier names from a Python AST node using getIdsFromNode for obfuscation', 'rename_ast_identifiers': 'rename identifiers on a Python AST node by setting new names with setIdsOnNode'}
```

## File: facebookresearch_codegen/codegen_sources/preprocessing/obfuscation/bobskater_obfuscator.py

Prompts

```
['create a Frame object to track identifiers and scope in a Python AST stack frame', 'add a FrameEntry to a Frame to record an identifier with its source node and context', 'search upward through parent frames to find the first scoped entry for a given identifier ID', 'extract all identifier names from a Python AST node using getIdsFromNode for obfuscation', 'rename identifiers on a Python AST node by setting new names with setIdsOnNode', 'obfuscate a Python source code string by renaming identifiers and optionally removing docstrings', 'obfuscate a Python source file in place by renaming all eligible identifiers', 'generate an infinite iterator of valid Python identifiers that skip reserved keywords', 'build a FrameTrackingNodeVisitor to walk an AST and track all identifier scopes and frames', 'transform an AST by mangling names using an ObfuscationTransformer with a root frame', 'obfuscate a Java program by replacing all identifiers with generated obfuscated names', 'get variable usages and method invocations from a Java program using AST parsing', 'add a declaration node for a class, method, or variable to the declarations dictionary', 'add a method invocation node to the list of nodes that need name replacement', 'compare two javalang token positions to determine ordering or equality', 'create an ObfuscatedNamesGenerator instance to generate obfuscated names for variables, functions, and classes', 'get a new obfuscated name for a variable, function, or class using get_new_name', 'get the complete obfuscation dictionary mapping obfuscated names back to original names', 'check if a function name has already been obfuscated using function_is_obfuscated', 'obfuscate attribute names by passing isAttribute=True to get_new_name', 'cleanup an obfuscated function by renaming tokens and updating the deobfuscation dictionary', 'build a rename dictionary mapping obfuscated tokens to sequential VAR_ FUNC_ or CLASS_ prefixed names', 'rename obfuscated tokens in a string using a provided rename dictionary', 'replace a function name token with FUNC_0 in an obfuscated function string', 'read a pipe separated deobfuscation dictionary string into a Python dictionary']
```

Usage

```
{'obfuscate_python_string': 'obfuscate a Python source code string by renaming identifiers and optionally removing docstrings', 'obfuscate_python_file': 'obfuscate a Python source file in place by renaming all eligible identifiers', 'generate_valid_identifiers': 'generate an infinite iterator of valid Python identifiers that skip reserved keywords', 'build_frame_tracking_visitor': 'build a FrameTrackingNodeVisitor to walk an AST and track all identifier scopes and frames', 'transform_ast_names': 'transform an AST by mangling names using an ObfuscationTransformer with a root frame'}
```

## File: facebookresearch_codegen/codegen_sources/preprocessing/obfuscation/javalang_obfuscator.py

Prompts

```
['create a Frame object to track identifiers and scope in a Python AST stack frame', 'add a FrameEntry to a Frame to record an identifier with its source node and context', 'search upward through parent frames to find the first scoped entry for a given identifier ID', 'extract all identifier names from a Python AST node using getIdsFromNode for obfuscation', 'rename identifiers on a Python AST node by setting new names with setIdsOnNode', 'obfuscate a Python source code string by renaming identifiers and optionally removing docstrings', 'obfuscate a Python source file in place by renaming all eligible identifiers', 'generate an infinite iterator of valid Python identifiers that skip reserved keywords', 'build a FrameTrackingNodeVisitor to walk an AST and track all identifier scopes and frames', 'transform an AST by mangling names using an ObfuscationTransformer with a root frame', 'obfuscate a Java program by replacing all identifiers with generated obfuscated names', 'get variable usages and method invocations from a Java program using AST parsing', 'add a declaration node for a class, method, or variable to the declarations dictionary', 'add a method invocation node to the list of nodes that need name replacement', 'compare two javalang token positions to determine ordering or equality', 'create an ObfuscatedNamesGenerator instance to generate obfuscated names for variables, functions, and classes', 'get a new obfuscated name for a variable, function, or class using get_new_name', 'get the complete obfuscation dictionary mapping obfuscated names back to original names', 'check if a function name has already been obfuscated using function_is_obfuscated', 'obfuscate attribute names by passing isAttribute=True to get_new_name', 'cleanup an obfuscated function by renaming tokens and updating the deobfuscation dictionary', 'build a rename dictionary mapping obfuscated tokens to sequential VAR_ FUNC_ or CLASS_ prefixed names', 'rename obfuscated tokens in a string using a provided rename dictionary', 'replace a function name token with FUNC_0 in an obfuscated function string', 'read a pipe separated deobfuscation dictionary string into a Python dictionary']
```

Usage

```
{'obfuscate_java_program': 'obfuscate a Java program by replacing all identifiers with generated obfuscated names', 'get_variable_usages_from_java': 'get variable usages and method invocations from a Java program using AST parsing', 'add_declaration_node': 'add a declaration node for a class, method, or variable to the declarations dictionary', 'add_node_to_replace': 'add a method invocation node to the list of nodes that need name replacement', 'compare_token_positions': 'compare two javalang token positions to determine ordering or equality'}
```

## File: facebookresearch_codegen/codegen_sources/preprocessing/obfuscation/obfuscated_names_generator.py

Prompts

```
['create a Frame object to track identifiers and scope in a Python AST stack frame', 'add a FrameEntry to a Frame to record an identifier with its source node and context', 'search upward through parent frames to find the first scoped entry for a given identifier ID', 'extract all identifier names from a Python AST node using getIdsFromNode for obfuscation', 'rename identifiers on a Python AST node by setting new names with setIdsOnNode', 'obfuscate a Python source code string by renaming identifiers and optionally removing docstrings', 'obfuscate a Python source file in place by renaming all eligible identifiers', 'generate an infinite iterator of valid Python identifiers that skip reserved keywords', 'build a FrameTrackingNodeVisitor to walk an AST and track all identifier scopes and frames', 'transform an AST by mangling names using an ObfuscationTransformer with a root frame', 'obfuscate a Java program by replacing all identifiers with generated obfuscated names', 'get variable usages and method invocations from a Java program using AST parsing', 'add a declaration node for a class, method, or variable to the declarations dictionary', 'add a method invocation node to the list of nodes that need name replacement', 'compare two javalang token positions to determine ordering or equality', 'create an ObfuscatedNamesGenerator instance to generate obfuscated names for variables, functions, and classes', 'get a new obfuscated name for a variable, function, or class using get_new_name', 'get the complete obfuscation dictionary mapping obfuscated names back to original names', 'check if a function name has already been obfuscated using function_is_obfuscated', 'obfuscate attribute names by passing isAttribute=True to get_new_name', 'cleanup an obfuscated function by renaming tokens and updating the deobfuscation dictionary', 'build a rename dictionary mapping obfuscated tokens to sequential VAR_ FUNC_ or CLASS_ prefixed names', 'rename obfuscated tokens in a string using a provided rename dictionary', 'replace a function name token with FUNC_0 in an obfuscated function string', 'read a pipe separated deobfuscation dictionary string into a Python dictionary']
```

Usage

```
{'create_obfuscated_names_generator': 'create an ObfuscatedNamesGenerator instance to generate obfuscated names for variables, functions, and classes', 'get_new_obfuscated_name': 'get a new obfuscated name for a variable, function, or class using get_new_name', 'get_obfuscation_dictionary': 'get the complete obfuscation dictionary mapping obfuscated names back to original names', 'check_function_obfuscated': 'check if a function name has already been obfuscated using function_is_obfuscated', 'obfuscate_attribute_names': 'obfuscate attribute names by passing isAttribute=True to get_new_name'}
```

## File: facebookresearch_codegen/codegen_sources/preprocessing/obfuscation/utils_deobfuscation.py

Prompts

```
['create a Frame object to track identifiers and scope in a Python AST stack frame', 'add a FrameEntry to a Frame to record an identifier with its source node and context', 'search upward through parent frames to find the first scoped entry for a given identifier ID', 'extract all identifier names from a Python AST node using getIdsFromNode for obfuscation', 'rename identifiers on a Python AST node by setting new names with setIdsOnNode', 'obfuscate a Python source code string by renaming identifiers and optionally removing docstrings', 'obfuscate a Python source file in place by renaming all eligible identifiers', 'generate an infinite iterator of valid Python identifiers that skip reserved keywords', 'build a FrameTrackingNodeVisitor to walk an AST and track all identifier scopes and frames', 'transform an AST by mangling names using an ObfuscationTransformer with a root frame', 'obfuscate a Java program by replacing all identifiers with generated obfuscated names', 'get variable usages and method invocations from a Java program using AST parsing', 'add a declaration node for a class, method, or variable to the declarations dictionary', 'add a method invocation node to the list of nodes that need name replacement', 'compare two javalang token positions to determine ordering or equality', 'create an ObfuscatedNamesGenerator instance to generate obfuscated names for variables, functions, and classes', 'get a new obfuscated name for a variable, function, or class using get_new_name', 'get the complete obfuscation dictionary mapping obfuscated names back to original names', 'check if a function name has already been obfuscated using function_is_obfuscated', 'obfuscate attribute names by passing isAttribute=True to get_new_name', 'cleanup an obfuscated function by renaming tokens and updating the deobfuscation dictionary', 'build a rename dictionary mapping obfuscated tokens to sequential VAR_ FUNC_ or CLASS_ prefixed names', 'rename obfuscated tokens in a string using a provided rename dictionary', 'replace a function name token with FUNC_0 in an obfuscated function string', 'read a pipe separated deobfuscation dictionary string into a Python dictionary']
```

Usage

```
{'cleanup_obfuscated_function': 'cleanup an obfuscated function by renaming tokens and updating the deobfuscation dictionary', 'build_rename_dict': 'build a rename dictionary mapping obfuscated tokens to sequential VAR_ FUNC_ or CLASS_ prefixed names', 'rename_tok': 'rename obfuscated tokens in a string using a provided rename dictionary', 'replace_function_name': 'replace a function name token with FUNC_0 in an obfuscated function string', 'read_dict': 'read a pipe separated deobfuscation dictionary string into a Python dictionary'}
```

