# Agent Python Tools

- repo: facebookresearch/mvfst-rl
- repo_uri: https://github.com/facebookresearch/mvfst-rl

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/tools/run_tests/sanity/check_bazel_workspace.py

Prompts

```
['run the sanity check script to validate git submodules match Bazel WORKSPACE dependencies', 'review the BazelEvalState class that parses http_archive and git_repository rules from Bazel files', 'test the BazelEvalState http_archive method to verify it records dependency names and URLs', 'test the BazelEvalState git_repository method to verify it records dependency names and remote URLs', 'refactor the BazelEvalState existing_rules method to support custom override name lists', 'run the sanity check script to verify port_platform.h is the first included header in gRPC source files', 'run check_port_platform_inclusion on a directory to find files where port_platform.h is not the first include', 'review the check_port_platform_inclusion function that walks directories and validates C/C++ header inclusion order', 'refactor check_port_platform_inclusion to support additional file extensions or different port_platform.h include paths', 'test check_port_platform_inclusion by creating sample C files with correct and incorrect port_platform.h inclusion order', 'run the TestFilteringTest suite to verify gRPC pull request test filtering logic', 'test that changing a language source file only triggers that language test suite', 'test that changing multiple language files triggers only the relevant test suites', 'test that changing platform specific files like vsprojects triggers only windows tests', 'test that the whitelist regex patterns do not match files that should trigger all tests']
```

Usage

```
{'run_check_bazel_workspace': 'run the sanity check script to validate git submodules match Bazel WORKSPACE dependencies', 'review_BazelEvalState_class': 'review the BazelEvalState class that parses http_archive and git_repository rules from Bazel files', 'test_BazelEvalState_http_archive': 'test the BazelEvalState http_archive method to verify it records dependency names and URLs', 'test_BazelEvalState_git_repository': 'test the BazelEvalState git_repository method to verify it records dependency names and remote URLs', 'refactor_BazelEvalState_existing_rules': 'refactor the BazelEvalState existing_rules method to support custom override name lists'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/tools/run_tests/sanity/check_port_platform.py

Prompts

```
['run the sanity check script to validate git submodules match Bazel WORKSPACE dependencies', 'review the BazelEvalState class that parses http_archive and git_repository rules from Bazel files', 'test the BazelEvalState http_archive method to verify it records dependency names and URLs', 'test the BazelEvalState git_repository method to verify it records dependency names and remote URLs', 'refactor the BazelEvalState existing_rules method to support custom override name lists', 'run the sanity check script to verify port_platform.h is the first included header in gRPC source files', 'run check_port_platform_inclusion on a directory to find files where port_platform.h is not the first include', 'review the check_port_platform_inclusion function that walks directories and validates C/C++ header inclusion order', 'refactor check_port_platform_inclusion to support additional file extensions or different port_platform.h include paths', 'test check_port_platform_inclusion by creating sample C files with correct and incorrect port_platform.h inclusion order', 'run the TestFilteringTest suite to verify gRPC pull request test filtering logic', 'test that changing a language source file only triggers that language test suite', 'test that changing multiple language files triggers only the relevant test suites', 'test that changing platform specific files like vsprojects triggers only windows tests', 'test that the whitelist regex patterns do not match files that should trigger all tests']
```

Usage

```
{'run_check_port_platform': 'run the sanity check script to verify port_platform.h is the first included header in gRPC source files', 'run_check_port_platform_inclusion': 'run check_port_platform_inclusion on a directory to find files where port_platform.h is not the first include', 'review_check_port_platform_inclusion': 'review the check_port_platform_inclusion function that walks directories and validates C/C++ header inclusion order', 'refactor_check_port_platform_inclusion': 'refactor check_port_platform_inclusion to support additional file extensions or different port_platform.h include paths', 'test_check_port_platform_inclusion': 'test check_port_platform_inclusion by creating sample C files with correct and incorrect port_platform.h inclusion order'}
```

## File: facebookresearch_mvfst-rl/third-party/torchbeast/third_party/grpc/tools/run_tests/sanity/check_test_filtering.py

Prompts

```
['run the sanity check script to validate git submodules match Bazel WORKSPACE dependencies', 'review the BazelEvalState class that parses http_archive and git_repository rules from Bazel files', 'test the BazelEvalState http_archive method to verify it records dependency names and URLs', 'test the BazelEvalState git_repository method to verify it records dependency names and remote URLs', 'refactor the BazelEvalState existing_rules method to support custom override name lists', 'run the sanity check script to verify port_platform.h is the first included header in gRPC source files', 'run check_port_platform_inclusion on a directory to find files where port_platform.h is not the first include', 'review the check_port_platform_inclusion function that walks directories and validates C/C++ header inclusion order', 'refactor check_port_platform_inclusion to support additional file extensions or different port_platform.h include paths', 'test check_port_platform_inclusion by creating sample C files with correct and incorrect port_platform.h inclusion order', 'run the TestFilteringTest suite to verify gRPC pull request test filtering logic', 'test that changing a language source file only triggers that language test suite', 'test that changing multiple language files triggers only the relevant test suites', 'test that changing platform specific files like vsprojects triggers only windows tests', 'test that the whitelist regex patterns do not match files that should trigger all tests']
```

Usage

```
{'run_test_filtering': 'run the TestFilteringTest suite to verify gRPC pull request test filtering logic', 'test_individual_language_filters': 'test that changing a language source file only triggers that language test suite', 'test_combined_language_filters': 'test that changing multiple language files triggers only the relevant test suites', 'test_platform_filter': 'test that changing platform specific files like vsprojects triggers only windows tests', 'test_whitelist': 'test that the whitelist regex patterns do not match files that should trigger all tests'}
```

