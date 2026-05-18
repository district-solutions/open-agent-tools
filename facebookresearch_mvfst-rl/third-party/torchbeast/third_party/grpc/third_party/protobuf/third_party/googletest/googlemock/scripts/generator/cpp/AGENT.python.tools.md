# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/scripts/generator/cpp/ast.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over generated nodes', 'generate AST nodes from C++ source by calling AstBuilder.Generate() to yield class, function, and variable declarations', 'print all identifiers from a C++ source file filtered by a predicate function using PrintIndentifiers', 'print identifiers from multiple C++ source files using PrintAllIndentifiers with a filter predicate', 'convert a list of C++ tokens into Parameter AST nodes using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class mock generation from C++ source', 'test that virtual C++ methods are converted to MOCK_METHOD macros correctly', 'test that C++ classes are converted to Mock* classes with mock methods', 'test that constructors and destructors are ignored when generating mock methods', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template params', 'check if a given token string is a C++ keyword using the IsKeyword function', 'check if a given token string is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by importing the ALL set from the keywords module', 'list all C++ type keywords by importing the TYPES set from the keywords module', 'list all C++ control flow keywords by importing the CONTROL set from the keywords module', 'run GetTokens on a C++ source string to yield a sequence of Token objects', 'create a Token with a token_type, name, start index, and end index', 'run the script with a C++ filename argument to print all tokens to stdout', 'use _GetString to find the closing quote of a double-quoted string handling backslash escapes', 'use _GetChar to find the closing quote of a single-quoted char literal handling backslash escapes', 'read a file and return its contents as a string using ReadFile', 'read a file silently without printing errors by setting print_error to False', 'read a file and print an error message if the file cannot be opened', 'review the ReadFile function that opens a file and returns its contents or None on error', 'summarize the utils module which provides generic file reading utilities for C++ parsing']
```

Usage

```
{'build_cpp_ast_from_source': 'build an AST from C++ source code using BuilderFromSource and iterate over generated nodes', 'generate_cpp_ast_nodes': 'generate AST nodes from C++ source by calling AstBuilder.Generate() to yield class, function, and variable declarations', 'print_cpp_identifiers': 'print all identifiers from a C++ source file filtered by a predicate function using PrintIndentifiers', 'print_all_cpp_identifiers': 'print identifiers from multiple C++ source files using PrintAllIndentifiers with a filter predicate', 'convert_tokens_to_parameters': 'convert a list of C++ tokens into Parameter AST nodes using TypeConverter.ToParameters'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/scripts/generator/cpp/gmock_class_test.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over generated nodes', 'generate AST nodes from C++ source by calling AstBuilder.Generate() to yield class, function, and variable declarations', 'print all identifiers from a C++ source file filtered by a predicate function using PrintIndentifiers', 'print identifiers from multiple C++ source files using PrintAllIndentifiers with a filter predicate', 'convert a list of C++ tokens into Parameter AST nodes using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class mock generation from C++ source', 'test that virtual C++ methods are converted to MOCK_METHOD macros correctly', 'test that C++ classes are converted to Mock* classes with mock methods', 'test that constructors and destructors are ignored when generating mock methods', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template params', 'check if a given token string is a C++ keyword using the IsKeyword function', 'check if a given token string is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by importing the ALL set from the keywords module', 'list all C++ type keywords by importing the TYPES set from the keywords module', 'list all C++ control flow keywords by importing the CONTROL set from the keywords module', 'run GetTokens on a C++ source string to yield a sequence of Token objects', 'create a Token with a token_type, name, start index, and end index', 'run the script with a C++ filename argument to print all tokens to stdout', 'use _GetString to find the closing quote of a double-quoted string handling backslash escapes', 'use _GetChar to find the closing quote of a single-quoted char literal handling backslash escapes', 'read a file and return its contents as a string using ReadFile', 'read a file silently without printing errors by setting print_error to False', 'read a file and print an error message if the file cannot be opened', 'review the ReadFile function that opens a file and returns its contents or None on error', 'summarize the utils module which provides generic file reading utilities for C++ parsing']
```

Usage

```
{'run_gmock_class_tests': 'run the unittest test suite for gmock_class mock generation from C++ source', 'test_generate_mock_methods': 'test that virtual C++ methods are converted to MOCK_METHOD macros correctly', 'test_generate_mock_classes': 'test that C++ classes are converted to Mock* classes with mock methods', 'test_constructor_destructor_filtering': 'test that constructors and destructors are ignored when generating mock methods', 'test_template_class_mock_generation': 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template params'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/scripts/generator/cpp/keywords.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over generated nodes', 'generate AST nodes from C++ source by calling AstBuilder.Generate() to yield class, function, and variable declarations', 'print all identifiers from a C++ source file filtered by a predicate function using PrintIndentifiers', 'print identifiers from multiple C++ source files using PrintAllIndentifiers with a filter predicate', 'convert a list of C++ tokens into Parameter AST nodes using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class mock generation from C++ source', 'test that virtual C++ methods are converted to MOCK_METHOD macros correctly', 'test that C++ classes are converted to Mock* classes with mock methods', 'test that constructors and destructors are ignored when generating mock methods', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template params', 'check if a given token string is a C++ keyword using the IsKeyword function', 'check if a given token string is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by importing the ALL set from the keywords module', 'list all C++ type keywords by importing the TYPES set from the keywords module', 'list all C++ control flow keywords by importing the CONTROL set from the keywords module', 'run GetTokens on a C++ source string to yield a sequence of Token objects', 'create a Token with a token_type, name, start index, and end index', 'run the script with a C++ filename argument to print all tokens to stdout', 'use _GetString to find the closing quote of a double-quoted string handling backslash escapes', 'use _GetChar to find the closing quote of a single-quoted char literal handling backslash escapes', 'read a file and return its contents as a string using ReadFile', 'read a file silently without printing errors by setting print_error to False', 'read a file and print an error message if the file cannot be opened', 'review the ReadFile function that opens a file and returns its contents or None on error', 'summarize the utils module which provides generic file reading utilities for C++ parsing']
```

Usage

```
{'check_IsKeyword': 'check if a given token string is a C++ keyword using the IsKeyword function', 'check_IsBuiltinType': 'check if a given token string is a C++ builtin type using the IsBuiltinType function', 'list_ALL_keywords': 'list all C++ keywords by importing the ALL set from the keywords module', 'list_TYPES': 'list all C++ type keywords by importing the TYPES set from the keywords module', 'list_CONTROL': 'list all C++ control flow keywords by importing the CONTROL set from the keywords module'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/scripts/generator/cpp/tokenize.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over generated nodes', 'generate AST nodes from C++ source by calling AstBuilder.Generate() to yield class, function, and variable declarations', 'print all identifiers from a C++ source file filtered by a predicate function using PrintIndentifiers', 'print identifiers from multiple C++ source files using PrintAllIndentifiers with a filter predicate', 'convert a list of C++ tokens into Parameter AST nodes using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class mock generation from C++ source', 'test that virtual C++ methods are converted to MOCK_METHOD macros correctly', 'test that C++ classes are converted to Mock* classes with mock methods', 'test that constructors and destructors are ignored when generating mock methods', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template params', 'check if a given token string is a C++ keyword using the IsKeyword function', 'check if a given token string is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by importing the ALL set from the keywords module', 'list all C++ type keywords by importing the TYPES set from the keywords module', 'list all C++ control flow keywords by importing the CONTROL set from the keywords module', 'run GetTokens on a C++ source string to yield a sequence of Token objects', 'create a Token with a token_type, name, start index, and end index', 'run the script with a C++ filename argument to print all tokens to stdout', 'use _GetString to find the closing quote of a double-quoted string handling backslash escapes', 'use _GetChar to find the closing quote of a single-quoted char literal handling backslash escapes', 'read a file and return its contents as a string using ReadFile', 'read a file silently without printing errors by setting print_error to False', 'read a file and print an error message if the file cannot be opened', 'review the ReadFile function that opens a file and returns its contents or None on error', 'summarize the utils module which provides generic file reading utilities for C++ parsing']
```

Usage

```
{'tokenize_cpp_source': 'run GetTokens on a C++ source string to yield a sequence of Token objects', 'create_token_object': 'create a Token with a token_type, name, start index, and end index', 'run_cli_tokenizer': 'run the script with a C++ filename argument to print all tokens to stdout', 'extract_string_literal_end': 'use _GetString to find the closing quote of a double-quoted string handling backslash escapes', 'extract_char_literal_end': 'use _GetChar to find the closing quote of a single-quoted char literal handling backslash escapes'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/scripts/generator/cpp/utils.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over generated nodes', 'generate AST nodes from C++ source by calling AstBuilder.Generate() to yield class, function, and variable declarations', 'print all identifiers from a C++ source file filtered by a predicate function using PrintIndentifiers', 'print identifiers from multiple C++ source files using PrintAllIndentifiers with a filter predicate', 'convert a list of C++ tokens into Parameter AST nodes using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class mock generation from C++ source', 'test that virtual C++ methods are converted to MOCK_METHOD macros correctly', 'test that C++ classes are converted to Mock* classes with mock methods', 'test that constructors and destructors are ignored when generating mock methods', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template params', 'check if a given token string is a C++ keyword using the IsKeyword function', 'check if a given token string is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by importing the ALL set from the keywords module', 'list all C++ type keywords by importing the TYPES set from the keywords module', 'list all C++ control flow keywords by importing the CONTROL set from the keywords module', 'run GetTokens on a C++ source string to yield a sequence of Token objects', 'create a Token with a token_type, name, start index, and end index', 'run the script with a C++ filename argument to print all tokens to stdout', 'use _GetString to find the closing quote of a double-quoted string handling backslash escapes', 'use _GetChar to find the closing quote of a single-quoted char literal handling backslash escapes', 'read a file and return its contents as a string using ReadFile', 'read a file silently without printing errors by setting print_error to False', 'read a file and print an error message if the file cannot be opened', 'review the ReadFile function that opens a file and returns its contents or None on error', 'summarize the utils module which provides generic file reading utilities for C++ parsing']
```

Usage

```
{'read_file_contents': 'read a file and return its contents as a string using ReadFile', 'read_file_with_error_suppression': 'read a file silently without printing errors by setting print_error to False', 'read_file_with_error_printing': 'read a file and print an error message if the file cannot be opened', 'review_ReadFile_function': 'review the ReadFile function that opens a file and returns its contents or None on error', 'summarize_utils_module': 'summarize the utils module which provides generic file reading utilities for C++ parsing'}
```

