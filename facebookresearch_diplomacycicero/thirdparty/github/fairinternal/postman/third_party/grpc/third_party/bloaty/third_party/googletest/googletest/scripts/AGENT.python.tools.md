# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/bloaty/third_party/googletest/googletest/scripts/common.py

Prompts

```
['run a shell command and return its stdout as a list of stripped lines', 'run svn info to get the project name and current SVN workspace root path', 'run GetSvnInfo and return the SVN workspace trunk root path', 'run a check to determine if the current directory is inside the googletest SVN repository', 'run a check to determine if the current directory is inside the googlemock SVN repository', 'run the script to fuse Google Test source files into a single header and source file', 'run the script with a custom GTest root directory and output directory path', 'review the FuseGTest function that validates inputs and fuses gtest.h and gtest-all.cc', 'review the FuseGTestH function that recursively processes gtest header files into a fused header', 'review the FuseGTestAllCc function that recursively processes gtest source files into a fused source file']
```

Usage

```
{'run_GetCommandOutput': 'run a shell command and return its stdout as a list of stripped lines', 'run_GetSvnInfo': 'run svn info to get the project name and current SVN workspace root path', 'run_GetSvnTrunk': 'run GetSvnInfo and return the SVN workspace trunk root path', 'run_IsInGTestSvn': 'run a check to determine if the current directory is inside the googletest SVN repository', 'run_IsInGMockSvn': 'run a check to determine if the current directory is inside the googlemock SVN repository'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/third_party/bloaty/third_party/googletest/googletest/scripts/fuse_gtest_files.py

Prompts

```
['run a shell command and return its stdout as a list of stripped lines', 'run svn info to get the project name and current SVN workspace root path', 'run GetSvnInfo and return the SVN workspace trunk root path', 'run a check to determine if the current directory is inside the googletest SVN repository', 'run a check to determine if the current directory is inside the googlemock SVN repository', 'run the script to fuse Google Test source files into a single header and source file', 'run the script with a custom GTest root directory and output directory path', 'review the FuseGTest function that validates inputs and fuses gtest.h and gtest-all.cc', 'review the FuseGTestH function that recursively processes gtest header files into a fused header', 'review the FuseGTestAllCc function that recursively processes gtest source files into a fused source file']
```

Usage

```
{'run_fuse_gtest': 'run the script to fuse Google Test source files into a single header and source file', 'run_fuse_gtest_with_root': 'run the script with a custom GTest root directory and output directory path', 'review_FuseGTest': 'review the FuseGTest function that validates inputs and fuses gtest.h and gtest-all.cc', 'review_FuseGTestH': 'review the FuseGTestH function that recursively processes gtest header files into a fused header', 'review_FuseGTestAllCc': 'review the FuseGTestAllCc function that recursively processes gtest source files into a fused source file'}
```

