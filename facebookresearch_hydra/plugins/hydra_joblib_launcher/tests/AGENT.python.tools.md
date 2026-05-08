# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/plugins/hydra_joblib_launcher/tests/test_joblib_launcher.py

Prompts

```
['test that JoblibLauncher is discoverable via the Hydra plugins subsystem for Launcher type', 'run the LauncherTestSuite parametrized tests against the joblib launcher with no overrides', 'run the IntegrationTestSuite against the joblib launcher with process-based backend and debug logging', 'test running a Hydra sweep with four tasks using the joblib launcher and verify all returns', 'test the joblib launcher with various config overrides like batch_size, max_nbytes, and pre_dispatch']
```

Usage

```
{'test_discovery': 'test that JoblibLauncher is discoverable via the Hydra plugins subsystem for Launcher type', 'run_test_joblib_launcher_suite': 'run the LauncherTestSuite parametrized tests against the joblib launcher with no overrides', 'run_test_joblib_launcher_integration': 'run the IntegrationTestSuite against the joblib launcher with process-based backend and debug logging', 'test_example_app': 'test running a Hydra sweep with four tasks using the joblib launcher and verify all returns', 'test_example_app_launcher_overrides': 'test the joblib launcher with various config overrides like batch_size, max_nbytes, and pre_dispatch'}
```

