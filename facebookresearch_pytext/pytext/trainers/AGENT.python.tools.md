# Agent Python Tools

- repo: facebookresearch/pytext
- repo_uri: https://github.com/facebookresearch/pytext

## File: facebookresearch_pytext/pytext/trainers/ensemble_trainer.py

Prompts

```
['build an EnsembleTrainer instance with a list of real trainers for ensemble model training', 'create an EnsembleTrainer from a Config object and a torch.nn.Module with sub models', 'train an ensemble model by sequentially training each sub model and merging their states', 'review the EnsembleTrainer Config class that wraps a TaskTrainer config for real trainer setup', 'summarize the EnsembleTrainer init that delegates optimizer, test, and train_single_model from the first trainer', 'create a HogwildTrainer from a config with a specified number of workers for parallel training', 'run a training epoch using HogwildTrainer that spawns multiple processes for parallel parameter updates', 'set up shared memory for model parameters so multiple worker processes can update them concurrently', 'review the HogwildTrainer Config class to understand real_trainer and num_workers settings', 'refactor the HogwildTrainer from_config method to change the CUDA or single-worker fallback behavior', 'train a PyText model using Trainer.train with training data, eval data, and a metric reporter', 'configure a Trainer with a custom optimizer, scheduler, and sparsifier via Trainer.Config', 'run model evaluation using Trainer.eval_from_state with a TrainingState and BatchIterator', 'test a trained PyText model using Trainer.test with a test iterator and metric reporter', 'set up FP16 distributed training using FP16GradsTrainer with fp16 gradient compression hooks']
```

Usage

```
{'build_ensemble_trainer': 'build an EnsembleTrainer instance with a list of real trainers for ensemble model training', 'create_ensemble_trainer_from_config': 'create an EnsembleTrainer from a Config object and a torch.nn.Module with sub models', 'train_ensemble_model': 'train an ensemble model by sequentially training each sub model and merging their states', 'review_ensemble_trainer_config': 'review the EnsembleTrainer Config class that wraps a TaskTrainer config for real trainer setup', 'summarize_ensemble_trainer_init': 'summarize the EnsembleTrainer init that delegates optimizer, test, and train_single_model from the first trainer'}
```

## File: facebookresearch_pytext/pytext/trainers/hogwild_trainer.py

Prompts

```
['build an EnsembleTrainer instance with a list of real trainers for ensemble model training', 'create an EnsembleTrainer from a Config object and a torch.nn.Module with sub models', 'train an ensemble model by sequentially training each sub model and merging their states', 'review the EnsembleTrainer Config class that wraps a TaskTrainer config for real trainer setup', 'summarize the EnsembleTrainer init that delegates optimizer, test, and train_single_model from the first trainer', 'create a HogwildTrainer from a config with a specified number of workers for parallel training', 'run a training epoch using HogwildTrainer that spawns multiple processes for parallel parameter updates', 'set up shared memory for model parameters so multiple worker processes can update them concurrently', 'review the HogwildTrainer Config class to understand real_trainer and num_workers settings', 'refactor the HogwildTrainer from_config method to change the CUDA or single-worker fallback behavior', 'train a PyText model using Trainer.train with training data, eval data, and a metric reporter', 'configure a Trainer with a custom optimizer, scheduler, and sparsifier via Trainer.Config', 'run model evaluation using Trainer.eval_from_state with a TrainingState and BatchIterator', 'test a trained PyText model using Trainer.test with a test iterator and metric reporter', 'set up FP16 distributed training using FP16GradsTrainer with fp16 gradient compression hooks']
```

Usage

```
{'create_hogwild_trainer_from_config': 'create a HogwildTrainer from a config with a specified number of workers for parallel training', 'run_hogwild_epoch_multiprocess': 'run a training epoch using HogwildTrainer that spawns multiple processes for parallel parameter updates', 'setup_hogwild_shared_memory': 'set up shared memory for model parameters so multiple worker processes can update them concurrently', 'review_hogwild_trainer_config': 'review the HogwildTrainer Config class to understand real_trainer and num_workers settings', 'refactor_hogwild_from_config_fallback': 'refactor the HogwildTrainer from_config method to change the CUDA or single-worker fallback behavior'}
```

## File: facebookresearch_pytext/pytext/trainers/trainer.py

Prompts

```
['build an EnsembleTrainer instance with a list of real trainers for ensemble model training', 'create an EnsembleTrainer from a Config object and a torch.nn.Module with sub models', 'train an ensemble model by sequentially training each sub model and merging their states', 'review the EnsembleTrainer Config class that wraps a TaskTrainer config for real trainer setup', 'summarize the EnsembleTrainer init that delegates optimizer, test, and train_single_model from the first trainer', 'create a HogwildTrainer from a config with a specified number of workers for parallel training', 'run a training epoch using HogwildTrainer that spawns multiple processes for parallel parameter updates', 'set up shared memory for model parameters so multiple worker processes can update them concurrently', 'review the HogwildTrainer Config class to understand real_trainer and num_workers settings', 'refactor the HogwildTrainer from_config method to change the CUDA or single-worker fallback behavior', 'train a PyText model using Trainer.train with training data, eval data, and a metric reporter', 'configure a Trainer with a custom optimizer, scheduler, and sparsifier via Trainer.Config', 'run model evaluation using Trainer.eval_from_state with a TrainingState and BatchIterator', 'test a trained PyText model using Trainer.test with a test iterator and metric reporter', 'set up FP16 distributed training using FP16GradsTrainer with fp16 gradient compression hooks']
```

Usage

```
{'train_model_with_trainer': 'train a PyText model using Trainer.train with training data, eval data, and a metric reporter', 'configure_trainer_optimizer': 'configure a Trainer with a custom optimizer, scheduler, and sparsifier via Trainer.Config', 'run_evaluation_with_trainer': 'run model evaluation using Trainer.eval_from_state with a TrainingState and BatchIterator', 'test_model_with_trainer': 'test a trained PyText model using Trainer.test with a test iterator and metric reporter', 'setup_fp16_distributed_training': 'set up FP16 distributed training using FP16GradsTrainer with fp16 gradient compression hooks'}
```

