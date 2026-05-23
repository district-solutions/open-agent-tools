# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/third_party/moolib/src/tensorpipe/third_party/googletest/googlemock/scripts/generator/cpp/ast.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse a C++ file and print its full AST by running the module as a script with a filename argument', 'print all identifiers from a C++ source file that match a given predicate using PrintIndentifiers', 'print identifiers from multiple C++ source files using PrintAllIndentifiers with a filter predicate', 'review the AST node classes like Class, Function, Method, Type, and Typedef to understand C++ structure representation', 'run the unittest test suite for gmock_class generator to verify mock generation', 'convert C++ class source to Google Mock MOCK_METHOD macro output lines', 'convert C++ source to complete Google Mock mock class source with MOCK_METHOD macros', 'test that virtual methods are correctly converted to MOCK_METHOD macros ignoring constructors', 'test that templated C++ classes are correctly converted to mock classes with renamed template params', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by importing the ALL set from keywords.py', 'list C++ type keywords by importing the TYPES set from keywords.py', 'list C++ control flow keywords by importing the CONTROL set from keywords.py', 'run GetTokens on a C++ source string to yield a sequence of Token objects', 'create a Token instance with token_type, name, start index, and end index', 'run the module as a script to tokenize C++ files and print token types to stdout', 'use _GetString to find the closing quote of a C++ string literal with escapes', 'use _GetChar to find the closing quote of a C++ char literal with escapes', 'read a file and return its contents using the ReadFile function', 'read a file with optional error printing using ReadFile with print_error parameter', 'review the ReadFile function that reads files and handles IOError exceptions', 'summarize the ReadFile utility function for reading file contents safely', 'test the ReadFile function by reading a file and checking its returned contents']
```

Usage

```
{'build_cpp_ast_from_source': 'build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse_cpp_file_cli': 'parse a C++ file and print its full AST by running the module as a script with a filename argument', 'print_cpp_identifiers': 'print all identifiers from a C++ source file that match a given predicate using PrintIndentifiers', 'print_identifiers_multiple_files': 'print identifiers from multiple C++ source files using PrintAllIndentifiers with a filter predicate', 'review_ast_node_classes': 'review the AST node classes like Class, Function, Method, Type, and Typedef to understand C++ structure representation'}
```

## File: facebookresearch_rlmeta/third_party/moolib/src/tensorpipe/third_party/googletest/googlemock/scripts/generator/cpp/gmock_class_test.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse a C++ file and print its full AST by running the module as a script with a filename argument', 'print all identifiers from a C++ source file that match a given predicate using PrintIndentifiers', 'print identifiers from multiple C++ source files using PrintAllIndentifiers with a filter predicate', 'review the AST node classes like Class, Function, Method, Type, and Typedef to understand C++ structure representation', 'run the unittest test suite for gmock_class generator to verify mock generation', 'convert C++ class source to Google Mock MOCK_METHOD macro output lines', 'convert C++ source to complete Google Mock mock class source with MOCK_METHOD macros', 'test that virtual methods are correctly converted to MOCK_METHOD macros ignoring constructors', 'test that templated C++ classes are correctly converted to mock classes with renamed template params', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by importing the ALL set from keywords.py', 'list C++ type keywords by importing the TYPES set from keywords.py', 'list C++ control flow keywords by importing the CONTROL set from keywords.py', 'run GetTokens on a C++ source string to yield a sequence of Token objects', 'create a Token instance with token_type, name, start index, and end index', 'run the module as a script to tokenize C++ files and print token types to stdout', 'use _GetString to find the closing quote of a C++ string literal with escapes', 'use _GetChar to find the closing quote of a C++ char literal with escapes', 'read a file and return its contents using the ReadFile function', 'read a file with optional error printing using ReadFile with print_error parameter', 'review the ReadFile function that reads files and handles IOError exceptions', 'summarize the ReadFile utility function for reading file contents safely', 'test the ReadFile function by reading a file and checking its returned contents']
```

Usage

```
{'run_gmock_class_tests': 'run the unittest test suite for gmock_class generator to verify mock generation', 'generate_mock_methods_from_cpp': 'convert C++ class source to Google Mock MOCK_METHOD macro output lines', 'generate_full_mock_classes': 'convert C++ source to complete Google Mock mock class source with MOCK_METHOD macros', 'test_mock_method_generation': 'test that virtual methods are correctly converted to MOCK_METHOD macros ignoring constructors', 'test_mock_generation_with_templates': 'test that templated C++ classes are correctly converted to mock classes with renamed template params'}
```

