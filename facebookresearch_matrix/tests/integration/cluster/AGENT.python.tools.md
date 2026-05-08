# Agent Python Tools

- repo: facebookresearch/matrix
- repo_uri: https://github.com/facebookresearch/matrix

## File: facebookresearch_matrix/tests/integration/cluster/test_no_array_mode.py

Prompts

```
['test that a Ray cluster starts successfully with use_array=False and has valid hostname and port', 'test that workers have CPU resources allocated when starting a cluster with use_array=False', 'test deploying a hello application on a cluster started with use_array=False and verify health', 'test that workers can be added incrementally to a cluster with use_array=False and resources increase', 'test the module-scoped pytest fixture that starts and stops a Ray cluster with use_array=False']
```

Usage

```
{'test_cluster_starts_no_array': 'test that a Ray cluster starts successfully with use_array=False and has valid hostname and port', 'test_workers_have_resources_no_array': 'test that workers have CPU resources allocated when starting a cluster with use_array=False', 'test_deploy_hello_no_array': 'test deploying a hello application on a cluster started with use_array=False and verify health', 'test_incremental_scaling_no_array': 'test that workers can be added incrementally to a cluster with use_array=False and resources increase', 'test_matrix_cluster_no_array_fixture': 'test the module-scoped pytest fixture that starts and stops a Ray cluster with use_array=False'}
```

