# Agent Python Tools

- repo: facebookresearch/paco
- repo_uri: https://github.com/facebookresearch/paco

## File: facebookresearch_paco/tools/lazyconfig_train_net.py

Prompts

```
['run a detectron2 training job using a lazyconfig YAML file and optional CLI overrides', 'run evaluation only on a detectron2 model by loading a checkpoint and testing on the configured dataset', 'resume a detectron2 training run from the latest checkpoint in the output directory', 'launch multi-GPU distributed training for a detectron2 model using the num_gpus argument', 'apply command-line overrides to a lazyconfig YAML file before training or evaluation', 'run multi-node Detectron2 training via submitit on a SLURM cluster with multiple GPUs', 'submit a Detectron2 training job to a SLURM partition using the Trainer class and AutoExecutor', 'resume a previous Detectron2 training job from a checkpoint using the resume-job flag', 'parse command-line arguments for multi-node Detectron2 training including partition, timeout, and GPU count', 'check if a config file is a YACS config by inspecting its format and contents']
```

Usage

```
{'run_training': 'run a detectron2 training job using a lazyconfig YAML file and optional CLI overrides', 'run_evaluation': 'run evaluation only on a detectron2 model by loading a checkpoint and testing on the configured dataset', 'resume_training': 'resume a detectron2 training run from the latest checkpoint in the output directory', 'configure_multi_gpu': 'launch multi-GPU distributed training for a detectron2 model using the num_gpus argument', 'override_config': 'apply command-line overrides to a lazyconfig YAML file before training or evaluation'}
```

## File: facebookresearch_paco/tools/multi_node_training.py

Prompts

```
['run a detectron2 training job using a lazyconfig YAML file and optional CLI overrides', 'run evaluation only on a detectron2 model by loading a checkpoint and testing on the configured dataset', 'resume a detectron2 training run from the latest checkpoint in the output directory', 'launch multi-GPU distributed training for a detectron2 model using the num_gpus argument', 'apply command-line overrides to a lazyconfig YAML file before training or evaluation', 'run multi-node Detectron2 training via submitit on a SLURM cluster with multiple GPUs', 'submit a Detectron2 training job to a SLURM partition using the Trainer class and AutoExecutor', 'resume a previous Detectron2 training job from a checkpoint using the resume-job flag', 'parse command-line arguments for multi-node Detectron2 training including partition, timeout, and GPU count', 'check if a config file is a YACS config by inspecting its format and contents']
```

Usage

```
{'run_multi_node_training': 'run multi-node Detectron2 training via submitit on a SLURM cluster with multiple GPUs', 'submit_training_job': 'submit a Detectron2 training job to a SLURM partition using the Trainer class and AutoExecutor', 'resume_training_job': 'resume a previous Detectron2 training job from a checkpoint using the resume-job flag', 'parse_training_args': 'parse command-line arguments for multi-node Detectron2 training including partition, timeout, and GPU count', 'check_yacs_config': 'check if a config file is a YACS config by inspecting its format and contents'}
```

