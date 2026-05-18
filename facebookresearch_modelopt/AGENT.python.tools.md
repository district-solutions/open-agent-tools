# Agent Python Tools

- repo: facebookresearch/modelopt
- repo_uri: https://github.com/facebookresearch/model_opt

## File: facebookresearch_modelopt/benchmarks.py

Prompts

```
['run a benchmark for a PyTorch model like resnet18 in eval or train mode with a given batch size', 'run node ordering optimization on a computation graph to reduce peak memory usage using the ILP solver', 'run a memory simulation on a computation graph with a given node ordering to estimate peak memory usage', 'run rematerialization planning to reduce memory usage by a target percentage and measure the runtime overhead', 'run spilling planning to reduce memory usage by swapping data and measure the estimated runtime overhead', 'run python setup.py install to install the model_opt package with all dependencies', 'get the local version suffix string combining git hash and current date', 'write a version.py file containing the package version and optional git tag', 'read and return the list of install requirements from requirements.txt', 'review the setuptools setup configuration for the model_opt package']
```

Usage

```
{'run_model_benchmark': 'run a benchmark for a PyTorch model like resnet18 in eval or train mode with a given batch size', 'run_node_ordering': 'run node ordering optimization on a computation graph to reduce peak memory usage using the ILP solver', 'run_simulation': 'run a memory simulation on a computation graph with a given node ordering to estimate peak memory usage', 'run_rematerialization': 'run rematerialization planning to reduce memory usage by a target percentage and measure the runtime overhead', 'run_spilling': 'run spilling planning to reduce memory usage by swapping data and measure the estimated runtime overhead'}
```

## File: facebookresearch_modelopt/setup.py

Prompts

```
['run a benchmark for a PyTorch model like resnet18 in eval or train mode with a given batch size', 'run node ordering optimization on a computation graph to reduce peak memory usage using the ILP solver', 'run a memory simulation on a computation graph with a given node ordering to estimate peak memory usage', 'run rematerialization planning to reduce memory usage by a target percentage and measure the runtime overhead', 'run spilling planning to reduce memory usage by swapping data and measure the estimated runtime overhead', 'run python setup.py install to install the model_opt package with all dependencies', 'get the local version suffix string combining git hash and current date', 'write a version.py file containing the package version and optional git tag', 'read and return the list of install requirements from requirements.txt', 'review the setuptools setup configuration for the model_opt package']
```

Usage

```
{'run_setup_install': 'run python setup.py install to install the model_opt package with all dependencies', 'get_local_version_suffix': 'get the local version suffix string combining git hash and current date', 'write_version_file': 'write a version.py file containing the package version and optional git tag', 'get_install_requires': 'read and return the list of install requirements from requirements.txt', 'review_setup_config': 'review the setuptools setup configuration for the model_opt package'}
```

