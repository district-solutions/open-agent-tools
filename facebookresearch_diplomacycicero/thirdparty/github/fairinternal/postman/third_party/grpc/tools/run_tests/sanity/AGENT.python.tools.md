# Agent Python Tools

- repo: facebookresearch/diplomacycicero
- repo_uri: https://github.com/facebookresearch/diplomacy_cicero

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/tools/run_tests/sanity/check_bazel_workspace.py

Prompts

```
['run the check_bazel_workspace.py script to validate git submodules match Bazel WORKSPACE dependencies', 'review the BazelEvalState class that captures http_archive and git_repository calls from Bazel bzl files', 'test the git submodule hash extraction logic that parses 40-character git commit hashes', 'test the grpc_deps.bzl parsing that uses exec with a custom namespace to capture dependency names and URLs', 'test the dependency override validation loop that ensures each gRPC dependency can be overridden', 'run the sanity check script to verify port_platform.h is the first included header in gRPC C source files', 'check a directory tree for C/C++ files where port_platform.h is not the first included header', 'review gRPC source files to find violations of the port_platform.h inclusion ordering rule', 'test that all gRPC C source files include port_platform.h first with a blank line after', 'refactor the port_platform.h inclusion checker to support additional header files or directory paths', 'run the unittest suite to verify gRPC pull request test filtering logic works correctly', "test that changing a language-specific source file triggers only that language's test suite", 'test that changing multiple language source files triggers only the relevant test suites', 'test that changing platform-specific files like vsprojects triggers only the matching platform tests', 'test that the whitelist regex patterns do not match files that should trigger all tests']
```

Usage

```
{'run_bazel_workspace_sanity_check': 'run the check_bazel_workspace.py script to validate git submodules match Bazel WORKSPACE dependencies', 'review_BazelEvalState_class': 'review the BazelEvalState class that captures http_archive and git_repository calls from Bazel bzl files', 'test_git_submodule_hash_parsing': 'test the git submodule hash extraction logic that parses 40-character git commit hashes', 'test_bazel_dependency_parsing': 'test the grpc_deps.bzl parsing that uses exec with a custom namespace to capture dependency names and URLs', 'test_dependency_override_validation': 'test the dependency override validation loop that ensures each gRPC dependency can be overridden'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/tools/run_tests/sanity/check_port_platform.py

Prompts

```
['run the check_bazel_workspace.py script to validate git submodules match Bazel WORKSPACE dependencies', 'review the BazelEvalState class that captures http_archive and git_repository calls from Bazel bzl files', 'test the git submodule hash extraction logic that parses 40-character git commit hashes', 'test the grpc_deps.bzl parsing that uses exec with a custom namespace to capture dependency names and URLs', 'test the dependency override validation loop that ensures each gRPC dependency can be overridden', 'run the sanity check script to verify port_platform.h is the first included header in gRPC C source files', 'check a directory tree for C/C++ files where port_platform.h is not the first included header', 'review gRPC source files to find violations of the port_platform.h inclusion ordering rule', 'test that all gRPC C source files include port_platform.h first with a blank line after', 'refactor the port_platform.h inclusion checker to support additional header files or directory paths', 'run the unittest suite to verify gRPC pull request test filtering logic works correctly', "test that changing a language-specific source file triggers only that language's test suite", 'test that changing multiple language source files triggers only the relevant test suites', 'test that changing platform-specific files like vsprojects triggers only the matching platform tests', 'test that the whitelist regex patterns do not match files that should trigger all tests']
```

Usage

```
{'run_check_port_platform': 'run the sanity check script to verify port_platform.h is the first included header in gRPC C source files', 'check_port_platform_inclusion': 'check a directory tree for C/C++ files where port_platform.h is not the first included header', 'review_port_platform_inclusion': 'review gRPC source files to find violations of the port_platform.h inclusion ordering rule', 'test_port_platform_ordering': 'test that all gRPC C source files include port_platform.h first with a blank line after', 'refactor_check_port_platform': 'refactor the port_platform.h inclusion checker to support additional header files or directory paths'}
```

## File: facebookresearch_diplomacycicero/thirdparty/github/fairinternal/postman/third_party/grpc/tools/run_tests/sanity/check_test_filtering.py

Prompts

```
['run the check_bazel_workspace.py script to validate git submodules match Bazel WORKSPACE dependencies', 'review the BazelEvalState class that captures http_archive and git_repository calls from Bazel bzl files', 'test the git submodule hash extraction logic that parses 40-character git commit hashes', 'test the grpc_deps.bzl parsing that uses exec with a custom namespace to capture dependency names and URLs', 'test the dependency override validation loop that ensures each gRPC dependency can be overridden', 'run the sanity check script to verify port_platform.h is the first included header in gRPC C source files', 'check a directory tree for C/C++ files where port_platform.h is not the first included header', 'review gRPC source files to find violations of the port_platform.h inclusion ordering rule', 'test that all gRPC C source files include port_platform.h first with a blank line after', 'refactor the port_platform.h inclusion checker to support additional header files or directory paths', 'run the unittest suite to verify gRPC pull request test filtering logic works correctly', "test that changing a language-specific source file triggers only that language's test suite", 'test that changing multiple language source files triggers only the relevant test suites', 'test that changing platform-specific files like vsprojects triggers only the matching platform tests', 'test that the whitelist regex patterns do not match files that should trigger all tests']
```

Usage

```
{'run_test_filtering': 'run the unittest suite to verify gRPC pull request test filtering logic works correctly', 'test_individual_language_filters': "test that changing a language-specific source file triggers only that language's test suite", 'test_combined_language_filters': 'test that changing multiple language source files triggers only the relevant test suites', 'test_platform_filter': 'test that changing platform-specific files like vsprojects triggers only the matching platform tests', 'test_whitelist': 'test that the whitelist regex patterns do not match files that should trigger all tests'}
```

