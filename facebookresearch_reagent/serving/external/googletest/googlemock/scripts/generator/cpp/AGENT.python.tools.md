# Agent Python Tools

- repo: facebookresearch/reagent
- repo_uri: https://github.com/facebookresearch/reagent

## File: facebookresearch_reagent/serving/external/googletest/googlemock/scripts/generator/cpp/ast.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource to parse and generate abstract syntax tree nodes', 'generate AST nodes from a C++ token stream by calling AstBuilder.Generate() to yield parsed declarations and definitions', 'parse a C++ file and print all AST nodes by using BuilderFromSource with the file contents and iterating over Generate()', 'print all identifiers from C++ source files using PrintIndentifiers with a predicate function to filter which nodes to output', 'convert C++ tokens into Type AST nodes using TypeConverter.ToType() to parse base class and template type information', 'run the unittest test suite for gmock_class C++ mock generation', 'test the GenerateMethodsTest class to verify MOCK_METHOD macro generation from C++ source', 'test the GenerateMocksTest class to verify full mock class generation from C++ source', 'test the TestCase helper to strip leading whitespace and compare output ignoring indentation', 'test the GenerateMethodSource helper to convert C++ class source into Google Mock method macros', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token string is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by inspecting the ALL set constant', 'list C++ type keywords by inspecting the TYPES set constant', 'list C++ control flow keywords by inspecting the CONTROL set constant', 'run the C++ tokenizer on a source file to get a sequence of named tokens with types', 'create a Token object with a token type, name, start index, and end index', 'parse a C++ string literal from source code handling escaped quotes and backslashes', 'parse a C++ character literal from source code handling escaped single quotes', 'review the GetTokens generator function to understand how it tokenizes C++ identifiers, constants, and preprocessor directives', 'read the contents of a file and return it as a string or None on error', 'read a file silently without printing errors by setting print_error to False', 'read a file with debug mode enabled to see start and end token indices', 'summarize the ReadFile function that opens a file and returns its contents or None on IOError', 'review the ReadFile function and its error handling for IOError exceptions']
```

Usage

```
{'build_cpp_ast': 'build an AST from C++ source code using BuilderFromSource to parse and generate abstract syntax tree nodes', 'generate_ast_nodes': 'generate AST nodes from a C++ token stream by calling AstBuilder.Generate() to yield parsed declarations and definitions', 'parse_cpp_file': 'parse a C++ file and print all AST nodes by using BuilderFromSource with the file contents and iterating over Generate()', 'print_cpp_identifiers': 'print all identifiers from C++ source files using PrintIndentifiers with a predicate function to filter which nodes to output', 'convert_tokens_to_type': 'convert C++ tokens into Type AST nodes using TypeConverter.ToType() to parse base class and template type information'}
```

## File: facebookresearch_reagent/serving/external/googletest/googlemock/scripts/generator/cpp/gmock_class_test.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource to parse and generate abstract syntax tree nodes', 'generate AST nodes from a C++ token stream by calling AstBuilder.Generate() to yield parsed declarations and definitions', 'parse a C++ file and print all AST nodes by using BuilderFromSource with the file contents and iterating over Generate()', 'print all identifiers from C++ source files using PrintIndentifiers with a predicate function to filter which nodes to output', 'convert C++ tokens into Type AST nodes using TypeConverter.ToType() to parse base class and template type information', 'run the unittest test suite for gmock_class C++ mock generation', 'test the GenerateMethodsTest class to verify MOCK_METHOD macro generation from C++ source', 'test the GenerateMocksTest class to verify full mock class generation from C++ source', 'test the TestCase helper to strip leading whitespace and compare output ignoring indentation', 'test the GenerateMethodSource helper to convert C++ class source into Google Mock method macros', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token string is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by inspecting the ALL set constant', 'list C++ type keywords by inspecting the TYPES set constant', 'list C++ control flow keywords by inspecting the CONTROL set constant', 'run the C++ tokenizer on a source file to get a sequence of named tokens with types', 'create a Token object with a token type, name, start index, and end index', 'parse a C++ string literal from source code handling escaped quotes and backslashes', 'parse a C++ character literal from source code handling escaped single quotes', 'review the GetTokens generator function to understand how it tokenizes C++ identifiers, constants, and preprocessor directives', 'read the contents of a file and return it as a string or None on error', 'read a file silently without printing errors by setting print_error to False', 'read a file with debug mode enabled to see start and end token indices', 'summarize the ReadFile function that opens a file and returns its contents or None on IOError', 'review the ReadFile function and its error handling for IOError exceptions']
```

