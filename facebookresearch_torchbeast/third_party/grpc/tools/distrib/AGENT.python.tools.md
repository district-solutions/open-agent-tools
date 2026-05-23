# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/tools/distrib/check_copyright.py

Prompts

```
['run the copyright checker script to validate license headers across all source files in the repository', 'run the copyright checker in precommit mode to validate only modified files staged in git', 'run the copyright checker with list output mode to show only filenames without details', 'review the LICENSE_PREFIX dictionary that maps file extensions to regex patterns for license header validation', 'review the _EXEMPT frozenset listing files excluded from copyright header checks', 'run the include guard checker on all C header files in the gRPC repository', 'run the include guard checker with the --fix flag to automatically correct invalid guards', 'run the include guard checker in precommit mode to check only changed files', 'build the expected preprocessor guard name from a given C header file path', 'check a single C header file for correct ifndef, define, and endif preprocessor guards', 'run bazel build with compilation database aspect to generate compile_commands.json for all targets', 'filter compilation database entries to exclude headers, generated files, or external dependencies', 'modify compiler commands to remove C++11 flags, fix VSCode iquote issues, or strip system headers', 'process and write a filtered compilation database to compile_commands.json with modified commands', 'check if a filename is a C++ header file by testing for .h, .hh, .hpp, or .hxx extensions']
```

Usage

```
{'run_copyright_check': 'run the copyright checker script to validate license headers across all source files in the repository', 'run_copyright_check_precommit': 'run the copyright checker in precommit mode to validate only modified files staged in git', 'run_copyright_check_list_output': 'run the copyright checker with list output mode to show only filenames without details', 'review_LICENSE_PREFIX': 'review the LICENSE_PREFIX dictionary that maps file extensions to regex patterns for license header validation', 'review_EXEMPT': 'review the _EXEMPT frozenset listing files excluded from copyright header checks'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/distrib/check_include_guards.py

Prompts

```
['run the copyright checker script to validate license headers across all source files in the repository', 'run the copyright checker in precommit mode to validate only modified files staged in git', 'run the copyright checker with list output mode to show only filenames without details', 'review the LICENSE_PREFIX dictionary that maps file extensions to regex patterns for license header validation', 'review the _EXEMPT frozenset listing files excluded from copyright header checks', 'run the include guard checker on all C header files in the gRPC repository', 'run the include guard checker with the --fix flag to automatically correct invalid guards', 'run the include guard checker in precommit mode to check only changed files', 'build the expected preprocessor guard name from a given C header file path', 'check a single C header file for correct ifndef, define, and endif preprocessor guards', 'run bazel build with compilation database aspect to generate compile_commands.json for all targets', 'filter compilation database entries to exclude headers, generated files, or external dependencies', 'modify compiler commands to remove C++11 flags, fix VSCode iquote issues, or strip system headers', 'process and write a filtered compilation database to compile_commands.json with modified commands', 'check if a filename is a C++ header file by testing for .h, .hh, .hpp, or .hxx extensions']
```

Usage

```
{'run_check_include_guards': 'run the include guard checker on all C header files in the gRPC repository', 'run_check_include_guards_fix': 'run the include guard checker with the --fix flag to automatically correct invalid guards', 'run_check_include_guards_precommit': 'run the include guard checker in precommit mode to check only changed files', 'build_valid_guard': 'build the expected preprocessor guard name from a given C header file path', 'GuardValidator_check': 'check a single C header file for correct ifndef, define, and endif preprocessor guards'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/distrib/gen_compilation_database.py

Prompts

```
['run the copyright checker script to validate license headers across all source files in the repository', 'run the copyright checker in precommit mode to validate only modified files staged in git', 'run the copyright checker with list output mode to show only filenames without details', 'review the LICENSE_PREFIX dictionary that maps file extensions to regex patterns for license header validation', 'review the _EXEMPT frozenset listing files excluded from copyright header checks', 'run the include guard checker on all C header files in the gRPC repository', 'run the include guard checker with the --fix flag to automatically correct invalid guards', 'run the include guard checker in precommit mode to check only changed files', 'build the expected preprocessor guard name from a given C header file path', 'check a single C header file for correct ifndef, define, and endif preprocessor guards', 'run bazel build with compilation database aspect to generate compile_commands.json for all targets', 'filter compilation database entries to exclude headers, generated files, or external dependencies', 'modify compiler commands to remove C++11 flags, fix VSCode iquote issues, or strip system headers', 'process and write a filtered compilation database to compile_commands.json with modified commands', 'check if a filename is a C++ header file by testing for .h, .hh, .hpp, or .hxx extensions']
```

Usage

```
{'generate_compilation_database': 'run bazel build with compilation database aspect to generate compile_commands.json for all targets', 'filter_compile_targets': 'filter compilation database entries to exclude headers, generated files, or external dependencies', 'modify_compile_command': 'modify compiler commands to remove C++11 flags, fix VSCode iquote issues, or strip system headers', 'fix_compilation_database': 'process and write a filtered compilation database to compile_commands.json with modified commands', 'check_header_file': 'check if a filename is a C++ header file by testing for .h, .hh, .hpp, or .hxx extensions'}
```

