# Agent Python Tools

- repo: facebookresearch/hydra
- repo_uri: https://github.com/facebookresearch/hydra.git

## File: facebookresearch_hydra/plugins/hydra_ray_launcher/tests/test_ray_aws_launcher.py

Prompts

```
['build a wheel for the hydra_ray_launcher plugin and copy it to a temp directory', 'build a wheel for hydra-core and download its dependencies into a temp directory', 'upload hydra-core and plugin wheels to a Ray cluster and install them via pip', 'validate that ray, cloudpickle, and python versions match between local and remote cluster', 'test that RayAWSLauncher is discoverable via the Hydra plugins subsystem', 'test that RayLauncher is discoverable via Hydra plugins subsystem for Launcher type', 'run the LauncherTestSuite test suite against the Ray launcher with no overrides', 'run the IntegrationTestSuite against the Ray launcher with hydra debug logging enabled', 'review the TestRayLauncher class that extends LauncherTestSuite for Ray launcher unit tests', 'review the TestRayLauncherIntegration class that extends IntegrationTestSuite for Ray launcher integration tests']
```

Usage

```
{'build_ray_launcher_wheel': 'build a wheel for the hydra_ray_launcher plugin and copy it to a temp directory', 'build_core_wheel': 'build a wheel for hydra-core and download its dependencies into a temp directory', 'upload_and_install_wheels': 'upload hydra-core and plugin wheels to a Ray cluster and install them via pip', 'validate_lib_version': 'validate that ray, cloudpickle, and python versions match between local and remote cluster', 'test_discovery': 'test that RayAWSLauncher is discoverable via the Hydra plugins subsystem'}
```

## File: facebookresearch_hydra/plugins/hydra_ray_launcher/tests/test_ray_launcher.py

Prompts

```
['build a wheel for the hydra_ray_launcher plugin and copy it to a temp directory', 'build a wheel for hydra-core and download its dependencies into a temp directory', 'upload hydra-core and plugin wheels to a Ray cluster and install them via pip', 'validate that ray, cloudpickle, and python versions match between local and remote cluster', 'test that RayAWSLauncher is discoverable via the Hydra plugins subsystem', 'test that RayLauncher is discoverable via Hydra plugins subsystem for Launcher type', 'run the LauncherTestSuite test suite against the Ray launcher with no overrides', 'run the IntegrationTestSuite against the Ray launcher with hydra debug logging enabled', 'review the TestRayLauncher class that extends LauncherTestSuite for Ray launcher unit tests', 'review the TestRayLauncherIntegration class that extends IntegrationTestSuite for Ray launcher integration tests']
```

Usage

```
{'test_RayLauncher_discovery': 'test that RayLauncher is discoverable via Hydra plugins subsystem for Launcher type', 'run_TestRayLauncher_suite': 'run the LauncherTestSuite test suite against the Ray launcher with no overrides', 'run_TestRayLauncherIntegration_suite': 'run the IntegrationTestSuite against the Ray launcher with hydra debug logging enabled', 'review_TestRayLauncher_class': 'review the TestRayLauncher class that extends LauncherTestSuite for Ray launcher unit tests', 'review_TestRayLauncherIntegration_class': 'review the TestRayLauncherIntegration class that extends IntegrationTestSuite for Ray launcher integration tests'}
```

