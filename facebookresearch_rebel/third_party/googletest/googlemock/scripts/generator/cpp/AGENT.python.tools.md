# Agent Python Tools

- repo: facebookresearch/rebel
- repo_uri: https://github.com/facebookresearch/rebel

## File: facebookresearch_rebel/third_party/googletest/googlemock/scripts/generator/cpp/ast.py

Prompts

```
['use BuilderFromSource to create an AstBuilder from C++ source code and filename', 'call AstBuilder.Generate() to yield AST nodes like Class, Function, and Method from C++ source', 'use TypeConverter.ToParameters() to convert a list of tokens into Parameter AST nodes', 'use TypeConverter.ToType() to convert tokens representing base classes into Type AST nodes', 'use PrintIndentifiers to print all identifiers from a C++ source file filtered by a predicate', 'run the unittest test suite for gmock_class generator to verify mock generation', 'convert C++ class source to Google Mock MOCK_METHOD macro output lines', 'convert C++ source to complete Google Mock mock class source code', 'strip leading whitespace from each line in a multi-line string', 'assert two strings are equal ignoring leading whitespace on each line', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token string is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by printing the contents of the ALL set', 'list all C++ type keywords by printing the contents of the TYPES set', 'list all C++ control flow keywords by printing the contents of the CONTROL set', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'build a generator that yields Token objects from a string of C++ source code', 'create a Token object with a token type, name, start index, and end index', 'review the GetTokens function to understand how it handles preprocessor directives and #if 0 blocks', 'summarize the five token types: UNKNOWN, SYNTAX, CONSTANT, NAME, and PREPROCESSOR', 'create a python script that uses ReadFile to read and print the contents of a given file path', 'create a python script that calls ReadFile with print_error=False to silently handle missing files', 'build a python module that uses ReadFile to load a C++ source file for parsing', 'review the ReadFile function to understand its error handling and file reading behavior', 'summarize the utils module which provides ReadFile for reading files and a DEBUG flag for token tracing']
```

Usage

```
{'build_cpp_ast_from_source': 'use BuilderFromSource to create an AstBuilder from C++ source code and filename', 'generate_ast_nodes': 'call AstBuilder.Generate() to yield AST nodes like Class, Function, and Method from C++ source', 'convert_tokens_to_parameters': 'use TypeConverter.ToParameters() to convert a list of tokens into Parameter AST nodes', 'convert_tokens_to_types': 'use TypeConverter.ToType() to convert tokens representing base classes into Type AST nodes', 'print_cpp_identifiers': 'use PrintIndentifiers to print all identifiers from a C++ source file filtered by a predicate'}
```

## File: facebookresearch_rebel/third_party/googletest/googlemock/scripts/generator/cpp/gmock_class_test.py

Prompts

```
['use BuilderFromSource to create an AstBuilder from C++ source code and filename', 'call AstBuilder.Generate() to yield AST nodes like Class, Function, and Method from C++ source', 'use TypeConverter.ToParameters() to convert a list of tokens into Parameter AST nodes', 'use TypeConverter.ToType() to convert tokens representing base classes into Type AST nodes', 'use PrintIndentifiers to print all identifiers from a C++ source file filtered by a predicate', 'run the unittest test suite for gmock_class generator to verify mock generation', 'convert C++ class source to Google Mock MOCK_METHOD macro output lines', 'convert C++ source to complete Google Mock mock class source code', 'strip leading whitespace from each line in a multi-line string', 'assert two strings are equal ignoring leading whitespace on each line', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token string is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by printing the contents of the ALL set', 'list all C++ type keywords by printing the contents of the TYPES set', 'list all C++ control flow keywords by printing the contents of the CONTROL set', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'build a generator that yields Token objects from a string of C++ source code', 'create a Token object with a token type, name, start index, and end index', 'review the GetTokens function to understand how it handles preprocessor directives and #if 0 blocks', 'summarize the five token types: UNKNOWN, SYNTAX, CONSTANT, NAME, and PREPROCESSOR', 'create a python script that uses ReadFile to read and print the contents of a given file path', 'create a python script that calls ReadFile with print_error=False to silently handle missing files', 'build a python module that uses ReadFile to load a C++ source file for parsing', 'review the ReadFile function to understand its error handling and file reading behavior', 'summarize the utils module which provides ReadFile for reading files and a DEBUG flag for token tracing']
```