## File: facebookresearch_rlmeta/third_party/moolib/src/tensorpipe/third_party/googletest/googlemock/scripts/generator/cpp/keywords.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse a C++ file and print its full AST by running the module as a script with a filename argument', 'print all identifiers from a C++ source file that match a given predicate using PrintIndentifiers', 'print identifiers from multiple C++ source files using PrintAllIndentifiers with a filter predicate', 'review the AST node classes like Class, Function, Method, Type, and Typedef to understand C++ structure representation', 'run the unittest test suite for gmock_class generator to verify mock generation', 'convert C++ class source to Google Mock MOCK_METHOD macro output lines', 'convert C++ source to complete Google Mock mock class source with MOCK_METHOD macros', 'test that virtual methods are correctly converted to MOCK_METHOD macros ignoring constructors', 'test that templated C++ classes are correctly converted to mock classes with renamed template params', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by importing the ALL set from keywords.py', 'list C++ type keywords by importing the TYPES set from keywords.py', 'list C++ control flow keywords by importing the CONTROL set from keywords.py', 'run GetTokens on a C++ source string to yield a sequence of Token objects', 'create a Token instance with token_type, name, start index, and end index', 'run the module as a script to tokenize C++ files and print token types to stdout', 'use _GetString to find the closing quote of a C++ string literal with escapes', 'use _GetChar to find the closing quote of a C++ char literal with escapes', 'read a file and return its contents using the ReadFile function', 'read a file with optional error printing using ReadFile with print_error parameter', 'review the ReadFile function that reads files and handles IOError exceptions', 'summarize the ReadFile utility function for reading file contents safely', 'test the ReadFile function by reading a file and checking its returned contents']
```

Usage

```
{'check_if_cpp_keyword': 'check if a given token string is a C++ keyword using IsKeyword', 'check_if_builtin_type': 'check if a given token is a C++ builtin type using IsBuiltinType', 'list_all_cpp_keywords': 'list all C++ keywords by importing the ALL set from keywords.py', 'list_cpp_types': 'list C++ type keywords by importing the TYPES set from keywords.py', 'list_cpp_control_keywords': 'list C++ control flow keywords by importing the CONTROL set from keywords.py'}
```

## File: facebookresearch_rlmeta/third_party/moolib/src/tensorpipe/third_party/googletest/googlemock/scripts/generator/cpp/tokenize.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse a C++ file and print its full AST by running the module as a script with a filename argument', 'print all identifiers from a C++ source file that match a given predicate using PrintIndentifiers', 'print identifiers from multiple C++ source files using PrintAllIndentifiers with a filter predicate', 'review the AST node classes like Class, Function, Method, Type, and Typedef to understand C++ structure representation', 'run the unittest test suite for gmock_class generator to verify mock generation', 'convert C++ class source to Google Mock MOCK_METHOD macro output lines', 'convert C++ source to complete Google Mock mock class source with MOCK_METHOD macros', 'test that virtual methods are correctly converted to MOCK_METHOD macros ignoring constructors', 'test that templated C++ classes are correctly converted to mock classes with renamed template params', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by importing the ALL set from keywords.py', 'list C++ type keywords by importing the TYPES set from keywords.py', 'list C++ control flow keywords by importing the CONTROL set from keywords.py', 'run GetTokens on a C++ source string to yield a sequence of Token objects', 'create a Token instance with token_type, name, start index, and end index', 'run the module as a script to tokenize C++ files and print token types to stdout', 'use _GetString to find the closing quote of a C++ string literal with escapes', 'use _GetChar to find the closing quote of a C++ char literal with escapes', 'read a file and return its contents using the ReadFile function', 'read a file with optional error printing using ReadFile with print_error parameter', 'review the ReadFile function that reads files and handles IOError exceptions', 'summarize the ReadFile utility function for reading file contents safely', 'test the ReadFile function by reading a file and checking its returned contents']
```

Usage

```
{'tokenize_cpp_source': 'run GetTokens on a C++ source string to yield a sequence of Token objects', 'create_token_object': 'create a Token instance with token_type, name, start index, and end index', 'run_cli_tokenizer': 'run the module as a script to tokenize C++ files and print token types to stdout', 'parse_string_literals': 'use _GetString to find the closing quote of a C++ string literal with escapes', 'parse_char_literals': 'use _GetChar to find the closing quote of a C++ char literal with escapes'}
```

## File: facebookresearch_rlmeta/third_party/moolib/src/tensorpipe/third_party/googletest/googlemock/scripts/generator/cpp/utils.py

Prompts

```
['build an AST from C++ source code using BuilderFromSource and iterate over nodes with Generate', 'parse a C++ file and print its full AST by running the module as a script with a filename argument', 'print all identifiers from a C++ source file that match a given predicate using PrintIndentifiers', 'print identifiers from multiple C++ source files using PrintAllIndentifiers with a filter predicate', 'review the AST node classes like Class, Function, Method, Type, and Typedef to understand C++ structure representation', 'run the unittest test suite for gmock_class generator to verify mock generation', 'convert C++ class source to Google Mock MOCK_METHOD macro output lines', 'convert C++ source to complete Google Mock mock class source with MOCK_METHOD macros', 'test that virtual methods are correctly converted to MOCK_METHOD macros ignoring constructors', 'test that templated C++ classes are correctly converted to mock classes with renamed template params', 'check if a given token string is a C++ keyword using IsKeyword', 'check if a given token is a C++ builtin type using IsBuiltinType', 'list all C++ keywords by importing the ALL set from keywords.py', 'list C++ type keywords by importing the TYPES set from keywords.py', 'list C++ control flow keywords by importing the CONTROL set from keywords.py', 'run GetTokens on a C++ source string to yield a sequence of Token objects', 'create a Token instance with token_type, name, start index, and end index', 'run the module as a script to tokenize C++ files and print token types to stdout', 'use _GetString to find the closing quote of a C++ string literal with escapes', 'use _GetChar to find the closing quote of a C++ char literal with escapes', 'read a file and return its contents using the ReadFile function', 'read a file with optional error printing using ReadFile with print_error parameter', 'review the ReadFile function that reads files and handles IOError exceptions', 'summarize the ReadFile utility function for reading file contents safely', 'test the ReadFile function by reading a file and checking its returned contents']
```

Usage

```
{'read_file_contents': 'read a file and return its contents using the ReadFile function', 'read_file_with_error_handling': 'read a file with optional error printing using ReadFile with print_error parameter', 'review_ReadFile': 'review the ReadFile function that reads files and handles IOError exceptions', 'summarize_ReadFile': 'summarize the ReadFile utility function for reading file contents safely', 'test_ReadFile': 'test the ReadFile function by reading a file and checking its returned contents'}
```

