# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/upb/tools/amalgamate.py

Prompts

```
['run the amalgamate script to combine upb C source files into a single upb.h and upb.c output', 'create an Amalgamator instance with an output path to generate amalgamated upb header and source files', 'add an include search path to the Amalgamator so it can resolve relative file references', 'add a C source file to the Amalgamator for processing and inclusion in the amalgamated output', 'parse a C preprocessor include directive line and extract the included file path', 'run make_cmakelists.py with an output path argument to generate a CMakeLists.txt from BUILD and WORKSPACE files', 'convert Bazel BUILD and WORKSPACE files into a CMakeLists.txt file using the converter script', 'review the cc_library function to understand how it generates add_library CMake commands for source and header-only libraries', 'review the StripColons function that removes leading colons from Bazel dependency paths for CMake compatibility', 'review the IsSourceFile function that checks if a filename ends with .c or .cc extensions', 'run the staleness test to check if generated files match their targets', 'run the staleness test with --fix to overwrite missing or out-of-date files', 'test the CheckFilesMatch function to verify generated files match target files', 'review the Config class that parses file lists and extracts target, package, and pattern', 'refactor the FixFiles function to copy generated files over stale or missing targets', 'check whether each target file matches its corresponding generated file and return errors', 'fix missing or out-of-date files by copying generated files over stale targets', 'create a Config object from a file list with target name, package name, and pattern', 'generate a list of FilePair objects mapping target files to their generated counterparts', 'identify missing and stale files by comparing target contents against generated contents']
```

Usage

