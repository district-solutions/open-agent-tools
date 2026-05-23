# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/third_party/googletest/googlemock/scripts/generator/cpp/ast.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse C++ source code into an AST by calling BuilderFromSource with source string and filename', 'print all identifiers from a C++ file using PrintIndentifiers with a predicate filter function', 'convert a list of C++ tokens into Type AST nodes using TypeConverter.ToType', 'convert C++ function parameter tokens into Parameter AST nodes using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class C++ mock generation', 'test that simple virtual C++ methods are converted to MOCK_METHOD0 macros', 'test that constructors and destructors are ignored during mock method generation', 'test that generated mock classes preserve C++ namespace structure', 'test that templated C++ classes are converted to MOCK_METHOD_T macros', 'check if a given token is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords available in the ALL set', 'list all C++ type keywords available in the TYPES set', 'list all C++ control flow keywords available in the CONTROL set', 'run the C++ tokenizer on a source file to extract all tokens with their types and positions', 'create a Token object with a token type, name, start index, and end index for C++ code analysis', 'extract string literal tokens from C++ source code handling escape sequences and backslashes', 'extract character literal tokens from C++ source code handling escape sequences and single quotes', 'parse C++ preprocessor directives including conditional compilation blocks and include statements', 'create a function that reads a file and returns its contents using ReadFile', 'create a function that reads a file and prints errors on IOError using ReadFile', 'create a function that reads a file without printing errors by passing print_error=False to ReadFile', 'review the ReadFile function to understand its file reading and error handling behavior', 'summarize the utils module which provides generic C++ parsing utilities including ReadFile']
```

Usage

```
{'build_cpp_ast': 'build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse_cpp_source': 'parse C++ source code into an AST by calling BuilderFromSource with source string and filename', 'print_cpp_identifiers': 'print all identifiers from a C++ file using PrintIndentifiers with a predicate filter function', 'convert_tokens_to_type': 'convert a list of C++ tokens into Type AST nodes using TypeConverter.ToType', 'convert_tokens_to_parameters': 'convert C++ function parameter tokens into Parameter AST nodes using TypeConverter.ToParameters'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/googletest/googlemock/scripts/generator/cpp/gmock_class_test.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse C++ source code into an AST by calling BuilderFromSource with source string and filename', 'print all identifiers from a C++ file using PrintIndentifiers with a predicate filter function', 'convert a list of C++ tokens into Type AST nodes using TypeConverter.ToType', 'convert C++ function parameter tokens into Parameter AST nodes using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class C++ mock generation', 'test that simple virtual C++ methods are converted to MOCK_METHOD0 macros', 'test that constructors and destructors are ignored during mock method generation', 'test that generated mock classes preserve C++ namespace structure', 'test that templated C++ classes are converted to MOCK_METHOD_T macros', 'check if a given token is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords available in the ALL set', 'list all C++ type keywords available in the TYPES set', 'list all C++ control flow keywords available in the CONTROL set', 'run the C++ tokenizer on a source file to extract all tokens with their types and positions', 'create a Token object with a token type, name, start index, and end index for C++ code analysis', 'extract string literal tokens from C++ source code handling escape sequences and backslashes', 'extract character literal tokens from C++ source code handling escape sequences and single quotes', 'parse C++ preprocessor directives including conditional compilation blocks and include statements', 'create a function that reads a file and returns its contents using ReadFile', 'create a function that reads a file and prints errors on IOError using ReadFile', 'create a function that reads a file without printing errors by passing print_error=False to ReadFile', 'review the ReadFile function to understand its file reading and error handling behavior', 'summarize the utils module which provides generic C++ parsing utilities including ReadFile']
```

Usage

```
{'run_gmock_class_tests': 'run the unittest test suite for gmock_class C++ mock generation', 'test_generate_methods_simple': 'test that simple virtual C++ methods are converted to MOCK_METHOD0 macros', 'test_generate_methods_constructors': 'test that constructors and destructors are ignored during mock method generation', 'test_generate_mocks_namespaces': 'test that generated mock classes preserve C++ namespace structure', 'test_generate_mocks_templates': 'test that templated C++ classes are converted to MOCK_METHOD_T macros'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/googletest/googlemock/scripts/generator/cpp/keywords.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse C++ source code into an AST by calling BuilderFromSource with source string and filename', 'print all identifiers from a C++ file using PrintIndentifiers with a predicate filter function', 'convert a list of C++ tokens into Type AST nodes using TypeConverter.ToType', 'convert C++ function parameter tokens into Parameter AST nodes using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class C++ mock generation', 'test that simple virtual C++ methods are converted to MOCK_METHOD0 macros', 'test that constructors and destructors are ignored during mock method generation', 'test that generated mock classes preserve C++ namespace structure', 'test that templated C++ classes are converted to MOCK_METHOD_T macros', 'check if a given token is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords available in the ALL set', 'list all C++ type keywords available in the TYPES set', 'list all C++ control flow keywords available in the CONTROL set', 'run the C++ tokenizer on a source file to extract all tokens with their types and positions', 'create a Token object with a token type, name, start index, and end index for C++ code analysis', 'extract string literal tokens from C++ source code handling escape sequences and backslashes', 'extract character literal tokens from C++ source code handling escape sequences and single quotes', 'parse C++ preprocessor directives including conditional compilation blocks and include statements', 'create a function that reads a file and returns its contents using ReadFile', 'create a function that reads a file and prints errors on IOError using ReadFile', 'create a function that reads a file without printing errors by passing print_error=False to ReadFile', 'review the ReadFile function to understand its file reading and error handling behavior', 'summarize the utils module which provides generic C++ parsing utilities including ReadFile']
```

Usage

```
{'check_IsKeyword': 'check if a given token is a C++ keyword using IsKeyword', 'check_IsBuiltinType': 'check if a given token is a C++ builtin type using IsBuiltinType', 'list_ALL_keywords': 'list all C++ keywords available in the ALL set', 'list_TYPES': 'list all C++ type keywords available in the TYPES set', 'list_CONTROL_keywords': 'list all C++ control flow keywords available in the CONTROL set'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/googletest/googlemock/scripts/generator/cpp/tokenize.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse C++ source code into an AST by calling BuilderFromSource with source string and filename', 'print all identifiers from a C++ file using PrintIndentifiers with a predicate filter function', 'convert a list of C++ tokens into Type AST nodes using TypeConverter.ToType', 'convert C++ function parameter tokens into Parameter AST nodes using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class C++ mock generation', 'test that simple virtual C++ methods are converted to MOCK_METHOD0 macros', 'test that constructors and destructors are ignored during mock method generation', 'test that generated mock classes preserve C++ namespace structure', 'test that templated C++ classes are converted to MOCK_METHOD_T macros', 'check if a given token is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords available in the ALL set', 'list all C++ type keywords available in the TYPES set', 'list all C++ control flow keywords available in the CONTROL set', 'run the C++ tokenizer on a source file to extract all tokens with their types and positions', 'create a Token object with a token type, name, start index, and end index for C++ code analysis', 'extract string literal tokens from C++ source code handling escape sequences and backslashes', 'extract character literal tokens from C++ source code handling escape sequences and single quotes', 'parse C++ preprocessor directives including conditional compilation blocks and include statements', 'create a function that reads a file and returns its contents using ReadFile', 'create a function that reads a file and prints errors on IOError using ReadFile', 'create a function that reads a file without printing errors by passing print_error=False to ReadFile', 'review the ReadFile function to understand its file reading and error handling behavior', 'summarize the utils module which provides generic C++ parsing utilities including ReadFile']
```

Usage

```
{'tokenize_cpp_source': 'run the C++ tokenizer on a source file to extract all tokens with their types and positions', 'create_token_object': 'create a Token object with a token type, name, start index, and end index for C++ code analysis', 'extract_string_tokens': 'extract string literal tokens from C++ source code handling escape sequences and backslashes', 'extract_char_tokens': 'extract character literal tokens from C++ source code handling escape sequences and single quotes', 'parse_preprocessor_directives': 'parse C++ preprocessor directives including conditional compilation blocks and include statements'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/googletest/googlemock/scripts/generator/cpp/utils.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse C++ source code into an AST by calling BuilderFromSource with source string and filename', 'print all identifiers from a C++ file using PrintIndentifiers with a predicate filter function', 'convert a list of C++ tokens into Type AST nodes using TypeConverter.ToType', 'convert C++ function parameter tokens into Parameter AST nodes using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class C++ mock generation', 'test that simple virtual C++ methods are converted to MOCK_METHOD0 macros', 'test that constructors and destructors are ignored during mock method generation', 'test that generated mock classes preserve C++ namespace structure', 'test that templated C++ classes are converted to MOCK_METHOD_T macros', 'check if a given token is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords available in the ALL set', 'list all C++ type keywords available in the TYPES set', 'list all C++ control flow keywords available in the CONTROL set', 'run the C++ tokenizer on a source file to extract all tokens with their types and positions', 'create a Token object with a token type, name, start index, and end index for C++ code analysis', 'extract string literal tokens from C++ source code handling escape sequences and backslashes', 'extract character literal tokens from C++ source code handling escape sequences and single quotes', 'parse C++ preprocessor directives including conditional compilation blocks and include statements', 'create a function that reads a file and returns its contents using ReadFile', 'create a function that reads a file and prints errors on IOError using ReadFile', 'create a function that reads a file without printing errors by passing print_error=False to ReadFile', 'review the ReadFile function to understand its file reading and error handling behavior', 'summarize the utils module which provides generic C++ parsing utilities including ReadFile']
```

Usage

```
{'read_file_contents': 'create a function that reads a file and returns its contents using ReadFile', 'read_file_with_error_handling': 'create a function that reads a file and prints errors on IOError using ReadFile', 'read_file_silently': 'create a function that reads a file without printing errors by passing print_error=False to ReadFile', 'review_ReadFile': 'review the ReadFile function to understand its file reading and error handling behavior', 'summarize_utils': 'summarize the utils module which provides generic C++ parsing utilities including ReadFile'}
```

