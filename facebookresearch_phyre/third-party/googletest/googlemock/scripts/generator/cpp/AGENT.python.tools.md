# Agent Python Tools

- repo: facebookresearch/phyre
- repo_uri: https://github.com/facebookresearch/phyre

## File: facebookresearch_phyre/third-party/googletest/googlemock/scripts/generator/cpp/ast.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse all identifiers from a C++ file using PrintIndentifiers with a predicate filter', 'parse identifiers from multiple C++ files using PrintAllIndentifiers with a predicate filter', 'convert a list of C++ tokens into Parameter AST nodes using TypeConverter.ToParameters', 'convert a list of C++ tokens into Type AST nodes using TypeConverter.ToType for base classes', 'run the unittest suite to verify gmock_class generates correct mock methods from C++ source', 'test that virtual C++ methods are converted to MOCK_METHOD macros with correct signatures', 'test that C++ classes are converted to Mock classes with proper inheritance and namespaces', 'test that constructors, destructors, and copy/move operators are excluded from mock generation', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template parameters', 'check if a given token is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ type keywords from the TYPES set', 'list all C++ control flow keywords from the CONTROL set', 'list all C++ keywords from the ALL set', 'run GetTokens on a C++ source string to yield a sequence of Token objects', 'create a Token instance with token_type, name, start index, and end index', 'use _GetString to find the closing quote of a C++ string literal with escapes', 'use _GetChar to find the closing quote of a C++ character literal with escapes', 'review the Token class and token type constants UNKNOWN, SYNTAX, CONSTANT, NAME, PREPROCESSOR', 'create a python script that uses ReadFile to read and print the contents of a given file path', 'create a python script that uses ReadFile with print_error=False to silently handle missing files', 'build a python module that uses ReadFile to load C++ source files for parsing', 'test the ReadFile function by reading an existing file and verifying the returned content', 'review the ReadFile function and its error handling for IOError exceptions']
```

Usage

```
{'build_cpp_ast_from_source': 'build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse_cpp_identifiers': 'parse all identifiers from a C++ file using PrintIndentifiers with a predicate filter', 'parse_multiple_cpp_files': 'parse identifiers from multiple C++ files using PrintAllIndentifiers with a predicate filter', 'convert_tokens_to_parameters': 'convert a list of C++ tokens into Parameter AST nodes using TypeConverter.ToParameters', 'convert_tokens_to_types': 'convert a list of C++ tokens into Type AST nodes using TypeConverter.ToType for base classes'}
```

## File: facebookresearch_phyre/third-party/googletest/googlemock/scripts/generator/cpp/gmock_class_test.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse all identifiers from a C++ file using PrintIndentifiers with a predicate filter', 'parse identifiers from multiple C++ files using PrintAllIndentifiers with a predicate filter', 'convert a list of C++ tokens into Parameter AST nodes using TypeConverter.ToParameters', 'convert a list of C++ tokens into Type AST nodes using TypeConverter.ToType for base classes', 'run the unittest suite to verify gmock_class generates correct mock methods from C++ source', 'test that virtual C++ methods are converted to MOCK_METHOD macros with correct signatures', 'test that C++ classes are converted to Mock classes with proper inheritance and namespaces', 'test that constructors, destructors, and copy/move operators are excluded from mock generation', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template parameters', 'check if a given token is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ type keywords from the TYPES set', 'list all C++ control flow keywords from the CONTROL set', 'list all C++ keywords from the ALL set', 'run GetTokens on a C++ source string to yield a sequence of Token objects', 'create a Token instance with token_type, name, start index, and end index', 'use _GetString to find the closing quote of a C++ string literal with escapes', 'use _GetChar to find the closing quote of a C++ character literal with escapes', 'review the Token class and token type constants UNKNOWN, SYNTAX, CONSTANT, NAME, PREPROCESSOR', 'create a python script that uses ReadFile to read and print the contents of a given file path', 'create a python script that uses ReadFile with print_error=False to silently handle missing files', 'build a python module that uses ReadFile to load C++ source files for parsing', 'test the ReadFile function by reading an existing file and verifying the returned content', 'review the ReadFile function and its error handling for IOError exceptions']
```

Usage

```
{'test_gmock_class_generator': 'run the unittest suite to verify gmock_class generates correct mock methods from C++ source', 'test_generate_mock_methods': 'test that virtual C++ methods are converted to MOCK_METHOD macros with correct signatures', 'test_generate_mock_classes': 'test that C++ classes are converted to Mock classes with proper inheritance and namespaces', 'test_constructors_ignored': 'test that constructors, destructors, and copy/move operators are excluded from mock generation', 'test_template_class_generation': 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template parameters'}
```

