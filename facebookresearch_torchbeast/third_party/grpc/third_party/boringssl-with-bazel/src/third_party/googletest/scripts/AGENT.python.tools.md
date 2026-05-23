# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/third_party/boringssl-with-bazel/src/third_party/googletest/scripts/common.py

Prompts

```
['run a shell command and return its stdout as a list of stripped lines', 'run svn info to get the project name and SVN workspace root path', 'run GetSvnInfo and return the SVN workspace trunk root path', 'run a check to determine if the current directory is in the googletest SVN repository', 'run a check to determine if the current directory is in the googlemock SVN repository', 'run the script to fuse Google Test source code into a single .h and .cc file', 'create a fused gtest.h header file by recursively inlining all gtest header includes', 'build a fused gtest-all.cc source file by recursively inlining all gtest source includes', 'verify that a given directory contains valid Google Test root files before processing', 'check that the output directory is valid and prompt to overwrite existing files']
```

Usage

```
{'run_GetCommandOutput': 'run a shell command and return its stdout as a list of stripped lines', 'run_GetSvnInfo': 'run svn info to get the project name and SVN workspace root path', 'run_GetSvnTrunk': 'run GetSvnInfo and return the SVN workspace trunk root path', 'run_IsInGTestSvn': 'run a check to determine if the current directory is in the googletest SVN repository', 'run_IsInGMockSvn': 'run a check to determine if the current directory is in the googlemock SVN repository'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/boringssl-with-bazel/src/third_party/googletest/scripts/fuse_gtest_files.py

Prompts

```
['run a shell command and return its stdout as a list of stripped lines', 'run svn info to get the project name and SVN workspace root path', 'run GetSvnInfo and return the SVN workspace trunk root path', 'run a check to determine if the current directory is in the googletest SVN repository', 'run a check to determine if the current directory is in the googlemock SVN repository', 'run the script to fuse Google Test source code into a single .h and .cc file', 'create a fused gtest.h header file by recursively inlining all gtest header includes', 'build a fused gtest-all.cc source file by recursively inlining all gtest source includes', 'verify that a given directory contains valid Google Test root files before processing', 'check that the output directory is valid and prompt to overwrite existing files']
```

Usage

```
{'fuse_gtest_files': 'run the script to fuse Google Test source code into a single .h and .cc file', 'fuse_gtest_h': 'create a fused gtest.h header file by recursively inlining all gtest header includes', 'fuse_gtest_all_cc': 'build a fused gtest-all.cc source file by recursively inlining all gtest source includes', 'validate_gtest_root_dir': 'verify that a given directory contains valid Google Test root files before processing', 'validate_output_dir': 'check that the output directory is valid and prompt to overwrite existing files'}
```

