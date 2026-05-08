# Agent Python Tools

- repo: facebookresearch/looptool
- repo_uri: https://github.com/facebookresearch/loop_tool

## File: facebookresearch_looptool/extern/wasm-micro-runtime/test-tools/component-test/suites/01-life-cycle/suite_setup.py

Prompts

```
['set up the CTestSuite lifecycle test environment by copying binaries, wasm files, and start/stop scripts to the run directory', 'run the on_suite_setup method to prepare test cases and optionally rebuild the test-app via build.sh', 'run the on_suite_cleanup method to restore the working directory and log environment shutdown', 'review the CTestSuite class and its on_suite_setup and on_suite_cleanup lifecycle methods for WASM component testing', 'refactor the CTestSuite on_suite_setup to parameterize file copy paths instead of hardcoding relative directories']
```

Usage

```
{'setup_test_suite': 'set up the CTestSuite lifecycle test environment by copying binaries, wasm files, and start/stop scripts to the run directory', 'run_suite_setup': 'run the on_suite_setup method to prepare test cases and optionally rebuild the test-app via build.sh', 'cleanup_test_suite': 'run the on_suite_cleanup method to restore the working directory and log environment shutdown', 'review_CTestSuite': 'review the CTestSuite class and its on_suite_setup and on_suite_cleanup lifecycle methods for WASM component testing', 'refactor_CTestSuite': 'refactor the CTestSuite on_suite_setup to parameterize file copy paths instead of hardcoding relative directories'}
```

