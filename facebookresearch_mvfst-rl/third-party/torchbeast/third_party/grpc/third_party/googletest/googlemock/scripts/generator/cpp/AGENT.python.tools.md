# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/googletest/googlemock/scripts/generator/cpp/ast.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and Generate to yield parsed nodes', 'print all identifiers from a C++ source file filtered by a predicate function', 'print identifiers from multiple C++ source files using a shared predicate filter', 'run the C++ AST parser CLI on source files to print parsed AST nodes', 'review the Node subclasses like Class, Function, Method, Type, and Typedef for C++ AST structure', 'run the unittest suite to verify gmock_class generates correct mock macros from C++ source', 'test the _GenerateMethods function converts C++ class declarations into MOCK_METHOD macro lines', 'test the _GenerateMocks function produces complete Mock class source from C++ input', 'test that constructors and destructors are correctly ignored during mock method generation', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template parameters', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token string is a C++ builtin type using IsBuiltinType', 'list all C++ keywords from the ALL set constant', 'list all C++ type keywords from the TYPES set constant', 'list all C++ control flow keywords from the CONTROL set constant', 'run the C++ tokenizer on a source file to print all tokens with their types', 'create a generator that yields Token objects from C++ source code string input', 'build a Token data container with type, name, start, and end position attributes', 'review the _GetString helper that finds closing quotes while handling backslash escapes', 'summarize the token type constants UNKNOWN, SYNTAX, CONSTANT, NAME, and PREPROCESSOR', 'read the contents of a file and return the text or None on error', 'read a file silently without printing errors by setting print_error to False', 'review the ReadFile function that opens a file and returns its contents with error handling', 'summarize the ReadFile function which reads a file and handles IOError exceptions gracefully', 'test the ReadFile function by passing a filename and verifying it returns file contents or None']
```

Usage

```
{'build_ast_from_cpp_source': 'build an AST from C++ source code using BuilderFromSource and Generate to yield parsed nodes', 'print_identifiers_from_cpp_file': 'print all identifiers from a C++ source file filtered by a predicate function', 'print_identifiers_from_multiple_files': 'print identifiers from multiple C++ source files using a shared predicate filter', 'run_cpp_ast_parser_cli': 'run the C++ AST parser CLI on source files to print parsed AST nodes', 'review_ast_node_classes': 'review the Node subclasses like Class, Function, Method, Type, and Typedef for C++ AST structure'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/googletest/googlemock/scripts/generator/cpp/gmock_class_test.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and Generate to yield parsed nodes', 'print all identifiers from a C++ source file filtered by a predicate function', 'print identifiers from multiple C++ source files using a shared predicate filter', 'run the C++ AST parser CLI on source files to print parsed AST nodes', 'review the Node subclasses like Class, Function, Method, Type, and Typedef for C++ AST structure', 'run the unittest suite to verify gmock_class generates correct mock macros from C++ source', 'test the _GenerateMethods function converts C++ class declarations into MOCK_METHOD macro lines', 'test the _GenerateMocks function produces complete Mock class source from C++ input', 'test that constructors and destructors are correctly ignored during mock method generation', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template parameters', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token string is a C++ builtin type using IsBuiltinType', 'list all C++ keywords from the ALL set constant', 'list all C++ type keywords from the TYPES set constant', 'list all C++ control flow keywords from the CONTROL set constant', 'run the C++ tokenizer on a source file to print all tokens with their types', 'create a generator that yields Token objects from C++ source code string input', 'build a Token data container with type, name, start, and end position attributes', 'review the _GetString helper that finds closing quotes while handling backslash escapes', 'summarize the token type constants UNKNOWN, SYNTAX, CONSTANT, NAME, and PREPROCESSOR', 'read the contents of a file and return the text or None on error', 'read a file silently without printing errors by setting print_error to False', 'review the ReadFile function that opens a file and returns its contents with error handling', 'summarize the ReadFile function which reads a file and handles IOError exceptions gracefully', 'test the ReadFile function by passing a filename and verifying it returns file contents or None']
```

Usage

```
{'test_gmock_class_generation': 'run the unittest suite to verify gmock_class generates correct mock macros from C++ source', 'test_generate_methods': 'test the _GenerateMethods function converts C++ class declarations into MOCK_METHOD macro lines', 'test_generate_mocks': 'test the _GenerateMocks function produces complete Mock class source from C++ input', 'test_constructor_destructor_filtering': 'test that constructors and destructors are correctly ignored during mock method generation', 'test_template_class_mocks': 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template parameters'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/googletest/googlemock/scripts/generator/cpp/keywords.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and Generate to yield parsed nodes', 'print all identifiers from a C++ source file filtered by a predicate function', 'print identifiers from multiple C++ source files using a shared predicate filter', 'run the C++ AST parser CLI on source files to print parsed AST nodes', 'review the Node subclasses like Class, Function, Method, Type, and Typedef for C++ AST structure', 'run the unittest suite to verify gmock_class generates correct mock macros from C++ source', 'test the _GenerateMethods function converts C++ class declarations into MOCK_METHOD macro lines', 'test the _GenerateMocks function produces complete Mock class source from C++ input', 'test that constructors and destructors are correctly ignored during mock method generation', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template parameters', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token string is a C++ builtin type using IsBuiltinType', 'list all C++ keywords from the ALL set constant', 'list all C++ type keywords from the TYPES set constant', 'list all C++ control flow keywords from the CONTROL set constant', 'run the C++ tokenizer on a source file to print all tokens with their types', 'create a generator that yields Token objects from C++ source code string input', 'build a Token data container with type, name, start, and end position attributes', 'review the _GetString helper that finds closing quotes while handling backslash escapes', 'summarize the token type constants UNKNOWN, SYNTAX, CONSTANT, NAME, and PREPROCESSOR', 'read the contents of a file and return the text or None on error', 'read a file silently without printing errors by setting print_error to False', 'review the ReadFile function that opens a file and returns its contents with error handling', 'summarize the ReadFile function which reads a file and handles IOError exceptions gracefully', 'test the ReadFile function by passing a filename and verifying it returns file contents or None']
```

Usage

```
{'check_IsKeyword': 'check if a given token string is a C++ keyword using IsKeyword', 'check_IsBuiltinType': 'check if a given token string is a C++ builtin type using IsBuiltinType', 'list_ALL_keywords': 'list all C++ keywords from the ALL set constant', 'list_TYPES': 'list all C++ type keywords from the TYPES set constant', 'list_CONTROL_keywords': 'list all C++ control flow keywords from the CONTROL set constant'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/googletest/googlemock/scripts/generator/cpp/tokenize.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and Generate to yield parsed nodes', 'print all identifiers from a C++ source file filtered by a predicate function', 'print identifiers from multiple C++ source files using a shared predicate filter', 'run the C++ AST parser CLI on source files to print parsed AST nodes', 'review the Node subclasses like Class, Function, Method, Type, and Typedef for C++ AST structure', 'run the unittest suite to verify gmock_class generates correct mock macros from C++ source', 'test the _GenerateMethods function converts C++ class declarations into MOCK_METHOD macro lines', 'test the _GenerateMocks function produces complete Mock class source from C++ input', 'test that constructors and destructors are correctly ignored during mock method generation', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template parameters', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token string is a C++ builtin type using IsBuiltinType', 'list all C++ keywords from the ALL set constant', 'list all C++ type keywords from the TYPES set constant', 'list all C++ control flow keywords from the CONTROL set constant', 'run the C++ tokenizer on a source file to print all tokens with their types', 'create a generator that yields Token objects from C++ source code string input', 'build a Token data container with type, name, start, and end position attributes', 'review the _GetString helper that finds closing quotes while handling backslash escapes', 'summarize the token type constants UNKNOWN, SYNTAX, CONSTANT, NAME, and PREPROCESSOR', 'read the contents of a file and return the text or None on error', 'read a file silently without printing errors by setting print_error to False', 'review the ReadFile function that opens a file and returns its contents with error handling', 'summarize the ReadFile function which reads a file and handles IOError exceptions gracefully', 'test the ReadFile function by passing a filename and verifying it returns file contents or None']
```

Usage

```
{'run_tokenize_cpp_source': 'run the C++ tokenizer on a source file to print all tokens with their types', 'create_GetTokens_generator': 'create a generator that yields Token objects from C++ source code string input', 'build_Token_class': 'build a Token data container with type, name, start, and end position attributes', 'review_GetString_escape_handling': 'review the _GetString helper that finds closing quotes while handling backslash escapes', 'summarize_token_types': 'summarize the token type constants UNKNOWN, SYNTAX, CONSTANT, NAME, and PREPROCESSOR'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/googletest/googlemock/scripts/generator/cpp/utils.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and Generate to yield parsed nodes', 'print all identifiers from a C++ source file filtered by a predicate function', 'print identifiers from multiple C++ source files using a shared predicate filter', 'run the C++ AST parser CLI on source files to print parsed AST nodes', 'review the Node subclasses like Class, Function, Method, Type, and Typedef for C++ AST structure', 'run the unittest suite to verify gmock_class generates correct mock macros from C++ source', 'test the _GenerateMethods function converts C++ class declarations into MOCK_METHOD macro lines', 'test the _GenerateMocks function produces complete Mock class source from C++ input', 'test that constructors and destructors are correctly ignored during mock method generation', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template parameters', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token string is a C++ builtin type using IsBuiltinType', 'list all C++ keywords from the ALL set constant', 'list all C++ type keywords from the TYPES set constant', 'list all C++ control flow keywords from the CONTROL set constant', 'run the C++ tokenizer on a source file to print all tokens with their types', 'create a generator that yields Token objects from C++ source code string input', 'build a Token data container with type, name, start, and end position attributes', 'review the _GetString helper that finds closing quotes while handling backslash escapes', 'summarize the token type constants UNKNOWN, SYNTAX, CONSTANT, NAME, and PREPROCESSOR', 'read the contents of a file and return the text or None on error', 'read a file silently without printing errors by setting print_error to False', 'review the ReadFile function that opens a file and returns its contents with error handling', 'summarize the ReadFile function which reads a file and handles IOError exceptions gracefully', 'test the ReadFile function by passing a filename and verifying it returns file contents or None']
```

Usage

```
{'read_file_contents': 'read the contents of a file and return the text or None on error', 'read_file_with_error_suppression': 'read a file silently without printing errors by setting print_error to False', 'review_ReadFile_function': 'review the ReadFile function that opens a file and returns its contents with error handling', 'summarize_ReadFile_function': 'summarize the ReadFile function which reads a file and handles IOError exceptions gracefully', 'test_ReadFile_function': 'test the ReadFile function by passing a filename and verifying it returns file contents or None'}
```

