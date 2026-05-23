# Agent Python Tools

- repo: facebookresearch/rlmeta
- repo_uri: https://github.com/facebookresearch/rlmeta

## File: facebookresearch_rlmeta/third_party/moolib/src/tensorpipe/third_party/googletest/googletest/scripts/common.py

Prompts

```
['run a shell command and capture its stdout output as a list of stripped lines', 'run svn info to get the project name and current SVN workspace root path', 'run svn info to retrieve the current SVN workspace trunk root path', 'run a check to determine if the current directory is inside the googletest SVN repository', 'run a check to determine if the current directory is inside the googlemock SVN repository', 'run fuse_gtest_files.py to fuse Google Test source code into a single .h and .cc file', 'run fuse_gtest_files.py with a custom GTEST_ROOT_DIR and OUTPUT_DIR to generate fused gtest files', 'fuse all Google Test header files recursively into a single gtest.h output file', 'fuse all Google Test source files recursively into a single gtest-all.cc output file', 'validate that a given directory contains valid Google Test root files before fusing']
```

Usage

```
{'run_GetCommandOutput': 'run a shell command and capture its stdout output as a list of stripped lines', 'run_GetSvnInfo': 'run svn info to get the project name and current SVN workspace root path', 'run_GetSvnTrunk': 'run svn info to retrieve the current SVN workspace trunk root path', 'run_IsInGTestSvn': 'run a check to determine if the current directory is inside the googletest SVN repository', 'run_IsInGMockSvn': 'run a check to determine if the current directory is inside the googlemock SVN repository'}
```

## File: facebookresearch_rlmeta/third_party/moolib/src/tensorpipe/third_party/googletest/googletest/scripts/fuse_gtest_files.py

Prompts

```
['run a shell command and capture its stdout output as a list of stripped lines', 'run svn info to get the project name and current SVN workspace root path', 'run svn info to retrieve the current SVN workspace trunk root path', 'run a check to determine if the current directory is inside the googletest SVN repository', 'run a check to determine if the current directory is inside the googlemock SVN repository', 'run fuse_gtest_files.py to fuse Google Test source code into a single .h and .cc file', 'run fuse_gtest_files.py with a custom GTEST_ROOT_DIR and OUTPUT_DIR to generate fused gtest files', 'fuse all Google Test header files recursively into a single gtest.h output file', 'fuse all Google Test source files recursively into a single gtest-all.cc output file', 'validate that a given directory contains valid Google Test root files before fusing']
```

Usage

```
{'run_fuse_gtest': 'run fuse_gtest_files.py to fuse Google Test source code into a single .h and .cc file', 'run_fuse_gtest_with_root': 'run fuse_gtest_files.py with a custom GTEST_ROOT_DIR and OUTPUT_DIR to generate fused gtest files', 'fuse_gtest_h': 'fuse all Google Test header files recursively into a single gtest.h output file', 'fuse_gtest_all_cc': 'fuse all Google Test source files recursively into a single gtest-all.cc output file', 'validate_gtest_root_dir': 'validate that a given directory contains valid Google Test root files before fusing'}
```

