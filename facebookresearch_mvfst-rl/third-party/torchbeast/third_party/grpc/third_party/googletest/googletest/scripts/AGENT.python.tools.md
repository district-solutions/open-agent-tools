# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/googletest/googletest/scripts/common.py

Prompts

```
['run a shell command and return its stdout as a list of stripped lines', 'run svn info to get the project name and current SVN workspace root path', 'run GetSvnInfo and return the current SVN workspace trunk root path', 'run a check to determine if the current directory is inside the googletest SVN repository', 'run a check to determine if the current directory is inside the googlemock SVN repository', 'run fuse_gtest_files.py to merge all Google Test source files into a single header and source file', 'run fuse_gtest_files.py with a custom GTEST_ROOT_DIR and OUTPUT_DIR to fuse gtest into a new location', 'fuse all gtest header files recursively into a single gtest.h output file', 'fuse all gtest source files recursively into a single gtest-all.cc output file', 'validate that a given directory contains the required gtest seed files before fusing']
```

Usage

```
{'run_GetCommandOutput': 'run a shell command and return its stdout as a list of stripped lines', 'run_GetSvnInfo': 'run svn info to get the project name and current SVN workspace root path', 'run_GetSvnTrunk': 'run GetSvnInfo and return the current SVN workspace trunk root path', 'run_IsInGTestSvn': 'run a check to determine if the current directory is inside the googletest SVN repository', 'run_IsInGMockSvn': 'run a check to determine if the current directory is inside the googlemock SVN repository'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/googletest/googletest/scripts/fuse_gtest_files.py

Prompts

```
['run a shell command and return its stdout as a list of stripped lines', 'run svn info to get the project name and current SVN workspace root path', 'run GetSvnInfo and return the current SVN workspace trunk root path', 'run a check to determine if the current directory is inside the googletest SVN repository', 'run a check to determine if the current directory is inside the googlemock SVN repository', 'run fuse_gtest_files.py to merge all Google Test source files into a single header and source file', 'run fuse_gtest_files.py with a custom GTEST_ROOT_DIR and OUTPUT_DIR to fuse gtest into a new location', 'fuse all gtest header files recursively into a single gtest.h output file', 'fuse all gtest source files recursively into a single gtest-all.cc output file', 'validate that a given directory contains the required gtest seed files before fusing']
```

Usage

```
{'run_fuse_gtest_files': 'run fuse_gtest_files.py to merge all Google Test source files into a single header and source file', 'run_fuse_gtest_with_root': 'run fuse_gtest_files.py with a custom GTEST_ROOT_DIR and OUTPUT_DIR to fuse gtest into a new location', 'fuse_gtest_h': 'fuse all gtest header files recursively into a single gtest.h output file', 'fuse_gtest_all_cc': 'fuse all gtest source files recursively into a single gtest-all.cc output file', 'validate_gtest_root_dir': 'validate that a given directory contains the required gtest seed files before fusing'}
```

