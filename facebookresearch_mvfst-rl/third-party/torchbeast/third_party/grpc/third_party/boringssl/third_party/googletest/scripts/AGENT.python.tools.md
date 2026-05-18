# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/boringssl/third_party/googletest/scripts/common.py

Prompts

```
['run a shell command and return its stdout as a list of stripped lines', 'run svn info to get the project name and SVN workspace root path', 'run GetSvnTrunk to return the current SVN workspace trunk root path', 'run IsInGTestSvn to check if the current directory is in the googletest SVN repo', 'run IsInGMockSvn to check if the current directory is in the googlemock SVN repo', 'run fuse_gtest_files.py with an output directory to fuse Google Test source into single header and source files', 'run fuse_gtest_files.py with a gtest root directory and output directory to generate fused gtest files', 'call FuseGTest with a gtest root directory and output directory to fuse gtest.h and gtest-all.cc', 'call FuseGTestH to recursively scan and fuse all gtest header files into a single gtest.h output file', 'call ValidateGTestRootDir to verify the gtest root directory contains required seed files before fusing']
```

Usage

```
{'run_GetCommandOutput': 'run a shell command and return its stdout as a list of stripped lines', 'run_GetSvnInfo': 'run svn info to get the project name and SVN workspace root path', 'run_GetSvnTrunk': 'run GetSvnTrunk to return the current SVN workspace trunk root path', 'run_IsInGTestSvn': 'run IsInGTestSvn to check if the current directory is in the googletest SVN repo', 'run_IsInGMockSvn': 'run IsInGMockSvn to check if the current directory is in the googlemock SVN repo'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/third_party/boringssl/third_party/googletest/scripts/fuse_gtest_files.py

Prompts

```
['run a shell command and return its stdout as a list of stripped lines', 'run svn info to get the project name and SVN workspace root path', 'run GetSvnTrunk to return the current SVN workspace trunk root path', 'run IsInGTestSvn to check if the current directory is in the googletest SVN repo', 'run IsInGMockSvn to check if the current directory is in the googlemock SVN repo', 'run fuse_gtest_files.py with an output directory to fuse Google Test source into single header and source files', 'run fuse_gtest_files.py with a gtest root directory and output directory to generate fused gtest files', 'call FuseGTest with a gtest root directory and output directory to fuse gtest.h and gtest-all.cc', 'call FuseGTestH to recursively scan and fuse all gtest header files into a single gtest.h output file', 'call ValidateGTestRootDir to verify the gtest root directory contains required seed files before fusing']
```

Usage

```
{'run_fuse_gtest_files': 'run fuse_gtest_files.py with an output directory to fuse Google Test source into single header and source files', 'run_fuse_gtest_with_root': 'run fuse_gtest_files.py with a gtest root directory and output directory to generate fused gtest files', 'fuse_gtest': 'call FuseGTest with a gtest root directory and output directory to fuse gtest.h and gtest-all.cc', 'fuse_gtest_h': 'call FuseGTestH to recursively scan and fuse all gtest header files into a single gtest.h output file', 'validate_gtest_root_dir': 'call ValidateGTestRootDir to verify the gtest root directory contains required seed files before fusing'}
```

