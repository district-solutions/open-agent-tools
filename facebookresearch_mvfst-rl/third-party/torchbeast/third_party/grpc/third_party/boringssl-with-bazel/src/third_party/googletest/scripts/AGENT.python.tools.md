# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/boringssl-with-bazel/src/third_party/googletest/scripts/common.py

Prompts

```
['run a shell command and return its stdout as a list of stripped lines', 'run svn info to get the project name and current SVN workspace root path', 'run GetSvnInfo and return the current SVN workspace trunk root path', 'run a check to determine if the current directory is in the googletest SVN repository', 'run a check to determine if the current directory is in the googlemock SVN repository', 'run fuse_gtest_files.py with an output directory to fuse Google Test source into single header and source files', 'run fuse_gtest_files.py with a gtest root directory and output directory to fuse all gtest files', 'fuse all gtest header files recursively into a single gtest.h output file', 'fuse all gtest source files recursively into a single gtest-all.cc output file', 'validate that a given directory contains the required gtest seed header and source files']
```

Usage

```
{'run_GetCommandOutput': 'run a shell command and return its stdout as a list of stripped lines', 'run_GetSvnInfo': 'run svn info to get the project name and current SVN workspace root path', 'run_GetSvnTrunk': 'run GetSvnInfo and return the current SVN workspace trunk root path', 'run_IsInGTestSvn': 'run a check to determine if the current directory is in the googletest SVN repository', 'run_IsInGMockSvn': 'run a check to determine if the current directory is in the googlemock SVN repository'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/boringssl-with-bazel/src/third_party/googletest/scripts/fuse_gtest_files.py

Prompts

```
['run a shell command and return its stdout as a list of stripped lines', 'run svn info to get the project name and current SVN workspace root path', 'run GetSvnInfo and return the current SVN workspace trunk root path', 'run a check to determine if the current directory is in the googletest SVN repository', 'run a check to determine if the current directory is in the googlemock SVN repository', 'run fuse_gtest_files.py with an output directory to fuse Google Test source into single header and source files', 'run fuse_gtest_files.py with a gtest root directory and output directory to fuse all gtest files', 'fuse all gtest header files recursively into a single gtest.h output file', 'fuse all gtest source files recursively into a single gtest-all.cc output file', 'validate that a given directory contains the required gtest seed header and source files']
```

Usage

```
{'run_fuse_gtest': 'run fuse_gtest_files.py with an output directory to fuse Google Test source into single header and source files', 'run_fuse_gtest_with_root': 'run fuse_gtest_files.py with a gtest root directory and output directory to fuse all gtest files', 'fuse_gtest_h': 'fuse all gtest header files recursively into a single gtest.h output file', 'fuse_gtest_all_cc': 'fuse all gtest source files recursively into a single gtest-all.cc output file', 'validate_gtest_root_dir': 'validate that a given directory contains the required gtest seed header and source files'}
```

