# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/googletest/googlemock/scripts/generator/cpp/ast.py

Prompts

```
['build an abstract syntax tree from C++ source code using BuilderFromSource and Generate', 'print all identifiers from a C++ source file using PrintIndentifiers with a filter predicate', 'print identifiers from multiple C++ files using PrintAllIndentifiers with a filter predicate', 'parse C++ tokens into Type objects using TypeConverter.ToType for base class analysis', 'parse C++ function parameter tokens into Parameter objects using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class mock generation', 'test that C++ virtual methods are converted to MOCK_METHOD macros', 'test that C++ classes are converted to complete Mock class source', 'test that constructors and destructors are ignored during mock generation', 'test that templated C++ classes generate MOCK_METHOD_T macros', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by printing the ALL set from keywords module', 'list all C++ type keywords by printing the TYPES set from keywords module', 'list all C++ control flow keywords by printing the CONTROL set from keywords module', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'create a generator that yields Token objects from a string of C++ source code', 'build a Token object with a token type, name, start index, and end index', 'review how GetTokens handles preprocessor directives including #if 0 blocks and #include paths', 'summarize the Token class data container that represents C++ identifiers, syntax, constants, and preprocessor directives', 'read the contents of a file and return the text or None on error', 'read a file and optionally print an error message if the file cannot be opened', 'read a C++ source file for parsing using the ReadFile utility function', 'read a file without printing errors by passing print_error=False to ReadFile', 'review the ReadFile function which safely reads files and handles IOError exceptions']
```

Usage

