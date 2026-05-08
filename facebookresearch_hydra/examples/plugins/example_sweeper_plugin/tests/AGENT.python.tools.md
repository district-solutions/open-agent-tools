# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/examples/plugins/example_sweeper_plugin/tests/test_example_sweeper_plugin.py

Prompts

```
['test that ExampleSweeper is discoverable via Hydra Plugins.instance().discover(Sweeper)', 'test launching sweep jobs with config overrides using hydra_sweep_runner and verify returned job configs', "test the ExampleSweeper against Hydra's LauncherTestSuite with the basic launcher", 'test the ExampleSweeper against BatchedSweeperTestSuite with max_batch_size set to 2', "test the ExampleSweeper against Hydra's IntegrationTestSuite with multi-run mode enabled"]
```

Usage

```
{'test_discovery': 'test that ExampleSweeper is discoverable via Hydra Plugins.instance().discover(Sweeper)', 'test_launched_jobs': 'test launching sweep jobs with config overrides using hydra_sweep_runner and verify returned job configs', 'test_TestExampleSweeper': "test the ExampleSweeper against Hydra's LauncherTestSuite with the basic launcher", 'test_TestExampleSweeperWithBatching': 'test the ExampleSweeper against BatchedSweeperTestSuite with max_batch_size set to 2', 'test_TestExampleSweeperIntegration': "test the ExampleSweeper against Hydra's IntegrationTestSuite with multi-run mode enabled"}
```

