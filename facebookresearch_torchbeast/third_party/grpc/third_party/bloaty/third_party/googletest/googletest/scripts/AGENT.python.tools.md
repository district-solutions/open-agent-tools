# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/third_party/bloaty/third_party/googletest/googletest/scripts/common.py

Prompts

```
['run a shell command and return its stdout as a list of stripped lines', 'run svn info to get the project name and current SVN workspace root path', 'run svn info and return the current SVN workspace trunk root path', 'run a check to determine if the current directory is inside the googletest SVN repository', 'run a check to determine if the current directory is inside the googlemock SVN repository', 'run the script to fuse Google Test source code into a single .h and .cc file', 'create a fused gtest.h header file by recursively processing all gtest headers', 'build a fused gtest-all.cc source file by recursively processing all gtest source files', 'verify that the given directory is a valid Google Test root directory', 'verify that the output directory is valid and output files can be created']
```

Usage

```
{'run_GetCommandOutput': 'run a shell command and return its stdout as a list of stripped lines', 'run_GetSvnInfo': 'run svn info to get the project name and current SVN workspace root path', 'run_GetSvnTrunk': 'run svn info and return the current SVN workspace trunk root path', 'run_IsInGTestSvn': 'run a check to determine if the current directory is inside the googletest SVN repository', 'run_IsInGMockSvn': 'run a check to determine if the current directory is inside the googlemock SVN repository'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/bloaty/third_party/googletest/googletest/scripts/fuse_gtest_files.py

Prompts

```
['run a shell command and return its stdout as a list of stripped lines', 'run svn info to get the project name and current SVN workspace root path', 'run svn info and return the current SVN workspace trunk root path', 'run a check to determine if the current directory is inside the googletest SVN repository', 'run a check to determine if the current directory is inside the googlemock SVN repository', 'run the script to fuse Google Test source code into a single .h and .cc file', 'create a fused gtest.h header file by recursively processing all gtest headers', 'build a fused gtest-all.cc source file by recursively processing all gtest source files', 'verify that the given directory is a valid Google Test root directory', 'verify that the output directory is valid and output files can be created']
```

Usage

```
{'fuse_gtest_files': 'run the script to fuse Google Test source code into a single .h and .cc file', 'fuse_gtest_h': 'create a fused gtest.h header file by recursively processing all gtest headers', 'fuse_gtest_all_cc': 'build a fused gtest-all.cc source file by recursively processing all gtest source files', 'validate_gtest_root_dir': 'verify that the given directory is a valid Google Test root directory', 'validate_output_dir': 'verify that the output directory is valid and output files can be created'}
```

