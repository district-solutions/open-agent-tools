# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/scripts/generator/cpp/ast.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over generated nodes', 'generate AST nodes from a C++ token stream using AstBuilder.Generate as a generator', 'extract and print identifiers from a C++ source file using PrintIndentifiers with a predicate', 'parse C++ class definitions and method signatures into Class and Method AST nodes', 'process one or more C++ files via the CLI main function and print the full AST', 'run the unittest test suite for gmock_class C++ mock generator', 'test that C++ virtual methods are converted to MOCK_METHOD macros', 'test that C++ classes are converted to full Mock class source', 'test that constructors and destructors are ignored when generating mock methods', 'test that templated C++ classes generate MOCK_METHOD_T macros correctly', 'check if a given token is a C++ keyword using the IsKeyword function', 'check if a given token is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by importing and printing the ALL set from keywords module', 'list all C++ type keywords by importing and printing the TYPES set from keywords module', 'list all C++ control flow keywords by importing and printing the CONTROL set from keywords module', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'create a generator that yields Token objects for each token found in C++ source code', 'build a Token data container with token_type, name, start index, and end index attributes', 'summarize the _GetString helper that finds the closing quote of a double-quoted string handling backslash escapes', 'review the _GetChar helper that finds the closing quote of a single-quoted char literal handling backslash escapes', 'read the contents of a file and return the text or None on error', 'read a file silently without printing errors when the file is missing', 'review the ReadFile function that opens a file and returns its contents with error handling', 'summarize the ReadFile utility that reads a file and handles IOError exceptions gracefully', 'test the ReadFile function by reading an existing file and verifying the returned contents']
```

Usage

```
{'build_ast_from_cpp_source': 'build an AST from C++ source code using BuilderFromSource and iterate over generated nodes', 'generate_ast_nodes': 'generate AST nodes from a C++ token stream using AstBuilder.Generate as a generator', 'extract_cpp_identifiers': 'extract and print identifiers from a C++ source file using PrintIndentifiers with a predicate', 'parse_cpp_classes_and_methods': 'parse C++ class definitions and method signatures into Class and Method AST nodes', 'process_cpp_files_cli': 'process one or more C++ files via the CLI main function and print the full AST'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/scripts/generator/cpp/gmock_class_test.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over generated nodes', 'generate AST nodes from a C++ token stream using AstBuilder.Generate as a generator', 'extract and print identifiers from a C++ source file using PrintIndentifiers with a predicate', 'parse C++ class definitions and method signatures into Class and Method AST nodes', 'process one or more C++ files via the CLI main function and print the full AST', 'run the unittest test suite for gmock_class C++ mock generator', 'test that C++ virtual methods are converted to MOCK_METHOD macros', 'test that C++ classes are converted to full Mock class source', 'test that constructors and destructors are ignored when generating mock methods', 'test that templated C++ classes generate MOCK_METHOD_T macros correctly', 'check if a given token is a C++ keyword using the IsKeyword function', 'check if a given token is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by importing and printing the ALL set from keywords module', 'list all C++ type keywords by importing and printing the TYPES set from keywords module', 'list all C++ control flow keywords by importing and printing the CONTROL set from keywords module', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'create a generator that yields Token objects for each token found in C++ source code', 'build a Token data container with token_type, name, start index, and end index attributes', 'summarize the _GetString helper that finds the closing quote of a double-quoted string handling backslash escapes', 'review the _GetChar helper that finds the closing quote of a single-quoted char literal handling backslash escapes', 'read the contents of a file and return the text or None on error', 'read a file silently without printing errors when the file is missing', 'review the ReadFile function that opens a file and returns its contents with error handling', 'summarize the ReadFile utility that reads a file and handles IOError exceptions gracefully', 'test the ReadFile function by reading an existing file and verifying the returned contents']
```

Usage

```
{'run_gmock_class_tests': 'run the unittest test suite for gmock_class C++ mock generator', 'test_generate_mock_methods': 'test that C++ virtual methods are converted to MOCK_METHOD macros', 'test_generate_mock_classes': 'test that C++ classes are converted to full Mock class source', 'test_constructor_destructor_filtering': 'test that constructors and destructors are ignored when generating mock methods', 'test_template_class_generation': 'test that templated C++ classes generate MOCK_METHOD_T macros correctly'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/scripts/generator/cpp/keywords.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over generated nodes', 'generate AST nodes from a C++ token stream using AstBuilder.Generate as a generator', 'extract and print identifiers from a C++ source file using PrintIndentifiers with a predicate', 'parse C++ class definitions and method signatures into Class and Method AST nodes', 'process one or more C++ files via the CLI main function and print the full AST', 'run the unittest test suite for gmock_class C++ mock generator', 'test that C++ virtual methods are converted to MOCK_METHOD macros', 'test that C++ classes are converted to full Mock class source', 'test that constructors and destructors are ignored when generating mock methods', 'test that templated C++ classes generate MOCK_METHOD_T macros correctly', 'check if a given token is a C++ keyword using the IsKeyword function', 'check if a given token is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by importing and printing the ALL set from keywords module', 'list all C++ type keywords by importing and printing the TYPES set from keywords module', 'list all C++ control flow keywords by importing and printing the CONTROL set from keywords module', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'create a generator that yields Token objects for each token found in C++ source code', 'build a Token data container with token_type, name, start index, and end index attributes', 'summarize the _GetString helper that finds the closing quote of a double-quoted string handling backslash escapes', 'review the _GetChar helper that finds the closing quote of a single-quoted char literal handling backslash escapes', 'read the contents of a file and return the text or None on error', 'read a file silently without printing errors when the file is missing', 'review the ReadFile function that opens a file and returns its contents with error handling', 'summarize the ReadFile utility that reads a file and handles IOError exceptions gracefully', 'test the ReadFile function by reading an existing file and verifying the returned contents']
```

Usage

```
{'check_IsKeyword': 'check if a given token is a C++ keyword using the IsKeyword function', 'check_IsBuiltinType': 'check if a given token is a C++ builtin type using the IsBuiltinType function', 'list_ALL_keywords': 'list all C++ keywords by importing and printing the ALL set from keywords module', 'list_TYPES': 'list all C++ type keywords by importing and printing the TYPES set from keywords module', 'list_CONTROL_keywords': 'list all C++ control flow keywords by importing and printing the CONTROL set from keywords module'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/scripts/generator/cpp/tokenize.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over generated nodes', 'generate AST nodes from a C++ token stream using AstBuilder.Generate as a generator', 'extract and print identifiers from a C++ source file using PrintIndentifiers with a predicate', 'parse C++ class definitions and method signatures into Class and Method AST nodes', 'process one or more C++ files via the CLI main function and print the full AST', 'run the unittest test suite for gmock_class C++ mock generator', 'test that C++ virtual methods are converted to MOCK_METHOD macros', 'test that C++ classes are converted to full Mock class source', 'test that constructors and destructors are ignored when generating mock methods', 'test that templated C++ classes generate MOCK_METHOD_T macros correctly', 'check if a given token is a C++ keyword using the IsKeyword function', 'check if a given token is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by importing and printing the ALL set from keywords module', 'list all C++ type keywords by importing and printing the TYPES set from keywords module', 'list all C++ control flow keywords by importing and printing the CONTROL set from keywords module', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'create a generator that yields Token objects for each token found in C++ source code', 'build a Token data container with token_type, name, start index, and end index attributes', 'summarize the _GetString helper that finds the closing quote of a double-quoted string handling backslash escapes', 'review the _GetChar helper that finds the closing quote of a single-quoted char literal handling backslash escapes', 'read the contents of a file and return the text or None on error', 'read a file silently without printing errors when the file is missing', 'review the ReadFile function that opens a file and returns its contents with error handling', 'summarize the ReadFile utility that reads a file and handles IOError exceptions gracefully', 'test the ReadFile function by reading an existing file and verifying the returned contents']
```

Usage

```
{'run_tokenize_cpp_source': 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'create_GetTokens_generator': 'create a generator that yields Token objects for each token found in C++ source code', 'build_Token_class': 'build a Token data container with token_type, name, start index, and end index attributes', 'summarize_GetString_helper': 'summarize the _GetString helper that finds the closing quote of a double-quoted string handling backslash escapes', 'review_GetChar_helper': 'review the _GetChar helper that finds the closing quote of a single-quoted char literal handling backslash escapes'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/scripts/generator/cpp/utils.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over generated nodes', 'generate AST nodes from a C++ token stream using AstBuilder.Generate as a generator', 'extract and print identifiers from a C++ source file using PrintIndentifiers with a predicate', 'parse C++ class definitions and method signatures into Class and Method AST nodes', 'process one or more C++ files via the CLI main function and print the full AST', 'run the unittest test suite for gmock_class C++ mock generator', 'test that C++ virtual methods are converted to MOCK_METHOD macros', 'test that C++ classes are converted to full Mock class source', 'test that constructors and destructors are ignored when generating mock methods', 'test that templated C++ classes generate MOCK_METHOD_T macros correctly', 'check if a given token is a C++ keyword using the IsKeyword function', 'check if a given token is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by importing and printing the ALL set from keywords module', 'list all C++ type keywords by importing and printing the TYPES set from keywords module', 'list all C++ control flow keywords by importing and printing the CONTROL set from keywords module', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'create a generator that yields Token objects for each token found in C++ source code', 'build a Token data container with token_type, name, start index, and end index attributes', 'summarize the _GetString helper that finds the closing quote of a double-quoted string handling backslash escapes', 'review the _GetChar helper that finds the closing quote of a single-quoted char literal handling backslash escapes', 'read the contents of a file and return the text or None on error', 'read a file silently without printing errors when the file is missing', 'review the ReadFile function that opens a file and returns its contents with error handling', 'summarize the ReadFile utility that reads a file and handles IOError exceptions gracefully', 'test the ReadFile function by reading an existing file and verifying the returned contents']
```

Usage

```
{'read_file_contents': 'read the contents of a file and return the text or None on error', 'read_file_with_error_suppressed': 'read a file silently without printing errors when the file is missing', 'review_ReadFile': 'review the ReadFile function that opens a file and returns its contents with error handling', 'summarize_ReadFile': 'summarize the ReadFile utility that reads a file and handles IOError exceptions gracefully', 'test_ReadFile': 'test the ReadFile function by reading an existing file and verifying the returned contents'}
```

