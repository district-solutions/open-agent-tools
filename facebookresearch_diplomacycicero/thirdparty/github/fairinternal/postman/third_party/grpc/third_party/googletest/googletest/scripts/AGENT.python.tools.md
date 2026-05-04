# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/googletest/googletest/scripts/common.py

Prompts

```
['run a shell command and return its stdout as a list of stripped lines', 'run svn info to get the project name and current SVN workspace root path', 'run GetSvnInfo and return the current SVN workspace trunk root path', 'run a check to determine if the current directory is in the googletest SVN repository', 'run a check to determine if the current directory is in the googlemock SVN repository', 'run the script to fuse Google Test source files into a single header and source file', 'run the script with a custom GTest root directory and output directory path', 'fuse all Google Test header files recursively into a single gtest.h output file', 'fuse all Google Test C++ source files recursively into a single gtest-all.cc output file', 'validate that the given directory contains valid Google Test root seed files']
```

Usage

```
{'run_GetCommandOutput': 'run a shell command and return its stdout as a list of stripped lines', 'run_GetSvnInfo': 'run svn info to get the project name and current SVN workspace root path', 'run_GetSvnTrunk': 'run GetSvnInfo and return the current SVN workspace trunk root path', 'run_IsInGTestSvn': 'run a check to determine if the current directory is in the googletest SVN repository', 'run_IsInGMockSvn': 'run a check to determine if the current directory is in the googlemock SVN repository'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/googletest/googletest/scripts/fuse_gtest_files.py

Prompts

```
['run a shell command and return its stdout as a list of stripped lines', 'run svn info to get the project name and current SVN workspace root path', 'run GetSvnInfo and return the current SVN workspace trunk root path', 'run a check to determine if the current directory is in the googletest SVN repository', 'run a check to determine if the current directory is in the googlemock SVN repository', 'run the script to fuse Google Test source files into a single header and source file', 'run the script with a custom GTest root directory and output directory path', 'fuse all Google Test header files recursively into a single gtest.h output file', 'fuse all Google Test C++ source files recursively into a single gtest-all.cc output file', 'validate that the given directory contains valid Google Test root seed files']
```

Usage

```
{'run_fuse_gtest': 'run the script to fuse Google Test source files into a single header and source file', 'run_fuse_gtest_with_root': 'run the script with a custom GTest root directory and output directory path', 'fuse_gtest_h': 'fuse all Google Test header files recursively into a single gtest.h output file', 'fuse_gtest_all_cc': 'fuse all Google Test C++ source files recursively into a single gtest-all.cc output file', 'validate_gtest_root_dir': 'validate that the given directory contains valid Google Test root seed files'}
```