## File: facebookresearch_phyre/third-party/googletest/googlemock/scripts/generator/cpp/keywords.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse all identifiers from a C++ file using PrintIndentifiers with a predicate filter', 'parse identifiers from multiple C++ files using PrintAllIndentifiers with a predicate filter', 'convert a list of C++ tokens into Parameter AST nodes using TypeConverter.ToParameters', 'convert a list of C++ tokens into Type AST nodes using TypeConverter.ToType for base classes', 'run the unittest suite to verify gmock_class generates correct mock methods from C++ source', 'test that virtual C++ methods are converted to MOCK_METHOD macros with correct signatures', 'test that C++ classes are converted to Mock classes with proper inheritance and namespaces', 'test that constructors, destructors, and copy/move operators are excluded from mock generation', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template parameters', 'check if a given token is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ type keywords from the TYPES set', 'list all C++ control flow keywords from the CONTROL set', 'list all C++ keywords from the ALL set', 'run GetTokens on a C++ source string to yield a sequence of Token objects', 'create a Token instance with token_type, name, start index, and end index', 'use _GetString to find the closing quote of a C++ string literal with escapes', 'use _GetChar to find the closing quote of a C++ character literal with escapes', 'review the Token class and token type constants UNKNOWN, SYNTAX, CONSTANT, NAME, PREPROCESSOR', 'create a python script that uses ReadFile to read and print the contents of a given file path', 'create a python script that uses ReadFile with print_error=False to silently handle missing files', 'build a python module that uses ReadFile to load C++ source files for parsing', 'test the ReadFile function by reading an existing file and verifying the returned content', 'review the ReadFile function and its error handling for IOError exceptions']
```

Usage

```
{'check_is_keyword': 'check if a given token is a C++ keyword using IsKeyword', 'check_is_builtin_type': 'check if a given token is a C++ builtin type using IsBuiltinType', 'list_cpp_types': 'list all C++ type keywords from the TYPES set', 'list_cpp_control_keywords': 'list all C++ control flow keywords from the CONTROL set', 'list_all_cpp_keywords': 'list all C++ keywords from the ALL set'}
```

## File: facebookresearch_phyre/third-party/googletest/googlemock/scripts/generator/cpp/tokenize.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse all identifiers from a C++ file using PrintIndentifiers with a predicate filter', 'parse identifiers from multiple C++ files using PrintAllIndentifiers with a predicate filter', 'convert a list of C++ tokens into Parameter AST nodes using TypeConverter.ToParameters', 'convert a list of C++ tokens into Type AST nodes using TypeConverter.ToType for base classes', 'run the unittest suite to verify gmock_class generates correct mock methods from C++ source', 'test that virtual C++ methods are converted to MOCK_METHOD macros with correct signatures', 'test that C++ classes are converted to Mock classes with proper inheritance and namespaces', 'test that constructors, destructors, and copy/move operators are excluded from mock generation', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template parameters', 'check if a given token is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ type keywords from the TYPES set', 'list all C++ control flow keywords from the CONTROL set', 'list all C++ keywords from the ALL set', 'run GetTokens on a C++ source string to yield a sequence of Token objects', 'create a Token instance with token_type, name, start index, and end index', 'use _GetString to find the closing quote of a C++ string literal with escapes', 'use _GetChar to find the closing quote of a C++ character literal with escapes', 'review the Token class and token type constants UNKNOWN, SYNTAX, CONSTANT, NAME, PREPROCESSOR', 'create a python script that uses ReadFile to read and print the contents of a given file path', 'create a python script that uses ReadFile with print_error=False to silently handle missing files', 'build a python module that uses ReadFile to load C++ source files for parsing', 'test the ReadFile function by reading an existing file and verifying the returned content', 'review the ReadFile function and its error handling for IOError exceptions']
```

Usage

```
{'tokenize_cpp_source': 'run GetTokens on a C++ source string to yield a sequence of Token objects', 'create_token_object': 'create a Token instance with token_type, name, start index, and end index', 'parse_string_literals': 'use _GetString to find the closing quote of a C++ string literal with escapes', 'parse_char_literals': 'use _GetChar to find the closing quote of a C++ character literal with escapes', 'classify_token_types': 'review the Token class and token type constants UNKNOWN, SYNTAX, CONSTANT, NAME, PREPROCESSOR'}
```

## File: facebookresearch_phyre/third-party/googletest/googlemock/scripts/generator/cpp/utils.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse all identifiers from a C++ file using PrintIndentifiers with a predicate filter', 'parse identifiers from multiple C++ files using PrintAllIndentifiers with a predicate filter', 'convert a list of C++ tokens into Parameter AST nodes using TypeConverter.ToParameters', 'convert a list of C++ tokens into Type AST nodes using TypeConverter.ToType for base classes', 'run the unittest suite to verify gmock_class generates correct mock methods from C++ source', 'test that virtual C++ methods are converted to MOCK_METHOD macros with correct signatures', 'test that C++ classes are converted to Mock classes with proper inheritance and namespaces', 'test that constructors, destructors, and copy/move operators are excluded from mock generation', 'test that templated C++ classes generate MOCK_METHOD_T macros with renamed template parameters', 'check if a given token is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ type keywords from the TYPES set', 'list all C++ control flow keywords from the CONTROL set', 'list all C++ keywords from the ALL set', 'run GetTokens on a C++ source string to yield a sequence of Token objects', 'create a Token instance with token_type, name, start index, and end index', 'use _GetString to find the closing quote of a C++ string literal with escapes', 'use _GetChar to find the closing quote of a C++ character literal with escapes', 'review the Token class and token type constants UNKNOWN, SYNTAX, CONSTANT, NAME, PREPROCESSOR', 'create a python script that uses ReadFile to read and print the contents of a given file path', 'create a python script that uses ReadFile with print_error=False to silently handle missing files', 'build a python module that uses ReadFile to load C++ source files for parsing', 'test the ReadFile function by reading an existing file and verifying the returned content', 'review the ReadFile function and its error handling for IOError exceptions']
```

Usage

```
{'read_file_contents': 'create a python script that uses ReadFile to read and print the contents of a given file path', 'read_file_suppress_errors': 'create a python script that uses ReadFile with print_error=False to silently handle missing files', 'read_file_for_cpp_parsing': 'build a python module that uses ReadFile to load C++ source files for parsing', 'test_ReadFile': 'test the ReadFile function by reading an existing file and verifying the returned content', 'review_ReadFile': 'review the ReadFile function and its error handling for IOError exceptions'}
```

