# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/third_party/upb/cmake/make_cmakelists.py

Prompts

```
['run the script to convert Bazel BUILD and WORKSPACE files into a CMakeLists.txt file', 'convert a Bazel cc_library rule into a CMake add_library command with dependencies', 'convert a Bazel workspace rule into a CMake project with C99 standard', 'strip leading colons from Bazel dependency names when generating CMake target_link_libraries', 'check if a given filename is a C or C++ source file by extension', 'run the staleness test to check if generated files match their targets', 'run the staleness test with --fix to overwrite missing or out-of-date files', 'test the TestFilesMatch class to verify generated files match target files', 'review the CheckFilesMatch function that compares generated files against target files', 'review the Config class that parses file lists and extracts target, package, and pattern', 'check whether each target file matches its corresponding generated file and return errors', 'fix missing or out-of-date files by copying generated files to their target locations', 'create a Config object from a file list with target name, package name, and pattern', 'generate a list of FilePair objects mapping target files to their generated counterparts', 'identify missing target files and stale files whose contents differ from generated versions']
```

Usage

```
{'generate_cmakelists_from_build': 'run the script to convert Bazel BUILD and WORKSPACE files into a CMakeLists.txt file', 'convert_cc_library_to_cmake': 'convert a Bazel cc_library rule into a CMake add_library command with dependencies', 'convert_workspace_to_cmake_project': 'convert a Bazel workspace rule into a CMake project with C99 standard', 'strip_colons_from_deps': 'strip leading colons from Bazel dependency names when generating CMake target_link_libraries', 'check_is_source_file': 'check if a given filename is a C or C++ source file by extension'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/upb/cmake/staleness_test.py

Prompts

```
['run the script to convert Bazel BUILD and WORKSPACE files into a CMakeLists.txt file', 'convert a Bazel cc_library rule into a CMake add_library command with dependencies', 'convert a Bazel workspace rule into a CMake project with C99 standard', 'strip leading colons from Bazel dependency names when generating CMake target_link_libraries', 'check if a given filename is a C or C++ source file by extension', 'run the staleness test to check if generated files match their targets', 'run the staleness test with --fix to overwrite missing or out-of-date files', 'test the TestFilesMatch class to verify generated files match target files', 'review the CheckFilesMatch function that compares generated files against target files', 'review the Config class that parses file lists and extracts target, package, and pattern', 'check whether each target file matches its corresponding generated file and return errors', 'fix missing or out-of-date files by copying generated files to their target locations', 'create a Config object from a file list with target name, package name, and pattern', 'generate a list of FilePair objects mapping target files to their generated counterparts', 'identify missing target files and stale files whose contents differ from generated versions']
```

Usage

```
{'run_staleness_test': 'run the staleness test to check if generated files match their targets', 'fix_stale_files': 'run the staleness test with --fix to overwrite missing or out-of-date files', 'test_TestFilesMatch': 'test the TestFilesMatch class to verify generated files match target files', 'review_CheckFilesMatch': 'review the CheckFilesMatch function that compares generated files against target files', 'review_Config': 'review the Config class that parses file lists and extracts target, package, and pattern'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/upb/cmake/staleness_test_lib.py

Prompts

```
['run the script to convert Bazel BUILD and WORKSPACE files into a CMakeLists.txt file', 'convert a Bazel cc_library rule into a CMake add_library command with dependencies', 'convert a Bazel workspace rule into a CMake project with C99 standard', 'strip leading colons from Bazel dependency names when generating CMake target_link_libraries', 'check if a given filename is a C or C++ source file by extension', 'run the staleness test to check if generated files match their targets', 'run the staleness test with --fix to overwrite missing or out-of-date files', 'test the TestFilesMatch class to verify generated files match target files', 'review the CheckFilesMatch function that compares generated files against target files', 'review the Config class that parses file lists and extracts target, package, and pattern', 'check whether each target file matches its corresponding generated file and return errors', 'fix missing or out-of-date files by copying generated files to their target locations', 'create a Config object from a file list with target name, package name, and pattern', 'generate a list of FilePair objects mapping target files to their generated counterparts', 'identify missing target files and stale files whose contents differ from generated versions']
```

Usage

```
{'check_files_match': 'check whether each target file matches its corresponding generated file and return errors', 'fix_files': 'fix missing or out-of-date files by copying generated files to their target locations', 'create_Config': 'create a Config object from a file list with target name, package name, and pattern', 'get_file_pairs': 'generate a list of FilePair objects mapping target files to their generated counterparts', 'get_missing_and_stale_files': 'identify missing target files and stale files whose contents differ from generated versions'}
```

