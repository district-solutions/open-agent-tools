# Agent Python Tools

- repo: google-deepmind/deepmind-research
- repo_uri: https://github.com/google-deepmind/deepmind-research

## File: google-deepmind_deepmind-research/byol/byol_experiment.py

Prompts

```
['build a BYOL self-supervised representation learning experiment with configurable network and optimizer settings', 'run a single training step of the BYOL experiment with online and target network updates', 'create a loss function combining representation regression loss and classification cross-entropy loss', 'evaluate the BYOL model on a dataset subset and return accuracy and loss metrics', 'initialize the BYOL experiment state with online and target network parameters and optimizer state', 'build a linear evaluation experiment to evaluate a BYOL checkpoint on a classification dataset', 'run a single training step of the EvalExperiment with a given global step and RNG key', 'run evaluation on a dataset subset and return loss and top1/top5 accuracy metrics', 'save or load an EvalExperiment checkpoint to persist backbone and classifier parameters', 'configure the EvalExperiment to freeze the backbone for linear evaluation instead of fine-tuning', 'run the BYOL pretraining loop with a specified batch size and number of epochs', 'run the linear evaluation loop on a pretrained BYOL checkpoint', 'run the training loop with an experiment class and config mapping', 'run the evaluation loop that periodically loads checkpoints and evaluates performance', 'configure the JAX TPU driver backend for distributed training on TPUs', 'test the BYOL pretraining loop using main_loop.train_loop with ByolExperiment and a TinyResNet encoder', 'test the linear evaluation loop using main_loop.train_loop with EvalExperiment and a TinyResNet encoder', 'test the full BYOL pipeline by running pretraining then linear evaluation on the saved checkpoint', 'run the BYOL training loop with main_loop.train_loop passing an experiment class and config dictionary', 'run the BYOL evaluation loop with main_loop.eval_loop passing an experiment class and config dictionary']
```

Usage

```
{'build_byol_experiment': 'build a BYOL self-supervised representation learning experiment with configurable network and optimizer settings', 'run_byol_training_step': 'run a single training step of the BYOL experiment with online and target network updates', 'create_byol_loss_function': 'create a loss function combining representation regression loss and classification cross-entropy loss', 'evaluate_byol_model': 'evaluate the BYOL model on a dataset subset and return accuracy and loss metrics', 'initialize_byol_state': 'initialize the BYOL experiment state with online and target network parameters and optimizer state'}
```

## File: google-deepmind_deepmind-research/byol/eval_experiment.py

Prompts

```
['build a BYOL self-supervised representation learning experiment with configurable network and optimizer settings', 'run a single training step of the BYOL experiment with online and target network updates', 'create a loss function combining representation regression loss and classification cross-entropy loss', 'evaluate the BYOL model on a dataset subset and return accuracy and loss metrics', 'initialize the BYOL experiment state with online and target network parameters and optimizer state', 'build a linear evaluation experiment to evaluate a BYOL checkpoint on a classification dataset', 'run a single training step of the EvalExperiment with a given global step and RNG key', 'run evaluation on a dataset subset and return loss and top1/top5 accuracy metrics', 'save or load an EvalExperiment checkpoint to persist backbone and classifier parameters', 'configure the EvalExperiment to freeze the backbone for linear evaluation instead of fine-tuning', 'run the BYOL pretraining loop with a specified batch size and number of epochs', 'run the linear evaluation loop on a pretrained BYOL checkpoint', 'run the training loop with an experiment class and config mapping', 'run the evaluation loop that periodically loads checkpoints and evaluates performance', 'configure the JAX TPU driver backend for distributed training on TPUs', 'test the BYOL pretraining loop using main_loop.train_loop with ByolExperiment and a TinyResNet encoder', 'test the linear evaluation loop using main_loop.train_loop with EvalExperiment and a TinyResNet encoder', 'test the full BYOL pipeline by running pretraining then linear evaluation on the saved checkpoint', 'run the BYOL training loop with main_loop.train_loop passing an experiment class and config dictionary', 'run the BYOL evaluation loop with main_loop.eval_loop passing an experiment class and config dictionary']
```

Usage

```
{'build_eval_experiment': 'build a linear evaluation experiment to evaluate a BYOL checkpoint on a classification dataset', 'run_training_step': 'run a single training step of the EvalExperiment with a given global step and RNG key', 'run_evaluation': 'run evaluation on a dataset subset and return loss and top1/top5 accuracy metrics', 'save_load_checkpoint': 'save or load an EvalExperiment checkpoint to persist backbone and classifier parameters', 'freeze_backbone_linear_eval': 'configure the EvalExperiment to freeze the backbone for linear evaluation instead of fine-tuning'}
```

