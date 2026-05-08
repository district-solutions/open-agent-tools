# Agent Python Tools

- repo: facebookresearch/habitat-sim
- repo_uri: https://github.com/facebookresearch/habitat-sim

## File: facebookresearch_habitat-sim/src/deps/zstd/tests/DEPRECATED-test-zstd-speed.py

Prompts

```
['run the zstd speed benchmark script against test files and email warnings on regression', 'test a git commit by building zstd with gcc and clang and benchmarking compression speed', 'benchmark zstd compression and decompression speed then compare results against previous commit data', 'compute the md5 hash of a binary file by reading it in 64KB chunks', 'execute a shell command via subprocess with configurable output printing and timeout handling', 'run the zstd automated benchmark tool in current mode against local build with specified files and compression levels', 'run the zstd automated benchmark tool in continuous mode to monitor new PRs and detect regressions via email alerts', 'run the zstd automated benchmark tool with a custom dictionary file to benchmark dictionary-based compression performance', 'benchmark a single zstd executable at a given compression level against a specific file and return compression and decompression speeds', 'compare two zstd builds and detect compression or decompression speed regressions exceeding the configured tolerance threshold', 'run the test-license.py script to validate copyright and license headers across all source files', 'test the valid_file function to check if a single source file has correct copyright and license headers', "test the valid_copyright function to validate that a file's copyright line contains Facebook Inc without a year", 'test the valid_license function to verify a file contains the expected BSD/GPLv2 dual license text block', 'test the exclude function to check if a given filename should be skipped from license validation', 'run the zstd version interoperability test suite across all released tags', 'test decompressing all nodict compressed files with a specific zstd version tag', 'test decompressing all dictionary-compressed files with a specific zstd version tag', 'create a zstd dictionary from C and header source files for a given version tag', 'compress a sample file at multiple compression levels using a specific zstd version']
```

Usage

```
{'run_zstd_speed_benchmark': 'run the zstd speed benchmark script against test files and email warnings on regression', 'test_commit_benchmark': 'test a git commit by building zstd with gcc and clang and benchmarking compression speed', 'benchmark_and_compare': 'benchmark zstd compression and decompression speed then compare results against previous commit data', 'hashfile_md5': 'compute the md5 hash of a binary file by reading it in 64KB chunks', 'execute_shell_command': 'execute a shell command via subprocess with configurable output printing and timeout handling'}
```

## File: facebookresearch_habitat-sim/src/deps/zstd/tests/automated_benchmarking.py

Prompts

```
['run the zstd speed benchmark script against test files and email warnings on regression', 'test a git commit by building zstd with gcc and clang and benchmarking compression speed', 'benchmark zstd compression and decompression speed then compare results against previous commit data', 'compute the md5 hash of a binary file by reading it in 64KB chunks', 'execute a shell command via subprocess with configurable output printing and timeout handling', 'run the zstd automated benchmark tool in current mode against local build with specified files and compression levels', 'run the zstd automated benchmark tool in continuous mode to monitor new PRs and detect regressions via email alerts', 'run the zstd automated benchmark tool with a custom dictionary file to benchmark dictionary-based compression performance', 'benchmark a single zstd executable at a given compression level against a specific file and return compression and decompression speeds', 'compare two zstd builds and detect compression or decompression speed regressions exceeding the configured tolerance threshold', 'run the test-license.py script to validate copyright and license headers across all source files', 'test the valid_file function to check if a single source file has correct copyright and license headers', "test the valid_copyright function to validate that a file's copyright line contains Facebook Inc without a year", 'test the valid_license function to verify a file contains the expected BSD/GPLv2 dual license text block', 'test the exclude function to check if a given filename should be skipped from license validation', 'run the zstd version interoperability test suite across all released tags', 'test decompressing all nodict compressed files with a specific zstd version tag', 'test decompressing all dictionary-compressed files with a specific zstd version tag', 'create a zstd dictionary from C and header source files for a given version tag', 'compress a sample file at multiple compression levels using a specific zstd version']
```

Usage

```
{'run_automated_benchmark_current': 'run the zstd automated benchmark tool in current mode against local build with specified files and compression levels', 'run_automated_benchmark_continuous': 'run the zstd automated benchmark tool in continuous mode to monitor new PRs and detect regressions via email alerts', 'run_automated_benchmark_dictionary': 'run the zstd automated benchmark tool with a custom dictionary file to benchmark dictionary-based compression performance', 'benchmark_single': 'benchmark a single zstd executable at a given compression level against a specific file and return compression and decompression speeds', 'get_regressions': 'compare two zstd builds and detect compression or decompression speed regressions exceeding the configured tolerance threshold'}
```