Usage

```
{'run_gmock_class_tests': 'run the unittest test suite for gmock_class C++ mock generation', 'test_GenerateMethodsTest': 'test the GenerateMethodsTest class to verify MOCK_METHOD macro generation from C++ source', 'test_GenerateMocksTest': 'test the GenerateMocksTest class to verify full mock class generation from C++ source', 'test_TestCase_strip_whitespace': 'test the TestCase helper to strip leading whitespace and compare output ignoring indentation', 'test_GenerateMethodSource': 'test the GenerateMethodSource helper to convert C++ class source into Google Mock method macros'}
```

## File: facebookresearch_reagent/serving/external/googletest/googlemock/scripts/generator/cpp/keywords.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource to parse and generate abstract syntax tree nodes', 'generate AST nodes from a C++ token stream by calling AstBuilder.Generate() to yield parsed declarations and definitions', 'parse a C++ file and print all AST nodes by using BuilderFromSource with the file contents and iterating over Generate()', 'print all identifiers from C++ source files using PrintIndentifiers with a predicate function to filter which nodes to output', 'convert C++ tokens into Type AST nodes using TypeConverter.ToType() to parse base class and template type information', 'run the unittest test suite for gmock_class C++ mock generation', 'test the GenerateMethodsTest class to verify MOCK_METHOD macro generation from C++ source', 'test the GenerateMocksTest class to verify full mock class generation from C++ source', 'test the TestCase helper to strip leading whitespace and compare output ignoring indentation', 'test the GenerateMethodSource helper to convert C++ class source into Google Mock method macros', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token string is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by inspecting the ALL set constant', 'list C++ type keywords by inspecting the TYPES set constant', 'list C++ control flow keywords by inspecting the CONTROL set constant', 'run the C++ tokenizer on a source file to get a sequence of named tokens with types', 'create a Token object with a token type, name, start index, and end index', 'parse a C++ string literal from source code handling escaped quotes and backslashes', 'parse a C++ character literal from source code handling escaped single quotes', 'review the GetTokens generator function to understand how it tokenizes C++ identifiers, constants, and preprocessor directives', 'read the contents of a file and return it as a string or None on error', 'read a file silently without printing errors by setting print_error to False', 'read a file with debug mode enabled to see start and end token indices', 'summarize the ReadFile function that opens a file and returns its contents or None on IOError', 'review the ReadFile function and its error handling for IOError exceptions']
```

Usage

```
{'check_is_keyword': 'check if a given token string is a C++ keyword using IsKeyword', 'check_is_builtin_type': 'check if a given token string is a C++ builtin type using IsBuiltinType', 'list_all_keywords': 'list all C++ keywords by inspecting the ALL set constant', 'list_type_keywords': 'list C++ type keywords by inspecting the TYPES set constant', 'list_control_keywords': 'list C++ control flow keywords by inspecting the CONTROL set constant'}
```

## File: facebookresearch_reagent/serving/external/googletest/googlemock/scripts/generator/cpp/tokenize.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource to parse and generate abstract syntax tree nodes', 'generate AST nodes from a C++ token stream by calling AstBuilder.Generate() to yield parsed declarations and definitions', 'parse a C++ file and print all AST nodes by using BuilderFromSource with the file contents and iterating over Generate()', 'print all identifiers from C++ source files using PrintIndentifiers with a predicate function to filter which nodes to output', 'convert C++ tokens into Type AST nodes using TypeConverter.ToType() to parse base class and template type information', 'run the unittest test suite for gmock_class C++ mock generation', 'test the GenerateMethodsTest class to verify MOCK_METHOD macro generation from C++ source', 'test the GenerateMocksTest class to verify full mock class generation from C++ source', 'test the TestCase helper to strip leading whitespace and compare output ignoring indentation', 'test the GenerateMethodSource helper to convert C++ class source into Google Mock method macros', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token string is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by inspecting the ALL set constant', 'list C++ type keywords by inspecting the TYPES set constant', 'list C++ control flow keywords by inspecting the CONTROL set constant', 'run the C++ tokenizer on a source file to get a sequence of named tokens with types', 'create a Token object with a token type, name, start index, and end index', 'parse a C++ string literal from source code handling escaped quotes and backslashes', 'parse a C++ character literal from source code handling escaped single quotes', 'review the GetTokens generator function to understand how it tokenizes C++ identifiers, constants, and preprocessor directives', 'read the contents of a file and return it as a string or None on error', 'read a file silently without printing errors by setting print_error to False', 'read a file with debug mode enabled to see start and end token indices', 'summarize the ReadFile function that opens a file and returns its contents or None on IOError', 'review the ReadFile function and its error handling for IOError exceptions']
```