Usage

```
{'run_gmock_class_tests': 'run the unittest test suite for gmock_class generator to verify mock generation', 'generate_mock_methods_from_cpp': 'convert C++ class source to Google Mock MOCK_METHOD macro output lines', 'generate_full_mock_classes': 'convert C++ source to complete Google Mock mock class source code', 'strip_leading_whitespace': 'strip leading whitespace from each line in a multi-line string', 'assert_equal_ignore_whitespace': 'assert two strings are equal ignoring leading whitespace on each line'}
```

## File: facebookresearch_rebel/third_party/googletest/googlemock/scripts/generator/cpp/keywords.py

Prompts

```
['use BuilderFromSource to create an AstBuilder from C++ source code and filename', 'call AstBuilder.Generate() to yield AST nodes like Class, Function, and Method from C++ source', 'use TypeConverter.ToParameters() to convert a list of tokens into Parameter AST nodes', 'use TypeConverter.ToType() to convert tokens representing base classes into Type AST nodes', 'use PrintIndentifiers to print all identifiers from a C++ source file filtered by a predicate', 'run the unittest test suite for gmock_class generator to verify mock generation', 'convert C++ class source to Google Mock MOCK_METHOD macro output lines', 'convert C++ source to complete Google Mock mock class source code', 'strip leading whitespace from each line in a multi-line string', 'assert two strings are equal ignoring leading whitespace on each line', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token string is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by printing the contents of the ALL set', 'list all C++ type keywords by printing the contents of the TYPES set', 'list all C++ control flow keywords by printing the contents of the CONTROL set', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'build a generator that yields Token objects from a string of C++ source code', 'create a Token object with a token type, name, start index, and end index', 'review the GetTokens function to understand how it handles preprocessor directives and #if 0 blocks', 'summarize the five token types: UNKNOWN, SYNTAX, CONSTANT, NAME, and PREPROCESSOR', 'create a python script that uses ReadFile to read and print the contents of a given file path', 'create a python script that calls ReadFile with print_error=False to silently handle missing files', 'build a python module that uses ReadFile to load a C++ source file for parsing', 'review the ReadFile function to understand its error handling and file reading behavior', 'summarize the utils module which provides ReadFile for reading files and a DEBUG flag for token tracing']
```

Usage

```
{'check_is_keyword': 'check if a given token string is a C++ keyword using IsKeyword', 'check_is_builtin_type': 'check if a given token string is a C++ builtin type using IsBuiltinType', 'list_all_keywords': 'list all C++ keywords by printing the contents of the ALL set', 'list_cpp_types': 'list all C++ type keywords by printing the contents of the TYPES set', 'list_control_keywords': 'list all C++ control flow keywords by printing the contents of the CONTROL set'}
```

## File: facebookresearch_rebel/third_party/googletest/googlemock/scripts/generator/cpp/tokenize.py

Prompts

