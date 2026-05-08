# Agent Python Tools

- repo: facebookresearch/looptool
- repo_uri: https://github.com/facebookresearch/loop_tool

## File: facebookresearch_looptool/extern/wasm-micro-runtime/test-tools/component-test/suites/01-life-cycle/cases/03-event/case.py

Prompts

```
['run the CTestCase to install a WASM app named App1 using 03_event.wasm', 'run the CTestCase to query installed apps and verify App1 is registered', 'run the CTestCase to register an event at /alert/overheat with min 2000 and max 5000 thresholds', 'run the CTestCase to deregister the /alert/overheat event and verify cleanup', 'run the CTestCase to start and stop the test environment using start_env and stop_env']
```

Usage

```
{'run_install_app_test': 'run the CTestCase to install a WASM app named App1 using 03_event.wasm', 'run_query_app_test': 'run the CTestCase to query installed apps and verify App1 is registered', 'run_register_event_test': 'run the CTestCase to register an event at /alert/overheat with min 2000 and max 5000 thresholds', 'run_deregister_event_test': 'run the CTestCase to deregister the /alert/overheat event and verify cleanup', 'run_setup_cleanup_test': 'run the CTestCase to start and stop the test environment using start_env and stop_env'}
```

