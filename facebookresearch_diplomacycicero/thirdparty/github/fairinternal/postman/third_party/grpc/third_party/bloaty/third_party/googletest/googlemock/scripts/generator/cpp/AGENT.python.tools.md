# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/bloaty/third_party/googletest/googlemock/scripts/generator/cpp/ast.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse a C++ file and print all identifiers matching a predicate using PrintIndentifiers', 'parse multiple C++ source files and print identifiers using PrintAllIndentifiers', 'convert a list of C++ tokens into Type AST nodes using TypeConverter.ToType', 'convert a list of C++ tokens into Parameter AST nodes using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class generator to verify mock method generation', 'test that C++ virtual methods are correctly converted to MOCK_METHOD macros', 'test that complete mock classes are generated from C++ source with proper inheritance', 'test that constructors and destructors are correctly ignored during mock generation', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template params', 'check if a given token is a C++ keyword using the IsKeyword function', 'check if a given token is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by inspecting the ALL set constant', 'list C++ type keywords by inspecting the TYPES set constant', 'list C++ control flow keywords by inspecting the CONTROL set constant', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'create a generator that yields Token objects for each token found in C++ source code', 'build a Token data container with token_type, name, start index, and end index attributes', 'test the _GetString helper that finds the closing quote of a C++ string literal handling backslash escapes', 'test the _GetChar helper that finds the closing quote of a C++ char literal handling backslash escapes', 'read a file and return its contents as a string using ReadFile', 'read a file with optional error printing using ReadFile with print_error flag', 'read a C++ source file for parsing using the ReadFile utility function', 'review the ReadFile function that reads file contents with IOError handling', 'summarize the utils module which provides generic utilities for C++ parsing']
```

Usage

```
{'build_cpp_ast_from_source': 'build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse_cpp_identifiers': 'parse a C++ file and print all identifiers matching a predicate using PrintIndentifiers', 'parse_multiple_cpp_files': 'parse multiple C++ source files and print identifiers using PrintAllIndentifiers', 'convert_tokens_to_type': 'convert a list of C++ tokens into Type AST nodes using TypeConverter.ToType', 'convert_tokens_to_parameters': 'convert a list of C++ tokens into Parameter AST nodes using TypeConverter.ToParameters'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/bloaty/third_party/googletest/googlemock/scripts/generator/cpp/gmock_class_test.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse a C++ file and print all identifiers matching a predicate using PrintIndentifiers', 'parse multiple C++ source files and print identifiers using PrintAllIndentifiers', 'convert a list of C++ tokens into Type AST nodes using TypeConverter.ToType', 'convert a list of C++ tokens into Parameter AST nodes using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class generator to verify mock method generation', 'test that C++ virtual methods are correctly converted to MOCK_METHOD macros', 'test that complete mock classes are generated from C++ source with proper inheritance', 'test that constructors and destructors are correctly ignored during mock generation', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template params', 'check if a given token is a C++ keyword using the IsKeyword function', 'check if a given token is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by inspecting the ALL set constant', 'list C++ type keywords by inspecting the TYPES set constant', 'list C++ control flow keywords by inspecting the CONTROL set constant', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'create a generator that yields Token objects for each token found in C++ source code', 'build a Token data container with token_type, name, start index, and end index attributes', 'test the _GetString helper that finds the closing quote of a C++ string literal handling backslash escapes', 'test the _GetChar helper that finds the closing quote of a C++ char literal handling backslash escapes', 'read a file and return its contents as a string using ReadFile', 'read a file with optional error printing using ReadFile with print_error flag', 'read a C++ source file for parsing using the ReadFile utility function', 'review the ReadFile function that reads file contents with IOError handling', 'summarize the utils module which provides generic utilities for C++ parsing']
```

Usage

```
{'run_gmock_class_tests': 'run the unittest test suite for gmock_class generator to verify mock method generation', 'test_generate_mock_methods': 'test that C++ virtual methods are correctly converted to MOCK_METHOD macros', 'test_generate_mock_classes': 'test that complete mock classes are generated from C++ source with proper inheritance', 'test_constructor_destructor_filtering': 'test that constructors and destructors are correctly ignored during mock generation', 'test_template_class_mock_generation': 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template params'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/bloaty/third_party/googletest/googlemock/scripts/generator/cpp/keywords.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse a C++ file and print all identifiers matching a predicate using PrintIndentifiers', 'parse multiple C++ source files and print identifiers using PrintAllIndentifiers', 'convert a list of C++ tokens into Type AST nodes using TypeConverter.ToType', 'convert a list of C++ tokens into Parameter AST nodes using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class generator to verify mock method generation', 'test that C++ virtual methods are correctly converted to MOCK_METHOD macros', 'test that complete mock classes are generated from C++ source with proper inheritance', 'test that constructors and destructors are correctly ignored during mock generation', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template params', 'check if a given token is a C++ keyword using the IsKeyword function', 'check if a given token is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by inspecting the ALL set constant', 'list C++ type keywords by inspecting the TYPES set constant', 'list C++ control flow keywords by inspecting the CONTROL set constant', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'create a generator that yields Token objects for each token found in C++ source code', 'build a Token data container with token_type, name, start index, and end index attributes', 'test the _GetString helper that finds the closing quote of a C++ string literal handling backslash escapes', 'test the _GetChar helper that finds the closing quote of a C++ char literal handling backslash escapes', 'read a file and return its contents as a string using ReadFile', 'read a file with optional error printing using ReadFile with print_error flag', 'read a C++ source file for parsing using the ReadFile utility function', 'review the ReadFile function that reads file contents with IOError handling', 'summarize the utils module which provides generic utilities for C++ parsing']
```

Usage

```
{'check_IsKeyword': 'check if a given token is a C++ keyword using the IsKeyword function', 'check_IsBuiltinType': 'check if a given token is a C++ builtin type using the IsBuiltinType function', 'list_ALL_keywords': 'list all C++ keywords by inspecting the ALL set constant', 'list_TYPES': 'list C++ type keywords by inspecting the TYPES set constant', 'list_CONTROL_keywords': 'list C++ control flow keywords by inspecting the CONTROL set constant'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/bloaty/third_party/googletest/googlemock/scripts/generator/cpp/tokenize.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse a C++ file and print all identifiers matching a predicate using PrintIndentifiers', 'parse multiple C++ source files and print identifiers using PrintAllIndentifiers', 'convert a list of C++ tokens into Type AST nodes using TypeConverter.ToType', 'convert a list of C++ tokens into Parameter AST nodes using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class generator to verify mock method generation', 'test that C++ virtual methods are correctly converted to MOCK_METHOD macros', 'test that complete mock classes are generated from C++ source with proper inheritance', 'test that constructors and destructors are correctly ignored during mock generation', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template params', 'check if a given token is a C++ keyword using the IsKeyword function', 'check if a given token is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by inspecting the ALL set constant', 'list C++ type keywords by inspecting the TYPES set constant', 'list C++ control flow keywords by inspecting the CONTROL set constant', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'create a generator that yields Token objects for each token found in C++ source code', 'build a Token data container with token_type, name, start index, and end index attributes', 'test the _GetString helper that finds the closing quote of a C++ string literal handling backslash escapes', 'test the _GetChar helper that finds the closing quote of a C++ char literal handling backslash escapes', 'read a file and return its contents as a string using ReadFile', 'read a file with optional error printing using ReadFile with print_error flag', 'read a C++ source file for parsing using the ReadFile utility function', 'review the ReadFile function that reads file contents with IOError handling', 'summarize the utils module which provides generic utilities for C++ parsing']
```

Usage

```
{'run_tokenize_cpp_file': 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'create_GetTokens_generator': 'create a generator that yields Token objects for each token found in C++ source code', 'build_Token_class': 'build a Token data container with token_type, name, start index, and end index attributes', 'test_GetString_helper': 'test the _GetString helper that finds the closing quote of a C++ string literal handling backslash escapes', 'test_GetChar_helper': 'test the _GetChar helper that finds the closing quote of a C++ char literal handling backslash escapes'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/bloaty/third_party/googletest/googlemock/scripts/generator/cpp/utils.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse a C++ file and print all identifiers matching a predicate using PrintIndentifiers', 'parse multiple C++ source files and print identifiers using PrintAllIndentifiers', 'convert a list of C++ tokens into Type AST nodes using TypeConverter.ToType', 'convert a list of C++ tokens into Parameter AST nodes using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class generator to verify mock method generation', 'test that C++ virtual methods are correctly converted to MOCK_METHOD macros', 'test that complete mock classes are generated from C++ source with proper inheritance', 'test that constructors and destructors are correctly ignored during mock generation', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template params', 'check if a given token is a C++ keyword using the IsKeyword function', 'check if a given token is a C++ builtin type using the IsBuiltinType function', 'list all C++ keywords by inspecting the ALL set constant', 'list C++ type keywords by inspecting the TYPES set constant', 'list C++ control flow keywords by inspecting the CONTROL set constant', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'create a generator that yields Token objects for each token found in C++ source code', 'build a Token data container with token_type, name, start index, and end index attributes', 'test the _GetString helper that finds the closing quote of a C++ string literal handling backslash escapes', 'test the _GetChar helper that finds the closing quote of a C++ char literal handling backslash escapes', 'read a file and return its contents as a string using ReadFile', 'read a file with optional error printing using ReadFile with print_error flag', 'read a C++ source file for parsing using the ReadFile utility function', 'review the ReadFile function that reads file contents with IOError handling', 'summarize the utils module which provides generic utilities for C++ parsing']
```

Usage

```
{'read_file_contents': 'read a file and return its contents as a string using ReadFile', 'read_file_with_error_handling': 'read a file with optional error printing using ReadFile with print_error flag', 'read_cpp_source_file': 'read a C++ source file for parsing using the ReadFile utility function', 'review_ReadFile': 'review the ReadFile function that reads file contents with IOError handling', 'summarize_utils_module': 'summarize the utils module which provides generic utilities for C++ parsing'}
```

