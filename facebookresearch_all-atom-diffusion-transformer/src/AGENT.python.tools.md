# Agent Python Tools

- repo: facebookresearch/all-atom-diffusion-transformer
- repo_uri: https://github.com/facebookresearch/all-atom-diffusion-transformer

## File: facebookresearch_all-atom-diffusion-transformer/src/eval_autoencoder.py

Prompts

```
['run the autoencoder evaluation script using Hydra config and a model checkpoint path', 'run the evaluate function to test an autoencoder checkpoint on a Lightning datamodule testset', 'run the main entry point that applies extras utilities and calls evaluate with Hydra config', 'review the evaluate function that instantiates a datamodule, autoencoder model, loggers, and trainer', 'review the task_wrapper decorator that controls failure behavior during multiruns and saves crash info', 'run the diffusion model evaluation on a checkpoint using Hydra config and Lightning trainer', 'run the main entry point that loads eval_diffusion.yaml config and starts evaluation', 'test a model checkpoint against the datamodule testset using the Lightning trainer', 'instantiate a diffusion model, datamodule, loggers, and trainer from a Hydra DictConfig', 'run the autoencoder training script with Hydra config overrides for model and data', 'train an autoencoder model for reconstruction using a Hydra DictConfig with Lightning trainer', 'test the trained autoencoder model using the best checkpoint from training', 'instantiate a LightningDataModule, LightningModule, Trainer, loggers, and callbacks from Hydra config', 'run Hydra-based hyperparameter optimization for the autoencoder and retrieve the optimized metric value', 'run the diffusion model training pipeline using Hydra config and PyTorch Lightning', 'train a diffusion model for generative modelling with configurable data module and callbacks', 'test the trained diffusion model using the best checkpoint from training', 'instantiate a Lightning Trainer with callbacks and loggers from Hydra config', 'run Hydra-based hyperparameter optimization and retrieve the optimized metric value']
```

Usage

```
{'run_autoencoder_evaluation': 'run the autoencoder evaluation script using Hydra config and a model checkpoint path', 'run_evaluate_function': 'run the evaluate function to test an autoencoder checkpoint on a Lightning datamodule testset', 'run_main_entry': 'run the main entry point that applies extras utilities and calls evaluate with Hydra config', 'review_evaluate_function': 'review the evaluate function that instantiates a datamodule, autoencoder model, loggers, and trainer', 'review_task_wrapper': 'review the task_wrapper decorator that controls failure behavior during multiruns and saves crash info'}
```

## File: facebookresearch_all-atom-diffusion-transformer/src/eval_diffusion.py

Prompts

```
['run the autoencoder evaluation script using Hydra config and a model checkpoint path', 'run the evaluate function to test an autoencoder checkpoint on a Lightning datamodule testset', 'run the main entry point that applies extras utilities and calls evaluate with Hydra config', 'review the evaluate function that instantiates a datamodule, autoencoder model, loggers, and trainer', 'review the task_wrapper decorator that controls failure behavior during multiruns and saves crash info', 'run the diffusion model evaluation on a checkpoint using Hydra config and Lightning trainer', 'run the main entry point that loads eval_diffusion.yaml config and starts evaluation', 'test a model checkpoint against the datamodule testset using the Lightning trainer', 'instantiate a diffusion model, datamodule, loggers, and trainer from a Hydra DictConfig', 'run the autoencoder training script with Hydra config overrides for model and data', 'train an autoencoder model for reconstruction using a Hydra DictConfig with Lightning trainer', 'test the trained autoencoder model using the best checkpoint from training', 'instantiate a LightningDataModule, LightningModule, Trainer, loggers, and callbacks from Hydra config', 'run Hydra-based hyperparameter optimization for the autoencoder and retrieve the optimized metric value', 'run the diffusion model training pipeline using Hydra config and PyTorch Lightning', 'train a diffusion model for generative modelling with configurable data module and callbacks', 'test the trained diffusion model using the best checkpoint from training', 'instantiate a Lightning Trainer with callbacks and loggers from Hydra config', 'run Hydra-based hyperparameter optimization and retrieve the optimized metric value']
```

Usage

```
{'run_diffusion_model_evaluation': 'run the diffusion model evaluation on a checkpoint using Hydra config and Lightning trainer', 'run_main_entry_point': 'run the main entry point that loads eval_diffusion.yaml config and starts evaluation', 'test_checkpoint_with_trainer': 'test a model checkpoint against the datamodule testset using the Lightning trainer', 'instantiate_diffusion_model_from_config': 'instantiate a diffusion model, datamodule, loggers, and trainer from a Hydra DictConfig', 'review_evaluate_function': 'review the evaluate function that instantiates components and runs trainer.test on a checkpoint'}
```

