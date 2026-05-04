# Agent Python Tools

- repo: facebookresearch/banmo
- repo_uri: https://github.com/facebookresearch/banmo

## File: facebookresearch_banmo/third_party/detectron2_old/projects/TensorMask/setup.py

Prompts

```
['build the tensormask python package with C++ extensions using python setup.py build_ext', 'install the tensormask package with CUDA support by setting FORCE_CUDA=1 before running pip install', 'build the tensormask package with CPU-only C++ extensions when CUDA is not available', 'review the get_extensions function to understand how C++ and CUDA sources are discovered and compiled', 'refactor the get_extensions function to support additional compiler flags or source directories', 'run the TensorMask training script with a config file and optional command line arguments', 'run the TensorMask training script in eval-only mode to test a model on a dataset', 'build a COCOEvaluator for the TensorMask Trainer class to evaluate model inference results', 'setup the TensorMask configuration by merging a config file and command line options', 'test a TensorMask model by building it, loading weights, and running evaluation']
```

Usage

```
{'build_tensormask_package': 'build the tensormask python package with C++ extensions using python setup.py build_ext', 'install_tensormask_with_cuda': 'install the tensormask package with CUDA support by setting FORCE_CUDA=1 before running pip install', 'build_tensormask_cpu_only': 'build the tensormask package with CPU-only C++ extensions when CUDA is not available', 'review_get_extensions': 'review the get_extensions function to understand how C++ and CUDA sources are discovered and compiled', 'refactor_get_extensions': 'refactor the get_extensions function to support additional compiler flags or source directories'}
```

## File: facebookresearch_banmo/third_party/detectron2_old/projects/TensorMask/train_net.py

Prompts

```
['build the tensormask python package with C++ extensions using python setup.py build_ext', 'install the tensormask package with CUDA support by setting FORCE_CUDA=1 before running pip install', 'build the tensormask package with CPU-only C++ extensions when CUDA is not available', 'review the get_extensions function to understand how C++ and CUDA sources are discovered and compiled', 'refactor the get_extensions function to support additional compiler flags or source directories', 'run the TensorMask training script with a config file and optional command line arguments', 'run the TensorMask training script in eval-only mode to test a model on a dataset', 'build a COCOEvaluator for the TensorMask Trainer class to evaluate model inference results', 'setup the TensorMask configuration by merging a config file and command line options', 'test a TensorMask model by building it, loading weights, and running evaluation']
```

Usage

```
{'run_train_net': 'run the TensorMask training script with a config file and optional command line arguments', 'run_train_net_eval_only': 'run the TensorMask training script in eval-only mode to test a model on a dataset', 'build_trainer_evaluator': 'build a COCOEvaluator for the TensorMask Trainer class to evaluate model inference results', 'setup_tensor_mask_config': 'setup the TensorMask configuration by merging a config file and command line options', 'test_tensor_mask_model': 'test a TensorMask model by building it, loading weights, and running evaluation'}
```