Usage

```
{'tokenize_cpp_source': 'run the C++ tokenizer on a source file to get a sequence of named tokens with types', 'create_token': 'create a Token object with a token type, name, start index, and end index', 'parse_string_literal': 'parse a C++ string literal from source code handling escaped quotes and backslashes', 'parse_char_literal': 'parse a C++ character literal from source code handling escaped single quotes', 'review_tokenizer': 'review the GetTokens generator function to understand how it tokenizes C++ identifiers, constants, and preprocessor directives'}
```

## File: facebookresearch_reagent/serving/external/googletest/googlemock/scripts/generator/cpp/utils.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource to parse and generate abstract syntax tree nodes', 'generate AST nodes from a C++ token stream by calling AstBuilder.Generate() to yield parsed declarations and definitions', 'parse a C++ file and print all AST nodes by using BuilderFromSource with the file contents and iterating over Generate()', 'print all identifiers from C++ source files using PrintIndentifiers with a predicate function to filter which nodes to output', 'convert C++ tokens into Type AST nodes using TypeConverter.ToType() to parse base class and template type information', 'run the unittest test suite for gmock_class C++ mock generation', 'test the GenerateMethodsTest class to verify MOCK_METHOD macro generation from C++ source', 'test the GenerateMocksTest class to verify full mock class generation from C++ source', 'test the TestCase helper to strip leading whitespace and compare output ignoring indentation', 'test the GenerateMethodSource helper to convert C++ class source into Google Mock method macros', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token string is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by inspecting the ALL set constant', 'list C++ type keywords by inspecting the TYPES set constant', 'list C++ control flow keywords by inspecting the CONTROL set constant', 'run the C++ tokenizer on a source file to get a sequence of named tokens with types', 'create a Token object with a token type, name, start index, and end index', 'parse a C++ string literal from source code handling escaped quotes and backslashes', 'parse a C++ character literal from source code handling escaped single quotes', 'review the GetTokens generator function to understand how it tokenizes C++ identifiers, constants, and preprocessor directives', 'read the contents of a file and return it as a string or None on error', 'read a file silently without printing errors by setting print_error to False', 'read a file with debug mode enabled to see start and end token indices', 'summarize the ReadFile function that opens a file and returns its contents or None on IOError', 'review the ReadFile function and its error handling for IOError exceptions']
```

Usage

```
{'read_file_contents': 'read the contents of a file and return it as a string or None on error', 'read_file_with_error_suppression': 'read a file silently without printing errors by setting print_error to False', 'read_file_with_debug': 'read a file with debug mode enabled to see start and end token indices', 'summarize_ReadFile': 'summarize the ReadFile function that opens a file and returns its contents or None on IOError', 'review_ReadFile': 'review the ReadFile function and its error handling for IOError exceptions'}
```