## File: facebookresearch_all-atom-diffusion-transformer/src/train_autoencoder.py

Prompts

```
['run the autoencoder evaluation script using Hydra config and a model checkpoint path', 'run the evaluate function to test an autoencoder checkpoint on a Lightning datamodule testset', 'run the main entry point that applies extras utilities and calls evaluate with Hydra config', 'review the evaluate function that instantiates a datamodule, autoencoder model, loggers, and trainer', 'review the task_wrapper decorator that controls failure behavior during multiruns and saves crash info', 'run the diffusion model evaluation on a checkpoint using Hydra config and Lightning trainer', 'run the main entry point that loads eval_diffusion.yaml config and starts evaluation', 'test a model checkpoint against the datamodule testset using the Lightning trainer', 'instantiate a diffusion model, datamodule, loggers, and trainer from a Hydra DictConfig', 'run the autoencoder training script with Hydra config overrides for model and data', 'train an autoencoder model for reconstruction using a Hydra DictConfig with Lightning trainer', 'test the trained autoencoder model using the best checkpoint from training', 'instantiate a LightningDataModule, LightningModule, Trainer, loggers, and callbacks from Hydra config', 'run Hydra-based hyperparameter optimization for the autoencoder and retrieve the optimized metric value', 'run the diffusion model training pipeline using Hydra config and PyTorch Lightning', 'train a diffusion model for generative modelling with configurable data module and callbacks', 'test the trained diffusion model using the best checkpoint from training', 'instantiate a Lightning Trainer with callbacks and loggers from Hydra config', 'run Hydra-based hyperparameter optimization and retrieve the optimized metric value']
```

Usage

```
{'run_train_autoencoder': 'run the autoencoder training script with Hydra config overrides for model and data', 'train_autoencoder_model': 'train an autoencoder model for reconstruction using a Hydra DictConfig with Lightning trainer', 'test_autoencoder_with_best_ckpt': 'test the trained autoencoder model using the best checkpoint from training', 'instantiate_lightning_components': 'instantiate a LightningDataModule, LightningModule, Trainer, loggers, and callbacks from Hydra config', 'optimize_hyperparameters_with_hydra': 'run Hydra-based hyperparameter optimization for the autoencoder and retrieve the optimized metric value'}
```

## File: facebookresearch_all-atom-diffusion-transformer/src/train_diffusion.py

Prompts

```
['run the autoencoder evaluation script using Hydra config and a model checkpoint path', 'run the evaluate function to test an autoencoder checkpoint on a Lightning datamodule testset', 'run the main entry point that applies extras utilities and calls evaluate with Hydra config', 'review the evaluate function that instantiates a datamodule, autoencoder model, loggers, and trainer', 'review the task_wrapper decorator that controls failure behavior during multiruns and saves crash info', 'run the diffusion model evaluation on a checkpoint using Hydra config and Lightning trainer', 'run the main entry point that loads eval_diffusion.yaml config and starts evaluation', 'test a model checkpoint against the datamodule testset using the Lightning trainer', 'instantiate a diffusion model, datamodule, loggers, and trainer from a Hydra DictConfig', 'run the autoencoder training script with Hydra config overrides for model and data', 'train an autoencoder model for reconstruction using a Hydra DictConfig with Lightning trainer', 'test the trained autoencoder model using the best checkpoint from training', 'instantiate a LightningDataModule, LightningModule, Trainer, loggers, and callbacks from Hydra config', 'run Hydra-based hyperparameter optimization for the autoencoder and retrieve the optimized metric value', 'run the diffusion model training pipeline using Hydra config and PyTorch Lightning', 'train a diffusion model for generative modelling with configurable data module and callbacks', 'test the trained diffusion model using the best checkpoint from training', 'instantiate a Lightning Trainer with callbacks and loggers from Hydra config', 'run Hydra-based hyperparameter optimization and retrieve the optimized metric value']
```

Usage

```
{'run_diffusion_training': 'run the diffusion model training pipeline using Hydra config and PyTorch Lightning', 'train_diffusion_model': 'train a diffusion model for generative modelling with configurable data module and callbacks', 'test_diffusion_model': 'test the trained diffusion model using the best checkpoint from training', 'instantiate_lightning_trainer': 'instantiate a Lightning Trainer with callbacks and loggers from Hydra config', 'optimize_hyperparameters': 'run Hydra-based hyperparameter optimization and retrieve the optimized metric value'}
```

