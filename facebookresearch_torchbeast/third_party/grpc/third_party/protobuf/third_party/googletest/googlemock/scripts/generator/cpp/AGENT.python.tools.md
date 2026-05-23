# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/scripts/generator/cpp/ast.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and Generate to parse classes, functions, and methods', 'create an AstBuilder from a token stream to parse C++ source with namespace and class context', 'parse C++ tokens into AST nodes like Class, Function, Method, and VariableDeclaration using the AstBuilder', 'convert C++ type tokens into Type objects with template support using TypeConverter.ToType', 'extract function parameters from C++ tokens into Parameter objects using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class generator to verify C++ mock generation', 'test the GenerateMethodSource helper to convert C++ source to Google Mock method output lines', 'test the GenerateMocks helper to convert C++ source to complete Google Mock class output', 'test the StripLeadingWhitespace helper to remove leading whitespace from each line in a string', 'test the assertEqualIgnoreLeadingWhitespace helper to compare strings ignoring indentation differences', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords in the ALL set for reference or validation', 'list the C++ type keywords in the TYPES set for parsing or analysis', 'list the C++ control flow keywords in the CONTROL set for parsing', 'run the C++ tokenizer on a source file to get a sequence of Token objects', 'create a Token with type, name, start index, and end index for C++ code analysis', 'use _GetString to find the closing quote of a C++ string literal handling escapes', 'use _GetChar to find the closing quote of a C++ character literal handling escapes', 'run the CLI driver to tokenize C++ files and print token types and names to stdout', 'read a file and return its contents using the ReadFile function', 'read a file with error printing disabled by setting print_error to False', 'review the ReadFile function that opens a file and returns its contents or None on error', 'summarize the ReadFile function which handles IOError and optionally prints error messages', 'test the ReadFile function by reading an existing file and verifying the returned contents']
```

Usage

```
{'build_cpp_ast': 'build an AST from C++ source code using BuilderFromSource and Generate to parse classes, functions, and methods', 'create_ast_builder': 'create an AstBuilder from a token stream to parse C++ source with namespace and class context', 'parse_cpp_tokens': 'parse C++ tokens into AST nodes like Class, Function, Method, and VariableDeclaration using the AstBuilder', 'convert_types': 'convert C++ type tokens into Type objects with template support using TypeConverter.ToType', 'extract_parameters': 'extract function parameters from C++ tokens into Parameter objects using TypeConverter.ToParameters'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/scripts/generator/cpp/gmock_class_test.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and Generate to parse classes, functions, and methods', 'create an AstBuilder from a token stream to parse C++ source with namespace and class context', 'parse C++ tokens into AST nodes like Class, Function, Method, and VariableDeclaration using the AstBuilder', 'convert C++ type tokens into Type objects with template support using TypeConverter.ToType', 'extract function parameters from C++ tokens into Parameter objects using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class generator to verify C++ mock generation', 'test the GenerateMethodSource helper to convert C++ source to Google Mock method output lines', 'test the GenerateMocks helper to convert C++ source to complete Google Mock class output', 'test the StripLeadingWhitespace helper to remove leading whitespace from each line in a string', 'test the assertEqualIgnoreLeadingWhitespace helper to compare strings ignoring indentation differences', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords in the ALL set for reference or validation', 'list the C++ type keywords in the TYPES set for parsing or analysis', 'list the C++ control flow keywords in the CONTROL set for parsing', 'run the C++ tokenizer on a source file to get a sequence of Token objects', 'create a Token with type, name, start index, and end index for C++ code analysis', 'use _GetString to find the closing quote of a C++ string literal handling escapes', 'use _GetChar to find the closing quote of a C++ character literal handling escapes', 'run the CLI driver to tokenize C++ files and print token types and names to stdout', 'read a file and return its contents using the ReadFile function', 'read a file with error printing disabled by setting print_error to False', 'review the ReadFile function that opens a file and returns its contents or None on error', 'summarize the ReadFile function which handles IOError and optionally prints error messages', 'test the ReadFile function by reading an existing file and verifying the returned contents']
```

Usage

```
{'run_gmock_class_tests': 'run the unittest test suite for gmock_class generator to verify C++ mock generation', 'test_generate_method_source': 'test the GenerateMethodSource helper to convert C++ source to Google Mock method output lines', 'test_generate_mocks': 'test the GenerateMocks helper to convert C++ source to complete Google Mock class output', 'test_strip_leading_whitespace': 'test the StripLeadingWhitespace helper to remove leading whitespace from each line in a string', 'test_assert_equal_ignore_leading_whitespace': 'test the assertEqualIgnoreLeadingWhitespace helper to compare strings ignoring indentation differences'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/scripts/generator/cpp/keywords.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and Generate to parse classes, functions, and methods', 'create an AstBuilder from a token stream to parse C++ source with namespace and class context', 'parse C++ tokens into AST nodes like Class, Function, Method, and VariableDeclaration using the AstBuilder', 'convert C++ type tokens into Type objects with template support using TypeConverter.ToType', 'extract function parameters from C++ tokens into Parameter objects using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class generator to verify C++ mock generation', 'test the GenerateMethodSource helper to convert C++ source to Google Mock method output lines', 'test the GenerateMocks helper to convert C++ source to complete Google Mock class output', 'test the StripLeadingWhitespace helper to remove leading whitespace from each line in a string', 'test the assertEqualIgnoreLeadingWhitespace helper to compare strings ignoring indentation differences', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords in the ALL set for reference or validation', 'list the C++ type keywords in the TYPES set for parsing or analysis', 'list the C++ control flow keywords in the CONTROL set for parsing', 'run the C++ tokenizer on a source file to get a sequence of Token objects', 'create a Token with type, name, start index, and end index for C++ code analysis', 'use _GetString to find the closing quote of a C++ string literal handling escapes', 'use _GetChar to find the closing quote of a C++ character literal handling escapes', 'run the CLI driver to tokenize C++ files and print token types and names to stdout', 'read a file and return its contents using the ReadFile function', 'read a file with error printing disabled by setting print_error to False', 'review the ReadFile function that opens a file and returns its contents or None on error', 'summarize the ReadFile function which handles IOError and optionally prints error messages', 'test the ReadFile function by reading an existing file and verifying the returned contents']
```

Usage

```
{'check_IsKeyword': 'check if a given token string is a C++ keyword using IsKeyword', 'check_IsBuiltinType': 'check if a given token is a C++ builtin type using IsBuiltinType', 'list_ALL_keywords': 'list all C++ keywords in the ALL set for reference or validation', 'list_TYPES_set': 'list the C++ type keywords in the TYPES set for parsing or analysis', 'list_CONTROL_set': 'list the C++ control flow keywords in the CONTROL set for parsing'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/scripts/generator/cpp/tokenize.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and Generate to parse classes, functions, and methods', 'create an AstBuilder from a token stream to parse C++ source with namespace and class context', 'parse C++ tokens into AST nodes like Class, Function, Method, and VariableDeclaration using the AstBuilder', 'convert C++ type tokens into Type objects with template support using TypeConverter.ToType', 'extract function parameters from C++ tokens into Parameter objects using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class generator to verify C++ mock generation', 'test the GenerateMethodSource helper to convert C++ source to Google Mock method output lines', 'test the GenerateMocks helper to convert C++ source to complete Google Mock class output', 'test the StripLeadingWhitespace helper to remove leading whitespace from each line in a string', 'test the assertEqualIgnoreLeadingWhitespace helper to compare strings ignoring indentation differences', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords in the ALL set for reference or validation', 'list the C++ type keywords in the TYPES set for parsing or analysis', 'list the C++ control flow keywords in the CONTROL set for parsing', 'run the C++ tokenizer on a source file to get a sequence of Token objects', 'create a Token with type, name, start index, and end index for C++ code analysis', 'use _GetString to find the closing quote of a C++ string literal handling escapes', 'use _GetChar to find the closing quote of a C++ character literal handling escapes', 'run the CLI driver to tokenize C++ files and print token types and names to stdout', 'read a file and return its contents using the ReadFile function', 'read a file with error printing disabled by setting print_error to False', 'review the ReadFile function that opens a file and returns its contents or None on error', 'summarize the ReadFile function which handles IOError and optionally prints error messages', 'test the ReadFile function by reading an existing file and verifying the returned contents']
```

Usage

```
{'tokenize_cpp_source': 'run the C++ tokenizer on a source file to get a sequence of Token objects', 'create_token_object': 'create a Token with type, name, start index, and end index for C++ code analysis', 'parse_string_literals': 'use _GetString to find the closing quote of a C++ string literal handling escapes', 'parse_char_literals': 'use _GetChar to find the closing quote of a C++ character literal handling escapes', 'tokenize_file_cli': 'run the CLI driver to tokenize C++ files and print token types and names to stdout'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/third_party/googletest/googlemock/scripts/generator/cpp/utils.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and Generate to parse classes, functions, and methods', 'create an AstBuilder from a token stream to parse C++ source with namespace and class context', 'parse C++ tokens into AST nodes like Class, Function, Method, and VariableDeclaration using the AstBuilder', 'convert C++ type tokens into Type objects with template support using TypeConverter.ToType', 'extract function parameters from C++ tokens into Parameter objects using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class generator to verify C++ mock generation', 'test the GenerateMethodSource helper to convert C++ source to Google Mock method output lines', 'test the GenerateMocks helper to convert C++ source to complete Google Mock class output', 'test the StripLeadingWhitespace helper to remove leading whitespace from each line in a string', 'test the assertEqualIgnoreLeadingWhitespace helper to compare strings ignoring indentation differences', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords in the ALL set for reference or validation', 'list the C++ type keywords in the TYPES set for parsing or analysis', 'list the C++ control flow keywords in the CONTROL set for parsing', 'run the C++ tokenizer on a source file to get a sequence of Token objects', 'create a Token with type, name, start index, and end index for C++ code analysis', 'use _GetString to find the closing quote of a C++ string literal handling escapes', 'use _GetChar to find the closing quote of a C++ character literal handling escapes', 'run the CLI driver to tokenize C++ files and print token types and names to stdout', 'read a file and return its contents using the ReadFile function', 'read a file with error printing disabled by setting print_error to False', 'review the ReadFile function that opens a file and returns its contents or None on error', 'summarize the ReadFile function which handles IOError and optionally prints error messages', 'test the ReadFile function by reading an existing file and verifying the returned contents']
```

Usage

```
{'read_file_contents': 'read a file and return its contents using the ReadFile function', 'read_file_suppress_errors': 'read a file with error printing disabled by setting print_error to False', 'review_ReadFile': 'review the ReadFile function that opens a file and returns its contents or None on error', 'summarize_ReadFile': 'summarize the ReadFile function which handles IOError and optionally prints error messages', 'test_ReadFile': 'test the ReadFile function by reading an existing file and verifying the returned contents'}
```