## File: google-deepmind_deepmind-research/byol/main_loop.py

Prompts

```
['build a BYOL self-supervised representation learning experiment with configurable network and optimizer settings', 'run a single training step of the BYOL experiment with online and target network updates', 'create a loss function combining representation regression loss and classification cross-entropy loss', 'evaluate the BYOL model on a dataset subset and return accuracy and loss metrics', 'initialize the BYOL experiment state with online and target network parameters and optimizer state', 'build a linear evaluation experiment to evaluate a BYOL checkpoint on a classification dataset', 'run a single training step of the EvalExperiment with a given global step and RNG key', 'run evaluation on a dataset subset and return loss and top1/top5 accuracy metrics', 'save or load an EvalExperiment checkpoint to persist backbone and classifier parameters', 'configure the EvalExperiment to freeze the backbone for linear evaluation instead of fine-tuning', 'run the BYOL pretraining loop with a specified batch size and number of epochs', 'run the linear evaluation loop on a pretrained BYOL checkpoint', 'run the training loop with an experiment class and config mapping', 'run the evaluation loop that periodically loads checkpoints and evaluates performance', 'configure the JAX TPU driver backend for distributed training on TPUs', 'test the BYOL pretraining loop using main_loop.train_loop with ByolExperiment and a TinyResNet encoder', 'test the linear evaluation loop using main_loop.train_loop with EvalExperiment and a TinyResNet encoder', 'test the full BYOL pipeline by running pretraining then linear evaluation on the saved checkpoint', 'run the BYOL training loop with main_loop.train_loop passing an experiment class and config dictionary', 'run the BYOL evaluation loop with main_loop.eval_loop passing an experiment class and config dictionary']
```

Usage

```
{'run_byol_pretraining': 'run the BYOL pretraining loop with a specified batch size and number of epochs', 'run_byol_linear_eval': 'run the linear evaluation loop on a pretrained BYOL checkpoint', 'run_train_loop': 'run the training loop with an experiment class and config mapping', 'run_eval_loop': 'run the evaluation loop that periodically loads checkpoints and evaluates performance', 'configure_tpu_driver': 'configure the JAX TPU driver backend for distributed training on TPUs'}
```

## File: google-deepmind_deepmind-research/byol/main_loop_test.py

Prompts

```
['build a BYOL self-supervised representation learning experiment with configurable network and optimizer settings', 'run a single training step of the BYOL experiment with online and target network updates', 'create a loss function combining representation regression loss and classification cross-entropy loss', 'evaluate the BYOL model on a dataset subset and return accuracy and loss metrics', 'initialize the BYOL experiment state with online and target network parameters and optimizer state', 'build a linear evaluation experiment to evaluate a BYOL checkpoint on a classification dataset', 'run a single training step of the EvalExperiment with a given global step and RNG key', 'run evaluation on a dataset subset and return loss and top1/top5 accuracy metrics', 'save or load an EvalExperiment checkpoint to persist backbone and classifier parameters', 'configure the EvalExperiment to freeze the backbone for linear evaluation instead of fine-tuning', 'run the BYOL pretraining loop with a specified batch size and number of epochs', 'run the linear evaluation loop on a pretrained BYOL checkpoint', 'run the training loop with an experiment class and config mapping', 'run the evaluation loop that periodically loads checkpoints and evaluates performance', 'configure the JAX TPU driver backend for distributed training on TPUs', 'test the BYOL pretraining loop using main_loop.train_loop with ByolExperiment and a TinyResNet encoder', 'test the linear evaluation loop using main_loop.train_loop with EvalExperiment and a TinyResNet encoder', 'test the full BYOL pipeline by running pretraining then linear evaluation on the saved checkpoint', 'run the BYOL training loop with main_loop.train_loop passing an experiment class and config dictionary', 'run the BYOL evaluation loop with main_loop.eval_loop passing an experiment class and config dictionary']
```

Usage

```
{'test_BYOL_pretraining': 'test the BYOL pretraining loop using main_loop.train_loop with ByolExperiment and a TinyResNet encoder', 'test_linear_evaluation': 'test the linear evaluation loop using main_loop.train_loop with EvalExperiment and a TinyResNet encoder', 'test_full_pipeline': 'test the full BYOL pipeline by running pretraining then linear evaluation on the saved checkpoint', 'run_main_loop_train': 'run the BYOL training loop with main_loop.train_loop passing an experiment class and config dictionary', 'run_main_loop_eval': 'run the BYOL evaluation loop with main_loop.eval_loop passing an experiment class and config dictionary'}
```

