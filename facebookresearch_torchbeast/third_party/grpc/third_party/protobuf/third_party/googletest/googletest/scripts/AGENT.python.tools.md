# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/third_party/googletest/googletest/scripts/common.py

Prompts

```
['run a shell command and return its stdout as a list of stripped lines', 'run svn info to get the project name and current SVN workspace root path', 'run GetSvnInfo and return the current SVN workspace trunk root path', 'run a check to determine if the current directory is inside the googletest SVN repository', 'run a check to determine if the current directory is inside the googlemock SVN repository', 'run fuse_gtest_files.py to fuse Google Test source code into a single .h and .cc file', 'run FuseGTestH to scan gtest root directory and generate a fused gtest.h header file', 'run FuseGTestAllCc to scan gtest root directory and generate a fused gtest-all.cc source file', 'run ValidateGTestRootDir to verify the given directory is a valid Google Test root directory', 'run ValidateOutputDir to verify the output directory is valid and files can be written']
```

Usage

```
{'run_GetCommandOutput': 'run a shell command and return its stdout as a list of stripped lines', 'run_GetSvnInfo': 'run svn info to get the project name and current SVN workspace root path', 'run_GetSvnTrunk': 'run GetSvnInfo and return the current SVN workspace trunk root path', 'run_IsInGTestSvn': 'run a check to determine if the current directory is inside the googletest SVN repository', 'run_IsInGMockSvn': 'run a check to determine if the current directory is inside the googlemock SVN repository'}
```

## File: facebookresearch_torchbeast/third_party/grpc/third_party/protobuf/third_party/googletest/googletest/scripts/fuse_gtest_files.py

Prompts

```
['run a shell command and return its stdout as a list of stripped lines', 'run svn info to get the project name and current SVN workspace root path', 'run GetSvnInfo and return the current SVN workspace trunk root path', 'run a check to determine if the current directory is inside the googletest SVN repository', 'run a check to determine if the current directory is inside the googlemock SVN repository', 'run fuse_gtest_files.py to fuse Google Test source code into a single .h and .cc file', 'run FuseGTestH to scan gtest root directory and generate a fused gtest.h header file', 'run FuseGTestAllCc to scan gtest root directory and generate a fused gtest-all.cc source file', 'run ValidateGTestRootDir to verify the given directory is a valid Google Test root directory', 'run ValidateOutputDir to verify the output directory is valid and files can be written']
```

Usage

```
{'fuse_gtest_files': 'run fuse_gtest_files.py to fuse Google Test source code into a single .h and .cc file', 'fuse_gtest_h': 'run FuseGTestH to scan gtest root directory and generate a fused gtest.h header file', 'fuse_gtest_all_cc': 'run FuseGTestAllCc to scan gtest root directory and generate a fused gtest-all.cc source file', 'validate_gtest_root_dir': 'run ValidateGTestRootDir to verify the given directory is a valid Google Test root directory', 'validate_output_dir': 'run ValidateOutputDir to verify the output directory is valid and files can be written'}
```

