# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/upb/tools/amalgamate.py

Prompts

```
['run the amalgamate script to combine upb C source files into a single upb.h and upb.c output', 'create an Amalgamator instance with an output path to generate amalgamated upb header and source files', 'add an include search path to the Amalgamator so it can resolve relative include directives in source files', 'add a C source file to the Amalgamator which will be processed and written to the amalgamated output', 'finish the amalgamation process by writing port_undef.inc to both the header and source output files', 'run make_cmakelists.py with an output path argument to generate a CMakeLists.txt from BUILD and WORKSPACE files', 'build a CMake add_library target from a Bazel cc_library rule including source and header files', 'convert a Bazel WORKSPACE file into a CMake project() declaration using WorkspaceFileFunctions', 'add target_link_libraries entries to CMake output by stripping colons from Bazel dependency names', 'generate a CMake INTERFACE library target for Bazel cc_library rules that contain only header files', 'run the staleness test to check if generated files match their targets', 'run the staleness test with --fix flag to overwrite missing or out-of-date files', 'test the CheckFilesMatch function to validate generated files match corresponding target files', 'test the FixFiles function to copy generated files over stale or missing target files', 'review the Config class that parses file lists and extracts target name, package name, and pattern', 'create a Config object from a file list to parse target name, package name, and pattern', 'run CheckFilesMatch on a Config to detect missing or out-of-date generated files', 'run FixFiles on a Config to overwrite missing or stale target files with generated ones', 'test _GetFilePairs to generate a list of target and generated file pair objects', 'test _GetMissingAndStaleFiles to classify file pairs as missing or stale by comparing contents']
```

Usage

