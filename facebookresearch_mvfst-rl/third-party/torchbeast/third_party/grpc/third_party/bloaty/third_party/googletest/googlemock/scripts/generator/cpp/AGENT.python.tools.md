# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/bloaty/third_party/googletest/googlemock/scripts/generator/cpp/ast.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over generated nodes', 'parse a C++ file and print all identifiers matching a predicate using PrintIndentifiers', 'parse multiple C++ files and print identifiers matching a predicate using PrintAllIndentifiers', 'run the AST builder on C++ source files via the main entry point with sys.argv', 'review the Node subclasses like Class, Function, Method, Type, and Typedef for C++ AST representation', 'run the unittest suite that tests gmock_class C++ to Google Mock code generation', 'test the _GenerateMethods function that converts C++ virtual methods to MOCK_METHOD macros', 'test the _GenerateMocks function that generates complete Mock class source from C++ headers', 'test the ast.BuilderFromSource parser that builds an AST from C++ source code strings', 'test MOCK_METHOD generation for const methods, templated classes, default parameters, and template types', 'check if a given token is a C++ keyword using the IsKeyword function', 'check if a given token is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by importing and printing the ALL set from the module', 'list all C++ type keywords by importing and printing the TYPES set from the module', 'list all C++ control flow keywords by importing and printing the CONTROL set from the module', 'run the C++ tokenizer on a source file and print each token type and name', 'create a Token object with a token type, name, start index, and end index', 'summarize the GetTokens generator that yields Token objects from C++ source code', 'review the _GetString and _GetChar helpers that handle escaped quotes in literals', 'test the token type constants UNKNOWN, SYNTAX, CONSTANT, NAME, and PREPROCESSOR', 'read a file and return its contents as a string using ReadFile', 'read a file silently without printing errors by passing print_error=False to ReadFile', 'read a file and print IOError messages by calling ReadFile with print_error=True', 'summarize the ReadFile function which opens a file, reads its contents, and handles IOError exceptions', 'review the ReadFile function for proper file handle cleanup and error handling']
```

Usage

```
{'build_cpp_ast_from_source': 'build an AST from C++ source code using BuilderFromSource and iterate over generated nodes', 'parse_cpp_file_identifiers': 'parse a C++ file and print all identifiers matching a predicate using PrintIndentifiers', 'parse_multiple_cpp_files': 'parse multiple C++ files and print identifiers matching a predicate using PrintAllIndentifiers', 'run_ast_builder_on_files': 'run the AST builder on C++ source files via the main entry point with sys.argv', 'review_ast_node_classes': 'review the Node subclasses like Class, Function, Method, Type, and Typedef for C++ AST representation'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/bloaty/third_party/googletest/googlemock/scripts/generator/cpp/gmock_class_test.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over generated nodes', 'parse a C++ file and print all identifiers matching a predicate using PrintIndentifiers', 'parse multiple C++ files and print identifiers matching a predicate using PrintAllIndentifiers', 'run the AST builder on C++ source files via the main entry point with sys.argv', 'review the Node subclasses like Class, Function, Method, Type, and Typedef for C++ AST representation', 'run the unittest suite that tests gmock_class C++ to Google Mock code generation', 'test the _GenerateMethods function that converts C++ virtual methods to MOCK_METHOD macros', 'test the _GenerateMocks function that generates complete Mock class source from C++ headers', 'test the ast.BuilderFromSource parser that builds an AST from C++ source code strings', 'test MOCK_METHOD generation for const methods, templated classes, default parameters, and template types', 'check if a given token is a C++ keyword using the IsKeyword function', 'check if a given token is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by importing and printing the ALL set from the module', 'list all C++ type keywords by importing and printing the TYPES set from the module', 'list all C++ control flow keywords by importing and printing the CONTROL set from the module', 'run the C++ tokenizer on a source file and print each token type and name', 'create a Token object with a token type, name, start index, and end index', 'summarize the GetTokens generator that yields Token objects from C++ source code', 'review the _GetString and _GetChar helpers that handle escaped quotes in literals', 'test the token type constants UNKNOWN, SYNTAX, CONSTANT, NAME, and PREPROCESSOR', 'read a file and return its contents as a string using ReadFile', 'read a file silently without printing errors by passing print_error=False to ReadFile', 'read a file and print IOError messages by calling ReadFile with print_error=True', 'summarize the ReadFile function which opens a file, reads its contents, and handles IOError exceptions', 'review the ReadFile function for proper file handle cleanup and error handling']
```

Usage

```
{'test_gmock_class_generation': 'run the unittest suite that tests gmock_class C++ to Google Mock code generation', 'test_generate_mock_methods': 'test the _GenerateMethods function that converts C++ virtual methods to MOCK_METHOD macros', 'test_generate_full_mocks': 'test the _GenerateMocks function that generates complete Mock class source from C++ headers', 'test_ast_builder_from_source': 'test the ast.BuilderFromSource parser that builds an AST from C++ source code strings', 'test_mock_method_variants': 'test MOCK_METHOD generation for const methods, templated classes, default parameters, and template types'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/bloaty/third_party/googletest/googlemock/scripts/generator/cpp/keywords.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over generated nodes', 'parse a C++ file and print all identifiers matching a predicate using PrintIndentifiers', 'parse multiple C++ files and print identifiers matching a predicate using PrintAllIndentifiers', 'run the AST builder on C++ source files via the main entry point with sys.argv', 'review the Node subclasses like Class, Function, Method, Type, and Typedef for C++ AST representation', 'run the unittest suite that tests gmock_class C++ to Google Mock code generation', 'test the _GenerateMethods function that converts C++ virtual methods to MOCK_METHOD macros', 'test the _GenerateMocks function that generates complete Mock class source from C++ headers', 'test the ast.BuilderFromSource parser that builds an AST from C++ source code strings', 'test MOCK_METHOD generation for const methods, templated classes, default parameters, and template types', 'check if a given token is a C++ keyword using the IsKeyword function', 'check if a given token is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by importing and printing the ALL set from the module', 'list all C++ type keywords by importing and printing the TYPES set from the module', 'list all C++ control flow keywords by importing and printing the CONTROL set from the module', 'run the C++ tokenizer on a source file and print each token type and name', 'create a Token object with a token type, name, start index, and end index', 'summarize the GetTokens generator that yields Token objects from C++ source code', 'review the _GetString and _GetChar helpers that handle escaped quotes in literals', 'test the token type constants UNKNOWN, SYNTAX, CONSTANT, NAME, and PREPROCESSOR', 'read a file and return its contents as a string using ReadFile', 'read a file silently without printing errors by passing print_error=False to ReadFile', 'read a file and print IOError messages by calling ReadFile with print_error=True', 'summarize the ReadFile function which opens a file, reads its contents, and handles IOError exceptions', 'review the ReadFile function for proper file handle cleanup and error handling']
```

Usage

```
{'check_IsKeyword': 'check if a given token is a C++ keyword using the IsKeyword function', 'check_IsBuiltinType': 'check if a given token is a C++ builtin type using the IsBuiltinType function', 'list_ALL_keywords': 'list all C++ keywords by importing and printing the ALL set from the module', 'list_TYPES': 'list all C++ type keywords by importing and printing the TYPES set from the module', 'list_CONTROL_keywords': 'list all C++ control flow keywords by importing and printing the CONTROL set from the module'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/bloaty/third_party/googletest/googlemock/scripts/generator/cpp/tokenize.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over generated nodes', 'parse a C++ file and print all identifiers matching a predicate using PrintIndentifiers', 'parse multiple C++ files and print identifiers matching a predicate using PrintAllIndentifiers', 'run the AST builder on C++ source files via the main entry point with sys.argv', 'review the Node subclasses like Class, Function, Method, Type, and Typedef for C++ AST representation', 'run the unittest suite that tests gmock_class C++ to Google Mock code generation', 'test the _GenerateMethods function that converts C++ virtual methods to MOCK_METHOD macros', 'test the _GenerateMocks function that generates complete Mock class source from C++ headers', 'test the ast.BuilderFromSource parser that builds an AST from C++ source code strings', 'test MOCK_METHOD generation for const methods, templated classes, default parameters, and template types', 'check if a given token is a C++ keyword using the IsKeyword function', 'check if a given token is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by importing and printing the ALL set from the module', 'list all C++ type keywords by importing and printing the TYPES set from the module', 'list all C++ control flow keywords by importing and printing the CONTROL set from the module', 'run the C++ tokenizer on a source file and print each token type and name', 'create a Token object with a token type, name, start index, and end index', 'summarize the GetTokens generator that yields Token objects from C++ source code', 'review the _GetString and _GetChar helpers that handle escaped quotes in literals', 'test the token type constants UNKNOWN, SYNTAX, CONSTANT, NAME, and PREPROCESSOR', 'read a file and return its contents as a string using ReadFile', 'read a file silently without printing errors by passing print_error=False to ReadFile', 'read a file and print IOError messages by calling ReadFile with print_error=True', 'summarize the ReadFile function which opens a file, reads its contents, and handles IOError exceptions', 'review the ReadFile function for proper file handle cleanup and error handling']
```

Usage

```
{'run_tokenize_cpp_file': 'run the C++ tokenizer on a source file and print each token type and name', 'create_token_object': 'create a Token object with a token type, name, start index, and end index', 'summarize_gettokens_generator': 'summarize the GetTokens generator that yields Token objects from C++ source code', 'review_string_parsing_helpers': 'review the _GetString and _GetChar helpers that handle escaped quotes in literals', 'test_tokenizer_constants': 'test the token type constants UNKNOWN, SYNTAX, CONSTANT, NAME, and PREPROCESSOR'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/bloaty/third_party/googletest/googlemock/scripts/generator/cpp/utils.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over generated nodes', 'parse a C++ file and print all identifiers matching a predicate using PrintIndentifiers', 'parse multiple C++ files and print identifiers matching a predicate using PrintAllIndentifiers', 'run the AST builder on C++ source files via the main entry point with sys.argv', 'review the Node subclasses like Class, Function, Method, Type, and Typedef for C++ AST representation', 'run the unittest suite that tests gmock_class C++ to Google Mock code generation', 'test the _GenerateMethods function that converts C++ virtual methods to MOCK_METHOD macros', 'test the _GenerateMocks function that generates complete Mock class source from C++ headers', 'test the ast.BuilderFromSource parser that builds an AST from C++ source code strings', 'test MOCK_METHOD generation for const methods, templated classes, default parameters, and template types', 'check if a given token is a C++ keyword using the IsKeyword function', 'check if a given token is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by importing and printing the ALL set from the module', 'list all C++ type keywords by importing and printing the TYPES set from the module', 'list all C++ control flow keywords by importing and printing the CONTROL set from the module', 'run the C++ tokenizer on a source file and print each token type and name', 'create a Token object with a token type, name, start index, and end index', 'summarize the GetTokens generator that yields Token objects from C++ source code', 'review the _GetString and _GetChar helpers that handle escaped quotes in literals', 'test the token type constants UNKNOWN, SYNTAX, CONSTANT, NAME, and PREPROCESSOR', 'read a file and return its contents as a string using ReadFile', 'read a file silently without printing errors by passing print_error=False to ReadFile', 'read a file and print IOError messages by calling ReadFile with print_error=True', 'summarize the ReadFile function which opens a file, reads its contents, and handles IOError exceptions', 'review the ReadFile function for proper file handle cleanup and error handling']
```

Usage

```
{'read_file_contents': 'read a file and return its contents as a string using ReadFile', 'read_file_with_error_suppression': 'read a file silently without printing errors by passing print_error=False to ReadFile', 'read_file_with_error_printing': 'read a file and print IOError messages by calling ReadFile with print_error=True', 'summarize_ReadFile': 'summarize the ReadFile function which opens a file, reads its contents, and handles IOError exceptions', 'review_ReadFile': 'review the ReadFile function for proper file handle cleanup and error handling'}
```