```
{'build_cpp_ast': 'build an abstract syntax tree from C++ source code using BuilderFromSource and Generate', 'print_cpp_identifiers': 'print all identifiers from a C++ source file using PrintIndentifiers with a filter predicate', 'print_all_cpp_identifiers': 'print identifiers from multiple C++ files using PrintAllIndentifiers with a filter predicate', 'parse_cpp_tokens_to_types': 'parse C++ tokens into Type objects using TypeConverter.ToType for base class analysis', 'parse_cpp_parameters': 'parse C++ function parameter tokens into Parameter objects using TypeConverter.ToParameters'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/googletest/googlemock/scripts/generator/cpp/gmock_class_test.py

Prompts

```
['build an abstract syntax tree from C++ source code using BuilderFromSource and Generate', 'print all identifiers from a C++ source file using PrintIndentifiers with a filter predicate', 'print identifiers from multiple C++ files using PrintAllIndentifiers with a filter predicate', 'parse C++ tokens into Type objects using TypeConverter.ToType for base class analysis', 'parse C++ function parameter tokens into Parameter objects using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class mock generation', 'test that C++ virtual methods are converted to MOCK_METHOD macros', 'test that C++ classes are converted to complete Mock class source', 'test that constructors and destructors are ignored during mock generation', 'test that templated C++ classes generate MOCK_METHOD_T macros', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by printing the ALL set from keywords module', 'list all C++ type keywords by printing the TYPES set from keywords module', 'list all C++ control flow keywords by printing the CONTROL set from keywords module', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'create a generator that yields Token objects from a string of C++ source code', 'build a Token object with a token type, name, start index, and end index', 'review how GetTokens handles preprocessor directives including #if 0 blocks and #include paths', 'summarize the Token class data container that represents C++ identifiers, syntax, constants, and preprocessor directives', 'read the contents of a file and return the text or None on error', 'read a file and optionally print an error message if the file cannot be opened', 'read a C++ source file for parsing using the ReadFile utility function', 'read a file without printing errors by passing print_error=False to ReadFile', 'review the ReadFile function which safely reads files and handles IOError exceptions']
```

Usage

```
{'run_gmock_class_tests': 'run the unittest test suite for gmock_class mock generation', 'test_generate_mock_methods': 'test that C++ virtual methods are converted to MOCK_METHOD macros', 'test_generate_full_mocks': 'test that C++ classes are converted to complete Mock class source', 'test_constructor_destructor_filtering': 'test that constructors and destructors are ignored during mock generation', 'test_template_class_mocks': 'test that templated C++ classes generate MOCK_METHOD_T macros'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/googletest/googlemock/scripts/generator/cpp/keywords.py

Prompts

```
['build an abstract syntax tree from C++ source code using BuilderFromSource and Generate', 'print all identifiers from a C++ source file using PrintIndentifiers with a filter predicate', 'print identifiers from multiple C++ files using PrintAllIndentifiers with a filter predicate', 'parse C++ tokens into Type objects using TypeConverter.ToType for base class analysis', 'parse C++ function parameter tokens into Parameter objects using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class mock generation', 'test that C++ virtual methods are converted to MOCK_METHOD macros', 'test that C++ classes are converted to complete Mock class source', 'test that constructors and destructors are ignored during mock generation', 'test that templated C++ classes generate MOCK_METHOD_T macros', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by printing the ALL set from keywords module', 'list all C++ type keywords by printing the TYPES set from keywords module', 'list all C++ control flow keywords by printing the CONTROL set from keywords module', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'create a generator that yields Token objects from a string of C++ source code', 'build a Token object with a token type, name, start index, and end index', 'review how GetTokens handles preprocessor directives including #if 0 blocks and #include paths', 'summarize the Token class data container that represents C++ identifiers, syntax, constants, and preprocessor directives', 'read the contents of a file and return the text or None on error', 'read a file and optionally print an error message if the file cannot be opened', 'read a C++ source file for parsing using the ReadFile utility function', 'read a file without printing errors by passing print_error=False to ReadFile', 'review the ReadFile function which safely reads files and handles IOError exceptions']
```

Usage

```
{'check_IsKeyword': 'check if a given token string is a C++ keyword using IsKeyword', 'check_IsBuiltinType': 'check if a given token is a C++ builtin type using IsBuiltinType', 'list_ALL_keywords': 'list all C++ keywords by printing the ALL set from keywords module', 'list_TYPES': 'list all C++ type keywords by printing the TYPES set from keywords module', 'list_CONTROL_keywords': 'list all C++ control flow keywords by printing the CONTROL set from keywords module'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/googletest/googlemock/scripts/generator/cpp/tokenize.py

Prompts

```
['build an abstract syntax tree from C++ source code using BuilderFromSource and Generate', 'print all identifiers from a C++ source file using PrintIndentifiers with a filter predicate', 'print identifiers from multiple C++ files using PrintAllIndentifiers with a filter predicate', 'parse C++ tokens into Type objects using TypeConverter.ToType for base class analysis', 'parse C++ function parameter tokens into Parameter objects using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class mock generation', 'test that C++ virtual methods are converted to MOCK_METHOD macros', 'test that C++ classes are converted to complete Mock class source', 'test that constructors and destructors are ignored during mock generation', 'test that templated C++ classes generate MOCK_METHOD_T macros', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by printing the ALL set from keywords module', 'list all C++ type keywords by printing the TYPES set from keywords module', 'list all C++ control flow keywords by printing the CONTROL set from keywords module', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'create a generator that yields Token objects from a string of C++ source code', 'build a Token object with a token type, name, start index, and end index', 'review how GetTokens handles preprocessor directives including #if 0 blocks and #include paths', 'summarize the Token class data container that represents C++ identifiers, syntax, constants, and preprocessor directives', 'read the contents of a file and return the text or None on error', 'read a file and optionally print an error message if the file cannot be opened', 'read a C++ source file for parsing using the ReadFile utility function', 'read a file without printing errors by passing print_error=False to ReadFile', 'review the ReadFile function which safely reads files and handles IOError exceptions']
```

Usage

```
{'run_tokenize_cpp_file': 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'create_GetTokens_generator': 'create a generator that yields Token objects from a string of C++ source code', 'build_Token_instance': 'build a Token object with a token type, name, start index, and end index', 'review_GetTokens_preprocessor_handling': 'review how GetTokens handles preprocessor directives including #if 0 blocks and #include paths', 'summarize_Token_class': 'summarize the Token class data container that represents C++ identifiers, syntax, constants, and preprocessor directives'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/googletest/googlemock/scripts/generator/cpp/utils.py

Prompts

```
['build an abstract syntax tree from C++ source code using BuilderFromSource and Generate', 'print all identifiers from a C++ source file using PrintIndentifiers with a filter predicate', 'print identifiers from multiple C++ files using PrintAllIndentifiers with a filter predicate', 'parse C++ tokens into Type objects using TypeConverter.ToType for base class analysis', 'parse C++ function parameter tokens into Parameter objects using TypeConverter.ToParameters', 'run the unittest test suite for gmock_class mock generation', 'test that C++ virtual methods are converted to MOCK_METHOD macros', 'test that C++ classes are converted to complete Mock class source', 'test that constructors and destructors are ignored during mock generation', 'test that templated C++ classes generate MOCK_METHOD_T macros', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by printing the ALL set from keywords module', 'list all C++ type keywords by printing the TYPES set from keywords module', 'list all C++ control flow keywords by printing the CONTROL set from keywords module', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'create a generator that yields Token objects from a string of C++ source code', 'build a Token object with a token type, name, start index, and end index', 'review how GetTokens handles preprocessor directives including #if 0 blocks and #include paths', 'summarize the Token class data container that represents C++ identifiers, syntax, constants, and preprocessor directives', 'read the contents of a file and return the text or None on error', 'read a file and optionally print an error message if the file cannot be opened', 'read a C++ source file for parsing using the ReadFile utility function', 'read a file without printing errors by passing print_error=False to ReadFile', 'review the ReadFile function which safely reads files and handles IOError exceptions']
```

Usage

```
{'read_file_contents': 'read the contents of a file and return the text or None on error', 'read_file_with_error_printing': 'read a file and optionally print an error message if the file cannot be opened', 'read_cpp_source_file': 'read a C++ source file for parsing using the ReadFile utility function', 'read_file_silently': 'read a file without printing errors by passing print_error=False to ReadFile', 'review_ReadFile_function': 'review the ReadFile function which safely reads files and handles IOError exceptions'}
```