```
{'run_amalgamate_upb_sources': 'run the amalgamate script to combine upb C source files into a single upb.h and upb.c output', 'create_amalgamator_instance': 'create an Amalgamator instance with an output path to generate amalgamated upb header and source files', 'add_include_path': 'add an include search path to the Amalgamator so it can resolve relative include directives in source files', 'add_src_file': 'add a C source file to the Amalgamator which will be processed and written to the amalgamated output', 'finish_amalgamation': 'finish the amalgamation process by writing port_undef.inc to both the header and source output files'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/upb/tools/make_cmakelists.py

Prompts

```
['run the amalgamate script to combine upb C source files into a single upb.h and upb.c output', 'create an Amalgamator instance with an output path to generate amalgamated upb header and source files', 'add an include search path to the Amalgamator so it can resolve relative include directives in source files', 'add a C source file to the Amalgamator which will be processed and written to the amalgamated output', 'finish the amalgamation process by writing port_undef.inc to both the header and source output files', 'run make_cmakelists.py with an output path argument to generate a CMakeLists.txt from BUILD and WORKSPACE files', 'build a CMake add_library target from a Bazel cc_library rule including source and header files', 'convert a Bazel WORKSPACE file into a CMake project() declaration using WorkspaceFileFunctions', 'add target_link_libraries entries to CMake output by stripping colons from Bazel dependency names', 'generate a CMake INTERFACE library target for Bazel cc_library rules that contain only header files', 'run the staleness test to check if generated files match their targets', 'run the staleness test with --fix flag to overwrite missing or out-of-date files', 'test the CheckFilesMatch function to validate generated files match corresponding target files', 'test the FixFiles function to copy generated files over stale or missing target files', 'review the Config class that parses file lists and extracts target name, package name, and pattern', 'create a Config object from a file list to parse target name, package name, and pattern', 'run CheckFilesMatch on a Config to detect missing or out-of-date generated files', 'run FixFiles on a Config to overwrite missing or stale target files with generated ones', 'test _GetFilePairs to generate a list of target and generated file pair objects', 'test _GetMissingAndStaleFiles to classify file pairs as missing or stale by comparing contents']
```

Usage

```
{'run_make_cmakelists': 'run make_cmakelists.py with an output path argument to generate a CMakeLists.txt from BUILD and WORKSPACE files', 'build_cc_library_cmake': 'build a CMake add_library target from a Bazel cc_library rule including source and header files', 'convert_workspace_to_cmake': 'convert a Bazel WORKSPACE file into a CMake project() declaration using WorkspaceFileFunctions', 'add_deps_target_link': 'add target_link_libraries entries to CMake output by stripping colons from Bazel dependency names', 'generate_header_only_library': 'generate a CMake INTERFACE library target for Bazel cc_library rules that contain only header files'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/upb/tools/staleness_test.py

Prompts

```
['run the amalgamate script to combine upb C source files into a single upb.h and upb.c output', 'create an Amalgamator instance with an output path to generate amalgamated upb header and source files', 'add an include search path to the Amalgamator so it can resolve relative include directives in source files', 'add a C source file to the Amalgamator which will be processed and written to the amalgamated output', 'finish the amalgamation process by writing port_undef.inc to both the header and source output files', 'run make_cmakelists.py with an output path argument to generate a CMakeLists.txt from BUILD and WORKSPACE files', 'build a CMake add_library target from a Bazel cc_library rule including source and header files', 'convert a Bazel WORKSPACE file into a CMake project() declaration using WorkspaceFileFunctions', 'add target_link_libraries entries to CMake output by stripping colons from Bazel dependency names', 'generate a CMake INTERFACE library target for Bazel cc_library rules that contain only header files', 'run the staleness test to check if generated files match their targets', 'run the staleness test with --fix flag to overwrite missing or out-of-date files', 'test the CheckFilesMatch function to validate generated files match corresponding target files', 'test the FixFiles function to copy generated files over stale or missing target files', 'review the Config class that parses file lists and extracts target name, package name, and pattern', 'create a Config object from a file list to parse target name, package name, and pattern', 'run CheckFilesMatch on a Config to detect missing or out-of-date generated files', 'run FixFiles on a Config to overwrite missing or stale target files with generated ones', 'test _GetFilePairs to generate a list of target and generated file pair objects', 'test _GetMissingAndStaleFiles to classify file pairs as missing or stale by comparing contents']
```

Usage

```
{'run_staleness_test': 'run the staleness test to check if generated files match their targets', 'fix_stale_files': 'run the staleness test with --fix flag to overwrite missing or out-of-date files', 'test_CheckFilesMatch': 'test the CheckFilesMatch function to validate generated files match corresponding target files', 'test_FixFiles': 'test the FixFiles function to copy generated files over stale or missing target files', 'review_Config_class': 'review the Config class that parses file lists and extracts target name, package name, and pattern'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/upb/tools/staleness_test_lib.py

Prompts

```
['run the amalgamate script to combine upb C source files into a single upb.h and upb.c output', 'create an Amalgamator instance with an output path to generate amalgamated upb header and source files', 'add an include search path to the Amalgamator so it can resolve relative include directives in source files', 'add a C source file to the Amalgamator which will be processed and written to the amalgamated output', 'finish the amalgamation process by writing port_undef.inc to both the header and source output files', 'run make_cmakelists.py with an output path argument to generate a CMakeLists.txt from BUILD and WORKSPACE files', 'build a CMake add_library target from a Bazel cc_library rule including source and header files', 'convert a Bazel WORKSPACE file into a CMake project() declaration using WorkspaceFileFunctions', 'add target_link_libraries entries to CMake output by stripping colons from Bazel dependency names', 'generate a CMake INTERFACE library target for Bazel cc_library rules that contain only header files', 'run the staleness test to check if generated files match their targets', 'run the staleness test with --fix flag to overwrite missing or out-of-date files', 'test the CheckFilesMatch function to validate generated files match corresponding target files', 'test the FixFiles function to copy generated files over stale or missing target files', 'review the Config class that parses file lists and extracts target name, package name, and pattern', 'create a Config object from a file list to parse target name, package name, and pattern', 'run CheckFilesMatch on a Config to detect missing or out-of-date generated files', 'run FixFiles on a Config to overwrite missing or stale target files with generated ones', 'test _GetFilePairs to generate a list of target and generated file pair objects', 'test _GetMissingAndStaleFiles to classify file pairs as missing or stale by comparing contents']
```

Usage

```
{'create_Config': 'create a Config object from a file list to parse target name, package name, and pattern', 'run_CheckFilesMatch': 'run CheckFilesMatch on a Config to detect missing or out-of-date generated files', 'run_FixFiles': 'run FixFiles on a Config to overwrite missing or stale target files with generated ones', 'test_GetFilePairs': 'test _GetFilePairs to generate a list of target and generated file pair objects', 'test_GetMissingAndStaleFiles': 'test _GetMissingAndStaleFiles to classify file pairs as missing or stale by comparing contents'}
```