## File: facebookresearch_habitat-sim/src/deps/zstd/tests/test-license.py

Prompts

```
['run the zstd speed benchmark script against test files and email warnings on regression', 'test a git commit by building zstd with gcc and clang and benchmarking compression speed', 'benchmark zstd compression and decompression speed then compare results against previous commit data', 'compute the md5 hash of a binary file by reading it in 64KB chunks', 'execute a shell command via subprocess with configurable output printing and timeout handling', 'run the zstd automated benchmark tool in current mode against local build with specified files and compression levels', 'run the zstd automated benchmark tool in continuous mode to monitor new PRs and detect regressions via email alerts', 'run the zstd automated benchmark tool with a custom dictionary file to benchmark dictionary-based compression performance', 'benchmark a single zstd executable at a given compression level against a specific file and return compression and decompression speeds', 'compare two zstd builds and detect compression or decompression speed regressions exceeding the configured tolerance threshold', 'run the test-license.py script to validate copyright and license headers across all source files', 'test the valid_file function to check if a single source file has correct copyright and license headers', "test the valid_copyright function to validate that a file's copyright line contains Facebook Inc without a year", 'test the valid_license function to verify a file contains the expected BSD/GPLv2 dual license text block', 'test the exclude function to check if a given filename should be skipped from license validation', 'run the zstd version interoperability test suite across all released tags', 'test decompressing all nodict compressed files with a specific zstd version tag', 'test decompressing all dictionary-compressed files with a specific zstd version tag', 'create a zstd dictionary from C and header source files for a given version tag', 'compress a sample file at multiple compression levels using a specific zstd version']
```

Usage

```
{'run_license_check': 'run the test-license.py script to validate copyright and license headers across all source files', 'test_valid_file': 'test the valid_file function to check if a single source file has correct copyright and license headers', 'test_valid_copyright': "test the valid_copyright function to validate that a file's copyright line contains Facebook Inc without a year", 'test_valid_license': 'test the valid_license function to verify a file contains the expected BSD/GPLv2 dual license text block', 'test_exclude': 'test the exclude function to check if a given filename should be skipped from license validation'}
```

## File: facebookresearch_habitat-sim/src/deps/zstd/tests/test-zstd-versions.py

Prompts

```
['run the zstd speed benchmark script against test files and email warnings on regression', 'test a git commit by building zstd with gcc and clang and benchmarking compression speed', 'benchmark zstd compression and decompression speed then compare results against previous commit data', 'compute the md5 hash of a binary file by reading it in 64KB chunks', 'execute a shell command via subprocess with configurable output printing and timeout handling', 'run the zstd automated benchmark tool in current mode against local build with specified files and compression levels', 'run the zstd automated benchmark tool in continuous mode to monitor new PRs and detect regressions via email alerts', 'run the zstd automated benchmark tool with a custom dictionary file to benchmark dictionary-based compression performance', 'benchmark a single zstd executable at a given compression level against a specific file and return compression and decompression speeds', 'compare two zstd builds and detect compression or decompression speed regressions exceeding the configured tolerance threshold', 'run the test-license.py script to validate copyright and license headers across all source files', 'test the valid_file function to check if a single source file has correct copyright and license headers', "test the valid_copyright function to validate that a file's copyright line contains Facebook Inc without a year", 'test the valid_license function to verify a file contains the expected BSD/GPLv2 dual license text block', 'test the exclude function to check if a given filename should be skipped from license validation', 'run the zstd version interoperability test suite across all released tags', 'test decompressing all nodict compressed files with a specific zstd version tag', 'test decompressing all dictionary-compressed files with a specific zstd version tag', 'create a zstd dictionary from C and header source files for a given version tag', 'compress a sample file at multiple compression levels using a specific zstd version']
```

Usage

```
{'run_zstd_version_interop_tests': 'run the zstd version interoperability test suite across all released tags', 'test_decompress_zst': 'test decompressing all nodict compressed files with a specific zstd version tag', 'test_decompress_dict': 'test decompressing all dictionary-compressed files with a specific zstd version tag', 'create_dict': 'create a zstd dictionary from C and header source files for a given version tag', 'compress_sample': 'compress a sample file at multiple compression levels using a specific zstd version'}
```

