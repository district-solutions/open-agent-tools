# Agent Python Tools

- repo: facebookresearch/looptool
- repo_uri: https://github.com/facebookresearch/loop_tool

## File: facebookresearch_looptool/extern/wasm-micro-runtime/tests/wamr-test-suites/spec-test-script/all.py

Prompts

```
['run the whole WebAssembly spec test suite against iwasm interpreter with AOT or SGX flags', 'run a single .wast test case file against the iwasm interpreter with target architecture', 'run the entire spec test suite in parallel across all available CPU cores', 'run the spec test suite in ahead-of-time compilation mode with wamrc compiler', 'run the spec test suite in SGX enclave environment with the iwasm SGX binary', 'run a WebAssembly .wast spec test file against the iwasm interpreter with optional AOT compilation', 'compile a .wast text format module to a .wasm binary using the wast2wasm tool', 'compile a .wasm module to an AOT binary for a target architecture like x86_64 or aarch64', 'parse a WebAssembly .wast file string into a list of top-level S-expression forms', 'test an assert_return form by invoking a WebAssembly function and comparing the return value']
```

Usage

```
{'run_spec_test_suite': 'run the whole WebAssembly spec test suite against iwasm interpreter with AOT or SGX flags', 'run_single_test_case': 'run a single .wast test case file against the iwasm interpreter with target architecture', 'run_parallel_test_suite': 'run the entire spec test suite in parallel across all available CPU cores', 'run_aot_test_suite': 'run the spec test suite in ahead-of-time compilation mode with wamrc compiler', 'run_sgx_test_suite': 'run the spec test suite in SGX enclave environment with the iwasm SGX binary'}
```

## File: facebookresearch_looptool/extern/wasm-micro-runtime/tests/wamr-test-suites/spec-test-script/runtest.py

Prompts

```
['run the whole WebAssembly spec test suite against iwasm interpreter with AOT or SGX flags', 'run a single .wast test case file against the iwasm interpreter with target architecture', 'run the entire spec test suite in parallel across all available CPU cores', 'run the spec test suite in ahead-of-time compilation mode with wamrc compiler', 'run the spec test suite in SGX enclave environment with the iwasm SGX binary', 'run a WebAssembly .wast spec test file against the iwasm interpreter with optional AOT compilation', 'compile a .wast text format module to a .wasm binary using the wast2wasm tool', 'compile a .wasm module to an AOT binary for a target architecture like x86_64 or aarch64', 'parse a WebAssembly .wast file string into a list of top-level S-expression forms', 'test an assert_return form by invoking a WebAssembly function and comparing the return value']
```

Usage

```
{'run_wasm_spec_tests': 'run a WebAssembly .wast spec test file against the iwasm interpreter with optional AOT compilation', 'compile_wast_to_wasm': 'compile a .wast text format module to a .wasm binary using the wast2wasm tool', 'compile_wasm_to_aot': 'compile a .wasm module to an AOT binary for a target architecture like x86_64 or aarch64', 'parse_wast_forms': 'parse a WebAssembly .wast file string into a list of top-level S-expression forms', 'test_assert_return': 'test an assert_return form by invoking a WebAssembly function and comparing the return value'}
```