```
['use BuilderFromSource to create an AstBuilder from C++ source code and filename', 'call AstBuilder.Generate() to yield AST nodes like Class, Function, and Method from C++ source', 'use TypeConverter.ToParameters() to convert a list of tokens into Parameter AST nodes', 'use TypeConverter.ToType() to convert tokens representing base classes into Type AST nodes', 'use PrintIndentifiers to print all identifiers from a C++ source file filtered by a predicate', 'run the unittest test suite for gmock_class generator to verify mock generation', 'convert C++ class source to Google Mock MOCK_METHOD macro output lines', 'convert C++ source to complete Google Mock mock class source code', 'strip leading whitespace from each line in a multi-line string', 'assert two strings are equal ignoring leading whitespace on each line', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token string is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by printing the contents of the ALL set', 'list all C++ type keywords by printing the contents of the TYPES set', 'list all C++ control flow keywords by printing the contents of the CONTROL set', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'build a generator that yields Token objects from a string of C++ source code', 'create a Token object with a token type, name, start index, and end index', 'review the GetTokens function to understand how it handles preprocessor directives and #if 0 blocks', 'summarize the five token types: UNKNOWN, SYNTAX, CONSTANT, NAME, and PREPROCESSOR', 'create a python script that uses ReadFile to read and print the contents of a given file path', 'create a python script that calls ReadFile with print_error=False to silently handle missing files', 'build a python module that uses ReadFile to load a C++ source file for parsing', 'review the ReadFile function to understand its error handling and file reading behavior', 'summarize the utils module which provides ReadFile for reading files and a DEBUG flag for token tracing']
```

Usage

```
{'run_tokenize_cpp_file': 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'build_GetTokens_generator': 'build a generator that yields Token objects from a string of C++ source code', 'create_Token_instance': 'create a Token object with a token type, name, start index, and end index', 'review_GetTokens_preprocessor': 'review the GetTokens function to understand how it handles preprocessor directives and #if 0 blocks', 'summarize_token_types': 'summarize the five token types: UNKNOWN, SYNTAX, CONSTANT, NAME, and PREPROCESSOR'}
```

## File: facebookresearch_rebel/third_party/googletest/googlemock/scripts/generator/cpp/utils.py

Prompts

```
['use BuilderFromSource to create an AstBuilder from C++ source code and filename', 'call AstBuilder.Generate() to yield AST nodes like Class, Function, and Method from C++ source', 'use TypeConverter.ToParameters() to convert a list of tokens into Parameter AST nodes', 'use TypeConverter.ToType() to convert tokens representing base classes into Type AST nodes', 'use PrintIndentifiers to print all identifiers from a C++ source file filtered by a predicate', 'run the unittest test suite for gmock_class generator to verify mock generation', 'convert C++ class source to Google Mock MOCK_METHOD macro output lines', 'convert C++ source to complete Google Mock mock class source code', 'strip leading whitespace from each line in a multi-line string', 'assert two strings are equal ignoring leading whitespace on each line', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token string is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by printing the contents of the ALL set', 'list all C++ type keywords by printing the contents of the TYPES set', 'list all C++ control flow keywords by printing the contents of the CONTROL set', 'run the C++ tokenizer on a source file and print each token type and name to stdout', 'build a generator that yields Token objects from a string of C++ source code', 'create a Token object with a token type, name, start index, and end index', 'review the GetTokens function to understand how it handles preprocessor directives and #if 0 blocks', 'summarize the five token types: UNKNOWN, SYNTAX, CONSTANT, NAME, and PREPROCESSOR', 'create a python script that uses ReadFile to read and print the contents of a given file path', 'create a python script that calls ReadFile with print_error=False to silently handle missing files', 'build a python module that uses ReadFile to load a C++ source file for parsing', 'review the ReadFile function to understand its error handling and file reading behavior', 'summarize the utils module which provides ReadFile for reading files and a DEBUG flag for token tracing']
```

Usage

```
{'read_file_contents': 'create a python script that uses ReadFile to read and print the contents of a given file path', 'read_file_suppress_errors': 'create a python script that calls ReadFile with print_error=False to silently handle missing files', 'read_file_for_parsing': 'build a python module that uses ReadFile to load a C++ source file for parsing', 'review_ReadFile': 'review the ReadFile function to understand its error handling and file reading behavior', 'summarize_utils_module': 'summarize the utils module which provides ReadFile for reading files and a DEBUG flag for token tracing'}
```

