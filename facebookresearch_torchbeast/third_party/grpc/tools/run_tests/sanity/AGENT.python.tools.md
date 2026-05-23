# Agent Python Tools

- repo: facebookresearch/torchbeast
- repo_uri: https://github.com/facebookresearch/torchbeast

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/sanity/check_bazel_workspace.py

Prompts

```
['run the check_bazel_workspace.py script to validate git submodules match Bazel WORKSPACE dependencies', 'review the BazelEvalState class that intercepts http_archive and git_repository calls to collect dependency names and URLs', 'test the git submodule hash extraction logic that parses 40-character commit hashes from git submodule output', 'refactor the BazelEvalState archive method to handle additional Bazel rule types beyond http_archive and git_repository', 'summarize how the script parses bazel/grpc_deps.bzl by executing it with a custom namespace to capture dependency declarations', 'run the sanity check script to verify port_platform.h is the first include in gRPC source files', 'run check_port_platform_inclusion on a directory to find files missing port_platform.h as the first include', 'check port_platform.h inclusion compliance across all C and C++ files in the src/core directory', 'check port_platform.h inclusion compliance across all C and C++ files in the include/grpc directory', 'review the check_port_platform_inclusion function to understand how it validates include order and blank line requirements', 'run the TestFilteringTest suite to validate gRPC pull request test filtering logic', "test that changing a language source file triggers only that language's test suite", 'test that changing multiple language files triggers only the relevant test suites', "test that changing platform-specific files triggers only that platform's test suite", 'test that the whitelist dictionary does not match files that should trigger all tests']
```

Usage

```
{'run_bazel_workspace_sanity_check': 'run the check_bazel_workspace.py script to validate git submodules match Bazel WORKSPACE dependencies', 'review_BazelEvalState_class': 'review the BazelEvalState class that intercepts http_archive and git_repository calls to collect dependency names and URLs', 'test_git_submodule_hash_extraction': 'test the git submodule hash extraction logic that parses 40-character commit hashes from git submodule output', 'refactor_BazelEvalState_archive_method': 'refactor the BazelEvalState archive method to handle additional Bazel rule types beyond http_archive and git_repository', 'summarize_bazel_dependency_parsing': 'summarize how the script parses bazel/grpc_deps.bzl by executing it with a custom namespace to capture dependency declarations'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/sanity/check_port_platform.py

Prompts

```
['run the check_bazel_workspace.py script to validate git submodules match Bazel WORKSPACE dependencies', 'review the BazelEvalState class that intercepts http_archive and git_repository calls to collect dependency names and URLs', 'test the git submodule hash extraction logic that parses 40-character commit hashes from git submodule output', 'refactor the BazelEvalState archive method to handle additional Bazel rule types beyond http_archive and git_repository', 'summarize how the script parses bazel/grpc_deps.bzl by executing it with a custom namespace to capture dependency declarations', 'run the sanity check script to verify port_platform.h is the first include in gRPC source files', 'run check_port_platform_inclusion on a directory to find files missing port_platform.h as the first include', 'check port_platform.h inclusion compliance across all C and C++ files in the src/core directory', 'check port_platform.h inclusion compliance across all C and C++ files in the include/grpc directory', 'review the check_port_platform_inclusion function to understand how it validates include order and blank line requirements', 'run the TestFilteringTest suite to validate gRPC pull request test filtering logic', "test that changing a language source file triggers only that language's test suite", 'test that changing multiple language files triggers only the relevant test suites', "test that changing platform-specific files triggers only that platform's test suite", 'test that the whitelist dictionary does not match files that should trigger all tests']
```

Usage

```
{'run_check_port_platform': 'run the sanity check script to verify port_platform.h is the first include in gRPC source files', 'run_check_port_platform_inclusion': 'run check_port_platform_inclusion on a directory to find files missing port_platform.h as the first include', 'check_port_platform_inclusion_src_core': 'check port_platform.h inclusion compliance across all C and C++ files in the src/core directory', 'check_port_platform_inclusion_include_grpc': 'check port_platform.h inclusion compliance across all C and C++ files in the include/grpc directory', 'review_check_port_platform_inclusion': 'review the check_port_platform_inclusion function to understand how it validates include order and blank line requirements'}
```

## File: facebookresearch_torchbeast/third_party/grpc/tools/run_tests/sanity/check_test_filtering.py

Prompts

```
['run the check_bazel_workspace.py script to validate git submodules match Bazel WORKSPACE dependencies', 'review the BazelEvalState class that intercepts http_archive and git_repository calls to collect dependency names and URLs', 'test the git submodule hash extraction logic that parses 40-character commit hashes from git submodule output', 'refactor the BazelEvalState archive method to handle additional Bazel rule types beyond http_archive and git_repository', 'summarize how the script parses bazel/grpc_deps.bzl by executing it with a custom namespace to capture dependency declarations', 'run the sanity check script to verify port_platform.h is the first include in gRPC source files', 'run check_port_platform_inclusion on a directory to find files missing port_platform.h as the first include', 'check port_platform.h inclusion compliance across all C and C++ files in the src/core directory', 'check port_platform.h inclusion compliance across all C and C++ files in the include/grpc directory', 'review the check_port_platform_inclusion function to understand how it validates include order and blank line requirements', 'run the TestFilteringTest suite to validate gRPC pull request test filtering logic', "test that changing a language source file triggers only that language's test suite", 'test that changing multiple language files triggers only the relevant test suites', "test that changing platform-specific files triggers only that platform's test suite", 'test that the whitelist dictionary does not match files that should trigger all tests']
```

Usage

```
{'run_test_filtering': 'run the TestFilteringTest suite to validate gRPC pull request test filtering logic', 'test_individual_language_filters': "test that changing a language source file triggers only that language's test suite", 'test_combined_language_filters': 'test that changing multiple language files triggers only the relevant test suites', 'test_platform_filter': "test that changing platform-specific files triggers only that platform's test suite", 'test_whitelist': 'test that the whitelist dictionary does not match files that should trigger all tests'}
```

