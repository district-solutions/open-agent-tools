# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/third_party/googletest/googletest/scripts/common.py

Prompts

```
['run a shell command and return its stdout as a list of stripped lines', 'run svn info to get the project name and current SVN workspace root path', 'run GetSvnInfo and return the current SVN workspace trunk root path', 'run a check to determine if the current directory is inside the googletest SVN repository', 'run a check to determine if the current directory is inside the googlemock SVN repository', 'run fuse_gtest_files.py to fuse Google Test source code into a single .h and .cc file', 'run fuse_gtest_files.py with a custom GTEST_ROOT_DIR and OUTPUT_DIR to generate fused gtest files', 'review the FuseGTestH function that recursively processes gtest headers and fuses them into gtest.h', 'review the FuseGTestAllCc function that recursively processes gtest source files and fuses them into gtest-all.cc', 'review the nested ProcessFile function that handles recursive include resolution for gtest headers and sources']
```

Usage

```
{'run_GetCommandOutput': 'run a shell command and return its stdout as a list of stripped lines', 'run_GetSvnInfo': 'run svn info to get the project name and current SVN workspace root path', 'run_GetSvnTrunk': 'run GetSvnInfo and return the current SVN workspace trunk root path', 'run_IsInGTestSvn': 'run a check to determine if the current directory is inside the googletest SVN repository', 'run_IsInGMockSvn': 'run a check to determine if the current directory is inside the googlemock SVN repository'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/googletest/googletest/scripts/fuse_gtest_files.py

Prompts

```
['run a shell command and return its stdout as a list of stripped lines', 'run svn info to get the project name and current SVN workspace root path', 'run GetSvnInfo and return the current SVN workspace trunk root path', 'run a check to determine if the current directory is inside the googletest SVN repository', 'run a check to determine if the current directory is inside the googlemock SVN repository', 'run fuse_gtest_files.py to fuse Google Test source code into a single .h and .cc file', 'run fuse_gtest_files.py with a custom GTEST_ROOT_DIR and OUTPUT_DIR to generate fused gtest files', 'review the FuseGTestH function that recursively processes gtest headers and fuses them into gtest.h', 'review the FuseGTestAllCc function that recursively processes gtest source files and fuses them into gtest-all.cc', 'review the nested ProcessFile function that handles recursive include resolution for gtest headers and sources']
```

Usage

```
{'run_fuse_gtest_files': 'run fuse_gtest_files.py to fuse Google Test source code into a single .h and .cc file', 'run_fuse_gtest_with_root': 'run fuse_gtest_files.py with a custom GTEST_ROOT_DIR and OUTPUT_DIR to generate fused gtest files', 'review_FuseGTestH': 'review the FuseGTestH function that recursively processes gtest headers and fuses them into gtest.h', 'review_FuseGTestAllCc': 'review the FuseGTestAllCc function that recursively processes gtest source files and fuses them into gtest-all.cc', 'review_ProcessFile': 'review the nested ProcessFile function that handles recursive include resolution for gtest headers and sources'}
```