```
{'run_amalgamate_upb_sources': 'run the amalgamate script to combine upb C source files into a single upb.h and upb.c output', 'create_amalgamator_instance': 'create an Amalgamator instance with an output path to generate amalgamated upb header and source files', 'add_include_path_amalgamator': 'add an include search path to the Amalgamator so it can resolve relative file references', 'add_src_amalgamator': 'add a C source file to the Amalgamator for processing and inclusion in the amalgamated output', 'parse_include_directive': 'parse a C preprocessor include directive line and extract the included file path'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/upb/tools/make_cmakelists.py

Prompts

```
['run the amalgamate script to combine upb C source files into a single upb.h and upb.c output', 'create an Amalgamator instance with an output path to generate amalgamated upb header and source files', 'add an include search path to the Amalgamator so it can resolve relative file references', 'add a C source file to the Amalgamator for processing and inclusion in the amalgamated output', 'parse a C preprocessor include directive line and extract the included file path', 'run make_cmakelists.py with an output path argument to generate a CMakeLists.txt from BUILD and WORKSPACE files', 'convert Bazel BUILD and WORKSPACE files into a CMakeLists.txt file using the converter script', 'review the cc_library function to understand how it generates add_library CMake commands for source and header-only libraries', 'review the StripColons function that removes leading colons from Bazel dependency paths for CMake compatibility', 'review the IsSourceFile function that checks if a filename ends with .c or .cc extensions', 'run the staleness test to check if generated files match their targets', 'run the staleness test with --fix to overwrite missing or out-of-date files', 'test the CheckFilesMatch function to verify generated files match target files', 'review the Config class that parses file lists and extracts target, package, and pattern', 'refactor the FixFiles function to copy generated files over stale or missing targets', 'check whether each target file matches its corresponding generated file and return errors', 'fix missing or out-of-date files by copying generated files over stale targets', 'create a Config object from a file list with target name, package name, and pattern', 'generate a list of FilePair objects mapping target files to their generated counterparts', 'identify missing and stale files by comparing target contents against generated contents']
```

Usage

```
{'run_make_cmakelists': 'run make_cmakelists.py with an output path argument to generate a CMakeLists.txt from BUILD and WORKSPACE files', 'convert_build_to_cmake': 'convert Bazel BUILD and WORKSPACE files into a CMakeLists.txt file using the converter script', 'review_cc_library': 'review the cc_library function to understand how it generates add_library CMake commands for source and header-only libraries', 'review_strip_colons': 'review the StripColons function that removes leading colons from Bazel dependency paths for CMake compatibility', 'review_is_source_file': 'review the IsSourceFile function that checks if a filename ends with .c or .cc extensions'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/upb/tools/staleness_test.py

Prompts

```
['run the amalgamate script to combine upb C source files into a single upb.h and upb.c output', 'create an Amalgamator instance with an output path to generate amalgamated upb header and source files', 'add an include search path to the Amalgamator so it can resolve relative file references', 'add a C source file to the Amalgamator for processing and inclusion in the amalgamated output', 'parse a C preprocessor include directive line and extract the included file path', 'run make_cmakelists.py with an output path argument to generate a CMakeLists.txt from BUILD and WORKSPACE files', 'convert Bazel BUILD and WORKSPACE files into a CMakeLists.txt file using the converter script', 'review the cc_library function to understand how it generates add_library CMake commands for source and header-only libraries', 'review the StripColons function that removes leading colons from Bazel dependency paths for CMake compatibility', 'review the IsSourceFile function that checks if a filename ends with .c or .cc extensions', 'run the staleness test to check if generated files match their targets', 'run the staleness test with --fix to overwrite missing or out-of-date files', 'test the CheckFilesMatch function to verify generated files match target files', 'review the Config class that parses file lists and extracts target, package, and pattern', 'refactor the FixFiles function to copy generated files over stale or missing targets', 'check whether each target file matches its corresponding generated file and return errors', 'fix missing or out-of-date files by copying generated files over stale targets', 'create a Config object from a file list with target name, package name, and pattern', 'generate a list of FilePair objects mapping target files to their generated counterparts', 'identify missing and stale files by comparing target contents against generated contents']
```

Usage

```
{'run_staleness_test': 'run the staleness test to check if generated files match their targets', 'fix_stale_files': 'run the staleness test with --fix to overwrite missing or out-of-date files', 'test_CheckFilesMatch': 'test the CheckFilesMatch function to verify generated files match target files', 'review_Config_class': 'review the Config class that parses file lists and extracts target, package, and pattern', 'refactor_FixFiles': 'refactor the FixFiles function to copy generated files over stale or missing targets'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/upb/tools/staleness_test_lib.py

Prompts

```
['run the amalgamate script to combine upb C source files into a single upb.h and upb.c output', 'create an Amalgamator instance with an output path to generate amalgamated upb header and source files', 'add an include search path to the Amalgamator so it can resolve relative file references', 'add a C source file to the Amalgamator for processing and inclusion in the amalgamated output', 'parse a C preprocessor include directive line and extract the included file path', 'run make_cmakelists.py with an output path argument to generate a CMakeLists.txt from BUILD and WORKSPACE files', 'convert Bazel BUILD and WORKSPACE files into a CMakeLists.txt file using the converter script', 'review the cc_library function to understand how it generates add_library CMake commands for source and header-only libraries', 'review the StripColons function that removes leading colons from Bazel dependency paths for CMake compatibility', 'review the IsSourceFile function that checks if a filename ends with .c or .cc extensions', 'run the staleness test to check if generated files match their targets', 'run the staleness test with --fix to overwrite missing or out-of-date files', 'test the CheckFilesMatch function to verify generated files match target files', 'review the Config class that parses file lists and extracts target, package, and pattern', 'refactor the FixFiles function to copy generated files over stale or missing targets', 'check whether each target file matches its corresponding generated file and return errors', 'fix missing or out-of-date files by copying generated files over stale targets', 'create a Config object from a file list with target name, package name, and pattern', 'generate a list of FilePair objects mapping target files to their generated counterparts', 'identify missing and stale files by comparing target contents against generated contents']
```

Usage

```
{'check_files_match': 'check whether each target file matches its corresponding generated file and return errors', 'fix_files': 'fix missing or out-of-date files by copying generated files over stale targets', 'create_Config': 'create a Config object from a file list with target name, package name, and pattern', 'get_file_pairs': 'generate a list of FilePair objects mapping target files to their generated counterparts', 'get_missing_and_stale': 'identify missing and stale files by comparing target contents against generated contents'}
```

