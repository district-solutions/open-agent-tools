# Agent Python Tools

- repo: facebookresearch/detectron2
- repo_uri: https://github.com/facebookresearch/detectron2.git

## File: facebookresearch_detectron2/projects/TensorMask/setup.py

Prompts

```
['build the tensormask C++ extension module with CUDA support using pytorch cpp_extension', 'build the tensormask C++ extension module for CPU only without CUDA compilation', 'review the get_extensions function that configures C++ and CUDA sources for the tensormask extension', 'review the setup call that configures the tensormask package with name version and ext_modules', 'summarize the CUDA compile arguments including FP16 support and half operator flags', 'run the TensorMask training script with a config file and optional CLI arguments via invoke_main', 'run the Trainer class test method to evaluate a model on a COCO dataset', 'build a COCOEvaluator for a given dataset name and output folder using Trainer.build_evaluator', 'run the setup function to create and freeze a TensorMask config from a config file and CLI opts', 'run the main function in eval_only mode to load weights and verify results on a dataset']
```

Usage

```
{'build_tensormask_extension': 'build the tensormask C++ extension module with CUDA support using pytorch cpp_extension', 'build_tensormask_cpu_only': 'build the tensormask C++ extension module for CPU only without CUDA compilation', 'review_get_extensions': 'review the get_extensions function that configures C++ and CUDA sources for the tensormask extension', 'review_setup_call': 'review the setup call that configures the tensormask package with name version and ext_modules', 'summarize_cuda_compile_args': 'summarize the CUDA compile arguments including FP16 support and half operator flags'}
```

## File: facebookresearch_detectron2/projects/TensorMask/train_net.py

Prompts

```
['build the tensormask C++ extension module with CUDA support using pytorch cpp_extension', 'build the tensormask C++ extension module for CPU only without CUDA compilation', 'review the get_extensions function that configures C++ and CUDA sources for the tensormask extension', 'review the setup call that configures the tensormask package with name version and ext_modules', 'summarize the CUDA compile arguments including FP16 support and half operator flags', 'run the TensorMask training script with a config file and optional CLI arguments via invoke_main', 'run the Trainer class test method to evaluate a model on a COCO dataset', 'build a COCOEvaluator for a given dataset name and output folder using Trainer.build_evaluator', 'run the setup function to create and freeze a TensorMask config from a config file and CLI opts', 'run the main function in eval_only mode to load weights and verify results on a dataset']
```

Usage

```
{'run_train_net': 'run the TensorMask training script with a config file and optional CLI arguments via invoke_main', 'run_trainer_test': 'run the Trainer class test method to evaluate a model on a COCO dataset', 'build_trainer_evaluator': 'build a COCOEvaluator for a given dataset name and output folder using Trainer.build_evaluator', 'run_setup_config': 'run the setup function to create and freeze a TensorMask config from a config file and CLI opts', 'run_main_eval': 'run the main function in eval_only mode to load weights and verify results on a dataset'}
```

