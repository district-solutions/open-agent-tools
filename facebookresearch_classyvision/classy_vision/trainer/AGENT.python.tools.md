# Agent Python Tools

- repo: facebookresearch/classyvision
- repo_uri: https://github.com/facebookresearch/classyvision

## File: facebookresearch_classyvision/classy_vision/trainer/classy_trainer.py

Prompts

```
['run the ClassyTrainer train method to execute training phases on a ClassyTask', 'create a subclass of ClassyTrainer to customize distributed training environment setup', 'review the ClassyTrainer train method and its outer training loop control flow', 'test the ClassyTrainer by passing a ClassyTask instance to the train method', 'summarize the ClassyTrainer base class responsible for setting up and controlling training', 'initialize distributed training with NCCL or Gloo backend using environment variables for process group setup', 'set default environment variables for distributed training including WORLD_SIZE, RANK, MASTER_ADDR, and NCCL error handling', 'train a model across multiple processes using DistributedTrainer with GPU or CPU support', 'configure CUDA device index based on local rank for distributed GPU training', 'review the DistributedTrainer class that extends ClassyTrainer for multi-process distributed training', 'run a LocalTrainer to train a ClassyTask on a single GPU or CPU process', 'create a LocalTrainer instance that extends ClassyTrainer for single-process training', 'train a task using LocalTrainer with GPU by setting task.use_gpu to true', 'train a task using LocalTrainer with CPU by setting task.use_gpu to false', 'review the LocalTrainer class and its train method for single-process training setup']
```

Usage

```
{'run_ClassyTrainer_train': 'run the ClassyTrainer train method to execute training phases on a ClassyTask', 'create_ClassyTrainer_subclass': 'create a subclass of ClassyTrainer to customize distributed training environment setup', 'review_ClassyTrainer_train_loop': 'review the ClassyTrainer train method and its outer training loop control flow', 'test_ClassyTrainer_with_task': 'test the ClassyTrainer by passing a ClassyTask instance to the train method', 'summarize_ClassyTrainer': 'summarize the ClassyTrainer base class responsible for setting up and controlling training'}
```

## File: facebookresearch_classyvision/classy_vision/trainer/distributed_trainer.py

Prompts

```
['run the ClassyTrainer train method to execute training phases on a ClassyTask', 'create a subclass of ClassyTrainer to customize distributed training environment setup', 'review the ClassyTrainer train method and its outer training loop control flow', 'test the ClassyTrainer by passing a ClassyTask instance to the train method', 'summarize the ClassyTrainer base class responsible for setting up and controlling training', 'initialize distributed training with NCCL or Gloo backend using environment variables for process group setup', 'set default environment variables for distributed training including WORLD_SIZE, RANK, MASTER_ADDR, and NCCL error handling', 'train a model across multiple processes using DistributedTrainer with GPU or CPU support', 'configure CUDA device index based on local rank for distributed GPU training', 'review the DistributedTrainer class that extends ClassyTrainer for multi-process distributed training', 'run a LocalTrainer to train a ClassyTask on a single GPU or CPU process', 'create a LocalTrainer instance that extends ClassyTrainer for single-process training', 'train a task using LocalTrainer with GPU by setting task.use_gpu to true', 'train a task using LocalTrainer with CPU by setting task.use_gpu to false', 'review the LocalTrainer class and its train method for single-process training setup']
```

Usage

```
{'init_distributed_training': 'initialize distributed training with NCCL or Gloo backend using environment variables for process group setup', 'setup_env_vars': 'set default environment variables for distributed training including WORLD_SIZE, RANK, MASTER_ADDR, and NCCL error handling', 'train_distributed': 'train a model across multiple processes using DistributedTrainer with GPU or CPU support', 'configure_gpu_device': 'configure CUDA device index based on local rank for distributed GPU training', 'review_DistributedTrainer': 'review the DistributedTrainer class that extends ClassyTrainer for multi-process distributed training'}
```

## File: facebookresearch_classyvision/classy_vision/trainer/local_trainer.py

Prompts

```
['run the ClassyTrainer train method to execute training phases on a ClassyTask', 'create a subclass of ClassyTrainer to customize distributed training environment setup', 'review the ClassyTrainer train method and its outer training loop control flow', 'test the ClassyTrainer by passing a ClassyTask instance to the train method', 'summarize the ClassyTrainer base class responsible for setting up and controlling training', 'initialize distributed training with NCCL or Gloo backend using environment variables for process group setup', 'set default environment variables for distributed training including WORLD_SIZE, RANK, MASTER_ADDR, and NCCL error handling', 'train a model across multiple processes using DistributedTrainer with GPU or CPU support', 'configure CUDA device index based on local rank for distributed GPU training', 'review the DistributedTrainer class that extends ClassyTrainer for multi-process distributed training', 'run a LocalTrainer to train a ClassyTask on a single GPU or CPU process', 'create a LocalTrainer instance that extends ClassyTrainer for single-process training', 'train a task using LocalTrainer with GPU by setting task.use_gpu to true', 'train a task using LocalTrainer with CPU by setting task.use_gpu to false', 'review the LocalTrainer class and its train method for single-process training setup']
```

Usage

```
{'run_local_training': 'run a LocalTrainer to train a ClassyTask on a single GPU or CPU process', 'create_local_trainer': 'create a LocalTrainer instance that extends ClassyTrainer for single-process training', 'train_with_gpu': 'train a task using LocalTrainer with GPU by setting task.use_gpu to true', 'train_with_cpu': 'train a task using LocalTrainer with CPU by setting task.use_gpu to false', 'review_local_trainer': 'review the LocalTrainer class and its train method for single-process training setup'}
```

